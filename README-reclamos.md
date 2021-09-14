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
    - [1.1.- Tipos de Reclamos](#11--tipos-de-reclamos)
        - [1.1.1.- Respuesta de Salida](#111--respuesta-de-salida)
            - [1.1.1.1- Respuesta de éxito](#1111--respuesta-de-éxito)
    - [1.2.- Tipos de Soluciones](#12--tipos-de-soluciones)
        - [1.2.1.- Respuesta de Salida](#121--respuesta-de-salida)
            - [1.2.1.1- Respuesta de éxito](#1211--respuesta-de-éxito)
    - [1.3.- Tipos de Motivos de Reclamos](#13--tipos-de-motivos-de-reclamos)
        - [1.3.1.- Respuesta de Salida](#131--respuesta-de-salida)
            - [1.3.1.1- Respuesta de éxito](#1311--respuesta-de-éxito)
    - [1.4.- Tipos de Notificación](#14--tipos-de-notificación)
        - [1.4.1.- Respuesta de Salida](#141--respuesta-de-salida)
            - [1.4.1.1- Respuesta de éxito](#1411--respuesta-de-éxito)
    - [1.5.- Tipos de Servicios](#15--tipos-de-servicios)
        - [1.5.1.- Ejemplo de llamada](#151--ejemplo-de-llamada)
        - [1.5.2.- Respuesta de Salida](#152--respuesta-de-salida)
            - [1.5.2.1- Respuesta de error](#1521--respuesta-de-error)
            - [1.5.2.2- Respuesta de éxito](#1522--respuesta-de-éxito)
    - [1.6.- Tipos de Servicios 2](#16--tipos-de-servicios-2)
        - [1.6.1.- Ejemplo de llamada](#161--ejemplo-de-llamada)
        - [1.6.2.- Respuesta de Salida](#162--respuesta-de-salida)
            - [1.6.2.1- Respuesta de error](#1621--respuesta-de-error)
            - [1.6.2.2- Respuesta de éxito](#1622--respuesta-de-éxito)
    - [1.7.- Motivos](#17--motivos)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de éxito](#1721--respuesta-de-éxito)
    - [1.8.- Tipos de Registro](#18--tipos-de-registro)
        - [1.8.1.- Respuesta de Salida](#181--respuesta-de-salida)
            - [1.8.1.1- Respuesta de éxito](#1811--respuesta-de-éxito)
    - [1.9.- Reclamos](#19--reclamos)
        - [1.9.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
        - [1.9.2.- Respuesta de Salida](#192--respuesta-de-salida)
            - [1.9.2.1- Respuesta de éxito](#1921--respuesta-de-éxito)
    - [1.10.- Estado de Reclamo](#101--estado-de-reclamo)
        - [1.10.1.- Respuesta de Salida](#1101--respuesta-de-salida)
            - [1.10.1.1- Respuesta de éxito](#11011--respuesta-de-éxito)
    - [1.11.- Ingresar Reclamos por Ejecutivos](#111--ingresar-reclamos-por-ejecutivos)
        - [1.11.1.- Ejemplo de llamada](#1111--ejemplo-de-llamada)
        - [1.11.2.- Respuesta de Salida](#1112--respuesta-de-salida)
            - [1.11.2.1- Respuesta de error](#11121--respuesta-de-error)
            - [1.11.2.2- Respuesta de éxito](#11122--respuesta-de-éxito)
    - [1.12.- Total Reclamos Comuna](#112--total-reclamos-comuna)
        - [1.12.1.- Ejemplo de llamada](#1121--ejemplo-de-llamada)
        - [1.12.2.- Respuesta de Salida](#1122--respuesta-de-salida)
            - [1.12.2.1- Respuesta de éxito](#11221--respuesta-de-éxito)
    - [1.13.- Total Reclamos por Comuna](#113--total-reclamos-por-comuna)
        - [1.13.1.- Ejemplo de llamada](#1131--ejemplo-de-llamada)
        - [1.13.2.- Respuesta de Salida](#1132--respuesta-de-salida)
            - [1.13.2.1- Respuesta de éxito](#11321--respuesta-de-éxito)
    - [1.14.- Reclamos por Fecha](#114--reclamos-por-fecha)
        - [1.14.1.- Ejemplo de llamada](#1141--ejemplo-de-llamada)
        - [1.14.2.- Respuesta de Salida](#1142--respuesta-de-salida)
            - [1.14.2.1- Respuesta de éxito](#11421--respuesta-de-éxito)
    - [1.15.- Reclamos por Motivo y Servicio](#115--reclamos-por-motivo-y-servicio)
        - [1.15.1.- Ejemplo de llamada](#1151--ejemplo-de-llamada)
        - [1.15.2.- Respuesta de Salida](#1152--respuesta-de-salida)
            - [1.15.2.1- Respuesta de éxito](#11521--respuesta-de-éxito)
    - [1.16.- Tipos de Conformidad](#116--tipos-de-conformidad)
        - [1.16.1.- Respuesta de Salida](#1161--respuesta-de-salida)
            - [1.16.1.1- Respuesta de éxito](#11611--respuesta-de-éxito)
    - [1.17.- Macromotivos](#117--macromotivos)
        - [1.17.1.- Respuesta de Salida](#1171--respuesta-de-salida)
            - [1.17.1.1- Respuesta de éxito](#11711--respuesta-de-éxito)
    - [1.18.- Editar Reclamo](#118--editar-reclamo)
        - [1.18.1.- Ejemplo de llamada](#1181--ejemplo-de-llamada)
        - [1.18.2.- Respuesta de Salida](#1182--respuesta-de-salida)
            - [1.18.2.1- Respuesta de error](#11821--respuesta-de-error)
            - [1.18.2.2- Respuesta de éxito](#11822--respuesta-de-éxito)
    - [1.19.- Exportar Reclamos](#119--exportar-reclamos)
        - [1.19.1.- Ejemplo de llamada](#1191--ejemplo-de-llamada)
        - [1.19.2.- Respuesta de Salida](#1192--respuesta-de-salida)
            - [1.19.2.1- Respuesta de éxito](#11921--respuesta-de-éxito)
    - [1.20.- Tipos de Teléfonos](#120--tipos-de-teléfonos)
        - [1.20.1.- Respuesta de Salida](#1201--respuesta-de-salida)
            - [1.20.1.1- Respuesta de éxito](#12011--respuesta-de-éxito)
    - [1.21.- Datos del Cliente IVR](#121--datos-del-cliente-ivr)
        - [1.21.1.- Ejemplo de llamada](#1211--ejemplo-de-llamada)
        - [1.21.2.- Respuesta de Salida](#1212--respuesta-de-salida)
            - [1.21.2.1- Respuesta de error](#12121--respuesta-de-error)
            - [1.21.2.2- Respuesta de éxito](#12122--respuesta-de-éxito)
    - [1.22.- Lista de Comunas](#122--lista-de-comunas)
        - [1.22.1.- Respuesta de Salida](#1221--respuesta-de-salida)
            - [1.22.1.1- Respuesta de éxito](#12211--respuesta-de-éxito)
    - [1.23.- Lista de Regiones](#123--lista-de-regiones)
        - [1.23.1.- Respuesta de Salida](#1231--respuesta-de-salida)
            - [1.23.1.1- Respuesta de éxito](#12311--respuesta-de-éxito)
    - [1.24.- Ingresar Comentario de Reclamo](#124--ingresar-comentario-de-reclamo)
        - [1.24.1.- Ejemplo de llamada](#1241--ejemplo-de-llamada)
        - [1.24.2.- Respuesta de Salida](#1242--respuesta-de-salida)
            - [1.24.2.1- Respuesta de error](#12421--respuesta-de-error)
            - [1.24.2.2- Respuesta de éxito](#12422--respuesta-de-éxito)
    - [1.25.- Lista Subcategorías Internas](#125--lista-subcategorias-internas)
        - [1.25.1.- Ejemplo de llamada](#1251--ejemplo-de-llamada)
        - [1.25.2.- Respuesta de Salida](#1252--respuesta-de-salida)
            - [1.25.2.1- Respuesta de éxito](#12521--respuesta-de-éxito)
  - [2.- Sucursal](#1--Sucursal)
    - [2.1.- Ingresar Reclamos desde Sucursal](#21--ingresar-reclamos-desde-sucursal)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Tipos de Reclamos](#22--tipos-de-reclamos)
        - [2.2.1.- Respuesta de Salida](#221--respuesta-de-salida)
            - [2.2.1.1- Respuesta de éxito](#2211--respuesta-de-éxito)
    - [2.3.- Tipos de Medios de Notificación](#23--tipos-de-medios-de-notificación)
        - [2.3.1.- Respuesta de Salida](#231--respuesta-de-salida)
            - [2.3.1.1- Respuesta de éxito](#2311--respuesta-de-éxito)
    - [2.4.- Tipos de Servicios Contratados](#24--tipos-de-servicios-contratados)
        - [2.4.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
        - [2.4.2.- Respuesta de Salida](#242--respuesta-de-salida)
            - [2.4.2.1- Respuesta de error](#2421--respuesta-de-error)
            - [2.4.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
    - [2.5.- Lista de Servicios Contratados](#25--lista-de-servicios-contratados)
        - [2.5.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
        - [2.5.2.- Respuesta de Salida](#252--respuesta-de-salida)
            - [2.5.2.1- Respuesta de error](#2521--respuesta-de-error)
            - [2.5.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
    - [2.6.- Lista de Motivos de Reclamo](#26--lista-de-motivos-de-reclamo)
        - [2.6.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
        - [2.6.2.- Respuesta de Salida](#262--respuesta-de-salida)
            - [2.6.2.1- Respuesta de éxito](#2621--respuesta-de-éxito)
    - [2.7.- Lista de Submotivos de Reclamo](#27--lista-de-submotivos-de-reclamo)
        - [2.7.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
        - [2.7.2.- Respuesta de Salida](#272--respuesta-de-salida)
            - [2.7.2.1- Respuesta de error](#2721--respuesta-de-error)
            - [2.7.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
    - [2.8.- Lista de Reclamos por Cliente](#28--lista-de-reclamos-por-cliente)
        - [2.8.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
        - [2.8.2.- Respuesta de Salida](#282--respuesta-de-salida)
            - [2.8.2.1- Respuesta de error](#2821--respuesta-de-error)
            - [2.8.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
    - [2.9.- Tipos de Teléfono](#29--tipos-de-teléfono)
        - [2.9.1.- Respuesta de Salida](#291--respuesta-de-salida)
            - [2.9.1.1- Respuesta de éxito](#2911--respuesta-de-éxito)
    - [2.10.- Servicios Contratados por Cliente](#210--servicios-contratados-por-cliente)
        - [2.10.1.- Ejemplo de llamada](#2101--ejemplo-de-llamada)
        - [2.10.2.- Respuesta de Salida](#2102--respuesta-de-salida)
            - [2.10.2.1- Respuesta de error](#21021--respuesta-de-error)
            - [2.10.2.2- Respuesta de éxito](#21022--respuesta-de-éxito)
  - [3.- IVR](#3--ivr)
    - [3.1.- Informe Reclamos](#31--informe-reclamos)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
    - [3.2.- Grabar Registro](#32--grabar-registro)
        - [3.2.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
        - [3.2.2.- Respuesta de Salida](#322--respuesta-de-salida)
            - [3.2.2.1- Respuesta de error](#3221--respuesta-de-error)
            - [3.2.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
    - [3.3.- Ingresar](#33--ingresar)
        - [3.3.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
        - [3.3.2.- Respuesta de Salida](#332--respuesta-de-salida)
            - [3.3.2.1- Respuesta de error](#3321--respuesta-de-error)
            - [3.3.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
    - [3.4.- Actualizar Contingencia](#34--actualizar-contingencia)
        - [3.4.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
        - [3.4.2.- Respuesta de Salida](#342--respuesta-de-salida)
            - [3.4.2.1- Respuesta de error](#3421--respuesta-de-error)
            - [3.4.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
    - [3.5.- Actualizar Teléfono de Cliente](#35--actualizar-teléfono-de-cliente)
        - [3.5.1.- Ejemplo de llamada](#351--ejemplo-de-llamada)
        - [3.5.2.- Respuesta de Salida](#352--respuesta-de-salida)
            - [3.5.2.1- Respuesta de error](#3521--respuesta-de-error)
            - [3.5.2.2- Respuesta de éxito](#3522--respuesta-de-éxito)
    - [3.6.- Actualizar Motivo de Reclamo](#36--actualizar-motivo-de-reclamo)
        - [3.6.1.- Ejemplo de llamada](#361--ejemplo-de-llamada)
        - [3.6.2.- Respuesta de Salida](#362--respuesta-de-salida)
            - [3.6.2.1- Respuesta de error](#3621--respuesta-de-error)
            - [3.6.2.2- Respuesta de éxito](#3622--respuesta-de-éxito)
    - [3.7.- Actualizar Rut de Cliente](#37--actualizar-rut-de-cliente)
        - [3.7.1.- Ejemplo de llamada](#371--ejemplo-de-llamada)
        - [3.7.2.- Respuesta de Salida](#372--respuesta-de-salida)
            - [3.7.2.1- Respuesta de error](#3721--respuesta-de-error)
            - [3.7.2.2- Respuesta de éxito](#3722--respuesta-de-éxito)
    - [3.8.- Actualizar Rut de Cliente Solicitante](#38--actualizar-rut-de-cliente-solicitante)
        - [3.8.1.- Ejemplo de llamada](#381--ejemplo-de-llamada)
        - [3.8.2.- Respuesta de Salida](#382--respuesta-de-salida)
            - [3.8.2.1- Respuesta de error](#3821--respuesta-de-error)
            - [3.8.2.2- Respuesta de éxito](#3822--respuesta-de-éxito)
    - [3.9.- Actualizar Submotivo de Reclamo](#39--actualizar-submotivo-de-reclamo)
        - [3.9.1.- Ejemplo de llamada](#391--ejemplo-de-llamada)
        - [3.9.2.- Respuesta de Salida](#392--respuesta-de-salida)
            - [3.9.2.1- Respuesta de error](#3921--respuesta-de-error)
            - [3.9.2.2- Respuesta de éxito](#3922--respuesta-de-éxito)
    - [3.10.- Actualizar Medio de Notificación](#310--actualizar-medio-de-notificación)
        - [3.10.1.- Ejemplo de llamada](#3101--ejemplo-de-llamada)
        - [3.10.2.- Respuesta de Salida](#3102--respuesta-de-salida)
            - [3.10.2.1- Respuesta de error](#31021--respuesta-de-error)
            - [3.10.2.2- Respuesta de éxito](#31022--respuesta-de-éxito)
    - [3.11.- Actualizar Tipo de Teléfono Reclamado](#311--actualizar-tipo-de-teléfono-reclamado)
        - [3.11.1.- Ejemplo de llamada](#3111--ejemplo-de-llamada)
        - [3.11.2.- Respuesta de Salida](#3112--respuesta-de-salida)
            - [3.11.2.1- Respuesta de error](#31121--respuesta-de-error)
            - [3.11.2.2- Respuesta de éxito](#31122--respuesta-de-éxito)
    - [3.12.- Actualizar Tipo de Servicio](#312--actualizar-tipo-de-servicio)
        - [3.12.1.- Ejemplo de llamada](#3121--ejemplo-de-llamada)
        - [3.12.2.- Respuesta de Salida](#3122--respuesta-de-salida)
            - [3.12.2.1- Respuesta de error](#31221--respuesta-de-error)
            - [3.12.2.2- Respuesta de éxito](#31222--respuesta-de-éxito)
    - [3.13.- Actualizar Número Móvil Reclamado](#313--actualizar-número-móvil-reclamo)
        - [3.13.1.- Ejemplo de llamada](#3131--ejemplo-de-llamada)
        - [3.13.2.- Respuesta de Salida](#3132--respuesta-de-salida)
            - [3.13.2.1- Respuesta de error](#31321--respuesta-de-error)
            - [3.13.2.2- Respuesta de éxito](#31322--respuesta-de-éxito)
    - [3.14.- Actualizar Cliente Reclamante](#314--actualizar-cliente-reclamante)
        - [3.14.1.- Ejemplo de llamada](#3141--ejemplo-de-llamada)
        - [3.14.2.- Respuesta de Salida](#3142--respuesta-de-salida)
            - [3.14.2.1- Respuesta de error](#31421--respuesta-de-error)
            - [3.14.2.2- Respuesta de éxito](#31422--respuesta-de-éxito)
    - [3.15.- Actualizar Teléfono Reclamado](#315--actualizar-teléfono-reclamado)
        - [3.15.1.- Ejemplo de llamada](#3151--ejemplo-de-llamada)
        - [3.15.2.- Respuesta de Salida](#3152--respuesta-de-salida)
            - [3.15.2.1- Respuesta de error](#31521--respuesta-de-error)
            - [3.15.2.2- Respuesta de éxito](#31522--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Reclamos
## 1.1.- Tipos de Reclamos
Método que retorna lista de tipos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-reclamo`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de reclamo                       |
| DESCRIPCION    | string       | Tipo de reclamo                                  |

### 1.1.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.1.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 6,
                    "DESCRIPCION": "Comercial"
                },
                {
                    "CODIGO": 100,
                    "DESCRIPCION": "Otros"
                },
                {
                    "CODIGO": 76,
                    "DESCRIPCION": "Queja"
                },
                {
                    "CODIGO": 7,
                    "DESCRIPCION": "Técnico"
                }
            ]
        },
        "codigo": 200
    }

## 1.2.- Tipos de Soluciones
Método que retorna lista de tipos de soluciones.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-solucion`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de solución                      |
| DESCRIPCION    | string       | Tipo de solución                                 |

### 1.2.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.2.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 14,
                    "DESCRIPCION": "Pendiente de solución"
                },
                {
                    "CODIGO": 15,
                    "DESCRIPCION": "Solución diferida"
                },
                {
                    "CODIGO": 16,
                    "DESCRIPCION": "Solución inmediata"
                }
            ]
        },
        "codigo": 200
    }

## 1.3.- Tipos de Motivos de Reclamos
Método que retorna lista de motivos por el que se acoge o no el reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/motivo-acoge`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de motivos de reclamos           |
| DESCRIPCION    | string       | Tipo de motivos de reclamos                      |

### 1.3.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.3.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 28,
                    "DESCRIPCION": "Acoge"
                },
                {
                    "CODIGO": 30,
                    "DESCRIPCION": "Acoge parcialmente"
                },
                {
                    "CODIGO": 31,
                    "DESCRIPCION": "No aplica"
                },
                {
                    "CODIGO": 29,
                    "DESCRIPCION": "Rechaza"
                }
            ]
        },
        "codigo": 200
    }

## 1.4.- Tipos de Notificación
Método que retorna los tipos de medios de notificación para el cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-notificacion`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de notificación                  |
| DESCRIPCION    | string       | Tipo de notificación                             |

### 1.4.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.4.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 3,
                    "DESCRIPCION": "Correo electrónico"
                },
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Teléfono"
                }
            ]
        },
        "codigo": 200
    }

## 1.5.- Tipos de Servicios
Método que retorna lista de tipos de servicios.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNN-C                     |                                            | Rut del cliente             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de servicio                      |
| DESCRIPCION    | string       | Tipo de servicio                                 |

### 1.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "Rut":"96722400-6"
	}

### 1.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.5.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encontraron servicios contratados para el cliente, contacte al cliente para obtener mayor información del reclamo"
        },
        "codigo": 204
    }
  
#### 1.5.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 1,
                    "DESCRIPCION": "Servicio móvil"
                },
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Servicio fijo"
                }
            ]
        },
        "codigo": 200
    }

## 1.6.- Tipos de Servicios 2
Método que retorna lista de tipos de servicios.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tiposervicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| idServicio   | int          |                                | No                                         | ID del servicio             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de solución                      |
| DESCRIPCION    | string       | Tipo de solución                                 |

### 1.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}

### 1.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.6.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos para mostrar"
        },
        "codigo": 204
    }
  
#### 1.6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Telefonía móvil"
                }
            ]
        },
        "codigo": 200
    }

## 1.7.- Motivos
Método que retorna lista de motivos de reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                 |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------------:|----------------------------:|
| idServicio   | int          |                                | No                            | ID del servicio             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del motivo del reclamo                    |
| DESCRIPCION    | string       | Motivo del reclamo                               |

### 1.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}

### 1.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.7.2.1.- Respuesta de éxito

    [
        {
            "CODIGO": 1,
            "DESCRIPCION": "Calidad servicio"
        },
        {
            "CODIGO": 3,
            "DESCRIPCION": "Facturación - cobros"
        },
        {
            "CODIGO": 5,
            "DESCRIPCION": "Servicio técnico"
        },
        {
            "CODIGO": 2,
            "DESCRIPCION": "Ventas - contratos"
        }
    ]

## 1.8.- Tipos de Registro
Método que retorna lista de tipos de registro de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-registro`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de registro                      |
| DESCRIPCION    | string       | Tipo de registro                                 |

### 1.8.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.8.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 11,
                    "DESCRIPCION": "Asistencia telefónica"
                },
                {
                    "CODIGO": 102,
                    "DESCRIPCION": "Me quiero salir"
                },
                {
                    "CODIGO": 80,
                    "DESCRIPCION": "Oficio Subtel"
                },
                {
                    "CODIGO": 81,
                    "DESCRIPCION": "Sernac"
                },
                {
                    "CODIGO": 10,
                    "DESCRIPCION": "Teléfono (IVR)"
                },
                {
                    "CODIGO": 9,
                    "DESCRIPCION": "Web"
                }
            ]
        },
        "codigo": 200
    }

## 1.9.- Reclamos
Método que retorna detalle de reclamo o lista de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/informes/reclamo`

**Parámetros de entrada:**
| Campo          |  Tipo        | Formato                        |     Requerido         |             Descripción     |
|:--------------:|:------------:|:------------------------------:|:---------------------:|----------------------------:|
| folio          | int          |                                | Si                    | Número de folio             |
| nombreEjecutivo| string       |                                | Si                    | Nombre del ejecutivo        |

**Datos de salida:**
| Campo                           |  Tipo        |                         Descripción              |
|:--------------------------------|:------------:|-------------------------------------------------:| 
| RERE_ID_RECLAMO                 | int          | ID del reclamo                                   | 
| RERE_ID_SUBCATEGORIA_INTERNA    | int          | ID de la subcategoría interna                    | 
| RERE_NOMBRE_USUARIO             | string       | Nombre del usuario                               | 
| RERE_USUARIO_ACTUALIZA          | string       | Nombre del usuario que actualiza                 | 
| RERE_ID_TIPO_TELEFONO           | int          | ID del tipo de teléfono                          | 
| RERE_DIRECCION_CEL_RECLAMADO    | string       | Dirección del celular reclamado                  | 
| RERE_FECHA_CIERRE               | timestamp    | Fecha de cierre                                  | 
| RERE_FECHA_NOTIFICACION         | timestamp    | Fecha de notificación                            | 
| RERE_FOLIO                      | string       | Número de folio                                  | 
| RERE_TEXTO                      | string       | Detalle del reclamo                              | 
| RERE_FECHA_REGISTRO             | timestamp    | Fecha de registro                                | 
| RERE_FECHA_RECLAMO              | timestamp    | Fecha de reclamo                                 | 
| RERE_CALLER_ID                  | int          | ID caller                                        | 
| RERE_ID_TIPO_NOTIFICACION       | int          | ID del tipo de notificación                      | 
| RERE_ID_ESTADO_RECLAMO          | int          | ID del estado del reclamo                        | 
| RERE_ID_SOLICITANTE             | int          | ID del solicitante                               | 
| RERE_ID_TIPO_RECLAMO            | int          | ID del tipo de reclamo                           | 
| RERE_ID_TIPO_SOLUCION           | int          | ID del tipo de solución                          | 
| RERE_ID_TIPO_REGISTRO           | int          | ID del tipo de registro                          | 
| RERE_ID_SERVICIO                | int          | ID del servicio                                  | 
| RERE_ID_TIPO_SERVICIO           | int          | ID del tipo de servicio                          | 
| RERE_ID_MOTIVO                  | int          | ID del motivo                                    | 
| RERE_ID_SUB_MOTIVO              | int          | ID del submotivo                                 | 
| RERE_ID_MACROMOTIVO             | int          | ID del macromotivo                               | 
| RERE_ID_CONFORMIDAD             | int          | ID de la conformidad                             | 
| RERE_HORAS_SIN_SERVICIO         | int          | Cantidad de horas sin servicio                   | 
| RERE_MONTO_TOTAL_RECLAMADO      | int          | Monto total reclamado                            | 
| RERE_CELULAR_RECLAMADO          | int          | Número de celular reclamado                      | 
| RERE_AREA_TELEFONO_RECLAMADO    | int          | Área del teléfono reclamado                      | 
| RERE_TELEFONO_RECLAMADO         | int          | Teléfono reclamado                               | 
| RERE_DIRECCION_TEL_RECLAMADO    | string       | Dirección del teléfono reclamado                 | 
| RERE_TOTAL_DESCUENTO            | int          | Total del descuento                              | 
| RERE_MONTO_INDEMNIZACION        | int          | Monto de indemnización                           | 
| RERE_MONTO_DESCUENTO            | int          | Monto de descuento                               | 
| RERE_ID_RECLAMO_SUBTEL          | int          | ID del reclamo Subtel                            | 
| RERE_ID_RECLAMO_SERNAC          | int          | ID del reclamo Sernac                            | 
| RERE_ID_USUARIO                 | int          | ID del usuario                                   | 
| RERE_ID_USUARIO_ACTUALIZA       | int          | ID del usuario que actualiza                     | 
| RERE_ID_ME_QUIERO_SALIR         | int          | ID me quiero salir                               | 
| ↓ tipo_notificacion             | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción de la notificación                   | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de notificación                      | 
| ↓ estado                        | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del estado                           | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del estado                                    | 
| ↓ solicitante                   | array[object]|                                                  | 
| ⤷ RESO_RUT                      | int          | Rut del solicitante                              | 
| ⤷ RESO_ES_TITULAR               | boolean      | Solicitante titular o no                         | 
| ⤷ RESO_RUT_DV                   | string       | Dígito verficador del rut del solicitante        | 
| ⤷ RESO_NUMERO_CALLE_REPRESENTANTE| int         | Número de calle                                  | 
| ⤷ RESO_NOMBRE_RAZON             | string       | Nombre o razón social del solicitante            | 
| ⤷ RESO_CODIGO_CLIENTE_BU        | string       | Código de cliente BU                             | 
| ⤷ RESO_ID_SOLICITANTE           | int          | ID del solicitante                               | 
| ⤷ RESO_COMUNA                   | string       | Nombre de comuna                                 | 
| ⤷ RESO_ID_COMUNA                | int          | ID de la comuna                                  | 
| ⤷ RESO_REGION                   | string       | Nombre de la región                              | 
| ⤷ RESO_ID_REGION                | int          | ID de la región                                  | 
| ⤷ RESO_PLAN_PRINCIPAL           | string       | Plan contratado                                  | 
| ⤷ RESO_NODO                     | string       | Nodo                                             | 
| ⤷ RESO_RUT_REPRESENTANTE        | int          | Rut del representante                            | 
| ⤷ RESO_RUT_DV_REPRESENTANTE     | string       | Dígito verficador del rut del representante      | 
| ⤷ RESO_NOMBRE_REPRESENTANTE     | string       | Nombre del representante                         | 
| ⤷ RESO_APELLIDOS_REPRESENTANTE  | string       | Apellidos del representante                      | 
| ⤷ RESO_TELEFONO_REPRESENTANTE   | int          | Teléfono del representante                       | 
| ⤷ RESO_EMAIL_REPRESENTANTE      | string       | Correo electrónico del representante             | 
| ⤷ RESO_EMAIL                    | string       | Correo electrónico del solicitante               | 
| ⤷ RESO_COMUNA_REPRESENTANTE     | string       | Nombre de la comuna del representante            | 
| ⤷ RESO_ID_COMUNA_REPRESENTANTE  | int          | ID de la comuna del representante                | 
| ⤷ RESO_DIRECCION_REPRESENTANTE  | string       | Dirección del representante                      | 
| ⤷ RESO_ID_REGION_REPRESENTANTE  | int          | ID de la región del representante                | 
| ⤷ RESO_REGION_REPRESENTANTE     | string       | Región del representante                         | 
| ⤷ RESO_CALLE                    | string       | Calle del solicitante                            | 
| ⤷ RESO_CLIENTE_UNIFICADO        | int          | Código del cliente unificado                     | 
| ⤷ RESO_TELEFONO                 | int          | Teléfono del solicitante                         |  
| ↓ tipo_reclamo                  | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de reclamo                  | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de reclamo                           | 
| ↓ tipo_solucion                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de solución                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de solución                          |
| ↓ tipo_registro                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de registro                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de registro                          |
| ↓ tipo_telefono                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de teléfono                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de teléfono                          |
| ↓ servicio                      | array[object]|                                                  | 
| ⤷ RESE_DESCRIPCION              | string       | Descripción del servicio                         | 
| ⤷ RESE_ID_SERVICIO              | int          | ID del servicio                                  |
| ↓ tipo_servicio                 | array[object]|                                                  | 
| ⤷ RETE_DESCRIPCION              | string       | Descripción del tipo de servicio                 | 
| ⤷ RETE_ID_TIPO_SERVICIO         | int          | ID del tipo de servicio                          |
| ↓ motivo                        | array[object]|                                                  | 
| ⤷ REMO_DESCRIPCION              | string       | Descripción del motivo                           | 
| ⤷ REMO_ID_MOTIVO                | int          | ID del motivo                                    |
| ↓ sub_motivo                    | array[object]|                                                  | 
| ⤷ RESM_DESCRIPCION              | string       | Descripción del submotivo                        | 
| ⤷ RESM_ID_SUB_MOTIVO            | int          | ID del submotivo                                 |
|   macromotivo                   | array[object]| Array con el macromotivo (Sin uso en esta ruta)  |
|   conformidad                   | array[object]| Array con la conformidad (Sin uso en esta ruta)  | 
|   archivos                      | array[object]| Array con los archivos (Sin uso en esta ruta)    | 
| ↓ acoge_reclamos                | array[object]|                                                  | 
| ⤷ REAR_ID_AGOGE_RECLAMO         | int          | ID de reclamo acogido                            |
| ⤷ REAR_FECHA_REGISTRO           | timestamp    | Fecha de registro                                |
| ⤷ REAR_COMENTARIO               | string       | Comentario                                       |
| ⤷ REAR_ID_RECLAMO               | int          | ID del reclamo                                   |
| ⤷ REAR_ID_ACOGE                 | int          | ID acoge                                         |
| ⤷ REAR_ID_USUARIO               | int          | ID usuario                                       |
| ⤷ REAR_USUARIO                  | string       | Nombre del usuario                               |
| ↓↓ tipo_acoge                   | array[object]|                                                  | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del subtipo                                   |
| ⤷ RETS_ID_ORIGEN                | int          | ID origen                                        |
| ⤷ RETS_DESCRIPCION              | string       | Descripción                                      |
| ⤷ RETS_CODIGO                   | string       | Código tipo acoge                                |
| ⤷ RETS_VIGENTE                  | boolean      | Si está vigente o no                             |
| ⤷ RETS_ID_REGISTRO_PADRE        | int          | ID del registro padre                            |
|   sub_categoria_interna         | array[object]| Array con las subcategorías internas (Sin uso en esta ruta)| 
| ↓ comentarios                   | array[object]|                                                  | 
| ⤷ REC_ID_COMENTARIO             | int          | ID del comentario                                |
| ⤷ REC_ID_RECLAMO                | int          | ID del reclamo                                   |
| ⤷ REC_DESC                      | string       | Descripción del comentario                       |
| ⤷ REC_DESC_USUARIO              | string       | Nombre del usuario                               |
| ⤷ REC_FECHA_REGISTRO            | timestamp    | Fecha de registro                                |
| ⤷ REC_ACTUALIZADO               | timestamp    | Fecha de actualización                           |
| ⤷ REC_VIGENTE                   | boolean      | Si está vigente o no                             |
| ⤷ REC_NOTIFICA_CLIENTE          | boolean      | Si se notificó a cliente o no                    |
| ↓↓ archivos                     | int          |                                                  |
| ⤷ REARC_ID_ARCHIVO              | int          | ID del archivo                                   |
| ⤷ REARC_ID_COMENTARIO           | int          | ID del comentario                                |
| ⤷ REARC_NOMBRE                  | string       | Nombre del archivo                               |
| ⤷ REARC_RUTA                    | string       | Ruta del archivo                                 |
| ⤷ REARC_ID_EXTENSION            | int          | ID de la extensión                               |
| ⤷ REARC_NOMBRE_REF              | string       | Referencia del nombre del archivo                |
|   subtel                        | array[object]| Array de reclamo de Subtel (Sin uso en esta ruta)|
|   sernac                        | array[object]| Array de reclamo de Sernac (Sin uso en esta ruta)| 
|   me_quiero_salir               | array[object]| Array de 'Me quiero salir' (Sin uso en esta ruta)| 
| ↓ usuario_crea                  | array[object]|                                                  | 
| ⤷ RU_ID                         | int          | ID del usuario                                   |
| ⤷ RU_EMAIL                      | string       | Correo electrónico del usuario                   |
| ⤷ RU_NOMBRE                     | string       | Nombre del usuario                               |
|   usuario_actualiza             | array[object]| Array de usuario que actualiza (sin uso en esta ruta)|

### 1.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "folio": 20214890,
        "nombreEjecutivo": "Oscar%20Dario%20Roman%20Millan"
	}

### 1.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.9.2.1.- Respuesta de éxito

    {
        "current_page": 1,
        "data": [
            {
                "RERE_ID_RECLAMO": 5704,
                "RERE_ID_SUBCATEGORIA_INTERNA": null,
                "RERE_NOMBRE_USUARIO": "Oscar Dario Roman Millan",
                "RERE_USUARIO_ACTUALIZA": "Oscar Dario Roman Millan",
                "RERE_ID_TIPO_TELEFONO": null,
                "RERE_DIRECCION_CEL_RECLAMADO": null,
                "RERE_FECHA_CIERRE": null,
                "RERE_FECHA_NOTIFICACION": "2021-08-30 18:43:20",
                "RERE_FOLIO": "20214890",
                "RERE_TEXTO": "Esto es un texto de prueba de reclamos",
                "RERE_FECHA_REGISTRO": "2021-08-30 18:43:20",
                "RERE_FECHA_RECLAMO": "2021-08-30 18:43:20",
                "RERE_CALLER_ID": null,
                "RERE_ID_TIPO_NOTIFICACION": 3,
                "RERE_ID_ESTADO_RECLAMO": 22,
                "RERE_ID_SOLICITANTE": 4897,
                "RERE_ID_TIPO_RECLAMO": 100,
                "RERE_ID_TIPO_SOLUCION": 14,
                "RERE_ID_TIPO_REGISTRO": 11,
                "RERE_ID_SERVICIO": 2,
                "RERE_ID_TIPO_SERVICIO": 9,
                "RERE_ID_MOTIVO": 1,
                "RERE_ID_SUB_MOTIVO": 12,
                "RERE_ID_MACROMOTIVO": null,
                "RERE_ID_CONFORMIDAD": null,
                "RERE_HORAS_SIN_SERVICIO": 0,
                "RERE_MONTO_TOTAL_RECLAMADO": null,
                "RERE_CELULAR_RECLAMADO": null,
                "RERE_AREA_TELEFONO_RECLAMADO": 22,
                "RERE_TELEFONO_RECLAMADO": 999999999,
                "RERE_DIRECCION_TEL_RECLAMADO": "LOS JAZMINES 91",
                "RERE_TOTAL_DESCUENTO": null,
                "RERE_MONTO_INDEMNIZACION": null,
                "RERE_MONTO_DESCUENTO": null,
                "RERE_ID_RECLAMO_SUBTEL": null,
                "RERE_ID_RECLAMO_SERNAC": null,
                "RERE_ID_USUARIO": 2,
                "RERE_ID_USUARIO_ACTUALIZA": null,
                "RERE_ID_ME_QUIERO_SALIR": null,
                "tipo_notificacion": {
                    "RETS_DESCRIPCION": "Correo electrónico",
                    "RETS_ID_SUBTIPO": 3
                },
                "estado": {
                    "RETS_DESCRIPCION": "Revisado",
                    "RETS_ID_SUBTIPO": 22
                },
                "solicitante": {
                    "RESO_RUT": 17225523,
                    "RESO_ES_TITULAR": true,
                    "RESO_RUT_DV": "k",
                    "RESO_NUMERO_CALLE_REPRESENTANTE": 91,
                    "RESO_NOMBRE_RAZON": "Denisse Milenka",
                    "RESO_CODIGO_CLIENTE_BU": "CC623805",
                    "RESO_ID_SOLICITANTE": 4897,
                    "RESO_COMUNA": "El Monte",
                    "RESO_ID_COMUNA": 13602,
                    "RESO_REGION": "Región Metropolitana de Santiago",
                    "RESO_ID_REGION": 13,
                    "RESO_PLAN_PRINCIPAL": "FIBRA + TVHD",
                    "RESO_NODO": "EMON_25",
                    "RESO_RUT_REPRESENTANTE": 17225523,
                    "RESO_RUT_DV_REPRESENTANTE": "k",
                    "RESO_NOMBRE_REPRESENTANTE": "Denisse Milenka",
                    "RESO_APELLIDOS_REPRESENTANTE": "Gajardo Hernández",
                    "RESO_TELEFONO_REPRESENTANTE": 987030303,
                    "RESO_EMAIL_REPRESENTANTE": "oscar.roman@mundopacifico.cl",
                    "RESO_EMAIL": "oscar.roman@mundopacifico.cl",
                    "RESO_COMUNA_REPRESENTANTE": "El Monte",
                    "RESO_ID_COMUNA_REPRESENTANTE": 13602,
                    "RESO_DIRECCION_REPRESENTANTE": "LOS JAZMINES",
                    "RESO_ID_REGION_REPRESENTANTE": 13,
                    "RESO_REGION_REPRESENTANTE": "Región Metropolitana de Santiago",
                    "RESO_CALLE": "LOS JAZMINES",
                    "RESO_CLIENTE_UNIFICADO": 624137,
                    "RESO_TELEFONO": 0
                },
                "tipo_reclamo": {
                    "RETS_DESCRIPCION": "Otros",
                    "RETS_ID_SUBTIPO": 100
                },
                "tipo_solucion": {
                    "RETS_DESCRIPCION": "Pendiente de solución",
                    "RETS_ID_SUBTIPO": 14
                },
                "tipo_registro": {
                    "RETS_DESCRIPCION": "Asistencia telefónica",
                    "RETS_ID_SUBTIPO": 11
                },
                "tipo_telefono": null,
                "servicio": {
                    "RESE_DESCRIPCION": "Servicio fijo",
                    "RESE_ID_SERVICIO": 2
                },
                "tipo_servicio": {
                    "RETE_DESCRIPCION": "Internet fijo - telefonía",
                    "RETE_ID_TIPO_SERVICIO": 9
                },
                "motivo": {
                    "REMO_DESCRIPCION": "Calidad servicio",
                    "REMO_ID_MOTIVO": 1
                },
                "sub_motivo": {
                    "RESM_DESCRIPCION": "Intermitencia",
                    "RESM_ID_SUB_MOTIVO": 12
                },
                "macromotivo": null,
                "conformidad": null,
                "archivos": [],
                "acoge_reclamo": [
                    {
                        "REAR_ID_AGOGE_RECLAMO": 514,
                        "REAR_FECHA_REGISTRO": "2021-08-30 18:43:20",
                        "REAR_COMENTARIO": null,
                        "REAR_ID_RECLAMO": 5704,
                        "REAR_ID_ACOGE": 30,
                        "REAR_ID_USUARIO": 624137,
                        "REAR_USUARIO": "Denisse Milenka",
                        "tipo_acoge": {
                            "RETS_ID_SUBTIPO": 30,
                            "RETS_ID_ORIGEN": null,
                            "RETS_DESCRIPCION": "Acoge parcialmente",
                            "RETS_CODIGO": "03",
                            "RETS_VIGENTE": true,
                            "RETS_ID_REGISTRO_PADRE": 27
                        }
                    }
                ],
                "sub_categoria_interna": null,
                "comentarios": [
                    {
                        "REC_ID_COMENTARIO": 147,
                        "REC_ID_RECLAMO": 5704,
                        "REC_DESC": "esto es una respuesta al cliente de prueba con url firmada de archivo",
                        "REC_DESC_USUARIO": "Oscar Dario Roman Millan",
                        "REC_FECHA_REGISTRO": "2021-08-30 18:45:00",
                        "REC_ACTUALIZADO": "2021-08-30 18:45:00",
                        "REC_VIGENTE": true,
                        "REC_NOTIFICA_CLIENTE": true,
                        "archivos": [
                            {
                                "REARC_ID_ARCHIVO": 37,
                                "REARC_ID_COMENTARIO": 147,
                                "REARC_NOMBRE": "612d5f73dd495.pdf",
                                "REARC_RUTA": "/storage/archivos/612d5f73dd495.pdf",
                                "REARC_ID_EXTENSION": 70,
                                "REARC_NOMBRE_REF": "PDF de prueba - Carta de respuesta.pdf"
                            }
                        ]
                    }
                ],
                "subtel": null,
                "sernac": null,
                "me_quiero_salir": null,
                "usuario_crea": {
                    "RU_ID": 2,
                    "RU_EMAIL": "oscar.roman@mundopacifico.cl",
                    "RU_NOMBRE": "Oscar Dario Roman Millan"
                },
                "usuario_actualiza": null
            }
        ],
        "first_page_url": "http://reclamos-dev.mundopacifico.cl/informes/reclamo?folio=20214890&nombreEjecutivo=Oscar%20Dario%20Roman%20Millan&page=1",
        "from": 1,
        "last_page": 1,
        "last_page_url": "http://reclamos-dev.mundopacifico.cl/informes/reclamo?folio=20214890&nombreEjecutivo=Oscar%20Dario%20Roman%20Millan&page=1",
        "next_page_url": null,
        "path": "http://reclamos-dev.mundopacifico.cl/informes/reclamo",
        "per_page": 15,
        "prev_page_url": null,
        "to": 1,
        "total": 1
    }

## 1.10.- Estado de Reclamo
Método que retorna lisa de estaos de reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/estado-reclamos`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del estado del reclamo                    |
| DESCRIPCION    | string       | Descripción del estado del reclamo               |

### 1.10.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.10.1.1.- Respuesta de éxito

    [
        {
            "CODIGO": 26,
            "DESCRIPCION": "Abierto"
        },
        {
            "CODIGO": 25,
            "DESCRIPCION": "Cerrado"
        },
        {
            "CODIGO": 23,
            "DESCRIPCION": "En proceso"
        },
        {
            "CODIGO": 21,
            "DESCRIPCION": "Registrado"
        },
        {
            "CODIGO": 22,
            "DESCRIPCION": "Revisado"
        },
        {
            "CODIGO": 24,
            "DESCRIPCION": "Términado"
        }
    ]

## 1.11.- Ingresar Reclamos por Ejecutivos
Método que permite ingresar reclamos en el portal por ejecutivos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/reclamo-ejecutivo-ingresar`

**Parámetros de entrada:**
| Campo                      |  Tipo        | Formato       | Requerido  |             Descripción     |
|:--------------------------:|:------------:|:-------------:|:----------:|----------------------------:|
| rutCliente                 | string       | NNNNNNNN      | Si         | Rut del cliente             |
| dvCliente                  | int          |               | Si         | Dígito verificador del rut del cliente|
| clienteUnificado           | string       |               |            | Código de cliente unificado |
| codigoClienteBu            | string       |               |            | Código del cliente BU       |
| idConexion                 | int          |               |            | ID de la conexión           |
| nombreRazon                | string       |               | Si         | Nombre o razón social del cliente|
| clienteNodo                | int          |               |            | Nodo                        |
| apellidos                  | string       |               |            | Apellidos del cliente       |
| calle                      | string       |               |            | Calle del cliente           |
| numeroCalle                | string       |               |            | Número de la calle          |
| email                      | string       |               | Si         | Correo electrónico del cliente|
| planPrincipal              | int          |               |            | Plan contratado             |
| fechaReclamo               | string       |               | Si         | Fecha del reclamo           |
| tipoNotificacion           | int          |               | Si         | ID del tipo de notificación |
| servicio                   | int          |               |            | ID del servicio             |
| tipoServicio               | int          |               | Si         | ID del tipo de servicio     |
| motivo                     | int          |               | Si         | ID del motivo               |
| idComuna                   | int          |               |            | ID de la comuna             |
| comuna                     | string       |               |            | Nombre de la comuna         |
| region                     | int          |               |            | Nombre de la región         |
| comentario                 | string       |               |            | Comentario                  |
| telefono                   | int          |               |            | Teléfono del cliente        |
| tipoSolucion               | int          |               | Si         | ID del tipo de solución     |
| tipoReclamo                | int          |               |            | ID del tipo de reclamo      |
| numeroContingencia         | string       |               |            | Número de contingencia      |
| ↓ archivos                 | array[object]|               |            |                             |
| ⤷ nombre                   | string       |               |            | Nombre del archivo          |
| ⤷ base64                   | string       |               |            | Archivo en formato base64   |
| ⤷ peso                     | int          |               |            | Peso del archivo            |
| ⤷ tipoarchivo              | string       |               |            | Tipo de archivo             |
| idAcoge                    | int          |               |            | ID Acoge                    |
| tipoRegistro               | int          |               |            | ID del tipo de registro     |
| celularReclamado           | string       |               |            | Número de celular reclamado |
| telefonoReclamado          | string       |               |            | Número de teléfono reclamado|
| areaTelefonoReclamado      | string       |               |            | Área del teléfono reclamado |
| direccionTelefonoReclamado | string       |               |            | Dirección del teléfono reclamado|
| rutRepresentante           | string       |               |            | Rut del representante       |
| dvRepresentante            | string       |               |            | Dígito verificador del rut del representante|
| nombreRepresentante        | string       |               |            | Nombre del representante    |
| apellidosRepresentante     | string       |               |            | Apellidos del representante |
| telefonoRepresentante      | string       |               |            | Teléfono del representante  |
| celularRepresentante       | string       |               |            | Celular del representante   |
| emailRepresentante         | string       |               |            | Correo electrónico del representante |
| direccionRepresentante     | string       |               |            | Dirección del representante |
| comunaRepresentante        | string       |               |            | Comuna del representante    |
| idComunaRepresentante      | int          |               |            | ID de la comuna del representate |
| totalReclamado             | string       |               |            | Total reclamado             |
| horasSinServicio           | string       |               |            | Cantidad de horas sin servicio|
| texto                      | string       |               |            | Texto                       |

### 1.11.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "rutCliente": "11111111",
        "dvCliente": 1,
        "clienteUnificado": "284953",
        "codigoClienteBu": "CC38860",
        "idConexion": null,
        "nombreRazon": "Cavicchioli Limitada",
        "clienteNodo": null,
        "apellidos": "Sociedad Comercial",
        "calle": "Mi domicilio de prueba",
        "numeroCalle": "22",
        "email": "oscar.roman@mundopacifico.cl",
        "planPrincipal": null,
        "fechaReclamo": "2021/01/12",
        "tipoNotificacion": 3,
        "servicio": 1,
        "tipoServicio": 1,
        "motivo": 1,
        "idComuna": 8101,
        "comuna": "Concepción",
        "region": 8,
        "comentario": "no aplica",
        "telefono": null,
        "tipoSolucion": 15,
        "tipoReclamo": 76,
        "numeroContingencia": "",
        "archivos": [],
        "idAcoge": 31,
        "tipoRegistro": 9,
        "celularReclamado": "999999999",
        "telefonoReclamado": "",
        "areaTelefonoReclamado": "",
        "direccionTelefonoReclamado": "",
        "rutRepresentante": "11111111",
        "dvRepresentante": 1,
        "nombreRepresentante": "Cavicchioli Limitada",
        "apellidosRepresentante": "Sociedad Comercial",
        "telefonoRepresentante": "999999999",
        "celularRepresentante": "999999999",
        "emailRepresentante": "oscar.roman@mundopacifico.cl",
        "direccionRepresentante": "Mi domicilio de prueba",
        "comunaRepresentante": "Concepción",
        "idComunaRepresentante": 8101,
        "totalReclamado": "",
        "horasSinServicio": "0",
        "texto": "sdsdsdsd"
    }

### 1.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.11.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": "No se pueden procesar los campos",
            "detalleRespuesta": [
                "El NOMBRE_CAMPO es obligatorio"
            ]
        },
        "code": 422
    }
  
#### 1.11.2.2.- Respuesta de éxito

`El reclamo ha sido ingresado con número de folio asociado: <b>2021875</b>`

## 1.12.- Total Reclamos Comunas
Método que retorna los datos para el reporte gráfico de reclamos de todas las comunas.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-total-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | yyyy-mm-dd                     |                              | Fecha de inicio             |
| fechaTermino | string       | yyyy-mm-dd                     |                              | Fecha de término            |
| idRegion     | int          |                                | Si                           | ID de la región             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| color          | string       | Color en hexadecimal                             |
| name           | string       | Nombre                                           |
| ↓ reclamos     | array[object]|                                                  |
| ⤷ name         | string       | Nombre de la comuna                              |
| ⤷ Reclamos     | int          | Cantidad de reclamos                             |

### 1.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "fechaInicio": "2020-12-11",
        "fechaTermino": "2021-01-11",
        "idRegion": 8
    }


### 1.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.12.2.1.- Respuesta de éxito

    {
        "color": "#64b5f6",
        "name": "Reclamos",
        "reclamos": [
            {
                "name": "Alto Biobío",
                "Reclamos": 0
            },
            {
                "name": "Antuco",
                "Reclamos": 0
            },
            {
                "name": "Arauco",
                "Reclamos": 0
            },
            {
                "name": "Cabrero",
                "Reclamos": 0
            },
            {
                "name": "Cañete",
                "Reclamos": 0
            },
            {
                "name": "Chiguayante",
                "Reclamos": 1
            },
            {
                "name": "Concepción",
                "Reclamos": 12
            },
            ...
        ]
    }

## 1.13.- Reclamos por Comuna
Método que retorna los datos para el reporte gráfico de reclamos por comuna.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | yyyy-mm-dd                     |                              | Fecha de inicio             |
| fechaTermino | string       | yyyy-mm-dd                     |                              | Fecha de término            |
| comunas      | array[int]   |                                | Si                           | Listado de comunas          |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ estados      | array[object]|                                                  |
| ⤷ color        | string       | Color en hexadecimal                             |
| ⤷ name         | string       | Nombre del estado del reclamo                    |
| ↓ reclamos     | array[object]|                                                  |
| ⤷ name         | string       | Nombre de la comuna                              |
| ⤷ Abierto      | int          | Cantidad de reclamos abiertos                    |
| ⤷ Cerrado      | int          | Cantidad de reclamos cerrados                    |
| ⤷ En proceso   | int          | Cantidad de reclamos en proceso                  |
| ⤷ Registrado   | int          | Cantidad de reclamos registrados                 |
| ⤷ Revisado     | int          | Cantidad de reclamos revisados                   |
| ⤷ Términado    | int          | Cantidad de reclamos terminados                  |

### 1.13.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "fechaInicio": "2021-01-01",
        "fechaTermino": "2021-02-15",
        "comunas": [16101, 8112]
    }

### 1.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.13.2.1.- Respuesta de éxito

    {
        "estados": [
            {
                "color": "#0088FE",
                "name": "Abierto"
            },
            {
                "color": "#00C49F",
                "name": "Cerrado"
            },
            {
                "color": "#FFBB28",
                "name": "En proceso"
            },
            {
                "color": "#FF8042",
                "name": "Registrado"
            },
            {
                "color": "#e57373",
                "name": "Revisado"
            },
            {
                "color": "#ba68c8",
                "name": "Términado"
            }
        ],
        "reclamos": [
            {
                "name": "Aisén",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "Algarrobo",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "Alhué",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "Alto Biobío",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 1,
                "Revisado": 0,
                "Términado": 0
            },
           ...
        ]
    }
    
## 1.14.- Reclamos por Fecha
Método que retorna los datos para el reporte gráfico de reclamos por rango de fecha.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-fecha`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | yyyy-mm-dd                     |                              | Fecha de inicio             |
| fechaTermino | string       | yyyy-mm-dd                     |                              | Fecha de término            |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ estados      | array[object]|                                                  |
| ⤷ color        | string       | Color en hexadecimal                             |
| ⤷ name         | string       | Nombre del estado del reclamo                    |
| ↓ reclamos     | array[object]|                                                  |
| ⤷ name         | string       | Nombre de la comuna                              |
| ⤷ Abierto      | int          | Cantidad de reclamos abiertos                    |
| ⤷ Cerrado      | int          | Cantidad de reclamos cerrados                    |
| ⤷ En proceso   | int          | Cantidad de reclamos en proceso                  |
| ⤷ Registrado   | int          | Cantidad de reclamos registrados                 |
| ⤷ Revisado     | int          | Cantidad de reclamos revisados                   |
| ⤷ Términado    | int          | Cantidad de reclamos terminados                  |

### 1.14.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
    "fechaInicio": "2021-01-01",
    "fechaTermino": "2021-01-05"
    }

### 1.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.14.2.1.- Respuesta de éxito

    {
        "estados": [
            {
                "color": "#0088FE",
                "name": "Abierto"
            },
            {
                "color": "#00C49F",
                "name": "Cerrado"
            },
            {
                "color": "#FFBB28",
                "name": "En proceso"
            },
            {
                "color": "#FF8042",
                "name": "Registrado"
            },
            {
                "color": "#e57373",
                "name": "Revisado"
            },
            {
                "color": "#ba68c8",
                "name": "Términado"
            }
        ],
        "reclamos": [
            {
                "name": "01-01-2021",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "02-01-2021",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "03-01-2021",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 0,
                "Revisado": 0,
                "Términado": 0
            },
            {
                "name": "04-01-2021",
                "Abierto": 0,
                "Cerrado": 0,
                "En proceso": 0,
                "Registrado": 3,
                "Revisado": 0,
                "Términado": 0
            }
        ]
    }

## 1.15.- Reclamos por Motivo y Servicio
Método que retorna los datos para el reporte gráfico de reclamos por motivos y servicios.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-servicio-motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | yyyy-mm-dd                     |                              | Fecha de inicio             |
| fechaTermino | string       | yyyy-mm-dd                     |                              | Fecha de término            |
| idServicio   | int          |                                | Si                           | ID del servicio             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ motivos      | array[object]|                                                  |
| color          | string       | Color en hexadecimal                             |
| name           | string       | Nombre del servicio                              |
| ↓ reclamos     | array[object]|                                                  |
| name           | string       | Nombre del servicio                              |
| value          | int          | Cantidad del reclamos                            |

### 1.15.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "fechaInicio": "2020-12-11",
        "fechaTermino": "2021-01-11",
        "idServicio": 1
    }

### 1.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.15.2.1.- Respuesta de éxito

    {
        "motivos": [
            {
                "color": "#0088FE",
                "name": "Calidad servicio"
            },
            {
                "color": "#00C49F",
                "name": "Facturación - cobros"
            },
            {
                "color": "#FFBB28",
                "name": "Servicio técnico"
            },
            {
                "color": "#FF8042",
                "name": "Ventas - contratos"
            }
        ],
        "reclamos": [
            {
                "name": "Calidad servicio",
                "value": 7
            },
            {
                "name": "Facturación - cobros",
                "value": 1
            },
            {
                "name": "Servicio técnico",
                "value": 3
            }
        ]
    }
    
## 1.16.- Tipos de Conformidad
Método que retorna el listado de tipos de conformidad del reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-conformidad`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de conformidad                   |
| DESCRIPCION    | string       | Tipo de conformidad                              |

### 1.16.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.16.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 33,
                    "DESCRIPCION": "Conforme"
                },
                {
                    "CODIGO": 34,
                    "DESCRIPCION": "No conforme"
                }
            ]
        },
        "codigo": 200
    }

## 1.17.- Macromotivos
Método que retorna el listado de macromotivos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/macromotivo`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del macromotivo                           |
| DESCRIPCION    | string       | Tipo de macromotivo                              |

### 1.17.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.17.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 1,
                    "DESCRIPCION": "Ventas / Contratos ,Telefonia Movil - Telefonia Fija - Mensajeria - BAM - Internet Movil - Internet Fija- TV pagada"
                },
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Facturacion, Telefonia Movil - Telefonia Fija - Mensajeria - BAM - Internet Movil - Internet Fija-TV pagada"
                },
                ...
            ]
        },
        "codigo": 200
    }

## 1.18.- Editar Reclamo
Método que permite editar un reclamo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/reclamo-editar`

**Parámetros de entrada:**
| Campo                  |  Tipo        | Formato    | Requerido   |             Descripción     |
|:----------------------:|:------------:|:----------:|:------------|----------------------------:|
| idReclamo              | int          |            | Si          | ID del reclamo              |
| estado                 | int          |            |             | Estado del reclamo          |
| texto                  | string       |            |             | Explicación del reclamo     |
| fechaReclamo           | timestamp    |            |             | Fecha del reclamo           |
| horaReclamo            | string       |            |             | Hora de reclamo             |
| montoDescuento         | string       |            |             | Monto de descuento          |
| montoIndeminizacion    | string       |            |             | Monto de indemnización      |
| totalDescuento         | string       |            |             | Total de descuento          |
| macromotivo            | string       |            |             | ID de macromotivo           |
| conformidad            | string       |            |             | ID de conformidad           |
| servicio               | int          |            |             | ID de servicio              |
| tipoServicio           | int          |            | Si          | ID del tipo de servicio     |
| motivo                 | int          |            | Si          | ID del motivo               |
| subMotivo              | string       |            |             | ID del submotivo            |
| codigoClienteBu        | string       |            |             | Código del cliente BU       |
| idConexion             | string       |            |             | ID de la conexión           |
| rutCliente             | string       | NNNNNNNN   | Si          | Rut del cliente             |
| dvCliente              | string       |            | Si          | Dígito verficador del rut del cliente|
| clienteNodo            | string       |            |             | Nodo del cliente            |
| apellidos              | string       |            |             | Apellidos del cliente       |
| calle                  | string       |            |             | Calle del cliente           |
| numeroCalle            | string       |            |             | Número de calle del cliente |
| idComuna               | int          |            |             | ID de la comuna             |
| comuna                 | string       |            |             | Comuna del cliente          |
| region                 | string       |            |             | Región del cliente          |
| idRegion               | int          |            |             | ID de la región del cliente |
| telefono               | string       |            |             | Teléfono del cliente        |
| email                  | string       |            | Si          | Correo electrónico del cliente|
| planPrincipal          | string       |            |             | Plan contratado             |
| esTitular              | string       |            |             | Si el cliente es titular o no|
| celular                | string       |            |             | Celular del cliente         |
| rutRepresentante       | string       | NNNNNNNN   |             | Rut del representante       |
| dvRepresentante        | int          |            |             | Dígito verificador del rut del representante|
| nombreRepresentante    | string       |            |             | Nombre del representante    |
| apellidosRepresentante | string       |            |             | Apellidos del representante |
| telefonoRepresentante  | string       |            |             | Teléfono del representante  |
| celularRepresentante   | string       |            |             | Celular del representante   |
| emailRepresentante     | string       |            |             | Correo electrónico del representante |
| direccionRepresentante | string       |            |             | Dirección del representante |
| numeroCalleRepresentante|string       |            |             | Número de calle del representante|
| comunaRepresentante    | string       |            |             | Comuna del representante    |
| idComunaRepresentante  | string       |            |             | ID de la comuna del representante|
| idRegionRepresentante  | string       |            |             | ID de la región del representante|
| regionRepresentante    | string       |            |             | Región del representante    |
| tipoReclamo            | int          |            |             | ID del tipo de reclamo      |
| tipoSolucion           | int          |            |             | ID del tipo de solución     |
| idAcoge                | int          |            |             | ID Acoge                    |
| clienteUnificado       | string       |            |             | Código de cliente unificado |
| nombreRazon            | string       |            | Si          | Nombre o razón social del cliente|
| celularReclamado       | string       |            |             | Número de celular reclamado |
| direccionCelularReclamado|string      |            |             | Dirección del teléfono reclamado|
| areaTelefonoReclamado  | string       |            |             | Área del teléfono reclamado |
| telefonoReclamado      | string       |            |             | Número de teléfono reclamado|
| direccionTelefonoReclamado| string    |            |             | Dirección del teléfono reclamado|
| tipoNotificacion       | int          |            | Si          | ID del tipo de notificación |
| idTipoTelefono         | string       |            |             | ID del tipo de teléfono     |
| tipoRegistro           | int          |            |             | ID del tipo de registro     |
| totalReclamado         | string       |            |             | Monto total reclamado       |
| horasSinServicio       | string       |            |             | Cantidad de horas sin servicio|
| archivos               | array[object]|            |             | Array con archivos          |
| comentario             | string       |            |             | Comentario                  |
| comentarioReclamo      | string       |            |             | Comentario del reclamo      |
| notificarClienteComentario|boolean    |            |             | Si se notificó al cliente   |
| nombreUsuario          | string       |            |             | Nombre usuario              |
| emailTitular           | string       |            |             | Correo electrónico del titular|
| idUsuarioGateway       | int          |            |             | ID del gateway usuario      |
| ↓ usuario              | array[object]|            |             |                             |
| ⤷ id                   | string       |            |             | ID del usuario              |
| ⤷ nombre               | string       |            |             | Nombre usuario              |
| ⤷ area                 | string       |            |             | Área del usuario            |
| ⤷ estatus              | string       |            |             | Estatus del usuario         |
| ⤷ email                | string       |            |             | Correo electrónico del usuario|
| ↓↓ rolePermiso         | array[object]|            |             |                             |
| ⤷ role                 | string       |            |             | Rol del usuario             |
| ⤷ permiso              | array[string]|            |             | Array con permisos          |
| idSubcategoriaInterna  | string       |            |             | ID de la subcategoría interna|
| ↓ archivoInformeCumplimiento|array[object]|        |             |                             |
| ⤷ nombre               | string       |            |             | Nombre del archivo          |
| ⤷ base64               | string       |            |             | Archivo en base64           |
| ⤷ peso                 | int          |            |             | Peso del archivo            |
| ⤷ tipoArchivo          | string       |            |             | Tipo de archivo             |
| ↓ archivoCartaRespuesta| array[object]|            |             |                             |
| ⤷ nombre               | string       |            |             | Nombre del archivo          |
| ⤷ base64               | string       |            |             | Archivo en base64           |
| ⤷ peso                 | int          |            |             | Peso del archivo            |
| ⤷ tipoArchivo          | string       |            |             | Tipo de archivo             |
| codigoServicioTecnico  | string       |            |             | Código servicio técnico     |
| codigoTraspasoSernac   | string       |            |             | Código traspaso Sernac      |
| sernac                 | array[object]|            |             | Array con los datos de Sernac|
| ↓ meQuieroSalir        | array[object]|            |             |                             |
| ⤷ idSolicitud          | int          |            |             | ID de la solicitud          |
| ⤷ idLlamada            | string       |            |             | ID de la llamada            |
| ⤷ horaLlamada          | int          |            |             | Hora de llamada             |
| ⤷ horaLlamadaCompleta  | string       |            |             | Hora de la llamada completada|

### 1.18.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": 1417,
        "estado": 22,
        "texto": "esta es la explicación por la que el cliente reclama , esto es una prueba",
        "fechaReclamo": "N/A",
        "horaReclamo": "",
        "montoDescuento": null,
        "montoIndeminizacion": null,
        "totalDescuento": null,
        "macromotivo": "",
        "conformidad": "",
        "servicio": 2,
        "tipoServicio": 9,
        "motivo": 1,
        "subMotivo": "",
        "codigoClienteBu": "CC1",
        "idConexion": "11203693",
        "rutCliente": "96722400",
        "dvCliente": 6,
        "clienteNodo": "STJU_01",
        "apellidos": "...",
        "calle": "Región del Biobío Concepción",
        "numeroCalle": "659",
        "idComuna": 8101,
        "comuna": "Concepción",
        "region": "Región del Biobío",
        "idRegion": 8,
        "telefono": "944099680",
        "email": "yarella.fernandez@mundopacifico.cl",
        "planPrincipal": "FIBRA + TVHD + FIJO",
        "esTitular": true,
        "celular": null,
        "rutRepresentante": "96722400",
        "dvRepresentante": 6,
        "nombreRepresentante": "Pacifico Cable Spa",
        "apellidosRepresentante": "no tiene",
        "telefonoRepresentante": "944099680",
        "celularRepresentante": "944099680",
        "emailRepresentante": "yarella.fernandez@mundopacifico.cl",
        "direccionRepresentante": "Esmeralda",
        "numeroCalleRepresentante": "292",
        "comunaRepresentante": "Concepción",
        "idComunaRepresentante": 8101,
        "idRegionRepresentante": 8,
        "regionRepresentante": "Región del Biobío",
        "tipoReclamo": 6,
        "tipoSolucion": 14,
        "idAcoge": 28,
        "clienteUnificado": "234197",
        "nombreRazon": "Pacifico Cable Spa",
        "celularReclamado": "",
        "direccionCelularReclamado": "",
        "areaTelefonoReclamado": "22",
        "telefonoReclamado": "999999999",
        "direccionTelefonoReclamado": "PASAJE HUEQUEN",
        "tipoNotificacion": "",
        "idTipoTelefono": "",
        "tipoRegistro": 102,
        "totalReclamado": null,
        "horasSinServicio": "",
        "archivos": [],
        "comentario": "",
        "comentarioReclamo": "",
        "notificarClienteComentario": false,
        "nombreUsuario": "Oscar Dario Roman Millan",
        "emailTitular": "yarella.fernandez@mundopacifico.cl",
        "idUsuarioGateway": 1610644338903,
        "usuario": {
            "id": 1610644338903,
            "nombre": "Oscar Dario Roman Millan",
            "area": "COMERCIAL",
            "estatus": "activo",
            "email": "oscar.roman@mundopacifico.cl",
            "rolePermiso": [
                {
                    "role": "Administrador-Reclamos",
                    "permiso": [
                        "admin-reclamos"
                    ]
                }
            ]
        },
        "idSubcategoriaInterna": "",
        "archivoInformeCumplimiento": null,
        "archivoCartaRespuesta": {
            "nombre": "PDF de prueba.pdf",
            "base64": "data:application/pdf;base64,JVBERi0xLjcKJcKzx9gNC...",
            "peso": 25045,
            "tipoArchivo": "pdf"
        },
        "codigoServicioTecnico": "",
        "codigoTraspasoSernac": "",
        "sernac": null,
        "meQuieroSalir": {
            "idSolicitud": 1481,
            "idLlamada": "2333-2323",
            "horaLlamada": "08:25:00",
            "horaLlamadaCompleta": ""
        }
    }

### 1.18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.18.2.1.- Respuesta de error

`No se pudo guardar el reclamo`
  
#### 1.18.2.2.- Respuesta de éxito

`Los datos del reclamo con número de folio asociado: <b>20214961</b> fueron actualizados`
`y se ha creado una tarea en BU con identificador asociado: TAR21/2981526`

## 1.19.- Exportar Reclamos
Método que permite generar un reporte de datos de reclamos para exportar a excel.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/informes/reclamo-export`

**Parámetros de entrada:**
| Campo              |  Tipo        | Formato            | Requerido |             Descripción     |
|:------------------:|:------------:|:------------------:|:---------:|----------------------------:|
| folio              | int          |                    |           | Número de folio             |
| codigoCliente      | string       |                    |           | Código de cliente           |
| rutReclamante      | string       |                    |           | Rut del reclamante          |
| nombreReclamante   | string       |                    |           | Nombre del reclamante       |
| conformidad        | string       |                    |           | Conformidad                 |
| fechaRegistroDesde | date         |                    |           | Fecha de registro, desde    |
| fechaRegistroHasta | date         |                    |           | Fecha de registro, hasta    |
| tipoReclamo        | int          |                    |           | ID del tipo de reclamo      |
| estado             | string       |                    |           | ID del estado               |
| macromotivo        | string       |                    |           | ID del macromotivo          |
| idComuna           | int          |                    |           | ID de la comuna             |
| servicio           | string       |                    |           | ID del servicio             |
| tipoServicio       | int          |                    |           | ID del tipo de servicio     |
| tipoRegistro       | int          |                    |           | ID del tipo de registro     |
| NroSolSubtel       | string       |                    |           | Número de solicitud de Subtel|
| NroCasoSernac      | string       |                    |           | Número de caso de Sernac    |
| NroSolMeQuieroSalir| string       |                    |           | Número de 'Me quiero salir' |

**Datos de salida:**
| Campo                           |  Tipo        |                         Descripción              |
|:--------------------------------|:------------:|-------------------------------------------------:| 
| RERE_ID_RECLAMO                 | int          | ID del reclamo                                   | 
| RERE_ID_SUBCATEGORIA_INTERNA    | int          | ID de la subcategoría interna                    | 
| RERE_NOMBRE_USUARIO             | string       | Nombre del usuario                               | 
| RERE_USUARIO_ACTUALIZA          | string       | Nombre del usuario que actualiza                 | 
| RERE_ID_TIPO_TELEFONO           | int          | ID del tipo de teléfono                          | 
| RERE_DIRECCION_CEL_RECLAMADO    | string       | Dirección del celular reclamado                  | 
| RERE_FECHA_CIERRE               | timestamp    | Fecha de cierre                                  | 
| RERE_FECHA_NOTIFICACION         | timestamp    | Fecha de notificación                            | 
| RERE_FOLIO                      | string       | Número de folio                                  | 
| RERE_TEXTO                      | string       | Detalle del reclamo                              | 
| RERE_FECHA_REGISTRO             | timestamp    | Fecha de registro                                | 
| RERE_FECHA_RECLAMO              | timestamp    | Fecha de reclamo                                 | 
| RERE_CALLER_ID                  | int          | ID caller                                        | 
| RERE_ID_TIPO_NOTIFICACION       | int          | ID del tipo de notificación                      | 
| RERE_ID_ESTADO_RECLAMO          | int          | ID del estado del reclamo                        | 
| RERE_ID_SOLICITANTE             | int          | ID del solicitante                               | 
| RERE_ID_TIPO_RECLAMO            | int          | ID del tipo de reclamo                           | 
| RERE_ID_TIPO_SOLUCION           | int          | ID del tipo de solución                          | 
| RERE_ID_TIPO_REGISTRO           | int          | ID del tipo de registro                          | 
| RERE_ID_SERVICIO                | int          | ID del servicio                                  | 
| RERE_ID_TIPO_SERVICIO           | int          | ID del tipo de servicio                          | 
| RERE_ID_MOTIVO                  | int          | ID del motivo                                    | 
| RERE_ID_SUB_MOTIVO              | int          | ID del submotivo                                 | 
| RERE_ID_MACROMOTIVO             | int          | ID del macromotivo                               | 
| RERE_ID_CONFORMIDAD             | int          | ID de la conformidad                             | 
| RERE_HORAS_SIN_SERVICIO         | int          | Cantidad de horas sin servicio                   | 
| RERE_MONTO_TOTAL_RECLAMADO      | int          | Monto total reclamado                            | 
| RERE_CELULAR_RECLAMADO          | int          | Número de celular reclamado                      | 
| RERE_AREA_TELEFONO_RECLAMADO    | int          | Área del teléfono reclamado                      | 
| RERE_TELEFONO_RECLAMADO         | int          | Teléfono reclamado                               | 
| RERE_DIRECCION_TEL_RECLAMADO    | string       | Dirección del teléfono reclamado                 | 
| RERE_TOTAL_DESCUENTO            | int          | Total del descuento                              | 
| RERE_MONTO_INDEMNIZACION        | int          | Monto de indemnización                           | 
| RERE_MONTO_DESCUENTO            | int          | Monto de descuento                               | 
| RERE_ID_RECLAMO_SUBTEL          | int          | ID del reclamo Subtel                            | 
| RERE_ID_RECLAMO_SERNAC          | int          | ID del reclamo Sernac                            | 
| RERE_ID_USUARIO                 | int          | ID del usuario                                   | 
| RERE_ID_USUARIO_ACTUALIZA       | int          | ID del usuario que actualiza                     | 
| RERE_ID_ME_QUIERO_SALIR         | int          | ID me quiero salir                               | 
| tipo_notificacion               | array[object]| Array con tipos de notificación (Sin uso en esta ruta)|
| ↓ estado                        | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del estado                           | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del estado                                    | 
| solicitante                     | array[object]| Array con solicitante (Sin uso en esta ruta)     | 
| tipo_reclamo                    | array[object]| Array con tipos de reclamo (Sin uso en esta ruta)| 
| tipo_solucion                   | array[object]| Array con tipos de solución (Sin uso en esta ruta)|
| ↓ tipo_registro                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de registro                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de registro                          |
| ⤷ RETS_CODIGO                   | int          | Código de tipo de registro                       |
| tipo_telefono                   | array[object]| Array con tipos de teléfono (Sin uso en esta ruta)|
| servicio                        | array[object]| Array con servicio (Sin uso en esta ruta)        | 
| tipo_servicio                   | array[object]| Array con tipos de servicio (Sin uso en esta ruta)|
| motivo                          | array[object]| Array con motivos (Sin uso en esta ruta)         | 
| sub_motivo                      | array[object]| Array con submotivos (Sin uso en esta ruta)      | 
| macromotivo                     | array[object]| Array con macromotivos (Sin uso en esta ruta)    | 
| conformidad                     | array[object]| Array con conformidad (Sin uso en esta ruta)     | 
| archivos                        | array[object]| Array con archivos (Sin uso en esta ruta)        | 
| acoge_reclamos                  | array[object]| Array con reclamos acogidos (Sin uso en esta ruta)|
| sub_categoria_interna           | array[object]| Array con subcategorías internas (Sin uso en esta ruta)|
| subtel                          | array[object]| Array con info de Subtel (Sin uso en esta ruta)  |
| ↓ sernac                        | array[object]|                                                  | 
| ⤷ RRSER_NRO_CASO                | string       | Número de caso                                   |
| ⤷ RRSER_ID_ESTADO               | int          | ID del estado                                    |
| ⤷ RRSER_FECHA_TRASLADO          | date         | Fecha de traslado                                |
| ⤷ RRSER_FECHA_RESP              | date         | Fecha de respuesta                               |
| ⤷ RRSER_FECHA_PLAZO_MAX         | date         | Fecha de plazo máximo                            |
| ⤷ RRSER_COD_OFERTA              | string       | Código de oferta                                 |
| ⤷ RRSER_DESC_PLAN_CONTRATADO    | string       | Descuento plan contratado                        |
| ⤷ RRSER_VALOR_PLAN              | string       | Valor del plan                                   |
| ⤷ RRSER_ID_MACRO                | int          | ID macro                                         |
| ⤷ RRSER_CICLO_FACTURACION       | string       | Ciclo de facturación                             |
| ⤷ RRSER_COMUNA_SUCURSAL         | string       | Comuna de la sucursal                            |
| ⤷ RRSER_FECHA_INSISTENCIA       | string       | Fecha de insistencia                             |
| ⤷ RRSER_ID_RECLAMO_SERNAC       | int          | ID del reclamo Sernac                            |
| ⤷ RRSER_FECHA_RESP_ESCALA       | string       | Fecha de respuesta de escala                     |
| ⤷ RRSER_FECHA_CREACION          | timestamp    | Fecha de creación                                |
| ⤷ RRSER_NOMBRE_USUARIO_FIN_GESTION| string     | Nombre de usuario                                |
| ⤷ RRSER_ID_USUARIO_CREA         | int          | ID del usuario                                   |
| me_quiero_salir                 | array[object]| Array con 'Me quiero salir' (Sin uso en esta ruta)| 
| usuario_crea                    | array[object]| Array con usuario que crea (Sin uso en esta ruta)| 
| usuario_actualiza               | array[object]| Array con usuario que actualiza (Sin uso en esta ruta)| 

### 1.19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "folio": "",
        "codigoCliente": "",
        "rutReclamante": "",
        "nombreReclamante": "",
        "conformidad": "",
        "fechaRegistroDesde": "2021/07/26",
        "fechaRegistroHasta": "2021/08/26",
        "tipoReclamo": "",
        "estado": "",
        "macromotivo": "",
        "idComuna": "",
        "servicio": "",
        "tipoServicio": "",
        "tipoRegistro": 81,
        "NroSolSubtel": "",
        "NroCasoSernac": "",
        "NroSolMeQuieroSalir": ""
	}

### 1.19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.19.2.1.- Respuesta de éxito

    {
        "numeroEmpresa": "504",
        "reclamos": [
            {
                "RERE_ID_RECLAMO": 1747,
                "RERE_ID_SUBCATEGORIA_INTERNA": null,
                "RERE_NOMBRE_USUARIO": null,
                "RERE_USUARIO_ACTUALIZA": "Oscar Dario Roman Millan",
                "RERE_DIRECCION_CEL_RECLAMADO": null,
                "RERE_FECHA_CIERRE": null,
                "RERE_ID_TIPO_TELEFONO": null,
                "RERE_FECHA_NOTIFICACION": null,
                "RERE_FOLIO": "2021955",
                "RERE_TEXTO": "PROBLEMAS DE SEÑAL, LENTITUD O CORTES INJUSTIFICADOS DEL SERVICIO",
                "RERE_FECHA_REGISTRO": "2021-08-25 14:40:42",
                "RERE_FECHA_RECLAMO": "2021-08-25 14:40:42",
                "RERE_CALLER_ID": null,
                "RERE_ID_TIPO_NOTIFICACION": null,
                "RERE_ID_ESTADO_RECLAMO": 22,
                "RERE_ID_SOLICITANTE": null,
                "RERE_ID_TIPO_RECLAMO": null,
                "RERE_ID_TIPO_SOLUCION": null,
                "RERE_ID_TIPO_REGISTRO": 81,
                "RERE_ID_SERVICIO": null,
                "RERE_ID_TIPO_SERVICIO": null,
                "RERE_ID_MOTIVO": null,
                "RERE_ID_SUB_MOTIVO": null,
                "RERE_ID_MACROMOTIVO": null,
                "RERE_ID_CONFORMIDAD": null,
                "RERE_HORAS_SIN_SERVICIO": null,
                "RERE_MONTO_TOTAL_RECLAMADO": 0,
                "RERE_CELULAR_RECLAMADO": null,
                "RERE_AREA_TELEFONO_RECLAMADO": null,
                "RERE_TELEFONO_RECLAMADO": null,
                "RERE_DIRECCION_TEL_RECLAMADO": null,
                "RERE_TOTAL_DESCUENTO": null,
                "RERE_MONTO_INDEMNIZACION": null,
                "RERE_MONTO_DESCUENTO": null,
                "RERE_ID_RECLAMO_SUBTEL": null,
                "RERE_ID_RECLAMO_SERNAC": 3805,
                "RERE_ID_USUARIO": null,
                "RERE_ID_USUARIO_ACTUALIZA": null,
                "RERE_ID_ME_QUIERO_SALIR": null,
                "tipo_notificacion": null,
                "estado": {
                    "RETS_DESCRIPCION": "Revisado",
                    "RETS_ID_SUBTIPO": 22
                },
                "solicitante": null,
                "tipo_reclamo": null,
                "tipo_solucion": null,
                "tipo_registro": {
                    "RETS_DESCRIPCION": "Sernac",
                    "RETS_ID_SUBTIPO": 81,
                    "RETS_CODIGO": "7"
                },
                "servicio": null,
                "tipo_servicio": null,
                "tipo_telefono": null,
                "motivo": null,
                "sub_motivo": null,
                "macromotivo": null,
                "conformidad": null,
                "archivos": [],
                "acoge_reclamo": [],
                "sub_categoria_interna": null,
                "subtel": null,
                "sernac": {
                    "RRSER_NRO_CASO": "R2021W5582129",
                    "RRSER_ID_ESTADO": null,
                    "RRSER_FECHA_TRASLADO": "2021-08-25",
                    "RRSER_FECHA_RESP": null,
                    "RRSER_FECHA_PLAZO_MAX": "2021-09-01",
                    "RRSER_COD_OFERTA": null,
                    "RRSER_DESC_PLAN_CONTRATADO": null,
                    "RRSER_VALOR_PLAN": null,
                    "RRSER_ID_MACRO": null,
                    "RRSER_CICLO_FACTURACION": null,
                    "RRSER_COMUNA_SUCURSAL": "CASA MATRIZ DE : PACIFICO CABLE SPA - MUNDO PACIFICO",
                    "RRSER_FECHA_INSISTENCIA": null,
                    "RRSER_ID_RECLAMO_SERNAC": 3805,
                    "RRSER_FECHA_RESP_ESCALA": null,
                    "RRSER_FECHA_CREACION": "2021-08-25 14:40:42.238074",
                    "RRSER_NOMBRE_USUARIO_FIN_GESTION": null,
                    "RRSER_ID_USUARIO_CREA": 2
                },
                "me_quiero_salir": null,
                "usuario_crea": null,
                "usuario_actualiza": null
            },
            ...
        ]
    }

## 1.20.- Tipos de Teléfonos
Método que retorna lista de tipos de teléfonos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-telefono`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de teléfono                          |
| DESCRIPCION    | string       | Tipo de teléfono                                 |

### 1.20.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.20.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 79,
                    "DESCRIPCION": "Smartphone"
                },
                {
                    "CODIGO": 78,
                    "DESCRIPCION": "Teléfono básico"
                }
            ]
        },
        "codigo": 200
    }


## 1.21.- Datos del Cliente IVR
Método que retorna los datos del cliente IVR.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/consultaClienteIVR`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| RUTCliente   | string       | NNNNNNNNC                      | Si                                         | Rut del cliente             |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| estado             | string       | Estado                                           |
| deudaPendiente     | string       | Deuda pendiente                                  |
| nodos              | string       | Nodo                                             |
| promocionActiva    | string       | Promoción activa                                 |
| tipoPromocion      | string       | Tipo de promoción                                |
| cantidadConexiones | int          | Cantidad de conexiones                           |

### 1.21.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "RUTCliente": "166101069"
	}

### 1.21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.21.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "RUT del cliente no ingresado."
        },
        "codigo": 422
    }
  
#### 1.21.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "estado": "PENDIENTE",
                "deudaPendiente": "CERO",
                "nodos": "MOLI_01,MOLI_01,MOLI_01,MOLI_01,MOLI_01,LEBU_01a,MOLI_01,CONC_47,MOLI_01,CHIL_57,MOLI_02",
                "promocionActiva": "no",
                "tipoPromocion": null,
                "cantidadConexiones": 11
            }
        },
        "codigo": 200
    }


## 1.22.- Lista de Comunas
Método que retorna lista de comunas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/comunas`

**Datos de salida:**
| Campo                |  Tipo        |                         Descripción              |
|:---------------------|:------------:|-------------------------------------------------:| 
| codigo               | int          | Código de la comuna                              |
| descripcion          | string       | Nombre de la comuna                              |
| codRegion            | int          | Código de la región                              |
| periodoInicioVigencia| int          | Inicio de periodo de vigencia                    |
| periodoFinVigencia   | int          | Fin de periodod de vigencia                      |

### 1.22.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.22.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "codigo": 11201,
                    "descripcion": "Aisén",
                    "codRegion": 11,
                    "periodoInicioVigencia": 19000101,
                    "periodoFinVigencia": 29001231
                },
                {
                    "codigo": 5602,
                    "descripcion": "Algarrobo",
                    "codRegion": 5,
                    "periodoInicioVigencia": 19000101,
                    "periodoFinVigencia": 29001231
                },
                ...
                ]
            }
        },
        "codigo": 200
	}

## 1.23.- Lista de Regiones
Método que retorna lista de regiones.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/regiones`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| codigo         | int          | Código de la región                              |
| descripcion    | string       | Nombre de la región                              |

### 1.23.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.23.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "codigo": 1,
                    "descripcion": "Región de Tarapacá"
                },
                {
                    "codigo": 2,
                    "descripcion": "Región de Antofagasta"
                },
                {
                    "codigo": 3,
                    "descripcion": "Región de Atacama"
                },
                ...
                ]
            }
        },
        "codigo": 200
	}

## 1.24.- Ingresar Comentario de Reclamo
Método que permite ingresar comentios de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/ingresar-comentario-reclamo`

**Parámetros de entrada:**
| Campo          |  Tipo        | Formato          | Requerido     |             Descripción     |
|:--------------:|:------------:|:----------------:|:-------------:|----------------------------:|
| idReclamo      | int          |                  | Si            | ID del reclamo              |
| comentario     | string       |                  |               | Comentario del reclamo      |
| nombreUsuario  | string       |                  |               | Nombre usuario              |
| notificaCliente| boolean      |                  |               | Si se le notificó a cliente o no|
| archivos       | array[object]|                  |               | Array con archivos          |
| ↓ usuario      | array[object]|                  |               |                             |
| ⤷ id           | int          |                  |               | ID del usuario              |
| ⤷ nombre       | string       |                  |               | Nombre del usuario          |
| ⤷ area         | string       |                  |               | Área del usuario            |
| ⤷ estatus      | string       |                  |               | Estatus                     |
| ⤷ email        | string       |                  |               | Correo electrónico de usuario|
| ↓↓ rolePermiso | array[object]|                  |               |                             |
| ⤷ role         | string       |                  |               | Rol del usuario             |
| ⤷ permiso      | array[string]|                  |               | Permisos del usuario        |

### 1.24.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": 5703,
        "comentario": "Esto es un mensaje de prueba con notificación al cliente",
        "nombreUsuario": "Oscar Dario Roman Millan",
        "notificaCliente": true,
        "archivos": [],
        "usuario": {
            "id": 1610644338903,
            "nombre": "Oscar Dario Roman Millan",
            "area": "COMERCIAL",
            "estatus": "activo",
            "email": "oscar.roman@mundopacifico.cl",
            "rolePermiso": [
                {
                    "role": "Administrador-Reclamos",
                    "permiso": [
                        "admin-reclamos"
                    ]
                }
            ]
        }
    }

### 1.24.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 1.24.2.1.- Respuesta de error

`Ocurrió un error al registrar el comentario del reclamo`
  
#### 1.24.2.2.- Respuesta de éxito

`El comentario ha sido ingresado con éxito`

## 1.25.- Lista Subcategorías Internas
Método que retorna lista de subcategorías internas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/subcategorias-internas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| idServicio   | int          |                                | Si                                         | ID del servicio             |
| idTipoReclamo| int          |                                | Si                                         | ID del tipo de reclamo      |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID de la subcategoría interna                    |
| DESCRIPCION    | string       | Subcategoría interna                             |

### 1.25.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 2,
        "idTipoReclamo": 6
	}

### 1.25.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 1.25.2.1.- Respuesta de éxito

    [
        {
            "CODIGO": 1,
            "DESCRIPCION": "AMPLIFICADOR WIFI (CONTRATACIÓN)"
        },
        {
            "CODIGO": 2,
            "DESCRIPCION": "CAMBIO DE PLAN"
        },
        {
            "CODIGO": 3,
            "DESCRIPCION": "CAMBIO DE TARIFA"
        },
        ...
    ]



# 2.- Sucursal
## 2.1.- Ingresar Reclamos desde Sucursal
Método que permite el ingreso de reclamos de clientes desde la sucursal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/sucursalVirtual/reclamo-ingresar?Rut={RUT}`

**Parámetros de entrada:**
| Campo                     |  Tipo        | Formato        |     Requerido      |             Descripción     |
|:-------------------------:|:------------:|:--------------:|:------------------:|----------------------------:|
| RUT                       | string       | NNNNNNNN-C     | Si                 | Rut del cliente             |
| clienteUnificado          | string       |                |                    | Código de cliente unificado |
| clienteNodo               | string       |                |                    | Nodo                        |
| codigoClienteBu           | string       |                |                    | Código de cliente BU        |
| idConexion                | string       |                |                    | ID de conexión              |
| nombreRazon               | string       |                |                    | Nombre o razón social       |
| apellidos                 | string       |                |                    | Apellidos del cliente       |
| calle                     | string       |                |                    | Calle del cliente           |
| numeroCalle               | string       |                |                    | Número de calle del cliente |
| email                     | string       |                |                    | Correo electrónico del cliente|
| planPrincipal             | string       |                |                    | Plan principal              |
| fechaReclamo              | string       |                |                    | Fecha de reclamo            |
| texto                     | string       |                |                    | Comentario del reclamo      |
| tipoNotificacion          | int          |                |                    | ID del tipo de notificación |
| servicio                  | int          |                |                    | ID del servicio             |
| tipoServicio              | int          |                |                    | ID del tipo de servicio     |
| motivo                    | int          |                |                    | ID del motivo               |
| subMotivo                 | int          |                |                    | ID del submotivo            |
| idComuna                  | int          |                |                    | ID de la comuna             |
| comuna                    | string       |                |                    | Nombre de comuna            |
| idRegion                  | int          |                |                    | ID de la región             |
| region                    | string       |                |                    | Nombre de la región         |
| telefono                  | string       |                |                    | Número de teléfono del cliente|
| nombreRepresentante       | string       |                |                    | Nombre del representante    |
| apellidosRepresentante    | string       |                |                    | Apellidos del representante |
| telefonoRepresentante     | string       |                |                    | Número de teléfono del representante|
| celularRepresentante      | string       |                |                    | Número de celular del representante|
| emailRepresentante        | string       |                |                    | Correo electrónico del representante|
| direccionRepresentante    | string       |                |                    | Dirección del representante |
| areaTelefonoReclamado     | string       |                |                    | Área del teléfono reclamado |
| telefonoReclamado         | string       |                |                    | Número de teléfono reclamado|
| direccionTelefonoReclamado| string       |                |                    | Dirección del teléfono reclamado|
| celularReclamado          | string       |                |                    | Número de celular reclamado |
| direccionCelularReclamado | string       |                |                    | Dirección del celular reclamado|
| totalReclamado            | string       |                |                    | Monto total reclamado       |
| horasSinServicio          | string       |                |                    | Cantidad de horas sin servicio|
| numeroContingencia        | string       |                |                    | Número de contingencia      |
| tipoTelefono              | string       |                |                    | ID del tipo de teléfono     |
| ↓ archivos                | array[object]|                |                    |                             |
| ⤷ nombre                  | string       |                |                    | Nombre del archivo          |
| ⤷ base64                  | string       |                |                    | Archivo en formato base64   |
| ⤷ peso                    | int          |                |                    | Peso del archivo            |
| ⤷ tipoarchivo             | string       |                |                    | Tipo de archivo             |
| esTitular                 | boolean      |                |                    | Si el cliente es titular o no|
| esCliente                 | boolean      |                |                    | Si es cliente o no          |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "clienteUnificado": "672012",
        "clienteNodo": "PURE_12",
        "codigoClienteBu": "CC671809",
        "idConexion": "67180991002597",
        "nombreRazon": "Yarella Francies",
        "apellidos": "Fernandez Burgos",
        "calle": "NAHUELCO",
        "numeroCalle": "761",
        "email": "oscar.roman@mundopacifico.cl",
        "planPrincipal": "FIBRA + TVHD",
        "fechaReclamo": "2021-09-06",
        "texto": "Esto es un reclamo de prueba, el cliente no tiene servicio hace 3 horas",
        "tipoNotificacion": 3,
        "servicio": 2,
        "tipoServicio": 3,
        "motivo": 1,
        "subMotivo": "",
        "idComuna": 9208,
        "comuna": "Purén",
        "idRegion": 9,
        "region": "Región de La Araucanía",
        "telefono": "963893252",
        "nombreRepresentante": "Yarella Francies",
        "apellidosRepresentante": " Fernandez ",
        "telefonoRepresentante": "963893252",
        "celularRepresentante": "963893252",
        "emailRepresentante": "oscar.roman@mundopacifico.cl",
        "direccionRepresentante": "NAHUELCO",
        "areaTelefonoReclamado": "",
        "telefonoReclamado": "",
        "direccionTelefonoReclamado": "NAHUELCO 761",
        "celularReclamado": "",
        "direccionCelularReclamado": "",
        "totalReclamado": "",
        "horasSinServicio": "",
        "numeroContingencia": "",
        "tipoTelefono": "",
        "archivos": [],
        "esTitular": true,
        "esCliente": true
    }

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.1.2.1.- Respuesta de error

`Ha ocurrido un error, su reclamo no ha podido ser ingresado.`
  
#### 2.1.2.2.- Respuesta de éxito

`Su reclamo ha sido ingresado con número de folio asociado: <b>20214958</b>`

## 2.2.- Tipos de Reclamos
Método que retorna lista de tipos de reclamos - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-reclamo`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de reclamo                       |
| DESCRIPCION    | string       | Tipo de reclamo                                  |

### 2.2.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 2.2.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 6,
                    "DESCRIPCION": "Comercial"
                },
                {
                    "CODIGO": 100,
                    "DESCRIPCION": "Otros"
                },
                {
                    "CODIGO": 76,
                    "DESCRIPCION": "Queja"
                },
                {
                    "CODIGO": 7,
                    "DESCRIPCION": "Técnico"
                }
            ]
        },
        "codigo": 200
    }

## 2.3.- Tipos de Medios de Notificación
Método que retorna lista de tipos de medios de notificación - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-notificacion`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de notificación                  |
| DESCRIPCION    | string       | Tipo de notificación                             |

### 2.3.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 2.3.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 3,
                    "DESCRIPCION": "Correo electrónico"
                },
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Teléfono"
                }
            ]
        },
        "codigo": 200
    }

## 2.4.- Tipos de Servicios Contratados
Método que retorna lista de tipos de servicios contratados por el cliente (Móvil o Fijo) - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNN-C                     |                                            | Rut del cliente             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de servicio                      |
| DESCRIPCION    | string       | Tipo de servicio                                 |

### 2.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "Rut":"96722400-6"
	}

### 2.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.4.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No se encontraron servicios contratados para el cliente, contacte al cliente para obtener mayor información del reclamo"
        },
        "codigo": 204
    }
  
#### 2.4.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 1,
                    "DESCRIPCION": "Servicio móvil"
                },
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Servicio fijo"
                }
            ]
        },
        "codigo": 200
    }

## 2.5.- Lista de Servicios Contratados
Método que retorna lista de servicios contratados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tiposervicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| idServicio   | int          |                                | No                                         | ID del servicio             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del tipo de solución                      |
| DESCRIPCION    | string       | Tipo de solución                                 |

### 2.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}

### 2.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.5.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos para mostrar"
        },
        "codigo": 204
    }
  
#### 2.5.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 2,
                    "DESCRIPCION": "Telefonía móvil"
                }
            ]
        },
        "codigo": 200
    }

## 2.6.- Lista de Motivos de Reclamo
Método que retorna lista de motivos de reclamo - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                 |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------------:|----------------------------:|
| idServicio   | int          |                                | No                            | ID del servicio             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | Código del motivo del reclamo                    |
| DESCRIPCION    | string       | Motivo del reclamo                               |

### 2.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}
### 2.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 2.6.2.1.- Respuesta de éxito

    [
        {
            "CODIGO": 1,
            "DESCRIPCION": "Calidad servicio"
        },
        {
            "CODIGO": 3,
            "DESCRIPCION": "Facturación - cobros"
        },
        {
            "CODIGO": 5,
            "DESCRIPCION": "Servicio técnico"
        },
        {
            "CODIGO": 2,
            "DESCRIPCION": "Ventas - contratos"
        }
    ]

## 2.7.- Lista de Submotivos de Reclamo
Método que retorna lista de submotivos de reclamo - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/submotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato          | Requerido         |             Descripción     |
|:------------:|:------------:|:----------------:|:-----------------:|----------------------------:|
| idMotivo     | int          |                  | Si                | ID del motivo               |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idMotivo": 
	}

### 2.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.7.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos para mostrar"
        },
        "codigo": 204
    }
  
#### 2.7.2.2.- Respuesta de éxito

	{
        ...
	}

## 2.8.- Lista de Reclamos por Cliente
Método que retorna lista con detalle de reclamos realizados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/informes/reclamo-cliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato             | Requerido     |             Descripción     |
|:------------:|:------------:|:-------------------:|:-------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC           | Si            | Rut de cliente              |
| page         | int          |                     |               | Número de página            |
| per_page     | int          |                     |               | Cantidad de resultados por página|

**Datos de salida:**
| Campo                       |  Tipo        |                         Descripción              |
|:----------------------------|:------------:|-------------------------------------------------:| 
| RERE_ID_RECLAMO             | int          | ID del reclamo                                   | 
| RERE_FECHA_CIERRE           | date         | Fecha de cierre                                  |
| RERE_FOLIO                  | string       | Número de folio                                  | 
| RERE_TEXTO                  | string       | Detalle del reclamo                              | 
| RERE_FECHA_RECLAMO          | timestamp    | Fecha de reclamo                                 | 
| RERE_ID_ESTADO_RECLAMO      | int          | ID del estado del reclamo                        | 
| RERE_ID_SOLICITANTE         | int          | ID del solicitante                               | 
| RERE_ID_TIPO_RECLAMO        | int          | ID del tipo de reclamo                           |
| RERE_ID_SERVICIO            | int          | ID del servicio                                  | 
| RERE_ID_TIPO_SERVICIO       | int          | ID del tipo de servicio                          | 
| RERE_DIRECCION_TEL_RECLAMADO| string       | Dirección del teléfono reclamado                 |
| RERE_DIRECCION_CEL_RECLAMADO| string       | Dirección del celular reclamado                  |
| tipo_notificacion           | array[object]| Array con el tipo de notificación (Sin uso en esta ruta)|
| ↓ estado                    | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION          | string       | Descripción del estado                           | 
| ⤷ RETS_ID_SUBTIPO           | int          | ID del estado                                    |  
| ↓ tipo_reclamo              | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION          | string       | Descripción del tipo de reclamo                  | 
| ⤷ RETS_ID_SUBTIPO           | int          | ID del tipo de reclamo                           | 
| solicitante                 | array[object]| Array con el solicitante (Sin uso en esta ruta)  |
| ↓ servicio                  | array[object]|                                                  | 
| ⤷ RESE_DESCRIPCION          | string       | Descripción del servicio                         | 
| ⤷ RESE_ID_SERVICIO          | int          | ID del servicio                                  |
| ↓ tipo_servicio             | array[object]|                                                  | 
| ⤷ RETE_DESCRIPCION          | string       | Descripción del tipo de servicio                 | 
| ⤷ RETE_ID_TIPO_SERVICIO     | int          | ID del tipo de servicio                          |
| ↓ respuesta_al_cliente      | array[object]|                                                  |
| ⤷ REC_ID_COMENTARIO         | int          | ID del comentario                                |
| ⤷ REC_ID_RECLAMO            | int          | ID del reclamo                                   |
| ⤷ REC_DESC                  | string       | Descripción                                      |
| ⤷ REC_DESC_USUARIO          | string       | Nombre usuario                                   |
| ⤷ REC_FECHA_REGISTRO        | timestamp    | Fecha de registro                                |
| ⤷ REC_ACTUALIZADO           | timestamp    | Fecha de actualización                           |
| ⤷ REC_VIGENTE               | boolean      | Si está vigente o no                             |
| ⤷ REC_NOTIFICA_CLIENTE      | boolean      | Si se le notificó a cliente o no                 |
| ↓↓ archivos                 | array[object]|                                                  |
| ⤷ REARC_ID_ARCHIVO          | int          | ID del archivo                                   |
| ⤷ REARC_ID_COMENTARIO       | int          | ID del comentario                                |
| ⤷ REARC_NOMBRE              | string       | Nombre del archivo                               |
| ⤷ REARC_TAMANO              | int          | Tamaño del archivo                               |
| ⤷ REARC_RUTA                | string       | Ruta del archivo                                 |
| ⤷ REARC_ID_EXTENSION        | int          | ID de la extensión                               |
| ⤷ REARC_NOMBRE_REF          | string       | Nombre de referencia del archivo                 |
| ⤷ REARC_VIGENTE             | boolean      | Si está vigente o no                             |
| ⤷ REARC_ID_USUARIO_CREA     | int          | ID del usuario que crea                          |
| ⤷ REARC_MIME_TYPE           | string       | Mime tipo                                        |

### 2.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "Rut": "183483811",
        "page": 0,
        "per_page": 5
	}

### 2.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.8.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "El rut  es inválido o no tiene formato correcto. El formato es NNNNNNNNC"
        },
        "codigo": 422
    }
  
#### 2.8.2.2.- Respuesta de éxito

    {
        "current_page": 1,
        "data": [
            {
                "RERE_ID_RECLAMO": 1237,
                "RERE_FECHA_CIERRE": null,
                "RERE_FOLIO": "2021481",
                "RERE_TEXTO": "No funciona mi servicio de telefonía móvil desde el día de ayer",
                "RERE_FECHA_RECLAMO": "2021-06-23 16:31:57",
                "RERE_ID_ESTADO_RECLAMO": 22,
                "RERE_ID_SOLICITANTE": 710,
                "RERE_ID_TIPO_RECLAMO": 6,
                "RERE_ID_SERVICIO": 1,
                "RERE_ID_TIPO_SERVICIO": 2,
                "RERE_DIRECCION_TEL_RECLAMADO": null,
                "RERE_DIRECCION_CEL_RECLAMADO": "ANIBAL PINTO 1874",
                "tipo_notificacion": null,
                "estado": {
                    "RETS_DESCRIPCION": "Revisado",
                    "RETS_ID_SUBTIPO": 22
                },
                "tipo_reclamo": {
                    "RETS_DESCRIPCION": "Comercial",
                    "RETS_ID_SUBTIPO": 6
                },
                "solicitante": null,
                "servicio": {
                    "RESE_DESCRIPCION": "Servicio móvil",
                    "RESE_ID_SERVICIO": 1
                },
                "tipo_servicio": {
                    "RETE_DESCRIPCION": "Telefonía móvil",
                    "RETE_ID_TIPO_SERVICIO": 2
                },
                "respuesta_al_cliente": {
                    "REC_ID_COMENTARIO": 117,
                    "REC_ID_RECLAMO": 1237,
                    "REC_DESC": "Esto es un mensaje de prueba de confirmación al cliente con archivo adjunto",
                    "REC_DESC_USUARIO": "Oscar Dario Roman Millan",
                    "REC_FECHA_REGISTRO": "2021-08-06 11:14:00",
                    "REC_ACTUALIZADO": "2021-08-06 11:14:00",
                    "REC_VIGENTE": true,
                    "REC_NOTIFICA_CLIENTE": true,
                    "archivos": [
                        {
                            "REARC_ID_ARCHIVO": 23,
                            "REARC_ID_COMENTARIO": 117,
                            "REARC_NOMBRE": "610d51c61a846.png",
                            "REARC_TAMANO": 14307,
                            "REARC_RUTA": "https://www.tumundo.cl/reclamos-archivos?extencion=png&mime=&nombreArchivo=/storage/archivos/610d51c61a846.png&user=1&signature=fa506b283f9f4c017180d7f52c6ce74ad0aead76b920c077d0916bf420aeeb20",
                            "REARC_ID_EXTENSION": 69,
                            "REARC_NOMBRE_REF": "email_footer_1_mobile.png",
                            "REARC_VIGENTE": true,
                            "REARC_ID_USUARIO_CREA": null,
                            "REARC_MIME_TYPE": null
                        }
                    ]
                }
            },
            ...
            ],
        "first_page_url": "...URL/informes/reclamo-cliente?Rut=183483811&per_page=5&page=1",
        "from": 1,
        "last_page": 13,
        "last_page_url": "...URL/informes/reclamo-cliente?Rut=183483811&per_page=5&page=13",
        "next_page_url": "...URL/informes/reclamo-cliente?Rut=183483811&per_page=5&page=2",
        "path": "...URL/informes/reclamo-cliente",
        "per_page": "5",
        "prev_page_url": null,
        "to": 5,
        "total": 65
    }

## 2.9.- Tipos de Teléfono
Método que retorna lista de tipos de teléfono - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-telefono`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de teléfono                          |
| DESCRIPCION    | string       | Tipo de teléfono                                 |

### 2.9.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje
  
#### 2.9.1.1.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": [
                {
                    "CODIGO": 79,
                    "DESCRIPCION": "Smartphone"
                },
                {
                    "CODIGO": 78,
                    "DESCRIPCION": "Teléfono básico"
                }
            ]
        },
        "codigo": 200
    }



## 2.10.- Servicios Contratados por Cliente
Método que retorna los servicios contratados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/datos-cliente-tipo-servicio`

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.10.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 2.10.1.1.- Respuesta de error

`No se encontraron servicios asociados`
  
#### 2.10.1.2.- Respuesta de éxito

	{
        ...
	}


# 3.- IVR
## 3.1.- Informe Reclamos
Método que retorna informe de datos de reclamos IVR por cliente para Mundo social.

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/MundoSocial/informe-reclamos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato          |     Requerido     |             Descripción     |
|:------------:|:------------:|:----------------:|:-----------------:|----------------------------:|
| rutCliente   | string       | NNNNNNNNC        | Si                | Rut del cliente             |

**Datos de salida:**
| Campo                           |  Tipo        |                         Descripción              |
|:--------------------------------|:------------:|-------------------------------------------------:| 
| RERE_ID_RECLAMO                 | int          | ID del reclamo                                   | 
| RERE_DIRECCION_CEL_RECLAMADO    | string       | Dirección del celular reclamado                  | 
| RERE_FECHA_CIERRE               | timestamp    | Fecha de cierre                                  | 
| RERE_ID_TIPO_TELEFONO           | int          | ID del tipo de teléfono                          |
| RERE_FECHA_NOTIFICACION         | timestamp    | Fecha de notificación                            |  
| RERE_FOLIO                      | string       | Número de folio                                  | 
| RERE_TEXTO                      | string       | Detalle del reclamo                              | 
| RERE_FECHA_REGISTRO             | timestamp    | Fecha de registro                                | 
| RERE_FECHA_RECLAMO              | timestamp    | Fecha de reclamo                                 | 
| RERE_CALLER_ID                  | int          | ID caller                                        | 
| RERE_ID_TIPO_NOTIFICACION       | int          | ID del tipo de notificación                      | 
| RERE_ID_ESTADO_RECLAMO          | int          | ID del estado del reclamo                        | 
| RERE_ID_SOLICITANTE             | int          | ID del solicitante                               | 
| RERE_ID_TIPO_RECLAMO            | int          | ID del tipo de reclamo                           | 
| RERE_ID_TIPO_SOLUCION           | int          | ID del tipo de solución                          | 
| RERE_ID_TIPO_REGISTRO           | int          | ID del tipo de registro                          | 
| RERE_ID_SERVICIO                | int          | ID del servicio                                  | 
| RERE_ID_TIPO_SERVICIO           | int          | ID del tipo de servicio                          | 
| RERE_ID_MOTIVO                  | int          | ID del motivo                                    | 
| RERE_ID_SUB_MOTIVO              | int          | ID del submotivo                                 | 
| RERE_ID_MACROMOTIVO             | int          | ID del macromotivo                               | 
| RERE_ID_CONFORMIDAD             | int          | ID de la conformidad                             | 
| RERE_HORAS_SIN_SERVICIO         | int          | Cantidad de horas sin servicio                   | 
| RERE_MONTO_TOTAL_RECLAMADO      | int          | Monto total reclamado                            | 
| RERE_CELULAR_RECLAMADO          | int          | Número de celular reclamado                      | 
| RERE_AREA_TELEFONO_RECLAMADO    | int          | Área del teléfono reclamado                      | 
| RERE_TELEFONO_RECLAMADO         | int          | Teléfono reclamado                               | 
| RERE_DIRECCION_TEL_RECLAMADO    | string       | Dirección del teléfono reclamado                 | 
| RERE_TOTAL_DESCUENTO            | int          | Total del descuento                              | 
| RERE_MONTO_INDEMNIZACION        | int          | Monto de indemnización                           | 
| RERE_MONTO_DESCUENTO            | int          | Monto de descuento                               |
| ↓ tipo_notificacion             | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción de la notificación                   | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de notificación                      | 
| ↓ estado                        | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del estado                           | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del estado                                    |
| ↓ solicitante                   | array[object]|                                                  | 
| ⤷ RESO_RUT                      | int          | Rut del solicitante                              | 
| ⤷ RESO_RUT_DV                   | string       | Dígito verficador del rut del solicitante        | 
| ⤷ RESO_NOMBRE_RAZON             | string       | Nombre o razón social del solicitante            | 
| ⤷ RESO_APELLIDOS                | string       | Apellidos del solicitante                        |
| ⤷ RESO_CODIGO_CLIENTE_BU        | string       | Código de cliente BU                             | 
| ⤷ RESO_ID_SOLICITANTE           | int          | ID del solicitante                               | 
| ⤷ RESO_COMUNA                   | string       | Nombre de comuna                                 | 
| ⤷ RESO_ID_COMUNA                | int          | ID de la comuna                                  | 
| ⤷ RESO_REGION                   | string       | Nombre de la región                              |  
| ⤷ RESO_PLAN_PRINCIPAL           | string       | Plan contratado                                  |
| ⤷ RESO_NODO                     | string       | Nodo                                             | 
| ⤷ RESO_RUT_REPRESENTANTE        | int          | Rut del representante                            | 
| ⤷ RESO_RUT_DV_REPRESENTANTE     | string       | Dígito verficador del rut del representante      | 
| ⤷ RESO_NOMBRE_REPRESENTANTE     | string       | Nombre del representante                         | 
| ⤷ RESO_APELLIDOS_REPRESENTANTE  | string       | Apellidos del representante                      | 
| ⤷ RESO_TELEFONO_REPRESENTANTE   | int          | Teléfono del representante                       |
| ⤷ RESO_EMAIL_REPRESENTANTE      | string       | Correo electrónico del representante             | 
| ⤷ RESO_COMUNA_REPRESENTANTE     | string       | Nombre de la comuna del representante            | 
| ⤷ RESO_ID_COMUNA_REPRESENTANTE  | int          | ID de la comuna del representante                | 
| ⤷ RESO_DIRECCION_REPRESENTANTE  | string       | Dirección del representante                      | 
| ⤷ RESO_ID_REGION_REPRESENTANTE  | int          | ID de la región del representante                | 
| ⤷ RESO_REGION_REPRESENTANTE     | string       | Región del representante                         | 
| ⤷ RESO_CALLE                    | string       | Calle del solicitante                            | 
| ⤷ RESO_CLIENTE_UNIFICADO        | int          | Código del cliente unificado                     |  
| ↓ tipo_reclamo                  | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de reclamo                  | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de reclamo                           | 
| ↓ tipo_solucion                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de solución                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de solución                          |
| ↓ tipo_registro                 | array[object]|                                                  | 
| ⤷ RETS_DESCRIPCION              | string       | Descripción del tipo de registro                 | 
| ⤷ RETS_ID_SUBTIPO               | int          | ID del tipo de registro                          |
| servicio                        | array[object]| Array con el servicio (Sin uso en esta ruta)     |
| tipo_servicio                   | array[object]| Array con el tipo de servicio (Sin uso en esta ruta)|
| motivo                          | array[object]| Array con el motivo (Sin uso en esta ruta)       |
| sub_motivo                      | array[object]| Array con el submotivo (Sin uso en esta ruta)    |
| macromotivo                     | array[object]| Array con el macromotivo (Sin uso en esta ruta)  |
| conformidad                     | array[object]| Array con la conformidad (Sin uso en esta ruta)  |
| ↓ archivos                      | array[object]|                                                  |
| ⤷ REAR_ID_ARCHIVO               | int          | ID del archivo                                   |
| ⤷ REAR_ID_RECLAMO               | int          | ID del reclamo                                   |
| ⤷ REAR_NOMBRE                   | string       | Nombre del archivo                               |
| ⤷ REAR_RUTA                     | string       | Ruta del archivo                                 |
| ⤷ REAR_ID_EXTENSION             | int          | Extensión del archivo                            |
| ⤷ usuario                       | int          | Usuario                                          |
| acoge_reclamo                   | array[object]| Array con los archivos (Sin uso en esta ruta)    |

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rutCliente": "183483811"
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.1.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Ha ocurrido un error y no se pudo obtener la información del reclamo solicitado."
        },
        "codigo": 422
    }
    
#### 3.1.2.2.- Respuesta de éxito

    [
        {
            "RERE_ID_RECLAMO": 1270,
            "RERE_DIRECCION_CEL_RECLAMADO": null,
            "RERE_FECHA_CIERRE": null,
            "RERE_ID_TIPO_TELEFONO": null,
            "RERE_FECHA_NOTIFICACION": "2021-07-19 17:13:59",
            "RERE_FOLIO": "2021514",
            "RERE_TEXTO": "Esta la descripcion del reclamo de prueba",
            "RERE_FECHA_REGISTRO": "2021-07-02 00:00:00",
            "RERE_FECHA_RECLAMO": "2021-07-02 00:00:00",
            "RERE_CALLER_ID": null,
            "RERE_ID_TIPO_NOTIFICACION": 3,
            "RERE_ID_ESTADO_RECLAMO": 22,
            "RERE_ID_SOLICITANTE": 747,
            "RERE_ID_TIPO_RECLAMO": 99,
            "RERE_ID_TIPO_SOLUCION": 14,
            "RERE_ID_TIPO_REGISTRO": 80,
            "RERE_ID_SERVICIO": null,
            "RERE_ID_TIPO_SERVICIO": null,
            "RERE_ID_MOTIVO": null,
            "RERE_ID_SUB_MOTIVO": null,
            "RERE_ID_MACROMOTIVO": null,
            "RERE_ID_CONFORMIDAD": null,
            "RERE_HORAS_SIN_SERVICIO": null,
            "RERE_MONTO_TOTAL_RECLAMADO": 10000,
            "RERE_CELULAR_RECLAMADO": 0,
            "RERE_AREA_TELEFONO_RECLAMADO": 0,
            "RERE_TELEFONO_RECLAMADO": 0,
            "RERE_DIRECCION_TEL_RECLAMADO": null,
            "RERE_TOTAL_DESCUENTO": null,
            "RERE_MONTO_INDEMNIZACION": null,
            "RERE_MONTO_DESCUENTO": null,
            "tipo_notificacion": {
                "RETS_DESCRIPCION": "Correo electrónico",
                "RETS_ID_SUBTIPO": 3
            },
            "estado": {
                "RETS_DESCRIPCION": "Revisado",
                "RETS_ID_SUBTIPO": 22
            },
            "solicitante": {
                "RESO_RUT": 18348381,
                "RESO_RUT_DV": "1",
                "RESO_NOMBRE_RAZON": "Patrick Alexander",
                "RESO_APELLIDOS": " Veloso ",
                "RESO_CODIGO_CLIENTE_BU": "CC499159",
                "RESO_ID_SOLICITANTE": 747,
                "RESO_COMUNA": "Concepción",
                "RESO_ID_COMUNA": 8101,
                "RESO_REGION": "Región del Biobío",
                "RESO_PLAN_PRINCIPAL": "FIBRA + TVHD + FIJO",
                "RESO_NODO": "CONC_09",
                "RESO_RUT_REPRESENTANTE": 18348381,
                "RESO_RUT_DV_REPRESENTANTE": "1",
                "RESO_NOMBRE_REPRESENTANTE": "Patrick Alexander",
                "RESO_APELLIDOS_REPRESENTANTE": " Veloso ",
                "RESO_TELEFONO_REPRESENTANTE": 123456556,
                "RESO_EMAIL_REPRESENTANTE": "oscar.roman@mundopacifico.cl",
                "RESO_COMUNA_REPRESENTANTE": "Concepción",
                "RESO_ID_COMUNA_REPRESENTANTE": 8101,
                "RESO_DIRECCION_REPRESENTANTE": "Anibal Pinto",
                "RESO_ID_REGION_REPRESENTANTE": 8,
                "RESO_REGION_REPRESENTANTE": "Región del Biobío",
                "RESO_CALLE": "Anibal Pinto",
                "RESO_CLIENTE_UNIFICADO": 499088
            },
            "tipo_reclamo": {
                "RETS_DESCRIPCION": "Subtel",
                "RETS_ID_SUBTIPO": 99
            },
            "tipo_solucion": {
                "RETS_DESCRIPCION": "Pendiente de solución",
                "RETS_ID_SUBTIPO": 14
            },
            "tipo_registro": {
                "RETS_DESCRIPCION": "Oficio Subtel",
                "RETS_ID_SUBTIPO": 80
            },
            "servicio": null,
            "tipo_servicio": null,
            "motivo": null,
            "sub_motivo": null,
            "macromotivo": null,
            "conformidad": null,
            "archivos": [
                {
                    "REAR_ID_ARCHIVO": 219,
                    "REAR_ID_RECLAMO": 1270,
                    "REAR_NOMBRE": "60f5eb1a79a9b.png",
                    "REAR_RUTA": "/storage/archivos/2021514/Subtel/DocumentosCobro/60f5eb1a79a9b.png",
                    "REAR_ID_EXTENSION": 69,
                    "usuario": null
                }
            ],
            "acoge_reclamo": []
        },
        ...
	}



## 3.2.- Grabar Registro
Método que permite grabar el reclamo IVR en la tabla principal de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/grabarregistro`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo    | string       |                  | Si                  | ID del reclamo              |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| folioReclamo   | string       | Número de folio del reclamo                      |

### 3.2.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617"
    }

### 3.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.2.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.2.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "folioReclamo": "20214961"
        },
        "codigo": 200
    }

## 3.3.- Ingresar
Método que permite ingresar temporalmente el reclamo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/ingresar`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| clienteUnificado| string       |                  |                     | Cliente unificado           |
| codigoClienteBu | string       |                  |                     | Código de cliente BU        |
| idConexion      | string       |                  |                     | ID de la conexión           |
| rutCliente      | string       |                  | Si                  | Rut del cliente             |
| nombreRazon     | string       |                  | Si                  | Nombre o razón social del cliente|
| apellidos       | string       |                  |                     | Apellidos del cliente       |
| calle           | string       |                  | Si                  | Calle de la dirección del cliente |
| numeroCalle     | string       |                  | Si                  | Número de la dirección del cliente|
| callerId        | string       |                  |                     | ID Caller                   |
| email           | string       |                  |                     | Correo electrónico del cliente|
| planPrincipal   | string       |                  |                     | Plan principal              |
| nodo            | string       |                  | Si                  | Código del nodo             |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idReclamo      | int          | ID del reclamo                                   |

### 3.3.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "clienteUnificado":"7688",
        "codigoClienteBu":"CC4785",
        "idConexion":"435830180563893",
        "rutCliente":"166101069",
        "nombreRazon":"cynthia",
        "apellidos":"aguilera",
        "calle":"carreton",
        "numeroCalle":"1541",
        "callerId":"2985444",
        "email":"cynthia.munoz@mundopacifico.cl",
        "planPrincipal":"plan",
        "nodo":"NODO_ARA01"
    }

### 3.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.3.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "No se pueden procesar los campos",
            "detalleRespuesta": [
                "El NOMBRE_CAMPO es obligatorio"
            ]
        },
        "code": 422
    }
  
#### 3.3.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 5776
        },
        "codigo": 200
    }



## 3.4.- Actualizar Contingencia
Método que permite actualizar contingencia del cliente en la tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-contingencia`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| horasSinServicio| string       |                  |                     | Cantidad de horas sin servicio|
| nroContingencia | string       |                  |                     | Número de contingencia      |
| nroStp          | string       |                  |                     | Número de stp               |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.4.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "horasSinServicio":"1",
        "nroContingencia":"1784",
        "nroStp":""
    }

### 3.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.4.2.1.- Respuesta de error

	{
...
	} 
  
#### 3.4.2.2.- Respuesta de éxito

	{
...
	}


## 3.5.- Actualizar Teléfono de Cliente
Método que permite actualizar el teléfono del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-fono`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| fonoReclamante  | string       |                  |                     | Teléfono a actualizar       |

### 3.5.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "fonoReclamante":"123456789"
    }

### 3.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.5.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.5.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }




## 3.6.- Actualizar Motivo de Reclamo
Método que permite actualizar el motivo del reclamo del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-motivo`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| idMotivo        | string       |                  | Si                  | ID del motivo nuevo         |

### 3.6.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "idMotivo":"2"
    }

### 3.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.6.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.7.- Actualizar Rut de Cliente
Método que permite actualizar el rut del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-rut`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| rutReclamante   | string       |                  | Si                  | Rut nuevo                   |

### 3.7.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "rutReclamante":"111111111"
    }

### 3.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.7.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "El rut 1 es invalido o no tiene formato correcto. El formato es NNNNNNNNC"
        },
        "codigo": 422
    }

#### 3.7.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }


## 3.8.- Actualizar Servicio del Cliente
Método que permite actualizar el servicio del cliente solicitante en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-servicio`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| idServicio      | string       |                  | Si                  | ID del servicio a actualizar|

### 3.8.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "idServicio":"1"
    }

### 3.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.8.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.8.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.9.- Actualizar Submotivo de Reclamo
Método que permite actualizar el submotivo de reclamo IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-submotivo`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| idSubMotivo     | string       |                  | Si                  | ID del submotivo a actualizar|

### 3.9.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "idSubMotivo":"9"
    }

### 3.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.9.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.9.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }


## 3.10.- Actualizar Medio de Notificación
Método que permite actualizar el medio de notificación del cliente en table temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tipo-notificacion`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| tipoNotificacion| string       |                  | Si                  | ID del tipo de notificación a actualizar|

### 3.10.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "tipoNotificacion":"2"
    }

### 3.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.10.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.10.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.11.- Actualizar Tipo de Teléfono Reclamado
Método que permite actualizar el tipo de teléfono reclamado - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tipo-telefono`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| tipoTelefono    | string       |                  | Si                  | ID del tipo de teléfono a actualizar|

### 3.11.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": "617",
        "tipoTelefono": "78"
    }

### 3.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.11.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.11.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.12.- Actualizar Tipo de Servicio
Método que permite actualizar el tipo de servicio en tabla temporal - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tiposervicio`

**Parámetros de entrada:**
| Campo           |  Tipo        | Formato          |     Requerido       |             Descripción     |
|:---------------:|:------------:|:----------------:|:-------------------:|----------------------------:|
| idReclamo       | string       |                  | Si                  | ID del reclamo              |
| idTipoServicio  | string       |                  | Si                  | ID del tipo de servicio a actualizar|

### 3.12.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo":"617",
        "idTipoServicio":"1"
    }

### 3.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.12.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.12.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.13.- Actualizar Número Móvil Reclamado
Método que permite actualizar el número móvil reclamado - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-celular-reclamado`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| idReclamo        | int          |                                | Si                          | ID del reclamo              |
| celularReclamado | int          |                                | Si                          | Número de celular reclamado |
| rutCliente       | string       | NNNNNNNNC                      | Si                          | Rut del cliente             |

### 3.13.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": 449,
        "celularReclamado": 931886427,
        "rutCliente": "183483811"
    }

### 3.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.13.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 204
    }
  
#### 3.13.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 449
        },
        "codigo": 200
    }

## 3.14.- Actualizar Cliente Reclamante
Método que permite actualizar en tabla temporal si el cliente es reclamante o no - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-cliente-es-reclamante`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| idReclamo        | int          |                                | Si                          | ID del reclamo              |
| esTitular        | boolean      |                                | Si                          | Si el cliente es titular o no|

### 3.14.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": "617",
        "esTitular": true
    }

### 3.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.14.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 422
    }
  
#### 3.14.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 617
        },
        "codigo": 200
    }

## 3.15.- Actualizar Teléfono Reclamado
Método que permite actualizar el teléfono reclamado en tabla temporal del IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-telefono-reclamado`

**Parámetros de entrada:**
| Campo            |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| idReclamo        | int          |                                | Si                          | ID del reclamo              |
| telefonoReclamado| int          |                                | Si                          | Teléfono reclamado a actualizar|
| rutCliente       | string       | NNNNNNNNC                      | Si                          | Rut del cliente             |

### 3.15.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "idReclamo": 449,
        "telefonoReclamado": 2885792,
        "rutCliente": "967224006"
    }

### 3.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripción del mensaje

#### 3.15.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error"
        },
        "codigo": 204
    }
  
#### 3.15.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "idReclamo": 449
        },
        "codigo": 200
    }



