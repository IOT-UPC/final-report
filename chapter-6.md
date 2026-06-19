# Capítulo VI: Product Implementation, Validation & Deployment
## 6.1. Software Configuration Management.

En este apartado se describe el proceso mediante el cual se organiza, gestiona y controla la configuración del software y los cambios en el desarrollo del proyecto. El objetivo es garantizar que todos los integrantes del equipo trabajen bajo un mismo entorno, utilizando herramientas estandarizadas y metodologías que aseguren la trazabilidad, la calidad y la colaboración continua.

### 6.1.1. Software Development Environment Configuration.

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
   <br>

2. HTML5: Lenguaje de marcado utilizado para estructurar y presentar el contenido de la aplicación web. Servirá como base para la maquetación de la interfaz.

   Ruta de referencia: https://www.w3schools.com/html/html5_syntax.asp
   <br>

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

 <br>

**Software Deployment**
1. Git: Sistema de control de versiones distribuido. Permitirá a los integrantes del equipo llevar un registro detallado de los cambios, gestionar ramas de desarrollo, y facilitar la integración de nuevas funcionalidades sin comprometer la estabilidad del proyecto.

   Ruta de referencia: https://git-scm.com/
   <br>
   <br>
   **Software Documentation and Project Management**
2. GitHub: Plataforma colaborativa en la nube para el alojamiento de repositorios Git. Será el medio oficial para la centralización del código, revisión de contribuciones y gestión de issues, además de permitir la integración con otras herramientas de desarrollo y CI/CD

   Ruta de referencia: https://github.com/

### 6.1.2. Source Code Management.

El proyecto adoptará las convenciones del modelo GitFlow para la gestión del control de versiones, utilizando GitHub como plataforma principal para alojar y organizar el código. GitFlow es un enfoque estructurado que facilita la colaboración en equipo, la integración de cambios y la gestión de múltiples versiones del software. Este modelo asegura que cada etapa de desarrollo esté debidamente aislada, probada y documentada antes de ser integrada en la rama principal.

A continuación, se detalla cómo se implementará este flujo de trabajo, junto con los enlaces a los repositorios donde se centralizan los entregables principales:

**Repositorio de GitHub:**
- Enlace para acceder a la organización en https://github.com/IOT-UPC
- Enlace para acceder al repositorio de la Landing Page https://github.com/Diseno-de-experimentos-Grupo-2/Landing-Page
- Enlace para acceder al repositorio del reporte en https://github.com/IOT-UPC/final-report
- Enlace para acceder al repositorio del Frontend Web https://github.com/IOT-UPC/front


**Flujo de trabajo GitFlow**

El flujo de trabajo se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

![Application Web](https://github.com/user-attachments/assets/df7f574c-1b14-44b8-aa30-de55f0ac4300)


**Estructura de branches (Ramas):**


1. **Master branch (Rama principal):** Contendrá únicamente versiones estables y listas para producción. Los cambios que lleguen aquí deberán haber pasado por pruebas y validaciones en develop y feature branches.

2. **Develop Branch (Rama de Desarrollo):** Funciona como la rama de integración, donde se combinan y prueban las nuevas funcionalidades antes de ser promovidas a master. Garantiza que el código en desarrollo se mantenga operativo y estable.

3. **Feature branch (Ramas de funcionalidad):** Cada nueva característica o mejora se desarrollará en una rama independiente creada a partir de develop. Una vez finalizada y probada, se fusionará nuevamente en develop.

Convención de nombres: feature/nombre-descriptivo.
Ejemplo: feature/bc-medication-management.

### 6.1.3. Source Code Style Guide & Conventions.

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

<div style="page-break-after: always;"></div>

### 6.1.4. Software Deployment Configuration.

### Landing page deployment:
Para el despliegue de la Landing Page se utilizará Vercel, siguiendo los pasos descritos a continuación:

1. Crear una cuenta en Vercel y vincularla con el repositorio de GitHub donde se encuentra el código de la landing page.
2. Iniciar el proceso de despliegue y esperar a que Vercel realice las validaciones y construya la landing page.
3. Una vez completado el despliegue, acceder al enlace generado para visualizar la landing page de PsyMed en producción.

Una vez completado el despliegue, la landing page quedará publicada y accesible públicamente mediante el enlace: https://landingpage-eosin-ten.vercel.app


![Landing Page Deployment](https://github.com/user-attachments/assets/531768d4-d72a-4432-ab16-31c2a740b197)

<div style="page-break-after: always;"></div>

### PsyMed frontend deployment:
Para el despliegue de la aplicación web de PsyMed se empleará Vercel, siguiendo los pasos descritos a continuación:

1. Crear una cuenta en Vercel y vincularla con el repositorio de GitHub donde se encuentra el código del frontend.
2. Configurar el proyecto en Vercel, seleccionando el repositorio correspondiente y definir los comandos de construcción y despliegue según las necesidades del proyecto (por ejemplo, "npm run build" para construir la aplicación).
3. Configurar las variables de entorno necesarias para el correcto funcionamiento de la aplicación.
4. Iniciar el proceso de despliegue y esperar a que Vercel realice las validaciones y construya la aplicación.
5. Una vez completado el despliegue, acceder al enlace generado para visualizar la aplicación web de PsyMed en producción.

Una vez desplegada, la aplicación web de PsyMed estará accesible públicamente mediante el enlace: https://psymed-frontend.vercel.app/
<img width="1296" height="633" alt="image" src="https://github.com/user-attachments/assets/5ec94ea8-e958-4d7f-9c31-819ccf53189a" />


<div style="page-break-after: always;"></div>

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.1. Sprint 1
En el Sprint #1, que comienza el 11/05/2026, nos enfocaremos en realizar el despliegue de la Landing Page y del Frontend Web de PsyMed. El objetivo es garantizar que ambas plataformas se encuentren accesibles públicamente, permitiendo presentar la propuesta de valor del producto y brindar una primera experiencia funcional a los usuarios. Este sprint estará dedicado a la configuración de entornos, integración con repositorios y validación del despliegue en producción mediante Vercel, asegurando la disponibilidad y correcto funcionamiento de las aplicaciones.


#### 6.2.1.1. Sprint Planning 1.



| **Sprint 1**                    | Sprint 1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sprint Planning Background      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Date                            | 11/05/2026                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Time                            | 19:00 - 21:00                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Location                        | Virtual via Discord                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Prepared By                     | Paolo Alessandro Torres Flores, Omar Harold Rivera Ticllacuri                                                                                                                                                                                                                                                                                                                                                                                                                               |
| Attendees (to planning meeting) | Paolo Alessandro Torres Flores, Omar Harold Rivera Ticllacuri, Romina Guadalupe Maita Falckenheiner, Luis Angel Montañez Moreno, Melisa Sulca Silva                                                                                                                                                                                                                                                                                                                                         |
| Sprint Goal & User Stories      |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| Sprint 1 Goal                   | **Our focus is on** deploying the first operational version of the PsyMed Landing Page and Frontend Web Application.<br> **We believe it delivers** public accessibility, project visibility, and a functional environment where users can interact with the platform through the deployed interfaces.<br> **This will be confirmed when** users can successfully access the landing page and frontend application through the production links deployed on Vercel without critical errors. |
| Sprint 1 Velocity               | El equipo ha establecido una capacidad de 12 story points para este sprint, considerando que las actividades estuvieron enfocadas principalmente en el despliegue de la landing page y la configuración inicial del frontend web.                                                                                                                                                                                                                                                                     |
| Sum of Story Points             | 12                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |


<div style="page-break-after: always;"></div>


#### 6.2.1.2. Aspect Leaders and Collaborators.
| Team member (LastName, First Name)    | GitHub UserName | Aspect 1:  Bounded Context Access (L/C) | Aspect 2:  Bounded Context Patient Tracker (L/C) | Aspect 3:  Bounded Context Medication Management (L/C) | Aspect 4:  Bounded Context Treatment (L/C) | Aspect 5: Bounded Context Payment (L/C) | Aspect 6: Bounded Context Appointment and Administration (L/C) |
| ------------------------------------- | --------------- | ---------------------- | ------------------------------- | ------------------------------------- | ------------------------- | ------------------------------------- | ------------------------------------------------------------ |
| Torres Flores, Paolo Alessandro       | PaleToFo        | L                      | C                               | L                                     | C                         | L                                     | C                                                            |
| Rivera Ticllacuri, Omar Harold        | TicSide         | C                      | L                               | C                                     | L                         | C                                     | L                                                            |
| Maita Falckenheiner, Romina Guadalupe | RominaMaita     | C                      | C                               | L                                     | C                         | L                                     | C                                                            |
| Montañez Moreno, Luis Angel           | Luiso-AM        | L                      | C                               | C                                     | C                         | C                                     | L                                                            |
| Sulca Silva, Melisa Sulca             | MSS02204        | C                      | L                               | C                                     | L                         | C                                     | C                                                            |

<div style="page-break-after: always;"></div>


#### 6.2.1.3. Sprint Backlog 1.

El Sprint 1 tuvo como objetivo realizar el despliegue de la Landing Page y del Frontend Web de PsyMed, además de configurar el entorno inicial de trabajo colaborativo y validar el acceso público a las aplicaciones desplegadas. Durante este sprint se configuraron los repositorios, la integración con Vercel y las funcionalidades básicas relacionadas con autenticación y visualización inicial de la plataforma. Asimismo, se realizaron pruebas de acceso y validaciones de despliegue para asegurar el correcto funcionamiento de las aplicaciones en producción.

**Herramienta utilizada:** Trello
**Link Trello:** [https://trello.com/b/JZtqQb87](https://trello.com/b/JZtqQb87)

![Sprint Backlog 1](https://github.com/user-attachments/assets/a704e70d-f75d-4cfc-9212-b81bb017b1c7)


|  Sprint 1  |                 Sprint 1                |     |                             |                                                                                                                |                    |               |                                                |
| :--------: | :-------------------------------------: | :-: | :-------------------------: | :------------------------------------------------------------------------------------------------------------: | :----------------: | :-----------: | :--------------------------------------------: |
| User Story |             Work-Item / Task            |     |                             |                                                                                                                |                    |               |                                                |
|     Id     |                  Title                  |  Id |            Title            |                                                   Description                                                  | Estimation (Hours) |  Assigned To  | Status (To do / In process / To review / Done) |
|    US12    |  Conocer el propósito de la aplicación  | W01 |    Landing page structure   |   Desarrollo de las secciones principales de la landing page para presentar la propuesta de valor de PsyMed.   |          4         |  Paolo Torres |                      Done                      |
|    US13    | Visualizar recursos visuales relevantes | W02 |     UI visual resources     | Integración de imágenes, banners e iconografía representativa para mejorar la comprensión visual del producto. |          3         |  Romina Maita |                      Done                      |
|    US14    |  Leer contenido con tipografía adecuada | W03 |    Typography and styles    |   Configuración de estilos visuales, tipografías y diseño responsive para mejorar la experiencia de lectura.   |          3         |  Melisa Sulca |                      Done                      |
|    US02    |       Iniciar sesión como paciente      | W04 |    Patient login frontend   |          Implementación de la interfaz inicial de inicio de sesión para pacientes en el frontend web.          |          4         |  Omar Rivera  |                      Done                      |
|    US03    |     Iniciar sesión como profesional     | W05 | Professional login frontend |                 Desarrollo de la interfaz de autenticación para profesionales de salud mental.                 |          4         | Luis Montañez |                      Done                      |
|    US15    |           Iniciar sesión móvil          | W06 |    Mobile login structure   |                  Configuración inicial de pantallas de autenticación para la aplicación móvil.                 |          3         |  Omar Rivera  |                      Done                      |


<div style="page-break-after: always;"></div>


#### 6.2.1.4. Development Evidence for Sprint Review.

En esta sección se presentan las evidencias del desarrollo realizado durante el Sprint 1, correspondientes al despliegue inicial de la Landing Page y del Frontend Web de PsyMed. Las evidencias muestran la implementación de las funcionalidades básicas relacionadas con autenticación, estructura visual de la plataforma y configuración de despliegue en producción mediante Vercel.

La validación del avance se respalda mediante los commits registrados en los repositorios oficiales, los cuales documentan el progreso técnico, la integración de componentes visuales, configuración de entornos y publicación de las aplicaciones en producción.

**Repositorio del landing:**
https://github.com/IOT-UPC/landing_page

**Repositorio del frontend:**
https://github.com/IOT-UPC/front

**Repositorio del frontend móvil:**
[https://github.com/IOT-UPC/mobile-project](https://github.com/IOT-UPC/mobile-project)

Los siguientes commits documentan los cambios más resaltantes realizados durante el Sprint 1:

| Repository      | Branch  | Commit Id | Commit Message                                      | Commit Message Body                                                                                                                       | Commited on (Date) |
| --------------- | ------- | --------- | --------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| front | feature/login-ui | e63512e441486448a53b5ef3b0c25fb2006d50ed  | feature: design login page with validation messages             | Implementación inicial de la interfaz de inicio de sesión para pacientes, incluyendo validaciones básicas y estructura visual responsive. | 11/05/2026          |
| front | feature/multi-role-auth | 6731bca05091f49f98b2e83c5a398ba341d5c261  | feature: implement role-based access control for routes| Desarrollo de la pantalla de autenticación para profesionales de salud mental y configuración inicial de rutas protegidas.                | 11/05/2026         |
| Landing-Page    | develop | 25cc3e00149c525873db51b0adc6e2a939c8d957  | feat(landing): initial landing page structure       | Creación de las secciones principales de la landing page para presentar la propuesta de valor de PsyMed.                                  | 11/05/2026        |
| Landing-Page    | develop | f295b658d8008d49474e70309871a17a8b4959a3  | style(ui): improve typography and responsive design | Ajustes visuales relacionados con tipografía, diseño responsive y mejora de experiencia de usuario.                                       | 11/05/2026 6         |
| front | feature/api-config | 63f08ee39860b644520ec9bfaa79f49ca776d77c  | chore(deploy): configure vercel deployment          | Configuración del despliegue automático del frontend mediante integración con GitHub y Vercel.                                            | 11/05/2026          |
| Landing-Page    | develop | 7a28d4105be63149fd99c5dd0cbaac777757727d  | chore(deploy): deploy landing page to vercel        | Publicación de la landing page en entorno de producción utilizando Vercel.                                                                | 11/05/2026         |

<div style="page-break-after: always;"></div>


#### 6.2.1.5. Testing Suite Evidence for Sprint Review.

En esta sección se presenta el conjunto de pruebas realizadas durante el Sprint 1 para validar el correcto funcionamiento de la Landing Page y del Frontend Web de PsyMed. Las pruebas estuvieron enfocadas principalmente en verificar la correcta visualización de componentes, funcionamiento de formularios de autenticación y validación del despliegue en producción.

Durante este sprint se realizaron pruebas funcionales manuales, pruebas de integración básicas y validaciones de acceso a las aplicaciones desplegadas mediante Vercel. Asimismo, se definieron escenarios iniciales de Acceptance Testing utilizando el enfoque BDD con lenguaje Gherkin para las funcionalidades principales implementadas.

## User Stories evaluadas

| User Story | Descripción                             |
| ---------- | --------------------------------------- |
| US12       | Conocer el propósito de la aplicación   |
| US13       | Visualizar recursos visuales relevantes |
| US14       | Leer contenido con tipografía adecuada  |
| US02       | Iniciar sesión como paciente            |
| US03       | Iniciar sesión como profesional         |
| US15       | Iniciar sesión móvil                    |

---

## Acceptance Tests – BDD Scenarios

### Feature: Patient Login

```gherkin
Feature: Patient Login

  As a patient
  I want to log into the platform
  So that I can access my personal information

  Scenario: Successful login
    Given the patient is on the login page
    When the patient enters valid credentials
    Then the system should redirect the patient to the dashboard
```


### Feature: Landing Page Visualization

```gherkin
Feature: Landing Page Visualization

  As a visitor
  I want to visualize the landing page correctly
  So that I can understand the purpose of PsyMed

  Scenario: Access landing page
    Given the visitor accesses the landing page URL
    Then the main sections should load correctly
```



### Unit Tests

Durante este Sprint se realizaron validaciones sobre componentes visuales y formularios de autenticación.

| Class / Component    | Tested Behavior                 | Type of Test |
| -------------------- | ------------------------------- | ------------ |
| LoginComponent       | Validación de campos vacíos     | Unit Test    |
| LoginComponent       | Validación de formato de correo | Unit Test    |
| LandingPageComponent | Correcta carga de secciones     | Unit Test    |
| NavbarComponent      | Navegación entre secciones      | Unit Test    |

<div style="page-break-after: always;"></div>

### Integration Tests

| Integration             | Description                            |
| ----------------------- | -------------------------------------- |
| Frontend + Vercel       | Verificación del despliegue automático |
| GitHub + Vercel         | Validación de integración continua     |
| Frontend Authentication | Validación de rutas de login           |

### Testing Repositories

**Frontend Repository:** <br>
https://github.com/IOT-UPC/front

**Landing Repository:** <br>
https://github.com/IOT-UPC/landing_page

### Testing Commits Evidence

| Repository      | Branch  | Commit Id | Commit Message                         | Commit Message Body                                                                                  | Commited on (Date) |
| --------------- | ------- | --------- | -------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------ |
| front | develop | XXXXXXXX  | test(auth): validate login form        | Se agregaron validaciones iniciales para formularios de autenticación y pruebas funcionales básicas. | 11/05/2026         |
| Landing-Page    | develop | XXXXXXXX  | test(ui): validate landing sections    | Se realizaron pruebas de visualización y navegación en las secciones principales de la landing page. | 11/05/2026         |
| front | develop | XXXXXXXX  | test(deploy): verify vercel deployment | Validación del correcto despliegue del frontend en entorno de producción mediante Vercel.            | 11/05/2026         |

<div style="page-break-after: always;"></div>

#### 6.2.1.6. Execution Evidence for Sprint Review.

En esta sección se muestra la evidencia de la ejecución del sprint, incluyendo las capturas del proyecto en funcionamiento.

<img width="960" height="460" alt="welcome_1" src="https://github.com/user-attachments/assets/819e2769-c171-4fa6-a811-3f633cfc889a" />
<img width="960" height="460" alt="lista_perfiles_2" src="https://github.com/user-attachments/assets/0cf3fc01-5026-4669-b20e-d1d65641aa0a" />
<img width="960" height="460" alt="appointment_calendar_4" src="https://github.com/user-attachments/assets/88106955-300e-4e99-be92-2e07acd32077" />
<img width="960" height="460" alt="mood_5" src="https://github.com/user-attachments/assets/036e193d-165f-4f4c-9bba-52f14ef094e5" />

#### 6.2.1.7. Services Documentation Evidence for Sprint Review.

Durante este sprint se completó exitosamente la implementación y documentación de todos los Web Services correspondientes a las historias de usuario planificadas.
Se configuró Swagger UI como herramienta central para la visualización, prueba e inspección de los endpoints, facilitando la validación funcional por parte del equipo.



| Módulo          | Endpoint                                    | Verbo | Descripción                                               | URL Documentación                                                                 |
|-----------------|---------------------------------------------|-------|-----------------------------------------------------------|----------------------------------------------------------------------------------|
| Patient Reports | `/api/v1/patients/{patientId}/mood-states`  | GET   | Obtiene el historial de estados de ánimo de un paciente   | https://psymed-backend-new.onrender.com/ui/index.html          |
|   | `/api/v1/patients/{patientId}/mood-states`  | POST  | Registra un nuevo estado de ánimo para un paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patients/{patientId}/biological-functions`  | GET  | Lista funciones biológicas del paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patients/{patientId}/biological-functions`  | POST  | Crea un registro de función biológica        | https://psymed-backend-new.onrender.com/ui/index.html           |
|  Professional Profiles | `/api/v1/professional-profiles`  | POST  | Crea un perfil profesional        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/professional-profiles{profileId}`  | GET  | Obtiene un perfil por Id        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/professional-profiles/account/{accountId}`  | GET  | Obtiene el perfil asociado a una cuenta        | https://psymed-backend-new.onrender.com/ui/index.html           |
| Authentication  | `/api/v1/authentication/sign-up`  | POST  | Registro de usuarios        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/authentication/sign-in`  | POST  | Autenticación con JWT        | https://psymed-backend-new.onrender.com/ui/index.html           |
|  Professional Sessions | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions`  | POST  | Reserva una sesión        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}`  | PUT  | Actualiza una sesión        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}`  | DELETE  | Elimina una sesión        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/professionals/{professionalId}/sessions`  | GET  | Obtiene sesiones de un profesional        | https://psymed-backend-new.onrender.com/ui/index.html           |
|  Medication | `/api/v1/pills`  | POST  | Crea un medicamento        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/pills/{pillId}`  | PUT  | Actualiza medicamento        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/pills/{pillId}`  | DELETE  | Elimina medicamento        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/pills`  | GET  | Lista medicamentos        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/pills/patient/{patientId}`  | GET  | Lista medicamentos asignados a un paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
| Patient Profiles  | `/api/v1/patient-profiles`  | POST  | Crea un perfil de paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patient-profiles/{profileId}`  | GET  | Obtiene perfil        | https://psymed-backend-new.onrender.com/ui/index.html           |
|    | `/api/v1/patient-profiles/{profileId}`  | PUT  | Actualiza perfil de paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patient-profiles/{profileId}`  | DELETE  | Elimina perfil de paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patient-profiles/professional/{professionalId}`  | GET  | Perfil asociados a un psicólogo        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patient-profiles/account/{accountId}`  | GET  | Perfiles asociados a una cuenta        | https://psymed-backend-new.onrender.com/ui/index.html           |
| Session Tools  | `/api/v1/sessions/{sessionId}/notes`  | POST  | Agrega nota clínica        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/notes`  | PUT  | Actualiza nota clínica        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/notes`  | GET  | Obtiene nota clínica        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/notes`  | DELETE  | Elimina nota clínica        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/tasks`  | GET  | Lista tareas de sesión        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/tasks`  | POST  | Agrega tarea        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/tasks/{taskId}/complete`  | POST  | Marca tarea completada        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/sessions/{sessionId}/tasks/{taskId}/incomplete`  | POST  | Marca tarea como incompleta        | https://psymed-backend-new.onrender.com/ui/index.html           |
|  Patient Sessions | `/api/v1/patients/{patientId}/tasks`  | GET  | Obtiene tareas asignadas al paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |
|   | `/api/v1/patients/{patientId}/sessions`  | GET  | Lista sesiones del paciente        | https://psymed-backend-new.onrender.com/ui/index.html           |


#### 6.2.1.8. Software Deployment Evidence for Sprint Review.

Se desplegó la landing page y el frontend usando Vercel. A continuación, se presentan las evidencias del despliegue exitoso de la landing page y frontend de Psymed.

- Landing page: <br>

<img width="600" height="227" alt="image" src="https://github.com/user-attachments/assets/993cde10-62aa-48b0-b4c9-02fdb429918b" />


- Frontend: <br>

<img width="600" height="300" alt="image" src="https://github.com/user-attachments/assets/a2fe0221-b25c-4abb-8ead-4932724365d9" />

<div style="page-break-after: always;"></div>

#### 6.2.1.9. Team Collaboration Insights during Sprint.

<img width="575" height="437" alt="front_collaboration" src="https://github.com/user-attachments/assets/52f898f7-384d-49be-a21a-71076e4b6c38" />


<div style="page-break-after: always;"></div>

### 6.2.2. Sprint 2
En el Sprint #2 el equipo desplazó el foco hacia los componentes de **IoT, Edge Computing y la aplicación móvil** de PsyMed, completando así la arquitectura distribuida de la solución (IoT device → Edge → Cloud → aplicaciones). El objetivo fue construir un prototipo funcional del dispositivo de monitoreo de signos vitales basado en ESP32, un servidor edge en Flask encargado de ingerir las lecturas del dispositivo, evaluar alertas locales y sincronizar la información con el backend en la nube, y una primera versión operativa de la aplicación móvil desarrollada en Flutter. Cabe precisar que, en esta etapa, la aplicación móvil consume directamente el **backend en la nube** (no la capa IoT/Edge) y se mantiene como un **prototipo ejecutado localmente**, sin despliegue en producción. De esta manera, el sprint conecta la capa física (sensores) con la capa de servicios y las aplicaciones de usuario.

#### 6.2.2.1. Sprint Planning 2.

| **Sprint 2**                    | Sprint 2                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sprint Planning Background      |                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Date                            | 12/05/2026                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Time                            | 19:00 - 21:00                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Location                        | Virtual via Discord                                                                                                                                                                                                                                                                                                                                                                                                            |
| Prepared By                     | Paolo Alessandro Torres Flores, Omar Harold Rivera Ticllacuri                                                                                                                                                                                                                                                                                                                                                                  |
| Attendees (to planning meeting) | Paolo Alessandro Torres Flores, Omar Harold Rivera Ticllacuri, Romina Guadalupe Maita Falckenheiner, Luis Angel Montañez Moreno, Melisa Sulca Silva                                                                                                                                                                                                                                                                            |
| Sprint 1 Review                 | Durante el Sprint 1 se desplegaron exitosamente la Landing Page y el Frontend Web de PsyMed en Vercel, quedando ambas plataformas accesibles públicamente. Se completaron las funcionalidades iniciales de autenticación (paciente y profesional) y la estructura visual de la landing. El equipo cumplió los 12 story points planificados.                                                                                       |
| Sprint 1 Retrospective          | El equipo identificó como aspecto positivo la rápida configuración del despliegue continuo con Vercel y GitHub. Como punto de mejora, se reconoció la necesidad de iniciar antes el trabajo sobre los componentes de IoT y Edge, dado que requieren hardware/simulación y mayor integración. Se acordó dividir el trabajo del Sprint 2 por capas (dispositivo, edge y móvil) para paralelizar mejor las tareas.                    |
| Sprint Goal & User Stories      |                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Sprint 2 Goal                   | **Our focus is on** integrating the IoT health-monitoring device with the Edge layer and delivering the first functional version of the PsyMed mobile application.<br> **We believe it delivers** continuous monitoring of patient vital signs (heart rate and temperature), local crisis detection and alerting at the edge, and mobile access to patient information.<br> **This will be confirmed when** the ESP32 prototype transmits vital-sign readings that the edge server ingests and evaluates for alerts, and the Flutter mobile application authenticates and displays patient data retrieved from the backend. |
| Sprint 2 Velocity               | El equipo estableció una capacidad de 15 story points para este sprint, considerando que las actividades se concentraron en el prototipado del dispositivo IoT, la construcción del edge server y la primera versión funcional de la aplicación móvil.                                                                                                                                                                            |
| Sum of Story Points             | 15                                                                                                                                                                                                                                                                                                                                                                                                                             |

<div style="page-break-after: always;"></div>

#### 6.2.2.2. Aspect Leaders and Collaborators.

Para el Sprint 2 los aspectos de trabajo se reorganizaron en torno a los nuevos componentes de la solución IoT (dispositivo, edge y aplicación móvil), manteniendo el esquema de Líder (L) y Colaborador (C) por cada aspecto.

| Team member (LastName, First Name)    | GitHub UserName | Aspect 1: IoT Device Firmware (ESP32) (L/C) | Aspect 2: Edge Server (Flask) (L/C) | Aspect 3: Mobile Application (Flutter) (L/C) | Aspect 4: Cloud Sync & Backend Integration (L/C) | Aspect 5: Testing & Deployment (L/C) |
| ------------------------------------- | --------------- | ------------------------------------------- | ----------------------------------- | -------------------------------------------- | ------------------------------------------------ | ------------------------------------ |
| Maita Falckenheiner, Romina Guadalupe | RominaMaita     | L                                           | L                                   | L                                            | C                                                | C                                    |
| Rivera Ticllacuri, Omar Harold        | TicSide         | C                                           | C                                   | C                                            | L                                                | C                                    |
| Torres Flores, Paolo Alessandro       | PaleToFo        | C                                           | C                                   | C                                            | L                                                | C                                    |
| Montañez Moreno, Luis Angel           | Luiso-AM        | C                                           | C                                   | C                                            | C                                                | L                                    |
| Sulca Silva, Melisa                   | MSS02204        | C                                           | C                                   | C                                            | C                                                | L                                    |

<div style="page-break-after: always;"></div>

#### 6.2.2.3. Sprint Backlog 2.

El Sprint 2 tuvo como objetivo construir el prototipo del dispositivo IoT de monitoreo de signos vitales, el edge server encargado de la ingesta y evaluación de alertas, y la primera versión funcional de la aplicación móvil. Las tareas se distribuyeron por capas de la arquitectura, asegurando la trazabilidad entre cada User Story y su evidencia de implementación en los repositorios correspondientes.

**Herramienta utilizada:** Trello
**Link Trello:** [https://trello.com/b/JZtqQb87](https://trello.com/b/JZtqQb87)

poner imagen aquí (captura del Sprint Backlog 2 en el board de Trello)

|  Sprint 2  |                 Sprint 2                |     |                                  |                                                                                                                                  |                    |               |                                                |
| :--------: | :-------------------------------------: | :-: | :------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :----------------: | :-----------: | :--------------------------------------------: |
| User Story |             Work-Item / Task            |     |                                  |                                                                                                                                  |                    |               |                                                |
|     Id     |                  Title                  |  Id |               Title              |                                                          Description                                                            | Estimation (Hours) |  Assigned To  | Status (To do / In process / To review / Done) |
|    US16    | Monitorear signos vitales del paciente  | W07 | ESP32 vital-signs firmware       | Firmware en ESP32 (PlatformIO/Arduino) que lee ritmo cardíaco (GPIO34) y temperatura mediante termistor NTC (GPIO32).            |          5         |  Romina Maita |                      Done                      |
|    US17    | Detectar crisis y alertar localmente    | W08 | Crisis detection & actuators     | Lógica de detección de crisis (BPM > 115 o T > 38 °C) con alarma por LED (GPIO5), buzzer 880 Hz (GPIO14) y servo calmante (GPIO13). |          4         |  Romina Maita |                      Done                      |
|    US18    | Visualizar datos en el dispositivo      | W09 | OLED status display              | Visualización de hora, BPM, temperatura y estado de alarma en pantalla OLED SSD1306 128×64.                                       |          3         |  Romina Maita |                      Done                      |
|    US19    | Ingerir lecturas en el edge server      | W10 | Edge readings ingestion          | Endpoint `POST /api/iot/readings` en Flask con autenticación por token de dispositivo y evaluación automática de alertas.         |          5         |  Romina Maita |                      Done                      |
|    US20    | Sincronizar datos con el backend        | W11 | Edge → Cloud sync                | Módulo de sincronización (sync) y job programado (APScheduler) para enviar lecturas y alertas al backend en la nube.              |          4         |  Omar Rivera  |                   In process                   |
|    US21    | Acceder a la app móvil como usuario     | W12 | Mobile authentication            | Pantalla de login en Flutter con consumo de los endpoints de autenticación del backend (sign-in / sign-up).                       |          4         |  Romina Maita |                      Done                      |
|    US22    | Consultar salud y tratamiento en móvil  | W13 | Mobile health & medication views | Pantallas de salud, medicación, citas y perfil en la app móvil, integradas con los servicios del backend.                         |          4         |  Romina Maita |                      Done                      |

<div style="page-break-after: always;"></div>

#### 6.2.2.4. Development Evidence for Sprint Review.

En esta sección se presentan las evidencias del desarrollo realizado durante el Sprint 2, correspondientes al prototipo del dispositivo IoT, el edge server y la aplicación móvil de PsyMed. Las evidencias muestran la implementación del firmware de monitoreo de signos vitales en ESP32, la construcción del servidor edge en Flask (ingesta de lecturas, evaluación de alertas y sincronización con el backend) y la primera versión funcional de la aplicación móvil desarrollada en Flutter.

La validación del avance se respalda mediante los commits registrados en los repositorios oficiales de la organización, los cuales documentan el progreso técnico de cada componente.

**Repositorio del dispositivo IoT (firmware ESP32):**
https://github.com/IOT-UPC/iot-model

**Repositorio del edge server:**
https://github.com/IOT-UPC/edge-server

**Repositorio de la aplicación móvil:**
https://github.com/IOT-UPC/mobileapp

Los siguientes commits documentan los cambios más resaltantes realizados durante el Sprint 2:

| Repository          | Branch | Commit Id | Commit Message                                                                                        | Commit Message Body                                                                                                                                  | Commited on (Date) |
| ------------------- | ------ | --------- | ----------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------ |
| IOT-UPC/iot-model   | main   | 1a6ead5   | chore: initial commit                                                                                  | Inicialización del repositorio del firmware del dispositivo IoT de monitoreo.                                                                        | 13/05/2026         |
| IOT-UPC/iot-model   | main   | cf76d61   | feat: add initial project structure with .gitignore, platformio configuration, and main firmware      | Estructura inicial del proyecto PlatformIO para ESP32, configuración de build (esp32dev) y firmware principal de lectura de signos vitales.          | 14/05/2026         |
| IOT-UPC/iot-model   | main   | ba1ca93   | extra content                                                                                         | Ajustes adicionales sobre el firmware y archivos de soporte del prototipo de monitoreo.                                                              | 14/05/2026         |
| IOT-UPC/edge-server | main   | 6f1a0d0   | chore: initial commit                                                                                  | Versión inicial del edge server en Flask: ingesta de lecturas IoT, evaluación de alertas, analítica y sincronización con el backend (módulo sync).   | 14/06/2026         |
| IOT-UPC/mobileapp   | main   | d9bbdcd   | chore: initial commit                                                                                  | Versión inicial de la aplicación móvil en Flutter: autenticación, pantallas de salud, medicación, citas y perfil, con servicios de consumo de API.  | 13/06/2026         |

<div style="page-break-after: always;"></div>

#### 6.2.2.5. Testing Suite Evidence for Sprint Review.

En esta sección se presenta el conjunto de pruebas realizadas durante el Sprint 2 para validar el correcto funcionamiento del flujo IoT → Edge → Cloud y de la aplicación móvil. Dado el carácter de prototipo de esta etapa, las pruebas se enfocaron en validar la ingesta de lecturas en el edge server, la detección de alertas y la sincronización con el backend.

El repositorio del edge server incluye scripts de prueba (PowerShell) que automatizan el envío de lecturas simuladas y la verificación de las respuestas del servidor:

- `test_reading.ps1`: envía una lectura normal de signos vitales al endpoint `POST /api/iot/readings` y valida la respuesta.
- `test_alert_reading.ps1`: envía una lectura que excede los umbrales de crisis (BPM > 115 o T > 38 °C) y verifica que el edge genere la alerta correspondiente.
- `test_backend_sync.ps1`: ejecuta la sincronización de lecturas y alertas hacia el backend en la nube y valida el resultado.

**User Stories evaluadas**

| User Story | Descripción                                |
| ---------- | ------------------------------------------ |
| US16       | Monitorear signos vitales del paciente     |
| US17       | Detectar crisis y alertar localmente       |
| US19       | Ingerir lecturas en el edge server         |
| US20       | Sincronizar datos con el backend           |
| US21       | Acceder a la app móvil como usuario        |

---

**Acceptance Tests – BDD Scenarios**

### Feature: IoT Reading Ingestion

```gherkin
Feature: IoT Reading Ingestion

  As the edge server
  I want to ingest vital-sign readings from authenticated devices
  So that patient data can be stored and evaluated

  Scenario: Valid reading is accepted
    Given a registered device with a valid X-Device-Token
    When the device posts a reading to /api/iot/readings
    Then the edge server should store the reading
    And return the reading id and the alert status
```

### Feature: Crisis Alert Detection

```gherkin
Feature: Crisis Alert Detection

  As the edge server
  I want to evaluate incoming readings against crisis thresholds
  So that an alert is raised when a patient is at risk

  Scenario: Reading above thresholds triggers an alert
    Given a device sends a reading with BPM greater than 115 or temperature greater than 38 C
    When the edge server processes the reading
    Then an alert should be created
    And the response should indicate an active alert
```

### Unit / Integration Tests

| Class / Component / Module       | Tested Behavior                                          | Type of Test      |
| -------------------------------- | ------------------------------------------------------- | ----------------- |
| readings/services.py             | Registro de una lectura válida                          | Integration Test  |
| alerts/services.py               | Generación de alerta al superar umbrales de crisis      | Integration Test  |
| sync/services.py                 | Sincronización de lecturas/alertas con el backend       | Integration Test  |
| ESP32 firmware (crisis logic)    | Activación de actuadores (LED, buzzer, servo) en crisis | Manual Test (Wokwi) |
| Flutter LoginScreen / AuthProvider | Autenticación y manejo de token                       | Manual Test       |

### Testing Repositories

**Edge Server Repository:** <br>
https://github.com/IOT-UPC/edge-server

**Testing Commits Evidence**

| Repository          | Branch | Commit Id | Commit Message        | Commit Message Body                                                                                          | Commited on (Date) |
| ------------------- | ------ | --------- | --------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------ |
| IOT-UPC/edge-server | main   | 6f1a0d0   | chore: initial commit | Incluye los scripts de prueba `test_reading.ps1`, `test_alert_reading.ps1` y `test_backend_sync.ps1` del edge. | 14/06/2026         |

<div style="page-break-after: always;"></div>

#### 6.2.2.6. Execution Evidence for Sprint Review.

En esta sección se muestra la evidencia de la ejecución del Sprint 2. Durante este sprint se logró poner en funcionamiento el prototipo del dispositivo IoT (simulado en Wokwi sobre ESP32), el edge server respondiendo a las peticiones de lecturas y alertas, y la aplicación móvil mostrando las pantallas principales conectadas al **backend en la nube** (la app no se integra con la capa IoT/Edge).

- Dispositivo IoT en funcionamiento (lectura de signos vitales y pantalla OLED): <br>
<img alt="EjecucionESP32" src="https://github.com/user-attachments/assets/c3cb5634-d55e-4f5c-9f54-d2de7b174dd3" />

- Edge server procesando una lectura y generando una alerta (consola / respuesta del endpoint): <br>
<img width="832" height="305" alt="CapturaLogsEdge" src="https://github.com/user-attachments/assets/77327417-f6e3-4fe5-8b2c-fddd8e8c723a" />


- Aplicación móvil ejecutada **localmente en emulador** (pantallas de login, home y salud), consumiendo el backend en la nube. Esta app **no forma parte del flujo IoT → Edge** y **no fue desplegada** en esta etapa.
<p align="center">
  <img src="https://github.com/user-attachments/assets/d60dce31-7915-4894-bb47-f7e47a5867c2" alt="Imagen 1" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/60c91c36-113e-49af-bb99-eb2ae439cda8" alt="Imagen 2" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d3d8fa70-0f47-400b-8806-4d8479246351" alt="Imagen 3" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/eaf9d6ea-764c-4f67-bd23-256ab8bede8b" alt="Imagen 4" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/df398009-4f7f-4245-ab1d-a1519e987d18" alt="Imagen 5" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e328de5a-59a8-442c-bb63-3d786dfdc5b3" alt="Imagen 6" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7d1c1ecd-2cfa-409c-9106-13361fcf5442" alt="Imagen 7" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f43b6518-2f23-461e-8d4b-fccef78bf80d" alt="Imagen 8" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/7b6b2085-e9d1-41b7-8ede-c0a2618ceaf2" alt="Imagen 9" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/09ee2c15-7310-4e35-824b-26d726164fbe" alt="Imagen 10" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/befef9dc-d225-459d-8ef5-4a347e14be67" alt="Imagen 11" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/db62de61-f89b-47b8-ab98-0f3327de9fcc" alt="Imagen 12" width="380">
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/42342328-b232-4cee-aa6a-3c7dc30ad00e" alt="Imagen 13" width="380">
</p>



#### 6.2.2.7. Services Documentation Evidence for Sprint Review.

Durante este sprint se implementó y documentó la API del **edge server** en Flask, encargada de la comunicación con el dispositivo IoT y la sincronización con el backend en la nube. Dado que en esta etapa el edge se ejecuta en un entorno local de desarrollo, las rutas de documentación corresponden a la URL local del servidor (ejecutado mediante Flask con `run.py`).

A continuación se presentan los endpoints implementados durante el Sprint 2:

| Módulo   | Endpoint                                  | Verbo | Descripción                                                                                                       | Autenticación        |
| -------- | ----------------------------------------- | ----- | ---------------------------------------------------------------------------------------------------------------- | -------------------- |
| Readings | `/api/iot/readings`                       | POST  | Recibe una lectura de signos vitales desde el dispositivo, evalúa alertas y retorna el id de la lectura y el estado de alerta. | Header `X-Device-Token` |
| Devices  | `/api/iot/devices/<device_id>/status`     | GET   | Devuelve los metadatos del dispositivo: estado de activación, versión de firmware y último contacto.             | No requiere          |
| Sync     | `/api/sync/retry`                         | POST  | Procesa las tareas de sincronización pendientes hacia el backend y retorna el resultado de la operación.         | No requiere          |
| Health   | `/api/health`                             | GET   | Retorna el estado del edge server: dispositivos activos, dispositivos en línea y total de lecturas registradas.  | No requiere          |

**Ejemplo de request (ingesta de lectura):**

```http
POST /api/iot/readings
X-Device-Token: <token-del-dispositivo>
Content-Type: application/json

{
  "bpm": 122,
  "temperature": 38.4,
  "timestamp": "2026-06-14T10:15:00-05:00"
}
```

**Ejemplo de response:**

```json
{
  "reading_id": 42,
  "alert": true
}
```

Captura de la interacción con la documentación / pruebas del edge server: <br>
poner imagen aquí

**Repositorio de Web Services (Edge):** https://github.com/IOT-UPC/edge-server — commit `6f1a0d0`.

<div style="page-break-after: always;"></div>

#### 6.2.2.8. Software Deployment Evidence for Sprint Review.

En esta sección se resumen las actividades de despliegue realizadas durante el Sprint 2. Considerando que esta etapa corresponde a la construcción de un **prototipo funcional**, el despliegue se realizó en un entorno local y de simulación, dejando el despliegue en la nube de estos componentes planificado para un sprint posterior.

- **Dispositivo IoT (ESP32):** el firmware fue desarrollado con PlatformIO (entorno `esp32dev`, framework Arduino) y ejecutado/validado mediante el simulador **Wokwi** (red `Wokwi-GUEST`). El dispositivo envía las lecturas vía HTTP, utilizando un endpoint de prueba (mock) que emula la API de ingesta del edge.
- **Edge Server (Flask):** se preparó el script `setup_edge.ps1` para la instalación del entorno virtual y dependencias (`requirements.txt`), utilizando una base de datos local **SQLite** (`edge.sqlite3`). El servidor se ejecuta localmente mediante `run.py` y expone los endpoints documentados en la sección 6.2.2.7.
- **Aplicación móvil (Flutter):** la app se compiló y ejecutó **localmente** en emulador/dispositivo, configurada para consumir el backend mediante una URL base local definida en `api_services.dart`. **No fue desplegada** en esta etapa ni se integra con la capa IoT/Edge; su despliegue queda planificado para un sprint posterior.

Capturas del entorno de despliegue/ejecución (Wokwi y edge server en consola): <br>
poner imagen aquí

#### 6.2.2.9. Team Collaboration Insights during Sprint.

En esta sección se presentan los analíticos de colaboración del equipo durante el Sprint 2. El trabajo se organizó por capas de la arquitectura: el firmware del dispositivo IoT, el edge server y la aplicación móvil, complementados con las tareas de integración con el backend, testing y despliegue. Las gráficas de contribución de los repositorios `iot-model`, `edge-server` y `mobileapp` evidencian la participación de los integrantes en los componentes de esta etapa.

Analíticos de colaboración (GitHub Insights de los repositorios iot-model, edge-server y mobileapp): <br>
poner imagen aquí

<div style="page-break-after: always;"></div>

## 6.3. Validation Interviews.

En esta sección se presentan los resultados de las entrevistas realizadas a profesionales de la salud mental y pacientes, con el objetivo de validar la usabilidad, funcionalidad y pertinencia de la aplicación PsyMed. Se detallan las preguntas formuladas, los resúmenes de cada entrevista y una evaluación basada en heurísticas de usabilidad e inclusión.

### 6.3.1. Diseño de Entrevistas.

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


### 6.3.2. Registro de Entrevistas.

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

<div style="page-break-after: always;"></div>
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

Finalmente, consideró que SciMed respeta la privacidad del paciente, dado que el registro emocional es parte del proceso terapéutico. Recomendó agregar el motivo de consulta y un sistema para asignar tareas terapéuticas, donde el paciente pueda indicar si comprendió la actividad y cómo se sintió al realizarla.

Concluyó afirmando que la plataforma es intuitiva, funcional y pertinente para el trabajo psicológico, y que con las mejoras propuestas podría convertirse en una herramienta integral para la práctica clínica y el acompañamiento terapéutico.

<div style="page-break-after: always;"></div>
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

<div style="page-break-after: always;"></div>

Entrevistas a segmento pacientes:

- Entrevista 1:

  ![ValidationInterviewSegmento#1Entrevista1](https://i.imgur.com/Du2K1Qe.png)
  
| Nombre               | Joaquin                     |
|----------------------|-----------------------------|
| Apellido             | Cuentas                     |
| Edad                 | 23 años                     |
| Distrito             | San Miguel                  |
| URL                  | https://acortar.link/rGFD6y |
| Inicio de entrevista | 00:00                       |
| Fin de entrevista    | 15:19                       |

Resumen de entrevista:

Joaquín Cuentas, de 23 años y residente en San Miguel, probó la propuesta de PsyMed, una aplicación móvil y web orientada al seguimiento de pacientes en salud mental. A partir de la sección de preguntas, la experiencia general fue positiva, ya que el entrevistado entendió con facilidad la diferencia entre el modo paciente y el modo profesional. También, señaló que el proceso de inicio de sesión y creación de usuario era claro, principalmente porque no había demasiadas opciones y eso hacía que la plataforma fuera intuitiva. Además, él indicó que el video explicativo del aplicativo móvil no le generó confusión, porque luego pudo relacionarlo con la versión web, la cual tenía funciones similares. En cuanto al registro de pacientes, medicamentos y citas, consideró que el flujo era secuencial y fácil de seguir, por lo que podría realizar esas acciones sin ayuda externa.

Sin embargo, Joaquín también identificó algunos aspectos por mejorar en la interfaz. Mencionó que algunos botones de la landing page no funcionaban correctamente y deberían redirigir al registro o a la sección correspondiente. Asimismo, observó que ciertos títulos de la landing page se veían muy parecidos al texto normal, por lo que no resaltaban la información principal. También, recomendó mejorar la distribución visual de algunos formularios, especialmente en la parte profesional, donde se agrega un paciente, porque ciertos campos se veían muy apretados en la ventana modal. Otro punto señalado fue la carga lenta en algunas secciones, lo que sugiere la necesidad de optimizar el rendimiento de la plataforma.

Respecto a las funciones de salud mental, el entrevistado consideró claro el registro del estado emocional y biológico en el modo paciente. También afirmó que le gustaría recibir notificaciones o recordatorios sobre citas y medicamentos, ya que esto haría más útil la aplicación. No obstante, expresó cierta incomodidad frente al registro diario del estado de ánimo, principalmente por motivos de privacidad. A pesar de ello, reconoció que PsyMed sí podría ayudar a los pacientes a ser más conscientes de su salud mental. Finalmente, percibió el sistema como confiable, porque separa los perfiles de paciente y profesional, y limita el acceso de la información al médico correspondiente.



- Entrevista 2:

<img width="1811" height="812" alt="foto_entrevista_paciente2" src="https://github.com/user-attachments/assets/6a35938e-e5d0-45bc-8d86-4c6a2832b4b3" />


| Nombre               | Leguer                     |
|----------------------|-----------------------------|
| Apellido             | Silva                       |
| Edad                 | 22 años                     |
| Distrito             | Magdalena del mar           |
| URL                  | https://acortar.link/IqE90D |
| Inicio de entrevista | 00:00                       |
| Fin de entrevista    | 14:13                       |

Resumen de entrevista:

Leguer Silva, de 22 años y residente en Magdalena del Mar, probó la propuesta de PsyMed, una aplicación móvil y web orientada al seguimiento de pacientes en salud mental. A partir de la entrevista realizada, la experiencia general fue positiva, ya que el entrevistado consideró que el flujo de la aplicación era intuitivo tanto en la versión móvil como en la versión web. Asimismo, indicó que procesos como la creación de usuarios, el registro de medicamentos y el agendamiento de citas eran fáciles de comprender y seguir, lo que le permitió navegar por la plataforma sin dificultades. Además, al observar la aplicación por primera vez, percibió que se trataba de una herramienta útil con potencial para ayudar a muchas personas a gestionar mejor su salud mental.

Sin embargo, Leguer también identificó algunos aspectos que podrían mejorarse en la interfaz y experiencia de usuario. Mencionó que el botón para agregar pacientes debería ser más accesible, ya que actualmente es necesario desplazarse por toda la lista para encontrarlo, lo que dificulta el proceso. Asimismo, sugirió realizar ajustes estéticos en el formulario de registro de medicamentos, especialmente en el centrado y distribución de los elementos visuales. También recomendó incorporar botones para regresar a pasos anteriores dentro de los procesos secuenciales y agregar mensajes de confirmación o aviso al guardar o enviar información, con el fin de brindar una retroalimentación más clara al usuario.

Respecto a las funciones relacionadas con la salud mental, el entrevistado señaló que se sentiría cómodo registrando su estado de ánimo diariamente, debido a que ya tiene el hábito de registrar información personal en otras aplicaciones, como el seguimiento de comidas. Además, consideró que PsyMed podría ayudar a los usuarios a desarrollar una mayor conciencia sobre su bienestar emocional y mental. Finalmente, aunque percibió la plataforma como una herramienta beneficiosa, manifestó que le gustaría contar con medidas adicionales de seguridad durante el inicio de sesión, como la implementación de una verificación en dos pasos, para reforzar la protección de la información personal de los usuarios.


<div style="page-break-after: always;"></div>
### 6.3.3. Evaluaciones según heurísticas.

#### **UX Heuristics & Principles Evaluation**
#### **Usability – Inclusive Design – Information Architecture**

**CARRERA:** Ingeniería de Software  <br>
**CURSO:** Desarrollo de Solucion IoT  <br>
**NRC:** 6785 <br>
**PROFESORES:** Marco Antonio Leon Baca <br>
**AUDITOR:** Paolo Torres <br>
**CLIENTE(S):** Grupo Go8u<br>

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

<div style="page-break-after: always;"></div>

## 6.4. Video About-the-Product.

Link del video en Microsoft Stream: https://acortar.link/bWwB1q
<br><br>

<img width="1357" height="765" alt="image" src="https://github.com/user-attachments/assets/6135843d-fcef-4bb1-b39e-7e78b0dc6c57" />

<div style="page-break-after: always;"></div>

# Conclusiones
- La salud mental en Perú enfrenta una crisis estructural caracterizada por la alta demanda de atención y la limitada capacidad del sistema para responder de manera oportuna, lo que deja a una gran parte de la población sin tratamiento adecuado. Esta situación se ve agravada por la escasez de profesionales y la sobrecarga administrativa, evidenciando la necesidad urgente de soluciones que optimicen la gestión y mejoren el acceso a los servicios de salud mental.

- Desde una perspectiva técnica, el desarrollo de una plataforma como PsyMed demuestra que la integración de tecnologías web con dispositivos IoT puede abordar de manera efectiva los problemas de gestión y monitoreo en salud mental. La centralización de datos clínicos, automatización de tareas administrativas y el monitoreo continuo de signos vitales permiten mejorar la eficiencia operativa, reducir errores y facilitar intervenciones tempranas mediante retroalimentación en tiempo real.

- A nivel económico, la implementación de PsyMed presenta una oportunidad sostenible mediante un modelo de suscripción que combina servicios digitales con dispositivos físicos diferenciadores. Además de generar ingresos recurrentes, la solución contribuye a reducir costos operativos en instituciones de salud al optimizar procesos y disminuir la carga administrativa, lo que puede traducirse en una mayor eficiencia en el uso de recursos dentro del sistema de salud.

# Video About-the-Team.

Link del video: https://acortar.link/sbpoWq

<img width="658" height="286" alt="image" src="https://github.com/user-attachments/assets/725b7d56-44e0-4678-a53e-fd1f64c74d9e" />

<div style="page-break-after: always;"></div>

# Bibliografía

<div style="margin-left: 1.25cm; margin-right: 1.50cm;">

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Angular. (s. f.). <em>Angular Material components</em>. Recuperado el 18 de abril de 2026, de <br>
https://material.angular.io/components/categories
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
AngularJS. (s. f.). <em>AngularJS Material</em>. Recuperado el 18 de abril de 2026, de <br> 
https://material.angularjs.org/latest/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Centro Nacional de Planeamiento Estratégico. (2022, diciembre). <em>Exacerbación de los problemas de salud mental</em>. Observatorio Nacional de Prospectiva. <br> Recuperado el 20 de abril de 2026, de https://observatorio.ceplan.gob.pe/ficha/r37_2022
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Centro Peruano de Estudios Gubernamentales. (2026, 3 de febrero). <em>El alto costo de la salud mental en el Perú: evidencia, brechas y desafíos de política pública</em>. BLOG – CEPEG. Recuperado el 20 de abril de 2026, de https://cepeg.pe/blog/alto-costo-salud-mental-peru/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Chang-Gómez, M., &amp; Chang-Gómez, M. Á. (2020). Bienestar en el trabajo de los profesionales de salud durante la pandemia de COVID-19: Revisión narrativa. <em>Revista Cubana de Salud Pública, 46</em>(4), e2146. https://doi.org/10.1590/rcsp.v46i4.2146
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Colegio Médico del Perú. (2022, 13 de octubre). <em>Salud mental en emergencia</em>. Colegio Médico del Perú. Recuperado el 20 de abril de 2026, de <br> https://www.cmp.org.pe/salud-mental-en-emergencia/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Conne, M. (2024). <em>The Markdown Guide</em>. MarkdownGuide. Recuperado el 18 de abril de 2026, de <br> https://www.markdownguide.org/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Conventional Commits. (s. f.). <em>Conventional commits v1.0.0</em>. Recuperado el 18 de abril de 2026, de <br> https://www.conventionalcommits.org/en/v1.0.0/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Defensoría del Pueblo. (2018, 10 de octubre). <em>Ocho de cada 10 personas no reciben atención en salud mental pese a requerirlo</em>. <br> Defensoría del Pueblo. Recuperado el 20 de abril de 2026, de <br> https://www.defensoria.gob.pe/ocho-de-cada-10-personas-no-reciben-atencion-en-salud-mental-pese-a-requerirlo/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Defensoría del Pueblo. (2020, 9 de octubre). <em>Defensoría del Pueblo: Estado peruano debe priorizar la atención de la salud mental</em>. <br> Defensoría del Pueblo. Recuperado el 20 de abril de 2026, de <br>
https://www.defensoria.gob.pe/defensoria-del-pueblo-estado-peruano-debe-priorizar-la-atencion-de-la-salud-mental/
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Diario Oficial El Peruano. (2023, 23 de abril). <em>Salud mental: casos atendidos por Minsa se incrementaron en casi 20 % durante el 2022</em>. <br> Diario Oficial El Peruano. Recuperado el 20 de abril de 2026, de <br>
https://elperuano.pe/noticia/210845-salud-mental-casos-atendidos-por-minsa-se-incrementaron-en-casi-20-durante-el-2022
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Digitalización de las instituciones hospitalarias. (2024, 9 de febrero). <em>Tecnología y salud: transformando el futuro de la atención médica en la región</em>. Observatorio de Desarrollo Digital. Recuperado el 5 de septiembre de 2024, de <br>
https://desarrollodigital.cepal.org/es/datos-y-hechos/digitalizacion-de-las-instituciones-hospitalarias
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Ministerio de Salud. (2024, 10 de octubre). <em>Más de 1 300 000 casos atendidos por trastornos de salud mental y problemas psicosociales</em>. <br> Plataforma del Estado Peruano. Recuperado el 20 de abril de 2026, de <br>
https://www.gob.pe/institucion/minsa/noticias/1037025-mas-de-1-300-000-casos-atendidos-por-trastornos-de-salud-mental-y-problemas-psicosociales
</p>

<p style="padding-left: 1.25cm; text-indent: -1.25cm; text-align: left;">
Organización Mundial de la Salud. (2022, 2 de marzo). <em>La pandemia de COVID-19 aumenta en un 25 % la prevalencia de la ansiedad y la depresión en todo el mundo</em>. Organización Mundial de la Salud. Recuperado el 20 de abril de 2026, de <br> 
https://www.who.int/es/news/item/02-03-2022-covid-19-pandemic-triggers-25-increase-in-prevalence-of-anxiety-and-depression-worldwide
</p>

</div>

# Anexos
### Anexo A: NeedFinding Interviews:
- Link de entrevistas: https://acortar.link/KSvAbw

### Anexo B: Video about the team:
- Link del video about the team: https://acortar.link/bWwB1q
