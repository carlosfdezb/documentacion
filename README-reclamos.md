| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Reclamos

<!-- Índice -->
- [Documentación Api´s para Reclamos](#documentación-apis-para-Reclamos)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Reclamos](#1--Reclamos)
    - [1.1.- Tipo Reclamo](#11--tipo-reclamo)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Tipo Solución](#12--tipo-solución)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- Motivo Acoge](#13--motivo-acoge)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
    - [1.4.- Motivo Acoge](#14--motivo-acoge)
        - [1.4.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
        - [1.4.2.- Respuesta de Salida](#142--respuesta-de-salida)
            - [1.4.2.1- Respuesta de error](#1421--respuesta-de-error)
            - [1.4.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
    - [1.5.- Tipo Notificación](#15--tipo-notificación)
        - [1.5.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
        - [1.5.2.- Respuesta de Salida](#152--respuesta-de-salida)
            - [1.5.2.1- Respuesta de error](#1521--respuesta-de-error)
            - [1.5.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
    - [1.6.- Servicio](#16--servicio)
        - [1.6.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
        - [1.6.2.- Respuesta de Salida](#162--respuesta-de-salida)
            - [1.6.2.1- Respuesta de error](#1621--respuesta-de-error)
            - [1.6.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
    - [1.7.- Tipo Servicio](#17--tipo-servicio)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de error](#1721--respuesta-de-error)
            - [1.7.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
    - [1.8.- Motivo](#18--motivo)
        - [1.8.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
        - [1.8.2.- Respuesta de Salida](#182--respuesta-de-salida)
            - [1.8.2.1- Respuesta de error](#1821--respuesta-de-error)
            - [1.8.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
    - [1.9.- Tipo Registro](#19--tipo-registro)
        - [1.9.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
        - [1.9.2.- Respuesta de Salida](#192--respuesta-de-salida)
            - [1.9.2.1- Respuesta de error](#1921--respuesta-de-error)
            - [1.9.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
    - [1.10.- Submotivo](#110--submotivo)
        - [1.10.1.- Ejemplo de llamada](#1101--ejemplo-de-llamada)
        - [1.10.2.- Respuesta de Salida](#1102--respuesta-de-salida)
            - [1.10.2.1- Respuesta de error](#11021--respuesta-de-error)
            - [1.10.2.2- Respuesta de éxito](#11022--respuesta-de-éxito)
    - [1.11.- Reclamo](#111--reclamo)
        - [1.11.1.- Ejemplo de llamada](#1111--ejemplo-de-llamada)
        - [1.11.2.- Respuesta de Salida](#1112--respuesta-de-salida)
            - [1.11.2.1- Respuesta de error](#11121--respuesta-de-error)
            - [1.11.2.2- Respuesta de éxito](#11122--respuesta-de-éxito)
    - [1.12.- Estado Reclamo](#112--estado-reclamo)
        - [1.12.1.- Ejemplo de llamada](#1121--ejemplo-de-llamada)
        - [1.12.2.- Respuesta de Salida](#1122--respuesta-de-salida)
            - [1.12.2.1- Respuesta de error](#11221--respuesta-de-error)
            - [1.12.2.2- Respuesta de éxito](#11222--respuesta-de-éxito)
    - [1.13.- Ingresar Reclamo Ejecutivo](#113--ingresar-reclamo-ejecutivo)
        - [1.13.1.- Ejemplo de llamada](#1131--ejemplo-de-llamada)
        - [1.13.2.- Respuesta de Salida](#1132--respuesta-de-salida)
            - [1.13.2.1- Respuesta de error](#11321--respuesta-de-error)
            - [1.13.2.2- Respuesta de éxito](#11322--respuesta-de-éxito)
    - [1.14.- Gráfico Reclamo Total Comuna](#114--gráfico-reclamo-total-comuna)
        - [1.14.1.- Ejemplo de llamada](#1141--ejemplo-de-llamada)
        - [1.14.2.- Respuesta de Salida](#1142--respuesta-de-salida)
            - [1.14.2.1- Respuesta de error](#11421--respuesta-de-error)
            - [1.14.2.2- Respuesta de éxito](#11422--respuesta-de-éxito)
    - [1.15.- Gráfico Reclamo por Comuna](#115--gráfico-reclamo-por-comuna)
        - [1.15.1.- Ejemplo de llamada](#1151--ejemplo-de-llamada)
        - [1.15.2.- Respuesta de Salida](#1152--respuesta-de-salida)
            - [1.15.2.1- Respuesta de error](#11521--respuesta-de-error)
            - [1.15.2.2- Respuesta de éxito](#11522--respuesta-de-éxito)
    - [1.16.- Gráfico Reclamo por Fecha](#116--gráfico-reclamo-por-fecha)
        - [1.16.1.- Ejemplo de llamada](#1161--ejemplo-de-llamada)
        - [1.16.2.- Respuesta de Salida](#1162--respuesta-de-salida)
            - [1.16.2.1- Respuesta de error](#11621--respuesta-de-error)
            - [1.16.2.2- Respuesta de éxito](#11622--respuesta-de-éxito)
    - [1.17.- Gráfico Reclamo por Servicio](#117--gráfico-reclamo-por-servicio)
        - [1.17.1.- Ejemplo de llamada](#1171--ejemplo-de-llamada)
        - [1.17.2.- Respuesta de Salida](#1172--respuesta-de-salida)
            - [1.17.2.1- Respuesta de error](#11721--respuesta-de-error)
            - [1.17.2.2- Respuesta de éxito](#11722--respuesta-de-éxito)
    - [1.18.- Tipo Conformidad](#118--tipo-conformidad)
        - [1.18.1.- Ejemplo de llamada](#1181--ejemplo-de-llamada)
        - [1.18.2.- Respuesta de Salida](#1182--respuesta-de-salida)
            - [1.18.2.1- Respuesta de error](#11821--respuesta-de-error)
            - [1.18.2.2- Respuesta de éxito](#11822--respuesta-de-éxito)
    - [1.19.- Macromotivo](#119--macromotivo)
        - [1.19.1.- Ejemplo de llamada](#1191--ejemplo-de-llamada)
        - [1.19.2.- Respuesta de Salida](#1192--respuesta-de-salida)
            - [1.19.2.1- Respuesta de error](#11921--respuesta-de-error)
            - [1.19.2.2- Respuesta de éxito](#11922--respuesta-de-éxito)
    - [1.20.- Editar Reclamo](#120--editar-reclamo)
        - [1.20.1.- Ejemplo de llamada](#1201--ejemplo-de-llamada)
        - [1.20.2.- Respuesta de Salida](#1202--respuesta-de-salida)
            - [1.20.2.1- Respuesta de error](#12021--respuesta-de-error)
            - [1.20.2.2- Respuesta de éxito](#12022--respuesta-de-éxito)
    - [1.21.- Exportar Reclamo](#121--exportar-reclamo)
        - [1.21.1.- Ejemplo de llamada](#1211--ejemplo-de-llamada)
        - [1.21.2.- Respuesta de Salida](#1212--respuesta-de-salida)
            - [1.21.2.1- Respuesta de error](#12121--respuesta-de-error)
            - [1.21.2.2- Respuesta de éxito](#12122--respuesta-de-éxito)
    - [1.22.- Tipo Teléfono](#122--tipo-teléfono)
        - [1.22.1.- Ejemplo de llamada](#1221--ejemplo-de-llamada)
        - [1.22.2.- Respuesta de Salida](#1222--respuesta-de-salida)
            - [1.22.2.1- Respuesta de error](#12221--respuesta-de-error)
            - [1.22.2.2- Respuesta de éxito](#12222--respuesta-de-éxito)
    - [1.23.- Contingencia Nodos](#123--contingencia-nodos)
        - [1.23.1.- Ejemplo de llamada](#1231--ejemplo-de-llamada)
        - [1.23.2.- Respuesta de Salida](#1232--respuesta-de-salida)
            - [1.23.2.1- Respuesta de error](#12321--respuesta-de-error)
            - [1.23.2.2- Respuesta de éxito](#12322--respuesta-de-éxito)
    - [1.24.- Consulta Cliente](#124--consulta-cliente)
        - [1.24.1.- Ejemplo de llamada](#1241--ejemplo-de-llamada)
        - [1.24.2.- Respuesta de Salida](#1242--respuesta-de-salida)
            - [1.24.2.1- Respuesta de error](#12421--respuesta-de-error)
            - [1.24.2.2- Respuesta de éxito](#12422--respuesta-de-éxito)
    - [1.25.- Consulta Cliente IVR](#125--consulta-cliente-ivr)
        - [1.25.1.- Ejemplo de llamada](#1251--ejemplo-de-llamada)
        - [1.25.2.- Respuesta de Salida](#1252--respuesta-de-salida)
            - [1.25.2.1- Respuesta de error](#12521--respuesta-de-error)
            - [1.25.2.2- Respuesta de éxito](#12522--respuesta-de-éxito)
    - [1.26.- divGeoClientePrincipal](#126--divGeoClientePrincipal)
        - [1.26.1.- Ejemplo de llamada](#1261--ejemplo-de-llamada)
        - [1.26.2.- Respuesta de Salida](#1262--respuesta-de-salida)
            - [1.26.2.1- Respuesta de error](#12621--respuesta-de-error)
            - [1.26.2.2- Respuesta de éxito](#12622--respuesta-de-éxito)
    - [1.27.- Comunas](#127--comunas)
        - [1.27.1.- Ejemplo de llamada](#1271--ejemplo-de-llamada)
        - [1.27.2.- Respuesta de Salida](#1272--respuesta-de-salida)
            - [1.27.2.1- Respuesta de error](#12721--respuesta-de-error)
            - [1.27.2.2- Respuesta de éxito](#12722--respuesta-de-éxito)
    - [1.28.- Regiones](#128--regiones)
        - [1.28.1.- Ejemplo de llamada](#1281--ejemplo-de-llamada)
        - [1.28.2.- Respuesta de Salida](#1282--respuesta-de-salida)
            - [1.28.2.1- Respuesta de error](#12821--respuesta-de-error)
            - [1.28.2.2- Respuesta de éxito](#12822--respuesta-de-éxito)
    - [1.29.- Datos Cliente Tipo Servicio](#129--datos-cliente-tipo-servicio)
        - [1.29.1.- Ejemplo de llamada](#1291--ejemplo-de-llamada)
        - [1.29.2.- Respuesta de Salida](#1292--respuesta-de-salida)
            - [1.29.2.1- Respuesta de error](#12921--respuesta-de-error)
            - [1.29.2.2- Respuesta de éxito](#12922--respuesta-de-éxito)
    - [1.30.- Ingresar Comentario Reclamo](#130--ingresar-comentario-reclamo)
        - [1.30.1.- Ejemplo de llamada](#1301--ejemplo-de-llamada)
        - [1.30.2.- Respuesta de Salida](#1302--respuesta-de-salida)
            - [1.30.2.1- Respuesta de error](#13021--respuesta-de-error)
            - [1.30.2.2- Respuesta de éxito](#13022--respuesta-de-éxito)
    - [1.31.- Subcategorías Internas](#131--subcategorias-internas)
        - [1.31.1.- Ejemplo de llamada](#1311--ejemplo-de-llamada)
        - [1.31.2.- Respuesta de Salida](#1312--respuesta-de-salida)
            - [1.31.2.1- Respuesta de error](#13121--respuesta-de-error)
            - [1.31.2.2- Respuesta de éxito](#13122--respuesta-de-éxito)
    - [1.32.- OficioReclamo](#132--oficioReclamo)
        - [1.32.1.- Ejemplo de llamada](#1321--ejemplo-de-llamada)
        - [1.32.2.- Respuesta de Salida](#1322--respuesta-de-salida)
            - [1.32.2.1- Respuesta de error](#13221--respuesta-de-error)
            - [1.32.2.2- Respuesta de éxito](#13222--respuesta-de-éxito)
    - [1.33.- Resolución Reclamo](#133--resolución-reclamo)
        - [1.33.1.- Ejemplo de llamada](#1331--ejemplo-de-llamada)
        - [1.33.2.- Respuesta de Salida](#1332--respuesta-de-salida)
            - [1.33.2.1- Respuesta de error](#13321--respuesta-de-error)
            - [1.33.2.2- Respuesta de éxito](#13322--respuesta-de-éxito)
  - [2.- Sucursal](#1--Sucursal)






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