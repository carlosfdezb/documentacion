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

| Campo          |  Tipo  | Formato  | Requerido | Descripción                |
|:---------------|:------:|:--------:|:---------:|---------------------------:|
| mes            | string |          |           | Mes a buscar               |
| empresa        | int    |          |           | ID de la empresa           |
| ejercicio      | string |          |           | Ejercicio                  |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "mes": "7", 
                "empresa": 219, 
                "ejercicio": "2021"
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

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| empresa                  | int          |          |           | ID de la empresa           |
| ejercicio                | string       |          |           | Ejercicio                  |
| mes                      | string       |          |           | Número del mes             |
| ↓ tarifas                | array[object]|          |           |                            |
| ⤷ id                     | int          |          |           | ID de la tarifa            |
| ⤷ fecha_inicio           | timestamp    |          |           | Fecha de inicio            |
| ⤷ tarifa_horario_normal  | int          |          |           | Tarifa en horario normal   |
| ⤷ tarifa_horario_reducido| int          |          |           | Tarifa en horario reducido |
| ⤷ tarifa_horario_nocturno| int          |          |           | Tarifa en horario nocturno |
| tarifasEliminadas        | array[object]|          |           | Array con tarifas eliminadas|

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

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

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
| id                | int          | Breve descripción                                |
| id_empresa_origen | int          | Breve descripción                                |
| id_empresa_destino| int          | Breve descripción                                |
| ejercicio         | int          | Breve descripción                                |
| mes               | int          | Breve descripción                                |
| id_horario        | int          | Breve descripción                                |
| monto_facturado   | int          | Breve descripción                                |
| id_estado         | int          | Breve descripción                                |
| indicador_entrada | int          | Breve descripción                                |
| fecha_enviada     | date         | Breve descripción                                |
| created_at        | timestamp    | Breve descripción                                |
| updated_at        | timestamp    | Breve descripción                                |
| ↓ empresa_origen  | array[object]| Breve descripción                                |
| ⤷ ido             | int          | Breve descripción                                |
| ⤷ nombre          | string       | Breve descripción                                |
| ↓ empresa_destino | array[object]| Breve descripción                                |
| ⤷ ido             | int          | Breve descripción                                |
| ⤷ nombre          | string       | Breve descripción                                |
| ⤷ dias_impugnacion| int          | Breve descripción                                |
| ↓ estado          | array[object]| Breve descripción                                |
| ⤷ id              | int          | Breve descripción                                |
| ⤷ nombre          | string       | Breve descripción                                |

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


## 4.- empresasHabilitadas
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


## 5.- empresasPrincipales
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


## 6.- getListaAnos
Método que permite obtener lista de años anteriores como un año más a futuro.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/getListaAnos`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ejercicio      | int          | Breve descripción                                |

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


## 7.- getListaMes
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



## 8.- cargarLiquidacionesId
Método que permite cargar datos de liquidación existente seleccionado de la grilla, para visualizar lo generado.

Los parámetros que recibe son los siguientes:

Ruta : GET `/cargos/cargarLiquidacionesId`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| id                       | int          |          | Si        |                            |

**Datos de salida:**
| Campo                       |  Tipo        |                         Descripción              |
|:----------------------------|:------------:|-------------------------------------------------:| 
| ↓ liquidacion               | array[object]| Breve descripción                                |
| ⤷ id                        | string       | Breve descripción                                |
| ⤷ estado                    | string       | Breve descripción                                |
| ⤷ mes                       | string       | Breve descripción                                |
| ⤷ ejercicio                 | string       | Breve descripción                                |
| ⤷ indicador_entrada         | string       | Breve descripción                                |
| ↓↓ empresa_liquidacion      | array[object]| Breve descripción                                |
| ⤷ ido                       | string       | Breve descripción                                |
| ⤷ rut                       | string       | Breve descripción                                |
| ⤷ razon_social              | string       | Breve descripción                                |
| ⤷ nombre                    | string       | Breve descripción                                |
| ↓↓ empresa_origen           | array[object]| Breve descripción                                |
| ⤷ ido                       | string       | Breve descripción                                |
| ⤷ rut                       | string       | Breve descripción                                |
| ⤷ razon_social              | string       | Breve descripción                                |
| ⤷ nombre                    | string       | Breve descripción                                |
| ↓↓ horario                  | array[object]| Breve descripción                                |
| ⤷ id                        | string       | Breve descripción                                |
| ⤷ nombre                    | string       | Breve descripción                                |
| ↓↓ periodos                 | array[object]| Breve descripción                                |
| ⤷ dia_inicio                | string       | Breve descripción                                |
| ⤷ dia_fin                   | string       | Breve descripción                                |
| ⤷ tarifa_horario_normal     | string       | Breve descripción                                |
| ⤷ tarifa_horario_nocturno   | string       | Breve descripción                                |
| ⤷ tarifa_horario_reducido   | string       | Breve descripción                                |
| ↓↓↓ detalle                 | array[object]| Breve descripción                                |
| ⤷ tipo_servicio             | string       | Breve descripción                                |
| ⤷ servicio                  | string       | Breve descripción                                |
| ⤷ monto_normal              | string       | Breve descripción                                |
| ⤷ monto_nocturno            | string       | Breve descripción                                |
| ⤷ monto_reducido            | string       | Breve descripción                                |
| ⤷ cantidad_llamadas_normal  | string       | Breve descripción                                |
| ⤷ cantidad_llamadas_nocturno| string       | Breve descripción                                |
| ⤷ cantidad_llamadas_reducido| string       | Breve descripción                                |
| ⤷ cantidad_segundos_normal  | string       | Breve descripción                                |
| ⤷ cantidad_segundos_nocturno| string       | Breve descripción                                |
| ⤷ cantidad_segundos_reducido| string       | Breve descripción                                |
| ⤷ monto_total               | string       | Breve descripción                                |
| ⤷ cantidad_total            | string       | Breve descripción                                |
| ⤷ segundo_total             | string       | Breve descripción                                |
| ↓↓ totales                  | array[object]| Breve descripción                                |
| ⤷ monto                     | string       | Breve descripción                                |
| ⤷ monto_normal              | string       | Breve descripción                                |
| ⤷ monto_nocturno            | string       | Breve descripción                                |
| ⤷ monto_reducido            | string       | Breve descripción                                |
| ⤷ cantidad_normal           | string       | Breve descripción                                |
| ⤷ cantidad_nocturno         | string       | Breve descripción                                |
| ⤷ cantidad_reducido         | string       | Breve descripción                                |
| ⤷ segundos_normal           | string       | Breve descripción                                |
| ⤷ segundos_nocturno         | string       | Breve descripción                                |
| ⤷ segundos_reducido         | string       | Breve descripción                                |
| ⤷ monto_total               | string       | Breve descripción                                |
| ⤷ cantidad_total            | string       | Breve descripción                                |
| ⤷ segundos_total            | string       | Breve descripción                                |
| ⤷ total_neto                | string       | Breve descripción                                |
| ⤷ iva                       | string       | Breve descripción                                |

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

## 9.- generarPDF
Método que permite generar archivo descargable en pdf de liquidación generada.

Los parámetros que recibe son los siguientes:

Ruta : POST `/cargos/generarPDF`

**Parámetros de entrada:**

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| ↓ data                   | array[object]|          |           |                            |
| ⤷ titulo                 | string       |          |           |                            |
| ⤷ totales                | string       |          |           |                            |
| ⤷ empresaDestino         | string       |          |           |                            |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

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

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| ido                      | int          |          |           |                            |
| idd                      | int          |          |           |                            |
| anio                     | int          |          |           |                            |
| mes                      | int          |          |           |                            |

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

| Campo                    |  Tipo        | Formato  | Requerido | Descripción                |
|:-------------------------|:------------:|:--------:|:---------:|---------------------------:|
| id_estado                | int          |          |           |                            |
| indicador_entrada        | int          |          |           |                            |
| detalle                  | array[object]|          |           |                            |
| mes                      | int          |          |           |                            |
| ejercicio                | int          |          |           |                            |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 11.1.- Ejemplo de llamada

Ejemplo: JSON 

        {
                "id_estado":1,
                "indicador_entrada":1,
                "detalle":[],
                "mes":0,
                "ejercicio":0
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