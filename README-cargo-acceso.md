| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para TITULO

<!-- Índice -->
- [Documentación Api´s para TITULO](#documentación-apis-para-TITULO)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
    - [1.- tarifasPorEmpresa](#1--tarifasPorEmpresa)
        - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
        - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
            - [1.2.1- Respuesta de error](#121--respuesta-de-error)
            - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
    - [2.- guardarTarifasPorEmpresa](#2--guardarTarifasPorEmpresa)
        - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
        - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
            - [2.2.1- Respuesta de error](#221--respuesta-de-error)
            - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
    - [3.- obtenerLiquidaciones](#3--obtenerLiquidaciones)
        - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
        - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
            - [3.2.1- Respuesta de error](#321--respuesta-de-error)
            - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
    - [4.- empresasHabilitadas](#4--empresasHabilitadas)
        - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
        - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
            - [4.2.1- Respuesta de error](#421--respuesta-de-error)
            - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
    - [5.- empresasPrincipales](#5--empresasPrincipales)
        - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
        - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
            - [5.2.1- Respuesta de error](#521--respuesta-de-error)
            - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
    - [6.- getListaAnos](#6--getListaAnos)
        - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
        - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
            - [6.2.1- Respuesta de error](#621--respuesta-de-error)
            - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
    - [7.- getListaMes](#7--getListaMes)
        - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
        - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
            - [7.2.1- Respuesta de error](#721--respuesta-de-error)
            - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
    - [8.- cargarLiquidacionesId](#8--cargarLiquidacionesId)
        - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
        - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
            - [8.2.1- Respuesta de error](#821--respuesta-de-error)
            - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
    - [9.- generarPDF](#9--generarPDF)
        - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
        - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
            - [9.2.1- Respuesta de error](#921--respuesta-de-error)
            - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
    - [10.- ObtenerCdr](#10--ObtenerCdr)
        - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
        - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
            - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
            - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)
    - [11.- guardarLiquidacion](#11--guardarLiquidacion)
        - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [11.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [11.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)



# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- tarifasPorEmpresa
Método que permite consultar tarifas de la empresa corresponsal indicada.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/tarifasPorEmpresa`

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

## 2.- guardarTarifasPorEmpresa
Método que permite guardar la tarifa ingresada asociada a la empresa corresponsal en BD.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/guardarTarifasPorEmpresa`

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


## 3.- obtenerLiquidaciones
Método que permite generar lista de liquidaciones generadas por entidad corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/obtenerLiquidaciones`

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


## 4.- empresasHabilitadas
Método que permite obtener lista de empresas corresponsales.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/empresasHabilitadas`

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


## 5.- empresasPrincipales
Método que permite obtener lista de empresa principal Mundo Pacifico Móvil u Hogar como corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/empresasPrincipales`

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


## 6.- getListaAnos
Método que permite obtener lista de años anteriores como un año más a futuro.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/getListaAnos`

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


## 7.- getListaMes
Método que permite obtener lista de meses ya ingresados según las liquidaciones existentes del año seleccionado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/getListaMes`

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



## 8.- cargarLiquidacionesId
Método que permite cargar datos de liquidación existente seleccionado de la grilla, para visualizar lo generado.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/cargarLiquidacionesId`

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

## 9.- generarPDF
Método que permite generar archivo descargable en pdf de liquidación generada.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/generarPDF`

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


## 10.- ObtenerCdr
Método que permite exportar en xls archivo cdr de la liquidación existente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/ObtenerCdr`

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


## 11.- guardarLiquidacion
Método que permite guardar liquidación generada del corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/guardarLiquidacion`

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
        ...
	} 
  
#### 11.2.2.- Respuesta de éxito

	{
        ...
	}