| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Portabilidad

<!-- Índice -->
- [Documentación Api´s para Portabilidad](#documentación-apis-para-portabilidad)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Monitor](#1--monitor)
    - [1.1.- **consultasPortOuts**](#11--consultasPortOuts)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- **monitor**](#12--monitor)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- **monitor/busqueda**](#13--monitor/busqueda)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
    - [1.4.- **portabilidadSalientes**](#14--portabilidadSalientes)
        - [1.4.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
        - [1.4.2.- Respuesta de Salida](#142--respuesta-de-salida)
            - [1.4.2.1- Respuesta de error](#1421--respuesta-de-error)
            - [1.4.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
  - [2.- Portabilidad](#2--portabilidad)
    - [2.1.- bloquearEquipo](#21--bloquearEquipo)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- cancelarPortacion](#22--cancelarPortacion)
        - [2.2.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#222--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#2221--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
    - [2.3.- desbloquearEquipo](#23--desbloquearEquipo)
        - [2.3.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
        - [2.3.2.- Respuesta de Salida](#232--respuesta-de-salida)
            - [2.3.2.1- Respuesta de error](#2321--respuesta-de-error)
            - [2.3.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
    - [2.4.- enviarDocumentacion](#24--enviarDocumentacion)
        - [2.4.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
        - [2.4.2.- Respuesta de Salida](#242--respuesta-de-salida)
            - [2.4.2.1- Respuesta de error](#2421--respuesta-de-error)
            - [2.4.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
    - [2.5.- generarCap](#25--generarCap)
        - [2.5.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
        - [2.5.2.- Respuesta de Salida](#252--respuesta-de-salida)
            - [2.5.2.1- Respuesta de error](#2521--respuesta-de-error)
            - [2.5.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
    - [2.6.- informaFinProcesoInOut](#26--informaFinProcesoInOut)
        - [2.6.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
        - [2.6.2.- Respuesta de Salida](#262--respuesta-de-salida)
            - [2.6.2.1- Respuesta de error](#2621--respuesta-de-error)
            - [2.6.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
    - [2.7.- informePortabilidad](#27--informePortabilidad)
        - [2.7.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
        - [2.7.2.- Respuesta de Salida](#272--respuesta-de-salida)
            - [2.7.2.1- Respuesta de error](#2721--respuesta-de-error)
            - [2.7.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
    - [2.8.- checkHolderBillingAsynDonorRequest](#28--checkHolderBillingAsynDonorRequest)
        - [2.8.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
        - [2.8.2.- Respuesta de Salida](#282--respuesta-de-salida)
            - [2.8.2.1- Respuesta de error](#2821--respuesta-de-error)
            - [2.8.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
    - [2.9.- checkHolderBillingAsynResponse](#29--checkHolderBillingAsynResponse)
        - [2.9.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
        - [2.9.2.- Respuesta de Salida](#292--respuesta-de-salida)
            - [2.9.2.1- Respuesta de error](#2921--respuesta-de-error)
            - [2.9.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
    - [2.10.- checkHolderBillingSynDonorRequest](#210--checkHolderBillingSynDonorRequest)
        - [2.10.1.- Ejemplo de llamada](#2101--ejemplo-de-llamada)
        - [2.10.2.- Respuesta de Salida](#2102--respuesta-de-salida)
            - [2.10.2.1- Respuesta de error](#21021--respuesta-de-error)
            - [2.10.2.2- Respuesta de éxito](#21022--respuesta-de-éxito)
    - [2.11.- genCAPResponse](#211--genCAPResponse)
        - [2.11.1.- Ejemplo de llamada](#2111--ejemplo-de-llamada)
        - [2.11.2.- Respuesta de Salida](#2112--respuesta-de-salida)
            - [2.11.2.1- Respuesta de error](#21121--respuesta-de-error)
            - [2.11.2.2- Respuesta de éxito](#21122--respuesta-de-éxito)
    - [2.12.- portInResponse](#212--portInResponse)
        - [2.12.1.- Ejemplo de llamada](#2121--ejemplo-de-llamada)
        - [2.12.2.- Respuesta de Salida](#2122--respuesta-de-salida)
            - [2.12.2.1- Respuesta de error](#21221--respuesta-de-error)
            - [2.12.2.2- Respuesta de éxito](#21222--respuesta-de-éxito)
    - [2.13.- sendAttachedDocsResponse](#213--sendAttachedDocsResponse)
        - [2.13.1.- Ejemplo de llamada](#2131--ejemplo-de-llamada)
        - [2.13.2.- Respuesta de Salida](#2132--respuesta-de-salida)
            - [2.13.2.1- Respuesta de error](#21321--respuesta-de-error)
            - [2.13.2.2- Respuesta de éxito](#21322--respuesta-de-éxito)
    - [2.14.- solicitarPortacion](#214--solicitarPortacion)
        - [2.14.1.- Ejemplo de llamada](#2141--ejemplo-de-llamada)
        - [2.14.2.- Respuesta de Salida](#2142--respuesta-de-salida)
            - [2.14.2.1- Respuesta de error](#21421--respuesta-de-error)
            - [2.14.2.2- Respuesta de éxito](#21422--respuesta-de-éxito)
    - [2.15.- verificarFactibilidad](#215--verificarFactibilidad)
        - [2.15.1.- Ejemplo de llamada](#2151--ejemplo-de-llamada)
        - [2.15.2.- Respuesta de Salida](#2152--respuesta-de-salida)
            - [2.15.2.1- Respuesta de error](#21521--respuesta-de-error)
            - [2.15.2.2- Respuesta de éxito](#21522--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Monitor
## 1.1.- consultasPortOuts
Método que entrega la totalidad de las consultas de titularidad de nuestros clientes desde otras compañías.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD 
`/consultasPortOuts`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.1.2.2.- Respuesta de éxito

	{
        ...
	}

## 1.2.- monitor
Método que permite acceder al monitor de portabilidades, muestra la lista de portabilidades en curso y exitosas de los últimos 2 días.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD 
`/monitor`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.2.2.2.- Respuesta de éxito

	{
        ...
	}


## 1.3.- monitor/busqueda
Método que permite buscar las consultas que ha hecho un número de teléfono indiferente de los resultados, se puede acotar a un rango de fechas.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD 
`/monitor/busqueda`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 1.4.- portabilidadSalientes
Método que permite acceder al listado de números de teléfono que han completado un proceso de portabilidad saliente desde nuestra compañía.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD 
`/portabilidadSalientes`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.4.2.2.- Respuesta de éxito

	{
        ...
	}

# 2.- Portabilidad
## 2.1.- bloquearEquipo
Método que permite el bloqueo de equipo por imei.

Los parámetros que recibe son los siguientes:

Ruta : POST `/bloquearEquipo`

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


## 2.2.- cancelarPortacion
Método que permite cancelar portabilidad (antes de las 21hrs).

Los parámetros que recibe son los siguientes:

Ruta : POST `/cancelarPortacion`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato       | Requerido    | Descripción                 |
|:----------------------|:------------:|:-------------:|:------------:|----------------------------:|
| descripcionMotivo     | string       |               |              | Breve descripción           |
| ↓ documentos          | array[object]|               |              | Breve descripción           |
| ⤷ tipoDocumento       | string       |               |              | Breve descripción           |
| ⤷ archivoBinario      | string       |               |              | Breve descripción           |
| idSolicitud           | int          |               |              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

        {	
                "descripcionMotivo":"Motivo personal",
                "documentos":[
                        {
                                "tipoDocumento":"021",
                                "archivoBinario":"/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAYGBgYHBgcICAcKCwoLCg8ODAwODxYQERAREBYiFRkV"
                        }
                ],
                "idSolicitud":85761
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

## 2.3.- desbloquearEquipo
Método que permite el desbloqueo de equipo por imei.

Los parámetros que recibe son los siguientes:

Ruta : POST `/desbloquearEquipo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.4.- enviarDocumentacion
Método que permite adjuntar documentación a un proceso de portabilidad posterior a su solicitud.

Los parámetros que recibe son los siguientes:

Ruta : POST `/enviarDocumentacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.4.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.5.- generarCap
Método que permite generar un nuevo CAP para portabilidades prepago.

Los parámetros que recibe son los siguientes:

Ruta : POST `/generarCap`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato       | Requerido    | Descripción                 |
|:----------------------|:------------:|:-------------:|:------------:|----------------------------:|
| numeroTelefono        | int          |               |              | Breve descripción           |
| idSolicitud           | int          |               |              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.5.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "numeroTelefono":56936000014,
                "idSolicitud":87
        }

### 2.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.5.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.6.- informaFinProcesoInOut
Método que permite consultar si una portabilidad ya se realizó correctamente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/informaFinProcesoInOut`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato       | Requerido    | Descripción                 |
|:----------------------|:------------:|:-------------:|:------------:|----------------------------:|
| tipoOperacion         | int          |               |              | Breve descripción           |
| idSolicitud           | int          |               |              | Breve descripción           |
| detalleRespuestas     | string       |               |              | Breve descripción           |
| ↓ numerosTelefonos    | array[object]|               |              | Breve descripción           |
| ⤷ numero              | int          |               |              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.6.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "tipoOperacion": 1,
                "idSolicitud": 2737,
                "detalleRespuestas": "",
                "numerosTelefonos": [
                        {
                        "numero": 56977525479
                        }
                ]
        }

### 2.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.6.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": [
                        {
                                "codigoError": 0,
                                "descripcionError": "Solicitud de portabilidad no encontrada o aun en curso para este numero 56977525479"
                        }
                        ]
                },
                "codigo": 404
        }
  
#### 2.6.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.7.- informePortabilidad
Método que permite descargar excel con listado de portabilidades en curso y exitosas de los últimos 2 días.

Los parámetros que recibe son los siguientes:

Ruta : POST `/informePortabilidad`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.7.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.8.- checkHolderBillingAsynDonorRequest
Método que permite recibir la petición de titularidad de otras compañías.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/checkHolderBillingAsynDonorRequest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.8.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.8.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.9.- checkHolderBillingAsynResponse
Método que permite recibir la respuesta de titularidad que realizamos asíncronamente.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/checkHolderBillingAsynResponse`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.9.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.9.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.10.- checkHolderBillingSynDonorRequest
Método que permite?

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/checkHolderBillingSynDonorRequest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.10.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.11.- genCAPResponset
Método que permite recibir el resultado de una generación de CAP.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/genCAPResponset`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.11.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.11.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.12.- portInResponse
Método que permite recibir el resultado de una petición de portabilidad.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/portInResponse`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.12.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.12.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.13.- sendAttachedDocsResponse
Método que permite recibir el resultado de una subida de documentos.

Los parámetros que recibe son los siguientes:

Ruta : GET | HEAD | POST | PUT | PATCH | DELETE | OPTIONS 
`/mp/service/sendAttachedDocsResponse`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.13.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.13.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.14.- solicitarPortacion
Método que permite solicitar una portabilidad.

Los parámetros que recibe son los siguientes:

Ruta : POST `/solicitarPortacion`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato       | Requerido    | Descripción                 |
|:----------------------|:------------:|:-------------:|:------------:|----------------------------:|
| ↓ numerosTelefonico   | array[object]|               |              | Breve descripción           |
| ⤷ numeroTelefono      | string       |               |              | Breve descripción           |
| ⤷ indCuentaAlDia      | int          |               |              | Breve descripción           |
| ⤷ montoDeudaAceptada  | int          |               |              | Breve descripción           |
| ⤷ CAP                 | string       |               |              | Breve descripción           |
| ⤷ iccid               | string       |               |              | Breve descripción           |
| ⤷ idPlan              | int          |               |              | Breve descripción           |
| ↓ documentos          | array[object]|               |              | Breve descripción           |
| ⤷ numeroTelefonoDoc   | sring        |               |              | Breve descripción           |
| ⤷ tipoDocumento       | sring        |               |              | Breve descripción           |
| ⤷ documentoBinario    | sring        |               |              | Breve descripción           |
| idSolicitud           | int          |               |              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.14.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "numerosTelefonico":[
                        {
                        "numeroTelefono":"56936000014",
                        "indCuentaAlDia":0,
                        "montoDeudaAceptada":0,
                        "CAP":"348250361886", 
                        "iccid":"8956072200000085070F",
                        "idPlan":502
                        }
	        ],
	        "documentos":[
                        {
                        "numeroTelefonoDoc":"0",
                        "tipoDocumento":"001",
                        "documentoBinario":"JVBERi0xLjQKJdPr6eEKMSAwIG9iago8PC9DcmVhdG9yIChDaHJvbWl1bSkKL1Byb2R1Y2VyIChTa2lhL1BERiBtNjYpCi9"
                        },
                        {
                        "numeroTelefonoDoc":"0",
                        "tipoDocumento":"006",
                        "documentoBinario":"JVBERi0xLjQKJdPr6eEKMSAwIG9iago8PC9DcmVhdG9yIChDaHJvbWl1bSkKL1Byb2R1Y2VyIChTa2lhL1BERiBtNjYpCi9"
                        },
                        {
                        "numeroTelefonoDoc":"0",
                        "tipoDocumento":"020",
                        "documentoBinario":"JVBERi0xLjQKJdPr6eEKMSAwIG9iago8PC9DcmVhdG9yIChDaHJvbWl1bSkKL1Byb2R1Y2VyIChTa2lhL1BERiBtNjYpCi9"
                        }
		
	        ],
	        "idSolicitud":87
        }

### 2.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.14.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.14.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.15.- verificarFactibilidad
Método que permite verificar la factibilidad.

Los parámetros que recibe son los siguientes:

Ruta : POST `/verificarFactibilidad`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato       | Requerido    | Descripción                 |
|:----------------------|:------------:|:-------------:|:------------:|----------------------------:|
| ↓ data                | array[object]|               |              | Breve descripción           |
| ⤷ ventaWeb            | int          |               |              | Breve descripción           |
| ⤷ rutSolicitante      | string       |               |              | Breve descripción           |
| ⤷ rutTitular          | string       |               |              | Breve descripción           |
| ⤷ nombreTitular       | string       |               |              | Breve descripción           |
| ⤷ apellidoTitular     | string       |               |              | Breve descripción           |
| ⤷ direccionTitular    | string       |               |              | Breve descripción           |
| ⤷ idModalidad         | int          |               |              | Breve descripción           |
| ⤷ tipoServicioOrigen  | int          |               |              | Breve descripción           |
| ⤷ tipoServicioDestino | int          |               |              | Breve descripción           |
| ⤷ metodoContacto      | int          |               |              | Breve descripción           |
| ⤷ region              | int          |               |              | Breve descripción           |
| ⤷ comuna              | int          |               |              | Breve descripción           |
| ⤷ localidad           | int          |               |              | Breve descripción           |
| ⤷ tipoSuscriptor      | int          |               |              | Breve descripción           |
| ↓↓ numeroTelefonos    | array[object]|               |              | Breve descripción           |
| ⤷ numeroTelefono      | int          |               |              | Breve descripción           |
| ⤷ IMEI                | string       |               |              | Breve descripción           |
| plataforma            | int          |               |              | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idSolicitud    | int          | Breve descripción                                |

### 2.15.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "data": {
                        "ventaWeb": 1,
                        "rutSolicitante": "15178204-3",
                        "rutTitular": "15178204-3",
                        "nombreTitular": "cristian",
                        "apellidoTitular": "fuentes",
                        "direccionTitular": "PASAJE TALCA 543",
                        "idModalidad":1,
                        "tipoServicioOrigen":0,
                        "tipoServicioDestino":0,
                        "metodoContacto":1,
                        "region": 8,
                        "comuna": 8102,
                        "localidad": 810201,
                        "tipoSuscriptor":1,
                        "numeroTelefonos":[
                                {
                                "numeroTelefono":56969078366,
                                "IMEI":"869325035121053"
                                }

                        ]
                },
                "plataforma": 5
        }

### 2.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.15.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": [
                        {
                                "codigoError": 500,
                                "descripcionError": "Rut Solicitante es obligatorio."
                        }
                        ]
                },
                "codigo": 422
        }
  
#### 2.15.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": "Recibido correctamente",
                        "idSolicitud": 148523
                },
                "codigo": 200
        }