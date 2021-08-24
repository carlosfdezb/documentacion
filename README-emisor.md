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


# 1.- MODULO
## 1.1.- RUTA 1 MODULO
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : TIPO `/RUTA/ruta`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
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
                     DATA
                    },
                ]
            }
        },
        "codigo": 200
	}