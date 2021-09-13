| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Mensajería

<!-- Índice -->
- [Documentación Api´s para Mensajeria](#documentación-apis-para-mensajerial)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Validar Conexión de Facebook](#1--validar-conexión-de-facebook)
    - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
    - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
        - [1.2.1- Respuesta de error](#121--respuesta-de-error)
        - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
  - [2.- Recibir Mensajes de Facebook](#2--recibir-mensajes-de-facebook)
    - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
    - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
        - [2.2.1- Respuesta de error](#221--respuesta-de-error)
        - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- Borrar Archivos](#1--borrar-archivos)
    - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
    - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
        - [3.2.1- Respuesta de error](#321--respuesta-de-error)
        - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- Día Actual](#4--día-actual)
    - [4.1.- Respuesta de Salida](#41--respuesta-de-salida)
        - [4.1.1- Respuesta de éxito](#411--respuesta-de-éxito)
  - [5.- Enviar Mensaje](#5--enviar-mensaje)
    - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
    - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
        - [5.2.1- Respuesta de error](#521--respuesta-de-error)
        - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- Enviar Mensaje Desarrollo](#6--enviar-mensaje-desarrollo)
    - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
    - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
        - [6.2.1- Respuesta de error](#621--respuesta-de-error)
        - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- Feriados Nacionales](#7--feriados-nacionales)
    - [7.1.- Respuesta de Salida](#71--respuesta-de-salida)
        - [7.1.1- Respuesta de éxito](#711--respuesta-de-éxito)
  - [8.- Recibir Mensajes de Hubspot](#8--recibir-mensajes-de-hubspot)
    - [8.1.- Respuesta de Salida](#81--respuesta-de-salida)
        - [8.1.1- Respuesta de error](#811--respuesta-de-error)
        - [8.1.2- Respuesta de éxito](#812--respuesta-de-éxito)
  - [9.- Informar de Contingencia](#9--informar-de-contingencia)
    - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
    - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
        - [9.2.1- Respuesta de error](#921--respuesta-de-error)
        - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- Mandar Mensajes](#10--mandar-mensajes)
    - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
    - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
        - [10.2.1- Respuesta de éxito](#1021--respuesta-de-éxito)
  - [11.- Recibir Mensajes](#11--recibir-mensajes)
    - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
    - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
        - [11.2.1- Respuesta de éxito](#1121--respuesta-de-éxito)
  - [12.- Recibir Mensajes de Whatsapp](#12--recibir-mensajes-de-whatsapp)
    - [12.1.- Respuesta de Salida](#121--respuesta-de-salida)
        - [12.1.1- Respuesta de error](#1211--respuesta-de-error)
        - [12.1.2- Respuesta de éxito](#1212--respuesta-de-éxito)
  - [13.- Recibir Mensajes Fail de Whatsapp](#13--recibir-mensajes-fail-de-whatsapp)
    - [13.1.- Respuesta de Salida](#131--respuesta-de-salida)
        - [13.1.1- Respuesta de error](#1311--respuesta-de-error)
        - [13.1.2- Respuesta de éxito](#1312--respuesta-de-éxito)
  - [14.- Recibir Status de Whatsapp](#14--recibir-status-de-whatsapp)
    - [14.1.- Respuesta de Salida](#141--respuesta-de-salida)
        - [14.1.1- Respuesta de error](#1411--respuesta-de-error)
        - [14.1.2- Respuesta de éxito](#1412--respuesta-de-éxito)
  - [15.- Recibir Mensajes de Telegram Connect](#15--recibir-mensajes-de-telegram-connect)
    - [15.1.- Respuesta de Salida](#151--respuesta-de-salida)
        - [15.1.1- Respuesta de error](#1511--respuesta-de-error)
        - [15.1.2- Respuesta de éxito](#1512--respuesta-de-éxito)
  - [16.- Recibir Mensajes de Telegram Soporte](#16--recibir-mensajes-de-telegram-soporte)
    - [16.1.- Respuesta de Salida](#161--respuesta-de-salida)
        - [16.1.1- Respuesta de error](#1611--respuesta-de-error)
        - [16.1.2- Respuesta de éxito](#1612--respuesta-de-éxito)
  - [17.- Recibir Mensaje de Telegram Soporte Empresas](#17--recibir-mensaje-de-telegram-soporte-empresas)
    - [17.1.- Respuesta de Salida](#171--respuesta-de-salida)
        - [17.1.1- Respuesta de error](#1711--respuesta-de-error)
        - [17.1.2- Respuesta de éxito](#1712--respuesta-de-éxito)
  - [18.- Recibir Mensajes de Telegram Soporte Técnico](#18--recibir-mensajes-de-telegram-soporte-técnico)
    - [18.1.- Respuesta de Salida](#181--respuesta-de-salida)
        - [18.1.1- Respuesta de error](#1811--respuesta-de-error)
        - [18.1.2- Respuesta de éxito](#1812--respuesta-de-éxito)
  - [19.- Recibir Mensajes de Telegram Test](#19--recibir-mensajes-de-telegram-test)
    - [19.1.- Respuesta de Salida](#191--respuesta-de-salida)
        - [19.1.1- Respuesta de error](#1911--respuesta-de-error)
        - [19.1.2- Respuesta de éxito](#1912--respuesta-de-éxito)
  - [20.- Recibir Mensajes de Telegram Ventas](#20--recibir-mensajes-de-telegram-ventas)
    - [20.1.- Respuesta de Salida](#201--respuesta-de-salida)
        - [20.1.1- Respuesta de error](#2011--respuesta-de-error)
        - [20.1.2- Respuesta de éxito](#2012--respuesta-de-éxito)
  - [21.- Recibir Mensajes de Twitter](#21--recibir-mensajes-de-twitter)
    - [21.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
    - [21.2.- Respuesta de Salida](#212--respuesta-de-salida)
        - [21.2.1- Respuesta de error](#2121--respuesta-de-error)
        - [21.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
  - [22.- Recepción de Mails](#22--recepción-de-mails)
    - [22.1.- Respuesta de Salida](#221--respuesta-de-salida)
        - [22.1.1- Respuesta de error](#2211--respuesta-de-error)
        - [22.1.2- Respuesta de éxito](#2212--respuesta-de-éxito)
  - [23.- Guardar Archivo](#23--guardar-archivo)
    - [23.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
    - [23.2.- Respuesta de Salida](#232--respuesta-de-salida)
        - [23.2.1- Respuesta de error](#2321--respuesta-de-error)
        - [23.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
  - [24.- Reenviar Mensajes de Twitter](#24--reenviar-mensajes-de-twitter)
    - [24.1.- Respuesta de Salida](#241--respuesta-de-salida)
        - [24.1.1- Respuesta de error](#2411--respuesta-de-error)
        - [24.1.2- Respuesta de éxito](#2412--respuesta-de-éxito)


# Objetivo

Disponer Api's para realizar la gestión de la Mensajería de Mundo.

# Restricciones

En este documento solo se describen Api's propias del sistema, no externas a este.


## 1.- Validar Conexión de Facebook
Método que permite validar conexión de servidor de facebook y mensajería.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/RecepcionFb`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| hub_mode         | string       |                                | Si                          | Este valor siempre estará configurado como subscribe|
| hub_challenge    | int          |                                | Si                          | Número que se debe volver a transmitir|
| hub_verify_token | string       |                                | Si                          | Token de verificación       |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "hub_mode": "subscribe",
                "hub_challenge": 1158201444,
                "hub_verify_token": "meatyhamhock"
	}

### 1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 1.2.2.- Respuesta de éxito

        {
                "status": "success",
                "codigo": 200
	} 

## 2.- Recibir Mensajes de Facebook
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
| text         | string       |                                |               | Texto                                   |
| ↓↓ user      | array[object]|                                |               |                                         |
| id           | string       |                                |               | Id del usuario                          |
| avatar       | string       |                                |               | Url de la imagen de perfil del usuario  |
| ↓↓ mediaUrl  | array[object]|                                |               |                                         |
| url          | string       |                                |               | Indica que contiene una imagen o multimedia |

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "type": "messages",
                "messages": [
                        {
                                "user": {
                                                "id":"@jmzavala_olv", 
                                                "avatar":""
                                        },
                                "type": "private_message",
                                "id": "sxlsd93mdf",
                                "text": "Buenos días" 
                        }
                ]
        }

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 2.2.2.- Respuesta de éxito

        {
                "status": "success",
                "codigo": 200
	} 

## 3.- Borrar Archivos
Método que permite eliminar archivos del storage. 

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/deleteArchivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| id           | int          |                                | Si                              | ID del archivo              |

### 3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "id": 22
	}

### 3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 3.2.2.- Respuesta de éxito

        {
                "status": "ok",
                "codigo": 200
	} 

## 4.- Día Actual
Método que responde si el día corresponde o no a un día feriado, y si es o no irrenunciable.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/diaactual`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| nombre         | string       | Nombre del feriado                               |
| feriado        | string       | Si es feriado o no                               |
| irrenunciable  | string       | Si es feriado irrenunciable o no                 |
| fecha          | date         | Fecha del feriado                                |
| diatexto       | string       | Descripción del día                              |

### 4.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.1.1.- Respuesta de éxito

        {
                "nombre": "",
                "feriado": "no",
                "irrenunciable": "",
                "fecha": "02-09-2021",
                "diatexto": "jueves 2 septiembre 2021"
        }

## 5.- Enviar Mensaje
Método que envía mensaje a cliente mediante cualquier canal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensaje`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| destinatario | string       |                                |                                 | Destinatario del mensaje    |
| remitente    | string       |                                |                                 | Remitente del mensaje       |
| asunto       | string       |                                |                                 | Asunto del mensaje          |
| mensaje      | string       |                                |                                 | Texto del mensaje           |
| sigla_sistema| string       |                                |                                 | Siglas del sistema          |
| canal_id     | int          |                                |                                 | ID del canal                |

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
                "status": "error",
                "codigo": 401
	} 
  
#### 5.2.2.- Respuesta de éxito

        {
                "status": "ok",
                "codigo": 200
	} 

## 6.- Enviar Mensaje Desarrollo
Método envía mensaje a cliente mediante canales de prueba.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/enviarMensajeDev`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                   |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| destinatario | string       |                                |                                 | Destinatario del mensaje    |
| remitente    | string       |                                |                                 | Remitente del mensaje       |
| asunto       | string       |                                |                                 | Asunto del mensaje          |
| mensaje      | string       |                                |                                 | Texto del mensaje           |
| sigla_sistema| string       |                                |                                 | Siglas del sistema          |
| canal_id     | int          |                                |                                 | ID del canal                |

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
                "status": "error",
                "codigo": 401
	} 
  
#### 6.2.2.- Respuesta de éxito

        {
                "status": "ok",
                "codigo": 200
	} 


## 7.- Feriados Nacionales
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



## 8.- Recibir Mensajes de Hubspot
Método que recibe mensaje de hubspot e interactua como puente hacia MundoSocial.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/hubspot`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        | Requerido   |             Descripción     |
|:-----------------:|:------------:|:------------------------------:|:-----------:|----------------------------:|
| value             | string       |                                |             | Valor                       |
| source-type       | string       |                                |             | Tipo de la fuente           |
| source-id         | string       |                                |             | ID de la fuente             |
| source-label      | string       |                                |             | Etiqueta de la fuente       |
| updated-by-user-id| string       |                                |             | ID del último usuario en actualizar|
| conversion-id     | string       |                                |             | ID de la conversión         |
| portal-id         | string       |                                |             | ID del portal               |
| page-url          | string       |                                |             | Url de la página            |
| canonical-url     | string       |                                |             | Url canónica                |
| page-title        | string       |                                |             | Título de la página         |
| page-id           | string       |                                |             | ID de la página             |
| form-type         | string       |                                |             | Tipo de formulario          |
| static-list-id    | string       |                                |             | ID de la lisa estática      |
| internal-list-id  | string       |                                |             | ID de la lista interna      |
| canal             | string       |                                |             | Tipo de canal               |
| destino           | string       |                                |             | Tipo de destino             |

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 8.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 8.2.2.- Respuesta de éxito

        {
                "status": "ok",
                "codigo": 200
	} 

## 9.- Informar de Contingencia
Método que recibe mensaje de contingencia en servidores y alerta a los usuarios registrados en sistema asociados a servidor.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/informarContingencia`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido             |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------:|----------------------------:|
| token        | string       |                                | Si                        | Token                       |
| mensaje      | string       |                                |                           | Contenido del mensaje       |
| sistema      | string       |                                |                           | Sistema                     |

### 9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "token": "token_example",
                "mensaje": "Nueva Contingencia",
                "sistema": "MS"
	}

### 9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.2.1.- Respuesta de error

	{
            "status": "error",
            "codigo": 401
	} 
  
#### 9.2.2.- Respuesta de éxito

        {
            "status": "success",
            "codigo": 200
	} 


## 10.- Mandar Mensajes
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

## 11.- Recibir Mensajes
Método que recibe mensaje de cliente y reenvía hacia atec.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mjein`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                                 |     Requerido                  |             Descripción     |
|:-----------------:|:------------:|:---------------------------------------:|:------------------------------:|----------------------------:|
| reme_respuesta    | int          | 1: Aceptado, 2: Postergado, 3: Rechazado| Si                             | Respuesta del cliente       |
| env_num_referencia| int          |                                         | Si                             | Identificador del cliente   |
| type              | string       | 'sms' o 'wsp'                           | Si                             | Tipo de canal               |

### 11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "reme_respuesta": 1,
                "env_num_referencia": 11111,
                "type": "sms"
	}

### 11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.1.- Respuesta de éxito

`enviado`


## 12.- Recibir Mensajes de Whatsapp
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

### 12.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.1.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 12.1.2.- Respuesta de éxito

	{
                "status": "ok",
                "codigo": 200
	} 

## 13.- Recibir Mensajes Fail de Whatsapp
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

### 13.1.- Respuesta de salida

codigo: 130 éxito mensaje: descripcion del mensaje

#### 13.1.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 13.1.2.- Respuesta de éxito

	{
                "status": "ok",
                "codigo": 200
	} 

## 14.- Recibir Status de Whatsapp
Método que recibe mensaje de servidores de Twilio en caso de fallo y alerta status de sistema.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMensajeWspStatus`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                 |     Requerido          |             Descripción     |
|:------------:|:------------:|:-----------------------:|:----------------------:|----------------------------:|
| MessageStatus| string       |                         |                        | Estado del mensaje          |
| SmsStatus    | string       |                         |                        | Mismo que MessageStatus, deprecado|

### 14.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 14.1.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 14.1.2.- Respuesta de éxito

	{
                "status": "ok",
                "codigo": 200
	} 



## 15.- Recibir Mensajes de Telegram Connect
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta)

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramConnect`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|


### 15.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 15.1.1.- Respuesta de error

`401`
  
#### 15.1.2.- Respuesta de éxito

`1`

## 16.- Recibir Mensajes de Telegram Soporte
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporte`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|

### 16.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.1.- Respuesta de error

`401`
  
#### 16.1.2.- Respuesta de éxito

`1`

## 17.- Recibir Mensaje de Telegram Soporte Empresas
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporteEmpresa`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|

### 17.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.1.1.- Respuesta de error

`401`
  
#### 17.1.2.- Respuesta de éxito

`1`

## 18.- Recibir Mensajes de Telegram Soporte Técnico
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramSoporteTecnico`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|

### 18.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.1.1.- Respuesta de error

`401`
  
#### 18.1.2.- Respuesta de éxito

`1`

## 19.- Recibir Mensajes de Telegram Test
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramTest`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|

### 19.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.1.1.- Respuesta de error

`401`
  
#### 19.1.2.- Respuesta de éxito

`1`

## 20.- Recibir Mensajes de Telegram Ventas
Método que recibe mensajes de telegram y reenvia a MS. (solo cambia cuenta).

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeMjeTelegramVentas`

**Parámetros de entrada:**
| Campo              |  Tipo                                          | Formato          | Requerido  | Descripción                 |
|:-------------------|:----------------------------------------------:|:----------------:|:----------:|----------------------------:|
| update_id          | int                                            |                  | Si         | Identificador del update    |
| ↓ message o edited_message| array[object]                           |                  | Si         |                             |
| ⤷ message_id       | int                                            |                  | Si         | Identificador del mensaje   |
| ⤷ from             | [User](https://core.telegram.org/bots/api#user)|                  |            | Remitente del mensaje       |
| ⤷ sender_chat      | [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Remitente del mensaje enviado en nombre de un chat|
| ⤷ date             | int                                            | Unix             | Si         | Fecha del mensaje           |
| ⤷ chat             | [Chat](https://core.telegram.org/bots/api#chat)|                  | Si         | Conversación a la que pertenece el mensaje|
| ⤷ forward_from     | [User](https://core.telegram.org/bots/api#user)|                  |            | Para mensajes reenviados, remitente del mensaje original|
| ⤷ forward_from_chat| [Chat](https://core.telegram.org/bots/api#chat)|                  |            | Para mensajes reenviados desde chats, remitente del mensaje original|
| ⤷ forward_from_message_id| int                                      |                  |            | Para mensajes reenviados desde chats, identificador del mensaje original|
| ⤷ forward_signature| string                                         |                  |            | Para mensajes reenviados desde chats, firma del autor de la publicación|
| ⤷ forward_sender_name| string                                       |                  |            | Nombre del remitente para los mensajes reenviado|
| ⤷ forward_date     | int                                            | Unix             |            | Para mensajes reenviados, fecha del mensaje original|
| ⤷ reply_to_message | [Message](https://core.telegram.org/bots/api#message)|            |            | Para respuestas, el mensaje original|
| ⤷ via_bot          | [User](https://core.telegram.org/bots/api#user)|                  |            | Bot a través del cual se envió el mensaje|
| ⤷ edit_date        | int                                            | Unix             |            | Fecha de la última edición del mensaje |
| ⤷ media_group_id   | string                                         |                  |            | Identificador de un grupo de mensajes multimedia |
| ⤷ author_signature | string                                         |                  |            | Firma del autor de la publicación |
| ⤷ text             | string                                         |                  |            | Texto del mensaje, hasta 4096 caracteres |
| ⤷ entities         | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes de texto, entidades especiales como url, comandos de bot, etc|
| ⤷ animation        | [Animation](https://core.telegram.org/bots/api#animation)|        |            | El mensaje es una animación |
| ⤷ audio            | [Audio](https://core.telegram.org/bots/api#audio)|                |            | El mensaje es un archivo de audio|
| ⤷ document         | [Document](https://core.telegram.org/bots/api#document)|          |            | El mensaje es un archivo    |
| ⤷ photo            | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | El mensaje es un foto       |
| ⤷ sticker          | [Sticker](https://core.telegram.org/bots/api#sticker)|            |            | El mensaje es un sticker    |
| ⤷ video            | [Video](https://core.telegram.org/bots/api#video)|                |            | El mensaje es un video      |
| ⤷ video_note       | [VideoNote](https://core.telegram.org/bots/api#videonote)|        |            | El mensaje es una nota de video|
| ⤷ voice            | [Voice](https://core.telegram.org/bots/api#voice)|                |            | El mensaje es de voz        |
| ⤷ caption          | string                                           |                |            | Pie de foto para animación, audio, documento, etc. Hasta 1024 caracteres|
| ⤷ caption_entities | Array de [MessageEntity](https://core.telegram.org/bots/api#messageentity)||   | Para mensajes con un título, entidades especiales como url, comandos de bot, etc|
| ⤷ contact          | [Contact](https://core.telegram.org/bots/api#contact)|            |            | El mensaje es un contacto compartido|
| ⤷ dice             | [Dice](https://core.telegram.org/bots/api#dice)|                  |            | El mensaje es un dado con valor aleatorio|
| ⤷ game             | [Game](https://core.telegram.org/bots/api#game)|                  |            | El mensaje es un juego      |
| ⤷ poll             | [Poll](https://core.telegram.org/bots/api#poll)|                  |            | El mensaje es una encuesta  |
| ⤷ venue            | [Venue](https://core.telegram.org/bots/api#venue)|                |            | El mensaje es un lugar      |
| ⤷ location         | [Location](https://core.telegram.org/bots/api#location)|          |            | El mensaje es una locación compartida|
| ⤷ new_chat_members | Array de [User](https://core.telegram.org/bots/api#user)|         |            | Nuevos miembros que se agregaron al grupo|
| ⤷ left_chat_member | [User](https://core.telegram.org/bots/api#user)|                  |            | Miembro removidos del grupo |
| ⤷ new_chat_title   | string                                         |                  |            | Nuevo título de chat        |
| ⤷ new_chat_photo   | Array de [PhotoSize](https://core.telegram.org/bots/api#photosize)||           | Nueva foto de chat          |
| ⤷ delete_chat_photo| boolean                                        |                  |            | Mensaje de servicio: se eliminó la foto del chat|
| ⤷ group_chat_created| boolean                                       |                  |            | Mensaje de servicio: se ha creado el grupo|
| ⤷ supergroup_chat_created| boolean                                  |                  |            | Mensaje de servicio: se ha creado el supergrupo|
| ⤷ channel_chat_created| boolean                                     |                  |            | Mensaje de servicio: se ha creado el canal|
| ⤷ message_auto_delete_timer_changed|[MessageAutoDeleteTimerChanged](https://core.telegram.org/bots/api#messageautodeletetimerchanged)|||Mensaje de servicio: la configuración del temporizador de eliminación automática cambió en el chat|
| ⤷ migrate_to_chat_id| int                                           |                  |            | El grupo se ha migrado a un supergrupo con el identificador especificado|
| ⤷ migrate_from_chat_id| int                                         |                  |            | El supergrupo se ha migrado a un grupo con el identificador especificado|
| ⤷ pinned_message   | [Message](https://core.telegram.org/bots/api#message)|            |            | Se fijó el mensaje especificado|
| ⤷ invoice          | [Invoice](https://core.telegram.org/bots/api#invoice)|            |            | El mensaje es una factura para un pago|
| ⤷ successful_payment| [SuccessfulPayment](https://core.telegram.org/bots/api#successfulpayment)||   | El mensaje es un mensaje de servicio sobre un pago exitoso|
| ⤷ connected_website| string                                         |                  |            | El nombre de dominio del sitio web en el que el usuario ha iniciado sesión|
| ⤷ passport_data    | [PassportData](https://core.telegram.org/bots/api#passportdata)|  |            | Datos de Telegram Passport|
| ⤷ proximity_alert_triggered| [ProximityAlertTriggered](https://core.telegram.org/bots/api#proximityalerttriggered)||| Un usuario en el chat activó la alerta de proximidad de otro usuario mientras compartía la ubicación en vivo|
| ⤷ voice_chat_scheduled| [VoiceChatScheduled](https://core.telegram.org/bots/api#voicechatscheduled)||| Mensaje de servicio: chat de voz programado|
| ⤷ voice_chat_started| [VoiceChatStarted](https://core.telegram.org/bots/api#voicechatstarted)||      | Mensaje de servicio: chat de voz iniciado|
| ⤷ voice_chat_ended  | [VoiceChatEnded](https://core.telegram.org/bots/api#voicechatended)||          | Mensaje de servicio: chat de voz finalizado|
| ⤷ voice_chat_participants_invited| [VoiceChatParticipantsInvited](https://core.telegram.org/bots/api#voicechatparticipantsinvited)||| Mensaje de servicio: nuevos participantes invitados a un chat de voz|
| ⤷ reply_markup    | [InlineKeyboardMarkup](https://core.telegram.org/bots/api#inlinekeyboardmarkup)||| Teclado en línea adjunto al mensaje|

### 20.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.1.1.- Respuesta de error

`401` 
  
#### 20.1.2.- Respuesta de éxito

`1`

## 21.- Recibir Mensajes de Twitter
Método que recibe Mensajes de Twitter desde Api de OneMarketer.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/recibeTwitter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        | Requerido     |             Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------:|----------------------------------------:|
| type         | string       |                                |               | Tipo que indica que son nuevos mensajes |
| ↓ messages   | array[object]|                                |               |                                         |
| ⤷ type       | string       |                                |               | Tweet                                   |
| ⤷ id         | string       |                                |               | Identificador del mensaje               |
| ⤷ contentType| string       |                                |               | Indica si el mensaje corresponde a texto, imagen o multimedia |
| ⤷ text       | string       |                                |               | Texto                                   |
| ↓↓ user      | array[object]|                                |               |                                         |
| ⤷ id         | string       |                                |               | Id del usuario                          |
| ⤷ avatar     | string       |                                |               | Url de la imagen de perfil del usuario  |
| ↓↓ mediaUrl  | array[object]|                                |               |                                         |
| ⤷ url        | string       |                                |               | Indica que contiene una imagen o multimedia |

### 21.1.- Ejemplo de llamada

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


### 21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 21.2.2.- Respuesta de éxito

	{
                "status": "success",
                "codigo": 200
	} 



## 22.- Recepción de Mails
Método que permite la recepción de mails sin esperar al cron.

Ruta : GET `/api/recibirMail`

### 22.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 22.1.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 22.1.2.- Respuesta de éxito

	{
                "status": "success",
                "codigo": 200
	} 



## 23.- Guardar Archivo
Método que permite guardar archivos en el servidor.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/storeArchivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| adjunto      | archive      |                                |                             | Archivo adjunto             |
| token        | string       |                                | Si                          | Token                       |

### 23.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "adjunto": "archivo.xls",
                "token": "token_example":
	}

### 23.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.2.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 23.2.2.- Respuesta de éxito

	{
                "status": "success",
                "codigo": 200
	} 


## 24.- Reenviar Mensajes de Twitter
Método que permite reenviar todos los mensajes de twitter que en su momento no fueron entregados. (Debe revisarse BD antes de usar) 

Ruta : POST `/api/twitterfixer`

### 24.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.1.1.- Respuesta de error

	{
                "status": "error",
                "codigo": 401
	} 
  
#### 24.1.2.- Respuesta de éxito

	{
                "status": "success",
                "codigo": 200
	} 