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
    - [1.4.- **portabilidadSalientes**](#13--portabilidadSalientes)
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
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
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
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.6.2.1.- Respuesta de error

	{
        ...
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
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
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
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.15.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.15.2.2.- Respuesta de éxito

	{
        ...
	}