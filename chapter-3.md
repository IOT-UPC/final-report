# Capítulo III: Requirements Specification

## 3.1. User Stories.

### Epics

<table>
  <tr>
    <th>Epic ID</th>
    <th>Título</th>
    <th>Descripción</th>
  </tr>
  <tr>
    <td>EP01</td>
    <td>Gestión de Identidad y Acceso</td>
    <td>Registro e inicio de sesión de pacientes y profesionales de la salud mental, incluyendo recuperación de contraseña y asignación de roles.</td>
  </tr>
  <tr>
    <td>EP02</td>
    <td>Seguimiento Emocional y Biológico</td>
    <td>Registro y visualización del estado de ánimo y funciones biológicas (sueño, hambre, energía, hidratación) del paciente.</td>
  </tr>
  <tr>
    <td>EP03</td>
    <td>Gestión de Medicamentos</td>
    <td>Registro de medicamentos por parte del profesional y visualización de los mismos por parte del paciente.</td>
  </tr>
  <tr>
    <td>EP04</td>
    <td>Gestión de Citas</td>
    <td>Creación de citas por parte del profesional y visualización de las citas programadas por parte del paciente.</td>
  </tr>
  <tr>
    <td>EP05</td>
    <td>Landing Page</td>
    <td>Página de presentación de la aplicación con información clara del propósito, imágenes relevantes y tipografía adecuada para visitantes.</td>
  </tr>
  <tr>
    <td>EP06</td>
    <td>Aplicación Móvil – Autenticación</td>
    <td>Inicio de sesión, visualización de perfil y cierre de sesión del paciente desde la aplicación móvil.</td>
  </tr>
  <tr>
    <td>EP07</td>
    <td>Aplicación Móvil – Seguimiento de Salud</td>
    <td>Registro diario del estado de salud del paciente (mood, hambre, hidratación, calidad de sueño, nivel de energía) desde la aplicación móvil.</td>
  </tr>
  <tr>
    <td>EP08</td>
    <td>Aplicación Móvil – Medicamentos</td>
    <td>Consulta de la lista de medicamentos asignados al paciente desde la aplicación móvil.</td>
  </tr>
  <tr>
    <td>EP09</td>
    <td>Aplicación Móvil – Citas</td>
    <td>Visualización de próximas citas médicas con sus detalles desde la aplicación móvil.</td>
  </tr>
  <tr>
    <td>EP10</td>
    <td>Gestión de Dispositivos IoT</td>
    <td>Emparejamiento de la pulsera PSYMED mediante Bluetooth y visualización del estado de conexión y batería del dispositivo.</td>
  </tr>
  <tr>
    <td>EP11</td>
    <td>Monitoreo Fisiológico IoT</td>
    <td>Visualización de métricas fisiológicas (HRV, frecuencia cardíaca, temperatura superficial), alertas de estrés, activación háptica y notificaciones al profesional.</td>
  </tr>
  <tr>
    <td>EP12</td>
    <td>Privacidad y Cumplimiento</td>
    <td>Aceptación de términos de uso y consentimiento informado, y registro de accesos a datos sensibles mediante log de auditoría.</td>
  </tr>
  <tr>
    <td>EP13</td>
    <td>Notificaciones y Recordatorios</td>
    <td>Envío de recordatorios push al paciente para la toma de medicamentos y asistencia a citas programadas.</td>
  </tr>
</table>

---

### EP01 — Gestión de Identidad y Acceso

---

**US01 - Registrar como profesional de la salud mental**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US01</td>
    <td>Profesional de la salud mental</td>
    <td>8</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar como profesional de la salud mental</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero registrarme con mis credenciales para poder acceder a las funcionalidades específicas y gestionar la información de mis pacientes.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso</b><br>
        Dado que el profesional proporciona toda la información requerida para su registro,<br>
        Cuando el sistema valida la información ingresada,<br>
        Entonces el sistema registra los datos del profesional de forma segura,<br>
        Y le asigna el rol correspondiente de profesional de la salud mental.</li>
        <li><b>Escenario 2: Información incompleta</b><br>
        Dado que el profesional no proporciona toda la información requerida,<br>
        Cuando el sistema valida los datos,<br>
        Entonces el sistema rechaza el registro,<br>
        Y notifica qué información falta para completarlo.</li>
        <li><b>Escenario 3: Credenciales duplicadas</b><br>
        Dado que el profesional intenta registrarse con credenciales ya existentes,<br>
        Cuando el sistema valida la información,<br>
        Entonces el sistema impide el registro,<br>
        Y notifica que las credenciales ya están registradas, sugiriendo la recuperación de acceso.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US02 - Iniciar sesión como paciente**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US02</td>
    <td>Paciente</td>
    <td>8</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Iniciar sesión como paciente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero iniciar sesión en la plataforma para acceder a mi información personal y seguimiento de tratamiento.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Inicio exitoso</b><br>
        Dado que el paciente ingresa correo y contraseña correctos,<br>
        Cuando hace clic en "Iniciar sesión",<br>
        Entonces accede a su cuenta y es dirigido a su panel de control.</li>
        <li><b>Escenario 2: Contraseña incorrecta</b><br>
        Dado que el paciente ingresa contraseña incorrecta,<br>
        Cuando hace clic en "Iniciar sesión",<br>
        Entonces el sistema muestra mensaje de error y ofrece opción de restablecerla.</li>
        <li><b>Escenario 3: Recuperación de contraseña</b><br>
        Dado que el paciente ha olvidado su contraseña,<br>
        Cuando hace clic en "Olvidé mi contraseña",<br>
        Entonces el sistema envía enlace de restablecimiento al correo registrado.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US03 - Iniciar sesión como profesional**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US03</td>
    <td>Profesional de la salud mental</td>
    <td>8</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Iniciar sesión como profesional</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero iniciar sesión en la plataforma para gestionar la información de mis pacientes y acceder a herramientas de seguimiento.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Inicio exitoso</b><br>
        Dado que el profesional ingresa correo y contraseña correctos,<br>
        Cuando hace clic en "Iniciar sesión",<br>
        Entonces accede a su cuenta con rol de profesional.</li>
        <li><b>Escenario 2: Contraseña incorrecta</b><br>
        Dado que el profesional ingresa contraseña incorrecta,<br>
        Cuando hace clic en "Iniciar sesión",<br>
        Entonces el sistema muestra mensaje de error y ofrece restablecerla.</li>
        <li><b>Escenario 3: Recuperación de contraseña</b><br>
        Dado que el profesional ha olvidado su contraseña,<br>
        Cuando hace clic en "Olvidé mi contraseña",<br>
        Entonces el sistema envía enlace de restablecimiento al correo registrado.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US04 - Registrar información personal del paciente**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US04</td>
    <td>Profesional de la salud mental</td>
    <td>5</td>
    <td>EP01</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar información personal del paciente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero registrar la información personal del paciente para tener una referencia detallada y precisa de sus datos básicos en cada consulta.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso</b><br>
        Dado que el profesional ingresa todos los datos del paciente,<br>
        Cuando hace clic en "Guardar",<br>
        Entonces la información se registra correctamente y queda disponible.</li>
        <li><b>Escenario 2: Registro incompleto</b><br>
        Dado que el profesional omite algún campo obligatorio,<br>
        Cuando hace clic en "Guardar",<br>
        Entonces el sistema muestra mensaje de error indicando los campos faltantes.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP02 — Seguimiento Emocional y Biológico

---

**US05 - Visualizar estado de ánimo del paciente**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US05</td>
    <td>Profesional de la salud mental</td>
    <td>3</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Visualizar estado de ánimo del paciente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero visualizar el estado de ánimo actual del paciente para evaluar su condición emocional.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización exitosa</b><br>
        Dado que el profesional ha accedido al perfil del paciente,<br>
        Cuando selecciona visualizar estados de ánimo,<br>
        Entonces el sistema muestra el estado de ánimo registrado el mismo día.</li>
        <li><b>Escenario 2: Sin registros</b><br>
        Dado que el paciente no ha registrado ningún estado de ánimo,<br>
        Cuando el profesional selecciona la opción,<br>
        Entonces el sistema muestra mensaje indicando que no hay datos disponibles.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US06 - Registrar estado de ánimo**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US06</td>
    <td>Paciente</td>
    <td>5</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar estado de ánimo</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero comunicarle a mi profesional mi estado de ánimo para que conozca mi estado actual.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro de emoción</b><br>
        Dado que el paciente está en la sección de registro de estado emocional,<br>
        Cuando registra su estado de ánimo actual,<br>
        Entonces el sistema actualiza el estado emocional en su perfil.</li>
        <li><b>Escenario 2: Historial de estados</b><br>
        Dado que el paciente tiene registros anteriores,<br>
        Cuando ingresa al historial de estados de ánimo,<br>
        Entonces el sistema muestra un calendario con los estados a lo largo del tiempo.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US07 - Registrar funciones biológicas**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US07</td>
    <td>Paciente</td>
    <td>5</td>
    <td>EP02</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar funciones biológicas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero registrar la calidad de mis funciones biológicas (sueño, hambre, energía, hidratación) para que mi profesional conozca mi estado actual de salud.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Ingreso de funciones</b><br>
        Dado que el paciente accede a la sección de registro de funciones biológicas,<br>
        Cuando selecciona su nivel de sueño, hambre, energía e hidratación en escala del 1 al 5,<br>
        Entonces la plataforma guarda los valores seleccionados correctamente.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP03 — Gestión de Medicamentos

---

**US08 - Registrar medicamentos del paciente**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US08</td>
    <td>Profesional de la salud mental</td>
    <td>3</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar medicamentos del paciente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero registrar los medicamentos del paciente para seguir adecuadamente su tratamiento farmacológico.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso</b><br>
        Dado que el profesional ingresa todos los datos del medicamento,<br>
        Cuando hace clic en "Guardar",<br>
        Entonces los datos se registran correctamente y se asocian al perfil del paciente.</li>
        <li><b>Escenario 2: Registro incompleto</b><br>
        Dado que el profesional omite algún campo obligatorio,<br>
        Cuando hace clic en "Guardar",<br>
        Entonces el sistema muestra mensaje de error indicando los campos incompletos.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US09 - Ver medicamentos**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US09</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP03</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Ver medicamentos</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder ver los medicamentos que mi profesional me ha asignado para estar pendiente de cuáles consumir.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de medicamentos</b><br>
        Dado que el paciente entra a la plataforma,<br>
        Cuando ingresa a la vista de medicamentos,<br>
        Entonces puede ver todos los medicamentos recetados con nombre, motivo, intervalo y cantidad.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP04 — Gestión de Citas

---

**US10 - Creación de citas**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US10</td>
    <td>Profesional de la salud</td>
    <td>2</td>
    <td>EP04</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Creación de citas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud, quiero agendar las citas de mis pacientes.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Creación de nueva cita</b><br>
        Dado que el profesional entra a la plataforma,<br>
        Cuando ingresa a la vista de citas sobre el perfil de un paciente y completa los datos (fecha, hora, duración),<br>
        Entonces la cita queda registrada en el sistema.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US11 - Ver citas médicas**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US11</td>
    <td>Paciente</td>
    <td>2</td>
    <td>EP04</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Ver citas médicas</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder ver las citas médicas programadas para saber qué días debo asistir al consultorio.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de citas</b><br>
        Dado que el paciente entra a la plataforma,<br>
        Cuando ingresa a la vista de citas,<br>
        Entonces puede ver todas las citas programadas con fecha, hora, duración y profesional ID.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP05 — Landing Page

---

**US12 - Encontrar información del propósito de la aplicación**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US12</td>
    <td>Visitante de la Landing Page</td>
    <td>1</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Encontrar información del propósito de la aplicación</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como visitante de la Landing Page, quiero encontrar fácilmente la información que explique el propósito de la aplicación para comprender cómo puede ser útil para mí.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visibilidad del propósito</b><br>
        Dado que el visitante se encuentra en la landing page,<br>
        Cuando explora la página principal,<br>
        Entonces la landing page posee información clara y concisa sobre el propósito de la aplicación.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US13 - Visualizar imágenes y gráficos relevantes**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US13</td>
    <td>Visitante de la Landing Page</td>
    <td>1</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Visualizar imágenes y gráficos relevantes</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como visitante de la Landing Page, quiero que las imágenes y gráficos sean claros y visualmente atractivos para captar mi interés y comprender mejor el contenido.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Calidad de las imágenes</b><br>
        Dado que el visitante explora la landing page,<br>
        Cuando observa las imágenes,<br>
        Entonces estas son de alta calidad y relevantes al contenido.</li>
        <li><b>Escenario 2: Relevancia de los gráficos</b><br>
        Dado que el visitante se desplaza por la página,<br>
        Entonces la landing page muestra gráficos que ayudan a comprender el contenido.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US14 - Usar tipografía cómoda y agradable estéticamente**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US14</td>
    <td>Visitante de la Landing Page</td>
    <td>1</td>
    <td>EP05</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Usar tipografía cómoda y agradable estéticamente</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como visitante de la Landing Page, quiero que la tipografía sea legible y estéticamente agradable para facilitar la lectura y la navegación.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Legibilidad de la tipografía</b><br>
        Dado que el visitante se desplaza por la página principal,<br>
        Entonces la tipografía es clara y de tamaño adecuado para su lectura.</li>
        <li><b>Escenario 2: Consistencia en el estilo tipográfico</b><br>
        Dado que el visitante cambia de sección,<br>
        Entonces el estilo tipográfico se mantiene consistente en toda la página.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP06 — Aplicación Móvil – Autenticación

---

**US15 - Iniciar sesión como paciente (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US15</td>
    <td>Paciente</td>
    <td>8</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Iniciar sesión como paciente (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder iniciar sesión con mi usuario y contraseña en la aplicación móvil para acceder a mi información personal y de salud.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Inicio exitoso</b><br>
        Dado que el paciente está en la pantalla de bienvenida e ingresa credenciales correctas,<br>
        Cuando pulsa "Iniciar sesión",<br>
        Entonces el sistema valida las credenciales y lo dirige a la pantalla principal.</li>
        <li><b>Escenario 2: Credenciales inválidas</b><br>
        Dado que el paciente ingresa usuario o contraseña incorrectos,<br>
        Cuando pulsa "Iniciar sesión",<br>
        Entonces el sistema muestra mensaje de error y no permite el acceso.</li>
        <li><b>Escenario 3: Campos vacíos</b><br>
        Dado que el paciente deja campos vacíos,<br>
        Cuando pulsa "Iniciar sesión",<br>
        Entonces el sistema muestra mensaje de error indicando los campos faltantes.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US16 - Visualizar información de perfil (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US16</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Visualizar información de perfil (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder ver mi información personal (correo, dirección, ID de paciente y ID de profesional) en la sección "Mi Perfil" para confirmar que mis datos son correctos.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización del perfil</b><br>
        Dado que el paciente navega a la pestaña "Profile",<br>
        Entonces ve su nombre completo, correo electrónico, dirección, ID de paciente y ID de profesional asignados.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US17 - Cerrar sesión (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US17</td>
    <td>Paciente</td>
    <td>2</td>
    <td>EP06</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Cerrar sesión (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder cerrar mi sesión de forma segura desde la pantalla de Mi Perfil para proteger mi privacidad.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Cierre exitoso</b><br>
        Dado que el paciente está en "Mi Perfil" y ha iniciado sesión,<br>
        Cuando pulsa "Cerrar sesión",<br>
        Entonces la sesión actual se cierra y es redirigido a la pantalla de inicio de sesión.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP07 — Aplicación Móvil – Seguimiento de Salud

---

**US18 - Registrar estado de salud diario (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US18</td>
    <td>Paciente</td>
    <td>5</td>
    <td>EP07</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar estado de salud diario (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder registrar mi estado de salud diario (mood, hunger, hydration, sleep quality, energy level) para llevar un seguimiento de mi bienestar.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro exitoso</b><br>
        Dado que el paciente está en la pestaña "Health" y no ha completado el registro de hoy,<br>
        Cuando selecciona una opción para cada categoría y pulsa el botón de registro,<br>
        Entonces el sistema guarda el registro y muestra mensaje de confirmación.</li>
        <li><b>Escenario 2: Reintento del mismo día</b><br>
        Dado que el paciente ya completó el registro hoy,<br>
        Cuando navega a la pestaña "Health",<br>
        Entonces ve un mensaje o botón deshabilitado indicando "Ya registrado hoy".</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP08 — Aplicación Móvil – Medicamentos

---

**US19 - Consultar lista de medicamentos (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US19</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP08</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Consultar lista de medicamentos (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder ver la lista de medicamentos que tengo asignados para conocer el nombre, el motivo, la frecuencia (intervalo) y la cantidad de cada uno.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de medicamentos</b><br>
        Dado que el paciente está en la pestaña "Medication",<br>
        Entonces ve una lista de todos sus medicamentos, mostrando para cada uno el motivo, el intervalo y la cantidad.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP09 — Aplicación Móvil – Citas

---

**US20 - Ver próximas citas (móvil)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US20</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP09</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Ver próximas citas (móvil)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero poder ver una lista de mis citas médicas próximas con sus detalles (fecha, hora, duración y profesional ID) para estar informado y planificar mi asistencia.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de citas</b><br>
        Dado que el paciente está en la pestaña "Appointments",<br>
        Entonces ve la sección "Próximas Citas" con una lista que muestra fecha, hora, duración y profesional ID de cada cita.</li>
        <li><b>Escenario 2: Identificación de cita de hoy</b><br>
        Dado que hay una cita programada para la fecha actual,<br>
        Entonces esa cita muestra una etiqueta distintiva con el texto "HOY".</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP10 — Gestión de Dispositivos IoT

---

**US21 - Emparejar dispositivo IoT (pulsera)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US21</td>
    <td>Paciente</td>
    <td>5</td>
    <td>EP10</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Emparejar dispositivo IoT (pulsera)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero emparejar mi pulsera inteligente PSYMED con mi aplicación móvil mediante Bluetooth para que los datos fisiológicos recolectados se asocien a mi perfil.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Pairing exitoso</b><br>
        Dado que el paciente ha iniciado sesión en la app móvil y el Bluetooth está activado,<br>
        Cuando navega a "Dispositivos" y selecciona "Emparejar nuevo dispositivo",<br>
        Entonces la app escanea y muestra la pulsera PSYMED cercana.</li>
        <li><b>Escenario 2: Confirmación del pairing</b><br>
        Dado que el paciente selecciona su pulsera de la lista,<br>
        Cuando se confirma un código de emparejamiento en ambos dispositivos,<br>
        Entonces la pulsera queda vinculada a la cuenta del paciente y muestra estado "Conectado".</li>
      </ul>
    </td>
  </tr>
</table>

---

**US22 - Ver estado del dispositivo IoT**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US22</td>
    <td>Paciente</td>
    <td>2</td>
    <td>EP10</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Ver estado del dispositivo IoT</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero ver el estado de conexión y el nivel de batería de mi pulsera emparejada en la aplicación para asegurarme de que funciona correctamente y saber cuándo cargarla.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de estado</b><br>
        Dado que el paciente tiene una pulsera emparejada,<br>
        Cuando accede a la sección "Mi dispositivo",<br>
        Entonces ve el estado de conexión (Conectado/Desconectado), el porcentaje de batería y la hora de la última sincronización.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP11 — Monitoreo Fisiológico IoT

---

**US23 - Visualizar datos fisiológicos del paciente (profesional)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US23</td>
    <td>Profesional de la salud mental</td>
    <td>5</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Visualizar datos fisiológicos del paciente (profesional)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero ver un dashboard con las tendencias de frecuencia cardíaca y HRV de mi paciente (últimas 4 horas, semanal, mensual) para evaluar objetivamente su respuesta fisiológica al estrés y la efectividad de los tratamientos.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de tendencias</b><br>
        Dado que el profesional está viendo el perfil detallado de un paciente,<br>
        Cuando selecciona la pestaña "Métricas IoT",<br>
        Entonces se muestran gráficos de líneas de HRV y frecuencia cardíaca en el período seleccionado, con anotaciones para eventos de estrés y activaciones hápticas.</li>
        <li><b>Escenario 2: Sin datos disponibles</b><br>
        Dado que el paciente no tiene datos de IoT registrados,<br>
        Cuando el profesional accede a la pestaña,<br>
        Entonces se muestra mensaje indicando que no hay datos disponibles.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US24 - Ver tendencias fisiológicas personales (paciente)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US24</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Ver tendencias fisiológicas personales (paciente)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero ver mis propias tendencias de frecuencia cardíaca y HRV en gráficos simples dentro de la aplicación móvil para tomar conciencia de las respuestas de mi cuerpo al estrés y ver mi progreso.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Visualización de tendencias personales</b><br>
        Dado que el paciente accede a la sección "Mis métricas IoT",<br>
        Entonces se muestran gráficos diarios y semanales de HRV y frecuencia cardíaca, con opción de ver detalles por día.</li>
        <li><b>Escenario 2: Datos históricos</b><br>
        Dado que el paciente selecciona un rango de fecha pasado,<br>
        Entonces el gráfico se actualiza para mostrar ese período.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US25 - Recibir notificaciones de alerta por estrés crítico**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US25</td>
    <td>Profesional de la salud mental / Paciente</td>
    <td>5</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Recibir notificaciones de alerta por estrés crítico</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero recibir notificaciones en la aplicación y por correo electrónico cuando un paciente experimenta un evento de estrés alto sostenido para poder contactarlo proactivamente. Como paciente, quiero recibir una notificación de que mi médico ha sido alertado.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Alerta al profesional</b><br>
        Dado que se detecta un evento de estrés alto sostenido (ej. HRV baja por más de 10 minutos),<br>
        Cuando el sistema genera la alerta,<br>
        Entonces el profesional recibe notificación push en la app y correo electrónico con detalles del paciente.</li>
        <li><b>Escenario 2: Confirmación al paciente</b><br>
        Dado que la alerta ha sido enviada al profesional,<br>
        Entonces el paciente recibe notificación push indicando que su médico ha sido notificado.</li>
        <li><b>Escenario 3: Preferencias de notificación</b><br>
        Dado que el profesional ha configurado sus preferencias,<br>
        Cuando se genera una alerta,<br>
        Entonces las notificaciones se envían solo por los canales seleccionados (app, email, o ambos).</li>
      </ul>
    </td>
  </tr>
</table>

---

**US26 - Activar vibración háptica y audio relajante por detección de ansiedad/estrés**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US26</td>
    <td>Paciente</td>
    <td>5</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Activar vibración háptica y audio relajante por detección de ansiedad/estrés</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero que mi pulsera inteligente active una vibración suave (háptica) y reproduzca un audio de relajación cuando detecte niveles elevados de ansiedad, estrés o depresión, para ayudarme a calmarme en tiempo real sin necesidad de mirar el teléfono.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Detección de ansiedad</b><br>
        Dado que el sistema detecta un nivel elevado de ansiedad (basado en HRV, FC y temperatura superficial),<br>
        Cuando el umbral configurado se supera,<br>
        Entonces la pulsera activa el motor de vibración háptica y reproduce un audio de relajación preconfigurado.</li>
        <li><b>Escenario 2: Detección de estrés</b><br>
        Dado que se detecta estrés sostenido por más de 2 minutos,<br>
        Cuando se confirma el patrón fisiológico,<br>
        Entonces se activa vibración + audio y se registra el evento.</li>
        <li><b>Escenario 3: Depresión (baja activación)</b><br>
        Dado que se detecta un patrón de baja variabilidad y FC deprimida,<br>
        Cuando el sistema lo identifica como posible episodio depresivo,<br>
        Entonces se activa una vibración más larga y suave más audio relajante.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US27 - Notificar al profesional en cada activación háptica**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US27</td>
    <td>Profesional de la salud mental</td>
    <td>3</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Notificar al profesional en cada activación háptica</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero recibir una notificación en mi aplicación cada vez que la pulsera de un paciente activa la vibración háptica y el audio por detección de un episodio de ansiedad, estrés o depresión, incluyendo datos de HRV, FC y temperatura superficial, para conocer la frecuencia de estos eventos y ajustar el tratamiento.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Notificación push</b><br>
        Dado que se activa la intervención (vibración + audio) en la pulsera del paciente,<br>
        Cuando el sistema registra el evento,<br>
        Entonces el profesional recibe notificación push con nombre del paciente, tipo de episodio, hora, HRV, FC y temperatura superficial.</li>
        <li><b>Escenario 2: Registro en dashboard</b><br>
        Dado que el profesional ingresa al perfil del paciente,<br>
        Cuando revisa la sección "Eventos IoT",<br>
        Entonces ve una lista con fecha, hora, tipo de episodio, los tres parámetros fisiológicos y si se activó la intervención.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US28 - Monitorear temperatura superficial para detección de estrés/ansiedad**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US28</td>
    <td>Profesional de la salud mental</td>
    <td>5</td>
    <td>EP11</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Monitorear temperatura superficial para detección de estrés/ansiedad</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud mental, quiero visualizar las tendencias de temperatura superficial del paciente junto con HRV y FC, ya que cambios en la temperatura periférica están asociados con activación del sistema nervioso simpático (estrés/ansiedad).</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Dashboard con temperatura</b><br>
        Dado que el profesional accede al perfil del paciente,<br>
        Cuando selecciona la pestaña "Métricas IoT",<br>
        Entonces ve un gráfico de líneas con temperatura superficial (°C) superpuesta o junto a HRV y FC.</li>
        <li><b>Escenario 2: Correlación automática</b><br>
        Dado que se detecta un evento de estrés,<br>
        Entonces el sistema muestra automáticamente la temperatura en ese momento.</li>
        <li><b>Escenario 3: Umbrales configurables</b><br>
        Dado que el profesional configura alertas,<br>
        Cuando la temperatura superficial cambia más de X grados en menos de Y minutos,<br>
        Entonces se genera una alerta temprana de posible episodio de ansiedad.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP12 — Privacidad y Cumplimiento

---

**US29 - Aceptar términos de uso y consentimiento informado**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US29</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP12</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Aceptar términos de uso y consentimiento informado</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero leer y aceptar los términos de uso y el consentimiento para el tratamiento de mis datos de salud (incluyendo los datos de la pulsera IoT) antes de usar la plataforma, para estar informado y dar mi autorización explícita.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Aceptación obligatoria</b><br>
        Dado que el paciente se registra por primera vez,<br>
        Cuando intenta continuar sin aceptar los términos,<br>
        Entonces el sistema no permite avanzar hasta que marque la casilla de aceptación.</li>
        <li><b>Escenario 2: Registro de consentimiento</b><br>
        Dado que el paciente acepta los términos,<br>
        Entonces el sistema guarda la fecha, hora y versión de los términos aceptados.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US30 - Registrar acceso a datos sensibles (log de auditoría)**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US30</td>
    <td>Profesional de la salud</td>
    <td>5</td>
    <td>EP12</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Registrar acceso a datos sensibles (log de auditoría)</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como profesional de la salud, quiero que cada acceso al historial clínico o datos fisiológicos de un paciente quede registrado en un log de auditoría, para garantizar la trazabilidad y cumplir con la ley de protección de datos.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Registro de acceso</b><br>
        Dado que un profesional visualiza el historial de un paciente,<br>
        Entonces el sistema crea un registro con: profesional ID, paciente ID, fecha, hora y acción realizada.</li>
        <li><b>Escenario 2: Consulta de auditoría</b><br>
        Dado que el administrador o el paciente solicitan ver quién accedió a sus datos,<br>
        Cuando se genera el reporte,<br>
        Entonces se muestra la lista completa de accesos registrados.</li>
      </ul>
    </td>
  </tr>
</table>

---

### EP13 — Notificaciones y Recordatorios

---

**US31 - Recibir recordatorio de medicamento**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US31</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP13</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Recibir recordatorio de medicamento</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero recibir una notificación push en mi móvil a la hora programada para tomar mi medicamento, para no olvidar mi tratamiento.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Recordatorio diario</b><br>
        Dado que el profesional ha registrado un medicamento con horario específico,<br>
        Cuando llega la hora configurada,<br>
        Entonces la app móvil envía una notificación push con el nombre del medicamento y la dosis.</li>
        <li><b>Escenario 2: Confirmación de toma</b><br>
        Dado que el paciente recibe el recordatorio,<br>
        Cuando marca "Tomado" en la notificación,<br>
        Entonces el sistema registra la confirmación y la notifica al profesional en el siguiente dashboard.</li>
      </ul>
    </td>
  </tr>
</table>

---

**US32 - Recibir recordatorio de cita**

<table>
  <tr>
    <th>Story ID</th>
    <th>User</th>
    <th>Priority</th>
    <th>Epic</th>
  </tr>
  <tr>
    <td>US32</td>
    <td>Paciente</td>
    <td>3</td>
    <td>EP13</td>
  </tr>
  <tr>
    <th colspan="4">Title</th>
  </tr>
  <tr>
    <td colspan="4">Recibir recordatorio de cita</td>
  </tr>
  <tr>
    <th colspan="4">Description</th>
  </tr>
  <tr>
    <td colspan="4">Como paciente, quiero recibir un recordatorio 24 horas antes y 1 hora antes de cada cita programada, para no faltar a mis sesiones.</td>
  </tr>
  <tr>
    <th colspan="4">Acceptance Criteria</th>
  </tr>
  <tr>
    <td colspan="4">
      <ul>
        <li><b>Escenario 1: Recordatorio anticipado (24h)</b><br>
        Dado que hay una cita programada para mañana a las 10:00,<br>
        Cuando son las 10:00 del día anterior,<br>
        Entonces el sistema envía notificación push y correo electrónico al paciente.</li>
        <li><b>Escenario 2: Recordatorio inmediato (1h)</b><br>
        Dado que la cita es en 1 hora,<br>
        Entonces se envía una notificación push adicional al paciente.</li>
      </ul>
    </td>
  </tr>
</table>

## 3.2. Impact Mapping.

### Impact Mapping Segmento Profesional de la Salud
#### Ernesto Alvarez Rojas
<p align="center">
<img src="https://imgur.com/isiuK6Y.png" alt="ImpactMappingSP">
</p>

### Impact Mapping Segmento Paciente
#### Alejandro Perez Nuñez
<p align="center">
<img src="https://imgur.com/bkU4YT1.png" alt="ImpactMappingSP">
</p>

## 3.3. Product Backlog.

| # Orden | User Story Id | Título                                                                       | Descripción                                                                                                                                                                                                                                                                                                                                                    | Story Points |
|---------|---------------|------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1       | US01          | Registrar profesional de salud mental                                        | Como profesional de la salud mental, quiero registrarme con mis credenciales para poder acceder a las funcionalidades específicas y gestionar la información de mis pacientes.                                                                                                                                                                                 | 8            |
| 2       | US02          | Iniciar sesión como paciente                                                 | Como paciente, quiero iniciar sesión en la plataforma para acceder a mi información personal y seguimiento de tratamiento.                                                                                                                                                                                                                                     | 8            |
| 3       | US03          | Iniciar sesión como profesional                                              | Como profesional de la salud mental, quiero iniciar sesión en la plataforma para gestionar la información de mis pacientes y acceder a herramientas de seguimiento.                                                                                                                                                                                            | 8            |
| 4       | US15          | Iniciar sesión como paciente (móvil)                                         | Como paciente, quiero poder iniciar sesión con mi usuario y contraseña en la aplicación móvil para acceder a mi información personal y de salud.                                                                                                                                                                                                               | 8            |
| 5       | US04          | Registrar información personal del paciente                                  | Como profesional de la salud mental, quiero registrar la información personal del paciente para tener una referencia detallada y precisa de sus datos básicos en cada consulta.                                                                                                                                                                                | 5            |
| 6       | US06          | Registrar estado de ánimo                                                    | Como paciente, quiero comunicarle a mi profesional mi estado de ánimo para que conozca mi estado actual.                                                                                                                                                                                                                                                       | 5            |
| 7       | US07          | Registrar funciones biológicas                                               | Como paciente, quiero registrar la calidad de mis funciones biológicas (sueño, hambre, energía, hidratación) para que mi profesional conozca mi estado actual de salud.                                                                                                                                                                                        | 5            |
| 8       | US18          | Registrar estado de salud diario (móvil)                                     | Como paciente, quiero poder registrar mi estado de salud diario (mood, hunger, hydration, sleep quality, energy level) para llevar un seguimiento de mi bienestar.                                                                                                                                                                                             | 5            |
| 9       | US21          | Emparejar dispositivo IoT (pulsera)                                          | Como paciente, quiero emparejar mi pulsera inteligente PSYMED con mi aplicación móvil mediante Bluetooth para que los datos fisiológicos recolectados se asocien a mi perfil.                                                                                                                                                                                  | 5            |
| 10      | US23          | Visualizar datos fisiológicos del paciente (profesional)                     | Como profesional de la salud mental, quiero ver un dashboard con las tendencias de frecuencia cardíaca y HRV de mi paciente (últimas 4 horas, semanal, mensual) para evaluar objetivamente su respuesta fisiológica al estrés y la efectividad de los tratamientos.                                                                                            | 5            |
| 11      | US25          | Recibir notificaciones de alerta por estrés crítico                          | Como profesional de la salud mental, quiero recibir notificaciones en la aplicación y por correo electrónico cuando un paciente experimenta un evento de estrés alto sostenido para poder contactarlo proactivamente. Como paciente, quiero recibir una notificación de que mi médico ha sido alertado.                                                        | 5            |
| 12      | US26          | Activar vibración háptica y audio relajante por detección de ansiedad/estrés | Como paciente, quiero que mi pulsera inteligente active una vibración suave (háptica) y reproduzca un audio de relajación cuando detecte niveles elevados de ansiedad, estrés o depresión, para ayudarme a calmarme en tiempo real sin necesidad de mirar el teléfono.                                                                                         | 5            |
| 13      | US28          | Monitorear temperatura superficial para detección de estrés/ansiedad         | Como profesional de la salud mental, quiero visualizar las tendencias de temperatura superficial del paciente junto con HRV y FC, ya que cambios en la temperatura periférica están asociados con activación del sistema nervioso simpático (estrés/ansiedad).                                                                                                 | 5            |
| 14      | US30          | Registrar acceso a datos sensibles (log de auditoría)                        | Como profesional de la salud, quiero que cada acceso al historial clínico o datos fisiológicos de un paciente quede registrado en un log de auditoría, para garantizar la trazabilidad y cumplir con la ley de protección de datos.                                                                                                                            | 5            |
| 15      | US05          | Visualizar estado de ánimo del paciente                                      | Como profesional de la salud mental, quiero visualizar el estado de ánimo actual del paciente para evaluar su condición emocional.                                                                                                                                                                                                                             | 3            |
| 16      | US08          | Registrar medicamentos del paciente                                          | Como profesional de la salud mental, quiero registrar los medicamentos del paciente para seguir adecuadamente su tratamiento farmacológico.                                                                                                                                                                                                                    | 3            |
| 17      | US09          | Ver medicamentos                                                             | Como paciente, quiero poder ver los medicamentos que mi profesional me ha asignado para estar pendiente de cuáles consumir.                                                                                                                                                                                                                                    | 3            |
| 18      | US16          | Visualizar información de perfil (móvil)                                     | Como paciente, quiero poder ver mi información personal (correo, dirección, ID de paciente y ID de profesional) en la sección "Mi Perfil" para confirmar que mis datos son correctos.                                                                                                                                                                          | 3            |
| 19      | US19          | Consultar lista de medicamentos (móvil)                                      | Como paciente, quiero poder ver la lista de medicamentos que tengo asignados para conocer el nombre, el motivo, la frecuencia (intervalo) y la cantidad de cada uno.                                                                                                                                                                                           | 3            |
| 20      | US20          | Ver próximas citas (móvil)                                                   | Como paciente, quiero poder ver una lista de mis citas médicas próximas con sus detalles (fecha, hora, duración y profesional ID) para estar informado y planificar mi asistencia.                                                                                                                                                                             | 3            |
| 21      | US24          | Ver tendencias fisiológicas personales (paciente)                            | Como paciente, quiero ver mis propias tendencias de frecuencia cardíaca y HRV en gráficos simples dentro de la aplicación móvil para tomar conciencia de las respuestas de mi cuerpo al estrés y ver mi progreso.                                                                                                                                              | 3            |
| 22      | US27          | Notificar al profesional en cada activación háptica                          | Como profesional de la salud mental, quiero recibir una notificación en mi aplicación cada vez que la pulsera de un paciente activa la vibración háptica y el audio por detección de un episodio de ansiedad, estrés o depresión, incluyendo datos de HRV, FC y temperatura superficial, para conocer la frecuencia de estos eventos y ajustar el tratamiento. | 3            |
| 23      | US29          | Aceptar términos de uso y consentimiento informado                           | Como paciente, quiero leer y aceptar los términos de uso y el consentimiento para el tratamiento de mis datos de salud (incluyendo los datos de la pulsera IoT) antes de usar la plataforma, para estar informado y dar mi autorización explícita.                                                                                                             | 3            |
| 24      | US31          | Recibir recordatorio de medicamento                                          | Como paciente, quiero recibir una notificación push en mi móvil a la hora programada para tomar mi medicamento, para no olvidar mi tratamiento.                                                                                                                                                                                                                | 3            |
| 25      | US32          | Recibir recordatorio de cita                                                 | Como paciente, quiero recibir un recordatorio 24 horas antes y 1 hora antes de cada cita programada, para no faltar a mis sesiones.                                                                                                                                                                                                                            | 3            |
| 26      | US10          | Crear citas                                                                  | Como profesional de la salud, quiero agendar las citas de mis pacientes.                                                                                                                                                                                                                                                                                       | 2            |
| 27      | US11          | Ver citas médicas                                                            | Como paciente, quiero poder ver las citas médicas programadas para saber qué días debo asistir al consultorio.                                                                                                                                                                                                                                                 | 2            |
| 28      | US17          | Cerrar sesión (móvil)                                                        | Como paciente, quiero poder cerrar mi sesión de forma segura desde la pantalla de Mi Perfil para proteger mi privacidad.                                                                                                                                                                                                                                       | 2            |
| 29      | US22          | Ver estado del dispositivo IoT                                               | Como paciente, quiero ver el estado de conexión y el nivel de batería de mi pulsera emparejada en la aplicación para asegurarme de que funciona correctamente y saber cuándo cargarla.                                                                                                                                                                         | 2            |
| 30      | US12          | Encontrar información del propósito de la aplicación                         | Como visitante de la Landing Page, quiero encontrar fácilmente la información que explique el propósito de la aplicación para comprender cómo puede ser útil para mí.                                                                                                                                                                                          | 1            |
| 31      | US13          | Visualizar imágenes y gráficos relevantes                                    | Como visitante de la Landing Page, quiero que las imágenes y gráficos sean claros y visualmente atractivos para captar mi interés y comprender mejor el contenido.                                                                                                                                                                                             | 1            |
| 32      | US14          | Usar tipografía cómoda y agradable estéticamente                             | Como visitante de la Landing Page, quiero que la tipografía sea legible y estéticamente agradable para facilitar la lectura y la navegación.                                                                                                                                                                                                                   | 1            |
