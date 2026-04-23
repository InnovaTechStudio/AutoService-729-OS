# Documentación del Trabajo Final - 1ASI0730 <!-- omit in toc -->

<div align="center">
  
![logo](docs/assets/upclogo.png)<br>
Universidad Peruana de Ciencias Aplicadas<br>
Facultad de Ingenería, Carrera de Ingeniería de Software<br>
**Ciclo:** 2026-10

**AV1 – Sprint Review**

**1ASI0730** Desarrollo de Aplicaciones Open Source<br>
**NRC:** 17952<br>
**Profesor:** Iván Robles Fernández<br>

**Nombre del startup:** InnovaTech<br>
**Nombre del producto:** AutoService<br>
Abril, 2026

#### Relación de integrantes <!-- omit in toc -->

  <table style="margin: auto;">
    <thead>
      <tr>
        <th style="text-align: left;">Código</th>
        <th style="text-align: left;">Apellidos y Nombres</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>U20251B991</td>
        <td>Aguilar Aguayo, Jeferson Renzo</td>
      </tr>
      <tr>
        <td>U202421866</td>
        <td>Lopez Monroy, Rodrigo Alfredo</td>
      </tr>
      <tr>
        <td>U20241D185</td>
        <td>Luis Miranda, Diego Andres</td>
      </tr>
      <tr>
        <td>U20241E299</td>
        <td>Mamani Vilca, Alan Jaivi</td>
      </tr>
      <tr>
        <td>U202319404</td>
        <td>Sanchez Cuadrado, Juan Antonio</td>
      </tr>
    </tbody>
  </table>

</div>

---

<br>
<br>
<br>

## Registro de Versiones del Informe <!-- omit in toc -->

<div align="center">
  <table style="margin: auto; text-align: center;">
    <thead>
      <tr>
        <th style="text-align: center;">Versión</th>
        <th style="text-align: center;">Fecha</th>
        <th style="text-align: center;">Autores</th>
        <th style="text-align: left;">Descripción de modificación</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>V1.0</td>
        <td>22/04/2026</td>
        <td>Aguilar Aguayo, Jeferson Renzo<br>Lopez Monroy, Rodrigo Alfredo<br>Luis Miranda, Diego Andres<br>Mamani Vilca, Alan Jaivi<br>Sanchez Cuadrado, Juan Antonio</td>
        <td>Elaboración de la primera entrega formal del proyecto (Capítulos I al V).<br> Incluye la definición del modelo de negocio (Lean UX),<br> levantamiento de requerimientos (Needfinding, EventStorming,<br> Product Backlog, User Stories) y el diseño del producto<br> (Arquitectura de Información, DDD, C4 Model y Wireframes UX/UI).<br> Asimismo, documenta la ejecución del Sprint 1, evidenciando<br> el despliegue de la Landing Page en GitHub Pages, la integración de<br> EmailJS y las métricas de colaboración del equipo utilizando GitFlow.</td>
      </tr>
      <!-- 
      <tr>
        <td>V2.0</td>
        <td>--/--/2026</td>
        <td>Aguilar Aguayo, Jeferson Renzo<br>Lopez Monroy, Rodrigo Alfredo<br>Luis Miranda, Diego Andres<br>Mamani Vilca, Alan Jaivi<br>Sanchez Cuadrado, Juan Antonio</td>
        <td style="text-align: left;"><i>Pendiente</i></td>
      </tr>
      <tr>
        <td>V3.0</td>
        <td>--/--/2026</td>
        <td>Aguilar Aguayo, Jeferson Renzo<br>Lopez Monroy, Rodrigo Alfredo<br>Luis Miranda, Diego Andres<br>Mamani Vilca, Alan Jaivi<br>Sanchez Cuadrado, Juan Antonio</td>
        <td style="text-align: left;"><i>Pendiente</i></td>
      </tr>
      <tr>
        <td>V4.0</td>
        <td>--/--/2026</td>
        <td>Aguilar Aguayo, Jeferson Renzo<br>Lopez Monroy, Rodrigo Alfredo<br>Luis Miranda, Diego Andres<br>Mamani Vilca, Alan Jaivi<br>Sanchez Cuadrado, Juan Antonio</td>
        <td style="text-align: left;"><i>Pendiente</i></td>
      </tr>
      -->
    </tbody>
  </table>
</div>

---

## Project Report Collaboration Insights <!-- omit in toc -->

* **URL del Repositorio de GitHub:** https://github.com/InnovaTechStudio/AutoService-729-OS
* **AV1:** - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

---

## Contenido <!-- omit in toc -->

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [Competitive Analysis Landscape](#competitive-analysis-landscape)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [Entrevista 1: Técnico Independiente](#entrevista-1-técnico-independiente)
    - [Entrevista 2: Técnico Independiente](#entrevista-2-técnico-independiente)
    - [Entrevista 3: Técnico Independiente](#entrevista-3-técnico-independiente)
    - [Entrevista 4: Administrador de Taller Automotriz](#entrevista-4-administrador-de-taller-automotriz)
    - [Entrevista 5: Administrador y Encargado de Logística de Taller Automotriz](#entrevista-5-administrador-y-encargado-de-logística-de-taller-automotriz)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [User Persona 1: Mechanic](#user-persona-1-mechanic)
    - [User Persona 2: Workshop Manager](#user-persona-2-workshop-manager)
    - [User Persona 3: Vehicle Owner](#user-persona-3-vehicle-owner)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [Análisis del User Task Matrix](#análisis-del-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
      - [Journey Map 1: Mechanic](#journey-map-1-mechanic)
    - [Journey Map 2: Workshop Manager](#journey-map-2-workshop-manager)
    - [Journey Map 3: Vehicle Owner](#journey-map-3-vehicle-owner)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [Empathy Map 1: Mechanic](#empathy-map-1-mechanic)
    - [Empathy Map 2: Workshop Manager](#empathy-map-2-workshop-manager)
    - [Empathy Map 3: Vehicle Owner](#empathy-map-3-vehicle-owner)
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [Estructura del Flujo (Timeline)](#estructura-del-flujo-timeline)
    - [Leyenda de Elementos](#leyenda-de-elementos)
    - [Hotspots y Oportunidades de Mejora](#hotspots-y-oportunidades-de-mejora)
  - [2.5. Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. User Stories](#31-user-stories)
  - [3.4. Impact Mapping](#34-impact-mapping)
  - [3.5. Product Backlog](#35-product-backlog)
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
    - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
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
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [\[Pendiente\]](#pendiente)
- [Anexos](#anexos)

---

## Student Outcome

<div align="center">
  <table style="margin: auto; text-align: left;">
    <thead>
      <tr>
        <th>Criterio específico</th>
        <th>Acciones realizadas</th>
        <th>Conclusiones</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Comunica oralmente con efectividad a diferentes rangos de audiencia.</td>
        <td>
          <b>Aguilar Aguayo, Jeferson Renzo</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Lopez Monroy, Rodrigo Alfredo</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Luis Miranda, Diego Andres</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Mamani Vilca, Alan Jaivi</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Sanchez Cuadrado, Juan Antonio</b> AV1: (ACCIONES REALIZADAS)
        </td>
        <td>AV1: Pendiente (Grupal)</td>
      </tr>
      <tr>
        <td>Comunica por escrito con efectividad a diferentes rangos de audiencia.</td>
        <td>
          <b>Aguilar Aguayo, Jeferson Renzo</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Lopez Monroy, Rodrigo Alfredo</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Luis Miranda, Diego Andres</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Mamani Vilca, Alan Jaivi</b> AV1: (ACCIONES REALIZADAS)<br>
          <b>Sanchez Cuadrado, Juan Antonio</b> AV1: (ACCIONES REALIZADAS)
        </td>
        <td>AV1: Pendiente (Grupal)</td>
      </tr>
    </tbody>
  </table>
</div>

---

## Capítulo I: Introducción

### 1.1. Startup Profile

<p align="justify"> El Startup Profile presenta una visión general del equipo y de la propuesta de valor del proyecto, describiendo el enfoque de la solución, el contexto en el que se desarrolla y las capacidades del equipo de trabajo. Esta sección permite comprender la finalidad de la startup, así como el aporte de cada integrante en el desarrollo del sistema. </p>

#### 1.1.1. Descripción de la Startup

<p align="justify"> Nuestra startup tiene como objetivo desarrollar una plataforma web orientada a la gestión integral de talleres automotrices, permitiendo optimizar los procesos operativos, mejorar la organización interna y brindar mayor transparencia al cliente final. <br><br> La solución está dirigida principalmente a mecánicos independientes y talleres automotrices (PYMES), quienes actualmente enfrentan dificultades en la gestión de clientes, vehículos, órdenes de trabajo y seguimiento de servicios. A través de este sistema, se busca centralizar la información, digitalizar procesos y facilitar la comunicación entre el taller y el cliente. <br><br> La plataforma permitirá registrar clientes y vehículos, gestionar órdenes de trabajo, realizar seguimiento del estado del servicio en tiempo real, controlar pagos y generar historiales detallados por vehículo. Además, el sistema implementa un modelo SaaS (Software as a Service), donde los talleres pagan una suscripción mensual para acceder a funcionalidades avanzadas, mientras que los clientes finales pueden acceder gratuitamente para visualizar el estado de sus servicios. <br><br> De esta manera, la startup busca aportar valor tanto al taller, mejorando su eficiencia y control, como al cliente, incrementando la confianza y transparencia en el servicio automotriz. </p>

#### 1.1.2. Perfiles de integrantes del equipo

<div align="center">
  <table style="margin: auto; width: 100%; border-collapse: collapse; border: 1px solid #ddd;">
    <tbody>
      <!-- Integrante 1 -->
      <tr>
        <td style="padding: 20px; border: 1px solid #ddd; width: 70%; vertical-align: middle; text-align: left;">
          <strong>Aguilar Aguayo, Jeferson Renzo</strong><br><br>
          <i>Estudiante del quinto ciclo de Ing. de Software. mis conocimientos sobre lenguajes de programacion se centran en JS, CSS, HTML y MySQL. Mis fortalezas como parte de un equipo son el trabajo colaborativo, responsabilidad con las entregas de las partes del trabajo y creatividad en ideas de mejoras sobre el proyecto.</i>
        </td>
        <td style="padding: 10px; border: 1px solid #ddd; width: 30%; text-align: center; vertical-align: middle;">
          <img src="docs/assets/jeferson.png" alt="Jeferson Aguilar" width="150" style="border-radius: 10px; border: 1px solid #ccc;">
        </td>
      </tr>
      <!-- Integrante 2 -->
      <tr>
        <td style="padding: 20px; border: 1px solid #ddd; vertical-align: middle; text-align: left;">
          <strong>Lopez Monroy, Rodrigo Alfredo</strong><br><br>
          <i>Estudiante del quinto ciclo de Ing. de Software. Mis principales fortalezas son la capacidad de organización, manejo de tiempos y gestión del trabajo en equipo. Me encuentro en constante aprendizaje de distintas tecnologías y siempre busco trabajar de manera pulida y a consciencia.</i>
        </td>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: center; vertical-align: middle;">
          <img src="docs/assets/rodrigo.png" alt="Rodrigo Lopez" width="150" style="border-radius: 10px; border: 1px solid #ccc;">
        </td>
      </tr>
      <!-- Integrante 3 -->
      <tr>
        <td style="padding: 20px; border: 1px solid #ddd; vertical-align: middle; text-align: left;">
          <strong>Luis Miranda, Diego Andres</strong><br><br>
          <i>Estoy cursando el quinto ciclo de mi carrera. A lo largo de mi experiencia aprendí muchas cosas como ser una persona proactiva, perseverante y responsable. Tengo conocimientos programando en diferentes leguajes C++, python, JS, CSS, HTML, SQL. En la parte de frontend me gusta diseñar para entregar un producto atractivo. Mediante mi conocimiento sé que puedo aportar más de mis capacidades para presentar un buen proyecto en equipo <br></i>
        </td>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: center; vertical-align: middle;">
          <img src="docs/assets/diego.png" alt="Diego Luis" width="150" style="border-radius: 10px; border: 1px solid #ccc;">
        </td>
      </tr>
      <!-- Integrante 4 -->
      <tr>
        <td style="padding: 20px; border: 1px solid #ddd; vertical-align: middle; text-align: left;">
          <strong>Mamani Vilca, Alan Jaivi</strong><br><br>
          <i>Soy estudiante de Ingeniería de Software en la UPC, con interés en machine learning y análisis de datos. Me caracterizo por mi pensamiento analítico, responsabilidad, proactividad y capacidad de trabajo en equipo. Me mantengo en constante aprendizaje, enfocado en la resolución de problemas y en aportar de manera eficiente y colaborativa en proyectos tecnológicos.</i>
        </td>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: center; vertical-align: middle;">
          <img src="docs/assets/alan.png" alt="Alan Mamani" width="150" style="border-radius: 10px; border: 1px solid #ccc;">
        </td>
      </tr>
      <!-- Integrante 5 -->
      <tr>
        <td style="padding: 20px; border: 1px solid #ddd; vertical-align: middle; text-align: left;">
          <strong>Sanchez Cuadrado, Juan Antonio</strong><br><br>
            <i>Soy estudiante de Ingeniería de Software con conocimientos en diversos lenguajes de programación y tecnologías web, entre ellos Python, JavaScript, Java, SQL, HTML y CSS. Poseo habilidades en desarrollo de aplicaciones web, lógica de programación y manejo de bases de datos, lo que me permite contribuir en la construcción tanto del frontend como del backend del sistema. Asimismo, tengo capacidad para analizar problemas, diseñar soluciones tecnológicas y trabajar en equipo bajo metodologías de desarrollo, aportando de manera activa en la implementación y mejora continua del proyecto.</i>
        </td>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: center; vertical-align: middle;">
          <img src="docs/assets/juan.png" alt="Juan Sanchez" width="150" style="border-radius: 10px; border: 1px solid #ccc;">
        </td>
      </tr>
    </tbody>
  </table>
</div>

### 1.2. Solution Profile

<p align="justify">
El Solution Profile presenta una visión general de la solución propuesta a partir del análisis del problema identificado en el dominio de los talleres automotrices.
</p>

<p>En esta sección se aborda:</p>
<ul>
  <li><strong>Antecedentes del problema</strong></li>
  <li><strong>Problemática existente</strong></li>
  <li><strong>Aspectos clave que la solución busca resolver</strong></li>
  <li><strong>Aplicación del enfoque Lean UX</strong></li>
</ul>

<p align="justify">
Asimismo, se emplea el enfoque Lean UX para validar hipótesis centradas en el usuario, permitiendo diseñar una solución orientada a mejorar la eficiencia operativa y la experiencia del cliente.
</p>

---

#### 1.2.1 Antecedentes y problemática

 <p><strong>Who (¿Quién?)</strong></p>
<ul>
  <li>Mecánicos independientes</li>
  <li>Talleres automotrices (PYMES)</li>
  <li>Clientes finales (propietarios de vehículos)</li>
</ul>

<p align="justify">
Estos actores gestionan clientes, vehículos y servicios sin sistemas especializados. Los clientes también se ven afectados por la falta de información clara y seguimiento.
</p>

<p><strong>What (¿Qué?)</strong></p>
<ul>
  <li>Deficiente gestión de procesos</li>
  <li>Problemas en:
    <ul>
      <li>Órdenes de trabajo</li>
      <li>Control de clientes</li>
      <li>Seguimiento de vehículos</li>
      <li>Registro de servicios</li>
    </ul>
  </li>
</ul>

<p align="justify">
Esto se debe al uso de métodos manuales o herramientas no integradas, generando desorganización, pérdida de información y errores.
</p>

<p><strong>Where (¿Dónde?)</strong></p>
<ul>
  <li>Talleres automotrices pequeños y medianos</li>
</ul>

<p>Se utilizan:</p>
<ul>
  <li>Cuadernos</li>
  <li>Hojas de cálculo</li>
  <li>Aplicaciones de mensajería</li>
</ul>

<p><strong>When (¿Cuándo?)</strong></p>
<p>Ocurre de manera constante, especialmente en:</p>
<ul>
  <li>Registro de servicios</li>
  <li>Seguimiento de vehículos</li>
  <li>Comunicación con clientes</li>
</ul>

<p><strong>Why (¿Por qué?)</strong></p>
<ul>
  <li>Falta de adopción de herramientas tecnológicas</li>
  <li>Ausencia de automatización y centralización</li>
  <li>Mala planificación y control del trabajo</li>
</ul>

<p align="justify">
Según Velneo (2023), la digitalización mejora la organización y la toma de decisiones. Sin embargo, muchos talleres no implementan estas soluciones.
<br><br>
JCM Automoción (2022) señala que la falta de control genera errores, retrabajos e insatisfacción.
</p>

<p><strong>How (¿Cómo?)</strong></p>
<ul>
  <li>Desorganización interna</li>
  <li>Falta de control</li>
  <li>Ausencia de historiales estructurados</li>
  <li>Deficiente comunicación con clientes</li>
</ul>

<p align="justify">
Esto impacta directamente en la calidad del servicio y la percepción del cliente.
<br><br>
Q2B Studio (2023) destaca que el software de gestión optimiza procesos y aumenta la eficiencia.
</p>

<p><strong>How Much (¿Cuánto impacta?)</strong></p>
<ul>
  <li>Pérdida de tiempo</li>
  <li>Errores en la gestión</li>
  <li>Baja productividad</li>
  <li>Disminución de la confianza del cliente</li>
</ul>

<p align="justify">
También afecta la reputación del taller debido a la falta de transparencia.
<br><br>
Quora (2023) indica que los sistemas de gestión mejoran la satisfacción del cliente mediante mayor claridad y seguimiento.
</p>

---

#### 1.2.2 Lean UX Process

<p align="justify">
El Lean UX Process permite definir y validar la solución a partir de la comprensión del problema y las necesidades del usuario.
</p>

<p><strong>Se basa en:</strong></p>
<ul>
  <li>Formulación de hipótesis</li>
  <li>Identificación de segmentos</li>
  <li>Análisis de valor</li>
</ul>

---

##### 1.2.2.1. Lean UX Problem Statements

<p><strong>Dominio (Domain):</strong></p>
<ul>
  <li>Gestión de talleres automotrices</li>
</ul>

<p><strong>Segmentos (Customer Segments):</strong></p>
<ul>
  <li>Mecánicos independientes</li>
  <li>Talleres automotrices</li>
</ul>

<p><strong>Problemas (Pain Points):</strong></p>
<ul>
  <li>Desorganización</li>
  <li>Falta de control de órdenes</li>
  <li>Ausencia de historial estructurado</li>
  <li>Deficiente comunicación</li>
</ul>

<p><strong>Impacto (Gap):</strong></p>
<ul>
  <li>Ineficiencia operativa</li>
  <li>Errores</li>
  <li>Pérdida de información</li>
  <li>Desconfianza del cliente</li>
</ul>

<p><strong>Visión / Estrategia:</strong></p>
<ul>
  <li>Plataforma web para:
    <ul>
      <li>Centralizar información</li>
      <li>Gestionar procesos</li>
      <li>Brindar seguimiento en tiempo real</li>
    </ul>
  </li>
</ul>

<p><strong>Segmento inicial:</strong></p>
<ul>
  <li>Mecánicos independientes</li>
  <li>Pequeños talleres</li>
</ul>

---

##### 1.2.2.2. Lean UX Assumptions

<p><strong>User Assumptions</strong></p>
<ul>
  <li>Dificultad para gestionar operaciones</li>
  <li>Uso de métodos manuales</li>
  <li>Necesidad de seguimiento en tiempo real</li>
  <li>Valoración de la transparencia</li>
  <li>Preferencia por soluciones simples</li>
</ul>

<p><strong>Business Assumptions</strong></p>
<ul>
  <li>Disposición a pagar por la solución</li>
  <li>Viabilidad del modelo SaaS</li>
  <li>Interés en mejorar eficiencia</li>
  <li>Digitalización como ventaja competitiva</li>
  <li>Generación de ingresos recurrentes</li>
</ul>

<p><strong>Product Assumptions</strong></p>
<ul>
  <li>Plataforma web suficiente inicialmente</li>
  <li>Centralización mejora organización</li>
  <li>Seguimiento aumenta confianza</li>
  <li>Digitalización reduce errores</li>
  <li>Interfaz debe ser simple</li>
</ul>

<p><strong>Technical Assumptions</strong></p>
<ul>
  <li>Uso de tecnologías web (HTML, CSS, JS, APIs)</li>
  <li>Base de datos con múltiples tablas (15+)</li>
  <li>Escalabilidad futura (móvil, IoT)</li>
  <li>Integración con APIs externas</li>
</ul>

<p><strong>Supuestos Críticos</strong></p>
<ul>
  <li>Existe el problema real</li>
  <li>Hay disposición de pago</li>
  <li>Se valora la transparencia</li>
  <li>El sistema será fácil de usar</li>
  <li>Generará mejoras reales</li>
</ul>

---

##### 1.2.2.3. Lean UX Hypothesis Statements

<p><strong>Hipótesis 1 – Gestión de Órdenes</strong></p>
<ul>
  <li><strong>Creemos que:</strong> un sistema digital mejorará la organización</li>
  <li><strong>Para:</strong> mecánicos y talleres</li>
  <li><strong>Lograremos:</strong> reducir errores y mejorar eficiencia</li>
  <li><strong>Lo sabremos cuando:</strong> disminuya el tiempo de registro</li>
</ul>

<p><strong>Hipótesis 2 – Seguimiento del Cliente</strong></p>
<ul>
  <li><strong>Creemos que:</strong> el seguimiento en tiempo real aumentará la confianza</li>
  <li><strong>Para:</strong> clientes</li>
  <li><strong>Lograremos:</strong> mayor satisfacción</li>
  <li><strong>Lo sabremos cuando:</strong> aumente la interacción y bajen consultas</li>
</ul>

<p><strong>Hipótesis 3 – Modelo SaaS</strong></p>
<ul>
  <li><strong>Creemos que:</strong> la suscripción mensual será atractiva</li>
  <li><strong>Para:</strong> talleres</li>
  <li><strong>Lograremos:</strong> ingresos recurrentes</li>
  <li><strong>Lo sabremos cuando:</strong> adopten planes pagos</li>
</ul>

<p><strong>Hipótesis 4 – Centralización</strong></p>
<ul>
  <li><strong>Creemos que:</strong> centralizar datos mejorará decisiones</li>
  <li><strong>Para:</strong> administradores</li>
  <li><strong>Lograremos:</strong> mejor control</li>
  <li><strong>Lo sabremos cuando:</strong> uso frecuente del dashboard</li>
</ul>

<p><strong>Hipótesis 5 – Usabilidad</strong></p>
<ul>
  <li><strong>Creemos que:</strong> una interfaz simple facilitará el uso</li>
  <li><strong>Para:</strong> usuarios no técnicos</li>
  <li><strong>Lograremos:</strong> adopción rápida</li>
  <li><strong>Lo sabremos cuando:</strong> no requieran capacitación</li>
</ul>

<p><strong>Hipótesis 6 – Éxito del sistema</strong></p>
<ul>
  <li><strong>Creemos que:</strong> la plataforma mejorará eficiencia y confianza</li>
  <li><strong>Para:</strong> talleres y clientes</li>
  <li><strong>Lograremos:</strong> mejor experiencia</li>
  <li><strong>Lo sabremos cuando:</strong> aumente el uso y satisfacción</li>
</ul>

---

##### 1.2.2.4. Lean UX Canvas

<p align="center">
  <img src="docs/assets/LeanUX .jpg" alt="LeanUX Canvas" width="1000">
</p>

---

### 1.3. Segmentos objetivo

<p align="justify">
Se identifican los tipos de usuarios que interactúan con la solución.
</p>

<h4><i>Segmentos que contratan nuestro servicio (Clientes del sistema)</i></h4>

<p><strong>1. Mecánicos Independientes</strong></p>
<ul>
  <li>Trabajan de forma autónoma</li>
  <li>Manejan pocos clientes</li>
  <li>Bajo nivel de digitalización</li>
  <li>Necesitan soluciones simples y económicas</li>
</ul>

<p align="justify">
Buscan mejorar organización, control de servicios y ofrecer mayor transparencia.
</p>

<p><strong>2. Talleres Automotrices / Empresas</strong></p>
<ul>
  <li>Mayor volumen de trabajo</li>
  <li>Varios mecánicos</li>
  <li>Necesidad de control administrativo</li>
  <li>Enfoque en eficiencia y competitividad</li>
</ul>

<p align="justify">
Requieren herramientas más completas para gestionar operaciones.
</p>

<h4><i>Segmento que recibe el servicio (Usuario Final)</i></h4>

<p><strong>3. Clientes (Propietarios de Vehículos)</strong></p>
<ul>
  <li>Buscan transparencia</li>
  <li>Desean seguimiento en tiempo real</li>
  <li>No tienen conocimientos técnicos</li>
  <li>Valoran claridad y confianza</li>
</ul>

<p align="justify">
Interactúan con la plataforma para consultar el estado del servicio y costos.
</p>

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis competitivo

### Competitive Analysis Landscape
<div align="center">
<table>
  <tr>
    <th colspan="6" style="text-align: center; background-color: #f2f2f2;">Competitive Analysis Landscape</th>
  </tr>
  <tr>
    <th colspan="2">¿Por qué llevar a cabo este análisis?</th>
    <td colspan="4">Tiene como objetivo identificar y comprender las características, fortalezas y debilidades de las soluciones existentes en el mercado, con el fin de detectar oportunidades de diferenciación y definir una propuesta de valor clara para AutoService.</td>
  </tr>
  <tr>
    <th colspan="2"></th>
    <th style="text-align: center;"><img src="docs/assets/chapter-2/AutoService.jpeg" alt="Logo" style="width: 150px;"></th>
    <th style="text-align: center;"><img src="docs/assets/chapter-2/shopmonkey.png" alt="Competidor 1" style="width: 150px;"></th>
    <th style="text-align: center;"><img src="docs/assets/chapter-2/appTallerMecanico.jpg" alt="Competidor 2" style="width: 150px;"></th>
    <th style="text-align: center;"><img src="docs/assets/chapter-2/AutoLeap.png" alt="Competidor 3" style="width: 150px;"></th>
  </tr>
  <tr>
    <td rowspan="2" style="vertical-align: middle; font-weight: bold;">Perfil</td>
    <td>Overview</td>
    <td><i>AutoService es una plataforma web tipo SaaS diseñada para digitalizar la gestión de talleres automotrices y mejorar la transparencia del servicio mediante el seguimiento en tiempo real del estado de los vehículos.
La plataforma permite a mecánicos y talleres gestionar clientes, vehículos, órdenes de trabajo y pagos en un entorno centralizado, mientras que el cliente final puede acceder al sistema para visualizar el progreso de su vehículo, los trabajos realizados y los costos asociados.</i></td>
    <td><i>Shopmonkey es una plataforma digital de gestión para talleres automotrices basada en la nube, diseñada para centralizar y optimizar las operaciones del negocio en un solo sistema. Permite a los talleres administrar procesos clave como la programación de citas, gestión de clientes, órdenes de trabajo, facturación, inventario y comunicación con clientes</i></td>
    <td><i>Esta plataforma permiten registrar clientes, vehículos, órdenes de trabajo, inventario y pagos, centralizando la información en un solo sistema accesible desde cualquier dispositivo. Se caracterizan por ser herramientas prácticas, enfocadas en digitalizar procesos básicos del taller y reemplazar métodos tradicionales como cuadernos o Excel.</i></td>
    <td><i>AutoLeap es un software de gestión para talleres automotrices basado en la nube que permite administrar de forma integral las operaciones del negocio, incluyendo órdenes de trabajo, clientes, inventario, facturación, comunicación y reportes</i></td>
  </tr>
  <tr>
    <td>Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</td>
    <td><i>Enfoque en la transparencia y el cliente final como usuario activo<br>
      <li>Para el taller: organización total del negocio, control de órdenes y procesos,mejora en la comunicación, incremento de confianza.</li>
      <li>Para el cliente: Seguimiento en tiempo real del vehículo, transparencia en trabajos y costos, reducción de incertidumbre, mayor confianza en el servicio.</li>
      <li>Para la plataforma (negocio): Ingreso recurrente (SaaS), comisión por servicios,escalabilidad</li>
    </i></td>
    <td><i>Ofrece una solución “todo en uno” que centraliza todas las operaciones del taller en una sola plataforma. Esto significa que, a diferencia de sistemas tradicionales o herramientas separadas. 
    <li>Integra gestión, facturación, clientes y pagos</li>
    <li>Automatiza procesos operativos</li>
    <li>Reduce errores y tiempo de trabajo</i></li></td>
    <td><i>
        <li>Simplicidad y accesibilidad para talleres pequeños</li>
        <li>Fácil de usar (no requiere conocimientos técnicos)</li>
        <li>Acceso desde celular (muy importante en LATAM)</li>
        <li>Implementación rápida</li></i></td>
    <td><i>Plataforma integral con enfoque en automatización y crecimiento del negocio
        <li>Eficiencia operativa<li>
        Gestión centralizada de todo el taller
        Automatización de tareas repetitivas
        <li>Crecimiento del negocio</li>
        Herramientas de marketing integradas
        Reportes de rendimiento y rentabilidad
        <li>Mejora en servicio al cliente</li>
        Comunicación digital (SMS, email)
        Inspecciones digitales con fotos/videos
    </i></td>
  </tr>
  <tr>
    <td rowspan="2" style="vertical-align: middle; font-weight: bold;">Perfil de Marketing</td>
    <td>Mercado objetivo</td>
    <td><i>
        <li>Mecánicos independientes</li>
         Baja digitalización
        Necesidad de orden y control
        <li>Talleres automotrices PYMEs</li>
        Flujo constante de clientes
        Necesidad de gestión y control
        <li>Clientes finales (dueños de vehículos)</li>
        Buscan confianza y transparencia
    </i></td>
    <td><i>Shopmonkey está dirigido principalmente a:
      <li>Talleres automotrices medianos y grandes</li>
      <li>Negocios en crecimiento que buscan digitalizarse</li>
      <li>Talleres especializados (llantas, aceite, flotas, etc.)</li>
      Apunta a negocios formales con capacidad de pago, no tanto a mecánicos informales.</i></td>
    <td><i>
        <li>Mecánicos independientes</li>
        <li>Talleres pequeños (1–5 personas)</li>
        <li>Negocios informales o en proceso de digitalización</li>
    </i></td>
    <td><i>
        <li>Talleres automotrices medianos y grandes</li>
        <li>Negocios en crecimiento que buscan escalar</li>
        <li>Empresas con múltiples sedes o franquicias</li>
    </i></td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td><i>
        <li>Marketing digital</li>
        <li>Enfoque en dolor real</li>
        <li>Modelo freemium</li>
        <li>Estrategia local (clave en LATAM)</li>
    </i></td>
    <td><i><li>Marketing digital (SaaS): demos online y prueba del sistema</li>
           <li>Posicionamiento como solución “todo en uno”</li>
           <li>Contenido educativo (blogs, guías, recursos)</li>
           <li>Enfoque en beneficios:
           <ul>
            <li>aumento de ingresos</li>
            <li>eficiencia</li>
            <li>satisfacción del cliente</li>
           </ul>
           </li>
          </i></td>
    <td><i>
        <li>Marketing digital básico (redes sociales, anuncios simples)<li>
        <li>Pruebas gratuitas o versiones freemium</li>
        <li>Enfoque en dolor real: Deja la libreta, Organiza tu taller</li>
        <li>Uso de WhatsApp como canal de contacto</li>
        <li>Promoción por recomendaciones (boca a boca)</li>
    </i></td>
    <td><i>
        <li>Demos personalizadas para captar clientes</li>
        <li>Enfoque en resultados: aumento de ingresos, eficiencia operativa</li>
        <li>Marketing de contenido (blogs, recursos, ROI calculators)</li>
        <li>Upselling de servicios adicionales (marketing suite, AI receptionist)</li>
    </i></td>
  </tr>
  <tr>
    <td rowspan="3" style="vertical-align: middle; font-weight: bold;">Perfil de producto</td>
    <td>Productos & Servicios</td>
    <td><i>
        <li>Gestión del taller
        Registro de clientes
        Registro de vehículos
        Órdenes de trabajo
        Historial por vehículo
        <li>Operación
        Estados del servicio (tracking)
        Asignación de tareas
        Diagnóstico y solución</li>
        <li>Experiencia del cliente:
        Acceso con código
        Seguimiento en tiempo real
        Visualización de costos
        Notificaciones
        <li>Negocio:
        Registro de pagos
        Generación de comprobantes (API)
        Reportes y dashboard</li>
        <li>Futuro (diferenciación)
        IA para explicación de trabajos
        Notificaciones automáticas
        App móvil</li>
    </i></td>
    <td><i>Gestión de clientes y vehículos, órdenes de trabajo, facturación y pagos integrados, inspecciones digitales, reportes y analítica, comunicación por SMS y email, integraciones (QuickBooks, CARFAX, etc.)</i></td>
    <td><i>
        <li>Registro de clientes y vehículos</li>
        <li>Órdenes de trabajo</li>
        <li>Cotizaciones y presupuestos</li>
        <li>Control de inventario</li>
        <li>Gestión de pagos</li>
        <li>Historial de servicios</li>
        <li>Recordatorios y notificaciones</li>
    </i></td>
    <td><i>
        <li>Órdenes de trabajo (Repair Orders)</li>
        <li>Gestión de clientes y vehículos</li>
        <li>Facturación y pagos integrados</li>
        <li>Inspecciones digitales (con fotos, videos, notas)</li>
        <li>Gestión de inventario y proveedores</li>
        <li>Reportes y dashboards en tiempo real</li>
        <li>CRM y comunicación con clientes</li>
    </i></td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td><i>
      <li>Free: Funcionalidades básicas, hasta cierto número de vehículos</li>
      <li>Pro (S/29–49 mensual):
        Vehículos ilimitados, historial completo, notificaciones</li>
      <li>Business (S/79–149 mensual): Gestión de staff, reportes avanzados</li>
    </i></td>
    <td><i>
    Planes aproximados:
      - Desde $179/mes (básico)
      - Hasta $400+ /mes (avanzado)
      - Costos adicionales:
      usuarios extra,
      add-ons (CRM, herramientas avanzadas)
    </i></td>
    <td><i>
        <li>Freemium (versión gratuita limitada)</li>
        <li>Planes económicos (≈ $5 – $30 USD / mes)</li>
        <li>Algunos modelos: Pago unico, Plan "fundador" o acceso inicial gratuito</li>
    </i></td>
    <td><i>Essentials: ~ $199/mes
        Pro: ~ $349/mes
        Elite: ~ $449/mes
        Enterprise: precio personalizado</i></td>
  </tr>
  <tr>
    <td>Canales de distribución<br>(Web y/o Móvil)</td>
    <td><i>
        <li>Plataforma web (principal)</li>
        <li>Acceso desde móvil y desktop</li>
        <li>Modelo de suscripción online</li>
        <li>Redes sociales y marketing digital</li>
        <li>Venta directa a talleres</li>
    </i></td>
    <td><i>
      <>Plataforma web (cloud-based)
      <li>Aplicaciones móviles (iOS y Android)</li>
      <li>Venta directa online (demo + suscripción)</li>
      <li>Soporte digital (chat, email, onboarding)</li></i></td>
    <td><i>Aplicaciones móviles (Android principalmente)
           Descarga directa o acceso online
           Canal principal:
           móvil (smartphone)</i></td>
    <td><i>
        <li>Plataforma web (cloud-based)</li>
        <li>Acceso desde desktop, tablet y móvil</li>
        <li>Venta directa online (demo + suscripción)</li>
        <li>Soporte digital (chat, email, onboarding)</li>
    </i></td>
  </tr>
  <tr>
    <td rowspan="4" style="vertical-align: middle; font-weight: bold;">Analisis SWOT</td>
    <td>Fortalezas</td>
    <td><i>
        <li>Diferenciación clara (tracking + cliente)</li>
        <li>Enfoque en confianza</li>
        <li>Modelo híbrido (SaaS + comisión)</li>
        <li>Adaptado a LATAM</li>
    </i></td>
    <td><i>
        <li>Plataforma completa (todo en uno)</li>
        <li>Automatización de procesos</li>
        <li>Integraciones con herramientas externas</li>
        <li>Mejora eficiencia y rentabilidad</li>
        <li>Enfoque en crecimiento del negocio</li></i></td>
    <td><i>
        <li>Fácil de usar</li>
        <li>Bajo costo</li>
        <li>Accesible desde celular</li>
        <li>Ideal para pequeños talleres</li>
        <li>Implementación rápida</li>
    </i></td>
    <td><i>
        <li>Plataforma completa (todo en uno)</li>
        <li>Funcionalidades avanzadas (IA, inspecciones digitales)</li>
        <li>Alta automatización</li>
        <li>Escalable (multi-sede, enterprise)</li>
    </i></td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td><i>
        <li>Marca nueva (sin posicionamiento)</li>
        <li>Recursos limitados (startup)</li>
        <li>Dependencia de adopción tecnológica</li>
        <li>Funcionalidades iniciales limitadas (MVP)</li>
    </i></td>
    <td><i>
      <li>Alto costo para pequeños talleres</li>
      <li>Curva de aprendizaje (muchas funciones)</li>
      <li>Puede ser complejo para usuarios no técnicos</li>
      <li>Dependencia de configuración inicial</li>
    </i></td>
    <td><i>
        <li>Funcionalidades limitadas</li>
        <li>Poca escalabilidad</li>
        <li>No integra procesos complejos</li>
        <li>Baja diferenciación</li>
        <li>En muchos casos, interfaz básica</li>
    </i></td>
    <td><i>
        <li>Alto costo (no accesible para pequeños talleres)</li>
        <li>Complejidad del sistema</li>
        <li>Implementación más exigente</li>
        <li>Dependencia de configuración inicial</li>
    </i></td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td><i>
        <li>Baja digitalización en talleres LATAM</li>
        <li>Alta desconfianza del cliente (problema real)</li>
        <li>Crecimiento del SaaS</li>
        <li>Integración con IA e IoT</li>
    </i></td>
    <td><i>
      <li>Crecimiento del mercado de digitalización automotriz</li>
      <li>Expansión a nuevos países (LATAM, Asia)</li>
      <li>Integración con nuevas tecnologías (IA, IoT)</li>
      <li>Mayor demanda de soluciones en la nube</li>
    </i></td>
    <td><i>
        <li>Crecimiento de digitalización en LATAM</li>
        <li>Gran cantidad de talleres informales</li>
        <li>Integración con pagos digitales</li>
        <li>Evolución hacia plataformas más completas</li>
    </i></td>
    <td><i>
        <li>Crecimiento de digitalización del sector automotriz</li>
        <li>Expansión a mercados emergentes (LATAM)</li>
        <li>Integración con IA e IoT</li>
        <li>Mayor demanda de soluciones SaaS</li>
    </i></td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td><i>
        <li>Competidores internacionales fuertes</li>
        <li>Apps simples más baratas</li>
        <li>Resistencia al cambio</li>
        <li>Uso de métodos tradicionales (Excel, papel)</li>
    </i></td>
    <td><i>
      <li>Nuevos competidores más simples y baratos</li>
      <li>Soluciones locales adaptadas a LATAM</li>
      <li>Resistencia al cambio (talleres tradicionales)</li>
      <li>Herramientas más simples (Excel, apps básicas)</li>
    </i></td>
    <td><i>
        <li>Competidores más completos (como Shopmonkey)</li>
        <li>Nuevas startups más innovadoras</li>
        <li>Resistencia al cambio tecnológico</li>
        <li>Uso de soluciones gratuitas (Excel, papel)</li>
    </i></td>
    <td><i>
        <li>Competidores más económicos y simples</li>
        <li>Soluciones locales adaptadas a pequeños talleres</li>
        <li>Resistencia al cambio tecnológico</li>
    </i></td>
  </tr>
</table>
</div>

---

#### 2.1.2. Estrategias y tácticas frente a competidores

<p align="justify">Nuestro producto adoptará una estrategia competitiva basada en la diferenciación a través de la transparencia del servicio y la integración del cliente en el proceso, respondiendo a las limitaciones actuales del mercado, donde predominan soluciones centradas únicamente en la gestión interna.</p>
<ol>
<li>Diferenciarnos mediante la transparencia del servicio

  <p align="justify">Muchos sistemas actuales se enfocan en la gestión interna del taller, dejando de lado la experiencia del cliente y generando incertidumbre durante el proceso del servicio.
  Para aprovechar esta oportunidad, AutoService se centrará en brindar visibilidad completa al cliente sobre el estado de su vehículo.</p>
  <ul>
    <li>Implementar seguimiento en tiempo real del vehículo</li>
    <li>Mostrar estados claros del servicio (pendiente, en proceso, finalizado)</li>
    <li>Visualizar trabajos realizados y costos asociados</li>
    <li>Incorporar notificaciones automáticas al cliente</li>
  </ul>
</li>

<li>Generar una experiencia simple e intuitiva para el usuario

  <p align="justify">Algunas soluciones del mercado pueden resultar complejas o poco accesibles para usuarios con bajo nivel tecnológico, dificultando su adopción.
  AutoService prioriza la facilidad de uso para garantizar una rápida implementación y aceptación.</p>
  
  <ul>
  <li>Diseño de interfaz clara y amigable</li>
  <li>Navegación sencilla y estructurada</li>
  <li>Acceso rápido a funciones principales</li>
  <li>Optimización para dispositivos móviles</li>
  </ul>
</li>

<li>Facilitar la digitalización de talleres pequeños y medianos

  <p align="justify">Muchos talleres enfrentan barreras para adoptar herramientas digitales debido a costos o complejidad.
AutoService busca reducir estas barreras y fomentar la digitalización del sector.</p>
  
  <ul>
  <li>Plan gratuito para nuevos usuarios</li>
  <li>Planes escalables según el crecimiento del taller</li>
  <li>Capacitación básica y guías de uso</li>
  <li>Implementación rápida sin necesidad de conocimientos técnicos</li>
  </ul>
</li>


<li>Aprovechar el crecimiento de la digitalización en el sector automotriz

  <p align="justify">El mercado presenta una tendencia creciente hacia el uso de herramientas digitales para la gestión de negocios.
AutoService se posiciona como una solución moderna alineada a esta transformación.</p>
  
  <ul>
  <li>Promoción del uso de tecnología en talleres</li>
  <li>Difusión en redes sociales y canales digitales</li>
  <li>Demostraciones del sistema en entornos reales</li>
  <li>Enfoque en beneficios como eficiencia y control</li>
  </ul>
</li>


<li>Fortalecer la confianza del cliente final

  <p align="justify">Uno de los principales problemas del sector es la desconfianza del cliente debido a la falta de información.
Se busca transformar esta percepción mediante transparencia y comunicación.</p>
  
  <ul>
  <li>Acceso del cliente al sistema mediante código único</li>
  <li>Información clara y detallada del servicio</li>
  <li>Reducción de dependencia de llamadas o mensajes</li>
  <li>(Futuro) evidencia visual del trabajo realizado</li>
  </ul>
</li>

<li>Diferenciarnos por el valor ofrecido y no solo por funcionalidades

  <p align="justify">Más allá de ofrecer herramientas de gestión, AutoService se enfoca en brindar una experiencia completa tanto para el taller como para el cliente.</p>
  
  <ul>
  <li>Integración del cliente en el proceso</li>
  <li>Mejora de la comunicación entre ambas partes</li>
  <li>Enfoque en confianza y transparencia</li>
  <li>Evolución continua del sistema con nuevas funcionalidades</li>
  </ul>
</li>

<li>Aprovechamiento de la baja digitalización en LATAM

  Captar talleres que aún no usan sistemas digitales
  
  <ul>
  <li>Campañas educativas (“digitaliza tu taller”)</li>
  <li>Demostraciones prácticas</li>
  <li>Uso de redes sociales y WhatsApp</li>

  </ul>
</li>

</ol>

---

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

<strong>SEGMENTO 1: Mecánicos Independientes</strong>
<ol>
  <li>¿Cuánto tiempo llevas trabajando como mecánico? ¿Podrías contarme cómo es un día típico en tu trabajo dentro del taller?</li>
  <li>¿Cómo registras actualmente la información de tus clientes, vehículos y trabajos?</li>
  <li>¿Cuáles son los principales problemas que enfrentas al gestionar los trabajos del taller?</li>
  <li>¿Cómo informas a tus clientes sobre el estado de sus vehículos?</li>
  <li>¿Qué tan seguido te llaman o escriben clientes para preguntar por el estado de su auto?</li>
  <li>¿Crees que tus clientes confían en el servicio que brindas? ¿Por qué?</li>
  <li>¿Llevas un historial de los trabajos realizados por vehículo o cliente?</li>
  <li>Si existiera una plataforma que te ayude a organizar tus trabajos y mostrar el progreso al cliente, ¿la usarías? ¿Por qué?</li>
  <li>¿Qué funcionalidad te sería más útil en una herramienta digital para tu trabajo diario?</li>
</ol>

<strong>SEGMENTO 2: Talleres Automotrices - Empresas</strong>
<ol>
  <li>¿Cuántas personas trabajan en su taller y cómo están organizadas sus funciones?</li>
  <li>¿Cómo gestionan actualmente los clientes, vehículos y órdenes de trabajo?</li>
  <li>¿Qué problemas tienen al coordinar el trabajo entre mecánicos o áreas?</li>
  <li>¿Cómo hacen seguimiento al estado de cada vehículo en reparación?</li>
  <li>¿Tienen algún sistema para medir ingresos, servicios realizados o rendimiento del taller?</li>
  <li>¿Cómo se comunican con los clientes sobre el avance del servicio?</li>
  <li>¿Han tenido problemas de desconfianza o reclamos por parte de clientes?</li>
  <li>Si existiera un sistema que te permita gestionar tu taller y mostrar a tus clientes el progreso en tiempo real, ¿lo usarías?</li>
  <li>¿Qué funcionalidades consideras indispensables en un sistema de gestión para talleres?</li>
</ol>

<strong>SEGMENTO 3: Clientes - Propietarios de vehículos</strong>
<ol>
  <li>¿Podrías contarme sobre la última vez que llevaste tu vehículo a un taller? ¿Qué servicio necesitabas?</li>
  <li>Durante el servicio, ¿cómo te informaban sobre el estado de tu vehículo?</li>
  <li>¿Tuviste alguna duda o preocupación mientras tu auto estaba en el taller? ¿Cuál fue?</li>
  <li>¿Alguna vez has sentido desconfianza hacia un taller? ¿Qué situación generó eso?</li>
  <li>¿Te gustaría poder ver el progreso de la reparación de tu auto en tiempo real desde tu celular o computadora? ¿Por qué?</li>
  <li>¿Qué tipo de información te gustaría ver mientras tu vehículo está en el taller?</li>
  <li>¿Qué tan cómodo te sientes usando plataformas digitales o aplicaciones para consultar información de servicios?</li>
  <li>Si existiera una plataforma que te permita ver el estado de tu vehículo, costos y trabajos realizados, ¿la usarías? ¿Qué te gustaría que incluya?</li>
</ol>


#### 2.2.2. Registro de entrevistas

#### Entrevista 1: Técnico Independiente

- **Nombre:** Fray Diaz Palomino
- **Edad:** 38
- **Residencia:** Ayacucho, Huamanga 
- **Ocupación:** Técnico Mecánico Automotriz  

- **Inicio:** 0:33  
- **Duración:** 8:30  

**Link:**  
[Ver video]()

---
**Resumen:**

El entrevistado Gurmecindo de 55 años con aproximadamente 35 años de experiencia, residente en San Juan Bautista, Ayacucho. Su trabajo se centra en la reparación de motores y mantenimiento general de vehículos. En su día a día, realiza diversas tareas mecánicas dependiendo de las fallas que presentan los autos. Actualmente, gestiona la información de sus clientes y vehículos de forma manual, utilizando cuadernos y actas de control donde registra datos como la hora de ingreso, la placa y el tipo de trabajo. En cuanto a la comunicación, suele llamar a los clientes cuando el vehículo está listo o también recibe llamadas de ellos para consultar el estado. Señala que sus clientes confían en su servicio debido a la garantía y puntualidad que ofrece, y sí mantiene un historial de trabajos de manera escrita. Frente a la propuesta de una plataforma digital, muestra una actitud positiva y considera que es necesaria en la actualidad para mejorar la gestión, destacando como funcionalidad importante la incorporación de herramientas como escáner automotriz para diagnosticar fallas electrónicas, lo que facilitaría y modernizaría su trabajo diario.

---

**Evidencia:**

![Entrevista Administrador Taller](docs/assets/chapter-2/interview-technical-1.png)

#### Entrevista 2: Técnico Independiente

- **Nombre:** Gurmencindo Ventura
- **Edad:** 55
- **Residencia:** Ayaacucho, Huamanga - San Juan Bautista
- **Ocupación:** Técnico Automotriz  

- **Inicio:** 0:38  
- **Duración:** 5:29  

**Link:**  
[Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d185_upc_edu_pe/IQC3R-wNkI7tQZ07-wGLrqBvAUckZJvae4x3Gvydyx-kgVk?e=MSpswt)

---
**Resumen:**

El entrevistado Gurmecindo de 55 años con aproximadamente 35 años de experiencia, residente en San Juan Bautista, Ayacucho. Su trabajo se centra en la reparación de motores y mantenimiento general de vehículos. En su día a día, realiza diversas tareas mecánicas dependiendo de las fallas que presentan los autos. Actualmente, gestiona la información de sus clientes y vehículos de forma manual, utilizando cuadernos y actas de control donde registra datos como la hora de ingreso, la placa y el tipo de trabajo. En cuanto a la comunicación, suele llamar a los clientes cuando el vehículo está listo o también recibe llamadas de ellos para consultar el estado. Señala que sus clientes confían en su servicio debido a la garantía y puntualidad que ofrece, y sí mantiene un historial de trabajos de manera escrita. Frente a la propuesta de una plataforma digital, muestra una actitud positiva y considera que es necesaria en la actualidad para mejorar la gestión, destacando como funcionalidad importante la incorporación de herramientas como escáner automotriz para diagnosticar fallas electrónicas, lo que facilitaría y modernizaría su trabajo diario.

---

**Evidencia:**

![Entrevista Administrador Taller](docs/assets/chapter-2/interview-technical-2.png)

#### Entrevista 3: Técnico Independiente

- **Nombre:** Antenor Ayala 
- **Edad:** 33
- **Residencia:** Ayacucho, Huamanga  
- **Ocupación:** Técnico Mecánico Automotriz  

- **Inicio:** 0:25  
- **Duración:** 9:11  

**Link:**  
[Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241d185_upc_edu_pe/IQCxbUZ3D94sQa4L_R0U-pTLAeS4IIX60VMV6GW0RGncMMA?e=mN7UdR)

---
**Resumen:**

El entrevistado Antenor Ayala, un mecánico automotriz de 33 años residente en Huamanga, con aproximadamente 5 años de experiencia en el rubro. Describe que su trabajo diario varía entre resolver fallas simples y complejas, comenzando con la recepción del cliente y el diagnóstico del problema, el cual a veces difiere de lo que el cliente cree. Lleva el registro de los trabajos de forma manual en un cuaderno, lo que puede generar desorganización. Señala que uno de los principales problemas que enfrenta es la gestión de clientes, ya que existen diferentes tipos de comportamientos y expectativas, además de que reconoce que en ocasiones pueden ocurrir errores humanos debido al cansancio o problemas personales. En cuanto a la comunicación, indica que antes tenía dificultades por no informar adecuadamente los cambios realizados, lo que generaba desconfianza, pero ahora busca mejorar avisando previamente o mostrando evidencias como fotos o videos. También menciona que algunos clientes llaman con mucha frecuencia mientras que otros son más independientes. Finalmente, muestra una actitud muy positiva hacia la implementación de una plataforma digital, ya que considera que le ayudaría a organizar mejor sus tareas, mejorar la comunicación, aumentar la confianza con los clientes y gestionar aspectos como horarios, inventario e historial de trabajos, lo que optimizaría su desempeño diario.

---

**Evidencia:**

![Entrevista Administrador Taller](docs/assets/chapter-2/interview-technical-3.png)


#### Entrevista 4: Administrador de Taller Automotriz

- **Nombre:** Juan Calisaya  
- **Edad:** 30  
- **Residencia:** Santa Anita, Lima  
- **Ocupación:** Propietario y Administrador de Taller Automotriz  

- **Inicio:** 0:05  
- **Duración:** 14:07  

**Link:**  
[Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241e299_upc_edu_pe/IQBuwdmTZaBDQ6FwqgTBqd_zAZXoZxFYUA9sZBDB-I4bGyw?e=WVr7u3)

---
**Resumen:**
<p style="text-align: justify;">
El entrevistado Juan Calisaya, de 30 años, es propietario y administrador de un taller automotriz en Santa Anita con más de 5 años de experiencia. Su negocio cuenta con un equipo de 4 trabajadores, donde existen roles diferenciados como mecánicos y personal de apoyo, aunque la distribución de tareas no está completamente formalizada y depende en gran medida de su supervisión directa. Actualmente, la gestión del taller se realiza mediante métodos manuales, principalmente cuadernos y registros en papel, lo que genera desorganización y dificultad para acceder a información histórica. La asignación de trabajos se realiza de manera verbal, lo que ocasiona falta de claridad en las responsabilidades y dependencia constante del administrador. Uno de los principales problemas es la falta de visibilidad sobre el estado de los vehículos en reparación. El seguimiento se realiza consultando directamente a los mecánicos, generando interrupciones frecuentes y retrasos en la atención, además de presión constante por parte de los clientes. En cuanto a la comunicación, el taller utiliza llamadas telefónicas y WhatsApp, lo que obliga al administrador a actuar como intermediario, generando demoras y sobrecarga de trabajo. A nivel administrativo, no cuentan con herramientas digitales para controlar ingresos, egresos ni inventario, lo que dificulta la trazabilidad de gastos y puede generar desbalances. Asimismo, la rotación de funciones entre trabajadores por necesidades operativas provoca desorganización interna, aunque el equipo es competente. El entrevistado presenta un nivel básico de adopción tecnológica, valorando herramientas simples como WhatsApp y Yape. Finalmente, muestra una actitud positiva hacia la implementación de un sistema digital que incluya registro de clientes, historial de servicios, asignación de tareas, seguimiento en tiempo real, control financiero e inventario, con el objetivo de mejorar la organización, optimizar el tiempo y fortalecer la confianza con los clientes.
</p>

---

**Evidencia:**

![Entrevista Administrador Taller](docs/assets/chapter-2/interview-admin-taller-1.png)



#### Entrevista 5: Administrador y Encargado de Logística de Taller Automotriz

- **Nombre:** Sebastián Rojas  
- **Edad:** 24  
- **Residencia:** Villa El Salvador, Lima  
- **Ocupación:** Administrador y Encargado de Logística de Taller Automotriz  

- **Inicio:** 0:04  
- **Duración:** 10:55  

**Link:**  
[Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20241e299_upc_edu_pe/IQAn-6pC1Ur6TbGWsrSbHCfUATVeVUjKORt507XsjZzhAKU?e=zj8iCk)

---

**Resumen:**
<p style="text-align: justify;">
El entrevistado Sebastián Rojas, de 24 años, se desempeña como administrador y encargado de logística en un taller automotriz con un equipo de 6 personas, donde las funciones están distribuidas según especialidad. La gestión actual combina registros en papel y Excel, lo que permite cierto orden, pero resulta limitado ante el crecimiento del volumen de trabajo. Uno de los principales problemas es la falta de coordinación entre áreas, especialmente entre mecánicos y almacén, generando cuellos de botella y dependencia del administrador para validar procesos. El seguimiento de los vehículos se realiza mediante un pizarrón físico, pero al no actualizarse constantemente, se requiere comunicación directa frecuente, lo que reduce la eficiencia. La comunicación con los clientes se da principalmente por llamadas y WhatsApp, enviando ocasionalmente fotos, pero esto genera desconfianza cuando no hay claridad en los avances o cambios en los costos. Además, el control de ingresos e inventario es básico, lo que limita el análisis del rendimiento del negocio. El entrevistado muestra interés en implementar un sistema digital que permita gestionar órdenes de trabajo, controlar inventario, visualizar el estado de los vehículos en tiempo real y generar reportes, con el objetivo de mejorar la organización, optimizar el tiempo y aumentar la transparencia con los clientes.
</p>

---a

**Evidencia:**

![Entrevista Administrador Logística](docs/assets/chapter-2/interview-admin-taller-2.png)


#### 2.2.3. Análisis de entrevistas

<p align="justify">
A partir de las entrevistas realizadas a los segmentos objetivo (mecánicos independientes y administradores/encargados de logística en talleres automotrices), se han identificado patrones clave, puntos de dolor recurrentes y necesidades que validan la propuesta de valor de <b>AutoService</b>:
</p>

<ul style="text-align: justify; margin-top: 0.5em; margin-bottom: 1.5em; padding-left: 1.5em;">
  <li style="margin-bottom: 0.8em;">
    <strong>Gestión operativa manual y descentralizada:</strong> La totalidad de los entrevistados depende parcial o totalmente de métodos tradicionales (cuadernos, pizarras físicas, hojas de papel o Excel básico) para registrar ingresos de vehículos, datos de clientes y órdenes de trabajo. Esto provoca desorganización, dificultad para rastrear historiales y cuellos de botella en la operación diaria.
  </li>
  <li style="margin-bottom: 0.8em;">
    <strong>Fricción constante en la comunicación y seguimiento:</strong> El flujo de información actual es ineficiente. Los clientes llaman o escriben frecuentemente (vía WhatsApp) para conocer el estado de sus vehículos, lo que interrumpe el trabajo técnico de los mecánicos. En talleres con más personal, el administrador se convierte en un intermediario saturado entre el técnico y el cliente.
  </li>
  <li style="margin-bottom: 0.8em;">
    <strong>Falta de visibilidad interna en tiempo real:</strong> Los administradores y encargados de logística carecen de un panorama actualizado sobre el progreso de las reparaciones. Para conocer el estado de un vehículo, deben interrumpir a los mecánicos y consultarles verbalmente, lo que retrasa la atención y genera descoordinación entre áreas (ej. taller y almacén de repuestos).
  </li>
  <li style="margin-bottom: 0.8em;">
    <strong>Desconfianza originada por falta de transparencia:</strong> La incapacidad de comunicar de forma estructurada los diagnósticos, avances y posibles cambios en los costos genera incertidumbre en el cliente final. Aunque los mecánicos intentan mitigar esto enviando fotos o videos de forma manual, reconocen que es un proceso tedioso que necesita optimización.
  </li>
  <li style="margin-bottom: 0.8em;">
    <strong>Deficiencia en el control administrativo y logístico:</strong> La mayoría de los talleres entrevistados carece de herramientas especializadas para controlar el inventario, registrar ingresos/egresos de forma detallada o medir la productividad del personal, limitando su capacidad de crecimiento y análisis de rentabilidad.
  </li>
  <li style="margin-bottom: 0.8em;">
    <strong>Alta disposición hacia la digitalización:</strong> A pesar de manejar procesos tradicionales, todos los entrevistados mostraron una actitud sumamente receptiva hacia la adopción de un sistema digital. Identifican como indispensable contar con historiales de vehículos, asignación clara de tareas, seguimiento de estados en tiempo real y automatización de la comunicación para modernizar sus talleres y fortalecer la confianza de sus clientes.
  </li>
</ul>

---

### 2.3. Needfinding

#### 2.3.1. User Personas

#### User Persona 1: Mechanic

Perfil de un mecánico que trabaja en talleres automotrices y requiere una gestión eficiente de órdenes de servicio.

![User Persona Mechanic](docs/assets/chapter-2/needfinding/user-persona-1-mechanic.png)


#### User Persona 2: Workshop Manager

Perfil de un administrador de taller que gestiona operaciones, personal y flujo de trabajo.

![User Persona Workshop Manager](docs/assets/chapter-2/needfinding/user-persona-2-workshop-manager.png)


#### User Persona 3: Vehicle Owner

Perfil de un cliente que busca servicios automotrices rápidos, confiables y con seguimiento.

![User Persona Vehicle Owner](docs/assets/chapter-2/needfinding/user-persona-3-vehicle-owner.png)

#### 2.3.2. User Task Matrix


<p style="text-align: justify;">
El User Task Matrix presenta de manera consolidada las tareas que realizan los tres User Personas identificados para el proyecto AutoService: Carlos Mendoza (Mecánico Independiente), Lucía Fernández (Administradora de Taller) y Ana Rojas (Cliente/Propietaria de vehículo).
</p>

<p style="text-align: justify;">
Es importante destacar que las tareas descritas en esta matriz representan actividades que los segmentos realizan actualmente en su operación diaria (usando cuadernos, Excel, WhatsApp o llamados telefónicos), independientemente de la existencia de nuestra solución de software. Estas tareas son la base para identificar oportunidades de mejora mediante la digitalización.
</p>

<table>
  <thead>
    <tr>
      <th rowspan="2" style="text-align: center; vertical-align: middle;">User Task<br>(Tarea del Usuario)</th>
      <th colspan="2" style="text-align: center; ">Carlos Mendoza<br>(Mecánico)</th>
      <th colspan="2" style="text-align: center; ">Lucía Fernández<br>(Administradora)</th>
      <th colspan="2" style="text-align: center; ">Ana Rojas<br>(Cliente)</th>
    </tr>
    <tr>
      <th style="text-align: center;">Frecuencia</th>
      <th style="text-align: center;">Importancia</th>
      <th style="text-align: center;">Frecuencia</th>
      <th style="text-align: center;">Importancia</th>
      <th style="text-align: center;">Frecuencia</th>
      <th style="text-align: center;">Importancia</th>
    </tr>
  </thead>
  <tbody>
    <tr><td>Diagnosticar fallas del vehículo</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Baja</td><td style="text-align:center">Media</td><td style="text-align:center">Baja</td><td style="text-align:center">Crítica</td></tr>
    <tr><td>Registrar información de clientes y vehículos</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Baja</td><td style="text-align:center">Media</td></tr>
    <tr><td>Gestionar y coordinar tareas del personal</td><td style="text-align:center">Media</td><td style="text-align:center">Alta</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">N/A</td><td style="text-align:center">N/A</td></tr>
    <tr><td>Comunicar el estado de la reparación al cliente</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Media</td><td style="text-align:center">Alta</td></tr>
    <tr><td>Realizar seguimiento al progreso del servicio</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td></tr>
    <tr><td>Gestionar pagos y facturación</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Baja</td><td style="text-align:center">Crítica</td></tr>
    <tr><td>Programar citas y recepción de vehículos</td><td style="text-align:center">Alta</td><td style="text-align:center">Alta</td><td style="text-align:center">Alta</td><td style="text-align:center">Crítica</td><td style="text-align:center">Baja</td><td style="text-align:center">Alta</td></tr>
    <tr><td>Consultar historial de mantenimientos</td><td style="text-align:center">Media</td><td style="text-align:center">Alta</td><td style="text-align:center">Alta</td><td style="text-align:center">Alta</td><td style="text-align:center">Baja</td><td style="text-align:center">Alta</td></tr>
  </tbody>
</table>

#### Análisis del User Task Matrix

<p style="text-align: justify;">
Al analizar la matriz, se identifican patrones significativos y puntos de dolor compartidos entre los segmentos:</p>

**1. Coincidencias (Puntos Críticos):**
<p style="text-align: justify;">
La tarea de <strong>"Realizar seguimiento al progreso del servicio"</strong> es crítica y de alta frecuencia tanto para Carlos y Lucía (quienes deben gestionarlo) como para Ana (quien necesita saberlo). Actualmente, esta tarea genera fricción: el mecánico pierde tiempo respondiendo llamadas y el cliente siente desconfianza por falta de información. Esto representa una oportunidad central para AutoService: automatizar este seguimiento para reducir la carga administrativa y aumentar la transparencia.</p>

**2. Diferencias por Segmento:**
<ul style="text-align: justify; margin-top: 0.5em; margin-bottom: 1.5em; padding-left: 1.5em;">
  <li><strong>Carlos Mendoza (Operativo):</strong> Sus tareas de mayor importancia giran en torno al diagnóstico técnico y la comunicación directa. Su frecuencia en tareas administrativas complejas (como reportes detallados) es menor, pero su necesidad de simplicidad es máxima para no entorpecer su trabajo manual.</li>
  <li><strong>Lucía Fernández (Gestión):</strong> Tiene una carga crítica en la <strong>coordinación de personal</strong> y la gestión de la información general. A diferencia de Carlos, ella necesita una visión panorámica del taller para delegar tareas, lo cual es un punto de dolor actual debido a la falta de herramientas de control.</li>
  <li><strong>Ana Rojas (Cliente):</strong> Su interacción es más esporádica en frecuencia (lleva el auto ocasionalmente), pero la importancia es crítica. Su principal frustración es la dependencia de llamadas telefónicas para enterarse del estado de su vehículo.</li>
</ul>

**3. Oportunidades para la Solución:**
<p style="text-align: justify;">
Existe una clara oportunidad para digitalizar la <strong>"Comunicación del estado"</strong>. Actualmente, esta tarea consume recursos del taller (tiempo de Carlos y Lucía) y genera insatisfacción en Ana. Al transformar esta tarea manual en una funcionalidad de consulta autónoma (Dashboard para clientes), se reduce la carga operativa para el taller y se satisface la necesidad de transparencia del cliente.</p>


#### 2.3.3. User Journey Mapping


##### Journey Map 1: Mechanic

Representa el flujo de trabajo del mecánico desde la recepción del vehículo hasta la finalización del servicio.

![Journey Map Mechanic](docs/assets/chapter-2/needfinding/journey-map-1-mechanic.png)


#### Journey Map 2: Workshop Manager

Describe la gestión operativa del administrador del taller y la supervisión de procesos.

![Journey Map Workshop Manager](docs/assets/chapter-2/needfinding/journey-map-2-workshop-manager.png)


#### Journey Map 3: Vehicle Owner

Muestra la experiencia del cliente al solicitar, seguir y recibir un servicio automotriz.

![Journey Map Vehicle Owner](docs/assets/chapter-2/needfinding/journey-map-3-vehicle-owner.png)


#### 2.3.4. Empathy Mapping


#### Empathy Map 1: Mechanic

Identifica pensamientos, emociones y necesidades del mecánico durante su trabajo.

![Empathy Map Mechanic](docs/assets/chapter-2/needfinding/empathy-map-1-mechanic.png)


#### Empathy Map 2: Workshop Manager

Refleja las preocupaciones, objetivos y frustraciones del administrador del taller.

![Empathy Map Workshop Manager](docs/assets/chapter-2/needfinding/empathy-map-2-workshop-manager.png)


#### Empathy Map 3: Vehicle Owner

Muestra las expectativas, emociones y percepciones del cliente.

![Empathy Map Vehicle Owner](docs/assets/chapter-2/needfinding/empathy-map-3-vehicle-owner.png)


---

### 2.4. Big Picture EventStorming


<p style="text-align: justify;">
En esta sección se presenta el **Big Picture EventStorming**, una técnica colaborativa utilizada para explorar el dominio del negocio de manera visual y de alto nivel. A través de una línea de tiempo horizontal, el equipo ha identificado los eventos significativos (naranjas) que ocurren en el flujo de trabajo de un taller automotriz, las acciones que los desencadenan (comandos azules), los actores involucrados (amarillos) y las reglas de negocio automatizadas (políticas moradas).
</p>

<p style="text-align: justify;">
Este artefacto nos permite comprender la secuencia natural de los procesos, desde la configuración inicial del taller hasta el cierre financiero y la generación de reportes, exponiendo oportunidades de automatización y **"Hotspots"** (puntos de dolor) críticos en la comunicación entre el taller y el cliente.
</p>

> **Nota:** El diagrama a continuación representa la interacción entre los User Personas (Carlos, Lucía y Ana) y el sistema propuesto, siguiendo una línea de tiempo de izquierda a derecha.

![Big Picture EventStorming](docs/assets/chapter-2/big-picture-event-storming.png)

#### Estructura del Flujo (Timeline)

<div style="text-align: justify; line-height: 1.6; margin-top: 1em; margin-bottom: 1.5em;">
<p>Para facilitar la comprensión del modelo, el Event Storming se ha organizado en <strong>5 bloques lógicos</strong> que representan las fases del ciclo de vida del servicio:</p>

<ol style="padding-left: 1.5em; margin-bottom: 1.5em;">
  <li><strong>Onboarding & Registration (Izquierda):</strong><br>
  Inicia con el <strong>System Admin</strong> registrando el taller (<code>Register Workshop</code> → <code>Workshop Account Created</code>). Se registran los actores clave: el <strong>Administrator</strong> o <strong>Mechanic</strong> registran clientes (<code>Client Registered</code>) y el <strong>Mechanic</strong> registra los vehículos (<code>Vehicle Registered</code>).<br>
  <em>Hotspot identificado:</em> <code>Data scattered across notebooks</code> (Datos dispersos en cuadernos), reflejando la desorganización actual.</li>

  <li><strong>Intake & Assessment (Centro-Superior):</strong><br>
  El <strong>Mechanic</strong> crea la orden de trabajo (<code>Create Work Order</code> → <code>Work Order Created</code>). Se aplica una política automática: <code>Code Generation Policy</code> que genera un código de seguimiento (<code>Tracking Code Generated</code>). El mecánico detalla las tareas (<code>Add task</code> → <code>Task Added</code>) y el administrador asigna turnos (<code>Assign Shift</code>).<br>
  <em>Hotspot identificado:</em> <code>Difficulty in estimating actual costs</code> (Dificultad para estimar costos reales), un problema que la digitalización busca resolver.</li>

  <li><strong>Execution & Follow-up (Centro-Inferior):</strong><br>
  El <strong>Mechanic</strong> inicia las tareas (<code>Start task</code> → <code>Task Started</code> → <code>Task Completed</code>). Se actualiza el estado del vehículo (<code>Update Vehicle Status</code> → <code>Vehicle Status Updated</code>).<br>
  <strong>Punto Clave:</strong> Aquí interviene la política <code>Notify Client Policy</code>. Al cambiar el estado, el sistema envía una notificación (<code>Email/SMS System</code> → <code>Notification Sent</code>), manteniendo al cliente informado sin llamadas manuales.<br>
  El <strong>Client</strong> puede consultar el estado ingresando su código (<code>Enter Tracking Code</code> → <code>Tracking Session Started</code>).<br>
  <em>Hotspot identificado:</em> <code>The customer keeps calling to ask about the status</code> (El cliente llama constantemente), resolviendo la frustración de Ana.</li>

  <li><strong>Closure & Billing (Derecha-Inferior):</strong><br>
  El <strong>Mechanic</strong> completa la orden (<code>Complete Work Order</code> → <code>Work Order Completed</code>). El <strong>Administrator</strong> genera la factura (<code>Generate Invoice</code> → <code>Invoice Generated</code>). El <strong>Client</strong> procesa el pago (<code>Process Payment</code> → <code>Payment Processed</code>), interactuando con la <code>Payment Gateway</code>.<br>
  <em>Hotspot identificado:</em> <code>Manual error in calculating totals</code> (Error manual en el cálculo de totales).</li>

  <li><strong>Reports & Metrics (Derecha-Superior):</strong><br>
  El <strong>Administrator</strong> visualiza métricas de productividad (<code>View Productivity Metrics</code> → <code>Workshop Productivity Calculated</code>). Se analizan tendencias de servicio (<code>Analyze Service Trends</code> → <code>Service Trends Analyzed</code>). Se generan reportes diarios de ingresos bajo la <code>Daily Closing Policy</code>.</li>
</ol>

#### Leyenda de Elementos

<p>Para la correcta interpretación del diagrama, se han utilizado los estándares visuales de EventStorming:</p>
<ul style="padding-left: 1.5em; margin-bottom: 1.5em;">
  <li>🟧 <strong>Domain Events (Naranja):</strong> Hechos relevantes que ya ocurrieron en el negocio (ej. <code>Vehicle Status Updated</code>, <code>Invoice Generated</code>).</li>
  <li>🟦 <strong>Commands (Azul):</strong> Acciones o decisiones que inician un proceso (ej. <code>Create Work Order</code>, <code>Process Payment</code>).</li>
  <li>🟨 <strong>Actors (Amarillo):</strong> Usuarios o sistemas que ejecutan los comandos (System Admin, Mechanic, Administrator, Client).</li>
  <li>🟪 <strong>Policies (Morado):</strong> Reglas de negocio o automatizaciones (ej. <code>Notify Client Policy</code>, <code>Code Generation Policy</code>).</li>
  <li>🟥 <strong>External Systems (Rosa fuerte):</strong> Servicios de terceros integrados (Email/SMS System, Payment Gateway).</li>
  <li>🔴 <strong>Hotspots (Rojo claro):</strong> Puntos de dolor o problemas identificados en el proceso actual.</li>
</ul>

#### Hotspots y Oportunidades de Mejora

<p>Durante el modelado, detectamos áreas problemáticas en el proceso actual que justifican la existencia de nuestra solución <strong>AutoService</strong>:</p>
<ol style="padding-left: 1.5em; margin-bottom: 1em;">
  <li><strong>Falta de Transparencia (Bloque Execution):</strong><br>
  <em>Problema:</em> El evento <code>Vehicle Status Updated</code> no llegaba al cliente, generando llamadas constantes.<br>
  <em>Solución:</em> La política <code>Notify Client Policy</code> automatiza la comunicación.</li>

  <li><strong>Desorganización Operativa (Bloque Onboarding/Intake):</strong><br>
  <em>Problema:</em> Datos dispersos en cuadernos y dificultad para estimar costos.<br>
  <em>Solución:</em> Centralización digital y cálculo automático basado en tareas registradas.</li>

  <li><strong>Errores Administrativos (Bloque Closure):</strong><br>
  <em>Problema:</em> Errores manuales al calcular totales de facturas.<br>
  <em>Solución:</em> Generación automática de invoices basada en los servicios completados.</li>
</ol>
</div>


### 2.5. Ubiquitous Language

<p style="text-align: justify;">
Para garantizar una comunicación clara y sin ambigüedades entre los miembros del equipo de desarrollo y los stakeholders del negocio, se ha definido el siguiente glosario de términos (Ubiquitous Language). Estos términos representan los conceptos fundamentales del dominio de la gestión de talleres automotrices.
</p>

<table>
  <thead>
    <tr>
      <th style="text-align: center; vertical-align: middle; ">Término<br>(Inglés)</th>
      <th style="text-align: center; vertical-align: middle; ">Equivalente<br>(Español)</th>
      <th style="text-align: left; vertical-align: middle; ">Definición</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align: center;"><strong>Work Order</strong></td>
      <td style="text-align: center;">Orden de Trabajo</td>
      <td>Documento digital que registra la solicitud de servicio de un vehículo, incluyendo los trabajos a realizar, los costos estimados y el estado actual del proceso.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Service Request</strong></td>
      <td style="text-align: center;">Solicitud de Servicio</td>
      <td>Petición inicial realizada por el cliente para el mantenimiento o reparación de su vehículo.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Mechanic / Technician</strong></td>
      <td style="text-align: center;">Mecánico / Técnico</td>
      <td>Usuario del sistema encargado de ejecutar las tareas técnicas de reparación y diagnóstico en los vehículos.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Workshop Administrator</strong></td>
      <td style="text-align: center;">Administrador del Taller</td>
      <td>Usuario responsable de gestionar las órdenes de trabajo, asignar tareas al personal, controlar inventarios y gestionar la facturación.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Vehicle</strong></td>
      <td style="text-align: center;">Vehículo</td>
      <td>El objeto físico (auto, moto, camión) que ingresa al taller para recibir servicio. Se asocia a un cliente específico.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Diagnostic</strong></td>
      <td style="text-align: center;">Diagnóstico</td>
      <td>Evaluación técnica realizada por el mecánico para identificar fallas o necesidades de mantenimiento en el vehículo.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Quote / Budget</strong></td>
      <td style="text-align: center;">Cotización / Presupuesto</td>
      <td>Estimación de costos detallada que se presenta al cliente antes de iniciar la reparación.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Maintenance History</strong></td>
      <td style="text-align: center;">Historial de Mantenimiento</td>
      <td>Registro cronológico de todos los servicios, reparaciones y cambios de piezas realizados a un vehículo a lo largo del tiempo.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Status</strong></td>
      <td style="text-align: center;">Estado</td>
      <td>Indicador del progreso de una Orden de Trabajo (ej. Pendiente, En Proceso, Listo, Entregado).</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Spare Part</strong></td>
      <td style="text-align: center;">Repuesto</td>
      <td>Pieza o componente de inventario que se utiliza para reemplazar piezas dañadas durante la reparación.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Client / Customer</strong></td>
      <td style="text-align: center;">Cliente</td>
      <td>Usuario final propietario del vehículo que contrata los servicios del taller.</td>
    </tr>
    <tr>
      <td style="text-align: center;"><strong>Staff</strong></td>
      <td style="text-align: center;">Personal</td>
      <td>Conjunto de mecánicos y personal de apoyo que labora en el taller.</td>
    </tr>
  </tbody>
</table>

---

## Capítulo III: Requirements Specification

En la presente sección se definen los requerimientos del sistema a partir de un enfoque ágil, utilizando artefactos como historias de usuario, historias técnicas, impact mapping y el product backlog. Estos elementos permiten estructurar las necesidades del producto, alinearlas con los objetivos del negocio y establecer una base clara para la planificación y desarrollo iterativo del sistema.

### 3.1. User Stories

En la presente sección se definen los requisitos del sistema consolidados junto con el conjunto de Epics, User Stories y Technical Stories identificados para el proyecto. Este cuadro permite visualizar claramente la jerarquía y relación entre los bloques funcionales de alto nivel (Epics), las funcionalidades descritas desde la perspectiva de los distintos actores del sistema (User Stories) y los requerimientos fundamentales de arquitectura, integración y despliegue (Technical Stories). Asimismo, cada historia incluye sus respectivos Criterios de Aceptación. Siguiendo los estándares de la industria y las exigencias del proyecto, estos criterios han sido redactados en formato Gherkin (Given-When-Then). A continuación, se presenta la tabla detallada:

<div align="center">
<table style="margin: auto; text-align: left; width: 100%;">
<thead>
  <tr>
    <th style="width: 10%;">Epic / Story ID</th>
    <th style="width: 20%;">Título</th>
    <th style="width: 30%;">Descripción</th>
    <th style="width: 30%;">Criterios de Aceptación</th>
    <th style="width: 10%;">Relacionado con (Epic ID)</th>
  </tr>
    </thead>
    <tbody>
    <!-- EPICS -->
  <tr>
    <td>EP-01</td>
    <td>Landing Page y presencia web</td>
    <td>Como usuario potencial, quiero visualizar una landing page informativa del producto, para conocer sus beneficios, funcionalidades y acceder a la plataforma.</td>
    <td><b>Given</b> que un usuario potencial accede al identificador web del sistema, <b>When</b> el sistema procesa la solicitud, <b>Then</b> el sistema muestra la información del producto y sus respectivos llamados a la acción de manera adaptable al dispositivo.</td>
    <td>-</td>
  </tr>
    <tr>
    <td>EP-02</td>
    <td>Gestión de usuarios y autenticación</td>
    <td>Como usuario del sistema, quiero iniciar sesión y acceder según mi rol, para utilizar las funcionalidades correspondientes.</td>
    <td><b>Given</b> que un usuario se encuentra registrado en el sistema, <b>When</b> el usuario envía sus credenciales de acceso, <b>Then</b> el sistema valida la identidad y concede los permisos asociados a su rol específico (administrador o mecánico).</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-03</td>
    <td>Gestión de vehículos y órdenes</td>
    <td>Como administrador, quiero registrar vehículos y gestionar órdenes de trabajo, para organizar los servicios del taller.</td>
    <td><b>Given</b> que un administrador gestiona el flujo del taller, <b>When</b> el administrador ingresa los datos de un vehículo y un servicio, <b>Then</b> el sistema registra el vehículo, crea la orden de trabajo correspondiente y le asigna un estado inicial.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-04</td>
    <td>Gestión de tareas y flujo de trabajo</td>
    <td>Como administrador, quiero definir tareas y gestionar su progreso, para controlar el avance de los servicios.</td>
    <td><b>Given</b> que un administrador administra una orden de trabajo, <b>When</b> el administrador define actividades asociadas a un vehículo, <b>Then</b> el sistema registra las tareas, sus estados y calcula el progreso global del servicio.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-05</td>
    <td>Gestión de personal (staff)</td>
    <td>Como administrador, quiero gestionar el personal mecánico, para asignar tareas y visualizar su desempeño.</td>
    <td><b>Given</b> que el administrador gestiona el talento humano, <b>When</b> el administrador asigna cargas de trabajo a los registros de mecánicos, <b>Then</b> el sistema asocia las tareas al personal y expone el nivel de ocupación de cada uno.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-06</td>
    <td>Seguimiento del vehículo (cliente)</td>
    <td>Como cliente, quiero consultar el estado de mi vehículo mediante un código, para conocer el progreso del servicio.</td>
    <td><b>Given</b> que un cliente posee un código de seguimiento válido, <b>When</b> el cliente somete el código al sistema, <b>Then</b> el sistema expone el progreso del vehículo, las tareas asociadas y las fechas estimadas de entrega.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-07</td>
    <td>Reportes e indicadores</td>
    <td>Como administrador, quiero visualizar métricas del taller, para tomar decisiones informadas.</td>
    <td><b>Given</b> que el administrador requiere información de negocio, <b>When</b> el administrador solicita las métricas operativas, <b>Then</b> el sistema procesa los datos y presenta los ingresos, servicios realizados e indicadores generales.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-08</td>
    <td>Diseño UX/UI del sistema</td>
    <td>Como usuario, quiero interactuar con una interfaz clara y usable, para tener una buena experiencia en la aplicación.</td>
    <td><b>Given</b> que cualquier usuario interactúa con la plataforma, <b>When</b> el usuario navega por las distintas vistas, <b>Then</b> el sistema presenta la información de forma jerarquizada, responsiva y manteniendo consistencia gráfica.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-09</td>
    <td>Arquitectura y backend del sistema</td>
    <td>Como sistema, quiero contar con una arquitectura basada en servicios, para garantizar escalabilidad y mantenimiento.</td>
    <td><b>Given</b> que el sistema atiende peticiones de clientes, <b>When</b> se realizan interacciones de negocio, <b>Then</b> el sistema procesa la lógica en una API REST modularizada y separada de la capa de presentación.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-10</td>
    <td>Base de datos y persistencia</td>
    <td>Como sistema, quiero almacenar la información de manera estructurada, para garantizar consistencia y acceso a los datos.</td>
    <td><b>Given</b> que el sistema genera y modifica registros operativos, <b>When</b> el sistema ejecuta transacciones de almacenamiento, <b>Then</b> el sistema persiste los datos conservando la integridad referencial y las relaciones del modelo.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-11</td>
    <td>Integraciones y servicios externos</td>
    <td>Como sistema, quiero integrarme con APIs externas, para ampliar funcionalidades como notificaciones y generación de comprobantes.</td>
    <td><b>Given</b> que el sistema requiere procesar operaciones delegadas, <b>When</b> el sistema contacta a un proveedor externo, <b>Then</b> el sistema envía la solicitud, parsea la respuesta y maneja posibles escenarios de error.</td>
    <td>-</td>
    </tr>
    <tr>
    <td>EP-12</td>
    <td>Despliegue y configuración</td>
    <td>Como developer, quiero desplegar el sistema en la nube, para que sea accesible y funcional para los usuarios.</td>
    <td><b>Given</b> que el equipo requiere disponibilizar la aplicación, <b>When</b> el entorno de producción se encuentra configurado, <b>Then</b> el sistema opera de forma pública y responde a las peticiones externas.</td>
    <td>-</td>
    </tr>
<!-- USER STORIES (US) -->
  <tr>
    <td>US-01</td>
    <td>Visualizar landing page</td>
    <td>Como usuario potencial, quiero acceder a la landing page, para conocer el producto y sus beneficios.</td>
    <td><b>Given</b> que un usuario potencial navega a la URL pública, <b>When</b> el sistema procesa la solicitud, <b>Then</b> el sistema presenta el contenido informativo del producto dividido en secciones estructuradas.</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-02</td>
    <td>Visualizar beneficios del sistema</td>
    <td>Como usuario potencial, quiero ver los beneficios del sistema, para entender su valor.</td>
    <td><b>Given</b> que el usuario potencial examina la información pública, <b>When</b> el sistema carga el contenido, <b>Then</b> el sistema expone una lista clara y comprensible con los beneficios clave del producto.</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-03</td>
    <td>Acceder a la plataforma desde CTA</td>
    <td>Como usuario potencial, quiero hacer clic en un botón de acción, para acceder al sistema.</td>
    <td><b>Given</b> que el usuario potencial requiere ingresar a las funcionalidades operativas, <b>When</b> el usuario activa un llamado a la acción (CTA), <b>Then</b> el sistema redirige la navegación hacia las pantallas de autenticación o seguimiento.</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-04</td>
    <td>Visualizar landing responsive</td>
    <td>Como usuario, quiero que la landing sea responsive, para poder verla desde mi celular.</td>
    <td><b>Given</b> que el usuario accede desde un dispositivo con pantalla reducida, <b>When</b> el sistema renderiza el entorno gráfico, <b>Then</b> el sistema adapta los elementos fluidamente sin alterar su legibilidad ni quebrar la navegación.</td>
    <td>EP-01</td>
  </tr>
  <tr>
    <td>US-05</td>
    <td>Iniciar sesión</td>
    <td>Como usuario del sistema, quiero iniciar sesión, para acceder a mis funcionalidades.</td>
    <td><b>Given</b> que un usuario proporciona credenciales válidas, <b>When</b> el usuario somete la solicitud de autenticación, <b>Then</b> el sistema autoriza el ingreso y redirige al panel de control correspondiente.</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-06</td>
    <td>Acceso según rol</td>
    <td>Como usuario, quiero ver funcionalidades según mi rol, para usar el sistema correctamente.</td>
    <td><b>Given</b> que un usuario autenticado posee un rol específico, <b>When</b> el usuario intenta acceder a distintas vistas, <b>Then</b> el sistema habilita el panel completo para administradores y limita la vista a tareas asignadas para mecánicos.</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-07</td>
    <td>Cerrar sesión</td>
    <td>Como usuario, quiero cerrar sesión, para proteger mi cuenta.</td>
    <td><b>Given</b> que un usuario activo decide terminar su actividad, <b>When</b> el usuario invoca la acción de cierre de sesión, <b>Then</b> el sistema invalida la sesión actual y redirige a la vista de autenticación.</td>
    <td>EP-02</td>
  </tr>
  <tr>
    <td>US-08</td>
    <td>Registrar vehículo</td>
    <td>Como administrador, quiero registrar un vehículo, para gestionar su servicio.</td>
    <td><b>Given</b> que un administrador posee los datos de un cliente y su vehículo, <b>When</b> el administrador ingresa y confirma la información, <b>Then</b> el sistema almacena permanentemente la relación entre el cliente y el vehículo.</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-09</td>
    <td>Crear orden de trabajo</td>
    <td>Como administrador, quiero crear una orden de trabajo, para iniciar un servicio.</td>
    <td><b>Given</b> que existe un vehículo registrado, <b>When</b> el administrador genera un nuevo servicio para el vehículo, <b>Then</b> el sistema crea la orden, asocia el vehículo y estampa la fecha de ingreso.</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-10</td>
    <td>Visualizar vehículos en el taller</td>
    <td>Como administrador, quiero ver los vehículos activos, para conocer el estado del taller.</td>
    <td><b>Given</b> que existen vehículos procesándose, <b>When</b> el administrador solicita visualizar el inventario activo, <b>Then</b> el sistema retorna una lista con la identificación de cada vehículo y su estado actual.</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-11</td>
    <td>Actualizar estado del vehículo</td>
    <td>Como administrador, quiero actualizar el estado de un vehículo, para reflejar su progreso.</td>
    <td><b>Given</b> que un vehículo se encuentra asociado a una orden, <b>When</b> el administrador modifica la etapa del vehículo, <b>Then</b> el sistema persiste el nuevo estado (pendiente, en proceso o listo) y actualiza su visualización general.</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-12</td>
    <td>Visualizar detalle del vehículo</td>
    <td>Como administrador, quiero ver el detalle de un vehículo, para revisar información completa.</td>
    <td><b>Given</b> que un administrador selecciona un vehículo específico, <b>When</b> el sistema procesa la consulta, <b>Then</b> el sistema expone conjuntamente los datos del cliente, características del vehículo y el detalle de la orden.</td>
    <td>EP-03</td>
  </tr>
  <tr>
    <td>US-13</td>
    <td>Crear tareas para vehículo</td>
    <td>Como administrador, quiero crear tareas para un vehículo, para definir los trabajos a realizar.</td>
    <td><b>Given</b> que una orden de trabajo se encuentra activa, <b>When</b> el administrador ingresa descripciones de actividades, <b>Then</b> el sistema vincula y almacena dichas tareas con el vehículo correspondiente.</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-14</td>
    <td>Asignar estado a tarea</td>
    <td>Como administrador, quiero definir el estado de una tarea, para controlar su progreso.</td>
    <td><b>Given</b> que una tarea pertenece a un vehículo, <b>When</b> el administrador reporta un cambio de avance, <b>Then</b> el sistema actualiza la tarea a un estado válido (pendiente, en proceso o completado).</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-15</td>
    <td>Visualizar progreso por vehículo</td>
    <td>Como administrador, quiero ver el progreso de un vehículo, para conocer el avance del servicio.</td>
    <td><b>Given</b> que un vehículo tiene un conjunto de tareas asignadas, <b>When</b> el administrador visualiza el vehículo, <b>Then</b> el sistema calcula y muestra el porcentaje de avance basado en las tareas completadas.</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-16</td>
    <td>Editar tareas</td>
    <td>Como administrador, quiero editar tareas, para actualizar información del servicio.</td>
    <td><b>Given</b> que existe una tarea registrada, <b>When</b> el administrador provee nueva información para dicha tarea, <b>Then</b> el sistema sobrescribe los datos anteriores y persiste los cambios correctamente.</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-17</td>
    <td>Eliminar tareas</td>
    <td>Como administrador, quiero eliminar tareas, para corregir errores o cambios en el servicio.</td>
    <td><b>Given</b> que una tarea ya no es requerida, <b>When</b> el administrador emite la orden de supresión, <b>Then</b> el sistema remueve la tarea del registro sin afectar el resto de las actividades de la orden.</td>
    <td>EP-04</td>
  </tr>
  <tr>
    <td>US-18</td>
    <td>Registrar mecánico</td>
    <td>Como administrador, quiero registrar un mecánico, para gestionar el personal del taller.</td>
    <td><b>Given</b> que el administrador cuenta con la información del talento, <b>When</b> el administrador ingresa el nombre y especialidad, <b>Then</b> el sistema crea el registro del personal e incluyé al mecánico en el padrón activo.</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-19</td>
    <td>Visualizar lista de mecánicos</td>
    <td>Como administrador, quiero ver todos los mecánicos registrados, para gestionar el equipo.</td>
    <td><b>Given</b> que existen profesionales registrados, <b>When</b> el administrador requiere observar el staff, <b>Then</b> el sistema lista la información básica de cada mecánico permitiendo el acceso a sus detalles individuales.</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-20</td>
    <td>Asignar tareas a mecánico</td>
    <td>Como administrador, quiero asignar tareas a mecánicos, para distribuir el trabajo.</td>
    <td><b>Given</b> que existe una tarea libre y un mecánico disponible, <b>When</b> el administrador asocia ambos registros, <b>Then</b> el sistema vincula la actividad al mecánico y la refleja en su lista personal de pendientes.</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-21</td>
    <td>Visualizar carga de trabajo</td>
    <td>Como administrador, quiero ver la carga de trabajo de cada mecánico, para equilibrar tareas.</td>
    <td><b>Given</b> que los mecánicos tienen actividades en curso, <b>When</b> el administrador consulta el nivel de ocupación, <b>Then</b> el sistema expone la cantidad y detalle de tareas vigentes por cada profesional.</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-22</td>
    <td>Ver detalle de mecánico</td>
    <td>Como administrador, quiero ver el detalle de un mecánico, para conocer su desempeño.</td>
    <td><b>Given</b> que el administrador inspecciona a un mecánico en particular, <b>When</b> el sistema procesa la petición, <b>Then</b> el sistema muestra su información personal, especialidad y el historial de tareas completadas.</td>
    <td>EP-05</td>
  </tr>
  <tr>
    <td>US-23</td>
    <td>Ingresar código de seguimiento</td>
    <td>Como cliente, quiero ingresar un código, para consultar mi vehículo.</td>
    <td><b>Given</b> que un cliente requiere información externa, <b>When</b> el cliente ingresa un identificador válido provisto por el taller, <b>Then</b> el sistema autentica el código y habilita la vista de progreso asociada a dicho identificador.</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-24</td>
    <td>Visualizar estado del vehículo</td>
    <td>Como cliente, quiero ver el estado del vehículo, para conocer su progreso.</td>
    <td><b>Given</b> que un cliente valida su acceso con el código, <b>When</b> el sistema entrega el panel de cliente, <b>Then</b> el sistema muestra en tiempo real la etapa global de procesamiento del vehículo (pendiente, proceso o listo).</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-25</td>
    <td>Visualizar tareas del vehículo</td>
    <td>Como cliente, quiero ver las tareas realizadas, para entender el trabajo.</td>
    <td><b>Given</b> que el cliente explora el detalle de su servicio, <b>When</b> el sistema expone los datos, <b>Then</b> el sistema lista las tareas declaradas para su orden mostrando el estado individual de cada una.</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-26</td>
    <td>Visualizar fechas estimadas</td>
    <td>Como cliente, quiero ver fechas estimadas, para saber cuándo estará listo.</td>
    <td><b>Given</b> que una orden tiene un estimado de conclusión proyectado, <b>When</b> el cliente visualiza el seguimiento, <b>Then</b> el sistema expone la fecha proyectada de finalización en un formato de fácil lectura.</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-27</td>
    <td>Visualizar costos del servicio</td>
    <td>Como cliente, quiero ver el costo estimado, para conocer el precio del servicio.</td>
    <td><b>Given</b> que la orden de trabajo posee valores monetarios tasados, <b>When</b> el cliente revisa la información de seguimiento, <b>Then</b> el sistema presenta el costo económico relacionado a las tareas planificadas.</td>
    <td>EP-06</td>
  </tr>
  <tr>
    <td>US-28</td>
    <td>Visualizar ingresos</td>
    <td>Como administrador, quiero ver los ingresos del taller, para evaluar rendimiento.</td>
    <td><b>Given</b> que existen órdenes facturadas en el sistema, <b>When</b> el administrador accede al panel de métricas, <b>Then</b> el sistema calcula y muestra de forma actualizada la sumatoria total de los montos percibidos.</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-29</td>
    <td>Visualizar servicios realizados</td>
    <td>Como administrador, quiero ver los servicios realizados, para analizar actividad.</td>
    <td><b>Given</b> que existen órdenes con estado completado, <b>When</b> el administrador solicita el reporte operativo, <b>Then</b> el sistema extrae y enlista históricamente los servicios procesados detallando los vehículos involucrados.</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-30</td>
    <td>Identificar trabajos frecuentes</td>
    <td>Como administrador, quiero identificar trabajos frecuentes, para optimizar servicios.</td>
    <td><b>Given</b> que el sistema posee un volumen de tareas históricas, <b>When</b> el administrador demanda tendencias operativas, <b>Then</b> el sistema agrupa y ordena las tareas listando aquellas de mayor incidencia en las órdenes.</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-31</td>
    <td>Visualizar métricas del sistema</td>
    <td>Como administrador, quiero ver métricas generales, para tomar decisiones.</td>
    <td><b>Given</b> que el sistema registra la trazabilidad del negocio, <b>When</b> el administrador visualiza el dashboard principal, <b>Then</b> el sistema consolida la información en resúmenes estadísticos de sencilla interpretación.</td>
    <td>EP-07</td>
  </tr>
  <tr>
    <td>US-32</td>
    <td>Navegar interfaz intuitiva</td>
    <td>Como usuario, quiero una interfaz clara, para usar el sistema fácilmente.</td>
    <td><b>Given</b> que un usuario explora la plataforma, <b>When</b> el usuario transita entre distintos módulos, <b>Then</b> el sistema proporciona un ruteo simple evitando flujos confusos y presentando opciones evidentes de navegación.</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-33</td>
    <td>Visualizar diseño consistente</td>
    <td>Como usuario, quiero consistencia visual, para tener mejor experiencia.</td>
    <td><b>Given</b> que el sistema renderiza diferentes componentes, <b>When</b> un usuario visualiza múltiples vistas, <b>Then</b> el sistema aplica estrictamente un estándar uniforme de colores, tipografías y proporciones en toda la herramienta.</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-34</td>
    <td>Usar sistema en móvil</td>
    <td>Como usuario, quiero usar el sistema en mi celular, para acceder desde cualquier lugar.</td>
    <td><b>Given</b> que un usuario interactúa mediante la pantalla de un smartphone, <b>When</b> se solicita información de las vistas, <b>Then</b> el sistema reorganiza los componentes manteniendo la operatividad y sin perder interacciones primarias.</td>
    <td>EP-08</td>
  </tr>
  <tr>
    <td>US-35</td>
    <td>Visualizar información clara</td>
    <td>Como usuario, quiero ver la información organizada, para entender rápidamente.</td>
    <td><b>Given</b> que un usuario lee agrupaciones de datos, <b>When</b> el sistema plasma listas o reportes, <b>Then</b> el sistema utiliza estructuras jerárquicas como tarjetas que favorecen la lectura escaneable de los contenidos.</td>
    <td>EP-08</td>
  </tr>

  <!-- TECHNICAL STORIES (TS) -->
  <tr>
    <td>TS-01</td>
    <td>Definir arquitectura del sistema</td>
    <td>Como developer, quiero definir la arquitectura del sistema, para asegurar escalabilidad y mantenimiento.</td>
    <td><b>Given</b> que el equipo técnico diseña la solución base, <b>When</b> se consolida la documentación arquitectónica, <b>Then</b> el diseño refleja una separación de capas nítida que independiza el desarrollo frontend del backend.</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <td>TS-02</td>
    <td>Implementar API REST</td>
    <td>Como sistema, quiero exponer una API REST, para permitir comunicación con el frontend.</td>
    <td><b>Given</b> que el cliente envía peticiones al servidor, <b>When</b> los endpoints son consumidos con métodos HTTP válidos, <b>Then</b> el sistema procesa la lógica y retorna las estructuras de respuesta estrictamente en formato JSON.</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <td>TS-03</td>
    <td>Estructurar backend modular</td>
    <td>Como developer, quiero organizar el backend en módulos, para mejorar mantenibilidad.</td>
    <td><b>Given</b> que el código del backend es desplegado o revisado, <b>When</b> se inspecciona la base de código, <b>Then</b> los repositorios denotan una segregación funcional basada en controladores, servicios y modelos que fomenta la reutilización.</td>
    <td>EP-09</td>
  </tr>
  <tr>
    <td>TS-04</td>
    <td>Diseñar modelo de base de datos</td>
    <td>Como developer, quiero definir el modelo de datos, para estructurar la información del sistema.</td>
    <td><b>Given</b> que el sistema requiere soporte para persistencia, <b>When</b> el esquema es evaluado, <b>Then</b> el diseño expone entidades concretas con tipos de datos correctos y constricciones válidas para el negocio.</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <td>TS-05</td>
    <td>Implementar persistencia de datos</td>
    <td>Como sistema, quiero guardar la información, para mantener registros permanentes.</td>
    <td><b>Given</b> que el sistema recibe operaciones de escritura, actualización o borrado, <b>When</b> la lógica negocia con la capa de datos, <b>Then</b> el motor de base de datos ejecuta la transacción reflejando el cambio sin romper la integridad.</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <td>TS-06</td>
    <td>Gestionar relaciones entre entidades</td>
    <td>Como sistema, quiero manejar relaciones entre entidades, para garantizar consistencia de datos.</td>
    <td><b>Given</b> que existen objetos de negocio interdependientes (ej. Vehículo y Órdenes), <b>When</b> se realizan consultas cruzadas o modificaciones asimétricas, <b>Then</b> el sistema respeta las llaves foráneas y mantiene la congruencia de los datos.</td>
    <td>EP-10</td>
  </tr>
  <tr>
    <td>TS-07</td>
    <td>Consumir APIs externas</td>
    <td>Como sistema, quiero consumir APIs externas, para extender funcionalidades.</td>
    <td><b>Given</b> que una operación requiere el servicio de un tercero, <b>When</b> el backend formula una petición saliente autorizada, <b>Then</b> el sistema establece la comunicación y capta con éxito el flujo de retorno del servicio externo.</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <td>TS-08</td>
    <td>Manejar respuestas de API</td>
    <td>Como sistema, quiero procesar respuestas de APIs, para utilizarlas correctamente.</td>
    <td><b>Given</b> que el sistema obtiene paquetes de datos crudos de terceros, <b>When</b> la información ingresa a la capa de integración, <b>Then</b> el sistema serializa y adapta la información para que sea digerible por el ecosistema local.</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <td>TS-09</td>
    <td>Implementar manejo de errores</td>
    <td>Como sistema, quiero manejar errores de integración, para evitar fallos críticos.</td>
    <td><b>Given</b> que un servicio de terceros falla o tarda excesivamente, <b>When</b> la petición encuentra un obstáculo, <b>Then</b> el sistema captura la excepción de red, previene la interrupción global y retorna un código de error controlado al usuario.</td>
    <td>EP-11</td>
  </tr>
  <tr>
    <td>TS-10</td>
    <td>Configurar entorno de desarrollo</td>
    <td>Como developer, quiero configurar el entorno, para trabajar de forma consistente.</td>
    <td><b>Given</b> que un ingeniero ingresa al ciclo de desarrollo, <b>When</b> el ingeniero sincroniza los repositorios, <b>Then</b> el sistema expone variables de entorno claras y documentación que permiten alzar la aplicación localmente sin conflictos.</td>
    <td>EP-12</td>
  </tr>
  <tr>
    <td>TS-11</td>
    <td>Desplegar aplicación</td>
    <td>Como developer, quiero desplegar la aplicación, para que sea accesible.</td>
    <td><b>Given</b> que el código ha superado la etapa de integración, <b>When</b> se activa la cadena de despliegue, <b>Then</b> el sistema compila y distribuye los artefactos en los servidores en la nube sin requerir paradas críticas forzadas.</td>
    <td>EP-12</td>
  </tr>
  <tr>
    <td>TS-12</td>
    <td>Configurar hosting y dominio</td>
    <td>Como developer, quiero configurar el hosting, para asegurar disponibilidad del sistema.</td>
    <td><b>Given</b> que la infraestructura en la nube está activa, <b>When</b> una petición HTTP ingresa por la URL de producción, <b>Then</b> los servicios de resolución de nombres y servidores dirigen la comunicación correctamente hacia la aplicación.</td>
    <td>EP-12</td>
  </tr>
</tbody>
</table>
</div>

### 3.4. Impact Mapping

En esta sección se desarrolla el impact mapping, una técnica que permite visualizar la relación entre los objetivos del negocio, los actores involucrados, los impactos esperados y las funcionalidades del sistema. Esto facilita la alineación entre el desarrollo del producto y el valor que se busca generar. Se realiza en la plataforma UXPressia, acorde a las indicaciones del TF.

![alt text](<docs/assets/Impact Map AutoService.png>)

### 3.5. Product Backlog

A continuación, se presenta el Product Backlog del proyecto. Las historias han sido priorizadas en función de su valor estratégico para el negocio, asegurando que los requerimientos de captación (Landing Page) y cimientos arquitectónicos encabecen la lista para ser abordados en el primer Sprint. Asimismo, y de acuerdo con checkolas buenas prácticas evaluadas, las historias vinculadas a la autenticación y seguridad han sido relegadas a un nivel posterior, garantizando la entrega temprana de funcionalidades del core business.

<div align="center">
  <table style="margin: auto; text-align: left; width: 100%;">
    <thead>
      <tr>
        <th style="text-align: left; width: 5%;"># Orden</th>
        <th style="text-align: left; width: 7%;">Story Id</th>
        <th style="width: 25%;">Título</th>
        <th style="width: 505%;">Descripción</th>
        <th style="text-align: left; width: 8%;">Story Points</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="text-align: left;">1</td>
        <td style="text-align: left;">US-01</td>
        <td>Visualizar landing page</td>
        <td>Como usuario potencial, quiero acceder a la landing page, para conocer el producto y sus beneficios.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">2</td>
        <td style="text-align: left;">US-02</td>
        <td>Visualizar beneficios del sistema</td>
        <td>Como usuario potencial, quiero ver los beneficios del sistema, para entender su valor.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">3</td>
        <td style="text-align: left;">US-03</td>
        <td>Acceder a la plataforma desde CTA</td>
        <td>Como usuario potencial, quiero hacer clic en un botón de acción, para acceder al sistema.</td>
        <td style="text-align: left;">1</td>
      </tr>
      <tr>
        <td style="text-align: left;">4</td>
        <td style="text-align: left;">US-04</td>
        <td>Visualizar landing responsive</td>
        <td>Como usuario, quiero que la landing sea responsive, para poder verla desde mi celular.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">5</td>
        <td style="text-align: left;">TS-01</td>
        <td>Definir arquitectura del sistema</td>
        <td>Como developer, quiero definir la arquitectura del sistema, para asegurar escalabilidad y mantenimiento.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">6</td>
        <td style="text-align: left;">TS-04</td>
        <td>Diseñar modelo de base de datos</td>
        <td>Como developer, quiero definir el modelo de datos, para estructurar la información del sistema.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">7</td>
        <td style="text-align: left;">TS-10</td>
        <td>Configurar entorno de desarrollo</td>
        <td>Como developer, quiero configurar el entorno, para trabajar de forma consistente.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">8</td>
        <td style="text-align: left;">TS-11</td>
        <td>Desplegar aplicación</td>
        <td>Como developer, quiero desplegar la aplicación, para que sea accesible.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">9</td>
        <td style="text-align: left;">US-08</td>
        <td>Registrar vehículo</td>
        <td>Como administrador, quiero registrar un vehículo, para gestionar su servicio.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">10</td>
        <td style="text-align: left;">US-09</td>
        <td>Crear orden de trabajo</td>
        <td>Como administrador, quiero crear una orden de trabajo, para iniciar un servicio.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">11</td>
        <td style="text-align: left;">US-10</td>
        <td>Visualizar vehículos en el taller</td>
        <td>Como administrador, quiero ver los vehículos activos, para conocer el estado del taller.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">12</td>
        <td style="text-align: left;">US-23</td>
        <td>Ingresar código de seguimiento</td>
        <td>Como cliente, quiero ingresar un código, para consultar mi vehículo.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">13</td>
        <td style="text-align: left;">US-24</td>
        <td>Visualizar estado del vehículo</td>
        <td>Como cliente, quiero ver el estado del vehículo, para conocer su progreso.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">14</td>
        <td style="text-align: left;">US-11</td>
        <td>Actualizar estado del vehículo</td>
        <td>Como administrador, quiero actualizar el estado de un vehículo, para reflejar su progreso.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">15</td>
        <td style="text-align: left;">US-12</td>
        <td>Visualizar detalle del vehículo</td>
        <td>Como administrador, quiero ver el detalle de un vehículo, para revisar información completa.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">16</td>
        <td style="text-align: left;">US-25</td>
        <td>Visualizar tareas del vehículo</td>
        <td>Como cliente, quiero ver las tareas realizadas, para entender el trabajo.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">17</td>
        <td style="text-align: left;">US-26</td>
        <td>Visualizar fechas estimadas</td>
        <td>Como cliente, quiero ver fechas estimadas, para saber cuándo estará listo.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">18</td>
        <td style="text-align: left;">US-27</td>
        <td>Visualizar costos del servicio</td>
        <td>Como cliente, quiero ver el costo estimado, para conocer el precio del servicio.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">19</td>
        <td style="text-align: left;">US-05</td>
        <td>Iniciar sesión</td>
        <td>Como usuario del sistema, quiero iniciar sesión, para acceder a mis funcionalidades.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">20</td>
        <td style="text-align: left;">US-06</td>
        <td>Acceso según rol</td>
        <td>Como usuario, quiero ver funcionalidades según mi rol, para usar el sistema correctamente.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">21</td>
        <td style="text-align: left;">US-07</td>
        <td>Cerrar sesión</td>
        <td>Como usuario, quiero cerrar sesión, para proteger mi cuenta.</td>
        <td style="text-align: left;">1</td>
      </tr>
      <tr>
        <td style="text-align: left;">22</td>
        <td style="text-align: left;">US-13</td>
        <td>Crear tareas para vehículo</td>
        <td>Como administrador, quiero crear tareas para un vehículo, para definir los trabajos a realizar.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">23</td>
        <td style="text-align: left;">US-14</td>
        <td>Asignar estado a tarea</td>
        <td>Como administrador, quiero definir el estado de una tarea, para controlar su progreso.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">24</td>
        <td style="text-align: left;">US-15</td>
        <td>Visualizar progreso por vehículo</td>
        <td>Como administrador, quiero ver el progreso de un vehículo, para conocer el avance del servicio.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">25</td>
        <td style="text-align: left;">US-16</td>
        <td>Editar tareas</td>
        <td>Como administrador, quiero editar tareas, para actualizar información del servicio.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">26</td>
        <td style="text-align: left;">US-17</td>
        <td>Eliminar tareas</td>
        <td>Como administrador, quiero eliminar tareas, para corregir errores o cambios en el servicio.</td>
        <td style="text-align: left;">1</td>
      </tr>
      <tr>
        <td style="text-align: left;">27</td>
        <td style="text-align: left;">US-18</td>
        <td>Registrar mecánico</td>
        <td>Como administrador, quiero registrar un mecánico, para gestionar el personal del taller.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">28</td>
        <td style="text-align: left;">US-19</td>
        <td>Visualizar lista de mecánicos</td>
        <td>Como administrador, quiero ver todos los mecánicos registrados, para gestionar el equipo.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">29</td>
        <td style="text-align: left;">US-20</td>
        <td>Asignar tareas a mecánico</td>
        <td>Como administrador, quiero asignar tareas a mecánicos, para distribuir el trabajo.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">30</td>
        <td style="text-align: left;">US-21</td>
        <td>Visualizar carga de trabajo</td>
        <td>Como administrador, quiero ver la carga de trabajo de cada mecánico, para equilibrar tareas.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">31</td>
        <td style="text-align: left;">US-22</td>
        <td>Ver detalle de mecánico</td>
        <td>Como administrador, quiero ver el detalle de un mecánico, para conocer su desempeño.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">32</td>
        <td style="text-align: left;">US-28</td>
        <td>Visualizar ingresos</td>
        <td>Como administrador, quiero ver los ingresos del taller, para evaluar rendimiento.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">33</td>
        <td style="text-align: left;">US-29</td>
        <td>Visualizar servicios realizados</td>
        <td>Como administrador, quiero ver los servicios realizados, para analizar actividad.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">34</td>
        <td style="text-align: left;">US-30</td>
        <td>Identificar trabajos frecuentes</td>
        <td>Como administrador, quiero identificar trabajos frecuentes, para optimizar servicios.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">35</td>
        <td style="text-align: left;">US-31</td>
        <td>Visualizar métricas del sistema</td>
        <td>Como administrador, quiero ver métricas generales, para tomar decisiones.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">36</td>
        <td style="text-align: left;">US-32</td>
        <td>Navegar interfaz intuitiva</td>
        <td>Como usuario, quiero una interfaz clara, para usar el sistema fácilmente.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">37</td>
        <td style="text-align: left;">US-33</td>
        <td>Visualizar diseño consistente</td>
        <td>Como usuario, quiero consistencia visual, para tener mejor experiencia.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">38</td>
        <td style="text-align: left;">US-34</td>
        <td>Usar sistema en móvil</td>
        <td>Como usuario, quiero usar el sistema en mi celular, para acceder desde cualquier lugar.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">39</td>
        <td style="text-align: left;">US-35</td>
        <td>Visualizar información clara</td>
        <td>Como usuario, quiero ver la información organizada, para entender rápidamente.</td>
        <td style="text-align: left;">2</td>
      </tr>
      <tr>
        <td style="text-align: left;">40</td>
        <td style="text-align: left;">TS-02</td>
        <td>Implementar API REST</td>
        <td>Como sistema, quiero exponer una API REST, para permitir comunicación con el frontend.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">41</td>
        <td style="text-align: left;">TS-03</td>
        <td>Estructurar backend modular</td>
        <td>Como developer, quiero organizar el backend en módulos, para mejorar mantenibilidad.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">42</td>
        <td style="text-align: left;">TS-05</td>
        <td>Implementar persistencia de datos</td>
        <td>Como sistema, quiero guardar la información, para mantener registros permanentes.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">43</td>
        <td style="text-align: left;">TS-06</td>
        <td>Gestionar relaciones entre entidades</td>
        <td>Como sistema, quiero manejar relaciones entre entidades, para garantizar consistencia de datos.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">44</td>
        <td style="text-align: left;">TS-07</td>
        <td>Consumir APIs externas</td>
        <td>Como sistema, quiero consumir APIs externas, para extender funcionalidades.</td>
        <td style="text-align: left;">5</td>
      </tr>
      <tr>
        <td style="text-align: left;">45</td>
        <td style="text-align: left;">TS-08</td>
        <td>Manejar respuestas de API</td>
        <td>Como sistema, quiero procesar respuestas de APIs, para utilizarlas correctamente.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">46</td>
        <td style="text-align: left;">TS-09</td>
        <td>Implementar manejo de errores</td>
        <td>Como sistema, quiero manejar errores de integración, para evitar fallos críticos.</td>
        <td style="text-align: left;">3</td>
      </tr>
      <tr>
        <td style="text-align: left;">47</td>
        <td style="text-align: left;">TS-12</td>
        <td>Configurar hosting y dominio</td>
        <td>Como developer, quiero configurar el hosting, para asegurar disponibilidad del sistema.</td>
        <td style="text-align: left;">2</td>
      </tr>
    </tbody>
  </table>
</div>

<br>

Para complementar la especificación detallada del Product Backlog y evidenciar su correcta trazabilidad en nuestra herramienta de gestión, a continuación se presenta la captura de pantalla del entorno de Jira Software. En dicha evidencia se aprecia el listado completo de las historias configuradas y listas para ser abordadas en sus respectivos ciclos de desarrollo, manteniendo el estricto orden de prioridad de negocio establecido y sus correspondientes estimaciones en Story Points.

<div align="center">

![alt text](docs/assets/jira_backlog.png)
</div>

URL del tablero completo en Jira: https://innovatechstudio.atlassian.net/jira/software/projects/ASS/boards/1/backlog

---

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines
[Pendiente]

#### 4.1.2. Web Style Guidelines
[Pendiente]

### 4.2. Information Architecture

#### 4.2.1. Organization Systems
[Pendiente]

#### 4.2.2. Labeling Systems
[Pendiente]

#### 4.2.3. SEO Tags and Meta Tags
[Pendiente]

#### 4.2.4. Searching Systems
[Pendiente]

#### 4.2.5. Navigation Systems
[Pendiente]

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe
[Pendiente]

#### 4.3.2. Landing Page Mock-up
[Pendiente]

### 4.4. Web Applications UX/UI Design

#### 4.4.1. Web Applications Wireframes
[Pendiente]

#### 4.4.2. Web Applications Wireflow Diagrams
[Pendiente]

#### 4.4.3. Web Applications Mock-ups
[Pendiente]

#### 4.4.4. Web Applications User Flow Diagrams
[Pendiente]

### 4.5. Web Applications Prototyping
[Pendiente]

### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Design-Level EventStorming
[Pendiente]

#### 4.6.2. Software Architecture Context Diagram
[Pendiente]

#### 4.6.3. Software Architecture Container Diagrams
[Pendiente]

#### 4.6.4. Software Architecture Components Diagrams
[Pendiente]

### 4.7. Software Object-Oriented Design

#### 4.7.1. Class Diagrams
[Pendiente]

### 4.8. Database Design

#### 4.8.1. Database Diagrams
[Pendiente]

---

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration
[Pendiente]

#### 5.1.2. Source Code Management
[Pendiente]

#### 5.1.3. Source Code Style Guide & Conventions
[Pendiente]

#### 5.1.4. Software Deployment Configuration
[Pendiente]

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1
[Pendiente]

##### 5.2.1.2. Aspect Leaders and Collaborators
[Pendiente]

##### 5.2.1.3. Sprint Backlog 1
[Pendiente]

##### 5.2.1.4. Development Evidence for Sprint Review
[Pendiente]

##### 5.2.1.5. Execution Evidence for Sprint Review
[Pendiente]

##### 5.2.1.6. Services Documentation Evidence for Sprint Review
[Pendiente]

##### 5.2.1.7. Software Deployment Evidence for Sprint Review
[Pendiente]

##### 5.2.1.8. Team Collaboration Insights during Sprint
[Pendiente]

### 5.3. Validation Interviews

#### 5.3.1. Diseño de Entrevistas
[Pendiente]

#### 5.3.2. Registro de Entrevistas
[Pendiente]

#### 5.3.3. Evaluaciones según heurísticas
[Pendiente]

### 5.4. Video About-the-Product
[Pendiente]

---

## Conclusiones

### Conclusiones y recomendaciones
[Pendiente]

### Video About-the-Team
[Pendiente]

---

## Bibliografía
[Pendiente]
---

## Anexos
[Pendiente]
