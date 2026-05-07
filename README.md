<div align="center">

<img src="assets/img/upc-logo.png" alt="UPC Logo" width="150"/>

# Universidad Peruana de Ciencias Aplicadas

## Facultad de Ingeniería

## Programa Académico de Ingeniería de Software

**Ciclo:** 2026-10

**Curso:** Desarrollo de aplicaciones Open Source

**NRC:** 11881

**Docente del curso:** Efraín Ricardo Bautista Ubillús


# Informe de Trabajo Final

**Nombre de la Startup:** Dermacare

**Nombre del producto:** Bloomie


## Integrantes

<p align="center">
u202416272 - Asmat Alminco, Martin Alejandro<br>
u202414802 - Contreras Torres, Arturo Valentino<br>
u202414970 - Gallardo Morales, Carla Alejandra<br>
u20241b843 - Mechan Montenegro, Luciana Carolina<br>
u202415551 - Ramirez Ruiz, Nickolas
</p>


*Abril, 2026*

</div>

---

# Registro de Versiones del Informe

<table>
  <tr>
    <th>Versión</th>
    <th>Fecha</th>
    <th>Autor</th>
    <th>Descripción de modificación</th>
  </tr>

  <tr>
    <td><b>Primera Entrega (AV1)</b></td>
    <td>12/04/2026</td>
    <td>
      Asmat Alminco, Martin Alejandro <br>
      <br>
      <p></p>
      Contreras Torres, Arturo Valentino <br>
      <br>
      <p></p>
      Gallardo Morales, Carla Alejandra <br>
      <br>
      <p></p>
      Mechan Montenegro, Luciana Carolina <br>
      <br>
      <p></p>
      Ramirez Ruiz, Nickolas <br>
    </td>
    <td>
    Capítulo I: Introducción <br>
    Capítulo II: Requirements Elicitation & Analysis <br>
    Capítulo III: Requirements Specification <br>
    Capítulo IV: Product Design <br>
    Capítulo V: Product Implementation, Validation & Deployment (5.1. & 5.2. Sprint 1) <br>
    Codificación Landing Page
    </td>
  </tr>


</table>



---

# Project Report Collaboration Insights

El informe del proyecto fue desarrollado de manera colaborativa por el equipo mediante un repositorio de GitHub creado dentro de la organización del equipo. Este repositorio contiene los archivos del informe, imágenes, diagramas, evidencias y el historial de versiones correspondiente a cada entrega.

URL del repositorio (Report): https://github.com/Bloomie-app/Bloomie-Report <br>
URL del repositorio (Backend): https://github.com/Bloomie-app/Bloomie-Backend <br>
URL del repositorio (Frontend): https://github.com/Bloomie-app/Bloomie-Frontend <br>
URL del repositorio (Landing Page): https://github.com/Bloomie-app/Bloomie-Landing-Page <br>

**Primera Entrega (AV1)**

El equipo desarrolló el Project Report de manera colaborativa, asignando diferentes secciones del documento a cada integrante. Cada miembro contribuyó al informe mediante la redacción de contenido, actualización de diagramas, carga de evidencias, corrección de formato y revisión de la versión final antes de cada entrega.

Además, como parte del avance del proyecto, el equipo también trabajó en el desarrollo de la landing page de Bloomie. Esta actividad fue documentada dentro del informe y alojada en su repositorio correspondiente, incluyendo evidencias relacionadas con su implementación, despliegue y relación con la propuesta de valor del producto.

GitHub fue utilizado como la herramienta principal de colaboración, ya que permitió registrar los cambios realizados a través de commits, organizar el trabajo del equipo y mantener evidencia del avance del informe y de la landing page. Asimismo, las capturas de los analíticos de colaboración y del historial de commits permiten comprobar la participación de los miembros del equipo.

La evidencia presentada en esta sección se encuentra alineada con el Registro de Versiones del Informe, debido a que cada entrega incluye actualizaciones que corresponden con los cambios documentados en dicho registro.

<img src="assets/img/Project-Report-Collaboration-Insights/AV1/github-organization-bloomie.png" width="500"/>

---

# Contenido

## Tabla de Contenidos

- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
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
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
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
  - [2.4. Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
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
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

---

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>

  <tr>
    <td><b>Comunica oralmente con efectividad a diferentes rangos de audiencia.</b></td>
    <td>
      <b>Asmat Alminco, Martin Alejandro</b> <br>
      <u>AV1</u> <br>
      Participó en la explicación de User Stories, configuración del entorno de desarrollo, evidencias de desarrollo para Sprint Review, Lean UX Assumptions, diseño de entrevistas y estrategias frente a competidores. Sus aportes permitieron comunicar la validación del problema, la definición funcional del producto y los avances técnicos iniciales del proyecto.
      <br> <br>
      <b>Contreras Torres, Arturo Valentino</b> <br>
      <u>AV1</u> <br>
      Participó en la exposición de Software Architecture Context Diagram, Software Architecture Container Diagrams, estrategias frente a competidores, Big Picture Event Storming, Design-Level Event Storming, Systems Diagrams, Class Diagrams, User Personas, User Task Matrix y Database Design. Su participación permitió comunicar aspectos del dominio del problema, arquitectura, diseño de software y estructura de datos del sistema.
      <br> <br>
      <b>Gallardo Morales, Carla Alejandra</b> <br>
      <u>AV1</u> <br>
      Sustentó User Stories, Lean UX Problem Statements, Lean UX Hypothesis Statements, estrategias frente a competidores, diseño de entrevistas, Impact Mapping, Product Backlog y SEO Tags and Meta Tags. Estas actividades permitieron explicar de forma clara las necesidades del usuario, las hipótesis del producto, la planificación funcional y los elementos de posicionamiento web.
      <br> <br>
      <b>Mechan Montenegro, Luciana Carolina</b> <br>
      <u>AV1</u> <br>
      Participó en la sustentación del Lean UX Canvas, segmentos objetivo, análisis de competidores, análisis competitivo, lenguaje ubicuo, Landing Page Wireframe, Software Architecture Component, Systems Diagrams y Class Diagrams. Durante estas actividades, comunicó ideas relacionadas con la propuesta de valor, el mercado, el diseño visual y la arquitectura del sistema, adecuando su explicación a una audiencia técnica y no técnica.
      <br> <br>
      <b>Ramirez Ruiz, Nickolas</b> <br>
      <u>AV1</u> <br>
      Sustentó Startup Profile, descripción de la startup, User Journey Mapping, Empathy Mapping, Landing Page Mock-up, General Style Guidelines, Web Style Guidelines, Sprint Planning 1, Aspect Leaders and Collaborators, Sprint Backlog 1 y estrategias frente a competidores. Sus aportes permitieron comunicar la identidad del proyecto, la experiencia del usuario, la línea visual del producto y la organización del primer sprint.
    </td>
    <td>
    <u>AV1</u> <br>
    Como equipo, durante el AV1 se fortaleció la comunicación oral mediante la sustentación de avances relacionados con investigación de usuarios, análisis competitivo, definición del producto, diseño visual, arquitectura, requerimientos y planificación inicial. La presentación permitió mejorar la claridad del mensaje, el uso de recursos visuales y la capacidad para justificar decisiones tomadas durante el desarrollo del proyecto.
    </td>
  </tr>

  <tr>
    <td><b>Comunica por escrito con efectividad a diferentes rangos de audiencia.</b></td>
    <td>
    <b>Asmat Alminco, Martin Alejandro</b> <br>
      <u>AV1</u> <br>
      Elaboró la documentación de User Stories, Software Development Environment Configuration, Development Evidence for Sprint Review, Lean UX Assumptions, diseño de entrevistas y estrategias frente a competidores. Sus aportes permitieron registrar de forma escrita las funcionalidades, la configuración técnica, las evidencias de desarrollo y la validación inicial del producto.
      <br> <br>
      <b>Contreras Torres, Arturo Valentino</b> <br>
      <u>AV1</u> <br>
      Redactó y organizó Software Architecture Context Diagram, Software Architecture Container Diagrams, estrategias frente a competidores, Big Picture Event Storming, Design-Level Event Storming, Systems Diagrams, Class Diagrams, User Personas, User Task Matrix y Database Design. Estas actividades aportaron a la documentación técnica del dominio, la arquitectura, el modelado del sistema y la base de datos.
      <br> <br>
      <b>Gallardo Morales, Carla Alejandra</b> <br>
      <u>AV1</u> <br>
      Documentó User Stories, Lean UX Problem Statements, Lean UX Hypothesis Statements, estrategias frente a competidores, diseño de entrevistas, Impact Mapping, Product Backlog y SEO Tags and Meta Tags. Su trabajo permitió estructurar por escrito el problema, las hipótesis, los requerimientos, el backlog y los elementos de posicionamiento web.
      <br> <br>
      <b>Mechan Montenegro, Luciana Carolina</b> <br>
      <u>AV1</u> <br>
      Redactó y documentó el Lean UX Canvas, segmentos objetivo, competidores, análisis competitivo, lenguaje ubicuo, Landing Page Wireframe, Software Architecture Component, Systems Diagrams y Class Diagrams. Estas secciones contribuyeron a organizar información sobre el mercado, el dominio del producto, el diseño de interfaz y la arquitectura del sistema.
      <br> <br>
      <b>Ramirez Ruiz, Nickolas</b> <br>
      <u>AV1</u> <br>
      Elaboró Startup Profile, descripción de la startup, User Journey Mapping, Empathy Mapping, Landing Page Mock-up, General Style Guidelines, Web Style Guidelines, Sprint Planning 1, Aspect Leaders and Collaborators, Sprint Backlog 1 y estrategias frente a competidores. Su documentación permitió presentar la identidad de la startup, la experiencia del usuario, la propuesta visual y la planificación del sprint inicial.
    </td>
    <td>
    <u>AV1</u> <br>
    Como equipo, durante el AV1 se desarrolló la comunicación escrita mediante la elaboración del informe técnico, integrando análisis de negocio, investigación de usuarios, requerimientos, diseño visual, arquitectura, base de datos y planificación inicial del desarrollo. La documentación permitió sintetizar ideas, mantener coherencia entre secciones y presentar información comprensible para audiencias técnicas y no técnicas. Asimismo, el uso de tablas, diagramas, mockups, backlog y evidencias contribuyó a mejorar la calidad y claridad del informe.
    </td>
  </tr>
</table>
---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Hoy en día, el cuidado personal ha tomado gran relevancia, lo que ha convertido al mercado del skincare en uno de los más dinámicos y en constante crecimiento. Cada vez más personas, tanto jóvenes como adultos, buscan alternativas que les permitan mantener una piel saludable y cuidar su apariencia. Sin embargo, este creciente interés ha traído consigo la necesidad de soluciones innovadoras que conecten las expectativas de los usuarios con herramientas confiables, accesibles y basadas en información objetiva.

Es en este escenario que nace Dermacare, una startup comprometida en ayudar a las personas a comprender y gestionar su rutina de cuidado de la piel de manera informada y personalizada. Como parte de esta propuesta surge Bloomie, una aplicación web y móvil que integra servicios de Inteligencia Artificial para analizar el estado de la piel a partir de imágenes y generar recomendaciones personalizadas.

Bloomie se posiciona como el núcleo de la solución, brindando una experiencia digital intuitiva que acompaña al usuario en la toma de decisiones relacionadas con su cuidado personal. A través de la combinación de análisis automatizado, seguimiento de la evolución de la piel y acceso a servicios dermatológicos, la plataforma busca convertirse en un aliado confiable en el día a día del usuario.

---

### Misión

Brindamos una guía integral y personalizada para el cuidado de la piel mediante el uso de servicios de inteligencia artificial y análisis de datos dermatológicos. Ofrecemos rutinas adaptadas a cada tipo de piel, recomendaciones de productos ajustadas al presupuesto y objetivos del usuario, así como herramientas digitales accesibles que promueven hábitos de skincare saludables y sostenibles.

---

### Visión

Convertirnos en la plataforma líder de cuidado de la piel a nivel global, reconocida por integrar análisis inteligente y validación profesional como base para generar rutinas personalizadas y efectivas. Nuestro propósito es impactar positivamente en millones de personas, ayudándoles a prevenir y tratar problemas dermatológicos, al mismo tiempo que fortalecemos su confianza y bienestar.

---

### Valores

- **Accesibilidad:**  
  En Dermacare creemos que el cuidado de la piel debe estar al alcance de todos. Nuestra plataforma está diseñada para ser intuitiva y fácil de usar, adaptándose a distintos niveles de conocimiento y presupuestos.

- **Innovación:**  
  Integramos servicios de inteligencia artificial para transformar la experiencia del skincare, ofreciendo recomendaciones basadas en datos y en constante mejora. Apostamos por la tecnología como motor de soluciones modernas y efectivas.

- **Confianza:**  
  La salud de la piel requiere respaldo y seguridad. Por ello, combinamos análisis automatizados con la posibilidad de acceso a profesionales dermatológicos, fortaleciendo la credibilidad de la plataforma.

- **Bienestar:**  
  Más allá de la estética, buscamos mejorar la calidad de vida de nuestros usuarios. Promovemos hábitos de cuidado que fortalecen la salud de la piel y contribuyen a su bienestar integral.

### 1.1.2. Perfiles de integrantes del equipo

### Perfil del Integrante

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/Carla-Gallardo.png" width="650"/>
    </td>
    <td><b>Nombre:</b> Carla Alejandra Gallardo Morales</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414970 </td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Carla Alejandra Gallardo Morales</b>, tengo 19 años. Desde que me incorporé en la Universidad Peruana de Ciencias Aplicadas en el periodo 2024-01, es decir que ahora mismo estoy cursando el quinto ciclo de la carrera de Ing. de Software, he adquirido y desarrollado distintos conocimientos a cerca de la programación, específicamente en el lenguaje C++ y Java, además, de forma autodidacta y extracurricular, he profundizado en el lenguaje Python, lo que ha ampliado mi perspectiva sobre la lógica y resolución de problemas.
      <br/><br/>
        Dentro del equipo, mi contribución se basa en el apoyo continuo del desarrollo del backend y frontend de nuestro aplicativo, asimismo ayudo en la implementación del informe de nuestro proyecto.
    </td>
  </tr>
</table>


<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/arturo-contreras.PNG" alt="Foto de Arturo Contreras" width="650"/>
    </td>
    <td><b>Nombre:</b> Arturo Valentino Contreras Torres</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202414802</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Arturo Valentino Contreras Torres</b>, tengo 19 años y estudio la carrera de Ingeniería de Software en la UPC, actualmente estoy en el 5to ciclo. Me gusta aprender y aplicar tecnologías innovadoras para resolver problemas complejos y desarrollar soluciones eficientes. Me apasiona participar en concursos de programación en donde aprendo más sobre temas como programación competitiva, lenguajes como C++, Python, Java, frameworks como Flutter y habilidades como el trabajo en equipo.
      <br/><br/>
      Dentro del equipo, contribuyo en el desarrollo frontend y backend, asegurándome de aplicar principios de Domain Driven Design, patrones de diseño y buenas prácticas de desarrollo de software. Me considero una persona responsable, creativa y orientada al trabajo en equipo, con un enfoque en la mejora continua frente a nuevos desafíos.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/luciana-mechan.png" alt="Foto de Luciana Mechan" width="550"/>
    </td>
    <td><b>Nombre:</b> Luciana Carolina Mechan Montenegro</td>
  </tr>
  <tr>
    <td><b>Código:</b> u20241b843</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Luciana Carolina Mechan Montenegro</b>, estudiante del quinto ciclo de la carrera de Ingeniería de Software. Cuento con conocimientos en lenguajes de programación como C++, Python y Java, los cuales he aplicado en distintos proyectos académicos orientados a la resolución de problemas y desarrollo de sistemas.
      <br/><br/>
      Dentro del equipo, mi contribución se enfoca tanto en el desarrollo frontend como backend, participando en la implementación de funcionalidades y en la integración de los distintos componentes del sistema. Me caracterizo por ser responsable, proactiva y con una alta capacidad de aprendizaje, además de tener facilidad para el trabajo en equipo y la adaptación a nuevos retos dentro del proyecto.
    </td>
  </tr>
</table>
<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/nickolas-ramirez.png" alt="Foto de Nickolas Ramirez" width="650"/>
    </td>
    <td><b>Nombre:</b> Nickolas Ramirez Ruiz</td>
  </tr>
  <tr>
    <td><b>Código:</b> u202415551</td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Nickolas Ramirez Ruiz</b>, estudiante del quinto ciclo de la carrera de Ingeniería de Software.<br/><br/>
       A lo largo de mi formación académica he adquirido conocimientos en programación, principalmente utilizando el lenguaje Java. Además, durante mis primeros ciclos, tuve la oportunidad de iniciarme en la programación con el lenguaje C++ a través del entorno de desarrollo Visual Studio. Me considero una persona organizada, comprometida y con un enfoque proactivo, siempre buscando cumplir con mis responsabilidades antes del tiempo previsto.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td rowspan="4" align="center">
      <img src="assets/img/martin-asmat.png" alt="Foto de Martin Asmat" width="550"/>
    </td>
    <td><b>Nombre:</b> Martin Alejandro Asmat Alminco </td>
  </tr>
  <tr>
    <td><b>Código:</b> u202416272 </td>
  </tr>
  <tr>
    <td>
      <b>Descripción:</b><br/>
      Soy <b>Martin Alejandro Asmat Alminco</b>, estudiante de quinto ciclo de la carrera de Ingeniería de Software. Cuento con experiencia en lenguajes de programación como Python y C++ para proyectos enfocados en el desarrollo de habilidades computacionales, las cuales apliqué en proyectos académicos enfocados en solucionar un problema a través de procesos de documentación de Ingeniería de software.
      <br/><br/>
        Dentro del equipo, cumplo el rol de un full stack al realizar actividades de documentación y programación a un nivel medio. Considero que soy una persona responsable y adaptable a distintas situaciones con buen time-management.  
    </td>
  </tr>
</table>

## 1.2. Solution Profile
### Descripción de la Solución

Nuestra solución consiste en una aplicación web y móvil denominada Bloomie, diseñada para asistir a personas interesadas en el cuidado de la piel mediante un sistema de análisis inteligente y personalizado. La aplicación permite que los usuarios registren un perfil personal y suban fotografías de su rostro, las cuales son procesadas a través de servicios de Inteligencia Artificial para identificar características relevantes de la piel, como presencia de acné, manchas, arrugas o textura desigual.

A partir de este análisis, Bloomie genera recomendaciones personalizadas de productos y hábitos de skincare, adaptadas a las necesidades específicas de cada usuario. A diferencia de otras soluciones basadas únicamente en cuestionarios, la plataforma combina el análisis automatizado con la posibilidad de acceso a servicios dermatológicos, brindando una experiencia más confiable y completa.

Asimismo, la aplicación permite realizar un seguimiento de la evolución de la piel a lo largo del tiempo, facilitando la comparación de resultados y la mejora continua de las rutinas recomendadas. Adicionalmente, integra funcionalidades como la visualización de productos disponibles en el mercado y la localización de puntos de compra cercanos.

El modelo de negocio de Bloomie se basa en un esquema de suscripción escalonado, en el cual los usuarios pueden acceder a distintos niveles de personalización, seguimiento y soporte según el plan contratado. Este enfoque permite ofrecer una solución accesible para distintos perfiles de usuario, al mismo tiempo que garantiza la sostenibilidad del servicio.

Como parte de la evolución del producto, se contempla la integración futura de dispositivos IoT orientados al monitoreo de condiciones de la piel, lo que permitirá complementar el análisis y mejorar la precisión de las recomendaciones, sin que ello represente una dependencia en la versión actual del sistema.
 confu
Para el sistema de análisis inteligente, se considerará el uso de Inteligencia Artificial (IA) para aplicación de algoritmos que logren Aprendizaje automático para aprender comportamiento o patrones con previo criterio programado. Dicho criterio constará de estudios sobre el cuidado de la piel para luego poder realizar comparaciones y diferenciar tipos de piel. Para ello, nos apoyaremos de la subdisciplina de IA: Visión de Computadora para que esta pueda interpretar información significativa a través de imágenes o videos.

### 1.2.1. Antecedentes y problemática

El interés por el cuidado de la piel ha incrementado de manera significativa en jóvenes y adultos que buscan prevenir o tratar afecciones cutáneas comunes. Según el Fortune Business Insight (2024), el mercado de skincare fue valorado en 115.6 mil millones de dólares y se estima que crezca a 194 mil millones en el año 2032. Sin embargo, dicha relevancia adquirida generó una sobreoferta de productos y desinformación sobre el cuidado de piel. Diariamente, los usuarios se enfrentan a cientos de marcas, auspiciadores y catálogos de cosméticos extenuantes, lo que genera confusión en la correcta adquisición de dichos productos y dificulta la elección de una rutina apta para el usuario.

En adición, existe una brecha en la atención dermatológica para los ciudadanos. Esto se debe las largas colas de espera por aseguradoras, como EsSalud, que se estima un tiempo de espera entre un par de semanas hasta 5 meses (INFOBAE, 2024). 

##### Metodología 5W+2H
   
###### What (Qué)   
Cantidades exorbitantes de desinformación sobre el skincare y su correcto uso, lo que genera que las personas realicen rutinas y utilicen productos que no son apropiados para su tipo de piel. Ello implica pérdidas de dinero y causar efectos adversos en la piel.

###### When (Cuándo)
Cuando el usuario desea continuar o empezar una rutina de skincare, comprar productos o buscar información en línea. 

Luego, nuestra aplicación será utilizada cuando nuestro usuario decida investigar o evaluar el tipo de rutina que necesita, que necesita la búsqueda de productos por geolocalización así como también desee consultar con un profesional de forma rápida y segura.

###### Where (Dónde)
Se encuentra a nivel nacional peruano por desinformación en redes de fácil accesibilidad así como también personas que recurren a algún tipo de seguro, que son más del 90% de los peruanos (INEI, 2024).

Nuestra aplicación puede ser utilizada en contextos cotidianos por parte de los usuarios, como el hogar o el trabajo, donde puedan dedicar un tiempo a la visualización de la rutina y notificaciones en el transcurso del día con respecto a su tratamiento. 

###### Who (Quién)
La aplicación será utilizada por cualquier persona que esté interesada en el cuidado de la piel y busquen prevenir o tratar afecciones cutáneas, pero no tiene acceso fácil a un dermatólogo.

###### Why (Por qué)
El problema surge porque los usuarios tienden a seguir recomendaciones no aprobadas por un profesional por ahorro de costos o desconfianza. Luego, existe el caso donde no son capaces de poder directamente acceder a un tratamiento profesional por factores económicos, demográficos, etc. 

###### How (Cómo)

La razón por la cual el problema no se encuentra en su estado óptimo, es porque no hay una regulación clara con penalizaciones severas por compartir información errónea. También, las personas tienden a intentar solucionar sus problemas independientemente antes de consultar con un profesional, ya que, según el INEI (2025), solo 1 de cada 3 cuidadanos acude a atención médica pese a presentar algún malestar. 
Luego, existe que mucha de la información que pese a que provenga de un  estudio científico, no es garantizado el satisfacer las necesidades particulares de cada tipo de piel. 

Con nuestra propuesta, se disminuye los intentos de autocuidado por muchas personas al integrar posibles soluciones personalizables y brindar la posibilidad de conectar con profesionales que cubran con sus necesidades específicas. 

##### How much (Cuánto)

El problema es amplio y afecta a una gran cantidad de personas. En relación con los efectos adversos causados por una mala elección de dermocosméticos, Nayak et al. (2023) realizó una encuesta con 400 participantes y los resultados fueron claros: el 44 % experimentó efectos negativos, de los cuales el 25,5 % correspondió al rostro. Además, el estudio reveló que solo el 15 % de las mujeres consultó a un dermatólogo, mientras que un 22,25 % optó por la automedicación, lo que refleja la ausencia de orientación profesional en la mayoría de casos.

A continucación, el gráfico de la técnica 5W+2H: 

 <div align="center">
      <img src="assets/img/5W+2H.png" alt="5W+2H imagen" width="600"/>
    </div>

### 1.2.2. Lean UX Process



#### 1.2.2.1. Lean UX Problem Statements

 En el dominio de la salud y bienestar enfocado en el cuidado de la piel, los jóvenes adultos de 21 a 30 años, especialmente estudiantes universitarios y jóvenes profesionales familiarizados con aplicaciones móviles, enfrentan múltiples dificultades al momento de cuidar su piel. La sobrecarga de información contradictoria en redes sociales, la falta de personalización en las recomendaciones, y la tendencia a la automedicación, lo cual muchas veces produce un efecto adverso, generan frustración, gastos innecesarios y resultados poco efectivos, además de no contar con herramientas que les permitan hacer un seguimiento real de su progreso.

Asimismo, las soluciones actuales no logran cubrir estas necesidades de manera integral, ya que se basan en métodos genéricos y carecen de análisis más precisos y personalizados. Esto evidencia la oportunidad de ofrecer una solución accesible y confiable que permita a los usuarios tomar decisiones informadas, mejorar continuamente el cuidado de su piel y evitar los riesgos asociados a la desinformación.

¿Cómo podríamos ayudar a los jóvenes adultos a acceder a una experiencia personalizada, confiable y efectiva que optimice el cuidado de su piel y reduzca los efectos secundarios?


#### 1.2.2.2. Lean UX Assumptions

- Assumptions Worksheet:
  - Creemos que nuestros usuarios necesitan identificar correctamente su tipo y estado de piel para poder elegir productos de skincare adecuados, ya que actualmente existe una gran cantidad de información contradictoria y una amplia variedad de productos en el mercado que genera confusión y malas decisiones.
  - Estas necesidades pueden resolverse mediante la aplicación Bloomie, la cual permitirá a los usuarios analizar su piel a través de imágenes utilizando inteligencia artificial, brindando recomendaciones personalizadas de productos y hábitos de cuidado.
  - Nuestros clientes iniciales serán jóvenes adultos interesados en el cuidado de la piel y con acceso a dispositivos tecnológicos, pero no cuentan con el conocimiento suficiente para elegir productos adecuados para su tipo de piel o necesidades.
  - El principal valor que los usuarios esperan de nuestro servicio es contar con una herramienta confiable, práctica, fácil de usar y personalizada que les permita mejorar el estado de su piel sin necesidad de invertir tiempo y dinero en distintos productos o consultas innecesarias.
  - Los usuarios también podrán obtener beneficios adicionales como el seguimiento continuo de la evolución de su piel, la comparación de resultados a lo largo del tiempo y el acceso a orientación profesional mediante consultas con dermatólogos.
  - Planeamos adquirir la mayoría de nuestros usuarios a través de estrategias de marketing digital, principalmente mediante redes sociales, contenido educativo sobre skincare, colaboraciones con creadores de contenido y campañas publicitarias dirigidas a nuestros segmentos objetivos.
  - Generaremos ingresos mediante un modelo de suscripción escalonado (sin planes free), que permitirá a los usuarios acceder a diferentes niveles de personalización, seguimiento y servicios adicionales de Bloomie. Asimismo, se contempla la posibilidad de generar ingresos a través de alianzas con marcas de productos dermatológicos.
  - Nuestra competencia principalmente estará conformada por aplicaciones de skincare que ofrecen recomendaciones genéricas o análisis básicos de la piel, así como contenido no especializado en redes sociales que influye en las decisiones que toman los usuarios.
  - Nos diferenciaremos al ofrecer un enfoque integral basado en inteligencia artificial, análisis de imágenes, seguimiento continuo y la posibilidad de acceso a dermatólogos, lo que permitirá brindar recomendaciones más precisas, confiables y personalizadas.
  - Nuestro mayor riesgo de producto es que los usuarios no confíen inicialmente en el análisis de imágenes para identificar el tipo de piel o no adopten el uso continuo de la aplicación.
  - Planeamos mitigar este riesgo mediante la generación de confianza a través de resultados visibles, validación con especialistas dermatológicos, experiencia de usuario intuitiva y estrategias de educación digital sobre el uso adecuado de la aplicación.

  <b>¿Quién es el usuario?</b><br>
  Se trata de jóvenes adultos entre 21 y 30 años, incluyendo estudiantes universitarios y jóvenes profesionales, que muestran interés en el cuidado de la piel y consumen contenido relacionado con skincare en redes sociales.
  Estos usuarios cuentan con acceso a dispositivos móviles y están familiarizados con el uso de aplicaciones digitales. Sin embargo, enfrentan dificultades para elegir productos adecuados debido a la gran cantidad de información contradictoria que existe en internet.
  Además, suelen experimentar problemas como acné, manchas o sensibilidad en la piel, que los motiva a buscar soluciones efectivas. Esta situación los lleva a invertir en productos que muchas veces no generan los resultados esperados, provocando frustración y desconfianza en los usuarios. También consideramos a dermatólogos certificados que interactúan con la aplicación para validar diagnósticos y atender consultas virtuales de manera más eficiente.
  <br>

   <b>¿Dónde encaja nuestro producto en su trabajo o vida?</b><br>
   Para los jóvenes adultos, Bloomie se integra como parte de su rutina diaria de cuidado personal, permitiéndoles analizar el estado de su piel, recibir recomendaciones personalizadas y realizar seguimiento continuo de su evolución. <br>
   La aplicación acompaña al usuario en momentos clave, como la elección de productos, la evaluación de resultados y la mejora progresiva de su rutina de skincare. <br>
   Para los dermatólogos, Bloomie encaja como una herramienta de apoyo en su práctica profesional, facilitando el acceso a información previa del paciente, optimizando el tiempo de consulta y permitiendo un seguimiento más estructurado y eficiente. Además, de facilitar la conexión con clientes con problemas en el cuidado de su piel.
  <br>

   <b>¿Qué problemas tiene nuestro producto? ¿Resolver?</b><br>
   Nuestro producto debe resolver la confusión causada por la publicidad engañosa y las recomendaciones contradictorias que existen acerca de productos o rutinas de skincare, evitando que los usuarios realicen gastos innecesarios y efectos adversos. También debe responder a la dificultad de acceso a consultas dermatológicas por sus altos costos y largas esperas. En el caso de los dermatólogos, busca eliminar la dependencia de descripciones subjetivas de los pacientes y ofrecer información, además de facilitar la relación médico - paciente.
  <br>

   <b>¿Cuándo y cómo es usado nuestro producto?</b><br>
   Bloomie será utilizado principalmente en el hogar, de forma diaria o periódica, permitiendo a los usuarios analizar su piel mediante imágenes, revisar recomendaciones personalizadas y registrar su progreso. <br>
   También será utilizado en momentos específicos, como antes de adquirir productos de skincare, donde el usuario podrá consultar sugerencias adecuadas a sus necesidades. <br>
   En el caso de los dermatólogos, la aplicación será utilizada durante consultas virtuales o seguimientos, facilitando el acceso a información previa del paciente y mejorando la toma de decisiones.

  <br>

   <b>¿Qué características son importantes?</b><br>
   La precisión del análisis de imágenes mediante inteligencia artificial es fundamental para garantizar recomendaciones confiables y adaptadas a cada usuario. <br>
   Asimismo, la privacidad y seguridad de los datos personales, especialmente de las imágenes faciales, es un aspecto crítico para generar confianza en el usuario. <br>
   La interfaz debe ser intuitiva y fácil de usar, permitiendo una navegación clara y accesible para distintos niveles de experiencia digital.
  <br>

   <b>¿Cómo debe verse nuestro producto y cómo comportarse?</b><br>
   Bloomie debe presentar un diseño moderno, limpio y profesional, transmitiendo confianza y seguridad desde el primero contacto con el usuario. La interfaz debe ser intuitiva, con una estructura clara, uso de colores suaves y jerarquía visual que facilite la comprensión de la información mostrada, como diagnósticos, recomendaciones y seguimiento. <br>
   En cuanto a su comportamiento, la aplicación debe ser ágil y fluida, con tiempos de respuestas rápidos en el procesamiento de imágenes y navegación. Además, debe actuar de manera proactiva mediante notificaciones inteligentes, recordatorios de rutina y sugerencias personalizadas incentivando la constancia del usuario en el cuidado de su piel.

  <br>

- Business Outcomes:
  - Posicionar a Bloomie como una solución confiable en el cuidad de la piel mediante uso de inteligencia artificial y análisis personalizado
  - Generar ingresos a través de un modelo de suscripción escalonado, reflejado en el aumento progresivo de usuarios de los diferentes planes que existen en Bloomie
  - Reducir la incertidumbre y el gasto innecesario en productos de skincare no adecuados, mejorando la satisfacción del usuario con los resultados obtenidos
  - Establecer alianzas con dermatólogos certificados, ampliando el alcance del servicio y fortaleciendo la propuesta de valor de la plataforma
  - Ser un producto tecnológico con una interfaz sencilla y fácil de entender para el cuidado de la piel de los usuarios
<br>

- User Outcomes:
  - <b>Mayor comprensión del estado de su piel:</b> <br>
  Los usuarios podrán conocer con mayor precisión las características de su piel mediante el análisis de imágenes procesadas por inteligencia artificial, lo que permitirá tomar decisiones mejor informadas.
  - <b>Obtención de recomendaciones personalizadas:</b> <br>
  A partir del análisis de piel realizado, los usuarios recibirán sugerencias adaptadas a necesidades específicas, incluyendo productos y hábitos adecuados para su tipo de piel.
  - <b>Reducción de gastos innecesarios:</b> <br>
  Gracias a la información de Bloomie, los usuarios evitarán invertir en productos ineficaces, optimizando su presupuesto destinado al cuidado personal.
  - <b>Seguimiento continuo de la evolución de la piel:</b> <br>
  Los usuarios podrán registrar y comparar el estado de su piel a lo largo del tiempo, facilitando la evaluación de resultados y la mejora continua de la rutina de skincare.
  - <b>Acceso a orientación profesional:</b> <br>
  Los usuarios podrán fortalecer su rutina de cuidado de la piel mediante la posibilidad de consultar dermatólogos, obteniendo una experiencia más confiable y completa.
<br>

- Features:
  - Registro de usuarios para gestionar su perfil personal y características de la piel
  - Análisis de imágenes del rostro mediante inteligencia artificial para identificar condiciones como acné, manchas o textura irregular
  - Generación de recomendaciones personalizadas de productos y rutinas de skincare
  - Historial de seguimiento con registro de imágenes para comparar la evolución de la piel
  - Visualización de productos disponibles en el mercado relacionados con las recomendaciones generales propuestas por la app
  - Integración con servicios dermatológicos para consultas y seguimiento profesional
  - Notificaciones y sugerencias inteligentes basadas en cambios detectados en la piel
  - Interfaz intuitiva y fácil de usar, adaptada a usuarios con diferentes niveles de experiencia digital
<br>

#### 1.2.2.3. Lean UX Hypothesis Statements

- Hipotesis de negocio: 
  - <b>Creemos que</b> ofrecer recomendaciones personalizadas basadas en análisis de la piel permitirá a los usuarios tomar mejores decisiones sobre productos de skincare. <b>Sabremos que</b> hemos tenido éxito <b>cuando</b> observemos un aumento del 10% en la retención de usuarios mensuales.
  - <b>Creemos que</b> implementar un modelo de suscripción escalonado permitirá atender a usuarios con diferentes necesidades y niveles de compromiso. <b>Sabremos que</b> hemos tenido éxito <b>cuando</b> logremos que al menos el 15% de los usuarios que visitan la plataforma se suscriban a algún plan.
  - <b>Creemos que</b> integrar el acceso a dermatólogos dentro de la plataforma incrementará la confianza en la solución. <b>Sabremos que</b> hemos tenido éxito <b>cuando</b> al menos el 20% de los usuarios premium utilicen funcionalidades relacionadas a consultas o validación profesional.
  <br>

- Hipotesis de usuario: 
  - <b> Creemos que </b> proporcionar recomendaciones personalizadas permitirá a los usuarios elegir productos más adecuados para su tipo de piel,lo que resultará en una reducción de efectos adversos y mejores resultados en su rutina de cuidado. <b> Sabremos que </b> hemos tenido razón <b> cuando </b> al menos el 50% de los usuarios reporten mejoras en su piel o disminución de reacciones negativas.
  
  - <b> Creemos que </b> permitir a los usuarios visualizar el progreso de su piel aumentará su constancia en el cuidado personal, lo que resultará en mejores resultados a largo plazo. <b> Sabremos que </b> hemos tenido éxito <b>cuando </b> al menos el 50% de los usuarios mantengan una rutina constante durante un mes y registren mejoras progresivas.
  
  - <b>Creemos que </b>ofrecer un análisis de piel mediante imágenes ayudará a los usuarios a identificar correctamente su tipo y estado de piel, lo que resultará en decisiones más informadas y efectivas.
  <b>Sabremos que </b> hemos tenido éxito <b> cuando </b> al menos el 60% de los usuarios sigan las recomendaciones generadas y reporten resultados positivos en su cuidado.
  
#### 1.2.2.4. Lean UX Canvas


<div align="center">
  <img src="assets/img/lean-ux-canvas.png" alt="LeanUXCanvas imagen" width="750"/>
</div>

## 1.3. Segmentos objetivo
Bloomie identifica dos segmentos principales de usuarios, definidos a partir del dominio del problema y respaldados por estadísticas del contexto peruano.

#### Segmento 1: Jóvenes adultos de 21 a 30 años interesados en el cuidado de la piel

Este segmento comprende estudiantes universitarios y jóvenes profesionales residentes en zonas urbanas del Perú, con acceso a dispositivos móviles y alta exposición a contenido digital sobre skincare. Se trata de un público con capacidad de gasto en productos de cuidado personal y con hábitos de consumo digital consolidados.
En términos de capacidad económica, según el MTPE (2024), el ingreso laboral promedio mensual del grupo de 25 a 44 años ascendió a S/ 1,847 en el período abril 2023–marzo 2024, siendo el grupo de mayor ingreso promedio por edad. Esto indica que este segmento cuenta con ingresos suficientes para sostener un modelo de suscripción como el propuesto por Bloomie. Respecto al comportamiento digital, el 80% de los usuarios peruanos de redes sociales las utilizan de forma diaria (Statista, 2023), confirmando que el segmento objetivo tiene una presencia digital intensa que facilita tanto la adopción de la aplicación como el consumo de contenido de skincare.
Respecto al mercado de skincare en Perú, según COPECOH–CCL, el consumo promedio per cápita en rutinas de skincare asciende a S/ 828 al año, impulsado por el crecimiento de los dermocosméticos, que han aumentado hasta en 100% en comparación con años anteriores. Además, la categoría de tratamiento facial fue la de mayor crecimiento dentro del sector, registrando un aumento del 32% en 2023, lo que evidencia una demanda activa y creciente en el tipo de orientación que Bloomie busca brindar.

#### Segmento 2: Dermatólogos certificados
Este segmento comprende a médicos dermatólogos colegiados y en ejercicio activo que buscan herramientas digitales para optimizar su práctica clínica, ampliar su alcance a pacientes y ofrecer servicios de teleconsulta o seguimiento remoto. Bloomie les ofrece una plataforma para conectar con usuarios que ya cuentan con un análisis previo de su piel, lo que permite consultas más informadas y eficientes.
En el Perú, la distribución de especialistas dermatólogos es marcadamente desigual: la mayoría se concentra en Lima y en las principales ciudades del país, mientras que en regiones periféricas la oferta es escasa o nula. Esta concentración geográfica limita el acceso de gran parte de la población a atención especializada, generando una demanda insatisfecha que plataformas como Bloomie pueden canalizar digitalmente. Asimismo, el consumo promedio peruano en productos de higiene y cuidado personal entre los 15 y 65 años alcanza USD 225 anuales, con un crecimiento del 3% respecto al período anterior (COPECOH–CCL, 2024), lo que refleja una base de usuarios con disposición real a invertir en su salud dermatológica, representando una oportunidad concreta para que los especialistas amplíen su práctica a través de canales digitales.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores
#### Skin Bliss 
Skin Bliss es una aplicación móvil que utiliza inteligencia artificial para analizar la piel y 
recomendar rutinas personalizadas. Permite a los usuarios crear un perfil de su piel, escanear 
productos para evaluar sus ingredientes y registrar un historial visual de cambios a lo largo del 
tiempo. Su fortaleza radica en la transparencia científica y en la personalización de rutinas 
según las características y necesidades de cada usuario. Sin embargo, sus servicios están 
limitados al ámbito preventivo y estético, ya que no incorpora validación médica profesional ni 
consultas con dermatólogos, lo que reduce la credibilidad clínica de sus recomendaciones. 

#### Miiskin Skin Tracker 
Miiskin está enfocada en el seguimiento visual de la piel, especialmente para controlar lunares 
y cambios en manchas, arrugas o texturas. Fue diseñada para un uso prolongado, permite 
comparar fotos a lo largo del tiempo y está en cumplimiento con estándares como HIPAA, lo 
que refuerza su legitimidad en telemedicina. Su fortaleza radica en el tratamiento médico y 
privacidad, aunque sus servicios se limitan a seguimiento visual sin ofrecer diagnóstico o 
recomendaciones de productos, no ofrece un sistema integral de análisis automatizado orientado a recomendaciones personalizadas de skincare.

#### First Derm 
First Derm es una plataforma de teledermatología donde los usuarios envían casos, incluyendo 
imágenes, para que dermatólogos certificados los evalúen. La app está disponible en iOS, 
Android y web, y ya ha atendido gran cantidad de casos en diferentes países. Su principal 
ventaja es el acceso directo a diagnóstico profesional, pero su enfoque es más médico que 
preventivo o educativo; no incluye análisis automatizado ni rutinas personalizadas, y no integra 
seguimiento visual continuo ni recomendaciones de productos.

### 2.1.1. Análisis competitivo

## Competitive Analysis Landscape
Como se observa en la siguiente tabla se desarrolló un proceso de análisis para determinar 
nuestro FODA frente a competidores. 

<table>
  <tr>
    <th colspan="6" align="left">Competitive Analysis Landscape</th>
  </tr>

  <tr>
    <td><b>¿Por qué llevar a cabo este análisis?</b></td>
    <td colspan="5">
      Conocer a profundidad a los principales competidores en el mercado digital del skincare (Skin Bliss, Miiskin Skin Tracker y First Derm), para identificar sus fortalezas, debilidades, oportunidades y amenazas, y así definir las ventajas competitivas y estrategias de Bloomie.
    </td>
  </tr>
  <tr>
    <th>Perfil</th>
    <th>Aspecto</th>
    <th>Bloomie</th>
    <th>Skin Bliss</th>
    <th>Miski Skin Tracer</th>
    <th>First Derm</th>
  </tr>

  <!-- OVERVIEW -->
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>Plataforma web y móvil que analiza la piel con IA, genera rutinas personalizadas, conecta con dermatólogos y permite seguimiento visual del progreso.</td>
    <td>App que combina escaneo facial con rutinas personalizadas, evaluaciones de ingredientes y seguimiento visual con fotos comparativas.</td>
    <td>App enfocada en el monitoreo de lunares y manchas, con comparativas fotográficas y alertas de cambios.</td>
    <td>Servicio de teledermatología donde dermatólogos certificados atienden casos enviados por usuarios a través de la app.</td>
  </tr>

  <tr>
    <td><b>Ventaja competitiva</b></td>
    <td>Integración en una sola plataforma de análisis automatizado, recomendaciones personalizadas, seguimiento continuo y acceso a dermatólogos.</td>
    <td>Ofrece análisis de piel, gestión de productos, programa de rutina y historial visual con lógica de ingredientes.</td>
    <td>Cumplimiento con estándares médicos (HIPAA), alta confianza en privacidad y seguridad.</td>
    <td>Acceso directo a dermatólogos en múltiples países con diagnóstico en menos de 24h.</td>
  </tr>

  <!-- MARKETING -->
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>Jóvenes y adultos interesados en skincare confiable, accesible y personalizado, así como dermatólogos.</td>
    <td>Usuarios interesados en skincare preventivo y estético.</td>
    <td>Pacientes preocupados por salud dermatológica (lunares, cáncer de piel, manchas).</td>
    <td>Personas con problemas serios en la piel que requieren diagnóstico rápido y seguro.</td>
  </tr>

  <tr>
    <td><b>Estrategias</b></td>
    <td>Marketing digital en redes sociales, alianzas estratégicas y posicionamiento en comunidades de skincare.</td>
    <td>Comunicación centrada en ciencia y seguridad, difusión en redes sociales y app stores.</td>
    <td>Alianzas con hospitales y dermatólogos, marketing en sector salud.</td>
    <td>Estrategias basadas en confianza médica y respaldo de especialistas.</td>
  </tr>

  <!-- PRODUCTO -->
  <tr>
    <td rowspan="4"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>Diagnóstico mediante servicios de IA, rutinas personalizadas, historial visual, acceso a dermatólogos, mapa de farmacias y chatbot.</td>
    <td>Escaneo facial, creación de rutinas, análisis de ingredientes, historial visual y comparativas de productos.</td>
    <td>Seguimiento visual de lunares y manchas, comparaciones fotográficas y recordatorios.</td>
    <td>Consulta médica online, envío de fotos y diagnóstico profesional.</td>
  </tr>

  <tr>
    <td><b>Precios y Costos</b></td>
    <td>Modelo de suscripción escalonado con diferentes niveles de acceso según funcionalidades.</td>
    <td>Modelo freemium con suscripción mensual para funciones avanzadas.</td>
    <td>Freemium con opciones avanzadas de almacenamiento y seguimiento.</td>
    <td>Pago por consulta entre $30–40 por caso.</td>
  </tr>

  <tr>
    <td><b>Canales de distribución</b></td>
    <td>App móvil (iOS y Android), versión web y redes sociales.</td>
    <td>App móvil disponible en iOS y Android.
    </td>
    <td>App móvil (iOS y Android).</td>
    <td>App móvil y web.</td>
  </tr>

  <!-- SWOT -->
  <tr>
    <td><b>Fortalezas</b></td>
    <td>Integralidad diagnóstica, rutinas, validación médica y multiplataforma.</td>
    <td>Rutinas personalizadas, transparencia científica e historial visual.</td>
    <td>Seguridad médica, confianza y respaldo de estándares.</td>
    <td>Respaldo profesional y rapidez en diagnóstico.</td>
  </tr>

  <tr>
    <td rowspan="3"><b>Análisis SWOT</b></td>
    <td><b>Debilidades</b></td>
    <td>Requiere confianza del usuario para compartir fotos y mayor complejidad.</td>
    <td>No integra validación médica ni consultas dermatológicas.</td>
    <td>Sin recomendaciones personalizadas ni rutinas.</td>
    <td>No ofrece seguimiento ni personalización.</td>
  </tr>

  <tr>
    <td><b>Oportunidades</b></td>
    <td>Creciente interés en skincare y adopción de soluciones digitales en salud, junto con alianzas con marcas del sector.</td>
    <td>Integrar consultas médicas para mayor credibilidad.</td>
    <td>Crecimiento del mercado preventivo de skincare.</td>
    <td>Integración con IA y rutinas personalizadas.</td>
  </tr>

  <tr>
    <td><b>Amenazas</b></td>
    <td>Competencia de grandes marcas tecnológicas y desconfianza en datos.</td>
    <td>Apps más completas con diagnóstico clínico.</td>
    <td>Apps más atractivas enfocadas en estética.</td>
    <td>Alta competencia en telemedicina y costos.</td>
  </tr>

</table>

### 2.1.2. Estrategias y tácticas frente a competidores
- <b>Personalización integral con respaldo profesional: </b>
<br> Como estrategia principal, Bloomie se diferencia al integrar en una sola plataforma el análisis automatizado mediante servicios de IA y el acceso a dermatólogos. Esto permite afrontar la debilidad de competidores como Skin Bliss, que se enfocan únicamente en recomendaciones estéticas sin validación profesional. La táctica consiste en posicionar la aplicación como una solución confiable que combina tecnología y respaldo médico, fortaleciendo la confianza del usuario.

- <b>Seguimiento continuo orientado a la experiencia del usuario:</b>
<br> Frente a soluciones como Miiskin, cuyo enfoque principal es el monitoreo visual, Bloomie incorpora seguimiento acompañado de rutinas personalizadas y recordatorios inteligentes. Esta estrategia permite aprovechar la debilidad de la competencia en cuanto a falta de acompañamiento activo, mientras que la táctica se centra en mejorar la adherencia del usuario a su rutina mediante notificaciones y visualización de progreso.

- <b> Modelo de suscripción accesible y escalable: </b>
<br> A diferencia de First Derm, que maneja un modelo de pago por consulta, Bloomie adopta un esquema de suscripción escalonado que permite a los usuarios acceder a distintos niveles de servicio según sus necesidades. Esta estrategia aprovecha la oportunidad de captar un mercado más amplio con diferentes capacidades de pago, mientras que la táctica consiste en ofrecer valor progresivo a través de planes diferenciados.

- <b> Integración de funcionalidades en un solo ecosistema </b>
<br> Mientras que los competidores se enfocan en funcionalidades específicas, Bloomie apuesta por una estrategia de integración que centraliza diagnóstico, recomendaciones, seguimiento y acceso a servicios dermatológicos. La táctica consiste en reducir la fragmentación del proceso de cuidado de la piel, respondiendo a la debilidad de soluciones parciales y posicionando la plataforma como un ecosistema completo.

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

En esta sección se presenta el diseño de las entrevistas dirigidas a los segmentos objetivos con el propósito de recolectar información relevante que permita comprender sus necesidades, comportamientos y problemáticas. Para ello, se formularon las siguientes preguntas divididas en iniciales y principales, permitiendo que se asegure la obtención de datos de nuestros segmentos objetivos.

#### Segmento 1: Jóvenes adultos interesados en skincare
**Preguntas iniciales**
- ¿Qué edad tienes?
- ¿A qué te dedicas actualmente?
- ¿En qué distrito o ciudad resides?
- ¿Qué dispositivo utilizas con mayor frecuencia (celular, laptop, tablet)?

**Preguntas principales**
1. Cuéntame cómo es actualmente tu rutina de cuidado de la piel.
2. ¿Cómo decides qué productos de skincare utilizar?
3. ¿Qué dificultades has tenido al intentar seguir una rutina de cuidado de la piel?
4. ¿Qué haces cuando tienes un problema en la piel o no sabes qué producto usar?
5. ¿Qué tan confiable consideras la información que encuentras en redes sociales o internet sobre skincare? ¿Por qué?
6. ¿Has tenido alguna experiencia negativa al usar productos para tu piel? Cuéntame.
7. ¿Qué te frustra más del proceso de elegir productos o armar una rutina?
8. ¿Qué esperas lograr al cuidar tu piel?

**Preguntas de validación de solución**

9. ¿Cómo te sentirías al usar una aplicación que analice tu piel a partir de fotografías?
10. ¿Qué dudas o preocupaciones tendrías al compartir imágenes o información sobre tu piel en una app?
11. ¿Qué tendría que ofrecerte una aplicación para que confíes en sus recomendaciones?
12. ¿En qué situaciones usarías una aplicación así en tu día a día?
13. ¿Qué tendría que pasar para que sigas usando una aplicación como esta a largo plazo? 

#### Segmento 2: Dermatólogos certificados
**Preguntas iniciales**

- ¿Cuántos años de experiencia tienes como dermatólogo?
- ¿Trabajas de manera independiente o en una institución?
- ¿En qué ciudad o distrito ejerces actualmente?

**Preguntas principales**

1. ¿Cómo es actualmente tu proceso de atención a pacientes desde el diagnóstico hasta el seguimiento?
2. ¿Qué tipo de información del paciente consideras esencial antes de iniciar una consulta?
3. ¿Qué dificultades encuentras al evaluar a un paciente antes de verlo presencialmente?
4. ¿Cómo realizas actualmente el seguimiento de la evolución de tus pacientes?
5. ¿Qué limitaciones has identificado en las herramientas digitales que utilizas hoy en día?
6. ¿Qué problemas observas con mayor frecuencia en pacientes que siguen rutinas de skincare por su cuenta?
7. ¿Cómo percibes el nivel de información o desinformación de los pacientes respecto al cuidado de su piel?

**Preguntas de validación de solución**

8. ¿Qué opinas sobre el uso de inteligencia artificial como apoyo en diagnósticos preliminares?
9. ¿Qué valor tendría para ti contar con un reporte previo automatizado del estado de la piel del paciente?
10. ¿Qué tan útil sería tener acceso a un historial visual estructurado antes de la consulta?
11. ¿Qué barreras o preocupaciones tendrías al utilizar una herramienta digital de este tipo?
12. ¿Qué funcionalidades considerarías indispensables para integrar una solución como esta en tu práctica?
13. ¿En qué casos recomendarías a un paciente el uso de una aplicación como esta?
### 2.2.2. Registro de entrevistas

**PRIMER SEGMENTO OBJETIVO**

<u>Entrevista 1:</u>

Entrevistador: Carla Gallardo Morales

Datos del entrevistado

- **Nombre:** Fiorella  
- **Apellidos:** Gallardo Morales
- **Edad:** 25 años
- **Distrito:** La Molina
- **Timing:** Desde 0:00 minutos a 8:39 minutos
  

<img src="assets/img/entrevista-carla.png" width="500"/>

**Resumen descriptivo:**

Fiorella es una joven de 25 años que está interesada en el cuidado de su piel y por consiguiente, sigue una rutina básica de cuidado de la piel: por la mañana limpia su rostro y aplica protector solar, y por la noche utiliza una crema hidratante. Sin embargo, señala que no reaplica el protector durante el día.
<br>Menciona que uno de sus principales problemas es la dificultad para elegir productos debido a la gran variedad en el mercado. Para tomar decisiones, recurre a reseñas y recomendaciones en redes sociales como TikTok, aunque reconoce que no siempre son confiables, ya que cada piel reacciona de manera diferente. Incluso relata una experiencia negativa reciente con un producto que le causó sequedad.
Aunque ha considerado acudir a un dermatólogo, prefiere informarse por su cuenta. Respecto a aplicaciones de análisis de piel, indica que estaría dispuesta a usarlas por la orientación que brindan, aunque tiene ciertas preocupaciones sobre la privacidad de sus datos.
<br> Finalmente, señala que no confiaría únicamente en una sola plataforma y que continuaría usando una aplicación solo si las recomendaciones resultan efectivas.


<u>Entrevista 2:</u>

Entrevistador:Nickolas Ramirez Ruiz

Datos del entrevistado

- **Nombre:** Yamileth Sherlyn 
- **Apellidos:** Corimaya Cuello 
- **Edad:** 23 Años 
- **Ciudad:** Arequipa
- **Timing:** Desde 8:39 minutos hasta 20:14 minutos

<img src="assets/img/entrevista-nickolas.png" width="500"/>


**Resumen descriptivo:**
Llamileth Corimaya Cuello, una estudiante de Derecho de 23 años residente en Arequipa que se dedica a la asesoría legal y comercial, mantiene una rutina de cuidado de piel minimalista y tecnológica pero enfrenta dificultades con la dosificación y el orden de los productos tras experiencias negativas con especialistas, por lo que desconfía de las redes sociales y la piratería, prefiriendo guiarse por recomendaciones de amigas y mostrando una alta disposición a utilizar una aplicación eficiente que analice su piel mediante fotografías por las noches para obtener fuentes confiables y resultados seguros.

<u>Entrevista 3:</u>

Entrevistador: Luciana Mechan Montenegro

Datos del entrevistado

- **Nombre:** Britny 
- **Apellidos:** Alarcon
- **Edad:** 20
- **Distrito:** San Martín de Porres
- **Timing:** Desde 20:14 minutos hasta 29:03 minutos

<img src="assets/img/entrevista-dermatologos-luciana.png" width="500"/>

**Resumen descriptivo:**

La entrevistada, Britney, tiene 20 años, reside en San Martín de Porres y es estudiante de psicología. Utiliza principalmente el celular como su dispositivo principal y se informa sobre el cuidado de la piel a través de redes sociales, especialmente TikTok, complementándolo con búsquedas en Google. Su comportamiento refleja una alta dependencia de medios digitales y una influencia significativa de tendencias en redes, aunque mantiene una postura crítica respecto a la confiabilidad de esta información.

En cuanto a su rutina de skincare, presenta piel mixta a grasa y problemas como granitos, por lo que selecciona productos en función de estas características. Sin embargo, su proceso se basa en la prueba y error, ya que considera que cada piel reacciona de manera diferente. Su principal dificultad es la falta de constancia debido a su rutina diaria como estudiante, lo que le impide seguir adecuadamente los pasos del cuidado de la piel. Además, ha tenido experiencias negativas con productos que no cumplen lo prometido o generan reacciones adversas, lo que incrementa su frustración al momento de construir una rutina adecuada.

Finalmente, la entrevistada muestra interés en una aplicación que analice su piel y le brinde recomendaciones personalizadas, ya que facilitaría la toma de decisiones y le ofrecería una guía constante. Para confiar en este tipo de solución, considera importante que esté respaldada por dermatólogos y tecnología como inteligencia artificial. Asimismo, valora funcionalidades como recordatorios o notificaciones, que le ayudarían a mantener la constancia, aunque expresa preocupación por la privacidad de sus datos si la información no es manejada de forma personal.

<br>

**SEGUNDO SEGMENTO OBJETIVO**

<u>Entrevista 1:</u>

Entrevistador: Arturo Contreras Torres

Datos del entrevistado

- **Nombre:** Justo
- **Apellidos:** Valverde
- **Edad:** 48 años
- **Distrito:** San Martín de Porres
- **Timing:**  Desde 29:05 minutos hasta 48:30 minutos

<img src="assets/img/entrevista-arturo.png" width="500"/>

**Resumen descriptivo:**

El entrevistado fue Justo Valverde, un médico con 22 años de experiencia, actualmente trabajando en una institución pública de salud. Justo describe que la atención médica sigue un proceso de entrevista clínica, diagnóstico y tratamiento. Señala que las consultas presenciales son más efectivas debido al apoyo de exámenes clínicos, mientras que las virtuales cumplen principalmente un rol informativo, aunque el seguimiento del paciente si puede realizarse de forma remota. <br>
Utiliza una aplicación para gestionar historiales clínicos, la cual, pese a ciertas fallas, ha mejorado su trabajo frente al uso tradicional del papel. Advierte sobre los riesgos de que los pacientes utilicen productos sin información adecuada y valora positivamente la integración de inteligencia artifical como herramienta informativa, siempre complementada por un profesional de la salud. <br>
Considera que nuestro producto, Bloomie, puede agilizar la atención médica al proporcionar información previa del paciente, permitiendo al especialista optimizar el tiempo de consulta y enfocarse en decisiones clínicas más precisas.


<u>Entrevista 2:</u>

Entrevistador: Martin Alejandro Asmat Alminco

Datos del entrevistado

- **Nombre:** Antonio
- **Apellidos:** Paredes 
- **Edad:** 67 años
- **Distrito:** Jesús María
- **Timing:** Desde 48:30 minutos hasta 1:01:16  minutos

<img src="assets/img/entrevista-martin.png" width="500"/>

**Resumen descriptivo:** 

En entrevistado fue Antonio Paredes, un médico con 40 años de experiencia en la especialidad de dermatología, y que actualmente trabaja en una clínica privada ubicada en Jesús María. Él considera relevante para sus consultas un buen diagnóstico, para lo cual evalúa antecedentes, lesiones cutáneas o la automedicación. Sin embargo, considera que existen casos en los cuales se puede complicar el correcto tratamiento de los pacientes al casos completamente variantes, por lo que ve necesario un correcto historial clínico y uso de un sistema brindado por la clínica. Luego, se encuentra parcialmente en desacuerdo con el uso de productos relacionados con el skin care, ya que propone que en su mayoría, estos no contienen la certificación médica para poder ser utilizados de forma libre, lo que complica el tratamiento. 

Después, con respecto a una posible aplicación, menciona que se debe mantener un correcto uso de la información, no desde el lado técnico en software, sino información que en teoría está protegida por la ley y que tiene peso legal, ello por ejemplo incluye el historial clínico. Sin embargo, si ve pertinente la integración de una aplicación en formato puente, donde pueda unir a los dermatólogos y pacientes en un entorno con mayor comunicación para ahorro de tiempo yo costos a comparación del sistema de citas tradicional. 

Finalmente, el doctor está de acuerdo que las herramientas de inteligencia aertificial son beneficiosas para el uso cotidiano y de ser aplicable, para el caso de los dermatólogos especialistas como él. Sin embargo, considera que es pertinente la supervisión de profesionales debido a posibles diagnósticos erróneos generados por patrones, ya que los casos de pacientes se consideran únicos, especialmente por intentos de autocuidado. 


<u>Entrevista 3:</u>

Entrevistador: Luciana Mechan

Datos del entrevistado

- **Nombre:** Andrea 
- **Apellidos:** Rosas
- **Edad:** 45
- **Distrito:** San Isidro
- **Timing:** Desde 1:01:17 minutos hasta 1:06:26 minutos

El entrevistado no autorizo para la grabación de su rostro  

**Resumen descriptivo:**

La entrevistada, Andrea Rosas, es dermatóloga con 30 años de experiencia, trabaja de manera independiente y ejerce en el distrito de San Isidro. Su proceso de atención inicia con la evaluación visual del paciente, seguido del diagnóstico y la prescripción del tratamiento, mientras que el seguimiento depende en gran medida de que el paciente regrese a consulta, lo cual no siempre ocurre. Para realizar un diagnóstico adecuado, considera esencial contar con información previa como historial dermatológico, alergias, medicamentos actuales, rutina de productos y antecedentes familiares; sin embargo, en la práctica suele iniciar desde cero debido a la falta de información previa estructurada por parte del paciente.

En cuanto a las herramientas digitales, la entrevistada señala que el seguimiento es principalmente manual, utilizando fotos tomadas con el celular o enviadas por WhatsApp, lo que evidencia la ausencia de un sistema especializado. Además, menciona que las historias clínicas electrónicas actuales no están adaptadas a las necesidades de la dermatología, ya que no permiten una adecuada gestión ni comparación visual de imágenes. También identifica como un problema frecuente que los pacientes sigan rutinas de skincare basadas en redes sociales, lo que genera daños en la piel y dificulta el diagnóstico, debido a la falta de conocimiento sobre ingredientes y el uso incorrecto de productos.

Finalmente, la dermatóloga muestra una percepción positiva hacia el uso de inteligencia artificial como herramienta de apoyo, siempre que no reemplace el criterio profesional. Considera que un reporte previo automatizado, acompañado de un historial visual estructurado y un resumen de productos utilizados, aportaría un alto valor al proceso de consulta, ya que permitiría ahorrar tiempo y mejorar la precisión del diagnóstico. Asimismo, identifica como principales beneficios el seguimiento de la evolución del paciente y la optimización de consultas, aunque expresa preocupación por la posible mala interpretación de resultados por parte de los usuarios. Indica que recomendaría este tipo de solución especialmente en pacientes con tratamientos prolongados, como el acné, donde el monitoreo constante resulta clave.

**Enlace del video único de las entrevistas:** [*Ver grabación aquí*](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202414802_upc_edu_pe/IQBNkNJeD-G7TZeChphX-tz0AXsuN0Qpx9bOQVOKp_op9rk?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=mt5kc7)

### 2.2.3. Análisis de entrevistas

#### Segmento 1:  Jóvenes adultos interesados en el skin care 

###### Proceso de atención 
100% realiza diagnóstico mediante evaluación clínica (visual + anamnesis)
66.7% incluye exámenes complementarios en casos necesarios
100% considera la consulta presencial como más efectiva
33.3% reconoce que el seguimiento puede hacerse de forma remota

###### Información esencial del paciente
100% considera esencial el historial médico (enfermedades, alergias, medicación)
100% requiere conocer productos/rutinas del paciente
66.7% incluye antecedentes familiares o contexto adicional (ocupación, enfermedades sistémicas)

###### Dificultades antes de la consulta presencial
100% reporta falta de información previa estructurada
100% indica que pacientes llegan con la condición alterada (automedicación/productos)
66.7% menciona problemas por demora en citas o evolución de la lesión

###### Seguimiento de pacientes
100% no cuenta con un sistema de seguimiento completamente estructurado y  dentro de este grupo, solo el 66,7 % cuenta con un sistema por parte de su hospital o clínica.
33.3% realiza seguimiento manual (fotos, mensajería) debido a posibles consultas virtuales.
66.7% depende de consultas presenciales porque consideran que es lo mejor en tratamiento.
33.3% reconoce viabilidad del seguimiento remoto 

###### Limitaciones de herramientas digitales
66.7% considera que las herramientas actuales son básicas o poco adaptadas
66.7% reporta dificultades en manejo/comparación de imágenes
33.3% utiliza sistemas digitales que mejoran frente al papel, pero con limitaciones
66.7% teme mala interpretación por parte del paciente
33.3% menciona riesgos generales asociados al uso de la herramienta

###### Problemas en pacientes con skincare propio
100% observa uso incorrecto de productos por intentos de autocuidado 
100% reporta efectos negativos en la piel (irritación, alteraciones)
66.7% menciona uso excesivo o múltiples productos simultáneos

###### Nivel de información del paciente
100% percibe desinformación generalizada
100% identifica influencia de redes sociales y marketing
66.7% señala falta de criterio o comprensión sobre productos

######  Uso de IA en diagnósticos preliminares
100% considera la IA útil como apoyo
100% coincide en que no reemplaza al profesional

###### Historial visual estructurado
100% lo considera útil o muy útil
66.7% destaca impacto en seguimiento y evaluación clínica

###### Funcionalidades indispensables
100% requiere acceso a información previa del paciente
66.7% considera clave el historial visual comparativo
33.3% valora gestión digital de historiales clínicos

###### Casos de uso recomendados
100% recomienda uso para optimizar consulta médica
66.7% lo enfoca en seguimiento de tratamientos
33.3% lo considera útil como apoyo informativo para pacientes 


#### Segmento 2:  Dermatólogos certificados

###### Rutina de cuidado de la piel
100% sigue alguna rutina de skincare por cuenta propia o tratada. 
33.3% presenta uso incorrecto o incompleto pese a recomendaciones de profesionales. 
33.3% reporta dificultad explícita para mantener constancia.
66.7% presenta problemas implícitos en la piel.

###### Fuentes de información para decisiones
66.7% utiliza redes sociales como fuente principal de casos verídicos y primeras referencias antes de comprar un producto.
33.3% prefiere recomendaciones cercanas de familiares o amigos. 
33.3% complementa con búsquedas en Google para averiguar mayor información. 
66.7% reconoce que la información no es confiable 
33.3% desconfía activamente de redes sociales

###### Proceso de elección de productos
100% presenta dificultad para elegir productos
66.7% basa sus decisiones en prueba y error
66.7% considera que cada piel reacciona diferente
33.3% tiene problemas específicos con el orden o dosificación

###### Problemas con productos de skincare
100% ha tenido experiencias negativas
33.3% reporta resequedad
33.3% reporta irritaciones o reacciones adversas
33.3% menciona malas experiencias con especialistas o recomendaciones.

###### Relación con dermatólogos y expertos
33.3% ha considerado acudir a un dermatólogo
33.3% ha tenido experiencias negativas con especialistas
100% no tiene acompañamiento profesional constante
66.7% prefiere autogestionar su cuidado

###### Nivel de confianza en la información presente en internet
100% muestra desconfianza hacia fuentes actuales
66.7% mantiene una postura crítica pero sigue usándolas
33.3% evita activamente fuentes digitales no confiables

###### Interés en aplicaciones de skincare
100% estaría dispuesto a usar una app de análisis de piel
66.7% busca guía constante en internet sobre los posibles productos para aplicarse. 
33.3% busca fuentes confiables y seguras de farmacias y atención al médico.

###### Expectativas de la solución
100% espera recomendaciones personalizadas sobre rutina y productos. 
33.3% valora recordatorios o notificaciones por parte de la aplicaicón.
33.3% espera análisis mediante fotografías o scanners al sentir mayor seriedad y profesioanlismo. 
33.3% busca precisión en uso (orden/dosificación) de sus productos.

###### Barreras o preocupaciones
66.7% tiene preocupación por privacidad de datos
33.3% no lo menciona explícitamente pero sí exige confiabilidad
33.3% muestra desconfianza general por experiencias previas
33.3% menciona importancia de IA confiable

## 2.3. Needfinding

### 2.3.1. User Personas

En esta sección se presentan los user personas construidos a partir del análisis de las entrevistas realizadas a usuarios y especialistas dermatológicos. Estos artefactos sintetizan patrones de comportamiento, necesidades, motivaciones y frustraciones identificadas durante la investigación, permitiendo representar de manera clara a los segmentos clave de nuestro proyecto.

**PRIMER SEGMENTO OBJETIVO**

<img src="assets/img/user-persona-segmento1.png" width="500"/>

<br>

**SEGUNDO SEGMENTO OBJETIVO**

<img src="assets/img/user-persona-segmento2.png" width="500"/>

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping
En esta sección se detallan los User Journey Maps en su versión "As-Is", uno por cada segmento de usuario definido. El objetivo de estos mapas es ilustrar el proceso de extremo a extremo que realizan actualmente los usuarios para intentar resolver su necesidad, evidenciando los puntos de dolor, las frustraciones y las ineficiencias que experimentan antes de la implementación de nuestra solución propuesta.

A continuación, se presentan los diagramas que resumen la situación actual de los usuarios:
####  2.3.3.1 Segmento 1: Jóvenes adultos
![foto](assets/img/joven.png)
![foto](assets/img/joven2.png)
![foto](assets/img/joven3.png)

#### 2.3.3.2 Segmento 2: Dermatólogos certificados
![foto](assets/img/dermatologos.png)

![foto](assets/img/dermatologos2.png)

![foto](assets/img/dermatologos3.png)

### 2.3.4. Empathy Mapping
En esta sección se presenta el Empathy Mapping elaborado para el segmento de negocio. Esta herramienta nos permite profundizar en el conocimiento de nuestro User Persona, yendo más allá de las características demográficas para comprender sus dolores, necesidades y el entorno que influye en su toma de decisiones.

A continuación, se visualizan los aspectos psicográficos, frustraciones y metas que definen la experiencia del usuario respecto a la problemática identificada:
####  2.3.4.1 Segmento 1: Jóvenes adultos
![foto](assets/img/segmento1.png)

#### 2.3.4.2 Segmento 2: Dermatólogos certificados
![foto](assets/img/segmento2.png)

## 2.4. Big Picture Event Storming

En esta sección se presenta el proceso de Big Picture Event Storming realizado por el equipo, con el propósito de comprender el dominio del negocio de manera general y visualizar sus procesos más relevantes. A través de una sesión colaborativa, se identificaron los principales eventos del dominio, los actores involucrados y sus relaciones, permitiendo obtener una primera visión integral del funcionamiento del sistema. Este modelado de alto nivel ayudó a reconocer flujos clave del negocio, así como posibles problemas, oportunidades y puntos de mejora dentro del contexto del proyecto.

Para realizar el Big Picture Event Storming se utilizaron 3 pasos importantes:

- **Step 1: Generating Domain Events** <br>
  En esta primera etapa se reconocieron los eventos más importantes del dominio del negocio, es decir, aquellos sucesos significativos que reflejan un cambio relevante dentro del sistema. Estos eventos fueron redactados en pasado, ya que representan hechos que ya ocurrieron, y sirvieron como punto de partida para entender el comportamiento general del negocio.

  <div>
    <img src="assets/img/big-picture-event-storming-step1.png" alt="Big picture event storming (step 1)" width="500"/>
  </div> <br>

- **Step 2: Sorting Domain Events (chronologically)** <br>
  Luego, los eventos identificados se organizaron de manera cronológica, con el fin de representar el flujo general de las actividades del negocio. Esta secuencia permitió observar con mayor claridad cómo se conectan los distintos sucesos y cómo evolucionan los procesos dentro del dominio.

  <div>
    <img src="assets/img/big-picture-event-storming-step2.png" alt="Big picture event storming (step 1)" width="500"/>
  </div> <br>

- **Step 3: Adding Actors and External systems** <br>
  Finalmente, se añadieron los actores y sistemas externos que intervienen en los procesos del negocio. Esto permitió identificar quiénes participan en cada interacción y qué elementos externos influyen en el desarrollo de los eventos, brindando así una visión más completa del contexto en el que opera el sistema.

  <div>
    <img src="assets/img/big-picture-event-storming-step3.png" alt="Big picture event storming (step 1)" width="500"/>
  </div> <br>



## 2.5. Ubiquitous Language

En esta sección se define el lenguaje ubicuo del dominio del negocio, el cual permite establecer una comunicación clara, consistente y sin ambigüedades entre todos los stakeholders del proyecto, incluyendo desarrolladores, diseñadores y usuarios del sistema.

El Ubiquitous Language se construye a partir de términos propios del dominio del cuidado de la piel (skincare), la atención dermatológica y la personalización de rutinas, evitando el uso de conceptos técnicos de ingeniería de software.

Este lenguaje debe mantenerse consistente a lo largo de todo el proyecto, incluyendo la definición de requerimientos, User Stories, modelos de dominio y diseño del sistema.

 <u> Glosario de Términos del Dominio </u> 

- **User (Usuario)** <br>
  Persona que utiliza la aplicación para analizar su piel, recibir recomendaciones personalizadas y realizar seguimiento de su rutina de cuidado.

- **Dermatologist (Dermatólogo)** <br>
  Profesional de la salud especializado en el cuidado de la piel que brinda consultas, diagnósticos y recomendaciones a los usuarios dentro de la plataforma.

- **Skin Analysis (Análisis de piel)** <br>
  Proceso mediante el cual se evalúa el estado de la piel del usuario, generalmente a partir de imágenes o información proporcionada, para identificar condiciones y necesidades específicas.

- **Skin Type (Tipo de piel)** <br>
  Clasificación de la piel del usuario (por ejemplo: seca, grasa, mixta o sensible), utilizada como base para personalizar recomendaciones.

- **Skin Condition (Condición de la piel)** <br>
  Estado específico de la piel en un momento determinado, incluyendo problemas como acné, manchas, irritación o deshidratación.

- **Routine (Rutina)** <br>
  Conjunto estructurado de pasos y productos recomendados que el usuario debe seguir para el cuidado de su piel.

- **Routine Step (Paso de rutina)** <br>
  Acción específica dentro de una rutina, como limpieza, hidratación o aplicación de un producto.

- **Routine Tracking (Seguimiento de rutina)** <br>
  Registro del cumplimiento diario de la rutina por parte del usuario, utilizado para medir consistencia y progreso.

- **Adherence (Adherencia)** <br>
  Indicador que refleja qué tan consistentemente el usuario sigue su rutina a lo largo del tiempo.

- **Streak (Racha)** <br>
  Cantidad de días consecutivos en los que el usuario ha cumplido su rutina.

- **Product (Producto)** <br>
  Artículo de cuidado de la piel recomendado al usuario como parte de su rutina, con base en su análisis de piel.

- **Product Compatibility (Compatibilidad del producto)** <br>
  Nivel en el que un producto es adecuado para la piel del usuario según su tipo, condición y rutina actual.

- **Catalog (Catálogo)** <br>
  Conjunto de productos disponibles que el usuario puede explorar dentro de la aplicación.

- **Appointment (Cita)** <br>
  Interacción programada entre el usuario y un dermatólogo para recibir asesoría profesional.

- **Consultation (Consulta)** <br>
  Sesión de atención entre el usuario y el dermatólogo, en la cual se evalúa el estado de la piel y se brindan recomendaciones.

- **Diagnosis (Diagnóstico)** <br>
  Evaluación realizada por el dermatólogo sobre la condición de la piel del usuario, acompañada de recomendaciones.

- **Recommendation (Recomendación)** <br>
  Sugerencia de productos, hábitos o tratamientos basada en el análisis de piel o en la evaluación del dermatólogo.

- **Subscription Plan (Plan de suscripción)** <br>
  Modelo de acceso mediante el cual el usuario obtiene las funcionalidades de la aplicación a cambio de un pago.

- **Availability (Disponibilidad)** <br>
  Horario definido por el dermatólogo en el cual puede atender consultas.

- **Skin Progress (Progreso de la piel)** <br>
  Evolución del estado de la piel del usuario a lo largo del tiempo, basada en el seguimiento y análisis continuo.

# Capítulo III: Requirements Specification

## 3.1. User Stories
En esta sección se presentan los requerimientos del sistema definidos mediante un conjunto de User Stories y Epics, los cuales describen de manera clara y concisa las funcionalidades esperadas desde la perspectiva de los diferentes actores del sistema, tales como el usuario joven adulto, el dermatólogo, el visitante del sitio web y el desarrollador.

Cada User Story representa una necesidad específica del negocio y está orientada a generar valor dentro del contexto del cuidado personalizado de la piel.

Asimismo, cada User Story incluye uno o más criterios de aceptación redactados en tercera persona, en tiempo presente y siguiendo la estructura de Gherkin (Given–When–Then). Estos criterios permiten definir comportamientos verificables del sistema, asegurando que las funcionalidades puedan ser validadas de manera objetiva.

El conjunto de User Stories se encuentra organizado en Epics, los cuales agrupan funcionalidades relacionadas dentro de los distintos contextos del dominio, tales como gestión de usuarios, rutinas, atención dermatológica, experiencia web y servicios REST. Esta organización facilita la comprensión del sistema y su evolución incremental.

Finalmente, se incluyen tanto User Stories funcionales orientadas al usuario final como Technical Stories asociadas a la implementación de servicios RESTful, permitiendo cubrir tanto la perspectiva del negocio como los aspectos necesarios para la construcción del sistema.

<table border="1" cellspacing="0" cellpadding="8">

  <tr>
    <th>Epic / Story ID</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Criterios de Aceptación</th>
    <th>Relacionado con (Epic ID)</th>
  </tr>

  <tr>
    <td><strong>E1</strong></td>
    <td>Onboarding de usuario</td>
    <td>
      Como joven adulto, quiero completar el proceso de registro e inicio para acceder a Bloomie.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US01</strong></td>
    <td>Registro de cuenta</td>
    <td>
      Como joven adulto, quiero registrarme con mis datos personales para crear una cuenta y acceder a Bloomie.
    </td>
    <td>
      <strong>Escenario 1: Registro exitoso</strong><br>
      Dado que el usuario proporciona nombre, apellido, email y contraseña válidos
      Cuando confirma el registro
      Entonces el sistema crea la cuenta
      Y redirige al cuestionario inicial de piel
      <p></p>
      <strong>Escenario 2: Datos inválidos</strong><br>
      Dado que el usuario ingresa datos incompletos o con formato incorrecto
      Cuando intenta registrarse
      Entonces el sistema rechaza la solicitud
      Y muestra el mensaje de error correspondiente
    </td>
    <td>E1(Onboarding de usuario)</td>
  </tr>

  <tr>
    <td><strong>US02</strong></td>
    <td>Completar perfil de piel</td>
    <td>
      Como joven adulto, quiero completar un cuestionario inicial sobre mis condiciones de piel en mi primer ingreso para que la aplicación configure mi perfil correctamente.
    </td>
    <td>
      <strong>Escenario 1: Cuestionario presentado</strong><br>
      Dado que el usuario accede por primera vez tras registrarse
      Cuando el sistema valida su autenticación
      Entonces solicita completar el cuestionario de tipo de piel y sensibilidad
      <p></p>
      <strong>Escenario 2: Perfil completado exitosamente</strong><br>
      Dado que el usuario proporciona su tipo de piel y nivel de sensibilidad
      Cuando confirma el envío
      Entonces el sistema guarda el perfil
      Y redirige al proceso de escaneo facial
    </td>
    <td>E1(Onboarding de usuario)</td>
  </tr>

  <tr>
    <td><strong>E2</strong></td>
    <td>Análisis de piel</td>
    <td>
      Como joven adulto, quiero analizar mi piel mediante escaneo facial para obtener un diagnóstico personalizado.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US03</strong></td>
    <td>Escaneo facial</td>
    <td>
      Como joven adulto, quiero realizar un escaneo facial con la cámara para que la aplicación capture mi piel y obtenga un diagnóstico preciso.
    </td>
    <td>
      <strong>Escenario 1: Escaneo completado</strong><br>
      Dado que el usuario inicia el proceso de escaneo facial
      Cuando el sistema captura correctamente la imagen
      Entonces completa el escaneo
      Y continúa con el procesamiento del análisis
      <p></p>
      <strong>Escenario 2: Escaneo fallido</strong><br>
      Dado que el usuario inicia el proceso de escaneo facial
      Cuando la captura no se completa correctamente
      Entonces el sistema indica que el escaneo no fue exitoso
      Y permite reintentar
    </td>
    <td>E2(Análisis de piel)</td>
  </tr>

  <tr>
    <td><strong>US04</strong></td>
    <td>Diagnóstico preliminar automático</td>
    <td>
      Como joven adulto, quiero recibir un diagnóstico generado por IA después del escaneo para conocer el estado de mi piel y los cuidados que necesito.
    </td>
    <td>
      <strong>Escenario 1: Diagnóstico generado correctamente</strong><br>
      Dado que el usuario completó el escaneo facial
      Cuando el sistema procesa la imagen mediante IA
      Entonces genera un diagnóstico con scores de hidratación, textura, sensibilidad y brillo
      Y muestra el reporte al usuario
      <p></p>
      <strong>Escenario 2: Error de procesamiento</strong><br>
      Dado que ocurre un error al procesar la imagen
      Cuando el sistema no puede completar el análisis
      Entonces informa al usuario
      Y permite reintentar el escaneo
    </td>
    <td>E2(Análisis de piel)</td>
  </tr>

  <tr>
    <td><strong>E4</strong></td>
    <td>Descubrimiento de productos</td>
    <td>
      Como joven adulto, quiero explorar productos de skincare para tomar decisiones informadas según mi tipo de piel.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US08</strong></td>
    <td>Explorar catálogo de productos</td>
    <td>
      Como joven adulto, quiero explorar el catálogo de productos y aplicar filtros para encontrar opciones relevantes a mis necesidades.
    </td>
    <td>
      <strong>Escenario 1: Catálogo cargado</strong><br>
      Dado que el usuario accede al catálogo de productos
      Cuando el sistema carga la información
      Entonces muestra la lista de productos con su categoría y score de compatibilidad
      <p></p>
      <strong>Escenario 2: Filtro aplicado con resultados</strong><br>
      Dado que el usuario aplica un filtro por categoría
      Cuando existen productos que cumplen el criterio
      Entonces el sistema muestra únicamente los productos filtrados
      <p></p>
      <strong>Escenario 3: Filtro sin resultados</strong><br>
      Dado que el usuario aplica un filtro por categoría
      Cuando no existen productos que cumplan el criterio
      Entonces el sistema informa que no hay productos disponibles para ese filtro
    </td>
    <td>E4(Descubrimiento de productos)</td>
  </tr>

  <tr>
    <td><strong>E5</strong></td>
    <td>Seguimiento y progreso del usuario</td>
    <td>
      Como joven adulto, quiero visualizar mi progreso para entender mi constancia y evolución en el cuidado de mi piel.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US11</strong></td>
    <td>Visualizar métricas de progreso</td>
    <td>
      Como joven adulto, quiero visualizar métricas de mi constancia y evolución en el cuidado de mi piel para entender mi progreso.
    </td>
    <td>
      <strong>Escenario 1: Métricas disponibles</strong><br>
      Dado que el usuario accede a la sección de progreso
      Cuando el sistema procesa los datos registrados
      Entonces muestra la racha de días consecutivos, tasa de adherencia, días completados en la semana y el gráfico de skin health score a lo largo del tiempo
      <p></p>
      <strong>Escenario 2: Sin datos suficientes</strong><br>
      Dado que el usuario accede a la sección de progreso
      Cuando no existen registros de cumplimiento ni escaneos previos
      Entonces el sistema informa que no hay datos suficientes
      Y sugiere completar la rutina diaria o realizar un escaneo facial
    </td>
    <td>E5(Seguimiento y progreso del usuario)</td>
  </tr>

  <tr>
    <td><strong>US12</strong></td>
    <td>Consultar historial de escaneos faciales</td>
    <td>
      Como joven adulto, quiero consultar mis escaneos faciales anteriores dentro de la sección Skin Scan para revisar mi evolución y los resultados de cada análisis.
    </td>
    <td>
      <strong>Escenario 1: Historial disponible</strong><br>
      Dado que el usuario accede a la sección de escaneos pasados dentro de Skin Scan
      Cuando el sistema carga su historial
      Entonces muestra la lista de escaneos ordenados por fecha con score general, tipo de piel y scores de hidratación, textura y brillo de cada uno
      <p></p>
      <strong>Escenario 2: Sin escaneos registrados</strong><br>
      Dado que el usuario accede a la sección de escaneos pasados
      Cuando no existen análisis previos registrados
      Entonces el sistema informa que no hay escaneos disponibles
      Y sugiere realizar el primer escaneo facial
    </td>
    <td>E2(Análisis de piel)</td>
  </tr>

  <tr>
    <td><strong>E6</strong></td>
    <td>Soporte inteligente</td>
    <td>
      Como joven adulto, quiero consultar dudas sobre mi piel para recibir orientación personalizada.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US13</strong></td>
    <td>Consultar asistente virtual de skincare</td>
    <td>
      Como joven adulto, quiero consultar dudas sobre productos, rutinas o ingredientes para recibir orientación inmediata basada en mi perfil de piel.
    </td>
    <td>
      <strong>Escenario 1: Consulta respondida</strong><br>
      Dado que el usuario envía una consulta al asistente
      Cuando el sistema procesa la solicitud usando el perfil de piel y último escaneo del usuario
      Entonces genera una respuesta personalizada
      Y la muestra en el chat
      <p></p>
      <strong>Escenario 2: Consulta con sugerencia de consulta médica</strong><br>
      Dado que el usuario realiza una consulta que excede el alcance del asistente
      Cuando el sistema detecta que requiere atención profesional
      Entonces informa la limitación
      Y sugiere agendar una consulta con un dermatólogo
    </td>
    <td>E6(Soporte inteligente)</td>
  </tr>

  <tr>
    <td><strong>E7</strong></td>
    <td>Atención dermatológica</td>
    <td>
      Como joven adulto, quiero acceder a consultas con dermatólogos para recibir atención especializada.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US14</strong></td>
    <td>Listar y seleccionar dermatólogo</td>
    <td>
      Como joven adulto, quiero visualizar una lista de dermatólogos disponibles con su información relevante para elegir con quién agendar una consulta.
    </td>
    <td>
      <strong>Escenario 1: Lista disponible</strong><br>
      Dado que el usuario accede a la sección de consultas dermatológicas
      Cuando el sistema carga la información
      Entonces muestra la lista de dermatólogos con nombre, especialidad, años de experiencia, rating y costo por consulta
      <p></p>
      <strong>Escenario 2: Sin especialistas disponibles</strong><br>
      Dado que el usuario accede a la sección
      Cuando no existen dermatólogos disponibles
      Entonces el sistema informa que no hay especialistas disponibles en este momento
    </td>
    <td>E7(Atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US15</strong></td>
    <td>Pagar y confirmar cita dermatológica</td>
    <td>
      Como joven adulto, quiero realizar el pago de una consulta dermatológica para confirmar mi cita.
    </td>
    <td>
      <strong>Escenario 1: Pago exitoso</strong><br>
      Dado que el usuario ha seleccionado un dermatólogo y horario
      Cuando proporciona datos de pago válidos y confirma la transacción
      Entonces el sistema procesa el pago
      Y confirma la cita con estado CONFIRMED
      <p></p>
      <strong>Escenario 2: Pago fallido</strong><br>
      Dado que el usuario intenta realizar el pago
      Cuando ocurre un error en la transacción
      Entonces el sistema informa que el pago no fue completado
      Y permite reintentar
    </td>
    <td>E7(Atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US16</strong></td>
    <td>Cancelar cita dermatológica</td>
    <td>
      Como joven adulto, quiero cancelar una cita programada para gestionar cambios en mi disponibilidad.
    </td>
    <td>
      <strong>Escenario 1: Cancelación con reembolso</strong><br>
      Dado que el usuario tiene una cita confirmada
      Y la cancelación se realiza dentro del tiempo permitido
      Cuando selecciona una razón y confirma la cancelación
      Entonces el sistema cancela la cita
      Y procesa el reembolso correspondiente
      <p></p>
      <strong>Escenario 2: Cancelación sin reembolso</strong><br>
      Dado que el usuario tiene una cita confirmada
      Y la cancelación se realiza fuera del tiempo permitido
      Cuando confirma la cancelación
      Entonces el sistema cancela la cita
      Y notifica que no aplica reembolso
    </td>
    <td>E7(Atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>E8</strong></td>
    <td>Gestión de suscripción</td>
    <td>
      Como joven adulto, quiero gestionar mi plan de suscripción para acceder a las funcionalidades de la aplicación.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US17</strong></td>
    <td>Seleccionar y pagar plan de suscripción</td>
    <td>
      Como joven adulto, quiero seleccionar un plan de suscripción y completar el pago para acceder a Bloomie.
    </td>
    <td>
      <strong>Escenario 1: Plan seleccionado y pago exitoso</strong><br>
      Dado que el usuario visualiza los planes disponibles con sus características y precios
      Cuando selecciona un plan y completa el pago correctamente
      Entonces el sistema activa la suscripción
      Y habilita el acceso a las funcionalidades correspondientes
      <p></p>
      <strong>Escenario 2: Pago fallido</strong><br>
      Dado que el usuario ha seleccionado un plan
      Cuando ocurre un error en la transacción
      Entonces el sistema informa que el pago no fue completado
      Y permite reintentar
    </td>
    <td>E8(Gestión de suscripción)</td>
  </tr>

  <tr>
    <td><strong>US18</strong></td>
    <td>Gestionar suscripción activa</td>
    <td>
      Como joven adulto, quiero gestionar mi suscripción activa para cambiar de plan o cancelarla según mis necesidades.
    </td>
    <td>
      <strong>Escenario 1: Cambio de plan exitoso</strong><br>
      Dado que el usuario tiene una suscripción activa
      Cuando selecciona un nuevo plan y confirma el cambio
      Entonces el sistema actualiza la suscripción
      Y aplica el nuevo plan en el siguiente ciclo
      <p></p>
      <strong>Escenario 2: Cancelación de suscripción</strong><br>
      Dado que el usuario tiene una suscripción activa
      Cuando solicita cancelarla y confirma la acción
      Entonces el sistema cancela la renovación automática
      Y mantiene el acceso hasta el fin del período vigente
    </td>
    <td>E8(Gestión de suscripción)</td>
  </tr>

  <tr>
    <td><strong>E9</strong></td>
    <td>Gestión de perfil del usuario</td>
    <td>
      Como joven adulto, quiero gestionar mi información personal para mantener mi cuenta actualizada.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US19</strong></td>
    <td>Editar perfil e información personal</td>
    <td>
      Como joven adulto, quiero editar mi información personal para mantener mis datos actualizados.
    </td>
    <td>
      <strong>Escenario 1: Edición exitosa</strong><br>
      Dado que el usuario modifica su nombre, apellido o email
      Cuando el sistema valida los datos
      Entonces guarda los cambios correctamente
      <p></p>
      <strong>Escenario 2: Datos inválidos</strong><br>
      Dado que el usuario ingresa datos con formato incorrecto
      Cuando el sistema valida la información
      Entonces rechaza los cambios
      Y notifica el error específico
    </td>
    <td>E9(Gestión de perfil del usuario)</td>
  </tr>

  <tr>
    <td><strong>US20</strong></td>
    <td>Actualizar características de piel</td>
    <td>
      Como joven adulto, quiero actualizar mis características de piel para recibir recomendaciones más precisas.
    </td>
    <td>
      <strong>Escenario 1: Actualización exitosa</strong><br>
      Dado que el usuario modifica su tipo de piel o nivel de sensibilidad
      Cuando el sistema valida los datos
      Entonces guarda la información actualizada
      Y recalcula las recomendaciones según el nuevo perfil
    </td>
    <td>E9(Gestión de perfil del usuario)</td>
  </tr>

  <tr>
    <td><strong>US21</strong></td>
    <td>Cambiar contraseña</td>
    <td>
      Como joven adulto, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta.
    </td>
    <td>
      <strong>Escenario 1: Cambio exitoso</strong><br>
      Dado que el usuario ingresa una nueva contraseña válida
      Cuando el sistema valida que cumple las reglas de seguridad
      Entonces actualiza la contraseña correctamente
      <p></p>
      <strong>Escenario 2: Contraseña inválida</strong><br>
      Dado que el usuario ingresa una contraseña que no cumple las reglas
      Cuando el sistema valida la información
      Entonces rechaza el cambio
      Y explica los requisitos no cumplidos
    </td>
    <td>E9(Gestión de perfil del usuario)</td>
  </tr>

  <tr>
    <td><strong>E10</strong></td>
    <td>Experiencia web — Landing Page</td>
    <td>
      Como visitante, quiero explorar el sitio web de Bloomie para entender su propuesta de valor antes de registrarme.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US22</strong></td>
    <td>Comprender la propuesta de valor</td>
    <td>
      Como visitante, quiero comprender qué ofrece Bloomie para evaluar si resuelve mis necesidades.
    </td>
    <td>
      <strong>Escenario 1: Contenido disponible</strong><br>
      Dado que el visitante accede a la landing page
      Cuando el sistema carga el contenido
      Entonces presenta la propuesta de valor principal con las funcionalidades destacadas de análisis de piel, rutinas personalizadas y consultas dermatológicas
    </td>
    <td>E10(Experiencia web — Landing Page)</td>
  </tr>

  <tr>
    <td><strong>US23</strong></td>
    <td>Explorar planes y precios</td>
    <td>
      Como visitante, quiero visualizar los planes disponibles y sus precios para elegir la opción que mejor se adapte a mis necesidades.
    </td>
    <td>
      <strong>Escenario 1: Planes mostrados</strong><br>
      Dado que el visitante accede a la sección de precios
      Cuando el sistema carga la información
      Entonces muestra los tres planes con sus características, límites y precios
      <p></p>
      <strong>Escenario 2: Comparación de planes</strong><br>
      Dado que el visitante visualiza los planes
      Cuando analiza las diferencias
      Entonces el sistema presenta claramente qué incluye cada plan y qué lo diferencia de los demás
    </td>
    <td>E10(Experiencia web — Landing Page)</td>
  </tr>

  <tr>
    <td><strong>US24</strong></td>
    <td>Navegar entre secciones del sitio</td>
    <td>
      Como visitante, quiero navegar entre las secciones de la landing page para explorar todo el contenido disponible.
    </td>
    <td>
      <strong>Escenario 1: Navegación exitosa</strong><br>
      Dado que el visitante accede a la landing page
      Cuando selecciona una sección del menú de navegación
      Entonces el sistema desplaza la vista a la sección correspondiente
    </td>
    <td>E10(Experiencia web — Landing Page)</td>
  </tr>

  <tr>
    <td><strong>E11</strong></td>
    <td>Gestión de atención dermatológica</td>
    <td>
      Como dermatólogo, quiero gestionar mi práctica clínica en Bloomie para ofrecer consultas eficientes y de calidad.
    </td>
    <td></td>
    <td></td>
  </tr>

  <tr>
    <td><strong>US25</strong></td>
    <td>Registro de dermatólogo</td>
    <td>
      Como dermatólogo, quiero registrar mis credenciales profesionales para acceder a las funcionalidades especializadas de Bloomie.
    </td>
    <td>
      <strong>Escenario 1: Registro exitoso</strong><br>
      Dado que el dermatólogo proporciona nombre, apellido, email, contraseña y especialidad válidos
      Cuando el sistema valida la información
      Entonces registra la cuenta con rol DERMATOLOGIST
      Y habilita el acceso a funcionalidades médicas
      <p></p>
      <strong>Escenario 2: Credenciales inválidas</strong><br>
      Dado que el dermatólogo proporciona información incompleta o incorrecta
      Cuando el sistema valida los datos
      Entonces rechaza el registro
      Y notifica el campo específico con error
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US26</strong></td>
    <td>Configurar perfil profesional</td>
    <td>
      Como dermatólogo, quiero configurar mi perfil profesional con mi especialidad y tarifa de consulta para que los pacientes puedan encontrarme y saber qué esperar.
    </td>
    <td>
      <strong>Escenario 1: Perfil configurado exitosamente</strong><br>
      Dado que el dermatólogo accede a la configuración de perfil
      Cuando ingresa su especialidad, años de experiencia y tarifa de consulta
      Entonces el sistema guarda el perfil
      Y lo hace visible para los usuarios que buscan dermatólogos
      <p></p>
      <strong>Escenario 2: Datos inválidos</strong><br>
      Dado que el dermatólogo ingresa información incompleta
      Cuando el sistema valida los datos
      Entonces rechaza los cambios
      Y notifica los campos requeridos
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US27</strong></td>
    <td>Definir disponibilidad de atención</td>
    <td>
      Como dermatólogo, quiero definir mis horarios de disponibilidad para que los pacientes puedan agendar citas en horarios válidos.
    </td>
    <td>
      <strong>Escenario 1: Disponibilidad registrada</strong><br>
      Dado que el dermatólogo accede a la configuración de disponibilidad
      Cuando define sus horarios de atención
      Entonces el sistema guarda la disponibilidad
      Y la refleja en el proceso de agendamiento para los pacientes
      <p></p>
      <strong>Escenario 2: Disponibilidad actualizada</strong><br>
      Dado que el dermatólogo tiene horarios registrados
      Cuando modifica su disponibilidad
      Entonces el sistema guarda los cambios
      Y actualiza los horarios disponibles para nuevas citas
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US28</strong></td>
    <td>Visualizar agenda de consultas</td>
    <td>
      Como dermatólogo, quiero visualizar mis consultas programadas para gestionar mi tiempo de atención.
    </td>
    <td>
      <strong>Escenario 1: Agenda con citas</strong><br>
      Dado que el dermatólogo accede a su agenda
      Cuando existen citas confirmadas
      Entonces el sistema muestra las consultas con fecha, hora y datos del paciente
      <p></p>
      <strong>Escenario 2: Sin citas programadas</strong><br>
      Dado que el dermatólogo accede a su agenda
      Cuando no existen citas registradas
      Entonces el sistema informa que no hay consultas programadas
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US29</strong></td>
    <td>Realizar consulta virtual en tiempo real</td>
    <td>
      Como dermatólogo, quiero interactuar en tiempo real con el paciente durante la consulta virtual para evaluar su condición y brindar recomendaciones.
    </td>
    <td>
      <strong>Escenario 1: Consulta iniciada</strong><br>
      Dado que el dermatólogo accede a una cita confirmada en el horario programado
      Cuando inicia la consulta
      Entonces el sistema habilita la sesión virtual
      Y permite la comunicación en tiempo real con el paciente
      <p></p>
      <strong>Escenario 2: Consulta finalizada</strong><br>
      Dado que la consulta está activa
      Cuando el dermatólogo finaliza la sesión
      Entonces el sistema registra el cierre
      Y actualiza el estado de la consulta a COMPLETED
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US30</strong></td>
    <td>Registrar notas y recomendaciones clínicas</td>
    <td>
      Como dermatólogo, quiero registrar notas clínicas y recomendaciones durante la consulta para dejar un registro del caso atendido.
    </td>
    <td>
      <strong>Escenario 1: Notas registradas exitosamente</strong><br>
      Dado que el dermatólogo tiene una consulta activa
      Cuando ingresa notas clínicas y recomendaciones para el paciente
      Entonces el sistema guarda la información
      Y la asocia a la consulta correspondiente
      <p></p>
      <strong>Escenario 2: Registro sin notas</strong><br>
      Dado que el dermatólogo finaliza una consulta sin ingresar notas
      Cuando confirma el cierre
      Entonces el sistema finaliza la consulta
      Y deja los campos de notas y recomendaciones vacíos
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US31</strong></td>
    <td>Registrar fotografías clínicas</td>
    <td>
      Como dermatólogo, quiero registrar fotografías clínicas del paciente durante la consulta para documentar su evolución.
    </td>
    <td>
      <strong>Escenario 1: Foto registrada exitosamente</strong><br>
      Dado que el dermatólogo tiene una consulta activa
      Cuando sube una fotografía clínica del paciente
      Entonces el sistema almacena la imagen
      Y la asocia a la consulta correspondiente
      <p></p>
      <strong>Escenario 2: Sin fotos registradas</strong><br>
      Dado que el dermatólogo accede al historial de una consulta
      Cuando no existen fotografías registradas
      Entonces el sistema informa que no hay imágenes disponibles
    </td>
    <td>11(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US32</strong></td>
    <td>Consultar historial de consultas atendidas</td>
    <td>
      Como dermatólogo, quiero consultar el historial de mis consultas atendidas para revisar casos previos y sus registros clínicos.
    </td>
    <td>
      <strong>Escenario 1: Historial disponible</strong><br>
      Dado que el dermatólogo accede a su historial
      Cuando existen consultas registradas
      Entonces el sistema muestra las consultas atendidas con fecha, paciente, notas y recomendaciones registradas
      <p></p>
      <strong>Escenario 2: Sin historial</strong><br>
      Dado que el dermatólogo accede a su historial
      Cuando no existen consultas registradas
      Entonces el sistema informa que no hay consultas disponibles
    </td>
    <td>E9(Gestión de atención dermatológica)</td>
  </tr>

  <tr>
    <td><strong>US33</strong></td>
    <td>Actualizar perfil profesional</td>
    <td>
      Como dermatólogo, quiero actualizar mi información profesional para mantener mi perfil al día.
    </td>
    <td>
      <strong>Escenario 1: Actualización exitosa</strong><br>
      Dado que el dermatólogo modifica su especialidad, tarifa o años de experiencia
      Cuando el sistema valida los datos
      Entonces guarda los cambios
      Y actualiza el perfil visible para los usuarios
      <p></p>
      <strong>Escenario 2: Datos inválidos</strong><br>
      Dado que el dermatólogo ingresa información incorrecta
      Cuando el sistema valida los datos
      Entonces rechaza los cambios
      Y notifica el error específico
    </td>
    <td>E11(Gestión de atención dermatológica)</td>
  </tr>

<!-- Technical Stories -->

<tr>
  <td><strong>TS01</strong></td>
  <td>Procesar pago de consulta dermatológica</td>
  <td>
    Como developer, quiero registrar y verificar el pago de una consulta dermatológica mediante una API de pagos para confirmar la cita del usuario.
  </td>
  <td>
    <strong>Escenario 1: Creación exitosa de orden de pago</strong><br>
      Dado que el usuario ha seleccionado una cita válida
      Cuando el developer envía una solicitud POST a /api/pagos/consultas con el identificador de la cita y el monto
      Entonces la API devuelve una respuesta exitosa con el identificador de la transacción
      Y el estado inicial del pago queda como pendiente.
    <p></p>
    <strong>Escenario 2: Confirmación exitosa del pago</strong><br>
      Dado que existe una transacción de pago pendiente
      Cuando el developer consulta o recibe la confirmación del proveedor de pagos
      Entonces la API actualiza el estado de la transacción a pagado
      Y la cita queda confirmada.
    <p></p>
    <strong>Escenario 3: Pago rechazado</strong><br>
      Dado que el usuario intenta completar el pago
      Cuando el proveedor de pagos rechaza la operación
      Entonces la API devuelve un estado de pago fallido
      Y la cita no se confirma.
    <p></p>
    <strong>Escenario 4: Datos inválidos de pago</strong><br>
      Dado que la solicitud contiene una cita inexistente o un monto inválido
      Cuando el developer envía la solicitud
      Entonces la API responde con error 400 Bad Request
      Y muestra el detalle de validación.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

<tr>
  <td><strong>TS02</strong></td>
  <td>Procesar pago de compra de plan dermatológico</td>
  <td>
    Como developer, quiero registrar y verificar el pago de un plan dermatológico mediante una API de pagos para activar el plan adquirido por el usuario.
  </td>
  <td>
    <strong>Escenario 1: Creación exitosa de orden de pago del plan</strong><br>
      Dado que el usuario ha seleccionado un plan dermatológico disponible
      Cuando el developer envía una solicitud POST a /api/pagos/planes con el identificador del plan, usuario y monto
      Entonces la API devuelve una respuesta exitosa con el identificador de la transacción
      Y el estado inicial del pago queda como pendiente.
    <p></p>
    <strong>Escenario 2: Activación exitosa del plan</strong><br>
      Dado que existe una transacción de pago pendiente asociada a un plan
      Cuando el developer consulta o recibe la confirmación del proveedor de pagos
      Entonces la API actualiza el estado de la transacción a pagado
      Y el plan queda activo para el usuario.
    <p></p>
    <strong>Escenario 3: Pago rechazado del plan</strong><br>
      Dado que el usuario intenta completar el pago de un plan
      Cuando el proveedor de pagos rechaza la operación
      Entonces la API devuelve un estado de pago fallido
      Y el plan no se activa.
    <p></p>
    <strong>Escenario 4: Plan o monto inválido</strong><br>
      Dado que la solicitud contiene un plan inexistente o un monto inválido
      Cuando el developer envía la solicitud
      Entonces la API responde con error 400 Bad Request
      Y muestra el detalle de validación.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

<tr>
  <td><strong>TS03</strong></td>
  <td>Consultar estado de una transacción de pago</td>
  <td>
    Como developer, quiero consultar el estado de una transacción de pago mediante una API de pagos para verificar si una consulta debe confirmarse o un plan debe activarse.
  </td>
  <td>
    <strong>Escenario 1: Consulta exitosa de transacción</strong><br>
      Dado que existe una transacción de pago registrada
      Cuando el developer envía una solicitud GET a /api/pagos/{transactionId}
      Entonces la API devuelve una respuesta 200 OK
      Y muestra el estado actual de la transacción.
    <p></p>
    <strong>Escenario 2: Transacción pagada</strong><br>
      Dado que la transacción fue completada correctamente
      Cuando el developer consulta el estado del pago
      Entonces la API devuelve el estado pagado
      Y muestra si corresponde a una consulta dermatológica o a un plan.
    <p></p>
    <strong>Escenario 3: Transacción pendiente</strong><br>
      Dado que el usuario aún no completó el pago
      Cuando el developer consulta el estado de la transacción
      Entonces la API devuelve el estado pendiente
      Y mantiene la consulta o el plan sin confirmar.
    <p></p>
    <strong>Escenario 4: Transacción no encontrada</strong><br>
      Dado que el developer envía un identificador de transacción inexistente
      Cuando realiza la solicitud de consulta
      Entonces la API responde con error 404 Not Found
      Y muestra un mensaje indicando que la transacción no fue encontrada.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

<tr>
  <td><strong>TS04</strong></td>
  <td>Obtener análisis y respuesta del asistente de IA</td>
  <td>
    Como developer, quiero enviar una consulta del usuario a una API de inteligencia artificial para obtener orientación sobre productos, ingredientes, rutinas o estado de la piel.
  </td>
  <td>
    <strong>Escenario 1: Consulta respondida correctamente</strong><br>
      Dado que el usuario ingresa una pregunta válida
      Cuando el developer envía una solicitud POST a /api/ai/consultas con el texto de la consulta
      Entonces la API devuelve una respuesta 200 OK
      Y retorna una respuesta generada por la IA.
    <p></p>
    <strong>Escenario 2: Consulta con contexto del usuario</strong><br>
      Dado que el usuario tiene información registrada sobre su tipo de piel o rutina
      Cuando el developer envía la consulta junto con ese contexto
      Entonces la API devuelve una respuesta más personalizada.
    <p></p>
    <strong>Escenario 3: Consulta vacía o inválida</strong><br>
      Dado que el developer envía una solicitud sin texto de consulta
      Cuando la API valida la entrada
      Entonces responde con 400 Bad Request
      Y explica que la consulta es obligatoria.
    <p></p>
    <strong>Escenario 4: La IA no puede responder</strong><br>
      Dado que la pregunta no puede resolverse con suficiente confianza
      Cuando la API procesa la consulta
      Entonces devuelve una respuesta indicando la limitación
      Y sugiere consultar a un dermatólogo.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

<tr>
  <td><strong>TS05</strong></td>
  <td>Obtener recomendación de productos dermatológicos</td>
  <td>
    Como developer, quiero enviar el tipo de piel, necesidades y preferencias del usuario a una API de inteligencia artificial para obtener recomendaciones de productos dermatológicos adecuados.
  </td>
  <td>
    <strong>Escenario 1: Recomendación exitosa de productos</strong><br>
      Dado que el usuario indica su tipo de piel y necesidad principal
      Cuando el developer envía una solicitud POST a /api/ai/recomendaciones/productos con los datos del usuario
      Entonces la API devuelve una respuesta 200 OK
      Y retorna una lista de productos recomendados.
    <p></p>
    <strong>Escenario 2: Recomendación personalizada según tipo de piel</strong><br>
      Dado que el usuario tiene registrado su tipo de piel
      Cuando la API genera la recomendación
      Entonces prioriza productos adecuados para ese tipo de piel
      Y explica brevemente por qué son recomendados.
    <p></p>
    <strong>Escenario 3: Datos insuficientes del usuario</strong><br>
      Dado que el developer no envía información suficiente sobre el tipo de piel o necesidad del usuario
      Cuando la API procesa la solicitud
      Entonces responde con 400 Bad Request
      Y solicita completar los datos necesarios para generar la recomendación.
    <p></p>
    <strong>Escenario 4: No hay productos adecuados disponibles</strong><br>
      Dado que no existen productos relacionados con la necesidad indicada
      Cuando la API busca recomendaciones
      Entonces devuelve una respuesta indicando que no se encontraron productos adecuados
      Y sugiere consultar con un dermatólogo.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

<tr>
  <td><strong>TS06</strong></td>
  <td>Generar rutina personalizada de cuidado de piel</td>
  <td>
    Como developer, quiero enviar información del perfil dermatológico del usuario a una API de inteligencia artificial para generar una rutina personalizada de cuidado de piel.
  </td>
  <td>
    <strong>Escenario 1: Rutina generada correctamente</strong><br>
      Dado que el usuario proporciona su tipo de piel y objetivo dermatológico
      Cuando el developer envía una solicitud POST a /api/ai/rutinas con la información del usuario
      Entonces la API devuelve una respuesta 200 OK
      Y retorna una rutina organizada en pasos de mañana y noche.
    <p></p>
    <strong>Escenario 2: Rutina con productos recomendados</strong><br>
      Dado que existen productos compatibles con el perfil del usuario
      Cuando la API genera la rutina personalizada
      Entonces incluye productos sugeridos dentro de cada paso
      Y explica la función de cada producto en la rutina.
    <p></p>
    <strong>Escenario 3: Información incompleta del perfil</strong><br>
      Dado que el developer no envía información suficiente sobre el perfil dermatológico del usuario
      Cuando la API procesa la solicitud
      Entonces devuelve una rutina general
      Y solicita completar el perfil para una recomendación más precisa.
    <p></p>
    <strong>Escenario 4: Caso que requiere atención dermatológica</strong><br>
      Dado que el usuario describe síntomas severos o persistentes
      Cuando la API genera la respuesta
      Entonces evita dar un diagnóstico definitivo
      Y recomienda acudir a un dermatólogo.
  </td>
  <td>E11(Servicios REST)</td>
</tr>

</table>

## 3.2. Impact Mapping
#### 3.2.1. Business Goal 1: 
- Incrementar la tasa de usuarios y dermatólogos que realicen el proceso de onboarding del 60% al 85% en un plazo de 3 meses.

<img src="assets/img/impactmap-1.png" alt="impact mapping photo" width="550"/>

#### 3.2.2. Business Goal 2: 
- Lograr que al menos el 70% de los usuarios que realizan el escaneo facial completen el flujo hasta recibir su rutina personalizada , y que al menos el 50% de los dermatólogos activos utilicen la plataforma para consultar información de pacientes, en un plazo de 4 meses.

<img src="assets/img/impactmap-2.png" alt="impact mapping photo" width="550"/>

#### 3.2.3. Business Goal 3: 
- Aumentar la tasa de usuarios activos que registran su rutina al menos 3 veces por semana del 30% al 55%, y lograr que el 60% de los dermatólogos gestionen activamente sus consultas en la plataforma, en un periodo de 5 meses.

<img src="assets/img/impactmap-3.png" alt="impact mapping photo" width="550"/>



## 3.3. Product Backlog
<table border="1" cellspacing="0" cellpadding="8">

  <tr>
    <th>#Orden</th>
    <th>User story id</th>
    <th>Título</th>
    <th>Descripción</th>
    <th>Story points (1/2/3/5/8)</th>
  </tr>

  <tr>
    <td><strong>01</strong></td>
    <td>US22</td>
    <td> Comprender la propuesta de valor </td>
    <td>
      Como visitante, quiero comprender la propuesta de valor de la aplicación para evaluar si resuelve mis necesidades.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>02</strong></td>
    <td>US24</td>
    <td>Navegar entre secciones del sitio
    </td>
    <td>
       Como visitante, quiero navegar entre las diferentes secciones del sitio para explorar el contenido disponible.
    </td>
    <td> 2 </td>
  </tr>


  <tr>
    <td><strong>03</strong></td>
    <td>US03</td>
    <td>Escaneo facial</td>
    <td>
        Como joven adulto, quiero realizar un escaneo facial moviendo mi cabeza frente a la cámara para que la aplicación capture imágenes desde diferentes ángulos y obtenga un diagnóstico preciso de mi tipo de piel.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>04</strong></td>
    <td>US04</td>
    <td>Diagnóstico preliminar automático</td>
    <td>
        Como joven adulto, quiero recibir un reporte preliminar generado por la inteligencia artificial después del escaneo facial para conocer el estado de mi piel y entender qué tipo de cuidados necesito.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>05</strong></td>
    <td>US12</td>
    <td>Consultar historial de escaneos faciales</td>
    <td>
      Como joven adulto, quiero consultar mis escaneos faciales anteriores dentro de la sección Skin Scan para revisar mi evolución y los resultados de cada análisis.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>06</strong></td>
    <td>US02</td>
    <td>Completar perfil de piel</td>
    <td>
       Como joven adulto, quiero completar un cuestionario inicial de hábitos y condiciones de piel en mi primer ingreso para que la aplicación configure diagnósticos y rutinas personalizadas.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>07</strong></td>
    <td>US11</td>
    <td>Visualizar métricas de progreso</td>
    <td>
       Como joven adulto, quiero visualizar métricas de mi progreso para entender mi constancia y evolución en el cuidado de mi piel.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>08</strong></td>
    <td>US08</td>
    <td>Explorar catálogo de productos</td>
    <td>
       Como joven adulto, quiero explorar un catálogo de productos y aplicar filtros para encontrar opciones relevantes a mis necesidades.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>10</strong></td>
    <td>US15</td>
    <td>Registrar cumplimiento de rutina diaria</td>
    <td>
       Como joven adulto, quiero marcar si completé mi rutina diaria para llevar un seguimiento de mi progreso.
    </td>
    <td> 3 </td>
  </tr>

  
  <tr>
    <td><strong>12</strong></td>
    <td>US06</td>
    <td>Adaptar rutina mediante reemplazo de productos</td>
    <td>
       Como joven adulto, quiero modificar los productos sugeridos en mi rutina para adaptarlos a mis necesidades o disponibilidad.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>13</strong></td>
    <td>US07</td>
    <td>Recordatorios de rutina</td>
    <td>
       CComo joven adulto, quiero recibir recordatorios para cumplir con mi rutina de cuidado de la piel y mantener constancia.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>14</strong></td>
    <td>US08</td>
    <td>Explorar catálogo de productos con filtros</td>
    <td>
       Como joven adulto, quiero explorar un catálogo de productos y aplicar filtros para encontrar opciones relevantes a mis necesidades.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>17</strong></td>
    <td>US14</td>
    <td>Listar y seleccionar dermatólogos para agendar</td>
    <td>
       Como joven adulto, quiero visualizar una lista de dermatólogos con información relevante para elegir a quién agendar una consulta.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>22</strong></td>
    <td>US15</td>
    <td>Pagar y confirmar cita dermatológica</td>
    <td>
      Como joven adulto, quiero realizar el pago de una consulta dermatológica para confirmar mi cita. 
    </td>
    <td> 3 </td>
  </tr>

   <tr>
    <td><strong>15</strong></td>
    <td>US09</td>
    <td>Evaluar compatibilidad de productos</td>
    <td>
       Como joven adulto, quiero conocer la compatibilidad de un producto para tomar decisiones informadas.
    </td>
    <td> 5 </td>
  </tr>

 <tr>
    <td><strong>20</strong></td>
    <td>US14</td>
    <td>Cancelar cita dermatológica</td>
    <td>
      Como joven adulto, quiero cancelar una cita programada para gestionar cambios en mi disponibilidad.
    </td>
    <td> 3 </td>
  </tr>


   <tr>
    <td><strong>23</strong></td>
    <td>US19</td>
    <td>Editar perfil e información personal</td>
    <td>
      Como joven adulto, quiero editar mi información personal para mantener mis datos actualizados.
    </td>
    <td> 3 </td>
  </tr>


   <tr>
    <td><strong>24</strong></td>
    <td>US20</td>
    <td>Actualizar características de piel</td>
    <td>
      Como joven adulto, quiero actualizar mis características de piel para recibir recomendaciones más precisas.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>25</strong></td>
    <td>US01</td>
    <td>Registro de cuenta</td>
    <td>
      Como joven adulto, quiero registrarme con mis datos personales para crear una cuenta y acceder a Bloomie.
    </td>
    <td> 3 </td>
  </tr>
 
 <tr>
    <td><strong>26</strong></td>
    <td>US21</td>
    <td>Cambiar contraseña</td>
    <td>
      Como joven adulto, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta.
    </td>
    <td> 2 </td>
  </tr>

  <tr>
    <td><strong>16</strong></td>
    <td>US10</td>
    <td>Asistente virtual de skincare</td>
    <td>
       Como joven adulto, quiero consultar dudas sobre productos, rutinas o ingredientes para recibir orientación inmediata.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>17</strong></td>
    <td>US14</td>
    <td>Listar y seleccionar dermatólogos para agendar</td>
    <td>
       Como joven adulto, quiero visualizar una lista de dermatólogos con información relevante para elegir a quién agendar una consulta.
    </td>
    <td> 3 </td>
  </tr>

 <tr>
    <td><strong>18</strong></td>
    <td>US31</td>
    <td>Definir disponibilidad de atención</td>
    <td>
       Como dermatólogo, quiero definir mi disponibilidad para que los pacientes puedan agendar citas en horarios válidos.
    </td>
    <td> 5 </td>
  </tr>

   <tr>
    <td><strong>19</strong></td>
    <td>US13</td>
    <td>Realizar pago de consulta dermatológica</td>
    <td>
       Como joven adulto, quiero realizar el pago de una consulta dermatológica para confirmar mi cita.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>20</strong></td>
    <td>US14</td>
    <td>Cancelar cita dermatológica</td>
    <td>
      Como joven adulto, quiero cancelar una cita programada para gestionar cambios en mi disponibilidad.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>21</strong></td>
    <td>US11</td>
    <td>Explorar mapa de tiendas y productos</td>
    <td>
      Como joven adulto, quiero visualizar en un mapa interactivo tiendas cercanas donde pueda encontrar productos para facilitar su compra.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>22</strong></td>
    <td>US19</td>
    <td>Visualizar perfil</td>
    <td>
      Como joven adulto, quiero visualizar mi perfil para consultar mi información personal.
    </td>
    <td> 2 </td>
  </tr>

  <tr>
    <td><strong>24</strong></td>
    <td>US21</td>
    <td>Actualizar características de piel</td>
    <td>
      Como joven adulto, quiero actualizar mis características de piel para recibir recomendaciones más precisas.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>25</strong></td>
    <td>US01</td>
    <td>Registro de cuenta</td>
    <td>
      Como joven adulto, quiero registrarme con mis datos personales para crear una cuenta y acceder a Bloomie.
    </td>
    <td> 3 </td>
  </tr>

<tr>
    <td><strong>26</strong></td>
    <td>US21</td>
    <td>Cambiar contraseña</td>
    <td>
      Como joven adulto, quiero cambiar mi contraseña para mantener la seguridad de mi cuenta.
    </td>
    <td> 2 </td>
  </tr>

<tr>
    <td><strong>26</strong></td>
    <td>US23</td>
    <td>Cambiar contraseña</td>
    <td>
       Como visitante, quiero visualizar los planes disponibles y sus precios para elegir la opción que mejor se adapte a mis necesidades.
    </td>
    <td> 3 </td>
  </tr>
  

  <tr>
    <td><strong>27</strong></td>
    <td>US17</td>
    <td>Seleccionar plan de suscripción</td>
    <td>
      Como joven adulto, quiero seleccionar un plan de suscripción para acceder a las funcionalidades de la aplicación.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>29</strong></td>
    <td>US17</td>
    <td>Seleccionar plan de suscripción</td>
    <td>
     Como joven adulto, quiero seleccionar un plan de suscripción para acceder a las funcionalidades de la aplicación.
    </td>
    <td> 3 </td>
  </tr>
  
  <tr>
    <td><strong>29</strong></td>
    <td>US18</td>
    <td>Gestionar suscripción activa</td>
    <td>
    Como joven adulto, quiero gestionar mi suscripción activa para cambiar de plan o cancelarla según mis necesidades.
    </td>
    <td> 3 </td>
  </tr>

 <tr>
    <td><strong>29</strong></td>
    <td>US25</td>
    <td>Registrar dermatólogo</td>
    <td>
     Como dermatólogo, quiero registrar mis credenciales profesionales para acceder a funcionalidades especializadas.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>27</strong></td>
    <td>US27</td>
    <td>Definir disponibilidad de atención</td>
    <td>
     Como dermatólogo, quiero definir mi disponibilidad para que los pacientes puedan agendar citas en horarios válidos.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>34</strong></td>
    <td>US28</td>
    <td>Visualizar agenda de consultas</td>
    <td>
      Como dermatólogo, quiero visualizar mis consultas programadas para gestionar mi tiempo.
    </td>
    <td> 3 </td>
  </tr>

  <tr>
    <td><strong>31</strong></td>
    <td>US25</td>
    <td>Realizar consulta en tiempo real</td>
    <td>
      Como dermatólogo, quiero interactuar en tiempo real con el paciente para evaluar su condición y brindar recomendaciones.
    </td>
    <td> 5 </td>
  </tr>
llllllll
  <tr>
    <td><strong>30</strong></td>
    <td>US24</td>
    <td>Visualizar pacientes recientes</td>
    <td>
      Como dermatólogo, quiero visualizar mis pacientes recientes para acceder a su información clínica.
    </td>
    <td> 5 </td>
  </tr>

  <tr>
    <td><strong>31</strong></td>
    <td>US29</td>
    <td>Realizar consulta en tiempo real</td>
    <td>
      Como dermatólogo, quiero interactuar en tiempo real con el paciente para evaluar su condición y brindar recomendaciones.
    </td>
    <td> 5 </td>
  </tr>

   <tr>
    <td><strong>32</strong></td>
    <td>US31</td>
    <td>Registrar fotografías clínicas</td>
    <td>
      Como dermatólogo, quiero registrar fotografías clínicas del paciente durante la consulta para documentar su evolución.
    </td>
    <td> 3 </td>
  </tr>


  <tr>
    <td><strong>37</strong></td>
    <td>US32</td>
    <td>Consultar historial de consultas atendidas</td>
    <td>
      Como dermatólogo, quiero consultar el historial de consultas atendidas para analizar casos previos.
    </td>
    <td> 3 </td>
  </tr>

   <tr>
    <td><strong>38</strong></td>
    <td>US33</td>
    <td>Actualizar perfil profesional</td>
    <td>
      Como dermatólogo, quiero actualizar mi perfil profesional para mantener mi información actualizada.
    </td>
    <td> 3 </td>
  </tr>
  <table>

</table>

**Enlace del product backlog en trello:** [*Ir a trello aquí*](https://trello.com/b/Y2tqaAyd/product-backlog)

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
#### 4.1.1.1. Branding
Nuestro objetivo como empresa es reflejar una imagen de confort, confianza y 
confidencialidad. Por tanto, la identidad visual para nuestro logo utiliza colores directos, así 
como también un diseño práctico para mayor credibilidad y seriedad al tratarse de la salud.  

#### Logo de la marca

<img src="assets/img/logo-bloomie.jpg" alt="logo-bloomie" width="500"/>

#### 4.1.1.2. Spacing
El sistema de espaciado asegura consistencia visual en la interfaz y mejora la legibilidad, 
accesibilidad y usabilidad en web y móvil. Se establecen reglas claras para la separación entre 
elementos, aplicables en toda la plataforma. 

#### Sistema modular
Se adopta un sistema modular basado en múltiplos de 4 px (4, 8, 12, 16, 24, 32…). Esto 
garantiza uniformidad en márgenes y paddings en todos los componentes. 

1. Distancia mínima entre íconos

Los íconos deben mantener un espaciado mínimo de 10 px entre sí (como se muestra en la 
referencia visual adjunta), para evitar saturación y asegurar claridad.

<img src="assets/img/distancia-iconos.png" alt="distancia-iconos" width="500"/>

2. Márgenes y paddings estándar 

- Entre secciones principales: 24–32 px en web / 16–20 px en móvil. 
- Entre bloques de texto y botones: mínimo 16px.
- Entre íconos y etiquetas de texto: mínimo 8 px.

3. Tamaños mínimos de elementos interactivos
- Botones: mínimo 44x44px (recomendado por estándares de accesibilidad).
- Íconos no menores a 30x30 px. 
- Logotipo: no reducir a menos de 30 px de alto para evitar pérdida de legibilidad.

4. Espaciado en texto (relacionado a tipografía) 
- Interlineado (line-height): 1.5x el tamaño de la fuente para párrafos. 
- Espaciado entre párrafos: mínimo 16px.

#### 4.1.1.3. Typography
La tipografía oficial de Bloomie es Montserrat, seleccionada por su legibilidad en pantallas 
digitales, su estilo moderno y minimalista.  
Se emplea en distintos pesos y tamaños para jerarquizar el contenido y asegurar una 
experiencia visual consistente en todas las interfaces (web y móvil).

<table>
  <tr>
    <th>Estilo</th>
    <th>Uso principal</th>
    <th>Fuente</th>
    <th>Peso</th>
    <th>Tamaño Desktop</th>
    <th>Tamaño Mobile</th>
    <th>Line-height</th>
    <th>Ejemplo de uso</th>
  </tr>

  <tr>
    <td><b>H1</b></td>
    <td>Títulos principales (ej. <i>Bloomie</i>).</td>
    <td>Montserrat</td>
    <td>Semibold</td>
    <td>62 px</td>
    <td>28 px</td>
    <td>120%</td>
    <td>Pantallas de inicio, títulos de portada</td>
  </tr>

  <tr>
    <td><b>H2</b></td>
    <td>Subtítulos grandes (ej. <i>Your Skincare Journey Starts Here</i>)</td>
    <td>Montserrat</td>
    <td>Semibold</td>
    <td>48 px</td>
    <td>20 px</td>
    <td>120%</td>
    <td>Subtítulos en secciones o mensajes clave</td>
  </tr>

  <tr>
    <td><b>H3</b></td>
    <td>Encabezados menores</td>
    <td>Montserrat</td>
    <td>Semibold</td>
    <td>18 px</td>
    <td>16 px</td>
    <td>120%</td>
    <td>Títulos de tarjetas, secciones intermedias</td>
  </tr>

  <tr>
    <td><b>Body</b></td>
    <td>Texto de párrafo</td>
    <td>Montserrat</td>
    <td>Regular</td>
    <td>16 px</td>
    <td>14 px</td>
    <td>150%</td>
    <td>Textos explicativos, indicaciones generales</td>
  </tr>

  <tr>
    <td><b>Small</b></td>
    <td>Texto auxiliar o notas</td>
    <td>Montserrat</td>
    <td>Regular</td>
    <td>12 px</td>
    <td>12 px</td>
    <td>140%</td>
    <td>Mensajes de ayuda, disclaimers, instrucciones</td>
  </tr>

  <tr>
    <td><b>Button</b></td>
    <td>Acciones principales (Login, Signup)</td>
    <td>Montserrat</td>
    <td>Semibold</td>
    <td>16 px</td>
    <td>13 px</td>
    <td>120%</td>
    <td>Botones de acción, CTAs</td>
  </tr>

  <tr>
    <td><b>Label / Tag</b></td>
    <td>Etiquetas, chips, filtros</td>
    <td>Montserrat</td>
    <td>Medium</td>
    <td>14 px</td>
    <td>12 px</td>
    <td>120%</td>
    <td>Filtros, estados, badges</td>
  </tr>
</table>

#### 4.1.1.4. Tono de comunicación y lenguaje aplicado
El lenguaje de Bloomie es cercano, respetuoso y sereno, alineado con el propósito de 
acompañar al usuario en el cuidado de su piel.

1. Dimensiones definidas: 
- Formal/Casual: Casual. Mensajes sencillos y amigables.
- Respetuoso/Irreverente: Respetuoso. Siempre transmitiendo confianza y empatía.
- Entusiasta/Sereno: Sereno. El tono es calmado, motivador y positivo, evitando dramatizar problemas de la piel.

2. Lineamientos de redacción:
- Usar frases cortas y claras.
- Priorizar mensajes positivos (“You can improve your skin with small steps”) en lugar de negativos.
- Evitar tecnicismos dermatológicos complejos; se debe comunicar en un lenguaje que cualquier usuario entienda.

#### 4.1.1.5. Colores
La paleta de Bloomie está diseñada con tonos cálidos y suaves, pensados para transmitir frescura, bienestar y confianza en el cuidado de la piel. Se emplean colores neutros y acentos rosados para lograr armonía visual y consistencia en todas las interfaces.

1. Fondos
- #FDFFF8

<img src="assets/img/color-bloomie-uno.png" alt="color-bloomie-uno" width="250"/>

Casos de uso: fondo principal de la aplicación, mantiene un estilo cálido y limpio.

- #CEBEBE

<img src="assets/img/color-bloomie-dos.png" alt="color-bloomie-dos" width="250"/>

Casos de uso: cuadros con íconos, secciones importantes, bloques secundarios.

2. Textos
- #333333

<img src="assets/img/color-bloomie-tres.png" alt="color-bloomie-tres" width="250"/>

Casos de uso: texto principal y párrafos (legible y elegante, sin llegar a ser negro puro). 

3. Botones y enlaces
- #A26769 

<img src="assets/img/color-bloomie-cuatro.png" alt="color-bloomie-tres" width="250"/>

Casos de uso: botones principales (acciones clave), títulos destacados y elementos de énfasis. 

- #333333

<img src="assets/img/color-bloomie-tres.png" alt="color-bloomie-tres" width="250"/>

Casos de uso: botones principales de acceso (Login, Signup). 

#### Botones
Los botones tienen una fuente Montserrat y un tamaño de 16 px para desktop y 13 px para 
móvil. La estructura es la siguiente:

<img src="assets/img/botones.png" alt="botones" width="250"/>

#### Cabecera

Estas son las dos cabeceras usadas en la app web, en el lado izquierda se observa el logo 
con el nombre de la aplicación y en la parte izquierda enlaces para acceso rápido de aspectos 
importantes dentro de la aplicación.

#### Iconografía
Bloomie utiliza un set propio de íconos minimalistas y lineales, diseñados para ser claros, modernos y consistentes. Los íconos cumplen un rol funcional:

- Comunicar acciones de manera inmediata.
- Sugerir interactividad.
- Destacar información importante.

Todos los íconos mantienen coherencia visual con la paleta de colores y la tipografía definida 
en esta guía. 

<img src="assets/img/iconografia.png" alt="iconografia" width="500"/>


### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

El sistema de etiquetado de Bloomie fue diseñado para garantizar claridad, coherencia y 
simplicidad en la comunicación de todos los elementos dentro de la experiencia digital. Las 
etiquetas, títulos y botones fueron redactados en un lenguaje cotidiano y cercano, de modo 
que los usuarios comprendan fácilmente las acciones que pueden realizar, reduciendo la carga 
cognitiva y reforzando la identidad visual de la marca.

##### Labeling System Landing Page

En la interfaz web se utilizan etiquetas sencillas y universales que guían la exploración inicial del usuario: How it works, Results, Features, About Us, Pricing y Log in en el navigation bar del encabezado principal. Estas se acompañan con botones de otro color como "Analyze my skin" redactados con verbos directos que promueven la interacción con el usuario e incite a utilizar una funcionalidad clave de nuestro producto. 
El encabezado principal incluye el apartado de traducción de idiomas con el i18n, complementado con subtítulos que explican brevemente la propuesta de valor de Bloomie y el botón principal de descarga.

navigation bar: 
<p align = "center">
<img src="assets/img/web-nav.png" alt="navigation-bar" width="500"/>

luego, mantenemos una paleta de colores de contraste entre los blancos con sombreado cafe y variantes. Con ello se genera esa armonía visual.
<p align = "center">
<img src="assets/img/button.png" alt="mensaje-barra" width="500"/>


##### Labeling System App para Jóvenes adultos

En la versión móvil, las etiquetas se enfocan en la acción y el beneficio, manteniendo un tono amable		y		motivador. En el dashboard principal se observan las etiquetas: Personalized skincare, Consult a dermatologist,	Product		suggestion,		etc. Dentro de cada módulo, se mantienen etiquetas descriptivas como Mi rutina, Productos recomendados,   Añadir  paso,   Mis  consultas  y  Resultados  de  análisis. El lenguaje empleado es cercano y positivo, en línea con la voz de marca que busca acompañar y educar al usuario en su cuidado personal.

###### Iconografía estándar

En este apartado de considera todos los icons que son completamente intuitivos para el usuario que se adapta a una acción o funcionalidad en específico.

<p align = "center">
<img src="assets/img/flecha.png" alt="icon" width="250"/>
<img src="assets/img/lupa.png" alt="icon2" width="250"/>



###### Elementos de interacción activa

Son los elementos con los que el joven interactua más seguido, como también lo cumple la navigation bar del móvil.

*navigation bar*
<p align = "center">
<img src="assets/img/navigation.png" alt="nav" width="500"/>

###### Elementos de validación

Icons que aparecen para validar algún tipo de guardado que informe al usuario sobre la evaluación del sistema. 

*icons*
<p align = "center">
<img src="assets/img/check.png" alt="check" width="300"/>
<p align = "center">
<img src="assets/img/error.png" alt="x" width="300"/>


###### Labeling System App para Dermatólogos certificados

En la vista profesional, las etiquetas se adaptan al entorno clínico, priorizando precisión y funcionalidad.
Las secciones principales son Appointments and consultations, My patients, treatment plans and analytics.

De esta manera, se mantiene una coherencia estructural con la versión de usuarios, pero con terminología técnica acorde al perfil profesional.

algunos *icons* de ejemplo:


*icon horario*
<p align = "center">

<img src="assets/img/horario.png" alt="x" width="300"/>
</d>

*icon paciente*
<p align = "center">
<img src="assets/img/corazo.png" alt="x" width="300"/>



### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los SEO Tags y Meta Tags utilizados en la plataforma Bloomie, tanto para la Landing Page como para la Web Application.


- **Landing Page** 

### Principal 

- **Title:**  
  Bloomie — AI Skin Analysis & Personalized Skincare  

- **Description:**  
  AI-powered skin analysis that detects acne, spots, and texture to create your personalized skincare routine.

- **Keywords:**  
  skincare, AI skin analysis, acne detection, personalized skincare, beauty tech, dermatology AI

- **Author:**  
  Dermacare



### Features

- **Title:**  
  Features — Bloomie  

- **Description:**  
  Discover Bloomie features including AI skin analysis, personalized routines, progress tracking, and dermatologist access.

- **Keywords:**  
  skincare features, AI skincare tools, skin analysis app, personalized routine, beauty technology  

- **Author:**  
Dermacare


### How it Works

- **Title:**  
  How it works — Bloomie  

- **Description:**  
  Learn how Bloomie analyzes your skin using AI and creates a personalized skincare routine in seconds.

- **Keywords:**  
  how AI skincare works, skin analysis process, AI dermatology, skincare steps  

- **Author:**  
Dermacare

###  Pricing

- **Title:**  
  Pricing — Bloomie  

- **Description:**  
  Explore Bloomie pricing plans. Start free and upgrade to advanced AI skincare features.

- **Keywords:**  
  skincare app pricing, AI skincare plans, subscription skincare, beauty app pricing  

- **Author:**  
Dermacare

### Results

- **Title:**  
  Results — Bloomie  

- **Description:**  
  Real results from users who improved their skin using Bloomie personalized routines.

- **Keywords:**  
  skincare results, acne improvement, user testimonials skincare, AI skincare results  

- **Author:**  
 Dermacare  


###  About Us

- **Title:**  
  About us — Bloomie  

- **Description:**  
  Meet the team behind Bloomie and learn about our mission to improve skincare using AI.

- **Keywords:**  
  Dermacare, skincare startup, AI skincare company, about Bloomie  

- **Author:**  
Dermacare
<br> </br>
- **Web application**

Para la aplicación web, se definen los siguientes meta tags generales:

- **Title:**  
  Dashboard — Bloomie  

- **Description:**  
  Track your skin progress, manage your routine, and get personalized AI skincare recommendations.

- **Keywords:**  
  skincare dashboard, skin tracking app, AI skincare routine, skin health monitoring  

- **Author:**  
Dermacare


### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

La aplicación Bloomie, en su versión dirigida a jóvenes adultos interesados en el cuidado de la piel, está estructurada bajo un sistema de organización jerárquico, secuencial y parcialmente matricial, con el objetivo de ofrecer una experiencia intuitiva, guiada y flexible. Esta estructura responde directamente a los flujos representados en el sistema, donde el usuario avanza desde procesos iniciales controlados hacia una navegación más libre centrada en sus necesidades.



#### Organización jerárquica

El contenido se organiza siguiendo una estructura jerárquica tipo top-down, claramente reflejada en el flujo principal del sistema.

Nivel 1 – Acceso principal:
Onboarding, Registro de cuenta, Inicio de sesión y Dashboard.
Nivel 2 – Navegación principal (desde Dashboard):
Home, Skin Care, Consultar IA y Perfil.
Nivel 3 – Submódulos y acciones específicas:
En Skin Care: acceso a la rutina personalizada.
En Perfil: configuración de información personal, cambio de foto, skin profile, settings, security y favoritos.
En Consultar IA / funcionalidades clínicas: acceso a consultas, historial, agendamiento y seguimiento.

Esta jerarquía permite que el usuario identifique rápidamente los puntos de entrada principales y acceda progresivamente a funcionalidades más específicas, reduciendo la carga cognitiva y facilitando la exploración del sistema.

#### Organización secuencial

El sistema presenta flujos claramente secuenciales en procesos críticos donde el usuario debe avanzar paso a paso:

###### Registro de usuario:
Registro → Solicitud de datos personales → Lifestyle Questions → Decisión de permitir uso de cámara →
(Sí → Escaneo facial / No → Creación de perfil) → Rutina personalizada generada → Dashboard.
###### Consulta dermatológica:
Consultar dermatólogo → Seleccionar tipo de acción (ver consultas pasadas / agendar nueva / unirse a consulta) →
Selección de fecha → Confirmación → Pago → Ejecución de consulta.

Estos flujos aseguran que el usuario complete correctamente procesos complejos mediante una guía estructurada, minimizando errores y mejorando la usabilidad.

#### Uso de nodos de decisión (decisiones del usuario)

Dentro de los flujos secuenciales se integran puntos de decisión que representan elecciones clave del usuario:

Permitir o no el uso de la cámara (impacta directamente en la personalización).
Aplicación de filtros en búsqueda de productos o tiendas.
Cancelación o continuación de procesos (como citas o consultas).

Estos nodos permiten modelar escenarios alternativos dentro del sistema, asegurando que la experiencia contemple tanto caminos principales como situaciones excepcionales, manteniendo coherencia en la navegación.

#### Organización matricial

El sistema incorpora conexiones transversales entre módulos que permiten al usuario navegar de forma no lineal según su contexto:

Desde el Dashboard se puede acceder tanto a funcionalidades de cuidado (Skin Care) como a consultas médicas o perfil.
Desde los módulos de consulta, el usuario puede alternar entre historial, nuevas citas y comunicación directa.
La exploración de productos y tiendas permite múltiples rutas de acceso mediante búsqueda, filtros y ubicación.

Esta estructura matricial complementa la jerarquía principal, ofreciendo mayor flexibilidad sin romper la lógica del sistema.

#### Categorización del contenido

El contenido se organiza mediante distintos esquemas según el contexto de uso:

###### Por audiencia:
Esta vista está orientada a usuarios finales (jóvenes adultos), diferenciándose claramente de la vista profesional.
Por tópicos:
Las funcionalidades se agrupan en secciones como Skin Care, Consultas, Navegación, Perfil y Búsqueda.
###### Cronológica:
Aplicada en historial de consultas, chats y seguimiento de interacciones pasadas.
###### Alfabética:
Utilizada en listas como productos, dermatólogos o tiendas, facilitando la búsqueda directa.



<p align = "center">
<img src="assets/img/organization-jovenes.png" alt="jovenes-system" width="500"/>


### Segmento 2: Dermatólogos certificados

La aplicación Bloomie, en su versión dirigida a dermatólogos certificados, está estructurada bajo un sistema de organización jerárquico, secuencial y matricial, diseñado para optimizar la gestión clínica, facilitar el acceso a la información de pacientes y asegurar una navegación clara y orientada a tareas profesionales. Esta estructura responde directamente a los flujos representados en el sistema, donde el dermatólogo transita desde procesos de validación profesional hacia un entorno centralizado de trabajo clínico.

##### Organización jerárquica

El contenido se organiza mediante una estructura jerárquica top-down, claramente evidenciada en el flujo del sistema.

Nivel 1 – Acceso principal:
Onboarding, Registro, Inicio de sesión y Dashboard.
Nivel 2 – Módulos principales (desde Dashboard):
Navigation, Home, Skin Care, Consultar IA, Perfil, Analytics, Appointments and Consultations, Treatment Plans y My Patients.
Nivel 3 – Submódulos y acciones específicas:
En Appointments and Consultations:
consultas pasadas, citas agendadas, lista de dermatólogos disponibles, selección de fecha y pago de consulta.
En My Patients:
lista de pacientes, acceso a detalles, notas y diagnóstico.
En Treatment Plans:
creación y edición de planes de tratamiento.
En Analytics:
visualización de estadísticas de pacientes.
En Perfil:
configuración de información personal, cambio de foto, credenciales, seguridad y favoritos.

Esta jerarquía permite organizar las funcionalidades en función de la prioridad clínica, asegurando que las tareas más frecuentes estén accesibles desde el Dashboard y que la información se despliegue progresivamente según el contexto de uso.

##### Organización secuencial

El sistema presenta flujos secuenciales en procesos clave que requieren validación o seguimiento paso a paso:

Registro profesional:
Registro → Solicitud de datos personales → Professional registration → Validación de cuenta → Creación de perfil → Dashboard.
Gestión de consultas:
Appointments and Consultations → Selección de acción (ver consultas pasadas / agendar nueva / citas programadas) →
selección de fecha → confirmación → pago → ejecución de consulta.
Gestión de pacientes:
My Patients → Lista de pacientes → Selección de paciente → acceso a detalles / notas / diagnóstico.

Estos flujos aseguran que el dermatólogo pueda realizar tareas clínicas de forma estructurada, reduciendo errores y garantizando la correcta gestión de la información.

##### Uso de nodos de decisión

Dentro de los flujos se integran puntos de decisión que permiten modelar distintas situaciones dentro del sistema:

Cancelación o continuación de citas o consultas.
Aplicación de filtros en la búsqueda de información (pacientes, consultas).
Selección de acciones dentro de módulos clínicos (por ejemplo, elegir entre ver historial o gestionar nuevas citas).

Estos nodos permiten representar escenarios alternativos dentro de los procesos, asegurando que el sistema sea flexible y responda a diferentes necesidades del profesional sin perder coherencia estructural.

##### Organización matricial

El sistema incorpora conexiones transversales entre módulos, permitiendo al dermatólogo moverse de forma flexible entre distintas funcionalidades:

Desde Appointments and Consultations, se puede acceder a distintas acciones como historial, nuevas citas o gestión de agenda.
Desde My Patients, el dermatólogo puede navegar entre información detallada, notas clínicas y diagnósticos sin salir del contexto del paciente.
Desde el Dashboard, se accede directamente a múltiples módulos según la tarea a realizar, sin necesidad de seguir un único flujo lineal.

Esta organización matricial mejora la eficiencia del trabajo clínico, permitiendo cambios de contexto rápidos y una navegación más dinámica.

##### Categorización del contenido

El contenido se organiza mediante distintos esquemas según el contexto de uso:

Por audiencia:
Esta vista está dirigida exclusivamente a dermatólogos, diferenciándose de la versión para usuarios finales mediante funcionalidades, terminología y estructura orientadas a la práctica clínica.
Por tópicos:
Las funcionalidades se agrupan en módulos como Analytics, Pacientes, Consultas, Tratamientos, Perfil y Navegación.
Cronológica:
Aplicada en consultas pasadas, citas programadas y seguimiento de pacientes, organizando la información según fechas.
Alfabética:
Utilizada en listas de pacientes o registros, facilitando la búsqueda rápida de información específica.


<p align = "center">
<img src="assets/img/organization-dermatologos.png" alt="dermatologos-system" width="500"/>

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

- Dashboard
<p align = "center">
<img src="assets/img/landing/LandingPage 3.png" alt="dermatologos-system" width="500"/>

- Information
<p align = "center">
<img src="assets/img/landing/LandingPage 1.png" alt="dermatologos-system" width="500"/>

- Pricing 
<p align = "center">
<img src="assets/img/landing/landingpage-5.png" alt="dermatologos-system" width="500"/>

- Needing
<p align = "center">
<img src="assets/img/landing/landingpage-4.png" alt="dermatologos-system" width="500"/>


## 4.4. Web Applications UX/UI Design

Esta sección incluye secciones internas donde se presenta y explica la propuesta
visual y de interacción para las aplicaciones que constituyen la experiencia de
usuario con los productos digitales.

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

1) <strong>Wireflow 1:</strong> Registro básico
- User goal: 
<br> Como joven adulto, quiero registrarme en Bloomie.

<br><strong>User Story asociada: </br></strong>
US01 - Como joven adulto, quiero registrarme con mis datos personales para crear una cuenta y acceder a Bloomie.

<p align = "center">
<img src="assets/img/landing/wireflow-1-app.png" alt="wireflow app" width="550"/>

<p align = "center">
<img src="assets/img/landing/wireflow-1-web.png" alt="wireflow app" width="550"/>


2) <strong>Wireflow 2:</strong> Completar perfil básico de piel
- User goal: 
<br> Como joven adulto, quiero completar mi perfil básico de peil.

<br><strong>User Story asociada: </br></strong>
US02 - Como joven adulto, quiero completar un cuestionario inicial de hábitos y condiciones de piel en mi primer ingreso para que la aplicación configure diagnósticos y rutinas personalizadas.

<p align = "center">
<img src="assets/img/landing/wireflow-2-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-2-web.png" alt="wireflow app" width="550"/>

3) <strong>Wireflow 3:</strong> Escaneo facial con cámara
- User goal: 
<br> Como joven adulto, quiero realizar un escaneo facial con cámara.

<br><strong>User Story asociada: </br></strong>
US03 - Como joven adulto, quiero realizar un escaneo facial moviendo mi cabeza frente a la cámara para que la aplicación capture imágenes desde diferentes ángulos y obtenga un diagnóstico preciso de mi tipo de piel.

<p align = "center">
<img src="assets/img/landing/wireflow-3-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-3-web.png" alt="wireflow app" width="550"/>



4) <strong>Wireflow 4:</strong> Diagnóstico preliminar automático

- User goal: 
<br> Como joven adulto, quiero recibir un diagnóstico preliminar.

<br><strong>User Story asociada: </br></strong>
US04 - Como joven adulto, quiero recibir un reporte preliminar generado por la inteligencia artificial después del escaneo facial para conocer el estado de mi piel y entender qué tipo de cuidados necesito.

<p align = "center">
<img src="assets/img/landing/wireflow-4-appl.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-4-web.png" alt="wireflow app" width="550"/>

5) <strong>Wireflow 5:</strong> Generar rutina personalizada con productos

- User goal: 
<br> Como joven adulto, quiero generar una rutina personalizada.

<br><strong>User Story asociada: </br></strong>
US05 - Como joven adulto, quiero recibir una rutina personalizada con productos específicos basados en mi diagnóstico de piel para seguir un tratamiento adecuado.

<p align = "center">
<img src="assets/img/landing/wireflow-5-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-5-web.png" alt="wireflow app" width="550"/>
</br>

6) <strong>Wireflow 6:</strong> Adaptar rutina mediante reemplazo de productos

- User goal: 
<br> Como joven adulto, quiero adaptar mi rutina mediante reemplazo de productos

<br><strong>User Story asociada: </br></strong>
US06 - Como joven adulto, quiero modificar los productos sugeridos en mi rutina para adaptarlos a mis necesidades o disponibilidad.

<p align = "center">
<img src="assets/img/landing/wireflow-6-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-6-web.png" alt="wireflow app" width="550"/>
</br>

7) <strong>Wireflow 7:</strong> Recordatorios de rutina

- User goal: 
<br> Como joven adulto, quiero tener recordatorios de rutina.

<br><strong>User Story asociada: </br></strong>
US07 - Como joven adulto, quiero recibir recordatorios para cumplir con mi rutina de cuidado de la piel y mantener constancia.

<p align = "center">
<img src="assets/img/landing/wireflow-7-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-7-web.png" alt="wireflow app" width="550"/>
</br>

8) <strong>Wireflow 8:</strong> Explorar catálogo de productos con filtros

- User goal: 
<br> Como joven adulto, quiero explorar catálogo de productos con filtros.

<br><strong>User Story asociada: </br></strong>
US08 - Como joven adulto, quiero explorar un catálogo de productos y aplicar filtros para encontrar opciones relevantes a mis necesidades.

<p align = "center">
<img src="assets/img/landing/wireflow-8-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-8-web.png" alt="wireflow app" width="550"/>
</br>

9) <strong>Wireflow 9:</strong> Evaluar compatibilidad de productos

- User goal: 
<br> Como joven adulto, quiere evaluar compatibilidad de productos.

<br><strong>User Story asociada: </br></strong>
US09 - Como joven adulto, quiero conocer la compatibilidad de un producto para tomar decisiones informadas.

<p align = "center">
<img src="assets/img/landing/wireflow-9-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-9-web.png" alt="wireflow app" width="550"/>
</br>

10) <strong>Wireflow 10:</strong> Asistente virtual de skincare

- User goal: 
<br> Como joven adulto, quiero un asistente virtual de skincare.

<br><strong>User Story asociada: </br></strong>
US10 - Como joven adulto, quiero consultar dudas sobre productos, rutinas o ingredientes para recibir orientación inmediata.

<p align = "center">
<img src="assets/img/landing/wireflow-10-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-10-web.png" alt="wireflow app" width="550"/>
</br>

11) <strong>Wireflow 11:</strong> Explorar mapa de tiendas y productos

- User goal: 
<br> Como joven adulto, quiero explorar mapas de tiendas y productos.

<br><strong>User Story asociada: </br></strong>
US11 - Como joven adulto, quiero visualizar en un mapa interactivo tiendas cercanas donde pueda encontrar productos para facilitar su compra.

<p align = "center">
<img src="assets/img/landing/wireflow-11-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-11-web.png" alt="wireflow app" width="550"/>
</br>

12) <strong>Wireflow 12:</strong> Listar dermatólogos para agendar

- User goal: 
<br> Como joven adulto, quiero listar dematólogos para agendar.

<br><strong>User Story asociada: </br></strong>
US12 - Como joven adulto, quiero visualizar una lista de dermatólogos con información relevante para elegir a quién agendar una consulta.

<p align = "center">
<img src="assets/img/landing/wireflow-12-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-12-web.png" alt="wireflow app" width="550"/>
</br>

13) <strong>Wireflow 13:</strong> Realizar pago de consulta dermatológica

- User goal: 
<br> Como joven adulto, quiero realizar el pago de una consulta.

<br><strong>User Story asociada: </br></strong>
US13 - Como joven adulto, quiero realizar el pago de una consulta dermatológica para confirmar mi cita.

<p align = "center">
<img src="assets/img/landing/wireflow-13-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-13-web.png" alt="wireflow app" width="550"/>
</br>

14) <strong>Wireflow 14:</strong> Cancelar cita dermatológica

- User goal: 
<br> Como joven adulto, quiero cancelar mi cita dermatológica.

<br><strong>User Story asociada: </br></strong>
US14 - Como joven adulto, quiero cancelar una cita programada para gestionar cambios en mi disponibilidad.

<p align = "center">
<img src="assets/img/landing/wireflow-14-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-14-web.png" alt="wireflow app" width="550"/>
</br>

15) <strong>Wireflow 15:</strong> Registrar cumplimiento de rutina diaria

- User goal: 
<br> Como joven adulto, quiero registrar el cumplimento de mi rutina.

<br><strong>User Story asociada: </br></strong>
US15 - Como joven adulto, quiero marcar si completé mi rutina diaria para llevar un seguimiento de mi progreso.

<p align = "center">
<img src="assets/img/landing/wireflow-15-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-15-web.png" alt="wireflow app" width="550"/>
</br>

16) <strong>Wireflow 16:</strong> Visualizar progreso en skin trackera
- User goal: 
<br> Como joven adulto, quiero visualizar mi progreso en skin trackera

<br><strong>User Story asociada: </br></strong>
US16 - Como joven adulto, quiero visualizar métricas de mi progreso para entender mi constancia y evolución en el cuidado de mi piel.

<p align = "center">
<img src="assets/img/landing/wireflow-16-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-16-web.png" alt="wireflow app" width=git"550"/>
</br>


17) <strong>Wireflow 17:</strong> Seleccionar plan de suscripción

- User goal: 
<br> Como joven adulto, quiero seleccionar mi plan de suscripción

<br><strong>User Story asociada: </br></strong>
US17 - Como joven adulto, quiero seleccionar un plan de suscripción para acceder a las funcionalidades de la aplicación.

<p align = "center">
<img src="assets/img/landing/wireflow-18-app.png" alt="wireflow app" width="550"/>
</br>

<p align = "center">
<img src="assets/img/landing/wireflow-17-web.png" alt="wireflow app" width="550"/>
</br>

18) <strong>Wireflow 18:</strong> Realizar pago de suscripción. 

- User goal: 
<br> Como joven adulto, quiero realizar mi pago de suscripción

<br><strong>User Story asociada: </br></strong>
US18 - Como joven adulto, quiero pagar un plan de suscripción para acceder a la aplicación.

<p align = "center">
<img src="assets/img/landing/wireflow-17-app.png" alt="wireflow app" width="550"/>
</br>
<p align = "center">
<img src="assets/img/landing/wireflow-18-web.png" alt="wireflow app" width="550"/>
</br>


### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

Mock-up: Facial scanning with camera

![foto](assets/img/facial.png)


## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming

En esta sección se presenta el Design-Level EventStorming realizado para refinar el modelado del dominio de Bloomie a partir del Big Picture EventStorming. En esta etapa, el equipo profundizó en los principales flujos del negocio, identificando comandos, eventos de dominio, políticas, aggregates y bounded contexts con un mayor nivel de detalle.

A partir de este análisis, se definieron los bounded contexts más relevantes de la solución y las relaciones existentes entre ellos, buscando mantener coherencia con el dominio del problema y con la naturaleza de Bloomie como plataforma SaaS orientada a servicios.

Finalmente, se incluyen las capturas elaboradas en la herramienta colaborativa utilizada, las cuales evidencian el trabajo realizado por el equipo durante la sesión.

**Design Level Event Storming - Bloomie**

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Design-Level-Event-Storming-Bloomie.png" alt="Design Level Event Storming - Bloomie" width="500"/>
  </div> <br>

**Bounded Contexts**

Identity & Access Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Identity-&-Access-Context.png" alt="Identity & Access Context - Bloomie" width="500"/>
  </div> 

<br>
Skin Analysis Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Skin-Analysis-Context.png" alt="Skin Analysis Context - Bloomie" width="500"/>
  </div> 

<br>
Product Discovery Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Product-Discovery-Context.png" alt="Product Discovery Context - Bloomie" width="500"/>
  </div> 

<br>
Intelligent Support Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Intelligent-Support-Context.png" alt="Intelligent Support Context - Bloomie" width="500"/>
  </div> 

<br>
Dermatology Care Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Dermatology-Care-Context.png" alt="Dermatology Care Context - Bloomie" width="500"/>
  </div> 

<br>
Routine Management Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Routine-Management-Context.png" alt="Routine Management Context - Bloomie" width="500"/>
  </div> 

<br>
Payments Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Payments-Context.png" alt="Payments Context - Bloomie" width="500"/>
  </div> 

<br>
Subscription Context <br>

  <div>
    <img src="assets/img/Design-Level-Event-Storming/Subscription-Context.png" alt="Subscription Context - Bloomie" width="500"/>
  </div>

### 4.6.2. Software Architecture Context Diagram

 <img src="assets/img/contexto.png" alt="contexto" width="500"/>

### 4.6.3. Software Architecture Container Diagrams

 <img src="assets/img/contenedores.png" alt="contenedores" width="500"/>

### 4.6.4. Software Architecture Components Diagrams

 <img src="assets/img/component-frontend.png" alt="componentes" width="500"/>

 <img src="assets/img/component-backend.png" alt="componentes" width="500"/>
 


## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<img src="assets/img/Class-Diagram/Dermatology-Payments.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/Class-Diagram/Identity-Skin.png" alt="Class Diagrams" width="1000"/> <br>
<img src="assets/img/Class-Diagram/Intelligent-Dermatology.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/Class-Diagram/Payments-Subscription.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/Class-Diagram/ProductDiscovery-Routine.png" alt="Class Diagram" width="1000"/> <br>
<img src="assets/img/Class-Diagram/Skin-Routine.png" alt="Class Diagram" width="1000"/> <br>

## 4.8. Database Design

### 4.8.1. Database Diagrams

<img src="assets/img/db-diagram.jpg" alt="DB Diagram" width="1000"/> <br>

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas y tecnologías utilizadas por el equipo para el desarrollo colaborativo del producto digital, abarcando actividades de gestión de proyecto, diseño UX/UI, desarrollo de software, pruebas, documentación y despliegue. Estas herramientas permiten asegurar consistencia, trazabilidad y eficiencia durante todo el ciclo de vida del proyecto.

A continuación, se presenta la configuración del entorno de desarrollo de Bloomie:

| **Herramienta / Tecnología** | **Propósito en el Proyecto**                                                             | **Tipo**       | **Ruta de Acceso / Descarga**                                  |
| ---------------------------- | ---------------------------------------------------------------------------------------- | -------------- | -------------------------------------------------------------- |
| GitHub                       | Control de versiones, gestión de repositorios y colaboración mediante commits y branches | SaaS           | [https://github.com](https://github.com)                       |
| Trello                       | Gestión de tareas y seguimiento del Sprint Backlog mediante tableros Kanban              | SaaS           | [https://trello.com](https://trello.com)                       |
| Figma                        | Diseño de interfaces UI (wireframes, mockups y prototipos)                               | SaaS           | [https://figma.com](https://figma.com)                         |
| UXPressia                    | Elaboración de artefactos UX como User Personas, Journey Maps y Empathy Maps             | SaaS           | [https://uxpressia.com](https://uxpressia.com)                 |
| Postman                      | Pruebas de endpoints RESTful y validación de servicios backend                           | Desktop / SaaS | [https://www.postman.com](https://www.postman.com)             |
| Visual Studio Code           | Entorno de desarrollo para frontend y backend                                            | Desktop        | [https://code.visualstudio.com](https://code.visualstudio.com) |
| Angular Framework            | Desarrollo de aplicaciones web frontend bajo arquitectura SPA                            | Framework      | [https://angular.io](https://angular.io)                       |
| HTML5, CSS3, JavaScript      | Tecnologías base para estructura, estilos e interacción en frontend                      | Lenguajes      | [https://developer.mozilla.org](https://developer.mozilla.org) |
| MySQL                        | Sistema de gestión de base de datos relacional para persistencia de datos                | DBMS           | [https://www.mysql.com](https://www.mysql.com)                 |
| Vercel                       | Plataforma de despliegue para aplicaciones frontend (Landing Page y Web App)             | SaaS (Cloud)   | [https://vercel.com](https://vercel.com)                       |
| Markdown (GitHub README) | Documentación técnica del proyecto y del informe en formato Markdown | SaaS | [https://www.markdownguide.org](https://www.markdownguide.org) |

El equipo adopta un enfoque basado en herramientas open-source y plataformas SaaS, permitiendo el trabajo colaborativo en tiempo real y el acceso remoto a los recursos del proyecto. GitHub actúa como eje central para la gestión del código fuente, integrándose con Vercel para automatizar el despliegue continuo del frontend. 

Por otro lado, herramientas como Figma y UXPressia facilitan la construcción de artefactos de diseño centrados en el usuario, mientras que Trello permite organizar el trabajo en Sprints siguiendo principios ágiles. Postman se utiliza para validar la comunicación con los servicios RESTful, asegurando el correcto funcionamiento de los endpoints desarrollados.

Esta configuración permite mantener una alineación entre diseño, desarrollo, pruebas y despliegue, asegurando una entrega continua de valor en cada iteración del proyecto Bloomie.

### 5.1.2. Source Code Management

En esta sección se describen las estrategias, herramientas y convenciones utilizadas por el equipo para la gestión del código de Bloomie, asegurando trazabilidad, control de versiones y colaboración efectiva durante el desarrollo del producto digital.

**Repositorios del Proyecto** <br>
El equipo utiliza GitHub como plataforma principal para el control de versiones, manteniendo repositorios independientes para cada componente de la solución:

- Report:
  https://github.com/Bloomie-app/Bloomie-Report
- Landing Page:
  https://github.com/Bloomie-app/Bloomie-Landing-Page
- Frontend Web Application:
  https://github.com/Bloomie-app/Bloomie-Frontend
- Backend Web Services (RESTful API):
  https://github.com/Bloomie-app/Bloomie-Backend

Estos repositorios permiten gestionar de manera modular los distintos productos del sistema, facilitando el trabajo paralelo y la integración continua.

**Estrategia de Control de Versiones (GitFlow)**

El equipo adopta una estrategia basada en los principios de GitFlow, adaptada a la organización del proyecto académico. Esta estrategia permite mantener estabilidad en la rama principal y facilitar el desarrollo incremental de funcionalidades.

Se utilizan las siguientes ramas:

- **main:** <br>
  Contiene la versión estable y desplegable del producto.
- **develop:** <br>
  Rama de integración donde se consolidan los avances de desarrollo antes de ser promovidos a producción.
- **feature branches:** <br>
  Se utilizan para el desarrollo de funcionalidades o entregables específicos. En este proyecto, las ramas feature están organizadas por capítulos del informe:
    - feature/chapter-01
    - feature/chapter-02
    - feature/chapter-03
    - feature/chapter-04
    - feature/chapter-05

Cada rama feature se desarrolla de forma independiente y posteriormente se integra en la rama develop.

**Convenciones de Nombres de Ramas**

Se establece las siguientes convenciones:

- **feature/*:** para desarrollo de funcionalidades o secciones específicas <br>
  Ejemplo: feature/chapter-03
- **release/*:** para preparación de versiones estables <br>
  Ejemplo: release/v1.0.0
- **hotfix/*:** para correcciones urgentes en producción <br>
  Ejemplo: hotfix/fix-login-error

Estas convenciones permiten identificar rápidamente el propósito de cada rama y mantener una estructura organizada del repositorio.

**Conventional Commits**

Para los mensajes de commit, el equipo adopta el estándar Conventional Commits, lo cual permite mantener consistencia y facilitar la comprensión del historial de cambios.

Se utilizan los siguientes prefijos:

- **feat:** nueva funcionalidad
- **fix:** corrección de errores
- **docs:** cambios en documentación
- **style:** cambios de formato (no funcionales)
- **refactor:** mejoras internas sin cambio de funcionalidad
- **test:** adición o modificación de pruebas

**Semantic Versioning**

El equipo aplica Semantic Versioning 2.0.0 para el versionado de releases, utilizando el formato:

_MAJOR.MINOR.PATCH_ <br>

- **MAJOR:** cambios incompatibles con versiones anteriores
- **MINOR:** nuevas funcionalidades compatibles
- **PATCH:** correcciones de errores

Ejemplo: <br>
  v1.0.0 : primera versión estable del producto

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

Para la configuración de despliegue de la solución, el equipo ha definido el uso de Vercel como plataforma principal para publicar los productos web del proyecto. En esta etapa, la solución contempla el despliegue de la Landing Page y la Frontend Web Application desde sus respectivos repositorios de GitHub, permitiendo que cada cambio integrado a la rama principal pueda generar una versión publicada de forma automática.

Para el entregable TB1, también se considera el uso de Microsoft Azure App Service para desplegar el servicio simulado de datos basado en JSON Server. Este servicio funciona como una Mock API temporal, permitiendo que la aplicación frontend consuma endpoints en la nube en lugar de depender de un servidor local. De esta manera, se puede validar la integración entre la aplicación web y una ruta pública de API durante la revisión del entregable.

**Productos digitales y plataformas de despliegue**

| Producto digital         | Plataforma de despliegue | Propósito                                                   |
| ------------------------ | ------------------------ | ----------------------------------------------------------- |
| Landing Page             | Vercel                   | Publicar el sitio informativo del producto.                 |
| Frontend Web Application | Vercel                   | Publicar la aplicación web principal.                       |
| Mock API / JSON Server   | Azure App Service        | Exponer temporalmente los endpoints usados por el frontend. |

**Despliegue de Landing Page en Vercel**

El despliegue de la Landing Page se realiza desde el repositorio correspondiente en GitHub. Para ello, se conecta el repositorio con Vercel, se configura la rama principal como rama de producción y se ejecuta el proceso de despliegue automático.

<u>Pasos principales:</u>

1. Subir el proyecto de la Landing Page al repositorio de GitHub.
2. Importar el repositorio desde Vercel.
3. Configurar el comando de construcción, si corresponde.
4. Publicar la aplicación.
5. Validar la URL generada por Vercel.

**Despliegue de Frontend Web Application en Vercel**

La aplicación web frontend también se despliega en Vercel desde su repositorio de GitHub. Esta aplicación consume la API mediante una variable de entorno o archivo de configuración de producción, donde se define la URL base del servicio.

En desarrollo, la aplicación puede consumir JSON Server localmente. Para producción, esta URL se reemplaza por la ruta pública del servicio desplegado en Azure.

De esta forma, el frontend publicado en Vercel puede conectarse a la MockAPI alojada en Azure.

<u>Pasos principales:</u>

1. Subir el proyecto del Frontend Web Application al repositorio de GitHub.
2. Importar el repositorio desde Vercel.
3. Configurar el comando de construcción, si corresponde.
4. Publicar la aplicación.
5. Validar la URL generada por Vercel.

**Despliegue de Mock API con JSON Server en Azure**

Para la TB1, el equipo despliega una Mock API basada en JSON Server utilizando Azure App Service. Esta API contiene los archivos necesarios para simular los endpoints del sistema, como db.json y routes.json.

**Flujo general de despligue (TB1)**

El flujo de despliegue definido por el equipo es el siguiente:

1. Los integrantes desarrollan cambios en ramas de trabajo.
2. Los cambios se integran al repositorio mediante Pull Requests.
3. La rama principal activa el despliegue automático en Vercel o Azure.
4. Vercel publica la Landing Page y la Frontend Web Application.
5. Azure App Service publica la Mock API basada en JSON Server.
6. El equipo valida que el frontend consuma correctamente los endpoints publicados.

**Consideración final**

En esta etapa del proyecto, JSON Server se utiliza únicamente como una solución temporal para simular los Web Services. Para entregas posteriores, esta Mock API podrá ser reemplazada por una RESTful API desarrollada internamente (backend), manteniendo la misma estructura de endpoints para reducir cambios en el frontend.

<div align="center">
<img src="assets/img/deployment-configuration/vercel-logo.png" alt="vercel logo" height="100"/>
<img src="assets/img/deployment-configuration/microsoft-azure.png" alt="microsoft azure logo" height="100"/>
</div>

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1
| Campo | Detalle                                                                                                                                                                                                                                                                                                               |
|---|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint #** | Sprint 1                                                                                                                                                                                                                                                                                                              |
| **Sprint Planning Date** | 13 de abril de 2026                                                                                                                                                                                                                                                                                                   |
| **Time** | 9:00 p.m. – 11:00 p.m.                                                                                                                                                                                                                                                                                             |
| **Location** | Reunión virtual vía Discord                                                                                                                                                                                                                                                                                           |
| **Prepared By** | Ramirez Ruiz, Nickolas y Asmat Alminco, Martin                                                                                                                                                                                                                                                                                    |
| **Attendees** | Asmat Alminco, Martin Alejandro · Contreras Torres, Arturo Valentino · Gallardo Morales, Carla Alejandra · Mechan Montenegro, Luciana Carolina · Ramirez Ruiz, Nickolas                                                                                                                                               |
| **Sprint 1 – 0 Review Summary** | No aplica. Este es el primer sprint del proyecto. No existen reviews previas.                                                                                                                                                                                                                                         |
| **Sprint 1 – 0 Retrospective Summary** | No aplica. Este es el primer sprint del proyecto. No existen retrospectivas previas.                                                                                                                                                                                                                                  |
| **Sprint 1 Goal** | Nuestro enfoque está en validar nuestra propuesta de valor a través de una landing page. Creemos que esto brinda claridad y confianza a jóvenes adultos que buscan soluciones confiables para el cuidado de la piel. Esto se confirmará cuando al menos el 10% de los visitantes se registren en nuestra plataforma y permanezcan más de 5 minutos en la página. |
| **Sprint 1 Velocity** | 10 story points                                                                                                                                                                                                                                                                                                       |
| **Sum of Story Points** | 8 story points                                                                                                                                                                                                                                                                                                       |
#### 5.2.1.2. Aspect Leaders and Collaborators

| Aspecto / Sección | User Story | Líder | Colaborador |
|---|---|---|---|
| Propuesta de valor | US34 | Gallardo Morales, Carla | Mechan Montenegro, Luciana |
| Funcionamiento del servicio | US35 | Contreras Torres, Arturo | Ramirez Ruiz, Nickolas |
| Funcionalidades del producto | US36 | Asmat Alminco, Martin | Contreras Torres, Arturo |
| Navegación entre secciones | US38 | Mechan Montenegro, Luciana | Gallardo Morales, Carla |
| Comparar planes de suscripción | US37 | Ramirez Ruiz, Nickolas | Asmat Alminco, Martin |

---
#### 5.2.1.3. Sprint Backlog 1

El Sprint 1 tuvo como objetivo implementar y desplegar la Landing Page de Bloomie con todas sus secciones informativas. A continuación se presenta el board de seguimiento utilizado durante el sprint, junto con la tabla de control de estado de las tareas.

[Sprint-Backlog-1](https://trello.com/b/PA2Tjn3g/sprint-1-bloomie)

URL del board: https://trello.com/b/PA2Tjn3g/sprint-1-bloomie

| User Story ID | Título | Task ID | Descripción de tarea | Estimación | Responsable | Estado |
|---|---|---|---|---|---|---|
| US34 | Comprender la propuesta de valor | T-01 | Diseñar e implementar sección Hero con headline, subheadline y CTA | 4h | Gallardo, Carla | Done |
| US34 | Comprender la propuesta de valor | T-02 | Implementar sección de beneficios con íconos y textos descriptivos | 3h | Mechan, Luciana | Done |
| US35 | Comprender el funcionamiento del servicio | T-03 | Implementar sección "Cómo funciona" con pasos ilustrados (registro, escaneo, rutina) | 4h | Contreras, Arturo | Done |
| US35 | Comprender el funcionamiento del servicio | T-04 | Agregar animaciones o transiciones de desplazamiento en la sección | 2h | Ramirez, Nickolas | Done |
| US36 | Explorar funcionalidades del producto | T-05 | Implementar sección de features con cards: análisis IA, rutinas, seguimiento, dermatólogos | 4h | Asmat, Martin | Done |
| US36 | Explorar funcionalidades del producto | T-06 | Aplicar estilos responsivos a las cards de funcionalidades | 2h | Contreras, Arturo | Done |
| US38 | Navegar entre secciones del sitio | T-07 | Implementar navbar fijo con scroll suave a cada sección y logo de Bloomie | 3h | Mechan, Luciana | Done |
| US38 | Navegar entre secciones del sitio | T-08 | Implementar footer con links, redes sociales y copyright | 2h | Gallardo, Carla | Done |
| US37 | Comparar planes de suscripción | T-09 | Diseñar e implementar sección de pricing con tabla comparativa de planes | 4h | Ramirez, Nickolas | Done |
| US37 | Comparar planes de suscripción | T-10 | Agregar botón CTA por plan con enlace a registro/suscripción | 2h | Asmat, Martin | Done |


#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint se desarrolló la estructura de la landing page de Bloomy orientada a dermatólogos, incluyendo secciones clave como propuesta de valor, descripción del producto, funcionalidades principales, modelo de suscripción y servicios modulares (white-label). Asimismo, se aplicó un sistema visual consistente alineado con la identidad de la marca, priorizando la claridad de la información y la conversión del usuario mediante llamados a la acción estratégicos.

| Repository | Branch                         | Commit Message                                          | Commit Message Body                                                                                     |
| ---------- | ------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| BloomyApp  | feature/landing-dermatologists | feat: add landing hero section for dermatologists       | Includes main value proposition, CTA and visual identity aligned with dermatology users                 |
| BloomyApp  | feature/landing-dermatologists | feat: implement "About the Product" section             | Describes Bloomy’s purpose, benefits and problem-solution fit for dermatologists                        |
| BloomyApp  | feature/landing-dermatologists | feat: add features section for dermatology workflow     | Highlights core functionalities such as patient tracking, skincare analysis and digital recommendations |
| BloomyApp  | feature/landing-dermatologists | feat: implement pricing section with subscription model | Defines monthly subscription tiers and value differentiation between plans                              |
| BloomyApp  | feature/landing-dermatologists | feat: add modular services (white-label system) section | Presents customizable modules and                                                                       |





Durante el Sprint se desarrolló la estructura de la landing page de Bloomy orientada a dermatólogos, incluyendo secciones clave como propuesta de valor, descripción del producto, funcionalidades principales, modelo de suscripción y servicios modulares (white-label). Asimismo, se aplicó un sistema visual consistente alineado con la identidad de la marca, priorizando la claridad de la información y la conversión del usuario mediante llamados a la acción estratégicos.

| Repository | Branch                         | Commit Message                                          | Commit Message Body                                                                                     |
| ---------- | ------------------------------ | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| BloomyApp  | feature/landing-dermatologists | feat: add landing hero section for dermatologists       | Includes main value proposition, CTA and visual identity aligned with dermatology users                 |
| BloomyApp  | feature/landing-dermatologists | feat: implement "About the Product" section             | Describes Bloomy’s purpose, benefits and problem-solution fit for dermatologists                        |
| BloomyApp  | feature/landing-dermatologists | feat: add features section for dermatology workflow     | Highlights core functionalities such as patient tracking, skincare analysis and digital recommendations |
| BloomyApp  | feature/landing-dermatologists | feat: implement pricing section with subscription model | Defines monthly subscription tiers and value differentiation between plans                              |
| BloomyApp  | feature/landing-dermatologists | feat: add modular services (white-label system) section | Presents customizable modules and                                                                       |




#### 5.2.1.5. Execution Evidence for Sprint Review
En esta sección se detallan los procesos realizados para el despliegue de la solución durante el Sprint 1.La prioridad principal del sprint fue poner en producción la versión inicial de la Landing Page, lo que permite modelar de forma más adecuada cómo nuestros segmentos objetivos esperan que se visualice de forma profesional.

La landing page fue desarrollada en visual studio code con aplicación de javascript, CSS y HTML. Partimos de esta sintaxis por la gran variedad de apoyo que tienen como lenguajes debido a su robustez.

<p align = "center">
Desarrollo de la landing (Editor de código)


 <img src="assets/img/landing-codigo.png" alt="codigo_landing" width="650"/>  


Para el despliegue, se utilizó vercel, aprovechando su versatilidad como servicio gratuito para un despliegue seguro y rápido. El proceso consistió en los siguientes pasos estratégicos:

Luego, para el seguimiento de trabajo de cada integrante, utilizamos Github repository como herramienta de repositorio en la nube para un correcto manejo de flujo en el trabajo. Para ello, cada usuario debió revisar conceptos sobre GitFlow.

  <p align = "center">
  Vista Principal de la landing page
  <p align = "center">
 <img src="assets/img/landing-deploy.png" alt="deploy" width="650"/>

<p align = "center">
Apartado de suscripciones del modelo de negocio definido
<img src="assets/img/landing-pagos.png" alt="deploy-cod" width="650"/>

Se puede acceder a nuestra lading page ya deployada a través del siguiente enlace: https://bloomie-landing-page.vercel.app/index.html



#### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este Sprint se definieron y documentaron los endpoints necesarios para la gestión del perfil de usuario dentro de la aplicación. Aunque los servicios aún no se encuentran desplegados en un entorno productivo, se ha desarrollado su especificación utilizando OpenAPI, permitiendo validar la estructura de las solicitudes y respuestas, así como su integración futura con el frontend.


| Endpoint       | Método | Acción            | Descripción               | URL documentación   |
| -------------- | ------ | ----------------- | ------------------------- | ------------------- |
| /profile       | GET    | Obtener perfil    | Retorna datos del usuario | localhost:3000/docs |
| /profile       | PUT    | Actualizar perfil | Actualiza nombre y correo | localhost:3000/docs |
| /profile/photo | PATCH  | Cambiar foto      | Actualiza avatar          | localhost:3000/docs |


#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Conocimiento sobre vercel y como integrarlo: Se tuvo que indagar cómo utilizar vercel de forma adecuada para poder así agilizar procesos de front end.
Activación del Servicio: Se importó el formato nativo de html de modo que el vercel lo traduzca y por tanto, lo pueda desplegar.


#### 5.2.1.8. Team Collaboration Insights during Sprint

Durante el Sprint 1, el equipo mantuvo un flujo de trabajo altamente colaborativo y organizado, aplicando estrictamente la estrategia de control de versiones GitFlow. Para asegurar la calidad y revisión por pares, todo el desarrollo de la arquitectura, investigación de UX/UI y codificación de la Landing Page se trabajó en ramas independientes (feature branches). La integración del trabajo se realizó exclusivamente mediante Pull Requests hacia la rama develop, lo que fomentó la comunicación y revisión conjunta antes de consolidar los avances.

A continuación, se presentan los analíticos extraídos de GitHub (Insights) que evidencian la participación equitativa y constante de todos los miembros del equipo (Aspect Leaders y Collaborators) tanto en el repositorio principal de documentación como en el de la Landing Page.

##### Resumen de actividad del Sprint

<img src="assets/img/resumen.png" alt="resumen" width="400"/>