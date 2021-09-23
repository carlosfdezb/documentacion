| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Mundo Móvil

<!-- Índice -->
- [Documentación Api´s para Mundo Móvil](#documentación-apis-para-mundo-móvil)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Provisión](#1--provisión)
    - [1.1.- Alta](#11--alta)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Alta Adicional](#12--alta-adicional)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- Baja](#13--baja)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
    - [1.4.- Habilitación](#14--habilitación)
        - [1.4.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
        - [1.4.2.- Respuesta de Salida](#142--respuesta-de-salida)
            - [1.4.2.1- Respuesta de error](#1421--respuesta-de-error)
            - [1.4.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
    - [1.5.- Informar Portabilidad Móvil](#15--informar-portabilidad-movil)
        - [1.5.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
        - [1.5.2.- Respuesta de Salida](#152--respuesta-de-salida)
            - [1.5.2.1- Respuesta de error](#1521--respuesta-de-error)
            - [1.5.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
    - [1.6.- Modificar Plan](#16--modificar-plan)
        - [1.6.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
        - [1.6.2.- Respuesta de Salida](#162--respuesta-de-salida)
            - [1.6.2.1- Respuesta de error](#1621--respuesta-de-error)
            - [1.6.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
    - [1.7.- Modificar Suscriptor](#17--modificar-suscriptor)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de error](#1721--respuesta-de-error)
            - [1.7.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
    - [1.8.- Suspensión](#18--suspensión)
        - [1.8.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
        - [1.8.2.- Respuesta de Salida](#182--respuesta-de-salida)
            - [1.8.2.1- Respuesta de error](#1821--respuesta-de-error)
            - [1.8.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
  - [2.- Soporte](#2--provisión)
    - [2.1.- BlockSim](#21--blockSim)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- CheckBuzon](#22--checkBuzon)
        - [2.2.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#222--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#2221--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
    - [2.3.- CheckNum](#23--checkNum)
        - [2.3.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
        - [2.3.2.- Respuesta de Salida](#232--respuesta-de-salida)
            - [2.3.2.1- Respuesta de error](#2321--respuesta-de-error)
            - [2.3.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
    - [2.4.- CheckPort](#24--checkPort)
        - [2.4.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
        - [2.4.2.- Respuesta de Salida](#242--respuesta-de-salida)
            - [2.4.2.1- Respuesta de error](#2421--respuesta-de-error)
            - [2.4.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
    - [2.5.- CheckSessions](#25--checkSessions)
        - [2.5.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
        - [2.5.2.- Respuesta de Salida](#252--respuesta-de-salida)
            - [2.5.2.1- Respuesta de error](#2521--respuesta-de-error)
            - [2.5.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
    - [2.6.- CheckSim](#26--checkSim)
        - [2.6.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
        - [2.6.2.- Respuesta de Salida](#262--respuesta-de-salida)
            - [2.6.2.1- Respuesta de error](#2621--respuesta-de-error)
            - [2.6.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
    - [2.7.- CheckSubscription](#27--checkSubscription)
        - [2.7.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
        - [2.7.2.- Respuesta de Salida](#272--respuesta-de-salida)
            - [2.7.2.1- Respuesta de error](#2721--respuesta-de-error)
            - [2.7.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
    - [2.8.- getBolsas](#28--getBolsas)
        - [2.8.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
        - [2.8.2.- Respuesta de Salida](#282--respuesta-de-salida)
            - [2.8.2.1- Respuesta de error](#2821--respuesta-de-error)
            - [2.8.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
    - [2.9.- getConsumo](#29--getConsumo)
        - [2.9.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
        - [2.9.2.- Respuesta de Salida](#292--respuesta-de-salida)
            - [2.9.2.1- Respuesta de error](#2921--respuesta-de-error)
            - [2.9.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
    - [2.10.- getConsumoIVR](#210--getConsumoIVR)
        - [2.10.1.- Ejemplo de llamada](#2101--ejemplo-de-llamada)
        - [2.10.2.- Respuesta de Salida](#2102--respuesta-de-salida)
            - [2.10.2.1- Respuesta de error](#21021--respuesta-de-error)
            - [2.10.2.2- Respuesta de éxito](#21022--respuesta-de-éxito)
    - [2.11.- getConsumoPlan](#211--getConsumoPlan)
        - [2.11.1.- Ejemplo de llamada](#2111--ejemplo-de-llamada)
        - [2.11.2.- Respuesta de Salida](#2112--respuesta-de-salida)
            - [2.11.2.1- Respuesta de error](#21121--respuesta-de-error)
            - [2.11.2.2- Respuesta de éxito](#21122--respuesta-de-éxito)
    - [2.12.- getESim](#212--getESim)
        - [2.12.1.- Ejemplo de llamada](#2121--ejemplo-de-llamada)
        - [2.12.2.- Respuesta de Salida](#2122--respuesta-de-salida)
            - [2.12.2.1- Respuesta de error](#21221--respuesta-de-error)
            - [2.12.2.2- Respuesta de éxito](#21222--respuesta-de-éxito)
    - [2.13.- getPlan](#213--getPlan)
        - [2.13.1.- Ejemplo de llamada](#2131--ejemplo-de-llamada)
        - [2.13.2.- Respuesta de Salida](#2132--respuesta-de-salida)
            - [2.13.2.1- Respuesta de error](#21321--respuesta-de-error)
            - [2.13.2.2- Respuesta de éxito](#21322--respuesta-de-éxito)
    - [2.14.- getSimInfo](#214--getSimInfo)
        - [2.14.1.- Ejemplo de llamada](#2141--ejemplo-de-llamada)
        - [2.14.2.- Respuesta de Salida](#2142--respuesta-de-salida)
            - [2.14.2.1- Respuesta de error](#21421--respuesta-de-error)
            - [2.14.2.2- Respuesta de éxito](#21422--respuesta-de-éxito)
    - [2.15.- Liberar Número](#215--liberar-número)
        - [2.15.1.- Ejemplo de llamada](#2151--ejemplo-de-llamada)
        - [2.15.2.- Respuesta de Salida](#2152--respuesta-de-salida)
            - [2.15.2.1- Respuesta de error](#21521--respuesta-de-error)
            - [2.15.2.2- Respuesta de éxito](#21522--respuesta-de-éxito)
    - [2.16.- Login](#216--login)
        - [2.16.1.- Ejemplo de llamada](#2161--ejemplo-de-llamada)
        - [2.16.2.- Respuesta de Salida](#2162--respuesta-de-salida)
            - [2.16.2.1- Respuesta de error](#21621--respuesta-de-error)
            - [2.16.2.2- Respuesta de éxito](#21622--respuesta-de-éxito)
    - [2.17.- Logout](#217--logout)
        - [2.17.1.- Ejemplo de llamada](#2171--ejemplo-de-llamada)
        - [2.17.2.- Respuesta de Salida](#2172--respuesta-de-salida)
            - [2.17.2.1- Respuesta de error](#21721--respuesta-de-error)
            - [2.17.2.2- Respuesta de éxito](#21722--respuesta-de-éxito)
    - [2.18.- UpdatePlan](#218--updatePlan)
        - [2.18.1.- Ejemplo de llamada](#2181--ejemplo-de-llamada)
        - [2.18.2.- Respuesta de Salida](#2182--respuesta-de-salida)
            - [2.18.2.1- Respuesta de error](#21821--respuesta-de-error)
            - [2.18.2.2- Respuesta de éxito](#21822--respuesta-de-éxito)
 



# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Provisión
## 1.1.- Dar de Alta
Método que permite dar de alta una línea.

Los parámetros que recibe son los siguientes:

Ruta : POST `/alta`

**Parámetros de entrada:**
| Campo              |  Tipo        | Formato        | Requerido       |             Descripción     |
|:-------------------|:------------:|:--------------:|:---------------:|----------------------------:|
| idEmpresa          | int          |                |                 | ID de la empresa            |
| operacion          | int          |                |                 | Código de operación         |
| ↓ detalleServicios | array[object]|                |                 |                             |
| ⤷ servicio         | int          |                |                 | ID del servicio             |
| ↓↓ datosServicios  | array[object]|                |                 |                             |
| ⤷ idPackage        | string       |                |                 | ID del package              |
| ⤷ cicloFacturacion | string       |                |                 | Ciclo de facturación        |
| ↓↓↓ suscriptores   | array[object]|                |                 |                             |
| ⤷ numeroTelefono   | string       |                |                 | Número de teléfono          |
| ⤷ iccid            | string       |                |                 | ID ICC                      |
| ⤷ codigoExterno    | string       |                |                 | Código externo              |
| ⤷ portabilidad     | int          |                |                 | ID de portabilidad          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa": 1,
        "operacion": 1001,
        "detalleServicios": [
            {
                "servicio": 400,
                "datosServicios": [
                    {
                        "idPackage": "581",
                        "cicloFacturacion": "25",
                        "suscriptores": [
                            {
                                "numeroTelefono": "56923609315",
                                "iccid": "8956072200000000673F",
                                "codigoExterno": "CC49915956923609315",
                                "portabilidad": 0
                            }
                        ]
                    }
                ]
            }
        ]
    }

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": [
                {
                    "codigoError": 0,
                    "descripcionError": "SIM activa con otra linea"
                }
            ]
        },
        "codigo": 422
    }
  
#### 1.1.2.2.- Respuesta de éxito

	{
        ...
	}

## 1.2.- Agregar Línea a Suscripción Familiar
Método que permite agregar una línea a una suscripción familiar.

Los parámetros que recibe son los siguientes:

Ruta : POST `/alta-adicional`

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

## 1.3.- Dar de Baja
Método que permite dar de baja una línea.

Los parámetros que recibe son los siguientes:

Ruta : DELETE `/baja`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:------------------|:------------:|:----------:|:--------------:|----------------------------:|
| idEmpresa         | string       |            |                | ID de la empresa            |
| operacion         | string       |            |                | Código de operación         |
| codigoExterno     | string       |            |                | Código externo              |
| ↓ detalleServicios| array[object]|            |                |                             |
| ⤷ servicio        | string       |            |                | ID del servicio             |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa":"1",
        "operacion":"3001",
        "codigoExterno": "CC49915956923609315",
        "detalleServicios":[
            {
                "servicio":"400"
            }
        ] 
    }

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.3.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idSolicitud": 38473,
            "descripcionRespuesta": "Petición enviada correctamente"
        },
        "codigo": 200
    }

## 1.4.- Habilitar Línea
Método que permite sacar del estado de suspensión a una línea.

Los parámetros que recibe son los siguientes:

Ruta : PATCH `/habilitacion`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:------------------|:------------:|:----------:|:--------------:|----------------------------:|
| idEmpresa         | string       |            |                | ID de la empresa            |
| operacion         | string       |            |                | Código de operación         |
| codigoExterno     | string       |            |                | Código externo              |
| ↓ detalleServicios| array[object]|            |                |                             |
| ⤷ servicio        | string       |            |                | ID de servicio              |

### 1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa":1,
        "operacion":2001,
        "codigoExterno": "CC63056936000014",
        "detalleServicios":[
            {
                "servicio":400
            }
        ]
    }

### 1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.4.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idSolicitud": 38477,
            "descripcionRespuesta": "Petición enviada correctamente"
        },
        "codigo": 200
    }


## 1.5.- Informar Portabilidad Móvil
Método que permite informar a móvil de una portabilidad a suceder en la próxima ventana.

Los parámetros que recibe son los siguientes:

Ruta : POST `/informarportabilidadmovil`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.5.2.2.- Respuesta de éxito

	{
        ...
	}


## 1.6.- Modificar Plan
Método que permite cambiar plan o agregar una bolsa a una línea.

Los parámetros que recibe son los siguientes:

Ruta : PATCH `/modificarPlan`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:------------------|:------------:|:----------:|:--------------:|----------------------------:|
| idEmpresa         | string       |            |                | ID de la empresa            |
| operacion         | string       |            |                | Código de operación         |
| codigoExterno     | string       |            |                | Código externo              |
| ↓ detalleServicios| array[object]|            |                |                             |
| ⤷ servicio        | int          |            |                | ID de servicio              |
| ↓↓ datosServicios |array[object] |            |                |                             |
| ⤷ cicloFacturacion| int          |            |                | Ciclo de facturación        |
| ⤷ idPackage       | string       |            |                | ID de package               |

### 1.6.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa":1,
        "operacion":4002,
        "codigoExterno": "mundo56936000129",
        "detalleServicios":[
            {
                "servicio":400,
                "datosServicios":[
                    {
                        "cicloFacturacion":1,
                        "idPackage": "503"
                    }
                ]
            }
        ]
    }

### 1.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idSolicitud": 38479,
            "descripcionRespuesta": "Petición enviada correctamente"
        },
        "codigo": 200
    }

## 1.7.- Modificar Suscripción
Método que permite cambiar código externo, sim o línea de una suscripción.

Los parámetros que recibe son los siguientes:

Ruta : PUT `/modificarSuscriptor`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:------------------|:------------:|:----------:|:--------------:|----------------------------:|
| idEmpresa         | string       |            |                | ID de empresa               |
| operacion         | string       |            |                | Código de operación         |
| codigoExterno     | string       |            |                | Código externo              |
| ↓ detalleServicios| array[object]|            |                |                             |
| ⤷ servicio        | int          |            |                | ID de servicio              |
| ↓↓ datosServicios |array[object] |            |                |                             |
| ↓↓↓ suscriptores  |array[object] |            |                |                             |
| ⤷ iccid           | string       |            |                | ID de ICC                   |

### 1.7.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa": "1",
        "operacion": "4001",
        "codigoExterno": "CC156966586186",
        "detalleServicios": [
            {
                "servicio": "400",
                "datosServicios": [
                    {
                        "suscriptores": [
                            {
                                "iccid": "8956072200000053227F"
                            }
                        ]
                    }
                ]
            }
        ]
    }

### 1.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.7.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idSolicitud": 38482,
            "descripcionRespuesta": "Petición enviada correctamente"
        },
        "codigo": 200
    }

## 1.8.- Suspender una Línea
Método que permite suspender una línea.

Los parámetros que recibe son los siguientes:

Ruta : PATCH `/suspension`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| idEmpresa         | string       |            |                | ID de la empresa            |
| operacion         | string       |            |                | Código de operación         |
| codigoExterno     | string       |            |                | Código externo              |
| ↓ detalleServicios| array[object]|            |                |                             |
| ⤷ servicio        | string       |            |                | ID de servicio              |

### 1.8.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idEmpresa":1,
        "operacion":2002,
        "codigoExterno": "CC63056936000014",
        "detalleServicios":[
            {
                "servicio":400
            }
        ]
    }

### 1.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.8.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": [
                {
                    "codigoError": 0,
                    "descripcionError": "Undefined index: datosServicios"
                }
            ]
        },
        "codigo": 0
    }
  
#### 1.8.2.2.- Respuesta de éxito

	{
        ...
	}


# 2.- Soporte
## 2.1.- Bloquear SIM
Método que permite bloquear o desbloquear una SIM.

Los parámetros que recibe son los siguientes:

Ruta : PATCH `/blockSim`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | string       |            |                | Número de teléfono          |
| simStatus         | string       |            |                | ID del estatus de la SIM    |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": "",
        "simStatus": ""
	}

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": [
                {
                    "codigoError": 0,
                    "descripcionError": "Suscriptor no encontrado"
                }
            ]
        },
        "codigo": 404
    }
  
#### 2.1.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.2.- Estado de Buzón de Voz
Método que permite obtener el estado del buzón de voz.

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkBuzon`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | string       |            |                | Número de teléfono          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": "56936000016"
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

## 2.3.- Obtener Datos de una Línea
Método que permite obtener los datos de una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkNum`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | string       |            |                | Número de teléfono          |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ↓ getMsisdnInfoResult | array[object]|                                                  |
| ⤷ wsSessionId         | string       | ID de ws Session                                 |
| ⤷ callID              | string       | Call ID                                          |
| ⤷ callCode            | int          | Call code                                        |
| ⤷ resultCode          | string       | Código de resultado                              |
| ⤷ callMsg             | string       | Call message                                     |
| ⤷ subscriptionID      | string       | ID de la suscripción                             |
| ↓↓ item               | array[object]|                                                  |
| ⤷ packageInstanceID   | string       | ID de la instancia del package                   |
| ⤷ status              | int          | Estatus                                          |
| ⤷ msisdn              | string       | Msisdn                                           |

### 2.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": "936000014"
	}

### 2.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.3.2.1.- Respuesta de error

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "getMsisdnInfoResult": {
                    "wsSessionId": "EWSab6b9a90429578",
                    "callID": "EWSab6b9a90429578COR2288dc7f2672ff",
                    "callCode": 105,
                    "resultCode": "ENTITY_NOT_FOUND",
                    "callMsg": "MSISDN[numeroTelefono] not found"
                }
            }
        },
        "codigo": 200
    }
  
#### 2.3.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "getMsisdnInfoResult": {
                    "wsSessionId": "EWSab6b9a90429578",
                    "callID": "EWSab6b9a90429578CORab6ffc72f5df5e",
                    "callCode": 0,
                    "resultCode": "OK",
                    "callMsg": "ok",
                    "item": {
                        "packageInstanceID": "PKGID234273_TS1625491811353",
                        "status": 0,
                        "msisdn": "936000014"
                    },
                    "subscriptionID": "SID115397_TS1625491811294_0"
                }
            }
        },
        "codigo": 200
    }

## 2.4.- Estado de Portabilidad
Método que permite obtener el estado de una portabilidad.

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkPort`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | string       |            |                | Número de teléfono          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono":"valor"
	}

### 2.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.4.2.1.- Respuesta de error

    {
        "getPortabilityResult": {
            "wsSessionId": "EWSad2e3b816c39e5",
            "callID": "EWSad2e3b816c39e5COR2447a850858294",
            "callCode": 101,
            "resultCode": "VALIDATION",
            "callMsg": "At least one parameter is mandatory"
        }
    }
  
#### 2.4.2.2.- Respuesta de éxito

    {
        ...
    }


## 2.5.- Sesiones Abiertas
Método que permite obtener las sesiones abiertas por el Ws de mundo móvil en SUMA.

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkSessions`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.5.2.2.- Respuesta de éxito

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

## 2.6.- Obtener Datos de SIM
Método que permite obtener los datos de una tarjeta sim.

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkSim`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| icc               | int          |            |                | Código ICC                  |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| ↓ getSimInfoResult | array[object]|                                                  |
| ⤷ wsSessionId      | string       | ID de ws Session                                 |
| ⤷ callID           | string       | Call ID                                          |
| ⤷ callCode         | int          | Call code                                        |
| ⤷ resultCode       | string       | Código de resultado                              |
| ⤷ callMsg          | string       | Call message                                     |
| ⤷ subscriptionID   | string       | ID de la suscripción                             |
| ↓↓ item            | array[object]|                                                  |
| ⤷ packageInstanceID| string       | ID de la instancia del package                   |
| ⤷ icc              | string       | Código ICC                                       | 
| ⤷ puk              | string       | Código PUK                                       | 
| ⤷ status           | int          | Estatus                                          | 
| ⤷ imsiID           | string       | Código IMSI                                      | 
| ⤷ additionalImsi   | string       | IMSI adicional                                   | 

### 2.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "icc": 8956072200000000673
	}

### 2.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.6.2.1.- Respuesta de error

    {
        "getSimInfoResult": {
            "wsSessionId": "EWSaba2d3b8399d84",
            "callID": "EWSaba2d3b8399d84COR22c1750fec4b6f",
            "callCode": 105,
            "resultCode": "ENTITY_NOT_FOUND",
            "callMsg": "SIM[ICC] not found"
        }
    }
  
#### 2.6.2.2.- Respuesta de éxito

    {
        "getSimInfoResult": {
            "wsSessionId": "EWSaba2d3b8399d84",
            "callID": "EWSaba2d3b8399d84CORaba8716c618d26",
            "callCode": 0,
            "resultCode": "OK",
            "callMsg": "ok",
            "item": {
                "packageInstanceID": "PKGID269653_TS1627321662016"
                "icc": "8956072200000000673"
                "puk": "66505235"
                "status": 3
                "imsiID": "730072200000067"
                "additionalImsi": "730072200000067"
            },
            "subscriptionID": "SID131753_TS1627321661965_0"
        }
    }

## 2.7.- Obtener Datos de una Suscripción
Método que permite obtener datos de una suscripción (más completa, incluye consumo).

Los parámetros que recibe son los siguientes:

Ruta : GET `/checkSubscription`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| subscriptionID    | string       |            |                | ID de la suscripción        |

**Datos de salida:**
| Campo                   |  Tipo        |                         Descripción              |
|:------------------------|:------------:|-------------------------------------------------:| 
| wsSessionId             | string       | ID de la ws Session                              |
| callID                  | string       | Call ID                                          |
| callCode                | int          | Call code                                        |
| resultCode              | string       | Código de resultado                              |
| callMsg                 | string       | Call message                                     |
| ↓ item                  | array[object]|                                                  |
| ↓↓ subscriptionBasic    | array[object]|                                                  |
| ⤷ subscriptionID        | string       | ID de la suscripción                             |
| ⤷ idSubscriber          | int          | ID de la suscripción                             |
| ⤷ msisdn                | string       | Código msisdn                                    |
| ⤷ icc                   | string       | Código ICC                                       |
| ⤷ imsi                  | string       | Código IMSI                                      |
| ⤷ status                | int          | Estado                                           |
| ⤷ computedStatus        | int          | ComputedStatus                                   |
| ⤷ networkStatus         | int          | Estado de la red                                 |
| ⤷ type                  | int          | ID del tipo                                      |
| ⤷ portabilityStatus     | int          | Estado de la portabilidad                        |
| ↓↓ itemBalance          | array[object]|                                                  |
| ⤷ balance               | string       | Balance                                          |
| ⤷ expirationDate        | timestamp    | Fecha de expiración                              |
| ↓↓ service              | array[object]|                                                  |
| ⤷ active                | boolean      | Breve descripción                                |
| ⤷ extBool               | boolean      | Breve descripción                                |
| ⤷ extNumber             | int          | Breve descripción                                |
| ⤷ extString             | string       | Breve descripción                                |
| ⤷ userModifiable        | boolean      | Breve descripción                                |
| ⤷ userVisible           | boolean      | Breve descripción                                |
| ⤷ featureName           | string       | Breve descripción                                |
| ⤷ featureID             | string       | Breve descripción                                |
| ⤷ featureModel          | string       | Breve descripción                                |
| ⤷ featureOnlyAdmin      | boolean      | Breve descripción                                |
| ↓↓ bonus                | array[object]|                                                  |
| ⤷ packageInstanceID     | string       | Breve descripción                                |
| ⤷ bssRefID              | string       | Breve descripción                                |
| ⤷ status                | int          | Breve descripción                                |
| ⤷ scope                 | int          | Breve descripción                                |
| ⤷ renewable             | boolean      | Breve descripción                                |
| ⤷ renewalCount          | int          | Breve descripción                                |
| ⤷ promotion             | boolean      | Breve descripción                                |
| ⤷ startDate             | timestamp    | Breve descripción                                |
| ⤷ origStartDate         | timestamp    | Breve descripción                                |
| ⤷ terminationDate       | timestamp    | Breve descripción                                |
| ⤷ trafficLimitValueOrig | string       | Breve descripción                                |
| ⤷ trafficLimitValue     | string       | Breve descripción                                |
| ⤷ trafficLimitValueRenewal|string      | Breve descripción                                |
| ⤷ name                  | string       | Breve descripción                                |
| ⤷ deltaPriceplanID      | string       | Breve descripción                                |
| ⤷ type                  | int          | Breve descripción                                |
| ⤷ category              | string       | Breve descripción                                |
| ↓↓ mpp                  | array[object]|                                                  |
| ⤷ packageInstanceID     | string       | Breve descripción                                |
| ⤷ bssRefID              | string       | Breve descripción                                |
| ⤷ status                | int          | Breve descripción                                |
| ⤷ scope                 | int          | Breve descripción                                |
| ⤷ renewable             | boolean      | Breve descripción                                |
| ⤷ renewalCount          | int          | Breve descripción                                |
| ⤷ promotion             | boolean      | Breve descripción                                |
| ⤷ startDate             | timestamp    | Breve descripción                                |
| ⤷ origStartDate         | timestamp    | Breve descripción                                |
| ⤷ name                  | string       | Breve descripción                                |
| ⤷ deltaPriceplanID      | string       | Breve descripción                                |
| ⤷ type                  | int          | Breve descripción                                |
| ⤷ category              | string       | Breve descripción                                |
| ↓↓ pack                 | array[object]|                                                  |
| ⤷ packageInstanceID     | string       | Breve descripción                                |
| ⤷ bssRefID              | string       | Breve descripción                                |
| ⤷ status                | int          | Breve descripción                                |
| ⤷ scope                 | int          | Breve descripción                                |
| ⤷ renewable             | boolean      | Breve descripción                                |
| ⤷ renewalCount          | int          | Breve descripción                                |
| ⤷ promotion             | boolean      | Breve descripción                                |
| ⤷ startDate             | timestamp    | Breve descripción                                |
| ⤷ origStartDate         | timestamp    | Breve descripción                                |
| ⤷ terminationDate       | timestamp    | Breve descripción                                |
| ⤷ chargingLimitValueOrig| string       | Breve descripción                                |
| ⤷ chargingLimitValue    | string       | Breve descripción                                |
| ⤷ chargingLimitValueRenewal|string     | Breve descripción                                |
| ⤷ name                  | string       | Breve descripción                                |
| ⤷ deltaPriceplanID      | string       | Breve descripción                                |
| ⤷ type                  | int          | Breve descripción                                |
| ⤷ category              | string       | Breve descripción                                |
| ↓↓↓ child               | array[object]|                                                  |
| ⤷ bssRefID              | string       | Breve descripción                                |
| ⤷ status                | int          | Breve descripción                                |
| ⤷ scope                 | int          | Breve descripción                                |
| ⤷ renewalCount          | int          | Breve descripción                                |
| ⤷ promotion             | boolean      | Breve descripción                                |
| ⤷ startDate             | timestamp    | Breve descripción                                |
| ⤷ origStartDate         | timestamp    | Breve descripción                                |
| ⤷ name                  | string       | Breve descripción                                |
| ⤷ deltaPriceplanID      | string       | Breve descripción                                |
| ⤷ type                  | int          | Breve descripción                                |
| ⤷ category              | string       | Breve descripción                                |

### 2.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "subscriptionID": "SID21356_TS1608234799559_0"
	}

### 2.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.7.2.1.- Respuesta de error

    {
        "subscriptionProfileResult": {
            "wsSessionId": "EWSabb7ea00fe977d"
            "callID": "EWSabb7ea00fe977dCOR22d0c52a3a0420"
            "callCode": 115
            "resultCode": "INVALID_SUBSCRIPTION"
            "callMsg": "Invalid SID[subscriptionID]"
        }
    }
  
#### 2.7.2.2.- Respuesta de éxito

    {
        "subscriptionProfileResult": {
            "wsSessionId": "EWSaba2d3b8399d84",
            "callID": "EWSaba2d3b8399d84COR22c311eaafb34f",
            "callCode": 0,
            "resultCode": "OK",
            "callMsg": "ok",
            "item": {
                "subscriptionBasic": {
                    "subscriptionID": "SID21356_TS1608234799559_0",
                    "idSubscriber": 25924,
                    "msisdn": "936003595",
                    "icc": "8956072200000046544",
                    "imsi": "730072200004654",
                    "status": 18,
                    "computedStatus": 18,
                    "networkStatus": 11,
                    "type": 0,
                    "portabilityStatus": 0
                },
                "itemBalance": {
                    "balance": "0",
                    "expirationDate": "2021-03-17T18:53:20-03:00"
                },
                "service": [
                    {
                        "active": false,
                        "extBool": false,
                        "extNumber": -1,
                        "extString": "",
                        "userModifiable": false,
                        "userVisible": false,
                        "featureName": "Incoming Calls Blocked",
                        "featureID": "Baic",
                        "featureModel": "SupplementaryService.xsd",
                        "featureOnlyAdmin": false
                    },
                    ...
                ],
                "bonus": [
                    {
                        "packageInstanceID": "PKGID37592_TS1608234799613",
                        "bssRefID": "MM_Mimundo_L|PKGID37592_TS1608234799613|RP_MiMundo_L_Minutos|165552",
                        "status": 0,
                        "scope": 0,
                        "renewable": true,
                        "renewalCount": 9,
                        "promotion": false,
                        "startDate": "2021-08-25T00:00:00-04:00",
                        "origStartDate": "2020-12-17T18:53:20-03:00",
                        "terminationDate": "2021-09-25T00:00:00-03:00",
                        "trafficLimitValueOrig": "30000.000000",
                        "trafficLimitValue": "60000.000000",
                        "trafficLimitValueRenewal": "60000.000000",
                        "name": "RP_MiMundo_L_Minutos",
                        "deltaPriceplanID": "RP_MiMundo_L_Minutos",
                        "type": 0,
                        "category": "voice"
                    },
                    ...
                ],
                "mpp": [
                    {
                        "packageInstanceID": "PKGID37592_TS1608234799613",
                        "bssRefID": "MM_Mimundo_L|PKGID37592_TS1608234799613|MiniPP_ServiciosOperador|165544",
                        "status": 0,
                        "scope": 0,
                        "renewable": false,
                        "renewalCount": 0,
                        "promotion": false,
                        "startDate": "2020-12-17T18:53:20-03:00",
                        "origStartDate": "2020-12-17T18:53:20-03:00",
                        "name": "MiniPP_ServiciosOperador",
                        "deltaPriceplanID": "MiniPP_ServiciosOperador",
                        "type": 1,
                        "category": "generic"
                    },
                    ...
                ],
                "pack": {
                    "packageInstanceID": "PKGID37592_TS1608234799613",
                    "bssRefID": "MM_Mimundo_L|PKGID37592_TS1608234799613|RP_MiMundo_L|165560",
                    "status": 0,
                    "scope": 0,
                    "renewable": true,
                    "renewalCount": 9,
                    "promotion": false,
                    "startDate": "2021-08-25T00:00:00-04:00",
                    "origStartDate": "2020-12-17T18:53:20-03:00",
                    "terminationDate": "2021-09-25T00:00:00-03:00",
                    "chargingLimitValueOrig": "30720.000000",
                    "chargingLimitValue": "40960.000000",
                    "chargingLimitValueRenewal": "40960.000000",
                    "name": "RP_MiMundo_L",
                    "deltaPriceplanID": "RP_MiMundo_L",
                    "type": 2,
                    "category": "combo",
                    "child": {
                        "bssRefID": "MM_Mimundo_L|PKGID37592_TS1608234799613|MiniPP_RRSS|165564",
                        "status": 0,
                        "scope": 0,
                        "renewalCount": 0,
                        "promotion": false,
                        "startDate": "2020-12-17T18:53:20-03:00",
                        "origStartDate": "2020-12-17T18:53:20-03:00",
                        "name": "MiniPP_RRSS",
                        "deltaPriceplanID": "MiniPP_RRSS",
                        "type": 1,
                        "category": "data"
                    }
                }
            }
        }
    }

## 2.8.- Bolsas Adquiridas
Método que permite obtener el historial de bolsas adquiridas por una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getBolsas`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.8.2.2.- Respuesta de éxito

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

## 2.9.- Obtener Consumo de una Línea
Método que permite obtener el consumo de una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getConsumo`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | string       |            |                | Número de teléfono          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| datos          | int          | Datos consumidos                                 |
| voz            | int          | Minutos consumidos                               |
| sms            | int          | Sms consumidos                                   |
| fechaRenovacion| date         | Fecha de renovación                              |
| fechaInicial   | date         | Fecha inicial                                    |
| sim            | string       | Código de SIM                                    |

### 2.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": 56936000052
	}

### 2.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.9.2.1.- Respuesta de error

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": null
        },
        "codigo": 200
    }
  
#### 2.9.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "datos": 10194,
                "voz": 1390,
                "sms": 300,
                "fechaRenovacion": "25-09-2021",
                "fechaInicial": "13-08-2020",
                "sim": "8956072200000014419F"
            }
        },
        "codigo": 200
    }

## 2.10.- Obtener Consumo de una Línea IVR
Método que permite obtener el consumo de una línea con respuesta en formato especial para IVR.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getConsumoIVR`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.10.2.2.- Respuesta de éxito

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

## 2.11.- Obtener Consumo de Plan de una Línea
Método que permite obtener el consumo y los datos del plan de una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getConsumoPlan`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.11.2.2.- Respuesta de éxito

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

## 2.12.- Obtener Código de Provisión E-SIM
Método que permite obtener el código de provisión de una e-sim (QR).

Los parámetros que recibe son los siguientes:

Ruta : GET `/getESim`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| sid               |              |            |                | Breve descripción           |
| icc               |              |            |                | Código ICC                  |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "sid": ,
        "icc":
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

## 2.13.- Obtener Datos de Plan de una Línea
Método que permite obtener los datos del plan de una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getPlan`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | int          |            |                | Número de teléfono          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| nombre         | string       | Nombre de plan                                   |
| traficoDatos   | int          | Tráfico de datos                                 |
| traficoVoz     | int          | Tráfico de voz                                   |
| traficoSms     | int          | Tráfico de sms                                   |
| imsi           | string       | Código IMSI                                      |
| dispositivos   | array[object]|                                                  |
| msisdn         | int          | msisdn                                           |
| imsi           | string       | Código IMSI                                      |
| imei           | string       | Código IMEI                                      |
| modelo         | string       | Modelo de teléfono                               |
| marca          | string       | Marca de teléfono                                |

### 2.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": 936000012
	}

### 2.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.13.2.1.- Respuesta de error

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": null
        },
        "codigo": 200
    }
  
#### 2.13.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "nombre": "Movil 36 GB",
                "traficoDatos": 30720,
                "traficoVoz": 500,
                "traficoSms": 50,
                "imsi": "730072200000012",
                "dispositivos": [
                    {
                        "msisdn": 936000012,
                        "imsi": "730072200000012",
                        "imei": "353642093977934",
                        "modelo": "J2 Prime DS (Latam)",
                        "marca": "SAMSUNG"
                    }
                ]
            }
        },
        "codigo": 200
    }

## 2.14.- Obtener Datos de SIM
Método que devuelve los datos de una SIM a partir de una línea.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getSimInfo`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.14.2.2.- Respuesta de éxito

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

## 2.15.- Liberar Número
Método que permite liberar un número en cuarentena.

Los parámetros que recibe son los siguientes:

Ruta : GET `/liberarNumero`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| numeroTelefono    | int          |            |                | Número de teléfono          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| wsSessionId    | string       | ID de ws Session                                 |
| callID         | string       | Call ID                                          |
| callCode       | int          | Call code                                        |
| resultCode     | string       | Código de resultado                              |
| callMsg        | string       | Call message                                     |

### 2.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "numeroTelefono": 940158996
	}

### 2.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.15.2.1.- Respuesta de error

    {
        "callResult": {
            "wsSessionId": "EWSabb7ea00fe977d",
            "callID": "EWSabb7ea00fe977dCOR22d5416cf681a3",
            "callCode": 105,
            "resultCode": "ENTITY_NOT_FOUND",
            "callMsg": "Msisdn not found [numeroTelefono]"
        }
    }
  
#### 2.15.2.2.- Respuesta de éxito

    {
        "callResult": {
            "wsSessionId": "EWSabb7ea00fe977d",
            "callID": "EWSabb7ea00fe977dCOR22d4dc031f6f74",
            "callCode": 113,
            "resultCode": "MSISDN_PORTED",
            "callMsg": "MSISDN ported"
        }
    }

## 2.16.- Login
Método que permite obtener una sesión en la api de SUMA.

Los parámetros que recibe son los siguientes:

Ruta : GET `/login`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.16.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "El servidor de autorización denegó la solicitud"
        },
        "codigo": 401
    }
  
#### 2.16.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.17.- Logout
Método que permite borrar una sesión en la api de SUMA.

Los parámetros que recibe son los siguientes:

Ruta : GET `/logout`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.17.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.17.2.2.- Respuesta de éxito

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

## 2.18.- Actualizar Plan
Método que permite actualizar los montos de los bonos de un plan asignado a una suscripción, no funciona con bolsas sueltas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/updatePlan`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato    | Requerido      |             Descripción     |
|:-----------------:|:------------:|:----------:|:--------------:|----------------------------:|
| sid               | string       |            |                | Breve descripción           |
| bssRefID          | string       |            |                | Breve descripción           |
| renewalValue      | int          |            |                | Breve descripción           |
| value             | int          |            |                | Breve descripción           |
| tipo              | string       |            |                | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "sid": "SID69033_TS1618975474995_0",
        "bssRefID": "MM_Mimundo_M|PKGID130033_TS1619120874243|RP_MiMundo_M|567521",
        "renewalValue": 25600,
        "value": 25600,
        "tipo": "internet"
	}

### 2.18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.18.2.1.- Respuesta de error

    {
        "callResult": {
            "wsSessionId": "EWSabb7ea00fe977d",
            "callID": "EWSabb7ea00fe977dCOR22d628b46e0a08",
            "callCode": 105,
            "resultCode": "ENTITY_NOT_FOUND",
            "callMsg": "bssRef[bssRefID] not found"
        }
    }
  
#### 2.18.2.2.- Respuesta de éxito

	{
        ...
	}