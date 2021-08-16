| Tipo de seguridad|
|:----------------:|
|                  |

<!-- Título -->
# Documentación Api´s para Mundo Social

<!-- Índice -->
- [Documentación Api´s para Mundo Social](#documentación-apis-para-mundo-social)
  - [Objetivo](#objetivo)
  - [Restricciones](#restricciones)
  - [1.- Asignación de Usuarios](#1--asignación-de-usuarios)
    - [1.1.- Listar Usuarios](#11--listar-usuarios)
        - [1.1.1.- Ejemplo de llamada](#111--ejemplo-de-llamada)
        - [1.1.2.- Respuesta de Salida](#112--respuesta-de-salida)
            - [1.1.2.1- Respuesta de error](#1121--respuesta-de-error)
            - [1.1.2.2- Respuesta de éxito](#1122--respuesta-de-éxito)
    - [1.2.- Asignar Usuario a Ticket](#12--asignar-usuario-a-ticket)
        - [1.2.1.- Ejemplo de llamada](#121--ejemplo-de-llamada)
        - [1.2.2.- Respuesta de Salida](#122--respuesta-de-salida)
            - [1.2.2.1- Respuesta de error](#1221--respuesta-de-error)
            - [1.2.2.2- Respuesta de éxito](#1222--respuesta-de-éxito)
  - [2.- Autoasignación](#2--autoasignación)
    - [2.1.- Autoasignación](#21--autoasignación)
        - [2.1.1.- Ejemplo de llamada](#211--ejemplo-de-llamada)
        - [2.1.2.- Respuesta de Salida](#212--respuesta-de-salida)
            - [2.1.2.1- Respuesta de error](#2121--respuesta-de-error)
            - [2.1.2.2- Respuesta de éxito](#2122--respuesta-de-éxito)
  - [3.- Cambia Face](#3--cambia-face)
    - [3.1.- Cambia](#31--cambia)
        - [3.1.1.- Ejemplo de llamada](#311--ejemplo-de-llamada)
        - [3.1.2.- Respuesta de Salida](#312--respuesta-de-salida)
            - [3.1.2.1- Respuesta de error](#3121--respuesta-de-error)
            - [3.1.2.2- Respuesta de éxito](#3123--respuesta-de-éxito)
  - [4.- Canales](#4--canales)
    - [4.1.- getCanales](#41--getCanales)
        - [4.1.1.- Ejemplo de llamada](#411--ejemplo-de-llamada)
        - [4.1.2.- Respuesta de Salida](#412--respuesta-de-salida)
            - [4.1.2.1- Respuesta de error](#4121--respuesta-de-error)
            - [4.1.2.2- Respuesta de éxito](#4122--respuesta-de-éxito)
  - [5.- Canal Grupo](#5--canal-grupo)
    - [5.1.- Get](#51--get)
        - [5.1.1.- Ejemplo de llamada](#511--ejemplo-de-llamada)
        - [5.1.2.- Respuesta de Salida](#512--respuesta-de-salida)
            - [5.1.2.1- Respuesta de error](#5121--respuesta-de-error)
            - [5.1.2.2- Respuesta de éxito](#5122--respuesta-de-éxito)
    - [5.2.- Crear](#52--crear)
        - [5.2.1.- Ejemplo de llamada](#521--ejemplo-de-llamada)
        - [5.2.2.- Respuesta de Salida](#522--respuesta-de-salida)
            - [5.2.2.1- Respuesta de error](#5221--respuesta-de-error)
            - [5.2.2.2- Respuesta de éxito](#5222--respuesta-de-éxito)
    - [5.3.- Update](#53--update)
        - [5.3.1.- Ejemplo de llamada](#531--ejemplo-de-llamada)
        - [5.3.2.- Respuesta de Salida](#532--respuesta-de-salida)
            - [5.3.2.1- Respuesta de error](#5321--respuesta-de-error)
            - [5.3.2.2- Respuesta de éxito](#5322--respuesta-de-éxito)
    - [5.4.- Delete](#54--delete)
        - [5.4.1.- Ejemplo de llamada](#541--ejemplo-de-llamada)
        - [5.4.2.- Respuesta de Salida](#542--respuesta-de-salida)
            - [5.4.2.1- Respuesta de error](#5421--respuesta-de-error)
            - [5.4.2.2- Respuesta de éxito](#5422--respuesta-de-éxito)
    - [5.5.- Cuenta By Canal](#55--cuenta-by-canal)
        - [5.5.1.- Ejemplo de llamada](#551--ejemplo-de-llamada)
        - [5.5.2.- Respuesta de Salida](#552--respuesta-de-salida)
            - [5.5.2.1- Respuesta de error](#5521--respuesta-de-error)
            - [5.5.2.2- Respuesta de éxito](#5522--respuesta-de-éxito)
  - [6.- Clientes](#6--clientes)
    - [6.1.- Buscar Cliente](#61--buscar-cliente)
        - [6.1.1.- Ejemplo de llamada](#611--ejemplo-de-llamada)
        - [6.1.2.- Respuesta de Salida](#612--respuesta-de-salida)
            - [6.1.2.1- Respuesta de error](#6121--respuesta-de-error)
            - [6.1.2.2- Respuesta de éxito](#6122--respuesta-de-éxito)
    - [6.2.- Crear Cliente](#62--crear-cliente)
        - [6.2.1.- Ejemplo de llamada](#621--ejemplo-de-llamada)
        - [6.2.2.- Respuesta de Salida](#622--respuesta-de-salida)
            - [6.2.2.1- Respuesta de error](#6221--respuesta-de-error)
            - [6.2.2.2- Respuesta de éxito](#6222--respuesta-de-éxito)
    - [6.3.- ClienteTicket](#63--clienteTicket)
        - [6.3.1.- Ejemplo de llamada](#631--ejemplo-de-llamada)
        - [6.3.2.- Respuesta de Salida](#632--respuesta-de-salida)
            - [6.3.2.1- Respuesta de error](#6321--respuesta-de-error)
            - [6.3.2.2- Respuesta de éxito](#6322--respuesta-de-éxito)
  - [7.- Colas](#7--colas)
    - [7.1.- Buscar Siguiente Ticket](#71--buscar-siguiente-ticket)
        - [7.1.1.- Ejemplo de llamada](#711--ejemplo-de-llamada)
        - [7.1.2.- Respuesta de Salida](#712--respuesta-de-salida)
            - [7.1.2.1- Respuesta de error](#7121--respuesta-de-error)
            - [7.1.2.2- Respuesta de éxito](#7122--respuesta-de-éxito)
    - [7.2.- Cambiar Grupo](#72--cambiar-grupo)
        - [7.2.1.- Ejemplo de llamada](#721--ejemplo-de-llamada)
        - [7.2.2.- Respuesta de Salida](#722--respuesta-de-salida)
            - [7.2.2.1- Respuesta de error](#7221--respuesta-de-error)
            - [7.2.2.2- Respuesta de éxito](#7222--respuesta-de-éxito)
    - [7.3.- Diferencia](#73--diferencia)
        - [7.3.1.- Ejemplo de llamada](#731--ejemplo-de-llamada)
        - [7.3.2.- Respuesta de Salida](#732--respuesta-de-salida)
            - [7.3.2.1- Respuesta de error](#7321--respuesta-de-error)
            - [7.3.2.2- Respuesta de éxito](#7322--respuesta-de-éxito)
  - [8.- Cuentas Internas](#8--cuentas-internas)
    - [8.1.- getCuentabyCanal](#81--getCuentabyCanal)
        - [8.1.1.- Ejemplo de llamada](#811--ejemplo-de-llamada)
        - [8.1.2.- Respuesta de Salida](#812--respuesta-de-salida)
            - [8.1.2.1- Respuesta de error](#8121--respuesta-de-error)
            - [8.1.2.2- Respuesta de éxito](#8122--respuesta-de-éxito)
    - [8.2.- Update](#82--update)
        - [8.2.1.- Ejemplo de llamada](#821--ejemplo-de-llamada)
        - [8.2.2.- Respuesta de Salida](#822--respuesta-de-salida)
            - [8.2.2.1- Respuesta de error](#8221--respuesta-de-error)
            - [8.2.2.2- Respuesta de éxito](#8222--respuesta-de-éxito)
  - [9.- Departamento](#9--departamento)
    - [9.1.- Get](#91--get)
        - [9.1.1.- Ejemplo de llamada](#911--ejemplo-de-llamada)
        - [9.1.2.- Respuesta de Salida](#912--respuesta-de-salida)
            - [9.1.2.1- Respuesta de error](#9121--respuesta-de-error)
            - [9.1.2.2- Respuesta de éxito](#9122--respuesta-de-éxito)
    - [9.2.- Crear](#92--crear)
        - [9.2.1.- Ejemplo de llamada](#921--ejemplo-de-llamada)
        - [9.2.2.- Respuesta de Salida](#922--respuesta-de-salida)
            - [9.2.2.1- Respuesta de error](#9221--respuesta-de-error)
            - [9.2.2.2- Respuesta de éxito](#9222--respuesta-de-éxito)
    - [9.3.- Update](#93--update)
        - [9.3.1.- Ejemplo de llamada](#931--ejemplo-de-llamada)
        - [9.3.2.- Respuesta de Salida](#932--respuesta-de-salida)
            - [9.3.2.1- Respuesta de error](#9321--respuesta-de-error)
            - [9.3.2.2- Respuesta de éxito](#9322--respuesta-de-éxito)
    - [9.4.- Delete](#94--delete)
        - [9.4.1.- Ejemplo de llamada](#941--ejemplo-de-llamada)
        - [9.4.2.- Respuesta de Salida](#942--respuesta-de-salida)
            - [9.4.2.1- Respuesta de error](#9421--respuesta-de-error)
            - [9.4.2.2- Respuesta de éxito](#9422--respuesta-de-éxito)
  - [10.- Estado de Conexión](#10--estado-de-conexión)
    - [10.1.- Estados de Conexión](#101--estados-de-conexión)
        - [10.1.1.- Ejemplo de llamada](#1011--ejemplo-de-llamada)
        - [10.1.2.- Respuesta de Salida](#1012--respuesta-de-salida)
            - [10.1.2.1- Respuesta de error](#10121--respuesta-de-error)
            - [10.1.2.2- Respuesta de éxito](#10122--respuesta-de-éxito)
    - [10.2.- Modificar Estado de Conexión](#102--modificar-estado-de-conexión)
        - [10.2.1.- Ejemplo de llamada](#1021--ejemplo-de-llamada)
        - [10.2.2.- Respuesta de Salida](#1022--respuesta-de-salida)
            - [10.2.2.1- Respuesta de error](#10221--respuesta-de-error)
            - [10.2.2.2- Respuesta de éxito](#10222--respuesta-de-éxito)
  - [11.- FAQ](#11--faq)
    - [11.1.- Preguntas Frecuentes](#111--preguntas-frecuentes)
        - [11.1.1.- Get](#1111--get)
            - [11.1.1.1.- Ejemplo de llamada](#11111--ejemplo-de-llamada)
            - [11.1.1.2.- Respuesta de Salida](#11112--respuesta-de-salida)
                - [11.1.1.2.1- Respuesta de error](#111121--respuesta-de-error)
                - [11.1.1.2.2- Respuesta de éxito](#111122--respuesta-de-éxito)
        - [11.1.2.- Crear](#1112--crear)
            - [11.1.2.1.- Ejemplo de llamada](#11121--ejemplo-de-llamada)
            - [11.1.2.2.- Respuesta de Salida](#11122--respuesta-de-salida)
                - [11.1.2.2.1- Respuesta de error](#111221--respuesta-de-error)
                - [11.1.2.2.2- Respuesta de éxito](#111222--respuesta-de-éxito)
        - [11.1.3.- Update](#1113--update)
            - [11.1.3.1.- Ejemplo de llamada](#11131--ejemplo-de-llamada)
            - [11.1.3.2.- Respuesta de Salida](#11132--respuesta-de-salida)
                - [11.1.3.2.1- Respuesta de error](#111321--respuesta-de-error)
                - [11.1.3.2.2- Respuesta de éxito](#111322--respuesta-de-éxito)
        - [11.1.4.- Delete](#1114--delete)
            - [11.1.4.1.- Ejemplo de llamada](#11141--ejemplo-de-llamada)
            - [11.1.4.2.- Respuesta de Salida](#11142--respuesta-de-salida)
                - [11.1.4.2.1- Respuesta de error](#111421--respuesta-de-error)
                - [11.1.4.2.2- Respuesta de éxito](#111422--respuesta-de-éxito)
    - [11.2.- Preguntas Alternativas](#112--preguntas-alternativas)
        - [11.2.1.- Get](#1121--get)
            - [11.2.1.1.- Ejemplo de llamada](#11211--ejemplo-de-llamada)
            - [11.2.1.2.- Respuesta de Salida](#11212--respuesta-de-salida)
                - [11.2.1.2.1- Respuesta de error](#112121--respuesta-de-error)
                - [11.2.1.2.2- Respuesta de éxito](#112122--respuesta-de-éxito)
        - [11.2.2.- Crear](#1121--crear)
            - [11.2.2.1.- Ejemplo de llamada](#11221--ejemplo-de-llamada)
            - [11.2.2.2.- Respuesta de Salida](#11222--respuesta-de-salida)
                - [11.2.2.2.1- Respuesta de error](#112221--respuesta-de-error)
                - [11.2.2.2.2- Respuesta de éxito](#112222--respuesta-de-éxito)
        - [11.2.3.- Update](#1123--update)
            - [11.2.3.1.- Ejemplo de llamada](#11231--ejemplo-de-llamada)
            - [11.2.3.2.- Respuesta de Salida](#11232--respuesta-de-salida)
                - [11.2.3.2.1- Respuesta de error](#112321--respuesta-de-error)
                - [11.2.3.2.2- Respuesta de éxito](#112322--respuesta-de-éxito)
        - [11.2.4.- Delete](#1124--delete)
            - [11.2.4.1.- Ejemplo de llamada](#11241--ejemplo-de-llamada)
            - [11.2.4.2.- Respuesta de Salida](#11242--respuesta-de-salida)
                - [11.2.4.2.1- Respuesta de error](#112421--respuesta-de-error)
                - [11.2.4.2.2- Respuesta de éxito](#112422--respuesta-de-éxito)
  - [12.- Grupos](#12--grupos)
    - [12.1.- Get](#121--get)
        - [12.1.1.- Ejemplo de llamada](#1211--ejemplo-de-llamada)
        - [12.1.2.- Respuesta de Salida](#1212--respuesta-de-salida)
            - [12.1.2.1- Respuesta de error](#12121--respuesta-de-error)
            - [12.1.2.2- Respuesta de éxito](#12122--respuesta-de-éxito)
    - [12.2.- Crear](#122--crear)
        - [12.2.1.- Ejemplo de llamada](#1221--ejemplo-de-llamada)
        - [12.2.2.- Respuesta de Salida](#1222--respuesta-de-salida)
            - [12.2.2.1- Respuesta de error](#12221--respuesta-de-error)
            - [12.2.2.2- Respuesta de éxito](#12222--respuesta-de-éxito)
    - [12.3.- Update](#123--update)
        - [12.3.1.- Ejemplo de llamada](#1231--ejemplo-de-llamada)
        - [12.3.2.- Respuesta de Salida](#1232--respuesta-de-salida)
            - [12.3.2.1- Respuesta de error](#12321--respuesta-de-error)
            - [12.3.2.2- Respuesta de éxito](#12322--respuesta-de-éxito)
    - [12.4.- Delete](#124--delete)
        - [12.4.1.- Ejemplo de llamada](#1241--ejemplo-de-llamada)
        - [12.4.2.- Respuesta de Salida](#1242--respuesta-de-salida)
            - [12.4.2.1- Respuesta de error](#12421--respuesta-de-error)
            - [12.4.2.2- Respuesta de éxito](#12422--respuesta-de-éxito)
  - [13.- Grupo Usuario](#13--grupo-usuario)
    - [13.1.- getGrupoByUser](#131--getGrupoByUser)
        - [13.1.1.- Ejemplo de llamada](#1311--ejemplo-de-llamada)
        - [13.1.2.- Respuesta de Salida](#1312--respuesta-de-salida)
            - [13.1.2.1- Respuesta de error](#13121--respuesta-de-error)
            - [13.1.2.2- Respuesta de éxito](#13122--respuesta-de-éxito)
    - [13.2.- Asignación](#132--asignación)
        - [13.2.1.- Ejemplo de llamada](#1321--ejemplo-de-llamada)
        - [13.2.2.- Respuesta de Salida](#1322--respuesta-de-salida)
            - [13.2.2.1- Respuesta de error](#13221--respuesta-de-error)
            - [13.2.2.2- Respuesta de éxito](#13222--respuesta-de-éxito)
  - [14.- Horarios](#14--horarios)
    - [14.1.- Get](#141--get)
        - [14.1.1.- Ejemplo de llamada](#1411--ejemplo-de-llamada)
        - [14.1.2.- Respuesta de Salida](#1412--respuesta-de-salida)
            - [14.1.2.1- Respuesta de error](#14121--respuesta-de-error)
            - [14.1.2.2- Respuesta de éxito](#14122--respuesta-de-éxito)
    - [14.2.- Store](#142--store)
        - [14.2.1.- Ejemplo de llamada](#1421--ejemplo-de-llamada)
        - [14.2.2.- Respuesta de Salida](#1422--respuesta-de-salida)
            - [14.2.2.1- Respuesta de error](#14221--respuesta-de-error)
            - [14.2.2.2- Respuesta de éxito](#14222--respuesta-de-éxito)
  - [15.- Hubspot](#15--hubspot)
    - [15.1.- Hubspot](#151--hubspot)
        - [15.1.1.- Ejemplo de llamada](#1511--ejemplo-de-llamada)
        - [15.1.2.- Respuesta de Salida](#1512--respuesta-de-salida)
            - [15.1.2.1- Respuesta de error](#15121--respuesta-de-error)
            - [15.1.2.2- Respuesta de éxito](#15122--respuesta-de-éxito)
    - [15.2.- EnvíaMail](#152--envíaMail)
        - [15.2.1.- Ejemplo de llamada](#1521--ejemplo-de-llamada)
        - [15.2.2.- Respuesta de Salida](#1522--respuesta-de-salida)
            - [15.2.2.1- Respuesta de error](#15221--respuesta-de-error)
            - [15.2.2.2- Respuesta de éxito](#15222--respuesta-de-éxito)
  - [16.- Integración CRM](#16--integración-crm)
    - [16.1.- Crear Cliente](#161--crear-cliente)
        - [16.1.1.- Crear Cliente](#1611--crear-cliente)
            - [16.1.1.1.- Ejemplo de llamada](#16111--ejemplo-de-llamada)
            - [16.1.1.2.- Respuesta de Salida](#16112--respuesta-de-salida)
                - [16.1.1.2.1- Respuesta de error](#161121--respuesta-de-error)
                - [16.1.1.2.2- Respuesta de éxito](#161122--respuesta-de-éxito)
        - [16.1.2.- Crear Cliente Empresa](#1612--crear-cliente-empresa)
            - [16.1.2.1.- Ejemplo de llamada](#16121--ejemplo-de-llamada)
            - [16.1.2.2.- Respuesta de Salida](#16122--respuesta-de-salida)
                - [16.1.2.2.1- Respuesta de error](#161221--respuesta-de-error)
                - [16.1.2.2.2- Respuesta de éxito](#161222--respuesta-de-éxito)
        - [16.1.3.- Fuente y Segmentación](#1613--fuente-y-segmentación)
            - [16.1.3.1.- Ejemplo de llamada](#16131--ejemplo-de-llamada)
            - [16.1.3.2.- Respuesta de Salida](#16132--respuesta-de-salida)
                - [16.1.3.2.1- Respuesta de error](#161321--respuesta-de-error)
                - [16.1.3.2.2- Respuesta de éxito](#161322--respuesta-de-éxito)
        - [16.1.4.- Actividades Profesionales](#1614--actividades-profesionales)
            - [16.1.4.1.- Ejemplo de llamada](#16141--ejemplo-de-llamada)
            - [16.1.4.2.- Respuesta de Salida](#16142--respuesta-de-salida)
                - [16.1.4.2.1- Respuesta de error](#161421--respuesta-de-error)
                - [16.1.4.2.2- Respuesta de éxito](#161422--respuesta-de-éxito)
        - [16.1.5.- Cargos](#1615--cargos)
            - [16.1.5.1.- Ejemplo de llamada](#16151--ejemplo-de-llamada)
            - [16.1.5.2.- Respuesta de Salida](#16152--respuesta-de-salida)
                - [16.1.5.2.1- Respuesta de error](#161521--respuesta-de-error)
                - [16.1.5.2.2- Respuesta de éxito](#161522--respuesta-de-éxito)
        - [16.1.6.- Tipo Vía](#1616--tipo-vía)
            - [16.1.6.1.- Ejemplo de llamada](#16161--ejemplo-de-llamada)
            - [16.1.6.2.- Respuesta de Salida](#16162--respuesta-de-salida)
                - [16.1.6.2.1- Respuesta de error](#161621--respuesta-de-error)
                - [16.1.6.2.2- Respuesta de éxito](#161622--respuesta-de-éxito)
        - [16.1.7.- Localidades](#1617--localidades)
            - [16.1.7.1.- Ejemplo de llamada](#16171--ejemplo-de-llamada)
            - [16.1.7.2.- Respuesta de Salida](#16172--respuesta-de-salida)
                - [16.1.7.2.1- Respuesta de error](#161721--respuesta-de-error)
                - [16.1.7.2.2- Respuesta de éxito](#161722--respuesta-de-éxito)
        - [16.1.8.- Comunas](#1618--comunas)
            - [16.1.8.1.- Ejemplo de llamada](#16181--ejemplo-de-llamada)
            - [16.1.8.2.- Respuesta de Salida](#16182--respuesta-de-salida)
                - [16.1.8.2.1- Respuesta de error](#161821--respuesta-de-error)
                - [16.1.8.2.2- Respuesta de éxito](#161822--respuesta-de-éxito)
    - [16.2.- Ofertas](#162--ofertas)
        - [16.2.1.- Ejemplo de llamada](#1621--ejemplo-de-llamada)
        - [16.2.2.- Respuesta de Salida](#1622--respuesta-de-salida)
            - [16.2.2.1- Respuesta de error](#16221--respuesta-de-error)
            - [16.2.2.2- Respuesta de éxito](#16222--respuesta-de-éxito)
    - [16.3.- Tareas](#163--tareas)
        - [16.3.1.- Ejemplo de llamada](#1631--ejemplo-de-llamada)
        - [16.3.2.- Respuesta de Salida](#1632--respuesta-de-salida)
            - [16.3.2.1- Respuesta de error](#16321--respuesta-de-error)
            - [16.3.2.2- Respuesta de éxito](#16322--respuesta-de-éxito)
    - [16.4.- Crear Tarea Oferta](#164--crear-tarea-oferta)
        - [16.4.1.- Ejemplo de llamada](#1641--ejemplo-de-llamada)
        - [16.4.2.- Respuesta de Salida](#1642--respuesta-de-salida)
            - [16.4.2.1- Respuesta de error](#16421--respuesta-de-error)
            - [16.4.2.2- Respuesta de éxito](#16422--respuesta-de-éxito)
    - [16.5.- Tipos de Tareas](#165--tipos-de-tareas)
        - [16.5.1.- Ejemplo de llamada](#1651--ejemplo-de-llamada)
        - [16.5.2.- Respuesta de Salida](#1652--respuesta-de-salida)
            - [16.5.2.1- Respuesta de error](#16521--respuesta-de-error)
            - [16.5.2.2- Respuesta de éxito](#16522--respuesta-de-éxito)
    - [16.6.- Motivos de Tareas](#166--motivos-de-tareas)
        - [16.6.1.- Ejemplo de llamada](#1661--ejemplo-de-llamada)
        - [16.6.2.- Respuesta de Salida](#1662--respuesta-de-salida)
            - [16.6.2.1- Respuesta de error](#16621--respuesta-de-error)
            - [16.6.2.2- Respuesta de éxito](#16622--respuesta-de-éxito)
  - [17.- Listar Tickets](#17--listar-tickets)
    - [17.1.- Listar Tickets](#171--listar-tickets)
        - [17.1.1.- Ejemplo de llamada](#1711--ejemplo-de-llamada)
        - [17.1.2.- Respuesta de Salida](#1712--respuesta-de-salida)
            - [17.1.2.1- Respuesta de error](#17121--respuesta-de-error)
            - [17.1.2.2- Respuesta de éxito](#17122--respuesta-de-éxito)
    - [17.2.- Cola Tickets](#172--cola-tickets)
        - [17.2.1.- Ejemplo de llamada](#1721--ejemplo-de-llamada)
        - [17.2.2.- Respuesta de Salida](#1722--respuesta-de-salida)
            - [17.2.2.1- Respuesta de error](#17221--respuesta-de-error)
            - [17.2.2.2- Respuesta de éxito](#17222--respuesta-de-éxito)
    - [17.3.- Mis Tickets en Proceso](#173--mis-tickets-en-proceso)
        - [17.3.1.- Ejemplo de llamada](#1731--ejemplo-de-llamada)
        - [17.3.2.- Respuesta de Salida](#1732--respuesta-de-salida)
            - [17.3.2.1- Respuesta de error](#17321--respuesta-de-error)
            - [17.3.2.2- Respuesta de éxito](#17322--respuesta-de-éxito)
    - [17.4.- Mis Tickets Cerrados](#174--mis-tickets-cerrados)
        - [17.4.1.- Ejemplo de llamada](#1741--ejemplo-de-llamada)
        - [17.4.2.- Respuesta de Salida](#1742--respuesta-de-salida)
            - [17.4.2.1- Respuesta de error](#17421--respuesta-de-error)
            - [17.4.2.2- Respuesta de éxito](#17422--respuesta-de-éxito)
  - [18.- Mensajes](#18--mensajes)
    - [18.1.- Recibe](#181--recibe)
        - [18.1.1.- Ejemplo de llamada](#1811--ejemplo-de-llamada)
        - [18.1.2.- Respuesta de Salida](#1812--respuesta-de-salida)
            - [18.1.2.1- Respuesta de error](#18121--respuesta-de-error)
            - [18.1.2.2- Respuesta de éxito](#18122--respuesta-de-éxito)
    - [18.2.- Sale](#182--sale)
        - [18.2.1.- Ejemplo de llamada](#1821--ejemplo-de-llamada)
        - [18.2.2.- Respuesta de Salida](#1822--respuesta-de-salida)
            - [18.2.2.1- Respuesta de error](#18221--respuesta-de-error)
            - [18.2.2.2- Respuesta de éxito](#18222--respuesta-de-éxito)
    - [18.3.- Conversaciones](#183--conversaciones)
        - [18.3.1.- Ejemplo de llamada](#1831--ejemplo-de-llamada)
        - [18.3.2.- Respuesta de Salida](#1832--respuesta-de-salida)
            - [18.3.2.1- Respuesta de error](#18321--respuesta-de-error)
            - [18.3.2.2- Respuesta de éxito](#18322--respuesta-de-éxito)
    - [18.4.- Mensajes No Leídos](#184--mensajes-no-leídos)
        - [18.4.1.- Ejemplo de llamada](#1841--ejemplo-de-llamada)
        - [18.4.2.- Respuesta de Salida](#1842--respuesta-de-salida)
            - [18.4.2.1- Respuesta de error](#18421--respuesta-de-error)
            - [18.4.2.2- Respuesta de éxito](#18422--respuesta-de-éxito)
    - [18.5.- Sale dmtw](#185--sale-dmtw)
        - [18.5.1.- Ejemplo de llamada](#1851--ejemplo-de-llamada)
        - [18.5.2.- Respuesta de Salida](#1852--respuesta-de-salida)
            - [18.5.2.1- Respuesta de error](#18521--respuesta-de-error)
            - [18.5.2.2- Respuesta de éxito](#18522--respuesta-de-éxito)
    - [18.6.- Sucursal](#186--sucursal)
        - [18.6.1.- Ejemplo de llamada](#1861--ejemplo-de-llamada)
        - [18.6.2.- Respuesta de Salida](#1862--respuesta-de-salida)
            - [18.6.2.1- Respuesta de error](#18621--respuesta-de-error)
            - [18.6.2.2- Respuesta de éxito](#18622--respuesta-de-éxito)
  - [19.- Omnicanalidad](#19--omnicanalidad)
    - [19.1.- Listar Canales](#191--listar-canales)
        - [19.1.1.- Ejemplo de llamada](#1911--ejemplo-de-llamada)
        - [19.1.2.- Respuesta de Salida](#1912--respuesta-de-salida)
            - [19.1.2.1- Respuesta de error](#19121--respuesta-de-error)
            - [19.1.2.2- Respuesta de éxito](#19122--respuesta-de-éxito)
    - [19.2.- Canales de un Cliente](#192--canales-de-un-cliente)
        - [19.2.1.- Ejemplo de llamada](#1921--ejemplo-de-llamada)
        - [19.2.2.- Respuesta de Salida](#1922--respuesta-de-salida)
            - [19.2.2.1- Respuesta de error](#19221--respuesta-de-error)
            - [19.2.2.2- Respuesta de éxito](#19222--respuesta-de-éxito)
    - [19.3.- Crear Canal del Cliente](#193--crear-canal-del-cliente)
        - [19.3.1.- Ejemplo de llamada](#1931--ejemplo-de-llamada)
        - [19.3.2.- Respuesta de Salida](#1932--respuesta-de-salida)
            - [19.3.2.1- Respuesta de error](#19321--respuesta-de-error)
            - [19.3.2.2- Respuesta de éxito](#19322--respuesta-de-éxito)
    - [19.4.- Tickets Abiertos de una Cuenta de Cliente](#194--tickets-abiertos-de-una-cuenta-de-cliente)
        - [19.4.1.- Ejemplo de llamada](#1941--ejemplo-de-llamada)
        - [19.4.2.- Respuesta de Salida](#1942--respuesta-de-salida)
            - [19.4.2.1- Respuesta de error](#19421--respuesta-de-error)
            - [19.4.2.2- Respuesta de éxito](#19422--respuesta-de-éxito)
    - [19.5.- Tickets Relacionados All](#195--tickets-relacionados-all)
        - [19.5.1.- Ejemplo de llamada](#1951--ejemplo-de-llamada)
        - [19.5.2.- Respuesta de Salida](#1952--respuesta-de-salida)
            - [19.5.2.1- Respuesta de error](#19521--respuesta-de-error)
            - [19.5.2.2- Respuesta de éxito](#19522--respuesta-de-éxito)
    - [19.6.- Vincular Ticket](#196--vincular-ticket)
        - [19.6.1.- Ejemplo de llamada](#1961--ejemplo-de-llamada)
        - [19.6.2.- Respuesta de Salida](#1962--respuesta-de-salida)
            - [19.6.2.1- Respuesta de error](#19621--respuesta-de-error)
            - [19.6.2.2- Respuesta de éxito](#19622--respuesta-de-éxito)
    - [19.7.- Vincular Todos](#197--vincular-todos)
        - [19.7.1.- Ejemplo de llamada](#1971--ejemplo-de-llamada)
        - [19.7.2.- Respuesta de Salida](#1972--respuesta-de-salida)
            - [19.7.2.1- Respuesta de error](#19721--respuesta-de-error)
            - [19.7.2.2- Respuesta de éxito](#19722--respuesta-de-éxito)
  - [20.- Plantilla Wsp](#20--plantilla-wsp)
    - [20.1.- Get](#201--get)
        - [20.1.1.- Ejemplo de llamada](#2011--ejemplo-de-llamada)
        - [20.1.2.- Respuesta de Salida](#2012--respuesta-de-salida)
            - [20.1.2.1- Respuesta de error](#20121--respuesta-de-error)
            - [20.1.2.2- Respuesta de éxito](#20122--respuesta-de-éxito)
    - [20.2.- Generar Ticket desde Mundo](#202--generar-ticket-desde-mundo)
        - [20.2.1.- Ejemplo de llamada](#2021--ejemplo-de-llamada)
        - [20.2.2.- Respuesta de Salida](#2022--respuesta-de-salida)
            - [20.2.2.1- Respuesta de error](#20221--respuesta-de-error)
            - [20.2.2.2- Respuesta de éxito](#20222--respuesta-de-éxito)
  - [21.- Publicaciones](#21--publicaciones)
    - [21.1.- GetById](#211--getById)
        - [21.1.1.- Ejemplo de llamada](#2111--ejemplo-de-llamada)
        - [21.1.2.- Respuesta de Salida](#2112--respuesta-de-salida)
            - [21.1.2.1- Respuesta de error](#21121--respuesta-de-error)
            - [21.1.2.2- Respuesta de éxito](#21122--respuesta-de-éxito)
    - [21.2.- GetAll](#212--getAll)
        - [21.2.1.- Ejemplo de llamada](#2121--ejemplo-de-llamada)
        - [21.2.2.- Respuesta de Salida](#2122--respuesta-de-salida)
            - [21.2.2.1- Respuesta de error](#21221--respuesta-de-error)
            - [21.2.2.2- Respuesta de éxito](#21222--respuesta-de-éxito)
    - [21.3.- Guardar](#213--guardar)
        - [21.3.1.- Ejemplo de llamada](#2131--ejemplo-de-llamada)
        - [21.3.2.- Respuesta de Salida](#2132--respuesta-de-salida)
            - [21.3.2.1- Respuesta de error](#21321--respuesta-de-error)
            - [21.3.2.2- Respuesta de éxito](#21322--respuesta-de-éxito)
    - [21.4.- Update](#214--update)
        - [21.4.1.- Ejemplo de llamada](#2141--ejemplo-de-llamada)
        - [21.4.2.- Respuesta de Salida](#2142--respuesta-de-salida)
            - [21.4.2.1- Respuesta de error](#21421--respuesta-de-error)
            - [21.4.2.2- Respuesta de éxito](#21422--respuesta-de-éxito)
    - [21.5.- Delete](#215--delete)
        - [21.5.1.- Ejemplo de llamada](#2151--ejemplo-de-llamada)
        - [21.5.2.- Respuesta de Salida](#2152--respuesta-de-salida)
            - [21.5.2.1- Respuesta de error](#21521--respuesta-de-error)
            - [21.5.2.2- Respuesta de éxito](#21522--respuesta-de-éxito)
  - [22.- Reportes](#22--reportes)
    - [22.1.- Reporte](#221--reporte)
        - [22.1.1.- Ejemplo de llamada](#2211--ejemplo-de-llamada)
        - [22.1.2.- Respuesta de Salida](#2212--respuesta-de-salida)
            - [22.1.2.1- Respuesta de error](#22121--respuesta-de-error)
            - [22.1.2.2- Respuesta de éxito](#22122--respuesta-de-éxito)
  - [23.- Respuestas Rápidas](#23--respuestas-rápidas)
    - [23.1.- GetAll](#231--getAll)
        - [23.1.1.- Ejemplo de llamada](#2311--ejemplo-de-llamada)
        - [23.1.2.- Respuesta de Salida](#2312--respuesta-de-salida)
            - [23.1.2.1- Respuesta de error](#23121--respuesta-de-error)
            - [23.1.2.2- Respuesta de éxito](#23122--respuesta-de-éxito)
    - [23.2.- Store](#232--store)
        - [23.2.1.- Ejemplo de llamada](#2321--ejemplo-de-llamada)
        - [23.2.2.- Respuesta de Salida](#2322--respuesta-de-salida)
            - [23.2.2.1- Respuesta de error](#23221--respuesta-de-error)
            - [23.2.2.2- Respuesta de éxito](#23222--respuesta-de-éxito)
    - [23.3.- Update](#233--update)
        - [23.3.1.- Ejemplo de llamada](#2331--ejemplo-de-llamada)
        - [23.3.2.- Respuesta de Salida](#2332--respuesta-de-salida)
            - [23.3.2.1- Respuesta de error](#23321--respuesta-de-error)
            - [23.3.2.2- Respuesta de éxito](#23322--respuesta-de-éxito)
    - [23.4.- Delete](#234--delete)
        - [23.4.1.- Ejemplo de llamada](#2341--ejemplo-de-llamada)
        - [23.4.2.- Respuesta de Salida](#2342--respuesta-de-salida)
            - [23.4.2.1- Respuesta de error](#23421--respuesta-de-error)
            - [23.4.2.2- Respuesta de éxito](#23422--respuesta-de-éxito)
  - [24.- Usuarios](#24--usuarios)
    - [24.1.- Get Usuarios](#241--get-usuarios)
        - [24.1.1.- Ejemplo de llamada](#2411--ejemplo-de-llamada)
        - [24.1.2.- Respuesta de Salida](#2412--respuesta-de-salida)
            - [24.1.2.1- Respuesta de error](#24121--respuesta-de-error)
            - [24.1.2.2- Respuesta de éxito](#24122--respuesta-de-éxito)
    - [24.2.- Get Usuario](#242--get-usuario)
        - [24.2.1.- Ejemplo de llamada](#2421--ejemplo-de-llamada)
        - [24.2.2.- Respuesta de Salida](#2422--respuesta-de-salida)
            - [24.2.2.1- Respuesta de error](#24221--respuesta-de-error)
            - [24.2.2.2- Respuesta de éxito](#24222--respuesta-de-éxito)
    - [24.3.- Crear](#243--crear)
        - [24.3.1.- Ejemplo de llamada](#2431--ejemplo-de-llamada)
        - [24.3.2.- Respuesta de Salida](#2432--respuesta-de-salida)
            - [24.3.2.1- Respuesta de error](#24321--respuesta-de-error)
            - [24.3.2.2- Respuesta de éxito](#24322--respuesta-de-éxito)
    - [24.4.- Roles](#244--roles)
        - [24.4.1.- Ejemplo de llamada](#2441--ejemplo-de-llamada)
        - [24.4.2.- Respuesta de Salida](#2442--respuesta-de-salida)
            - [24.4.2.1- Respuesta de error](#24421--respuesta-de-error)
            - [24.4.2.2- Respuesta de éxito](#24422--respuesta-de-éxito)
    - [24.5.- Update](#245--update)
        - [24.5.1.- Ejemplo de llamada](#2451--ejemplo-de-llamada)
        - [24.5.2.- Respuesta de Salida](#2452--respuesta-de-salida)
            - [24.5.2.1- Respuesta de error](#24521--respuesta-de-error)
            - [24.5.2.2- Respuesta de éxito](#24522--respuesta-de-éxito)
    - [24.6.- Delete](#246--delete)
        - [24.6.1.- Ejemplo de llamada](#2461--ejemplo-de-llamada)
        - [24.6.2.- Respuesta de Salida](#2462--respuesta-de-salida)
            - [24.6.2.1- Respuesta de error](#24621--respuesta-de-error)
            - [24.6.2.2- Respuesta de éxito](#24622--respuesta-de-éxito)


# Objetivo

Describir objetivo

# Restricciones

Especificar restricciones


# 1.- Asignación de Usuarios
## 1.1.- Listar Usuarios
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/direcciones`

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
        "mensaje": "ok",
        "direcciones": []
    }

## 1.2.- Asignar Usuario a Ticket
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/ticket/asignausuario`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| tick_id      | int          |                                | Si                                         | ID del ticket    |
| usua_id      | int          |                                | Si                                         | ID del usuario   |

### 1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 74,
        "usua_id": 2
	}

### 1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 1.2.2.1.- Respuesta de error

	{
        "mensaje": "Problemas para validar"
    } 
  
#### 1.2.2.2.- Respuesta de éxito

	{
        "mensaje": "ok",
        ...
    }


# 2.- Autoasignación
## 2.1.- Autoasignación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/ticket/asignausuario`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| auto         | string       |                                | Si                                         | Indica                      |
| tick_id      | int          |                                | Si                                         | ID del ticket    |
| mail         | string       |                                | Si                                         | Email de                    |

### 2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "auto":"S",
        "tick_id": 561,
        "mail": "daniel.bustos@prueba.com"
	}

### 2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 2.1.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": {
                "mensaje": "Error al autoasignar:El grupo asignado al ticket no permite la auto asignación",
                "0": ""
            }
        },
        "codigo": 400
    }
  
#### 2.1.2.2.- Respuesta de éxito

	{
        "mensaje": "ok",
        ...
    }


# 3.- Cambia Face
## 3.1.- Cambia
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/comentfb`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:-----------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| remitenteOriginal | string       |                                | Si                                         | Indica                      |
| nuevoRemitente    | int          |                                | Si                                         | Indica                      |

### 3.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "remitenteOriginal": "155555_15522",
        "nuevoRemitente": "122222224"
	}

### 3.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 3.1.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": {
                "mensaje": "",
                "0": ""
            }
        },
        "codigo": 400
    }
  
#### 3.1.2.2.- Respuesta de éxito

	{
        "mensaje": "ok"
    }


# 4.- Canales
## 4.1.- getCanales
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/cuentacanales`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| cana_id      | int          |                                | Si                                         | ID de            |

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
| cuen_id           | int          | Breve descripción                                |
| cuen_identificador| string       | Breve descripción                                |
| cuen_bot          | boolean      | Breve descripción                                |
| cuen_descripcion  | string       | Breve descripción                                |

### 4.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cana_id": 4
	}

### 4.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 4.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 4.1.2.2.- Respuesta de éxito

	{
        "mensaje": "ok",
        "cuentas": [
            {
                "cuen_id": 12,
                "cuen_identificador": "contencion.general.dev@mundopacifico.cl",
                "cuen_bot": false,
                "cuen_descripcion": "Mail Contención"
            },
            {
                "cuen_id": 5,
                "cuen_identificador": "promociones99@mundopacifico.cl",
                "cuen_bot": false,
                "cuen_descripcion": "MAIL SOPORTE"
            }
        ]
    }


# 5.- Canal Grupo
## 5.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/canalgrupo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| grup_id      | int          |                                | Si                                         | ID del grupo    |

**Datos de salida:**
| Campo             |  Tipo        |                         Descripción              |
|:------------------|:------------:|-------------------------------------------------:| 
|                   |              | Breve descripción                                |

### 5.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1
	}

### 5.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.1.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": []
    }


## 5.2.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/canalgrupo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| grup_id      | int          |                                | Si                                         | ID del grupo    |
| cuen_id      | int          |                                | Si                                         | ID de la cuenta |
| cagr_usa_bot | boolean      |                                | Si                                         |                             |


### 5.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1,
        "cuen_id": 1,
        "cagr_usa_bot": true
	}

### 5.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.2.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }

## 5.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/canalgrupo/update`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| cagr_id      | int          |                                | Si                                         | ID de            |
| grup_id      | int          |                                | Si                                         | ID del grupo     |
| cuen_id      | int          |                                | Si                                         | ID de la cuenta  |
| cagr_usa_bot | boolean      |                                | Si                                         |                             |


### 5.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cagr_id": 2,
        "grup_id": 1,
        "cuen_id": 1,
        "cagr_usa_bot": false
	}

### 5.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.3.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }

## 5.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/canalgrupo/delete`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| cagr_id      | int          |                                | Si                                         | ID de            |


### 5.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cagr_id": 2
	}

### 5.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.4.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }

## 5.5.- Cuenta By Canal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/cuentabycanal`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| grup_id      | int          |                                | Si                                         | ID del grupo      |


### 5.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 2
	}

### 5.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 5.5.2.1.- Respuesta de error

	{
        ...
	} 
  
#### 5.5.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "cuentas": []
    }


# 6.- Clientes
## 6.1.- Buscar Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/cliente`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| rut          | string       | 123456789                      | Si                                         | Rut del cliente a buscar    |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_id               | int          | ID del cliente                        |
| clie_rut              | string       | Rut del cliente                                  |
| clie_nombre           | string       | Nombres del cliente                              |
| clie_apellido1        | string       | Apellido paterno del cliente                     |
| clie_apellido2        | string       | Apellido materno del cliente                     |
| clie_telefono         | string       | Teléfono principal del cliente                   |
| ticl_id_tipos_clientes| int          | Breve descripción                                |
| clie_genero           | string       | Género del cliente                               |
| clie_telefono2        | string       | Teléfono secundario del cliente                  |
| clie_avatar           | string       | Avatar del cliente                               |
| dataBu                |              | Breve descripción                                |
| EsCLienteBu           | boolean      | Breve descripción                                |
| Tipo                  | string       | Breve descripción                                |

### 6.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "rut": "134918071"
	}

### 6.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.1.2.1.- Respuesta de error

	{
        "cliente": null,
        "InfoBeyond": {
            "dataBu": [],
            "EsClienteBU": false,
            "Tipo": "Particular"
        }
    }
  
#### 6.1.2.2.- Respuesta de éxito

    {
        "cliente": {
            "clie_id": 75,
            "clie_rut": "134918071",
            "clie_nombre": "Fernando Javier",
            "clie_apellido1": "Sepulveda",
            "clie_apellido2": "Sepulveda",
            "clie_telefono": "939029334",
            "ticl_id_tipos_clientes": 2,
            "clie_genero": "Pendiente",
            "clie_telefono2": "Pendiente",
            "clie_avatar": "Pendiente"
        },
        "InfoBeyond": {
            "dataBu": [],
            "EsClienteBU": false,
            "Tipo": "Particular"
        }
    }


## 6.2.- Crear Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/cliente`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato               |     Requerido           |             Descripción          |
|:---------------------:|:------------:|:---------------------:|:-----------------------:|---------------------------------:|
| clie_rut              | string       |                       |  Si                     | Rut del cliente                  |
| clie_nombre           | string       |                       |  Si                     | Nombres del cliente              |
| clie_apellido1        | string       |                       |  Si                     | Apellido paterno del cliente     |
| clie_apellido2        | string       |                       |  Si                     | Apellido materno del cliente     |
| clie_telefono         | string       |                       |  Si                     | Teléfono principal del cliente   |
| clie_telefono2        | string       |                       |                         | Teléfono secundario del cliente  |
| clie_genero           | string       |                       |  Si                     | Género del cliente               |
| clie_avatar           | string       |                       |                         | Avatar del cliente               |


### 6.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "clie_rut": "134918071",
        "clie_nombre": "Fernando Javier",
        "clie_apellido1": "Sepulveda",
        "clie_apellido2": "Sepulveda",
        "clie_telefono": "939029334",
        "clie_telefono2": "Pendiente",
        "clie_genero": "H",
        "clie_avatar": "Pendiente"
	}

### 6.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.2.2.1.- Respuesta de error

	{
        ...
	}
  
#### 6.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        ...
    }

## 6.3.- ClienteTicket
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/cliente/cliente`

**Parámetros de entrada:**
| Campo                 |  Tipo        | Formato               |     Requerido           |             Descripción          |
|:---------------------:|:------------:|:---------------------:|:-----------------------:|---------------------------------:|
| tick_id               | string       |                       |  Si                     | ID del ticket        |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombres del cliente                              |
| clie_apellido1        | string       | Apellido paterno del cliente                     |
| clie_id_canales       | int          |                                                  |
| calc_identificador    | string       |                                                  |
| clie_id               | int          | ID del cliente                       |


### 6.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 188,
	}

### 6.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 6.3.2.1.- Respuesta de error

	{
        ...
	}
  
#### 6.3.2.2.- Respuesta de éxito

    {
        "cliente": {
            "clie_nombre": "Daniel",
            "clie_apellido1": "Bustos",
            "cana_id_canales": 1,
            "cacl_identificador": "whatsapp:+56961877547",
            "clie_id": 28
        }
    }


# 7.- Colas
## 7.1.- Buscar Siguiente Ticket
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/siguienteticket`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| mail         | string       |                                | Si                                         | Mail del X                  |

### 7.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com"
	}

### 7.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.1.2.1.- Respuesta de error

	{
        "mensaje": "Usuario no se encuentra en línea"
    }
  
#### 7.1.2.2.- Respuesta de éxito

    {
        ...
    }

## 7.2.- Cambiar Grupo
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/cambiargrupo`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| tick_id      | int          |                                | Si                                         | ID del ticket   |
| grup_id      | int          |                                | Si                                         | ID del grupo    |

### 7.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com"
	}

### 7.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 7.2.2.2.- Respuesta de éxito

    {
        ...
    }

## 7.3.- Diferencia
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/diferencia`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| enviados              | int          |                                                  |
| mensajeEnviado        | string       |                                                  |

### 7.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
       null
	}

### 7.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 7.3.2.1.- Respuesta de error

	{
       ...
    }
  
#### 7.3.2.2.- Respuesta de éxito

    {
        "enviados": 367,
        "mensajeEnviado": "En este momento nuestros ejecutivos se encuentran ocupados,en unos minutos un ejecutivo analizara su solicitud."
    }


# 8.- Cuentas Internas
## 8.1.- getCuentabyCanal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/cuentacanales`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| cana_id      | int          |                                | Si                                         | ID del canal     |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| cuen_id               | int          | ID de la cuenta                      |
| cuen_identificador    | string       | Identificador de la cuenta                       |
| cuen_bot              | boolean      |                                                  |
| cuen_descripcion      | string       | Descripción de la cuenta                         |

### 8.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cana_id": 3
	}

### 8.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 8.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 8.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "cuentas": [
            {
                "cuen_id": 6,
                "cuen_identificador": "875674658",
                "cuen_bot": false,
                "cuen_descripcion": "TWITTER RECLAMOS"
            },
            {
                "cuen_id": 7,
                "cuen_identificador": "963289466",
                "cuen_bot": false,
                "cuen_descripcion": "Twitter Reclamos 2"
            }
        ]
    }

## 8.2.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/cuentainterna/update`

**Parámetros de entrada:**
| Campo        |  Tipo        | Formato                        |     Requerido                              |             Descripción     |
|:------------:|:------------:|:------------------------------:|:------------------------------------------:|----------------------------:|
| cuen_bot     | boolean      |                                | Si                                         |                             |

### 8.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cuen_bot": true
	}

### 8.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 8.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 8.2.2.2.- Respuesta de éxito

    {
        ...
    }


# 9.- Departamento
## 9.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/departamento`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| depa_id               | int          | ID del departamento                  |
| depa_descripcion      | string       | Nombre del departamento                          |

### 9.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        null
	}

### 9.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 9.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "departamentos": [
            {
                "depa_id": 2,
                "depa_descripcion": "Ventas"
            },
            {
                "depa_id": 3,
                "depa_descripcion": "Cobranza"
            },
            ...
    }

## 9.2.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/departamento`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| depa_descripcion  | string       |                                |  Si                     | Nombre del departamento         |

### 9.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "depa_descripcion": "Contabilidad"
	}

### 9.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.2.2.1.- Respuesta de error

	{
        "mensaje": "Ya existe el departamento"
    }
    
#### 9.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "departamentoId": 16
    }

## 9.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/departamento/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido                              |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:------------------------------------------:|--------------------------------:|
| depa_id           | int          |                                |  Si                                        | ID del departamento |
| depa_descripcion  | string       |                                |  Si                                        | Nombre del departamento         |

### 9.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "depa_id": 16,
        "depa_descripcion": "Contabilidad Modificado"
	}

### 9.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.3.2.1.- Respuesta de error

	{
        "mensaje": "Ya existe el departamento en otro registro"
    }
    
#### 9.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "departamentoId": 16
    }

## 9.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/departamento/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido                              |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:------------------------------------------:|--------------------------------:|
| depa_id           | int          |                                |  Si                                        | ID del departamento |

### 9.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "depa_id": 16
	}

### 9.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 9.4.2.1.- Respuesta de error

	{
        "mensaje": "No existe el departamento"
    }
    
#### 9.4.2.2.- Respuesta de éxito

    {
        "mensaje": "eliminado"
    }


# 10.- Estado de Conexión
## 10.1.- Estados de Conexión
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/estadosconex`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| esco_id               | int          | ID del estado de conexión            |
| esco_descripcion      | string       | Descripción del estado de conexión               |
| esco_activo           | boolean      |                                                  |
| esco_orden            | int          |                                                  |
| esco_desconecta       | boolean      |                                                  |

### 10.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        null
	}

### 10.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 10.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 10.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "estados": [
            {
                "esco_id": 1,
                "esco_descripcion": "En Línea",
                "esco_activo": true,
                "esco_orden": 1,
                "esco_desconecta": true
            },
            {
                "esco_id": 2,
                "esco_descripcion": "Ausente",
                "esco_activo": true,
                "esco_orden": 2,
                "esco_desconecta": true
            },
            ...
    }

## 10.2.- Modificar Estado de Conexión
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/modificaestadoconex`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| usua_nombre       | string       |                                |  Si                     | Mail                            |
| esco_id           | int          |                                |  Si                     | ID del estado de conexión  |

### 10.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "usua_nombre": "NoAsignado@mail.com",
        "esco_id": 1
	}

### 10.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 10.2.2.1.- Respuesta de error

	{
        ...
    }
    
#### 10.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "validaEstado": true
    }


# 11.- FAQ
## 11.1.- Preguntas Frecuentes
## 11.1.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/faq/preguntas`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| preg_id               | int          | Coódigo interno de la pregunta                   |
| preg_tema             | string       | Enunciado de pregunta                            |
| preg_respuesta        | string       | Respuesta de pregunta                            |
| created_at            | timestamp    | Fecha de creación de la pregunta                 |
| updated_at            | timestamp    | Última fecha de modificación de la pregunta      |

### 11.1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 11.1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.1.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 11.1.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "preg_id": 1,
                "preg_tema": "¿En qué consiste la fibra Mundo?",
                "preg_respuesta": "La fibra Mundo consiste en una red descentralizada que se encuentra desplegada a nivel mundial, donde diferentes redes se interconecta con el fin de ofrecer múltiples servicios, así como recursos",
                "created_at": "2020-10-08T14:34:25.000000Z",
                "updated_at": "2020-10-09T12:46:31.000000Z"
            },
            ...
    }

## 11.1.2.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/preguntas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| preg_tema         | string       |                                |  Si                     | Enunciado de pregunta           |
| preg_respuesta    | string       |                                |  Si                     | Respuesta de pregunta           |


### 11.1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_tema": "¿Cómo puedo medir mi velocidad de navegación?",
        "preg_respuesta": "Para esta medición utiliza un computador conectado a cable de red.  Estas pruebas realizadas a través de un dispositivo móvil, tv, playstation, xbox u otro similar no permite la obtención de resultados reales."
	}

### 11.1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.1.2.2.1.- Respuesta de error

	{
        "mensaje": "Pregunta ya está registrada"
    }
  
#### 11.1.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 11.1.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/preguntas/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| preg_id           | int          |                                |  Si                     | ID de la pregunta frecuente  |
| preg_tema         | string       |                                |  Si                     | Enunciado de pregunta           |
| preg_respuesta    | string       |                                |  Si                     | Respuesta de pregunta           |


### 11.1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_id": 10,
        "preg_tema": "¿Cómo puedo medir mi velocidad de navegación correctamente?",
        "preg_respuesta": "Para esta medición utiliza un computador conectado a cable de red.  Estas pruebas realizadas a través de un dispositivo móvil, tv, playstation, xbox u otro similar no permite la obtención de resultados reales."
	}

### 11.1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.1.3.2.1.- Respuesta de error

	{
        "mensaje": "Pregunta ya está registrada"
    }
  
#### 11.1.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 11.1.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/preguntas/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| preg_id           | int          |                                |  Si                     | ID de la pregunta frecuente   |


### 11.1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_id": 10
	}

### 11.1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.1.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 11.1.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 11.2.- Preguntas Alternativas
## 11.2.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/faq/alternativas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| preg_id           | string       |                                |  Si                     | ID de la pregunta frecuente     |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| prega_id              | int          |                    |
| prega_descripcion     | string       |                    |
| preg_id               | int          | ID de la pregunta                    |
| created_at            | timestamp    | Fecha de creación de la pregunta                 |
| updated_at            | timestamp    | Última fecha de modificación de la pregunta      |
| prega_display         | string       |                    |

### 11.2.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_id": 1
	}

### 11.2.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 11.2.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "prega_id": 12,
                "prega_descripcion": "¿QUEESFIBRAMUNDO?",
                "preg_id": 1,
                "created_at": "2020-10-08T20:43:52.000000Z",
                "updated_at": "2020-10-15T18:43:19.000000Z",
                "prega_display": "¿que es fibra mundo?"
            },
            ...
    }

## 11.2.2.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/alternativas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:----------------------------------------------:|:-----------------------:|--------------------------------:|
| preg_id           | int          |                                                |  Si                     | ID de la pregunta frecuente     |
| prega_descripcion | string       | Todo en mayúsculas, sin espacios y sin acentos |  Si                     |           |
| prega_display     | string       |                                                |  Si                     | Respuesta de pregunta que se va visualizar|


### 11.2.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_id": 1,
        "prega_descripcion": "NOCUENTASCONCONEXIONWIFI?",
        "prega_display": "No cuentas con conexión WiFi?"
	}

### 11.2.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.2.2.1.- Respuesta de error

	{
        "mensaje": "Pregunta alternativa ya está registrada"
    }
  
#### 11.2.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 11.2.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/alternativas/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:----------------------------------------------:|:-----------------------:|--------------------------------:|
| preg_id           | int          |                                                |  Si                     | ID de la pregunta frecuente     |
| prega_id           | int          |                                                |  Si                     | ID de la pregunta alternativa   |
| prega_descripcion | string       | Todo en mayúsculas, sin espacios y sin acentos |  Si                     |           |
| prega_display     | string       |                                                |  Si                     | Respuesta de pregunta que se va visualizar|


### 11.2.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "preg_id": 1,
        "prega_id": 16,
        "prega_descripcion": "NOCUENTASCONCONEXIONWIFI?",
        "prega_display": "¿No cuentas con conexión WiFi?"
	}

### 11.2.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.3.2.1.- Respuesta de error

	{
        "mensaje": "Pregunta alternativa ya está registrada"
    }
  
#### 11.2.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 11.2.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/faq/alternativas/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| prega_id          | int          |                                |  Si                     | ID de la pregunta alternativa   |


### 11.2.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "prega_id": 16
	}

### 11.1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 11.2.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 11.2.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


# 12.- Grupos
## 12.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/grupos`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| configuracion     | string       |                                | opcional                |           |
| grup_id           | int          |                                | opcional                |           |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| grup_id               | int          | ID del grupo                              |
| grup_descripcion      | string       | Descripción del grupo                          |
| depa_id_departamentos | int          |                              |
| grup_feriado          | string       |                          |
| grup_cantidad_ticket  | int          |                              |
| grup_bloquea_horario  | boolean      |                           |
| grup_auto_asigna      | boolean      |                               |
| grup_reasigna         | boolean      |                          |
| grup_toma_otro        | boolean      |                               |
| grup_usa_auxiliar1    | boolean      |                          |
| grup_usa_auxiliar2    | boolean      |                               |
| grup_auxiliar1_nombre | string       |                          |
| grup_auxiliar2_nombre | string       |                               |
| grup_no_traspasar     | boolean      |                          |
| depa_id               | int          | ID del departamento                              |
| depa_descripcion      | string       | Nombre del departamento                          |

### 12.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        null
	}

### 12.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 12.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "grupos": [
            {
                "grup_id": 8,
                "grup_descripcion": "grupo 1",
                "depa_id_departamentos": 10,
                "grup_feriado": null,
                "grup_cantidad_ticket": 10,
                "grup_bloquea_horario": false,
                "grup_auto_asigna": false,
                "grup_reasigna": false,
                "grup_toma_otro": false,
                "grup_usa_auxiliar1": false,
                "grup_usa_auxiliar2": false,
                "grup_auxiliar1_nombre": null,
                "grup_auxiliar2_nombre": null,
                "grup_no_traspasar": false,
                "departamento": {
                    "depa_id": 10,
                    "depa_descripcion": "departamento - 1"
                }
            },
            ...
    }

## 12.2.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/grupos`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_descripcion  | string       |                                |  Si                     | Nombre del grupo         |
| depa_id           | int          |                                |  Si                     | ID del departamento         |
| grup_feriado      | boolean      |                                |  Si                     |         |

### 12.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_descripcion": "Ventas Empresa Prueba",
        "depa_id": 3,
        "grup_feriado": true
	}

### 12.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.2.2.1.- Respuesta de error

	{
        "mensaje": "Grupo ya existe para este departamento",
        "grup_id": 0
    }
    
#### 12.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "grup_id": 16
    }

## 12.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/grupos/update`

**Parámetros de entrada:**
| Campo                |  Tipo        | Formato                        |     Requerido                              |             Descripción         |
|:--------------------:|:------------:|:------------------------------:|:------------------------------------------:|--------------------------------:|
| grup_id              | int          |                                |  Si                                        | ID del departamento             |
| grup_auto_asigna     | int          |                                |  Si                                        | ID del departamento             |
| grup_reasigna        | int          |                                |  Si                                        | ID del departamento             |
| grup_toma_otro       | int          |                                |  Si                                        | ID del departamento             |
| configuracion        | int          |                                |  Si                                        | ID del departamento             |
| grup_usa_auxiliar1   | int          |                                |  Si                                        | ID del departamento             |
| grup_usa_auxiliar2   | int          |                                |  Si                                        | ID del departamento             |
| grup_auxiliar1_nombre| int          |                                |  Si                                        | ID del departamento             |
| grup_auxiliar2_nombre| int          |                                |  Si                                        | ID del departamento             |

### 12.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "depa_id": 16,
        "depa_descripcion": "Contabilidad Modificado"
	}

### 12.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.3.2.1.- Respuesta de error

	{
        "mensaje": "Ya existe el departamento en otro registro"
    }
    
#### 12.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "departamentoId": 16
    }

## 12.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/grupos/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido                              |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:------------------------------------------:|--------------------------------:|
| grup_id           | int          |                                |  Si                                        | ID del grupo |

### 12.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 16
	}

### 12.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.4.2.1.- Respuesta de error

	{
        "mensaje": "No existe el grupo"
    }
    
#### 12.4.2.2.- Respuesta de éxito

    {
        "mensaje": "eliminado"
    }

# 13.- Grupo Usuario
## 13.1.- getGrupoByUser
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/grupousuario`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| usua_id           | int          |                                | Si                      |  ID del usuario                 |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| grup_id               | int          | ID del grupo                              |
| grup_descripcion      | string       | Descripción del grupo                          |
| depa_descripcion      | string       |                              |
| existe                | boolean      |                          |
| usuario               | string       |                              |

### 13.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "usua_id": 1
	}

### 13.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 13.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 13.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "grup_id": 8,
                "grup_descripcion": "grupo 1",
                "depa_descripcion": "departamento - 1",
                "existe": false,
                "usuario": "1"
            },
            ...
    }

## 13.2.- Asignación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/grupousuario`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_id           | int          |                                |  Si                     | ID del grupo                    |
| usua_id           | int          |                                |  Si                     | ID del usuario                  |

### 13.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1,
        "usua_id": 1
	}

### 13.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 13.2.2.1.- Respuesta de error

	{
        ...
    }
    
#### 13.2.2.2.- Respuesta de éxito

    {
        "mensaje": "registrado"
    }


# 14.- Horarios
## 14.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/horarios`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_id           | int          |                                | Si                      |  ID del grupo                   |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| hora_id               | int          | ID de                                            |
| hora_dia              | int          | Número de día                                    |
| hora_ini              | datetime     | Hora de inicio                                   |
| hora_fin              | datetime     | Hora de fin                                      |
| grup_id               | int          | ID del grupo                                     |
| created_at            | timestamp    | Fecha de creación                                |
| updated_at            | timestamp    | Fecha de última actualización                    |

### 14.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1
	}

### 14.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 14.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 14.1.2.2.- Respuesta de éxito

    {
        "mensajes": "ok",
        "dias": [
            {
                "hora_id": 1,
                "hora_dia": 0,
                "hora_ini": "00:00:01",
                "hora_fin": "22:00:00",
                "grup_id": 1,
                "created_at": "2020-10-16T14:47:17.000000Z",
                "updated_at": "2020-10-29T17:57:55.000000Z"
            },
            {
                "hora_id": 7,
                "hora_dia": 6,
                "hora_ini": "00:00:01",
                "hora_fin": "22:00:00",
                "grup_id": 1,
                "created_at": "2020-10-16T14:47:17.000000Z",
                "updated_at": "2020-10-29T17:57:55.000000Z"
            },
            ...
    }

## 14.2.- Store
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/horarios`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_id           | int          |                                |  Si                     | ID del grupo                    |
| hora_dia          | int          |                                |  Si                     | Número de día                   |
| hora_ini          | int          |                                |  Si                     | Hora de inicio                  |
| hora_fin          | int          |                                |  Si                     | Hora de fin                     |

### 14.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id":1,
        "dias": [
            {
                "hora_dia": 0,
                "hora_ini": "09:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 1,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 2,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 3,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 4,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 5,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            },
            {
                "hora_dia": 6,
                "hora_ini": "08:30",
                "hora_fin": "23:00"
            }
        ]
    }
### 14.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 14.2.2.1.- Respuesta de error

	{
        ...
    }
    
#### 14.2.2.2.- Respuesta de éxito

    {
        "mensajes": "ok"
    }


# 15.- Hubspot
## 15.1.- Hubspot
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/hubspot`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
|                   |              |                                |                         |                                 |

### 15.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 15.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 15.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 15.1.2.2.- Respuesta de éxito

    {
            ...
    }

## 15.2.- Store
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/hubspot/sendmail`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| to                | string       |                                |  Si                     | Email del destinatario          |
| mensaje           | string       |                                |  Si                     | Contenido del mensaje           |

### 15.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "to": "carlos.fernandez.b@mundopacifico.cl",
        "mensaje": "Prueba" 
    }
### 15.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 15.2.2.1.- Respuesta de error

	{
        ...
    }
    
#### 15.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


# 16.- Integración CRM
## 16.1.- Crear Cliente
## 16.1.1.- Crear Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/crearCliente`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| numDocumentacion  | string       | 123456789                      | Si                      | Rut del cliente                 |
| nombre            | string       |                                | Si                      | Nombre del cliente              |
| apellido1         | string       |                                | Si                      | Apellido paterno del cliente    |
| apellido2         | string       |                                | Si                      | Apellido materno del cliente    |
| sexo              | int          | 0 = hombre, 1 = mujer          |                         | Sexo del cliente                |
| telefono          | int          |                                |                         | Teléfono del cliente            |
| fechaNacimiento   | string       | YYYY-mm-dd                     |                         | Fecha de nacimiento del cliente |
| correo            | string       |                                |                         | Correo electrónico del cliente  |
| codigoPostal      | int          |                                |                         | Código postal del domicilio del cliente  |
| localidad         | string       |                                |                         | Localidad del domicilio del cliente  |
| tipoVia           | int          |                                |                         |                                 |
| direccion         | string       |                                |                         | Calle del domicilio del cliente |
| numero            | int          |                                |                         | Número del domicilio del cliente |
| piso              | int          |                                |                         | Número de piso del domicilio del cliente  |
| puerta            | int          |                                |                         | Número de puerta del domicilio del cliente|
| bloque            | int          |                                |                         | Número de bloque del domicilio del cliente|
| acceso            | int          |                                |                         | Número de acceso del domicilio del cliente|
| actividadProfesional| int        |                                |                         | ID de la actividad profesional del cliente|

### 16.1.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "cliente": {
            "codigo": "200",
            "mensaje": "OK.",
            "object": {
                "id": 1178278,
                "numDocumentacion": "191403991",
                "tipoDocumento": 5,
                "segmentacion": {
                    "id": 1178278,
                    "fuente": {
                        "id": 1
                    },
                    "segmento": {
                        "id": 1
                    }
                },
                "contactoPrincipal": {
                    "id": 1187174,
                    "nombre": "Carlos",
                    "apellido1": "Fernández",
                    "apellido2": "Barra",
                    "sexo": 0,
                    "cargo": {
                        "id": 3
                    },
                    "fechaNacimiento": {
                        "year": 1996,
                        "month": "AUGUST",
                        "monthValue": 8,
                        "dayOfMonth": 13,
                        "chronology": {
                            "calendarType": "iso8601",
                            "id": "ISO"
                        },
                        "dayOfWeek": "TUESDAY",
                        "era": "CE",
                        "dayOfYear": 226,
                        "leapYear": true
                    },
                    "telefono": "1234567",
                    "movil": "1234567",
                    "email": "carlos.fernandez.b@mundopacifico.cl",
                    "esPrincipal": true,
                    "delegaciones": [
                        {
                            "id": 2016562,
                            "nombre": "Carlos",
                            "via": 4,
                            "direccion": "Calle",
                            "numero": "7932",
                            "codigoPostal": {
                                "id": 75761,
                                "codigoPostal": "4130000",
                                "valorCampo1": "San Pedro De La Paz",
                                "valorCampo2": "San Pedro De La Paz",
                                "valorCampo3": "Concepción",
                                "valorCampo4": "Biobío"
                            },
                            "latitud": -36.850753,
                            "longitud": -73.1479217,
                            "esPrincipal": true,
                            "esFiscal": true,
                            "esEnvio": true,
                            "esInstalacion": false
                        }
                    ],
                    "esFiscal": true,
                    "esEnvio": true
                },
                "delegacionPrincipal": {
                    "id": 2016562,
                    "nombre": "Carlos",
                    "via": 4,
                    "direccion": "Calle",
                    "numero": "7932",
                    "codigoPostal": {
                        "id": 75761,
                        "codigoPostal": "4130000",
                        "valorCampo1": "San Pedro De La Paz",
                        "valorCampo2": "San Pedro De La Paz",
                        "valorCampo3": "Concepción",
                        "valorCampo4": "Biobío"
                    },
                    "latitud": -36.850753,
                    "longitud": -73.1479217,
                    "esPrincipal": true,
                    "esFiscal": true,
                    "esEnvio": true,
                    "esInstalacion": false
                },
                "actividadProfesional": {
                    "id": 57
                },
                "nombre": "Carlos",
                "apellido1": "Fernández",
                "apellido2": "Barra",
                "sexo": 0
            }
        }
    }


## 16.1.2.- Crear Cliente Empresa
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/crearClienteEmpresa`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
|                   |              |                                |                         |                                 |

### 16.1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.2.2.2.- Respuesta de éxito

    {
            ...
    }