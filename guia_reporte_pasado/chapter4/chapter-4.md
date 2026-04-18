# Capítulo IV: Product Implementation & Validation

# 4. Product Implementation & Validation

## 4.1. Software Configuration Management

En este apartado se describe el proceso mediante el cual se organiza, gestiona y controla la configuración del software y los cambios en el desarrollo del proyecto. El objetivo es garantizar que todos los integrantes del equipo trabajen bajo un mismo entorno, utilizando herramientas estandarizadas y metodologías que aseguren la trazabilidad, la calidad y la colaboración continua.
### 4.1.1 Software Development Environment Configuration.
**Requirements Management**
1.Requirements Management

Trello: Plataforma de gestión de proyectos basada en tableros Kanban. Será utilizada por el equipo de PsyMed para planificar, organizar y hacer seguimiento del trabajo, especialmente bajo metodologías ágiles (Scrum). Permite asignar responsables, definir prioridades y actualizar el estado de cada tarea en tiempo real, lo que mejora la visibilidad del progreso y la coordinación del equipo.

Ruta de referencia: https://trello.com/es

Tableros de la organización: https://trello.com/invite/b/68e438bc12fe9651d240dfe1/ATTIc34f9aa0fa66bc1feb777cef9467dfeeE331B2D7/diseno

**Product UX/UI Design**

1. Figma: Herramienta colaborativa para el diseño de interfaces y prototipado. Se empleará en la construcción de los prototipos de la aplicación, tanto en su versión Desktop como en Mobile Web Browser. Facilita el diseño en equipo y permite iterar rápidamente en el aspecto visual antes del desarrollo.

Ruta de referencia: https://www.figma.com/login

**Software Development**
1. WebStorm: Entorno de desarrollo integrado (IDE) especializado en tecnologías web. Ha sido elegido por su soporte avanzado para HTML, CSS, JavaScript y frameworks como React y Angular. Ofrece herramientas de refactorización, depuración, integración con Git y compatibilidad multiplataforma, lo que optimiza la productividad y estandariza el desarrollo del equipo.

   Ruta de referencia: https://www.jetbrains.com/webstorm/
   <br><br>

2. HTML5: Lenguaje de marcado utilizado para estructurar y presentar el contenido de la aplicación web. Servirá como base para la maquetación de la interfaz.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp
   <br><br>

3. CSS: Lenguaje de hojas de estilo en cascada para definir la presentación visual del contenido. En conjunto con HTML, permitirá dar estilo, diseño adaptable y coherencia visual a la aplicación.

   Ruta de referencia: https://google.github.io/styleguide/htmlcssguide.html
   <br>
   <br>

4. JavaScript: Lenguaje de programación dinámico y orientado a objetos. Se utilizará para el desarrollo de la lógica de la interfaz y la interacción del usuario con la aplicación.

   Ruta de referencia: https://developer.mozilla.org/es/docs/Web/JavaScript
   <br>
   <br>

5. Angular: Framework de JavaScript escrito en TypeScript. Será la principal tecnología para el desarrollo del front-end del proyecto PsyMed. Permite crear aplicaciones escalables, modulares y mantenibles. El código desarrollado se encuentra alojado en el repositorio correspondiente.

   Ruta de referencia: https://github.com/Diseno-de-experimentos-Grupo-2/psymed-frontend
   <br><br>
6. Android Studio: Entorno de desarrollo integrado (IDE) oficial para el desarrollo de aplicaciones Android. Se utilizará para crear la versión móvil de la aplicación PsyMed, aprovechando sus herramientas de diseño, emulación y depuración específicas para dispositivos Android.

   Ruta de referencia: https://developer.android.com/studio
   <br>
   <br>
7. Flutter: Framework de código abierto desarrollado por Google para la creación de aplicaciones nativas multiplataforma. Se empleará para desarrollar la aplicación móvil de PsyMed, permitiendo compartir una base de código entre Android e iOS, lo que optimiza el tiempo de desarrollo y asegura una experiencia consistente en ambas plataformas. <br> <br>
8. Dart: Lenguaje de programación optimizado para aplicaciones de interfaz de usuario. Será el lenguaje principal utilizado en conjunto con Flutter para desarrollar la lógica y funcionalidad de la aplicación móvil PsyMed.

   Ruta de referencia: https://dart.dev/
   <br>
   <br>
9. Jetpack Compose: Conjunto de herramientas modernas para construir interfaces de usuario nativas en Android. Se utilizará para diseñar y desarrollar la interfaz de la aplicación móvil PsyMed, facilitando la creación de componentes reutilizables y una experiencia de usuario fluida.

   Ruta de referencia: https://developer.android.com/jetpack/compose
   <br>
   <br>
10. Kotlin: Lenguaje de programación moderno y conciso para el desarrollo de aplicaciones Android. Se empleará para complementar el desarrollo de la aplicación móvil PsyMed, aprovechando su interoperabilidad con Java y sus características avanzadas que mejoran la productividad del desarrollador.

   Ruta de referencia: https://kotlinlang.org/
   <br>
   <br>

**Software Deployment**
1. Git: Sistema de control de versiones distribuido. Permitirá a los integrantes del equipo llevar un registro detallado de los cambios, gestionar ramas de desarrollo, y facilitar la integración de nuevas funcionalidades sin comprometer la estabilidad del proyecto.

   Ruta de referencia: https://git-scm.com/
   <br>
   <br>
   **Software Documentation and Project Management**
2. GitHub: Plataforma colaborativa en la nube para el alojamiento de repositorios Git. Será el medio oficial para la centralización del código, revisión de contribuciones y gestión de issues, además de permitir la integración con otras herramientas de desarrollo y CI/CD

   Ruta de referencia: https://github.com/


### 4.1.2. Source Code Management.
El proyecto adoptará las convenciones del modelo GitFlow para la gestión del control de versiones, utilizando GitHub como plataforma principal para alojar y organizar el código. GitFlow es un enfoque estructurado que facilita la colaboración en equipo, la integración de cambios y la gestión de múltiples versiones del software. Este modelo asegura que cada etapa de desarrollo esté debidamente aislada, probada y documentada antes de ser integrada en la rama principal.

A continuación, se detalla cómo se implementará este flujo de trabajo, junto con los enlaces a los repositorios donde se centralizan los entregables principales:

**Repositorio de GitHub:**
- Enlace para acceder a la [organización en GitHub](https://github.com/Diseno-de-experimentos-Grupo-2)
- Enlace para acceder al repositorio de la [Landing Page](https://github.com/Diseno-de-experimentos-Grupo-2/Landing-Page)
- Enlace para acceder al repositorio del [Reporte Final](https://github.com/Diseno-de-experimentos-Grupo-2/psymed-report)
- Enlace para acceder al repositorio del [Frontend Web](https://github.com/Diseno-de-experimentos-Grupo-2/psymed-frontend)
- Enlace para acceder al repositorio del [Frontend Móvil](https://github.com/Diseno-de-experimentos-Grupo-2/psymed-mobile-flutter)

**Flujo de trabajo GitFlow**

El flujo de trabajo se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

![GitFlowDiagram.png](../../assets/GitFlowDiagram.png)

**Estructura de branches (Ramas):**


1. **Master branch (Rama principal):** Contendrá únicamente versiones estables y listas para producción. Los cambios que lleguen aquí deberán haber pasado por pruebas y validaciones en develop y feature branches.

2. **Develop Branch (Rama de Desarrollo):** Funciona como la rama de integración, donde se combinan y prueban las nuevas funcionalidades antes de ser promovidas a master. Garantiza que el código en desarrollo se mantenga operativo y estable.

3. **Feature branch (Ramas de funcionalidad):** Cada nueva característica o mejora se desarrollará en una rama independiente creada a partir de develop. Una vez finalizada y probada, se fusionará nuevamente en develop.

Convención de nombres: feature/nombre-descriptivo.
Ejemplo: feature/bc-medication-management.

### 4.1.3. Source Code Style Guide & Conventions.
**HTML:** Para garantizar un código legible, mantenible y coherente, se seguirán las siguientes prácticas y guías de estilo:

1. Cerrar todos los elementos HTML: Por ejemplo, ```<p>Esto es un párrafo.</p>```
2. Siempre declarar el tipo de documento en la primera línea del documento, para
   HTML es "<!DOCTYPE html>”.
3. Escribir en una línea los comentarios cortos.
4. Utilizar comillas en caso de que los atributos contengan espacios entre sí.
5. Procurar especificar el texto alt y las dimensiones width y height de las imágenes, ya que de esta manera se facilitará la
   disponibilidad del contenido. Por ejemplo:   ```<img src="abc.img" alt="image name"  
   style="width:128px;height:128px">```
6. Se nos recomienda no usar el espacio al momento de utilizar los signos porque
   es más fácil de leerlo de esta forma.  
   <br>
   HTML: (https://www.w3schools.com/html/html5_syntax.asp)

**CSS:** Entre las prácticas empleadas se menciona:

1. Usar sangría de 2 espacios, evitando tabulaciones.
2. Escribir el código en minúsculas.
3. Eliminar espacios en blanco innecesarios.
4. Documentar el código mediante comentarios.
5. Utilizar nombres de clase descriptivos y significativos.
   <br>

   CSS: (https://google.github.io/styleguide/htmlcssguide.html)



### 4.1.4. Software Deployment Configuration.

### Landing page deployment:
Para el despliegue de la Landing Page se utilizará GitHub Pages, siguiendo los pasos descritos a continuación:

1. Colocar los archivos de la página en la raíz del repositorio.
2. Nombrar los archivos de acuerdo a las convenciones: "index.html" para la landing page, "styles.css" para los estilos, "main.js" para los scripts, y una carpeta llamada "assets/images" para las imágenes.
3. Subir los archivos al repositorio mediante un commit.
4. Ir a Settings > Pages y seleccionar el branch main.
5. Definir la carpeta raíz (root) como fuente de la página.
6. Esperar que GitHub realice las validaciones necesarias.
7. Acceder al enlace generado para visualizar la página desplegada.

## GithubPages

![alt text](../../assets/GithubPages.png)
Una vez completado el despliegue, la landing page quedará publicada y accesible públicamente mediante el enlace: https://wx55-closed-source.github.io/landing-page/

## 4.2. Landing Page & Mobile Application Implementation
### 4.2.1. Sprint 1
#### 4.2.1.1. Sprint Planning 1

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 1</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td>Implementación inicial de la plataforma PsyMed para profesionales de la salud mental y pacientes.</td>
  </tr>
  <tr>
    <th>Date</th>
    <td>2025-11-08</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>10:00 AM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Reunión virtual vía Discord</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td>Maita Falckenheiner, Romina Guadalupe</td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>Torres Flores, Paolo Alessandro</td>
  </tr>
  <tr>
    <th>Sprint 1 – 1 Review Summary</th>
    <td>No aplica — este es el Sprint inicial del proyecto PsyMed.</td>
  </tr>
  <tr>
    <th>Sprint 1 – 1 Retrospective Summary</th>
    <td>No aplica — no existen iteraciones anteriores.</td>
  </tr>
  <tr>
    <th>Sprint Goal &amp; User Stories</th>
    <td></td>
  </tr>
  <tr>
    <th>Sprint 1 Goal</th>
    <td>
      <strong>Nuestro enfoque está en</strong> entregar la primera versión funcional de la plataforma PsyMed, que permita la conexión entre profesionales de la salud mental y sus pacientes para una gestión eficiente de las terapias.<br>
      <strong>Creemos que esto ofrece</strong> una mejora en la comunicación, el seguimiento de tratamientos y la gestión de citas en un entorno seguro y accesible para profesionales de la salud mental y pacientes.<br>
      <strong>Esto se confirmará cuando</strong> los usuarios puedan registrarse, agendar sesiones y hacer seguimiento de su progreso terapéutico dentro de la plataforma móvil, con funcionamiento estable en los módulos principales.
    </td>
  </tr>
  <tr>
    <th>Sprint 1 - Velocity</th>
    <td>Estimado en 162 Story Points, enfocado en entregar el MVP con funcionalidades de backend, frontend y autenticación.</td>
  </tr>
  <tr>
    <th>Sprint 1 - Story Points</th>
    <td>162 Story Points distribuidos en 40 User Stories, incluyendo registro, inicio de sesión, gestión de pacientes, programación de citas, gestion de medicación y control de estado</td>
  </tr>
</table>

#### 4.2.1.2. Sprint Backlog 1

Durante este Sprint, el equipo se enfocó en desarrollar la primera versión funcional completa de PsyMed, una plataforma web y móvil 
destinada a optimizar la gestión, comunicación y seguimiento de pacientes en terapia con profesionales de la salud mental. El objetivo fue 
implementar todas las funcionalidades esenciales del MVP (web, móvil y landing page), garantizando el flujo completo de registro, inicio de sesión, 
gestión de pacientes, citas, medicamentos y monitoreo del estado emocional.

**Url del trello:** https://trello.com/invite/b/68e438bc12fe9651d240dfe1/ATTIc34f9aa0fa66bc1feb777cef9467dfeeE331B2D7/psymed-moviles-sprint-1
<br>

<br>

<img width="1299" height="631" alt="image" src="https://github.com/user-attachments/assets/03a13d13-6c5b-4499-9882-22f086644cb4" />



<br>

<table>
  <tr>
    <th colspan="1">Sprint #</th>
    <td colspan="7">Sprint 1</td>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="5">Work-Item / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status</th>
  </tr>

  <tr>
    <td>US01</td>
    <td>Registrar como profesional de la salud mental</td>
    <td>T01</td>
    <td>Implementar formulario de registro</td>
    <td>Creación del formulario de registro para profesionales con validación de credenciales.</td>
    <td>6</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T02</td>
    <td>Conexión backend para registro</td>
    <td>Configurar endpoint para registro de profesionales y guardado en base de datos.</td>
    <td>8</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US02</td>
    <td>Iniciar sesión como paciente</td>
    <td>T03</td>
    <td>Diseño de interfaz de login</td>
    <td>Diseñar la vista de inicio de sesión para pacientes.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T04</td>
    <td>Validación de credenciales (backend)</td>
    <td>Desarrollar lógica de autenticación y validación JWT para pacientes.</td>
    <td>6</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US03</td>
    <td>Iniciar sesión como profesional de la salud mental</td>
    <td>T05</td>
    <td>Interfaz de login para profesionales</td>
    <td>Diseñar y desarrollar la interfaz de inicio de sesión para profesionales.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US04</td>
    <td>Registrar información personal del paciente</td>
    <td>T06</td>
    <td>Formulario de datos personales</td>
    <td>Diseñar formulario para registrar datos personales de pacientes.</td>
    <td>5</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US05</td>
    <td>Visualizar estado de ánimo del paciente</td>
    <td>T07</td>
    <td>Implementar módulo de visualización</td>
    <td>Diseñar gráfico y panel para mostrar estado de ánimo actual.</td>
    <td>5</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US06</td>
    <td>Registrar estado de ánimo</td>
    <td>T08</td>
    <td>Creación del formulario de estado de ánimo</td>
    <td>Permitir al paciente registrar su estado emocional diario.</td>
    <td>4</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US07</td>
    <td>Registrar funciones biológicas</td>
    <td>T09</td>
    <td>Implementar formulario de funciones biológicas</td>
    <td>Registro de sueño, apetito, energía e hidratación.</td>
    <td>5</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US08</td>
    <td>Registrar medicamentos del paciente</td>
    <td>T10</td>
    <td>Formulario de medicamentos</td>
    <td>Desarrollo del módulo para registrar medicamentos asignados.</td>
    <td>6</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US09</td>
    <td>Ver medicamentos</td>
    <td>T11</td>
    <td>Implementar vista de medicamentos</td>
    <td>Visualización de medicamentos asignados al paciente.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US10</td>
    <td>Crear citas</td>
    <td>T12</td>
    <td>Diseño de módulo de citas</td>
    <td>Crear interfaz para agendar citas entre profesional y paciente.</td>
    <td>6</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US11</td>
    <td>Ver citas médicas</td>
    <td>T13</td>
    <td>Visualización de citas</td>
    <td>Mostrar citas médicas del paciente con detalle de fecha y profesional.</td>
    <td>4</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US12</td>
    <td>Iniciar sesión como paciente (Móvil)</td>
    <td>T14</td>
    <td>UI Login Móvil</td>
    <td>Implementar vista con campos de usuario, contraseña y validación de campos vacíos.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T15</td>
    <td>Integración Auth Móvil</td>
    <td>Conectar con API para validar credenciales y manejar tokens de sesión.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US13</td>
    <td>Visualizar información de perfil (Móvil)</td>
    <td>T16</td>
    <td>Vista de Perfil</td>
    <td>Crear pantalla que muestre nombre, correo, dirección e ID recuperados del backend.</td>
    <td>2</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US14</td>
    <td>Cerrar sesión (Móvil)</td>
    <td>T17</td>
    <td>Lógica de Logout</td>
    <td>Implementar funcionalidad para eliminar datos de sesión y redirigir al login.</td>
    <td>1</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US15</td>
    <td>Registrar mi estado de salud diario (Móvil)</td>
    <td>T18</td>
    <td>Formulario de Salud Móvil</td>
    <td>Desarrollar interfaz para ingreso de estado diario y conexión POST API.</td>
    <td>4</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US16</td>
    <td>Consultar lista de medicamentos (Móvil)</td>
    <td>T19</td>
    <td>Listado de Medicamentos Móvil</td>
    <td>Implementar lista para mostrar medicamentos, dosis y frecuencia.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US17</td>
    <td>Ver próximas citas (Móvil)</td>
    <td>T20</td>
    <td>Listado de Citas Móvil</td>
    <td>Crear vista de citas próximas con distinción visual para la cita del día actual.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
</table>



#### 4.2.1.3. Development Evidence for Sprint Review

Durante este Sprint, se completó la implementación funcional de PsyMed, incluyendo la versión móvil y su backend.
Se desarrollaron los principales módulos de autenticación, gestión de pacientes, manejo de medicamentos, control de sesiones, visualización de estadísticas emocionales y biológicas, y mejoras en la interfaz de usuario.
Las evidencias de desarrollo se reflejan en los commits realizados en el repositorio principal del proyecto de la aplicación móvil y el backend.

#### Aplicación móvil PsyMed
<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Commited on (Date)</th>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>001a3d9</td>
    <td>chore: initial commit</td>
    <td>Configuración inicial del repositorio y estructura base del proyecto PsyMed.</td>
    <td>2025-11-09</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>fa97d25</td>
    <td>refactor: streamline analytics and tasks screen layouts; improve loading state handling</td>
    <td>Optimización de las pantallas de analíticas y tareas, mejorando la gestión de estados de carga.</td>
    <td>2025-11-09</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>f1a29d7</td>
    <td>refactor: improve analytics loading and calculation methods; enhance date parsing logic</td>
    <td>Mejora en los métodos de carga y cálculo de analíticas, con optimización en el análisis de fechas.</td>
    <td>2025-11-10</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>d9f22b6</td>
    <td>refactor: streamline analytics and tasks screen layouts; improve loading state handling</td>
    <td>Refactorización del diseño de pantallas de analíticas y tareas, mejorando el manejo del estado de carga.</td>
    <td>2025-11-10</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>cc1a6f8</td>
    <td>feat: add PSYMED logo to login screen and include in asset bundle</td>
    <td>Incorporación del logotipo oficial de PsyMed en la pantalla de inicio de sesión y su inclusión en los recursos del proyecto.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>e2f1c9d</td>
    <td>refactor: update app color palette to Mint/Teal theme and adjust theme usage in AppTheme</td>
    <td>Actualización de la paleta de colores de la aplicación al tema Mint/Teal y ajuste del uso de temas globales.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>a6b4f31</td>
    <td>feat: add registration screen for professionals and update API services</td>
    <td>Creación de la pantalla de registro para profesionales y actualización de servicios API.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>d9f22b6</td>
    <td>feat: replace top TabBar with bottom navigation for improved navigation experience</td>
    <td>Sustitución de la barra de navegación superior por navegación inferior para una mejor experiencia de usuario.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>f1a29d7</td>
    <td>feat: add mood and biological statistics cards to patient detail screen</td>
    <td>Integración de tarjetas de estadísticas de estado de ánimo y funciones biológicas en el detalle del paciente.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>3d8a7e2</td>
    <td>feat: implement medication management with add, edit, and delete functionalities</td>
    <td>Implementación del módulo de manejo de medicamentos con opciones de agregar, editar y eliminar.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>1e2b4c8</td>
    <td>feat: enhance session management with create, update, and delete functionalities</td>
    <td>Gestión de sesiones con funciones de creación, actualización y eliminación; refactor de manejo de tiempos de sesión.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>7c9d1f4</td>
    <td>feat: add task update functionality and enhance error handling in task service</td>
    <td>Implementación de la actualización de tareas y mejora en el manejo de errores dentro del servicio de tareas.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>8b7d2e9</td>
    <td>feat: refactor task progress display and enhance UI for better user experience</td>
    <td>Refactorización de la visualización del progreso de tareas y mejora de la experiencia de usuario en la interfaz móvil.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Mobile-Dev-upc/PsyMed-Flutter</td>
    <td>feature/professionalversion</td>
    <td>14ca4e3</td>
    <td>Merge pull request #1 from Mobile-Dev-upc/feature/professionalversion</td>
    <td>Integración de los cambios principales para la versión profesional de PsyMed.</td>
    <td>2025-11-11</td>
  </tr>
</table>

#### Backend PsyMed

<table>
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Commited on (Date)</th>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>c01a8d9</td>
    <td>chore: add domain models and commands for roles, pills, and patient profiles</td>
    <td>Creación de modelos de dominio y comandos para roles, medicamentos y perfiles de pacientes, estableciendo la base del dominio DDD.</td>
    <td>2025-11-10</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>a02b7e4</td>
    <td>feat: implement update and delete functionality for patient profiles and tasks</td>
    <td>Implementación de funcionalidades para actualizar y eliminar perfiles de pacientes y tareas.</td>
    <td>2025-11-10</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>b03c6f5</td>
    <td>feat: add commands and resource assemblers for updating and deleting patient profiles and tasks</td>
    <td>Agregados comandos y ensambladores de recursos para actualizar y eliminar tareas y perfiles de pacientes en la capa de aplicación.</td>
    <td>2025-11-10</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>c15d4e2</td>
    <td>feat: implement update and delete functionality for notes in patient sessions</td>
    <td>Implementación de endpoints y comandos para actualizar y eliminar notas en sesiones de pacientes.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>d27e8b1</td>
    <td>feat: implement functionality to mark tasks as incomplete</td>
    <td>Desarrollo de funcionalidad para permitir marcar tareas como incompletas dentro del seguimiento de sesiones.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>e31c9a7</td>
    <td>feat: add createdAt field to BiologicalFunctionResource and MoodStateResource</td>
    <td>Adición de campos <code>createdAt</code> en los recursos de función biológica y estado de ánimo para mejorar trazabilidad.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>f48b6d2</td>
    <td>feat: implement update functionality for pills</td>
    <td>Implementación de actualización de información de medicamentos en la capa de servicios.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>g59d7c4</td>
    <td>feat: implement update and delete functionality for sessions</td>
    <td>Desarrollo de las operaciones de actualización y eliminación para sesiones de pacientes.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>h64a9e8</td>
    <td>feat: add Docker configuration for backend and MySQL services</td>
    <td>Configuración de contenedores Docker para el backend y el servicio de base de datos MySQL, facilitando el despliegue del entorno.</td>
    <td>2025-11-11</td>
  </tr>

  <tr>
    <td>Backend-Dev-upc/psymed-backend-appmoviles</td>
    <td>main</td>
    <td>i73b2f1</td>
    <td>fix: change Hibernate ddl-auto setting from validate to update for production environment</td>
    <td>Ajuste de la configuración de Hibernate en producción de <code>validate</code> a <code>update</code> para sincronización automática de esquemas.</td>
    <td>2025-11-11</td>
  </tr>
</table>


#### 4.2.1.4. Testing Suite Evidence for Sprint Review

En esta sección se detallarán los user stories implementadas en el presente sprint con sus respectivos tests de aceptación (Gherkin).

### US01
Feature: Registro de profesional de la salud mental  
Como profesional de la salud mental<br>
Quiero registrarme con mis credenciales<br>
Para acceder a las funcionalidades específicas y gestionar información de mis pacientes.<br>

Escenario: Registro exitoso<br>
Dado que el profesional de la salud mental proporciona la información requerida para su registro<br>
Cuando el sistema valida la información ingresada<br>
Entonces el sistema debe registrar los datos del profesional de forma segura<br>
Y asignarle el rol correspondiente de profesional de la salud mental<br>

Escenario: Información incompleta<br>
Dado que el profesional no proporciona toda la información requerida<br>
Cuando el sistema valida los datos<br>
Entonces el sistema debe rechazar el registro<br>
Y notificar qué información falta para completarlo<br>

Escenario: Credenciales duplicadas<br>
Dado que el profesional intenta registrarse con credenciales ya existentes<br>
Cuando el sistema valida la información<br>
Entonces el sistema debe impedir el registro<br>
Y notificar que las credenciales ya están registradas, sugiriendo la recuperación de acceso<br><br>

---

### US02
Feature: Inicio de sesión como paciente  
Como paciente<br>
Quiero iniciar sesión en la plataforma<br>
Para acceder a mi información personal y seguimiento de tratamiento.<br>

Escenario: Inicio exitoso<br>
Dado que el paciente proporciona credenciales válidas<br>
Cuando el sistema las valida<br>
Entonces el sistema debe permitir el acceso al entorno del paciente<br>
Y habilitar las funciones asociadas a su rol<br>

Escenario: Credenciales incorrectas<br>
Dado que el paciente ingresa credenciales incorrectas<br>
Cuando el sistema valida la información<br>
Entonces el sistema debe denegar el acceso<br>
Y notificar que las credenciales no son válidas, ofreciendo una opción de recuperación<br>

Escenario: Recuperación de acceso<br>
Dado que el paciente solicita recuperar su acceso<br>
Cuando el sistema procesa la solicitud<br>
Entonces debe enviar un enlace de restablecimiento al correo electrónico registrado<br><br>

---

### US03
Feature: Inicio de sesión como profesional de la salud mental  
Como profesional de la salud mental<br>
Quiero iniciar sesión en la plataforma<br>
Para gestionar la información de mis pacientes y acceder a herramientas de seguimiento.<br>

Escenario: Inicio exitoso<br>
Dado que el profesional proporciona credenciales válidas<br>
Cuando el sistema las valida<br>
Entonces el sistema debe permitir el acceso<br>
Y habilitar las funciones de gestión de pacientes correspondientes a su rol<br>

Escenario: Credenciales inválidas<br>
Dado que el profesional proporciona credenciales incorrectas<br>
Cuando el sistema las valida<br>
Entonces el sistema debe denegar el acceso<br>
Y notificar el error, ofreciendo la opción de restablecer el acceso<br>

Escenario: Recuperación de acceso<br>
Dado que el profesional solicita recuperar su contraseña<br>
Cuando el sistema procesa la solicitud<br>
Entonces debe enviar un enlace de restablecimiento al correo asociado<br><br>

---

### US04
Feature: Registro de información personal del paciente  
Como profesional de la salud mental<br>
Quiero registrar la información personal del paciente<br>
Para tener una referencia detallada y precisa de sus datos básicos en cada consulta.<br>

Escenario: Registro exitoso<br>
Dado que el profesional proporciona toda la información requerida del paciente<br>
Cuando el sistema valida los datos<br>
Entonces debe almacenar la información de manera segura y asociarla al perfil del paciente<br>

Escenario: Datos incompletos<br>
Dado que el profesional no completa toda la información requerida<br>
Cuando el sistema valida los datos<br>
Entonces debe impedir el registro<br>
Y notificar qué información falta para completarlo<br><br>

---

### US05
Feature: Visualización del estado de ánimo del paciente  
Como profesional de la salud mental<br>
Quiero visualizar el estado de ánimo actual del paciente<br>
Para evaluar su condición emocional.<br>

Escenario: Estado disponible<br>
Dado que existe un registro del estado de ánimo del paciente<br>
Cuando el sistema consulta el perfil<br>
Entonces debe mostrar el estado de ánimo más reciente registrado<br>

Escenario: Sin registros previos<br>
Dado que no existen registros de estado de ánimo<br>
Cuando el sistema realiza la consulta<br>
Entonces debe indicar la ausencia de registros disponibles<br><br>

---

### US06
Feature: Registro de estado de ánimo  
Como paciente<br>
Quiero comunicar mi estado emocional actual<br>
Para que mi profesional pueda evaluar mi progreso.<br>

Escenario: Registro exitoso<br>
Dado que el paciente proporciona su estado emocional actual<br>
Cuando el sistema valida la información<br>
Entonces el sistema debe almacenar el registro de estado de ánimo<br>
Y asociarlo al perfil del paciente<br>

Escenario: Visualización del historial<br>
Dado que el paciente tiene registros previos de estados de ánimo<br>
Cuando el sistema consulta el historial<br>
Entonces debe mostrar los registros anteriores organizados cronológicamente<br><br>

---

### US07
Feature: Registro de funciones biológicas  
Como paciente<br>
Quiero registrar mis funciones biológicas<br>
Para que mi profesional conozca mi estado de salud actual.<br>

Escenario: Registro exitoso<br>
Dado que el paciente proporciona información sobre sueño, hambre, energía e hidratación<br>
Cuando el sistema valida y procesa los datos<br>
Entonces debe almacenar la información en su perfil<br>
Y permitir su posterior consulta por el profesional<br><br>

---

### US08
Feature: Registro de medicamentos del paciente  
Como profesional de la salud mental<br>
Quiero registrar los medicamentos del paciente<br>
Para seguir adecuadamente su tratamiento farmacológico.<br>

Escenario: Registro exitoso<br>
Dado que el profesional proporciona toda la información requerida del medicamento<br>
Cuando el sistema valida los datos<br>
Entonces debe registrar la información y asociarla al paciente<br>

Escenario: Información incompleta<br>
Dado que la información ingresada es incompleta o incorrecta<br>
Cuando el sistema valida los datos<br>
Entonces debe rechazar el registro<br>
Y notificar los campos que necesitan corrección<br><br>

---

### US09
Feature: Visualización de medicamentos del paciente  
Como paciente<br>
Quiero ver los medicamentos que me asignó mi profesional<br>
Para poder seguir correctamente mi tratamiento.<br>

Escenario: Visualización de medicamentos<br>
Dado que existen medicamentos registrados por el profesional<br>
Cuando el sistema consulta la información<br>
Entonces debe mostrar la lista completa de medicamentos y sus detalles<br>

Escenario: Sin medicamentos registrados<br>
Dado que no hay medicamentos asignados<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje indicando la ausencia de registros<br><br>

---

### US10
Feature: Creación de citas  
Como profesional de la salud mental<br>
Quiero agendar citas con mis pacientes<br>
Para organizar las sesiones de terapia.<br>

Escenario: Creación de cita<br>
Dado que el profesional proporciona fecha, hora, duración y paciente<br>
Cuando el sistema valida y registra la información<br>
Entonces debe crear la cita y asociarla al paciente<br><br>

---

### US11
Feature: Visualización de citas médicas  
Como paciente<br>
Quiero ver mis citas médicas programadas<br>
Para saber cuándo debo asistir al consultorio.<br>

Escenario: Visualización de citas<br>
Dado que existen citas registradas<br>
Cuando el sistema consulta las citas del paciente<br>
Entonces debe mostrar la lista con fecha, hora y profesional asignado<br>

Escenario: Sin citas registradas<br>
Dado que no existen citas programadas<br>
Cuando el sistema realiza la consulta<br>
Entonces debe indicar que no hay citas próximas<br><br>

---

### US12
Feature: Inicio de sesión como paciente en aplicación móvil  
Como paciente<br>
Quiero iniciar sesión con mi usuario y contraseña<br>
Para acceder a mi información personal y de salud dentro de la aplicación móvil.<br>

Escenario: Inicio exitoso<br>
Dado que el paciente proporciona credenciales válidas<br>
Cuando el sistema las valida<br>
Entonces debe permitir el acceso al entorno móvil del paciente<br>
Y cargar su información personal<br>

Escenario: Credenciales inválidas<br>
Dado que el paciente proporciona credenciales incorrectas<br>
Cuando el sistema valida la información<br>
Entonces debe rechazar el acceso<br>
Y mostrar un mensaje de error<br>

Escenario: Campos vacíos<br>
Dado que el paciente deja campos de autenticación vacíos<br>
Cuando el sistema valida la solicitud<br>
Entonces debe impedir el acceso<br>
Y notificar la ausencia de datos requeridos<br><br>

---

### US13
Feature: Visualización de información de perfil en aplicación móvil  
Como paciente<br>
Quiero ver mi información personal<br>
Para confirmar que mis datos sean correctos dentro de la aplicación.<br>

Escenario: Visualización del perfil<br>
Dado que el paciente accede a su perfil<br>
Cuando el sistema recupera su información<br>
Entonces debe mostrar nombre, correo, dirección, ID de paciente y profesional asociado<br><br>

---

### US14
Feature: Cierre de sesión en aplicación móvil  
Como paciente<br>
Quiero cerrar mi sesión de forma segura<br>
Para proteger mi privacidad y evitar accesos no autorizados.<br>

Escenario: Cierre exitoso<br>
Dado que el paciente ha iniciado sesión<br>
Cuando solicita cerrar sesión<br>
Entonces el sistema debe finalizar la sesión activa<br>
Y eliminar los datos temporales de autenticación<br><br>

---

### US15
Feature: Registro del estado de salud diario en aplicación móvil  
Como paciente<br>
Quiero registrar mi estado de salud diario<br>
Para llevar un seguimiento de mi bienestar y progreso terapéutico.<br>

Escenario: Registro exitoso<br>
Dado que el paciente proporciona su estado diario en todas las categorías requeridas<br>
Cuando el sistema valida y guarda la información<br>
Entonces debe registrar los datos de ese día<br>
Y confirmar la acción<br>

Escenario: Registro duplicado<br>
Dado que el paciente ya registró su estado diario<br>
Cuando intenta volver a hacerlo el mismo día<br>
Entonces el sistema debe impedir el registro duplicado<br>
Y notificar que ya existe un registro para esa fecha<br><br>

---

### US16
Feature: Consulta de lista de medicamentos en aplicación móvil  
Como paciente<br>
Quiero ver mi lista de medicamentos asignados<br>
Para conocer los detalles de motivo, frecuencia e intervalo.<br>

Escenario: Visualización de medicamentos<br>
Dado que existen medicamentos registrados<br>
Cuando el sistema recupera la información<br>
Entonces debe mostrar cada medicamento con su motivo, intervalo y cantidad<br>

Escenario: Sin medicamentos registrados<br>
Dado que el paciente no tiene medicamentos asignados<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje informando la ausencia de registros<br><br>

---

### US17
Feature: Visualización de próximas citas en aplicación móvil  
Como paciente<br>
Quiero ver mis próximas citas médicas con sus detalles<br>
Para planificar mi asistencia de forma eficiente.<br>

Escenario: Visualización de citas futuras<br>
Dado que existen citas programadas<br>
Cuando el sistema recupera la información<br>
Entonces debe mostrar la lista con fecha, hora, duración y profesional asignado<br>

Escenario: Cita actual<br>
Dado que existe una cita para la fecha actual<br>
Cuando el sistema carga la información<br>
Entonces debe marcarla con una etiqueta distintiva que indique “Cita de hoy”<br>

Escenario: Sin citas registradas<br>
Dado que no hay citas programadas<br>
Cuando el sistema consulta la información<br>
Entonces debe mostrar un mensaje que indique que no hay citas próximas<br><br>


#### 4.2.1.5. Execution Evidence for Sprint Review

En esta sección se muestra la evidencia de la ejecución del sprint, incluyendo las capturas del proyecto en funcionamiento.

<img width="1571" height="1008" alt="image" src="https://github.com/user-attachments/assets/27d21a8e-4430-4a0a-8b40-45d54ffd94ef" />

<br>

<img width="504" height="858" alt="image" src="https://github.com/user-attachments/assets/88081474-14ea-46d3-b0ac-2a8e35686639" />

<br>

<img width="486" height="855" alt="image" src="https://github.com/user-attachments/assets/25307ee0-52bf-4209-8777-e28303688f49" />

<br>

<img width="485" height="851" alt="image" src="https://github.com/user-attachments/assets/f6aa20f0-9de2-472b-930a-558872cb2858" />

<br>

<img width="482" height="852" alt="image" src="https://github.com/user-attachments/assets/4fe92ea0-4578-40b0-a78e-bc8fca5cda05" />

<br>

<img width="488" height="857" alt="image" src="https://github.com/user-attachments/assets/e16517f6-39cf-4308-a3c4-4bb9ad44301c" />

<br>

#### 4.2.1.6. Services Documentation Evidence for Sprint Review

Durante este sprint se completó exitosamente la implementación y documentación de todos los Web Services correspondientes a las historias de usuario planificadas.
Se configuró Swagger UI como herramienta central para la visualización, prueba e inspección de los endpoints, facilitando la validación funcional por parte del equipo.

Se generó documentación detallada por cada endpoint, incluyendo:

- Sintaxis de la ruta

- Parámetros requeridos

- Ejemplo de request

- Ejemplo de response

- Explicación

- Evidencias mediante capturas de Swagger UI
  <br><br>

| Módulo                    | Endpoint                                                                           | Verbo  | Descripción                                             | URL Documentación                                                                                                              |
|---------------------------|------------------------------------------------------------------------------------|--------|---------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| **Patient Reports**       | `/api/v1/patients/{patientId}/mood-states`                                         | GET    | Obtiene el historial de estados de ánimo de un paciente | [https://psymed-backend-new.onrender.com/swagger-ui/index.html](https://psymed-backend-new.onrender.com/swagger-ui/index.html) |
|                           | `/api/v1/patients/{patientId}/mood-states`                                         | POST   | Registra un nuevo estado de ánimo para un paciente      |                                                                                                                                |
|                           | `/api/v1/patients/{patientId}/biological-functions`                                | GET    | Lista funciones biológicas del paciente                 |                                                                                                                                |
|                           | `/api/v1/patients/{patientId}/biological-functions`                                | POST   | Crea un registro de función biológica                   |                                                                                                                                |
| **Professional Profiles** | `/api/v1/professional-profiles`                                                    | POST   | Crea un perfil profesional                              |                                                                                                                                |
|                           | `/api/v1/professional-profiles/{profileId}`                                        | GET    | Obtiene un perfil por ID                                |                                                                                                                                |
|                           | `/api/v1/professional-profiles/account/{accountId}`                                | GET    | Obtiene el perfil asociado a una cuenta                 |                                                                                                                                |
| **Authentication**        | `/api/v1/authentication/sign-up`                                                   | POST   | Registro de usuarios                                    |                                                                                                                                |
|                           | `/api/v1/authentication/sign-in`                                                   | POST   | Autenticación con JWT                                   |                                                                                                                                |
| **Professional Sessions** | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions`             | POST   | Reserva una sesión                                      |                                                                                                                                |
|                           | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}` | PUT    | Actualiza una sesión                                    |                                                                                                                                |
|                           | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}` | DELETE | Elimina una sesión                                      |                                                                                                                                |
|                           | `/api/v1/professionals/{professionalId}/sessions`                                  | GET    | Obtiene sesiones de un profesional                      |                                                                                                                                |
| **Medication**            | `/api/v1/pills`                                                                    | POST   | Crea un medicamento                                     |                                                                                                                                |
|                           | `/api/v1/pills/{pillId}`                                                           | PUT    | Actualiza medicamento                                   |                                                                                                                                |
|                           | `/api/v1/pills/{pillId}`                                                           | DELETE | Elimina medicamento                                     |                                                                                                                                |
|                           | `/api/v1/pills`                                                                    | GET    | Lista medicamentos                                      |                                                                                                                                |
|                           | `/api/v1/pills/patient/{patientId}`                                                | GET    | Lista medicamentos asignados a un paciente              |                                                                                                                                |
| **Patient Profiles**      | `/api/v1/patient-profiles`                                                         | POST   | Crea un perfil de paciente                              |                                                                                                                                |
|                           | `/api/v1/patient-profiles/{profileId}`                                             | GET    | Obtiene perfil                                          |                                                                                                                                |
|                           | `/api/v1/patient-profiles/{profileId}`                                             | PUT    | Actualiza perfil                                        |                                                                                                                                |
|                           | `/api/v1/patient-profiles/{profileId}`                                             | DELETE | Elimina perfil                                          |                                                                                                                                |
|                           | `/api/v1/patient-profiles/professional/{professionalId}`                           | GET    | Perfiles asociados a un psicólogo                       |                                                                                                                                |
|                           | `/api/v1/patient-profiles/account/{accountId}`                                     | GET    | Perfiles asociados a una cuenta                         |                                                                                                                                |
| **Session Tools**         | `/api/v1/sessions/{sessionId}/notes`                                               | POST   | Agrega nota clínica                                     |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/notes`                                               | PUT    | Actualiza nota                                          |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/notes`                                               | GET    | Obtiene nota                                            |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/notes`                                               | DELETE | Elimina nota                                            |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/tasks`                                               | GET    | Lista tareas de sesión                                  |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/tasks`                                               | POST   | Agrega tarea                                            |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/tasks/{taskId}/complete`                             | POST   | Marca tarea completada                                  |                                                                                                                                |
|                           | `/api/v1/sessions/{sessionId}/tasks/{taskId}/incomplete`                           | POST   | Marca tarea como incompleta                             |                                                                                                                                |
| **Patient Sessions**      | `/api/v1/patients/{patientId}/tasks`                                               | GET    | Obtiene tareas asignadas al paciente                    |                                                                                                                                |
|                           | `/api/v1/patients/{patientId}/sessions`                                            | GET    | Lista sesiones del paciente                             |                                                                                                                                |

<br>

- **Ejemplo de Documentación de un Endpoint** <br><br>
  **GET**: /api/v1/patients/{patientId}/mood-states
  <br>
  <br>

- **Acción:** <br>
  Obtiene todos los registros de estados de ánimo del paciente indicado.
  <br><br>

- **Parámetros:**

 | Tipo | Nombre    | Descripción     |
|------|-----------|-----------------|
| Path | patientId | ID del paciente |
<br>

- **Response de ejemplo** <br>
```
{
    "patientId": 12,
    "moodStates": 
    [
        {
            "id": 47,
            "mood": "Happy",
            "date": "2025-01-12T15:20:00"
        }
    ]
}
```

- **Explicación**<br><br>
  El servicio retorna una lista de estados de ánimo previamente registrados. Permite al profesional de la salud mental visualizar la evolución emocional del paciente.
  <br><br>

- **Capturas de Evidencia**<br>

<img width="1600" height="697" alt="image" src="https://github.com/user-attachments/assets/f9503522-650c-4004-bbc0-35e49d5637c4" />

<br>

<img width="1600" height="809" alt="image" src="https://github.com/user-attachments/assets/5696fa85-9fc4-4dab-9040-f6a2b213bb8e" />

<br>

<img width="1600" height="823" alt="image" src="https://github.com/user-attachments/assets/fde88c5b-8219-43ee-bc27-a1edecece882" />

<br>

<img width="1600" height="695" alt="image" src="https://github.com/user-attachments/assets/1b318bac-70b4-4954-ac70-437ce9b074e1" />

<br>

<img width="1600" height="746" alt="image" src="https://github.com/user-attachments/assets/17bd4cfe-7985-423d-acd8-088830472529" />

<br>

<img width="1600" height="282" alt="image" src="https://github.com/user-attachments/assets/2123e219-31ba-4371-bac7-b7cb3cacef4c" />

<br>

- **Repositorio:** https://github.com/Mobile-Dev-upc/psymed-backend-appmoviles
  <br><br>

- **Conclusiones**<br>

  Todos los endpoints previstos fueron implementados, documentados y verificados. Las historias de usuario del Sprint
  fueron completadas satisfactoriamente y validadas mediante la documentación generada en Swagger UI.
  <br>
  <br>

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

Se desplegó el backend usando Render como plataforma de despliegue de aplicaciones en la nube. A continuación, se presentan las evidencias del despliegue exitoso del backend de Psymed.

<img width="1296" height="678" alt="image" src="https://github.com/user-attachments/assets/25187fb1-8087-4388-8ce1-8e422cdf1368" />

<br>

<img width="1319" height="684" alt="image" src="https://github.com/user-attachments/assets/9c577f97-cbb2-4d8e-b9be-5d564e8035c2" />

<br>

Se puede ver el API documentation desde Swagger UI desde la ruta del despliegue como se nota en el link de la barra buscadora.

#### 4.2.1.8. Team Collaboration Insights during Sprint

<img width="898" height="215" alt="image" src="https://github.com/user-attachments/assets/6a3e9dbe-f9df-40e9-9cec-0b0253e7e795" />


### 4.2.2. Sprint 2
#### 4.2.2.1. Sprint Planning 2

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 2</td>
  </tr>
  <tr>
    <th>Sprint Planning Background</th>
    <td>Implementación final de la plataforma PsyMed para profesionales de la salud mental y pacientes.</td>
  </tr>
  <tr>
    <th>Date</th>
    <td>2025-11-28</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>10:00 AM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Reunión virtual vía Discord</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td>Maita Falckenheiner, Romina Guadalupe</td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>Torres Flores, Paolo Alessandro</td>
  </tr>
  <tr>
    <th>Sprint 2 – 2 Review Summary</th>
    <td>Se revisó el entregable pasado, verificando la correcta implementación de las User Stories designadas.</td>
  </tr>
  <tr>
    <th>Sprint 2 – 2 Retrospective Summary</th>
    <td>Se confirma la correcta implementación de User Stories con funcionalidades core y se toma como impulso para añadir las siguientes funcionalidades</td>
  </tr>
  <tr>
    <th>Sprint Goal &amp; User Stories</th>
    <td></td>
  </tr>
  <tr>
    <th>Sprint 2 Goal</th>
    <td>
      <strong>Nuestro enfoque está en</strong> entregar la versión final funcional de la plataforma PsyMed, que permita la conexión entre profesionales de la salud mental y sus pacientes para una gestión eficiente de las terapias.<br>
      <strong>Creemos que esto ofrece</strong> una mejora en la comunicación, el seguimiento de tratamientos y la gestión de citas en un entorno seguro y accesible para profesionales de la salud mental y pacientes.<br>
      <strong>Esto se confirmará cuando</strong> los usuarios puedan registrarse, agendar sesiones y hacer seguimiento de su progreso terapéutico dentro de la plataforma móvil, con funcionamiento estable en los módulos principales.
    </td>
  </tr>
  <tr>
    <th>Sprint 2 - Velocity</th>
    <td>Estimado en 162 Story Points, enfocado en entregar el MVP con funcionalidades de backend, frontend y autenticación.</td>
  </tr>
  <tr>
    <th>Sprint 2 - Story Points</th>
    <td>162 Story Points distribuidos en 40 User Stories, incluyendo registro, inicio de sesión, gestión de pacientes, programación de citas, gestion de medicación y control de estado</td>
  </tr>
</table>

#### 4.2.2.2. Sprint Backlog 2

Se usó Trello para el correcto control de realización de tareas.<br>
Link del trello: https://trello.com/invite/b/692b1e1e3c5cd474cf90539e/ATTIc2d47750f8fbe65b0a2ebbf2a2f708be7C599AD0/sprint-2 <br>

<br>
<br>
<img width="1309" height="626" alt="image" src="https://github.com/user-attachments/assets/ba807531-16e6-4e95-929e-248bc350f6e6" />
<br><br>

<table>
  <tr>
    <th colspan="1">Sprint #</th>
    <td colspan="7">Sprint 2</td>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="5">Work-Item / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status</th>
  </tr>

  <tr>
    <td>US18</td>
    <td>Encontrar información del propósito de la aplicación</td>
    <td>T21</td>
    <td>Implementar sección Hero y Propósito</td>
    <td>Redacción y maquetación del contenido textual claro que explique el valor de la app.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T22</td>
    <td>Implementar Call to Action</td>
    <td>Integrar botones de acción y textos persuasivos para conversión de visitantes.</td>
    <td>2</td>
    <td>Romina Maita</td>
    <td>To-do</td>
  </tr>

  <tr>
    <td>US19</td>
    <td>Visualizar imágenes y gráficos relevantes</td>
    <td>T23</td>
    <td>Diseño e integración de assets visuales</td>
    <td>Selección e implementación de imágenes de alta calidad y gráficos coherentes con la marca.</td>
    <td>4</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US20</td>
    <td>Visualizar tipografía cómoda y estética</td>
    <td>T124</td>
    <td>Definición de estilos y tipografía</td>
    <td>Configurar estilos globales (CSS) para asegurar legibilidad, contraste y jerarquía visual.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US21</td>
    <td>Crear paciente desde la aplicación móvil</td>
    <td>T25</td>
    <td>Crear vista de registro de paciente</td>
    <td>Diseño e implementación de una vista móvil para registrar pacientes.</td>
    <td>6</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T26</td>
    <td>Conectar API de creación de paciente</td>
    <td>Integrar formulario con endpoint POST de creación de paciente.</td>
    <td>8</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T27</td>
    <td>Términos y Condiciones</td>
    <td>Implementar pantalla de términos y checkbox obligatorio antes de finalizar el registro.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>To-do</td>
  </tr>
  <tr>
    <td></td><td></td>
    <td>T28</td>
    <td>Distribución en Firebase</td>
    <td>Configurar proyecto y desplegar el APK/IPA mediante Firebase App Distribution.</td>
    <td>5</td>
    <td>Paolo Torres</td>
    <td>To-do</td>
  </tr>

  <tr>
    <td>US22</td>
    <td>Visualizar lista de pacientes</td>
    <td>T29</td>
    <td>Diseñar listado de pacientes</td>
    <td>Implementar listado con búsqueda y paginación.</td>
    <td>5</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US23</td>
    <td>Editar información del paciente</td>
    <td>T30</td>
    <td>Crear formulario de edición</td>
    <td>Permitir modificar datos personales del paciente.</td>
    <td>6</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US24</td>
    <td>Eliminar paciente</td>
    <td>T31</td>
    <td>Implementar función de eliminación</td>
    <td>Agregar botón y lógica para eliminar paciente con confirmación.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US25</td>
    <td>Crear tarea para un paciente</td>
    <td>T32</td>
    <td>Formulario de creación de tareas</td>
    <td>Crear formulario para asignar tareas al paciente.</td>
    <td>5</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US26</td>
    <td>Visualizar tareas del paciente (profesional)</td>
    <td>T33</td>
    <td>Lista de tareas</td>
    <td>Mostrar tareas asignadas con estados.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US27</td>
    <td>Editar tarea del paciente</td>
    <td>T34</td>
    <td>Editar tarea</td>
    <td>Modificar título, descripción o fecha límite.</td>
    <td>4</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US28</td>
    <td>Eliminar tarea</td>
    <td>T35</td>
    <td>Eliminar tarea</td>
    <td>Implementar acción de eliminación con confirmación.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US29</td>
    <td>Ver tareas asignadas</td>
    <td>T36</td>
    <td>Interfaz de tareas del paciente</td>
    <td>Mostrar lista de tareas pendientes y completadas.</td>
    <td>5</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US30</td>
    <td>Marcar tarea como completada</td>
    <td>T37</td>
    <td>Implementar acción de completado</td>
    <td>Agregar botón de check y actualización del estado.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US31</td>
    <td>Desmarcar tarea completada</td>
    <td>T38</td>
    <td>Desmarcar tarea</td>
    <td>Permitir revertir estado completado.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US32</td>
    <td>Crear cita médica (móvil)</td>
    <td>T39</td>
    <td>Formulario de cita (móvil)</td>
    <td>Crear interfaz para agendar una cita desde el móvil.</td>
    <td>6</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US33</td>
    <td>Ver citas (profesional móvil)</td>
    <td>T40</td>
    <td>Listado de citas</td>
    <td>Mostrar citas programadas con filtro por fecha.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US34</td>
    <td>Editar cita médica</td>
    <td>T41</td>
    <td>Modificar datos de cita</td>
    <td>Permitir cambios en fecha, hora o duración de la cita.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US35</td>
    <td>Eliminar cita (móvil)</td>
    <td>T42</td>
    <td>Eliminar cita</td>
    <td>Implementar acción de borrado con confirmación.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US36</td>
    <td>Registrar medicamento del paciente (móvil)</td>
    <td>T43</td>
    <td>Formulario de medicamentos</td>
    <td>Registrar medicamentos asignados desde la app móvil.</td>
    <td>5</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US37</td>
    <td>Ver medicamentos del paciente (profesional)</td>
    <td>T44</td>
    <td>Vista de medicamentos</td>
    <td>Mostrar lista de medicamentos recetados por paciente.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US38</td>
    <td>Editar medicamento del paciente</td>
    <td>T45</td>
    <td>Editar medicamento</td>
    <td>Modificar dosis, frecuencia o motivo.</td>
    <td>3</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US39</td>
    <td>Eliminar medicamento del paciente</td>
    <td>T46</td>
    <td>Eliminar medicamento</td>
    <td>Permitir eliminar medicamento con confirmación.</td>
    <td>3</td>
    <td>Romina Maita</td>
    <td>Done</td>
  </tr>

  <tr>
    <td>US40</td>
    <td>Ver medicamentos asignados (paciente)</td>
    <td>T47</td>
    <td>Vista de medicamentos (paciente)</td>
    <td>Listado simple de medicamentos para el paciente.</td>
    <td>4</td>
    <td>Paolo Torres</td>
    <td>Done</td>
  </tr>
</table>

#### 4.2.2.3. Development Evidence for Sprint Review


#### 4.2.2.4. Testing Suite Evidence for Sprint Review

En esta sección se detallarán los user stories implementadas en el presente sprint con sus respectivos tests de aceptación (Gherkin).

### US18
Feature: Visualización del propósito de la aplicación en la Landing Page  
Como visitante de la Landing Page<br>
Quiero entender claramente el propósito de la aplicación<br>
Para saber cómo puede ayudarme.<br>

Escenario: Propósito visible<br>
Dado que el visitante accede a la página principal<br>
Cuando el sistema carga el contenido<br>
Entonces debe mostrar información clara y concisa sobre el propósito de la aplicación<br><br>

---

### US19
Feature: Visualización de imágenes y gráficos relevantes en la Landing Page  
Como visitante de la Landing Page<br>
Quiero ver imágenes y gráficos claros y relevantes<br>
Para complementar la información y aumentar mi interés en la aplicación.<br>

Escenario: Imágenes relevantes<br>
Dado que el visitante navega por la página<br>
Cuando el sistema presenta contenido visual<br>
Entonces las imágenes deben ser de alta calidad y coherentes con el mensaje del sitio<br>

Escenario: Gráficos informativos<br>
Dado que el visitante visualiza secciones con gráficos<br>
Cuando el sistema muestra estos elementos<br>
Entonces deben facilitar la comprensión del contenido textual<br><br>

---

### US20
Feature: Visualización de tipografía cómoda y agradable estéticamente  
Como visitante de la Landing Page<br>
Quiero que la tipografía sea legible y visualmente coherente<br>
Para facilitar la lectura y mantener una experiencia estética agradable.<br>

Escenario: Legibilidad de la tipografía<br>
Dado que el visitante accede a la Landing Page<br>
Cuando el sistema muestra el contenido textual<br>
Entonces debe utilizar una tipografía clara, con tamaño adecuado y contraste suficiente para facilitar la lectura<br>

Escenario: Consistencia tipográfica<br>
Dado que el visitante navega entre diferentes secciones de la página<br>
Cuando el sistema renderiza los textos<br>
Entonces debe mantener coherencia visual en los estilos tipográficos (fuente, tamaño y color)<br><br>

--- 
### US21

Feature: Creación de paciente en aplicación móvil
Como profesional de la salud mental<br>
Quiero crear un paciente desde la aplicación móvil<br>
Para registrarlo rápidamente y gestionarlo desde la plataforma.<br>

Escenario: Creación exitosa<br>
Dado que el profesional proporciona todos los datos requeridos del paciente<br>
Cuando el sistema valida la información<br>
Entonces debe crear el registro del paciente<br>
Y asociarlo al perfil del profesional<br>

Escenario: Datos incompletos<br>
Dado que el profesional deja algún campo requerido vacío<br>
Cuando el sistema valida la información<br>
Entonces debe impedir la creación del paciente<br>
Y notificar los campos faltantes<br>

Escenario: Paciente duplicado<br>
Dado que el profesional intenta registrar un paciente ya existente<br>
Cuando el sistema valida la información<br>
Entonces debe impedir la creación<br>
Y mostrar un mensaje indicando que ya existe un paciente con esos datos<br><br>
--- 
### US22

Feature: Visualización de lista de pacientes
Como profesional de la salud mental<br>
Quiero visualizar la lista de mis pacientes<br>
Para acceder rápidamente a su información y estado actual.<br>

Escenario: Lista disponible<br>
Dado que existen pacientes registrados<br>
Cuando el sistema recupera la información<br>
Entonces debe mostrar la lista de pacientes con nombre, ID y estado general<br>

Escenario: Lista vacía<br>
Dado que no existen pacientes asignados<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje indicando que no hay pacientes registrados<br><br>
--- 
### US23

Feature: Edición de información del paciente
Como profesional<br>
Quiero editar la información del paciente<br>
Para actualizar sus datos cuando sea necesario.<br>

Escenario: Edición exitosa<br>
Dado que el profesional actualiza uno o más campos<br>
Cuando el sistema valida los datos<br>
Entonces debe aplicar los cambios y guardar la información<br>

Escenario: Datos inválidos<br>
Dado que algún dato ingresado no cumple los requisitos<br>
Cuando el sistema valida la información<br>
Entonces debe impedir la actualización<br>
Y notificar los campos incorrectos<br><br>
--- 
### US24

Feature: Eliminación de paciente
Como profesional<br>
Quiero eliminar un paciente de mi lista<br>
Para mantener una gestión organizada y actualizada.<br>

Escenario: Eliminación exitosa<br>
Dado que el profesional confirma la eliminación<br>
Cuando el sistema procesa la solicitud<br>
Entonces debe borrar el registro del paciente<br>
Y retirarlo de la lista del profesional<br>

Escenario: Cancelación de eliminación<br>
Dado que el profesional inicia la eliminación<br>
Cuando decide cancelar<br>
Entonces el sistema debe mantener el registro intacto<br><br>
--- 
### US25

Feature: Creación de tareas para un paciente
Como profesional<br>
Quiero crear tareas para un paciente<br>
Para asignarle actividades terapéuticas que apoyen su progreso.<br>

Escenario: Creación exitosa<br>
Dado que el profesional define nombre, descripción y fecha límite<br>
Cuando el sistema valida la información<br>
Entonces debe crear la tarea y asociarla al paciente<br>

Escenario: Información incompleta<br>
Dado que falta algún dato requerido<br>
Cuando el sistema valida la información<br>
Entonces debe impedir la creación<br>
Y mostrar los campos faltantes<br><br>
--- 
### US26

Feature: Visualización de tareas del paciente (profesional)
Como profesional<br>
Quiero ver las tareas asignadas a cada paciente<br>
Para monitorear su avance terapéutico.<br>

Escenario: Tareas disponibles<br>
Dado que existen tareas registradas para el paciente<br>
Cuando el sistema recupera la información<br>
Entonces debe mostrar la lista con estado, nombre y fecha límite<br>

Escenario: Sin tareas<br>
Dado que el paciente no tiene tareas asignadas<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje indicando que no hay tareas disponibles<br><br>
--- 
### US27

Feature: Edición de tarea asignada
Como profesional<br>
Quiero editar una tarea asignada<br>
Para modificar su contenido o fecha cuando sea necesario.<br>

Escenario: Edición exitosa<br>
Dado que el profesional actualiza uno o más campos<br>
Cuando el sistema valida la información<br>
Entonces debe guardar los cambios en la tarea<br>

Escenario: Datos inválidos<br>
Dado que el profesional ingresa un dato incorrecto<br>
Cuando el sistema valida<br>
Entonces debe rechazar la edición<br>
Y mostrar el error<br><br>
--- 
### US28

Feature: Eliminación de tarea
Como profesional<br>
Quiero eliminar una tarea asignada al paciente<br>
Para retirar actividades que ya no son necesarias.<br>

Escenario: Eliminación exitosa<br>
Dado que el profesional confirma la eliminación<br>
Cuando el sistema procesa la solicitud<br>
Entonces debe borrar la tarea del registro<br>

Escenario: Cancelación de eliminación<br>
Dado que el profesional inicia la eliminación<br>
Cuando decide cancelarla<br>
Entonces el sistema debe mantener la tarea activa<br><br>
--- 
### US29

Feature: Visualización de tareas asignadas (paciente)
Como paciente<br>
Quiero ver las tareas que me asignó mi profesional<br>
Para realizar mis actividades terapéuticas.<br>

Escenario: Tareas disponibles<br>
Dado que existen tareas asignadas<br>
Cuando el sistema consulta la información<br>
Entonces debe mostrar la lista con detalles y fecha límite<br>

Escenario: Sin tareas<br>
Dado que no existen tareas registradas<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje indicando que no hay tareas disponibles<br><br>
--- 
### US30

Feature: Marcado de tarea completada
Como paciente<br>
Quiero marcar una tarea como completada<br>
Para llevar registro de mi progreso.<br>

Escenario: Marcado exitoso<br>
Dado que la tarea está pendiente<br>
Cuando el paciente la marca como completada<br>
Entonces el sistema debe actualizar su estado<br>

Escenario: Tarea ya completada<br>
Dado que la tarea ya está marcada como completada<br>
Cuando el paciente intenta completarla de nuevo<br>
Entonces el sistema debe impedir la acción<br>
Y notificar que ya está completada<br><br>
---
### US31

Feature: Desmarcar tarea completada
Como paciente<br>
Quiero desmarcar una tarea completada<br>
Para corregir errores o cambios en mi progreso.<br>

Escenario: Desmarcado exitoso<br>
Dado que la tarea está completada<br>
Cuando el paciente solicita revertir el estado<br>
Entonces el sistema debe marcarla como pendiente nuevamente<br>

Escenario: Tarea pendiente<br>
Dado que la tarea no está completada<br>
Cuando el paciente intenta desmarcarla
Entonces el sistema debe notificar que no es posible revertir el estado<br><br>
---
### US32

Feature: Creación de cita médica en móvil
Como profesional<br>
Quiero crear una cita desde la app móvil<br>
Para gestionar sesiones sin necesidad de la web.<br>

Escenario: Creación exitosa<br>
Dado que se ingresan fecha, hora, duración y paciente<br>
Cuando el sistema valida los datos<br>
Entonces debe crear la cita y asociarla al paciente<br>

Escenario: Datos incompletos<br>
Dado que falta algún campo obligatorio<br>
Cuando el sistema valida<br>
Entonces debe rechazar la creación<br>
Y mostrar los campos faltantes<br><br>
---
### US33

Feature: Visualización de citas médicas en móvil (profesional)
Como profesional<br>
Quiero ver mis citas desde la aplicación móvil<br>
Para organizar mejor mi agenda diaria.<br>

Escenario: Visualización exitosa<br>
Dado que existen citas registradas<br>
Cuando el sistema recupera la información<br>
Entonces debe mostrar la lista con fecha, hora y paciente<br>

Escenario: Sin citas
Dado que no existen citas programadas<br>
Cuando el sistema consulta<br>
Entonces debe indicar que no hay citas próximas<br><br>
---
### US34

Feature: Edición de cita médica
Como profesional<br>
Quiero editar una cita médica<br>
Para corregir o modificar detalles de la sesión.<br>

Escenario: Edición exitosa<br>
Dado que el profesional actualiza fecha, hora o duración<br>
Cuando el sistema valida la información<br>
Entonces debe guardar los cambios<br>

Escenario: Datos inválidos<br>
Dado que la nueva información no es válida<br>
Cuando el sistema valida
Entonces debe rechazar la actualización<br>
Y notificar el error<br><br>
---

### US35

Feature: Eliminación de cita médica
Como profesional<br>
Quiero eliminar una cita médica
Para retirar sesiones canceladas.<br>

Escenario: Eliminación exitosa<br>
Dado que el profesional confirma la acción<br>
Cuando el sistema procesa la solicitud<br>
Entonces debe borrar la cita del registro<br>

Escenario: Cancelación de eliminación<br>
Dado que el profesional inicia la acción<br>
Cuando decide cancelarla<br>
Entonces el sistema debe mantener la cita intacta<br><br>

---
### US36

Feature: Registro de medicamento del paciente en móvil
Como profesional<br>
Quiero registrar medicamentos desde la app móvil<br>
Para actualizar rápidamente el tratamiento del paciente.<br>

Escenario: Registro exitoso<br>
Dado que el profesional ingresa motivo, frecuencia e intervalo<br>
Cuando el sistema valida la información<br>
Entonces debe registrar el medicamento<br>
Y asociarlo al paciente<br>

Escenario: Datos incompletos<br>
Dado que falta información requerida<br>
Cuando el sistema valida
Entonces debe impedir el registro<br>
Y mostrar los campos faltantes<br><br>
---

### US37

Feature: Visualización de medicamentos del paciente (profesional)
Como profesional<br>
Quiero ver los medicamentos asignados al paciente<br>
Para revisar su tratamiento farmacológico.<br>

Escenario: Visualización exitosa<br>
Dado que existen medicamentos registrados<br>
Cuando el sistema consulta la información
Entonces debe mostrarlos con sus detalles<br>

Escenario: Sin medicamentos<br>
Dado que no existen medicamentos asignados<br>
Cuando el sistema realiza la consulta<br>
Entonces debe mostrar un mensaje indicando que no hay medicamentos disponibles<br><br>
---

### US38

Feature: Edición de medicamento del paciente
Como profesional<br>
Quiero editar un medicamento del paciente
Para actualizar su tratamiento farmacológico.<br>

Escenario: Edición exitosa<br>
Dado que el profesional actualiza uno o más campos
Cuando el sistema valida los datos<br>
Entonces debe aplicar los cambios<br>

Escenario: Datos inválidos<br>
Dado que la información ingresada no es válida
Cuando el sistema valida<br>
Entonces debe impedir la edición
Y notificar los errores<br><br>
---

### US39

Feature: Eliminación de medicamento del paciente
Como profesional<br>
Quiero eliminar un medicamento del paciente<br>
Para retirar tratamientos que ya no corresponden a su plan terapéutico.<br>

Escenario: Eliminación confirmada<br>
Dado que el profesional solicita eliminar un medicamento<br>
Cuando confirma la acción<br>
Entonces el sistema debe borrar el registro de forma definitiva<br>

Escenario: Cancelación<br>
Dado que el profesional inicia la acción de eliminar un medicamento<br>
Cuando decide cancelarla<br>
Entonces el sistema debe conservar el medicamento sin cambios<br><br>

---
### US40

Feature: Visualización de medicamentos asignados (paciente)
Como paciente<br>
Quiero ver los medicamentos asignados por mi profesional
Para cumplir correctamente con mi tratamiento.<br>

Escenario: Medicamentos disponibles<br>
Dado que existen medicamentos asignados
Cuando el sistema recupera la información<br>
Entonces debe mostrarlos con nombre, motivo y frecuencia<br>

Escenario: Sin medicamentos
Dado que no existen medicamentos registrados<br>
Cuando el sistema consulta
Entonces debe indicar que no hay medicamentos disponibles<br><br>

#### 4.2.2.5. Execution Evidence for Sprint Review

En este punto se demuestra las capturas de ejecución de la version distribuida desde Firebase

![WhatsApp Image 2025-11-29 at 1 35 04 AM](https://github.com/user-attachments/assets/0e58a78c-e2c1-41f6-9ee5-f4080879c5f8)


![WhatsApp Image 2025-11-29 at 1 41 10 AM](https://github.com/user-attachments/assets/cc8dc12c-e38e-4576-b843-0ed37fb8c537)


![WhatsApp Image 2025-11-29 at 1 41 10 AM (1)](https://github.com/user-attachments/assets/22b7f951-b982-4872-aa0f-8dcf43f490fc)


![WhatsApp Image 2025-11-29 at 1 41 10 AM (2)](https://github.com/user-attachments/assets/28925d25-4fcd-4b4c-9182-2d1bb08c6443)

![WhatsApp Image 2025-11-29 at 1 41 10 AM (3)](https://github.com/user-attachments/assets/9823b866-1544-407b-b28e-08eecc973257)

![WhatsApp Image 2025-11-29 at 1 41 11 AM](https://github.com/user-attachments/assets/80f385b6-485a-45b7-af7f-a3e2bd714d5f)

![WhatsApp Image 2025-11-29 at 1 41 11 AM (1)](https://github.com/user-attachments/assets/568da408-2f8f-4d1e-8985-fcbde1f5037e)

![WhatsApp Image 2025-11-29 at 1 41 11 AM (2)](https://github.com/user-attachments/assets/a1015b15-d813-4fd6-9cce-570e5bba54f4)

![WhatsApp Image 2025-11-29 at 1 41 11 AM (3)](https://github.com/user-attachments/assets/d0c27751-10d8-4e95-be17-082e9b61c015)

![WhatsApp Image 2025-11-29 at 1 41 12 AM](https://github.com/user-attachments/assets/245301ca-cba1-4cd5-bfc0-560b2e64c953)

![WhatsApp Image 2025-11-29 at 1 41 12 AM (1)](https://github.com/user-attachments/assets/0901c803-b0b9-4dba-863e-3e7cac7518c3)

![WhatsApp Image 2025-11-29 at 1 41 12 AM (2)](https://github.com/user-attachments/assets/7a2e7f28-5eaf-46f6-a9cf-e5bedac1f0c1)

![WhatsApp Image 2025-11-29 at 1 41 12 AM (3)](https://github.com/user-attachments/assets/a15528dd-7dff-4b69-8899-a1fe277ba2a4)

![WhatsApp Image 2025-11-29 at 1 41 13 AM](https://github.com/user-attachments/assets/7e18f3d7-0df7-4562-9229-db2e5bb62f1a)

#### 4.2.2.6. Services Documentation Evidence for Sprint Review

- **Capturas de Evidencia**<br>

<img width="1600" height="697" alt="image" src="https://github.com/user-attachments/assets/f9503522-650c-4004-bbc0-35e49d5637c4" />

<br>

<img width="1600" height="809" alt="image" src="https://github.com/user-attachments/assets/5696fa85-9fc4-4dab-9040-f6a2b213bb8e" />

<br>

<img width="1600" height="823" alt="image" src="https://github.com/user-attachments/assets/fde88c5b-8219-43ee-bc27-a1edecece882" />

<br>

<img width="1600" height="695" alt="image" src="https://github.com/user-attachments/assets/1b318bac-70b4-4954-ac70-437ce9b074e1" />

<br>

<img width="1600" height="746" alt="image" src="https://github.com/user-attachments/assets/17bd4cfe-7985-423d-acd8-088830472529" />

<br>

<img width="1600" height="282" alt="image" src="https://github.com/user-attachments/assets/2123e219-31ba-4371-bac7-b7cb3cacef4c" />

<br>

#### 4.2.2.7. Software Deployment Evidence for Sprint Review

Nuestro backend está desplegado en Render y nuestra base de datos en Neon Database, a continuación captura de la evidencia

![WhatsApp Image 2025-11-29 at 12 11 10 PM](https://github.com/user-attachments/assets/760f24d8-efe7-47c4-8522-b46e23989347)

![WhatsApp Image 2025-11-29 at 12 12 22 PM](https://github.com/user-attachments/assets/347139f6-e276-4992-a658-cefdad9b29f9)


Hemos Utilizado Firebase App Distribution para poder compartir con nuestros testers nuestra primera versión, a continuación captura de la evidencia

![WhatsApp Image 2025-11-29 at 12 15 06 PM](https://github.com/user-attachments/assets/9985f1ca-1835-40eb-a487-3d57a9ad10ca)

![9c5fb7e2-c68c-48a4-9632-670cb1d7f765](https://github.com/user-attachments/assets/4fd4050d-94ac-4516-8b98-6db5422e2081)


#### 4.2.2.8. Team Collaboration Insights during Sprint

En esta sección se demuestra la colaboración en equipo que tuvimos para nuestro segundo sprint

![WhatsApp Image 2025-11-29 at 12 58 27 PM](https://github.com/user-attachments/assets/c23e4de9-f2bb-455f-bd1f-1c074e46c18a)

## 4.3. Validation Interviews
### 4.3.1. Diseño de Entrevistas

Preguntas para segmento profesionales:

- ¿Qué tan fácil te resultó entender cómo crear un nuevo usuario o iniciar sesión?

- ¿Te pareció intuitivo el proceso para registrar un paciente o ingresar medicamentos/citas?

- ¿Hubo algún momento en el video en el que te sentiste confundido o perdiste el hilo de lo que pasaba?

- Si tuvieras que hacer tú mismo las acciones que mostró el video (crear usuario, registrar medicamento, etc.), ¿crees que podrías hacerlo sin ayuda?

- ¿Qué mejorarías para que la app sea más fácil de usar?

- ¿Te resultó clara la parte del registro del estado emocional y biológico?

- ¿Crees que esta app te ayudaría a estar más consciente del estado del paciente?

- ¿Cómo te sentiste al ver la app? (por ejemplo: tranquilo, confundido, interesado, indiferente)

- ¿Sientes que la app respeta la privacidad y la sensibilidad de la información de salud mental?

Preguntas para segmento pacientes:

- ¿Qué tan fácil te resultó entender cómo crear un nuevo usuario o iniciar sesión?

- ¿Te pareció intuitivo el proceso para registrar un paciente o ingresar medicamentos/citas?

- ¿Hubo algún momento en el video en el que te sentiste confundido o perdiste el hilo de lo que pasaba?

- Si tuvieras que hacer tú mismo las acciones que mostró el video (crear usuario, registrar medicamento, etc.), ¿crees que podrías hacerlo sin ayuda?

- ¿Qué mejorarías para que la app sea más fácil de usar?

- ¿Te resultó clara la parte del registro del estado emocional y biológico?

- ¿Te gustaría recibir recordatorios de tus citas o medicamentos?

- ¿Te sentirías cómodo registrando tu estado de ánimo todos los días?

- ¿Crees que esta app te ayudaría a estar más consciente de tu salud mental?

- ¿Cómo te sentiste al ver la app? (por ejemplo: tranquilo, confundido, interesado, indiferente)

- ¿Sientes que la app respeta la privacidad y la sensibilidad de la información de salud mental?

- ¿Qué tan confiable te parece el sistema para manejar información médica?

### 4.3.2. Registro de Entrevistas
Entrevistas a segmento profesionales:

- Entrevista 1:

![WhatsApp Image 2025-11-06 at 11 39 00 PM](https://github.com/user-attachments/assets/d236f0f9-7542-455b-a9d0-4742c60feb45)


| Nombre               | Karina                      |
|----------------------|-----------------------------|
| Apellido             | Ramirez                     |
| Edad                 | 51 años                     |
| Distrito             | La Molina                   |
| URL                  | https://acortar.link/W1pxX8 |
| Inicio de entrevista | 00:01                       |
| Fin de entrevista    | 20:35                       |

Resumen de entrevista:

La psicoterapeuta Karina Ramírez Sedano brindó una evaluación detallada de la plataforma PSYMED, destinada a facilitar la gestión de pacientes, sesiones, tareas y seguimiento emocional y físico por parte de psicólogos y psiquiatras.

Desde el inicio, la entrevistada consideró que la interfaz de registro de pacientes es clara y funcional, ya que permite recopilar los datos básicos necesarios para abrir una historia clínica y comenzar el seguimiento del tratamiento. Destacó que el sistema facilita la organización inicial y constituye un filtro adecuado para el trabajo terapéutico.

Respecto al módulo de citas, indicó que la aplicación resulta sencilla de usar y adaptable a las dinámicas de sesión, que suelen durar entre 45 y 50 minutos. Apreció que la agenda pueda registrar sesiones semanales y que el sistema no permita programar fechas anteriores, lo cual refuerza la coherencia del registro.

En cuanto al seguimiento emocional del paciente, valoró la idea de que el usuario registre su estado diario, aunque advirtió que en casos clínicos como la depresión los cambios podrían no reflejar una mejora inmediata. Señaló que esta función debe servir como apoyo complementario, más que como indicador clínico determinante.

Sobre la vista de datos físicos y medicamentos, consideró que es útil para psiquiatras y que los psicólogos podrían beneficiarse de tener acceso limitado a esta información. No obstante, enfatizó la importancia de garantizar la privacidad, proponiendo que la aplicación incluya un espacio exclusivo para el profesional, donde se guarden notas confidenciales, protegidas mediante cifrado o acceso restringido.

En términos de usabilidad, Karina Ramírez afirmó que la plataforma es intuitiva y visualmente clara. Recomendó incorporar tonos pastel y colores suaves, que transmitan tranquilidad y cercanía. También sugirió que las sesiones o tareas aparezcan estructuradas como “libretos digitales”, simulando los cuadernos que usan los pacientes en terapia presencial.

Sobre la versión móvil, opinó que es conveniente contar con ambas opciones (web y móvil), ya que los psicoterapeutas suelen trabajar virtualmente con computadoras, mientras que los pacientes usan más el teléfono.

Finalmente, consideró que la plataforma favorece la conciencia emocional del paciente y facilita el seguimiento terapéutico. Recalcó la necesidad de mantener altos estándares de seguridad y confidencialidad, especialmente en la información compartida entre distintos profesionales de salud. Concluyó destacando que el proyecto es innovador, funcional y de gran utilidad para el ámbito psicológico y psiquiátrico.

- Entrevista 2:

![WhatsApp Image 2025-11-08 at 12 04 54 PM](https://github.com/user-attachments/assets/b29e3748-54f2-481f-bfca-aa277d20838a)


| Nombre               | Hortensia                   |
|----------------------|-----------------------------|
| Apellido             | Piedra Cáceres              |
| Edad                 | 36 años                     |
| Distrito             | Arequipa                    |
| URL                  | https://acortar.link/xlvlUg |
| Inicio de entrevista | 00:01                       |
| Fin de entrevista    | 17:05                       |

Resumen de entrevista:

La psicóloga clínica Hortensia Piedra Cáceres, residente en Arequipa, brindó una evaluación detallada de la plataforma Psymed, un sistema web y móvil diseñado para optimizar la gestión de pacientes, citas y seguimiento emocional y físico en el ámbito psicológico y psiquiátrico.

Desde el inicio, la entrevistada consideró que el proceso de inicio de sesión es claro y sencillo, permitiendo distinguir adecuadamente entre el acceso de pacientes y profesionales. En cuanto al registro de pacientes, sugirió incluir información adicional como la edad y antecedentes de terapia previa, para enriquecer la historia clínica inicial.

Respecto al módulo de citas, destacó su facilidad de uso y propuso añadir opciones que reflejen distintos tipos de atención, como evaluaciones psicológicas, entregas de informes, orientación vocacional o terapias grupales (DBT). También recomendó incorporar campos para registrar costos, paquetes de sesiones y reprogramaciones, ya que son aspectos frecuentes en la práctica clínica.

Sobre el seguimiento emocional y físico, valoró que el paciente pueda registrar su estado diario, pero sugirió incluir un campo de notas donde exprese la causa o contexto de sus emociones, facilitando el análisis posterior en sesión. Consideró apropiado mantener cierta separación entre la información del psicólogo y la del psiquiatra, por motivos de confidencialidad.

En el ámbito de la versión móvil, la psicóloga afirmó que sería útil para profesionales, especialmente para consultar citas y el progreso de sus pacientes. Recalcó la conveniencia de que los terapeutas puedan acceder también desde el celular, no solo desde la computadora.

En términos de diseño y usabilidad, propuso emplear colores cálidos (melón, beige, café claro) en lugar de tonos fríos o clínicos, con el fin de generar cercanía y evitar una estética hospitalaria. También sugirió incorporar pequeñas imágenes decorativas que aporten calidez visual.

Finalmente, consideró que PsyMed respeta la privacidad del paciente, dado que el registro emocional es parte del proceso terapéutico. Recomendó agregar el motivo de consulta y un sistema para asignar tareas terapéuticas, donde el paciente pueda indicar si comprendió la actividad y cómo se sintió al realizarla.

Concluyó afirmando que la plataforma es intuitiva, funcional y pertinente para el trabajo psicológico, y que con las mejoras propuestas podría convertirse en una herramienta integral para la práctica clínica y el acompañamiento terapéutico.

- Entrevista 3:

![WhatsApp Image 2025-11-09 at 2 11 16 PM](https://github.com/user-attachments/assets/4bbee769-9e23-43ea-b749-1a0a2063e341)

| Nombre               | Valerie                     |
|----------------------|-----------------------------|
| Apellido             | Hikaru Ouchida              |
| Edad                 | 29 años                     |
| Distrito             | Lince                       |
| URL                  | https://acortar.link/LMeRNa |
| Inicio de entrevista | 00:01                       |
| Fin de entrevista    | 09:45                       |

Resumen de entrevista:

Desde el inicio, consideró que el diseño es intuitivo y de fácil uso, destacando la claridad del proceso de inicio de sesión y registro de profesionales. En cuanto al registro de pacientes, recomendó añadir la edad y el motivo de consulta, ya que estos datos permiten contextualizar los casos y facilitan la organización de la información clínica.

Respecto al módulo de citas, coincidió con la necesidad de incluir campos adicionales, como el tipo de sesión (terapia o seguimiento), frecuencia semanal o mensual, número de sesiones y reprogramaciones, lo cual permitiría un control más preciso del tratamiento.

En relación con el seguimiento emocional y físico, consideró muy útil que los pacientes puedan registrar su estado de ánimo diario, aunque subrayó que este módulo requiere compromiso por parte del paciente. Sugirió incorporar un espacio para notas, donde puedan expresar el contexto o las razones detrás de su estado emocional, favoreciendo así el análisis terapéutico.

Sobre la versión móvil, indicó que, por su estilo de trabajo, le resulta más práctico el acceso desde computadora o laptop, ya que facilita la redacción y el registro de información profesional, aunque valoró la utilidad de la aplicación móvil para pacientes.

En cuanto al diseño visual, opinó que la interfaz transmite seriedad, pero podría resultar demasiado médica. Propuso añadir ilustraciones minimalistas relacionadas con la salud mental y usar colores más cálidos o pasteles (como crema o café claro), con el fin de generar un entorno más acogedor y menos clínico.

En conclusión, la psicóloga consideró que la plataforma Psymed es funcional, clara y pertinente para la práctica clínica, y que con pequeñas mejoras en la presentación visual y la ampliación de ciertos campos, podría convertirse en una herramienta integral para el seguimiento terapéutico y la organización profesional.


### 4.3.3. Evaluaciones según heurísticas
#### **UX Heuristics & Principles Evaluation**
#### **Usability – Inclusive Design – Information Architecture**

**CARRERA:** Ingeniería de Software  <br>
**CURSO:** Aplicaciones para dispositivos móviles  <br>
**NRC:** 1827 <br>
**PROFESORES:** David Gerardo Quevedo Velasco<br>
**AUDITOR:** Paolo Torres <br>
**CLIENTE(S):** Grupo Go7U<br>

---

#### **SITE o APP A EVALUAR:**
**Psymed** – Aplicación para profesionales de la salud mental y pacientes que facilita la gestión de procesos interactivos entre ambos.

---

#### **TAREAS A EVALUAR:**
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Registro de paciente
2. Registro de profesional de la salud mental
3. Inicio de sesión y acceso al panel principal
4. Agendar una cita terapéutica
5. Enviar mensaje al terapeuta o paciente
6. Registrar notas o avances de sesión
7. Visualizar historial clínico
8. Cancelar o reprogramar una cita

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Generar reportes estadísticos de sesiones
2. Configurar recordatorios automáticos por correo o SMS
3. Integrar pagos en línea
4. Exportar historial clínico a otros formatos
5. Funcionalidades de supervisión entre terapeutas

---

#### **ESCALA DE SEVERIDAD:**

| Nivel | Descripción                                                                                                                                       |
|-------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No requiere corrección inmediata.            |
| **2** | Problema menor: ocurre con cierta frecuencia o genera confusión leve. Se recomienda corregir en una futura iteración.                             |
| **3** | Problema mayor: ocurre frecuentemente o impide al usuario completar una tarea sin ayuda. Debe corregirse con prioridad alta.                      |
| **4** | Problema muy grave: impide completamente el uso de la herramienta o compromete la experiencia del usuario. Debe corregirse antes del lanzamiento. |

---

#### **TABLA RESUMEN:**

| # | Problema                                                                                       | Escala de severidad | Heurística / Principio violado                |
|---|------------------------------------------------------------------------------------------------|---------------------|-----------------------------------------------|
| 1 | No existe un botón claro para regresar al panel principal desde la vista de historial clínico. | 3                   | Usability: Libertad y control del usuario     |
| 2 | Los íconos de funciones no tienen etiquetas textuales para lectores de pantalla.               | 2                   | Inclusive Design: Experiencias comparables    |
| 3 | La jerarquía visual de la sección de mensajes no resalta las conversaciones activas.           | 2                   | Information Architecture: Is it usable?       |
| 4 | Al registrar una cita, no se muestra retroalimentación inmediata tras confirmar.               | 3                   | Usability: Visibilidad del estado del sistema |
| 5 | El botón “Cancelar cita” está demasiado próximo al botón “Guardar cambios”.                    | 3                   | Usability: Prevención de errores              |

---

#### **DESCRIPCIÓN DE PROBLEMAS:**

#### **PROBLEMA #1: No existe un botón claro para regresar al panel principal desde la vista de historial clínico**
**Severidad:** 3  
**Heurística violada:** Usabilidad – Libertad y control del usuario  
**Problema:**  
Cuando el usuario revisa el historial clínico, no dispone de una opción visible que le permita regresar fácilmente al panel principal. Esto genera confusión y obliga a usar el navegador para retroceder, afectando la fluidez de la navegación.

**Recomendación:**  
Incorporar un botón “Volver al panel” o un ícono de navegación persistente en la interfaz, que permita retornar fácilmente sin perder el contexto actual.

---

#### **PROBLEMA #2: Los íconos de funciones no tienen etiquetas textuales para lectores de pantalla**
**Severidad:** 2  
**Heurística violada:** Inclusive Design – Proporciona experiencias comparables  
**Problema:**  
Algunos íconos, como el de mensajes o configuración, carecen de atributos `aria-label` o texto alternativo, lo que dificulta la interacción para usuarios con discapacidad visual.

**Recomendación:**  
Agregar etiquetas accesibles (`aria-label` o `alt`) a todos los elementos interactivos para garantizar compatibilidad con tecnologías de asistencia.

---

#### **PROBLEMA #3: La jerarquía visual de la sección de mensajes no resalta las conversaciones activas**
**Severidad:** 2  
**Heurística violada:** Information Architecture – Is it usable?  
**Problema:**  
La interfaz de mensajes no diferencia visualmente las conversaciones activas de las archivadas, dificultando la búsqueda y seguimiento de pacientes.

**Recomendación:**  
Aplicar un esquema visual claro (colores, tipografía o etiquetas) que distinga estados de conversación y facilite la navegación.

---

#### **PROBLEMA #4: Al registrar una cita, no se muestra retroalimentación inmediata tras confirmar**
**Severidad:** 3  
**Heurística violada:** Usabilidad – Visibilidad del estado del sistema  
**Problema:**  
Luego de presionar “Confirmar cita”, el sistema no muestra un mensaje o indicador que confirme la acción, generando incertidumbre sobre si la cita fue registrada correctamente.

**Recomendación:**  
Incluir una notificación visual o sonora (por ejemplo, un mensaje de éxito o un ícono animado) que confirme la creación de la cita.

---

#### **PROBLEMA #5: El botón “Cancelar cita” está demasiado próximo al botón “Guardar cambios”**
**Severidad:** 3  
**Heurística violada:** Usabilidad – Prevención de errores  
**Problema:**  
La cercanía entre ambos botones aumenta el riesgo de cancelación accidental, especialmente en pantallas táctiles o móviles.

**Recomendación:**  
Separar ambos botones con espacio suficiente o colores contrastantes para minimizar errores involuntarios.

---


# Conclusiones
### Conclusiones y recomendaciones.

**Conclusiones:**<br>

- PsyMed cumple su objetivo central al proporcionar una plataforma que facilita el acompañamiento terapéutico continuo, integrando seguimiento clínico, comunicación y gestión de citas para fortalecer el vínculo entre pacientes y profesionales de la salud mental dentro de un entorno seguro y accesible.
<br><br>

- La solución técnica de PsyMed destaca por su arquitectura multiplataforma, que permite ofrecer una experiencia móvil unificada en distintos dispositivos. La integración entre backend y aplicación móvil se desarrolla de manera consistente mediante servicios REST bien definidos, asegurando sincronización en tiempo real, fácil mantenibilidad y capacidad de expansión futura.
<br><br>

- PsyMed se consolida como una herramienta estratégica para modernizar los procesos de atención en salud mental, mejorando la eficiencia operativa de los profesionales y aumentando la adherencia del paciente, lo que la posiciona como una solución digital de alto valor para clínicas, instituciones y consultorios especializados.

**Recomendaciones:**<br>

- Fortalecer la participación del paciente mediante funciones de acompañamiento activo, como recordatorios automáticos, check-ins emocionales y seguimiento guiado, para incrementar la adherencia terapéutica y maximizar el impacto clínico del sistema.
<br><br>

- Optimizar la arquitectura multiplataforma implementando estrategias de rendimiento y sincronización offline-first, que permitan a los usuarios registrar datos incluso sin conexión, garantizando una experiencia fluida y confiable en distintos dispositivos y condiciones de red.
<br><br>

- Establecer una hoja de ruta de escalabilidad que contemple alianzas con instituciones de salud mental, mejora continua del backend y ampliación de módulos clínicos, con el fin de posicionar a PsyMed como una solución integral y competitiva dentro del mercado de herramientas digitales para salud mental.

<br>

### Video App Validation

Link del video: https://goo.su/f259FM3

<br><br>

<img width="1314" height="633" alt="image" src="https://github.com/user-attachments/assets/965b4968-de24-40d3-835d-4a8a4703b185" />

<br>

### Video About the product

**Link del video:** https://n9.cl/tfsu4 

<br>

<br>
<img width="1309" height="560" alt="image" src="https://github.com/user-attachments/assets/f6e65260-d708-40db-a738-0148685b9ad5" />


<br><br>

### Video About the team

Link del video: https://n9.cl/chydo <br> <br>

<img width="1316" height="641" alt="image" src="https://github.com/user-attachments/assets/11dcd906-73cc-4817-af77-bc4e242287c7" />


### Glosario

**Paciente**<br>
Usuario que recibe atención terapéutica y registra su progreso mediante estados de ánimo, funciones biológicas, tareas y seguimiento clínico dentro de la aplicación.

**Profesional de la salud mental**<br>
Especialista (psicólogo, terapeuta, psiquiatra u otro) que administra sesiones, registra notas clínicas, revisa el progreso del paciente y gestiona su tratamiento en la plataforma.

**Estado de ánimo (Mood State)**<br>
Registro emocional que el paciente actualiza periódicamente para permitir un seguimiento longitudinal de su bienestar psicológico.

**Funciones biológicas (Biological Functions)**<br>
Indicadores físicos del paciente como sueño, apetito o energía, utilizados para complementar el análisis clínico y detectar variaciones relevantes en su salud mental.

**Tareas terapéuticas (Session Tasks)**<br>
Actividades asignadas por el profesional que el paciente debe completar entre sesiones, relacionadas al avance de su proceso terapéutico.

**Notas clínicas (Session Notes)** <br>
Anotaciones privadas realizadas por el profesional durante o después de una sesión, que documentan observaciones, avances y decisiones terapéuticas.

**Sesión clínica (Session)**<br>
Encuentro agendado entre profesional y paciente, ya sea presencial o virtual, que se gestiona mediante la aplicación.

**Perfiles de usuario (Patient/Professional Profile)**<br>
Información relevante del paciente o profesional asociada a su rol dentro de la plataforma, incluyendo datos clínicos, personales y de identificación.

**Autenticación (Authentication)**<br>
Proceso de verificación de identidad mediante correo y contraseña, con generación de tokens que permiten el acceso seguro a la plataforma.

**JWT (JSON Web Token)**<br>
Token digital utilizado para mantener sesiones seguras y validar permisos del usuario en las operaciones de la API.

**Backend (API REST)**<br>
Conjunto de servicios web que gestionan la lógica del sistema, operaciones con datos, seguridad y comunicación con la app móvil o web.

**Frontend móvil multiplataforma**<br>
Aplicación móvil desarrollada con tecnologías que permiten desplegarla en distintos sistemas operativos (Android/iOS) con una sola base de código.

**Seguimiento clínico**<br>
Proceso de recopilación continua de datos del paciente, como estados de ánimo, tareas y funciones biológicas, que permiten al profesional evaluar su evolución.

### Bibliografía

- Flutter - Build apps for any screen. (s/f). Flutter.dev. Recuperado el 14 de noviembre de 2025, de https://flutter.dev
<br><br>
- Download Android Studio & app tools. (s/f). Android Developers. Recuperado el 14 de noviembre de 2025, de https://developer.android.com/studio
<br><br>
- API Documentation & Design Tools for Teams. (s/f). Swagger.io. Recuperado el 14 de noviembre de 2025, de https://swagger.io
<br><br>

### Anexos

- Video About the Product: https://n9.cl/tfsu4 <br>

- Video About the Team: https://n9.cl/chydo <br>

- Video Expo TF: https://goo.su/7Y3OZ  <br>

- Video Validation: https://goo.su/f259FM3 <br>
