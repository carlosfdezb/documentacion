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
    - [1.7.- Motivos](#17--motivos)
        - [1.7.1.- Ejemplo de llamada](#171--ejemplo-de-llamada)
        - [1.7.2.- Respuesta de Salida](#172--respuesta-de-salida)
            - [1.7.2.1- Respuesta de error](#1721--respuesta-de-error)
            - [1.7.2.2- Respuesta de éxito](#1722--respuesta-de-éxito)
    - [1.8.- Tipos de Registro](#18--tipos-de-registro)
        - [1.8.1.- Ejemplo de llamada](#181--ejemplo-de-llamada)
        - [1.8.2.- Respuesta de Salida](#182--respuesta-de-salida)
            - [1.8.2.1- Respuesta de error](#1821--respuesta-de-error)
            - [1.8.2.2- Respuesta de éxito](#1822--respuesta-de-éxito)
    - [1.9.- Submotivos](#19--submotivos)
        - [1.9.1.- Ejemplo de llamada](#191--ejemplo-de-llamada)
        - [1.9.2.- Respuesta de Salida](#192--respuesta-de-salida)
            - [1.9.2.1- Respuesta de error](#1921--respuesta-de-error)
            - [1.9.2.2- Respuesta de éxito](#1922--respuesta-de-éxito)
    - [1.10.- Reclamos](#110--reclamos)
        - [1.10.1.- Ejemplo de llamada](#1101--ejemplo-de-llamada)
        - [1.10.2.- Respuesta de Salida](#1102--respuesta-de-salida)
            - [1.10.2.1- Respuesta de error](#11021--respuesta-de-error)
            - [1.10.2.2- Respuesta de éxito](#11022--respuesta-de-éxito)
    - [1.11.- Estado de Reclamo](#111--estado-de-reclamo)
        - [1.11.1.- Ejemplo de llamada](#1111--ejemplo-de-llamada)
        - [1.11.2.- Respuesta de Salida](#1112--respuesta-de-salida)
            - [1.11.2.1- Respuesta de error](#11121--respuesta-de-error)
            - [1.11.2.2- Respuesta de éxito](#11122--respuesta-de-éxito)
    - [1.12.- Ingresar Reclamos por Ejecutivos](#112--ingresar-reclamos-por-ejecutivos)
        - [1.12.1.- Ejemplo de llamada](#1121--ejemplo-de-llamada)
        - [1.12.2.- Respuesta de Salida](#1122--respuesta-de-salida)
            - [1.12.2.1- Respuesta de error](#11221--respuesta-de-error)
            - [1.12.2.2- Respuesta de éxito](#11222--respuesta-de-éxito)
    - [1.13.- Total Reclamos Comuna](#113--total-reclamos-comuna)
        - [1.13.1.- Ejemplo de llamada](#1131--ejemplo-de-llamada)
        - [1.13.2.- Respuesta de Salida](#1132--respuesta-de-salida)
            - [1.13.2.1- Respuesta de error](#11321--respuesta-de-error)
            - [1.13.2.2- Respuesta de éxito](#11322--respuesta-de-éxito)
    - [1.14.- Total Reclamos por Comuna](#114--total-reclamos-por-comuna)
        - [1.14.1.- Ejemplo de llamada](#1141--ejemplo-de-llamada)
        - [1.14.2.- Respuesta de Salida](#1142--respuesta-de-salida)
            - [1.14.2.1- Respuesta de error](#11421--respuesta-de-error)
            - [1.14.2.2- Respuesta de éxito](#11422--respuesta-de-éxito)
    - [1.15.- Reclamos por Fecha](#115--reclamos-por-fecha)
        - [1.15.1.- Ejemplo de llamada](#1151--ejemplo-de-llamada)
        - [1.15.2.- Respuesta de Salida](#1152--respuesta-de-salida)
            - [1.15.2.1- Respuesta de error](#11521--respuesta-de-error)
            - [1.15.2.2- Respuesta de éxito](#11522--respuesta-de-éxito)
    - [1.16.- Reclamos por Motivo y Servicio](#116--reclamos-por-motivo-y-servicio)
        - [1.16.1.- Ejemplo de llamada](#1161--ejemplo-de-llamada)
        - [1.16.2.- Respuesta de Salida](#1162--respuesta-de-salida)
            - [1.16.2.1- Respuesta de error](#11621--respuesta-de-error)
            - [1.16.2.2- Respuesta de éxito](#11622--respuesta-de-éxito)
    - [1.17.- Tipos de Conformidad](#117--tipos-de-conformidad)
        - [1.17.1.- Ejemplo de llamada](#1171--ejemplo-de-llamada)
        - [1.17.2.- Respuesta de Salida](#1172--respuesta-de-salida)
            - [1.17.2.1- Respuesta de error](#11721--respuesta-de-error)
            - [1.17.2.2- Respuesta de éxito](#11722--respuesta-de-éxito)
    - [1.18.- Macromotivos](#118--macromotivos)
        - [1.18.1.- Ejemplo de llamada](#1181--ejemplo-de-llamada)
        - [1.18.2.- Respuesta de Salida](#1182--respuesta-de-salida)
            - [1.18.2.1- Respuesta de error](#11821--respuesta-de-error)
            - [1.18.2.2- Respuesta de éxito](#11822--respuesta-de-éxito)
    - [1.19.- Editar Reclamo](#119--editar-reclamo)
        - [1.19.1.- Ejemplo de llamada](#1191--ejemplo-de-llamada)
        - [1.19.2.- Respuesta de Salida](#1192--respuesta-de-salida)
            - [1.19.2.1- Respuesta de error](#11921--respuesta-de-error)
            - [1.19.2.2- Respuesta de éxito](#11922--respuesta-de-éxito)
    - [1.20.- Exportar Reclamos](#120--exportar-reclamos)
        - [1.20.1.- Ejemplo de llamada](#1201--ejemplo-de-llamada)
        - [1.20.2.- Respuesta de Salida](#1202--respuesta-de-salida)
            - [1.20.2.1- Respuesta de error](#12021--respuesta-de-error)
            - [1.20.2.2- Respuesta de éxito](#12022--respuesta-de-éxito)
    - [1.21.- Tipos de Teléfonos](#121--tipos-de-teléfonos)
        - [1.21.1.- Ejemplo de llamada](#1211--ejemplo-de-llamada)
        - [1.21.2.- Respuesta de Salida](#1212--respuesta-de-salida)
            - [1.21.2.1- Respuesta de error](#12121--respuesta-de-error)
            - [1.21.2.2- Respuesta de éxito](#12122--respuesta-de-éxito)
    - [1.22.- Contingencias Cliente](#122--contingencias-cliente)
        - [1.22.1.- Ejemplo de llamada](#1221--ejemplo-de-llamada)
        - [1.22.2.- Respuesta de Salida](#1222--respuesta-de-salida)
            - [1.22.2.1- Respuesta de error](#12221--respuesta-de-error)
            - [1.22.2.2- Respuesta de éxito](#12222--respuesta-de-éxito)
    - [1.23.- Datos del Cliente](#123--datos-del-cliente)
        - [1.23.1.- Ejemplo de llamada](#1231--ejemplo-de-llamada)
        - [1.23.2.- Respuesta de Salida](#1232--respuesta-de-salida)
            - [1.23.2.1- Respuesta de error](#12321--respuesta-de-error)
            - [1.23.2.2- Respuesta de éxito](#12322--respuesta-de-éxito)
    - [1.24.- Datos del Cliente IVR](#124--datos-del-cliente-ivr)
        - [1.24.1.- Ejemplo de llamada](#1241--ejemplo-de-llamada)
        - [1.24.2.- Respuesta de Salida](#1242--respuesta-de-salida)
            - [1.24.2.1- Respuesta de error](#12421--respuesta-de-error)
            - [1.24.2.2- Respuesta de éxito](#12422--respuesta-de-éxito)
    - [1.25.- Datos Domicilio de Cliente](#125--datos-domicilio-de-cliente)
        - [1.25.1.- Ejemplo de llamada](#1251--ejemplo-de-llamada)
        - [1.25.2.- Respuesta de Salida](#1252--respuesta-de-salida)
            - [1.25.2.1- Respuesta de error](#12521--respuesta-de-error)
            - [1.25.2.2- Respuesta de éxito](#12522--respuesta-de-éxito)
    - [1.26.- Lista de Comunas](#126--lista-de-comunas)
        - [1.26.1.- Ejemplo de llamada](#1261--ejemplo-de-llamada)
        - [1.26.2.- Respuesta de Salida](#1262--respuesta-de-salida)
            - [1.26.2.1- Respuesta de error](#12621--respuesta-de-error)
            - [1.26.2.2- Respuesta de éxito](#12622--respuesta-de-éxito)
    - [1.27.- Lista de Regiones](#127--lista-de-regiones)
        - [1.27.1.- Ejemplo de llamada](#1271--ejemplo-de-llamada)
        - [1.27.2.- Respuesta de Salida](#1272--respuesta-de-salida)
            - [1.27.2.1- Respuesta de error](#12721--respuesta-de-error)
            - [1.27.2.2- Respuesta de éxito](#12722--respuesta-de-éxito)
    - [1.28.- Servicios Contratados por Cliente](#128--servicios-contratados-por-cliente)
        - [1.28.1.- Ejemplo de llamada](#1281--ejemplo-de-llamada)
        - [1.28.2.- Respuesta de Salida](#1282--respuesta-de-salida)
            - [1.28.2.1- Respuesta de error](#12821--respuesta-de-error)
            - [1.28.2.2- Respuesta de éxito](#12822--respuesta-de-éxito)
    - [1.29.- Ingresar Comentario de Reclamo](#129--ingresar-comentario-de-reclamo)
        - [1.29.1.- Ejemplo de llamada](#1291--ejemplo-de-llamada)
        - [1.29.2.- Respuesta de Salida](#1292--respuesta-de-salida)
            - [1.29.2.1- Respuesta de error](#12921--respuesta-de-error)
            - [1.29.2.2- Respuesta de éxito](#12922--respuesta-de-éxito)
    - [1.30.- Lista Subcategorías Internas](#130--lista-subcategorias-internas)
        - [1.30.1.- Ejemplo de llamada](#1301--ejemplo-de-llamada)
        - [1.30.2.- Respuesta de Salida](#1302--respuesta-de-salida)
            - [1.30.2.1- Respuesta de error](#13021--respuesta-de-error)
            - [1.30.2.2- Respuesta de éxito](#13022--respuesta-de-éxito)
    - [1.31.- Ingresar Oficio de Reclamo Subtel](#131--ingresar-oficio-de-reclamo-subtel)
        - [1.31.1.- Ejemplo de llamada](#1311--ejemplo-de-llamada)
        - [1.31.2.- Respuesta de Salida](#1312--respuesta-de-salida)
            - [1.31.2.1- Respuesta de error](#13121--respuesta-de-error)
            - [1.31.2.2- Respuesta de éxito](#13122--respuesta-de-éxito)
    - [1.32.- Ingresar Resolución de Reclamo Subtel](#132--ingresar-resolución-de-reclamo-subtel)
        - [1.32.1.- Ejemplo de llamada](#1321--ejemplo-de-llamada)
        - [1.32.2.- Respuesta de Salida](#1322--respuesta-de-salida)
            - [1.32.2.1- Respuesta de error](#13221--respuesta-de-error)
            - [1.32.2.2- Respuesta de éxito](#13222--respuesta-de-éxito)
  - [2.- Sucursal](#1--Sucursal)
    - [2.1.- Ingresar Reclamos desde Sucursal](#21--ingresar-reclamos-desde-sucursal)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
    - [2.2.- Tipos de Reclamos](#22--tipos-de-reclamos)
        - [2.2.1.- Ejemplo de llamada](#2231--ejemplo-de-llamada)
        - [2.2.2.- Respuesta de Salida](#2232--respuesta-de-salida)
            - [2.2.2.1- Respuesta de error](#22321--respuesta-de-error)
            - [2.2.2.2- Respuesta de éxito](#22322--respuesta-de-éxito)
    - [2.3.- Tipos de Medios de Notificación](#23--tipos-de-medios-de-notificación)
        - [2.3.1.- Ejemplo de llamada](#231--ejemplo-de-llamada)
        - [2.3.2.- Respuesta de Salida](#232--respuesta-de-salida)
            - [2.3.2.1- Respuesta de error](#2321--respuesta-de-error)
            - [2.3.2.2- Respuesta de éxito](#2322--respuesta-de-éxito)
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
            - [2.6.2.1- Respuesta de error](#2621--respuesta-de-error)
            - [2.6.2.2- Respuesta de éxito](#2622--respuesta-de-éxito)
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
        - [2.9.1.- Ejemplo de llamada](#291--ejemplo-de-llamada)
        - [2.9.2.- Respuesta de Salida](#292--respuesta-de-salida)
            - [2.9.2.1- Respuesta de error](#2921--respuesta-de-error)
            - [2.9.2.2- Respuesta de éxito](#2922--respuesta-de-éxito)
    - [2.10.- Contingencias Cliente](#210--contingencias-cliente)
        - [2.10.1.- Ejemplo de llamada](#2101--ejemplo-de-llamada)
        - [2.10.2.- Respuesta de Salida](#2102--respuesta-de-salida)
            - [2.10.2.1- Respuesta de error](#21021--respuesta-de-error)
            - [2.10.2.2- Respuesta de éxito](#21022--respuesta-de-éxito)
    - [2.11.- Consultar Datos de Cliente IVR](#211--consultar-datos-de-cliente-ivr)
        - [2.11.1.- Ejemplo de llamada](#2111--ejemplo-de-llamada)
        - [2.11.2.- Respuesta de Salida](#2112--respuesta-de-salida)
            - [2.11.2.1- Respuesta de error](#21121--respuesta-de-error)
            - [2.11.2.2- Respuesta de éxito](#21122--respuesta-de-éxito)
    - [2.12.- Datos Domicilio de Cliente](#212--datos-domicilio-de-cliente)
        - [2.12.1.- Ejemplo de llamada](#2121--ejemplo-de-llamada)
        - [2.12.2.- Respuesta de Salida](#2122--respuesta-de-salida)
            - [2.12.2.1- Respuesta de error](#21221--respuesta-de-error)
            - [2.12.2.2- Respuesta de éxito](#21222--respuesta-de-éxito)
    - [2.13.- Servicios Contratados por Cliente](#213--servicios-contratados-por-cliente)
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
    - [3.6.- Actualizar Contingencia](#36--actualizar-contingencia)
        - [3.6.1.- Ejemplo de llamada](#361--ejemplo-de-llamada)
        - [3.6.2.- Respuesta de Salida](#362--respuesta-de-salida)
            - [3.6.2.1- Respuesta de error](#3621--respuesta-de-error)
            - [3.6.2.2- Respuesta de éxito](#3622--respuesta-de-éxito)
    - [3.7.- Actualizar Estado de Reclamo](#37--actualizar-estado-de-reclamo)
        - [3.7.1.- Ejemplo de llamada](#371--ejemplo-de-llamada)
        - [3.7.2.- Respuesta de Salida](#372--respuesta-de-salida)
            - [3.7.2.1- Respuesta de error](#3721--respuesta-de-error)
            - [3.7.2.2- Respuesta de éxito](#3722--respuesta-de-éxito)
    - [3.8.- Actualizar Teléfono de Cliente](#38--actualizar-teléfono-de-cliente)
        - [3.8.1.- Ejemplo de llamada](#381--ejemplo-de-llamada)
        - [3.8.2.- Respuesta de Salida](#382--respuesta-de-salida)
            - [3.8.2.1- Respuesta de error](#3821--respuesta-de-error)
            - [3.8.2.2- Respuesta de éxito](#3822--respuesta-de-éxito)
    - [3.9.- Actualizar Teléfono Reclamado por Cliente](#39--actualizar-teléfono-reclamado-por-cliente)
        - [3.9.1.- Ejemplo de llamada](#391--ejemplo-de-llamada)
        - [3.9.2.- Respuesta de Salida](#392--respuesta-de-salida)
            - [3.9.2.1- Respuesta de error](#3921--respuesta-de-error)
            - [3.9.2.2- Respuesta de éxito](#3922--respuesta-de-éxito)
    - [3.10.- Actualizar Motivo de Reclamo](#310--actualizar-motivo-de-reclamo)
        - [3.10.1.- Ejemplo de llamada](#3101--ejemplo-de-llamada)
        - [3.10.2.- Respuesta de Salida](#3102--respuesta-de-salida)
            - [3.10.2.1- Respuesta de error](#31021--respuesta-de-error)
            - [3.10.2.2- Respuesta de éxito](#31022--respuesta-de-éxito)
    - [3.11.- Actualizar Rut de Cliente](#311--actualizar-rut-de-cliente)
        - [3.11.1.- Ejemplo de llamada](#3111--ejemplo-de-llamada)
        - [3.11.2.- Respuesta de Salida](#3112--respuesta-de-salida)
            - [3.11.2.1- Respuesta de error](#31121--respuesta-de-error)
            - [3.11.2.2- Respuesta de éxito](#31122--respuesta-de-éxito)
    - [3.12.- Actualizar Rut de Cliente Solicitante](#312--actualizar-rut-de-cliente-solicitante)
        - [3.12.1.- Ejemplo de llamada](#3121--ejemplo-de-llamada)
        - [3.12.2.- Respuesta de Salida](#3122--respuesta-de-salida)
            - [3.12.2.1- Respuesta de error](#31221--respuesta-de-error)
            - [3.12.2.2- Respuesta de éxito](#31222--respuesta-de-éxito)
    - [3.13.- Actualizar Servicio del Cliente](#313--actualizar-servicio-del-cliente)
        - [3.13.1.- Ejemplo de llamada](#3131--ejemplo-de-llamada)
        - [3.13.2.- Respuesta de Salida](#3132--respuesta-de-salida)
            - [3.13.2.1- Respuesta de error](#31321--respuesta-de-error)
            - [3.13.2.2- Respuesta de éxito](#31322--respuesta-de-éxito)
    - [3.14.- Actualizar Submotivo de Reclamo](#314--actualizar-submotivo-de-reclamo)
        - [3.14.1.- Ejemplo de llamada](#3141--ejemplo-de-llamada)
        - [3.14.2.- Respuesta de Salida](#3142--respuesta-de-salida)
            - [3.14.2.1- Respuesta de error](#31421--respuesta-de-error)
            - [3.14.2.2- Respuesta de éxito](#31422--respuesta-de-éxito)
    - [3.15.- Actualizar Medio de Notificación](#315--actualizar-medio-de-notificación)
        - [3.15.1.- Ejemplo de llamada](#3151--ejemplo-de-llamada)
        - [3.15.2.- Respuesta de Salida](#3152--respuesta-de-salida)
            - [3.15.2.1- Respuesta de error](#31521--respuesta-de-error)
            - [3.15.2.2- Respuesta de éxito](#31522--respuesta-de-éxito)
    - [3.16.- Actualizar Tipo de Teléfono Reclamado](#316--actualizar-tipo-de-teléfono-reclamado)
        - [3.16.1.- Ejemplo de llamada](#3161--ejemplo-de-llamada)
        - [3.16.2.- Respuesta de Salida](#3162--respuesta-de-salida)
            - [3.16.2.1- Respuesta de error](#31621--respuesta-de-error)
            - [3.16.2.2- Respuesta de éxito](#31622--respuesta-de-éxito)
    - [3.17.- Actualizar Tipo de Servicio](#317--actualizar-tipo-de-servicio)
        - [3.17.1.- Ejemplo de llamada](#3171--ejemplo-de-llamada)
        - [3.17.2.- Respuesta de Salida](#3172--respuesta-de-salida)
            - [3.17.2.1- Respuesta de error](#31721--respuesta-de-error)
            - [3.17.2.2- Respuesta de éxito](#31722--respuesta-de-éxito)
    - [3.18.- Actualizar Número Móvil Reclamado](#318--actualizar-número-móvil-reclamo)
        - [3.18.1.- Ejemplo de llamada](#3181--ejemplo-de-llamada)
        - [3.18.2.- Respuesta de Salida](#3182--respuesta-de-salida)
            - [3.18.2.1- Respuesta de error](#31821--respuesta-de-error)
            - [3.18.2.2- Respuesta de éxito](#31822--respuesta-de-éxito)
    - [3.19.- Actualizar Cliente Reclamante](#319--actualizar-cliente-reclamante)
        - [3.19.1.- Ejemplo de llamada](#3191--ejemplo-de-llamada)
        - [3.19.2.- Respuesta de Salida](#3192--respuesta-de-salida)
            - [3.19.2.1- Respuesta de error](#31921--respuesta-de-error)
            - [3.19.2.2- Respuesta de éxito](#31922--respuesta-de-éxito)
    - [3.20.- Actualizar Teléfono Reclamado](#320--actualizar-teléfono-reclamado)
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

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de reclamo                           |
| DESCRIPCION    | string       | Tipo de reclamo                                  |

### 1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.1.2.2.- Respuesta de éxito

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
| CODIGO         | int          | ID del tipo de solución                          |
| DESCRIPCION    | string       | Tipo de solución                                 |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.2.2.2.- Respuesta de éxito

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
| CODIGO         | int          | ID del tipo de motivos de reclamos               |
| DESCRIPCION    | string       | Tipo de motivos de reclamos                      |

### 1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.3.2.2.- Respuesta de éxito

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
| CODIGO         | int          | ID del tipo de notificación                      |
| DESCRIPCION    | string       | Tipo de notificación                             |

### 1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.4.2.2.- Respuesta de éxito

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
| Rut          | string       | 12345678-9                     |                                            | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de servicio                          |
| DESCRIPCION    | string       | Tipo de servicio                                 |

### 1.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "Rut":"96722400-6"
	}

### 1.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

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
| idServicio   | int          |                                | No                                         | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de solución                          |
| DESCRIPCION    | string       | Tipo de solución                                 |

### 1.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}

### 1.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

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
| idServicio   | int          |                                | No                            | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del motivo del reclamo                        |
| DESCRIPCION    | string       | Motivo del reclamo                               |

### 1.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 1
	}

### 1.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.7.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.7.2.2.- Respuesta de éxito

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
| CODIGO         | int          | ID del tipo de registro                          |
| DESCRIPCION    | string       | Tipo de registro                                 |

### 1.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.8.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.8.2.2.- Respuesta de éxito

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

## 1.9.- Submotivos
Método que retorna lista de submotivos de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/submotivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| idMotivo     | int          |                                | Especificar si parámetro es requerido o no | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| Nombre Campo   | Tipo de dato | Breve descripción                                |

### 1.9.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idMotivo": 1
	}

### 1.9.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.9.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "No hay datos para mostrar"
        },
        "codigo": 204
    }
  
#### 1.9.2.2.- Respuesta de éxito

	{
        ...
	}

## 1.10.- Reclamos
Método que retorna detalle de reclamo o lista de reclamos.

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/reclamos/listado/reclamo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido         |             Descripción     |
|:------------:|:------------:|:------------------------------:|:---------------------:|----------------------------:|
| IdReclamo    | int          |                                | No                    | ID de reclamo               |
| page         | int          |                                | No                    | Número de página            |

**Datos de salida:**
| Campo                           |  Tipo        |                         Descripción              |
|:--------------------------------|:------------:|-------------------------------------------------:| 
| RERE_ID_RECLAMO                 | int          | Breve descripción                                | 
| RERE_ID_SUBCATEGORIA_INTERNA    | Tipo de dato | Breve descripción                                | 
| RERE_NOMBRE_USUARIO             | string       | Breve descripción                                | 
| RERE_USUARIO_ACTUALIZA          | Tipo de dato | Breve descripción                                | 
| RERE_ID_TIPO_TELEFONO           | int          | Breve descripción                                | 
| RERE_DIRECCION_CEL_RECLAMADO    | string       | Breve descripción                                | 
| RERE_FECHA_CIERRE               | Tipo de dato | Breve descripción                                | 
| RERE_FECHA_NOTIFICACION         | timestamp    | Breve descripción                                | 
| RERE_FOLIO                      | string       | Breve descripción                                | 
| RERE_TEXTO                      | string       | Breve descripción                                | 
| RERE_FECHA_REGISTRO             | timestamp    | Breve descripción                                | 
| RERE_FECHA_RECLAMO              | timestamp    | Breve descripción                                | 
| RERE_CALLER_ID                  | Tipo de dato | Breve descripción                                | 
| RERE_ID_TIPO_NOTIFICACION       | int          | Breve descripción                                | 
| RERE_ID_ESTADO_RECLAMO          | int          | Breve descripción                                | 
| RERE_ID_SOLICITANTE             | int          | Breve descripción                                | 
| RERE_ID_TIPO_RECLAMO            | int          | Breve descripción                                | 
| RERE_ID_TIPO_SOLUCION           | int          | Breve descripción                                | 
| RERE_ID_TIPO_REGISTRO           | int          | Breve descripción                                | 
| RERE_ID_SERVICIO                | int          | Breve descripción                                | 
| RERE_ID_TIPO_SERVICIO           | int          | Breve descripción                                | 
| RERE_ID_MOTIVO                  | int          | Breve descripción                                | 
| RERE_ID_SUB_MOTIVO              | Tipo de dato | Breve descripción                                | 
| RERE_ID_MACROMOTIVO             | Tipo de dato | Breve descripción                                | 
| RERE_ID_CONFORMIDAD             | Tipo de dato | Breve descripción                                | 
| RERE_HORAS_SIN_SERVICIO         | Tipo de dato | Breve descripción                                | 
| RERE_MONTO_TOTAL_RECLAMADO      | Tipo de dato | Breve descripción                                | 
| RERE_CELULAR_RECLAMADO          | Tipo de dato | Breve descripción                                | 
| RERE_AREA_TELEFONO_RECLAMADO    | Tipo de dato | Breve descripción                                | 
| RERE_TELEFONO_RECLAMADO         | Tipo de dato | Breve descripción                                | 
| RERE_DIRECCION_TEL_RECLAMADO    | Tipo de dato | Breve descripción                                | 
| RERE_TOTAL_DESCUENTO            | Tipo de dato | Breve descripción                                | 
| RERE_MONTO_INDEMNIZACION        | Tipo de dato | Breve descripción                                | 
| RERE_MONTO_DESCUENTO            | Tipo de dato | Breve descripción                                | 
| RERE_ID_RECLAMO_SUBTEL          | Tipo de dato | Breve descripción                                | 
| RERE_ID_RECLAMO_SERNAC          | Tipo de dato | Breve descripción                                | 
| RERE_ID_USUARIO                 | int          | Breve descripción                                | 
| RERE_ID_USUARIO_ACTUALIZA       | Tipo de dato | Breve descripción                                | 
| RERE_ID_ME_QUIERO_SALIR         | Tipo de dato | Breve descripción                                | 
| ↓ tipo_notificacion             | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                | 
| ↓ estado                        | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                | 
| ↓ solicitante                   | array[object]| Breve descripción                                | 
| RESO_RUT                        | int          | Breve descripción                                | 
| RESO_ES_TITULAR                 | boolean      | Breve descripción                                | 
| RESO_RUT_DV                     | string       | Breve descripción                                | 
| RESO_NUMERO_CALLE_REPRESENTANTE | int          | Breve descripción                                | 
| RESO_NOMBRE_RAZON               | string       | Breve descripción                                | 
| RESO_CODIGO_CLIENTE_BU          | string       | Breve descripción                                | 
| RESO_ID_SOLICITANTE             | int          | Breve descripción                                | 
| RESO_COMUNA                     | string       | Breve descripción                                | 
| RESO_ID_COMUNA                  | int          | Breve descripción                                | 
| RESO_REGION                     | string       | Breve descripción                                | 
| RESO_ID_REGION                  | int          | Breve descripción                                | 
| RESO_PLAN_PRINCIPAL             | string       | Breve descripción                                | 
| RESO_NODO                       | string       | Breve descripción                                | 
| RESO_RUT_REPRESENTANTE          | int          | Breve descripción                                | 
| RESO_RUT_DV_REPRESENTANTE       | string       | Breve descripción                                | 
| RESO_NOMBRE_REPRESENTANTE       | string       | Breve descripción                                | 
| RESO_APELLIDOS_REPRESENTANTE    | string       | Breve descripción                                | 
| RESO_TELEFONO_REPRESENTANTE     | int          | Breve descripción                                | 
| RESO_EMAIL_REPRESENTANTE        | string       | Breve descripción                                | 
| RESO_EMAIL                      | string       | Breve descripción                                | 
| RESO_COMUNA_REPRESENTANTE       | string       | Breve descripción                                | 
| RESO_ID_COMUNA_REPRESENTANTE    | int          | Breve descripción                                | 
| RESO_DIRECCION_REPRESENTANTE    | string       | Breve descripción                                | 
| RESO_ID_REGION_REPRESENTANTE    | int          | Breve descripción                                | 
| RESO_REGION_REPRESENTANTE       | string       | Breve descripción                                | 
| RESO_CALLE                      | string       | Breve descripción                                | 
| RESO_CLIENTE_UNIFICADO          | int          | Breve descripción                                |  
| ↓ tipo_reclamo                  | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                | 
| ↓ tipo_solucion                 | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                |
| ↓ tipo_registro                 | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                |
| ↓ tipo_telefono                 | array[object]| Breve descripción                                | 
| RETS_DESCRIPCION                | string       | Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                |
| ↓ servicio                      | array[object]| Breve descripción                                | 
| RESE_DESCRIPCION                | string       | Breve descripción                                | 
| RESE_ID_SERVICIO                | int          | Breve descripción                                |
| ↓ tipo_servicio                 | array[object]| Breve descripción                                | 
| RETE_DESCRIPCION                | string       | Breve descripción                                | 
| RETE_ID_TIPO_SERVICIO           | int          | Breve descripción                                |
| ↓ motivo                        | array[object]| Breve descripción                                | 
| REMO_DESCRIPCION                | string       | Breve descripción                                | 
| REMO_ID_MOTIVO                  | int          | Breve descripción                                |
| ↓ sub_motivo                    | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ macromotivo                   | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ conformidad                   | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ archivos                      | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ acoge_reclamos                | array[object]| Breve descripción                                | 
| REAR_ID_AGOGE_RECLAMO           | int          | Breve descripción                                |
| REAR_FECHA_REGISTRO             | timestamp    | Breve descripción                                |
| REAR_COMENTARIO                 | Tipo de dato | Breve descripción                                |
| REAR_ID_RECLAMO                 | int          | Breve descripción                                |
| REAR_ID_ACOGE                   | int          | Breve descripción                                |
| REAR_ID_USUARIO                 | int          | Breve descripción                                |
| REAR_USUARIO                    | string       | Breve descripción                                |
| ↓↓ tipo_acoge                   | array[object]| Breve descripción                                | 
| RETS_ID_SUBTIPO                 | int          | Breve descripción                                |
| RETS_ID_ORIGEN                  | Tipo de dato | Breve descripción                                |
| RETS_DESCRIPCION                | string       | Breve descripción                                |
| RETS_CODIGO                     | string       | Breve descripción                                |
| RETS_VIGENTE                    | boolean      | Breve descripción                                |
| RETS_ID_REGISTRO_PADRE          | int          | Breve descripción                                |
| ↓ sub_categoria_interna         | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ comentarios                   | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ subtel                        | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ sernac                        | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ me_quiero_salir               | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |
| ↓ usuario_crea                  | array[object]| Breve descripción                                | 
| RU_ID                           | int          | Breve descripción                                |
| RU_EMAIL                        | string       | Breve descripción                                |
| RU_NOMBRE                       | string       | Breve descripción                                |
| ↓ usuario_actualiza             | array[object]| Breve descripción                                | 
| ?                               | Tipo de dato | Breve descripción                                |

### 1.10.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "IdReclamo": 63,
        "page": 1
	}

### 1.10.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.10.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.10.2.2.- Respuesta de éxito

	{
        "current_page": 1,
        "data": [
            {
                "RERE_ID_RECLAMO": 63,
                "RERE_ID_SUBCATEGORIA_INTERNA": null,
                "RERE_NOMBRE_USUARIO": null,
                "RERE_USUARIO_ACTUALIZA": null,
                "RERE_ID_TIPO_TELEFONO": null,
                "RERE_DIRECCION_CEL_RECLAMADO": null,
                "RERE_FECHA_CIERRE": null,
                "RERE_FECHA_NOTIFICACION": null,
                "RERE_FOLIO": "10878",
                "RERE_TEXTO": "asda",
                "RERE_FECHA_REGISTRO": "2020-12-23 15:45:27",
                "RERE_FECHA_RECLAMO": "2020-12-23 00:00:00",
                "RERE_CALLER_ID": null,
                "RERE_ID_TIPO_NOTIFICACION": 2,
                "RERE_ID_ESTADO_RECLAMO": 25,
                "RERE_ID_SOLICITANTE": 55,
                "RERE_ID_TIPO_RECLAMO": 7,
                "RERE_ID_TIPO_SOLUCION": null,
                "RERE_ID_TIPO_REGISTRO": null,
                "RERE_ID_SERVICIO": 1,
                "RERE_ID_TIPO_SERVICIO": 1,
                "RERE_ID_MOTIVO": 1,
                "RERE_ID_SUB_MOTIVO": null,
                "RERE_ID_MACROMOTIVO": null,
                "RERE_ID_CONFORMIDAD": null,
                "RERE_HORAS_SIN_SERVICIO": 1,
                "RERE_MONTO_TOTAL_RECLAMADO": 1,
                "RERE_CELULAR_RECLAMADO": null,
                "RERE_AREA_TELEFONO_RECLAMADO": null,
                "RERE_TELEFONO_RECLAMADO": null,
                "RERE_DIRECCION_TEL_RECLAMADO": null,
                "RERE_TOTAL_DESCUENTO": null,
                "RERE_MONTO_INDEMNIZACION": null,
                "RERE_MONTO_DESCUENTO": null,
                "RERE_ID_RECLAMO_SUBTEL": null,
                "RERE_ID_RECLAMO_SERNAC": null,
                "RERE_ID_USUARIO": null,
                "RERE_ID_USUARIO_ACTUALIZA": null,
                "RERE_ID_ME_QUIERO_SALIR": null,
                "tipo_notificacion": {
                    "RETS_DESCRIPCION": "Teléfono",
                    "RETS_ID_SUBTIPO": 2
                },
                "estado": {
                    "RETS_DESCRIPCION": "Cerrado",
                    "RETS_ID_SUBTIPO": 25
                },
                "solicitante": {
                    "RESO_RUT": 18348381,
                    "RESO_ES_TITULAR": false,
                    "RESO_RUT_DV": "1",
                    "RESO_NUMERO_CALLE_REPRESENTANTE": null,
                    "RESO_NOMBRE_RAZON": "Patrick Alexander",
                    "RESO_CODIGO_CLIENTE_BU": null,
                    "RESO_ID_SOLICITANTE": 55,
                    "RESO_COMUNA": null,
                    "RESO_ID_COMUNA": 8101,
                    "RESO_REGION": null,
                    "RESO_ID_REGION": null,
                    "RESO_PLAN_PRINCIPAL": "FIBRA + TVHD + FIJO",
                    "RESO_NODO": null,
                    "RESO_RUT_REPRESENTANTE": 18348381,
                    "RESO_RUT_DV_REPRESENTANTE": "1",
                    "RESO_NOMBRE_REPRESENTANTE": "Patrick Alexander",
                    "RESO_APELLIDOS_REPRESENTANTE": "Chavarria",
                    "RESO_TELEFONO_REPRESENTANTE": 944660808,
                    "RESO_EMAIL_REPRESENTANTE": "patrick.chavarria.veloso@gmail.com",
                    "RESO_EMAIL": "patrick.chavarria.veloso@gmail.com",
                    "RESO_COMUNA_REPRESENTANTE": "Concepción",
                    "RESO_ID_COMUNA_REPRESENTANTE": 8101,
                    "RESO_DIRECCION_REPRESENTANTE": "Anibal Pinto",
                    "RESO_ID_REGION_REPRESENTANTE": null,
                    "RESO_REGION_REPRESENTANTE": null,
                    "RESO_CALLE": "Anibal Pinto",
                    "RESO_CLIENTE_UNIFICADO": 499088
                },
                "tipo_reclamo": {
                    "RETS_DESCRIPCION": "Técnico",
                    "RETS_ID_SUBTIPO": 7
                },
                "tipo_solucion": null,
                "tipo_registro": null,
                "tipo_telefono": null,
                "servicio": {
                    "RESE_DESCRIPCION": "Servicio móvil",
                    "RESE_ID_SERVICIO": 1
                },
                "tipo_servicio": {
                    "RETE_DESCRIPCION": "Internet",
                    "RETE_ID_TIPO_SERVICIO": 1
                },
                "motivo": {
                    "REMO_DESCRIPCION": "Calidad servicio",
                    "REMO_ID_MOTIVO": 1
                },
                "sub_motivo": null,
                "macromotivo": null,
                "conformidad": null,
                "archivos": [],
                "acoge_reclamo": [],
                "sub_categoria_interna": null,
                "comentarios": [],
                "subtel": null,
                "sernac": null,
                "me_quiero_salir": null,
                "usuario_crea": null,
                "usuario_actualiza": null
            }
        ],
        "first_page_url": "...URL/informes/reclamo?IdReclamo=63&page=1",
        "from": 1,
        "last_page": 1,
        "last_page_url": "...URL/informes/reclamo?IdReclamo=63&page=1",
        "next_page_url": null,
        "path": "...URL/informes/reclamo",
        "per_page": 15,
        "prev_page_url": null,
        "to": 1,
        "total": 1
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
| Campo                      |  Tipo        | Formato                        |     Requerido               |             Descripción     |
|:--------------------------:|:------------:|:------------------------------:|:---------------------------:|----------------------------:|
| rutCliente                 | string       |                                |                             | Breve descripción           |
| dvCliente                  | int          |                                |                             | Breve descripción           |
| clienteUnificado           | string       |                                |                             | Breve descripción           |
| codigoClienteBu            | string       |                                |                             | Breve descripción           |
| idConexion                 | ?            |                                |                             | Breve descripción           |
| nombreRazon                | string       |                                |                             | Breve descripción           |
| clienteNodo                | ?            |                                |                             | Breve descripción           |
| apellidos                  | string       |                                |                             | Breve descripción           |
| calle                      | string       |                                |                             | Breve descripción           |
| numeroCalle                | string       |                                |                             | Breve descripción           |
| email                      | string       |                                |                             | Breve descripción           |
| planPrincipal              | ?            |                                |                             | Breve descripción           |
| fechaReclamo               | string       |                                |                             | Breve descripción           |
| tipoNotificacion           | int          |                                |                             | Breve descripción           |
| servicio                   | int          |                                |                             | Breve descripción           |
| tipoServicio               | int          |                                |                             | Breve descripción           |
| motivo                     | int          |                                |                             | Breve descripción           |
| idComuna                   | int          |                                |                             | Breve descripción           |
| comuna                     | string       |                                |                             | Breve descripción           |
| region                     | int          |                                |                             | Breve descripción           |
| comentario                 | string       |                                |                             | Breve descripción           |
| telefono                   | ?            |                                |                             | Breve descripción           |
| tipoSolucion               | int          |                                |                             | Breve descripción           |
| tipoReclamo                | int          |                                |                             | Breve descripción           |
| numeroContingencia         | string       |                                |                             | Breve descripción           |
| archivos                   | ?            |                                |                             | Breve descripción           |
| idAcoge                    | int          |                                |                             | Breve descripción           |
| tipoRegistro               | int          |                                |                             | Breve descripción           |
| celularReclamado           | string       |                                |                             | Breve descripción           |
| telefonoReclamado          | string       |                                |                             | Breve descripción           |
| areaTelefonoReclamado      | string       |                                |                             | Breve descripción           |
| direccionTelefonoReclamado | string       |                                |                             | Breve descripción           |
| rutRepresentante           | string       |                                |                             | Breve descripción           |
| dvRepresentante            | string       |                                |                             | Breve descripción           |
| nombreRepresentante        | string       |                                |                             | Breve descripción           |
| apellidosRepresentante     | string       |                                |                             | Breve descripción           |
| telefonoRepresentante      | string       |                                |                             | Breve descripción           |
| celularRepresentante       | string       |                                |                             | Breve descripción           |
| emailRepresentante         | string       |                                |                             | Breve descripción           |
| direccionRepresentante     | string       |                                |                             | Breve descripción           |
| comunaRepresentante        | string       |                                |                             | Breve descripción           |
| idComunaRepresentante      | int          |                                |                             | Breve descripción           |
| totalReclamado             | string       |                                |                             | Breve descripción           |
| horasSinServicio           | string       |                                |                             | Breve descripción           |
| texto                      | string       |                                |                             | Breve descripción           |

### 1.12.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "rutCliente": "11111111",
        "dvCliente": 1,
        "clienteUnificado": "284953",
        "codigoClienteBu": "CC38860",
        "idConexion": null,
        "nombreRazon": "Empresa Limitada",
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
        "nombreRepresentante": "Empresa Limitada",
        "apellidosRepresentante": "Sociedad Comercial",
        "telefonoRepresentante": "999999999",
        "celularRepresentante": "999999999",
        "emailRepresentante": "oscar.roman@mundopacifico.cl",
        "direccionRepresentante": "Mi domicilio de prueba",
        "comunaRepresentante": "Concepción",
        "idComunaRepresentante": 8101,
        "totalReclamado": "",
        "horasSinServicio": "0",
        "texto": ""
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

`El reclamo ha sido ingresado con número de folio asociado: <b>2021875</b>`

## 1.13.- Total Reclamos Comunas
Método que retorna los datos para el reporte gráfico de reclamos de todas las comunas.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-total-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | 2021-08-23                     | No                           | Breve descripción           |
| fechaTermino | string       | 2021-08-23                     | Si                           | Breve descripción           |
| idRegion     | int          |                                | Si                           | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| color          | string       | Breve descripción                                |
| name           | string       | Breve descripción                                |
| ↓ reclamos     | array[object]| Breve descripción                                |
| name           | string       | Breve descripción                                |
| Reclamos       | int          | Breve descripción                                |

### 1.13.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "fechaInicio": "2020-12-11",
        "fechaTermino": "2021-01-11",
        "idRegion": 8
    }


### 1.13.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.13.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.13.2.2.- Respuesta de éxito

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

## 1.14.- Reclamos por Comuna
Método que retorna los datos para el reporte gráfico de reclamos por comuna.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-comuna`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | 2021-08-23                     | No                           | Breve descripción           |
| fechaTermino | string       | 2021-08-23                     | Si                           | Breve descripción           |
| comunas      | array        |                                | Si                           | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ estados      | array[object]| Breve descripción                                |
| color          | string       | Breve descripción                                |
| name           | string       | Breve descripción                                |
| ↓ reclamos     | array[object]| Breve descripción                                |
| name           | string       | Breve descripción                                |
| Abierto        | int          | Breve descripción                                |
| Cerrado        | int          | Breve descripción                                |
| En             | int          | Breve descripción                                |
| Registrado     | int          | Breve descripción                                |
| Revisado       | int          | Breve descripción                                |
| Términado      | int          | Breve descripción                                |

### 1.14.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "fechaInicio": "2021-01-01",
        "fechaTermino": "2021-02-15",
        "comunas": [16101, 8112]
    }

### 1.14.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.14.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.14.2.2.- Respuesta de éxito

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
    
## 1.15.- Reclamos por Fecha
Método que retorna los datos para el reporte gráfico de reclamos por rango de fecha.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-fecha`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | 2021-08-23                     | No                           | Breve descripción           |
| fechaTermino | string       | 2021-08-23                     | Si                           | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ estados      | array[object]| Breve descripción                                |
| color          | string       | Breve descripción                                |
| name           | string       | Breve descripción                                |
| ↓ reclamos     | array[object]| Breve descripción                                |
| name           | string       | Breve descripción                                |
| Abierto        | int          | Breve descripción                                |
| Cerrado        | int          | Breve descripción                                |
| En             | int          | Breve descripción                                |
| Registrado     | int          | Breve descripción                                |
| Revisado       | int          | Breve descripción                                |
| Términado      | int          | Breve descripción                                |

### 1.15.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
    "fechaInicio": "2021-01-01",
    "fechaTermino": "2021-01-05"
    }

### 1.15.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.15.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.15.2.2.- Respuesta de éxito

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

## 1.16.- Reclamos por Motivo y Servicio
Método que retorna los datos para el reporte gráfico de reclamos por motivos y servicios.

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/reclamos/grafico-reclamo-por-servicio-motivo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                |             Descripción     |
|:------------:|:------------:|:------------------------------:|:----------------------------:|----------------------------:|
| fechaInicio  | string       | 2021-08-23                     | No                           | Breve descripción           |
| fechaTermino | string       | 2021-08-23                     | Si                           | Breve descripción           |
| idServicio   | int          |                                | Si                           | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| ↓ motivos      | array[object]| Breve descripción                                |
| color          | string       | Breve descripción                                |
| name           | string       | Breve descripción                                |
| ↓ reclamos     | array[object]| Breve descripción                                |
| name           | string       | Breve descripción                                |
| value          | int          | Breve descripción                                |

### 1.16.1.- Ejemplo de llamada

Ejemplo: JSON 

    {
        "fechaInicio": "2020-12-11",
        "fechaTermino": "2021-01-11",
        "idServicio": 1
    }

### 1.16.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.16.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.16.2.2.- Respuesta de éxito

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

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID del tipo de teléfono                          |
| DESCRIPCION    | string       | Tipo de teléfono                                 |

### 1.21.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 1.21.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.21.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.21.2.2.- Respuesta de éxito

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
| RUTCliente   | string       | 123456789                      | Si                                         | Breve descripción           |

**Datos de salida:**
| Campo              |  Tipo        |                         Descripción              |
|:-------------------|:------------:|-------------------------------------------------:| 
| estado             | string       | Breve descripción                                |
| deudaPendiente     | string       | Breve descripción                                |
| nodos              | string       | Breve descripción                                |
| promocionActiva    | string       | Breve descripción                                |
| tipoPromocion      | Tipo de dato | Breve descripción                                |
| cantidadConexiones | int          | Breve descripción                                |

### 1.24.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "RUTCliente": "166101069"
	}

### 1.24.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.24.2.1.- Respuesta de error

    {
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "RUT del cliente no ingresado."
        },
        "codigo": 422
    }
  
#### 1.24.2.2.- Respuesta de éxito

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
| idServicio   | int          |                                | Si                                         | Breve descripción           |
| idTipoReclamo| int          |                                | Si                                         | Breve descripción           |

**Datos de salida:**
| Campo          |  Tipo        |                         Descripción              |
|:---------------|:------------:|-------------------------------------------------:| 
| CODIGO         | int          | ID de la subcategoría interna                    |
| DESCRIPCION    | string       | Subcategoría interna                             |

### 1.30.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idServicio": 2,
        "idTipoReclamo": 6
	}

### 1.30.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.30.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 1.30.2.2.- Respuesta de éxito

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

## 2.2.- Tipos de Reclamos
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
| ?            | int          |                                | No                                         | Breve descripción           |

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
       ...
    }
  
#### 2.5.2.2.- Respuesta de éxito

    {

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



