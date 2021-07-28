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
            - [1.1.2.1- Respuesta de Error Homepass no disponible](#1121--respuesta-de-error-homepass-no-disponible)
            - [1.1.2.2- Respuesta de Error código Homepass erróneo](#1122--respuesta-de-error-código-homepass-erróneo)
            - [1.1.2.3- Respuesta de Exito](#1123--respuesta-de-exito)
    - [1.2.- Factibilidad por dirección](#12--factibilidad-por-direccion)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de Error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de Exito](#1222--respuesta-de-exito)
  - [2.- Naps](#2--naps)
    - [2.1.- setGeoreferencia](#21--setgeoreferencia)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de Error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de Exito](#2122--respuesta-de-exito)
  - [3.- Nivel de señal](#3--nivel-de-senal)
    - [3.1.- Niveles](#31--niveles)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de Error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de Exito](#3122--respuesta-de-exito)
  - [4.- Provisión](#4--provision)
    - [4.1.- Alta](#41--alta)
        - [4.1.1.- Ejemplo de llamada](#411--ejemplo-de-llamada)
        - [4.1.2.- Respuesta de Salida](#412--respuesta-de-salida)
            - [4.1.2.1- Respuesta de Error](#4121--respuesta-de-error)
            - [4.1.2.2- Respuesta de Exito](#4122--respuesta-de-exito)
    - [4.2.- Baja](#41--baja)
        - [4.2.1.- Ejemplo de llamada](#421--ejemplo-de-llamada)
        - [4.2.2.- Respuesta de Salida](#422--respuesta-de-salida)
            - [4.2.2.1- Respuesta de Error](#4221--respuesta-de-error)
            - [4.2.2.2- Respuesta de Exito](#4222--respuesta-de-exito)
    - [4.3.- Desconexión](#41--desconexion)
        - [4.3.1.- Ejemplo de llamada](#431--ejemplo-de-llamada)
        - [4.3.2.- Respuesta de Salida](#432--respuesta-de-salida)
            - [4.3.2.1- Respuesta de Error](#4321--respuesta-de-error)
            - [4.3.2.2- Respuesta de Exito](#4322--respuesta-de-exito)
  - [5.- Reservas](#5--reservas)
    - [5.1.- Creación de Reserva](#51--creación-de-reserva)
        - [5.1.1.- Ejemplo de llamada](#511--ejemplo-de-llamada)
        - [5.1.2.- Respuesta de Salida](#512--respuesta-de-salida)
            - [5.1.2.1- Respuesta de Error Homepass no disponible](#5121--respuesta-de-error-homepass-no-disponible)
            - [5.1.2.2- Respuesta de Error código Homepass erróneo](#5122--respuesta-de-error-código-homepass-erróneo-1)
            - [5.1.2.3- Respuesta de Error código de Operador](#5123--respuesta-de-error-código-de-operador)
            - [5.1.2.4- Respuesta de Exito](#5124--respuesta-de-exito)
    - [5.2.- Obtener Reservas](#52--obtener-reservas)
        - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
        - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
            - [5.2.2.1.- Respuesta de Error](#5221--respuesta-de-error)
            - [5.2.2.2.- Respuesta de Exito](#5222--respuesta-de-exito)
    - [5.3.- Anular de Reserva](#53--anular-de-reserva)
        - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
        - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
            - [5.3.2.1- Respuesta de Error al anular Reserva de Homepass](#5321--respuesta-de-error-al-anular-reserva-de-homepass)
            - [5.3.2.2- Respuesta de Exito](#5322--respuesta-de-exito-1)
  - [6.- Servicialidad](#6--servicialidad)
    - [6.1.- Servicialidad por Nodo](#61--servicialidad-por-nodo)
        - [6.1.1.- Ejemplo de llamada](#611--ejemplo-de-llamada)
        - [6.1.2.- Respuesta de Salida](#612--respuesta-de-salida)
            - [6.1.2.1.- Respuesta de Error](#6121--respuesta-de-error)
            - [6.1.2.2.- Respuesta de Exito](#6122--respuesta-de-exito)
    - [6.2.- Servicialidad por Mufa](#61--servicialidad-por-mufa)
        - [6.2.1.- Ejemplo de llamada](#621--ejemplo-de-llamada)
        - [6.2.2.- Respuesta de Salida](#622--respuesta-de-salida)
            - [6.2.2.1.- Respuesta de Error](#6221--respuesta-de-error)
            - [6.2.2.2.- Respuesta de Exito](#6222--respuesta-de-exito)
  - [7.- Servicios externos](#7--servicios-externos)
    - [7.1.- Get all hubs](#71--get-all-hubs)
        - [7.1.1.- Ejemplo de llamada](#711--ejemplo-de-llamada)
        - [7.1.2.- Respuesta de Salida](#712--respuesta-de-salida)
            - [7.1.2.1.- Respuesta de Error](#7121--respuesta-de-error)
            - [7.1.2.2.- Respuesta de Exito](#7122--respuesta-de-exito)
    - [7.2.- Get token arcgis](#72--get-token-arcgis)
        - [7.2.1.- Ejemplo de llamada](#721--ejemplo-de-llamada)
        - [7.2.2.- Respuesta de Salida](#722--respuesta-de-salida)
            - [7.2.2.1.- Respuesta de Error](#7221--respuesta-de-error)
            - [7.2.2.2.- Respuesta de Exito](#7222--respuesta-de-exito)
    - [7.3.- Get token arcgis](#73--get-token-arcgis)
        - [7.3.1.- Ejemplo de llamada](#731--ejemplo-de-llamada)
        - [7.3.2.- Respuesta de Salida](#732--respuesta-de-salida)
            - [7.3.2.1.- Respuesta de Error](#7321--respuesta-de-error)
            - [7.3.2.2.- Respuesta de Exito](#7322--respuesta-de-exito)
    - [7.4.- Get token arcgis](#74--get-token-arcgis)
        - [7.4.1.- Ejemplo de llamada](#741--ejemplo-de-llamada)
        - [7.4.2.- Respuesta de Salida](#742--respuesta-de-salida)
            - [7.4.2.1.- Respuesta de Error](#7421--respuesta-de-error)
            - [7.4.2.2.- Respuesta de Exito](#7422--respuesta-de-exito)
  - [8.-Datos de Ubicaciones Geográficas de Chile](#8-datos-de-ubicaciones-geográficas-de-chile)
    - [8.1 .- Listado de Regiones](#81---listado-de-regiones)
    - [8.2 .- Listado de Provincias](#82---listado-de-provincias)
    - [8.3 .- Listado de Comunas](#83---listado-de-comunas)

## Objetivo

Disponer Apis para que beyond Up realice gestión sobre los Homepass de Mundo Pacífico.

## Restricciones
A partir de la habilitación de estas Apis, beyond UP debe deja de hacer gestión sobre Homepass y de asignación de Bocas de Naps.

## 1.- Factibilidad por Homepass
Este método permite consultar la factibilidad de un homepass.

Los parámetros que recibe son los siguientes:

Parámetros de entrada
| Campo           |  Tipo  | Formato | Requerido |   Descripción      |
|:---------------:|:------:|:-------:|:---------:|-------------------:|
| codigoHomepass  | int    |         |    Si     | Codigo del Homepass|

Datos de Salida
|  Campo          |  Tipo  | Descripción                      |
|:----------------|:------:|----------------------------------:|
| idHomepass      |  int   | Codigo interno del Homepass       |                 
| codigoHomepass  |  int   | Codigo del Homepass               |                   
| tecnologia      | string | Indica la tecnología              |
| codigonap       |  int   | Codigo del Nap                    |                     
| nap             | string | Descripcion del Nap               |
| comuna          | string | Nombre de la comuna               |
| codigoPostal    |  int   | Codigo Postal                     |
| via             |  string| Tipo de Calle                     |
| calle           | string | Nombre de la calle                |
| numero          | string | Numeracion de la calle            |
| departamento    | string | Departamento                      |
| acceso          | string |                                   |                    
| estado          | string |                                   |                    
| cliente         | string | Si esta ocupado indicar el codigo de cliente|
| bocaNap         | string | Si esta ocupado indicar la boca   |
| bocaDisponible  | string | Si no esta ocupado indicar si hay boca disponible (SI o NO) | 
| Nodo            | string |  Nodo al que esta asignado el Homepass |

Ruta : GET /factibilidad/consultahp

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
		"codigoHomepass": "98024346"	 
	}
### 1.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripción del mensaje

### 1.2.1- Respuesta de Error Homepass no disponible

	{
		"error": {
			"codigoRespuesta": 0,
			"descripcionRespuesta": "Error",
			"detalleRespuesta": "Homepass no se encuentra disponible"
		},
		"codigo": 409
	} 


### 1.2.2- Respuesta de Error código Homepass erróneo

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "Código Homepass no existente"
    },
    “codigo”: 404
	}
  
### 1.2.3- Respuesta de Exito

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

## 2.- Creación de Reserva
Este método permite crear una reserva de Homepass y entrega la boca del NAP asignada al HP.

Los parámetros que recibe son los siguientes:

Parámetros de entrada

| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| operador       | String |          |    Si     |        Código del operador |       
| externalId     | String |          |    Si     | Identificador del Cliente del Operador |
| codigoHomepass |  int   | NNNNNNNN |    Si     |  Código del Homepass        |
| descripcion    |  string|          |    no     | Descripción de la reserva   |    

Ruta : POST /reserva

### 2.1.- Ejemplo de llamada

Ejemplo: JSON

	{
		"operador":"123" 	 
		"externalId":"CC12548745200" 
		"codigoHomepass":"12548745" 
		"descripcion":"Reserva Casa Hualpen" 
	}
	
### 2.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripcion del mensaje

### 2.2.1- Respuesta de Error Homepass no disponible

	{
    "error": {
        "codigoRespuesta": 0,
        "descripcionRespuesta": "Error",
        "detalleRespuesta": "Homepass no se encuentra disponible"
    },
    "codigo": 409
	} 


### 1.2.2- Respuesta de Error código Homepass erróneo

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "Código Homepass no existente"
    },
    “codigo”: 404
	}

### 1.2.3- Respuesta de Error código de Operador

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "Código de Operardor no existente"
    },
    “codigo”: 404
	}

  
### 3.2.2- Respuesta de Exito

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

## 3.- Anular de Reserva
Este método permite Anular la reserva de un Homepass.
Debe dejar habilitado el Homepass y la boca reservada con anterioridad

Los parámetros que recibe son los siguientes:

Parámetros de entrada
| Campo          |  Tipo  | Formato  | Requerido |  Descripción          |
|:---------------|:------:|:--------:|:---------:|----------------------:|
| id_reserva     | int    | NNNNNNN  |    Si     | Identificador de la Reserva |
| motivo         | String |          |    Si     | Motivo de la Anulacion |

Ruta : PUT reserva/anular

### 3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
    "id_reserva":21,
    "motivo":"Cliente no acepta plan",
    "operador":"000"
	}
	
### 3.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripción del mensaje

### 3.2.2- Respuesta de Error al anular Reserva de Homepass

	{
    “error”: {
        “codigoRespuesta”: 0,
        “descripcionRespuesta”: “Error”,
        “detalleRespuesta”: "No ha sido posible anular la reservar del Homepass debido a un error"
    },
    “codigo”: 500
	}
  
### 3.2.2- Respuesta de Exito
	{
    "success": {
        "codigoRespuesta": 1,
        "descripcionRespuesta": {
            "data":  {
               "id_reserva":21
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

## 4.- Obtener Reservas
Este método permite Buscar las reservas de un operador.

Los parámetros que recibe son los siguientes:

Parámetros de entrada
| Campo         |  Tipo  | Formato | Requerido |         Descripción         |
|:------------- |:------:|:-------:|:---------:|----------------------------:|
| fecha_desde   |  date  | yyyy-mm-dd |    Si  | Fecha de Inicio de búsqueda |
| fecha_hasta     | date |    yyyy-mm-dd      |    Si     |   Fecha de termino de búsqueda   |
| codigo_operador |   int     |         |    Si       | Código del operador  | 
| per_page   |  int      |         |    Si       |    numero de paginas      |

Ruta : GET  /reserva

### 4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
     "fecha_desde":"2020-07-21",
     "fecha_hasta":"2020/07/21"
     "codigo_operador":"210" 
     "per_page" : "2"
	}

### 4.2.- Respuesta de Salida

codigo: 200 éxito mensaje: descripcion del mensaje

### 4.2.1- Respuesta de Error

	{
    "error": {
        "codigoRespuesta": 0,
        "descripcionRespuesta": "Error",
        "detalleRespuesta": "No hay datos relacionados "
    },
    "codigo": 404
	} 
  
### 4.2.2- Respuesta de Exito

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


## 5.- Factibilidad por direccion
Este método permite consultar la factibildiad de una dirección.

Los parámetros que recibe son los siguientes:

Parámetros de entrada
| Campo  |  Tipo  | Formato |     Requerido      |             Descripción     |
|:------ |:------:|:-------:|:------------------:|----------------------------:|
| calle  | string |         |         Si         |          nombre de la calle |
| numero | string |   no    |         No         |        número de la calle   |
|comuna  |  int   |         |      Si            |Código de comuna según Subtel|
|forcenap|  int   |         |      Si            |Al indicar 1, solo se valide que exista boca disponible|

Ruta : GET /factibilidad/consultaFactibilidad

Datos de Salida
| Campo          |  Tipo  |                         Descripción              |
|:---------------|:------:|-------------------------------------------------:| 
| idHomepass     |  int   |                 Código interno del Homepass      |
| codigoHomepass |  int   |                 Código del Homepass              | 
| tecnologia     | string |                 Indica la tecnología             |
| codigonap      |  int   |                       Código del Nap        |         
| nap            | string |                     Descripción del Nap      |               
| comuna         | string |                     Nombre de la comuna       |              
| codigoPostal   |  int   |                        Código Postal           |      
| via            |  string|                        Tipo de Calle        |                
| calle          | string |                     Nombre de la calle       |               
| numero         | string |                   Numeración de la calle      |              
| departamento   | string |                       Departamento             |           
| acceso         | string |                                          |           
| estado         | string |                                           |                  
| cliente        | string |        Si esta ocupado indicar el codigo de cliente|         
| bocaNap        | string |               Si esta ocupado indicar la boca     |        
| bocaDisponible | string | Si no esta ocupado indicar si hay boca disponible (SI o NO) |
| Nodo           | string |            Nodo al que esta asignado el Homepass |

### 5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
	  "calle":"MINERO VICTOR FUENTEALBA"
	  "numero":"981" 	
	  "comuna":"8102" 
	  "forcenap":"" 
	}

### 5.2.- Respuesta de Salida
codigo: 200 éxito mensaje: descripcion del mensaje
### 5.2.1- Respuesta de Error

	{
    "error": {
        "codigoRespuesta": 0,
        "descripcionRespuesta": "Error",
        "detalleRespuesta": "No hay datos relacionados "
    },
    "codigo": 404
	} 
  
### 6.2.2- Respuesta de Exito

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


## 6.-Datos de Ubicaciones Geográficas de Chile
Para obtener los datos de regiones, provincias y comunas de Chile, Mundo pacifico pondra a disposición de los operadores las apis necesarias para ese fin.

### 6.1 .- Listado de Regiones

Ruta : GET /parametros/regiones

### 6.2 .- Listado de Provincias

Ruta : GET /parametros/provincias
Parámetro : codigoRegion

### 6.3 .- Listado de Comunas

Rut : GET /parametros/comunas
Parámetro : codigoRegion