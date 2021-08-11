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
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Tipos de Soluciones](#12--tipos-de-soluciones)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
    - [1.3.- Tipos de Motivos de Reclamos](#13--tipos-de-motivos-de-reclamos)
        - [1.3.1.- Ejemplo de llamada](#131--ejemplo-de-llamada)
        - [1.3.2.- Respuesta de Salida](#132--respuesta-de-salida)
            - [1.3.2.1- Respuesta de error](#1321--respuesta-de-error)
            - [1.3.2.2- Respuesta de éxito](#1322--respuesta-de-éxito)
    - [1.4.- Tipos de Notificación](#14--tipos-de-notificación)
        - [1.4.1.- Ejemplo de llamada](#141--ejemplo-de-llamada)
        - [1.4.2.- Respuesta de Salida](#142--respuesta-de-salida)
            - [1.4.2.1- Respuesta de error](#1421--respuesta-de-error)
            - [1.4.2.2- Respuesta de éxito](#1422--respuesta-de-éxito)
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
    - [1.7.- Motivo](#17--motivo)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de error](#1721--respuesta-de-error)
            - [1.7.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
    - [1.8.- Tipo Registro](#18--tipo-registro)
        - [1.8.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
        - [1.8.2.- Respuesta de Salida](#182--respuesta-de-salida)
            - [1.8.2.1- Respuesta de error](#1821--respuesta-de-error)
            - [1.8.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
    - [1.9.- Submotivo](#19--submotivo)
        - [1.9.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
        - [1.9.2.- Respuesta de Salida](#192--respuesta-de-salida)
            - [1.9.2.1- Respuesta de error](#1921--respuesta-de-error)
            - [1.9.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
    - [1.10.- Reclamo](#110--reclamo)
        - [1.10.1.- Ejemplo de llamada](#1101--ejemplo-de-llamada)
        - [1.10.2.- Respuesta de Salida](#1102--respuesta-de-salida)
            - [1.10.2.1- Respuesta de error](#11021--respuesta-de-error)
            - [1.10.2.2- Respuesta de éxito](#11022--respuesta-de-éxito)
    - [1.11.- Estado Reclamo](#111--estado-reclamo)
        - [1.11.1.- Ejemplo de llamada](#1111--ejemplo-de-llamada)
        - [1.11.2.- Respuesta de Salida](#1112--respuesta-de-salida)
            - [1.11.2.1- Respuesta de error](#11121--respuesta-de-error)
            - [1.11.2.2- Respuesta de éxito](#11122--respuesta-de-éxito)
    - [1.12.- Ingresar Reclamo Ejecutivo](#112--ingresar-reclamo-ejecutivo)
        - [1.12.1.- Ejemplo de llamada](#1121--ejemplo-de-llamada)
        - [1.12.2.- Respuesta de Salida](#1122--respuesta-de-salida)
            - [1.12.2.1- Respuesta de error](#11221--respuesta-de-error)
            - [1.12.2.2- Respuesta de éxito](#11222--respuesta-de-éxito)
    - [1.13.- Gráfico Reclamo Total Comuna](#113--gráfico-reclamo-total-comuna)
        - [1.13.1.- Ejemplo de llamada](#1131--ejemplo-de-llamada)
        - [1.13.2.- Respuesta de Salida](#1132--respuesta-de-salida)
            - [1.13.2.1- Respuesta de error](#11321--respuesta-de-error)
            - [1.13.2.2- Respuesta de éxito](#11322--respuesta-de-éxito)
    - [1.14.- Gráfico Reclamo por Comuna](#114--gráfico-reclamo-por-comuna)
        - [1.14.1.- Ejemplo de llamada](#1141--ejemplo-de-llamada)
        - [1.14.2.- Respuesta de Salida](#1142--respuesta-de-salida)
            - [1.14.2.1- Respuesta de error](#11421--respuesta-de-error)
            - [1.14.2.2- Respuesta de éxito](#11422--respuesta-de-éxito)
    - [1.15.- Gráfico Reclamo por Fecha](#115--gráfico-reclamo-por-fecha)
        - [1.15.1.- Ejemplo de llamada](#1151--ejemplo-de-llamada)
        - [1.15.2.- Respuesta de Salida](#1152--respuesta-de-salida)
            - [1.15.2.1- Respuesta de error](#11521--respuesta-de-error)
            - [1.15.2.2- Respuesta de éxito](#11522--respuesta-de-éxito)
    - [1.16.- Gráfico Reclamo por Servicio](#116--gráfico-reclamo-por-servicio)
        - [1.16.1.- Ejemplo de llamada](#1161--ejemplo-de-llamada)
        - [1.16.2.- Respuesta de Salida](#1162--respuesta-de-salida)
            - [1.16.2.1- Respuesta de error](#11621--respuesta-de-error)
            - [1.16.2.2- Respuesta de éxito](#11622--respuesta-de-éxito)
    - [1.17.- Tipo Conformidad](#117--tipo-conformidad)
        - [1.17.1.- Ejemplo de llamada](#1171--ejemplo-de-llamada)
        - [1.17.2.- Respuesta de Salida](#1172--respuesta-de-salida)
            - [1.17.2.1- Respuesta de error](#11721--respuesta-de-error)
            - [1.17.2.2- Respuesta de éxito](#11722--respuesta-de-éxito)
    - [1.18.- Macromotivo](#118--macromotivo)
        - [1.18.1.- Ejemplo de llamada](#1181--ejemplo-de-llamada)
        - [1.18.2.- Respuesta de Salida](#1182--respuesta-de-salida)
            - [1.18.2.1- Respuesta de error](#11821--respuesta-de-error)
            - [1.18.2.2- Respuesta de éxito](#11822--respuesta-de-éxito)
    - [1.19.- Editar Reclamo](#119--editar-reclamo)
        - [1.19.1.- Ejemplo de llamada](#1191--ejemplo-de-llamada)
        - [1.19.2.- Respuesta de Salida](#1192--respuesta-de-salida)
            - [1.19.2.1- Respuesta de error](#11921--respuesta-de-error)
            - [1.19.2.2- Respuesta de éxito](#11922--respuesta-de-éxito)
    - [1.20.- Exportar Reclamo](#120--exportar-reclamo)
        - [1.20.1.- Ejemplo de llamada](#1201--ejemplo-de-llamada)
        - [1.20.2.- Respuesta de Salida](#1202--respuesta-de-salida)
            - [1.20.2.1- Respuesta de error](#12021--respuesta-de-error)
            - [1.20.2.2- Respuesta de éxito](#12022--respuesta-de-éxito)
    - [1.21.- Tipo Teléfono](#121--tipo-teléfono)
        - [1.21.1.- Ejemplo de llamada](#1211--ejemplo-de-llamada)
        - [1.21.2.- Respuesta de Salida](#1212--respuesta-de-salida)
            - [1.21.2.1- Respuesta de error](#12121--respuesta-de-error)
            - [1.21.2.2- Respuesta de éxito](#12122--respuesta-de-éxito)
    - [1.22.- Contingencia Nodos](#122--contingencia-nodos)
        - [1.22.1.- Ejemplo de llamada](#1221--ejemplo-de-llamada)
        - [1.22.2.- Respuesta de Salida](#1222--respuesta-de-salida)
            - [1.22.2.1- Respuesta de error](#12221--respuesta-de-error)
            - [1.22.2.2- Respuesta de éxito](#12222--respuesta-de-éxito)
    - [1.23.- Consulta Cliente](#123--consulta-cliente)
        - [1.23.1.- Ejemplo de llamada](#1231--ejemplo-de-llamada)
        - [1.23.2.- Respuesta de Salida](#1232--respuesta-de-salida)
            - [1.23.2.1- Respuesta de error](#12321--respuesta-de-error)
            - [1.23.2.2- Respuesta de éxito](#12322--respuesta-de-éxito)
    - [1.24.- Consulta Cliente IVR](#124--consulta-cliente-ivr)
        - [1.24.1.- Ejemplo de llamada](#1241--ejemplo-de-llamada)
        - [1.24.2.- Respuesta de Salida](#1242--respuesta-de-salida)
            - [1.24.2.1- Respuesta de error](#12421--respuesta-de-error)
            - [1.24.2.2- Respuesta de éxito](#12422--respuesta-de-éxito)
    - [1.25.- divGeoClientePrincipal](#125--divGeoClientePrincipal)
        - [1.25.1.- Ejemplo de llamada](#1251--ejemplo-de-llamada)
        - [1.25.2.- Respuesta de Salida](#1252--respuesta-de-salida)
            - [1.25.2.1- Respuesta de error](#12521--respuesta-de-error)
            - [1.25.2.2- Respuesta de éxito](#12522--respuesta-de-éxito)
    - [1.26.- Comunas](#126--comunas)
        - [1.26.1.- Ejemplo de llamada](#1261--ejemplo-de-llamada)
        - [1.26.2.- Respuesta de Salida](#1262--respuesta-de-salida)
            - [1.26.2.1- Respuesta de error](#12621--respuesta-de-error)
            - [1.26.2.2- Respuesta de éxito](#12622--respuesta-de-éxito)
    - [1.27.- Regiones](#127--regiones)
        - [1.27.1.- Ejemplo de llamada](#1271--ejemplo-de-llamada)
        - [1.27.2.- Respuesta de Salida](#1272--respuesta-de-salida)
            - [1.27.2.1- Respuesta de error](#12721--respuesta-de-error)
            - [1.27.2.2- Respuesta de éxito](#12722--respuesta-de-éxito)
    - [1.28.- Datos Cliente Tipo Servicio](#128--datos-cliente-tipo-servicio)
        - [1.28.1.- Ejemplo de llamada](#1281--ejemplo-de-llamada)
        - [1.28.2.- Respuesta de Salida](#1282--respuesta-de-salida)
            - [1.28.2.1- Respuesta de error](#12821--respuesta-de-error)
            - [1.28.2.2- Respuesta de éxito](#12822--respuesta-de-éxito)
    - [1.29.- Ingresar Comentario Reclamo](#129--ingresar-comentario-reclamo)
        - [1.29.1.- Ejemplo de llamada](#1291--ejemplo-de-llamada)
        - [1.29.2.- Respuesta de Salida](#1292--respuesta-de-salida)
            - [1.29.2.1- Respuesta de error](#12921--respuesta-de-error)
            - [1.29.2.2- Respuesta de éxito](#12922--respuesta-de-éxito)
    - [1.30.- Subcategorías Internas](#130--subcategorias-internas)
        - [1.30.1.- Ejemplo de llamada](#1301--ejemplo-de-llamada)
        - [1.30.2.- Respuesta de Salida](#1302--respuesta-de-salida)
            - [1.30.2.1- Respuesta de error](#13021--respuesta-de-error)
            - [1.30.2.2- Respuesta de éxito](#13022--respuesta-de-éxito)
    - [1.31.- OficioReclamo](#131--oficioReclamo)
        - [1.31.1.- Ejemplo de llamada](#1311--ejemplo-de-llamada)
        - [1.31.2.- Respuesta de Salida](#1312--respuesta-de-salida)
            - [1.31.2.1- Respuesta de error](#13121--respuesta-de-error)
            - [1.31.2.2- Respuesta de éxito](#13122--respuesta-de-éxito)
    - [1.32.- Resolución Reclamo](#132--resolución-reclamo)
        - [1.32.1.- Ejemplo de llamada](#1321--ejemplo-de-llamada)
        - [1.32.2.- Respuesta de Salida](#1322--respuesta-de-salida)
            - [1.32.2.1- Respuesta de error](#13221--respuesta-de-error)
            - [1.32.2.2- Respuesta de éxito](#13222--respuesta-de-éxito)
  - [2.- Sucursal](#1--Sucursal)
    - [2.1.- Ingresar Reclamo](#21--ingresar-reclamo)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Tipo Reclamo](#22--tipo-reclamo)
        - [2.2.1.- Ejemplo de llamada](#2231--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#2232--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#22321--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#22322--respuesta-de-éxito)
    - [2.3.- Tipo Notificación](#23--tipo-notificación)
        - [2.3.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
        - [2.3.2.- Respuesta de Salida](#232--respuesta-de-salida)
            - [2.3.2.1- Respuesta de error](#2321--respuesta-de-error)
            - [2.3.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
    - [2.4.- Servicio](#24--servicio)
        - [2.4.1.- Ejemplo de llamada](#241--ejemplo-de-llamada)
        - [2.4.2.- Respuesta de Salida](#242--respuesta-de-salida)
            - [2.4.2.1- Respuesta de error](#2421--respuesta-de-error)
            - [2.4.2.2- Respuesta de éxito](#2422--respuesta-de-éxito)
    - [2.5.- Tipo Servicio](#25--tipo-servicio)
        - [2.5.1.- Ejemplo de llamada](#251--ejemplo-de-llamada)
        - [2.5.2.- Respuesta de Salida](#252--respuesta-de-salida)
            - [2.5.2.1- Respuesta de error](#2521--respuesta-de-error)
            - [2.5.2.2- Respuesta de éxito](#2522--respuesta-de-éxito)
    - [2.6.- Motivo](#26--motivo)
        - [2.6.1.- Ejemplo de llamada](#261--ejemplo-de-llamada)
        - [2.6.2.- Respuesta de Salida](#262--respuesta-de-salida)
            - [2.6.2.1- Respuesta de error](#2621--respuesta-de-error)
            - [2.6.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
    - [2.7.- Submotivo](#27--submotivo)
        - [2.7.1.- Ejemplo de llamada](#271--ejemplo-de-llamada)
        - [2.7.2.- Respuesta de Salida](#272--respuesta-de-salida)
            - [2.7.2.1- Respuesta de error](#2721--respuesta-de-error)
            - [2.7.2.2- Respuesta de éxito](#2722--respuesta-de-éxito)
    - [2.8.- Reclamo Cliente](#28--reclamo-cliente)
        - [2.8.1.- Ejemplo de llamada](#281--ejemplo-de-llamada)
        - [2.8.2.- Respuesta de Salida](#282--respuesta-de-salida)
            - [2.8.2.1- Respuesta de error](#2821--respuesta-de-error)
            - [2.8.2.2- Respuesta de éxito](#2822--respuesta-de-éxito)
    - [2.9.- Tipo Teléfono](#29--tipo-teléfono)
        - [2.9.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
        - [2.9.2.- Respuesta de Salida](#292--respuesta-de-salida)
            - [2.9.2.1- Respuesta de error](#2921--respuesta-de-error)
            - [2.9.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
    - [2.10.- Contingencia Nodos](#210--contingencia-nodos)
        - [2.10.1.- Ejemplo de llamada](#2101--ejemplo-de-llamada)
        - [2.10.2.- Respuesta de Salida](#2102--respuesta-de-salida)
            - [2.10.2.1- Respuesta de error](#21021--respuesta-de-error)
            - [2.10.2.2- Respuesta de éxito](#21022--respuesta-de-éxito)
    - [2.11.- Consulta Cliente IVR](#211--consulta-cliente-ivr)
        - [2.11.1.- Ejemplo de llamada](#2111--ejemplo-de-llamada)
        - [2.11.2.- Respuesta de Salida](#2112--respuesta-de-salida)
            - [2.11.2.1- Respuesta de error](#21121--respuesta-de-error)
            - [2.11.2.2- Respuesta de éxito](#21122--respuesta-de-éxito)
    - [2.12.- divGeoClientePrincipal](#212--divGeoClientePrincipal)
        - [2.12.1.- Ejemplo de llamada](#2121--ejemplo-de-llamada)
        - [2.12.2.- Respuesta de Salida](#2122--respuesta-de-salida)
            - [2.12.2.1- Respuesta de error](#21221--respuesta-de-error)
            - [2.12.2.2- Respuesta de éxito](#21222--respuesta-de-éxito)
    - [2.13.- Datos Clientes Tipo Servicio](#213--datos-clientes-tipo-servicio)
        - [2.13.1.- Ejemplo de llamada](#2131--ejemplo-de-llamada)
        - [2.13.2.- Respuesta de Salida](#2132--respuesta-de-salida)
            - [2.13.2.1- Respuesta de error](#21321--respuesta-de-error)
            - [2.13.2.2- Respuesta de éxito](#21322--respuesta-de-éxito)
  - [3.- IVR](#3--ivr)
    - [3.1.- Informe Reclamos](#31--informe-reclamos)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3122--respuesta-de-éxito)
    - [3.2.- Finalizar](#32--finalizar)
        - [3.2.1.- Ejemplo de llamada](#321--ejemplo-de-llamada)
        - [3.2.2.- Respuesta de Salida](#322--respuesta-de-salida)
            - [3.2.2.1- Respuesta de error](#3221--respuesta-de-error)
            - [3.2.2.2- Respuesta de éxito](#3222--respuesta-de-éxito)
    - [3.3.- Grabar Registro](#33--grabar-registro)
        - [3.3.1.- Ejemplo de llamada](#331--ejemplo-de-llamada)
        - [3.3.2.- Respuesta de Salida](#332--respuesta-de-salida)
            - [3.3.2.1- Respuesta de error](#3321--respuesta-de-error)
            - [3.3.2.2- Respuesta de éxito](#3322--respuesta-de-éxito)
    - [3.4.- Ingresar](#34--ingresar)
        - [3.4.1.- Ejemplo de llamada](#341--ejemplo-de-llamada)
        - [3.4.2.- Respuesta de Salida](#342--respuesta-de-salida)
            - [3.4.2.1- Respuesta de error](#3421--respuesta-de-error)
            - [3.4.2.2- Respuesta de éxito](#3422--respuesta-de-éxito)
    - [3.5.- Ingresar Reclamo](#35--ingresar-reclamo)
        - [3.5.1.- Ejemplo de llamada](#351--ejemplo-de-llamada)
        - [3.5.2.- Respuesta de Salida](#352--respuesta-de-salida)
            - [3.5.2.1- Respuesta de error](#3521--respuesta-de-error)
            - [3.5.2.2- Respuesta de éxito](#3522--respuesta-de-éxito)
    - [3.6.- Upd Contingencia](#36--upd-contingencia)
        - [3.6.1.- Ejemplo de llamada](#361--ejemplo-de-llamada)
        - [3.6.2.- Respuesta de Salida](#362--respuesta-de-salida)
            - [3.6.2.1- Respuesta de error](#3621--respuesta-de-error)
            - [3.6.2.2- Respuesta de éxito](#3622--respuesta-de-éxito)
    - [3.7.- Upd Estado](#37--upd-estado)
        - [3.7.1.- Ejemplo de llamada](#371--ejemplo-de-llamada)
        - [3.7.2.- Respuesta de Salida](#372--respuesta-de-salida)
            - [3.7.2.1- Respuesta de error](#3721--respuesta-de-error)
            - [3.7.2.2- Respuesta de éxito](#3722--respuesta-de-éxito)
    - [3.8.- Upd Fono](#38--upd-fono)
        - [3.8.1.- Ejemplo de llamada](#381--ejemplo-de-llamada)
        - [3.8.2.- Respuesta de Salida](#382--respuesta-de-salida)
            - [3.8.2.1- Respuesta de error](#3821--respuesta-de-error)
            - [3.8.2.2- Respuesta de éxito](#3822--respuesta-de-éxito)
    - [3.9.- Upd Fono Reclamo](#39--upd-fono-reclamo)
        - [3.9.1.- Ejemplo de llamada](#391--ejemplo-de-llamada)
        - [3.9.2.- Respuesta de Salida](#392--respuesta-de-salida)
            - [3.9.2.1- Respuesta de error](#3921--respuesta-de-error)
            - [3.9.2.2- Respuesta de éxito](#3922--respuesta-de-éxito)
    - [3.10.- Upd Motivo](#310--upd-motivo)
        - [3.10.1.- Ejemplo de llamada](#3101--ejemplo-de-llamada)
        - [3.10.2.- Respuesta de Salida](#3102--respuesta-de-salida)
            - [3.10.2.1- Respuesta de error](#31021--respuesta-de-error)
            - [3.10.2.2- Respuesta de éxito](#31022--respuesta-de-éxito)
    - [3.11.- Upd Rut](#311--upd-rut)
        - [3.11.1.- Ejemplo de llamada](#3111--ejemplo-de-llamada)
        - [3.11.2.- Respuesta de Salida](#3112--respuesta-de-salida)
            - [3.11.2.1- Respuesta de error](#31121--respuesta-de-error)
            - [3.11.2.2- Respuesta de éxito](#31122--respuesta-de-éxito)
    - [3.12.- Upd Rut Solicitante](#312--upd-rut-solicitante)
        - [3.12.1.- Ejemplo de llamada](#3121--ejemplo-de-llamada)
        - [3.12.2.- Respuesta de Salida](#3122--respuesta-de-salida)
            - [3.12.2.1- Respuesta de error](#31221--respuesta-de-error)
            - [3.12.2.2- Respuesta de éxito](#31222--respuesta-de-éxito)
    - [3.13.- Upd Servicio](#313--upd-servicio)
        - [3.13.1.- Ejemplo de llamada](#3131--ejemplo-de-llamada)
        - [3.13.2.- Respuesta de Salida](#3132--respuesta-de-salida)
            - [3.13.2.1- Respuesta de error](#31321--respuesta-de-error)
            - [3.13.2.2- Respuesta de éxito](#31322--respuesta-de-éxito)
    - [3.14.- Upd Submotivo](#314--upd-submotivo)
        - [3.14.1.- Ejemplo de llamada](#3141--ejemplo-de-llamada)
        - [3.14.2.- Respuesta de Salida](#3142--respuesta-de-salida)
            - [3.14.2.1- Respuesta de error](#31421--respuesta-de-error)
            - [3.14.2.2- Respuesta de éxito](#31422--respuesta-de-éxito)
    - [3.15.- Upd Tipo Notificación](#315--upd-tipo-notificación)
        - [3.15.1.- Ejemplo de llamada](#3151--ejemplo-de-llamada)
        - [3.15.2.- Respuesta de Salida](#3152--respuesta-de-salida)
            - [3.15.2.1- Respuesta de error](#31521--respuesta-de-error)
            - [3.15.2.2- Respuesta de éxito](#31522--respuesta-de-éxito)
    - [3.16.- Upd Tipo Teléfono](#316--upd-tipo-teléfono)
        - [3.16.1.- Ejemplo de llamada](#3161--ejemplo-de-llamada)
        - [3.16.2.- Respuesta de Salida](#3162--respuesta-de-salida)
            - [3.16.2.1- Respuesta de error](#31621--respuesta-de-error)
            - [3.16.2.2- Respuesta de éxito](#31622--respuesta-de-éxito)
    - [3.17.- Upd Tipo Servicio](#317--upd-tipo-servicio)
        - [3.17.1.- Ejemplo de llamada](#3171--ejemplo-de-llamada)
        - [3.17.2.- Respuesta de Salida](#3172--respuesta-de-salida)
            - [3.17.2.1- Respuesta de error](#31721--respuesta-de-error)
            - [3.17.2.2- Respuesta de éxito](#31722--respuesta-de-éxito)
    - [3.18.- Update Celular Reclamado](#318--update-celular-reclamo)
        - [3.18.1.- Ejemplo de llamada](#3181--ejemplo-de-llamada)
        - [3.18.2.- Respuesta de Salida](#3182--respuesta-de-salida)
            - [3.18.2.1- Respuesta de error](#31821--respuesta-de-error)
            - [3.18.2.2- Respuesta de éxito](#31822--respuesta-de-éxito)
    - [3.19.- Update Cliente es Reclamante](#319--update-cliente-es-reclamante)
        - [3.19.1.- Ejemplo de llamada](#3191--ejemplo-de-llamada)
        - [3.19.2.- Respuesta de Salida](#3192--respuesta-de-salida)
            - [3.19.2.1- Respuesta de error](#31921--respuesta-de-error)
            - [3.19.2.2- Respuesta de éxito](#31922--respuesta-de-éxito)
    - [3.20.- Update Teléfono Reclamado](#320--update-teléfono-reclamado)
        - [3.20.1.- Ejemplo de llamada](#3201--ejemplo-de-llamada)
        - [3.20.2.- Respuesta de Salida](#3202--respuesta-de-salida)
            - [3.20.2.1- Respuesta de error](#32021--respuesta-de-error)
            - [3.20.2.2- Respuesta de éxito](#32022--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Reclamos
## 1.1.- Tipos de Reclamos
Método que retorna lista de tipos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-reclamo`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.1.2.2.- Respuesta de éxito

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

## 1.2.- Tipos de Soluciones
Método que retorna lista de tipos de soluciones.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-solucion`

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

## 1.3.- Tipos de Motivos de Reclamos
Método que retorna lista de motivos por el que se acoge o no el reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/motivo-acoge`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.3.2.2.- Respuesta de éxito

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

## 1.4.- Tipos de Notificación
Método que retorna los tipos de medios de notificación para el cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-notificacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.4.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.4.2.2.- Respuesta de éxito

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

## 1.5.- Tipos de Servicios
Método que retorna lista de tipos de servicios.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.5.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.5.2.2.- Respuesta de éxito

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

## 1.6.- Tipos de Servicios 2
Método que retorna lista de tipos de servicios.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tiposervicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.6.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.6.2.2.- Respuesta de éxito

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

## 1.7.- Motivos
Método que retorna lista de motivos de reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.7.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.7.2.2.- Respuesta de éxito

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

## 1.8.- Tipos de Registro
Método que retorna lista de tipos de registro de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-registro`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.8.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.8.2.2.- Respuesta de éxito

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

## 1.9.- Submotivos
Método que retorna lista de submotivos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/submotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.9.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.9.2.2.- Respuesta de éxito

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

## 1.10.- Reclamos
Método que retorna detalle de reclamo o lista de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/reclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.10.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.10.2.2.- Respuesta de éxito

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

## 1.11.- Estado de Reclamo
Método que retorna lisa de estaos de reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/estado-reclamos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.11.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.11.2.2.- Respuesta de éxito

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

## 1.12.- Ingresar Reclamos por Ejecutivos
Método que permite ingresar reclamos en el portal por ejecutivos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/reclamo-ejecutivo-ingresar`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.12.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.12.2.2.- Respuesta de éxito

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

## 1.13.- Total Reclamos Comunas
Método que retorna los datos para el reporte gráfico de reclamos de todas las comunas.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-total-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.13.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.13.2.2.- Respuesta de éxito

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

## 1.14.- Reclamos por Comuna
Método que retorna los datos para el reporte gráfico de reclamos por comuna.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.14.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.14.2.2.- Respuesta de éxito

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
    
## 1.15.- Reclamos por Fecha
Método que retorna los datos para el reporte gráfico de reclamos por rango de fecha.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-fecha`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.15.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.15.2.2.- Respuesta de éxito

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

## 1.16.- Reclamos por Motivo y Servicio
Método que retorna los datos para el reporte gráfico de reclamos por motivos y servicios.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-servicio-motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.16.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.16.2.2.- Respuesta de éxito

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
    
## 1.17.- Tipos de Conformidad
Método que retorna el listado de tipos de conformidad del reclamo.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-conformidad`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.17.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.17.2.2.- Respuesta de éxito

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

## 1.18.- Macromotivos
Método que retorna el listado de macromotivos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/macromotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.18.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.18.2.2.- Respuesta de éxito

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

## 1.19.- Editar Reclamo
Método que permite editar un reclamo.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/reclamo-editar`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.19.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.19.2.2.- Respuesta de éxito

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

## 1.20.- Exportar Reclamos
Método que permite generar un reporte de datos de reclamos para exportar a excel.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/informes/reclamo-export`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.20.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.20.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.20.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.20.2.2.- Respuesta de éxito

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

## 1.21.- Tipos de Teléfonos
Método que retorna lista de tipos de teléfonos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/tipo-telefono`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.21.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.21.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.21.2.2.- Respuesta de éxito

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

## 1.22.- Contingencias Cliente
Método que retorna las contingencias que tiene el cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/contingenciasNodos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.22.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.22.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.22.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.22.2.2.- Respuesta de éxito

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

## 1.23.- Datos del Cliente
Método que retorna los datos del cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/consultaCliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.23.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.23.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.23.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.23.2.2.- Respuesta de éxito

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

## 1.24.- Datos del Cliente IVR
Método que retorna los datos del cliente IVR.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/consultaClienteIVR`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.24.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.24.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.24.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.24.2.2.- Respuesta de éxito

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

## 1.25.- Datos Domicilio de Cliente
Método que retorna los datos del domicilio del cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/divGeoClientePrincipal`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.25.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.25.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.25.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.25.2.2.- Respuesta de éxito

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

## 1.26.- Lista de Comunas
Método que retorna lista de comunas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/comunas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.26.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.26.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.26.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.26.2.2.- Respuesta de éxito

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

## 1.27.- Lista de Regiones
Método que retorna lista de regiones.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/regiones`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.27.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.27.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.27.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.27.2.2.- Respuesta de éxito

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

## 1.28.- Servicios Contratados por Cliente
Método que retorna los servicios contratados por el cliente.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/datos-cliente-tipo-servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.28.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.28.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.28.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.28.2.2.- Respuesta de éxito

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

## 1.29.- Ingresar Comentario de Reclamo
Método que permite ingresar comentios de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/ingresar-comentario-reclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.29.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.29.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.29.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.29.2.2.- Respuesta de éxito

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

## 1.30.- Lista Subcategorías Internas
Método que retorna lista de subcategorías internas.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/subcategorias-internas`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.30.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.30.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.30.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.30.2.2.- Respuesta de éxito

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

## 1.31.- Ingresar Oficio de Reclamo Subtel
SOAP service para ingreso de oficios de reclamos de subtel.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/subtel/OficioReclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.31.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.31.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.31.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.31.2.2.- Respuesta de éxito

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

## 1.32.- Ingresar Resolución de Reclamo Subtel
SOAP service para ingreso de resoluciones de reclamos de subtel.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/subtel/ResolucionReclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.32.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 1.32.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.32.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 1.32.2.2.- Respuesta de éxito

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

# 2.- Sucursal
## 2.1.- Ingresar Reclamos desde Sucursal
Método que permite el ingreso de reclamos de clientes desde la sucursal.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/reclamo-ingresar`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.1.2.2.- Respuesta de éxito

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

## 2.2.- Tipos de Reclamos.
Método que retorna lista de tipos de reclamos - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-reclamo`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.2.2.2.- Respuesta de éxito

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

## 2.3.- Tipos de Medios de Notificación
Método que retorna lista de tipos de medios de notificación - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-notificacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.3.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.3.2.2.- Respuesta de éxito

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

## 2.4.- Tipos de Servicios Contratados
Método que retorna lista de tipos de servicios contratados por el cliente (Móvil o Fijo) - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.4.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.4.2.2.- Respuesta de éxito

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

## 2.5.- Lista de Servicios Contratados
Método que retorna lista de servicios contratados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tiposervicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.5.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.5.2.2.- Respuesta de éxito

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

## 2.6.- Lista de Motivos de Reclamo
Método que retorna lista de motivos de reclamo - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.6.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.6.2.2.- Respuesta de éxito

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

## 2.7.- Lista de Submotivos de Reclamo
Método que retorna lista de submotivos de reclamo - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/submotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.7.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.7.2.2.- Respuesta de éxito

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

## 2.8.- Lista de Reclamos por Cliente
Método que retorna lista con detalle de reclamos realizados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/informes/reclamo-cliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.8.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.8.2.2.- Respuesta de éxito

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

## 2.9.- Tipos de Teléfono
Método que retorna lista de tipos de teléfono - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/listado/tipo-telefono`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.9.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.9.2.2.- Respuesta de éxito

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

## 2.10.- Contingencias Cliente
Método que retorna las posibles contingencias relacionadas al cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/contigenciasNodos`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.10.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.10.2.2.- Respuesta de éxito

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

## 2.11.- Consultar Datos de Cliente IVR
Método que permite consultar datos del cliente para IVR.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/consultaClienteIVR`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.11.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.11.2.2.- Respuesta de éxito

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

## 2.12.- Datos Domicilio de Cliente
Método que retorna los datos del domicilio del cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/divGeoClientePrincipal`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.12.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.12.2.2.- Respuesta de éxito

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

## 2.13.- Servicios Contratados por Cliente
Método que retorna los servicios contratados por el cliente - Sucursal virtual.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/sucursalVirtual/datos-cliente-tipo-servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 2.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 2.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.13.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 2.13.2.2.- Respuesta de éxito

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


# 3.- IVR
## 3.1.- Informe Reclamos
Método que retorna informe de datos de reclamos IVR por cliente para Mundo social.

Los parámetros que recibe son los siguientes:

Ruta : GET `/ivr/MundoSocial/informe-reclamos`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.1.2.2.- Respuesta de éxito

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

## 3.2.- Finalizar
BREVE DESCRIPCIÓN

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/finalizar`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.2.2.2.- Respuesta de éxito

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

## 3.3.- Grabar Registro
Método que permite grabar el registro inicial de IVR de forma temporal.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/grabarregistro`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.3.2.2.- Respuesta de éxito

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

## 3.4.- Ingresar
BREVE DESCRIPCIÓN

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/ingresar`

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
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.4.2.2.- Respuesta de éxito

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

## 3.5.- Ingresar Reclamo
BREVE DESCRIPCIÓN

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/ingresarReclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.5.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.5.2.2.- Respuesta de éxito

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

## 3.6.- Actualizar Contingencia
Método que permite actualizar contingencia del cliente en la tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-contingencia`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.6.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.6.2.2.- Respuesta de éxito

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

## 3.7.- Actualizar Estado de Reclamo
Método que permite actualizar estado del reclamo del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-estado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.7.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.7.2.2.- Respuesta de éxito

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

## 3.8.- Actualizar Teléfono de Cliente
Método que permite actualizar el teléfono del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-fono`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.8.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.8.2.2.- Respuesta de éxito

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

## 3.9.- Actualizar Teléfono Reclamado por Cliente
Método que permite actualizar el teléfono reclamado por el cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-fono-reclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.9.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.9.2.2.- Respuesta de éxito

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

## 3.10.- Actualizar Motivo de Reclamo
Método que permite actualizar el motivo del reclamo del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.10.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.10.2.2.- Respuesta de éxito

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

## 3.11.- Actualizar Rut de Cliente
Método que permite actualizar el rut del cliente en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-rut`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.11.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.11.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.11.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.11.2.2.- Respuesta de éxito

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

## 3.12.- Actualizar Rut de Cliente Solicitante
Método que permite actualizar el rut del cliente solicitante en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-rut-solicitante`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.12.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.12.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.12.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.12.2.2.- Respuesta de éxito

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

## 3.13.- Actualizar Servicio del Cliente
Método que permite actualizar el servicio del cliente solicitante en tabla temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-servicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.13.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.13.2.2.- Respuesta de éxito

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

## 3.14.- Actualizar Submotivo de Reclamo
Método que permite actualizar el submotivo de reclamo IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-submotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.14.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.14.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.14.2.2.- Respuesta de éxito

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


## 3.15.- Actualizar Medio de Notificación
Método que permite actualizar el medio de notificación del cliente en table temporal IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tipo-notificacion`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.15.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.15.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.15.2.2.- Respuesta de éxito

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

## 3.16.- Actualizar Tipo de Teléfono Reclamado
Método que permite actualizar el tipo de teléfono reclamado - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tipo-telefono`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.16.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.16.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.16.2.2.- Respuesta de éxito

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

## 3.17.- Actualizar Tipo de Servicio
Método que permite actualizar el tipo de servicio en tabla temporal - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/upd-tiposervicio`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.17.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.17.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.17.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.17.2.2.- Respuesta de éxito

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

## 3.18.- Actualizar Número Móvil Reclamado
Método que permite actualizar el número móvil reclamado - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-celular-reclamado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.18.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.18.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.18.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.18.2.2.- Respuesta de éxito

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

## 3.19.- Actualizar Cliente Reclamante
Método que permite actualizar en tabla temporal si el cliente es reclamante o no - IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-cliente-es-reclamante`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.19.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.19.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.19.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.19.2.2.- Respuesta de éxito

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

## 3.20.- Actualizar Teléfono Reclamado
Método que permite actualizar el teléfono reclamado en tabla temporal del IVR.

Los parámetros que recibe son los siguientes:

Ruta : POST `/ivr/update-telefono-reclamado`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| Nombre Campo | Tipo de dato | Especificar formato (opcional) | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 3.20.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "NOMBRE_CAMPO":"valor"
	}

### 3.20.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.20.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos relacionados"
        },
        "codigo": 404
	} 
  
#### 3.20.2.2.- Respuesta de éxito

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



