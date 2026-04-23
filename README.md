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
  - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
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
[Pendiente]

#### 2.1.2. Estrategias y tácticas frente a competidores
[Pendiente]

---

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas
[Pendiente]

#### 2.2.2. Registro de entrevistas
[Pendiente]

#### 2.2.3. Análisis de entrevistas
[Pendiente]

---

### 2.3. Needfinding

#### 2.3.1. User Personas
[Pendiente]

#### 2.3.2. User Task Matrix
[Pendiente]

#### 2.3.3. User Journey Mapping
[Pendiente]

#### 2.3.4. Empathy Mapping
[Pendiente]

---

### 2.4. Big Picture EventStorming
[Pendiente]

### 2.5. Ubiquitous Language
[Pendiente]

---

## Capítulo III: Requirements Specification

### 3.1. User Stories
[Pendiente]

### 3.4. Impact Mapping
[Pendiente]

### 3.5. Product Backlog
[Pendiente]

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
