---
title: "Apis Mutualidad para uso de Beyond UP"
author: "Alvaro Muñoz B."
date: "23/09/2020"
---
# Documentación Api´s para Beyond Up Mutualidad

- [Documentación Api´s para Beyond Up Mutualidad](#documentación-apis-para-beyond-up-mutualidad)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Factibilidad](#1--factibilidad)
    - [1.1.- Factibilidad por Homepass](#11--factibilidad-por-homepass)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error Homepass no disponible](#1121--respuesta-de-error-homepass-no-disponible)
            - [1.1.2.2- Respuesta de error código Homepass erróneo](#1122--respuesta-de-error-código-homepass-erróneo)
            - [1.1.2.3- Respuesta de éxito](#1123--respuesta-de-éxito)
    - [1.2.- Factibilidad por dirección](#12--factibilidad-por-dirección)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- Factibilidad por dirección con servicios](#13--factibilidad-por-dirección-con-servicios)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
  - [2.- Naps](#2--naps)
    - [2.1.- Asignar ubicación exacta del dispositivo](#21--asignar-ubicación-exacta-del-dispositivo)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Obtener bocas disponibles](#22--obtener-bocas-disponibles)
        - [2.2.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#222--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#2221--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
    - [2.3.- Niveles](#23--niveles)
        - [2.3.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
        - [2.3.2.- Respuesta de Salida](#232--respuesta-de-salida)
            - [2.3.2.1- Respuesta de error](#2321--respuesta-de-error)
            - [2.3.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
  - [3.- Nivel de señal](#3--nivel-de-señal)
    - [3.1.- Niveles](#31--niveles)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
  - [4.- Provisión](#4--provisión)
    - [4.1.- Alta](#41--alta)
        - [4.1.1.- Ejemplo de llamada](#411--ejemplo-de-llamada)
        - [4.1.2.- Respuesta de Salida](#412--respuesta-de-salida)
            - [4.1.2.1- Respuesta de error](#4121--respuesta-de-error)
            - [4.1.2.2- Respuesta de éxito](#4122--respuesta-de-éxito)
    - [4.2.- Baja](#42--baja)
        - [4.2.1.- Ejemplo de llamada](#421--ejemplo-de-llamada)
        - [4.2.2.- Respuesta de Salida](#422--respuesta-de-salida)
            - [4.2.2.1- Respuesta de error](#4221--respuesta-de-error)
            - [4.2.2.2- Respuesta de éxito](#4222--respuesta-de-éxito)
    - [4.3.- Desconexión](#43--desconexión)
        - [4.3.1.- Ejemplo de llamada](#431--ejemplo-de-llamada)
        - [4.3.2.- Respuesta de Salida](#432--respuesta-de-salida)
            - [4.3.2.1- Respuesta de error](#4321--respuesta-de-error)
            - [4.3.2.2- Respuesta de éxito](#4322--respuesta-de-éxito)
  - [5.- Reservas](#5--reservas)
    - [5.1.- Creación de Reserva](#51--creación-de-reserva)
        - [5.1.1.- Ejemplo de llamada](#511--ejemplo-de-llamada)
        - [5.1.2.- Respuesta de Salida](#512--respuesta-de-salida)
            - [5.1.2.1- Respuesta de error Homepass no disponible](#5121--respuesta-de-error-homepass-no-disponible)
            - [5.1.2.2- Respuesta de error código Homepass erróneo](#5122--respuesta-de-error-código-homepass-erróneo-1)
            - [5.1.2.3- Respuesta de error código de Operador](#5123--respuesta-de-error-código-de-operador)
            - [5.1.2.4- Respuesta de éxito](#5124--respuesta-de-éxito)
    - [5.2.- Anular Reserva](#52--anular-reserva)
        - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
        - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
            - [5.2.2.1- Respuesta de error al anular Reserva de Homepass](#5221--respuesta-de-error-al-anular-reserva-de-homepass)
            - [5.2.2.2- Respuesta de éxito](#5222--respuesta-de-éxito-1)
    - [5.3.- Obtener Reservas](#53--obtener-reservas)
        - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
        - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
            - [5.3.2.1.- Respuesta de error](#5321--respuesta-de-error)
            - [5.3.2.2.- Respuesta de éxito](#5322--respuesta-de-éxito)
  - [6.- Servicialidad](#6--servicialidad)
    - [6.1.- Servicialidad por Nodo](#61--servicialidad-por-nodo)
        - [6.1.1.- Ejemplo de llamada](#611--ejemplo-de-llamada)
        - [6.1.2.- Respuesta de Salida](#612--respuesta-de-salida)
            - [6.1.2.1.- Respuesta de error](#6121--respuesta-de-error)
            - [6.1.2.2.- Respuesta de éxito](#6122--respuesta-de-éxito)
    - [6.2.- Servicialidad por Mufa](#62--servicialidad-por-mufa)
        - [6.2.1.- Ejemplo de llamada](#621--ejemplo-de-llamada)
        - [6.2.2.- Respuesta de Salida](#622--respuesta-de-salida)
            - [6.2.2.1.- Respuesta de error](#6221--respuesta-de-error)
            - [6.2.2.2.- Respuesta de éxito](#6222--respuesta-de-éxito)
    - [6.3.- Servicialidad por Planta](#63--servicialidad-por-planta)
        - [6.3.1.- Ejemplo de llamada](#631--ejemplo-de-llamada)
        - [6.3.2.- Respuesta de Salida](#632--respuesta-de-salida)
            - [6.3.2.1.- Respuesta de error](#6321--respuesta-de-error)
            - [6.3.2.2.- Respuesta de éxito](#6322--respuesta-de-éxito)
    - [6.4.- Servicialidad por Planta paginada](#64--servicialidad-por-planta-paginada)
        - [6.4.1.- Ejemplo de llamada](#641--ejemplo-de-llamada)
        - [6.4.2.- Respuesta de Salida](#642--respuesta-de-salida)
            - [6.4.2.1.- Respuesta de error](#6421--respuesta-de-error)
            - [6.4.2.2.- Respuesta de éxito](#6422--respuesta-de-éxito)
  - [7.- Servicios externos](#7--servicios-externos)
    - [7.1.- Obtener todos los HUBS](#71--obtener-todos-los-hubs)
        - [7.1.1.- Ejemplo de llamada](#711--ejemplo-de-llamada)
        - [7.1.2.- Respuesta de Salida](#712--respuesta-de-salida)
            - [7.1.2.1- Respuesta de error](#7121--respuesta-de-error)
            - [7.1.2.2- Respuesta de éxito](#7122--respuesta-de-éxito)
    - [7.2.- Obtener Nodos por HUB](#71--obtener-nodos-por-hub)
        - [7.2.1.- Ejemplo de llamada](#711--ejemplo-de-llamada)
        - [7.2.2.- Respuesta de Salida](#712--respuesta-de-salida)
            - [7.2.2.1- Respuesta de error](#7121--respuesta-de-error)
            - [7.2.2.2- Respuesta de éxito](#7122--respuesta-de-éxito)
    - [7.3.- Obtener Token ArcGis](#73--obtener-token-arcgis)
        - [7.3.1.- Ejemplo de llamada](#731--ejemplo-de-llamada)
        - [7.3.2.- Respuesta de Salida](#732--respuesta-de-salida)
            - [7.3.2.1- Respuesta de error](#7321--respuesta-de-error)
            - [7.3.2.2- Respuesta de éxito](#7322--respuesta-de-éxito)
  - [8.- Datos de Ubicaciones Geográficas de Chile](#8--datos-de-ubicaciones-geográficas-de-chile)
    - [8.1.- Listado de Regiones](#81--listado-de-regiones)
    - [8.2.- Listado de Provincias](#82--listado-de-provincias)
    - [8.3.- Listado de Comunas](#83--listado-de-comunas)

# Objetivo

Disponer Apis para que beyond Up realice gestión sobre los Homepass de Mundo Pacífico.

# Restricciones
A partir de la habilitación de estas Apis, beyond UP debe deja de hacer gestión sobre Homepass y de asignación de Bocas de Naps.

# 1.- Factibilidad
## 1.1.- Factibilidad por Homepass
Este método permite consultar la factibilidad de un homepass.

Los parámetros que recibe son los siguientes:

Ruta : GET `/factibilidad/consultahp`

**Parámetros de entrada:**
| Campo           |  Tipo  | Formato | Requerido |   Descripción      |
|:---------------:|:------:|:-------:|:---------:|-------------------:|
| codigoHomepass  | int    |         |    Si     | Código del Homepass|

**Datos de salida:**
|  Campo          |  Tipo  | Descripción                      |
|:----------------|:------:|----------------------------------:|
| idHomepass      |  int   | Código interno del Homepass       |                 
| codigoHomepass  |  int   | Código del Homepass               |                   
| tecnologia      | string | Indica la tecnología              |
| codigonap       |  int   | Código del Nap                    |                     
| nap             | string | Descripción del Nap               |
| comuna          | string | Nombre de la comuna               |
| codigoPostal    |  int   | Código Postal                     |
| via             |  string| Tipo de Calle                     |
| calle           | string | Nombre de la calle                |
| numero          | string | Numeración de la calle            |
| departamento    | string | Departamento                      |
| acceso          | string |                                   |                    
| estado          | string |                                   |                    
| cliente         | string | Si está ocupado indicar el codigo de cliente|
| bocaNap         | string | Si está ocupado indicar la boca   |
| bocaDisponible  | string | Si no está ocupado indicar si hay boca disponible (SI o NO) | 
| Nodo            | string |  Nodo al que está asignado el Homepass |


### 1.1.1- Ejemplo de llamada

Ejemplo: JSON 

	{
		"codigoHomepass": "98024346"	 
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.1.2.1.- Respuesta de error Homepass no disponible

	{
		"error": {
			"codigoRespuesta": 0,
			"descripcionRespuesta": "Error",
			"detalleRespuesta": "Homepass no se encuentra disponible"
		},
		"codigo": 409
	} 


#### 1.1.2.2.- Respuesta de error código Homepass erróneo

	{
        “error”: {
            “codigoRespuesta”: 0,
            “descripcionRespuesta”: “Error”,
            “detalleRespuesta”: "Código Homepass no existente"
        },
        “codigo”: 404
	}
  
#### 1.1.2.3.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                    "idHomepass": 458530,
                    "codigoHomepass": 26001745,
                    "tecnologia": "ftth",
                    "codigonap": 9879,
                    "nap": "01",
                    "comuna": "chillan",
                    "codigoPostal": 1458744,
                    "via": "Pasaje",
                    "calle": "EL MEDIO",
                    "numero": "235",
                    "departamento": null,
                    "acceso": "G",
                    "estado": "Ocupado",
                    "cliente": "CC1451474",
                    "bocaNap": "01",
                    "bocadisponible": "SI",
                    "nodo": "CHIL_01"
                    }
                ]
            }
        },
        "codigo": 200
    }


	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                    "idHomepass":458530,
                    "codigoHomepass":26001745,
                    "tecnologia":"ftth",
                    "codigonap":98794,
                    "nap":"01",
                    "comuna":"chillan",
                    "codigoPostal":1458744,
                        "via": "Pasaje",
                    "calle":"EL MEDIO",
                    "numero":"235",
                    "departamento":null,
                    "acceso":"G",
                    "estado":"Disponible",
                    "cliente":"",
                    "bocaNap":"",
                    "bocadisponible":"NO",
                    "nodo": "CHIL_01"
                    }
                ]
            }
        },
        "codigo": 200
	}

## 1.2.- Factibilidad por dirección
Este método permite consultar la factibilidad de una dirección.

Los parámetros que recibe son los siguientes:

Ruta : GET `/factibilidad/consultaFactibilidad`

**Parámetros de entrada:**
| Campo  |  Tipo  | Formato |     Requerido      |             Descripción     |
|:------ |:------:|:-------:|:------------------:|----------------------------:|
| calle  | string |         |         Si         |   Nombre de la calle        |
| numero | string |   no    |         No         |   Número de la calle        |
|comuna  |  int   |         |         Si         |   Código de comuna según Subtel|
|forcenap|  int   |         |         Si         |   Al indicar 1, solo se valide que exista boca disponible|

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| idHomepass     |  int   |                 Código interno del Homepass      |
| codigoHomepass |  int   |                 Código del Homepass              | 
| tecnologia     | string |                 Indica la tecnología             |
| codigonap      |  int   |                       Código del Nap             |         
| nap            | string |                     Descripción del Nap          |               
| comuna         | string |                     Nombre de la comuna          |              
| codigoPostal   |  int   |                        Código Postal             |      
| via            |  string|                        Tipo de Calle             |                
| calle          | string |                     Nombre de la calle           |               
| numero         | string |                   Numeración de la calle         |              
| departamento   | string |                       Departamento               |           
| acceso         | string |                                                  |           
| estado         | string |                                                  |                  
| cliente        | string |      Si está ocupado indicar el codigo de cliente|         
| bocaNap        | string |              Si está ocupado indicar la boca     |        
| bocaDisponible | string | Si no está ocupado indicar si hay boca disponible (SI o NO) |
| Nodo           | string |            Nodo al que esta asignado el Homepass |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "calle":"MINERO VICTOR FUENTEALBA",
        "numero":"981",
        "comuna":"8102",
        "forcenap":"" 
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 1.2.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                    "idHomepass": 458530,
                    "codigoHomepass": 26001745,
                    "tecnologia": "ftth",
                    "codigonap": 9879,
                    "nap": "01",
                    "codComuna": 8102,
                    "comuna": "chillan",
                    "codigoPostal": 1458744,
                    "via": "Pasaje",
                    "calle": "MINERO LUIS ALFREDO AMAYA",
                    "numero": "235",
                    "departamento": null,
                    "acceso": "G",
                    "estado": "Ocupado",
                    "cliente": "CC1451474",
                    "bocaNap": "01",
                    "bocadisponible": "SI",
                    "nodo": "CHIL_01"
                    },
                    {
                    "idHomepass": 458531,
                    "codigoHomepass": 26001715,
                    "tecnologia": "ftth",
                    "codigonap": 9879,
                    "nap": "01",
                    "codComuna": 8102,
                    "comuna": "chillan",
                    "codigoPostal": 1458744,
                    "via": "Pasaje",
                    "calle": "MINERO LUIS ALFREDO AMAYA",
                    "numero": "235",
                    "departamento": null,
                    "acceso": "G",
                    "estado": "Disponible",
                    "cliente": "CC1451474",
                    "bocaNap": "01",
                    "bocadisponible": "SI",
                    "nodo": "CHIL_01"               
                    }
                ]
            }
        },
        "codigo": 200
	}

## 1.3.- Factibilidad por dirección con servicios
Este método permite consultar la factibilidad de una dirección, también indica los servicios disponibles.

Los parámetros que recibe son los siguientes:

Ruta : GET `/factibilidad/factibilidadMundo`

**Parámetros de entrada:**
| Campo  |  Tipo  | Formato |     Requerido      |             Descripción     |
|:------ |:------:|:-------:|:------------------:|----------------------------:|
| calle  | string |         |         Si         |          Nombre de la calle |
| numero |  int   |   no    |         No         |        Número de la calle   |
| comuna |  int   |         |         Si         |Código de comuna según Subtel|
|forcenap|  int   |         |         Si         |Al indicar 1, solo se valide que exista boca disponible|

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
|   idHomepass   |  int   | Código interno del Homepass                      |                 
| codigoHomepass |  int   | Código del Homepass                              |
|   nap          | string | Descripción del Nap                              |
|   comuna       | string | Nombre de la comuna                              |
|   calle        | string | Nombre de la calle                               |               
| numero         | string | Numeración de la calle                           |              
| departamento   | string | Departamento                                     |
|   edificio     | string | Edificio                                         |
|   acceso       | string |                                                  |
|   habilitado   | string |                                                  |
|   servicios    | string | Servicios disponibles                            |
|   tecnologia   | string | Tecnología disponible                            |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "calle":"Las rosas",
        "numero":388,
        "comuna":6115,
        "forcenap":"" 
	}

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se han encontrados datos"
        },
        "codigo": 404
	} 
  
#### 1.3.2.2.- Respuesta de éxito

	{
          "success": {
                "codigoRespuesta": 1,
                "descripcionRespuesta": {
                    "data": [
                        {
                            "idHomepass": 1157345,
                            "codigoHomepass": 53014160,
                            "nap": "15",
                            "comuna": 6115,
                            "calle": "LAS ROSAS",
                            "numero": "388",
                            "departamento": null,
                            "edificio": null,
                            "acceso": "N/A",
                            "habilitado": 0,
                            "servicios": [
                                {
                                    "idServicio": 5,
                                    "servicio": "Digital"
                                },
                                {
                                    "idServicio": 3,
                                    "servicio": "Telefonía"
                                },
                                {
                                    "idServicio": 2,
                                    "servicio": "Internet"
                                },
                                {
                                    "idServicio": 1,
                                    "servicio": "Televisión"
                                }
                            ],
                            "tecnologia": [
                                {
                                    "idTecnologia": 4,
                                    "tecnologia": "FTTH"
                                }
                            ]
                        }
                    ]
                }
            },
        "codigo": 200
	}
# 2.- Naps
## 2.1.- Asignar ubicación exacta del dispositivo
Este método permite asignar la ubicación exacta del elemento o dispositivo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/nap/georeferencia`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idNap          | int    |          |    Si     |Identificador único del nap |       
| latitud        | int    |          |    Si     |      Latitud               | 
| longitud       | int    |          |    Si     |     Longitud               | 
| altitud        | int    |          |    Si     |     Altitud                | 
| presicion      | int    |          |    Si     |     Presición              |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idNap": 1,
        "latitud": -36.8931574,
        "longitud": -73.1421935,
        "altitud": 50,
        "presicion": 1
	}
### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

	{
         "error": {
                "codigoRespuesta": 0,
                "descripcionRespuesta": "Error",
                "detalleRespuesta": "No existe el nap con el id :88444445555551"
            },
        "codigo": 404
	} 
  
#### 2.1.2.2.- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": "Nap actualizado correctamente"
            }
        },
        "codigo": 200
	}

## 2.2.- Obtener bocas disponibles
Este método entrega las bocas disponibles para la conexión de un homepass.

Los parámetros que recibe son los siguientes:

Ruta : GET `/bocaNap/bocaDisponible`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| codigoHomepass | int    |          |    Si     |  Código del Homepass       |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| IdHomepass     | int    |   Identificador del homepass                     | 
| codigoHomepass | int    |   Código del homepass                            | 
| codigoNap      | int    |   Código de la nap                               | 
| nap            | string |   Descripción del Nap                            | 
| bocaNap        | string |   Si está ocupado indica la boca                 | 
| nodo           | string |   Nodo al que está asignado el Homepass          | 

### 2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoHomepass": 152002770
	}
### 2.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Homepass no encontrado"
        },
        "codigo": 404
	} 
  
#### 2.2.2.2.- Respuesta de éxito

	{
         "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": {
                    "IdHomepass": 2267454,
                    "codigoHomepass": "152002770",
                    "codigoNap": 1520183,
                    "nap": "10",
                    "bocaNap": "01",
                    "nodo": "PELL_10"
                }
            }
        },
        "codigo": 200
	}

## 2.3.- Niveles
Este metodo permite setear los niveles de intensidad de cada boca del nap.

Los parámetros que recibe son los siguientes:

Ruta : POST `/bocaNap/niveles`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idBocaNap      | int    |          |    Si     | Identificador de la boca del nap|
| nivel          | int    |          |    Si     | Intensidad de señal de la boca|

### 2.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idBocaNap": ,
        "nivel":
	}
### 2.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.3.2.1.- Respuesta de error

	{
         "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No existe boca de nap con el id :1584848484848"
        },
        "codigo": 404
	} 
  
#### 2.3.2.2.- Respuesta de éxito

	{
         "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": "Boca de nap  actualizada correctamente"
            }
        },
        "codigo": 200
	}
# 3.- Nivel de señal
## 3.1.- Nivel de señal de ONT
Este método permite obtener los niveles de señal de ONT.

Los parámetros que recibe son los siguientes:

Ruta : GET `/support/getOntSignal`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idReserva      | int    |          |    Si     | Identificador de la reserva |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| ?              |  ?     |                 ?                                | 

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idReserva": 57
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 3.1.2.2- Respuesta de éxito

	{
         "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": {
                    "señalOnt": {}
                }
            }
        },
        "codigo": 200
	}
# 4.- Provisión
## 4.1.- Alta
Método que permite dar alta de servicio a un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/support/alta`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idReserva      | int    |          |    Si     | Identificador de la reserva|
| externalId     | string |          |    Si     | Identificador del Cliente del Operador|
| internet       | string |          |    Si     | Plan de internet|
| telefono       | int    |          |    Si     | Plan de teléfono|
| user           | string |          |           |       ?                    |
| pass           | string |          |           |       ?                    |
| serieOnt       | string |          |    Si     |       ?                    |
| tv             | string |          |    Si     |       ?                    |
| telefono       | int    |          |    Si     |       ?                    |
| user           | string |          |           |       ?                    |
| pass           | string |          |           |       ?                    |

### 4.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idReserva":60,
        "externalID":"CC46000049",
        "idPackage" :
        {
            "internet":"500"
            "telefono":0,
            "user":"",
            "pass":""
        },
        "serieOnt":"464854549225A878",
        "tv":"no",
        "telefono":0,
        "user":"",
        "pass":""
    }
    
### 4.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.1.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 4.1.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": "Alta realizada correctamente"
            }
        },
        "codigo": 200
	}

## 4.2.- Baja
Método para dar de baja de servicio a un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/support/baja`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idReserva      | int    |          |    Si     | Identificador de la reserva   |

### 4.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idReserva":56,
    }
    
### 4.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.2.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 4.2.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": "Baja realizada correctamente"
            }
        },
        "codigo": 200
	}

## 4.3.- Desconexión
Método para quitar servicios a un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/support/desconectar`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| idReserva      | int    |          |    Si     | Identificador de la reserva|
| operador       | string |          |    Si     |Código del operador         |
### 4.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idReserva":56,
        "operador":"000"  
    }
    
### 4.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.3.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 4.3.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": "Desconexion realizada correctamente"
            }
        },
        "codigo": 200
	}
# 5.- Reservas
## 5.1.- Creación de Reserva
Este método permite crear una reserva de Homepass y entrega la boca del NAP asignada al HP.

Los parámetros que recibe son los siguientes:

Ruta : POST `/reserva`

**Parámetros de entrada**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| operador       | String |          |    Si     |        Código del operador |       
| externalId     | String |          |    Si     | Identificador del Cliente del Operador |
| codigoHomepass |  int   | NNNNNNNN |    Si     |  Código del Homepass        |
| descripcion    |  string|          |    no     | Descripción de la reserva   |    

### 5.1.1.- Ejemplo de llamada

Ejemplo: JSON

	{
		"operador":"123", 	 
		"externalId":"CC12548745200",
		"codigoHomepass":"12548745",
		"descripcion":"Reserva Casa Hualpen" 
	}
	
### 5.1.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.1.2.1.- Respuesta de error Homepass no disponible

	{
    "error": {
        "codigoRespuesta": 0,
        "descripcionRespuesta": "Error",
        "detalleRespuesta": "Homepass no se encuentra disponible"
    },
    "codigo": 409
	} 


#### 5.1.2.2.- Respuesta de error código Homepass erróneo

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "Código Homepass no existente"
    },
    “codigo”: 404
	}

#### 5.1.2.3.- Respuesta de error código de operador

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "Código de Operardor no existente"
    },
    “codigo”: 404
	}

  
#### 5.1.2.4.- Respuesta de éxito

	{
    "success": {
        "codigoRespuesta": 1,
        "descripcionRespuesta": {
            "data": {
                "Reserva creada con éxito": {
                    "idReserva": 28,
                    "descripcion": "Reserva Casa Hualpen",
                    "externalId":"CC12548745200" 
                    "estado": "ingresada",
                    "fechaReserva": "21/09/2020",
                    "fechaCaducidad": "23/09/2020",              
                    "idHomepass": 458530,
                    "codigoHomepass": 12548745,
                    "codigonap": 98794,
                    "nap": "01",
                    "bocaNap": "02"   
                    "nodo": "REMC_02" 
                }
            }
        }
    },
    "codigo": 201
	}

## 5.2.- Anular Reserva
Este método permite Anular la reserva de un Homepass.
Debe dejar habilitado el Homepass y la boca reservada con anterioridad

Los parámetros que recibe son los siguientes:

Ruta : PATCH `/reserva/anular`

**Parámetros de entrada**
| Campo          |  Tipo  | Formato  | Requerido |  Descripción          |
|:---------------|:------:|:--------:|:---------:|----------------------:|
| id_reserva     | int    | NNNNNNN  |    Si     | Identificador de la Reserva |
| motivo         | String |          |    Si     | Motivo de la Anulacion |

### 5.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "id_reserva":21,
        "motivo":"Cliente no acepta plan",
        "operador":"000"
	}
	
### 5.2.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 5.2.2.1.- Respuesta de error al anular Reserva de Homepass

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "No ha sido posible anular la reservar del Homepass debido a un error"
    },
    “codigo”: 500
	}
  
#### 5.2.2.2.- Respuesta de éxito
	{
    "success": {
        "codigoRespuesta": 1,
        "descripcionRespuesta": {
            "data":  {
                "id_reserva":21,
                "idHomepass":418535,
                "codigoHomepass":77020466,
                "codigonap":98799,
                "nap":"02",
                "bocaNap":"01",
	            "nodo": "CHIL_01"
            }
        }
    },
    "codigo": 200
	}

## 5.3.- Obtener Reservas
Este método permite Buscar las reservas de un operador.

Los parámetros que recibe son los siguientes:

Ruta : GET  `/reserva`

**Parámetros de entrada:**
| Campo         |  Tipo  | Formato | Requerido |         Descripción         |
|:------------- |:------:|:-------:|:---------:|----------------------------:|
| fecha_desde   |  date  | yyyy-mm-dd |    Si  | Fecha de Inicio de búsqueda |
| fecha_hasta     | date |    yyyy-mm-dd      |    Si     |   Fecha de termino de búsqueda   |
| codigo_operador |   int     |         |    Si       | Código del operador  | 
| per_page   |  int      |         |    Si       |    numero de paginas      |

**Datos de salida:**
| Campo         |  Tipo  |         Descripción         |
|:------------- |:------:|:---------------------------:|
| current_page   |  int  | Página actual               |
| idReserva      | int   | Identificador de la reserva |
| descripcion    |string | Nombre de la reserva | 
| fechaReserva   |string | Fecha de la reserva         | 
| fechaCaducidad |string | Fecha de vencimiento de la reserva | 
| externalId     |string | Identificador del cliente   | 
| codigoHomepass |string | Código único del homepass   | 
| calle          |string | Nombre de la calle          | 
| numero         |string | Numeración de la calle      | 
| estado         |string | Estado de la reserva        | 

### 5.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
     "fecha_desde":"2020-07-21",
     "fecha_hasta":"2020/07/21"
     "codigo_operador":"210" 
     "per_page" : "2"
	}

### 5.3.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.3.2.1.- Respuesta de Error

	{
    "error": {
        "codigoRespuesta": 0,
        "descripcionRespuesta": "Error",
        "detalleRespuesta": "No hay datos relacionados "
    },
    "codigo": 404
	} 
  
#### 5.3.2.2.- Respuesta de Exito

	{
    "current_page": 1,
    "data": [
		     {
          "idReserva" : 20,
          "descripcion" => "casa Talcahuano",
          "fechaReserva" => "2020/09/21",
          "fechaCaducidad" => "2020/09/23",
          "externalId" => "CC2541121",
          "codigoHomepass" => "42546885"                       
          "calle"=> "Las Acacias",
          "numero" => "3012",
          "estado" => "Ingresada"       
       
        },
        
         {
          "idReserva" : 22,
          "descripcion" => "casa Talcahuano SUR",
          "fechaReserva" => "2020/09/23",
          "fechaCaducidad" => "2020/09/24",
          "externalId" => "CC2541121",
          "codigoHomepass" => "425776885"                       
          "calle"=> "Las Acacias",
          "numero" => "200",
          "estado" => "Anulada"       
       
        },
        
    ],
    "first_page_url": "http://mutualidad/public/reserva?page=1",
    "from": 1,
    "last_page": 1,
    "last_page_url": "http://mutualidad/public/reserva?page=1",
    "next_page_url": null,
    "path": "http://mutualidad/public/reserva",
    "per_page": "4",
    "prev_page_url": null,
    "to": 2,
    "total": 2
	}
# 6.- Servicialidad
## 6.1.- Servicialidad por nodo
Api utilizada por Gis para buscar la servicialidad de acuerdo a un nodo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/servicialidad/getServicialidad`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| nodo           |string  |          |    Si     |Nodo al que esta asignado el Homepass|
| nap            | int    |          |    Si     |Descripción del Nap         |
| mufad          | int    |          |    Si     |Descripción de la mufa      |
| splitter       | int    |          |    Si     |Descripción del splitter    |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| correlativoRed |  int   | Identificador de la servicialidad                |
| nodo           | string | Identificador del nodo                           | 
| nap            |  int   | Identificador de la nap                          | 
| mufa           |  int   | Identificador de la mufa                         | 
| spliterMufa    |  int   | Identificador del splitter de la mufa            | 
| bocaNap        |  int   | Identificador de la boca de la mufa              | 
| spliterNap     |  int   | Identificador del splitter de la nap             | 
| puertaPon      |  int   | Identificador de la puertaPon                    | 
| ponEdfa        |  ?     |  ?                                               | 
| homepass       |  int   | Identificador del homepass                       | 
| calle          | string | Nombre de la calle                               | 
| numero         | string | Numeración de la calle                           | 
| olt            |  int   | Identificador del OLT                            | 
| tarjetaPon     |  int   | Identificador de la tarjetaPon                   | 
| edfa           |  int   | ?                                                | 
| spliter        |  int   | Identificador del splitter                       | 

### 6.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "nodo":"RENC_86",
        "nap":01, 
        "mufad":1,  
        "splitter":2 
    }
    
### 6.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.1.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 6.1.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                        "correlativoRed": 840250,
                        "nodo": "RENC_86",
                        "nap": "01",
                        "mufa": "1",
                        "spliterMufa": "5",
                        "bocaNap": "09",
                        "spliterNap": "2",
                        "puertaPon": "14",
                        "ponEdfa": "15",
                        "homepass": 62019123,
                        "calle": "HERCULES",
                        "numero": "1179",
                        "olt": "3",
                        "tarjetaPon": "16",
                        "edfa": "21",
                        "spliter": "02"
                    },
                    {
                        "correlativoRed": 840251,
                        "nodo": "RENC_86",
                        "nap": "01",
                        "mufa": "1",
                        "spliterMufa": "5",
                        "bocaNap": "10",
                        "spliterNap": "2",
                        "puertaPon": "14",
                        "ponEdfa": "15",
                        "homepass": 62019124,
                        "calle": "HERCULES",
                        "numero": "1171",
                        "olt": "3",
                        "tarjetaPon": "16",
                        "edfa": "21",
                        "spliter": "02"
                    },
                ]
            }
        },
        "codigo": 200
	}


## 6.2.- Servicialidad por mufa
Api utilizada por Gis para buscar la servicialidad de acuerdo a una mufa.

Los parámetros que recibe son los siguientes:

Ruta : GET `/servicialidad/getServicialidadMufa`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| nodo           |string  |          |    Si     |Nodo al que esta asignado el Homepass|
| tipoMufa       | string |          |    Si     |Tipo de mufa                |
| mufa           | int    |          |    Si     |Código de mufa              |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| correlativoRed |  int   | Identificador de la servicialidad                |
| nodo           | string | Identificador del nodo                           | 
| mufaTroncal    | string | Identificador de la mufa troncal                 | 
|mufaDistribucion| string | ?                                                | 
| nap            | string | Código del Nap                                   | 
| mufa           | string | Identificador del nodo                           | 
| spliterMufa    | string | Identificador del splitter de la mufa            | 
| bocaNap        | string | Identificador de la boca del nap                 | 
| spliterNap     | string | Identificador del splitter del nap               | 
| homepass       |  int   | Identificador del homepass                       | 
| calle          | string | Nombre de la calle                               | 
| numero         | string | Numeración de la calle                           | 

### 6.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "nodo":"RENC_86",
        "tipoMufa":"MT", 
        "mufa":04,  
    }
    
### 6.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 6.2.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                        "correlativoRed": 840258,
                        "nodo": "RENC_86",
                        "mufaTroncal": "04",
                        "mufaDistribucion": "1",
                        "nap": "02",
                        "mufa": "1",
                        "spliterMufa": "1",
                        "bocaNap": "01",
                        "spliterNap": "1",
                        "homepass": 62019062,
                        "calle": "ARGOS",
                        "numero": "7438"
                    },
                    {
                        "correlativoRed": 840402,
                        "nodo": "RENC_86",
                        "mufaTroncal": "04",
                        "mufaDistribucion": "2",
                        "nap": "11",
                        "mufa": "2",
                        "spliterMufa": "3",
                        "bocaNap": "01",
                        "spliterNap": "1",
                        "homepass": 62019201,
                        "calle": "VICUNA MACKENNA",
                        "numero": "7698"
                    }
                
                ]
            }
        },
        "codigo": 200
	}

## 6.3.- Servicialidad por planta
Api utilizada por Gis para buscar la servicialidad de acuerdo a la planta.

Los parámetros que recibe son los siguientes:

Ruta : GET `/servicialidad/getServicialidadPlanta`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| codigoInfraestructura|string|      |    Si     | Identificador del HUB      |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| hub            |string  | Identificador del HUB                            | 
| direccion      |string  | ?                                                | 
| olt            |string  | Identificador del OLT                            | 
| nodo           |string  | Identificador del nodo                           | 
| edfa           |string  | ?                                                | 
| tarjetaPon     |string  | Identificador de tarjetaPon                      | 
| ponEdfa        |string  | ?                                                | 
| puertaPon      |string  | Identificador de puertaPon                       | 
| splitter       |string  | Identificador del splitter                       | 

### 6.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoInfraestructura":"ANGO_HUB1"
    }
    
### 6.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.3.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 6.3.2.2- Respuesta de éxito

	{
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": [
                    {
                        "hub": "ANGO_HUB1",
                        "direccion": "Rancagua #291",
                        "olt": "1",
                        "nodo": "ANGO_12",
                        "edfa": "1",
                        "tarjetaPon": "02",
                        "ponEdfa": "24",
                        "puertaPon": "07",
                        "splitter": "1X2"
                    },
                    {
                        "hub": "ANGO_HUB1",
                        "direccion": "Rancagua #291",
                        "olt": "2",
                        "nodo": "ANGO_79",
                        "edfa": "11",
                        "tarjetaPon": "10",
                        "ponEdfa": "16",
                        "puertaPon": "15",
                        "splitter": "1X2"
                    }
                
                ]
            }
        },
        "codigo": 200
	}

## 6.4.- Servicialidad por planta paginada
Api utilizada por Gis para buscar la servicialidad de acuerdo a la planta.

Los parámetros que recibe son los siguientes:

Ruta : GET `/servicialidad/getServicialidadPlantaGis`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| codigoInfraestructura|string|      |    Si     | Identificador del HUB      |
| per_page       |  int   |          |    Si     |Cantidad de resultados por página|
| page           |  int   |          |    Si     |Especificación de página    |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| hub            |string  | Identificador del HUB                            | 
| direccion      |string  | ?                                                | 
| olt            |string  | Identificador del OLT                            | 
| nodo           |string  | Identificador del nodo                           | 
| edfa           |string  | ?                                                | 
| tarjetaPon     |string  | Identificador de tarjetaPon                      | 
| ponEdfa        |string  | ?                                                | 
| puertaPon      |string  | Identificador de puertaPon                       | 
| splitter       |string  | Identificador del splitter                       | 

### 6.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoInfraestructura":"ANGO_HUB1",
        "per_page": 20,
        "page": 1
    }
    
### 6.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.3.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 6.3.2.2- Respuesta de éxito

	{
         "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "data": {
                    "current_page": 1,
                    "data": [
                        {
                            "hub": "ANGO_HUB1",
                            "direccion": "Rancagua #291",
                            "olt": "1",
                            "nodo": "ANGO_01",
                            "edfa": "7",
                            "tarjetaPon": "01",
                            "ponEdfa": "01",
                            "puertaPon": "00",
                            "splitter": "1X2"
                        },
                        {
                            "hub": "ANGO_HUB1",
                            "direccion": "Rancagua #291",
                            "olt": "1",
                            "nodo": "ANGO_01",
                            "edfa": "7",
                            "tarjetaPon": "01",
                            "ponEdfa": "02",
                            "puertaPon": "01",
                            "splitter": "1X2"
                        },
                        {
                            "hub": "ANGO_HUB1",
                            "direccion": "Rancagua #291",
                            "olt": "1",
                            "nodo": "ANGO_01",
                            "edfa": "7",
                            "tarjetaPon": "16",
                            "ponEdfa": "01",
                            "puertaPon": "00",
                            "splitter": "1X2"
                        },
                        {
                            "hub": "ANGO_HUB1",
                            "direccion": "Rancagua #291",
                            "olt": "1",
                            "nodo": "ANGO_01",
                            "edfa": "7",
                            "tarjetaPon": "16",
                            "ponEdfa": "02",
                            "puertaPon": "01",
                            "splitter": "1X2"
                        },
                        {
                            "hub": "ANGO_HUB1",
                            "direccion": "Rancagua #291",
                            "olt": "1",
                            "nodo": "ANGO_02",
                            "edfa": "7",
                            "tarjetaPon": "01",
                            "ponEdfa": "03",
                            "puertaPon": "02",
                            "splitter": "1X2"
                        }
                    ],
                    "first_page_url": "https://mutualidad.mundopacifico.cl/servicialidad/getServicialidadPlantaGis?page=1",
                    "from": 1,
                    "last_page": 69,
                    "last_page_url": "https://mutualidad.mundopacifico.cl/servicialidad/getServicialidadPlantaGis?page=69",
                    "next_page_url": "https://mutualidad.mundopacifico.cl/servicialidad/getServicialidadPlantaGis?page=2",
                    "path": "https://mutualidad.mundopacifico.cl/servicialidad/getServicialidadPlantaGis",
                    "per_page": "5",
                    "prev_page_url": null,
                    "to": 5,
                    "total": 344
                }
            }
        },
        "codigo": 200
	}

# 7.- Servicios externos

## 7.1.- Obtener todos los HUBS
Api utilizada por Gis para obtener todos los HUBS.

Los parámetros que recibe son los siguientes:

Ruta : GET `/arcgis/rest/services/web_map/GIS_ARCGIS_MUNDO/FeatureServer/1/query`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| where          |string  |          |    Si     |          ?                 |
| outFields      |string  |          |    Si     |          ?                 |
| returnGeometry |boolean |          |    Si     |          ?                 |
| f              |string  |          |    Si     |          ?                 |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| ?              |  ?     | ?                                                |

### 7.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "where":"estado_p%3D3",
        "outFields":"id_planta%2C+cod_infraestructura%2C+nombre%2C+direccion%2C+dom_comuna%2C+nom_comuna%2C+dom_region%2C+region_nom%2C+estado%2C+descripcion", 
        "returnGeometry":false,  
        "f":"json"
    }
    
### 7.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.1.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 7.1.2.2- Respuesta de éxito

	{
        "success": {

        },
        "codigo": 200
	}

## 7.2.- Obtener Nodos por HUB
Api utilizada por Gis para obtener nodos de un HUB.

Los parámetros que recibe son los siguientes:

Ruta : GET `/arcgis/rest/services/web_map/GIS_ARCGIS_MUNDO/MapServer/6/query`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| where          |string  |          |    Si     |          ?                 |
| outFields      |string  |          |    Si     |          ?                 |
| returnGeometry |boolean |          |    Si     |          ?                 |
| f              |string  |          |    Si     |          ?                 |

**Datos de salida:**
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| ?              |  ?     | ?                                                |

### 7.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "where":"id_planta%3D10",
        "outFields":"id_nodo,nombre_nodo,id_planta", 
        "returnGeometry":false,  
        "f":"json"
    }
    
### 7.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.2.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 7.2.2.2- Respuesta de éxito

	{
        "success": {

        },
        "codigo": 200
	}

## 7.3.- Obtener Token ArcGis
Api utilizada por Gis para obtener token.

Los parámetros que recibe son los siguientes:

Ruta : POST `/arcgis/sharing/rest/generateToken`

**Parámetros de entrada:**
| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| username       |string  |          |    Si     |        Usuario             |
| password       |string  |          |    Si     |        Contraseña          |
| referer        |boolean |          |    Si     |        Url                 |
| f              |string  |          |    Si     |          ?                 |
| expiration     |string  |          |    Si     |          ?                 |

### 7.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "username":"usuario",
        "password":"contraseña", 
        "referer":"https://GISMUNDO.MUNDOPACIFICO.CL:7443/arcgis",  
        "f":"json",
        "expiration":"20160"
    }
    
### 7.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.3.2.1- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados "
        },
        "codigo": 404
	} 
  
#### 7.3.2.2- Respuesta de éxito

	{
        "success": {

        },
        "codigo": 200
	}
# 8.- Datos de Ubicaciones Geográficas de Chile
Para obtener los datos de regiones, provincias y comunas de Chile, Mundo pacífico pondrá a disposición de los operadores las apis necesarias para ese fin.

### 8.1.- Listado de Regiones

Ruta : GET `/parametros/regiones`

### 8.2.- Listado de Provincias

Ruta : GET `/parametros/provincias`
Parámetro : codigoRegion

### 8.3.- Listado de Comunas

Rut : GET `/parametros/comunas`
Parámetro : codigoRegion