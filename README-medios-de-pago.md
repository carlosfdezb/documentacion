| Tipo de seguridad|
|:----------------:|
| Ninguna          |

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
        - [2.1.- Procesar Pago](#21--procesar-pago)
            - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
            - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
                  - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
                  - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
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
            - [4.1.1.- Respuesta de Salida](#411--respuesta-de-salida)
                  - [4.1.1.1- Respuesta de éxito](#4111--respuesta-de-éxito)
        - [4.2.- Clientes Suscritos](#42--clientes-suscritos)
            - [4.2.1.- Respuesta de Salida](#421--respuesta-de-salida)
                  - [4.2.1.1- Respuesta de éxito](#4211--respuesta-de-éxito)
        - [4.3.- Eliminar Registro](#43--eliminar-registro)
            - [4.3.1.- Ejemplo de llamada](#431--ejemplo-de-llamada)
            - [4.3.2.- Respuesta de Salida](#432--respuesta-de-salida)
                  - [4.3.2.1- Respuesta de éxito](#4321--respuesta-de-éxito)
        - [4.4.- Exportar Factura](#44--exportar-factura)
            - [4.4.1.- Respuesta de Salida](#441--respuesta-de-salida)
                  - [4.4.1.1- Respuesta de éxito](#4411--respuesta-de-éxito)
        - [4.5.- Pago Factura](#45--pago-factura)
            - [4.5.1.- Respuesta de Salida](#451--respuesta-de-salida)
                  - [4.5.1.1- Respuesta de éxito](#4511--respuesta-de-éxito)
        - [4.6.- Empresa Factura](#46--empresa-factura)
        - [4.7.- Filtros Factura](#47--filtros-factura)
        - [4.8.- Pagos en 24 horas](#48--pagos-en-24-horas)
            - [4.8.1.- Ejemplo de llamada](#481--ejemplo-de-llamada)
            - [4.8.2.- Respuesta de Salida](#482--respuesta-de-salida)
                - [4.8.2.1- Respuesta de error](#4821--respuesta-de-error)
                - [4.8.2.2- Respuesta de éxito](#4822--respuesta-de-éxito)
        - [4.9.- Medios de Pago](#49--medios-de-pago)
            - [4.9.1.- Respuesta de Salida](#491--respuesta-de-salida)
                  - [4.9.1.1- Respuesta de éxito](#4911--respuesta-de-éxito)
        - [4.10.- Facturas Empresa](#410--facturas-empresa)
            - [4.10.1.- Ejemplo de llamada](#4101--ejemplo-de-llamada)
            - [4.10.2.- Respuesta de Salida](#4102--respuesta-de-salida)
                  - [4.10.2.1- Respuesta de éxito](#41021--respuesta-de-éxito)
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
        - [5.2.- Log de Pagos](#52--log-de-pagos)
            - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
            - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
                  - [5.2.2.1- Respuesta de éxito](#5221--respuesta-de-éxito)
        - [5.3.- Pagos](#52--pagos)
            - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
            - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
                  - [5.3.2.1- Respuesta de error](#5321--respuesta-de-error)
                  - [5.3.2.2- Respuesta de éxito](#5322--respuesta-de-éxito)
        - [5.4.- Recaudación](#54--recaudación)
            - [5.4.1.- Ejemplo de llamada](#541--ejemplo-de-llamada)
            - [5.4.2.- Respuesta de Salida](#542--respuesta-de-salida)
                  - [5.4.2.1- Respuesta de error](#5421--respuesta-de-error)
                  - [5.4.2.2- Respuesta de éxito](#5422--respuesta-de-éxito)
        - [5.5.- Registros Inválidos](#55--registros-inválidos)
            - [5.5.1.- Ejemplo de llamada](#551--ejemplo-de-llamada)
            - [5.5.2.- Respuesta de Salida](#552--respuesta-de-salida)
                  - [5.5.2.1- Respuesta de error](#5521--respuesta-de-error)
                  - [5.5.2.2- Respuesta de éxito](#5522--respuesta-de-éxito)
        - [5.6.- Resumen de Montos del mes anterior y actual](#56--resumen-de-montos-del-mes-anterior-y-actual)
            - [5.6.1.- Respuesta de Salida](#561--respuesta-de-salida)
                  - [5.6.1.1- Respuesta de éxito](#5611--respuesta-de-éxito)
        - [5.7.- Resumen de Transacciones del mes anterior y actual](#57--resumen-de-transacciones-del-mes-anterior-y-actual)
            - [5.7.1.- Respuesta de Salida](#571--respuesta-de-salida)
                  - [5.7.1.1- Respuesta de éxito](#5711--respuesta-de-éxito)
        - [5.8.- Transacciones anuladas](#58--transacciones-anuladas)
            - [5.8.1.- Respuesta de Salida](#581--respuesta-de-salida)
                  - [5.8.1.1- Respuesta de éxito](#5811--respuesta-de-éxito)
        - [5.9.- Resumen Acumulado del Día](#59--resumen-acumulado-del-día)
            - [5.9.1.- Respuesta de Salida](#591--respuesta-de-salida))
                  - [5.9.1.1- Respuesta de éxito](#5911--respuesta-de-éxito)
        - [5.10.- Resumen de Montos del mes anterior y actual](#510--resumen-de-montos-del-mes-anterior-y-actual)
            - [5.10.1.- Respuesta de Salida](#5101--respuesta-de-salida)
                  - [5.10.1.1- Respuesta de éxito](#51011--respuesta-de-éxito)
        - [5.11.- Resumen de Pagos](#511--resumen-de-pagos)
            - [5.11.1.- Respuesta de Salida](#5111--respuesta-de-salida)
                  - [5.11.1.1- Respuesta de éxito](#51111--respuesta-de-éxito)
        - [5.12.- Resumen de Pagos por Canal](#512--resumen-de-pagos-por-canal)
            - [5.12.1.- Respuesta de Salida](#5121--respuesta-de-salida)
                  - [5.12.1.1- Respuesta de éxito](#51211--respuesta-de-éxito)
        - [5.13.- Resumen de Recaudación](#513--resumen-de-recaudación)
            - [5.13.1.- Respuesta de Salida](#5131--respuesta-de-salida)
                  - [5.13.1.1- Respuesta de éxito](#51311--respuesta-de-éxito)
        - [5.14.- Resumen de Recaudación por Canal](#514--resumen-de-recaudación-por-canal)
            - [5.14.1.- Respuesta de Salida](#5141--respuesta-de-salida)
                  - [5.14.1.1- Respuesta de éxito](#51411--respuesta-de-éxito)
        - [5.15.- Resumen de Transacciones del mes anterior y actual](#515--resumen-de-transacciones-del-mes-anterior-y-actual)
            - [5.15.1.- Respuesta de Salida](#5151--respuesta-de-salida)
                  - [5.15.1.1- Respuesta de éxito](#51511--respuesta-de-éxito)
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
            - [6.3.1.- Respuesta de Salida](#631--respuesta-de-salida)
                  - [6.3.1.1- Respuesta de éxito](#6311--respuesta-de-éxito)
        - [6.4.- Pagos en Proceso Cliente](#64--pagos-en-proceso-cliente)
            - [6.4.1.- Ejemplo de llamada](#641--ejemplo-de-llamada)
            - [6.4.2.- Respuesta de Salida](#642--respuesta-de-salida)
                  - [6.4.2.1- Respuesta de error](#6421--respuesta-de-error)
                  - [6.4.2.2- Respuesta de éxito](#6422--respuesta-de-éxito)
        - [6.5.- Resumen Pagos en Proceso](#65--resumen-pagos-en-proceso)
            - [6.5.1.- Respuesta de Salida](#651--respuesta-de-salida)
                  - [6.5.1.1- Respuesta de éxito](#6511--respuesta-de-éxito)
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
        - [6.8.- Consolidar Deuda](#68--consolidar-deuda)
            - [6.8.1.- Ejemplo de llamada](#681--ejemplo-de-llamada)
            - [6.8.2.- Respuesta de Salida](#682--respuesta-de-salida)
                  - [6.8.2.1- Respuesta de error](#6821--respuesta-de-error)
                  - [6.8.2.2- Respuesta de éxito](#6822--respuesta-de-éxito)
        - [6.9.- Procesar Pago](#69--procesar-pago)
            - [6.9.1.- Ejemplo de llamada](#691--ejemplo-de-llamada)
            - [6.9.2.- Respuesta de Salida](#692--respuesta-de-salida)
                  - [6.9.2.1- Respuesta de error](#6921--respuesta-de-error)
                  - [6.9.2.2- Respuesta de éxito](#6922--respuesta-de-éxito)




# Objetivo

Disponer Api's para realizar la gestión de los distintos medios de pago de Mundo.

# Restricciones

En este documento solo se describen Api's propias del sistema, no externas a este.


# 1.- Empresas
## 1.1.- Existe Cliente
Método que permite comprobar la existencia de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/existecliente`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**

|          Descripción                             |
|-------------------------------------------------:| 
| 0 : si no existe cliente, 1 : si existe cliente  |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "NOMBRE_CAMPO":"166101069"
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "El rut  es invalido o no tiene formato correcto. El formato es NNNNNNNNC"
                },
                "codigo": 422
        }
  
#### 1.1.2.2.- Respuesta de éxito

`1`


## 1.2.- Obtener Deuda
Método que permite obtener la deuda de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/empresas/obtenerdeuda`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar deudas|

**Datos de salida:**

| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
| identificador     | string       | ID de la deuda                                   | 
| documentoVencido  | string       | Documento vencido                                | 
| fechaVencida      | date         | Fecha vencida                                    | 
| deudaVencida      | string       | Deuda vencida                                    | 
| documentoPorVencer| string       | Documento por vencer                             | 
| fechaPorVencer    | date         | Fecha de vencimiento de la deuda                 | 
| deudaPorVencer    | string       | Deuda por vencer                                 | 
| deudaTotal        | string       | Deuda total                                      | 
| fechaPago         | string       | Fecha de pago                                    | 
| idTransaccion     | string       | ID de la transacción                             | 
| nombre            | string       | Nombre del cliente                               |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":"166101069"
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos de Deuda"
                },
                "codigo": 204
        }
#### 1.2.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "identificador": "130914551",
                                        "documentoVencido": "5555",
                                        "fechaVencida": "22/01/2021",
                                        "deudaVencida": "45",
                                        "documentoPorVencer": null,
                                        "fechaPorVencer": null,
                                        "deudaPorVencer": null,
                                        "deudaTotal": "45",
                                        "fechaPago": "20210901160300803",
                                        "idTransaccion": "ce947ef4-1c39-d6bb-48da-1ec03e22ee20",
                                        "nombre": "jose orozco"
                                }
                        ]
                        }
                },
                "codigo": 200
        }



# 2.- Pago
## 2.1.- Procesar Pago
Método que permite procesar pago de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/procesapago`

**Parámetros de entrada:**

| Campo          | Formato        |     Requerido    |          Descripción      |
|:--------------:|:--------------:|:----------------:|--------------------------:|
| Canal          |                |                  | Tipo de canal             |
| IdTransaccion  |                | Si               | ID de la transacción      |
| IdCliente      | NNNNNNNNC      | Si               | Rut del cliente           |
| Monto          |                | Si               | Monto del pago            |
| Fecha          |                | Si               | Fecha del pagoo           |
| UnidadNegocio  |                |                  | Unidad de negocio         |
| CodigoRespuesta|                |                  | Código de respuesta       |
| Token          |                |                  | Token                     |
| OrdenCompra    |                |                  | Orden de compra           |
| CodAutorizacion|                |                  | Código de autorización    |
| TipoPago       |                |                  | Tipo de pago              |
| NumTarjeta     |                |                  | Número de tarjeta         |
| NumeroCuotas   |                |                  | Número Cuotas             |
| VCI            |                |                  | VCI                       |
| FechaContable  |                |                  | Fecha contable            |
| FechaTransaccion|               |                  | Fecha de transacción      |
| TipoCliente    |                |                  | Tipo de cliente           |

### 2.1.1.- Ejemplo de llamada

Ejemplo: XML 

```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ws="http://ws.mundo.accolm.com/">
   <soapenv:Header/>
   <soapenv:Body>
      <ws:ProcesaPago>
         <!--Optional:-->
         <Canal>BS</Canal>
         <IdTransaccion>b9e0ee94-1cdf-45f7-9c82-61c0a4d53ff5</IdTransaccion>
         <IdCliente>135982547</IdCliente>
         <Monto>12572</Monto>
         <Fecha>20201105085801000</Fecha>
         <!--Optional:-->
         <UnidadNegocio>MPH</UnidadNegocio>
         <!--Optional:-->
         <CodigoRespuesta></CodigoRespuesta>
         <!--Optional:-->
         <Token></Token>
         <!--Optional:-->
         <OrdenCompra></OrdenCompra>
         <!--Optional:-->
         <CodAutorizacion></CodAutorizacion>
         <!--Optional:-->
         <TipoPago></TipoPago>
         <!--Optional:-->
         <NumTarjeta></NumTarjeta>
         <!--Optional:-->
         <NumeroCuotas></NumeroCuotas>
         <!--Optional:-->
         <VCI>?</VCI>
         <!--Optional:-->
         <FechaContable>?</FechaContable>
         <!--Optional:-->
         <FechaTransaccion>?</FechaTransaccion>
         <!--Optional:-->
         <TipoCliente>0</TipoCliente>

      </ws:ProcesaPago>
   </soapenv:Body>
</soapenv:Envelope>
```

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

```xml
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
   <soap:Body>
      <ns2:ProcesaPagoResponse xmlns:ns2="http://ws.mundo.accolm.com/">
         <Resultados>
            <EstadoResultado>
               <Codigo>3100</Codigo>
               <Descripcion>Numero de Transacci�n Incorrecta</Descripcion>
               <Observaciones>El n�mero de transacci�n informado al procesar un pago es incorrecto</Observaciones>
            </EstadoResultado>
         </Resultados>
      </ns2:ProcesaPagoResponse>
   </soap:Body>
</soap:Envelope>
```
  
#### 2.1.2.2.- Respuesta de éxito

```xml
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
   <soap:Body>
      <ns2:ProcesaPagoResponse xmlns:ns2="http://ws.mundo.accolm.com/">
         <Resultados>
            <EstadoResultado>
               <Codigo>0</Codigo>
               <Descripcion>Respuesta de existo</Descripcion>
               <Observaciones>Respuesta de exito</Observaciones>
            </EstadoResultado>
         </Resultados>
      </ns2:ProcesaPagoResponse>
   </soap:Body>
</soap:Envelope>
```

# 3.- Rendiciones
## 3.1.- Rendiciones
Método que permite buscar rendiciones asociadas al rut del cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendiciones`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente             |

**Datos de salida:**

| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| fechaPago       | date         | Fecha de pago                                    |
| horaPago        | string       | Hora de pago                                     |
| montoPagado     | string       | Monto que se ha pagado                           |
| medioPago       | string       | Medio de pago                                    |
| archivorendicion| string       | Comprobante de pago                              |
| estadoPago      | string       | Estado del pago                                  |

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 3.1.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "fechaPago": "09/08/2021",
                                        "horaPago": "17:03:21",
                                        "montoPagado": "27570",
                                        "medioPago": "UNIRED WEB",
                                        "archivorendicion": "20210811000099800000000021882605UNRED.TXT",
                                        "estadoPago": "CARGO APLICADO"
                                },
                                {
                                        "fechaPago": "18/07/2021",
                                        "horaPago": "16:04:59",
                                        "montoPagado": "12970",
                                        "medioPago": "UNIRED WEB",
                                        "archivorendicion": "20210720000001900000000000138224UNPMP.TXT",
                                        "estadoPago": "CARGO APLICADO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 3.2.- Rendiciones Filtro
Método que permite buscar rendiciones asociadas al rut del cliente de forma paginada.

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilter`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| per_page     | int          |                                |                                 | Cantidad de resultados por página|
| rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente             |
| medioPago    | int          |                                | Si                              | Tipo de medio de pago       |


**Datos de salida:**

| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| MPRE_ID_REGISTRO   | int          | ID del registro                                  | 
| MPRE_FECHA_PAGO    | timestamp    | Fecha de pago                                    | 
| MPRE_MONTO_PAGADO  | string       | Monto del pago                                   | 
| ARCHIVO            | string       | Comprobante de pago                              | 
| MPRE_ID_TRANSACCION| string       | ID de la transacción                             | 
| MPRE_ID_CLIENTE    | string       | Rut del cliente                                  | 
| MPRE_FECHA_CONTABLE| timestamp    | Fecha contable                                   | 
| FORMA_PAGO         | string       | Medio de pago                                    |
| ESTADO             | string       | Estado del pago                                  |

### 3.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "per_page": 1,
                "rut": "166101069",
                "medioPago": 2
	}

### 3.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.2.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados "
                },
                "codigo": 204
        }
  
#### 3.2.2.2.- Respuesta de éxito

        {
                "current_page": 1,
                "data": [
                        {
                                "MPRE_ID_REGISTRO": 322492,
                                "MPRE_FECHA_PAGO": "2018-08-08 16:19:33.000",
                                "MPRE_MONTO_PAGADO": "25",
                                "ARCHIVO": "RenPCNorte_IN_20180809.TXT",
                                "MPRE_ID_TRANSACCION": "0b929594-7195-483f-8606-30cdf8313a4b",
                                "MPRE_ID_CLIENTE": "166101069",
                                "MPRE_FECHA_CONTABLE": "2018-08-09 00:00:00.000",
                                "FORMA_PAGO": "BANCO ESTADO.CL",
                                "ESTADO": "CARGO APLICADO"
                        }
                ],
                "first_page_url": "...URL/rendicionesFilter?per_page=4&rut=166101069&medioPago=2&page=1",
                "from": 1,
                "last_page": 1,
                "last_page_url": "...URL/rendicionesFilter?per_page=4&rut=166101069&medioPago=2&page=1",
                "next_page_url": null,
                "path": "...URL/rendicionesFilter",
                "per_page": "4",
                "prev_page_url": null,
                "to": 1,
                "total": 1
        }

## 3.3.- Rendiciones Filtro Exportar
Método que permite exportar las rendiciones asociadas al rut del cliente en excel.

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesFilterExportar`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| per_page     | int          |                                |                                 | Cantidad de resultados por página|
| rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente             |
| medioPago    | int          |                                | Si                              | Tipo de medio de pago       |

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTrx          | string       | ID de la transacción                             |
| identificador  | string       | Identificador del pago                           |
| montoPagado    | string       | Monto del papo                                   |
| fechaPago      | timestamp    | Fecha del pago                                   |
| fechaContable  | date         | Fecha contable                                   |
| archivo        | string       | Comprobante                                      |
| formaPago      | string       | Medio de pago                                    |
| estado         | string       | Estado del pago                                  |

### 3.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "per_page": 1,
                "rut": "166101069",
                "medioPago": 2
	}

### 3.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.3.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados"
                },
                "codigo": 204
        }
  
#### 3.3.2.2.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTrx": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                        "identificador": "166101069",
                                        "montoPagado": "27570",
                                        "fechaPago": "09/08/2021 17:03:21",
                                        "fechaContable": "09/08/2021",
                                        "archivo": "20210811000099800000000021882605UNRED.TXT",
                                        "formaPago": "UNIRED WEB",
                                        "estado": "CARGO APLICADO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 3.4.- Rendiciones Resumen Filtro
Método que permite obtener rendiciones de un medio de pago en específico y entre un rango de fechas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/rendicionesresumenFilter`

**Parámetros de entrada:**

| Campo         |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:-------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| medioPago     | int          |                                | Si                              | ID del medio de pago        |
| fechaPagoDesde| date         | yyyy/mm/dd                     |                                 | Fecha inicial               |
| fechaPagoHasta| date         | yyyy/mm/dd                     |                                 | Fecha final                 |

**Datos de salida:**

| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| FECHA              | date         | Fecha del pago                                   |
| DESC_CANAL         | string       | Medio de pago                                    |
| CTD                | string       | Cantidad de transacciones                        |
| MONTO              | string       | Monto del pago                                   |
| MONTO_TOTAL        | string       | Monto total del pago                             |
| CTD_TOTAL          | string       | Cantidad de transacciones totales                |

### 3.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "medioPago": 1,
                "fechaPagoDesde": 2021/08/10",
                "fechaPagoHasta": 2021/08/21"
	}

### 3.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.4.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados"
                },
                "codigo": 204
        }
  
#### 3.4.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "FECHA": "10/08/2021",
                                        "DESC_CANAL": "CAJA VECINA",
                                        "CTD": "7162",
                                        "MONTO": "149437871",
                                        "MONTO_TOTAL": "149437871",
                                        "CTD_TOTAL": "7162"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }

# 4.- Medios de Pago
## 4.1.- Canales de Pago
Método que permite obtener la lista de canales de pago.

Los parámetros que recibe son los siguientes:

Ruta : GET `/canalespago`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| IdUnidad       | string       | ID de unidad                                     |
| CodigoUnidad   | string       | Código de unidad                                 |
| UnidadNegocio  | string       | Tipo de servicio                                 |
| Canal          | string       | Abreviación de canal                             |
| NombreCanal    | string       | Nombre de canal                                  |

### 4.1.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.1.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "IdUnidad": "1",
                                        "CodigoUnidad": "MPH",
                                        "UnidadNegocio": "SERVICIO HOGAR",
                                        "Canal": "CV",
                                        "NombreCanal": "CAJA VECINA"
                                },
                                {
                                        "IdUnidad": "1",
                                        "CodigoUnidad": "MPH",
                                        "UnidadNegocio": "SERVICIO HOGAR",
                                        "Canal": "INT",
                                        "NombreCanal": "BANCO ESTADO.CL"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 4.2.- Clientes Suscritos
Método que permite obtener una lista de clientes suscritos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/clientessuscritos`

**Datos de salida:**

| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| identificador   | string       | Identificador del cliente                        |
| fechaSuscripcion| date         | Fecha de suscripción                             |
| medioSuscripcion| string       | Medio de suscripción                             |
| rutCliente      | string       | Rut del cliente                                  |

### 4.2.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.2.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "identificador": "0000005444",
                                        "fechaSuscripcion": "23-04-2021",
                                        "medioSuscripcion": "UNIVERSO PAC BANCO ESTADO",
                                        "rutCliente": "5444"
                                },
                                {
                                        "identificador": "0000053392",
                                        "fechaSuscripcion": "23-04-2021",
                                        "medioSuscripcion": "UNIVERSO PAC BANCO ESTADO",
                                        "rutCliente": "53392"
                                },
                                ...
                                ]
                        }
                },
                 "codigo": 200
	}

## 4.3.- Eliminar Registro
Método que permite eliminar registros.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getEliminaregistro`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| idregistro   | int          |                                | si                       | ID del registro             |

### 4.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idregistro": 47885
	}

### 4.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.3.2.2.- Respuesta de éxito

	{
                "data": 
                [
                        {
                                "data": "200"
                        }
                ]
        }

## 4.4.- Exportar Factura
Método que permite obtener lista con facturas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaExportar`

**Datos de salida:**

| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| MPDC_ID_DETALLE_CARGA | int          | Breve descripción                                |
| MPDC_ID_CARGA         | string       | Breve descripción                                |
| MPDC_IDENTIFICADOR    | string       | Identificador del cliente                        |
| MPDC_RUT_CLIENTE      | string       | Rut del cliente                                  |
| MPDC_RUT_DV           | string       | Dígito verificador del rut del cliente           |
| MPDC_RAZON_SOCIAL     | string       | Razón social                                     |
| MPDC_NUMERO_FACTURA   | string       | Número de factura                                |
| MPDC_MONTO            | string       | Breve descripción                                |
| MPDC_FECHA_VENCIMIENTO| timestamp    | Fecha de vencimiento                             |
| MPDC_ID_ESTADO        | string       | ID del estado                                    |
| MPPE_CANAL            | string       | Tipo de canal (abreviación)                      |
| MPPD_FECHA_PAGO       | timestamp    | Fecha de pago                                    |
| FORMA_PAGO            | string       | Forma de pago                                    |
| Estado                | string       | Estado del pago                                  |

### 4.4.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.4.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "MPDC_ID_DETALLE_CARGA": 45,
                                "MPDC_ID_CARGA": "22",
                                "MPDC_IDENTIFICADOR": "130914551",
                                "MPDC_RUT_CLIENTE": "13091455",
                                "MPDC_RUT_DV": "1",
                                "MPDC_RAZON_SOCIAL": "jose prueba",
                                "MPDC_NUMERO_FACTURA": "256",
                                "MPDC_MONTO": "10",
                                "MPDC_FECHA_VENCIMIENTO": "2021-01-19 00:00:00.000",
                                "MPDC_ID_ESTADO": "26",
                                "MPPE_CANAL": "BE",
                                "MPPD_FECHA_PAGO": "2021-01-19 06:56:32.000",
                                "FORMA_PAGO": "BOTON BANCO ESTADO",
                                "Estado": "REVERSADO POR SOLICITUD OTRO BANCO"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 4.5.- Pago Factura
Método que permite obtener facturas pagadas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/getFacturaPago`

**Datos de salida:**

| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| MPDC_ID_DETALLE_CARGA | int          | Breve descripción                                |
| MPDC_ID_CARGA         | string       | Breve descripción                                |
| MPDC_IDENTIFICADOR    | string       | Identificador del cliente                        |
| MPDC_RUT_CLIENTE      | string       | Rut del cliente                                  |
| MPDC_RUT_DV           | string       | Dígito verificador del rut del cliente           |
| MPDC_RAZON_SOCIAL     | string       | Razón social                                     |
| MPDC_NUMERO_FACTURA   | string       | Número de factura                                |
| MPDC_MONTO            | string       | Breve descripción                                |
| MPDC_FECHA_VENCIMIENTO| timestamp    | Fecha de vencimiento                             |
| MPDC_ID_ESTADO        | string       | ID del estado                                    |
| MPPE_CANAL            | string       | Tipo de canal (abreviación)                      |
| MPPD_FECHA_PAGO       | timestamp    | Fecha de pago                                    |
| FORMA_PAGO            | string       | Forma de pago                                    |
| Estado                | string       | Estado del pago                                  |

### 4.5.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.5.1.1.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                        "MPDC_ID_DETALLE_CARGA": 45,
                        "MPDC_ID_CARGA": "22",
                        "MPDC_IDENTIFICADOR": "130914551",
                        "MPDC_RUT_CLIENTE": "13091455",
                        "MPDC_RUT_DV": "1",
                        "MPDC_RAZON_SOCIAL": "jose prueba",
                        "MPDC_NUMERO_FACTURA": "256",
                        "MPDC_MONTO": "10",
                        "MPDC_FECHA_VENCIMIENTO": "2021-01-19 00:00:00.000",
                        "MPDC_ID_ESTADO": "26",
                        "MPPE_CANAL": "BE",
                        "MPPD_FECHA_PAGO": "2021-01-19 06:56:32.000",
                        "FORMA_PAGO": "BOTON BANCO ESTADO",
                        "Estado": "REVERSADO POR SOLICITUD OTRO BANCO"
                        },
                        ...
                ],
                "first_page_url": "...URL/getFacturaPago?page=1",
                "from": 1,
                "last_page": 1,
                "last_page_url": "...URL/getFacturaPago?page=1",
                "next_page_url": null,
                "path": "...URL/getFacturaPago",
                "per_page": 15,
                "prev_page_url": null,
                "to": 6,
                "total": 6
	}

## 4.6.- Empresa Factura
**Método sin uso, desactualizado y/o en mantenimiento**

Ruta : GET `/getFacturasEmpresa`



## 4.7.- Filtros Factura
**Método sin uso, desactualizado y/o en mantenimiento**

Ruta : GET `/getFacturasFilter`



## 4.8.- Pagos en 24 horas
Método que permite obtener los pagos realizados en las últimas 24 horas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/pagos24horas`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**

| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| MPRE_ID_TRANSACCION| string       | ID de la transacción                             |

### 4.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 4.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.8.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 4.8.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "MPRE_ID_TRANSACCION": "9dad30f4-1d2a-493c-9d4d-1686ec73a7b5"
                                }
                        ]
                        }
                },
                "codigo": 200
        }

## 4.9.- Medios de Pago
Método que permite obtener lista de medios de pago.

Los parámetros que recibe son los siguientes:

Ruta : GET `/mediosPago`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | ID del medio de pago                             |
| label          | string       | Nombre del medio de pago                         |

### 4.9.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.9.1.1.- Respuesta de éxito

	[
                {
                        "id": "1",
                        "label": "CAJA VECINA"
                },
                {
                        "id": "2",
                        "label": "BANCO ESTADO.CL"
                },
                {
                        "id": "3",
                        "label": "SERVI ESTADO"
                },
                ...
	}


## 4.10.- Facturas Empresa
Método que permite subir una planilla excel de la factura y la carga en el sistema.

Los parámetros que recibe son los siguientes:

Ruta : GET `/postFacturasEmpresa`

**Parámetros de entrada:**

| Campo           |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:---------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| tiporegistro    | int          |                                | Si                           | Tipo de registro            |
| ctdfilas        | int          |                                | Si                           | Cantidad de filas           |
| nombrearchivo   | string       |                                | Si                           | Nombre del archivo          |
| idarchivo       | int          |                                | Si                           | ID del archivo              |
| usuarioregistro | int          |                                | Si                           | Registro de usuario         |
| rut             | string       | NNNNNNNNC                      | Si                           | Rut                         |
| razonsocial     | int          |                                | Si                           | Razón social                |
| numerofactura   | int          |                                | Si                           | Número de factura           |
| monto           | int          |                                | Si                           | Monto                       |
| fechavencimiento| date         | YYYY/mm/dd                     | Si                           | Fecha vencimiento           |

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Id_Archivo     | string       | Id del archivo                                   |

### 4.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "tiporegistro": "1",
                "ctdfilas": "12",
                "nombrearchivo": "archivo.xls",
                "idarchivo": "21",
                "usuarioregistro": "12",
                "rut": "96587451",
                "razonsocial": "Empresa ltda",
                "numerofactura": "2521",
                "monto": "60000",
                "fechavencimiento": "2021/08/31"
	}

### 4.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 4.10.2.1.- Respuesta de éxito

        {
                "Respuesta": [
                        {
                                "Id_Archivo": "30"
                        }
                ]
        }


## 4.11.- Suscripciones
Método que permite obtener listado con los clientes suscritos a PAC o PAT.

Los parámetros que recibe son los siguientes:

Ruta : GET `/suscripciones`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**

| Campo           |  Tipo        |                         Descripción              |
|:----------------|:------------:|-------------------------------------------------:| 
| identificador   | string       | Identificador                                    |
| fechaSuscripcion| date         | Fecha de suscripción                             |
| medioSuscripcion| string       | Medio de suscripción                             |
| rutCliente      | string       | Rut de cliente                                   |

### 4.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":"166101069"
	}

### 4.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.11.2.1.- Respuesta de error

	{
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos relacionados al Rut: 191403991"
                },
                "codigo": 204
        }
  
#### 4.11.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "identificador": "0136188054",
                                        "fechaSuscripcion": "23-04-2021",
                                        "medioSuscripcion": "UNIVERSO PAC BANCO ESTADO",
                                        "rutCliente": "136188054"
                                }
                        ]
                        }
                },
                "codigo": 200
        }


# 5.- Informes
## 5.1.- Procesados
Método que permite obtener y buscar los archivos de empresas cargados en el sistema.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/archivos/procesados`

**Parámetros de entrada:**

| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| fechaProceso     | date         | dd/mm/yyyy                     |                          | Fecha                       |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**

| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
|  idArchivo        | string       | ID del archivo                                   |
|  rutaArchivo      | string       | Ruta del archivo                                 |
|  archivo          | string       | Nombre del archivo                               |
|  cantidadRegistros| string       | Cantidad de registros                            |
|  montoTotal       | string       | Monto total                                      |
|  fechaPago        | date         | Fecha de pago                                    |
|  fechaProceso     | timestamp    | Fecha de proceso                                 |
|  clasificacion    | string       | Clasificación                                    |
|  estado           | string       | Estado                                           |

### 5.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "fechaProceso": "01/01/2020",
                "per_page": 2
	}

### 5.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.1.2.1.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                        "idArchivo": "12416",
                        "rutaArchivo": "F:\\RepoSistemas\\Pagos\\Unired\\Ftp\\",
                        "archivo": "20200101000056400000000013999929UNRED.TXT",
                        "cantidadRegistros": "564",
                        "montoTotal": "13999929",
                        "fechaPago": "01/01/2020",
                        "fechaProceso": "01/01/2020 08:00:44",
                        "clasificacion": "UNIRED",
                        "estado": "CARGO APLICADO"
                        }
                        ...
                ],
                "first_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=1",
                "from": 1,
                "last_page": 7,
                "last_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=7",
                "next_page_url": "...URL/informes/archivos/procesados?fechaProceso=01%2F01%2F2020&per_page=1&page=2",
                "path": "...URL/informes/archivos/procesados",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 7
        }


## 5.2.- Log de Pagos
Método que permite obtener lista con los logs de pagos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/logpagos`

**Parámetros de entrada:**

| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| Rut              | string       | NNNNNNNNC                      |                          | Rut del cliente             |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**

| Campo               |  Tipo        |                         Descripción              |
|:--------------------|:------------:|-------------------------------------------------:| 
| identificador       | string       | ID del pago                                      |
| idTransaccion       | string       | ID de la transacción                             |
| fechaRegistro       | timestamp    | Fecha del registro                               |
| deudaVencida        | string       | Deuda vencida                                    |
| deudaPorVencer      | string       | Deuda por vencer                                 |
| deudaTotal          | string       | Deuda total                                      |
| montoPagado         | string       | Monto pagado                                     |
| codigoRespuesta     | string       | Código de la respuesta                           |
| descripcionRespuesta| string       | Descripción de la respuesta                      |
| formaPago           | string       | Medio de pago                                    |
| estadoPago          | string       | Estado del pago                                  |

### 5.2.1.- Ejemplo de llamada

Ejemplo: JSON  

	{
                "Rut": "166101069",
                "per_page": 2
	}

### 5.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.2.2.1.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                                "identificador": "166101069",
                                "idTransaccion": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                "fechaRegistro": "2021-08-11 08:12:18.943",
                                "deudaVencida": null,
                                "deudaPorVencer": null,
                                "deudaTotal": null,
                                "montoPagado": "27570",
                                "codigoRespuesta": null,
                                "descripcionRespuesta": "TRANSACCION CONFIRMADA, CARGADA EN CRM Y RENDIDA POR ENTIDAD",
                                "formaPago": "UNIRED WEB",
                                "estadoPago": "RENDIDO"
                        },
                        ...
                ],
                "first_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=1",
                "from": 1,
                "last_page": 681,
                "last_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=681",
                "next_page_url": "...URL/informes/logpagos?Rut=166101069&per_page=2&page=2",
                "path": "...URL/informes/logpagos",
                "per_page": "2",
                "prev_page_url": null,
                "to": 2,
                "total": 1362
        }

## 5.3.- Pagos
Método que permite obtener los pagos realizados por un cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagos`

**Parámetros de entrada:**

| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| Rut              | string       | NNNNNNNNC                      |                          | Rut del cliente             |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| identificador  | string       | Identificador del pago                           |
| idTransaccion  | string       | ID de la transacción                             |
| fechaPago      | timestamp    | Fecha de pago                                    |
| montoPagado    | string       | Monto pagado                                     |
| confimadoOnLine| string       | Confirmación de pago                             |
| medioPago      | string       | Medio de pago                                    |
| estadoPago     | string       | Estado del pago                                  |

### 5.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069",
                "per_page": 2
	}

### 5.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.3.2.1.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        {
                                "identificador": "166101069",
                                "idTransaccion": "d6cd8231-dcdb-4ac3-bb9f-1ce9bb964799",
                                "fechaPago": "2021-08-09 17:05:00.000",
                                "montoPagado": "27570",
                                "confimadoOnLine": "1",
                                "medioPago": "UNIRED WEB",
                                "estadoPago": "RENDIDO"
                        }
                        ...
                ],
                "first_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=1",
                "from": 1,
                "last_page": 46,
                "last_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=46",
                "next_page_url": "...URL/informes/pagos?Rut=166101069&per_page=1&page=2",
                "path": "...URL/informes/pagos",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 46
        }



## 5.4.- Recaudación
Método que permite obtener una sumatoria de los montos recaudados.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/recaudacion`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| Anio         | int          |                                |                         | Año                         |
| MesIni       | int          |                                |                         | Mes inicial                 |
| MesFin       | int          |                                |                         | Mes final                   |
| TipoReporte  | int          |                                |                         | ID del tipo de reporte      |

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Dia            | int          | Día                                              |
| Semana         | int          | Semana                                           |
| Nombre_Dia     | string       | Nombre del día                                   |
| Nombre_Mes     | string       | Nombre del mes                                   |
| Medio_Pago     | string       | Medio de pago                                    |
| Importe        | int          | Importe                                          |

### 5.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Anio": 2021,
                "MesIni": 7,
                "MesFin": 8,
                "TipoReporte": 1
	}

### 5.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.4.2.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "Dia": 1,
                                "Semana": 0,
                                "Nombre_Dia": "DOMINGO",
                                "Nombre_Mes": "AGOSTO",
                                "Medio_Pago": "BANCO ESTADO.CL",
                                "Importe": 23338904
                                },
                                ...
                                ]
                        }
                },
                 "codigo": 200
	}

## 5.5.- Registros Inválidos
Método que permite obtener los registros de rendiciones con error.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/registrosinvalidos`

**Parámetros de entrada:**

| Campo            |  Tipo        | Formato                        |     Requerido            |             Descripción     |
|:----------------:|:------------:|:------------------------------:|:------------------------:|----------------------------:|
| fechaProceso     | date         | YYYY/mm/dd                     |                          | Fecha del proceso           |
| per_page         | int          |                                |                          | Cantidad de resultados por página|

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| identificador  | string       | Identificador                                    |
| fechaPago      | string       | Fecha de pago                                    |
| monto          | string       | Monto                                            |
| archivo        | string       | Archivo                                          |
| fechaProceso   | timestamp    | Fecha del proceso                                |
| formaPago      | string       | Forma de pago                                    |
| Estado         | string       | Estado                                           |

### 5.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "fechaProceso": "2019/07/29",
                "per_page": 2
	}

### 5.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.5.2.1.- Respuesta de éxito

        {
                "current_page": 1,
                "data": [
                        {
                                "identificador": null,
                                "fechaPago": "2019-07-15 00:00:00.000",
                                "monto": "84915",
                                "archivo": "00000002477_R_20190722.DAT",
                                "fechaProceso": "2019-07-29 11:09:24.013",
                                "formaPago": "PAC BANCO ESTADO",
                                "Estado": "TIENE CONFIGURADO MONTO LIMITE O EL  MANDATO NO SE ENCUENTRA VIGENTE"
                        }
                ],
                "first_page_url": "...URL/informes/rendicion/registrosinvalidos?fechaProceso=2019%2F07%2F29&per_page=1&page=1",
                "from": 1,
                "last_page": 1780,
                "last_page_url": "...URL/informes/rendicion/registrosinvalidos?fechaProceso=2019%2F07%2F29&per_page=1&page=1780",
                "next_page_url": "...URL/informes/rendicion/registrosinvalidos?fechaProceso=2019%2F07%2F29&per_page=1&page=2",
                "path": "...URL/informes/rendicion/registrosinvalidos",
                "per_page": "1",
                "prev_page_url": null,
                "to": 1,
                "total": 1780
        }


## 5.6.- Resumen de Montos del mes anterior y actual
Método que permite obtener la recaudación del mes anterior y el actual en base a la rendición.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumenmontomesanterioactual`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Nombre del mes                                   |
| montos         | string       | Lista de montos                                  |

### 5.6.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.6.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "mes": "Agosto",
                                        "montos": "426234159,721663853,670666896,673432654,766210089,390710397,269471307,159858592,344040656,520641269,288621508,219664159,238685249,180035402,191807131,415781275,447032803,321628938,269712180,631628757,184451832,136271797,213661083,243546284,230750104,237547789,228478772,78252167,66548385,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.7.- Resumen de Transacciones del mes anterior y actual
Método que permite obtener las transacciones del mes anterior y el actual en base a la rendición.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/resumentrxmesanterioactual`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Nombre del mes                                   |
| montos         | string       | Lista de montos                                  |

### 5.7.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.7.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "mes": "Agosto",
                                        "montos": "19104,32419,29976,30646,37376,18412,12505,7417,15889,25843,13968,10585,11357,8601,9152,19953,21681,15239,12400,31421,9234,6678,10496,12143,11203,11664,10243,3796,3205,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}


## 5.8.- Transacciones anuladas
Métodos que permite obtener las transacciones anuladas por los bancos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/rendicion/trxanuladas`

### 5.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.8.2.1.- Respuesta de éxito

	{
                "current_page": 1,
                "data": [
                        ...
                ],
                "first_page_url": "...URL/informes/rendicion/trxanuladas?page=1",
                "from": null,
                "last_page": 1,
                "last_page_url": "...URL/informes/rendicion/trxanuladas?page=1",
                "next_page_url": null,
                "path": "...URL/informes/rendicion/trxanuladas",
                "per_page": 15,
                "prev_page_url": null,
                "to": null,
                "total": 0
        }


## 5.9.- Resumen Acumulado del Día
Método que permite tener los montos del día.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenacumuladodia`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| mes            | string       | Nombre del mes                                   |
| montos         | string       | Lista de montos                                  |

### 5.9.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.9.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                "unidad": "SERVICIO HOGAR",
                                "montos": "5757944,8189759,9267296,9771447,10295938,10878465,11889833,14641158,24459839,45462813,73303103,108409627,185714365,264744314,323044691,379214325,432405624,438577632,0,0,0,0,0,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }


## 5.10.- Resumen de Montos del mes anterior y actual
Método que permite obtener los montos del mes anterior y el actual en base a los pagos recibidos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenmontomesanterioactual`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| unidad         | string       | Nombre de la unidad                              |
| mes            | string       | Nombre del mes                                   |
| montos         | string       | Lista de montos                                  |

### 5.10.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.10.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "unidad": "SERVICIO HOGAR",
                                        "mes": "Agosto HOGAR",
                                        "montos": "423533012,719897364,668617660,670663652,763860570,388931640,268508756,158949652,342362975,518229058,286424005,218426722,235575054,179060984,190820141,413555948,444906157,320047675,312729539,629589115,183787932,135620638,212752542,242610810,229425651,236439097,345298457,254897600,204390534,773783155,319292992"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }

## 5.11.- Resumen de Pagos
Método que permite obtener un resumen de pagos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagos`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Hora del día                                     |
| horario        | string       | Rango horario                                    |
| dia            | string       | Número de día                                    |
| exito          | string       | Estado en el crm                                 |
| cargadocrm     | string       | Cargados al crm                                  |
| rendido        | string       | Rendido por la entidad de pago                   |
| error          | string       | Error al cargar al crm                           |
| reversado      | string       | Indica la cantidad de pagos reversados           |

### 5.11.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.11.1.1.- Respuesta de éxito

	{
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "id": "0",
                                        "horario": "00:00 00:59",
                                        "dia": "30",
                                        "exito": "1",
                                        "cargadocrm": "269",
                                        "rendido": "1",
                                        "error": "1",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.12.- Resumen de Pagos por Canal
Método que permite obtener un resumen de pagos separados por canal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosporcanal`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Hora del día                                     |
| horario        | string       | Rango horario                                    |
| canal          | string       | Tipo de canal                                    |
| dia            | string       | Número de día                                    |
| exito          | string       | Estado en el crm                                 |
| cargadocrm     | string       | Cargados al crm                                  |
| rendido        | string       | Rendido por la entidad de pago                   |
| error          | string       | Error al cargar al crm                           |
| reversado      | string       | Indica la cantidad de pagos reversados           |


### 5.12.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.12.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "id": "0",
                                        "horario": "00:00 00:59",
                                        "canal": "BANCO ESTADO.CL",
                                        "dia": "30",
                                        "exito": "0",
                                        "cargadocrm": "6",
                                        "rendido": "0",
                                        "error": "0",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.13.- Resumen de Recaudación
Método que permite obtener el resumen de la recaudación.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacion`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Hora del día                                     |
| horario        | string       | Rango horario                                    |
| dia            | string       | Número de día                                    |
| exito          | string       | Estado en el crm                                 |
| cargadocrm     | string       | Cargados al crm                                  |
| rendido        | string       | Rendido por la entidad de pago                   |
| error          | string       | Error al cargar al crm                           |
| reversado      | string       | Indica la cantidad de pagos reversados           |


### 5.13.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.13.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "id": "0",
                                        "horario": "00:00 00:59",
                                        "dia": "30",
                                        "exito": "0",
                                        "cargadocrm": "0",
                                        "rendido": "0",
                                        "error": "14982",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.14.- Resumen de Recaudación por Canal
Método que permite obtener el resumen de la recaudación por canales.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenrecaudacioncanal`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| id             | string       | Hora del día                                     |
| horario        | string       | Rango horario                                    |
| dia            | string       | Número de día                                    |
| exito          | string       | Estado en el crm                                 |
| cargadocrm     | string       | Cargados al crm                                  |
| rendido        | string       | Rendido por la entidad de pago                   |
| error          | string       | Error al cargar al crm                           |
| reversado      | string       | Indica la cantidad de pagos reversados           |

### 5.14.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.14.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "canal": "BANCO ESTADO.CL",
                                        "exito": "68473",
                                        "cargadocrm": "7944566",
                                        "rendido": "0",
                                        "error": "191127",
                                        "reversado": "0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 5.15.- Resumen de Transacciones del mes anterior y actual
Método que permite obtener el resumen de las transacciones en base a los montos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumentrxmesanterioactual`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| unidad         | string       | Nombre de la unidad                              |
| mes            | string       | Nombre del mes                                   |
| montos         | string       | Lista de montos                                  |

### 5.15.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 5.15.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "unidad": "SERVICIO HOGAR",
                                        "mes": "Agosto HOGAR",
                                        "montos": "18850,32170,29742,30363,37111,18218,12389,7325,15697,25591,13758,10437,11142,8489,9044,19696,21393,15047,14444,31206,9156,6588,10379,12027,11052,11529,15460,11918,9547,21828,0"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
        }


# 6.- Servicio de Pago
## 6.1.- Base64 a Guid
Método que permite convertir de Base64 a guid.

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/base64toguid`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| idTrx        | string       | base64                         | Si                      | Breve descripción           |

### 6.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idTrx":"58444dc"
	}

### 6.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.1.2.1.- Respuesta de error

`----`
  
#### 6.1.2.2.- Respuesta de éxito

`e7ce38e1-d7---`


## 6.2.- Guid a Base64
Método que permite convertir de guid a base64.

Los parámetros que recibe son los siguientes:

Ruta : GET `/funciones/guidtobase64`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido           |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-----------------------:|----------------------------:|
| idTrx        | string       | Guid                           | Si                      | Breve descripción           |

### 6.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "idTrx":"e7ce38e1-d7---"
	}

### 6.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.2.1.- Respuesta de error

`----` 
  
#### 6.2.2.2.- Respuesta de éxito

`58444dc=`

## 6.3.- Pagos en Proceso
Método que permite obtener lista con los pagos en proceso.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenproceso`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTransaccion  | string       | Identificador de la transacción                  |
| identificador  | string       | Identificador                                    |
| canal          | string       | Tipo de canal (abreviación)                      |
| monto          | int          | Monto                                            |
| unidadNegocio  | string       | Unidad de negocio                                |
| fechaPago      | timestamp    | fecha de pago                                    |
| tipoCliente    | int          | Tipo de cliente                                  |
| fechaRegistro  | timestamp    | Fecha de registro                                |

### 6.3.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 6.3.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTransaccion": "444ca478-6191-406b-8ec9-0c9106e709d9",
                                        "identificador": "140219932",
                                        "canal": "SN",
                                        "monto": 5489,
                                        "unidadNegocio": "MPM",
                                        "fechaPago": "2021-08-24T14:31:59",
                                        "tipoCliente": 99,
                                        "fechaRegistro": "2021-08-24 14:26:27"
                                },
                                ...
                                ]
                        }
                },
                "codigo": 200
	}

## 6.4.- Pagos en Proceso Cliente
Método que permite obtener lista de pagos en procesos de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/pagosenprocesocliente`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| idTransaccion  | string       | Identificador de la transacción                  |
| identificador  | string       | Identificador                                    |
| canal          | string       | Tipo de canal (abreviación)                      |
| monto          | int          | Monto                                            |
| unidadNegocio  | string       | Unidad de negocio                                |
| fechaPago      | timestamp    | fecha de pago                                    |
| tipoCliente    | int          | Tipo de cliente                                  |
| fechaRegistro  | timestamp    | Fecha de registro                                |

### 6.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut":  "166101069"
	}

### 6.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.4.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos pagos en proceso para el rut:191403991 "
                },
                "codigo": 204
        }
  
#### 6.4.2.2.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "idTransaccion": "c273b344-72df-48fc-bb4a-503db3b9ff3e",
                                        "identificador": "166101069",
                                        "canal": "WP",
                                        "monto": 14600,
                                        "unidadNegocio": "MPH",
                                        "fechaPago": "20210120001622958",
                                        "tipoCliente": 0,
                                        "fechaRegistro": "2021-04-07 09:26:00"
                                }
                                ]
                        }
                },
                "codigo": 200
        }

## 6.5.- Resumen Pagos en Proceso
Método que permite obtener un resumen de los pagos en proceso.

Los parámetros que recibe son los siguientes:

Ruta : GET `/informes/resumenpagosenproceso`

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| procesado      | int          | Breve descripción                                |
| cantidad       | int          | Breve descripción                                |

### 6.5.1.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje
  
#### 6.5.1.1.- Respuesta de éxito

        {
                "success": {
                        "codigoRespuesta": 1,
                        "descripcionRespuesta": {
                        "data": [
                                {
                                        "procesado": 0,
                                        "cantidad": 46
                                },
                                {
                                        "procesado": 1,
                                        "cantidad": 533
                                }
                        ]
                        }
                },
                "codigo": 200
        }

## 6.6.- Consulta Pagos
Método que permite consultar pagos de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/consultapago`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido                   | Descripción                 |
|:------------:|:------------:|:------------------------------:|:-------------------------------:|----------------------------:|
| Rut          | string       | NNNNNNNNC                      | Si                              | Rut del cliente a buscar    |

**Datos de salida:**

| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 6.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "Rut": "166101069"
	}

### 6.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.6.2.1.- Respuesta de error

        {
                "error": {
                        "codigoRespuesta": 0,
                        "descripcionRespuesta": "Error",
                        "detalleRespuesta": "No hay datos de pagos de pago para el rut 166101069. "
                },
                "codigo": 204
        }
  
#### 6.6.2.2.- Respuesta de éxito

	{
        ...
	}


## 6.7.- Actualizar Proceso
Método que permite actualizar procesos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/pagos/actualizaproceso`

**Parámetros de entrada:**

| Campo        |  Tipo        | Formato                        |     Requerido             |             Descripción     |
|:------------:|:------------:|:------------------------------:|:-------------------------:|----------------------------:|
| IdCliente    | string       | NNNNNNNNC                      | Si                        | ID del cliente              |
| idTransaccion| int          |                                | Si                        | ID de la transacción       |

### 6.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
                "IdCliente": "166101069",
                "idTransaccion": 54444
	}

### 6.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 6.7.2.2.- Respuesta de éxito

`OK`


## 6.8.- Consolidar Deuda
Método que permite consolidar deuda de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/MundoWebpay/services/servicioDeuda`

**Parámetros de entrada:**

| Campo        | Formato                        |     Requerido        |             Descripción     |
|:------------:|:------------------------------:|:--------------------:|----------------------------:|
| RutCliente   | NNNNNNNNC                      |  Si                  | Rut del cliente             |
| Canal        |                                |  Si                  | Tipo de canal               |
| UnidadNegocio|                                |                      | Unidad de negocio           |

**Datos de salida:**

| Campo          |                          Descripción              |
|:---------------|:-------------------------------------------------:| 
| IDTransaccion  |  ID de la transacción                             |
| IDCliente      |  ID del cliente                                   |
| NombreCliente  |  Nombre del cliente                               |
| DeudaVencida   |  Monto deuda vencida                              |
| FechaVencida   |  Fecha de deuda vencida                           |
| DeudaPorVencer |  Monto deuda por vencer                           |
| FechaPorVencer |  Fecha de deudar por vencer                       |
|DocumentoPorVencer|Documento de deuda por vencer                    |
| DeudaTotal     |  Deuda total                                      |
| TimeStamp      |  Fecha y hora                                     |


### 6.8.1.- Ejemplo de llamada

Ejemplo: XML 

```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ws="http://ws.mundo.accolm.com/">
   <soapenv:Header/>
   <soapenv:Body>
      <ws:ConsolidaDeudaRut>
         <RutCliente>189503253</RutCliente>
         <Canal>bs</Canal>
         <!--Optional: MPH = DEUDA HOGAR MPM= DEUDA MOVIL-->
         <UnidadNegocio>MPH</UnidadNegocio>
        
      </ws:ConsolidaDeudaRut>
   </soapenv:Body>
</soapenv:Envelope>
```

### 6.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.8.2.1.- Respuesta de error

```xml
<?xml version="1.0" encoding="UTF-8"?>
<SOAP-ENV:Envelope xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ns1="http://ws.mundo.accolm.com/">
    <SOAP-ENV:Body>
        <ns1:ConsolidaDeudaRutResponse>
            <Resultados>
                <EstadoResultado>
                    <Codigo>3000</Codigo>
                    <Descripcion>Sin deuda</Descripcion>
                    <Observaciones>El cliente existe pero no tiene deuda</Observaciones>
                </EstadoResultado>
                <DatosResultado/>
            </Resultados>
        </ns1:ConsolidaDeudaRutResponse>
    </SOAP-ENV:Body>
</SOAP-ENV:Envelope>
```
  
#### 6.8.2.2.- Respuesta de éxito

```xml
<?xml version="1.0" encoding="UTF-8"?>
<SOAP-ENV:Envelope xmlns:SOAP-ENV="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ns1="http://ws.mundo.accolm.com/">
    <SOAP-ENV:Body>
        <ns1:ConsolidaDeudaRutResponse>
            <Resultados>
                <EstadoResultado>
                    <Codigo>0</Codigo>
                    <Descripcion>Exito</Descripcion>
                    <Observaciones>Codigo devuelto en el caso de Exito</Observaciones>
                </EstadoResultado>
                <DatosResultado>
                    <IDTransaccion>3f98c1cf-3933-4ec5-b295-ba06849b9d73</IDTransaccion>
                    <IDCliente>189503253</IDCliente>
                    <NombreCliente>Zapata Castellon Guillermo Antonio</NombreCliente>
                    <DeudaVencida>0</DeudaVencida>
                    <FechaVencida></FechaVencida>
                    <DeudaPorVencer>1934</DeudaPorVencer>
                    <FechaPorVencer>10/09/2021</FechaPorVencer>
                    <DocumentoPorVencer>18479344</DocumentoPorVencer>
                    <DeudaTotal>1934</DeudaTotal>
                    <TimeStamp>20210901181223955</TimeStamp>
                </DatosResultado>
            </Resultados>
        </ns1:ConsolidaDeudaRutResponse>
    </SOAP-ENV:Body>
</SOAP-ENV:Envelope>
```

## 6.9.- Procesar Pago
Método que permite procesar pago de un cliente.

Los parámetros que recibe son los siguientes:

Ruta : POST `/MundoWebpay/services/servicioDeuda`

**Parámetros de entrada:**

| Campo          | Formato        |     Requerido    |          Descripción      |
|:--------------:|:--------------:|:----------------:|--------------------------:|
| Canal          |                |                  | Tipo de canal             |
| IdTransaccion  |                | Si               | ID de la transacción      |
| IdCliente      | NNNNNNNNC      | Si               | Rut del cliente           |
| Monto          |                | Si               | Monto del pago            |
| Fecha          |                | Si               | Fecha del pagoo           |
| UnidadNegocio  |                |                  | Unidad de negocio         |
| CodigoRespuesta|                |                  | Código de respuesta       |
| Token          |                |                  | Token                     |
| OrdenCompra    |                |                  | Orden de compra           |
| CodAutorizacion|                |                  | Código de autorización    |
| TipoPago       |                |                  | Tipo de pago              |
| NumTarjeta     |                |                  | Número de tarjeta         |
| NumeroCuotas   |                |                  | Número Cuotas             |
| VCI            |                |                  | VCI                       |
| FechaContable  |                |                  | Fecha contable            |
| FechaTransaccion|               |                  | Fecha de transacción      |
| TipoCliente    |                |                  | Tipo de cliente           |

### 6.9.1.- Ejemplo de llamada

Ejemplo: XML 

```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:ws="http://ws.mundo.accolm.com/">
   <soapenv:Header/>
   <soapenv:Body>
      <ws:ProcesaPago>
         <!--Optional:-->
         <Canal>BS</Canal>
         <IdTransaccion>b9e0ee94-1cdf-45f7-9c82-61c0a4d53ff5</IdTransaccion>
         <IdCliente>135982547</IdCliente>
         <Monto>12572</Monto>
         <Fecha>20201105085801000</Fecha>
         <!--Optional:-->
         <UnidadNegocio>MPH</UnidadNegocio>
         <!--Optional:-->
         <CodigoRespuesta></CodigoRespuesta>
         <!--Optional:-->
         <Token></Token>
         <!--Optional:-->
         <OrdenCompra></OrdenCompra>
         <!--Optional:-->
         <CodAutorizacion></CodAutorizacion>
         <!--Optional:-->
         <TipoPago></TipoPago>
         <!--Optional:-->
         <NumTarjeta></NumTarjeta>
         <!--Optional:-->
         <NumeroCuotas></NumeroCuotas>
         <!--Optional:-->
         <VCI>?</VCI>
         <!--Optional:-->
         <FechaContable>?</FechaContable>
         <!--Optional:-->
         <FechaTransaccion>?</FechaTransaccion>
         <!--Optional:-->
         <TipoCliente>0</TipoCliente>

      </ws:ProcesaPago>
   </soapenv:Body>
</soapenv:Envelope>
```

### 6.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.9.2.1.- Respuesta de error

```xml
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
   <soap:Body>
      <ns2:ProcesaPagoResponse xmlns:ns2="http://ws.mundo.accolm.com/">
         <Resultados>
            <EstadoResultado>
               <Codigo>3100</Codigo>
               <Descripcion>Numero de Transacci�n Incorrecta</Descripcion>
               <Observaciones>El n�mero de transacci�n informado al procesar un pago es incorrecto</Observaciones>
            </EstadoResultado>
         </Resultados>
      </ns2:ProcesaPagoResponse>
   </soap:Body>
</soap:Envelope>
```
  
#### 6.9.2.2.- Respuesta de éxito

```xml
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/">
   <soap:Body>
      <ns2:ProcesaPagoResponse xmlns:ns2="http://ws.mundo.accolm.com/">
         <Resultados>
            <EstadoResultado>
               <Codigo>0</Codigo>
               <Descripcion>Respuesta de existo</Descripcion>
               <Observaciones>Respuesta de exito</Observaciones>
            </EstadoResultado>
         </Resultados>
      </ns2:ProcesaPagoResponse>
   </soap:Body>
</soap:Envelope>
```