| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Facturación

<!-- Índice -->
- [Documentación Api´s para Facturación](#documentación-apis-para-facturación)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Obtener DTES](#1--obtener-dtes)
        - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
        - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
            - [1.2.1- Respuesta de éxito](#121--respuesta-de-éxito)
  - [2.- Registrar DTE](#2--registrar-dte)
        - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
        - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
            - [2.2.1- Respuesta de error](#221--respuesta-de-error)
            - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- Obtener PDF](#3--obtener-pdf)
        - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
        - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
            - [3.2.1- Respuesta de error](#321--respuesta-de-error)
            - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- Publicar PDF](#4--publicar-pdf)
        - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
        - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
            - [4.2.1- Respuesta de error](#421--respuesta-de-error)
            - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
  - [5.- Url PDF](#5--url-pdf)
        - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
        - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
            - [5.2.1- Respuesta de error](#521--respuesta-de-error)
            - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- Estado DTE](#6--estado-dte)
        - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
        - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
            - [6.2.1- Respuesta de error](#621--respuesta-de-error)
            - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- Obtener Masivos DTES](#7--obtener-masivos-dtes)
        - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
        - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
            - [7.2.1- Respuesta de error](#721--respuesta-de-error)
            - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
  - [8.- Consultar CAF](#8--consultar-caf)
        - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
        - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
            - [8.2.1- Respuesta de error](#821--respuesta-de-error)
            - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
  - [9.- Eliminar CAF](#9--eliminar-caf)
        - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
        - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
            - [9.2.1- Respuesta de error](#921--respuesta-de-error)
            - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- Registrar CAF](#10--registrar-caf)
        - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
        - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
            - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
            - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- Obtener DTES
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerDTES`

**Parámetros de entrada:**
| Campo          |  Tipo        | Formato     | Requerido   | Descripción                 |
|:--------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| sort           | Tipo de dato |             |             | Breve descripción           |
| page           | Tipo de dato |             |             | Breve descripción           |
| per_page       | Tipo de dato |             |             | Breve descripción           |
| fechaEmisionDte| Tipo de dato |             |             | Breve descripción           |
| fechaHasta     | Tipo de dato |             |             | Breve descripción           |
| rutReceptor    | Tipo de dato |             |             | Breve descripción           |
| respTec        | Tipo de dato |             |             | Breve descripción           |
| respCom        | Tipo de dato |             |             | Breve descripción           |
| tipoDctosId    | Tipo de dato |             |             | Breve descripción           |
| folioDte       | Tipo de dato |             |             | Breve descripción           |
| usuario        | Tipo de dato |             |             | Breve descripción           |

**Datos de salida:**
| Campo            |  Tipo        |                         Descripción              |
|:-----------------|:------------:|-------------------------------------------------:| 
| id               | int          | Breve descripción                                |
| folio_dte        | int          | Breve descripción                                |
| monto_dte        | int          | Breve descripción                                |
| rut_receptor     | string       | Breve descripción                                |
| dv_receptor      | string       | Breve descripción                                |
| fecha_emision_dte| date         | Breve descripción                                |
| envio_dtes_id    | int          | Breve descripción                                |
| cliente_api_id   | int          | Breve descripción                                |
| estado           | string       | Breve descripción                                |
| documento        | int          | Breve descripción                                |
| envio_dte        | array[object]| Breve descripción                                |
| id               | int          | Breve descripción                                |
| track_id         | int          | Breve descripción                                |

### 1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "sort": "",
        "page": 1,
        "per_page": 10,
        "fechaEmisionDte": "",
        "fechaHasta": "",
        "rutReceptor": "",
        "respTec": "",
        "respCom": "",
        "tipoDctosId": "",
        "folioDte": "",
        "usuario": ""
	}

### 1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 1.2.1.- Respuesta de éxito

    {
        "current_page": 1,
        "data": [
            {
                "id": 33164231,
                "folio_dte": 251377,
                "monto_dte": 173126,
                "rut_receptor": "77046984-8",
                "dv_receptor": "8",
                "fecha_emision_dte": "13-09-2021",
                "envio_dtes_id": 163033,
                "cliente_api_id": 2,
                "estado": "DOK",
                "documento": 33,
                "envio_dte": {
                    "id": 163033,
                    "track_id": 6174896436
                }
            },
            ...
        ],
        "first_page_url": "...URL/obtenerDTES?per_page=10&page=1",
        "from": 1,
        "last_page": 4,
        "last_page_url": "...URL/obtenerDTES?per_page=10&page=4",
        "links": [
            {
                "url": "...URL/obtenerDTES?per_page=10&page=1",
                "label": 1,
                "active": true
            },
            ...
        ],
        "next_page_url": "...URL/obtenerDTES?per_page=10&page=2",
        "path": "...URL/obtenerDTES",
        "per_page": "10",
        "prev_page_url": null,
        "to": 10,
        "total": 37
    }

## 2.- Registrar DTE
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/registrarDTE`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:----------------|:------------:|:-----------:|:-----------:|----------------------------:|
| ↓ data          | array[object]|             |             | Breve descripción           |
| ⤷ RUTEmisor     | string       | NNNNNNNN-C  |             | Breve descripción           |
| ⤷ periodo       | int          |             |             | Breve descripción           |
| ⤷ TipoDTE       | string       |             |             | Breve descripción           |
| ↓↓ Dte          | array[object]|             |             | Breve descripción           |
| ⤷ RUTRecep      | string       | NNNNNNNN-C  |             | Breve descripción           |
| ⤷ RznSocRecep   | string       |             |             | Breve descripción           |
| ⤷ Folio         | string       |             |             | Breve descripción           |
| ⤷ FchEmis       | date         | yyyy-mm-dd  |             | Breve descripción           |
| ⤷ DirRecep      | string       |             |             | Breve descripción           |
| ⤷ CmnaRecep     | string       |             |             | Breve descripción           |
| ⤷ IndServicio   | string       |             |             | Breve descripción           |
| ⤷ PeriodoDesde  | date         | yyyy-mm-dd  |             | Breve descripción           |
| ⤷ PeriodoHasta  | date         | yyyy-mm-dd  |             | Breve descripción           |
| ↓↓↓ Detalle     | array[object]|             |             | Breve descripción           |
| ⤷ NmbItem       | string       |             |             | Breve descripción           |
| ⤷ QtyItem       | string       |             |             | Breve descripción           |
| ⤷ PrcItem       | string       |             |             | Breve descripción           |
| ↓↓↓ DscRcgGlobal| array[object]|             |             | Breve descripción           |
| ↓↓↓ ImptoReten  | array[object]|             |             | Breve descripción           |
| ↓↓↓ Referencia  | array[object]|             |             | Breve descripción           |
| plataforma      | int          |             |             | Breve descripción           |

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "data": {
            "RUTEmisor": "96722400-6",
            "periodo": 201902,
            "TipoDTE": "39",
            "Dte": [
                {
                    "RUTRecep": "19801500-8",
                    "RznSocRecep": "Nunez Escalona, Matias Antonio",
                    "Folio": "311146",
                    "FchEmis": "2019-05-14",
                    "DirRecep": "Santa Luisa 6088",
                    "CmnaRecep": "Lo Prado",
                    "IndServicio": "2",
                    "PeriodoDesde": "2019-03-01",
                    "PeriodoHasta": "2019-04-01",
                    "Detalle": [
                        {
                            "NmbItem": "PLAN EMPRENDEDOR 200 MBPS + WIFI + TV DIGITAL",
                            "QtyItem": "1",
                            "PrcItem": "26725"
                        }
                    ],
                    "DscRcgGlobal": [],
                    "ImptoReten": [],
                    "Referencia": []
                }
            ]
        },
        "plataforma": 2
    }

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "RUT del Emisor no ingresado."
        },
        "codigo": 422
    }
  
#### 2.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": "Recibido correctamente."
        },
        "codigo": 200
    }


## 3.- Obtener PDF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/obtenerPDF`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| rutEmisor       | string       | NNNNNNNN-C  |             | Breve descripción           |
| folio           | int          |             |             | Breve descripción           |
| tipoDocumento   | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| rutEmisor      | string       | Breve descripción                                |
| rutReceptor    | string       | Breve descripción                                |
| Folio          | string       | Breve descripción                                |
| TipoDTE        | string       | Breve descripción                                |
| documentoPdf   | archive      | Breve descripción                                |

### 3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
	}

### 3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 3.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "rutEmisor": "96722400-6",
                "rutReceptor": null,
                "Folio": "7881654",
                "TipoDTE": "39",
                "documentoPdf": "JVBERi0xLjcKJeLjz9MK..."
            }
        },
        "codigo": 200
    }


## 4.- Publicar PDF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/publicPDF`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| dkey            | string       |             |             | Breve descripción           |
| expires         | int          |             |             | Breve descripción           |
| signature       | string       |             |             | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| rutEmisor      | string       | Breve descripción                                |
| rutReceptor    | string       | Breve descripción                                |
| Folio          | string       | Breve descripción                                |
| TipoDTE        | string       | Breve descripción                                |
| documentoPdf   | archive      | Breve descripción                                |

### 4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "dkey": "eyJpdiI6ImtRb...",
        "expires": 1643700808,
        "signature": "ece7f734..."
	}

### 4.2.- Respuesta de salida

#### 4.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Ruta invalida"
        },
        "codigo": 403
    }
  
#### 4.2.2.- Respuesta de éxito

`Archivo PDF con factura electrónica`


## 5.- Url PDF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/urlPDF`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| rutEmisor       | string       | NNNNNNNN-C  |             | Breve descripción           |
| folio           | int          |             |             | Breve descripción           |
| tipoDocumento   | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| rutEmisor      | string       | Breve descripción                                |
| rutReceptor    | string       | Breve descripción                                |
| Folio          | string       | Breve descripción                                |
| TipoDTE        | string       | Breve descripción                                |
| urlPdf         | string       | Breve descripción                                |

### 5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
	}

### 5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 5.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "rutEmisor": "96722400-6",
                "rutReceptor": null,
                "Folio": "7881654",
                "TipoDTE": "39",
                "urlPdf": "https://www.tumundo.cl/facturacion/ver-pdf/..."
            }
        },
        "codigo": 200
    }


## 6.- Estado DTE
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/estadoDTE`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| rutEmisor       | string       | NNNNNNNN-C  |             | Breve descripción           |
| folio           | int          |             |             | Breve descripción           |
| tipoDocumento   | int          |             |             | Breve descripción           |

### 6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
	}

### 6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": "DTE Integrado SII"
        },
        "codigo": 200
    }

## 7.- Obtener Masivos DTES
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerMasivosDTES`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| page            | int          |             |             | Breve descripción           |
| per_page        | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | int          | Breve descripción                                |
| cantidad_dtes  | int          | Breve descripción                                |
| created_at     | timestamp    | Breve descripción                                |
| peticiones     | string       | Breve descripción                                |
| estado         | string       | Breve descripción                                |

### 7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "page": 1,
        "per_page": 10
	}

### 7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 7.2.1.- Respuesta de éxito

    {
        "current_page": 1,
        "data": [
            {
                "id": 2,
                "cantidad_dtes": 968,
                "created_at": "2021-08-31T19:54:58.000000Z",
                "peticiones": "349542,349541",
                "estado": "Finalizado"
            },
            ...
        ],
        "first_page_url": "...URL/obtenerMasivosDTES?page=1",
        "from": 1,
        "last_page": 1,
        "last_page_url": "...URL/obtenerMasivosDTES?page=1",
        "links": [
            {
                "url": "...URL/obtenerMasivosDTES?page=1",
                "label": 1,
                "active": true
            },
            ...
        ],
        "next_page_url": null,
        "path": "...URL/obtenerMasivosDTES",
        "per_page": "10",
        "prev_page_url": null,
        "to": 2,
        "total": 2
    }


## 8.- Consultar CAF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/consultarCAF`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| sort            | int          |             |             | Breve descripción           |
| page            | int          |             |             | Breve descripción           |
| per_page        | int          |             |             | Breve descripción           |
| fecha_emision   | int          |             |             | Breve descripción           |
| tipo_dctos_id   | int          |             |             | Breve descripción           |
| clientes_api_id | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| id                 | int          | Breve descripción                                |
| fecha_emision      | date         | Breve descripción                                |
| rango_desde        | int          | Breve descripción                                |
| rando_hasta        | int          | Breve descripción                                |
| cantidad_disponible| int          | Breve descripción                                |
| cafs_xml_id        | int          | Breve descripción                                |
| empresas_id        | int          | Breve descripción                                |
| clientes_api_id    | int          | Breve descripción                                |
| tipo_dctos_id      | int          | Breve descripción                                |
| created_at         | timestamp    | Breve descripción                                |
| updated_at         | timestamp    | Breve descripción                                |
| vence              | int          | Breve descripción                                |
| tipo_dcto          | array[object]| Breve descripción                                |
| id                 | int          | Breve descripción                                |
| documentos         | string       | Breve descripción                                |
| clientes           | array[object]| Breve descripción                                |
| id                 | int          | Breve descripción                                |
| nombre             | string       | Breve descripción                                |

### 8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "sort": "",
        "page": 1,
        "per_page": 10,
        "fecha_emision": "",
        "tipo_dctos_id": "",
        "clientes_api_id": ""
	}

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 8.2.1.- Respuesta de éxito

    {
        "current_page": 1,
        "data": [
            {
                "id": 242,
                "fecha_emision": "2021-08-25",
                "rango_desde": 19037712,
                "rando_hasta": 19637711,
                "cantidad_disponible": 436996,
                "cafs_xml_id": 242,
                "empresas_id": 1,
                "clientes_api_id": 5,
                "tipo_dctos_id": 3,
                "created_at": null,
                "updated_at": null,
                "vence": -153,
                "tipo_dcto": {
                    "id": 3,
                    "documentos": "Boleta Electrónica"
                },
                "clientes": {
                    "id": 5,
                    "nombre": "beyond up"
                }
            },
            ...
        ],
        "first_page_url": "...URL/consultarCAF?page=1",
        "from": 1,
        "last_page": 21,
        "last_page_url": "...URL/consultarCAF?page=21",
        "links": [
            {
                "url": "...URL/consultarCAF?page=1",
                "label": 1,
                "active": true
            },
            ...
        ],
        "next_page_url": "...URL/consultarCAF?page=2",
        "path": "...URL/consultarCAF",
        "per_page": "10",
        "prev_page_url": null,
        "to": 10,
        "total": 210
    }


## 9.- Eliminar CAF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/eliminarCAF`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| id              | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo            |  Tipo        |                         Descripción              |
|:-----------------|:------------:|-------------------------------------------------:| 
|                  |              | Breve descripción                                |

### 9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "id": 140
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

## 10.- Registrar CAF
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/registrarCAF`

**Parámetros de entrada:**
| Campo              |  Tipo        | Formato     | Requerido   | Descripción                 |
|:------------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| xml                | file         |             |             | Breve descripción           |
| fecha_emision      | date         |             |             | Breve descripción           |
| rango_desde        | int          |             |             | Breve descripción           |
| rango_hasta        | int          |             |             | Breve descripción           |
| cantidad_disponible| int          |             |             | Breve descripción           |
| tipo_dctos_id      | int          |             |             | Breve descripción           |
| cliente_api        | int          |             |             | Breve descripción           |

**Datos de salida:**
| Campo            |  Tipo        |                         Descripción              |
|:-----------------|:------------:|-------------------------------------------------:| 
|                  |              | Breve descripción                                |

### 10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "xml": FILE.xml,
        "fecha_emision": "2021-02-09",
        "rango_desde": 1930301,
        "rango_hasta": 2030300,
        "cantidad_disponible": 100000,
        "tipo_dctos_id": 9,
        "cliente_api": 6
	}

### 10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 10.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Ocurrio un error al intentar registrar el Cafs"
        },
        "codigo": 422
    }
  
#### 10.2.2.- Respuesta de éxito

    {
        ...
    }