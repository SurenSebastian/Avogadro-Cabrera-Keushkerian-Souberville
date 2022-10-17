# Proyecto BONDi #
# Ingeniería de Software Ágil 1 #
## Docentes: 
- Fabiana Pedrini 
- Analía Moreira
## Alumnos: ##
- Leandro Avogadro - 221869  
- Daniel Cabrera - 198360 
- Suren Keushkerian - 141534 
- Denise Souberville - 223427 

## Tabla de Contenidos ##
1. [Introducción](#introduccion)
2. [Descripción de la aplicación](#descripcionaplicacion)
3. [Funcionalidades](#funcionalidades)
4. [Marco de Gestion](#marcodegestion)
5. [Planning](#planning1)
6. [Daily](#daily1)
7. [Sprint Retrospective](#sprintretrospective)
8. [Sprint Review](#sprintreview)
9. [Backlog Refinement](#backlogrefinement)
10. [Capacity](#capacity)
11. [Definition of Ready](#dor)
12. [Definition of Done](#dod)
13. [Estrategias de Branching y Pull Request](#estrategiaBranching)
14. [Roles](#roles)
15. [Relevamiento de aplicaciones](#relevamientoAplicaciones)
16. [Formulario de investigación](#formularioInviestiagcion)
17. [Realización de Encuestas](#realizacionEncuestas)
18. [Procesamiento de datos](#procesamientoDeDatos)
19. [Analisis de interesados](#analisisInteresados)
20. [Elección de Sistema Operativo](#sistemaoperativo)
21. [Gestion Agile](#gestionAgile)


# Introducción <a name="introduccion"></a>
Este documento lleva un registro de la ejecución y gestión del "Proyecto BONDi"con sus correspondientes acuerdos y evidencias.

# Descripción de la aplicación <a name="descripcionaplicacion"></a>
El resultado del proyecto es poder descubrir, idear y prototipar un MVP (Minimum Viable Product) de una aplicación móvil para ayudar al usuario con el transporte público en el día a día.
El MVP de la aplicación está dirigida principalmente a personas de cualquier edad que utilicen el transporte público, como usuarios finales. 

## Funcionalidades  <a name="funcionalidades"></a>
- Login de usuario.
- Registrar nuevo usuario.
- Editar usuario.
- Restaurar contraseña.
- Buscar línea de ómnibus utilizando filtros.
- Listado de las líneas más cercanas al usuario con información del destino/origen/tiempo estimado, con la información de cantidad de pasajeros en las mismas.
- Historias de los últimos viajes (líneas de ómnibus utilizadas).
- Modo viaje. El usuario debe poder seguir el trayecto de la línea de ómnibus a la que se subió, pudiendo saber en qué parte del recorrido se encuentra, cuáles son las paradas hasta el próximo destino e información del destino.
- Compartir mi viaje a otro usuario.
- Notificaciones:
* La línea seleccionada está por llegar a la parada de ómnibus.
* La siguiente parada es tu destino.
* Tu línea frecuente llega en X minutos (dependiendo de la distancia del usuario a la parada) a tu parada habitual.
* La línea seleccionada tiene un retraso y demorará en llegar a tu parada origen.
* La línea seleccionada tiene un desvío.
Algunos atributos de calidad (RNF) importantes son:
* La aplicación debe poder escalar a millones de usuarios (mínimamente a toda la población uruguaya).
* Debe ser fácil de usar por las distintas franjas etarias de población.
* Debe poder mantener la privacidad de datos sensibles de sus usuarios.
* Debe contar con una interfaz principalmente móvil (iOS y/o Android).

# Marco de Gestión <a name="marcodegestion"></a>  

Para la gestión de este proyecto vamos a utilizar Scrum, con las ceremonias: 

- Sprint Planning
- Daily
- Sprint Retrospective
- Sprint Review
- Backlog Refinement

## Planning  <a name="planning1"></a>  
Se va a realizar el primer día de cada sprint, la duración aproximada va a ser de 2 horas, se va a estimar utilizando planning poker. La escala de Story Points va a ser Fibonacci, considerando que 13 o mayor significa que la Story es muy compleja para ser completada en un sprint y va a necesitar ser dividida en partes más pequeñas.

## Daily <a name="daily1"></a>  
Dada la naturaleza de nuestro proyecto no va a tener mucho sentido el reunirse a diario a revisar progreso dado que no vamos a poder generar un progreso diario. Para ello vamos a tener 3 daily por semana distribuidas de la siguiente forma

- Jueves
- Sábado
- Domingo

Esto se debe a que la mayor contribución del equipo se concentra en los fines de semana, entonces nos parece importante que ahí sí se respete la daily. Se va a realizar por llamada en WhatsApp.

## Sprint Retrospective <a name="sprintretrospective"></a>   
Esta ceremonia va a suceder el último día del sprint (viernes), va a tener una duración máxima de 30 minutos y todos los action items van a ser convertidos en product backlog items, priorizados e ingresados en el próximo sprint planning para considerar y aplicar las mejoras.

## Sprint Review  <a name="sprintreview"></a>   
Esta ceremonia va a suceder el último día del sprint (viernes) y todo el feedback recibido va a ser convertido en product backlog items que luego deben ser priorizados con el PO e ingresados en futuros sprints. No va a durar más de 30 minutos y el objetivo es mostrar el incremento generado durante el sprint al PO para su validación.

## Backlog Refinement <a name="backlogrefinement"></a>  
Se va a realizar un refinamiento del backlog cada jueves a excepción de la última semana de cada sprint, en este caso el equipo va a estar enfocado en la planning y estimación del siguiente sprint.

## Capacity <a name="capacity"></a>  
Se va a considerar que cada miembro puede trabajar en total 7hs semanales.
 
## Definition of Ready  <a name="dor"></a>  
Una User Story se considera pronta para ser incluida en una planning si cumple con las condiciones:

- Es clara: El equipo tiene bien definido el incremento a entregar y no existen dudas respecto a lo que hay que hacer.
- Es realizable: todas las actividades relacionadas con la User Story son realizables dentro de un sprint y no hay impedimentos mayores.
- Es testeable: se puede probar los incrementos dentro del sprint sin problemas.
- Acceptance criteria está definido y es claro para el equipo.
- Las dependencias fueron identificadas claramente. El equipo sabe bien qué otras tareas se deben completar antes (si existe alguna) para poder comenzar a trabajar en la Story.
- Es demostrable: el equipo tiene en claro como hacer una demo de la User Story a los stakeholders o interesados que corresponda.


## Definition of Done  <a name="dod"></a>  
* La Definición de Done es un acuerdo entre el equipo de desarrollo y el Product Owner sobre lo que debe completarse para cada User Story.
* Son los criterios de aceptación acordados, que el Product Owner utilizará para aceptar el incremento del producto al final del sprint.
* En nuestro proyecto, el DoD va a ser diferente para los sprints, ya que abarcan distintas etapas del proyecto.
* Para el sprint 1, el DoD de las user story va a contemplar:
  * Evidencia de la tarea realizada mediante documentación.
  * Registro de Horas que llevó la tarea.
  
  

## Estrategias de Branching y Pull Request <a name="estrategiaBranching"></a> 
 - Ver documento [Estrategia de Branching.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Estrategia%20de%20Branching.pdf)
 
## Roles <a name="roles"></a> 

**Scrum Master:**
  * Daniel Cabrera:
    * Encargado de gestionar y asegurar que el proceso Scrum se lleva a cabo correctamente.
    * Facilitar la ejecución del proceso y sus mecánicas.
    * Tratar de eliminar impedimentos que van surgiendo.
  
**Product Owner:**
  * Suren Keushkerian:
    * Encargado de optimizar y maximizar el valor del producto.
    * Gestionar el Product Backlog para manetenerlo estructurado y priorizado.

**Developers:**
  * Denise Souberville
  * Leandro Avogadro
  * Daniel Cabrera
  * Suren Keushkerian
  
    * Encargados de  desarrollar el producto.
    * Son responsables de ser auto-organizádos y auto-gestionádos para entregar un incremento de software al final del sprint.
    * Participan activamente en las ceremonias de Scrum.
 
# Análisis de Requerimientos #
## Relevamiento de aplicaciones existentes <a name="relevamientoAplicaciones"></a> 

Aplicamos el proceso de ingeniería inversa a 3 aplicaciones ya existentes en el mercado, a los efectos de obtener mayor entendimiento del problema, lograr obtener ideas para adaptar a nuestra solución e intentar agregar mejoras o nuevas funcionalidades al backlog que puedan darle un valor agregado al producto. 

## Formulario de investigación <a name="formularioInviestiagcion"></a> 
Se creó un formulario para la investigación de las aplicaciones existentes, el cuál fue completado para cada una de las aplicaciones Moovit, ComoIr y Citymapper.
- Ver [Formulario Analisis Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Evidencias/Formularios/Formulario%20Analisis%20Aplicaciones.docx)
- Ver [Analisis Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Evidencias/Analisis%20Aplicaciones.docx)

## Realización de Encuestas <a name="realizacionEncuestas"></a> 

Procedimos también a buscar ideas y requerimientos mediante la realización de encuestas a algunos usuarios del transporte público de Montevideo.

#### Formulario mediante Google Forms  

Se realizó un formulario con 8 preguntas para lograr recabar información tal como las edades de los usuarios,tiempo de espera en la parada, demora del trayecto, cantidad de ómnibus para completar el viaje, funciones más comunes que usa de la aplicación de viaje y cualquier otra función que consideran necesario. El informe completo de la encuesta se encuentra en la carpeta Evidencias.

- Ver [Encuesta de Apliacion de Viaje.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Evidencias/Encuesta%20de%20Aplicacion%20de%20Viaje.pdf)

## Procesamiento de datos <a name="procesamientoDeDatos"></a> 
Se realizó un análisis de la información obtenida mediante el relevamiento de aplicaciones existentes y la realización de encuestas para obtener nuevos requerimientos, cuyos resultados quedaron adjuntos en el repositorio.

- Ver [Procesamiento de Encuestas y Análisis de Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Procesamiento%20de%20Encuestas%20y%20An%C3%A1lisis%20de%20Aplicaciones.docx)

## Analisis de interesados <a name="analisisInteresados"></a> 
Es de relevancia realizar un análisis de los interesados en el proyecto, ya que se necesita conocerlos y pedir su participación para recolectar requerimientos y obtener información acerca de los servicios que se deben proporcionar en la aplicación y las restricciones que se puedan presentar.
Definiremos sus roles y grados de poder e interés, a los efectos de definir prioridades en los requisitos, teniendo en cuenta que no siempre se puede satisfacer por completo a todos los interesados.
Para realizar el análisis de los interesados se procedió a realizar un brainstorm entre los integrantes del equipo del proyecto, además de realizar una investigación sobre las diferentes asociaciones relativas al transporte y áreas del gobierno que podrían intervenir. 

### 1. Lista de interesados
#### a.	Interesados Externos
Usuarios del sistema de transporte público: personas que utilizan o piensan utilizar en algún momento el transporte colectivo.

Proveedores de servicio de transporte público: empresas que proveen flota de transporte como ser CUTCSA, COECT, COPSA, etc.

Intendencia de cada departamento: son las que regulan las normas de tránsito y transporte de cada departamento.

Otras aplicaciones de transporte público: aplicaciones que brinda servicios similares a nuestro producto, como ser las aplicaciones ComoIr, Moovit.

Ministerio de Transporte y Obras Públicas - Dirección Nacional de Transporte: es responsable de asegurar la calidad del transporte regular de pasajeros como servicio público responsabilidad del Estado, mejorar su eficiencia, su calidad y su seguridad; así como de implementar y controlar políticas de transporte de pasajeros por carretera y transporte de carga.

Appstore y Play Store: son los Marketplace en los cuales debemos poner a disposición nuestra aplicación, los cuales nos deben revisar la app antes de publicarla.


#### b.	Interesados Internos
Equipo de proyecto: Product Owner, Developers, Scrum Master.


### 2. Registro de interesados

|Nombre |     Rol                   |     Requerimientos                                                                                                                                                                |     Expectativas                                                                         |     Influencia    |     Clasificación    |
|-------------------------------------------------------|---------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|-------------------|----------------------|
|     Usuarios del   sistema de transporte público      |     Usuario   directo     |     Tener   información sobre las líneas de ómnibus y sus horarios.                                                                                                               |     Facilitar   y optimizar tiempos y costos a la hora de usar el transporte público     |     Alta          |     Amigo            |
|      Proveedores de servicio de transporte público    |     Asesor                |     Informar   a los usuarios la situación de cada línea de bus.                                                                                                                  |     Mejorar   el servicio brindado a los usuarios.                                       |     Alta          |     Amigo            |
|     Intendencias                                      |     Asesor   / Sponsor    |     Regular   que la herramienta cumpla con la normativa departamental.                                                                                                           |     Brindar   mayor calidad al transporte público.                                       |     Alta          |     Neutro           |
|     MTOP - Dirección Nacional de Transporte           |     Asesor                |     Obtener   datos y estadísticas del uso del transporte urbano.                                                                                                                 |     Brindar   mayor calidad al transporte público.                                       |     Alta          |     Neutro           |
|     Otras aplicaciones de transporte público          |     Competidor            |     No   perder usuarios.                                                                                                                                                         |     Que   su negocio siga siendo redituable.                                             |     Media         |     Enemigo          |
|     Appstore y Play Store                             |     Asesor                |     Que   no contengan contenido restringido, ni propiedad intelectual robada, que siga   con las normas de seguridad y privacidad y que sus funcionalidades no estén   rotas.    |     Comprometerse   a proteger al usuario y a brindar calidad en las aplicaciones.       |     Media         |     Amigo            |
|     Equipo de proyecto                                |     Creador               |     Aprender,   exonerar la materia.                                                                                                                                              |     Aprender   el uso de la metodología SCRUM.                                           |     Alta          |     Amigo            |

### 3. Matrices de interesados
Según lo analizado se procedió a clasificar a los interesados según su nivel de poder e interés. Los jugadores claves son los que tienen alto poder e interés en el proyecto, pero también hay que mantener satisfechos a los que tienen alto poder pero no tanto interés. A los que tienen bajo interés y poder se les prestará menos dedicación al momento de satisfacerlos.

|              |             |     Interés                     |                                                                                                                                                                                                |
|--------------|-------------|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|              |             |     Bajo                        |     Alto                                                                                                                                                                                       |
|     Poder    |     Bajo    |     -Appstore   y Play Store    |     -Otras aplicaciones de transporte público                                                                                                                                                  |
|              |     Alto    |                                 |     -Usuarios del   sistema de transporte público     -Proveedores de servicio de transporte   público    -Intendencias    -MTOP - Dirección Nacional de Transporte     -Equipo de proyecto    |

También se realizó una tabla basada en el poder y dinamismo de los interesados, en la cual a un bajo poder los interesados generan pocos problemas, pero los que tienen alto poder y baja predecibilidad son los que pueden generar mayores peligros u oportunidades, que es el caso de las Intendencias (normas que cambian), el equipo de proyecto (enfermedad o situaciones personales imprevistas) y las compañías de transporte (cambios en la manera de operar), y que afecten el desarrollo del proyecto.

|              |             |     Predecibilidad                                                                                |                                                                                                                                 |
|--------------|-------------|---------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------|
|              |             |     Bajo                                                                                          |     Alto                                                                                                                        |
|     Poder    |     Bajo    |                                                                                                   |     -Appstore   y Play Store     -Otras aplicaciones de transporte público     -Usuarios del   sistema de transporte público    |
|              |     Alto    |      -Proveedores de servicio de transporte   público    -Intendencias     -Equipo de proyecto    |     -MTOP - Dirección Nacional de Transporte                                                                                    |


- Ver [AnálisisDeInteresadosBONDi.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/blob/iteracion2-suren/Iteraci%C3%B3n%201/Evidencias/An%C3%A1lisisDeInteresadosBONDi.docx)


# Elección de Sistema Operativo <a name="sistemaoperativo"></a> 

Luego de una búsqueda que nos brindara estadísticas que a nuestro criterio puedan ser representativas del uso de cada sistema operativo dentro de la sociedad uruguaya, se encontraron los siguientes artículos:

- https://www.elpais.com.uy/negocios/noticias/sistemas-operativos-android-vs-ios-gana-batalla.html

- https://www.elobservador.com.uy/nota/el-uso-de-smartphones-y-tablets-se-disparo-en-uruguay-20164151080

Podemos notar que estas estadísticas son del 2016 y somos conscientes que en la tecnología en 6 años las cosas pueden cambiar mucho. Igualmente, para esta tarea tomaremos estas estadísticas como aproximadas a la realidad actual.
De las estadísticas de ambas notas se desprende que Android supera en usuarios a iOS en Uruguay y Argentina (la cual consideraremos como una realidad similar a la uruguaya en este aspecto).

Además de esta búsqueda, estuvimos investigando sobre los costes y facilidad para la publicación de una app en cada Store. De esta investigación concluimos que publicar una App en la store de Android es mucho más simple y menos costoso que en iOS.
Por ejemplo, para publicar una aplicación en la store de Android debemos efectuar un único pago de 25 dólares, este pago es único ya que no hay cargos extras por actualizar la app e incluso podríamos continuar publicando otras apps utilizando la misma cuenta.
En iOS una cuenta para un único desarrollador tiene un precio de 99 dólares al año, mientras que para una empresa es de 299 dólares al año. También la store de iOS tiene la reputación de ser mucho más restrictiva o generar más conflicto a la hora de publicar una aplicación.

Otro factor significativo es el hecho de que somos un equipo con poca experiencia en este tipo de desarrollos, por lo tanto, creemos que como primera experiencia las facilidades y bajos costes que Android nos ofrece son un factor muy importante que poner sobre la balanza al momento de decantarse por un sistema operativo.

Por todo lo anteriormente mencionado, hemos decidido desarrollar nuestra aplicación para el sistema operativo Android. Al menos como primera experiencia, dependiendo de la recepción que esta aplicación tenga, más adelante podríamos plantearnos la idea de desarrollar nuestra app también para iOS.

# Gestión Agile <a name="gestionAgile"></a>
## Sprint 1 ##
### Planning ###

Para el primer sprint el equipo planificó un total de 36 Story Points a realizarse en 3 semanas desde el 23 de septiembre al 7 de octubre (los primeros 4 días del sprint fueron removidos ya que el equipo estaba trabajando en completar el product backlog para la planning).
Se realizó la planning para el sprint, documentando a continuación la evidencia.

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Planning/planning1.png)

![Estimacion Marco de Gestion](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Planning/estimacion1.png)

![Estimacion Requerimientos Interesados](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Planning/estimacion2.png)

### Sprint Progress ###

![Sprint Progress1](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint1.png)

![Sprint Progress2](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint2.png)

![Sprint Progress3](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint3.png)

![Sprint capacity](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/capacity.png)

**Burndown**

Como se puede observar en el burndown chart, el equipo los primeros días del sprint estuvo trabajando en el Product Backlog, lo cual indica lo chato de los primeros días. Luego progresivamente se fue completando el sprint y sus tareas, lo cual se observa en el salto que hay entre 26/9 y 28/9, donde el equipo terminó de crear todas las tareas pertinentes al sprint.
Desde el 28/9 en adelante se observa un progreso lento pero mantenido, donde por momentos nos salimos un poco del ideal trend, manejando cierto riesgo a la hora de completar el sprint.
Se puede observar algún pendiente de tareas hacia el final del sprint que se van un poco del ideal trend, lo cual implicó un poco más de esfuerzo por parte del equipo para poder cumplir con lo comprometido y así evitar tener carry over hacia el siguiente sprint.

![Burndown chart](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint4.png)

### Retrospective ###

Para el primer sprint decidimos utilizar el board de Open Box, que consiste en identificar qué cosas comenzar a hacer, qué cosas dejar de hacer y qué cosas continuar haciendo. Principalmente el objetivo es analizar procesos y dado que es nuestro primer sprint nos pareció un buen punto de partida.

[Open the Box Retro Board](https://metroretro.io/templates/open-the-box-retrospective "Open the Box Retro Board")

Los resultados de la Retrospective se pueden encontrar en el archivo

"Iteracion 1\Evidencias\Sprint\RetroISA1Sprint1.csv"

Se crearon los siguientes items en el backlog como consecuencia de los action items

- Setear ceremonias del Sprint en google calendar por parte del Scrum Master.
- Crear dashboard de completed work por persona.
- Crear dashboard con cantidad de tareas por persona y sus status.
- Generar esqueleto de documentación para el sprint.
- Actualizar documentación respecto a Pull Requests.
- Actualizar documentación de manejo del board.

## Sprint 2 ##
### Planning ###

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/123/Iteraci%C3%B3n%202/Evidencias/Planning/Planning.png)

### Sprint Progress ###
**Burndown**

### Daily ###
**Registro de daily realizada el 15/10**

*Suren*

Ayer Trabajo en la documentacion del feedback, falta agregarlo.
Hoy va a trabajar en la pantalla de recuperar constraseña y buscar la funcionalidad de valor agregado

*Denise*

Trabajo en las pantallas de registro y editar usuario. Quedaron pendientes las validaciones que no sabemos como hacer en framer
Para hoy va a estar tomando nuevas tareas.

*Daniel*

Estuve trabajando en dashboards y documentacion de la planning y el progreso del sprint. Además comencé con la pantalla de login.
Para hoy voy a continuar con login y la documentacion.

*Leandro*

No updates
Mañana va a trabajar en la pantalla de buscar linea de omnibus

### Retrospective ###

# Prototipo #

Link a Framer:

https://framer.com/projects/Untitled--qyTLTLUuXGXdJQfm3l02-fpOLN

# Bibliografía #


- [Gherkin](https://profile.es/blog/que-es-gherkin/)
- [Definition of Ready](https://agility.im/frequent-agile-question/what-is-a-definition-of-ready/)
- [Definition of Ready vs Definition of Done](https://www.linkedin.com/pulse/definition-ready-dor-vs-done-dod-brian-will)
