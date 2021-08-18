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
    - [18.5.- Sucursal](#185--sucursal)
        - [18.5.1.- Ejemplo de llamada](#1851--ejemplo-de-llamada)
        - [18.5.2.- Respuesta de Salida](#1852--respuesta-de-salida)
            - [18.5.2.1- Respuesta de error](#18521--respuesta-de-error)
            - [18.5.2.2- Respuesta de éxito](#18522--respuesta-de-éxito)
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
        ...
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

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| departamentoId        | int          | ID del departamento creado                       |

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

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| departamentoId        | int          | ID del departamento modificado                   |

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

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| validaEstado          | boolean      | ??                  |

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

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| grup_id               | int          | ID del grupo creado                       |

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
| grup_id              | int          |                                |  Si                                        | ??             |
| grup_auto_asigna     | boolean      |                                |  Si                                        | ??             |
| grup_reasigna        | boolean      |                                |  Si                                        | ??             |
| grup_toma_otro       | boolean      |                                |  Si                                        | ??             |
| configuracion        | string       |                                |  Si                                        | ??             |
| grup_usa_auxiliar1   | boolean      |                                |  Si                                        | ??             |
| grup_usa_auxiliar2   | boolean      |                                |  Si                                        | ??             |
| grup_auxiliar1_nombre| string       |                                |  Si                                        | ??             |
| grup_auxiliar2_nombre| string       |                                |  Si                                        | ??             |

### 12.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1,
        "grup_auto_asigna": true,
        "grup_reasigna": true,
        "grup_toma_otro": true,
        "configuracion": "S",
        "grup_usa_auxiliar1": true,
        "grup_usa_auxiliar2": true,
        "grup_auxiliar1_nombre": "Tecnología",
        "grup_auxiliar2_nombre": "Comuna"
	}

### 12.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 12.3.2.1.- Respuesta de error

	{
        ...
    }
    
#### 12.3.2.2.- Respuesta de éxito

    {
        ...
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
        "numDocumentacion": "191403991",
        "nombre": "Carlos",
        "apellido1": "Fernández",
        "apellido2": "Barra",
        "sexo": 0,
        "telefono": 123456789,
        "fechaNacimiento": "1996-08-13",
        "correo": "carlos.fernandez.b@mundopacifico.cl",
        "codigoPostal": 4130000,
        "localidad": "San Pedro de la Paz",
        "tipoVia": 4,
        "direccion": "Prueba",
        "numero": 1051,
        "piso": 0,
        "puerta": 0,
        "bloque": 0,
        "acceso": 0,
        "actividadProfesional": 882
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
| codigoPostal      | int          |                                |                         | Código postal del domicilio de la empresa  |
| localidad         | string       |                                |                         | Localidad del domicilio de la empresa  |
| sexo              | int          | 0 = hombre, 1 = mujer          |                         | Sexo de la empresa              |
| telefono          | int          |                                |                         | Teléfono de la empresa          |
| correo            | string       |                                |                         | Correo electrónico de la empresa|
| direccion         | string       |                                |                         | Calle del domicilio de la empresa |
| numero            | int          |                                |                         | Número del domicilio de la empresa |
| piso              | int          |                                |                         | Número de piso del domicilio de la empresa  |
| nombre            | string       |                                |                         | Nombre de la empresa  |
| razonSocial       | string       |                                |                         | Razón social de la empresa  |
| puerta            | int          |                                |                         | Número de puerta del domicilio de la empresa|
| bloque            | int          |                                |                         | Número de bloque del domicilio de la empresa|
| acceso            | int          |                                |                         | Número de acceso del domicilio de la empresa|
| numDocumentacion  | string       |                                |                         | Rut de la empresa|
| actividad         | int          |                                |                         | Rubro de la empresa|
| esEmprendedor     | int          | 1 = si, 0 = no                 |                         | Si la empresa corresponde o no a un emprendimiento|

### 16.1.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoPostal": 4130000,
        "localidad": ""SAN PEDRO DE LA PAZ,
        "sexo": 0,
        "telefono": 2313123,
        "correo": "carlos.fernandez.b@mundopacifico.cl",
        "direccion": "Prueba",
        "numero": 1051,
        "piso": 2,
        "nombre": EmpresaTest,
        "razonSocial": EmpresaTest ltda,
        "puerta": 1,
        "bloque": 1,
        "acceso": 1,
        "numDocumentacion": 216664590,
        "actividad": 888,
        "esEmprendedor": 1,
	}

### 16.1.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "cliente": {
            "codigo": "200",
            "mensaje": "OK.",
            "object": {
                "id": 1178909,
                "numDocumentacion": "216664590",
                "tipoDocumento": 5,
                "segmentacion": {
                    "id": 1178909,
                    "fuente": {
                        "id": 1
                    },
                    "segmento": {
                        "id": 1
                    }
                },
                "contactoPrincipal": {
                    "id": 1187813,
                    "nombre": "EmpresaTest",
                    "sexo": 0,
                    "cargo": {
                        "id": 4
                    },
                    "telefono": "2313123",
                    "movil": "2313123",
                    "email": "carlos.fernandez.b@mundopacifico.cl",
                    "esPrincipal": true,
                    "delegaciones": [
                        {
                            "id": 2017980,
                            "nombre": "EmpresaTest",
                            "via": 4,
                            "direccion": "Prueba",
                            "numero": "1051",
                            "piso": "2",
                            "puerta": "1",
                            "codigoPostal": {
                                "id": 75761,
                                "codigoPostal": "4130000",
                                "valorCampo1": "San Pedro De La Paz",
                                "valorCampo2": "San Pedro De La Paz",
                                "valorCampo3": "Concepción",
                                "valorCampo4": "Biobío"
                            },
                            "latitud": -36.8305354,
                            "longitud": -73.1167368,
                            "esPrincipal": true,
                            "esFiscal": true,
                            "esEnvio": true,
                            "bloque": "1",
                            "acceso": "1",
                            "esInstalacion": false
                        }
                    ],
                    "esFiscal": true,
                    "esEnvio": true
                },
                "delegacionPrincipal": {
                    "id": 2017980,
                    "nombre": "EmpresaTest",
                    "via": 4,
                    "direccion": "Prueba",
                    "numero": "1051",
                    "piso": "2",
                    "puerta": "1",
                    "codigoPostal": {
                        "id": 75761,
                        "codigoPostal": "4130000",
                        "valorCampo1": "San Pedro De La Paz",
                        "valorCampo2": "San Pedro De La Paz",
                        "valorCampo3": "Concepción",
                        "valorCampo4": "Biobío"
                    },
                    "latitud": -36.8305354,
                    "longitud": -73.1167368,
                    "esPrincipal": true,
                    "esFiscal": true,
                    "esEnvio": true,
                    "bloque": "1",
                    "acceso": "1",
                    "esInstalacion": false
                },
                "actividad": {
                    "id": 888
                },
                "razonSocial": "EmpresaTest",
                "tipoCliente": 1
            }
        }
    }

## 16.1.3.- Fuente y Segmentación
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/fuente`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | ID de                                            |
| nombre                | string       | Número de día                                    |

### 16.1.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.3.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "fuentes": [
                    {
                        "id": 5,
                        "nombre": "Activación Marketing"
                    },
                    {
                        "id": 11,
                        "nombre": "Convertia"
                    },
                    {
                        "id": 9,
                        "nombre": "Funcionario MP"
                    },
                    ...
                ],
                "segmentos": [
                    {
                        "id": 13,
                        "nombre": "A"
                    },
                    {
                        "id": 10,
                        "nombre": "B"
                    },
                    {
                        "id": 12,
                        "nombre": "C"
                    },
                    ...
                ]
            }
        },
        "codigo": 200
    }
    

## 16.1.4.- Actividades Profesionales
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/actividadesprof`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | ID de la actividad profesional                   |
| descripcion           | string       | Nombre de la actividad profesional               |
| codigo                | string       | Código de la actividad profesional               |

### 16.1.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.4.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "actividades": [
                    {
                        "id": 1,
                        "descripcion": "Abogado",
                        "codigo": "001"
                    },
                    {
                        "id": 2,
                        "descripcion": "Administrativo",
                        "codigo": "002"
                    },
                    {
                        "id": 3,
                        "descripcion": "Agricultor",
                        "codigo": "003"
                    },
                    ...
                ]
            }
        },
        "codigo": 200
    }

## 16.1.5.- Cargos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/cargos`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | ID del cargo                                     |
| descripcion           | string       | Descripción del cargo                            |

### 16.1.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.5.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "cargos": [
                    {
                        "id": 4,
                        "descripcion": "Contacto"
                    },
                    {
                        "id": 2,
                        "descripcion": "Influyente"
                    },
                    {
                        "id": 3,
                        "descripcion": "Titular / Administrador"
                    }
                ]
            }
        },
        "codigo": 200
    }


## 16.1.6.- Tipo Vía
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/tipoVia`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| value                 | int          | ID del tipo de vía                               |
| label                 | string       | Nombre del tipo de vía                           |

### 16.1.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.1.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.6.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.6.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "tipoVia": [
                    {
                        "value": 0,
                        "label": "Acera"
                    },
                    {
                        "value": 1,
                        "label": "Autopista"
                    },
                    {
                        "value": 2,
                        "label": "Autovía"
                    },
                    {
                        "value": 3,
                        "label": "Avenida"
                    },
                    ...
                ]
            }
        },
        "codigo": 200
    }


## 16.1.7.- Localidades
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/localidades`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| codigoPostal      | int          |                                |                         | Código postal a buscar          |


**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| localidades           |              | Lista con las localidades encontradas            |

### 16.1.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoPostal": 4130000
	}

### 16.1.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.7.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.7.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "localidades": [
                    "Andalué",
                    "El Venado",
                    "Gran Concepcion (p)",
                    "Gran Concepción",
                    "Lagunillas",
                    "Lomas Coloradas",
                    "Los Pinares",
                    "Monteáguila",
                    "San Pedro De La Paz"
                ]
            }
        },
        "codigo": 200
    }


## 16.1.8.- Comunas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/beyond/comuna`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| codigoPostal      | int          |                                |                         | Código postal a buscar          |
| localidad         | string       |                                |                         | Localidad a buscar              |


**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| comuna                | string       | Comuna encontrada                                |

### 16.1.8.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "codigoPostal": 4130000,
        "localidad": "San Pedro de la Paz"
	}

### 16.1.8.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.1.8.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.1.8.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "comuna": "San Pedro De La Paz"
            }
        },
        "codigo": 200
    }

## 16.2.- Ofertas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/ofertas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| tick_id           | int          |                                | Si                      |  ID del ticket                  |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | ID de                                            |
| codigoMp              | string       | Código de                                        |
| estado                | string       | Estado de                                        |
| direccion             | string       | Dirección del                                    |
| numero                | string       | Número del                                       |
| campoDireccion1       | string       | Ciudad                                           |
| campoDireccion4       | string       | Región                                           |
| nodo                  | string       | Nodo                                             |
| direccioncomp         | string       | Dirección completa del domicilio                 |
| tipoOferta            | string       | Tipo de plan/oferta                              |
| detalle               | string       | Detalle oferta                                   |
| clienteId             | int          | ID del cliente                                   |
| servicios             |              | Listado de servicios                             |
| servicios->id         | int          | ID del servicio                                  |
| servicios->descripcion| string       | Descripción del servicio                         |
| servicios->tipoProducto| string      | Tipo de servicio                                 |
| terminales            |              | Listado de terminales                            |
| terminales->descripcion| string      | Descripción del terminal                         |
| terminales->NumeroSerie| string      | Número de serie del terminal                     |

### 16.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 710
	}

### 16.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.2.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "mensaje": "ok",
                "DataFormat": [
                    {
                        "id": 1068557,
                        "codigoMp": "MP20/0552091",
                        "estado": "Conectado",
                        "direccion": "VICENTE PALACIOS",
                        "numero": "2678",
                        "campoDireccion1": "TOME",
                        "campoDireccion4": "BIOBIO",
                        "nodo": "TOME_90",
                        "direccioncomp": "VICENTE PALACIOS 2678 TOME",
                        "tipoOferta": "Mundo Fijo",
                        "detalle": "FIBRA + TV",
                        "clienteId": 464092,
                        "servicios": [
                            {
                                "id": 601,
                                "descripcion": "Televisión Básica FTTH",
                                "tipoProducto": "TV"
                            },
                            {
                                "id": 596,
                                "descripcion": "500/500 Mb",
                                "tipoProducto": "Internet"
                            },
                            {
                                "id": 43,
                                "descripcion": "Ampliación cobertura wifi interior",
                                "tipoProducto": "Servicios conexos"
                            }
                        ],
                        "terminales": [
                            {
                                "descripcion": "ONT HUAWEI EG 8247 Q",
                                "NumeroSerie": "4857544391C6079F"
                            }
                        ]
                    },
                    ...
                ],
                "error": ""
            }
        },
        "codigo": 200
    }


## 16.3.- Tareas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/tareas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| tick_id           | int          |                                | Si                      |  ID del ticket                  |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| identificador         | string       | Identificador de la tarea                        |
| estado                | string       | Estado de la tarea                               |
| motivo                | string       | Motivo de la tarea                               |
| tipoTarea             | string       | Tipo de tarea                                    |
| fechaHoraInicio       | string       | Fecha y hora de inicio                           |
| fechaHoraFin          | string       | Fecha y hora de fin                              |

### 16.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 710
	}

### 16.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "tareas": [
            {
                "identificador": "TAR20/4619318",
                "estado": "Cerrado",
                "motivo": "Servicios Conexos",
                "tipoTarea": "Op - Alta Adicional",
                "fechaHoraInicio": "2020-12-22 11:10:00",
                "fechaHoraFin": "2020-12-22 12:14:25"
            },
            ...
        ]
    }

## 16.4.- Crear Tarea Oferta
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/crearTareaOferta`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| idOferta          | int          |                                | Si                      |  ID de la oferta                |
| clienteID         | int          |                                | Si                      |  ID del cliente                 |
| usuarioBeyond     | int          |                                | Si                      |  ID del usuario de beyond       |
| observacion       | string       |                                | Si                      |  Observación respecto de la tarea|
| fechaHoraInicio   | string       | dd/mm/YYYY hh:mm:ss            | Si                      |  Fecha y hora de la tarea       |
| estadoTareaId     | int          |                                | Si                      |  ID del estado de la tarea      |
| motivoTarea       | int          |                                | Si                      |  ID del motivo de la tarea      |
| tipoTarea         | int          |                                | Si                      |  ID del tipo de tarea           |
| mailusuario       | string       |                                | Si                      |  Correo electrónico del usuario |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
|                      |               | ?                                                |

### 16.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idOferta": 547933,
        "clienteID": 690950,
        "usuarioBeyond": 2269,
        "observacion": "Crear Tarea desde mundo social",
        "fechaHoraInicio": "18/11/2020 09:05:00",
        "estadoTareaId": 22,
        "motivoTarea": 297,
        "tipoTarea": 35,
        "mailusuario": "carlos.fernandez.b@mundopacifico.cl",
	}

### 16.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "tarea": {
            "codigo": "200",
            "mensaje": "OK.",
            "object": {
                "tarea": {
                    "id": 9273088,
                    "identificador": "TAR21/3376015",
                    "estadoTarea": {
                        "id": 22,
                        "motivoTarea": [
                            {
                                "id": 297,
                                "tipoTarea": {
                                    "id": 35
                                }
                            }
                        ]
                    },
                    "fechaHoraInicio": {
                        "dayOfWeek": "WEDNESDAY",
                        "dayOfYear": 323,
                        "monthValue": 11,
                        "dayOfMonth": 18,
                        "hour": 9,
                        "minute": 5,
                        "second": 0,
                        "nano": 0,
                        "year": 2020,
                        "month": "NOVEMBER",
                        "chronology": {
                            "calendarType": "iso8601",
                            "id": "ISO"
                        }
                    },
                    "observacion": "Crear Tarea desde mundo social",
                    "informarCliente": false,
                    "gestionadoPor": {
                        "id": 1868
                    },
                    "usuario": {
                        "id": 1868
                    },
                    "evento": {
                        "id": 9294245
                    },
                    "cliente": {
                        "id": 690950
                    },
                    "editableMotivoEstado": false,
                    "aceptacion": "PENDIENTE_ACEPTACION",
                    "rol": {
                        "id": 171,
                        "descripcion": "Ejecutivo Bienvenida"
                    },
                    "contactosAEnviar": []
                },
                "idOfertaOp": 547933
            }
        },
        "info": "creada"
    }


## 16.5.- Tipos de Tareas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/tipostareas`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | Identificador de la tarea                        |
| nombre                | string       | Nombre de la tarea                               |

### 16.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 16.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.5.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "id": 58,
                "nombre": "Agente T. - Actividad"
            },
            {
                "id": 123,
                "nombre": "Aplicación de Exentos"
            },
            {
                "id": 35,
                "nombre": "Bienvenida"
            },
            ...
        ]
    }

## 16.6.- Motivos de Tareas
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/motivoTareas`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| idTipoTarea       | int          |                                | Si                      |  ID del tipo de tarea           |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| id                    | int          | Identificador del motivo                        |
| nombre                | string       | Nombre del motivo                               |
| tipoTarea             |              | Lista con el tipo de tarea                      |
| tipoTarea->id         | int          | Identificador del tipo de tarea                 |
| tipoTarea->nombre     | int          | Nombre del tipo de tarea                        |
| tiposActividad        | int          | Lista con el tipo de tarea                      |
| tieneSlo              | boolean      |                         |
| tieneSla              | boolean      |                         |
| tipoSla               | boolean      |                         |
| bloqueoSla            | boolean      |                         |
| unidadTiempoSla       | string       | Unidad de tiempo                                |
| tiempoSla             | int          |                         |
| habilSla              | boolean      |                         |
| rolesNoAutorizados    |              | Lista con roles no autorizados                  |
| ubicacionesAsociadas  |              | Lista con ubicaciones asociadas                 |
| flujoSecuencial       | boolean      |                         |

### 16.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "idTipoTarea": 36
	}

### 16.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 16.6.2.1.- Respuesta de error

	{
        ...
    }
  
#### 16.6.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "id": 234,
                "nombre": "Gestión Comercial",
                "tipoTarea": {
                    "id": 36,
                    "nombre": "Contención RRSS"
                },
                "tiposActividad": [],
                "tieneSlo": false,
                "tieneSla": true,
                "tipoSla": false,
                "bloqueoSla": false,
                "unidadTiempoSla": "Dias",
                "tiempoSla": 1,
                "habilSla": false,
                "rolesNoAutorizados": [],
                "ubicacionesAsociadas": [],
                "flujoSecuencial": false
            },
            ...
        ]
    }


# 17.- Listar Tickets
## 17.1.- Listar Tickets
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/mensajes`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| page              | int          |                                |                         | Número de página                |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombre del cliente?                              |
| cacl_identificador    | string       | email?                                           |
| tick_id               |  int         | ID del ticket                                    |
| tick_fecha_creacion   | timestamp    | Fecha de creación del ticket                     |
| tick_fecha_asignacion | timestamp    | Fecha de asignación del ticket                   |
| esta_descripcion      | string       | Descripción del ticket                           |
| usua_id               | int          | ID del usuario                                   |
| usua_nombre           | string       | Nombre del usuario                               |
| cana_id               | int          | ID del ?                                         |
| alerta                | boolean      |                                                  |

### 17.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "page": 1
	}

### 17.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 17.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "current_page": 1,
            "data": [
                {
                    "clie_nombre": "Pedro",
                    "cacl_identificador": "mail@mail.com",
                    "tick_id": 718,
                    "tick_fecha_creacion": "2021-08-13 16:37:11",
                    "tick_fecha_asignacion": null,
                    "esta_descripcion": "CERRADO",
                    "usua_id": 1,
                    "usua_nombre": "NoAsignado@mail.com",
                    "cana_id": 4,
                    "alerta": false
                },
                ...
            ],
            "first_page_url": "...URL/api/mundosocial/mensajes?page=1",
            "from": 1,
            "last_page": 24,
            "last_page_url": "...URL/api/mundosocial/mensajes?page=24",
            "next_page_url": "...URL/api/mundosocial/mensajes?page=2",
            "path": "URL/api/mundosocial/mensajes",
            "per_page": 25,
            "prev_page_url": null,
            "to": 25,
            "total": 577
        }
    }


## 17.2.- Cola Tickets
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/colatickets`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| mail              | string       |                                | Si                      | Correo electrónico de ?          |
| page              | int          |                                |                         | Número de página                |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombre del cliente?                              |
| cacl_identificador    | string       | email?                                           |
| tick_id               |  int         | ID del ticket                                    |
| tick_fecha_creacion   | timestam     | Fecha de creación del ticket                     |
| tick_fecha_asignacion | timestamp    | Fecha de asignación del ticket                   |
| esta_descripcion      | string       | Descripción del ticket                           |
| usua_id               | int          | ID del usuario                                   |
| usua_nombre           | string       | Nombre del usuario                               |
| cana_id               | int          | ID del ?                                         |
| alerta                | boolean      |                                                  |
| tick_ultimo_msj_cliente| timestamp   | Fecha del último mensaje                         |
| grup_auto_asigna      | boolean      |                                                  |
| cuen_descripcion      | string       |                                                  |
| cuen_identificador    | string       |                                                  |

### 17.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com",
        "page": 1
	}

### 17.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 17.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "current_page": 1,
            "data": [
                {
                    "clie_nombre": "PENDIENTE",
                    "cacl_identificador": "prueba@mail.com",
                    "tick_id": 716,
                    "tick_fecha_creacion": "2021-08-13 16:32:09",
                    "tick_fecha_asignacion": null,
                    "esta_descripcion": "No asignado",
                    "usua_id": 1,
                    "usua_nombre": "NoAsignado@mail.com",
                    "cana_id": 4,
                    "alerta": false,
                    "tick_ultimo_msj_cliente": "2021-08-13 16:32:09",
                    "grup_auto_asigna": false,
                    "cuen_descripcion": "MAIL SOPORTE",
                    "cuen_identificador": "prueba@mundopacifico.cl"
                },
                ...
            ],
            "first_page_url": "...URL/api/mundosocial/colatickets?page=1",
            "from": 1,
            "last_page": 5,
            "last_page_url": "...URL/api/mundosocial/colatickets?page=5",
            "next_page_url": "...URL/api/mundosocial/colatickets?page=2",
            "path": "...URL/api/mundosocial/colatickets",
            "per_page": 25,
            "prev_page_url": null,
            "to": 25,
            "total": 106
        },
        "hoy": 0,
        "orden": "Desc"
    }


## 17.3.- Mis Tickets en Proceso
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/misticketsenproceso`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| mail              | string       |                                | Si                      | Correo electrónico de ?          |
| page              | int          |                                |                         | Número de página                |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombre del cliente?                              |
| cacl_identificador    | string       | email?                                           |
| tick_id               |  int         | ID del ticket                                    |
| tick_fecha_creacion   | timestam     | Fecha de creación del ticket                     |
| tick_fecha_asignacion | timestamp    | Fecha de asignación del ticket                   |
| esta_descripcion      | string       | Descripción del ticket                           |
| usua_id               | int          | ID del usuario                                   |
| usua_nombre           | string       | Nombre del usuario                               |
| cana_id               | int          | ID del ?                                         |
| alerta                | boolean      |                                                  |
| tick_ultimo_msj_cliente| timestamp   | Fecha del último mensaje                         |
| cuen_descripcion      | string       |                                                  |
| cuen_identificador    | string       |                                                  |

### 17.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com",
        "page": 1
	}

### 17.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 17.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "current_page": 1,
            "data": [
                {
                    "clie_nombre": "PENDIENTE",
                    "cacl_identificador": "158056|Daniel Enrique Bustos Romero",
                    "tick_id": 667,
                    "tick_fecha_creacion": "2021-06-10 19:39:54",
                    "tick_fecha_asignacion": "2021-06-10 19:40:52",
                    "esta_descripcion": "ASIGNADO",
                    "usua_id": 2,
                    "usua_nombre": "daniel.bustos@prueba.com",
                    "cana_id": 2,
                    "alerta": false,
                    "tick_ultimo_msj_cliente": "2021-06-10 19:39:54",
                    "cuen_descripcion": "msn MundoCl",
                    "cuen_identificador": "tumundo.cl"
                },
                ...
            ],
            "first_page_url": "...URL/api/mundosocial/misticketsenproceso?page=1",
            "from": 1,
            "last_page": 1,
            "last_page_url": "...URL/api/mundosocial/misticketsenproceso?page=1",
            "next_page_url": null,
            "path": "...URL/api/mundosocial/misticketsenproceso",
            "per_page": 1000,
            "prev_page_url": null,
            "to": 13,
            "total": 13
        },
        "hoy": 0
    }


## 17.4.- Mis Tickets Cerrados
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/misticketscerrados`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| mail              | string       |                                | Si                      | Correo electrónico de ?          |
| page              | int          |                                |                         | Número de página                |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombre del cliente?                              |
| cacl_identificador    | string       | email?                                           |
| tick_id               |  int         | ID del ticket                                    |
| tick_fecha_creacion   | timestam     | Fecha de creación del ticket                     |
| tick_fecha_asignacion | timestamp    | Fecha de asignación del ticket                   |
| esta_descripcion      | string       | Descripción del ticket                           |
| usua_id               | int          | ID del usuario                                   |
| usua_nombre           | string       | Nombre del usuario                               |
| cana_id               | int          | ID del ?                                         |
| alerta                | boolean      |                                                  |
| tick_ultimo_msj_cliente| timestamp   | Fecha del último mensaje                         |
| cuen_descripcion      | string       |                                                  |
| cuen_identificador    | string       |                                                  |

### 17.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com",
        "page": 1
	}

### 17.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 17.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 17.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "current_page": 1,
            "data": [
                {
                    "clie_nombre": "daniel",
                    "cacl_identificador": "158056|Daniel Enrique Bustos Romero",
                    "tick_id": 664,
                    "tick_fecha_creacion": "2021-06-10 19:01:00",
                    "tick_fecha_asignacion": null,
                    "esta_descripcion": "CERRADO",
                    "usua_id": 2,
                    "usua_nombre": "daniel.bustos@prueba.com",
                    "cana_id": 5,
                    "alerta": false,
                    "tick_ultimo_msj_cliente": "2021-06-10 19:01:00",
                    "cuen_descripcion": "Fb MundoCl",
                    "cuen_identificador": "tumundo.cl"
                },
                ...
            ],
            "first_page_url": "...URL/api/mundosocial/misticketscerrados?page=1",
            "from": 1,
            "last_page": 2,
            "last_page_url": "...URL/api/mundosocial/misticketscerrados?page=2",
            "next_page_url": "...URL/api/mundosocial/misticketscerrados?page=2",
            "path": "...URL/api/mundosocial/misticketscerrados",
            "per_page": 25,
            "prev_page_url": null,
            "to": 25,
            "total": 26
        },
        "hoy": 0
    }


# 18.- Mensajes
## 18.1.- Recibe
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/mensajes/recibe`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| remitente         | string       |                                |  Si                     | Remitente del                |
| destinatario      | string       |                                |  Si                     | Destinatario del                |
| mensaje           | string       |                                |  Si                     | Mensaje a enviar?               |
| canal_id          | int          |                                |  Si                     | ID del canal               |
| tipo              | string       |                                |  Si                     | Tipo del mensaje                |
| url               | string       |                                |  Si                     | Url de ?                |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| mensaje               | string       | ?                              |
| etapa                 | string       | ?                                           |
| informadosocket       | string       | ?                                    |
| tick_id               | int          | ID del ticket                     |
| socketUsuario         | string       |                    |

### 18.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "remitente": "@dbustos_",
        "destinatario": "@no_existe",
        "mensaje": "test",
        "canal_id": 7,
        "tipo": "txt",
        "url": "www.prueba.cl",
	}

### 18.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.1.2.1.- Respuesta de error

	{
        "mensaje": "La cuenta de destino no existe en Mundo Social"
    }
  
#### 18.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "etapa": "mensaje conversacion",
        "informadosocket": "DESHABILITAR",
        "tick_id": 568,
        "socketUsuario": "NO ASIGNADO"
    }


## 18.2.- Sale
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/mensajes/sale`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| tick_id           | int          |                                |  Si                     | ID del ticket                   |
| mensaje           | string       |                                |  Si                     | Contenido del mensaje           |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| endpoint              | string       | Ruta del endpoint                              |
| mensajes              | int          | ?                                           |
| canal                 | int          | ?                                    |
| cuenta                | string       | ?                     |

### 18.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 254,
        "mensaje": "test salida"
	}

### 18.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 18.2.2.2.- Respuesta de éxito

    {
        "endpoint": "...URL/api/enviarMensaje",
        "mensajes": 502,
        "canal": 4,
        "cuenta": "promociones99@mundopacifico.cl"
    }


## 18.3.- Conversaciones
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/mensajes/conversacion`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| tick_id           | int          |                                |  Si                     | ID del ticket                   |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| emisor                | string       | Ruta del endpoint                                |
| mensaje               | string       | Contenido del mensaje                            |
| fecha                 | timestamp    | ?                                |
| tipo                  | string       | Tipo de mensaje                                  |
| url                   | string       | ?                                |
| id                    | int          | ID de la conversación                            |

### 18.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 254
	}

### 18.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 18.3.2.2.- Respuesta de éxito

    {
        "mensajes": [
            {
                "emisor": "promociones99@mundopacifico.cl",
                "mensaje": "Estimado cliente nuestro horario de atención es desde las 08:00 hasta las 18:00 horas.",
                "fecha": "2021-03-31 21:44:01",
                "tipo": "text",
                "url": "#",
                "id": 2
            },
            ...
        ]
    }


## 18.4.- Mensajes No Leídos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/mensajes/noLeidos`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| tick_id           | int          |                                |  Si                     | ID del ticket                   |
| ultimoid          | int          |                                |  Si                     | ?                   |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| emisor                | string       | Ruta del endpoint                                |
| mensaje               | string       | Contenido del mensaje                            |
| fecha                 | timestamp    | ?                                |
| tipo                  | string       | Tipo de mensaje                                  |
| url                   | string       | ?                                |
| id                    | int          | ID de la conversación                            |
| ultimo                | int          | ?                                |

### 18.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "tick_id": 254,
        "ultimoid": 1
	}

### 18.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 18.4.2.2.- Respuesta de éxito

    {
        "mensajes": [
            {
                "emisor": "promociones99@mundopacifico.cl",
                "mensaje": "Estimado cliente nuestro horario de atención es desde las 08:00 hasta las 18:00 horas.",
                "fecha": "2021-03-31 21:44:01",
                "tipo": "text",
                "url": "#",
                "id": 2,
                "ultimo": "1"
            },
            ...
        ]
    }


## 18.5.- Sucursal
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/sucursalvirtual`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| remitente         | string       |                                |  Si                     | ?                   |
| destinatario      | string       |                                |  Si                     | ?                   |
| mensaje           | string       |                                |  Si                     | ?                   |
| canal_id          | int          |                                |  Si                     | ?                   |
| tipo              | string       | txt o html                     |  Si                     | ?                   |
| url               | string       |                                |  Si                     | ?                   |
| rut               | string       |                                |  Si                     | ?                   |
| nombre            | string       |                                |  Si                     | ?                   |
| apellido1         | string       |                                |  Si                     | ?                   |
| apellido2         | string       |                                |  Si                     | ?                   |
| telefono          | int          |                                |  Si                     | ?                   |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?                     | ?            | ?                            |

### 18.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "remitente": "remitente@prueba.cl",
        "destinatario": "destinatario@prueba.cl",
        "mensaje": "Mensaje prueba",
        "canal_id": 4,
        "tipo": "txt",
        "url": "www.prueba.cl",
        "rut": "54298455",
        "nombre": "Carlos",
        "apellido1": "Fernández",
        "apellido2": "Barra",
        "telefono": 999988881,
	}

### 18.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 18.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 18.5.2.2.- Respuesta de éxito

    {
        ..
    }


# 19.- Omnicanalidad
## 19.1.- Listar Canales
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/omnicanalidad/canales`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| cana_id               | int          | ID del canal                                     |
| cana_descripcion      | string       | Descripción del canal                            |

### 19.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "canales": [
            {
                "cana_id": 1,
                "cana_descripcion": "Whatsapp"
            },
            {
                "cana_id": 2,
                "cana_descripcion": "Messenger Facebook"
            },
            ...
        ]
    }


## 19.2.- Listar Canales
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/omnicanalidad/canalescliente`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| clie_id           | int          |                                |  Si                     | ID del cliente                  |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| cana_id               | int          | ID del canal                                     |
| cana_descripcion      | string       | Descripción del canal                            |
| cacl_id               | int          | ID de canal de un cliente                        |
| cacl_identificador    | string       | ?                            |

### 19.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "canales": [
            {
                "cana_id": 2,
                "cana_descripcion": "Messenger Facebook",
                "cacl_id": 137,
                "cacl_identificador": "122222221"
            }
        ]
    }


## 19.3.- Crear Canal del Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/omnicanalidad/canalescliente`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| cacl_identificador| string       |                                |  Si                     | ?                  |
| cana_id           | int          |                                |  Si                     | ID del canal                    |
| clie_id           | int          |                                |  Si                     | ID del cliente                  |


### 19.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cacl_identificador": "+56988543265",
        "cana_id": 1,
        "clie_id": 34
	}

### 19.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.3.2.1.- Respuesta de error

	{
        "mensaje": "este canal ya ese encuentra registrado"
    }
  
#### 19.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 19.4.- Tickets Abiertos de una Cuenta de Cliente
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/omnicanalidad/ticketsrelacionadoscuenta`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| cacl_id           | int          |                                |  Si                     | ID de canal de un cliente       |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| tick_id               | int          | ID del ticket                                    |
| cana_descripcion      | string       | Descripción del canal                            |
| cacl_identificador    | string       | ?                            |
| esta_descripcion      | string       | ?                            |


### 19.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cacl_id": 225
	}

### 19.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "ticketsRelacionados": [
            {
                "tick_id": 370,
                "cana_descripcion": "Mail",
                "cacl_identificador": "prueba@correo.cl",
                "esta_descripcion": "No asignado"
            }
        ]
    }


## 19.5.- Tickets Relacionados All
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/omnicanalidad/ticketsrelacionadosall`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| ?                 | ?            |                                |  Si                     | ?       |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| tick_id               | int          | ID del ticket                                    |
| cana_descripcion      | string       | Descripción del canal                            |
| cacl_identificador    | string       | ?                            |
| esta_descripcion      | string       | ?                            |


### 19.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.5.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "ticketsRelacionados": [
            {
                "tick_id": 301,
                "cana_descripcion": "Messenger Facebook",
                "cacl_identificador": "33123123131313",
                "esta_descripcion": "No asignado"
            }
        ]
    }


## 19.6.- Vincular Ticket
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/omnicanalidad/vincularticket`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| ?                 | ?            |                                |  Si                     | ?       |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?               | ?          | ?                                    |


### 19.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.6.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.6.2.2.- Respuesta de éxito

    {
       ...
    }


## 19.7.- Vincular Todos
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/omnicanalidad/vinculartodos`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| ?                 | ?            |                                |  Si                     | ?       |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?               | ?          | ?                                    |


### 19.7.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 19.7.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 19.7.2.1.- Respuesta de error

	{
        ...
    }
  
#### 19.7.2.2.- Respuesta de éxito

    {
       ...
    }


# 20.- Plantilla Wsp
## 20.1.- Get
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/plantillawsp`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?               | ?          | ?                                     |

### 20.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 20.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 20.1.2.2.- Respuesta de éxito

    {
        "success": {
            "codigoRespuesta": 1,
            "descripcionRespuesta": {
                "plantilla": []
            }
        },
        "codigo": 200
    }

## 20.2.- Generar Ticket desde Mundo
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/plantillawsp`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| cuen_id           | int          |                                |  Si                     | ID de la cuenta?                |
| telefono_cliente  | string       |                                |  Si                     | Teléfono del cliente            |
| usuario_mail      | string       |                                |  Si                     | Mail del usuario                |
| plan_id           | int          |                                |  Si                     | ID del plan                     |


### 20.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "cuen_id": 4,
        "telefono_cliente": "+56988543265",
        "usuario_mail": "mundoSocialAdmin@tumundo.cl",
        "plan_id": 1
	}

### 20.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 20.2.2.1.- Respuesta de error

	{
        "error": {
            "codigoRespuesta": 0,
            "descripcionRespuesta": "Error",
            "detalleRespuesta": "Error al generar ticket desde Mundo al cliente"
        },
        "codigo": 400
    }
  
#### 20.2.2.2.- Respuesta de éxito

    {
        ...
    }


# 21.- Publicaciones
## 21.1.- GetById
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/publicacion`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| publ_id           | int          |                                |  Si                     | ID de la publicación            |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| publ_id               | int          | ID de la publicación                             |
| grup_id               | int          | ID del grupo                                     |
| cuen_id               | int          | ID de la cuenta                                  |
| publ_titulo           | string       | Título de la publicación                         |
| publ_descripcion      | string       | Descripción de la publicación                    |
| publ_ignorar          | boolean      | ?                                                |
| publ_foto             | string       | Fotografía de la publicación                     |

### 21.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "publ_id": 20
	}

### 21.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 21.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "publ_id": 20,
            "grup_id": 1,
            "cuen_id": 5,
            "publ_titulo": "t",
            "publ_descripcion": "des",
            "publ_ignorar": false,
            "publ_foto": "...FOTO"
        }
    }


## 21.2.- GetAll
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/publicaciones`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_id           | int          |                                |  Si                     | ID del grupo                    |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| publ_id               | int          | ID de la publicación                             |
| grup_id               | int          | ID del grupo                                     |
| cuen_id               | int          | ID de la cuenta                                  |
| publ_titulo           | string       | Título de la publicación                         |
| publ_descripcion      | string       | Descripción de la publicación                    |
| publ_ignorar          | boolean      | ?                                                |

### 21.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1
	}

### 21.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 21.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": [
            {
                "publ_id": 1,
                "grup_id": 1,
                "cuen_id": 5,
                "publ_titulo": "t",
                "publ_descripcion": "des",
                "publ_ignorar": false
            },
            ...
        ]
    }

## 21.3.- Guardar
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/publicaciones`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| grup_id           | int          |                                |  Si                     | ID del grupo                    |
| cuen_id           | int          |                                |  Si                     | ID de la cuenta                 |
| publ_titulo       | string       |                                |  Si                     | Título de la publicación        |
| publ_descripcion  | string       |                                |  Si                     | Descripción de la publicación   |
| publ_ignorar      | boolean      |                                |  Si                     | ?                               |
| publ_foto         | file         |                                |  Si                     | Fotografía de la publicación    |

### 21.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "grup_id": 1,
        "cuen_id": 4,
        "publ_titulo": "t",
        "publ_descripcion": "des",
        "publ_ignorar": false,
        "publ_foto": archivo-ejemplo.jpg
	}

### 21.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 21.3.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "respApiMensajeria": 502
    }


## 21.4.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/publicaciones/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| publ_id           | int          |                                |  Si                     | ID de la publicación            |
| grup_id           | int          |                                |  Si                     | ID del grupo                    |
| cuen_id           | int          |                                |  Si                     | ID de la cuenta                 |
| publ_titulo       | string       |                                |  Si                     | Título de la publicación        |
| publ_descripcion  | string       |                                |  Si                     | Descripción de la publicación   |
| publ_ignorar      | boolean      |                                |  Si                     | ?                               |
| publ_foto         | file         |                                |  Si                     | Fotografía de la publicación    |

### 21.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "publ_id": 67,
        "grup_id": 1,
        "cuen_id": 4,
        "publ_titulo": "t update",
        "publ_descripcion": "des update",
        "publ_ignorar": false,
        "publ_foto": archivo-ejemplo-update.jpg
	}

### 21.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 21.4.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


## 21.5.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/publicaciones/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| publ_id           | int          |                                |  Si                     | ID de la publicación            |

### 21.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "publ_id": 67
	}

### 21.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 21.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 21.5.2.2.- Respuesta de éxito

    {
        "mensaje": "ok"
    }


# 22.- Reportes
## 22.1.- Reporte
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/reportes/tickets`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| paginate          | int          |                                |                         | Cantidad de resultados por página|
| mail              | int          |                                |  Si                     | Correo electrónico de?            |
| estado            | int          |                                |  Si                     | Estado de?            |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| clie_nombre           | string       | Nombres del cliente                              ||
| cacl_identificador    | string       | email?                                           |
| tick_id               |  int         | ID del ticket                                    |
| tick_fecha_creacion   | timestamp    | Fecha de creación del ticket                     |
| tick_fecha_asignacion | timestamp    | Fecha de asignación del ticket                   |
| esta_descripcion      | string       | Descripción del ticket                           |
| usua_id               | int          | ID del usuario                                   |
| usua_nombre           | string       | Nombre del usuario                               |
| cana_id               | int          | ID del ?                                         |

### 22.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "paginate": 25,
        "mail": "daniel.bustos@prueba.com",
        "estado": 2
	}

### 22.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 22.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 22.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "data": {
            "current_page": 1,
            "data": [
                {
                    "clie_nombre": "PENDIENTE",
                    "cacl_identificador": "158056|Daniel Enrique Bustos Romero",
                    "tick_id": 667,
                    "tick_fecha_creacion": "2021-06-10 19:39:54",
                    "tick_fecha_asignacion": "2021-06-10 19:40:52",
                    "esta_descripcion": "ASIGNADO",
                    "usua_id": 2,
                    "usua_nombre": "daniel.bustos@prueba.com",
                    "cana_id": 2
                },
                ...
            ],
            "first_page_url": "...URL/api/mundosocial/reportes/tickets?page=1",
            "from": 1,
            "last_page": 1,
            "last_page_url": "...URL/api/mundosocial/reportes/tickets?page=1",
            "next_page_url": null,
            "path": "...URL/api/mundosocial/reportes/tickets",
            "per_page": 15,
            "prev_page_url": null,
            "to": 13,
            "total": 13
        }
    }


# 23.- Respuestas Rápidas
## 23.1.- GetAll
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/respuestasrapida`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| resp_id               | int          | ID de la respuesta rápida                        |
| resp_descripcion      | string       | Descripción de la respuesta rápida               |
| resp_contenido        | string       | Contenido de la respuesta rápida                 |
| resp_tipo             | int          | Tipo de respuesta rápida                         |

### 23.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 23.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 23.1.2.2.- Respuesta de éxito

    {
        "data": [
            {
                "resp_id": 6,
                "resp_descripcion": "Pedir documentos",
                "resp_contenido": "Estimado buenas tardes, hemos recibido su solicitud por favor envíenos: *Copia de su cédula de identidad\n*Boleta de servicios",
                "resp_tipo": 2
            },
            {
                "resp_id": 3,
                "resp_descripcion": "Saludo Inicial",
                "resp_contenido": "Hola bienvenidos mi nombre [[ejecutivo]], en que podemos ayudarlos",
                "resp_tipo": 1
            },
            ...
        ] 
    }

## 23.2.- Store
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/respuestasrapida`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| resp_descripcion  | string       |                                |  Si                     | Descripción de la respuesta rápida|
| resp_contenido    | string       |                                |  Si                     | Contenido de la respuesta rápida|

### 23.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "resp_descripcion": "Despedida Final",
        "resp_contenido": "Mi nombre [[ejecutivo]], espero haberlo ayudado, hasta pronto."
	}

### 23.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.2.2.1.- Respuesta de error

    {
        "mensajes": "Título ya existe"
    }
  
#### 23.2.2.2.- Respuesta de éxito

    {
        "mensajes": "ok"
    }


## 23.3.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/respuestasrapida/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| resp_id           | int          |                                |  Si                     | ID de la respuesta rápida       |
| resp_descripcion  | string       |                                |  Si                     | Descripción de la respuesta rápida|
| resp_contenido    | string       |                                |  Si                     | Contenido de la respuesta rápida|

### 23.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "resp_id": 47,
        "resp_descripcion": "Despedida Final Update",
        "resp_contenido": "Mi nombre [[ejecutivo]], espero haberlo ayudado, hasta pronto."
	}

### 23.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.3.2.1.- Respuesta de error

    {
        "mensajes": "Título ya existe"
    }
  
#### 23.3.2.2.- Respuesta de éxito

    {
        "mensajes": "ok"
    }

## 23.4.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/respuestasrapida/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| resp_id           | int          |                                |  Si                     | ID de la respuesta rápida       |

### 23.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "resp_id": 47
	}

### 23.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 23.4.2.1.- Respuesta de error

    {
        ...
    }
  
#### 23.4.2.2.- Respuesta de éxito

    {
        "mensajes": "eliminado"
    }


# 24.- Usuarios
## 24.1.- Get Usuarios
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/usuario/listar`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| todos             | string       |                                |  Si                     | ?                               |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| usua_id               | int          | ID del usuario                                   |
| usua_rol              | string       | Rol del usuario                                  |
| usua_nombre           | string       | Correo electrónico del usuario                   |
| esco_id               | int          | ?                         |
| usua_fecha_set_estado | timestamp    | ?                         |

### 24.1.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "todos": "s"
	}

### 24.1.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.1.2.1.- Respuesta de error

	{
        ...
    }
  
#### 24.1.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "usuarios": [
            {
                "usua_id": 18,
                "usua_rol": "ejecutivo",
                "usua_nombre": "ejecutivoEjemplo@tumundo.cl",
                "esco_id": null,
                "usua_fecha_set_estado": null
            },
            {
                "usua_id": 1,
                "usua_rol": "ejecutivo",
                "usua_nombre": "NoAsignado@mail.com",
                "esco_id": 1,
                "usua_fecha_set_estado": "2021-08-15 16:09:07"
            },
            ...
        ] 
    }

## 24.2.- Get Usuario
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/usuario`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| mail              | string       |                                |  Si                     | Correo electrónico del usuario a buscar|

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| usua_id               | int          | ID del usuario                                   |
| usua_rol              | string       | Rol del usuario                                  |
| usua_nombre           | string       | Correo electrónico del usuario                   |
| esco_id               | int          | ?                         |
| usua_fecha_set_estado | timestamp    | ?                         |

### 24.2.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "daniel.bustos@prueba.com"
	}

### 24.2.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.2.2.1.- Respuesta de error

	{
        ...
    }
  
#### 24.2.2.2.- Respuesta de éxito

    {
        "mensaje": "ok",
        "usuarios": {
            "usua_id": 2,
            "usua_rol": "admin",
            "usua_nombre": "daniel.bustos@prueba.com",
            "esco_id": 2,
            "usua_fecha_set_estado": "2021-08-16 12:52:49"
        }
    }


## 24.3.- Crear
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/usuario`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| mail              | string       |                                |  Si                     | Correo electrónico del usuario a crear|
| rol               | string       |                                |  Si                     | Rol del usuario a crear         |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?               | ?          | ?                                   |

### 24.3.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "mail": "carlos.fernandez.b@mundopacifico.cl",
        "rol": "programador"
	}

### 24.3.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.3.2.1.- Respuesta de error

	{
        ...
    }
  
#### 24.3.2.2.- Respuesta de éxito

    {
        ...
    }


## 24.4.- Roles
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : GET `/api/mundosocial/usuario/roles`

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| value                 | string       | Tipo de rol                                      |
| label                 | string       | Nombre del rol                                   |

### 24.4.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        ...
	}

### 24.4.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.4.2.1.- Respuesta de error

	{
        ...
    }
  
#### 24.4.2.2.- Respuesta de éxito

    {
        "rol": [
            {
                "value": "admin",
                "label": "admin"
            },
            {
                "value": "ejecutivo",
                "label": "ejecutivo"
            }
            ...
        ]
    }

## 24.5.- Update
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/usuario/update`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| usua_id           | int          |                                |  Si                     | ID del usuario a modificar      |
| mail              | string       |                                |  Si                     | Correo electrónico del usuario a crear|
| rol               | string       |                                |  Si                     | Rol del usuario a crear         |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?               | ?          | ?                                   |

### 24.5.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "usua_id": ?,
        "mail": "carlos.fernandez.b@mundopacifico.cl",
        "rol": "admin update"
	}

### 24.5.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.5.2.1.- Respuesta de error

	{
        ...
    }
  
#### 24.5.2.2.- Respuesta de éxito

    {
        ...
    }

## 24.6.- Delete
Breve descripción de ruta

Los parámetros que recibe son los siguientes:

Ruta : POST `/api/mundosocial/usuario/delete`

**Parámetros de entrada:**
| Campo             |  Tipo        | Formato                        |     Requerido           |             Descripción         |
|:-----------------:|:------------:|:------------------------------:|:-----------------------:|--------------------------------:|
| usua_id           | int          |                                |  Si                     | ID del usuario a modificar      |
| mail              | string       |                                |  Si                     | Correo electrónico del usuario a crear|
| rol               | string       |                                |  Si                     | Rol del usuario a crear         |

**Datos de salida:**
| Campo                 |  Tipo        |                         Descripción              |
|:----------------------|:------------:|-------------------------------------------------:| 
| ?                     | ?            | ?                                   |

### 24.6.1.- Ejemplo de llamada

Ejemplo: JSON 

	{
        "usua_id": ?
	}

### 24.6.2.- Respuesta de salida

codigo: 200 éxito mensaje: descripcion del mensaje

#### 24.6.2.1.- Respuesta de error

	{
        "mensaje": "El usuario tiene grupos asignados"
    }
  
#### 24.6.2.2.- Respuesta de éxito

    {
        ...
    }