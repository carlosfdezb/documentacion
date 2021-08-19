| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Medios de Pago

<!-- Índice -->
- [Documentación Api´s para Medios de Pago](#documentación-apis-para-medios-de-pago)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Empresas](#1--empresas)
    - [1.1.- Existe Cliente](#11--existe-cliente)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Obtener Deuda](#12--obtener-deuda)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [2.- Pago](#2--pago)
    - [2.1.- Consolida Deuda](#21--consolida-deuda)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Procesar Pago](#22--procesar-pago)
        - [2.2.1.- Ejemplo de llamada](#221--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#222--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#2221--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#2222--respuesta-de-éxito)
  - [3.- Rendiciones](#3--rendiciones)
    - [3.1.- Rendiciones](#31--rendiciones)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
    - [3.2.- Rendiciones Filtro](#32--rendiciones-filtro)
        - [3.2.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
        - [3.2.2.- Respuesta de Salida](#322--respuesta-de-salida)
            - [3.2.2.1- Respuesta de error](#3221--respuesta-de-error)
            - [3.2.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
    - [3.3.- Rendiciones Filtro Exportar](#33--rendiciones-filtro-exportar)
        - [3.3.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
        - [3.3.2.- Respuesta de Salida](#332--respuesta-de-salida)
            - [3.3.2.1- Respuesta de error](#3321--respuesta-de-error)
            - [3.3.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
    - [3.4.- Rendiciones Resumen Filtro](#34--rendiciones-resumen-filtro)
        - [3.4.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
        - [3.4.2.- Respuesta de Salida](#342--respuesta-de-salida)
            - [3.4.2.1- Respuesta de error](#3421--respuesta-de-error)
            - [3.4.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
  - [4.- Medios de Pago](#4--medios-de-pago)
    - [4.1.- Canales de Pago](#41--canales-de-pago)
        - [4.1.1.- Ejemplo de llamada](#411--ejemplo-de-llamada)
        - [4.1.2.- Respuesta de Salida](#412--respuesta-de-salida)
            - [4.1.2.1- Respuesta de error](#4121--respuesta-de-error)
            - [4.1.2.2- Respuesta de éxito](#4122--respuesta-de-éxito)
    - [4.2.- Clientes Suscritos](#42--clientes-suscritos)
        - [4.2.1.- Ejemplo de llamada](#421--ejemplo-de-llamada)
        - [4.2.2.- Respuesta de Salida](#422--respuesta-de-salida)
            - [4.2.2.1- Respuesta de error](#4221--respuesta-de-error)
            - [4.2.2.2- Respuesta de éxito](#4222--respuesta-de-éxito)
    - [4.3.- Eliminar Registro](#43--eliminar-registro)
        - [4.3.1.- Ejemplo de llamada](#431--ejemplo-de-llamada)
        - [4.3.2.- Respuesta de Salida](#432--respuesta-de-salida)
            - [4.3.2.1- Respuesta de error](#4321--respuesta-de-error)
            - [4.3.2.2- Respuesta de éxito](#4322--respuesta-de-éxito)
    - [4.4.- Exportar Factura](#44--exportar-factura)
        - [4.4.1.- Ejemplo de llamada](#441--ejemplo-de-llamada)
        - [4.4.2.- Respuesta de Salida](#442--respuesta-de-salida)
            - [4.4.2.1- Respuesta de error](#4421--respuesta-de-error)
            - [4.4.2.2- Respuesta de éxito](#4422--respuesta-de-éxito)
    - [4.5.- Pago Factura](#45--pago-factura)
        - [4.5.1.- Ejemplo de llamada](#451--ejemplo-de-llamada)
        - [4.5.2.- Respuesta de Salida](#452--respuesta-de-salida)
            - [4.5.2.1- Respuesta de error](#4521--respuesta-de-error)
            - [4.5.2.2- Respuesta de éxito](#4522--respuesta-de-éxito)
    - [4.6.- Empresa Factura](#46--empresa-factura)
        - [4.6.1.- Ejemplo de llamada](#461--ejemplo-de-llamada)
        - [4.6.2.- Respuesta de Salida](#462--respuesta-de-salida)
            - [4.6.2.1- Respuesta de error](#4621--respuesta-de-error)
            - [4.6.2.2- Respuesta de éxito](#4622--respuesta-de-éxito)
    - [4.7.- Filtros Factura](#47--filtros-factura)
        - [4.7.1.- Ejemplo de llamada](#471--ejemplo-de-llamada)
        - [4.7.2.- Respuesta de Salida](#472--respuesta-de-salida)
            - [4.7.2.1- Respuesta de error](#4721--respuesta-de-error)
            - [4.7.2.2- Respuesta de éxito](#4722--respuesta-de-éxito)
    - [4.8.- Pagos 24 horas](#48--pagos-24-horas)
        - [4.8.1.- Ejemplo de llamada](#481--ejemplo-de-llamada)
        - [4.8.2.- Respuesta de Salida](#482--respuesta-de-salida)
            - [4.8.2.1- Respuesta de error](#4821--respuesta-de-error)
            - [4.8.2.2- Respuesta de éxito](#4822--respuesta-de-éxito)
    - [4.9.- Medios de Pago](#49--medios-de-pago)
        - [4.9.1.- Ejemplo de llamada](#491--ejemplo-de-llamada)
        - [4.9.2.- Respuesta de Salida](#492--respuesta-de-salida)
            - [4.9.2.1- Respuesta de error](#4921--respuesta-de-error)
            - [4.9.2.2- Respuesta de éxito](#4922--respuesta-de-éxito)
    - [4.10.- Facturas Empresa](#410--facturas-empresa)
        - [4.10.1.- Ejemplo de llamada](#4101--ejemplo-de-llamada)
        - [4.10.2.- Respuesta de Salida](#4102--respuesta-de-salida)
            - [4.10.2.1- Respuesta de error](#41021--respuesta-de-error)
            - [4.10.2.2- Respuesta de éxito](#41022--respuesta-de-éxito)
    - [4.11.- Suscripciones](#411--suscripciones)
        - [4.11.1.- Ejemplo de llamada](#4111--ejemplo-de-llamada)
        - [4.11.2.- Respuesta de Salida](#4112--respuesta-de-salida)
            - [4.11.2.1- Respuesta de error](#41121--respuesta-de-error)
            - [4.11.2.2- Respuesta de éxito](#41122--respuesta-de-éxito)
  - [5.- Informes](#5--informes)
    - [5.1.- Procesados](#51--procesados)
        - [5.1.1.- Ejemplo de llamada](#511--ejemplo-de-llamada)
        - [5.1.2.- Respuesta de Salida](#512--respuesta-de-salida)
            - [5.1.2.1- Respuesta de error](#5121--respuesta-de-error)
            - [5.1.2.2- Respuesta de éxito](#5122--respuesta-de-éxito)
    - [5.2.- Log Pagos](#52--log-pagos)
        - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
        - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
            - [5.2.2.1- Respuesta de error](#5221--respuesta-de-error)
            - [5.2.2.2- Respuesta de éxito](#5222--respuesta-de-éxito)
    - [5.3.- Pagos](#52--pagos)
        - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
        - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
            - [5.3.2.1- Respuesta de error](#5321--respuesta-de-error)
            - [5.3.2.2- Respuesta de éxito](#5322--respuesta-de-éxito)
    - [5.4.- Resumen No Confirmados Online](#54--resuimen-no-confirmados-online)
        - [5.4.1.- Ejemplo de llamada](#541--ejemplo-de-llamada)
        - [5.4.2.- Respuesta de Salida](#542--respuesta-de-salida)
            - [5.4.2.1- Respuesta de error](#5421--respuesta-de-error)
            - [5.4.2.2- Respuesta de éxito](#5422--respuesta-de-éxito)
    - [5.5.- Recaudación](#55--recaudación)
        - [5.5.1.- Ejemplo de llamada](#551--ejemplo-de-llamada)
        - [5.5.2.- Respuesta de Salida](#552--respuesta-de-salida)
            - [5.5.2.1- Respuesta de error](#5521--respuesta-de-error)
            - [5.5.2.2- Respuesta de éxito](#5522--respuesta-de-éxito)
    - [5.6.- Registros Inválidos](#56--registros-inválidos)
        - [5.6.1.- Ejemplo de llamada](#561--ejemplo-de-llamada)
        - [5.6.2.- Respuesta de Salida](#562--respuesta-de-salida)
            - [5.6.2.1- Respuesta de error](#5621--respuesta-de-error)
            - [5.6.2.2- Respuesta de éxito](#5622--respuesta-de-éxito)
    - [5.7.- Resumen Monto Mes Anterior Actual](#57--resumen-monto-mes-anterior-actual)
        - [5.7.1.- Ejemplo de llamada](#571--ejemplo-de-llamada)
        - [5.7.2.- Respuesta de Salida](#572--respuesta-de-salida)
            - [5.7.2.1- Respuesta de error](#5721--respuesta-de-error)
            - [5.7.2.2- Respuesta de éxito](#5722--respuesta-de-éxito)
    - [5.8.- Resumen Trx Mes Anterior Actual](#58--resumen-trx-mes-anterior-actual)
        - [5.8.1.- Ejemplo de llamada](#581--ejemplo-de-llamada)
        - [5.8.2.- Respuesta de Salida](#582--respuesta-de-salida)
            - [5.8.2.1- Respuesta de error](#5821--respuesta-de-error)
            - [5.8.2.2- Respuesta de éxito](#5822--respuesta-de-éxito)
    - [5.9.- Trx Anuladas](#59--trx-anuladas)
        - [5.9.1.- Ejemplo de llamada](#591--ejemplo-de-llamada)
        - [5.9.2.- Respuesta de Salida](#592--respuesta-de-salida)
            - [5.9.2.1- Respuesta de error](#5921--respuesta-de-error)
            - [5.9.2.2- Respuesta de éxito](#5922--respuesta-de-éxito)
    - [5.10.- Resumen Acumulado Día](#510--resumen-acumulado-día)
        - [5.10.1.- Ejemplo de llamada](#5101--ejemplo-de-llamada)
        - [5.10.2.- Respuesta de Salida](#5102--respuesta-de-salida)
            - [5.10.2.1- Respuesta de error](#51021--respuesta-de-error)
            - [5.10.2.2- Respuesta de éxito](#51022--respuesta-de-éxito)
    - [5.11.- Resumen Monto Mes Anterior Actual](#511--resumen-monto-mes-anterior-actual)
        - [5.11.1.- Ejemplo de llamada](#5111--ejemplo-de-llamada)
        - [5.11.2.- Respuesta de Salida](#5112--respuesta-de-salida)
            - [5.11.2.1- Respuesta de error](#51121--respuesta-de-error)
            - [5.11.2.2- Respuesta de éxito](#51122--respuesta-de-éxito)
    - [5.12.- Resumen Pagos](#512--resumen-pagos)
        - [5.12.1.- Ejemplo de llamada](#5121--ejemplo-de-llamada)
        - [5.12.2.- Respuesta de Salida](#5122--respuesta-de-salida)
            - [5.12.2.1- Respuesta de error](#51221--respuesta-de-error)
            - [5.12.2.2- Respuesta de éxito](#51222--respuesta-de-éxito)
    - [5.13.- Resumen Pagos por Canal](#513--resumen-pagos-por-canal)
        - [5.13.1.- Ejemplo de llamada](#5131--ejemplo-de-llamada)
        - [5.13.2.- Respuesta de Salida](#5132--respuesta-de-salida)
            - [5.13.2.1- Respuesta de error](#51321--respuesta-de-error)
            - [5.13.2.2- Respuesta de éxito](#51322--respuesta-de-éxito)
    - [5.14.- Resumen Recaudación](#514--resumen-recaudación)
        - [5.14.1.- Ejemplo de llamada](#5141--ejemplo-de-llamada)
        - [5.14.2.- Respuesta de Salida](#5142--respuesta-de-salida)
            - [5.14.2.1- Respuesta de error](#51421--respuesta-de-error)
            - [5.14.2.2- Respuesta de éxito](#51422--respuesta-de-éxito)
    - [5.15.- Resumen Recaudación Canal](#515--resumen-recaudación-canal)
        - [5.15.1.- Ejemplo de llamada](#5151--ejemplo-de-llamada)
        - [5.15.2.- Respuesta de Salida](#5152--respuesta-de-salida)
            - [5.15.2.1- Respuesta de error](#51521--respuesta-de-error)
            - [5.15.2.2- Respuesta de éxito](#51522--respuesta-de-éxito)
    - [5.16.- Resumen Trx Mes Anterior Actual](#516--resumen-trx-mes-anterior-actual)
        - [5.16.1.- Ejemplo de llamada](#5161--ejemplo-de-llamada)
        - [5.16.2.- Respuesta de Salida](#5162--respuesta-de-salida)
            - [5.16.2.1- Respuesta de error](#51621--respuesta-de-error)
            - [5.16.2.2- Respuesta de éxito](#51622--respuesta-de-éxito)
  - [6.- Servicio de Pago](#6--servicio-de-pago)
    - [6.1.- Base64 a Guid](#61--base64-a-guid)
        - [6.1.1.- Ejemplo de llamada](#611--ejemplo-de-llamada)
        - [6.1.2.- Respuesta de Salida](#612--respuesta-de-salida)
            - [6.1.2.1- Respuesta de error](#6121--respuesta-de-error)
            - [6.1.2.2- Respuesta de éxito](#6122--respuesta-de-éxito)
    - [6.2.- Guid a Base64](#62--guid-a-base64)
        - [6.2.1.- Ejemplo de llamada](#621--ejemplo-de-llamada)
        - [6.2.2.- Respuesta de Salida](#622--respuesta-de-salida)
            - [6.2.2.1- Respuesta de error](#6221--respuesta-de-error)
            - [6.2.2.2- Respuesta de éxito](#6222--respuesta-de-éxito)
    - [6.3.- Pagos en Proceso](#63--pagos-en-proceso)
        - [6.3.1.- Ejemplo de llamada](#631--ejemplo-de-llamada)
        - [6.3.2.- Respuesta de Salida](#632--respuesta-de-salida)
            - [6.3.2.1- Respuesta de error](#6321--respuesta-de-error)
            - [6.3.2.2- Respuesta de éxito](#6322--respuesta-de-éxito)
    - [6.4.- Pagos en Proceso Cliente](#64--pagos-en-proceso-cliente)
        - [6.4.1.- Ejemplo de llamada](#641--ejemplo-de-llamada)
        - [6.4.2.- Respuesta de Salida](#642--respuesta-de-salida)
            - [6.4.2.1- Respuesta de error](#6421--respuesta-de-error)
            - [6.4.2.2- Respuesta de éxito](#6422--respuesta-de-éxito)
    - [6.5.- Resumen Pagos en Proceso](#65--resumen-pagos-en-proceso)
        - [6.5.1.- Ejemplo de llamada](#651--ejemplo-de-llamada)
        - [6.5.2.- Respuesta de Salida](#652--respuesta-de-salida)
            - [6.5.2.1- Respuesta de error](#6521--respuesta-de-error)
            - [6.5.2.2- Respuesta de éxito](#6522--respuesta-de-éxito)
    - [6.6.- Consulta Pagos](#66--consulta-pagos)
        - [6.6.1.- Ejemplo de llamada](#661--ejemplo-de-llamada)
        - [6.6.2.- Respuesta de Salida](#662--respuesta-de-salida)
            - [6.6.2.1- Respuesta de error](#6621--respuesta-de-error)
            - [6.6.2.2- Respuesta de éxito](#6622--respuesta-de-éxito)
    - [6.7.- Actualizar Proceso](#67--actualizar-proceso)
        - [6.7.1.- Ejemplo de llamada](#671--ejemplo-de-llamada)
        - [6.7.2.- Respuesta de Salida](#672--respuesta-de-salida)
            - [6.7.2.1- Respuesta de error](#6721--respuesta-de-error)
            - [6.7.2.2- Respuesta de éxito](#6722--respuesta-de-éxito)




# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Empresas
## 1.1.- Existe Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/existecliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 1.2.- Obtener Deuda
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/obtenerdeuda`

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



# 2.- Pago
## 2.1.- Consolida Deuda
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/consolidadeuda`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 2.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 2.2.- Procesar Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/procesapago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
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


# 3.- Rendiciones
## 3.1.- Rendiciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendiciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 3.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 3.2.- Rendiciones Filtro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 3.2.2.2.- Respuesta de éxito

	{
        ...
	}

## 3.3.- Rendiciones Filtro Exportar
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilterExportar`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 3.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 3.4.- Rendiciones Resumen Filtro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesresumenFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 3.4.2.2.- Respuesta de éxito

	{
        ...
	}


# 4.- Medios de Pago
## 4.1.- Canales de Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/canalespago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.2.- Clientes Suscritos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/clientessuscritos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.2.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.3.- Eliminar Registro
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getEliminaregistro`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.4.- Exportar Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaExportar`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.4.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.5.- Pago Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaPago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.5.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.6.- Empresa Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturasEmpresa`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.7.- Filtros Factura
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturasFilter`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.7.2.2.- Respuesta de éxito

	{
        ...
	}

## 4.8.- Pagos 24 horas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/pagos24horas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.8.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.8.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.9.- Medios de Pago
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/mediosPago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.9.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.9.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.10.- Facturas Empresa
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/postFacturasEmpresa`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.10.2.2.- Respuesta de éxito

	{
        ...
	}


## 4.11.- Suscripciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/suscripciones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 4.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 4.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.11.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.11.2.2.- Respuesta de éxito

	{
        ...
	}


# 5.- Informes
## 5.1.- Procesados
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/archivos/procesados`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 5.2.- Log Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/logpagos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.2.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.3.- Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.4.- Resumen No Confirmados Online
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagos/resumennoconfirmadosonline`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.4.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.5.- Recaudación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/recaudacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.5.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.6.- Registros Inválidos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/registrosinvalidos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 5.7.- Resumen Monto Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumenmontomesanterioactual`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.7.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.8.- Resumen Trx Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumentrxmesanterioactual`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.8.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.8.2.2.- Respuesta de éxito

	{
        ...
	}


## 5.9.- Trx Anuladas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/trxanuladas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.9.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.9.2.2.- Respuesta de éxito

	{
        ...
	}


## 5.10.- Resumen Acumulado Día
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenacumuladodia`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.10.2.2.- Respuesta de éxito

	{
        ...
	}


## 5.11.- Resumen Monto Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenmontomesanterioactual`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.11.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.11.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.12.- Resumen Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.12.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.12.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.13.- Resumen Pagos por Canal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosporcanal`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.13.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.13.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.14.- Resumen Recaudación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.14.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.14.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.15.- Resumen Recaudación Canal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacioncanal`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.15.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.15.2.2.- Respuesta de éxito

	{
        ...
	}

## 5.16.- Resumen Trx Mes Anterior Actual
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumentrxmesanterioactual`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 5.16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 5.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.16.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.16.2.2.- Respuesta de éxito

	{
        ...
	}


# 6.- Servicio de Pago
## 6.1.- Base64 a Guid
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/base64toguid`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.1.2.2.- Respuesta de éxito

	{
        ...
	}


## 6.2.- Guid a Base64
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/guidtobase64`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.2.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.3.- Pagos en Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenproceso`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.3.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.4.- Pagos en Proceso Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenprocesocliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.4.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.5.- Resumen Pagos en Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosenproceso`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.5.2.2.- Respuesta de éxito

	{
        ...
	}

## 6.6.- Consulta Pagos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/consultapago`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.6.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 6.7.- Actualizar Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/actualizaproceso`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 6.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.7.2.2.- Respuesta de éxito

	{
        ...
	}