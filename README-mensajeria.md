| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Mensajería

<!-- Índice -->
- [Documentación Api´s para Mensajeria](#documentación-apis-para-mensajerial)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- FacebookValidate](#1--FacebookValidate)
    - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
    - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
        - [1.2.1- Respuesta de error](#121--respuesta-de-error)
        - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
  - [2.- RecepcionFB](#2--RecepcionFB)
    - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
    - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
        - [2.2.1- Respuesta de error](#221--respuesta-de-error)
        - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- RecepcionFB](#3--RecepcionFB)
    - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
    - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
        - [3.2.1- Respuesta de error](#321--respuesta-de-error)
        - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- deleteArchivo](#1--deleteArchivo)
    - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
    - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
        - [4.2.1- Respuesta de error](#421--respuesta-de-error)
        - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
  - [5.- diaactual](#5--diaactual)
    - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
    - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
        - [5.2.1- Respuesta de error](#521--respuesta-de-error)
        - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- enviarMensaje](#6--enviarMensaje)
    - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
    - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
        - [6.2.1- Respuesta de error](#621--respuesta-de-error)
        - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- enviarMensajeDev](#7--enviarMensajeDev)
    - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
    - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
        - [7.2.1- Respuesta de error](#721--respuesta-de-error)
        - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
  - [8.- enviarPublicacion](#8--enviarPublicacion)
    - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
    - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
        - [8.2.1- Respuesta de error](#821--respuesta-de-error)
        - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
  - [9.- feriados](#9--feriados)
    - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
    - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
        - [9.2.1- Respuesta de error](#921--respuesta-de-error)
        - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- guerdarReceptor](#10--guerdarReceptor)
    - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
    - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
        - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
        - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)
  - [11.- hubspot](#11--hubspot)
    - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
    - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
        - [11.2.1- Respuesta de error](#1121--respuesta-de-error)
        - [11.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
  - [12.- informarContingencia](#12--informarContingencia)
    - [12.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
    - [12.2.- Respuesta de Salida](#122--respuesta-de-salida)
        - [12.2.1- Respuesta de error](#1221--respuesta-de-error)
        - [12.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [13.- mjeOut](#13--mjeOut)
    - [13.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
    - [13.2.- Respuesta de Salida](#132--respuesta-de-salida)
        - [13.2.1- Respuesta de error](#1321--respuesta-de-error)
        - [13.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
  - [14.- mjein](#14--mjein)
    - [14.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
    - [14.2.- Respuesta de Salida](#142--respuesta-de-salida)
        - [14.2.1- Respuesta de error](#1421--respuesta-de-error)
        - [14.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
  - [15.- purgaMails](#15--purgaMails)
    - [15.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
    - [15.2.- Respuesta de Salida](#152--respuesta-de-salida)
        - [15.2.1- Respuesta de error](#1521--respuesta-de-error)
        - [15.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
  - [16.- recibeFacebook](#16--recibeFacebook)
    - [16.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
    - [16.2.- Respuesta de Salida](#162--respuesta-de-salida)
        - [16.2.1- Respuesta de error](#1621--respuesta-de-error)
        - [16.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
  - [17.- recibeMensajeFb](#17--recibeMensajeFb)
    - [17.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
    - [17.2.- Respuesta de Salida](#172--respuesta-de-salida)
        - [17.2.1- Respuesta de error](#1721--respuesta-de-error)
        - [17.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
  - [18.- recibeMensajeInst](#18--recibeMensajeInst)
    - [18.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
    - [18.2.- Respuesta de Salida](#182--respuesta-de-salida)
        - [18.2.1- Respuesta de error](#1821--respuesta-de-error)
        - [18.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
  - [19.- recibeMensajeWsp](#19--recibeMensajeWsp)
    - [19.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
    - [19.2.- Respuesta de Salida](#192--respuesta-de-salida)
        - [19.2.1- Respuesta de error](#1921--respuesta-de-error)
        - [19.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
  - [20.- recibeMensajeWspFail](#20--recibeMensajeWspFail)
    - [20.1.- Ejemplo de llamada](#201--ejemplo-de-llamada)
    - [20.2.- Respuesta de Salida](#202--respuesta-de-salida)
        - [20.2.1- Respuesta de error](#2021--respuesta-de-error)
        - [20.2.2- Respuesta de éxito](#2022--respuesta-de-éxito)
  - [21.- recibeMensajeWspStatus](#21--recibeMensajeWspStatus)
    - [21.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
    - [21.2.- Respuesta de Salida](#212--respuesta-de-salida)
        - [21.2.1- Respuesta de error](#2121--respuesta-de-error)
        - [21.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
  - [22.- recibeMjeMsn](#22--recibeMjeMsn)
    - [22.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
    - [22.2.- Respuesta de Salida](#222--respuesta-de-salida)
        - [22.2.1- Respuesta de error](#2221--respuesta-de-error)
        - [22.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
  - [23.- recibeMjeTelegram](#23--recibeMjeTelegram)
    - [23.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
    - [23.2.- Respuesta de Salida](#232--respuesta-de-salida)
        - [23.2.1- Respuesta de error](#2321--respuesta-de-error)
        - [23.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
  - [24.- recibeMjeTelegramConnect](#24--recibeMjeTelegramConnect)
    - [24.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
    - [24.2.- Respuesta de Salida](#242--respuesta-de-salida)
        - [24.2.1- Respuesta de error](#2421--respuesta-de-error)
        - [24.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
  - [25.- recibeMjeTelegramSoporte](#25--recibeMjeTelegramSoporte)
    - [25.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
    - [25.2.- Respuesta de Salida](#252--respuesta-de-salida)
        - [25.2.1- Respuesta de error](#2521--respuesta-de-error)
        - [25.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
  - [26.- recibeMjeTelegramSoporteEmpresa](#26--recibeMjeTelegramSoporteEmpresa)
    - [26.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
    - [26.2.- Respuesta de Salida](#262--respuesta-de-salida)
        - [26.2.1- Respuesta de error](#2621--respuesta-de-error)
        - [26.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
  - [27.- recibeMjeTelegramSoporteTecnico](#27--recibeMjeTelegramSoporteTecnico)
    - [27.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
    - [27.2.- Respuesta de Salida](#272--respuesta-de-salida)
        - [27.2.1- Respuesta de error](#2721--respuesta-de-error)
        - [27.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
  - [28.- recibeMjeTelegramTest](#28--recibeMjeTelegramTest)
    - [28.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
    - [28.2.- Respuesta de Salida](#282--respuesta-de-salida)
        - [28.2.1- Respuesta de error](#2821--respuesta-de-error)
        - [28.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
  - [29.- recibeMjeTelegramVentas](#29--recibeMjeTelegramVentas)
    - [29.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
    - [29.2.- Respuesta de Salida](#292--respuesta-de-salida)
        - [29.2.1- Respuesta de error](#2921--respuesta-de-error)
        - [29.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
  - [30.- recibeTwitter](#30--recibeTwitter)
    - [30.1.- Ejemplo de llamada](#301--ejemplo-de-llamada)
    - [30.2.- Respuesta de Salida](#302--respuesta-de-salida)
        - [30.2.1- Respuesta de error](#3021--respuesta-de-error)
        - [30.2.2- Respuesta de éxito](#3022--respuesta-de-éxito)
  - [31.- recibirComentariosFb](#31--recibirComentariosFb)
    - [31.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
    - [31.2.- Respuesta de Salida](#312--respuesta-de-salida)
        - [31.2.1- Respuesta de error](#3121--respuesta-de-error)
        - [31.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
  - [32.- recibirConversaciones](#32--recibirConversaciones)
    - [32.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
    - [32.2.- Respuesta de Salida](#322--respuesta-de-salida)
        - [32.2.1- Respuesta de error](#3221--respuesta-de-error)
        - [32.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
  - [33.- recibirMail](#33--recibirMail)
    - [33.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
    - [33.2.- Respuesta de Salida](#332--respuesta-de-salida)
        - [33.2.1- Respuesta de error](#3321--respuesta-de-error)
        - [33.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
  - [34.- registraTelegram](#34--registraTelegram)
    - [34.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
    - [34.2.- Respuesta de Salida](#342--respuesta-de-salida)
        - [34.2.1- Respuesta de error](#3421--respuesta-de-error)
        - [34.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
  - [35.- storeArchivo](#35--storeArchivo)
    - [35.1.- Ejemplo de llamada](#351--ejemplo-de-llamada)
    - [35.2.- Respuesta de Salida](#352--respuesta-de-salida)
        - [35.2.1- Respuesta de error](#3521--respuesta-de-error)
        - [35.2.2- Respuesta de éxito](#3522--respuesta-de-éxito)
  - [36.- test](#36--test)
    - [36.1.- Ejemplo de llamada](#361--ejemplo-de-llamada)
    - [36.2.- Respuesta de Salida](#362--respuesta-de-salida)
        - [36.2.1- Respuesta de error](#3621--respuesta-de-error)
        - [36.2.2- Respuesta de éxito](#3622--respuesta-de-éxito)
  - [37.- twitterfixer](#37--twitterfixer)
    - [37.1.- Ejemplo de llamada](#371--ejemplo-de-llamada)
    - [37.2.- Respuesta de Salida](#372--respuesta-de-salida)
        - [37.2.1- Respuesta de error](#3721--respuesta-de-error)
        - [37.2.2- Respuesta de éxito](#3722--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- FacebookValidate
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/FacebookValidate`

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


## 2.- RecepcionFb
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/RecepcionFb`

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

## 3.- RecepcionFb
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/RecepcionFb`

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

## 4.- deleteArchivo
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/deleteArchivo`

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

## 5.- diaactual
Método que responde si el día corresponde o no a un día feriado, y si es o no irrenunciable.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/diaactual`

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

## 6.- enviarMensaje
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensaje`

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

## 7.- enviarMensajeDev
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensajeDev`

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

## 8.- enviarPublicacion
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarPublicacion`

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

## 9.- feriados
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/feriados`

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

## 10.- guardarReceptor
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/guardarReceptor`

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

## 11.- hubspot
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/hubspot`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 11.2.2.- Respuesta de éxito

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

## 12.- informarContingencia
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/informarContingencia`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 12.2.2.- Respuesta de éxito

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

## 13.- mjeOut
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mjeOut`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 13.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 13.2.2.- Respuesta de éxito

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

## 14.- mjein
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mjein`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 14.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 14.2.2.- Respuesta de éxito

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

## 15.- purgaMails
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/purgaMails`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 15.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 15.2.2.- Respuesta de éxito

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

## 16.- recibeFacebook
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeFacebook`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 16.2.2.- Respuesta de éxito

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

## 17.- recibeMensajeFb
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeFb`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 17.2.2.- Respuesta de éxito

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

## 18.- recibeMensajeInst
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeInst`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 18.2.2.- Respuesta de éxito

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

## 19.- recibeMensajeWsp
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWsp`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 19.2.2.- Respuesta de éxito

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

## 20.- recibeMensajeWspFail
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWspFail`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 20.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 20.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 20.2.2.- Respuesta de éxito

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

## 21.- recibeMensajeWspStatus
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWspStatus`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 21.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 21.2.2.- Respuesta de éxito

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

## 22.- recibeMjeMsn
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/recibeMjeMsn`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 22.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 22.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 22.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 22.2.2.- Respuesta de éxito

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

## 23.- recibeMjeTelegram
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegram`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 23.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 23.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 23.2.2.- Respuesta de éxito

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

## 24.- recibeMjeTelegramConnect
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramConnect`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 24.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 24.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 24.2.2.- Respuesta de éxito

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

## 25.- recibeMjeTelegramSoporte
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporte`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 25.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 25.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 25.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 25.2.2.- Respuesta de éxito

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

## 26.- recibeMjeTelegramSoporteEmpresa
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporteEmpresa`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 26.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 26.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 26.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 26.2.2.- Respuesta de éxito

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

## 27.- recibeMjeTelegramSoporteTecnico
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporteTecnico`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 27.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 27.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 27.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 27.2.2.- Respuesta de éxito

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

## 28.- recibeMjeTelegramTest
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramTest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 28.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 28.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 28.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 28.2.2.- Respuesta de éxito

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

## 29.- recibeMjeTelegramVentas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramVentas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 29.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 29.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 29.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 29.2.2.- Respuesta de éxito

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

## 30.- recibeTwitter
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeTwitter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 30.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 30.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 30.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 30.2.2.- Respuesta de éxito

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

## 31.- recibirComentariosFb
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/recibirComentariosFb`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 31.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 31.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 31.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 31.2.2.- Respuesta de éxito

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

## 32.- recibirConversaciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/recibirConversaciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 32.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 32.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 32.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 32.2.2.- Respuesta de éxito

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

## 33.- recibirMail
Método que permite la recepción de mails sin esperar al cron.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/recibirMail`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 33.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 33.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 33.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 33.2.2.- Respuesta de éxito

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

## 34.- registraTelegram
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/registraTelegram`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 34.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 34.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 34.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 34.2.2.- Respuesta de éxito

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

## 35.- storeArchivo
Método que permite guardar archivos en el servidor.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/storeArchivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 35.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 35.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 35.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 35.2.2.- Respuesta de éxito

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

## 36.- test
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/test`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 36.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 36.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 36.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 36.2.2.- Respuesta de éxito

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

## 37.- twitterfixer
Método que permite reenviar todos los mensajes de twitter que en su momento no fueron entregados. (Debe revisarse BD antes de usar) 

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/twitterfixer`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 37.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 37.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 37.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 37.2.2.- Respuesta de éxito

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