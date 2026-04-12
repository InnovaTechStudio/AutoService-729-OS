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

![alt text](assets/READMEmedia/jira_backlog.png)

URL del tablero completo en Jira: https://innovatechstudio.atlassian.net/jira/software/projects/ASS/boards/1/backlog