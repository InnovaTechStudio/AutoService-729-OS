## Capítulo IV: Product Design

### 4.1. Style Guidelines

<p align="justify">
En la siguiente sección se establecen las directrices de estilo que garantizan una presentación visual consistente y profesional en todos los artefactos del proyecto. Para lograrlo, el equipo ha creado un repositorio central de diseño dentro de la organización de GitHub.
</p>
<p align="justify">
Para lograrlo, el equipo ha creado un repositorio central de diseño dentro de la organización de GitHub bajo la carpeta:
</p>
<p align="justify">
/design-system/
</p>
<p align="justify">
Este repositorio contiene la paleta de colores oficial, tipografías, iconos, componentes UI reutilizables, guías de espaciado, assets gráficos y documentación de uso. El objetivo principal es mantener una experiencia unificada entre la Landing Page, la Web Application (Panel de Control) y la experiencia móvil, facilitando el trabajo colaborativo y asegurando que tanto los mecánicos/administradores como los clientes finales perciban la misma calidad, confianza y profesionalismo en la marca.
</p>

#### 4.1.1. General Style Guidelines

<p align="justify"> Las decisiones generales de estilo se basan en los valores de marca de AutoService: confianza, profesionalismo, transparencia y modernidad tecnológica aplicada al sector automotriz. </p>
Branding y tono de comunicación
<p align="justify"> • Tono: Profesional, claro, cercano y orientado a soluciones. Se evita lenguaje técnico excesivo para el cliente final, pero se mantiene rigor y precisión en la interfaz del taller.<br> • Personalidad de marca: Confiable, ordenada, moderna y empática.<br> • Valores visuales: Orden, claridad visual, jerarquía y un toque de dinamismo controlado que transmite progreso y control del servicio. </p>

<div align="center">
  <table style="margin: auto; width: 100%; border-collapse: collapse; border: 1px solid #ddd;">
    <thead>
      <tr style="background-color: #f2f2f2;">
        <th style="padding: 12px; border: 1px solid #ddd; text-align: left;">Color</th>
        <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">Hex</th>
        <th style="padding: 12px; border: 1px solid #ddd; text-align: left;">Significado y Justificación</th>
        <th style="padding: 12px; border: 1px solid #ddd; text-align: left;">Ejemplo de uso en la interfaz</th>
        <th style="padding: 12px; border: 1px solid #ddd; text-align: center;">Imagen</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Primary Blue</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#0A2540</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Representa confianza, profesionalismo y autoridad. Azul profundo que transmite estabilidad y seriedad, cualidades esenciales en un servicio técnico automotriz. Genera sensación de seguridad tanto para mecánicos como para clientes.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Sidebar izquierdo, navbar, botones principales (CTA), encabezados del Panel de Control.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/primary-blue.png" alt="Primary Blue" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Secondary Teal</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#00BFA5</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Simboliza progreso, eficiencia y modernidad. El turquesa verdoso evoca movimiento positivo y finalización exitosa. Ideal para indicar avance y estados positivos.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Barra de progreso, badges “En curso”, indicadores de avance en tareas.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/secondary-teal.png" alt="Secondary Teal" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Accent Orange</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#FF6B00</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Representa atención y urgencia. Color energético que capta la atención sin generar ansiedad. Reservado para elementos que requieren acción inmediata.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Notificaciones de alta prioridad, alertas</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/accent-orange.png" alt="Accent Orange" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Neutral Gray</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#F4F4F5</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Proporciona calma, orden y fondo limpio. Reduce la fatiga visual y permite que los elementos importantes resalten.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Fondo general del dashboard, tarjetas KPI y contenedores secundarios.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/neutral-gray.png" alt="Neutral Gray" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Dark Gray</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#1F2937</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Color para texto secundario. Ofrece alto contraste con fondos claros garantizando excelente legibilidad.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Cuerpo de texto, descripciones y etiquetas secundarias.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/dark-gray.png" alt="Dark Gray" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">Success Green</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#10B981</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Transmite éxito y completitud. Verde moderno que refuerza la sensación de logro al finalizar un servicio.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Badges “Completado” y confirmaciones exitosas.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/success-green.png" alt="Success Green" width="60" height="60" style="border-radius: 8px;"></td>
      </tr>
      <tr>
        <td style="padding: 12px; border: 1px solid #ddd; font-weight: bold;">White</td>
        <td style="padding: 12px; border: 1px solid #ddd; font-family: monospace; text-align: center;">#FFFFFF</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Representa claridad y espacio. Se usa como fondo principal de tarjetas y modales para maximizar legibilidad y dar sensación de orden.</td>
        <td style="padding: 12px; border: 1px solid #ddd;">Tarjetas KPI, modales y secciones principales.</td>
        <td style="padding: 12px; border: 1px solid #ddd; text-align: center;"><img src="assets/colors/white.png" alt="White" width="60" height="60" style="border: 1px solid #ddd; border-radius: 8px;"></td>
      </tr>
    </tbody>
  </table>
</div>
<br>
Tipografía
<p align="justify"> El sistema tipográfico se basa en dos familias principales con una escala tipográfica coherente (Base Value: 16 px, Scale: 1.25): </p>
<p align="justify"> Heading (títulos): Poppins (Semi-Bold / Bold)
<br> • h1 - Título: 61 px (3.813 rem)<br> • h2– Subtítulo: 49 px (3.063 rem)<br> • h3 – Base Título: 39 px (2.438 rem)<br>•	h4: 31 px (1.938 rem)<br> • h5: 25 px<br><br>

Espaciado e iconografía
<p align="justify"> • Sistema de espaciado basado en múltiplos de 8 px (8, 16, 24, 32, 40, 48, 64 px, etc.).<br> • Bordes redondeados: 8 px y 16 px.<br> • Sombras suaves para profundidad visual.<br> • Iconografía: Librería Lucide Icons (24 px base). </p>

#### 4.1.2. Web Style Guidelines

<p align="justify"> Estas directrices definen los estándares visuales y de interacción específicos para las interfaces web (Landing Page y Web Application). Se han aplicado de forma consistente en el Panel de Control (versión desktop) y en todas las vistas administrativas. </p>

Layout y estructura
<p align="justify"> • Sistema de grid de 12 columnas con contenedor máximo de 1280 px.<br> • Sidebar fijo a la izquierda (240 px) para navegación principal.<br> • Área de contenido principal con padding lateral de 24 px.<br> • Tarjetas con fondo blanco, borde de 1 px (#E5E7EB), border-radius de 16 px y shadow sutil. </p>

Componentes principales
<p align="justify">
• Botones primarios: Fondo #0A2540, texto blanco, hover más oscuro, border-radius 8 px, altura mínima 48 px.<br> • Botones secundarios: Borde #0A2540, fondo transparente, texto oscuro.<br> • Tarjetas de métricas (KPI): Fondo blanco, ícono grande en la parte superior, números destacados en Poppins Bold.<br> • Tablas de vehículos: Encabezados con fondo #F8FAFC, filas con hover #F1F5F9, progress bars con color Secondary Teal.<br> • Estados de vehículos: Badges con border-radius completo, padding 4 px / 12 px y colores según estado (En proceso → teal, Pendiente → naranja, Completado → verde).<br> • Search bar: Fondo #F8FAFC, borde redondeado, ícono de lupa a la izquierda.<br> •	Usuario / Avatar: Círculo en la esquina superior derecha con foto y nombre. </p>
Tipografía en web
<p align="justify">
• Títulos de sección: Poppins Semi-Bold (h1–h3).<br> • Texto de tarjetas y tablas: Inter Regular 16 px.<br> • Todos los tamaños se expresan en rem para mantener accesibilidad y escalabilidad.
</p>
Consistencia visual
<p align="justify">
Todos los componentes siguen estrictamente el Design System alojado en /design-system/. La paleta, tipografía y espaciados se mantienen idénticos en todas las vistas web, garantizando una experiencia unificada entre la Landing Page y la Web Application.
</p>

### 4.2. Information Architecture

<p align="justify">
Esta sección detalla cómo se organiza, etiqueta y estructura la información dentro de la plataforma AutoService para garantizar que los diferentes segmentos de usuario puedan navegar intuitivamente. El objetivo es minimizar el esfuerzo cognitivo tanto del personal del taller al gestionar operaciones como del cliente final al consultar el estado de su vehículo.
</p>
<p align="justify">
Para AutoService, se han implementado diversos sistemas de organización que responden a las necesidades operativas y de consulta del negocio:
</p>

#### 4.2.1. Organization Systems

<p style="text-align: justify;">
  <ul>
    <li>
      <strong>Jerarquía Visual (Visual Hierarchy):</strong> Se aplica principalmente en el Dashboard Administrativo, donde los indicadores críticos (KPIs) como el número de vehículos en proceso, ingresos del día y órdenes pendientes se presentan en la parte superior con un diseño destacado para una rápida interpretación.
    </li>
    <li>
      <strong>Organización Secuencial (Step-by-step):</strong> Se utiliza estrictamente en el flujo de creación de una Orden de Trabajo y en el registro de servicios. El sistema guía al mecánico a través de pasos lógicos: Información del cliente &gt; Datos del vehículo &gt; Diagnóstico inicial &gt; Asignación de tareas y costos.
    </li>
    <li>
      <strong>Esquema Cronológico:</strong> Se emplea en el Historial de Servicios de cada vehículo. Los registros se organizan del más reciente al más antiguo, permitiendo que tanto el taller como el dueño del auto visualicen la evolución del mantenimiento en el tiempo.
    </li>
    <li>
      <strong>Categorización según Audiencia:</strong> La estructura se divide en dos grandes rutas de acceso:
      <ul>
        <li><strong>Panel Operativo (B2B):</strong> Orientado a mecánicos y administradores para la gestión de flota, personal y facturación.</li>
        <li><strong>Portal de Seguimiento (B2C):</strong> Una interfaz simplificada para el propietario del vehículo, centrada únicamente en el progreso y transparencia del servicio actual.</li>
      </ul>
    </li>
  </ul>
</p>

#### 4.2.2. Labeling Systems

<p style="text-align: justify;">
  El sistema de etiquetado utiliza términos técnicos automotrices estandarizados en inglés para mantener la consistencia con las convenciones de desarrollo del proyecto.
</p>

<ul style="text-align: justify;">
  <li>
    <strong>Etiquetas de Navegación (Sidebar/Navbar):</strong>
    <ul>
      <li>Dashboard: Vista general de métricas.</li>
      <li>Vehicles: Listado y gestión de unidades.</li>
      <li>Work Orders: Control de servicios activos.</li>
      <li>Staff: Gestión del personal mecánico.</li>
      <li>Billing: Generación de comprobantes y pagos.</li>
    </ul>
  </li>

  <li>
    <strong>Etiquetas de Acción (Botones/CTAs):</strong>
    <ul>
      <li>Register Vehicle: Iniciar registro de unidad.</li>
      <li>Update Status: Cambiar etapa del servicio (Pending, In Process, Ready).</li>
      <li>Generate Invoice: Crear comprobante de pago.</li>
      <li>Track My Vehicle: Acceso para el cliente final.</li>
    </ul>
  </li>

  <li>
    <strong>Etiquetas de Estado:</strong>
    <ul>
      <li>Diagnostic: Etapa de revisión inicial.</li>
      <li>In Repair: Ejecución de tareas mecánicas.</li>
      <li>Ready for Pickup: Vehículo listo para entrega.</li>
    </ul>
  </li>
</ul>

#### 4.2.3. SEO Tags and Meta Tags

<p style="text-align: justify;">
  A continuación, se definen los metadatos estratégicos para el posicionamiento y la identidad de la plataforma tanto en la Landing Page como en la Aplicación Web:
</p>

<table style="width: 100%; border-collapse: collapse; text-align: justify;">
  <thead>
    <tr style="background-color: #f2f2f2;">
      <th style="border: 1px solid #ddd; padding: 8px;">Página</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Title Tag</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Meta Description</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Keywords</th>
      <th style="border: 1px solid #ddd; padding: 8px;">Author</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;">Landing Page</td>
      <td style="border: 1px solid #ddd; padding: 8px;">AutoService - Digital Management for Workshops</td>
      <td style="border: 1px solid #ddd; padding: 8px;">
        Optimiza tu taller mecánico con seguimiento en tiempo real, gestión de órdenes y transparencia para el cliente.
      </td>
      <td style="border: 1px solid #ddd; padding: 8px;">
        workshop software, mechanic SaaS, vehicle tracking, taller digital, gestión automotriz
      </td>
      <td style="border: 1px solid #ddd; padding: 8px;">InnovaTech Studio</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ddd; padding: 8px;">Web Application (Dashboard)</td>
      <td style="border: 1px solid #ddd; padding: 8px;">AutoService</td>
      <td style="border: 1px solid #ddd; padding: 8px;">
        Panel de control operativo para gestión integral de servicios automotrices.
      </td>
      <td style="border: 1px solid #ddd; padding: 8px;">app, workshop, management, ERP, automotive.</td>
      <td style="border: 1px solid #ddd; padding: 8px;">InnovaTech Studio</td>
    </tr>
  </tbody>
</table>

#### 4.2.4. Searching Systems

<p style="text-align: justify;">
  Para evitar que los usuarios se pierdan ante grandes volúmenes de datos, se han definido los siguientes mecanismos de búsqueda y filtrado:
</p>

<ul style="text-align: justify;">
  <li>
    <strong>Búsqueda Global por Placa (License Plate):</strong> El buscador principal permite localizar rápidamente cualquier vehículo en el sistema ingresando el número de placa, lo cual redirige al detalle de su Orden de Trabajo activa.
  </li>
  <li>
    <strong>Filtros de Estado en Tiempo Real:</strong> En el listado de órdenes, el usuario puede filtrar por "Pending", "In Process" o "Completed" para priorizar las tareas del día.
  </li>
  <li>
    <strong>Filtros por Rango de Fechas:</strong> Aplicable en la sección de reportes financieros y de productividad para analizar el desempeño del taller en periodos específicos.
  </li>
  <li>
    <strong>Presentación de Resultados:</strong> Los datos se muestran en formato de tarjetas (cards) o tablas interactivas con resaltado de sintaxis para los estados críticos.
  </li>
</ul>

#### 4.2.5. Navigation Systems

<p style="text-align: justify;">
  El sistema de navegación está diseñado para ser consistente entre la Landing Page y la Aplicación, guiando al usuario hacia sus objetivos finales:
</p>

<ul style="text-align: justify;">
  <li>
    <strong>Navegación Global (Navbar):</strong> Presente en la Landing Page para dirigir a los usuarios potenciales a las secciones de beneficios, precios y el acceso al sistema (Login).
  </li>
  <li>
    <strong>Navegación Vertical (Sidebar):</strong> Menú lateral persistente en la Web Application que permite el tránsito rápido entre los módulos operativos (Vehicles, Staff, Orders).
  </li>
  <li>
    <strong>Breadcrumbs (Migas de Pan):</strong> Utilizadas en las vistas de detalle (ej: Work Orders &gt; Order #1234 &gt; Task Update) para que el usuario siempre sepa en qué nivel de la jerarquía se encuentra.
  </li>
  <li>
    <strong>Navegación Contextual (CTAs):</strong> Enlaces directos desde el Dashboard hacia las acciones más frecuentes, como "Add New Vehicle" o "View Pending Tasks".
  </li>
</ul>

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

<p align="justify">
La arquitectura de software de AutoService se fundamenta en los principios de Domain-Driven Design (DDD), permitiendo una traducción directa entre las necesidades operativas del negocio automotriz y la estructura del sistema técnico. Mediante la aplicación del Modelo C4, representamos la arquitectura en distintos niveles de abstracción, asegurando que la solución sea escalable, mantenible y esté estrictamente alineada con los contextos delimitados identificados durante el proceso de EventStorming.
</p>

#### 4.6.1. Design-Level EventStorming

<p align="justify">
Para profundizar en la lógica de AutoService<, realizamos una sesión de Design-Level Event Storming. Esta técnica nos permitió transitar desde una visión general del negocio hacia un modelo técnico detallado, identificando los procesos críticos, las reglas de negocio y los límites de los módulos que compondrán nuestra arquitectura orientada a servicios.
</p>

<b>Step 1: Collect Domain Events (Big Picture)</b>
<p align="justify">
En esta fase inicial, realizamos una lluvia de ideas para identificar todos los Domain Events relevantes en el ciclo de vida del taller, desde el registro de la cuenta hasta el procesamiento de comprobantes. Los eventos se redactaron en tiempo pasado, enfocándonos exclusivamente en hechos significativos para el negocio sin preocuparnos por el orden cronológico.
</p>

<div align="center">

![alt text](docs/assets/chapter-4/event_storming_s1.jpg)
</div>

<b>Step 2: Refine Domain Events</b>
<p align="justify">
Organizamos los eventos identificados en una línea de tiempo horizontal para establecer el flujo lógico de la plataforma. Durante este proceso, refinamos la secuencia y detectamos eventos faltantes, como la generación automática de códigos de seguimiento y el disparo de notificaciones, asegurando una narrativa coherente de la experiencia del usuario.
</p>

<div align="center">

![alt text](docs/assets/chapter-4/event_storming_s2.jpg)
</div>

<b>Step 3: Track Causes (Process Modelling)</b>
<p align="justify">
En este paso, modelamos la causalidad de cada evento introduciendo <b>Actors</b> (quién realiza la acción), <b>Commands</b> (la acción ejecutada), <b>External Systems</b> y <b>Policies</b> (reglas automáticas). Esto nos permitió visualizar cómo interactúan los mecánicos y clientes con el sistema y qué procesos se disparan automáticamente tras un cambio de estado.
</p>

<div align="center">

![alt text](docs/assets/chapter-4/event_storming_s3.jpg)
</div>

<b>Step 4: Find Aggregates & Bounded Contexts (Software Modelling)</b>
<p align="justify">
Finalmente, agrupamos los comandos y eventos alrededor de sus <b>Aggregates</b> (entidades principales de datos) para definir los <b>Bounded Contexts</b>. Esta segmentación estratégica establece los límites de responsabilidad para nuestro API RESTful, identificando módulos clave como <i>Workshop Operations</i>, <i>Staff Management</i> y <i>Billing</i>.
</p>

<div align="center">

![alt text](docs/assets/chapter-4/event_storming_s4.jpg)
</div>

#### 4.6.2. Software Architecture Context Diagram

<p align="justify">
El diagrama de contexto representa el nivel más alto de abstracción de la solución AutoService Platform. Este diagrama permite visualizar cómo el sistema interactúa con su entorno, identificando a los actores principales: el Mecánico/Administrador, quien gestiona las operaciones del taller, y el Cliente Final, quien realiza el seguimiento de sus vehículos. Asimismo, se muestra la interacción con sistemas externos esenciales como el Messaging Service, encargado del envío automatizado de notificaciones de estado y comprobantes electrónicos de pago.
</p>

<div align="center">

![alt text](docs/assets/chapter-4/context_diagram_os.png)
</div>

#### 4.6.3. Software Architecture Container Diagrams

<p align="justify">
A nivel de contenedores, la solución se descompone en aplicaciones independientes que colaboran para ofrecer la funcionalidad completa de la plataforma. Siguiendo un enfoque de arquitectura desacoplada, se han definido los siguientes contenedores:
</p>

<ul style="text-align: justify;">
<li><strong>Landing Page:</strong> Desarrollada con HTML5, CSS3 y JavaScript, se encarga de proveer información del producto y captar nuevos talleres hacia el modelo SaaS.</li>
<li><strong>Web Application (SPA):</strong> Construida con Angular y TypeScript, actúa como la interfaz principal donde los administradores gestionan el taller y los clientes finales consultan el progreso de sus reparaciones.</li>
<li><strong>API RESTful:</strong> Constituye el núcleo de la lógica de negocio, implementado con Java y el framework Spring Boot. Centraliza todas las reglas de dominio y expone servicios web mediante el intercambio de JSON.</li>
<li><strong>Database:</strong> Una instancia de PostgreSQL encargada de la persistencia segura y relacional de la información de clientes, vehículos, órdenes, staff y facturación.</li>
</ul>

<div align="center">

![alt text](docs/assets/chapter-4/containers_diagram_os.png)
</div>

#### 4.6.4. Software Architecture Components Diagrams

<p align="justify">
Este diagrama profundiza en el contenedor API RESTful para exponer los bloques estructurales internos que implementan los casos de uso definidos en el dominio. La lógica interna se organiza a través de componentes especializados:
</p>

<ul style="text-align: justify;">
<li><strong>IAM Component:</strong> Basado en Spring Security, este componente gestiona la identidad, autenticación y autorización mediante tokens JWT, protegiendo el acceso a los recursos del sistema.</li>
<li><strong>Workshop Service:</strong> Componente encargado de la orquestación de servicios de taller, incluyendo la gestión de flota, registro de vehículos y el control de las órdenes de trabajo.</li>
<li><strong>Tracking Service:</strong> Servicio dedicado a procesar y proveer la información de seguimiento en tiempo real, permitiendo a los clientes visualizar el avance de sus reparaciones.</li>
<li><strong>Billing Service:</strong> Gestiona la lógica de facturación para la generación de boletas y facturas electrónicas, integrándose con el servicio de mensajería para el envío de comprobantes.</li>
<li><strong>Reporting Service:</strong> Componente analítico que procesa los datos operativos para calcular métricas de productividad del staff y generar reportes financieros detallados para los administradores.</li>
</ul>

<div align="center">

![alt text](docs/assets/chapter-4/components_diagram_os.png)
</div>

### 4.7. Software Object-Oriented Design

<p align="justify">
  En esta sección se presenta el diseño orientado a objetos del sistema <strong>AutoService</strong>, 
  alineado con los principios de <strong>Domain-Driven Design (DDD)</strong> y 
  <strong>Clean Architecture</strong>.
</p>

<p align="justify">
  Los diagramas de clases modelan la estructura estática de cada 
  <strong>Bounded Context</strong> identificado en el <strong>Event Storming</strong>, 
  asegurando una clara separación de responsabilidades, alta cohesión y bajo acoplamiento.
</p>



<table>
  <thead>
    <tr>
      <th>Característica</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Notación UML Estándar</td>
      <td align="justify">Se utiliza la sintaxis oficial de diagramas de clases.</td>
    </tr>
    <tr>
      <td>Visibilidad (Scope)</td>
      <td align="justify">- private, + public, # protected – encapsulamiento.</td>
    </tr>
    <tr>
      <td>Tipos de Datos C#</td>
      <td align="justify">Guid, string, DateTime, decimal, bool, int – tipado nativo .NET.</td>
    </tr>
    <tr>
      <td>Relaciones Explícitas</td>
      <td align="justify">Nombre de rol, dirección de navegación y multiplicidad (1, 0..1, *).</td>
    </tr>
    <tr>
      <td>Optimización para Persistencia</td>
      <td align="justify">Entidades consolidadas para mapeo directo al modelo relacional de 16 tablas.</td>
    </tr>
    <tr>
      <td>Patrones y Principios</td>
      <td align="justify">SOLID (SRP, DIP), Repository, Factory, Strategy.</td>
    </tr>
  </tbody>
</table>


#### 4.7.1. Class Diagrams

##### Diagrama de Clases General - AutoService

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-autoservice.png"width="1000">
</div>


##### Identity & Profile Context

###### Responsabilidades Principales
- Autenticación de usuarios mediante credenciales seguras (hash de contraseñas)
- Gestión de roles y asignación a usuarios
- Control de acceso multi-tenant mediante **WorkshopId**
- Auditoría de asignación de roles (fecha de asignación)

###### Reglas de Negocio Clave
- Cada usuario pertenece a un único taller (**WorkshopId**), asegurando aislamiento multi-tenant
- Los roles disponibles son: **Admin**, **Mechanic**, **Client**
- Un usuario puede tener múltiples roles simultáneamente
- La asignación de roles registra la fecha para trazabilidad
- Solo usuarios activos (**IsActive = true**) pueden autenticarse

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-identity-&-profile-context.png"width="400">
</div>


##### Workshop Operations Context (Core Domain)

###### Responsabilidades Principales
- Gestión del ciclo de vida completo de las órdenes de trabajo
- Registro y mantenimiento de información de clientes y vehículos
- Desglose operativo de servicios en tareas asignables a mecánicos
- Seguimiento del estado de servicios y auditoría de cambios
- Generación de códigos de seguimiento para transparencia al cliente

###### Reglas de Negocio Clave
- Cada orden de trabajo debe estar asociada a un vehículo y un taller
- Los vehículos deben tener un único propietario (cliente) registrado
- El estado de la orden sigue un flujo definido: **PENDING → IN_PROGRESS → COMPLETED → DELIVERED** (con soporte para **CANCELLED**)
- Cada cambio de estado se registra en **StatusHistory** para auditoría
- Cada orden genera un código de seguimiento único para consulta del cliente
- El monto total de la orden se calcula a partir de los costos de sus tareas

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-workshop-operations-context-core.png"width="800">
</div>


##### Staff Management Context (Supporting Domain)

###### Responsabilidades Principales
- Registro y gestión de información laboral de mecánicos
- Asignación y control de turnos de trabajo
- Validación de conflictos de horarios
- Cálculo de métricas laborales (ingresos semanales)
- Verificación de disponibilidad del personal técnico

###### Reglas de Negocio Clave
- Cada mecánico está asociado a un usuario del sistema (**UserId**) para autenticación
- Un mecánico pertenece a un único taller (**WorkshopId**)
- Los turnos de un mismo mecánico no pueden superponerse en el tiempo (**IsOverlapping()**)
- El estado **IsActive** determina si el mecánico está disponible para asignación
- Los tipos de turno son: **MORNING**, **AFTERNOON**, **NIGHT**, **OVERTIME**

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-staff-management-context.png"width="300">
</div>


##### Billing & Payment Context (Supporting Domain)

###### Responsabilidades Principales
- Generación de facturas y comprobantes fiscales
- Cálculo de subtotales, impuestos y totales
- Gestión de ítems detallados por factura
- Registro de pagos con múltiples métodos
- Procesamiento y seguimiento de transacciones
- Soporte para cancelación y reembolsos

###### Reglas de Negocio Clave
- Cada factura puede estar asociada a una orden de trabajo (relación opcional **0..1**)
- Los totales se calculan automáticamente a partir de los ítems y la tasa de impuesto
- Una factura puede recibir un solo pago (relación **0..1**), simplificando el modelo
- Se soportan múltiples métodos de pago: **efectivo**, **tarjeta crédito/débito**, **transferencia**
- Los pagos tienen un ciclo de vida: **PENDING → PROCESSING → COMPLETED / FAILED**
- Las facturas pueden estar en estado: **DRAFT**, **ISSUED**, **PAID**, **CANCELLED** o **OVERDUE**

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-billing-&-payment-context.png"width="500">
</div>


##### Customer Tracking & Notification Context (Supporting Domain)

###### Responsabilidades Principales
- Registro de notificaciones enviadas a clientes
- Envío de notificaciones a través de múltiples canales (Email, SMS, Push, WhatsApp)
- Seguimiento del estado de entrega de notificaciones
- Trazabilidad completa de la comunicación por cliente y orden de trabajo
- Soporte para notificaciones automáticas basadas en eventos del sistema

###### Reglas de Negocio Clave
- Cada notificación se registra antes de ser enviada, garantizando trazabilidad
- Las notificaciones se vinculan al cliente destinatario (**ClientId**)
- Opcionalmente, una notificación puede asociarse a una orden de trabajo (**WorkOrderId**)
- Los tipos de notificación incluyen: **actualización de estado**, **orden completada**, **pago recibido** y **recordatorios**
- El sistema soporta múltiples canales: **Email**, **SMS**, **Push Notification** y **WhatsApp**
- El ciclo de vida de una notificación es: **PENDING → SENT → DELIVERED / FAILED**

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-customer-tracking-&-notification-context.png"width="450">
</div>


##### Reporting & Analytics Context (Supporting Domain)

###### Responsabilidades Principales
- Generación de reportes bajo demanda o programada
- Almacenamiento de metadata de reportes generados (tipo, rango de fechas, URL del archivo)
- Exportación de reportes en múltiples formatos (PDF, Excel)
- Trazabilidad de quién generó cada reporte y cuándo

###### Regla de Negocio Clave
- Los reportes pueden generarse por rango de fechas personalizado
- Cada reporte está asociado a un taller específico (**WorkshopId**)
- Los tipos de reporte disponibles son: ingresos diarios, productividad semanal, resumen mensual y desempeño de mecánicos
- Los reportes generados se almacenan como archivos (PDF/Excel) con una URL de acceso
- La lógica de cálculo de métricas se ejecuta al momento de generar el reporte, consultando datos en vivo

<div align="center">
<img src="docs/assets/chapter-4/class-diagrams/class-diagram-reporting-&-analytics-context.png"width="300">
</div>


### 4.8. Database Design

<p align="justify">
En esta sección se presenta el diseño de la base de datos relacional para el <strong>AutoService</strong>, alineado con los <strong>Bounded Contexts</strong> identificados en el análisis de <strong>Domain-Driven Design (DDD)</strong> y optimizado para cumplir con el alcance del proyecto.
</p>


#### Características Principales del Diseño


<div style="overflow-x: auto;">
  <table>
    <thead>
      <tr>
        <th scope="col">Característica</th>
        <th scope="col">Descripción</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Motor de Base de Datos</td>
        <td style="text-align: justify;">
          PostgreSQL 15+ / SQL Server 2019+ (según configuración del entorno).
        </td>
      </tr>
      <tr>
        <td>Normalización</td>
        <td style="text-align: justify;">
          Tercera Forma Normal (3NF) para eliminar redundancias y garantizar integridad referencial.
        </td>
      </tr>
      <tr>
        <td>Claves Primarias</td>
        <td style="text-align: justify;">
          Todas las tablas utilizan Guid/UUID como clave primaria para escalabilidad distribuida y evitar conflictos en entornos multi-tenant.
        </td>
      </tr>
      <tr>
        <td>Claves Foráneas</td>
        <td style="text-align: justify;">
          Relaciones explícitas con restricciones ON DELETE CASCADE o ON DELETE RESTRICT según la lógica de negocio y preservación de datos históricos.
        </td>
      </tr>
      <tr>
        <td>Índices</td>
        <td style="text-align: justify;">
          Índices en columnas de búsqueda frecuente (Plate, Email, OrderNumber, StatusEnum, WorkshopId) para optimizar consultas.
        </td>
      </tr>
      <tr>
        <td>Soft Delete</td>
        <td style="text-align: justify;">
          Columna IsActive o IsArchived en entidades críticas para preservación histórica sin eliminación física.
        </td>
      </tr>
      <tr>
        <td>Auditoría Básica</td>
        <td style="text-align: justify;">
          Columnas CreatedAt, UpdatedAt en tablas transaccionales para trazabilidad temporal.
        </td>
      </tr>
      <tr>
        <td>Enumeraciones</td>
        <td style="text-align: justify;">
          Campos INT con valores controlados para estados (WorkOrderStatus, PaymentStatus) garantizando consistencia de datos a nivel de aplicación.
        </td>
      </tr>
      <tr>
        <td>Multi-tenancy</td>
        <td style="text-align: justify;">
          Columna WorkshopId en tablas operativas para aislamiento lógico entre talleres (modelo SaaS), con políticas de Row-Level Security (RLS) opcionales.
        </td>
      </tr>
    </tbody>
  </table>
</div>


#### 4.8.1. Database Diagrams

##### Diagrama de Base de Datos General - AutoService

<div align="center">

![alt text](docs/assets/chapter-4/database-diagram/database-diagram-autoservice.png)
</div>


##### Identity & Profile Context
Este contexto gestiona la autenticación, autorización y configuración multi-tenant del sistema.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-identity-&-profile-context.png"width="600">
</div>


##### Workshop Operations Context (Core Domain)
El núcleo del negocio: gestión de órdenes de trabajo, tareas y seguimiento.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-workshop-operations-context-core.png"width="1000">
</div>


##### Staff Management Context (Supporting Domain)
Administra el personal técnico, sus turnos y disponibilidad operativa.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-staff-management-context.png"width="600">
</div>


##### Billing & Payment Context (Supporting Domain)
Gestiona la facturación, comprobantes y registro de transacciones económicas.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-billing-&-payment-context.png"width="800">
</div>


##### Customer Tracking & Notification Context (Supporting Domain)
Facilita la comunicación proactiva con el cliente final y el seguimiento externo.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-customer-tracking-&-notification-context.png"width="500">
</div>


##### Reporting & Analytics Context (Supporting Domain)
El contexto de Reporting se alimenta de las siguientes tablas operativas distribuidas en otros Bounded Contexts como Customer & Assets Context
Gestiona la información de clientes propietarios y sus vehículos registrados.

<div align="center">
<img src="docs/assets/chapter-4/database-diagram/database-diagram-customer-&-assets-context.png"width="350">
</div>
