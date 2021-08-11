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
    - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
    - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
        - [1.2.1- Respuesta de error](#121--respuesta-de-error)
        - [1.2.2- Respuesta de éxito](#123--respuesta-de-éxito)
  - [2.- Entidades de Pago](#2--entidades-de-pago)
    - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
    - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
        - [2.2.1- Respuesta de error](#221--respuesta-de-error)
        - [2.2.2- Respuesta de éxito](#223--respuesta-de-éxito)
  - [3.- Consultar Deuda Según Cliente](#3--consultar-deuda-según-cliente)
    - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
    - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
        - [3.2.1- Respuesta de error](#321--respuesta-de-error)
        - [3.2.2- Respuesta de éxito](#323--respuesta-de-éxito)
  - [4.- Insertar Correo](#4--insertar-correo)
    - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
    - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
        - [4.2.1- Respuesta de error](#421--respuesta-de-error)
        - [4.2.2- Respuesta de éxito](#423--respuesta-de-éxito)
  - [5.- Intermedio](#5--intermedio)
    - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
    - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
        - [5.2.1- Respuesta de error](#521--respuesta-de-error)
        - [5.2.2- Respuesta de éxito](#523--respuesta-de-éxito)
  - [6.- Consultar Voucher](#6--consultar-voucher)
    - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
    - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
        - [6.2.1- Respuesta de error](#621--respuesta-de-error)
        - [6.2.2- Respuesta de éxito](#623--respuesta-de-éxito)
  - [7.- Redireccionar a Banco Estado](#7--redireccionar-a-banco-estado)
    - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
    - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
        - [7.2.1- Respuesta de error](#721--respuesta-de-error)
        - [7.2.2- Respuesta de éxito](#723--respuesta-de-éxito)
  - [8.- Redireccionar a WebPay Plus](#8--redireccionar-a-webPay-plus)
    - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
    - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
        - [8.2.1- Respuesta de error](#821--respuesta-de-error)
        - [8.2.2- Respuesta de éxito](#823--respuesta-de-éxito)
  - [9.- Redireccionar a Servipag](#9--redireccionar-a-servipag)
    - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
    - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
        - [9.2.1- Respuesta de error](#921--respuesta-de-error)
        - [9.2.2- Respuesta de éxito](#923--respuesta-de-éxito)
  - [10.- Consultar Datos de Voucher](#10--consultar-datos-de-voucher)
    - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
    - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
        - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
        - [10.2.2- Respuesta de éxito](#1023--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

En este documento solo se describen Api's propias del sistema, no externas a este.


## 1.- Consultar Datos de Cliente
Método que permite consultar datos del cliente para identificar tipo y correo electrónico.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultadatoscliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 2.- Entidades de Pago
Método que permite llamar imagen para crear botonera de selección de las entidades de pago.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/entidadpago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 3.- Consultar Deuda Según Cliente
Método que permite consultar la deuda según tipo de cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultadeudatipocliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 4.- Insertar Correo
Método que permite insertar correo indicado por el cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/insertacorreo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 4.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 5.- Intermedio
Método que determina la nueva ruta de pago fácil, según éxito, anular o error.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/intermedio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 5.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 6.- Consultar Voucher
Método que permite consultar datos para voucher.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultavoucherfront`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 6.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 7.- Redireccionar a Banco Estado
Método que permite redireccionar a pago con botón Banco Estado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/botonestado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 7.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 8.- Redireccionar a WebPay Plus
Método que permite redireccionar a pago con WebPay Plus.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/webpaypluss`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 8.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 8.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 9.- Redireccionar a Servipag
Método que permite redireccionar a pago con botón Servipag.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/servipagboton`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 9.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}

## 10.- Consultar Datos de Voucher
Método que permite consultar datos de voucher pagado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/pagoRapido/consultarvoucherbdfront`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 10.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 10.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}