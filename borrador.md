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
|   macromotivo                   | array[object]| Array con los macromotivos (Sin uso en esta ruta)|
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