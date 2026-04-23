## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

<p align="justify">
  La siguiente tabla presenta las herramientas, plataformas y guías empleadas para la configuración del entorno de desarrollo del proyecto <strong>AutoService</strong>, el cual tiene como objetivo digitalizar y optimizar la gestión de talleres automotrices mediante una solución web basada en arquitectura distribuida.
  
  Cada herramienta ha sido seleccionada considerando su compatibilidad con tecnologías open-source, su capacidad de integración y su uso en entornos profesionales de desarrollo de software.
</p>

<table>
  <thead>
    <tr>
      <th>Proceso</th>
      <th>Recurso o plataforma</th>
      <th>Finalidad</th>
      <th>Medio de acceso o Enlace</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Especificación de requisitos</td>
      <td>Convenciones Gherkin</td>
      <td>Definir criterios de aceptación claros para funcionalidades del sistema</td>
      <td><a href="https://cucumber.io/docs/gherkin/" target="_blank">Guía Gherkin</a></td>
    </tr>
    <tr>
      <td>Frontend Web Application</td>
      <td>Angular Framework</td>
      <td>Desarrollar la interfaz web dinámica del sistema AutoService</td>
      <td><a href="https://angular.io/" target="_blank">Angular</a></td>
    </tr>
    <tr>
      <td>Backend REST API</td>
      <td>Spring Boot</td>
      <td>Implementar servicios RESTful para la gestión de citas, clientes y servicios automotrices</td>
      <td><a href="https://spring.io/projects/spring-boot" target="_blank">Spring Boot</a></td>
    </tr>
    <tr>
      <td>Desarrollo Landing Page</td>
      <td>Visual Studio Code</td>
      <td>Editar y programar el código del Landing Page y frontend</td>
      <td><a href="https://code.visualstudio.com/" target="_blank">Visual Studio Code</a></td>
    </tr>
    <tr>
      <td>Control de versiones</td>
      <td>Git & GitHub</td>
      <td>Gestionar versiones y colaboración del equipo</td>
      <td><a href="https://github.com/" target="_blank">GitHub</a></td>
    </tr>
    <tr>
      <td>Diseño UX/UI</td>
      <td>Figma</td>
      <td>Diseñar wireframes, mockups y prototipos del sistema</td>
      <td><a href="https://figma.com" target="_blank">Figma</a></td>
    </tr>
    <tr>
      <td>Gestión del proyecto</td>
      <td>Trello</td>
      <td>Organizar backlog, tareas y seguimiento de sprints</td>
      <td><a href="https://trello.com" target="_blank">Trello</a></td>
    </tr>
    <tr>
      <td>Documentación API</td>
      <td>Swagger (OpenAPI)</td>
      <td>Documentar endpoints REST del sistema</td>
      <td><a href="https://swagger.io/" target="_blank">Swagger</a></td>
    </tr>
    <tr>
      <td>Modelado UX</td>
      <td>UXPressia</td>
      <td>Construir User Personas, Journey Maps y análisis UX</td>
      <td><a href="https://uxpressia.com/" target="_blank">UXPressia</a></td>
    </tr>
  </tbody>
</table>


#### 5.1.2. Source Code Management
<p align="justify">
  Para el desarrollo del proyecto AutoService, el equipo utiliza GitHub como plataforma principal de control de versiones, permitiendo gestionar de manera eficiente el código fuente tanto del Landing Page, como de la Web Application (Angular) y los Web Services (Spring Boot).
  
  Se ha adoptado el modelo GitFlow como estrategia principal de trabajo, lo que permite estructurar el desarrollo de manera ordenada y escalable. Este enfoque resulta especialmente adecuado para el proyecto, ya que involucra múltiples componentes (frontend, backend y landing page) que evolucionan en paralelo.
  
  La estructura de ramas implementada incluye:
</p>

- **main**: contiene la versión estable y desplegada del sistema AutoService  
- **develop**: integra los avances en desarrollo antes de pasar a producción  
- **feature/**: desarrollo de funcionalidades específicas (ej. gestión de citas, autenticación)  
- **hotfix/**: correcciones urgentes en producción  

<p align="justify">
  Cada funcionalidad es desarrollada en una rama independiente, lo que permite mantener el aislamiento de cambios y evitar conflictos. La integración se realiza mediante Pull Requests, los cuales son revisados por el equipo antes de ser fusionados.
  
  Adicionalmente, se implementa la convención de Conventional Commits para estandarizar los mensajes de confirmación:
</p>

- **feat**: nuevas funcionalidades (ej. creación de citas)  
- **fix**: corrección de errores  
- **docs**: cambios en documentación  
- **refactor**: mejoras internas sin alterar funcionalidad  
- **style**: cambios de formato  
- **test**: pruebas  

<p align="justify">
  Asimismo, se utiliza versionado semántico (Semantic Versioning) bajo el esquema MAJOR.MINOR.PATCH, lo cual permite gestionar de manera clara la evolución del sistema.
  
  Este enfoque garantiza una gestión organizada, colaborativa y escalable del proyecto AutoService.
</p>

#### 5.1.3. Source Code Style Guide & Conventions
<p align="justify">
  Con el propósito de garantizar la calidad, mantenibilidad y escalabilidad del sistema AutoService, se han establecido lineamientos de codificación aplicables a todos los componentes del proyecto, incluyendo el Landing Page (HTML, CSS, JavaScript), la Web Application (Angular) y el Backend (Spring Boot).
  
  Estos lineamientos permiten mantener consistencia en el desarrollo colaborativo, facilitar la lectura del código y asegurar su evolución a lo largo del tiempo. Como estándar general, todo el código fuente, nombres de variables, clases, métodos, archivos y documentación técnica se redacta en idioma inglés, alineándose con prácticas internacionales de desarrollo de software.
</p>

  **HTML Conventions**

<p align="justify">
Para la estructura del frontend se empleará HTML5 semántico, que prioriza la correcta organización del contenido y la accesibilidad.
</p>

<p align="justify">
Las principales convenciones adoptadas son:
</p>

- Uso de etiquetas semánticas como &lt;header&gt;, &lt;nav&gt;, &lt;main&gt;, &lt;section&gt; y &lt;footer&gt;
- Nombres de etiquetas y atributos en minúsculas
- Inclusión obligatoria del atributo alt en imágenes
- Uso de metadatos esenciales (&lt;title&gt;, &lt;meta&gt;)
- Evitar estilos inline

Ejemplo:

```html
<section class="hero-section">
  <img src="assets/images/banner.jpg" alt="AutoService platform banner" width="1200" height="600">
</section>
  ```

  **CSS Conventions**

<p align="justify">
  Para la hoja de estilos se seguirá una estructura modular y escalable, enfocada en la reutilización de componentes.
  - Uso de nomenclatura kebab-case.
  - Aplicación de metodología BEM.
  - Diseño responsive (mobile-first).
  - Uso de variables CSS en :root.
  - Uso de unidades relativas (rem, %, vh, vw).

  ``` CSS
  :root {
  --primary-color: #1e3a8a;
  --secondary-color: #64748b;
  }

  .main-header {
    padding: 1rem;
    background-color: var(--primary-color);
  }
  ```

  **JavaScript Conventions**

  Para la lógica del lado del cliente se adoptarán lineamientos orientados a la claridad, reutilización y mantenimiento del código.
  Se aplicarán las siguientes convenciones:
  - Uso de camelCase para variables y funciones.
  - Declaración con const y let (evitando var).
  - Código separado por módulos.
  - Uso de addEventListener().

  Ejemplo:
  ``` JavaScript
  const contactButton = document.querySelector("#contact-button");

  function handleContactClick() {
    console.log("Contact button clicked");
  }

  contactButton.addEventListener("click", handleContactClick);
  ```

  **Angular Conventions**

  Se utiliza como el framework principal para el desarrollo de la Web Application, es decir, la interfaz con la que interactúan los usuarios del sistema, como administradores de talleres y clientes. Su función es permitir la construcción de una aplicación web dinámica, moderna y altamente interactiva, capaz de consumir los servicios proporcionados por el backend desarrollado en Spring Boot.

  Se aplicarán las siguientes convenciones:

  - Uso de TypeScript.
  - Arquitectura basada en componentes.
  - Separación en modules, services y models.
  - camelCase para variables y métodos.
  - PascalCase para clases.
    
  Ejemplo:
  ``` angular
  export class AppointmentService {

    getAppointments() {
      return [];
    }
  }
  ```

  **Spring Boot Conventions**

  Para la definición de criterios de aceptación y pruebas funcionales se utilizará el lenguaje Gherkin, que sigue una estructura orientada al negocio.
  Las convenciones definidas son:
  - Uso de PascalCase para clases.
  - Uso de camelCase para variables y métodos.
  - Arquitectura en capas: Controllers, Services, Repositories, Models.
  - Uso de anotaciones REST.

  Ejemplo:

  ``` sprint boot
  @RestController
  @RequestMapping("/api/appointments")
  public class AppointmentController {

      @GetMapping
      public List<Appointment> getAllAppointments() {
          return new ArrayList<>();
      }
  }
  ```

  **Gherkin Conventions (User Stories & Testing)**

  Se utiliza como un lenguaje estructurado para definir las funcionalidades del sistema desde la perspectiva del usuario, permitiendo describir de manera clara y comprensible los comportamientos esperados de la aplicación. Su uso se integra principalmente en la redacción de User Stories y criterios de aceptación, facilitando la comunicación entre los miembros del equipo técnico y los stakeholders no técnicos, como usuarios finales o evaluadores del proyecto.

    - Uso de Given - When - Then.
    - Lenguaje entendible para negocio.
    - Escenarios claros.

  Ejemplo:

  ``` gherkin
  Feature: Appointment Management

  Escenario: Creación de cita exitosa
    Dado que el usuario ha iniciado sesión en AutoService, 
    cuando el usuario programa una nueva cita de servicio, 
    entonces el sistema guarda la cita correctamente.
  ```

  **Coding Principles Adopted**

  De manera transversal, el equipo aplicará los siguientes principios:
  - Readbility First: código fácil de leer y entender.
  - Consistency: mantener el mismo estilo en toda la solución.
  - Modularity: separación clara de responsabilidades.
  - Scalability: estructura preparada para crecimiento futuro.
  - Maintainability: facilidad para futuras modificaciones.
</p>


#### 5.1.4. Software Deployment Configuration
<p align="justify">
Para la configuración del despliegue del sistema AutoService, se ha definido una estrategia que contempla la publicación independiente de cada uno de sus componentes: el Landing Page, la Web Application desarrollada en Angular y el Backend basado en servicios REST con Spring Boot. Esta separación responde a la arquitectura distribuida del proyecto, permitiendo una mayor escalabilidad, mantenibilidad y facilidad de integración entre las distintas capas del sistema.
</p>

**Landing Page Deployment - HTML, CSS and JavaScript**

**Source Repository Setup**
<p align="justify">
  En el caso específico del Landing Page, se utilizará un repositorio remoto alojado en GitHub, en el cual se almacenarán todos los archivos fuente correspondientes a la interfaz web estática. Este componente cumple la función de presentar la propuesta de valor de AutoService y servir como punto de entrada para los usuarios hacia la plataforma.
  
  Dado que el Landing Page ha sido desarrollado con HTML, CSS y JavaScript, es indispensable que el archivo principal <strong>index.html</strong> permanezca en la raíz del repositorio, ya que este será utilizado como punto de inicio durante el proceso de despliegue. Asimismo, los archivos complementarios como hojas de estilo, scripts e imágenes se organizarán en directorios específicos, con el fin de mantener una estructura clara, facilitar el mantenimiento del código y permitir futuras actualizaciones del sistema.
  
  Ejemplo:
  ```
  /
  |---index.html
  |---css/
  |    |__ styles.css
  |---js/
  |    |__ main.js
  |---assets/
        |__ images/
  ```
</p>

**Deployment Process (GitHub Pages)**
<p align="justify">
  La publicación del sitio se realizará mediante el servicio GitHub Pages, el cual permite desplegar sitios estáticos directamente desde el repositorio.
  Para habilitar el despliegue, se seguirán los siguientes pasos:
  - Acceder al repositorio del proyecto en GitHub
  - Ingresar a la sección Settings
  - Seleccionar la opción Pages
  - Configurar la rama main como fuente de despliegue
  - Definir la carpeta raíz (root) como directorio de publicación
  - Guardar la configuración
  Una vez configurado, GitHub Pages generará automáticamente el sitio web.
</p>

**Published Access**
<p align="justify">
  El Landing Page estará disponible mediante una URL pública con la siguiente estructura:
  
  ```
  https://<usernanme>.github.io/<repository-name>/
  ```

  Este enlace corresponderá a la versión oficial publicada del producto.
</p>

**Frontend Deployment (Angular)**
<p align="justify">
  La aplicación web desarrollada en Angular será desplegada en plataformas cloud como Firebase Hosting o Vercel, permitiendo alta disponibilidad y tiempos de respuesta óptimos.

  Proceso:
  - Generación de build de producción:

  ```
  ng build --prod
  ```

  - Despliegue en plataforma cloud seleccionada
</p>

**Backend Deployment (Spring Boot)**

<p align="justify">
  El backend del sistema será desplegado en servicios cloud como Render, Railway o AWS, permitiendo la ejecución continua de la API REST.

  Proceso:

  - Compilación del proyecto y generación del archivo .jar
  - Configuración de variables de entorno
  - Despliegue en servidor cloud

</p>

**System Integration**

<p align="justify">
  La Web Application se comunica con el backend mediante peticiones HTTP a través de una API REST, permitiendo la gestión de citas, clientes y servicios automotrices en tiempo real.

  Ejemplo:

  **Request:**

  ```
    GET /api/appointments
  ```

  **Respuesta (JSON):**

  ```
    json
    [
      {
        "id": 1,
        "clientName": "Juan Perez",
        "service": "Cambio de aceite",
        "date": "2026-04-20"
      }
    ]
  ```
</p>

**Updates System**

<p align="justify">
  Cada modificación realizada en el repositorio principal genera una nueva versión del sistema. Al actualizar la rama principal, los cambios pueden ser desplegados automáticamente o de forma manual, garantizando que la versión publicada se mantenga sincronizada con el código fuente más reciente.
</p>

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

<div align="center">
  <table style="margin: auto; width: 100%; border-collapse: collapse; text-align: left;">
    <thead>
      <tr>
        <th colspan="2" style="text-align: center; background-color: #f2f2f2; font-size: 1.2em; padding: 10px; border: 1px solid #ddd;">Sprint #1</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td colspan="2" style="background-color: #fafafa; font-weight: bold; text-align: center; padding: 10px; border: 1px solid #ddd;">Sprint Planning Background</td>
      </tr>
      <tr>
        <td style="width: 30%; font-weight: bold; padding: 10px; border: 1px solid #ddd;">Date</td>
        <td style="padding: 10px; border: 1px solid #ddd;">2026-04-08</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Time</td>
        <td style="padding: 10px; border: 1px solid #ddd;">10:00 AM</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Location</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Reunión presencial en la UPC. (Pabellón L, piso 4, cubículo 11)</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Prepared By</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Sanchez Cuadrado, Juan Antonio</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Attendees (to planning meeting)</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Aguilar Aguayo, Jeferson Renzo / López Monroy, Rodrigo Alfredo / Luis Miranda, Diego Andres / Mamani Vilca, Alan Jaivi / Sanchez Cuadrado, Juan Antonio</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Sprint 0 Review Summary</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Al ser la iteración inicial del proyecto, no existe un Sprint previo para revisar. El equipo se enfocó en el setup inicial de herramientas, creación de la organización en GitHub y configuración del espacio de trabajo en Jira Software.</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Sprint 0 Retrospective Summary</td>
        <td style="padding: 10px; border: 1px solid #ddd;">Al ser el primer ciclo, no hay retrospectiva previa. Sin embargo, el equipo acordó como norma de trabajo el uso estricto de Feature Branching para el control de versiones y la comunicación constante ante bloqueos técnicos.</td>
      </tr>
      <tr>
        <td colspan="2" style="background-color: #fafafa; font-weight: bold; text-align: center; padding: 10px; border: 1px solid #ddd;">Sprint Goal & User Stories</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Sprint 1 Goal</td>
        <td style="padding: 10px; border: 1px solid #ddd;">
          <strong>Our focus is on</strong> deploying the official Landing Page and establishing the core software architecture and database design.<br><br>
          <strong>We believe it delivers</strong> a solid online presence for early user acquisition and a reliable technical foundation for the development team.<br><br>
          <strong>This will be confirmed when</strong> the Landing Page is publicly accessible via a web link with responsive design, and the C4 Model diagrams along with the Database Entity-Relationship diagram are fully documented and approved.
        </td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Sprint 1 Velocity</td>
        <td style="padding: 10px; border: 1px solid #ddd;">27 Story Points</td>
      </tr>
      <tr>
        <td style="font-weight: bold; padding: 10px; border: 1px solid #ddd;">Sum of Story Points</td>
        <td style="padding: 10px; border: 1px solid #ddd;">27 Story Points (US-01: 3, US-02: 2, US-03: 1, US-04: 3, TS-01: 5, TS-04: 3, TS-10: 5, TS-11: 5).</td>
      </tr>
    </tbody>
  </table>
</div>

##### 5.2.1.2. Aspect Leaders and Collaborators

En el presente Sprint 1, el alcance funcional y técnico se ha dividido en tres aspectos principales para garantizar una entrega eficiente:
1. Landing Page (Frontend): Desarrollo de la interfaz gráfica e identidad visual.
2. Architecture & Database: Diseño de diagramas C4 y modelado relacional de la base de datos.
3. DevOps & Deployment: Configuración de repositorios, CI/CD básico y hosting estático.

<div align="center">
  <table style="margin: auto; width: 100%; border-collapse: collapse; text-align: center;">
    <thead>
      <tr style="background-color: #f2f2f2;">
        <th style="padding: 10px; border: 1px solid #ddd; text-align: left;">Team Member (Last Name, First Name)</th>
        <th style="padding: 10px; border: 1px solid #ddd;">GitHub Username</th>
        <th style="padding: 10px; border: 1px solid #ddd;">Landing Page (Frontend)<br><small>Leader (L) / Collaborator (C)</small></th>
        <th style="padding: 10px; border: 1px solid #ddd;">Architecture & Database<br><small>Leader (L) / Collaborator (C)</small></th>
        <th style="padding: 10px; border: 1px solid #ddd;">DevOps & Deployment<br><small>Leader (L) / Collaborator (C)</small></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: left;">Aguilar Aguayo, Jeferson Renzo</td>
        <td style="padding: 10px; border: 1px solid #ddd;">jefersomblan</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: left;">López Monroy, Rodrigo Alfredo</td>
        <td style="padding: 10px; border: 1px solid #ddd;">rodrigolopezu</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold; color: #2e7d32;">L</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: left;">Luis Miranda, Diego Andres</td>
        <td style="padding: 10px; border: 1px solid #ddd;">andrewdmr</td>
        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold; color: #2e7d32;">L</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: left;">Mamani Vilca, Alan Jaivi</td>
        <td style="padding: 10px; border: 1px solid #ddd;">alanmamaniv</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold; color: #2e7d32;">L</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
      </tr>
      <tr>
        <td style="padding: 10px; border: 1px solid #ddd; text-align: left;">Sanchez Cuadrado, Juan Antonio</td>
        <td style="padding: 10px; border: 1px solid #ddd;">juanasc05</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
        <td style="padding: 10px; border: 1px solid #ddd; font-weight: bold; color: #2e7d32;">L</td>
        <td style="padding: 10px; border: 1px solid #ddd; color: #1976d2;">C</td>
      </tr>
    </tbody>
  </table>
</div>

##### 5.2.1.3. Sprint Backlog 1

El presente Sprint Backlog detalla la descomposición técnica de las historias de usuario y técnicas seleccionadas para la primera iteración. El objetivo principal de este Sprint es establecer la presencia web inicial mediante la Landing Page y sentar las bases arquitectónicas del sistema. A continuación, se presenta la captura de nuestro tablero en Jira Software, seguida de la tabla de control de estado con la distribución de los Work-Items.

<div align="center">

![alt text](assets/READMEmedia/sprint1_jira.png)

</div>

<div align="center">
  <table style="margin: auto; width: 100%; border-collapse: collapse; text-align: left; font-size: 13px; border: 1px solid #ddd;">
    <thead>
      <tr style="background-color: #e0e0e0; font-weight: bold;">
        <th style="padding: 10px; text-align: center; border: 1px solid #ddd;">Sprint #</th>
        <th colspan="7" style="padding: 10px; text-align: left; border: 1px solid #ddd;">1</th>
      </tr>
      <tr style="background-color: #f2f2f2;">
        <th colspan="2" style="text-align: center; border: 1px solid #ddd; padding: 10px;">User Story</th>
        <th colspan="6" style="text-align: center; border: 1px solid #ddd; padding: 10px;">Work-Item / Task</th>
      </tr>
      <tr style="background-color: #fafafa; text-align: center;">
        <th style="border: 1px solid #ddd; padding: 5px; width: 6%;">Id</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 15%;">Title</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 6%;">Id</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 15%;">Title</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 30%;">Description</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 8%;">Estimation (Hours)</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 12%;">Assigned To</th>
        <th style="border: 1px solid #ddd; padding: 5px; width: 8%;">Status</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">US-01</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Visualizar landing page</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-01</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Diseño inicial</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Diseñar wireframes y mockup inicial de la estructura web.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Luis, Diego</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-02</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Setup Frontend</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Configurar proyecto base utilizando React y Tailwind CSS.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
        <td style="border: 1px solid #ddd; padding: 8px;">López, Rodrigo</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">US-02</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Visualizar beneficios del sistema</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-03</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Redacción Copy</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Redactar y estructurar el contenido (copy) explicativo.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">2</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Sanchez, Juan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-04</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Componente Cards</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Desarrollar los componentes de tarjetas para beneficios.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Mamani, Alan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">US-03</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Acceder a la plataforma desde CTA</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-05</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Botones CTA</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Maquetar los botones de llamado a la acción.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">2</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Luis, Diego</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-06</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Enrutamiento React</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Configurar el enrutamiento base hacia vistas futuras.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Aguilar, Jeferson</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">US-04</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Visualizar landing responsive</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-07</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Media Queries</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Aplicar clases utilitarias para ajuste a móviles y tablets.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Aguilar, Jeferson</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-08</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Testing UI</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Realizar validaciones de renderizado en pantallas.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">2</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Aguilar, Jeferson</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="3" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">TS-01</td>
        <td rowspan="3" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Definir arquitectura del sistema</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-09</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Context Diagram</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Diseñar Context Diagram bajo el modelo C4.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Mamani, Alan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-10</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Container Diagram</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Diseñar Container Diagram bajo el modelo C4.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Sanchez, Juan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-11</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Event Storming</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Elaborar el Design-Level Event Storming.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Mamani, Alan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">TS-04</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Diseñar modelo de base de datos</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-12</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Modelo Conceptual</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Identificar entidades y relaciones de negocio.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Sanchez, Juan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-13</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Diagrama Lógico ER</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Elaborar el Diagrama Entidad-Relación de la BD.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">5</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Mamani, Alan</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">TS-10</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Configurar entorno de desarrollo</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-14</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Configuración Git</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Definir estructura de repositorio y flujo de ramas.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">3</td>
        <td style="border: 1px solid #ddd; padding: 8px;">López, Rodrigo</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-15</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Definir guía de estilos de código</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Code style guide and conventions.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">5</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Aguilar, Jeferson</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle; text-align: center; font-weight: bold;">TS-11</td>
        <td rowspan="2" style="border: 1px solid #ddd; padding: 8px; vertical-align: middle;">Desplegar aplicación</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-16</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Hosting de la landing page</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Configurar el servicio de hosting estático para la Landing Page.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">4</td>
        <td style="border: 1px solid #ddd; padding: 8px;">López, Rodrigo</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
      <tr>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">WI-17</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Pruebas de acceso</td>
        <td style="border: 1px solid #ddd; padding: 8px;"><i>Verificar el acceso público al enlace.</i></td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center;">2</td>
        <td style="border: 1px solid #ddd; padding: 8px;">Aguilar, Jeferson</td>
        <td style="border: 1px solid #ddd; padding: 8px; text-align: center; font-weight: bold; color: #d32f2f;">To-do</td>
      </tr>
    </tbody>
  </table>
</div>

##### 5.2.1.4. Development Evidence for Sprint Review

<p align="justify">
Durante el Sprint 1, el equipo completó la base estratégica y técnica del proyecto, abarcando desde la definición del perfil de la startup hasta el diseño detallado del producto en los Capítulos I al IV. En cuanto a la implementación técnica, los esfuerzos se centraron en el diseño de mockups de alta fidelidad, el despliegue de la versión inicial de la Landing Page y la configuración de los entornos de desarrollo para la implementación de la Web Application y el RESTful API en los siguientes sprints.<br><br>
En la siguiente tabla se presentan commits que representan hitos clave del desarrollo de este sprint:
</p>

<table style="width: 100%; border-collapse: collapse; text-align: justify;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th style="border: 1px solid #ddd; padding: 8px;">Repository</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Branch</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Commit Id</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Commit Message</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Commit Message Body</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Commited on (Date)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>main</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>43a3a61</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">chore:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">initial project setup</td>
      <td style="border: 1px solid #ddd; padding: 8px;">12/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/capitulo-1</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>a8c043e</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add solution profile</td>
      <td style="border: 1px solid #ddd; padding: 8px;">12/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-3</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>25b600f</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add product backlog table and jira evidence</td>
      <td style="border: 1px solid #ddd; padding: 8px;">12/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-5</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>3815e12</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add sprint 1 backlog table</td>
      <td style="border: 1px solid #ddd; padding: 8px;">12/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-2/interview-struct</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>e262f08</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add chapter-2 intervier record,1,2,3 and interview design</td>
      <td style="border: 1px solid #ddd; padding: 8px;">14/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/information-architecture-and-ddd</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>d1e9556</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add event storming section and c4 diagrams</td>
      <td style="border: 1px solid #ddd; padding: 8px;">16/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-2-requirements-analysis</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>03e330c</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add user task matrix for Chapter 2 needfinding section</td>
      <td style="border: 1px solid #ddd; padding: 8px;">17/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-4-design-diagrams</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>a1e4b4f</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add database design diagram for Chapter 4</td>
      <td style="border: 1px solid #ddd; padding: 8px;">19/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-729-OS</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/chapter-4-design-diagrams</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>0f7718c</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">docs:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">add class diagrams for Chapter 4 object-oriented design</td>
      <td style="border: 1px solid #ddd; padding: 8px;">19/04/2026</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>InnovaTechStudio/AutoService-landing</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>feature/landing-base</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;"><code>5c2cdfa</code></td>
      <td style="border: 1px solid #ddd; padding: 8px;">feat:</td>
      <td style="border: 1px solid #ddd; padding: 8px;">redesign landing page visual system</td>
      <td style="border: 1px solid #ddd; padding: 8px;">19/04/2026</td>
    </tr>
  </tbody>
</table>

##### 5.2.1.5. Execution Evidence for Sprint Review

<p align="justify">
En esta sección se presenta la evidencia de la ejecución del producto lograda durante el Sprint 1. El resultado principal de esta iteración es la primera versión funcional de la Landing Page de AutoService, desarrollada con HTML5, CSS3 y JavaScript. Esta interfaz presenta de forma clara el modelo de negocio, las herramientas principales de la plataforma y los planes de suscripción disponibles. Se ha verificado que la navegación interactiva (scroll suave y menú hamburguesa) sea fluida y que el diseño sea completamente adaptable (responsive web design) para garantizar una correcta experiencia de usuario tanto en navegadores de escritorio como en dispositivos móviles.
</p>

<div align="center">
  <h5>Vista Principal de la Landing Page (Hero Section y Navegación)</h5>
  <img src="docs/assets/chapter-5/hero-landing.png" alt="Landing Page Hero Section" width="80%">
  
  <h5>Sección de Características y Planes de Suscripción</h5>
  <img src="docs/assets/chapter-5/pricing-landing.png" alt="Landing Page Pricing y Features" width="80%">
</div>

<p align="justify">
Para ilustrar la visualización y las interacciones logradas en este Sprint, se adjunta el enlace a un video demostrativo. En este registro se evidencia el funcionamiento de los componentes clave, la adaptabilidad del diseño en distintas resoluciones y la coherencia visual con los lineamientos de UI establecidos en el Capítulo IV del proyecto.
</p>

---

##### 5.2.1.6. Services Documentation Evidence for Sprint Review

<p align="justify">
Durante el Sprint 1, el equipo priorizó estratégicamente el diseño del dominio (Domain-Driven Design), la elaboración de artefactos UX/UI y el desarrollo e implementación de la Landing Page. De acuerdo con la planificación de nuestro Sprint Backlog y la priorización de valor del producto, la implementación del contenedor API RESTful y su respectiva documentación con OpenAPI (Swagger) han sido programados para sprints futuros. Por tal motivo, en esta iteración inicial no se reportan endpoints implementados ni capturas de interacción de Web Services.
</p>

---

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

<p align="justify">
En esta sección se detallan los procesos realizados para el despliegue de la solución durante el Sprint 1. El objetivo principal fue poner en producción la versión inicial de la Landing Page, permitiendo que el modelo de negocio de AutoService sea accesible para los interesados y potenciales clientes desde cualquier navegador.
</p>

<p align="justify">
Para el despliegue, se utilizó <b>GitHub Pages</b>, aprovechando su integración nativa con el repositorio de código fuente. El proceso consistió en los siguientes pasos estratégicos:
</p>

<ol style="text-align: justify;">
  <li><strong>Configuración del Entorno:</strong> Se configuró el repositorio específico para la Landing Page, asegurando que el archivo <code>index.html</code> se encuentre en la raíz para su correcto reconocimiento.</li>
  <li><strong>Activación del Servicio:</strong> Se habilitó GitHub Pages desde los ajustes del repositorio, seleccionando la rama <code>main</code> como fuente de despliegue.</li>
  <li><strong>Automatización (CI/CD):</strong> Se validó el flujo de trabajo automático mediante GitHub Actions, el cual dispara un nuevo despliegue cada vez que se realiza un merge a la rama principal.</li>
</ol>

<div align="center">

  <h5>Evidencia 1: Configuración de GitHub Pages en el Repositorio</h5>
    <img src="docs/assets/chapter-5/deployment_github_settings.png" alt="GitHub Pages Settings" width="80%">
  <h5>Evidencia 2: Ejecución Exitosa del Workflow de Despliegue</h5>
    <img src="docs/assets/chapter-5/deployment_actions_success.png" alt="GitHub Actions Workflow" width="80%">
  <h5>Evidencia 3: Visualización de la Landing Page en Producción</h5>
    <img src="docs/assets/chapter-5/deployment_live_url.png" alt="Live Landing Page" width="80%">

</div><p align="justify">

La Landing Page se encuentra actualmente operativa en la siguiente URL: <code>https://innovatechstudio.github.io/AutoService-landing/</code>.
</p>

---

##### 5.2.1.8. Team Collaboration Insights during Sprint

<p align="justify">
Durante el Sprint 1, el equipo mantuvo un flujo de trabajo altamente colaborativo y organizado, aplicando estrictamente la estrategia de control de versiones GitFlow. Para asegurar la calidad y revisión por pares, todo el desarrollo de la arquitectura, investigación de UX/UI y codificación de la Landing Page se trabajó en ramas independientes (<i>feature branches</i>). La integración del trabajo se realizó exclusivamente mediante <b>Pull Requests</b> hacia la rama <code>develop</code>, lo que fomentó la comunicación y revisión conjunta antes de consolidar los avances.
</p>

<p align="justify">
A continuación, se presentan los analíticos extraídos de GitHub (Insights) que evidencian la participación equitativa y constante de todos los miembros del equipo (<i>Aspect Leaders</i> y <i>Collaborators</i>) tanto en el repositorio principal de documentación como en el de la Landing Page.
</p>

<div align="center">
  <h5>Evidencia 1: Gráfico de Contribuciones por Miembro del Equipo</h5>
  <img src="docs/assets/chapter-5/contributors.png" alt="GitHub Contributors Graph" width="80%">
  
  <h5>Evidencia 2: Resumen de Actividad del Sprint (GitHub Pulse)</h5>
  <img src="docs/assets/chapter-5/pulse.png" alt="GitHub Pulse Activity" width="80%">

  <h5>Evidencia 3: Gestión Colaborativa mediante Pull Requests</h5>
  <img src="docs/assets/chapter-5/closed_pr.png" alt="GitHub Closed Pull Requests" width="80%">
</div>

<p align="justify">
Como demuestran las gráficas y el resumen de actividad, la carga de trabajo se distribuyó de manera eficiente, logrando que el 100% de los integrantes registre commits significativos (alineados a <i>Conventional Commits</i>), gestione integraciones (Merges) y participe activamente en las fases de análisis, diseño e implementación temprana del producto.
</p>

---

### 5.3. Validation Interviews

#### 5.3.1. Diseño de Entrevistas
[Pendiente]

#### 5.3.2. Registro de Entrevistas
[Pendiente]

#### 5.3.3. Evaluaciones según heurísticas
[Pendiente]

### 5.4. Video About-the-Product
[Pendiente]