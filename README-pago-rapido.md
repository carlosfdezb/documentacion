| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Pago Rápido

<!-- Índice -->
- [Documentación Api´s para Pago Rápido](#documentación-apis-para-pago-rápido)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Consultar Datos de Cliente](#1--consultar-datos-de-cliente)
    - [1.1.- Respuesta de Salida](#11--respuesta-de-salida)
        - [1.1.1- Respuesta de éxito](#111--respuesta-de-éxito)
  - [2.- Entidades de Pago](#2--entidades-de-pago)
    - [2.1.- Respuesta de Salida](#21--respuesta-de-salida)
        - [2.1.1- Respuesta de éxito](#211--respuesta-de-éxito)
  - [3.- Consultar Deuda Según Cliente](#3--consultar-deuda-según-cliente)
    - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
    - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
        - [3.2.1- Respuesta de éxito](#321--respuesta-de-éxito)
  - [4.- Insertar Correo](#4--insertar-correo)
    - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
  - [5.- Redireccionar a Banco Estado](#5--redireccionar-a-banco-estado)
    - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
  - [6.- Redireccionar a WebPay Plus](#6--redireccionar-a-webPay-plus)
    - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
  - [7.- Redireccionar a Servipag](#7--redireccionar-a-servipag)
    - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
  - [8.- Consultar Datos de Voucher](#8--consultar-datos-de-voucher)
    - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
    - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
        - [8.2.1- Respuesta de éxito](#821--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

En este documento solo se describen Api's propias del sistema, no externas a este.


## 1.- Consultar Datos de Cliente
Método que permite consultar datos del cliente para identificar tipo y correo electrónico.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultadatoscliente/{rut}`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| rut          | string       | NNNNNNNNC                      | Si                      | Rut del cliente a buscar    |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| tipo               | array[string]| Listado con tipos                                |
| correoelElectronico| Tipo de dato | Correo electrónico                               |

### 1.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.1.1.- Respuesta de éxito

    {
        "tipo":["EMPRESA","DOMICILIARIO"],
        "correoelElectronico":"*****ne@mundopacifico.cl"
    }

## 2.- Entidades de Pago
Método que permite llamar imagen para crear botonera de selección de las entidades de pago.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/entidadpago`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| MPPR_CANAL     | string       | Tipo de canal                                    |
| MPPR_VALOR     | string       | Imagen del canal                                 |
| MPPR_RUTA      | string       | Ruta del canal                                   |

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 2.2.2.- Respuesta de éxito

    {
        "success":
            {
                "codigoRespuesta":1,
                "descripcionRespuesta":[
                    {
                        "MPPR_CANAL":"BS",
                        "MPPR_VALOR":"https:\/\/ww3.servipag.com\/pagoenlinea\/wcm\/connect\/58ccbff6-fa42-490b-9b35-296d9b7917b4\/logo+header+170x80px.svg?MOD=AJPERES&CACHEID=58ccbff6-fa42-490b-9b35-296d9b7917b4",
                        "MPPR_RUTA":"\/servipagboton"
                    },
                    {
                        "MPPR_CANAL":"WP",
                        "MPPR_VALOR":"https:\/\/www.tumundo.cl\/multimedia\/2020\/11\/webpayplus.png",
                        "MPPR_RUTA":"\/webpaypluss"
                    },
                    {
                        "MPPR_CANAL":"BE",
                        "MPPR_VALOR":"https:\/\/www.tumundo.cl\/multimedia\/2020\/11\/Logo_BE.png",
                        "MPPR_RUTA":"\/botonestado"
                    }
                ]
            },
        "codigo":200
    }

## 3.- Consultar Deuda Según Cliente
Método que permite consultar la deuda según tipo de cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultadeudatipocliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| rut          | string       | NNNNNNNNC                      | Si                      | Rut del cliente a buscar    |
| canal        | string       |                                |                         | Tipo de canal               |
| unidadneg    | string       |                                |                         | Unidad                      |
| tpcliente    | int          |                                |                         | Tipo de cliente             |

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| IDTransaccion   | string       | ID de la transacción                             |
| IDCliente       | string       | ID del cliente                                   |
| NombreCliente   | string       | Nombre de la sucursal del cliente                |
| DeudaVencida    | string       | Deuda vencida                                    |
| FechaVencida    | date         | Fecha de deuda vencida                           |
| DocumentoVencido| string       | Documento de deuda vencida                       |
| DeudaPorVencer  | string       | Deuda por vencer                                 |
| FechaPorVencer  | date         | Fecha de deuda por vencer                        |
| DocumentoPorVencer|string      | Documento de deuda por vencer                    |
| DeudaTotal      | string       | Deuda total                                      |
| TimeStamp       | timestamp    | Fecha                                            |

### 3.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "data": {
            "rut": "967224006", 
            "canal": "wp", 
            "unidadneg": "MPH", 
            "tpcliente": 0
        }
    }

### 3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 3.2.2.- Respuesta de éxito

    {
        "EstadoResultado":{
            "Codigo":"0",
            "Descripcion":"Exito",
            "Observaciones":"Codigo devuelto en el caso de Exito"
        },
        "DatosResultado":{
            "IDTransaccion":"d24f0f11-dc9a-4589-9e95-066797ae87aa",
            "IDCliente":"967224006",
            "NombreCliente":"Sucursal Oficina Comercial Lampa",
            "DeudaVencida":"419872",
            "FechaVencida":"21\/08\/2021",
            "DocumentoVencido":"17945583",
            "DeudaPorVencer":"35567",
            "FechaPorVencer":"21\/09\/2021",
            "DocumentoPorVencer":"18666559",
            "DeudaTotal":"455439",
            "TimeStamp":"20210907125433501"
        }
    }

## 4.- Insertar Correo
Método que permite insertar correo indicado por el cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/insertacorreo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| idcliente    | string       |                                |                         | Id del cliente              |
| rut          | string       |                                |                         | Rut del cliente sin dígito verficador|
| rut_dv       | string       |                                |                         | Dígito verificador del rut  |
| correo       | string       |                                |                         | Correo electrónico          |

### 4.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idcliente": "967224006", 
        "rut": "96722400", 
        "rut_dv": "6", 
        "correo": "*****ne@mundopacifico.cl"
    }

## 5.- Redireccionar a Banco Estado
Método que permite redireccionar a pago con botón Banco Estado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/botonestado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| red          | string       |                                | Si                      | Red                         |
| hamb         | string       |                                | Si                      | Ambiente                    |

### 5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "red":"L3dlYnBheXB ... 9V1A=",
        "hamb": "Production"
	}

## 6.- Redireccionar a WebPay Plus
Método que permite redireccionar a pago con WebPay Plus.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/webpaypluss`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| red          | string       |                                | Si                      | Red                         |
| hamb         | string       |                                | Si                      | Ambiente                    |

### 6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "red":"L3dlYnBheXB ... 9V1A=",
        "hamb": "Production"
	}

## 7.- Redireccionar a Servipag
Método que permite redireccionar a pago con botón Servipag.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/servipagboton`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| red          | string       |                                | Si                      | Red                         |
| hamb         | string       |                                | Si                      | Ambiente                    |

### 7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "red":"L3dlYnBheXB ... 9V1A=",
        "hamb": "Production"
	}


## 8.- Consultar Datos de Voucher
Método que permite consultar datos de voucher pagado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultarvoucherbdfront`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| tokenlog     | string       |                                | Si                      | Token                       |

### 8.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "tokenlog": "0202109071534440967224006"
    }

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 8.2.1.- Respuesta de éxito

    {
        "data": 0
    }