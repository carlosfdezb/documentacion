| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para TITULO

<!-- Índice -->
- [Documentación Api´s para TITULO](#documentación-apis-para-TITULO)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- MODULO](#1--MODULO)
    - [1.1.- RUTA 1 MODULO](#11--RUTA-1-MODULO)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.3- Respuesta de éxito](#1123--respuesta-de-éxito)


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