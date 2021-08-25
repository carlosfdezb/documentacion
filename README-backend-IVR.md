| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Backend IVR

<!-- Índice -->
- [Documentación Api´s para TITULO](#documentación-apis-para-backend-ivr)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- RecorridoClienteIVR](#1--RecorridoClienteIVR)
      - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
      - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
          - [1.2.1- Respuesta de error](#121--respuesta-de-error)
          - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
  - [2.- ultimasLlamadas](#2--ultimasLlamadas)
      - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
      - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
          - [2.2.1- Respuesta de error](#221--respuesta-de-error)
          - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- obtenerDataNodosLlamadaTecnica](#3--obtenerDataNodosLlamadaTecnica)
      - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
      - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
          - [3.2.1- Respuesta de error](#321--respuesta-de-error)
          - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- obtenerDataComunasLlamadaTecnica](#4--obtenerDataComunasLlamadaTecnica)
      - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
      - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
          - [4.2.1- Respuesta de error](#421--respuesta-de-error)
          - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
  - [5.- obtenerDataAccionLlamadaTecnica](#5--obtenerDataAccionLlamadaTecnica)
      - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
      - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
          - [5.2.1- Respuesta de error](#521--respuesta-de-error)
          - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- ConsultaIvrHorario](#6--ConsultaIvrHorario)
      - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
      - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
          - [6.2.1- Respuesta de error](#621--respuesta-de-error)
          - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- consultasoftstop](#7--consultasoftstop)
      - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
      - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
          - [7.2.1- Respuesta de error](#721--respuesta-de-error)
          - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
  - [8.- store](#8--store)
      - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
      - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
          - [8.2.1- Respuesta de error](#821--respuesta-de-error)
          - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
  - [9.- index](#9--index)
      - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
      - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
          - [9.2.1- Respuesta de error](#921--respuesta-de-error)
          - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- update](#10--update)
      - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
      - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
          - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
          - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)

# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- RecorridoClienteIVR
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/RecorridoClienteIVR`

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
        ...
	} 
  
#### 1.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.- ultimasLlamadas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/ultimasLlamadas`

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
        ...
	} 
  
#### 2.2.2.- Respuesta de éxito

	{
        ...
	}

## 3.- obtenerDataNodosLlamadaTecnica
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/obtenerDataNodosLlamadaTecnica`

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
        ...
	} 
  
#### 3.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.- obtenerDataComunasLlamadaTecnica
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/obtenerDataComunasLlamadaTecnica`

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

## 5.- obtenerDataAccionLlamadaTecnica
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/obtenerDataAccionLlamadaTecnica`

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
        ...
	} 
  
#### 5.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.- ConsultaIvrHorario
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/ConsultaIvrHorario`

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
        ...
	} 
  
#### 6.2.2.- Respuesta de éxito

	{
        ...
	}

## 7.- consultasoftstop
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/consultasoftstop`

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
        ...
	} 
  
#### 7.2.2.- Respuesta de éxito

	{
        ...
	}

## 8.- store
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/store`

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

## 9.- index
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/index`

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
        ...
	} 
  
#### 9.2.2.- Respuesta de éxito

	{
        ...
	}


## 10.- update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : PUT `/api/update/{id}`

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
        ...
	} 
  
#### 10.2.2.- Respuesta de éxito

	{
        ...
	}