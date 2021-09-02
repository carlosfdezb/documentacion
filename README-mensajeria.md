| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Mensajería

<!-- Índice -->
- [Documentación Api´s para Mensajeria](#documentación-apis-para-mensajerial)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- RecepcionFB](#1--RecepcionFB)
    - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
    - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
        - [1.2.1- Respuesta de error](#121--respuesta-de-error)
        - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
  - [2.- RecepcionFB](#2--RecepcionFB)
    - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
    - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
        - [2.2.1- Respuesta de error](#221--respuesta-de-error)
        - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- deleteArchivo](#1--deleteArchivo)
    - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
    - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
        - [3.2.1- Respuesta de error](#321--respuesta-de-error)
        - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- diaactual](#4--diaactual)
    - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
    - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
        - [4.2.1- Respuesta de error](#421--respuesta-de-error)
        - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
  - [5.- enviarMensaje](#5--enviarMensaje)
    - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
    - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
        - [5.2.1- Respuesta de error](#521--respuesta-de-error)
        - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- enviarMensajeDev](#6--enviarMensajeDev)
    - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
    - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
        - [6.2.1- Respuesta de error](#621--respuesta-de-error)
        - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- feriados](#7--feriados)
    - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
    - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
        - [7.2.1- Respuesta de error](#721--respuesta-de-error)
        - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
  - [8.- hubspot](#8--hubspot)
    - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
    - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
        - [8.2.1- Respuesta de error](#821--respuesta-de-error)
        - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
  - [9.- informarContingencia](#9--informarContingencia)
    - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
    - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
        - [9.2.1- Respuesta de error](#921--respuesta-de-error)
        - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- mjeOut](#10--mjeOut)
    - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
    - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
        - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
        - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)
  - [11.- mjein](#11--mjein)
    - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
    - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
        - [11.2.1- Respuesta de error](#1121--respuesta-de-error)
        - [11.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
  - [12.- recibeMensajeWsp](#12--recibeMensajeWsp)
    - [12.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
    - [12.2.- Respuesta de Salida](#122--respuesta-de-salida)
        - [12.2.1- Respuesta de error](#1221--respuesta-de-error)
        - [12.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [13.- recibeMensajeWspFail](#13--recibeMensajeWspFail)
    - [13.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
    - [13.2.- Respuesta de Salida](#132--respuesta-de-salida)
        - [13.2.1- Respuesta de error](#1321--respuesta-de-error)
        - [13.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
  - [14.- recibeMensajeWspStatus](#14--recibeMensajeWspStatus)
    - [14.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
    - [14.2.- Respuesta de Salida](#142--respuesta-de-salida)
        - [14.2.1- Respuesta de error](#1421--respuesta-de-error)
        - [14.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
  - [15.- recibeMjeTelegramConnect](#15--recibeMjeTelegramConnect)
    - [15.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
    - [15.2.- Respuesta de Salida](#152--respuesta-de-salida)
        - [15.2.1- Respuesta de error](#1521--respuesta-de-error)
        - [15.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
  - [16.- recibeMjeTelegramSoporte](#16--recibeMjeTelegramSoporte)
    - [16.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
    - [16.2.- Respuesta de Salida](#162--respuesta-de-salida)
        - [16.2.1- Respuesta de error](#1621--respuesta-de-error)
        - [16.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
  - [17.- recibeMjeTelegramSoporteEmpresa](#17--recibeMjeTelegramSoporteEmpresa)
    - [17.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
    - [17.2.- Respuesta de Salida](#172--respuesta-de-salida)
        - [17.2.1- Respuesta de error](#1721--respuesta-de-error)
        - [17.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
  - [18.- recibeMjeTelegramSoporteTecnico](#18--recibeMjeTelegramSoporteTecnico)
    - [18.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
    - [18.2.- Respuesta de Salida](#182--respuesta-de-salida)
        - [18.2.1- Respuesta de error](#1821--respuesta-de-error)
        - [18.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
  - [19.- recibeMjeTelegramTest](#19--recibeMjeTelegramTest)
    - [19.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
    - [19.2.- Respuesta de Salida](#192--respuesta-de-salida)
        - [19.2.1- Respuesta de error](#1921--respuesta-de-error)
        - [19.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
  - [20.- recibeMjeTelegramVentas](#20--recibeMjeTelegramVentas)
    - [20.1.- Ejemplo de llamada](#201--ejemplo-de-llamada)
    - [20.2.- Respuesta de Salida](#202--respuesta-de-salida)
        - [20.2.1- Respuesta de error](#2021--respuesta-de-error)
        - [20.2.2- Respuesta de éxito](#2022--respuesta-de-éxito)
  - [21.- recibeTwitter](#21--recibeTwitter)
    - [21.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
    - [21.2.- Respuesta de Salida](#212--respuesta-de-salida)
        - [21.2.1- Respuesta de error](#2121--respuesta-de-error)
        - [21.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
  - [22.- recibirMail](#22--recibirMail)
    - [22.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
    - [22.2.- Respuesta de Salida](#222--respuesta-de-salida)
        - [22.2.1- Respuesta de error](#2221--respuesta-de-error)
        - [22.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
  - [23.- storeArchivo](#23--storeArchivo)
    - [23.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
    - [23.2.- Respuesta de Salida](#232--respuesta-de-salida)
        - [23.2.1- Respuesta de error](#2321--respuesta-de-error)
        - [23.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
  - [24.- twitterfixer](#24--twitterfixer)
    - [24.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
    - [24.2.- Respuesta de Salida](#242--respuesta-de-salida)
        - [24.2.1- Respuesta de error](#2421--respuesta-de-error)
        - [24.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- RecepcionFb
Método que permite validar conexión de servidor de facebook y mensajería.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/RecepcionFb`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido                       |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:-----------------------------------:|----------------------------:|
| hub_mode         | string       |                                |                                     | Breve descripción           |
| hub_challenge    | ?            |                                |                                     | Breve descripción           |
| hub_verify_token | ?            |                                |                                     | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "hub_mode": "subscribe",
        "hub_challenge": "",
        "hub_verify_token": ""
	}

### 1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.- RecepcionFb
Método que permite recibir mensajes de messenger facebook.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/RecepcionFb`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        | Requerido     |             Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------:|----------------------------------------:|
| type         | string       |                                |               | Tipo que indica que son nuevos mensajes |
| ↓ messages   | array[object]|                                |               |                                         |
| type         | string       |                                |               | private message, para facebook wall o messenger, dependiendo de si es público o privado|
| id           | string       |                                |               | Identificador del mensaje               |
| contentType  | string       |                                |               | Indica si el mensaje corresponde a texto, imagen o multimedia |
| text         | string       |                                |               | ?                                       |
| ↓↓ user      | array[object]|                                |               |                                         |
| id           | string       |                                |               | Id del usuario                          |
| avatar       | string       |                                |               | Url de la imagen de perfil del usuario  |
| ↓↓ mediaUrl  | array[object]|                                |               |                                         |
| url          | string       |                                |               | Indica que contiene una imagen o multimedia |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "type": "messages",
        "messages": [
            {
                "user": {
                    "id":"@jmzavala_olv", 
                    "avatar":"https://twitter.com/JM_Zavala/photo"
                    },
                "type": "tweet",
                "id": "sxlsd93mdf",
                "text": "Buenos días" 
            }
        ]
	}

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.1.- Respuesta de error

	{
        "status":"error",
        "detail": ""
    }
  
#### 2.2.2.- Respuesta de éxito

    {
        "status":"success"
    }

## 3.- deleteArchivo
Método que permite eliminar archivos del storage. 

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/deleteArchivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| id           | int          |                                | Si                              | Breve descripción           |

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
        ...
	} 
  
#### 3.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.- diaactual
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

### 4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.- enviarMensaje
Método que envía mensaje a cliente mediante cualquier canal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensaje`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| destinatario | ?            |                                |                                 | ?          |
| remitente    | ?            |                                |                                 | ?          |
| asunto       | ?            |                                |                                 | ?          |
| mensaje      | ?            |                                |                                 | ?          |
| sigla_sistema| ?            |                                |                                 | ?          |
| canal_id     | ?            |                                |                                 | ?          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "destinatario": "",
        "remitente": "",
        "asunto": "",
        "mensaje": "",
        "sigla_sistema": "",
        "canal_id": "",
	}

### 5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.- enviarMensajeDev
Método envía mensaje a cliente mediante canales de prueba.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensajeDev`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| destinatario | ?            |                                |                                 | ?          |
| remitente    | ?            |                                |                                 | ?          |
| asunto       | ?            |                                |                                 | ?          |
| mensaje      | ?            |                                |                                 | ?          |
| sigla_sistema| ?            |                                |                                 | ?          |
| canal_id     | ?            |                                |                                 | ?          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.1.- Ejemplo de llamada

Ejemplo: JSON

	{
        "destinatario": "",
        "remitente": "",
        "asunto": "",
        "mensaje": "",
        "sigla_sistema": "",
        "canal_id": "",
	}

### 6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.1.- Respuesta de error

	{
       ...
	} 
  
#### 6.2.2.- Respuesta de éxito

	{
        ...
	}


## 7.- feriados
Método que permite descargar la base de datos de feriados nacionales. 

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/feriados`

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
| feri_dia          | string       | Día feriado                                      |
| feri_motivo       | string       | Motivo del feriado                               |
| feri_irrenunciable| boolean      | Especifica si es feriado irrenunciable o no      |

### 7.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 7.1.1.- Respuesta de éxito

	{
        {
            "feri_dia":"2021-01-03",
            "feri_motivo":"Domingo",
            "feri_irrenunciable":false
        },
        {
            "feri_dia":"2021-01-10",
            "feri_motivo":"Domingo",
            "feri_irrenunciable":false
        },
        {
            "feri_dia":"2021-01-17",
            "feri_motivo":"Domingo",
            "feri_irrenunciable":false
        },
        ...
	}



## 8.- hubspot
Método que recibe mensaje de hubspot e interactua como puente hacia MundoSocial.

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

### 8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 8.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 8.2.2.- Respuesta de éxito

	{
       ...
	}

## 9.- informarContingencia
Método que recibe mensaje de contingencia en servidores y alerta a los usuarios registrados en sistema asociados a servidor.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/informarContingencia`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido             |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------:|----------------------------:|
| token        | ?            |                                |                           | Breve descripción           |
| mensaje      | ?            |                                |                           | Breve descripción           |
| sistema      | ?            |                                |                           | Breve descripción           |

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
        ...
	} 
  
#### 9.2.2.- Respuesta de éxito

	{
        ...
	}

## 10.- mjeOut
Método que recibe mensaje desde atec y envía a cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mjeOut`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| horario      | string       |                                | Si                      | Puede ser mañana o tarde    |
| fecha        | date         | dd-mm-yyyy                     | Si                      | Fecha                       |
| num_cliente  | int          |                                | Si                      | Número al que se le enviará el mensaje|
| nombre       | string       |                                | Si                      | Nombre del cliente          |

### 10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "horario": "mañana",
                "fecha": "02-09-2021",
                "num_cliente": "99885463",
                "nombre": "Carlos"
	}

### 10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 10.2.1.- Respuesta de éxito

`enviado`

## 11.- mjein
Método que recibe mensaje de cliente y reenvía hacia atec.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mjein`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                                 |     Requerido                  |             Descripción     |
|:-----------------:|:------------:|:---------------------------------------:|:------------------------------:|----------------------------:|
| reme_respuesta    | int          | 1: Aceptado, 2: Postergado, 3: Rechazado| Si                             | Respuesta del cliente       |
| env_num_referencia| int          |                                         | Si                             | Identificador del cliente   |
| type              | string       | 'sms' o 'wsp'                           | Si                             | Tipo de canal               |

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
        ...
	} 
  
#### 11.2.2.- Respuesta de éxito

	{
        ...
	}









## 12.- recibeMensajeWsp
Método que recibe mensaje de servidores de Twilio y reenvia hacia MS.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWsp`

**Parámetros de entrada:**
| Campo              |  Tipo        | Formato               | Requerido        |             Descripción     |
|:------------------:|:------------:|:---------------------:|:----------------:|----------------------------:|
| MessageSid         | string       |                       | Si               | Identificador del mensaje   |
| SmsSid             | string       |                       | Si               | Misma valor que MessageSid, deprecado|
| AccountSid         | string       |                       | Si               | Identificador de la cuenta  |
| MessagingServiceSid| string       |                       | Si               | Identificador del servicio de mensajes|
| From               | string       |                       | Si               | Número telefónico que envía el mensaje|
| To                 | string       |                       | Si               | Número telefónico que recibe el mensaje|
| Body               | string       |                       | Si               | Texto del mensaje, de hasta 1600 caracteres|
| NumMedia           | int          |                       | Si               | Número de ítems multimedia asociados al mensaje|

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
        ...
	} 
  
#### 12.2.2.- Respuesta de éxito

	{
        ...
	}

## 13.- recibeMensajeWspFail
Método que recibe mensaje de servidores de Twilio y reenvia hacia MS (backup).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWspFail`

**Parámetros de entrada:**
| Campo              |  Tipo        | Formato               | Requerido        |             Descripción     |
|:------------------:|:------------:|:---------------------:|:----------------:|----------------------------:|
| MessageSid         | string       |                       | Si               | Identificador del mensaje   |
| SmsSid             | string       |                       | Si               | Misma valor que MessageSid, deprecado|
| AccountSid         | string       |                       | Si               | Identificador de la cuenta  |
| MessagingServiceSid| string       |                       | Si               | Identificador del servicio de mensajes|
| From               | string       |                       | Si               | Número telefónico que envía el mensaje|
| To                 | string       |                       | Si               | Número telefónico que recibe el mensaje|
| Body               | string       |                       | Si               | Texto del mensaje, de hasta 1600 caracteres|
| NumMedia           | int          |                       | Si               | Número de ítems multimedia asociados al mensaje|

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

codigo: 130 éxito mensaje: descripcion del mensaje

#### 13.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 13.2.2.- Respuesta de éxito

	{
        ...
	}

## 14.- recibeMensajeWspStatus
Método que recibe mensaje de servidores de Twilio en caso de fallo y alerta status de sistema.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWspStatus`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                 |     Requerido          |             Descripción     |
|:------------:|:------------:|:-----------------------:|:----------------------:|----------------------------:|
| MessageStatus| string       |                         |                        | Estado del mensaje          |
| SmsStatus    | string       |                         |                        | Mismo que MessageStatus, deprecado|

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

`error`
  
#### 14.2.2.- Respuesta de éxito

	{
        ...
	}



## 15.- recibeMjeTelegramConnect
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta)

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramConnect`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido           | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:-------------------:|----------------------------:|
| update_id          | int                                            |                  | Si                  | Identificador del update    |
| ⇩ message          | array[object]                                  |                  | Si                  |                             |
| ↳ message_id       | int                                            |                  | Si                  | Identificador del mensaje   |
| ↳ from             | [User](https://core.telegram.org/bots/api#user)|                  |                     | Remitente del mensaje       |
| ↳ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |                     | Remitente del mensaje enviado en nombre de un chat|
| ↳ date             | date                                           | Unix             | Si                  | Fecha del mensaje           |
| ↳ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si                  | Conversación a la que pertenece el mensaje|
| ↳ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |                     | Para mensajes reenviados, remitente del mensaje original|
| ↳ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |                     | Para mensajes reenviados desde chats, remitente del mensaje original|
| ↳ forward_from_message_id| int                                      |                  |                     | Para mensajes reenviados desde chats, identificador del mensaje original|
| ↳ forward_signature| string                                         |                  |                     | Para mensajes reenviados desde chats, firma del autor de la publicación|

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
        ...
	} 
  
#### 15.2.2.- Respuesta de éxito

	{
       ...
	}

## 16.- recibeMjeTelegramSoporte
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

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

### 16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 16.2.2.- Respuesta de éxito

	{
        ...
	}

## 17.- recibeMjeTelegramSoporteEmpresa
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

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

### 17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 17.2.2.- Respuesta de éxito

	{
       ...
	}

## 18.- recibeMjeTelegramSoporteTecnico
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

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

### 18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 18.2.2.- Respuesta de éxito

	{
        ...
	}

## 19.- recibeMjeTelegramTest
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

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

### 19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 19.2.2.- Respuesta de éxito

	{
        ...
	}

## 20.- recibeMjeTelegramVentas
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

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

### 20.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 20.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 20.2.2.- Respuesta de éxito

	{
        ...
	}

## 21.- recibeTwitter
Método que recibe Mensajes de Twitter y facebook desde Api de OneMarketer.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeTwitter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        | Requerido     |             Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------:|----------------------------------------:|
| type         | string       |                                |               | Tipo que indica que son nuevos mensajes |
| ↓ messages   | array[object]|                                |               |                                         |
| type         | string       |                                |               | Tweet                                   |
| id           | string       |                                |               | Identificador del mensaje               |
| contentType  | string       |                                |               | Indica si el mensaje corresponde a texto, imagen o multimedia |
| text         | string       |                                |               | ?                                       |
| ↓↓ user      | array[object]|                                |               |                                         |
| id           | string       |                                |               | Id del usuario                          |
| avatar       | string       |                                |               | Url de la imagen de perfil del usuario  |
| ↓↓ mediaUrl  | array[object]|                                |               |                                         |
| url          | string       |                                |               | Indica que contiene una imagen o multimedia |

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
        ...
	} 
  
#### 21.2.2.- Respuesta de éxito

	{
        ...
	}



## 22.- recibirMail
Método que permite la recepción de mails sin esperar al cron.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/recibirMail`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 22.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 22.1.1.- Respuesta de error

	{
        ...
	} 
  
#### 22.1.2.- Respuesta de éxito

	{
        ...
	}



## 23.- storeArchivo
Método que permite guardar archivos en el servidor.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/storeArchivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| adjunto      | archive      |                                |                             | Breve descripción           |
| token        | string       |                                |                             | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 23.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "adjunto":,
        "token": "":
	}

### 23.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 23.2.2.- Respuesta de éxito

	{
        ...
	}


## 24.- twitterfixer
Método que permite reenviar todos los mensajes de twitter que en su momento no fueron entregados. (Debe revisarse BD antes de usar) 

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/twitterfixer`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 24.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.1.1.- Respuesta de error

	{
        ...
	} 
  
#### 24.1.2.- Respuesta de éxito

	{
        ...
	}