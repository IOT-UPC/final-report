# Capítulo III: Solution UI/UX Design
## 3.1. Product Design: 
En esta sección, presentaremos el concepto de diseño para la página web y
la aplicación, para proporcionar a nuestros usuarios una interfaz amigable
y funcional. Con este propósito en mente, hemos optado por compartir un proyecto
Figma en el que hemos trabajado todos y el cual todos pueden editar y usar los
Assets, fonts y demás.

### 3.1.1. Style Guidelines

### 3.1.1.1. General Style Guidelines

- **Branding:** El branding del logo de nuestra aplicación "PSYMED" representa un cerebro
  sobre un fondo verde, simbolizando la fusión entre la salud mental
  y el soporte administrativo eficiente. El cerebro es un emblema
  universal del conocimiento y la mente humana, lo que lo convierte
  en la elección ideal para una plataforma dedicada a apoyar a los
  médicos en el campo de la salud mental.El fondo verde añade una sensación de equilibrio, serenidad
  y crecimiento, reflejando el entorno calmado y profesional
  que nuestra aplicación busca ofrecer. Este diseño visual
  transmite confianza y un enfoque moderno, asegurando que
  tanto los médicos como sus pacientes se sientan apoyados en
  cada etapa de su interacción con la plataforma.

<div align="center">
  <img width="300" height="300" src="../../assets/PSYMED.png" alt="PsyMed">
</div>

- **Colors:**
Nuestra paleta de colores se ha seleccionado para proporcionar un 
entorno digital de apoyo a la salud mental y el bienestar, tanto para 
los psiquiatras como para sus pacientes. El objetivo principal de 
nuestra plataforma es crear un espacio donde la confianza, la claridad 
y la seguridad sean primordiales, asegurando que la interacción entre 
profesionales y pacientes sea fluida y efectiva. Este enfoque se refleja
en la selección de colores, que buscan transmitir calma, confiabilidad y 
profesionalismo. A continuación, se presenta una breve descripción de los 
colores que se utilizarán en nuestra aplicación:

- **#091133 (Azul Profundo)** Este color aporta un nivel de
  profundidad y seriedad a la plataforma, lo que lo convierte en una
  excelente elección para textos clave y elementos que requieren un
  alto contraste. Su tonalidad oscura asegura una legibilidad superior
  y destaca información crucial, permitiendo a los usuarios concentrarse
  en los detalles más importantes con facilidad. Es ideal para títulos,
  subtítulos, y enlaces que guían la experiencia del usuario de manera
  efectiva y profesional.

<div align="center">
  <img width="400" height="210" alt="image" src="https://github.com/user-attachments/assets/a8997847-10d5-447c-9c32-43944f4c3cf4" />
</div>

- **#FFFFFF (Blanco):** Este color ofrece una apariencia limpia y
  minimalista, siendo ideal para fondos y áreas de contenido que
  requieren claridad y simplicidad. Su neutralidad ayuda a crear
  un espacio visualmente relajante y despejado, permitiendo que
  otros colores y elementos destacados resalten de manera efectiva.
  El blanco es fundamental para proporcionar contraste y asegurar
  que el contenido sea fácil de leer y navegar, especialmente en
  secciones de la plataforma que buscan ofrecer una experiencia
  de usuario sin distracciones.

<div align="center">
  <img width="400" height="210" alt="image" src="https://github.com/user-attachments/assets/eaa6e5b4-83e4-49fc-8c4c-557323dfd225" />
</div>

- **#10BEAE (Teal Brillante):** Este color vibrante y refrescante
  aporta energía y modernidad a la plataforma. Es ideal para
  elementos que requieren un toque de frescura, como botones
  de acción o enlaces destacados. Su tonalidad brillante y alegre
  asegura que los usuarios se sientan motivados y comprometidos,
  creando un ambiente visual que equilibra tanto la funcionalidad
  como la estética. Este color es perfecto para destacar
  información que debe ser notada rápidamente, sin comprometer
  la armonía general de la interfaz.

<div align="center">
  <img width="400" height="210" alt="image" src="https://github.com/user-attachments/assets/985a5a2c-3d06-4fc7-a6dd-52674cde478b" />
</div>

**Scale:**
- **Base:** El tamaño base es de 18px.
- **Ratio:** Utilizaremos un ratio de escala (por ejemplo, 1.2) que definirá la relación entre los tamaños de texto, creando una jerarquía visual consistente y armoniosa en la aplicación.


**Line Spacing (Espaciado entre líneas):** Entre 1.4 y 1.6, dependiendo del tamaño de la fuente y el contexto de uso. Esto asegurará una legibilidad óptima, especialmente en textos más largos.

### Nomenclature

- **Name / Size / Weights**

    - **Heading 0 / 22px / Medium**  
      Uso: Secciones importantes o subtítulos destacados.

    - **Heading 1 / 38px / Medium**  
      Uso: Títulos principales, como el nombre de la sección o la página.

    - **Heading 2 / 34px / Medium**  
      Uso: Subtítulos de menor jerarquía, pero aún relevantes.

    - **Heading 3 / 25px / Medium**  
      Uso: Títulos de secciones menores o encabezados de subsecciones.

    - **Heading 4 / 22px / Medium**  
      Uso: Encabezados para elementos menores, como cuadros de información o tarjetas.

    - **Base / 18px / Light**  
      Uso: Texto principal o cuerpo de texto, ideal para párrafos largos y contenido estándar.

    - **Body 1 / 10px / Regular**  
      Uso: Detalles secundarios, etiquetas pequeñas o textos de ayuda.
- **Tipo de lenguaje**
  Utilizamos un lenguaje formal para garantizar que los usuarios comprendan
  claramente la información proporcionada. Este enfoque también refleja nuestro
  compromiso con la seriedad y profesionalismo en el tratamiento de la salud
  mental.


## 3.1.2. Information Architecture
La sección de arquitectura de la información se centra en 
estructurar el contenido tanto de la aplicación web como 
de la página principal de **PSYMED**. Esta sección 
abarca los siguientes aspectos clave:

### 3.1.2.1. Organization Systems
Para asegurar una jerarquía clara y precisa en nuestra aplicación, es crucial facilitar una navegación satisfactoria para el usuario. La estructura que hemos definido es la siguiente:

**Medicos:**

Al acceder a la plataforma del proyecto para profesionales de la salud mental, los usuarios (psiquiatras, psicólogos y otros profesionales de la salud mental) pueden iniciar sesión, registrarse si no tienen una cuenta previa, escoger su plan de pago y recuperar su contraseña en caso de olvido. Una vez autenticados, la página principal presenta un calendario con las fechas de sus citas y una barra lateral con las opciones: Citas, Inicio, Pacientes y Notificaciones.

En la sección de Citas, se pueden observar todas las citas del profesional con sus pacientes, así como agendar nuevas consultas o modificar horarios.

En la sección Pacientes, los profesionales pueden ver una lista de sus pacientes actuales y seleccionar a uno para acceder a su perfil detallado, con una barra lateral que incluye las opciones: Diagnóstico, Historial Clínico, Terapia, Citas.

- En Diagnóstico, se puede visualizar y agregar un nuevo diagnóstico, así como revisar el historial de diagnósticos previos.
- En Historial Clínico, se muestra la información clínica del paciente.
- En la sección Terapia, se centralizan botones para acceder a: Funciones Biológicas, Estados de Ánimo, Prescripción y Track de Pastillas.
  - Funciones Biológicas: muestra reportes estadísticos de los datos fisiológicos del paciente.
  - Estados de Ánimo: permite observar el registro y evolución emocional del paciente.
  - Prescripciones: contiene la lista de medicamentos con sus datos, dosis, frecuencia y duración del tratamiento. Incluye la opción de agregar o modificar medicamentos.
  - Track de Pastillas: permite confirmar el consumo de los medicamentos.

En la sección de Notificaciones, los profesionales reciben confirmaciones sobre actividades realizadas por los pacientes.

<div align="center">
<img width="720" height="405" alt="image" src="https://github.com/user-attachments/assets/48e18ae2-ef8f-4eb2-aac7-ac7f232ecf17" />
</div>

---
**Pacientes:**

Al acceder a la plataforma, los usuarios pueden iniciar sesión con sus credenciales, cambiar la contraseña en caso necesario, y una vez autenticados, la página principal presenta un Sidebar con las opciones: Inicio, Terapia, Citas.

En la sección "Lista de Tareas" se pueden visualizar los 
conjuntos de actividades designados por el profesional de 
la salud mental en cada sesión. Dentro de esta vista, se puede 
acceder a opciones tales como ver tareas y marcar como completadas.

- En la sección Terapia, se muestran accesos a Diagnóstico, Funciones Biológicas, Estados de Ánimo y Prescripción.
  - Diagnóstico: visualización del diagnóstico otorgado por el profesional.
  - Funciones Biológicas: muestra los registros de datos fisiológicos.
  - Estados de Ánimo: muestra el seguimiento de los estados emocionales.
  - Prescripción: permite visualizar los medicamentos recetados y confirmar su consumo.
- En la sección Citas, los pacientes pueden visualizar las citas programadas y acceder a sus detalles.
- En la sección Perfil, se puede visualizar y actualizar la información personal, incluyendo datos de contacto y de salud.

<div align="center">
  <img width="720" height="405" alt="image" src="https://github.com/user-attachments/assets/5f3803ae-8940-4afe-a2f0-7bc65ed12674" />
</div>

### 3.1.2.2. Labeling Systems

**Medicos:**

**inicio**
- Iniciar sesión
- Registrarse 
- Recuperar su contraseña

1. **Navegación Principal** (Header/Barra de navegación lateral)
   **Página** principal del usuario después de iniciar sesión.
   **Citas:** Calendario y gestión de citas con pacientes.
   **Pacientes:** Gestión de pacientes y acceso a historiales clínicos.
   **Notificaciones:** Alertas y confirmaciones de actividades.
   **Perfil:** Información del profesional de salud mental.
   Ajustes: Configuración y seguridad de la cuenta.

**Pacientes** 
  - lista de sus pacientes
      - Historial de citas
      - Tratamientos en curso
          - Diagnósticos
          - Datos fisiológicos
          - Registro de estados de ánimo
          - Tareas asignadas
          - Asignar Medicamentos

**Agenda:** 
- Agendar nuevas consultas
- Modificar horarios
- Enviar recordatorios

**Perfil:** 
- Datos de contacto
- Especialidad

**Ajustes:** 
- Cambiar contraseñas

---
**Pacientes:**

**Inicio** 
- Iniciar sesión 
- Cambiar la contraseña

**Pagina principal**
- Perfil
- Citas
- Tratamiento Actual

**Perfil:** 
- Datos de contacto
- Datos de salud

**Citas:** 
- Ver detalles de la cita

**Tratamiento Actual:** 
- Registro de Medicamentos
- Diagnóstico Actual
- Formulario de Estados de Ánimo
    - Registro de Estados Fisiológicos
    - Ver datos estadísticos de su estado a lo largo del tratamiento


### 3.1.2.3. SEO Tags and Meta Tags
Las etiquetas reflejan el contenido de nuestro proyecto, abarcando tanto la Landing Page como el Sitio Web. Han sido creadas para mejorar la visibilidad de nuestro proyecto en los principales motores de búsqueda, lo que permitirá a los usuarios encontrar fácilmente nuestra aplicacion de PSYMED.

Para la landing page:
- **Título:** PSYMED - Plataforma de Gestión de Salud Mental
- **Descripción:** PSYMED - plataforma de gestión de salud mental - LandingPage .
- **keywords:** Salud Mental,Psiquiatras, Software, Citas Médicas, Historial Clínico, Plataforma Psicólogos, Registro Pacientes, Tratamiento Psicológico, Seguimiento Pacientes. 
- **Author:** closedSource
para el Web Side: 
- **Título:** PSYMED - Plataforma de Gestión de Salud Mental
- **Descripción:** PSYMED - plataforma de gestión de salud mental - Web Side .
- **keywords:** Salud Mental,Psiquiatras, Software, Citas Médicas, Historial Clínico, Plataforma Psicólogos, Registro Pacientes, Tratamiento Psicológico, Seguimiento Pacientes.
- **Author:** closedSource

### 3.1.2.4. Searching Systems
Los médicos pueden utilizar los métodos de búsqueda por:

- Filtrado de Información por Fechas:
    - Búsqueda de sesiones por fecha
    - Búsqueda de diagnósticos por fecha
    - Búsqueda de prescripciones por fecha
    - Ver sesiones por fecha
  
Los pacientes pueden utilizar los metodos de busqueda por: 
- Filtrado de información por ID
    - Confirmación de prescripciones por ID

### 3.1.2.5. Navigation Systems

**Para Psiquiatras:**

En la plataforma para profesionales de salud mental, tras iniciar sesión, los usuarios acceden a un panel de control con un menú superior que incluye "Inicio", "Pacientes", "Agenda", "Perfil" y "Ajustes".

En "Pacientes", pueden ver y gestionar perfiles detallados de los pacientes, incluyendo historial de citas y tratamientos.

"Agenda" muestra un calendario con citas programadas y permite agendar nuevas, modificar horarios y enviar recordatorios.

En "Perfil", se visualiza la información personal del profesional y en "Ajustes", se gestionan aspectos de seguridad de la cuenta.

**Para Pacientes:**

Al ingresar, los pacientes ven un panel con opciones como "Inicio", "Perfil", "Citas" y "Tratamiento Actual".

"Tratamiento Actual" ofrece detalles sobre prescripciones, diagnósticos, estados de ánimo y datos estadísticos.

"Citas" permite ver y gestionar citas programadas, mientras que "Perfil" muestra la información personal del paciente.

Este sistema asegura un acceso rápido y sencillo a las funciones y datos clave tanto para psiquiatras como para pacientes.

## 3.1.3. Landing Page UI Design

### 3.1.3.1. Landing Page Wireframe

![WhatsApp Image 2025-11-14 at 4 16 22 AM](https://github.com/user-attachments/assets/24ee5383-262f-48bb-bc9a-d15f8353bd7b)


### 3.1.3.2. Landing Page Mock-up

![WhatsApp Image 2025-11-14 at 4 20 34 AM](https://github.com/user-attachments/assets/e2406a76-d506-4af2-bb42-f5e56158bef9)

## 3.1.4. Mobile Applications UX/UI Design. 
### 3.1.4.1. Mobile Applications Wireframes. 

![WhatsApp Image 2025-11-14 at 1 02 21 AM](https://github.com/user-attachments/assets/e36e6791-c9c9-4a16-a456-2b39b664b049)

![WhatsApp Image 2025-11-14 at 1 02 29 AM](https://github.com/user-attachments/assets/fcc39275-1402-490f-a38b-c05c0e9ed27c)


### 3.1.4.2. Mobile Applications Wireflow Diagrams.

![WhatsApp Image 2025-11-14 at 1 01 33 AM](https://github.com/user-attachments/assets/2292b40a-54d9-4fb2-8501-bab0cb8bcd5c)

![WhatsApp Image 2025-11-14 at 1 01 42 AM](https://github.com/user-attachments/assets/151a4cae-cfc6-4d11-baf8-5d7ea5157621)

### 3.1.4.3. Mobile Applications Mock-ups. 

![WhatsApp Image 2025-11-14 at 1 01 56 AM](https://github.com/user-attachments/assets/8e459426-3ea3-4f06-94f0-152b671c81da)

![WhatsApp Image 2025-11-14 at 1 02 07 AM](https://github.com/user-attachments/assets/04167e65-f6ac-44d3-b521-c5f16af0b774)

### 3.1.4.4. Mobile Applications User Flow Diagrams. 

![WhatsApp Image 2025-11-14 at 1 29 46 AM](https://github.com/user-attachments/assets/c5b0ee72-6bb4-4a14-8bff-e554e26f2451)

![WhatsApp Image 2025-11-14 at 1 30 12 AM](https://github.com/user-attachments/assets/2c3bbb26-11cc-4022-af5b-928ee7ad765b)

![WhatsApp Image 2025-11-14 at 1 45 54 AM](https://github.com/user-attachments/assets/a75e1387-c05a-406a-9440-f8a59ccb4753)

![WhatsApp Image 2025-11-14 at 1 46 03 AM](https://github.com/user-attachments/assets/16ea422c-6d36-4d81-8601-a305bace9964)

![WhatsApp Image 2025-11-14 at 1 54 22 AM](https://github.com/user-attachments/assets/6a05dcb8-13ea-4836-9a89-e392d20f5b9d)

![WhatsApp Image 2025-11-14 at 1 58 21 AM](https://github.com/user-attachments/assets/691ec546-6560-4dfb-bfbe-2982f5a3df0c)

![WhatsApp Image 2025-11-14 at 2 02 13 AM](https://github.com/user-attachments/assets/81c49f13-df7c-4cd2-bf5b-ffc47ae84236)

![WhatsApp Image 2025-11-14 at 2 05 38 AM](https://github.com/user-attachments/assets/6ada22d0-714d-4552-a941-00ef9b345baa)

![WhatsApp Image 2025-11-14 at 2 07 01 AM](https://github.com/user-attachments/assets/3041cf32-cfdf-4a12-8785-700a32c9c9a9)

![WhatsApp Image 2025-11-14 at 2 10 28 AM](https://github.com/user-attachments/assets/469b47fe-c1bc-439a-9147-52e479810896)



## 3.1.4.5. Mobile Applications Prototyping.

En esta sección se presenta el prototipo de la aplicación móvil. El prototipo incluye las pantallas principales y la navegación diseñada para representar la experiencia del usuario.

El prototipo puede visualizarse en el siguiente enlace: https://marvelapp.com/prototype/34ij6a2g 

![WhatsApp Image 2025-11-14 at 3 44 37 AM](https://github.com/user-attachments/assets/ad98640a-7ca5-4ef2-a636-aaa58e34054e)




