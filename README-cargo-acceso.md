| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Cargo de Acceso

<!-- Índice -->
- [Documentación Api´s para Cargo de Acceso](#documentación-apis-para-cargo-de-acceso)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
    - [1.- Tarifas por Empresa](#1--tarifas-por-empresa)
        - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
        - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
            - [1.2.1- Respuesta de éxito](#121--respuesta-de-éxito)
    - [2.- Guardar Tarifas por Empresa](#2--guardar-tarifas-por-empresa)
        - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
        - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
            - [2.2.1- Respuesta de éxito](#221--respuesta-de-éxito)
    - [3.- Obtener Liquidaciones](#3--obtener-liquidaciones)
        - [3.1.- Respuesta de Salida](#31--respuesta-de-salida)
            - [3.1.1- Respuesta de éxito](#311--respuesta-de-éxito)
    - [4.- Empresas Habilitadas](#4--empresas-habilitadas)
        - [4.1.- Respuesta de Salida](#41--respuesta-de-salida)
            - [4.1.1- Respuesta de éxito](#411--respuesta-de-éxito)
    - [5.- Empresa Principal](#5--empresa-principal)
        - [5.1.- Respuesta de Salida](#51--respuesta-de-salida)
            - [5.1.1- Respuesta de éxito](#511--respuesta-de-éxito)
    - [6.- Obtener Años](#6--obtener-años)
        - [6.1.- Respuesta de Salida](#61--respuesta-de-salida)
            - [6.1.1- Respuesta de éxito](#611--respuesta-de-éxito)
    - [7.- Obtener Meses](#7--obtener-meses)
        - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
        - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
            - [7.2.1- Respuesta de éxito](#721--respuesta-de-éxito)
    - [8.- Obtener Liquidación por ID](#8--obtener-liquidación-por-id)
        - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
        - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
            - [8.2.1- Respuesta de éxito](#821--respuesta-de-éxito)
    - [9.- Generar PDF](#9--generar-pdf)
        - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
        - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
            - [9.2.1- Respuesta de éxito](#921--respuesta-de-éxito)
    - [10.- Exportar CDR](#10--exportar-cdr)
        - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
        - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
            - [10.2.1- Respuesta de éxito](#1021--respuesta-de-éxito)
    - [11.- Guardar Liquidación](#11--guardar-liquidación)
        - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [11.2.1- Respuesta de éxito](#1121--respuesta-de-éxito)



# Objetivo

Disponer Api's para realizar la gestión de Cargos de Acceso de Mundo.

# Restricciones

En este documento solo se describen Api's propias del sistema, no externas a este.


## 1.- Tarifas por Empresa
Método que permite consultar tarifas de la empresa corresponsal indicada.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/tarifasPorEmpresa`

**Parámetros de entrada:**

| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| mes            | string |          |           | Mes a buscar               |
| empresa        | int    |          |           | ID de la empresa           |
| ejercicio      | string |          |           | Año                        |

**Datos de salida:**
| Campo                  |  Tipo        |                         Descripción              |
|:-----------------------|:------------:|-------------------------------------------------:| 
| id                     | int          | ID de la tarifa                                  |
| fecha_inicio           | date         | Fecha de inicio                                  |
| tarifa_horario_normal  | int          | Tarifa en horario normal                         |
| tarifa_horario_reducido| int          | Tarifa en horario reducido                       |
| tarifa_horario_nocturno| int          | Tarifa en horario nocturno                       |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "mes": "7", 
                "empresa": 219, 
                "ejercicio": "2021"
        }

### 1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.2.1.- Respuesta de éxito

        [
                {
                        "id": 163,
                        "fecha_inicio": "2021-07-01",
                        "tarifa_horario_normal": 0.0436,
                        "tarifa_horario_reducido": 0.0326,
                        "tarifa_horario_nocturno": 0.0218
                },
                {
                        "id": 164,
                        "fecha_inicio": "2021-07-25",
                        "tarifa_horario_normal": 0.044,
                        "tarifa_horario_reducido": 0.033,
                        "tarifa_horario_nocturno": 0.022
                }
        ]

## 2.- Guardar Tarifas por Empresa
Método que permite guardar la tarifa ingresada asociada a la empresa corresponsal en BD.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/guardarTarifasPorEmpresa`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| empresa                  | int          |          |           | ID de la empresa           |
| ejercicio                | string       |          |           | Año                        |
| mes                      | string       |          |           | Número del mes             |
| ↓ tarifas                | array[object]|          |           |                            |
| ⤷ id                     | int          |          |           | ID de la tarifa            |
| ⤷ fecha_inicio           | timestamp    |          |           | Fecha de inicio            |
| ⤷ tarifa_horario_normal  | int          |          |           | Tarifa en horario normal   |
| ⤷ tarifa_horario_reducido| int          |          |           | Tarifa en horario reducido |
| ⤷ tarifa_horario_nocturno| int          |          |           | Tarifa en horario nocturno |
| tarifasEliminadas        | array[object]|          |           | Array con tarifas eliminadas|

**Datos de salida:**
| Campo                  |  Tipo        |                         Descripción              |
|:-----------------------|:------------:|-------------------------------------------------:| 
| id                     | int          | ID de la tarifa                                  |
| fecha_inicio           | date         | Fecha de inicio                                  |
| tarifa_horario_normal  | int          | Tarifa en horario normal                         |
| tarifa_horario_reducido| int          | Tarifa en horario reducido                       |
| tarifa_horario_nocturno| int          | Tarifa en horario nocturno                       |

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "empresa":219,
                "ejercicio":"2021",
                "mes":"7",
                "tarifas":[
                        {
                                "id":163,
                                "fecha_inicio":"2021-07-01T00:00:00.000-04:00",
                                "tarifa_horario_normal":0.0436,
                                "tarifa_horario_reducido":0.0326,
                                "tarifa_horario_nocturno":0.0218
                        },
                        {       "id":164,
                                "fecha_inicio":"2021-07-25T00:00:00.000-04:00",
                                "tarifa_horario_normal":0.044,
                                "tarifa_horario_reducido":0.033,
                                "tarifa_horario_nocturno":0.022
                        }
                ],
                "tarifasEliminadas":[]
        }

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 2.2.1.- Respuesta de éxito

        [
                {
                        "id": 163,
                        "fecha_inicio": "2021-07-01",
                        "tarifa_horario_normal": 0.0436,
                        "tarifa_horario_reducido": 0.0326,
                        "tarifa_horario_nocturno": 0.0218
                },
                {
                        "id": 164,
                        "fecha_inicio": "2021-07-25",
                        "tarifa_horario_normal": 0.044,
                        "tarifa_horario_reducido": 0.033,
                        "tarifa_horario_nocturno": 0.022
                }
        ]


## 3.- Obtener Liquidaciones
Método que permite generar lista de liquidaciones generadas por entidad corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/obtenerLiquidaciones`

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
| id                | int          | ID de la liquidación                             |
| id_empresa_origen | int          | ID de la empresa de origen                       |
| id_empresa_destino| int          | ID de la empresa de destino                      |
| ejercicio         | int          | Año                                              |
| mes               | int          | Mes                                              |
| id_horario        | int          | ID del horario                                   |
| monto_facturado   | int          | Monto facturado                                  |
| id_estado         | int          | ID del estado                                    |
| indicador_entrada | int          | Indicador de entrada                             |
| fecha_enviada     | date         | Fecha enviada                                    |
| created_at        | timestamp    | Fecha de creación                                |
| updated_at        | timestamp    | Última fecha de actualización                    |
| ↓ empresa_origen  | array[object]|                                                  |
| ⤷ ido             | int          | ID empresa origen                                |
| ⤷ nombre          | string       | Nombre de empresa de origen                      |
| ↓ empresa_destino | array[object]|                                                  |
| ⤷ ido             | int          | ID empresa destino                               |
| ⤷ nombre          | string       | Nombre de empresa de destino                     |
| ⤷ dias_impugnacion| int          | Cantidad de dias de impugnación                  |
| ↓ estado          | array[object]|                                                  |
| ⤷ id              | int          | ID del estado                                    |
| ⤷ nombre          | string       | Descripción del estado                           |

### 3.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.1.- Respuesta de éxito

        {
                "current_page": 1,
                "data": [
                        {
                                "id": 472,
                                "id_empresa_origen": 316,
                                "id_empresa_destino": 348,
                                "ejercicio": 2021,
                                "mes": 8,
                                "id_horario": 4,
                                "monto_facturado": 0,
                                "id_estado": 1,
                                "indicador_entrada": 1,
                                "fecha_enviada": "2021-09-10",
                                "created_at": "2021-09-10 16:26:57",
                                "updated_at": "2021-09-10 16:26:57",
                                "empresa_origen": {
                                        "ido": 316,
                                        "nombre": "316 - TELSUR"
                                },
                                "empresa_destino": {
                                        "ido": 348,
                                        "nombre": "348 - PACIFICO CABLE",
                                        "dias_impugnacion": 0
                                },
                                "estado": {
                                        "id": 1,
                                        "nombre": "Ingresada"
                                }
                        }
                ],
                "first_page_url": "...URL/ObtenerLiquidaciones?page=1",
                "from": 1,
                "last_page": 1,
                "last_page_url": "...URL/ObtenerLiquidaciones?page=1",
                "next_page_url": null,
                "path": "...URL/ObtenerLiquidaciones",
                "per_page": null,
                "prev_page_url": null,
                "to": 404,
                "total": 404
        }


## 4.- Empresas Habilitadas
Método que permite obtener lista de empresas corresponsales.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/empresasHabilitadas`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ido            | int          | ID de la empresa                                 |
| nombre         | string       | Nombre de la empresa                             |
| rut            | string       | Rut de la empresa                                |

### 4.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.1.1.- Respuesta de éxito

        [
                {
                        "ido": 0,
                        "nombre": "- TODOS -",
                        "rut": "0"
                },
                {
                        "ido": 120,
                        "nombre": "120 - GLOBUS 120",
                        "rut": "968874209"
                },
                {
                        "ido": 151,
                        "nombre": "151 - ASTRO S.A.",
                        "rut": "968671308"
                },
                {
                        "ido": 159,
                        "nombre": "159 - GTD LARGA DISTANCIA",
                        "rut": "96894200K"
                },
                ...
        ]


## 5.- Empresa Principal 
Método que permite obtener lista de empresa principal Mundo Pacifico Móvil u Hogar como corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/empresasPrincipales`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ido            | int          | ID de la empresa                                 |
| nombre         | string       | Nombre de la empresa                             |

### 5.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.1.1.- Respuesta de éxito

        [
                {
                        "ido": 0,
                        "nombre": "- TODOS -"
                },
                {
                        "ido": 250,
                        "nombre": "250 - PACIFICO CABLE (MOVIL)"
                },
                {
                        "ido": 348,
                        "nombre": "348 - PACIFICO CABLE"
                }
        ]


## 6.- Obtener Años
Método que permite obtener lista de años anteriores como un año más a futuro.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/getListaAnos`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ejercicio      | int          | Año                                              |

### 6.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 6.1.1.- Respuesta de éxito

        [
                {
                        "ejercicio": 2019
                },
                {
                        "ejercicio": 2021
                },
                {
                        "ejercicio": 2020
                }
        ]


## 7.- Obtener Meses
Método que permite obtener lista de meses ya ingresados según las liquidaciones existentes del año seleccionado.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/getListaMes`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| ↓ data                   | array[object]|          |           |                            |
| ⤷ año                    | int          |          |           | Año                        |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | int          | Número del mes                                   |

### 7.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "data":{
                        "año":2021
                }
        }

### 7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 7.2.1.- Respuesta de éxito

        [
                {
                        "mes": 8
                },
                {
                        "mes": 7
                },
                {
                        "mes": 1
                },
                {
                        "mes": 5
                },
                {
                        "mes": 4
                },
                {
                        "mes": 2
                },
                {
                        "mes": 6
                },
                {
                        "mes": 3
                }
        ]



## 8.- Obtener Liquidación por ID
Método que permite cargar datos de liquidación existente seleccionado de la grilla, para visualizar lo generado.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/cargarLiquidacionesId`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| id                       | int          |          | Si        | ID de la liquidación       |

**Datos de salida:**
| Campo                       |  Tipo        |                         Descripción              |
|:----------------------------|:------------:|-------------------------------------------------:| 
| ↓ liquidacion               | array[object]|                                                  |
| ⤷ id                        | string       | ID de la liquidación                             |
| ⤷ estado                    | string       | Descripción del estado                           |
| ⤷ mes                       | string       | Mes                                              |
| ⤷ ejercicio                 | string       | Año                                              |
| ⤷ indicador_entrada         | string       | Indicador de entrada                             |
| ↓↓ empresa_liquidacion      | array[object]|                                                  |
| ⤷ ido                       | string       | ID de empresa                                    |
| ⤷ rut                       | string       | Rut de la empresa                                |
| ⤷ razon_social              | string       | Razón social                                     |
| ⤷ nombre                    | string       | Nombre de la empresa                             |
| ↓↓ empresa_origen           | array[object]|                                                  |
| ⤷ ido                       | string       | ID de empresa de origen                          |
| ⤷ rut                       | string       | Rut de empresa de origen                         |
| ⤷ razon_social              | string       | Razón social de la empresa                       |
| ⤷ nombre                    | string       | Nombre de la empresa                             |
| ↓↓ horario                  | array[object]|                                                  |
| ⤷ id                        | string       | ID del horario                                   |
| ⤷ nombre                    | string       | Nombre del horario                               |
| ↓↓ periodos                 | array[object]|                                                  |
| ⤷ dia_inicio                | string       | Día de inicio                                    |
| ⤷ dia_fin                   | string       | Día de fin                                       |
| ⤷ tarifa_horario_normal     | string       | Tarifa de horario normal                         |
| ⤷ tarifa_horario_nocturno   | string       | Tarifa de horario nocturno                       |
| ⤷ tarifa_horario_reducido   | string       | Tarifa de horario reducido                       |
| ↓↓↓ detalle                 | array[object]|                                                  |
| ⤷ tipo_servicio             | string       | ID de tipo de servicio                           |
| ⤷ servicio                  | string       | Descripción del tipo de servicio                 |
| ⤷ monto_normal              | string       | Monto normal                                     |
| ⤷ monto_nocturno            | string       | Monto nocturno                                   |
| ⤷ monto_reducido            | string       | Monto reducido                                   |
| ⤷ cantidad_llamadas_normal  | string       | Cantidad de llamadas horario normal              |
| ⤷ cantidad_llamadas_nocturno| string       | Cantidad de llamadas horario nocturno            |
| ⤷ cantidad_llamadas_reducido| string       | Cantidad de llamadas horario reducido            |
| ⤷ cantidad_segundos_normal  | string       | Cantidad de segundos horario normal              |
| ⤷ cantidad_segundos_nocturno| string       | Cantidad de segundos horario nocturno            |
| ⤷ cantidad_segundos_reducido| string       | Cantidad de segundos horario reducido            |
| ⤷ monto_total               | string       | Monto total                                      |
| ⤷ cantidad_total            | string       | Cantidad total                                   |
| ⤷ segundo_total             | string       | Segundos totales                                 |
| ↓↓ totales                  | array[object]|                                                  |
| ⤷ monto                     | string       | Monto                                            |
| ⤷ monto_normal              | string       | Monto en horario normal                          |
| ⤷ monto_nocturno            | string       | Monto en horario nocturno                        |
| ⤷ monto_reducido            | string       | Monto en horario reducido                        |
| ⤷ cantidad_normal           | string       | Cantidad de llamadas en horario normal           |
| ⤷ cantidad_nocturno         | string       | Cantidad de llamadas en horario nocturno         |
| ⤷ cantidad_reducido         | string       | Cantidad de llamadas en horario reducido         |
| ⤷ segundos_normal           | string       | Cantidad de segundos horario normal              |
| ⤷ segundos_nocturno         | string       | Cantidad de segundos horario nocturno            |
| ⤷ segundos_reducido         | string       | Cantidad de segundos horario reducido            |
| ⤷ monto_total               | string       | Monto total                                      |
| ⤷ cantidad_total            | string       | Cantidad de llamadas totales                     |
| ⤷ segundos_total            | string       | Cantidad de segundos totales                     |
| ⤷ total_neto                | string       | Total neto                                       |
| ⤷ iva                       | string       | IVA                                              |

### 8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "id": 33
	}

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 8.2.1.- Respuesta de éxito

        {
                "liquidacion": {
                        "id": "33",
                        "estado": "Ingresada",
                        "mes": "9",
                        "ejercicio": "2019",
                        "indicador_entrada": "0",
                        "empresa_liquidacion": {
                                "ido": "322",
                                "rut": "966974109",
                                "razon_social": "ENTEL TELEFONIA LOCAL S.A. (322)",
                                "nombre": "322 - ENTELPHONE"
                        },
                        "empresa_origen": {
                                "ido": "348",
                                "rut": "967224006",
                                "razon_social": "PACIFICO CABLE SpA (348)",
                                "nombre": "348 - PACIFICO CABLE"
                        },
                        "horario": {
                                "id": "4",
                                "nombre": "Horario 4"
                        },
                        "periodos": [
                                {
                                        "dia_inicio": "1",
                                        "dia_fin": "24",
                                        "tarifa_horario_normal": "0.0850",
                                        "tarifa_horario_nocturno": "0.0425",
                                        "tarifa_horario_reducido": "0.0637",
                                        "detalle": [
                                        {
                                                "tipo_servicio": "1",
                                                "servicio": "VOIP",
                                                "monto_normal": "628109",
                                                "monto_nocturno": "19414",
                                                "monto_reducido": "161479",
                                                "cantidad_llamadas_normal": "33599",
                                                "cantidad_llamadas_nocturno": "3874",
                                                "cantidad_llamadas_reducido": "10102",
                                                "cantidad_segundos_normal": "7385871",
                                                "cantidad_segundos_nocturno": "456597",
                                                "cantidad_segundos_reducido": "2535101",
                                                "monto_total": "809002",
                                                "cantidad_total": "47575",
                                                "segundo_total": "10377569"
                                        },
                                        ...
                                        ]
                                },
                                ...
                        ],
                        "totales": {
                                "monto": "868116",
                                "monto_normal": "868116",
                                "monto_nocturno": "31993",
                                "monto_reducido": "213938",
                                "cantidad_normal": "47625",
                                "cantidad_nocturno": "9096",
                                "cantidad_reducido": "13348",
                                "segundos_normal": "10187074",
                                "segundos_nocturno": "751176",
                                "segundos_reducido": "3351345",
                                "monto_total": "1114047",
                                "cantidad_total": "70069",
                                "segundos_total": "14289595",
                                "total_neto": "1325715.93",
                                "iva": "211668.93"
                        }
                }
        }

## 9.- Generar PDF
Método que permite generar archivo descargable en pdf de liquidación generada.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/generarPDF`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| ↓ data                   | array[object]|          |           |                            |
| ⤷ titulo                 | string       |          | Si        | Título del pdf             |
| ⤷ periodos               | string       |          | Si        | Periodos                   |
| ⤷ totales                | string       |          | Si        | Totales                    |
| ⤷ empresaDestino         | string       |          | Si        | Empresa de destino         |

### 9.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "data":{
                        "titulo":"LIQUIDACIÓN SEPTIEMBRE 2019",
                        "periodos":"[{\"dia_inicio\":\"1\",\"dia_fin\":\"24\",\"tarifa_horario_normal\":\"0.0850\",\"tarifa_horario_nocturno\":\"0.0425\",\"tarifa_horario_reducido\":\"0.0637\",\"detalle\":[{\"tipo_servicio\":\"1\",\"servicio\":\"VOIP\",\"monto_normal\":\"628109\",\"monto_nocturno\":\"19414\",\"monto_reducido\":\"161479\",\"cantidad_llamadas_normal\":\"33599\",\"cantidad_llamadas_nocturno\":\"3874\",\"cantidad_llamadas_reducido\":\"10102\",\"cantidad_segundos_normal\":\"7385871\",\"cantidad_segundos_nocturno\":\"456597\",\"cantidad_segundos_reducido\":\"2535101\",\"monto_total\":\"809002\",\"cantidad_total\":\"47575\",\"segundo_total\":\"10377569\"},{\"tipo_servicio\":\"2\",\"servicio\":\"800\",\"monto_normal\":\"11939\",\"monto_nocturno\":\"3383\",\"monto_reducido\":\"1414\",\"cantidad_llamadas_normal\":\"2017\",\"cantidad_llamadas_nocturno\":\"2121\",\"cantidad_llamadas_reducido\":\"173\",\"cantidad_segundos_normal\":\"140399\",\"cantidad_segundos_nocturno\":\"79574\",\"cantidad_segundos_reducido\":\"22202\",\"monto_total\":\"16736\",\"cantidad_total\":\"4311\",\"segundo_total\":\"242175\"}]},{\"dia_inicio\":\"25\",\"dia_fin\":\"30\",\"tarifa_horario_normal\":\"0.0857\",\"tarifa_horario_nocturno\":\"0.0428\",\"tarifa_horario_reducido\":\"0.0643\",\"detalle\":[{\"tipo_servicio\":\"1\",\"servicio\":\"VOIP\",\"monto_normal\":\"219231\",\"monto_nocturno\":\"4545\",\"monto_reducido\":\"50648\",\"cantidad_llamadas_normal\":\"10375\",\"cantidad_llamadas_nocturno\":\"716\",\"cantidad_llamadas_reducido\":\"3005\",\"cantidad_segundos_normal\":\"2557700\",\"cantidad_segundos_nocturno\":\"106268\",\"cantidad_segundos_reducido\":\"787858\",\"monto_total\":\"274424\",\"cantidad_total\":\"14096\",\"segundo_total\":\"3451826\"},{\"tipo_servicio\":\"2\",\"servicio\":\"800\",\"monto_normal\":\"8837\",\"monto_nocturno\":\"4651\",\"monto_reducido\":\"397\",\"cantidad_llamadas_normal\":\"1634\",\"cantidad_llamadas_nocturno\":\"2385\",\"cantidad_llamadas_reducido\":\"68\",\"cantidad_segundos_normal\":\"103104\",\"cantidad_segundos_nocturno\":\"108737\",\"cantidad_segundos_reducido\":\"6184\",\"monto_total\":\"13885\",\"cantidad_total\":\"4087\",\"segundo_total\":\"218025\"}]}]",
                        "totales":"{\"monto\":\"868116\",\"monto_normal\":\"868116\",\"monto_nocturno\":\"31993\",\"monto_reducido\":\"213938\",\"cantidad_normal\":\"47625\",\"cantidad_nocturno\":\"9096\",\"cantidad_reducido\":\"13348\",\"segundos_normal\":\"10187074\",\"segundos_nocturno\":\"751176\",\"segundos_reducido\":\"3351345\",\"monto_total\":\"1114047\",\"cantidad_total\":\"70069\",\"segundos_total\":\"14289595\",\"total_neto\":\"1325715.93\",\"iva\":\"211668.93\"}",
                        "empresaDestino":"{\"ido\":\"348\",\"rut\":\"967224006\",\"razon_social\":\"PACIFICO CABLE SpA (348)\",\"nombre\":\"348 - PACIFICO CABLE\"}"
                }
        }

### 9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 9.2.1.- Respuesta de éxito

`Archivo PDF con liquidación generada`


## 10.- Exportar CDR
Método que permite exportar en xls archivo cdr de la liquidación existente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/ObtenerCdr`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| ido                      | int          |          |           |  ID empresa origen         |
| idd                      | int          |          |           |  ID empresa destino        |
| anio                     | int          |          |           |  Año                       |
| mes                      | int          |          |           |  Mes                       |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "ido": 348,
                "idd": 322,
                "anio": 2019,
                "mes": 9
	}

### 10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 10.2.1.- Respuesta de éxito

	{
        ...
	}


## 11.- Guardar Liquidación
Método que permite guardar liquidación generada del corresponsal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/guardarLiquidacion`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| id_estado                | int          |          |           | ID del estado              |
| id_empresa_origen        | int          |          | Si        | ID de la empresa de origen |
| id_empresa_destino       | int          |          | Si        | ID de la empresa de destino|
| indicador_entrada        | int          |          |           | Indicador de entrada       |
| detalle                  | array[object]|          |           | Array con detalle          |
| mes                      | int          |          |           | Mes                        |
| ejercicio                | int          |          |           | Año                        |

**Datos de salida:**
| Campo            |  Tipo        |                         Descripción              |
|:-----------------|:------------:|-------------------------------------------------:| 
| ID DE LIQUIDACIÓN| int          | ID de la liquidación generada                    |

### 11.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "id_estado":1,
                "id_empresa_origen":348,
                "id_empresa_destino":322,
                "indicador_entrada":1,
                "detalle":[],
                "mes":0,
                "ejercicio":0
        }

### 11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 11.2.1.- Respuesta de éxito

`479`