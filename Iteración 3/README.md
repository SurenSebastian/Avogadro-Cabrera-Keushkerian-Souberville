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
[Propuesta de valor](#propuestadevalor)
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
21. [Backlog](#backlog)
22. [Gestion Agile](#gestionAgile)
[Prototipo](#gestionAgile)


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
- Pago de boleto con celular
- Notificaciones:
    * La línea seleccionada está por llegar a la parada de ómnibus.
    * La siguiente parada es tu destino.
    * Tu línea frecuente llega en X minutos (dependiendo de la distancia del usuario a la parada) a tu parada habitual.
    * La línea seleccionada tiene un retraso y demorará en llegar a tu parada origen.
    * La línea seleccionada tiene un desvío.

Atributos de calidad (RNF):
   * Alcance a toda la población uruguaya.
   * Fácil de usar por las distintas franjas etarias de población.
   * Privacidad de datos sensibles de sus usuarios.
   * Interfaz principalmente móvil (Android).

## Propuesta de valor <a name="propuestadevalor"></a>  
**BONDi: horarios de ómnibus al alcance de tu mano.**
![Logo](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Logos/logo-white.png)
Ofrecemos flexibilidad y conveniencia adaptada a los usuarios del transporte público colectivo.
- Un nuevo sistema para satisfacer la necesidad de los usuarios a través de una única aplicación móvil para dispositivos Android que integra a toda la red de proveedores de transporte público de Uruguay.
-  BONDi propone más flexibilidad y conveniencia, permitiendo satisfacer las necesidades específicas para cada usuario, en términos de elección de ruta y tiempos de viaje.
-Nuestro ecosistema es dinámico y evoluciona constantemente
- La propuesta de valor clave para los usuarios es a través de la búsqueda de rutas, el despliegue de información de paradas cercanas, detalle de la ocupación del bus, horarios, pago de boleto, historial de rutas y más.
- Somos pioneros en la compra del boleto urbano a través de nuestra tecnología, permitiendo integrar distintos métodos de pago.
- Facilitamos la comunicación con la familia o amigos al permitir compartir el viaje, brindando comodidad y seguridad.
-Permitimos generar oportunidad de mercado a las distintas empresas de transporte público del país, brindando mayor flujo de usuarios y generando una mejora en los servicios que proveen a sus clientes.
- Al brindar a los ciudadanos mejores servicios de transporte promovemos el uso de transporte público, ayudando a respetar el medio ambiente al reducir la contaminación generada.

# Marco de Gestión <a name="marcodegestion"></a>

Para la gestión de este proyecto vamos a utilizar Scrum, con las ceremonias: 

- Sprint Planning
- Daily
- Sprint Retrospective
- Sprint Review
- Backlog Refinement

## Planning <a name="planning1"></a>
Se va a realizar el primer día de cada sprint, la duración aproximada va a ser de 2 horas, se va a estimar utilizando planning poker. La escala de Story Points va a ser Fibonacci, considerando que 13 o mayor significa que la Story es muy compleja para ser completada en un sprint y va a necesitar ser dividida en partes más pequeñas.

## Daily <a name="daily1"></a>
Dada la naturaleza de nuestro proyecto no va a tener mucho sentido el reunirse a diario a revisar progreso dado que no vamos a poder generar un progreso diario. Para ello vamos a tener 3 daily por semana distribuidas de la siguiente forma

- Jueves
- Sábado
- Domingo

Esto se debe a que la mayor contribución del equipo se concentra en los fines de semana, entonces nos parece importante que ahí sí se respete la daily. Se va a realizar por llamada en WhatsApp.
Esto nos da 2 ventajas claras:
1. Facilita la coordinación, ya que no necesitamos estar físicamente en el mismo lugar y WhatsApp es una aplicación que todos utilizamos.
2. Al ser 3 veces a la semana nos permite revisar el progreso del sprint conforme los momentos de trabajo que va a tener nuestro equipo. Ya que de lunes a viernes por diferentes circunstancias no se espera demasiado progreso, poner una daily diaria implicaría muchas veces que no hay updates, con lo cual supone una perdida de tiempo. Sin embargo si fuera menor la frecuencia terminaría quedando muchos días sin sincronización, con lo cual podría generar situaciones complicadas a la hora de gestionar el proyecto.

## Sprint Retrospective <a name="sprintretrospective"></a>
Esta ceremonia va a suceder el último día del sprint (viernes), va a tener una duración máxima de 30 minutos y todos los action items van a ser convertidos en product backlog items, priorizados e ingresados en el próximo sprint planning para considerar y aplicar las mejoras.

## Sprint Review <a name="sprintreview"></a>
Esta ceremonia va a suceder el último día del sprint (viernes) y todo el feedback recibido va a ser convertido en product backlog items que luego deben ser priorizados con el PO e ingresados en futuros sprints. No va a durar más de 30 minutos y el objetivo es mostrar el incremento generado durante el sprint al PO para su validación.

## Backlog Refinement <a name="backlogrefinement"></a>
Se va a realizar un refinamiento del backlog cada jueves a excepción de la última semana de cada sprint, en este caso el equipo va a estar enfocado en la planning y estimación del siguiente sprint.

## Capacity <a name="capacity"></a>
Se va a considerar que cada miembro puede trabajar en total 7hs semanales.

## Definition of Ready <a name="dor"></a>
Una User Story se considera pronta para ser incluida en una planning si cumple con las condiciones:

- Es clara y realizable: el equipo entiende la User Story y puede descomponer la User Story en tareas las cuales todas son realizables dentro de un sprint considerando dependencias.
- Es testeable: el equipo pudo identificar distintos escenarios (al menos el happy path) para poder testear la User Story.
- Acceptance criteria está definido en lenguaje BDD y el equipo lo revisó y lo entiende.
- Las dependencias fueron identificadas claramente. El equipo sabe bien qué otras tareas se deben completar antes (si existe alguna) para poder comenzar a trabajar en la Story.
- Es demostrable: el equipo tiene en claro como hacer una demo de la User Story, tiene identificados a los stakeholders o interesados que corresponda demostrar la Story.


## Definition of Done <a name="dod"></a>
* La Definición de Done es un acuerdo entre el equipo de desarrollo y el Product Owner sobre lo que debe completarse para cada User Story.
* Son los criterios de aceptación acordados, que el Product Owner utilizará para aceptar el incremento del producto al final del sprint.
* En nuestro proyecto, el DoD va a ser diferente para los sprints, ya que abarcan distintas etapas del proyecto.
* Para el sprint 1, el DoD de las user story va a contemplar:
  * Evidencia de la tarea realizada mediante documentación.
  * Registro de Horas que llevó la tarea.
  
## Estrategias de Branching y Pull Request <a name="estrategiaBranching"></a> 
 - Ver documento [Estrategia de Branching.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Estrategia%20de%20Branching.pdf)
 -  Para los pull request se establece la metodología que 2 approvers  deben validar la información que se ingresa a la rama Iteracion-X.  Siendo x el sprint correspondiente y luego desde la rama Iteracion-X que se hace el merge a main .  El desarrollador que genera el request es responsable de notificar a 2 colegas ya sea usando la función de Review de Github o notificarlos por otro medio.
 - Estructra de Git por Iteración:
    - [GIt-Iteracion1-Main.png](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Capturas/GIt-Iteracion1-Main.png) 
 
## Roles: <a name="roles"></a>

**Scrum Master:**

  - Daniel Cabrera:
    - Encargado de gestionar y asegurar que el proceso Scrum se lleva a cabo correctamente.
    - Facilitar la ejecución del proceso y sus mecánicas.
    - Tratar de eliminar impedimentos que van surgiendo. 
  
**Product Owner:**
  
* Suren Keushkerian:
    * Encargado de optimizar y maximizar el valor del producto.
    * Gestionar el Product Backlog para manetenerlo estructurado y priorizado.
  
**Developers:**

  - Denise Souberville
  - Leandro Avogadro
  - Daniel Cabrera
  - Suren Keushkerian

* Encargados de  desarrollar el producto.
    * Son responsables de ser auto-organizádos y auto-gestionádos para entregar un incremento de software al final del sprint.
    * Participan activamente en las ceremonias de Scrum.
  
# Análisis de Requerimientos #
## Relevamiento de aplicaciones existentes <a name="relevamientoAplicaciones"></a>

Aplicamos el proceso de ingeniería inversa a 3 aplicaciones ya existentes en el mercado, a los efectos de obtener mayor entendimiento del problema, lograr obtener ideas para adaptar a nuestra solución e intentar agregar mejoras o nuevas funcionalidades al backlog que puedan darle un valor agregado al producto. 

### Formulario de investigación <a name="formularioInviestiagcion"></a>
Se creó un formulario para la investigación de las aplicaciones existentes, el cuál fue completado para cada una de las aplicaciones Moovit, ComoIr y Citymapper.
- Ver [Formulario Analisis Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Formularios/Formulario%20Analisis%20Aplicaciones.docx)
- Ver [Analisis Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Analisis%20Aplicaciones.docx)

## Realización de Encuestas <a name="realizacionEncuestas"></a>

Procedimos también a buscar ideas y requerimientos mediante la realización de encuestas a algunos usuarios del transporte público de Montevideo.

#### Formulario mediante Google Forms

Se realizó un formulario con 8 preguntas para lograr recabar información tal como las edades de los usuarios,tiempo de espera en la parada, demora del trayecto, cantidad de ómnibus para completar el viaje, funciones más comunes que usa de la aplicación de viaje y cualquier otra función que consideran necesario. El informe completo de la encuesta se encuentra en la carpeta Evidencias.

- Ver [Encuesta de Apliacion de Viaje.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Encuesta%20de%20Aplicacion%20de%20Viaje.pdf)

## Procesamiento de datos <a name="procesamientoDeDatos"></a>
Se realizó un análisis de la información obtenida mediante el relevamiento de aplicaciones existentes y la realización de encuestas para obtener nuevos requerimientos, cuyos resultados quedaron adjuntos en el repositorio.

- Ver [Procesamiento de Encuestas y Análisis de Aplicaciones.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Procesamiento%20de%20Encuestas%20y%20An%C3%A1lisis%20de%20Aplicaciones.docx)

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

- Ver [AnálisisDeInteresadosBONDi.docx](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/An%C3%A1lisisDeInteresadosBONDi.docx)

### Detalle de las funcionalidades por stakeholder ###

**Usuarios:**
- Login de usuario.
- Registrar nuevo usuario.
- Editar usuario.
- Restaurar contraseña.
- Buscar línea de ómnibus utilizando filtros.
- Listado de las líneas más cercanas al usuario con información del destino/origen/tiempo estimado, con la información de cantidad de pasajeros en las mismas.
- Historias de los últimos viajes (líneas de ómnibus utilizadas).
- Modo viaje. El usuario debe poder seguir el trayecto de la línea de ómnibus a la que se subió, pudiendo saber en qué parte del recorrido se encuentra, cuáles son las paradas hasta el próximo destino e información del destino.
- Compartir mi viaje a otro usuario.
- Pago de boleto con celular
- Escalabilidad a toda la población uruguaya.
- Alcance a toda la población uruguaya.
- Fácil de usar por las distintas franjas etarias de población.
- Privacidad de datos sensibles de sus usuarios.
- Interfaz principalmente móvil (Android).
- Notificaciones:
    * La línea seleccionada está por llegar a la parada de ómnibus.
    * La siguiente parada es tu destino.
    * Tu línea frecuente llega en X minutos (dependiendo de la distancia del usuario a la parada) a tu parada habitual.
    * La línea seleccionada tiene un retraso y demorará en llegar a tu parada origen.
    * La línea seleccionada tiene un desvío.
**Gobierno:**
- Alcance a toda la población uruguaya.
- Privacidad de datos sensibles de sus usuarios.
**Empresas de transporte:**
- Buscar línea de ómnibus utilizando filtros.
- Listado de las líneas más cercanas al usuario con información del destino/origen/tiempo estimado, con la información de cantidad de pasajeros en las mismas.
- Pago de boleto con celular
**Playstore**
-Interfaz principalmente móvil (Android).

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

## Backlog <a name="backlog"></a>
 * Ver imagen [ProductBacklog.png](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Capturas/ProductBacklog.png).
 * El criterio para dar prioridad al backlog se basó en lograr primero la mayor cantidad de funciones que son requeridas para el sistema, según la letra del obligatorio, pero a su vez poner una función de valor adicional tanto en el Sprint 2 como el Sprint 3.Se busca lograr una funcionalidad básica que luego permita seguir incrementando en valor agregado en futuros sprints.


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
[RetroISA1Sprint1.csv](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%201/Evidencias/Sprint/RetroISA1Sprint1.csv)

**Análisis:**
En términos generales, respecto a lo que deberíamos empezar a hacer o mejorar, el equipo concordó en que se debería crear eventos en google calendar para la coordinación de las reuniones, también que se deberían de mejorar algunos aspectos de comunicación en cuanto a si no se puede asistir a alguna reunión o si no se llega con las tareas. Se podría mejorar en el uso de la herramienta de devops y en la organización de la documentación.

En consideración a lo que se debería dejar de hacer, se hace mención a situaciones respecto a la puntualidad de las reuniones y al poco avance en general de la entrega en los primeros días del sprint.

En cuanto a la parte positiva y como cosas a mantener, se destacan como punto fuerte la comunicación y flexibilidad entre los compañeros, la eficacia de las daily y la disposición de reasignación de tareas durante el desarrollo del sprint.


Se crearon los siguientes items en el backlog como consecuencia de los action items

- Setear ceremonias del Sprint en google calendar por parte del Scrum Master.
- Crear dashboard de completed work por persona.
- Crear dashboard con cantidad de tareas por persona y sus status.
- Generar esqueleto de documentación para el sprint.
- Actualizar documentación respecto a Pull Requests.
- Actualizar documentación de manejo del board.

## Sprint 2 ##
### Planning ###

Para este segundo sprint el objetivo era trabajar en las primeras pantallas de la aplicación y comenzar con el diseño de esto.

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Planning/Planning.png)

En este segundo sprint el equipo tuvo que agregar algunas Stories durante el sprint, por diferentes items que nos perdimos durante la planificación y que no estaban en el backlog. Eso nos llevó a tener que realizar una segunda planning documentada abajo

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Planning/Planning2.png)

### Sprint Progress ###

![Sprint Progress1](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Sprint/sprint1.png)

![Sprint Progress2](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Sprint/sprint2.png)

![Sprint Progress3](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Sprint/sprint3.png)

![Sprint capacity](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Sprint/capacity.png)

**Burndown**

En este sprint logramos tener un desempeño más parejo que el anterior, pudiendo ser un poco más constantes en el esfuerzo.

Por otro lado también se puede observar algunos puntos de subida en el burndown que corresponden a esos momentos en que se agregaron nuevas User Stories, como se mencionó en la sección Planning.

![Burndown chart](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/Sprint/burndown.png)

**Velocity**
Si consideramos los Story Points para los últimos 2 Sprints
Sprint 1 - 36
Sprint 2 - 32

La velocidad del equipo se puede calcular como
(36+32) / 2 = 34

Mejor Sprint = 36
Peor Sprint = 32

Por lo tanto la velocidad de nuestro equipo es 34.

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

Para este sprint decidimos usar una retrospectiva diferente, en este caso la idea es intentar analizar por un lado las cosas buenas del equipo y por otro los problemas que surgieron durante el sprint con el delivery. Al ser el primer sprint que tenía un producto para liberar, nos pareció una buena oportunidad para analizarlo de esta forma.

[The Boxing Ring](https://metroretro.io/BOP0LNN2YA19 "The Boxing Ring")

Los resultados de la Retrospective se pueden encontrar en el archivo

"Iteracion 2\Evidencias\Sprint\Sprint-2-102022.csv"

Como se puede observar por los resultados hubo una buena coordinación del lado del equipo, entendemos que eso es de las cosas que hicimos mejor.

Mientras que por otro lado en cuanto a los problemas evidenciados se observa el problema de planificación que tuvimos por los items que identificamos tarde en el sprint, para lo cual se creó un item para revisar la rúbrica previo a la iteración y crear las stories necesarias. El otro feedback que surgió fue respecto al uso de framer y la creación de los prototipos, que por un lado framer nos pareció una herramienta más difícil de lo que esperábamos y por otro lado el proceso de diseño de los prototipos fue un poco caótico, sin lineamientos de estilo y con poca coordinación en ese sentido. Para esto se creo un item para elegir una pantalla como referencia de look and feel para ajustarnos a ese ejemplo. 

### StoryMap ###
A continuación se documenta el roadmap generado hasta el sprint 2.
Como se puede observar hay algunas funcionalidades que el equipo considera valiosas pero no hay suficiente capacidad para completarlas, con lo cual las consideramos para el sprint 5 en adelante, junto con las subsecuentes mejoras que puedan surgir a lo largo de los sprints restantes.

![Sprint capacity](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Evidencias/specmap-Obligatorio%20ISA1-Roadmap.png)

## Sprint 3 ##
### Planning ###
Para este tercer sprint el objetivo es completar lo más posible la aplicación, intentando cumplir con todas las funcionalidades pedidas. Para eso el equipo estimo y considero 32 Story Points, algo bastante cercano a la velocidad actual del equipo 34.

![Planning](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%203/Evidencias/Planning/Planning.png)

![Planning2](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%203/Evidencias/Planning/Planning2.png)

### Sprint Progress ###


**Burndown**

**Velocity**
Si consideramos los Story Points para los últimos Sprints
Sprint 1 - 36
Sprint 2 - 32
Sprint 3 - 32

La velocidad del equipo se puede calcular como
(36+32+32) / 3 = 34

Mejor Sprint = 36
Peor Sprint = 32

Por lo tanto la velocidad de nuestro equipo es 34.


### Daily ###
**Registro de daily realizada el 15/10**


### Retrospective ###
 

### StoryMap ###

# Prototipo # <a name="Prototipo"></a>
Link a Framer:
https://framer.com/projects/Untitled--qyTLTLUuXGXdJQfm3l02-fpOLN
Link aL prototipo publicado:
https://happen-forego-312426.framer.app/

Las funcionalidades implementadas en el primer release fueron:
- Registro de usuario
- Login de usuario
- Editar usuario
- Agregar método de pago
- Búsqueda de lineas
- Lineas cercanas
- Pago de boleto con celular

## Evidencia ##
A continuación se deja evidencia visual de las diferentes pantallas
| -|-  |
|---|---|
| ![Pantallaprincipal](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/1.png) | ![MenuDesplegado](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/2.png) | 
| ![Registro](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/3.png) | ![Login](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/4.png) | 
| ![RestaurarPass](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/5.png) | ![IngresarMail](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/6.png) |
| ![MenuLogged](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/7.png) | ![MetodoPago](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/8.png) |
| ![ConfigurarTarjeta](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/9.png) | ![TarjetaAgregada](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/10.png) | 
| ![Lineas](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/11.png) | ![MapaLinea](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/12.png) |
| ![LineasCercanas](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/13.png) | ![OpcionPago](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/14.png) | 
| ![EdicionUsuario](https://raw.githubusercontent.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/Iteraci%C3%B3n%202/Prototipo/15.png) |

## Validación ##
Se procedió a realizar una encuesta de google forms a algunos usuarios de transporte urbano para validar el prototipo generado, el esqueleto del formulario y los datos de las respuestas se encuentran a disposición en los documentos [EncuestaPreguntas.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/EncuestaPreguntas.pdf) y [EncuestaRespuestas.pdf](https://github.com/SurenSebastian/Avogadro-Cabrera-Keushkerian-Souberville/main/EncuestaRespuestas.pdf)

### Análisis del feedback de usuarios
-En terminos generales de la aplicación, algunos usuarios manifestaron su conformidad, mientras que otros comentaron que encontraron dificultad para encontrar los paneles de registro, inicio de sesión y edición de usuario. La opinión sobre el estilo/diseño de la aplicación no tuvo comentarios negativos, a excepción de alguna desconformidad con los colores elegidos. También se sugirió utilizar en la aplicación todo en español o todo en inglés y no ambos.
-Como funcionalidades que podriamos agregar fueron sugeridas: mostrar ubicación de los omnibus en tiempo real, opción de busqueda de viaje ingresando inicio y destino, agregar accesibilidad para no videntes y agregar una opción que permita buscar cuanto demora en promedio un bus en llegar de una parada a otra.
-Respecto a las funcionalidades de inicio de sesión y registro, algunos usuarios sugirieron mostrar un icono en el menu principal que muestre si estás logged, aunque actualmente se encuentra implementado tal vez no esté lo suficientemente visible para el usuario. También se sugirió que en los campos de ingreso de fecha de nacimiento, se utilice un calendario que permita seleccionar la fecha.
-En cuanto a los datos de usuario, se sugirió que exista una pantalla que muestre los datos del usuario, previo a la edición.
-De la funcionalidad de pago se sugiere que se informe en algún área qué métodos de pago se encuentran asociados y que en caso de permitir tener más de uno se pueda seleccionar el deseado antes del pago.
-Para las funcionalidades que impliquen ingresar una dirección que exista un botón que permita seleccionar automáticamente la ubicación actual del usuario.

Se crearon los siguientes items en el backlog como consecuencia de la validación de usuario

- Corregir dualidad de idioma en toda la aplicación.
- Busqueda de viaje con incio/destino
- Calculo tiempo estimado entre una parada y otra
- Reubicar el icono de usuario logeado para hacerlo mas visible
- Pantalla para ver datos de usuario (Previa a edición)
- Ver metodos de pagos asociados
- Seleccionar metodo de pago a usar
- Seleccionar ubicación actual


# Bibliografía #


- [Gherkin](https://profile.es/blog/que-es-gherkin/)
- [Definition of Ready](https://agility.im/frequent-agile-question/what-is-a-definition-of-ready/)
- [Definition of Ready vs Definition of Done](https://www.linkedin.com/pulse/definition-ready-dor-vs-done-dod-brian-will)
