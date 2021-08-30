| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Medios de Pago

<!-- Índice -->
- [Documentación Api´s para Medios de Pago](#documentación-apis-para-medios-de-pago)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Empresas](#1--empresas)
    - [1.1.- Existe Cliente](#11--existe-cliente)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Obtener Deuda](#12--obtener-deuda)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [2.- Pago](#2--pago)
    - [2.1.- Consolida Deuda](#21--consolida-deuda)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Procesar Pago](#22--procesar-pago)
        - [2.2.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#222--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#2221--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
  - [3.- Rendiciones](#3--rendiciones)
    - [3.1.- Rendiciones](#31--rendiciones)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
    - [3.2.- Rendiciones Filtro](#32--rendiciones-filtro)
        - [3.2.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
        - [3.2.2.- Respuesta de Salida](#322--respuesta-de-salida)
            - [3.2.2.1- Respuesta de error](#3221--respuesta-de-error)
            - [3.2.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
    - [3.3.- Rendiciones Filtro Exportar](#33--rendiciones-filtro-exportar)
        - [3.3.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
        - [3.3.2.- Respuesta de Salida](#332--respuesta-de-salida)
            - [3.3.2.1- Respuesta de error](#3321--respuesta-de-error)
            - [3.3.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
    - [3.4.- Rendiciones Resumen Filtro](#34--rendiciones-resumen-filtro)
        - [3.4.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
        - [3.4.2.- Respuesta de Salida](#342--respuesta-de-salida)
            - [3.4.2.1- Respuesta de error](#3421--respuesta-de-error)
            - [3.4.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
  - [4.- Medios de Pago](#4--medios-de-pago)
    - [4.1.- Canales de Pago](#41--canales-de-pago)
        - [4.1.1.- Ejemplo de llamada](#411--ejemplo-de-llamada)
        - [4.1.2.- Respuesta de Salida](#412--respuesta-de-salida)
            - [4.1.2.1- Respuesta de error](#4121--respuesta-de-error)
            - [4.1.2.2- Respuesta de éxito](#4122--respuesta-de-éxito)
    - [4.2.- Clientes Suscritos](#42--clientes-suscritos)
        - [4.2.1.- Ejemplo de llamada](#421--ejemplo-de-llamada)
        - [4.2.2.- Respuesta de Salida](#422--respuesta-de-salida)
            - [4.2.2.1- Respuesta de error](#4221--respuesta-de-error)
            - [4.2.2.2- Respuesta de éxito](#4222--respuesta-de-éxito)
    - [4.3.- Eliminar Registro](#43--eliminar-registro)
        - [4.3.1.- Ejemplo de llamada](#431--ejemplo-de-llamada)
        - [4.3.2.- Respuesta de Salida](#432--respuesta-de-salida)
            - [4.3.2.1- Respuesta de error](#4321--respuesta-de-error)
            - [4.3.2.2- Respuesta de éxito](#4322--respuesta-de-éxito)
    - [4.4.- Exportar Factura](#44--exportar-factura)
        - [4.4.1.- Ejemplo de llamada](#441--ejemplo-de-llamada)
        - [4.4.2.- Respuesta de Salida](#442--respuesta-de-salida)
            - [4.4.2.1- Respuesta de error](#4421--respuesta-de-error)
            - [4.4.2.2- Respuesta de éxito](#4422--respuesta-de-éxito)
    - [4.5.- Pago Factura](#45--pago-factura)
        - [4.5.1.- Ejemplo de llamada](#451--ejemplo-de-llamada)
        - [4.5.2.- Respuesta de Salida](#452--respuesta-de-salida)
            - [4.5.2.1- Respuesta de error](#4521--respuesta-de-error)
            - [4.5.2.2- Respuesta de éxito](#4522--respuesta-de-éxito)
    - [4.6.- Empresa Factura](#46--empresa-factura)
        - [4.6.1.- Ejemplo de llamada](#461--ejemplo-de-llamada)
        - [4.6.2.- Respuesta de Salida](#462--respuesta-de-salida)
            - [4.6.2.1- Respuesta de error](#4621--respuesta-de-error)
            - [4.6.2.2- Respuesta de éxito](#4622--respuesta-de-éxito)
    - [4.7.- Filtros Factura](#47--filtros-factura)
        - [4.7.1.- Ejemplo de llamada](#471--ejemplo-de-llamada)
        - [4.7.2.- Respuesta de Salida](#472--respuesta-de-salida)
            - [4.7.2.1- Respuesta de error](#4721--respuesta-de-error)
            - [4.7.2.2- Respuesta de éxito](#4722--respuesta-de-éxito)
    - [4.8.- Pagos 24 horas](#48--pagos-24-horas)
        - [4.8.1.- Ejemplo de llamada](#481--ejemplo-de-llamada)
        - [4.8.2.- Respuesta de Salida](#482--respuesta-de-salida)
            - [4.8.2.1- Respuesta de error](#4821--respuesta-de-error)
            - [4.8.2.2- Respuesta de éxito](#4822--respuesta-de-éxito)
    - [4.9.- Medios de Pago](#49--medios-de-pago)
        - [4.9.1.- Ejemplo de llamada](#491--ejemplo-de-llamada)
        - [4.9.2.- Respuesta de Salida](#492--respuesta-de-salida)
            - [4.9.2.1- Respuesta de error](#4921--respuesta-de-error)
            - [4.9.2.2- Respuesta de éxito](#4922--respuesta-de-éxito)
    - [4.10.- Facturas Empresa](#410--facturas-empresa)
        - [4.10.1.- Ejemplo de llamada](#4101--ejemplo-de-llamada)
        - [4.10.2.- Respuesta de Salida](#4102--respuesta-de-salida)
            - [4.10.2.1- Respuesta de error](#41021--respuesta-de-error)
            - [4.10.2.2- Respuesta de éxito](#41022--respuesta-de-éxito)
    - [4.11.- Suscripciones](#411--suscripciones)
        - [4.11.1.- Ejemplo de llamada](#4111--ejemplo-de-llamada)
        - [4.11.2.- Respuesta de Salida](#4112--respuesta-de-salida)
            - [4.11.2.1- Respuesta de error](#41121--respuesta-de-error)
            - [4.11.2.2- Respuesta de éxito](#41122--respuesta-de-éxito)
  - [5.- Informes](#5--informes)
    - [5.1.- Procesados](#51--procesados)
        - [5.1.1.- Ejemplo de llamada](#511--ejemplo-de-llamada)
        - [5.1.2.- Respuesta de Salida](#512--respuesta-de-salida)
            - [5.1.2.1- Respuesta de error](#5121--respuesta-de-error)
            - [5.1.2.2- Respuesta de éxito](#5122--respuesta-de-éxito)
    - [5.2.- Log Pagos](#52--log-pagos)
        - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
        - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
            - [5.2.2.1- Respuesta de error](#5221--respuesta-de-error)
            - [5.2.2.2- Respuesta de éxito](#5222--respuesta-de-éxito)
    - [5.3.- Pagos](#52--pagos)
        - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
        - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
            - [5.3.2.1- Respuesta de error](#5321--respuesta-de-error)
            - [5.3.2.2- Respuesta de éxito](#5322--respuesta-de-éxito)
    - [5.4.- Resumen No Confirmados Online](#54--resuimen-no-confirmados-online)
        - [5.4.1.- Ejemplo de llamada](#541--ejemplo-de-llamada)
        - [5.4.2.- Respuesta de Salida](#542--respuesta-de-salida)
            - [5.4.2.1- Respuesta de error](#5421--respuesta-de-error)
            - [5.4.2.2- Respuesta de éxito](#5422--respuesta-de-éxito)
    - [5.5.- Recaudación](#55--recaudación)
        - [5.5.1.- Ejemplo de llamada](#551--ejemplo-de-llamada)
        - [5.5.2.- Respuesta de Salida](#552--respuesta-de-salida)
            - [5.5.2.1- Respuesta de error](#5521--respuesta-de-error)
            - [5.5.2.2- Respuesta de éxito](#5522--respuesta-de-éxito)
    - [5.6.- Registros Inválidos](#56--registros-inválidos)
        - [5.6.1.- Ejemplo de llamada](#561--ejemplo-de-llamada)
        - [5.6.2.- Respuesta de Salida](#562--respuesta-de-salida)
            - [5.6.2.1- Respuesta de error](#5621--respuesta-de-error)
            - [5.6.2.2- Respuesta de éxito](#5622--respuesta-de-éxito)
    - [5.7.- Resumen Monto Mes Anterior Actual](#57--resumen-monto-mes-anterior-actual)
        - [5.7.1.- Ejemplo de llamada](#571--ejemplo-de-llamada)
        - [5.7.2.- Respuesta de Salida](#572--respuesta-de-salida)
            - [5.7.2.1- Respuesta de error](#5721--respuesta-de-error)
            - [5.7.2.2- Respuesta de éxito](#5722--respuesta-de-éxito)
    - [5.8.- Resumen Trx Mes Anterior Actual](#58--resumen-trx-mes-anterior-actual)
        - [5.8.1.- Ejemplo de llamada](#581--ejemplo-de-llamada)
        - [5.8.2.- Respuesta de Salida](#582--respuesta-de-salida)
            - [5.8.2.1- Respuesta de error](#5821--respuesta-de-error)
            - [5.8.2.2- Respuesta de éxito](#5822--respuesta-de-éxito)
    - [5.9.- Trx Anuladas](#59--trx-anuladas)
        - [5.9.1.- Ejemplo de llamada](#591--ejemplo-de-llamada)
        - [5.9.2.- Respuesta de Salida](#592--respuesta-de-salida)
            - [5.9.2.1- Respuesta de error](#5921--respuesta-de-error)
            - [5.9.2.2- Respuesta de éxito](#5922--respuesta-de-éxito)
    - [5.10.- Resumen Acumulado Día](#510--resumen-acumulado-día)
        - [5.10.1.- Ejemplo de llamada](#5101--ejemplo-de-llamada)
        - [5.10.2.- Respuesta de Salida](#5102--respuesta-de-salida)
            - [5.10.2.1- Respuesta de error](#51021--respuesta-de-error)
            - [5.10.2.2- Respuesta de éxito](#51022--respuesta-de-éxito)
    - [5.11.- Resumen Monto Mes Anterior Actual](#511--resumen-monto-mes-anterior-actual)
        - [5.11.1.- Ejemplo de llamada](#5111--ejemplo-de-llamada)
        - [5.11.2.- Respuesta de Salida](#5112--respuesta-de-salida)
            - [5.11.2.1- Respuesta de error](#51121--respuesta-de-error)
            - [5.11.2.2- Respuesta de éxito](#51122--respuesta-de-éxito)
    - [5.12.- Resumen Pagos](#512--resumen-pagos)
        - [5.12.1.- Ejemplo de llamada](#5121--ejemplo-de-llamada)
        - [5.12.2.- Respuesta de Salida](#5122--respuesta-de-salida)
            - [5.12.2.1- Respuesta de error](#51221--respuesta-de-error)
            - [5.12.2.2- Respuesta de éxito](#51222--respuesta-de-éxito)
    - [5.13.- Resumen Pagos por Canal](#513--resumen-pagos-por-canal)
        - [5.13.1.- Ejemplo de llamada](#5131--ejemplo-de-llamada)
        - [5.13.2.- Respuesta de Salida](#5132--respuesta-de-salida)
            - [5.13.2.1- Respuesta de error](#51321--respuesta-de-error)
            - [5.13.2.2- Respuesta de éxito](#51322--respuesta-de-éxito)
    - [5.14.- Resumen Recaudación](#514--resumen-recaudación)
        - [5.14.1.- Ejemplo de llamada](#5141--ejemplo-de-llamada)
        - [5.14.2.- Respuesta de Salida](#5142--respuesta-de-salida)
            - [5.14.2.1- Respuesta de error](#51421--respuesta-de-error)
            - [5.14.2.2- Respuesta de éxito](#51422--respuesta-de-éxito)
    - [5.15.- Resumen Recaudación Canal](#515--resumen-recaudación-canal)
        - [5.15.1.- Ejemplo de llamada](#5151--ejemplo-de-llamada)
        - [5.15.2.- Respuesta de Salida](#5152--respuesta-de-salida)
            - [5.15.2.1- Respuesta de error](#51521--respuesta-de-error)
            - [5.15.2.2- Respuesta de éxito](#51522--respuesta-de-éxito)
    - [5.16.- Resumen Trx Mes Anterior Actual](#516--resumen-trx-mes-anterior-actual)
        - [5.16.1.- Ejemplo de llamada](#5161--ejemplo-de-llamada)
        - [5.16.2.- Respuesta de Salida](#5162--respuesta-de-salida)
            - [5.16.2.1- Respuesta de error](#51621--respuesta-de-error)
            - [5.16.2.2- Respuesta de éxito](#51622--respuesta-de-éxito)
  - [6.- Servicio de Pago](#6--servicio-de-pago)
    - [6.1.- Base64 a Guid](#61--base64-a-guid)
        - [6.1.1.- Ejemplo de llamada](#611--ejemplo-de-llamada)
        - [6.1.2.- Respuesta de Salida](#612--respuesta-de-salida)
            - [6.1.2.1- Respuesta de error](#6121--respuesta-de-error)
            - [6.1.2.2- Respuesta de éxito](#6122--respuesta-de-éxito)
    - [6.2.- Guid a Base64](#62--guid-a-base64)
        - [6.2.1.- Ejemplo de llamada](#621--ejemplo-de-llamada)
        - [6.2.2.- Respuesta de Salida](#622--respuesta-de-salida)
            - [6.2.2.1- Respuesta de error](#6221--respuesta-de-error)
            - [6.2.2.2- Respuesta de éxito](#6222--respuesta-de-éxito)
    - [6.3.- Pagos en Proceso](#63--pagos-en-proceso)
        - [6.3.1.- Ejemplo de llamada](#631--ejemplo-de-llamada)
        - [6.3.2.- Respuesta de Salida](#632--respuesta-de-salida)
            - [6.3.2.1- Respuesta de error](#6321--respuesta-de-error)
            - [6.3.2.2- Respuesta de éxito](#6322--respuesta-de-éxito)
    - [6.4.- Pagos en Proceso Cliente](#64--pagos-en-proceso-cliente)
        - [6.4.1.- Ejemplo de llamada](#641--ejemplo-de-llamada)
        - [6.4.2.- Respuesta de Salida](#642--respuesta-de-salida)
            - [6.4.2.1- Respuesta de error](#6421--respuesta-de-error)
            - [6.4.2.2- Respuesta de éxito](#6422--respuesta-de-éxito)
    - [6.5.- Resumen Pagos en Proceso](#65--resumen-pagos-en-proceso)
        - [6.5.1.- Ejemplo de llamada](#651--ejemplo-de-llamada)
        - [6.5.2.- Respuesta de Salida](#652--respuesta-de-salida)
            - [6.5.2.1- Respuesta de error](#6521--respuesta-de-error)
            - [6.5.2.2- Respuesta de éxito](#6522--respuesta-de-éxito)
    - [6.6.- Consulta Pagos](#66--consulta-pagos)
        - [6.6.1.- Ejemplo de llamada](#661--ejemplo-de-llamada)
        - [6.6.2.- Respuesta de Salida](#662--respuesta-de-salida)
            - [6.6.2.1- Respuesta de error](#6621--respuesta-de-error)
            - [6.6.2.2- Respuesta de éxito](#6622--respuesta-de-éxito)
    - [6.7.- Actualizar Proceso](#67--actualizar-proceso)
        - [6.7.1.- Ejemplo de llamada](#671--ejemplo-de-llamada)
        - [6.7.2.- Respuesta de Salida](#672--respuesta-de-salida)
            - [6.7.2.1- Respuesta de error](#6721--respuesta-de-error)
            - [6.7.2.2- Respuesta de éxito](#6722--respuesta-de-éxito)




# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Empresas
## 1.1.- Existe Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/existecliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "NOMBRE_CAMPO":"166101069"
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "El rut  es invalido o no tiene formato correcto. El formato es NNNNNNNNC"
                },
                "codigo": 422
        }
  
#### 1.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 1.2.- Obtener Deuda
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/obtenerdeuda`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar deudas|

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":"166101069"
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos de Deuda"
                },
                "codigo": 204
        }
#### 1.2.2.2.- Respuesta de éxito

	{
        ...
	}



# 2.- Pago
## 2.1.- Consolida Deuda
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/consolidadeuda`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.2.- Procesar Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/procesapago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.2.2.2.- Respuesta de éxito

	{
        ...
	}


# 3.- Rendiciones
## 3.1.- Rendiciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendiciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | ?   |

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| fechaPago       | string       | Breve descripción                                |
| horaPago        | string       | Breve descripción                                |
| montoPagado     | string       | Breve descripción                                |
| medioPago       | string       | Breve descripción                                |
| archivorendicion| string       | Breve descripción                                |
| estadoPago      | string       | Breve descripción                                |

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 3.1.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "fechaPago": "09/08/2021",
                                        "horaPago": "17:03:21",
                                        "montoPagado": "27570",
                                        "medioPago": "UNIRED WEB",
                                        "archivorendicion": "20210811000099800000000021882605UNRED.TXT",
                                        "estadoPago": "CARGO APLICADO"
                                },
                                {
                                        "fechaPago": "18/07/2021",
                                        "horaPago": "16:04:59",
                                        "montoPagado": "12970",
                                        "medioPago": "UNIRED WEB",
                                        "archivorendicion": "20210720000001900000000000138224UNPMP.TXT",
                                        "estadoPago": "CARGO APLICADO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 3.2.- Rendiciones Filtro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| per_page     | int          |                                |                                 | ?    |
| rut          | string       | NNNNNNNNC                      | Si                              | ?   |


**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTrx          | string       | ?                               | 
| identificador  | string       | ?                               | 
| montoPagado    | string       | ?                               | 
| fechaPago      | string       | ?                               | 
| fechaContable  | string       | ?                               | 
| archivo        | string       | ?                               | 
| formaPago      | string       | ?                               | 
| estado         | string       | ?                               |

### 3.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "per_page": 1,
                "rut": "166101069"
	}

### 3.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados "
                },
                "codigo": 204
        }
  
#### 3.2.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTrx": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                        "identificador": "166101069",
                                        "montoPagado": "27570",
                                        "fechaPago": "09/08/2021 17:03:21",
                                        "fechaContable": "09/08/2021",
                                        "archivo": "20210811000099800000000021882605UNRED.TXT",
                                        "formaPago": "UNIRED WEB",
                                        "estado": "CARGO APLICADO"
                                },
                                {
                                        "idTrx": "3a261851-7eec-4664-bbb9-c934c45556b0",
                                        "identificador": "166101069",
                                        "montoPagado": "12970",
                                        "fechaPago": "18/07/2021 16:04:59",
                                        "fechaContable": "18/07/2021",
                                        "archivo": "20210720000001900000000000138224UNPMP.TXT",
                                        "formaPago": "UNIRED WEB",
                                        "estado": "CARGO APLICADO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 3.3.- Rendiciones Filtro Exportar
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilterExportar`

**Parámetros de entrada:**
| Campo         |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:-------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| medioPago     | int          |                                |                                 | ?    |
| fechaPagoDesde| date         | yyyy/mm/dd                     |                                 | ?   |
| fechaPagoHasta| date         | yyyy/mm/dd                     |                                 | ?   |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| FECHA          | string       | Breve descripción                                |
| DESC_CANAL     | string       | Breve descripción                                |
| CTD            | string       | Breve descripción                                |
| MONTO          | string       | Breve descripción                                |
| MONTO_TOTAL    | string       | Breve descripción                                |
| CTD_TOTAL      | string       | Breve descripción                                |

### 3.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "medioPago":,
                "fechaPagoDesde": 2021/08/10",
                "fechaPagoHasta": 2021/08/21"

	}

### 3.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.3.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados"
                },
                "codigo": 204
        }
  
#### 3.3.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "FECHA": "10/08/2021",
                                        "DESC_CANAL": "CAJA VECINA",
                                        "CTD": "7162",
                                        "MONTO": "149437871",
                                        "MONTO_TOTAL": "149437871",
                                        "CTD_TOTAL": "7162"
                                },
                                {
                                        "FECHA": "11/08/2021",
                                        "DESC_CANAL": "CAJA VECINA",
                                        "CTD": "5234",
                                        "MONTO": "112234985",
                                        "MONTO_TOTAL": "112234985",
                                        "CTD_TOTAL": "5234"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 3.4.- Rendiciones Resumen Filtro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesresumenFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| per_page     | int          |                                |                                 | ?    |
| rut          | string       | NNNNNNNNC                      | Si                              | ?   |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| MPRE_ID_REGISTRO   | string       | Breve descripción                                |
| MPRE_FECHA_PAGO    | timestamp    | Breve descripción                                |
| MPRE_MONTO_PAGADO  | string       | Breve descripción                                |
| ARCHIVO            | string       | Breve descripción                                |
| MPRE_ID_TRANSACCION| string       | Breve descripción                                |
| MPRE_ID_CLIENTE    | string       | Breve descripción                                |
| MPRE_FECHA_CONTABLE| timestamp    | Breve descripción                                |
| FORMA_PAGO         | string       | Breve descripción                                |
| ESTADO             | string       | Breve descripción                                |

### 3.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "per_page": 1,
                "rut": "166101069"
	}

### 3.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 3.4.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                                "MPRE_ID_REGISTRO": 15693308,
                                "MPRE_FECHA_PAGO": "2021-08-09 17:03:21.000",
                                "MPRE_MONTO_PAGADO": "27570",
                                "ARCHIVO": "20210811000099800000000021882605UNRED.TXT",
                                "MPRE_ID_TRANSACCION": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                "MPRE_ID_CLIENTE": "166101069",
                                "MPRE_FECHA_CONTABLE": "2021-08-09 00:00:00.000",
                                "FORMA_PAGO": "UNIRED WEB",
                                "ESTADO": "CARGO APLICADO"
                        }
                        ...
                ],
                "first_page_url": "...URL/rendicionesFilter?per_page=1&rut=166101069&page=1",
                "from": 1,
                "last_page": 58,
                "last_page_url": "...URL/rendicionesFilter?per_page=1&rut=166101069&page=58",
                "next_page_url": "...URL/rendicionesFilter?per_page=1&rut=166101069&page=2",
                "path": "...URL/rendicionesFilter",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 58
        }

# 4.- Medios de Pago
## 4.1.- Canales de Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/canalespago`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| IdUnidad       | string       | Breve descripción                                |
| CodigoUnidad   | string       | Breve descripción                                |
| UnidadNegocio  | string       | Breve descripción                                |
| Canal          | string       | Breve descripción                                |
| NombreCanal    | string       | Breve descripción                                |

### 4.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 4.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.1.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "IdUnidad": "1",
                                        "CodigoUnidad": "MPH",
                                        "UnidadNegocio": "SERVICIO HOGAR",
                                        "Canal": "CV",
                                        "NombreCanal": "CAJA VECINA"
                                },
                                {
                                        "IdUnidad": "1",
                                        "CodigoUnidad": "MPH",
                                        "UnidadNegocio": "SERVICIO HOGAR",
                                        "Canal": "INT",
                                        "NombreCanal": "BANCO ESTADO.CL"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 4.2.- Clientes Suscritos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/clientessuscritos`

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| identificador   | string       | Breve descripción                                |
| fechaSuscripcion| string       | Breve descripción                                |
| medioSuscripcion| string       | Breve descripción                                |
| rutCliente      | string       | Breve descripción                                |

### 4.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 4.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.2.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "identificador": "0000005444",
                                        "fechaSuscripcion": "23-04-2021",
                                        "medioSuscripcion": "UNIVERSO PAC BANCO ESTADO",
                                        "rutCliente": "5444"
                                },
                                {
                                        "identificador": "0000053392",
                                        "fechaSuscripcion": "23-04-2021",
                                        "medioSuscripcion": "UNIVERSO PAC BANCO ESTADO",
                                        "rutCliente": "53392"
                                },
                                ...
                                ]
                        }
                },
                 "codigo": 200
	}

## 4.3.- Eliminar Registro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getEliminaregistro`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| idregistro   | int          |                                | si                       | ID del registro             |

### 4.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idregistro": 47885
	}

### 4.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.3.2.2.- Respuesta de éxito

	{
                "data": 
                [
                        {
                                "data": "200"
                        }
                ]
        }

## 4.4.- Exportar Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaExportar`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| MPDC_ID_DETALLE_CARGA | int          | Breve descripción                                |
| MPDC_ID_CARGA         | string       | Breve descripción                                |
| MPDC_IDENTIFICADOR    | string       | Breve descripción                                |
| MPDC_RUT_CLIENTE      | string       | Breve descripción                                |
| MPDC_RUT_DV           | string       | Breve descripción                                |
| MPDC_RAZON_SOCIAL     | string       | Breve descripción                                |
| MPDC_NUMERO_FACTURA   | string       | Breve descripción                                |
| MPDC_MONTO            | string       | Breve descripción                                |
| MPDC_FECHA_VENCIMIENTO| string       | Breve descripción                                |
| MPDC_ID_ESTADO        | string       | Breve descripción                                |
| MPPE_CANAL            | string       | Breve descripción                                |
| MPPD_FECHA_PAGO       | string       | Breve descripción                                |
| FORMA_PAGO            | string       | Breve descripción                                |
| Estado                | string       | Breve descripción                                |

### 4.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 4.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.4.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "MPDC_ID_DETALLE_CARGA": 45,
                                "MPDC_ID_CARGA": "22",
                                "MPDC_IDENTIFICADOR": "130914551",
                                "MPDC_RUT_CLIENTE": "13091455",
                                "MPDC_RUT_DV": "1",
                                "MPDC_RAZON_SOCIAL": "jose prueba",
                                "MPDC_NUMERO_FACTURA": "256",
                                "MPDC_MONTO": "10",
                                "MPDC_FECHA_VENCIMIENTO": "2021-01-19 00:00:00.000",
                                "MPDC_ID_ESTADO": "26",
                                "MPPE_CANAL": "BE",
                                "MPPD_FECHA_PAGO": "2021-01-19 06:56:32.000",
                                "FORMA_PAGO": "BOTON BANCO ESTADO",
                                "Estado": "REVERSADO POR SOLICITUD OTRO BANCO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 4.5.- Pago Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaPago`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| MPDC_ID_DETALLE_CARGA | int          | Breve descripción                                | 
| MPDC_ID_CARGA         | string       | Breve descripción                                | 
| MPDC_IDENTIFICADOR    | string       | Breve descripción                                | 
| MPDC_RUT_CLIENTE      | string       | Breve descripción                                | 
| MPDC_RUT_DV           | string       | Breve descripción                                | 
| MPDC_RAZON_SOCIAL     | string       | Breve descripción                                | 
| MPDC_NUMERO_FACTURA   | string       | Breve descripción                                | 
| MPDC_MONTO            | string       | Breve descripción                                | 
| MPDC_FECHA_VENCIMIENTO| timestamp    | Breve descripción                                | 
| MPDC_ID_ESTADO        | string       | Breve descripción                                | 
| MPPE_CANAL            | string       | Breve descripción                                | 
| MPPD_FECHA_PAGO       | timestamp    | Breve descripción                                | 
| FORMA_PAGO            | string       | Breve descripción                                | 
| Estado                | string       | Breve descripción                                |

### 4.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 4.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.5.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                        "MPDC_ID_DETALLE_CARGA": 45,
                        "MPDC_ID_CARGA": "22",
                        "MPDC_IDENTIFICADOR": "130914551",
                        "MPDC_RUT_CLIENTE": "13091455",
                        "MPDC_RUT_DV": "1",
                        "MPDC_RAZON_SOCIAL": "jose prueba",
                        "MPDC_NUMERO_FACTURA": "256",
                        "MPDC_MONTO": "10",
                        "MPDC_FECHA_VENCIMIENTO": "2021-01-19 00:00:00.000",
                        "MPDC_ID_ESTADO": "26",
                        "MPPE_CANAL": "BE",
                        "MPPD_FECHA_PAGO": "2021-01-19 06:56:32.000",
                        "FORMA_PAGO": "BOTON BANCO ESTADO",
                        "Estado": "REVERSADO POR SOLICITUD OTRO BANCO"
                        },
                        ...
                ],
                "first_page_url": "...URL/getFacturaPago?page=1",
                "from": 1,
                "last_page": 1,
                "last_page_url": "...URL/getFacturaPago?page=1",
                "next_page_url": null,
                "path": "...URL/getFacturaPago",
                "per_page": 15,
                "prev_page_url": null,
                "to": 6,
                "total": 6
	}

## 4.6.- Empresa Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturasEmpresa`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| idarchivo    | int          |                                |                                 | Breve descripción           |
| rutfact      | string       | NNNNNNNNC                      |                                 | Breve descripción           |
| numfact      | int          |                                |                                 | Breve descripción           |
| estadofact   | int          |                                |                                 | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idarchivo": 1,
                "rutfact":"156780901",
                "numfact":"",
                "estadofact":""
	}

### 4.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.7.- Filtros Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturasFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.7.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.8.- Pagos 24 horas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/pagos24horas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 4.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.8.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 4.8.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.9.- Medios de Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/mediosPago`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | ID del medio de pago                             |
| label          | string       | Nombre del medio de pago                         |

### 4.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 4.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.9.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 4.9.2.2.- Respuesta de éxito

	[
                {
                        "id": "1",
                        "label": "CAJA VECINA"
                },
                {
                        "id": "2",
                        "label": "BANCO ESTADO.CL"
                },
                {
                        "id": "3",
                        "label": "SERVI ESTADO"
                },
                ...
	}


## 4.10.- Facturas Empresa
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/postFacturasEmpresa`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:---------------:|:------------:|:------------------------------:|:------------- --------------:|----------------------------:|
| tiporegistro    | int          |                                |                              | Breve descripción           |
| ctdfilas        | int          |                                |                              | Breve descripción           |
| nombrearchivo   | string       |                                |                              | Breve descripción           |
| idarchivo       | int          |                                |                              | Breve descripción           |
| usuarioregistro | int          |                                |                              | Breve descripción           |
| rut             | string       | NNNNNNNNC                      |                              | Breve descripción           |
| razonsocial     | int          |                                |                              | Breve descripción           |
| numerofactura   | int          |                                |                              | Breve descripción           |
| monto           | int          |                                |                              | Breve descripción           |
| fechavencimiento| date         |                                |                              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "tiporegistro":"",
                "ctdfilas":"",
                "nombrearchivo":"",
                "idarchivo":"",
                "usuarioregistro":"",
                "rut":"",
                "razonsocial":"",
                "numerofactura":"",
                "monto":"",
                "fechavencimiento":""
	}

### 4.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.10.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.11.- Suscripciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/suscripciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":"166101069"
	}

### 4.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.11.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 4.11.2.2.- Respuesta de éxito

	{
        ...
	}


# 5.- Informes
## 5.1.- Procesados
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/archivos/procesados`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| fechaProceso     | date         | dd/mm/yyyy                     |                          | Breve descripción           |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
|  idArchivo        | string       | Breve descripción                                |
|  rutaArchivo      | string       | Breve descripción                                |
|  archivo          | string       | Breve descripción                                |
|  cantidadRegistros| string       | Breve descripción                                |
|  montoTotal       | string       | Breve descripción                                |
|  fechaPago        | date         | Breve descripción                                |
|  fechaProceso     | timestamp    | Breve descripción                                |
|  clasificacion    | string       | Breve descripción                                |
|  estado           | string       | Breve descripción                                |

### 5.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "fechaProceso": "01/01/2020",
                "per_page": 2
	}

### 5.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.1.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                        "idArchivo": "12416",
                        "rutaArchivo": "F:\\RepoSistemas\\Pagos\\Unired\\Ftp\\",
                        "archivo": "20200101000056400000000013999929UNRED.TXT",
                        "cantidadRegistros": "564",
                        "montoTotal": "13999929",
                        "fechaPago": "01/01/2020",
                        "fechaProceso": "01/01/2020 08:00:44",
                        "clasificacion": "UNIRED",
                        "estado": "CARGO APLICADO"
                        }
                        ...
                ],
                "first_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=1",
                "from": 1,
                "last_page": 7,
                "last_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=7",
                "next_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=2",
                "path": "...URL/informes/archivos/procesados",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 7
        }


## 5.2.- Log Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/logpagos`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| Rut              | string       | NNNNNNNNC                      |                          | Breve descripción           |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**
| Campo               |  Tipo        |                         Descripción              |
|:--------------------|:------------:|-------------------------------------------------:| 
| identificador       | string       | Breve descripción                                |
| idTransaccion       | string       | Breve descripción                                |
| fechaRegistro       | timestamp    | Breve descripción                                |
| deudaVencida        | ?       | Breve descripción                                |
| deudaPorVencer      | ?       | Breve descripción                                |
| deudaTotal          | ?       | Breve descripción                                |
| montoPagado         | string       | Breve descripción                                |
| codigoRespuesta     | ?       | Breve descripción                                |
| descripcionRespuesta| string       | Breve descripción                                |
| formaPago           | string       | Breve descripción                                |
| estadoPago          | string       | Breve descripción                                |

### 5.2.1.- Ejemplo de llamada

Ejemplo: JSON  

	{
                "Rut": "166101069",
                "per_page": 2
	}

### 5.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.2.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                                "identificador": "166101069",
                                "idTransaccion": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                "fechaRegistro": "2021-08-11 08:12:18.943",
                                "deudaVencida": null,
                                "deudaPorVencer": null,
                                "deudaTotal": null,
                                "montoPagado": "27570",
                                "codigoRespuesta": null,
                                "descripcionRespuesta": "TRANSACCION CONFIRMADA, CARGADA EN CRM Y RENDIDA POR ENTIDAD",
                                "formaPago": "UNIRED WEB",
                                "estadoPago": "RENDIDO"
                        },
                        ...
                ],
                "first_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=1",
                "from": 1,
                "last_page": 681,
                "last_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=681",
                "next_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=2",
                "path": "...URL/informes/logpagos",
                "per_page": "2",
                "prev_page_url": null,
                "to": 2,
                "total": 1362
        }

## 5.3.- Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagos`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| Rut              | string       | NNNNNNNNC                      |                          | Breve descripción           |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| identificador  | string       | Breve descripción                                |
| idTransaccion  | string       | Breve descripción                                |
| fechaPago      | string       | Breve descripción                                |
| montoPagado    | string       | Breve descripción                                |
| confimadoOnLine| string       | Breve descripción                                |
| medioPago      | string       | Breve descripción                                |
| estadoPago     | string       | Breve descripción                                |

### 5.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069",
                "per_page": 2
	}

### 5.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.3.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                                "identificador": "166101069",
                                "idTransaccion": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                "fechaPago": "2021-08-09 17:05:00.000",
                                "montoPagado": "27570",
                                "confimadoOnLine": "1",
                                "medioPago": "UNIRED WEB",
                                "estadoPago": "RENDIDO"
                        }
                        ...
                ],
                "first_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=1",
                "from": 1,
                "last_page": 46,
                "last_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=46",
                "next_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=2",
                "path": "...URL/informes/pagos",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 46
        }

## 5.4.- Resumen No Confirmados Online
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagos/resumennoconfirmadosonline`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.4.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.5.- Recaudación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/recaudacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| Anio         | int          |                                |                         | Breve descripción           |
| MesIni       | int          |                                |                         | Breve descripción           |
| MesFin       | int          |                                |                         | Breve descripción           |
| TipoReporte  | int          |                                |                         | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Dia            | int          | Breve descripción                                |
| Semana         | int          | Breve descripción                                |
| Nombre_Dia     | string       | Breve descripción                                |
| Nombre_Mes     | string       | Breve descripción                                |
| Medio_Pago     | string       | Breve descripción                                |
| Importe        | int          | Breve descripción                                |

### 5.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Anio": 2021,
                "MesIni": 7,
                "MesFin": 8,
                "TipoReporte": 1
	}

### 5.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.5.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "Dia": 1,
                                "Semana": 0,
                                "Nombre_Dia": "DOMINGO",
                                "Nombre_Mes": "AGOSTO",
                                "Medio_Pago": "BANCO ESTADO.CL",
                                "Importe": 23338904
                                },
                                ...
                                ]
                        }
                },
                 "codigo": 200
	}

## 5.6.- Registros Inválidos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/registrosinvalidos`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| Rut              | string       | NNNNNNNNC                      |                          | Breve descripción           |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069",
                "per_page": 2
	}

### 5.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.6.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [

                ],
                "first_page_url": "...URL/informes/rendicion/registrosinvalidos?Rut=166101069&per_page=1&page=1",
                "from": null,
                "last_page": 1,
                "last_page_url": "...URL/informes/rendicion/registrosinvalidos?Rut=166101069&per_page=1&page=1",
                "next_page_url": null,
                "path": "...URL/informes/rendicion/registrosinvalidos",
                "per_page": "1",
                "prev_page_url": null,
                "to": null,
                "total": 0
        }


## 5.7.- Resumen Monto Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumenmontomesanterioactual`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Breve descripción                                |
| montos         | string       | Breve descripción                                |

### 5.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.7.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.7.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "mes": "Agosto",
                                        "montos": "426234159,721663853,670666896,673432654,766210089,390710397,269471307,159858592,344040656,520641269,288621508,219664159,238685249,180035402,191807131,415781275,447032803,321628938,269712180,631628757,184451832,136271797,213661083,243546284,230750104,237547789,228478772,78252167,66548385,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.8.- Resumen Trx Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumentrxmesanterioactual`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Breve descripción                                |
| montos         | string       | Breve descripción                                |

### 5.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.8.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.8.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "mes": "Agosto",
                                        "montos": "19104,32419,29976,30646,37376,18412,12505,7417,15889,25843,13968,10585,11357,8601,9152,19953,21681,15239,12400,31421,9234,6678,10496,12143,11203,11664,10243,3796,3205,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 5.9.- Trx Anuladas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/trxanuladas`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.9.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.9.2.2.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [

                ],
                "first_page_url": "...URL/informes/rendicion/trxanuladas?page=1",
                "from": null,
                "last_page": 1,
                "last_page_url": "...URL/informes/rendicion/trxanuladas?page=1",
                "next_page_url": null,
                "path": "...URL/informes/rendicion/trxanuladas",
                "per_page": 15,
                "prev_page_url": null,
                "to": null,
                "total": 0
        }


## 5.10.- Resumen Acumulado Día
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenacumuladodia`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Breve descripción                                |
| montos         | string       | Breve descripción                                |

### 5.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.10.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "unidad": "SERVICIO HOGAR",
                                "montos": "5757944,8189759,9267296,9771447,10295938,10878465,11889833,14641158,24459839,45462813,73303103,108409627,185714365,264744314,323044691,379214325,432405624,438577632,0,0,0,0,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }


## 5.11.- Resumen Monto Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenmontomesanterioactual`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Breve descripción                                |
| montos         | string       | Breve descripción                                |

### 5.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.11.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.11.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "mes": "Agosto",
                                "montos": "19104,32419,29976,30646,37376,18412,12505,7417,15889,25843,13968,10585,11357,8601,9152,19953,21681,15239,12400,31421,9234,6678,10496,12143,11203,11664,10243,3796,3205,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }

## 5.12.- Resumen Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagos`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Breve descripción                                |
| horario        | string       | Breve descripción                                |
| dia            | string       | Breve descripción                                |
| exito          | string       | Breve descripción                                |
| cargadocrm     | string       | Breve descripción                                |
| rendido        | string       | Breve descripción                                |
| error          | string       | Breve descripción                                |
| reversado      | string       | Breve descripción                                |

### 5.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.12.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.12.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "id": "0",
                                "horario": "00:00 00:59",
                                "dia": "30",
                                "exito": "1",
                                "cargadocrm": "269",
                                "rendido": "1",
                                "error": "1",
                                "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.13.- Resumen Pagos por Canal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosporcanal`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Breve descripción                                |
| horario        | string       | Breve descripción                                |
| canal          | string       | Breve descripción                                |
| dia            | string       | Breve descripción                                |
| exito          | string       | Breve descripción                                |
| cargadocrm     | string       | Breve descripción                                |
| rendido        | string       | Breve descripción                                |
| error          | string       | Breve descripción                                |
| reversado      | string       | Breve descripción                                |

### 5.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.13.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.13.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "id": "0",
                                        "horario": "00:00 00:59",
                                        "canal": "BANCO ESTADO.CL",
                                        "dia": "30",
                                        "exito": "0",
                                        "cargadocrm": "6",
                                        "rendido": "0",
                                        "error": "0",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.14.- Resumen Recaudación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacion`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Breve descripción                                |
| horario        | string       | Breve descripción                                |
| dia            | string       | Breve descripción                                |
| exito          | string       | Breve descripción                                |
| cargadocrm     | string       | Breve descripción                                |
| rendido        | string       | Breve descripción                                |
| error          | string       | Breve descripción                                |
| reversado      | string       | Breve descripción                                |

### 5.14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.14.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.14.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "id": "0",
                                        "horario": "00:00 00:59",
                                        "dia": "30",
                                        "exito": "0",
                                        "cargadocrm": "0",
                                        "rendido": "0",
                                        "error": "14982",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.15.- Resumen Recaudación Canal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacioncanal`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| canal          | string       | Breve descripción                                |
| exito          | string       | Breve descripción                                |
| cargadocrm     | string       | Breve descripción                                |
| rendido        | string       | Breve descripción                                |
| error          | string       | Breve descripción                                |
| reversado      | string       | Breve descripción                                |

### 5.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.15.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.15.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "canal": "BANCO ESTADO.CL",
                                        "exito": "68473",
                                        "cargadocrm": "7944566",
                                        "rendido": "0",
                                        "error": "191127",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.16.- Resumen Trx Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumentrxmesanterioactual`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| unidad         | string       | Breve descripción                                |
| mes            | string       | Breve descripción                                |
| montos         | string       | Breve descripción                                |

### 5.16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 5.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.16.2.1.- Respuesta de error

	{
                ...
	} 
  
#### 5.16.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "unidad": "SERVICIO HOGAR",
                                        "mes": "Agosto HOGAR",
                                        "montos": "18850,32170,29742,30363,37111,18218,12389,7325,15697,25591,13758,10437,11142,8489,9044,19696,21393,15047,14444,31206,9156,6588,10379,12027,11052,11529,15460,11918,9547,21828,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }


# 6.- Servicio de Pago
## 6.1.- Base64 a Guid
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/base64toguid`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| idTrx        | string       | base64                         | Si                      | Breve descripción           |

### 6.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idTrx":"58444dc"
	}

### 6.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.1.2.1.- Respuesta de error

`----`
  
#### 6.1.2.2.- Respuesta de éxito

`e7ce38e1-d7---`


## 6.2.- Guid a Base64
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/guidtobase64`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| idTrx        | string       | Guid                           | Si                      | Breve descripción           |

### 6.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idTrx":"e7ce38e1-d7---"
	}

### 6.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.2.2.2.- Respuesta de éxito

`58444dc=`

## 6.3.- Pagos en Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenproceso`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTransaccion  | string       | Breve descripción                                |
| identificador  | string       | Breve descripción                                |
| canal          | string       | Breve descripción                                |
| monto          | int          | Breve descripción                                |
| unidadNegocio  | string       | Breve descripción                                |
| fechaPago      | timestamp    | Breve descripción                                |
| tipoCliente    | int          | Breve descripción                                |
| fechaRegistro  | timestamp    | Breve descripción                                |

### 6.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 6.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.3.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTransaccion": "444ca478-6191-406b-8ec9-0c9106e709d9",
                                        "identificador": "140219932",
                                        "canal": "SN",
                                        "monto": 5489,
                                        "unidadNegocio": "MPM",
                                        "fechaPago": "2021-08-24T14:31:59",
                                        "tipoCliente": 99,
                                        "fechaRegistro": "2021-08-24 14:26:27"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 6.4.- Pagos en Proceso Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenprocesocliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTransaccion  | string       | Breve descripción                                |
| identificador  | string       | Breve descripción                                |
| canal          | string       | Breve descripción                                |
| monto          | int          | Breve descripción                                |
| unidadNegocio  | string       | Breve descripción                                |
| fechaPago      | string       | Breve descripción                                |
| tipoCliente    | int          | Breve descripción                                |
| fechaRegistro  | string       | Breve descripción                                |

### 6.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":  "166101069"
	}

### 6.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.4.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos pagos en proceso para el rut:191403991 "
                },
                "codigo": 204
        }
  
#### 6.4.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTransaccion": "c273b344-72df-48fc-bb4a-503db3b9ff3e",
                                        "identificador": "166101069",
                                        "canal": "WP",
                                        "monto": 14600,
                                        "unidadNegocio": "MPH",
                                        "fechaPago": "20210120001622958",
                                        "tipoCliente": 0,
                                        "fechaRegistro": "2021-04-07 09:26:00"
                                }
                                ]
                        }
                },
                "codigo": 200
        }

## 6.5.- Resumen Pagos en Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosenproceso`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| procesado      | int          | Breve descripción                                |
| cantidad       | int          | Breve descripción                                |

### 6.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                ...
	}

### 6.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.5.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "procesado": 0,
                                "cantidad": 46
                                },
                                {
                                "procesado": 1,
                                "cantidad": 533
                                }
                        ]
                        }
                },
                "codigo": 200
        }

## 6.6.- Consulta Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/consultapago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 6.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.6.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos de pagos de pago para el rut 166101069. "
                },
                "codigo": 204
        }
  
#### 6.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 6.7.- Actualizar Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/actualizaproceso`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido             |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------:|----------------------------:|
| IdCliente    | string       | NNNNNNNNC                      | Si                        | Breve descripción           |
| idTransaccion| int          |                                | Si                        | Breve descripción           |

### 6.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "IdCliente": "166101069",
                "idTransaccion": 54444
	}

### 6.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.7.2.2.- Respuesta de éxito

`OK`