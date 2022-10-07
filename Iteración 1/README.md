# Proyecto BONDi #
# Ingeniería de Software Ágil 1 #
## Docentes: 
- Fabiana Pedrini 
- Analía Moreira
## Alumnos: ##
-Leandro Avogadro - 221869 
-Daniel Cabrera - 198360 
-Suren Keushkerian - 141534 
-Denise Souberville - 223427 


# Introducción #
Descripción del documento

# Descripción de la aplicación #

## Funcionalidades ##

# Marco de Gestión #

Para la gestión de este proyecto vamos a utilizar Scrum, con las ceremonias: 

- Sprint Planning
- Daily
- Sprint Retrospective
- Sprint Review
- Backlog Refinement

## Planning ##
Se va a realizar el primer día de cada sprint, la duración aproximada va a ser de 2 horas, se va a estimar utilizando planning poker. La escala de Story Points va a ser Fibonacci, considerando que 13 o mayor significa que la Story es muy compleja para ser completada en un sprint y va a necesitar ser dividida en partes más pequeñas.

## Daily ##
Dada la naturaleza de nuestro proyecto no va a tener mucho sentido el reunirse a diario a revisar progreso dado que no vamos a poder generar un progreso diario. Para ello vamos a tener 3 daily por semana distribuidas de la siguiente forma

- Jueves
- Sábado
- Domingo

Esto se debe a que la mayor contribución del equipo se concentra en los fines de semana, entonces nos parece importante que ahí sí se respete la daily. Se va a realizar por llamada en WhatsApp.

## Sprint Retrospective ##
Esta ceremonia va a suceder el último día del sprint (viernes), va a tener una duración máxima de 30 minutos y todos los action items van a ser convertidos en product backlog items, priorizados e ingresados en el próximo sprint planning para considerar y aplicar las mejoras.

## Sprint Review ##
Esta ceremonia va a suceder el último día del sprint (viernes) y todo el feedback recibido va a ser convertido en product backlog items que luego deben ser priorizados con el PO e ingresados en futuros sprints. No va a durar más de 30 minutos y el objetivo es mostrar el incremento generado durante el sprint al PO para su validación.

## Backlog Refinement ##
Se va a realizar un refinamiento del backlog cada jueves a excepción de la última semana de cada sprint, en este caso el equipo va a estar enfocado en la planning y estimación del siguiente sprint.

## Capacity ##
Se va a considerar que cada miembro puede trabajar en total 7hs semanales.

## Definition of Ready ##
Una User Story se considera pronta para ser incluida en una planning si cumple con las condiciones:

- Es clara: El equipo tiene bien definido el incremento a entregar y no existen dudas respecto a lo que hay que hacer.
- Es realizable: todas las actividades relacionadas con la User Story son realizables dentro de un sprint y no hay impedimentos mayores.
- Es testeable: se puede probar los incrementos dentro del sprint sin problemas.
- Acceptance criteria está definido y es claro para el equipo.
- Las dependencias fueron identificadas claramente. El equipo sabe bien qué otras tareas se deben completar antes (si existe alguna) para poder comenzar a trabajar en la Story.
- Es demostrable: el equipo tiene en claro como hacer una demo de la User Story a los stakeholders o interesados que corresponda.


## Definition of Done ##
* La Definición de Done es un acuerdo entre el equipo de desarrollo y el Product Owner sobre lo que debe completarse para cada User Story.
* Son los criterios de aceptación acordados, que el Product Owner utilizará para aceptar el incremento del producto al final del sprint.
* En nuestro proyecto, el DoD va a ser diferente para los sprints, ya que abarcan distintas etapas del proyecto.
* Para el sprint 1, el DoD de las user story va a contemplar:
  * Evidencia de la tarea realizada mediante documentación.
  * Registro de Horas que llevó la tarea.
  
  

## Estrategias de Branching ##
 - Ver documento de ***Estrategia de Branching.docx*** en carpeta Iteracion 1
 
## Roles: ##

**Scrum Master:**
  - Daniel Cabrera 
  
**Product Owner:**
  - Suren Keushkerian
  
**Developers:**
  - Denise Souberville
  - Leandro Avogadro
  - Daniel Cabrera
  - Suren Keushkerian
  
# Análisis de Requerimientos #
## Relevamiento de aplicaciones existentes ##

Aplicamos el proceso de ingeniería inversa a 3 aplicaciones ya existentes en el mercado, a los efectos de obtener mayor entendimiento del problema, lograr obtener ideas para adaptar a nuestra solución e intentar agregar mejoras o nuevas funcionalidades al backlog que puedan darle un valor agregado al producto. 

### Formulario de investigación ##
Se creó un formulario para la investigación de las aplicaciones existentes, el cuál fue completado para cada una de las aplicaciones Moovit, ComoIr y Citymapper.
- Ver ***Formulario Analisis Aplicaciones.docx*** en carpeta "Iteracion 1/Evidencias/Formularios".
- Ver ***Analisis Aplicaciones.docx*** en carpeta "Iteracion 1/Evidencias".

## Realización de Encuestas

Procedimos también a buscar ideas y requerimientos mediante la realización de encuestas a algunos usuarios del transporte público de Montevideo.

#### Formulario mediante Google Forms

Se realizó un formulario con 8 preguntas para lograr recabar información tal como las edades de los usuarios,tiempo de espera en la parada, demora del trayecto, cantidad de ómnibus para completar el viaje, funciones más comunes que usa de la aplicación de viaje y cualquier otra función que consideran necesario. El informe completo de la encuesta se encuentra en la carpeta Evidencias.

- Ver documento ***Encuesta de Apliacion de Viaje.pdf*** en carpeta "Iteracion 1/Evidencias".

## Procesamiento de datos
Se realizó un análisis de la información obtenida mediante el relevamiento de aplicaciones existentes y la realización de encuestas para obtener nuevos requerimientos, cuyos resultados quedaron adjuntos en el repositorio.

- Ver documento ***Procesamiento de Encuestas y Análisis de Aplicaciones.docx*** en carpeta "Iteracion 1".

## Analisis de interesados
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


- Ver documento de ***AnálisisDeInteresadosBONDi.docx*** en carpeta Iteracion 1


# Gestión Agile #
## Sprint 1 ##
### Planning ###

Para el primer sprint el equipo planificó un total de 36 Story Points a realizarse en 3 semanas desde el 23 de septiembre al 7 de octubre (los primeros 4 días del sprint fueron removidos ya que el equipo estaba trabajando en completar el product backlog para la planning).
Se realizó la planning para el sprint, documentando a continuación la evidencia.

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Planning/planning1.png)

![Estimacion Marco de Gestion](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Planning/estimacion1.png)

![Estimacion Requerimientos Interesados](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Planning/estimacion2.png)

### Sprint Progress ###

![Sprint Progress1](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint1.png)

![Sprint Progress2](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint2.png)

![Sprint Progress3](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Sprint/sprint3.png)

![Sprint capacity](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/feature/scrum/Iteraci%C3%B3n%201/Evidencias/Sprint/capacity.png)

### Retrospective ###

Para el primer sprint decidimos utilizar el board de Open Box, que consiste en identificar qué cosas comenzar a hacer, qué cosas dejar de hacer y qué cosas continuar haciendo. Principalmente el objetivo es analizar procesos y dado que es nuestro primer sprint nos pareció un buen punto de partida.

[Open the Box Retro Board](https://metroretro.io/templates/open-the-box-retrospective "Open the Box Retro Board")

# Bibliografía #


- [Gherkin](https://profile.es/blog/que-es-gherkin/)
- [Definition of Ready](https://agility.im/frequent-agile-question/what-is-a-definition-of-ready/)
- [Definition of Ready vs Definition of Done](https://www.linkedin.com/pulse/definition-ready-dor-vs-done-dod-brian-will)

# Anexos #