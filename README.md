<p align="center">
  <img src="images/Upclo.png" alt="Logo de UPC" width="100%">
</p>

# Universidad Peruana de Ciencias Aplicadas

## Carrera de Ingeniería de Software

<div align="center">

Ciclo: 2024 - 1

Curso: Aplicaciones Web

Sección: SW55

Profesor: Francisco José Cáceres Honores

Startup: PetPal

Producto: PetPal

|            Integrantes              |   Código   |
| :---------------------------------: | :--------: |
|    Francis Daniel Mamani Silva      | u202219315 |
|        Ian Macavilca Quispe         | u202121325 |
|  Frank Junion Salazar Saldarriaga   | u20181h103 |
| Paolo Del Carmen Martines Villanueva| u202010039 |
|   Michael Stefano Carmelino Dueñas  | u202212760 |

</div>

# **Registro de Versiones**

| Versión   | Fecha       | Autor      | Descripción                                                                                      | Estado    |
|-----------|-------------|------------|--------------------------------------------------------------------------------------------------|-----------|
| 1.0       |  2024/03/18    | | Creación del documento de trabajo en formato markdown. | Completado  |
| 1.1       |  2024/03/18    | | Agregar la plantilla del reporte en markdown | Completado  |
| 1.2       |  2024/03/18    | |Redacción del startup profile y solution profile, delimitación de segmentos objetivo, redacción de preguntas para el diseño de entrevistas |Completado|
| 1.3       |  2024/03/18    | |Elaboración y registro de entrevistas a segmentos objetivo, análisis de entrevistas    | Pendiente |
| 1.4       |  2024/03/18    | |Elaboración de user personas, user task matrix, user journey mapping, empathy mapping, as-is   | Pendiente |
| 1.5       |  2024/03/18    | |Elaboración de to-be, impact mapping   | Pendiente |
| 1.6       |  2024/03/18    | Martinez Villanueva, Paolo Del Carmen |Elaboración de user stories, product backlog | Completado |
| 1.7       |  2024/03/18    | |Elaboración de prototipos de wireframes y mockups  | Pendiente |
| 1.8       |  2024/03/18    | |Redacción de style guidelines e information architecture| Pendiente |
| 1.9       |  2024/03/29    | Martinez Villanueva, Paolo Del Carmen |Elaboración de diagrama de base de datos,diagrama de clases, diccionario de clases, diagramas de contenedores, diagramas de contexto, diagramas de componentes | Completado |
| 2.0       |  2024/03/18    | |Registro de evidencias del Sprint 1 | Pendiente |
| 2.1       |  2024/03/18    | |Rediseño de mockups. Elaboración de wireflows y user-flows| Pendiente |
| 2.2       |  2024/04/04    | Martinez Villanueva, Paolo Del Carmen | Redacción de software configuration management, sprint planning 1, sprint backlog 1 | Completado |
| 2.3       |  2024/03/18    | |Redacción de Collaboration Insights | Pendiente |

# **Project Report Collaboration Insights**

URL Project Report (Github): https://github.com/PetPalORG/PetPal-Informe

# **Tabla de Contenido**

- [Registro de Versiones](#registro-de-versiones)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#Capítulo-I-Introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#Capítulo-II-Requirements-Elicitation--Analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#23-ubiquitous-language)
- [Capítulo III: Requirements Specification](#Capítulo-III-Requirements-Specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#Capítulo-IV-Product-Design)
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#Capítulo-V-Product-Implementation-Validation--Deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint n](#521-sprint-n)
      - [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n) -[5.2.1.2. Sprint Backlog n](#5212-sprint-backlog-n)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)
 
# **Capítulo I: Introducción** 

**1.1. Startup Profile** 

Actualmente, las mascotas ya no son consideradas simplemente animales domésticos a los cuales mantenemos en casa, estos ahora son considerados miembros importantes de la familia en muchos hogares, y el desarrollo de tecnologías que faciliten y mejoren su cuidado está en aumento.

Según datos recientes, se tiene estimado que el 67% de los hogares en el país tienen como mínimo una mascota, y esta cifra no ha dejado de crecer con el pasar de los años. Sin embargo, a pesar de la importancia que le damos a nuestras mascotas, aún se tiene la necesidad de herramientas que gestionen de manera óptima el cuidado de los engreídos del hogar. 

**1.1.1. Descripción de la Startup** 

PetPal es una aplicación dedicada al cuidado de nuestras mascotas diseñada para hacer más sencillo a los clientes la gestión y seguimiento de la salud y bienestar de nuestras mascotas. Nos brinda una plataforma intuitiva la cual permite a los usuarios la creación de perfiles personalizados para cada uno de nuestros engreídos, donde puedes registrar información esencial como la dieta, las vacunas, las citas a la veterinaria y otros aspectos importantes en el cuidado de nuestras mascotas. Además, Petpal nos ofrece acceso a recursos y consejos de expertos en el cuidado de mascotas, para de esta manera ayudar a los dueños a tomar decisiones de manera responsable sobre la salud y el bienestar de nuestros engreídos.

**1.1.2. Perfiles de integrantes del equipo**

|**Integrantes**|**Descripción del Perfil**|
| :-: | :-: |
|**Michael Stefano Carmelino Dueñas (U202212760)**|Estudiando la carrera de Ingeniería de Software en la UPC, tengo conocimientos básicos en C++, Python y Java. Soy una persona que le gusta el liderazgo y organización en equipo, coordinación y poder generar un buen entorno. Ayudo a quienes lo necesiten con lo máximo que pueda. De igual forma tengo conocimientos en los que son fundamentos en Ciencia de Datos.|
|<p>**Frank Junior Salazar Saldarriaga**</p><p>**(U20181H103)**</p><p></p>|Mi nombre es Frank Junior Salazar Saldarriaga, estudiante de la carrega de ingeniería de software de la UPC, tengo conocimientos en lenguajes como C++, Python, Java, C#, .net, Angular. Soy una persona proactiva y autodidacta.|
|<p>**Integrante 3**</p><p>**Francis Daniel Mamani Silva(U202121325)**</p><p></p>|Mi nombre es Francis Daniel Mamani Silva, un estudiante de 19 años de origen peruano con una pasión desenfrenada por los videojuegos. Actualmente estoy inmerso en mi carrera de Ingeniería de Software, donde combino mi amor por la tecnología con mi fascinación por los juegos. Destacándome en mis estudios universitarios, aspiro a fusionar estos dos mundos para contribuir al desarrollo de experiencias interactivas innovadoras. Mi energía optimista, junto con mi creatividad y determinación, me posicionan como un futuro líder en la industria del desarrollo de software.|
|<p>**Integrante 4**</p><p>**Ian Macavilca Quispe (U202121325)**</p><p><br></p>|Como estudiante de Ingeniería de Software, mi destreza en el pensamiento lógico me habilita para abordar desafíos de manera eficaz, optimizar procesos, diseñar software robusto, comunicar de manera clara, ser resiliente ante obstáculos y colaborar efectivamente en equipos, con lo que pienso aportar al éxito y eficiencia de la startup.|
|<p>**Integrante 5**</p><p>**Paolo Del Carmen Martinez Villanueva (U202010039)**</p><p></p>|Mi nombre es Paolo Del Carmen Martinez Villanueva, soy estudiante del 6to ciclo de la carrera de Ingeniería de Software con conocimientos de programación intermedios. Me considero una persona responsable, ordenada y trabajadora. Por ello, pongo en disposición mis conocimientos y mi forma de trabajar y me comprometo a apoyar a mi equipo y a adquirir nuevos conocimientos para poder aportar todo lo que sea necesario para el trabajo.|

**1.2. Solution Profile**

El cuidado de las mascotas es una preocupación latente en cada uno de los propietarios, pero una gran cantidad enfrenta dificultad para gestionar la información importante sobre nuestras mascotas, como la dieta o sus vacunas de manera eficiente. Por otro lado, encontrar consejos de personas expertas y recursos para el cuidado de nuestras mascotas puede ser un desafío en un mundo de información en las cuales se contradicen unas con otras.

**1.2.1 Antecedentes y problemática**

**What?**

PetPal es una aplicación la cual fue diseñada para volver más sencillo el cuidado de nuestras mascotas, de esta manera haciendo posible a los dueños el gestionar y llevar a la mano aspectos con mucha importancia como citas veterinarias, la dieta y el acceso a una opinión experta para el cuidado de nuestros engreídos.


**Why?**

Porque la preocupación por la salud de nuestras mascotas y la escasez de herramientas óptimas para gestionar su cuidado va en crecimiento. La existencia de una brecha en el mercado para las soluciones confiables derivadas de la opinión de un experto, lo que lleva a tomar decisiones apresuradas afectando la calidad de vida de nuestras mascotas.

**Where?** 

El problema surge en las familias de todo el país las cuales consideran a sus mascotas como miembros importantes de la familia. Además, se puede visualizar a nivel mundial, ya que la importancia que actualmente se le brinda a nuestras mascotas y la preocupación por ellas es universal.

**When?** 

La necesidad se va dando a medida que nuestra sociedad va reconociendo la importancia del bienestar de nuestra mascota y la necesidad de brindarles la mejor atención con herramientas óptimas para la gestión del cuidado de nuestros compañeros peludos.

**Who?**

Los dueños de estas mascotas son principalmente los afectos, ya que estos tienen que superar desafíos para una correcta gestión en el cuidado de sus mascotas. Además, las mascotas mismas también tienen un problema cuando no pueden recibir un correcto cuidado.

**How?**

PetPal aborda esta problemática proporcionando una plataforma integral que permite a los propietarios de mascotas gestionar fácilmente el cuidado de sus amigos peludos, desde el seguimiento de la dieta y las citas veterinarias hasta el acceso a consejos de expertos en cuidado de mascotas, todo a través de una interfaz intuitiva y centralizada.


**1.2.2 Lean UX Process.**

**1.2.2.1. Lean UX Problem Statements.**

Propietarios de mascota:

Existe la dificultad entre los propietarios para mantener un registro correcto de información importante sobre nuestras mascotas, tales como dieta o citas veterinarias. Además, existen problemas al momento de intentar conseguir recursos y consejos para el cuidado de nuestras mascotas, debido a la información contrariada que existe.

¿Cómo podemos ayudar a los propietarios a llevar una correcta gestión de la información de sus mascotas, y poder conseguir información confiable para conseguir recursos y consejos sobre el cuidado de nuestra mascota.

**1.2.2.2. Lean UX Assumptions.**


- **User Assumptions**

**¿Quién es el usuario?** Personas que consideran a sus mascotas como parte esencial de la familia.

**¿Dónde encaja nuestro producto, en su trabajo o en su vida?** En su vida

**¿Qué problema resuelve nuestro producto?** Mejora la calidad de vida de las mascotas de los clientes.

**¿Cuándo y cómo se utiliza nuestro producto?** Siempre que necesiten registrar información sobre su mascota o conseguir consejos de expertos para su cuidado, todo esto posible ingresando a la app.

**¿Qué características son importantes?** El registro de información importante de nuestra mascota y el poder conseguir información sobre dónde conseguir recursos, y consejos para el cuidado de nuestras mascotas.

**¿Cómo debe verse y comportarse nuestro producto?** Funcional, eficaz y minimalista, donde el usuario pueda registrar la información de sus mascotas de forma sencilla y realizar la búsqueda de información para el cuidado de sus mascotas.

**1.2.2.3. Lean UX Hypothesis Statements.**


- Usuario cliente

**Creemos que** al ofrecer una aplicación móvil para el cuidado de mascotas con funcionalidades de seguimiento y acceso a consejos de confianza

**Lograremos** mejorar la experiencia de los dueños de mascotas y aumentaremos su satisfacción.

**Sabremos que hemos tenido éxito** cuando seamos la aplicación para los cuidados de nuestras mascotas con más descargas.

**1.2.2.4. Lean UX Canvas.**


![Lean UX Canvas Template](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/102317309/3e04f774-c29e-40e7-b844-66e6dc3e0e4d)



**1.3. Segmentos objetivo.**

Propietarios de mascotas que buscan una solución conveniente para gestionar la salud y el bienestar de sus animales de compañía.

Personas interesadas en obtener consejos y recursos confiables sobre el cuidado de mascotas en una sola plataforma.

Este perfil proporciona una visión detallada de PetPal, incluyendo la descripción de la startup, los perfiles del equipo, el contexto del problema, el proceso Lean UX y los segmentos objetivo.


# **Capítulo II: Requirements Elicitation & Analysis**

2\.1. Competidores

El examen de la competencia es fundamental para la toma de decisiones estratégicas, la detección de oportunidades y riesgos, así como para establecer ventajas competitivas duraderas en el mercado. Por estas razones, es vital para las empresas mantenerse ágiles y tomar decisiones bien fundamentadas en un entorno empresarial en constante evolución. A continuación, se presenta cómo se integra esta práctica en el desarrollo del proyecto y se analizan los competidores:

2\.1.1. Análisis competitivo.

<table><tr><th colspan="6" valign="top">Competitive Analysis Landscape</th></tr>
<tr><td colspan="2" rowspan="2" valign="top">¿Por qué llevar a cabo este análisis?</td><td colspan="4" valign="top">¿Quiénes son nuestros principales competidores?</td></tr>
<tr><td colspan="4" valign="top">Mediante el estudio de la competencia en el mercado, se adquiere una comprensión clara del entorno competitivo en el que nuestro producto se desenvolverá. Esto nos permite identificar tanto a nuestros competidores directos como indirectos y elaborar estrategias basadas en la información recopilada sobre su posición actual en el mercado.</td></tr>
<tr><td rowspan="3" valign="top">PERFIL </td><td rowspan="2" valign="top">Overview </td><td valign="top"><p>PetPal</p><p></p></td><td valign="top"><p>Pet First Aid</p><p></p></td><td valign="top"><p>Go Pets</p><p></p></td><td valign="top"><p>Vet+O </p><p></p></td></tr>
<tr><td valign="top">PetPal es una aplicación que simplifica el cuidado de mascotas al permitir a los usuarios crear perfiles personalizados para sus animales. Ofrece funciones para registrar información vital como dieta, vacunas y citas veterinarias. Además, proporciona acceso a recursos y consejos de expertos en cuidado animal, facilitando a los propietarios tomar decisiones informadas sobre la salud y el bienestar de sus mascotas. Es una plataforma intuitiva diseñada para hacer más fácil el seguimiento y la gestión de la salud de los animales domésticos.</td><td valign="top">Pet First Aid es esencial para todos los dueños de mascotas. Ya sea que estés lidiando con lesiones menores o enfrentando una situación de emergencia, saber cómo proporcionar atención inmediata puede marcar una gran diferencia en el bienestar de tu mascota. Aquí tienes algunos recursos para ayudarte a estar preparado:</td><td valign="top">GoPets es una plataforma enérgica y cautivadora dedicada a todo lo relacionado con mascotas y animales. Su misión es involucrar, educar e inspirar a los amantes de los animales en todo el mundo.</td><td valign="top">Vet+O es una aplicación para dispositivos móviles que conecta a los dueños de mascotas con médicos veterinarios en cualquier momento del día. A través de videollamadas, los usuarios pueden recibir asesoría veterinaria sin importar la hora o el lugar.</td></tr>
<tr><td valign="top">Ventaja Competitiva ¿Qué valor ofrece a los clientes? </td><td valign="top"><p>- ` `Ampliación de la Comunidad en Línea: Desarrollar una plataforma de comunidad en línea donde los usuarios puedan compartir experiencias, consejos y preguntas sobre el cuidado de sus mascotas, creando así una red de apoyo y conocimiento.</p><p>- Asistencia 24/7: Ofrecemos ayuda  y asistencia en cualquier momento del día en caso de que ocurra una emergencia</p><p>- Permite el registro de las mascotas, brindando una base de datos amplia sobre distintos aspectos de estos.</p><p></p></td><td valign="top"><p>Proporciona educación en primeros auxilios y RCP para mascotas. Los profesionales capacitados en primeros auxilios pueden actuar rápidamente en situaciones de emergencia.</p><p>Valor para los Clientes:</p><p>- Seguridad: Los clientes confían en que sus mascotas están en buenas manos.</p><p>- Respuesta inmediata: En caso de emergencia, los cuidadores saben qué hacer sin demoras.</p><p>- Calidad de servicio.</p><p></p></td><td valign="top"><p>Su enfoque en localización de clínicas veterinarias cercanas a través de GPS es una característica única.</p><p>Valor para los Clientes:</p><p>- ` `Acceso rápido a atención veterinaria: Encontrar clínicas cercanas en caso de emergencia.</p><p>- Recordatorios de citas médicas: Ayuda a mantener el bienestar de las mascotas.</p><p>- Fácil uso: interfaz interactiva con el usuario.</p><p></p></td><td valign="top"><p>Ofrece asesoría veterinaria en línea 24/7 a través de videollamadas.</p><p>Valor para los Clientes:</p><p>- Acceso inmediato a veterinarios: Resuelve dudas y preocupaciones en cualquier momento.</p><p>- Comodidad: Evita desplazamientos y largas esperas en clínicas.</p><p>- Registro de mascotas: Permite crear perfiles con información médica relevante</p><p> </p><p></p></td></tr>
<tr><td rowspan="2" valign="top">PERFIL DEL MARKETING </td><td valign="top">Mercado Objetivo </td><td valign="top"><p>Propietarios de mascotas primerizos: Aquellos que recientemente han adquirido una mascota y buscan orientación y recursos para el cuidado adecuado.</p><p></p></td><td valign="top">Dueños de mascotas y personas responsables del cuidado de animales.</td><td valign="top"><p>Dueños de mascotas y personas que trabajan en clínicas veterinarias, refugios de animales y guarderías para mascotas.</p><p></p></td><td valign="top"><p>Dueños de mascotas que buscan asesoría veterinaria en línea.</p><p></p></td></tr>
<tr><td valign="top">Estrategias de Marketing</td><td valign="top"><p>Marketing de redes sociales: Utilizar plataformas como Instagram y Facebook para compartir contenido relevante sobre el cuidado de mascotas y testimonios de usuarios satisfechos.</p><p>Colaboraciones con influencers: Asociarse con expertos en cuidado de mascotas para promocionar la aplicación a través de reseñas y publicaciones patrocinadas.</p><p>Programa de referidos: Implementar un programa que recompense a los usuarios por recomendar la aplicación a amigos, ofreciendo incentivos como descuentos en servicios premium.</p><p></p></td><td valign="top"><p>Marketing de Contenidos: Crear contenido útil y relevante sobre primeros auxilios para mascotas para atraer a propietarios preocupados por la salud de sus mascotas.</p><p>SEO: Optimizar el contenido de la aplicación para mejorar su visibilidad en los motores de búsqueda para términos relacionados con primeros auxilios para mascotas.</p><p></p></td><td valign="top"><p>Publicidad en Redes Sociales: Utilizar anuncios en redes sociales para llegar a una audiencia interesada en actividades al aire libre y viajes con mascotas.</p><p>Marketing de Influencers: Colaborar con influencers que compartan contenido relacionado con el estilo de vida activo y el cuidado de mascotas.</p><p></p></td><td valign="top"><p>SEO: Optimizar el sitio web y el contenido de la aplicación para mejorar su visibilidad en los motores de búsqueda para términos relacionados con servicios veterinarios en línea.</p><p>Publicidad en Redes Sociales: Utilizar anuncios en redes sociales para llegar a propietarios de mascotas interesados en acceder a servicios veterinarios en línea.</p><p></p></td></tr>
<tr><td rowspan="3" valign="top">PERFIL DEL PRODUCTO</td><td valign="top">Productos & Servicios</td><td valign="top"><p><b>Productos:</b></p><p>Plataforma web de PetPal: Una interfaz en línea que permite a los usuarios crear perfiles personalizados para sus mascotas.</p><p><b>Servicios:</b></p><p>Seguimiento de salud y bienestar: Herramientas integradas que permiten a los usuarios registrar información vital sobre sus mascotas, como dieta, vacunas y citas veterinarias.</p><p>Recursos educativos: Acceso a una variedad de recursos educativos, incluyendo artículos, videos y consejos de expertos en cuidado de mascotas.</p><p>Asistencia y soporte en línea: Servicios adicionales como asesoramiento veterinario y la posibilidad de conectarse con profesionales de la salud animal para obtener orientación y ayuda en situaciones de emergencia.</p><p></p></td><td valign="top"><p><b>Productos:</b></p><p>Kit de Primeros Auxilios para Perros: Estos kits contienen suministros esenciales para tratar heridas, raspaduras, picaduras de insectos y otros problemas de salud menores en tus mascotas. Algunos elementos comunes incluyen vendajes, tijeras, termómetros digitales y productos antihistamínicos</p><p><b>Servicios:</b></p><p>Educación en Primeros Auxilios: Proporciona información sobre cómo actuar en situaciones de emergencia con mascotas.</p><p>Aplicación de Primeros Auxilios para Mascotas: Ofrece instrucciones rápidas y efectivas para el cuidado de perros y gatos.</p><p></p></td><td valign="top"><p><b>Productos:</b></p><p>Alimentos para Mascotas: Ofrece una variedad de alimentos y suplementos vitamínicos para perros y gatos.</p><p>Juguetes y Accesorios: Desde ruedas de ejercicio hasta alfombras olfativas, Go Pets tiene opciones para mantener a tus mascotas entretenidas y activas.</p><p><b>Servicios:</b></p><p>Localización de Clínicas Veterinarias: Destaca esta característica única en tu marketing.</p><p>Recordatorios de Citas Médicas: Facilita el seguimiento de las necesidades de las mascotas</p><p></p></td><td valign="top"><p><b>Productos:</b></p><p>Aplicación Móvil Vet+O: Conecta a los dueños de mascotas con médicos veterinarios a través de videollamadas en cualquier momento del día.</p><p><b>Servicios:</b></p><p>Asesoría Veterinaria en Línea 24/7: Resuelve dudas y preocupaciones de manera inmediata.</p><p>Comodidad y Seguridad: Evita desplazamientos y largas esperas en clínicas.</p><p>Registro de Mascotas: Permite crear perfiles con información médica relevante</p><p></p></td></tr>
<tr><td valign="top">Precios & Costos</td><td valign="top"></td><td valign="top">Aplicación gratuita, además incluyen un plan premium</td><td valign="top">Precio variable en base a eleccion del usuario</td><td valign="top">Precio tratable en las consultas</td></tr>
<tr><td valign="top">Canales de distribución (web/móvil)</td><td valign="top">El canal de distribución de PetPal como una aplicación web ofrece a los usuarios acceso conveniente a través de navegadores web en diversos dispositivos. Permite el registro de cuentas, la creación de perfiles detallados para mascotas, el seguimiento de su salud y bienestar, así como acceso a recursos educativos y servicios de asistencia en línea.</td><td valign="top"><b>Aplicación Móvil:</b> La principal plataforma de distribución para Pet First Aid es a través de su aplicación móvil, disponible en tiendas de aplicaciones como App Store para dispositivos iOS y Google Play Store para dispositivos Android. Los usuarios pueden descargar la aplicación de forma gratuita desde estas tiendas en sus dispositivos móviles.</td><td valign="top"><p><b>Aplicación Móvil:</b> Al igual que Pet First Aid, Go Pets se distribuye principalmente a través de su aplicación móvil, disponible en tiendas de aplicaciones como App Store y Google Play Store. Los usuarios pueden descargar la aplicación de forma gratuita para acceder a sus servicios y funciones.</p><p><b>Sitio Web:</b> Go Pets también puede tener un sitio web donde los usuarios pueden obtener más información sobre la aplicación, registrarse para recibir actualizaciones, acceder a recursos adicionales y posiblemente iniciar sesión en sus cuentas desde un navegador de escritorio.</p></td><td valign="top"><p><b>Aplicación Móvil:</b> Vet+O se distribuye principalmente a través de su aplicación móvil, que los usuarios pueden descargar de manera gratuita desde tiendas de aplicaciones como App Store y Google Play Store. La aplicación permite a los usuarios acceder a servicios veterinarios en línea, programar citas, acceder a información de salud de mascotas y más.</p><p></p></td></tr>
<tr><td rowspan="4" valign="top">ANÁLISIS SWOT</td><td valign="top">Fortalezas</td><td valign="top"><p>Interfaz intuitiva facilita la gestión de perfiles de mascotas y acceso a recursos educativos.</p><p>Herramientas completas para seguimiento y gestión de la salud de las mascotas.</p><p>Ofrece asistencia en línea y servicios de asesoramiento veterinario.</p><p>Amplia variedad de recursos educativos disponibles.</p><p></p></td><td valign="top"><p>Amplia gama de productos para el cuidado de mascotas.</p><p>Buena reputación en el mercado.</p><p>Relaciones establecidas con veterinarios y tiendas de mascotas.</p><p></p></td><td valign="top"><p>Plataforma de aplicaciones móviles fácil de usar.</p><p>Amplia base de usuarios y crecimiento constante.</p><p>Colaboraciones con veterinarios y entrenadores de mascotas.</p><p></p></td><td valign="top"><p>Red de clínicas veterinarias bien establecida.</p><p>Personal altamente capacitado y experimentado.</p><p>Fuerte relación con proveedores de medicamentos y equipos.</p><p></p></td></tr>
<tr><td valign="top">Debilidades </td><td valign="top"><p>Dependencia de la conectividad a Internet.</p><p>Competencia fuerte en el mercado de aplicaciones de cuidado de mascotas.</p></td><td valign="top"><p>Poca visibilidad en línea y falta de presencia en redes sociales.</p><p>Precios relativamente altos en comparación con competidores.</p><p>Limitada disponibilidad en tiendas físicas.</p></td><td valign="top"><p>Limitada disponibilidad en algunos países.</p><p>Necesidad de mejorar la interfaz de usuario y la experiencia.</p><p>Competencia de otras aplicaciones similares.</p></td><td valign="top"><p>Altos costos operativos debido a la infraestructura física.</p><p>Limitada presencia en línea y falta de marketing digital.</p><p>Competencia de otras clínicas veterinarias.</p></td></tr>
<tr><td valign="top">Oportunidades</td><td valign="top"><p>Crecimiento del mercado de cuidado de mascotas.</p><p>Potencial para expandir los servicios ofrecidos.</p><p></p></td><td valign="top"><p>Creciente conciencia sobre la salud de las mascotas.</p><p>Expansión a mercados internacionales.</p><p>Desarrollo de nuevos productos innovadores.</p><p></p></td><td valign="top"><p>Expansión a nuevos mercados geográficos.</p><p>Integración con dispositivos inteligentes para mascotas.</p><p>Ofrecer servicios premium para suscriptores.</p><p></p></td><td valign="top"><p>Expansión a servicios de telemedicina para mascotas.</p><p>Programas de fidelidad para clientes.</p><p>Educación continua para el personal veterinario.</p><p></p></td></tr>
<tr><td valign="top">Amenazas</td><td valign="top"><p>Cambios rápidos en la tecnología que pueden requerir actualizaciones frecuentes.</p><p>Posibles cambios en regulaciones y cumplimiento que podrían impactar las operaciones.</p><p></p></td><td valign="top"><p>Competencia intensa de otras marcas de cuidado de mascotas.</p><p>Cambios en las regulaciones de la industria.</p><p>Fluctuaciones económicas que afectan el gasto en mascotas.</p><p></p></td><td valign="top"><p>Cambios en las preferencias de los usuarios hacia aplicaciones rivales.</p><p>Problemas de seguridad de datos.</p><p>Regulaciones gubernamentales sobre privacidad de datos.</p><p></p></td><td valign="top"><p>Cambios en las preferencias de los dueños de mascotas hacia servicios en línea.</p><p>Escasez de personal veterinario calificado.</p><p>Fluctuaciones económicas que afectan la demanda de servicios veterinarios.</p></td></tr>
</table>

2\.1.2. Estrategias y tácticas frente a competidores

Gracias al análisis exhaustivo de la competencia realizado previamente, pudimos identificar con precisión las fortalezas, debilidades, oportunidades y amenazas más relevantes de nuestros competidores. Este conocimiento es esencial para desarrollar estrategias y tácticas efectivas que nos permitan superar a la competencia una vez que nuestro servicio se lance al mercado de manera rentable. A continuación, se presentarán una serie de estrategias y tácticas delineadas para alcanzar este objetivo.

**Afrontando las fortalezas de nuestros competidores:**

**Comprendemos que nuestras fortalezas son:**

- Interfaz intuitiva y completa para el seguimiento de la salud de las mascotas.
- Servicios de asistencia en línea y recursos educativos variados.

**Estrategias:**

- Diferenciación: Resaltar la facilidad de uso y la amplitud de nuestros servicios en comparación con los competidores.
- Marketing centrado en la experiencia del usuario: Destacar la conveniencia y la utilidad de nuestros recursos educativos y servicios de asistencia en línea.

**Tácticas:**

- Campañas de marketing digital que resalten la accesibilidad y la utilidad de nuestra plataforma.
- Creación de contenido educativo relevante y de alta calidad para atraer y retener a los usuarios.

**Afrontando las debilidades de nuestros competidores:**

**Comprendemos que nuestras debilidades son:**

- Dependencia de la conectividad a Internet.
- Competencia fuerte en el mercado de aplicaciones de cuidado de mascotas.

**Estrategias:**

- Mejora de la accesibilidad: Buscar formas de optimizar la aplicación para funcionar mejor en condiciones de conectividad limitada.
- Diferenciación a través de la innovación: Introducir características únicas y útiles que nuestros competidores no ofrecen.

**Tácticas:**

- Desarrollo de una versión offline de la aplicación para usuarios con conectividad limitada.
- Investigación y desarrollo continuo para identificar nuevas características y funcionalidades que diferencien a PetPal de sus competidores.

**Afrontando las oportunidades de nuestros competidores:**

**Comprendemos que nuestras oportunidades son:**

- Crecimiento del mercado de cuidado de mascotas.
- Potencial para expandir los servicios ofrecidos.

**Estrategias:**

- Expansión del mercado: Identificar y llegar a nuevos segmentos de usuarios interesados en el cuidado de mascotas.
- Diversificación de servicios: Explorar nuevas áreas de servicio, como la venta de productos relacionados con mascotas o la colaboración con veterinarios locales.

**Tácticas:**

- Desarrollo de campañas de marketing dirigidas a nuevos segmentos de usuarios, como propietarios de mascotas mayores o dueños de mascotas exóticas.
- Investigación de mercado para identificar las necesidades y demandas de los usuarios que podrían llevar a la expansión de servicios.

**Afrontando las amenazas de nuestros competidores:**

**Comprendemos que nuestras amenazas son:**

- Cambios rápidos en la tecnología.
- Posibles cambios en regulaciones y cumplimiento.

**Estrategias:**

- Adaptación continua: Mantenernos ágiles y estar preparados para ajustar nuestra estrategia en respuesta a cambios tecnológicos y regulatorios.
- Cumplimiento y transparencia: Asegurar que nuestras operaciones cumplan con todas las regulaciones relevantes y mantener una comunicación abierta y transparente con nuestros usuarios.

**Tácticas:**

- Estar al tanto de las últimas tendencias tecnológicas y adaptar nuestra plataforma en consecuencia.
- Mantener una estrecha colaboración con expertos legales y reguladores para garantizar el cumplimiento normativo en todo momento.

2\.2. Entrevistas.

Esta sección se centra en el procedimiento de identificar nuestros grupos demográficos clave a través de la recopilación de datos obtenidos mediante entrevistas en profundidad. Durante este proceso, buscamos comprender a fondo las necesidades, preferencias y comportamientos de nuestros clientes potenciales para poder ofrecer productos y servicios que satisfagan sus demandas de manera efectiva.

2\.2.1. Diseño de entrevistas

- **Preguntas principales:**
  - ¿Con qué frecuencia buscas información sobre el cuidado de tus mascotas?
  - ¿Qué tipo de mascotas tienes en tu hogar?
  - ¿Qué aspectos del cuidado de tus mascotas consideras más importantes?
  - ¿Cómo gestionas actualmente las citas veterinarias de tus mascotas?
  - ¿Qué te gustaría poder registrar sobre la dieta de tus mascotas para mejorar su salud?
  - ¿Qué dificultades encuentras al organizar la información relacionada con el cuidado de tus mascotas?
  - ¿Cómo te gustaría que una aplicación te ayudara a seguir la dieta de tus mascotas?
  - ¿Qué tan importante es para ti el acceso rápido a consejos de cuidado de mascotas?
  - ¿Qué funcionalidades esperarías de una aplicación de cuidado de mascotas?
  - ¿Qué te motiva a utilizar una aplicación para el cuidado de mascotas en lugar de métodos tradicionales?
  - ¿Qué características específicas de una mascota consideras importante registrar en una aplicación?
  - ¿Cuál es tu mayor preocupación en términos de salud para tus mascotas?
  - ¿Te gustaría recibir recordatorios para citas veterinarias y otros eventos importantes relacionados con tus mascotas?
  - ¿Qué tipo de información sobre la salud de tus mascotas te gustaría poder compartir con tu veterinario?
  - ¿Qué nivel de personalización esperarías en un perfil de mascota dentro de una aplicación?
  - ¿Qué te parece más conveniente, poder acceder a la aplicación desde tu dispositivo móvil o desde una computadora?
  - ¿Cómo prefieres recibir notificaciones sobre el estado de salud y recordatorios de tus mascotas?
  - ¿Considerarías compartir información sobre el cuidado de tus mascotas con otros usuarios de la aplicación?
  - ¿Qué medidas de seguridad esperarías que una aplicación de cuidado de mascotas implemente para proteger la información de tus mascotas?
  - ¿Cuál sería el factor decisivo para elegir una aplicación de cuidado de mascotas sobre otra?

2\.2.2. Registro de entrevistas

|**Entevistado 1**|** Renzo Castañeda|
| :- | :- |
|**Edad**|**20**|
|**Distrito**|** San Juan de Lurigancho|
|** |<p>** Durante la entrevista, se obtuvieron respuestas que destacan varios aspectos importantes relacionados con el cuidado de mascotas, específicamente de un perro de raza coque spanier. La frecuencia de búsqueda de información sobre el cuidado de mascotas es baja, centrada principalmente en cuestiones de salud. La gestión de citas veterinarias se realiza de forma virtual, preferiblemente a través de correo electrónico o WhatsApp. Se identificaron preocupaciones específicas sobre el cuidado del pelaje y las orejas del perro, así como el deseo de registrar su dieta para abordar problemas de sobrepeso.</p><p>El entrevistado expresó dificultades para organizar la información relacionada con el cuidado de sus mascotas de forma manual y desearían un sistema automático con consejos integrados. Se destacó la importancia del acceso rápido a consejos de cuidado de mascotas y se expresó el deseo de recibir ayuda veterinaria en línea en momentos de emergencia.</p><p>La decisión de utilizar una aplicación de cuidado de mascotas sobre otra se basaría en un interfaz simple y atractivo, fácil acceso y comprensión. Los usuarios prefieren acceder a la aplicación principalmente desde dispositivos móviles, aunque la disponibilidad en ambas plataformas (móvil y de escritorio) es ideal. Las notificaciones simples son preferidas para comunicar el estado de salud y recordatorios, y se considera compartir información sobre el cuidado de mascotas con otros usuarios si se ofrece un foro comunitario</p>|
|Duración: 16 minutos|` `**URL:<https://youtu.be/5cA7uI0_67A>**|

|**Entevistado 2**|** Marycielo Zeballos|
| :- | :- |
|**Edad**|**28 años**|
|**Distrito**|San Martín De Porres|
|** |<p>** Durante la entrevista, Marycielo nos contó sobre sus gatitos y perros que tiene, de los cuales sus perros son alérgicos a ciertos alimentos y sus gatitos tienen algunas enfermedades. Nos cuenta que la información sobre la salud de las mascotas es desactualizada y no siempre lo que encuentra es verdad porque en otra página o red social puede leer o ver algo distinto.</p><p>El entrevistado comentó que le gustaría poder tener más organizado la información de cada una de las mascotas que tiene ya que ella los considera uno más en su familia.</p><p>El nivel de seguridad sobre la información de sus mascotas no le preocupa mucho, con poner un patrón, números o una contraseña ya se sentiría segura de que nadie pueda acceder. Además que prefiere tener la app para dispositivo móvil debido a que es lo que usa en su día a día ya que muy pocas veces usa la computadora.</p><p>Le gustaría poder ver y compartir su información con otros usuarios ya que nos cuenta que una vez una persona desconocida le brindó una información muy buena que mejoró la salud de sus mascotas, y a ella le gustaría si tiene la oportunidad también ayudar a compartir información.</p>|
|Duración: 14 minutos|` `**URL:<https://youtu.be/iny8H5ssbwE>** |

|**Entevistado 3**|** Antonella Jauliz|
| :- | :- |
|**Edad**|**24 años**|
|**Distrito**|Breña|
|** |<p>Durante el video  Antonella nos comenta que cuenta con una gata de edad avanzada, para la cual consulta constantemente información en internet sobre su cuidado. También nos menciona que el aspecto más importante en los cuidados de su mascota es su salud y es importante poder llevar una dieta balanceada con sus mascotas. </p><p>La entrevistada comentó que le gustaría poder organizar mejor la información de su mascota y que a la vez le sería de utilidad conseguir opiniones confiables para el cuidado de sus mascotas. Menciona también que sería muy útil no solo registrar las comidas de su mascota, sino los nutrientes que contienen estas. Le parece que el poder compartir información es importante, ya que puede ser útil para alguien más, y de la misma manera le interesa poder leer opiniones de otras personas.</p>|
|Duración: 7 minutos|**URL:<https://www.youtube.com/watch?v=wWsmLXuN4GI>** |

|**Entevistado 4**|** David Palti|
| :- | :- |
|**Edad**|**21 años**|
|**Distrito**|San Juan de Miraflores|
|** |Durante la entrevista David nos comenta que cuenta con un perro de mascota. Para él es importante poder acceder a información acerca del cuidado de sus mascotas sobre todo para informarse en cuanto a la correcta alimentación y qué hacer en caso su mascota tenga alergias o alguna indicación médica. Además, nos cuenta que él agenda citas al veterinario una vez al mes y que lo gestiona mediante el canal de Whatsapp de su veterinaria. Comenta que para él es muy importante que su mascota se encuentre bien tanto física como mentalmente. Le parece importante poder registrar los medicamentos que debe administrarle y qué alimentos debe proporcionarle a su mascota en caso se encuentre en tratamiento. Nos cuenta que le gustaría poder recibir consejos sobre su cuidado de manera rápida y sencilla para tenerlos a mano en caso los necesite, y que le gustaría poder contar con una aplicación que sea accesible desde su celular para que sea accesible poder visitarla las veces que él lo desee. Por último, nos comenta que espera que una aplicación de cuidado de mascotas brinde buena calidad y buena atención al cliente para poder decidir utilizarla frente a la competencia. |
|Duración: 4 minutos|**URL:<https://youtu.be/OQK9fKMuDSE?si=Vyf3VKDv9LMOgNlz>** |

|**Entevistado 5**|** Piero Alesandro|
| :- | :- |
|**Edad**|**20 años**|
|**Distrito**|Chorrillos|
|** |En esta entrevista, un propietario de mascotas comparte su experiencia y necesidades en el cuidado de sus compañeros animales. Con perros y gatos en su hogar, busca constantemente información sobre cómo garantizar su bienestar, especialmente en aspectos como la alimentación, el ejercicio y las citas veterinarias. Destaca la importancia de poder registrar detalladamente la dieta de sus mascotas para mejorar su salud, aunque reconoce las dificultades para organizar toda esta información. Expresa su deseo de que una aplicación pueda proporcionarle recomendaciones personalizadas y recordatorios útiles. La conveniencia y la capacidad de mantener registros precisos son motivadores clave para su uso de aplicaciones de cuidado de mascotas. Prioriza la inclusión de detalles como historiales médicos, alergias y comportamientos específicos en los perfiles de mascotas dentro de la aplicación. Su mayor preocupación radica en detectar problemas de salud a tiempo y proporcionar la atención necesaria. Espera recibir recordatorios para citas veterinarias y compartir información detallada con su veterinario, siempre que se garantice la privacidad de los datos. La seguridad de la información es crucial, y busca medidas robustas de protección en cualquier aplicación que elija. En última instancia, la facilidad de uso, las funcionalidades ofrecidas y la seguridad de los datos son los factores decisivos para su elección de una aplicación de cuidado de mascotas sobre otra.|
|Duración: 4 minutos|**URL:**|

2\.2.3. Análisis de entrevistas.

**Analisis del segmento de propietarios con mascotas:**

Las entrevistas proporcionan una visión general de las necesidades y preferencias de los propietarios de mascotas en cuanto al cuidado de sus animales. Aquí hay un análisis general de los temas comunes encontrados en las entrevistas:

1. **Preocupación por la salud y el bienestar de las mascotas**: Todos los entrevistados expresan una gran preocupación por la salud y el bienestar de sus mascotas. Esto incluye aspectos como la dieta adecuada, el cuidado del pelaje, las alergias y la gestión de citas veterinarias.
2. **Búsqueda de información y asesoramiento**: Los propietarios buscan activamente información sobre el cuidado de sus mascotas, especialmente en línea. Sin embargo, la confiabilidad de la información encontrada puede ser una preocupación, ya que se menciona que a veces es difícil discernir la veracidad de la información.
3. **Organización de la información**: Todos los entrevistados expresan la necesidad de tener una manera más organizada de mantener la información relacionada con sus mascotas. Esto incluye detalles sobre la salud, la dieta y los medicamentos administrados.
4. **Acceso a consejos y ayuda rápida**: Existe una clara preferencia por recibir consejos y ayuda rápida sobre el cuidado de las mascotas, especialmente en momentos de emergencia. La disponibilidad de una aplicación que brinde información y asistencia instantánea es valorada positivamente.
5. **Facilidad de uso y accesibilidad**: La mayoría de los entrevistados prefieren una aplicación móvil que sea fácil de usar y accesible desde sus dispositivos cotidianos. La conveniencia de acceder a la información en cualquier momento es fundamental.
6. **Compartir información**: Existe interés en la posibilidad de compartir información y experiencias con otros propietarios de mascotas. Esto se ve como una forma de obtener consejos útiles y contribuir al bienestar de otras mascotas.
7. **Seguridad y privacidad de los datos**: La seguridad y la privacidad de la información personal y de las mascotas son preocupaciones importantes. Los propietarios desean asegurarse de que sus datos estén protegidos al utilizar una aplicación de cuidado de mascotas.

Las entrevistas revelan una serie de necesidades comunes entre los propietarios de mascotas, incluida la búsqueda de información confiable y el deseo de una herramienta digital que facilite el cuidado y la organización de la información relacionada con sus animales. Una aplicación de cuidado de mascotas que sea fácil de usar, brinde asesoramiento rápido y confiable, y garantice la seguridad de los datos sería altamente valorada por este grupo demográfico.

2\.3. Needfinding.

  2\.3.1. User Personas.
- **User Persona de un dueño con mascotas**

<p align="center">
  <img src="images/userpersona.png" width="100%">
</p>
  
  2\.3.2. User Task Matrix.

|Personas dueñas de mascotas|||
| :-: | :- | :- |
|Task|Frequency|Importance|
|Buscar información sobre cuidado de mascotas|Sometimes|Medium|
|Organizar información sobre las mascotas|Never|Medium|
|Registrar la dieta de las mascotas|Always|High|
|Gestionar citas veterinarias|Always|High|
|Recibir consejos y asistencia rápida|Always|High|
|Compartir información y experiencias|Sometimes|Medium|
|Monitorear la salud de las mascotas|Always|High|
|Controlar el ejercicio de las mascotas|Always|High|
|Administrar medicamentos y tratamientos|Always|High|
|Mantener registros de vacunación y desparasitación|Always|Medium|
|Evaluar y corregir problemas de comportamiento|Sometimes|Medium|
|Mantener limpio el entorno de las mascotas|Sometimes|High|
|Proporcionar entretenimiento y enriquecimiento|Sometimes|High|
|Establecer rutinas y horarios|Never|High|
|Supervisar el desarrollo físico y mental|Always|High|

Las tareas que tienen mayor frecuencia son aquellas que realizan los dueños de mascotas, ya que deben estar constantemente atentos al cuidado y bienestar de sus compañeros animales. Tienen que buscar información, organizar registros, gestionar citas veterinarias y proporcionar atención y cuidados diarios para garantizar que sus mascotas estén saludables y felices. Además, deben estar atentos a cualquier cambio en el comportamiento o la salud de sus mascotas y tomar medidas correctivas según sea necesario. Por otro lado, hay tareas que realizan con menos frecuencia, como evaluar y corregir problemas de comportamiento o realizar cambios en la dieta y el régimen de ejercicio de las mascotas para mejorar su calidad de vida a largo plazo.

  2\.3.3. User Journey Mapping.

En esta sección, se presenta el recorrido completo de extremo a extremo de la aplicación para el cuidado de mascotas para los segmentos objetivos de los dueños de mascotas. El mapeo del viaje del usuario comienza desde el momento en que el cliente se familiariza con la aplicación, pasando por el proceso de decisión de utilizarla, registrarse, hacer uso de sus funciones y, finalmente, la posibilidad de dejar de utilizarla.

**Personas dueñas de mascotas:**  

<p align="center">
  <img src="images/userjour.png" width="100%">
</p>

  2\.3.4. Empathy Mapping.


**Personas dueñas de mascotas:**

<p align="center">
  <img src="images/empathymaping.png" width="100%">
</p>
  
  2\.3.5. As-is Scenario Mapping.

<p align="center">
  <img src="images/as-is.png" width="100%">
</p>

# **Capitulo III: Requirements Specification**

3\.1. To-Be Scenario Mapping.

**3.2. User Stories.**

|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de aceptación**|**Relacionado con (Epic ID)**|
| :- | :- | :- | :- | :- |
|**EP01**|Autenticación de usuario|<p>**Como** usuario</p><p>**Quiero** registrarme e iniciar sesión</p><p>**Para** acceder a la aplicación PetPal</p>|Epic|EP01|
|**EP02**|Gestión de cuentas|<p>**Como** usuario</p><p>**Quiero** administrar y personalizar mi cuenta</p><p>**Para** poder realizar cambios en mi cuenta</p>|Epic|EP02|
|**EP03**|Perfil de mascotas|<p>**Como** usuario</p><p>**Quiero** crear un perfil para cada una de mis mascotas</p><p>**Para** poder mantener un registro detallado</p>|Epic|EP03|
|**EP04**|Seguimiento de datos|<p>**Como** usuario</p><p>**Quiero** registrar y seguir la dieta de mis mascotas</p><p>**Para** asegurarme de que están recibiendo la nutrición adecuada</p>|Epic|EP04|
|**EP05**|Gestión de citas veterinarias|<p>**Como** usuario</p><p>**Quiero** programar citas veterinarias</p><p>**Para** garantizar su bienestar y salud</p>|Epic|EP05|
|**EP06**|Acceso a consejos|<p>**Como** usuario</p><p>**Quiero** acceder a una sección de consejos</p><p>**Para** mejorar el cuidado de mis mascotas</p>|Epic|EP06|
|**EP07**|Personalización de perfiles|<p>**Como** usuario</p><p>**Quiero** personalizar el perfil de mis mascotas</p><p>**Para** tener un registro completo de cada mascota</p>|Epic|EP07|
|**EP08**|Gestión de medicamentos|<p>**Como** usuario</p><p>**Quiero** registrar y administrar tratamientos para mis mascotas</p><p>**Para** garantizar que reciban el cuidado necesario de su salud en caso de enfermedad</p>|Epic|EP08|
|**EP09**|Contacto|<p>**Como** visitante del landing page</p><p>**Quiero** contar con una sección que me permita contactar con los desarrolladores de la aplicación</p><p>**Para** resolver algún problema o dar mi opinión sobre la aplicación** </p>|Epic|EP09|
|**EP10**|Optimización de la experiencia del usuario|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una presentación atractiva</p><p>**Para** conocer los servicios y características que ofrece TripMate</p>|Epic|EP10|
|**US01**|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en PetPal</p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p>**Escenario 1: Registro exitoso**</p><p></p><p>**Dado que** el usuario es nuevo</p><p>**Cuando** acceda a la página de registro</p><p>**Y** complete todos los campos requeridos</p><p>**Entonces** debería recibir una confirmación de registro</p><p> </p><p>**Escenario 2: Registro fallido**</p><p></p><p>**Dado que** el usuario completó el formulario de registro</p><p>**Cuando** ingrese información inválida o incompleta</p><p>**Entonces** debería recibir un mensaje de error que indiquen los campos a corregir</p>|EP01|
|**US02**|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p>**Escenario 1: Inicio de sesión exitoso**</p><p></p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese su correo electrónico y contraseña</p><p>**Entonces** debería poder acceder a mi cuenta</p><p>** </p><p>**Escenario 2: Inicio de sesión fallido**</p><p>** </p><p>**Dado que** el usuario se ha registrado</p><p>**Cuando** ingrese una credencial incorrecta</p><p>**Entonces** debería recibir un mensaje de error</p>|EP01|
|**US03**|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p>**Escenario 1: Solicitud de recuperación de contraseña exitosa**</p><p>** </p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** acceda a la opción de recuperar contraseña</p><p>**Y** coloca el correo asociado a su cuenta</p><p>**Entonces** recibirá un correo electrónico con instrucciones para recuperar su contraseña</p><p>** </p><p>**Escenario 2: Solicitud de recuperación de contraseña fallida**</p><p>** </p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** accede a la opción de recuperar contraseña</p><p>**Y** coloca un correo no asociado a su cuenta</p><p>**Entonces** mostrará un mensaje de error</p><p>Y deberá ingresar su correo nuevamente</p>|EP01|
|**US04**|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p>**Escenario 1: Acceder a la configuración de la cuenta**</p><p>** </p><p>**Dado que** el usuario está registrado y ha iniciado sesión en la aplicación</p><p>**Cuando** acceda a la configuración de su cuenta desde el menú de perfil</p><p>**Entonces** podrá encontrar una opción para cambiar su dirección de correo electrónico</p><p>** </p><p>**Escenario 2: Verificación de la nueva dirección de correo electrónico**</p><p>** </p><p>**Dado que** el usuario ha ingresado una nueva dirección de correo electrónico en la configuración de su cuenta</p><p>**Cuando** guarde los cambios y la aplicación solicite verificar la nueva dirección</p><p>**Entonces** recibirá un correo electrónico de verificación en la nueva dirección </p><p>**Y** seguirá un proceso para confirmar el cambio</p>|EP01|
|**US05**|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p>|<p>**Escenario 1: Eliminar cuenta**</p><p>** </p><p>**Dado que** el usuario ha decidido eliminar su cuenta de PetPal</p><p>**Cuando** acceda a la configuración de su cuenta y seleccione la opción para eliminarla</p><p>**Entonces** recibirá una** confirmación </p><p>**Y**,** después de confirmar, su cuenta y todos los datos asociados serán eliminados permanentemente</p><p></p><p>**Escenario 2:** Cancelar eliminación de cuenta</p><p></p><p>**Dado que** el usuario va a eliminar su cuenta</p><p>**Cuando** se muestre la confirmación de cancelar su cuenta</p><p>**Y** cancele la confirmación</p><p>**Entonces** la cuenta del usuario no se eliminará</p>|EP02|
|**US06**|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p>**Escenario 1: Suscripción exitosa**</p><p>** </p><p>**Dado que** el usuario está interesado en obtener beneficios adicionales en la aplicación</p><p>**Cuando** acceda a la sección de membresía premium</p><p>**Y** seleccione el plan premium</p><p>**Entonces** podrá completar el proceso de suscripción</p><p>** </p><p>**Escenario 2: Error durante la suscripción**</p><p>** </p><p>**Dado que** el usuario está interesado en obtener beneficios adicionales en la** aplicación</p><p>**Cuando** intente suscribirse a la membresía premium</p><p>**Y** durante el proceso ingrese un método de pago incorrecto o haya un problema con el servicio de pago</p><p>**Entonces** recibirá un mensaje de error indicando la naturaleza del problema</p>|EP02|
|**US07**|Visualización de perfil de mascota|<p>**Como** usuario</p><p>**Quiero** poder ver el perfil completo de cada una de mis mascotas</p><p>**Para** acceder a su información detallada y necesidades individuales</p>|<p>**Escenario 1: Acceso al perfil**</p><p></p><p>**Dado que** el usuario está en la página principal</p><p>**Cuando** haga clic en el perfil de la mascota</p><p>**Entonces** podrá ver información detallada de su mascota</p><p></p><p>**Escenario 2: Ver información adicional**</p><p></p><p>**Dado que** el usuario está en el perfil de su mascota</p><p>**Cuando** desplace hacia abajo el perfil</p><p>**Entonces** podrá ver información adicional como recordatorio de citas veterinarias, medicinas, notas, etc.</p>|EP03|
|**US08**|Edición del perfil de mascota|<p>**Como** usuario</p><p>**Quiero** poder editar la información de mi mascota en su perfil</p><p>**Para** mantenerla actualizada</p>|<p>**Escenario 1: Edición del perfil exitosa**</p><p></p><p>**Dado que** el usuario está en el perfil de su mascota</p><p>**Cuando** seleccione el botón para modificar algún campo de información</p><p>**Entonces** podrá editar la información de su mascota </p><p>**Y** podrá guardar los cambios registrados.</p><p></p><p>**Escenario 2: Error durante edición**</p><p></p><p>**Dado que** el usuario está editando el perfil de su mascota</p><p>**Cuando** intente guardar los cambios sin completar un campo obligatorio</p><p>**Entonces** recibirá un mensaje de error</p>|EP03|
|**US09**|Eliminación del perfil de mascota|<p>**Como** usuario</p><p>**Quiero** quiero poder eliminar un perfil de mascota</p><p>**Para** actualizar mis perfiles si es necesario</p>|<p>**Escenario 1: Petición para eliminar perfil**</p><p></p><p>**Dado que** el usuario está visualizando los perfiles de sus mascotas</p><p>**Cuando** seleccione un perfil</p><p>**Y** seleccione la opción “Eliminar Perfil”</p><p>**Entonces** recibirá una confirmación de eliminación antes de completar la acción</p><p></p><p>**Escenario 2: Eliminación exitosa**</p><p></p><p>**Dado que** el usuario ha confirmado la eliminación de un perfil</p><p>**Cuando** se complete la acción</p><p>**Entonces** el perfil de mascota será eliminado de manera permanente</p>|EP03|
|**US10**|Registro de dieta diaria|<p>**Como** usuario</p><p>**Quiero** poder registrar la dieta diaria de mis mascotas</p><p>**Para** asegurarme que reciben la nutrición adecuada</p>|<p>**Escenario 1: Registro de alimentos**</p><p></p><p>**Dado que** el usuario está en la sección de alimentación</p><p>**Cuando** ingrese los detalles de la comida consumida por la mascota</p><p>**Entonces** se registrará correctamente en el sistema</p><p></p><p>**Escenario 2: Exceso de alimentos**</p><p></p><p>**Dado que** el usuario está registrando la dieta de su mascota</p><p>**Cuando** intente registrar una cantidad de comida que exceda los límites</p><p>**Entonces** recibirá una advertencia indicando que la cantidad de comida es excesiva</p>|EP04|
|**US11**|Seguimiento de peso|<p>**Como** usuario</p><p>**Quiero** registrar el peso de mis mascotas</p><p>**Para** monitorizar su salud y bienestar</p>|<p>**Escenario 1: Registro exitoso**</p><p></p><p>**Dado que** el usuario está en la sección de seguimiento de su mascota</p><p>**Cuando** ingrese los detalles del peso actual de su mascota</p><p>**Entonces** se mostrará para su visualización y seguimiento</p><p></p><p>**Escenario 2: Advertencia de peso**</p><p></p><p>**Dado que** el usuario ingresa datos en el peso de su mascota** </p><p>**Cuando** los datos ingresados muestran un cambio significativo</p><p>**Entonces** recibirá una alerta para que esté al tanto del peso de su mascota</p>|EP04|
|**US12**|Recordatorios de alimentación|<p>**Como** usuario</p><p>**Quiero** establecer recordatorios para las comidas de mis mascotas</p><p>**Para** asegurarme que sigan una rutina de alimentación regular</p>|<p>**Escenario 1: Configurar recordatorio**</p><p></p><p>**Dado que** el usuario está en la sección de alimentación</p><p>**Cuando** establezca un recordatorio en una hora específica del día</p><p>**Entonces** el sistema generará una notificación para recordar al usuario la hora de alimentar a su mascota</p><p></p><p>**Escenario 2: Desactivar recordatorio**</p><p></p><p>**Dado que** el usuario ha configurado un recordatorio</p><p>**Cuando** decida desactivar o eliminar el recordatorio</p><p>**Entonces** la notificación se eliminará del sistema</p>|EP04|
|**US13**|Programación de cita veterinaria|<p>**Como** usuario</p><p>**Quiero** programar una cita veterinaria para mi mascota</p><p>**Para** garantizar su salud y bienestar</p>|<p>**Escenario 1: Programación de cita**</p><p></p><p>**Dado que** el usuario está en la página de programación de citas</p><p>**Cuando** seleccione la opción para agregar nueva cita</p><p>**Entonces** podrá ingresar los detalles de la cita como fecha, hora, motivo, etc.</p><p></p><p>**Escenario 2: Notificación de cita**</p><p></p><p>**Dado que** el usuario ha programado una cita veterinaria</p><p>**Cuando** la fecha de esta cita llegue</p><p>**Entonces** el sistema notificará al usuario para asegurarse que no se pierda la cita</p>|EP05|
|**US14**|Historial de citas veterinarias|<p>**Como** usuario</p><p>**Quiero** ver el historial completo de citas veterinarias de mis mascotas</p><p>**Para** tener un registro de su atención médica</p>|<p>**Escenario 1: Ver historial de citas** </p><p></p><p>**Dado que** el usuario está en la página de historial de citas veterinarias</p><p>**Cuando** seleccione una mascota específica</p><p>**Entonces** podrá ver una lista de todas las citas veterinarias programadas y pasadas</p><p></p><p>**Escenario 2: Ver detalles de citas**</p><p></p><p>**Dado que** el usuario está visualizando la lista de citas veterinarias</p><p>**Cuando** haga clic en una cita específica</p><p>**Entonces** podrá ver detalles adicionales de la cita</p>|EP05|
|**US15**|Cancelación de cita veterinaria|<p>**Como** usuario</p><p>**Quiero** cancelar una cita veterinaria</p><p>**Para** actualizar si es necesario</p>|<p>**Escenario 1: Petición de cancelación**</p><p></p><p>**Dado que** el usuario está visualizando sus citas planificadas</p><p>**Cuando** seleccione una cita programada</p><p>**Entonces** podrá ver una opción para cancelar la cita</p><p></p><p>**Escenario 2:** **Confirmación de cancelación**</p><p></p><p>**Dado que** el usuario ha seleccionado una cita para cancelar</p><p>**Cuando** confirme la cancelación</p><p>**Entonces** la cita se eliminará del sistema</p>|EP05|
|**US16**|Visualización de consejos|<p>**Como** usuario</p><p>**Quiero** acceder a una sección de consejos de cuidado de mascotas</p><p>**Para** mejorar el cuidado de mis mascotas</p>|<p>**Escenario 1: Visualización de consejos**</p><p></p><p>**Dado que** el usuario está en la página principal de la aplicación</p><p>**Cuando** navegue a la sección de consejos </p><p>**Entonces** podrá ver una lista de consejos organizados por categorías</p><p></p><p>**Escenario 2: Selección de consejos**</p><p></p><p>**Dado que** el usuario está visualizando las categorías de consejos</p><p>**Cuando** seleccione una categoría específica</p><p>**Entonces** podrá ver consejos para sus mascotas referentes a esa categoría</p>|EP06|
|**US17**|Búsqueda de consejos específicos|<p>**Como** usuario</p><p>**Quiero** buscar consejos específicos</p><p>**Para** encontrar información más rápidamente</p>|<p>**Escenario 1: Búsqueda de consejos**</p><p></p><p>**Dado que** el usuario se encuentra en la página de consejos</p><p>**Cuando** ingrese una palabra clave en el campo de búsqueda</p><p>**Entonces** podrá ver una lista de consejos relacionados que coincidan con la búsqueda</p><p></p><p>**Escenario 2: Ver detalles sobre consejos**</p><p></p><p>**Dado que** el usuario ha realizado una búsqueda de consejos</p><p>**Cuando** seleccione un resultado específico en la búsqueda</p><p>**Entonces** podrá ver detalles completos y acceder a información detallada sobre el tema buscado</p>|EP06|
|**US18**|Agregar foto de perfil a la mascota|<p>**Como** usuario</p><p>**Quiero** poder agregar una foto al perfil de mi mascota</p><p>**Para** personalizarlo y hacerlo más identificable</p>|<p>**Escenario 1: Carga de imagen**</p><p>** </p><p>**Dado que** el usuario está en el perfil de su mascota</p><p>**Cuando** seleccione la opción para cargar una foto</p><p>**Entonces** podrá seleccionar una imagen de su biblioteca de imágenes</p><p></p><p>**Escenario 2: Aplicar imagen** </p><p></p><p>**Dado que** el usuario ha cargado la imagen al perfil de su mascota</p><p>**Cuando** la imagen se cargue correctamente</p><p>**Entonces** podrá ver la foto asociada al perfil de su mascota</p><p>**Y** confirmar los cambios</p>|EP07|
|**US19**|Agregar descripción de mascota|<p>**Como** usuario</p><p>**Quiero** agregar una descripción de mi mascota</p><p>**Para** registrarla como información relevante de mi mascota</p>|<p>**Escenario 1:** </p><p></p><p>**Dado que**</p><p>**Cuando**</p><p>**Entonces**</p><p></p><p>**Escenario 2:**</p><p></p><p>**Dado que**</p><p>**Cuando**</p><p>**Entonces**</p>||
|**US20**|Registro de tratamientos|<p>**Como** usuario</p><p>**Quiero** registrar los tratamientos administrados a mi mascota</p><p>**Para** garantizar que recibe el cuidado necesario</p>|<p>**Escenario 1: Registro de tratamientos**</p><p></p><p>**Dado que** el usuario está en la página de registro de tratamiento</p><p>**Cuando** ingrese los detalles del tratamiento administrado a su mascota</p><p>**Entonces** se registrará correctamente en el sistema</p><p></p><p>**Escenario 2: Registro incorrecto**</p><p></p><p>**Dado que** el usuario está en la página de registro de tratamiento</p><p>**Cuando** ingrese los detalles del tratamiento administrado a su mascota</p><p>**Y** olvide llenar un campo</p><p>**Entonces** se mostrará un mensaje de error</p><p>**Y** no se creará el registro</p>|EP8|
|**US21**|Recordatorio de medicamentos|<p>**Como** usuario</p><p>**Quiero** recibir recordatorios para la administración de medicamentos</p><p>**Para** asegurarme que mi mascota siga su tratamiento correctamente</p>|<p>**Escenario 1: Crear recordatorio**</p><p></p><p>**Dado que** el usuario se encuentra en la sección de tratamientos</p><p>**Cuando** ingrese los detalles del medicamento y su programación de dosificación</p><p>**Entonces** el sistema generará automáticamente un recordatorio de administración según la frecuencia y el horario establecido</p><p></p><p>**Escenario 2: Recordatorio incorrecto**</p><p></p><p>**Dado que** el usuario se encuentra en la sección de tratamientos</p><p>**Cuando** ingrese los detalles del medicamento</p><p>**Y** olvide llenar un campo</p><p>**Entonces** se mostrará un mensaje de error</p><p>**Y** no se creará el recordatorio</p>|EP8|
|**US22**|Historial médico|<p>**Como** usuario</p><p>**Quiero** ver el historial médico de mi mascota</p><p>**Para** tener un registro detallado de su salud</p>|<p>**Escenario 1: Visualización de historial médico**</p><p></p><p>**Dado que** el usuario está en la página de historial médico</p><p>**Cuando** seleccione la mascota específica</p><p>**Entonces** podrá ver una lista de todos los tratamientos administrados a su mascota</p><p></p><p>**Escenario 2: Ver detalles** </p><p></p><p>**Dado que** el usuario desea ver detalles sobre un tratamiento</p><p>**Cuando** haga clic en el tratamiento deseado</p><p>**Entonces** podrá ver información detallada sobre el tratamiento seleccionado</p>|EP8|
|**US23**|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p>**Escenario 1: Envío de consulta**</p><p>** </p><p>**Dado que** el usuario tiene una pregunta sobre el funcionamiento de la aplicación o desea realizar un reclamo</p><p>**Cuando** acceda a la sección de soporte</p><p>**Y** complete el formulario de contacto</p><p>**Entonces** podrá enviar su consulta al soporte</p><p>** </p><p>**Escenario 2: Respuesta del soporte**</p><p>** </p><p>**Dado que** el usuario ha enviado una consulta al soporte</p><p>**Cuando** reciba una respuesta</p><p>**Entonces** podrá recibir asistencia a su problema</p>|EP09|
|**US24**|Dar feedback|<p>**Como** usuario</p><p>**Quiero** poder proporcionar feedback sobre la aplicación</p><p>**Para** compartir sugerencias o comentarios que ayuden a mejorar la experiencia del usuario</p>|<p>**Escenario 1: Compartir sugerencias**</p><p>** </p><p>**Dado que** el usuario tiene una idea para mejorar la aplicación</p><p>**Cuando** acceda a la sección de contacto</p><p>**Entonces** podrá enviar un correo al equipo de desarrollo para poder mejorar la aplicación</p>|EP09|
|**US25**|Visualizar una landing page atractiva|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una landing page clara y atractiva</p><p>**Para** entender el propósito de la aplicación</p>|<p>**Escenario 01:** Landing page clara y atractiva</p><p></p><p>**Dado que** el visitante ve la landing page con imágenes, videos e información relevante</p><p>**Cuando** complete el proceso de registro y login</p><p>**Entonces** será redirigido a la aplicación web</p><p></p><p>**Escenario 2:** Acceso al landing page, pero no es responsive con cualquier dispositivo</p><p></p><p>**Dado que** el usuario está ingresando al landing page desde otro dispositivo</p><p>**Cuando** revise la información y lo note desordenado y desagradable para la vista</p><p>**Entonces** cierra nuestra landing page y se dedica a seguir navegando por internet</p>|EP10|
|**US26**|Sección “Servicios”|<p>**Como** visitante del landing page</p><p>**Quiero** conocer sobre los servicios que brinda la aplicación</p><p>**Para** informarme sobre su uso</p>|<p>**Escenario 1: Visualización de los features**</p><p>** </p><p>**Dado que** el usuario se encuentra en el landing page </p><p>**Cuando** acceda a la sección “Servicios”</p><p>**Entonces** podrá visualizar los servicios que brinda la aplicación</p>|EP10|
|**US27**|Sección “Recursos”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Recursos”</p><p>**Para** obtener información sobre los recursos que brinda PetPal</p>|<p>**Escenario 1: Acceso a la sección “Recursos”**</p><p>** </p><p>**Dado que** el usuario está explorando el landing page</p><p>**Cuando ac**ceda a la sección “Recursos”</p><p>**Entonces** podrá leer sobre los recursos que brinda la aplicación</p>|EP10|
|**US28**|Sección “Comunidad”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Comunidad”</p><p>**Para** conocer a la comunidad de PetPal</p>|<p>**Escenario 1: Acceso a la sección “Comunidad”**</p><p>** </p><p>**Dado que** el usuario está explorando el landing page</p><p>**Cuando ac**ceda a la sección “Comunidad”</p><p>**Entonces** podrá conocer</p><p>a la comunidad de usuarios de PetPal</p>|EP10|
|**US29**|Sección “Nosotros”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Nosotros”</p><p>**Para** conocer al equipo de PetPal</p>|<p>**Escenario 1: Acceso a la sección “Recursos”**</p><p>** </p><p>**Dado que** el usuario está explorando el landing page</p><p>**Cuando ac**ceda a la sección “Nosotros”</p><p>**Entonces** podrá conocer y leer acerca del equipo de PetPal</p>|EP10|

**Technical User Stories**

|**Technical Story ID**|**Título**|**Descripción**|
| :- | :- | :- |
|**TS01**|**Post User**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar a un nuevo usuario mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p><p></p><p>**Escenario 1:** Añadir usuario nuevo</p><p></p><p>**Dado que** el endpoint “/usuarios” está disponible</p><p>**Cuando** una post request es enviada con los valores del usuario</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se incluye un usuario con un nuevo id y sus valores registrados</p><p></p><p>**Escenario 2:** Añadir usuario ya existente</p><p></p><p>**Dado que** el endpoint “/usuarios” está disponible</p><p>**Cuando** una post request es enviada con los datos del usuario</p><p>**Y** un usuario ya esté registrado con esos datos</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “Un usuario con estos datos ya existe”</p>|
|**TS02**|**Get User**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de un usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p><p></p><p>**Escenario 1:** Obtener usuario</p><p></p><p>**Dado que** el endpoint “/usuarios” está disponible</p><p>**Cuando** una get request es enviada con el identificador del usuario</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se obtiene los datos del usuario</p><p></p><p>**Escenario 2:** Obtener usuario no disponible</p><p></p><p>**Dado** que el endpoint “/usuarios” está disponible</p><p>**Cuando** una get request es enviada con el identificador del usuario</p><p>**Y** el identificador no exista</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “No existe un usuario con este identificador”</p>|
|**TS03**|**Post Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar una nueva mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p><p></p><p>**Escenario 1:** Añadir mascota nueva</p><p></p><p>**Dado que** el endpoint “/mascotas” está disponible</p><p>**Cuando** una post request es enviada con los valores de la mascota</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se incluye una mascota con un nuevo id y sus valores registrados</p><p></p><p>**Escenario 2:** Añadir usuario ya existente</p><p></p><p>**Dado que** el endpoint “/mascotas” está disponible</p><p>**Cuando** una post request es enviada con los datos del usuario</p><p>**Y** una mascota ya esté registrado con esos datos</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “Una mascota con estos datos ya existe”</p><p></p>|
|**TS04**|**Get Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de una mascota mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p><p></p><p>**Escenario 1:** Obtener mascota</p><p></p><p>**Dado que** el endpoint “/mascotas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la mascota</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se obtiene los datos de la mascota</p><p></p><p>**Escenario 2:** Obtener mascota no disponible</p><p></p><p>**Dado** que el endpoint “/mascotas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la mascota</p><p>**Y** el identificador no exista</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “No existe una mascota con este identificador”</p>|
|**TS05**|**Post Food**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar la alimentación de una mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p><p></p><p>**Escenario 1:** Añadir alimento nuevo</p><p></p><p>**Dado que** el endpoint “/comidas” está disponible</p><p>**Cuando** una post request es enviada con los valores de la comida</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se incluye una comida con un nuevo id y sus valores registrados</p><p></p><p>**Escenario 2:** Añadir comida ya existente</p><p></p><p>**Dado que** el endpoint “/comidas” está disponible</p><p>**Cuando** una post request es enviada con los datos de la comida</p><p>**Y** un usuario ya esté registrado con esos datos</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “Una comida con estos datos ya existe”</p><p></p>|
|**TS06**|**Get Food by Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de la alimentación por mascota mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p><p></p><p>**Escenario 1:** Obtener usuario</p><p></p><p>**Dado que** el endpoint “/comidas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la mascota</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se obtiene los datos de la comida de esa mascota</p><p></p><p>**Escenario 2:** Obtener usuario no disponible</p><p></p><p>**Dado** que el endpoint “/comidas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la mascota</p><p>**Y** el identificador no exista</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “No existe comida asociada a este identificador de mascota”</p>|
|**TS07**|**Post Vet Appointment**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar citas al veterinario por mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p><p></p><p>**Escenario 1:** Añadir cita nueva</p><p></p><p>**Dado que** el endpoint “/citas” está disponible</p><p>**Cuando** una post request es enviada con los valores de la cita</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se incluye una cita con un nuevo id y sus valores registrados</p><p></p><p>**Escenario 2:** Añadir cita ya existente</p><p></p><p>**Dado que** el endpoint “/citas” está disponible</p><p>**Cuando** una post request es enviada con los datos de la cita</p><p>**Y** una cita ya esté registrado con esos datos</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “Una cita con estos datos ya existe”</p><p></p>|
|**TS08**|**Get Vet Appointment**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información sobre las citas al veterinario por mascota mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p><p></p><p>**Escenario 1:** Obtener cita</p><p></p><p>**Dado que** el endpoint “/citas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la cita</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se obtiene los datos de la cita</p><p></p><p>**Escenario 2:** Obtener cita no disponible</p><p></p><p>**Dado** que el endpoint “/citas” está disponible</p><p>**Cuando** una get request es enviada con el identificador de la cita</p><p>**Y** el identificador no exista</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “No existe una cita con este identificador”</p>|
|**TS09**|**Get Advice**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de consejos para mascotas mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p><p></p><p>**Escenario 1:** Obtener consejo</p><p></p><p>**Dado que** el endpoint “/consejos” está disponible</p><p>**Cuando** una get request es enviada con el identificador del consejo</p><p>**Entonces** una respuesta es recibida con status 201</p><p>**Y** se obtiene los datos del consejo</p><p></p><p>**Escenario 2:** Obtener consejo no disponible</p><p></p><p>**Dado** que el endpoint “/consejos” está disponible</p><p>**Cuando** una get request es enviada con el identificador del consejo</p><p>**Y** el identificador no exista</p><p>**Entonces** una respuesta es recibida con status 400</p><p>**Y** se mostrará un mensaje que dice “No existe un consejo con este identificador”</p>|

3\.3. Impact Mapping.

3\.4. **Product Backlog**

|**# Orden**|**User Story ID**|**Título**|**Descripción**|**Story Points (1 / 2 / 3 / 5 / 8)**|
| :- | :- | :- | :- | :- |
|1|**US07**|Visualización de perfil de mascota|<p>**Como** usuario</p><p>**Quiero** poder ver el perfil completo de cada una de mis mascotas</p><p>**Para** acceder a su información detallada y necesidades individuales</p>|<p></p><p>3</p>|
|2|**US08**|Edición del perfil de mascota|<p>**Como** usuario</p><p>**Quiero** poder editar la información de mi mascota en su perfil</p><p>**Para** mantenerla actualizada</p>|<p></p><p>3</p>|
|3|**US09**|Eliminación del perfil de mascota|<p>**Como** usuario</p><p>**Quiero** quiero poder eliminar un perfil de mascota</p><p>**Para** actualizar mis perfiles si es necesario</p>|<p></p><p>3</p>|
|4|**US10**|Registro de dieta diaria|<p>**Como** usuario</p><p>**Quiero** poder registrar la dieta diaria de mis mascotas</p><p>**Para** asegurarme que reciben la nutrición adecuada</p>|<p></p><p>8</p>|
|5|**US11**|Seguimiento de peso|<p>**Como** usuario</p><p>**Quiero** registrar el peso de mis mascotas</p><p>**Para** monitorizar su salud y bienestar</p>|<p></p><p>5</p>|
|6|**US12**|Recordatorios de alimentación|<p>**Como** usuario</p><p>**Quiero** establecer recordatorios para las comidas de mis mascotas</p><p>**Para** asegurarme que sigan una rutina de alimentación regular</p>|<p></p><p>5</p>|
|7|**US13**|Programación de cita veterinaria|<p>**Como** usuario</p><p>**Quiero** programar una cita veterinaria para mi mascota</p><p>**Para** garantizar su salud y bienestar</p>|<p></p><p>8</p>|
|8|**US14**|Historial de citas veterinarias|<p>**Como** usuario</p><p>**Quiero** ver el historial completo de citas veterinarias de mis mascotas</p><p>**Para** tener un registro de su atención médica</p>|<p></p><p>5</p>|
|9|**US15**|Cancelación de cita veterinaria|<p>**Como** usuario</p><p>**Quiero** cancelar una cita veterinaria</p><p>**Para** actualizar si es necesario</p>|<p></p><p>5</p>|
|10|**US16**|Visualización de consejos|<p>**Como** usuario</p><p>**Quiero** acceder a una sección de consejos de cuidado de mascotas</p><p>**Para** mejorar el cuidado de mis mascotas</p>|<p></p><p>5</p>|
|11|**US17**|Búsqueda de consejos específicos|<p>**Como** usuario</p><p>**Quiero** buscar consejos específicos</p><p>**Para** encontrar información más rápidamente</p>|<p></p><p>5</p>|
|12|**US18**|Agregar foto de perfil a la mascota|<p>**Como** usuario</p><p>**Quiero** poder agregar una foto al perfil de mi mascota</p><p>**Para** personalizarlo y hacerlo más identificable</p>|<p></p><p>3</p>|
|13|**US19**|Agregar descripción de mascota|<p>**Como** usuario</p><p>**Quiero** agregar una descripción de mi mascota</p><p>**Para** registrarla como información relevante de mi mascota</p>|<p></p><p>3</p>|
|14|**US20**|Registro de tratamientos|<p>**Como** usuario</p><p>**Quiero** registrar los tratamientos administrados a mi mascota</p><p>**Para** garantizar que recibe el cuidado necesario</p>|<p></p><p>8</p>|
|15|**US21**|Recordatorio de medicamentos|<p>**Como** usuario</p><p>**Quiero** recibir recordatorios para la administración de medicamentos</p><p>**Para** asegurarme que mi mascota siga su tratamiento correctamente</p>|<p></p><p>5</p>|
|16|**US22**|Historial médico|<p>**Como** usuario</p><p>**Quiero** ver el historial médico de mi mascota</p><p>**Para** tener un registro detallado de su salud</p>|<p></p><p>5</p>|
|17|**US06**|Suscripción a membresía premium|<p>**Como** usuario</p><p>**Quiero** poder suscribirme a una membresía en la aplicación</p><p>**Para** poder adquirir beneficios adicionales</p>|<p></p><p>1</p>|
|18|**US25**|Visualizar una landing page atractiva|<p>**Como** visitante del landing page</p><p>**Quiero** visualizar una landing page clara y atractiva</p><p>**Para** entender el propósito de la aplicación</p>|<p></p><p>3</p>|
|19|**US26**|Sección “Servicios”|<p>**Como** visitante del landing page</p><p>**Quiero** conocer sobre los servicios que brinda la aplicación</p><p>**Para** informarme sobre su uso</p>|<p></p><p>3</p>|
|20|**US27**|Sección “Recursos”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Recursos”</p><p>**Para** obtener información sobre los recursos que brinda PetPal</p>|<p></p><p>3</p>|
|21|**US28**|Sección “Comunidad”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Comunidad”</p><p>**Para** conocer a la comunidad de PetPal</p>|<p></p><p>3</p>|
|22|**US29**|Sección “Nosotros”|<p>**Como** visitante del landing page</p><p>**Quiero** poder acceder a la sección “Nosotros”</p><p>**Para** conocer al equipo de PetPal</p>|<p></p><p>3</p>|
|23|**US23**|Contactar al soporte|<p>**Como** usuario</p><p>**Quiero** poder contactar al equipo de soporte de la aplicación</p><p>**Para** obtener ayuda con problemas técnicos</p>|<p></p><p>3</p>|
|24|**US01**|Registro de usuario|<p>**Como** usuario nuevo</p><p>**Quiero** poder registrarme en PetPal</p><p>**Para** poder acceder a todas las funcionalidades de la aplicación</p>|<p></p><p>1</p>|
|25|**US02**|Inicio de sesión|<p>**Como** usuario registrado</p><p>**Quiero** poder iniciar sesión en la aplicación</p><p>**Para** acceder a mi cuenta</p>|<p></p><p>1</p>|
|26|**US03**|Recuperación de contraseña|<p>**Como** usuario registrado</p><p>**Quiero** tener la opción de recuperación de contraseña</p><p>**Para** poder acceder a mi cuenta sin problemas</p>|<p></p><p>1</p>|
|27|**US04**|Cambiar dirección de correo electrónico|<p>**Como** usuario</p><p>**Quiero** poder cambiar la dirección de correo electrónico asociada a mi cuenta</p><p>**Para** mantener mi información de contacto actualizada</p>|<p></p><p>1</p>|
|28|**US05**|Eliminar cuenta|<p>**Como** usuario</p><p>**Quiero** tener la opción de eliminar permanentemente mi cuenta y todos los datos asociados</p><p>**Para** borrar la información de mi cuenta de la aplicación</p>|<p></p><p>1</p>|
|29|**TS01**|**Post User**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar a un nuevo usuario mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p>|<p></p><p>3</p>|
|30|**TS02**|**Get User**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de un usuario mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>3</p>|
|31|**TS03**|**Post Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar una nueva mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p>|<p></p><p>5</p>|
|32|**TS04**|**Get Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de una mascota mediante una API</p><p>**Para** mostrarla en la aplicación cuando se solicite</p>|<p></p><p>5</p>|
|33|**TS05**|**Post Food**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar la alimentación de una mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p>|<p></p><p>5</p>|
|34|**TS06**|**Get Food by Pet**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de la alimentación por mascota mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p>|<p></p><p>5</p>|
|35|**TS07**|**Post Vet Appointment**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** registrar citas al veterinario por mascota mediante una API</p><p>**Para** que esté disponible para crear funcionalidades en mi aplicación</p>|<p></p><p>5</p>|
|36|**TS08**|**Get Vet Appointment**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información sobre las citas al veterinario por mascota mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p>|<p></p><p>5</p>|
|37|**TS09**|**Get Advice**|<p>**Como** desarrollador que trabaja en la aplicación de PetPal</p><p>**Quiero** obtener la información de consejos para mascotas mediante una API</p><p>**Para** mostrarla en la aplicación en caso se solicite</p>|<p></p><p>5</p>|



# **Capítulo IV: Product Design**

4\.1. Style Guidelines

4\.1.1. General Style Guidelines.

4\.1.2. Web Style Guidelines

4\.2. Information Architecture

4\.2.1. Organization Systems

4\.2.2. Labeling Systems

4\.2.3. SEO Tags and Meta Tags

4\.2.4. Searching Systems

4\.2.5. Navigation Systems.

4\.3. Landing Page UI Design.

4\.3.1. Landing Page Wireframe.

4\.3.2. Landing Page Mock-up

4\.4. Web Applications UX/UI Design

4\.4.1. Web Applications Wireframes.

4\.4.2. Web Applications Wireflow Diagrams

4\.4.3. Web Applications Mock-ups.

4\.4.4. Web Applications User Flow Diagrams

4\.5. Web Applications Prototyping

4\.6. **Domain-Driven Software Architecture.** 

4\.6.1. Software Architecture Context Diagram.

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/0cdfe015-2cb4-4708-b654-dfba64532c4c)


4\.6.2. Software Architecture Container Diagrams.

Usuarios

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/389f944a-1715-4753-b2bf-3fc392293578)


Administrador

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/47f85cbf-dd8c-4d33-8b61-66d34b1e5b24)



4\.6.3. Software Architecture Components Diagrams.

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/874ae73b-30b7-448e-b083-98f459db87b7)


4\.7.1. Class Diagrams.

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/3a32ef84-b1ff-4d03-8123-8e1d45e20152)


4\.7.2. Class Dictionary.

Class Usuario

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador del usuario|
|nombre|str|Nombre del usuario|
|correoElectronico|str|Correo electrónico del usuario|
|contrasenia|str|Contraseña del usuario|
|fechaRegistro|datetime|Fecha en la que el usuario se registró en la aplicación|

Class Mascota

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador de la mascota|
|nombre|str|Nombre de la mascota|
|especie|str|Especie de la mascota|
|raza|str|Raza de la mascota|
|fechaNacimiento|datetime|Fecha de nacimiento de la mascota|
|dieta|str|Alimento preferido de la mascota|
|vacunas|vacuna|Lista de vacunas de la mascota|
|citasVeterinario|cita|Citas veterinarias de la mascota|

Class Cita

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|motivo|str|Motivo de la cita|
|fecha|datetime|Fecha de la cita|

Class Vacuna

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|tipoVacuna|str|Tipo de vacuna|
|fecha|datetime|Fecha en la que se aplicó la vacuna|

Class Dieta

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|alimento|str|Alimento que consumió la mascota|
|fecha|datetime|Fecha en la que se alimentó a la mascota|

Class HistorialMedico

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|citas|cita|Citas médicas de la mascota|

Class Medicamento

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|nombre|str|Nombre de la vacuna|
|dosis|str|Dosis de la vacuna|
|frecuencia|str|Frecuencia de aplicación de la vacuna|
|duracion|str|Duración total de la aplicación de la vacuna|

Class Tratamiento

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador del tratamiento|
|motivo|str|Motivo del tratamiento|
|medicamentos|medicamento|Medicamentos a aplicar en el tratamiento|
|fechaInicio|datetime|Fecha en la que se inició el tratamiento|
|fechaFin|datetime|Fecha en la que terminó el tratamiento|

Class Consejo

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador del consejo|
|contenido|str|Contenido del consejo|
|fechaPublicacion|datetime|Fecha de publicación del consejo|

Class Notificacion

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|motivo|str|Motivo de la notificación|
|hora|datetime|Hora de activación de la notificación|
|fecha|datetime|Fecha de activación de la notificación|

Class Feedback

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador del feedback|
|idUsuario|int|Identificador del usuario que envió el feedback|
|fechaFeedback|datetime|Fecha en la que se envió el feedback|
|mensaje|str|Mensaje que contiene el feedback|

Class soporteTecnico

|Atributo|Variable|Descripción|
| :-: | :-: | :-: |
|id|int|Identificador del soporte técnico|
|idUsuario|int|Identificador del usuario que contactó al soporte técnico|
|fecha|datetime|Fecha en la que se contactó con el soporte técnico|
|mensaje|str|Mensaje que se envió al soporte técnico|

4\.8. Database Design.

Para el proyecto PetPal, se ha optado por utilizar MySQL como motor de base de datos. Se ha tomado esta decisión debido a que MySQL es una plataforma escalable y cuenta con una interfaz intuitiva y fácil de usar. Además, el equipo tiene experiencia previa con el motor de Microsoft SQL Server, lo que facilita la transición. MySQL permite expandir los recursos utilizados en la base de datos según las necesidades y requisitos del negocio, lo que lo hace una elección adecuada para nuestro proyecto.

4\.8.1. Database Diagram.

![image](https://github.com/PetPalORG/PetPal-Emprendimiento/assets/164519824/c42e5688-690f-47a9-8dbc-0ff49fb1a734)


# **Capítulo V: Product Implementation, Validation & Deployment.** 

5\.1. Software Configuration Management. 

5\.1.1. Software Development Environment Configuration. 

5\.1.2. Source Code Management. 

5\.1.3. Source Code Style Guide & Conventions. 

5\.1.4. Software Deployment Configuration. 

5\.2. Landing Page, Services & Applications Implementation. 

5\.2.1. Sprint 1 

5\.2.1.1. Sprint Planning 1. 

5\.2.1.2. Sprint Backlog 1. 

5\.2.1.3. Development Evidence for Sprint Review. 

5\.2.1.4. Testing Suite Evidence for Sprint Review. 

5\.2.1.5. Execution Evidence for Sprint Review. 

5\.2.1.6. Services Documentation Evidence for Sprint Review. 

5\.2.1.7. Software Deployment Evidence for Sprint Review. 

5\.2.1.8. Team Collaboration Insights during Sprint.

5\.3. Validation Interviews.

5\.3.1. Diseño de Entrevistas.

5\.3.2. Registro de Entrevistas.

5\.3.3. Evaluaciones según heurísticas.

5\.4. Video About-the-Product.

Avance de Conclusiones, Bibliografía y Anexos.
  


