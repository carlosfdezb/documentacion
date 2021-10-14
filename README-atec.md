| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para ATEC

<!-- Índice -->
- [Documentación Api´s para ATEC](#documentación-apis-para-atec)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Recursos](#1--recursos)
    - [1.1.- Listar Horarios](#11--listar-horarios)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Guardar Horarios](#12--guardar-horarios)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- Modificar Horarios](#13--modificar-horarios)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
    - [1.4.- Eliminar Horarios](#14--eliminar-horarios)
        - [1.4.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
        - [1.4.2.- Respuesta de Salida](#142--respuesta-de-salida)
            - [1.4.2.1- Respuesta de error](#1421--respuesta-de-error)
            - [1.4.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
    - [1.5.- Horarios Cliente Listar](#15--horarios-cliente-listar)
        - [1.5.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
        - [1.5.2.- Respuesta de Salida](#152--respuesta-de-salida)
            - [1.5.2.1- Respuesta de error](#1521--respuesta-de-error)
            - [1.5.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
    - [1.6.- Horarios Turno Listar](#16--horarios-turno-listar)
        - [1.6.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
        - [1.6.2.- Respuesta de Salida](#162--respuesta-de-salida)
            - [1.6.2.1- Respuesta de error](#1621--respuesta-de-error)
            - [1.6.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
    - [1.7.- Regiones](#17--regiones)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de error](#1721--respuesta-de-error)
            - [1.7.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
    - [1.8.- Provincias](#18--provincias)
        - [1.8.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
        - [1.8.2.- Respuesta de Salida](#182--respuesta-de-salida)
            - [1.8.2.1- Respuesta de error](#1821--respuesta-de-error)
            - [1.8.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
    - [1.9.- Comunas](#19--comunas)
        - [1.9.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
        - [1.9.2.- Respuesta de Salida](#192--respuesta-de-salida)
            - [1.9.2.1- Respuesta de error](#1921--respuesta-de-error)
            - [1.9.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
    - [1.10.- Ejecutivos Zonas Listar](#110--ejecutivos-zonas-listar)
        - [1.10.1.- Ejemplo de llamada](#1101--ejemplo-de-llamada)
        - [1.10.2.- Respuesta de Salida](#1102--respuesta-de-salida)
            - [1.10.2.1- Respuesta de error](#11021--respuesta-de-error)
            - [1.10.2.2- Respuesta de éxito](#11022--respuesta-de-éxito)
    - [1.11.- Ejecutivos Zonas Guardar](#111--ejecutivos-zonas-guardar)
        - [1.11.1.- Ejemplo de llamada](#1111--ejemplo-de-llamada)
        - [1.11.2.- Respuesta de Salida](#1112--respuesta-de-salida)
            - [1.11.2.1- Respuesta de error](#11121--respuesta-de-error)
            - [1.11.2.2- Respuesta de éxito](#11122--respuesta-de-éxito)
    - [1.12.- Ejecutivos Zonas Eliminar](#112--ejecutivos-zonas-eliminar)
        - [1.12.1.- Ejemplo de llamada](#1121--ejemplo-de-llamada)
        - [1.12.2.- Respuesta de Salida](#1122--respuesta-de-salida)
            - [1.12.2.1- Respuesta de error](#11221--respuesta-de-error)
            - [1.12.2.2- Respuesta de éxito](#11222--respuesta-de-éxito)
    - [1.13.- Ejecutivos Crear](#113--ejecutivos-crear)
        - [1.13.1.- Ejemplo de llamada](#1131--ejemplo-de-llamada)
        - [1.13.2.- Respuesta de Salida](#1132--respuesta-de-salida)
            - [1.13.2.1- Respuesta de error](#11321--respuesta-de-error)
            - [1.13.2.2- Respuesta de éxito](#11322--respuesta-de-éxito)
    - [1.14.- Ejecutivos Modificar](#114--ejecutivos-modificar)
        - [1.14.1.- Ejemplo de llamada](#1141--ejemplo-de-llamada)
        - [1.14.2.- Respuesta de Salida](#1142--respuesta-de-salida)
            - [1.14.2.1- Respuesta de error](#11421--respuesta-de-error)
            - [1.14.2.2- Respuesta de éxito](#11422--respuesta-de-éxito)
    - [1.15.- Ejecutivos Eliminar](#115--ejecutivos-eliminar)
        - [1.15.1.- Ejemplo de llamada](#1151--ejemplo-de-llamada)
        - [1.15.2.- Respuesta de Salida](#1152--respuesta-de-salida)
            - [1.15.2.1- Respuesta de error](#11521--respuesta-de-error)
            - [1.15.2.2- Respuesta de éxito](#11522--respuesta-de-éxito)

            

  - [x.- aa](#x--aa)
    - [x.y.- Teex Listar](#xy--teex-listar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Teex Guardar](#xy--teex-guardar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Teex Modificar](#xy--teex-modificar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Teex Eliminar](#xy--teex-eliminar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Supervisor Despacho Listar](#xy--supervisor-despacho-listar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Supervisor Despacho Listar por Zona](#xy--supervisor-despacho-listar-por-zona)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Supervisor Despacho Guardar](#xy--supervisor-despacho-guardar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Supervisor Despacho Modificar](#xy--supervisor-despacho-modificar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Supervisor Despacho Eliminar](#xy--supervisor-despacho-eliminar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Listar](#xy--técnico-listar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Guardar](#xy--técnico-guardar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Modificar](#xy--técnico-modificar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Eliminar](#xy--técnico-eliminar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Listar Calendario](#xy--técnico-listar-calendario)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnico Sin Asignar](#xy--técnico-sin-asignar)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Técnicos Asignados](#xy--técnicos-asignados)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Asignar Técnicos Ejecutivos](#xy--asignar-técnicos-ejecutivos)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)
    - [x.y.- Eliminar Técnicos Ejecutivos](#xy--eliminar-técnicos-ejecutivos)
        - [x.y.1.- Ejemplo de llamada](#xy1--ejemplo-de-llamada)
        - [x.y.2.- Respuesta de Salida](#xy2--respuesta-de-salida)
            - [x.y.2.1- Respuesta de error](#xy21--respuesta-de-error)
            - [x.y.2.2- Respuesta de éxito](#xy22--respuesta-de-éxito)



# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Recursos
## 1.1.- Listar Horarios
Método que lista los horarios de atención o trabajo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/horarios/listar`

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| hora_id         | int          | ID del horario                                   |
| hora_descripcion| string       | Descripción del horario                          |
| hora_ini        | time         | Hora de inicio                                   |
| hora_fin        | time         | Hora de fin                                      |
| hora_tipo       | string       | Tipo de hora                                     |
| created_at      | timestamp    | Fecha de creación                                |
| updated_at      | timestamp    | Última fecha de actualización                    |

### 1.1.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.1.1.1.- Respuesta de éxito

    [
        {
            "hora_id": 3,
            "hora_descripcion": "TURNO UNO",
            "hora_ini": "08:00:00",
            "hora_fin": "18:00:00",
            "hora_tipo": "TURNO",
            "created_at": null,
            "updated_at": "2020-05-18 16:20:15"
        },
        {
            "hora_id": 4,
            "hora_descripcion": "TURNO DOS",
            "hora_ini": "11:00:00",
            "hora_fin": "22:00:00",
            "hora_tipo": "TURNO",
            "created_at": null,
            "updated_at": "2020-05-20 17:51:38"
        },
        ...
    ]


## 1.2.- Guardar Horarios
Método que permite guardar horarios de atención o trabajo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/horarios/guardar`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción     |
|:---------------:|:------------:|:-----------:|:--------------:|----------------------------:|
| hora_descripcion| string       |             | Si             | Descripción del horario     |
| hora_ini        | time         |             |                | Hora de inicio              |
| hora_fin        | time         |             |                | Hora de fin                 |
| hora_tipo       | string       |             |                | Tipo de hora                |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "hora_descripcion": "PRUEBA",
        "hora_ini": "09:00",
        "hora_fin": "11:11",
        "hora_tipo": "CLIENTE"	
    }

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

    {
        "mensaje": "Ya existe esta descripción"
    }
  
#### 1.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 1.3.- Modificar Horarios
Método que permite modificar horarios de trabajo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/horarios/modificar`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción     |
|:---------------:|:------------:|:-----------:|:--------------:|----------------------------:|
| hora_id         | int          |             | Si             | ID del horario              |
| hora_descripcion| string       |             | Si             | Descripción del horario     |
| hora_ini        | time         |             |                | Hora de inicio              |
| hora_fin        | time         |             |                | Hora de fin                 |
| hora_tipo       | string       |             |                | Tipo de hora                |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "hora_id" : 76,
        "hora_descripcion": "PRUEBA-EDIT",
        "hora_ini": "09:00:00",
        "hora_fin": "11:11:00",
        "hora_tipo": "CLIENTE"
    }

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

    {
        ...
    }
  
#### 1.3.2.2.- Respuesta de éxito

    {
        "mensaje": "MODIFICADO"
    }


## 1.4.- Eliminar Horarios
Método que permite eliminar un horario mediante un id.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/horarios/eliminar`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción     |
|:---------------:|:------------:|:-----------:|:--------------:|----------------------------:|
| hora_id         | int          |             | Si             | ID del horario              |

### 1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "hora_id" : 75
    }

### 1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.4.2.1.- Respuesta de error

    {
        ...
    }
  
#### 1.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ELIMINADO"
    }


## 1.5.- Horarios Cliente Listar
Método que permite listar solo los horarios de clientes.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/horarios/listar/cliente`

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| hora_id         | int          | ID del horario                                   |
| hora_descripcion| string       | Descripción del horario                          |
| hora_ini        | time         | Hora de inicio                                   |
| hora_fin        | time         | Hora de fin                                      |
| hora_tipo       | string       | Tipo de hora                                     |
| created_at      | timestamp    | Fecha de creación                                |
| updated_at      | timestamp    | Última fecha de actualización                    |
| hora_label      | string       | Rango de horario                                 |


### 1.5.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.5.1.1.- Respuesta de éxito

    [
        {
            "hora_id": 1,
            "hora_descripcion": "ATENCION CLIENTES AM",
            "hora_ini": "08:00:00",
            "hora_fin": "14:00:00",
            "hora_tipo": "CLIENTE",
            "created_at": null,
            "updated_at": "2020-05-26 18:05:38",
            "hora_label": "08:00:00 a 14:00:00"
        },
        {
            "hora_id": 2,
            "hora_descripcion": "ATENCION CLIENTES PM",
            "hora_ini": "14:00:00",
            "hora_fin": "19:00:00",
            "hora_tipo": "CLIENTE",
            "created_at": null,
            "updated_at": "2020-04-13 14:19:10",
            "hora_label": "14:00:00 a 19:00:00"
        }
    ]


## 1.6.- Horarios Turno Listar
Método que permite listar solo los horarios de trabajos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/horarios/listar/turno`

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| hora_id         | int          | ID del horario                                   |
| hora_descripcion| string       | Descripción del horario                          |
| hora_ini        | time         | Hora de inicio                                   |
| hora_fin        | time         | Hora de fin                                      |
| hora_tipo       | string       | Tipo de hora                                     |
| created_at      | timestamp    | Fecha de creación                                |
| updated_at      | timestamp    | Última fecha de actualización                    |


### 1.6.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.6.1.1.- Respuesta de éxito

    [
        {
            "hora_id": 3,
            "hora_descripcion": "TURNO UNO",
            "hora_ini": "08:00:00",
            "hora_fin": "18:00:00",
            "hora_tipo": "TURNO",
            "created_at": null,
            "updated_at": "2020-05-18 16:20:15"
        },
        {
            "hora_id": 4,
            "hora_descripcion": "TURNO DOS",
            "hora_ini": "11:00:00",
            "hora_fin": "22:00:00",
            "hora_tipo": "TURNO",
            "created_at": null,
            "updated_at": "2020-05-20 17:51:38"
        }
    ]

## 1.7.- Regiones
Método que devuelve las regiones que ATEC transforma desde los archivos de BU a su propia tabla.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/regiones`

**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:|
| regi_id         | int          | ID de la región                                  |
| regi_descripcion| string       | Nombre de la región                              |
| created_at      | timestamp    | Fecha de creación                                |
| updated_at      | timestamp    | Última fecha de actualización                    |


### 1.7.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.7.1.1.- Respuesta de éxito

    [
        {
            "regi_id": 1,
            "regi_descripcion": "BIOBIO",
            "created_at": null,
            "updated_at": null
        },
        {
            "regi_id": 2,
            "regi_descripcion": "LA ARAUCANIA",
            "created_at": null,
            "updated_at": null
        },
        ...
    ]


## 1.8.- Provincias
Método que devuelve las provincias que son cargadas por archivos de BU.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/provincias`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción     |
|:---------------:|:------------:|:-----------:|:--------------:|----------------------------:|
| regi_id         | int          |             | Si             | ID de la región             |


**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:|
| prov_id         | int          | ID de la provincia                               |
| regi_id         | int          | ID de la región                                  |
| prov_descripcion| string       | Nombre de la provincia                           |

### 1.8.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "regi_id": 1
    }


### 1.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.8.2.1.- Respuesta de éxito

    [
        {
            "prov_id": 1,
            "regi_id": 1,
            "prov_descripcion": "ARAUCO"
        },
        {
            "prov_id": 2,
            "regi_id": 1,
            "prov_descripcion": "BIOBIO"
        },
        {
            "prov_id": 3,
            "regi_id": 1,
            "prov_descripcion": "CONCEPCION"
        },
        ...
    ]


## 1.9.- Comunas
Método que devuelve lista con comunas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/comunas`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción     |
|:---------------:|:------------:|:-----------:|:--------------:|----------------------------:|
| prov_id         | int          |             | Si             | ID de la provincia          |


**Datos de salida:**
| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:|
| comu_id         | int          | ID de la comuna                                  |
| prov_id         | int          | ID de la provincia                               |
| comu_descripcion| string       | Nombre de la comuna                              |

### 1.9.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "prov_id": 3
    }


### 1.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.9.2.1.- Respuesta de éxito

    [
        {
            "comu_id": 13,
            "prov_id": 3,
            "comu_descripcion": "CONCEPCION"
        },
        {
            "comu_id": 14,
            "prov_id": 3,
            "comu_descripcion": "CORONEL"
        },
        {
            "comu_id": 12,
            "prov_id": 3,
            "comu_descripcion": "CHIGUAYANTE"
        },
        ...
    ]


## 1.10.- Ejecutivos Zonas Listar
Método que devuelve ejecutivos de despacho.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/ejecutivos/zonas/listar`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido      |             Descripción        |
|:---------------:|:------------:|:-----------:|:--------------:|-------------------------------:|
| mail            | string       |             | Si             | Correo electrónico de ejecutivo|


**Datos de salida:**
| Campo               |  Tipo        |                         Descripción              |
|:--------------------|:------------:|-------------------------------------------------:|
| cate_id             | int          |                                  |
| cate_nombre         | string       |                                  |
| comu_id             | int          |                                  |
| cate_direccion      | string       |                                  |
| cate_coor_x         | string       |                                  |
| cate_coor_y         | string       |                                  |
| created_at          | timestamp    |                                  |
| updated_at          | timestamp    |                                  |
| cate_activa_capacity| boolean      |                                  |
| cate_activa_apolo   | boolean      |                                  |
| existe              | boolean      |                                  |

### 1.10.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "mail": "kevin.orozco@mundopacifico.cl"
    }


### 1.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.10.2.1.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "cate_id": 10,
                "cate_nombre": "CT CONCEPCION",
                "comu_id": 13,
                "cate_direccion": "INDEPENDENCIA 2470, CONCEPCION",
                "cate_coor_x": "-36.805061",
                "cate_coor_y": "-73.057610",
                "created_at": null,
                "updated_at": null,
                "cate_activa_capacity": true,
                "cate_activa_apolo": false,
                "existe": true
            },
            ...
        ]
    }