| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Emisor

<!-- Índice -->
- [Documentación Api´s para Emisor](#documentación-apis-para-emisor)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- masivoDTE](#1--masivoDTE)
      - [1.1.- Ejemplo de llamada](#11--ejemplo-de-llamada)
      - [1.2.- Respuesta de Salida](#12--respuesta-de-salida)
          - [1.2.1- Respuesta de error](#121--respuesta-de-error)
          - [1.2.2- Respuesta de éxito](#122--respuesta-de-éxito)
  - [2.- obtenerMasivosDTE](#2--obtenerMasivosDTE)
      - [2.1.- Ejemplo de llamada](#21--ejemplo-de-llamada)
      - [2.2.- Respuesta de Salida](#22--respuesta-de-salida)
          - [2.2.1- Respuesta de error](#221--respuesta-de-error)
          - [2.2.2- Respuesta de éxito](#222--respuesta-de-éxito)
  - [3.- consultaEnvioSII](#3--consultaEnvioSII)
      - [3.1.- Ejemplo de llamada](#31--ejemplo-de-llamada)
      - [3.2.- Respuesta de Salida](#32--respuesta-de-salida)
          - [3.2.1- Respuesta de error](#321--respuesta-de-error)
          - [3.2.2- Respuesta de éxito](#322--respuesta-de-éxito)
  - [4.- procesarEnvioSII](#4--procesarEnvioSII)
      - [4.1.- Ejemplo de llamada](#41--ejemplo-de-llamada)
      - [4.2.- Respuesta de Salida](#42--respuesta-de-salida)
          - [4.2.1- Respuesta de error](#421--respuesta-de-error)
          - [4.2.2- Respuesta de éxito](#422--respuesta-de-éxito)
  - [5.- integrarMasivo](#5--integrarMasivo)
      - [5.1.- Ejemplo de llamada](#51--ejemplo-de-llamada)
      - [5.2.- Respuesta de Salida](#52--respuesta-de-salida)
          - [5.2.1- Respuesta de error](#521--respuesta-de-error)
          - [5.2.2- Respuesta de éxito](#522--respuesta-de-éxito)
  - [6.- registrarDTE](#6--registrarDTE)
      - [6.1.- Ejemplo de llamada](#61--ejemplo-de-llamada)
      - [6.2.- Respuesta de Salida](#62--respuesta-de-salida)
          - [6.2.1- Respuesta de error](#621--respuesta-de-error)
          - [6.2.2- Respuesta de éxito](#622--respuesta-de-éxito)
  - [7.- obtenerPDF](#7--obtenerPDF)
      - [7.1.- Ejemplo de llamada](#71--ejemplo-de-llamada)
      - [7.2.- Respuesta de Salida](#72--respuesta-de-salida)
          - [7.2.1- Respuesta de error](#721--respuesta-de-error)
          - [7.2.2- Respuesta de éxito](#722--respuesta-de-éxito)
  - [8.- obtenerDTES](#8--obtenerDTES)
      - [8.1.- Ejemplo de llamada](#81--ejemplo-de-llamada)
      - [8.2.- Respuesta de Salida](#82--respuesta-de-salida)
          - [8.2.1- Respuesta de error](#821--respuesta-de-error)
          - [8.2.2- Respuesta de éxito](#822--respuesta-de-éxito)
  - [9.- publicPDF](#9--publicPDF)
      - [9.1.- Ejemplo de llamada](#91--ejemplo-de-llamada)
      - [9.2.- Respuesta de Salida](#92--respuesta-de-salida)
          - [9.2.1- Respuesta de error](#921--respuesta-de-error)
          - [9.2.2- Respuesta de éxito](#922--respuesta-de-éxito)
  - [10.- estadoDTE](#10--estadoDTE)
      - [10.1.- Ejemplo de llamada](#101--ejemplo-de-llamada)
      - [10.2.- Respuesta de Salida](#102--respuesta-de-salida)
          - [10.2.1- Respuesta de error](#1021--respuesta-de-error)
          - [10.2.2- Respuesta de éxito](#1022--respuesta-de-éxito)
  - [11.- urlPDF](#11--urlPDF)
      - [11.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
      - [11.2.- Respuesta de Salida](#112--respuesta-de-salida)
          - [11.2.1- Respuesta de error](#1121--respuesta-de-error)
          - [11.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
  - [12.- guiaDespachoRequest](#12--guiaDespachoRequest)
      - [12.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
      - [12.2.- Respuesta de Salida](#122--respuesta-de-salida)
          - [12.2.1- Respuesta de error](#1221--respuesta-de-error)
          - [12.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [13.- obtenerPDFDespachoRequest](#13--obtenerPDFDespachoRequest)
      - [13.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
      - [13.2.- Respuesta de Salida](#132--respuesta-de-salida)
          - [13.2.1- Respuesta de error](#1321--respuesta-de-error)
          - [13.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
  - [14.- consultarBoletaRequest](#14--consultarBoletaRequest)
      - [14.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
      - [14.2.- Respuesta de Salida](#142--respuesta-de-salida)
          - [14.2.1- Respuesta de error](#1421--respuesta-de-error)
          - [14.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
  - [15.- consultarCAF](#15--consultarCAF)
      - [15.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
      - [15.2.- Respuesta de Salida](#152--respuesta-de-salida)
          - [15.2.1- Respuesta de error](#1521--respuesta-de-error)
          - [15.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
  - [16.- registrarCAF](#16--registrarCAF)
      - [16.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
      - [16.2.- Respuesta de Salida](#162--respuesta-de-salida)
          - [16.2.1- Respuesta de error](#1621--respuesta-de-error)
          - [16.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
  - [17.- eliminarCAF](#17--eliminarCAF)
      - [17.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
      - [17.2.- Respuesta de Salida](#172--respuesta-de-salida)
          - [17.2.1- Respuesta de error](#1721--respuesta-de-error)
          - [17.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
  - [18.- obtenerNextFolio](#18--obtenerNextFolio)
      - [18.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
      - [18.2.- Respuesta de Salida](#182--respuesta-de-salida)
          - [18.2.1- Respuesta de error](#1821--respuesta-de-error)
          - [18.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
  - [19.- obtenerTipoDocumentos](#19--obtenerTipoDocumentos)
      - [19.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
      - [19.2.- Respuesta de Salida](#192--respuesta-de-salida)
          - [19.2.1- Respuesta de error](#1921--respuesta-de-error)
          - [19.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
  - [20.- ObtenerClientes](#20--ObtenerClientes)
      - [20.1.- Ejemplo de llamada](#201--ejemplo-de-llamada)
      - [20.2.- Respuesta de Salida](#202--respuesta-de-salida)
          - [20.2.1- Respuesta de error](#2021--respuesta-de-error)
          - [20.2.2- Respuesta de éxito](#2022--respuesta-de-éxito)
  - [21.- obtenerContribuyente](#21--obtenerContribuyente)
      - [21.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
      - [21.2.- Respuesta de Salida](#212--respuesta-de-salida)
          - [21.2.1- Respuesta de error](#2121--respuesta-de-error)
          - [21.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
  - [22.- get contribuyentes](#22--get-contribuyentes)
      - [22.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
      - [22.2.- Respuesta de Salida](#222--respuesta-de-salida)
          - [22.2.1- Respuesta de error](#2221--respuesta-de-error)
          - [22.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
  - [23.- post contribuyentes](#23--post-contribuyentes)
      - [23.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
      - [23.2.- Respuesta de Salida](#232--respuesta-de-salida)
          - [23.2.1- Respuesta de error](#2321--respuesta-de-error)
          - [23.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
  - [24.- put contribuyentes](#24--put-contribuyentes)
      - [24.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
      - [24.2.- Respuesta de Salida](#242--respuesta-de-salida)
          - [24.2.1- Respuesta de error](#2421--respuesta-de-error)
          - [24.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
  - [25.- consultarRecepcion](#25--consultarRecepcion)
      - [25.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
      - [25.2.- Respuesta de Salida](#252--respuesta-de-salida)
          - [25.2.1- Respuesta de error](#2521--respuesta-de-error)
          - [25.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
  - [26.- exportarRecepcion](#26--exportarRecepcion)
      - [26.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
      - [26.2.- Respuesta de Salida](#262--respuesta-de-salida)
          - [26.2.1- Respuesta de error](#2621--respuesta-de-error)
          - [26.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
  - [27.- rutas](#27--rutas)
      - [27.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
      - [27.2.- Respuesta de Salida](#272--respuesta-de-salida)
          - [27.2.1- Respuesta de error](#2721--respuesta-de-error)
          - [27.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
  - [28.- recepciones](#28--recepciones)
      - [28.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
      - [28.2.- Respuesta de Salida](#282--respuesta-de-salida)
          - [28.2.1- Respuesta de error](#2821--respuesta-de-error)
          - [28.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
  - [29.- actualizar-recepcion](#29--actualizar-recepcion)
      - [29.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
      - [29.2.- Respuesta de Salida](#292--respuesta-de-salida)
          - [29.2.1- Respuesta de error](#2921--respuesta-de-error)
          - [29.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
  - [30.- RecepcionPdf](#30--RecepcionPdf)
      - [30.1.- Ejemplo de llamada](#301--ejemplo-de-llamada)
      - [30.2.- Respuesta de Salida](#302--respuesta-de-salida)
          - [30.2.1- Respuesta de error](#3021--respuesta-de-error)
          - [30.2.2- Respuesta de éxito](#3022--respuesta-de-éxito)
  - [31.- consultarRecof](#31--consultarRecof)
      - [31.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
      - [31.2.- Respuesta de Salida](#312--respuesta-de-salida)
          - [31.2.1- Respuesta de error](#3121--respuesta-de-error)
          - [31.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
  - [32.- obtenerResumenRecof](#32--obtenerResumenRecof)
      - [32.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
      - [32.2.- Respuesta de Salida](#322--respuesta-de-salida)
          - [32.2.1- Respuesta de error](#3221--respuesta-de-error)
          - [32.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
  - [33.- obtenerCertificados](#33--obtenerCertificados)
      - [33.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
      - [33.2.- Respuesta de Salida](#332--respuesta-de-salida)
          - [33.2.1- Respuesta de error](#3321--respuesta-de-error)
          - [33.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
  - [34.- registrarCertificado](#34--registrarCertificado)
      - [34.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
      - [34.2.- Respuesta de Salida](#342--respuesta-de-salida)
          - [34.2.1- Respuesta de error](#3421--respuesta-de-error)
          - [34.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
  - [35.- eliminarCertificado](#35--eliminarCertificado)
      - [35.1.- Ejemplo de llamada](#351--ejemplo-de-llamada)
      - [35.2.- Respuesta de Salida](#352--respuesta-de-salida)
          - [35.2.1- Respuesta de error](#3521--respuesta-de-error)
          - [35.2.2- Respuesta de éxito](#3522--respuesta-de-éxito)
  - [36.- obtenerEmpresas](#36--obtenerEmpresas)
      - [36.1.- Ejemplo de llamada](#361--ejemplo-de-llamada)
      - [36.2.- Respuesta de Salida](#362--respuesta-de-salida)
          - [36.2.1- Respuesta de error](#3621--respuesta-de-error)
          - [36.2.2- Respuesta de éxito](#3622--respuesta-de-éxito)



# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


## 1.- masivoDTE
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/masivoDTE`

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
        ...
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


## 2.- obtenerMasivosDTE
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

### 2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "page": 1,
        "per_page": 10
	}

### 2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 2.2.1.- Respuesta de éxito

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

## 3.- consultaEnvioSII
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/consultaEnvioSII`

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
        ...
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


## 4.- procesarEnvioSII
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/procesarEnvioSII`

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
        ...
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

## 5.- integrarMasivo
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/integrarMasivo`

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
        ...
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

## 6.- registrarDTE
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

### 6.1.- Ejemplo de llamada

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

### 6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "RUT del Emisor no ingresado."
        },
        "codigo": 422
    }
  
#### 6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": "Recibido correctamente."
        },
        "codigo": 200
    }


## 7.- obtenerPDF
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

### 7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
	}

### 7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 7.2.2.- Respuesta de éxito

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


## 8.- obtenerDTES
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

### 8.1.- Ejemplo de llamada

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

### 8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 8.2.1.- Respuesta de éxito

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

## 9.- publicPDF
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

### 9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "dkey": "eyJpdiI6ImtRb...",
        "expires": 1643700808,
        "signature": "ece7f734..."
	}

### 9.2.- Respuesta de salida

#### 9.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Ruta invalida"
        },
        "codigo": 403
    }
  
#### 9.2.2.- Respuesta de éxito

`Archivo PDF con factura electrónica`


## 10.- estadoDTE
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/estadoDTE`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato     | Requerido   | Descripción                 |
|:---------------:|:------------:|:-----------:|:-----------:|----------------------------:|
| rutEmisor       | string       | NNNNNNNN-C  |             | Breve descripción           |
| folio           | int          |             |             | Breve descripción           |
| tipoDocumento   | int          |             |             | Breve descripción           |

### 10.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
    }

### 10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 10.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 10.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": "DTE Integrado SII"
        },
        "codigo": 200
    }

## 11.- urlPDF
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

### 11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutEmisor": "96722400-6",
        "folio": 7881654,
        "tipoDocumento": 39
	}

### 11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encuentra Folio registrado con los datos suministrados"
        },
        "codigo": 404
    }
  
#### 11.2.2.- Respuesta de éxito

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


## 12.- guiaDespachoRequest
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/guiaDespachoRequest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 12.2.2.- Respuesta de éxito

	{
        ...
	}


## 13.- obtenerPDFDespachoRequest
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerPDFDespachoRequest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 13.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 13.2.2.- Respuesta de éxito

	{
        ...
	}

## 14.- consultarBoletaRequest
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/consultarBoletaRequest`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 14.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 14.2.2.- Respuesta de éxito

	{
        ...
	}

## 15.- consultarCAF
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

### 15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "sort": "",
        "page": 1,
        "per_page": 10,
        "fecha_emision": "",
        "tipo_dctos_id": "",
        "clientes_api_id": ""
	}

### 15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 15.2.1.- Respuesta de éxito

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


## 16.- registrarCAF
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

### 16.1.- Ejemplo de llamada

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

### 16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Ocurrio un error al intentar registrar el Cafs"
        },
        "codigo": 422
    }
  
#### 16.2.2.- Respuesta de éxito

    {
        ...
    }

## 17.- eliminarCAF
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

### 17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "id": 140
	}

### 17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.2.1.- Respuesta de error

    {
        ...
    }
  
#### 17.2.2.- Respuesta de éxito

    {
        ...
    }

## 18.- obtenerNextFolio
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/obtenerNextFolio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 18.2.2.- Respuesta de éxito

	{
        ...
	}


## 19.- obtenerTipoDocumentos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerTipoDocumentos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 19.2.2.- Respuesta de éxito

	{
        ...
	}


## 20.- ObtenerClientes
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/ObtenerClientes`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 20.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 20.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 20.2.2.- Respuesta de éxito

	{
        ...
	}

## 21.- obtenerContribuyente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerContribuyente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 21.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 21.2.2.- Respuesta de éxito

	{
        ...
	}

## 22.- get contribuyentes
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/contribuyentes`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 22.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 22.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 22.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 22.2.2.- Respuesta de éxito

	{
        ...
	}

## 23.- post contribuyentes
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/contribuyentes`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 23.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 23.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 23.2.2.- Respuesta de éxito

	{
        ...
	}


## 24.- put contribuyentes
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : PUT `/contribuyentes`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 24.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 24.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 24.2.2.- Respuesta de éxito

	{
        ...
	}

## 25.- consultarRecepcion
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/consultarRecepcion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 25.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 25.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 25.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 25.2.2.- Respuesta de éxito

	{
        ...
	}

## 26.- exportarRecepcion
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/exportarRecepcion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 26.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 26.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 26.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 26.2.2.- Respuesta de éxito

	{
        ...
	}

## 27.- rutas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rutas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 27.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 27.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 27.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 27.2.2.- Respuesta de éxito

	{
        ...
	}

## 28.- recepciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/recepciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 28.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 28.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 28.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 28.2.2.- Respuesta de éxito

	{
        ...
	}

## 29.- actualizar-recepcion
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/actualizar-recepcion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 29.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 29.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 29.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 29.2.2.- Respuesta de éxito

	{
        ...
	}

## 30.- RecepcionPdf
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/RecepcionPdf`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 30.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 30.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 30.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 30.2.2.- Respuesta de éxito

	{
        ...
	}

## 31.- consultarRecof
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/consultarRecof`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 31.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 31.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 31.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 31.2.2.- Respuesta de éxito

	{
        ...
	}

## 32.- obtenerResumenRecof
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerResumenRecof`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 32.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 32.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 32.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 32.2.2.- Respuesta de éxito

	{
        ...
	}

## 33.- obtenerCertificados
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerCertificados`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 33.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 33.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 33.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 33.2.2.- Respuesta de éxito

	{
        ...
	}

## 34.- registrarCertificado
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/registrarCertificado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 34.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 34.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 34.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 34.2.2.- Respuesta de éxito

	{
        ...
	}

## 35.- eliminarCertificado
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/eliminarCertificado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 35.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 35.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 35.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 35.2.2.- Respuesta de éxito

	{
        ...
	}

## 36.- obtenerEmpresas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/obtenerEmpresas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 36.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 36.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 36.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 36.2.2.- Respuesta de éxito

	{
        ...
	}