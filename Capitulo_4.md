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

En esta sección se presentan los wireframes desarrollados para AutoService, los cuales representan la estructura base de las interfaces antes de la aplicación del diseño visual final. Estos wireframes permiten definir la organización del contenido, la jerarquía de la información y los flujos de navegación, asegurando una experiencia de usuario clara y eficiente.

Se desarrollaron wireframes tanto para el flujo del administrador como para el cliente, considerando sus diferentes objetivos dentro del sistema.

<div align= center><img src="docs/assets/chapter4-designUX/wireframes.png"></div>

<p>Trabajo hecho en figma - link: <a href="https://www.figma.com/design/rOJ6k8HLfI85lI8Xsik6TN/AUTOSERVICE-AW?node-id=2562-14849&t=wWO9xK4PqrC4tToK-1">https://www.figma.com/design/rOJ6k8HLfI85lI8Xsik6TN/AUTOSERVICE-AW?node-id=2562-14849&t=wWO9xK4PqrC4tToK-1</a><p>

1. Principios de Diseño

Contraste:
Aunque los wireframes no incluyen color, se utilizó contraste mediante tamaños, pesos visuales y jerarquía de elementos para destacar acciones principales como botones y títulos.

Repetición:
Se mantuvo consistencia en la disposición de componentes como formularios, listas y botones, permitiendo que el usuario reconozca patrones de interacción a lo largo de las distintas pantallas.
<div align= center><img src="docs/assets/chapter4-designUX/repetition-wireframe.png" width="300"></div>

Alineación:
Los elementos fueron organizados siguiendo estructuras de grilla, garantizando orden y facilitando la lectura. Esto es evidente en pantallas como el dashboard y los formularios de registro.
<div align= center><img src="docs/assets/chapter4-designUX/align-wireframe.png" width="300"></div>

Proximidad:
Se agruparon elementos relacionados, como campos de formularios o información del vehículo, para mejorar la comprensión y reducir la carga cognitiva del usuario.
<div align= center><img src="docs/assets/chapter4-designUX/proximity-wireframe.png" width="300"></div>

2. Elementos de Diseño Utilizados
- Formularios estructurados (registro de vehículo, datos del cliente)
- Tablas y listas (vehículos, órdenes de trabajo)
- Botones de acción (primarios y secundarios)
- Contenedores o secciones (cards)
- Menú de navegación lateral (sidebar)
- Indicadores de progreso y estados

Estos elementos fueron definidos de manera genérica para posteriormente ser estilizados en los mock-ups.

3. Diseño Inclusivo
- Distribución clara de elementos para facilitar la comprensión
- Formularios simples con campos bien organizados
- Navegación predecible y consistente
- Reducción de pasos innecesarios en los flujos

Esto permite que el sistema sea fácil de usar incluso para usuarios con poca experiencia digital.

4. Arquitectura de Información

Los wireframes evidencian una arquitectura clara basada en los flujos del sistema:

Panel Administrador:
- Dashboard como punto de entrada
- Navegación lateral persistente
- Módulos organizados por funcionalidad (vehículos, órdenes, tareas, personal, reportes)

<div align= center><img src="docs/assets/chapter4-designUX/information-a.png" width="300"></div>
Flujo de Registro de Vehículo:
- Proceso dividido en pasos (stepper)
- Separación de datos del cliente y del vehículo

Panel Cliente:
- Interfaz simplificada con acciones principales
- Flujo directo para consultar estado o agendar cita
<div align= center><img src="docs/assets/chapter4-designUX/panel-client-wireframe.png" width="300"></div>

Los wireframes sirvieron como base estructural para el desarrollo de los mock-ups, donde posteriormente se incorporaron elementos visuales como color, tipografía e identidad gráfica. Gracias a esta fase previa, se logró validar la organización de la información y los flujos antes de avanzar al diseño de alta fidelidad.

#### 4.4.2. Web Applications Wireflow Diagrams

<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Cliente - dueño del vehículo</td>
    <td class="header">Número</td>
    <td>1</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
      Ingresar al sistema, visualizar y consultar el estado de mi vehículo mediante un código de seguimiento, para conocer el progreso del servicio, el diagnóstico y la fecha estimada de entrega sin necesidad de contactar directamente al taller.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
      El usuario accede a la plataforma del taller e inicia sesión desde la pantalla de login ingresando sus credenciales. Tras una autenticación exitosa, es dirigido al panel principal del cliente, donde puede visualizar las opciones disponibles.

Desde el panel, el usuario selecciona la opción “Consultar estado del vehículo”, lo que lo redirige a la pantalla de consulta. En esta vista, el usuario ingresa el código de seguimiento o identificador del servicio asociado a su vehículo.
Una vez ingresado el código, el usuario hace clic en “Consultar estado”. El sistema valida la información y, si es correcta, muestra la pantalla de estado del vehículo.

En esta pantalla, el usuario puede visualizar el detalle completo del servicio, incluyendo:
<li>Estado actual del mantenimiento (por ejemplo, en proceso)</li>
<li>Lista de tareas realizadas o pendientes</li>
<li>Tiempo estimado de entrega</li>
<li>Costo estimado total</li>
<li>Información adicional relevante del servicio</li>

Con esta información, el usuario obtiene visibilidad clara y en tiempo real sobre el progreso de su vehículo sin necesidad de hacer llamada directa con el taller.
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-1.png)
Wireflow Diagram - 1<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-1.png" width="600px">
</div>

<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Cliente - dueño del vehículo</td>
    <td class="header">Número</td>
    <td>2</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
     Agendar cita de mantenimiento para un vehículo, para seleccionar una fecha y hora disponible de manera rápida y asegurar la atención en el taller sin necesidad de coordinación manual
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
    El usuario accede a la plataforma del taller e inicia sesión desde la pantalla de login ingresando sus credenciales. Una vez autenticado correctamente, es redirigido al panel principal del cliente, donde visualiza las opciones disponibles.

Desde este panel, el usuario selecciona la opción “Agendar cita”, lo que lo lleva al flujo de programación. En la siguiente pantalla, el usuario elige el tipo de servicio requerido (por ejemplo, cambio de aceite, diagnóstico o mantenimiento general). Luego, selecciona una fecha disponible en el calendario y una hora dentro de los horarios habilitados. Tras completar esta selección, hace clic en “Siguiente”.

En el siguiente paso, el usuario visualiza el formulario de agendamiento de citas, donde se muestran o completa sus datos personales y la información del vehículo. Revisa que toda la información sea correcta y continúa seleccionando “Siguiente”.

Finalmente, el sistema procesa la solicitud y muestra una pantalla de confirmación exitosa, indicando que la cita ha sido agendada correctamente, junto con el detalle de la fecha y hora seleccionadas. Con esto, el usuario asegura su atención en el taller sin necesidad de coordinación manual adicional.
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-2.png)
Wireflow Diagram - 2<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-2.png" width="600px">
</div>

<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Administrador - dueño del taller</td>
    <td class="header">Número</td>
    <td>3</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
     Registro y gestion de tareas de servicio para los vehículos, asignando mecánicos y manteniendo el control del estado de los trabajos en curso.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
<ol>
<li>Inicio de sesión: 
El administrador ingresa sus credenciales en la pantalla de login.</li>
<li>Acceso al dashboard: 
El sistema valida la información y lo redirige al dashboard principal.</li>
<li>Navegación a gestión de tareas: 
El administrador accede a la sección “Gestión de Tareas” desde el menú o accesos directos.</li>
<li>Visualización del listado de tareas
El sistema muestra las tareas existentes con sus estados y detalles relevantes.</li>
<li>Inicio de creación de tarea: 
El administrador hace clic en el botón “Crear tarea”.</li>
<li>Despliegue del modal de creación: 
El sistema muestra una ventana modal con el formulario para registrar la nueva tarea.</li>
<li>Ingreso de información: 
El administrador completa los campos requeridos, por ejemplo:
Nombre o descripción de la tarea
Vehículo asociado, 
Prioridad, 
Posible asignación (mecánico o responsable), </li>
<li>Confirmación de creación: 
El administrador hace clic en “Crear tarea”.</li>
<li>Procesamiento de la solicitud: 
El sistema valida los datos y registra la nueva tarea en la base de datos.</li>
<li>Feedback de éxito: 
Se muestra un mensaje/modal indicando que la tarea fue creada correctamente.</li>
<li>Actualización del listado: 
El sistema regresa a la vista de tareas y actualiza la lista mostrando la nueva tarea creada.</li>
</ol>
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-3.png)
Wireflow Diagram - 3<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-3.png" width="800px">
</div>

<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Administrador - dueño del taller</td>
    <td class="header">Número</td>
    <td>4</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
   Registrar un vehículo nuevo en el sistema de manera rápida y sin errores, asegurando que la información ingresada sea válida y quede almacenada correctamente.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
<ol>
<li>Inicio de sesión: 
El administrador accede al sistema ingresando sus credenciales desde la pantalla de login.</li>
<li>Acceso al dashboard: 
Tras autenticarse, el sistema lo redirige al dashboard donde visualiza el estado general del taller.</li>
<li>Navegación a vehículos: 
El administrador accede a la sección “Vehículos en el taller”.</li>
<li>Inicio de registro: 
Hace clic en la acción “Registrar vehículo” para iniciar el proceso.</li>
<li>Ingreso de datos del cliente: 
El sistema muestra el formulario correspondiente.
El administrador completa la información del cliente (nombre, contacto, etc.) y continúa.</li>
<li>Ingreso de datos del vehículo: 
El sistema presenta el siguiente paso del formulario.
El administrador ingresa los datos del vehículo (marca, modelo, año, placa, etc.) y avanza.</li>
<li>Revisión y confirmación: 
El sistema muestra una pantalla de resumen con toda la información ingresada (cliente + vehículo).
El administrador valida que los datos sean correctos.</li>
<li>Confirmación del registro: 
El administrador hace clic en “Registrar vehículo”.</li>
<li>Procesamiento de la información: 
El sistema guarda los datos en la base de datos de forma segura.</li>
<li>Feedback de éxito: 
Se muestra una pantalla de confirmación indicando que el vehículo fue registrado correctamente.</li>
<li>Continuidad de flujo: 
El administrador puede optar por:
Registrar otro vehículo, 
Volver al listado de vehículos</li>
</ol>
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-4.png)
Wireflow Diagram - 4<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-4.png" width="800px">
</div>


<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Administrador - dueño del taller</td>
    <td class="header">Número</td>
    <td>5</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
   Eliminar una tarea registrada en el sistema de forma segura, asegurando que el usuario confirme la acción antes de que la información sea eliminada definitivamente.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
    <ol>
<li>Inicio de sesión
El administrador accede al sistema ingresando sus credenciales válidas desde la pantalla de login.
<li>Acceso al dashboard</li>
Tras autenticarse correctamente, el sistema lo redirige al dashboard principal, donde puede visualizar un resumen general del estado del taller.</li>
<li>Navegación a gestión de tareas
El administrador selecciona la opción “Gestión de Tareas” desde el menú lateral o desde un acceso directo en el dashboard.</li>
<li>Visualización del listado de tareas
El sistema muestra la lista de tareas registradas con información relevante (vehículo, estado, prioridad, etc.).</li>
<li>Selección de tarea a eliminar
El administrador identifica la tarea que desea eliminar y hace clic en el icono o acción de “Eliminar” correspondiente.</li>
<li>Despliegue de modal de confirmación
El sistema presenta una ventana modal solicitando confirmación, indicando que la acción es irreversible.</li>
<li>Confirmación de la acción
El administrador confirma la eliminación haciendo clic en el botón de “Eliminar”.</li>
<li>Procesamiento de la solicitud
El sistema elimina la tarea de forma segura de la base de datos.</li>
<li>Feedback al usuario
El sistema muestra un mensaje de éxito indicando que la tarea fue eliminada correctamente.</li>
<li>Actualización del listado
La lista de tareas se actualiza automáticamente, reflejando la eliminación sin necesidad de recargar la página.</li>
</ol>
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-5.png)
Wireflow Diagram - 5<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-5.png" width="800px">
</div>


<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Administrador - dueño del taller</td>
    <td class="header">Número</td>
    <td>6</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
    Registrar un nuevo mecánico en el sistema, asegurando que sus datos sean ingresados correctamente para su posterior asignación a tareas dentro del taller.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
   El usuario ingresa al sistema desde la pantalla de login proporcionando sus credenciales. El sistema valida la información y, al ser correcta, le permite acceder al dashboard principal, donde puede visualizar métricas generales del taller como carga de trabajo, vehículos en proceso y actividad reciente.
Desde el menú lateral, el administrador navega a la sección de “Gestión de personal”. En esta vista se muestra un listado de mecánicos con información resumida como nombre, especialidad y estado. Esto le permite tener una visión rápida del equipo disponible.
El administrador decide agregar un nuevo mecánico y selecciona la opción correspondiente. El sistema lo dirige a una pantalla con un formulario de registro. Allí, el administrador completa los campos requeridos, incluyendo datos personales, información de contacto y especialidades técnicas.
Una vez que todos los campos obligatorios están completos, el administrador confirma el registro. El sistema procesa la información, valida los datos y guarda correctamente el nuevo mecánico en la base de datos.
Finalmente, el administrador es redirigido nuevamente al listado de personal, donde puede ver al nuevo mecánico agregado. Con esto, el flujo concluye al haber incorporado exitosamente un nuevo miembro al equipo del taller.
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-6.png)
Wireflow Diagram - 6<br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-6.png" width="800px">
</div>


<table>
  <tr>
    <td class="header">User Persona</td>
    <td>Administrador - dueño del taller</td>
    <td class="header">Número</td>
    <td>7</td>
  </tr>
  <tr>
    <td class="header">User Goal</td>
    <td colspan="3" class="italic bold">
     Visualizar y consultar el detalle de los vehículos registrados en el sistema para dar seguimiento a su estado y gestionar la operación del taller.
    </td>
  </tr>
  <tr>
    <td class="header">Happy path</td>
    <td colspan="3">
    El usuario ingresa al sistema desde la pantalla de login introduciendo sus credenciales válidas. Al autenticarse correctamente, accede al dashboard donde puede ver un resumen general de la operación del taller.
Desde el menú principal, navega a la sección “Vehículos en el taller”, donde se muestra un listado con todos los vehículos registrados y su estado actual. El administrador revisa la lista y selecciona un vehículo específico para consultar más información.
Al hacer clic, se abre el detalle del vehículo, donde puede visualizar datos relevantes como cliente, diagnóstico, estado del servicio y progreso del trabajo. Desde esta vista, el administrador puede tomar acciones como generar una orden de trabajo o continuar con la gestión del vehículo.
El flujo finaliza cuando el administrador obtiene la información necesaria y realiza la acción deseada para dar seguimiento al vehículo.
    </td>
  </tr>
</table>

<div align="center">

![alt text](docs/assets/chapter4-designUX/wireflow-7.png)
<p>Wireflow Diagram - 7</p><br><br>
<img src="docs/assets/chapter4-designUX/wireflow-diagram-7.png" width="800px">
</div>

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