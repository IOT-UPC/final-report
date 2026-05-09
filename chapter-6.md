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
- Enlace para acceder al repositorio de la [Landing Page](https://github.com/Diseno-de-experimentos-Grupo-2/Landing-Page)
- Enlace para acceder al repositorio del reporte en https://github.com/IOT-UPC/final-report
- Enlace para acceder al repositorio del [Frontend Web](https://github.com/Diseno-de-experimentos-Grupo-2/psymed-frontend)
- Enlace para acceder al repositorio del [Frontend Móvil](https://github.com/Diseno-de-experimentos-Grupo-2/psymed-mobile-flutter)

**Flujo de trabajo GitFlow**

El flujo de trabajo se basará en el modelo propuesto por Vincent Driessen en "A successful Git branching model".

# AÑADIR IMAGEN

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


### 6.1.4. Software Deployment Configuration.

### Landing page deployment:
Para el despliegue de la Landing Page se utilizará Vercel, siguiendo los pasos descritos a continuación:

1. Crear una cuenta en Vercel y vincularla con el repositorio de GitHub donde se encuentra el código de la landing page.
2. Iniciar el proceso de despliegue y esperar a que Vercel realice las validaciones y construya la landing page.
3. Una vez completado el despliegue, acceder al enlace generado para visualizar la landing page de PsyMed en producción.

Una vez completado el despliegue, la landing page quedará publicada y accesible públicamente mediante el enlace: https://landingpage-eosin-ten.vercel.app

### PsyMed frontend deployment:
Para el despliegue de la aplicación web de PsyMed se empleará Vercel, siguiendo los pasos descritos a continuación:

1. Crear una cuenta en Vercel y vincularla con el repositorio de GitHub donde se encuentra el código del frontend.
2. Configurar el proyecto en Vercel, seleccionando el repositorio correspondiente y definir los comandos de construcción y despliegue según las necesidades del proyecto (por ejemplo, "npm run build" para construir la aplicación).
3. Configurar las variables de entorno necesarias para el correcto funcionamiento de la aplicación.
4. Iniciar el proceso de despliegue y esperar a que Vercel realice las validaciones y construya la aplicación.
5. Una vez completado el despliegue, acceder al enlace generado para visualizar la aplicación web de PsyMed en producción.

Una vez desplegada, la aplicación web de PsyMed estará accesible públicamente mediante el enlace: https://psymed-frontend.vercel.app/patient/prescription/27

## 6.2. Landing Page, Services & Applications Implementation.

### 6.2.X. Sprint n

#### 6.2.X.1. Sprint Planning n.

#### 6.2.X.2. Aspect Leaders and Collaborators.

#### 6.2.X.3. Sprint Backlog n.

#### 6.2.X.4. Development Evidence for Sprint Review.

#### 6.2.X.5. Testing Suite Evidence for Sprint Review.

#### 6.2.X.6. Execution Evidence for Sprint Review.

#### 6.2.X.7. Services Documentation Evidence for Sprint Review.

#### 6.2.X.8. Software Deployment Evidence for Sprint Review.

#### 6.2.X.9. Team Collaboration Insights during Sprint.

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

## 6.4. Video About-the-Product.

Link del video en Microsoft Stream: https://acortar.link/bWwB1q
<br>

<img width="1357" height="765" alt="image" src="https://github.com/user-attachments/assets/6135843d-fcef-4bb1-b39e-7e78b0dc6c57" />


# Conclusiones

# Conclusiones y recomendaciones.

# Video About-the-Team.

# Bibliografía

# Anexos
