
## 2.4. Requirements specification
### 2.4.1 User Stories.

US01 - Registrar como profesional de la salud mental
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US01</td> <td>Profesional de la salud mental</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Registrar como profesional de la salud mental</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero registrarme con mis credenciales para poder acceder a las funcionalidades específicas y gestionar la información de mis pacientes. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional de la salud mental proporciona la información requerida para su registro,<br> Cuando el sistema valida la información ingresada,<br> Entonces el sistema debe registrar los datos del profesional de forma segura,<br> Y asignarle el rol correspondiente de profesional de la salud mental.</li> <li><b>Escenario 2: Información incompleta</b><br> Dado que el profesional de la salud mental no proporciona toda la información requerida,<br> Cuando el sistema valida los datos,<br> Entonces el sistema debe rechazar el registro,<br> Y notificar qué información falta para completarlo.</li> <li><b>Escenario 3: Credenciales duplicadas</b><br> Dado que el profesional intenta registrarse con credenciales ya existentes,<br> Cuando el sistema valida la información,<br> Entonces el sistema debe impedir el registro,<br> Y notificar que las credenciales ya están registradas, sugiriendo la recuperación de acceso.</li> </ul> </td> </tr> </table>

US02 - Iniciar de sesión como paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US02</td> <td>Paciente</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Iniciar sesión como paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como paciente, quiero iniciar sesión en la plataforma para acceder a mi información personal y seguimiento de tratamiento. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el paciente proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe permitir el acceso al entorno del paciente,<br> Y habilitar las funciones asociadas a su rol.</li> <li><b>Escenario 2: Credenciales incorrectas</b><br> Dado que el paciente ingresa credenciales incorrectas,<br> Cuando el sistema valida la información,<br> Entonces el sistema debe denegar el acceso,<br> Y notificar que las credenciales no son válidas, ofreciendo una opción de recuperación.</li> <li><b>Escenario 3: Recuperación de acceso</b><br> Dado que el paciente solicita recuperar su acceso,<br> Cuando el sistema procesa la solicitud,<br> Entonces debe enviar un enlace de restablecimiento al correo electrónico registrado.</li> </ul> </td> </tr> </table>

US03 - Iniciar de sesión como profesional de la salud mental
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US03</td> <td>Profesional de la salud mental</td> <td>8</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Iniciar de sesión como profesional de la salud mental</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero iniciar sesión en la plataforma para gestionar la información de mis pacientes y acceder a herramientas de seguimiento. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el profesional de la salud mental proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe permitir el acceso,<br> Y habilitar las funciones de gestión de pacientes correspondientes a su rol.</li> <li><b>Escenario 2: Credenciales inválidas</b><br> Dado que el profesional proporciona credenciales incorrectas,<br> Cuando el sistema las valida,<br> Entonces el sistema debe denegar el acceso,<br> Y notificar el error, ofreciendo la opción de restablecer el acceso.</li> <li><b>Escenario 3: Recuperación de acceso</b><br> Dado que el profesional solicita recuperar su contraseña,<br> Cuando el sistema procesa la solicitud,<br> Entonces debe enviar un enlace de restablecimiento al correo asociado.</li> </ul> </td> </tr> </table>

US04 - Registrar de información personal del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US04</td> <td>Profesional de la salud mental</td> <td>5</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Registrar información personal del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero registrar la información personal del paciente para tener una referencia detallada y precisa de sus datos básicos en cada consulta. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional proporciona toda la información personal requerida del paciente,<br> Cuando el sistema valida los datos,<br> Entonces debe almacenar la información de manera segura y asociarla al perfil del paciente.</li> <li><b>Escenario 2: Datos incompletos</b><br> Dado que el profesional no completa toda la información requerida,<br> Cuando el sistema valida los datos,<br> Entonces debe impedir el registro,<br> Y notificar qué información falta para completarlo.</li> </ul> </td> </tr> </table>

US05 - Visualizar del estado actual de ánimo del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US05</td> <td>Profesional de la salud mental</td> <td>3</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar el estado actual de ánimo del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como profesional de la salud mental, quiero visualizar el estado de ánimo actual del paciente para evaluar su condición emocional. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Estado disponible</b><br> Dado que existe un registro de estado de ánimo del paciente,<br> Cuando el sistema consulta el perfil del paciente,<br> Entonces debe mostrar el estado de ánimo más reciente registrado.</li> <li><b>Escenario 2: Sin registros previos</b><br> Dado que no existen registros de estado de ánimo del paciente,<br> Cuando el sistema realiza la consulta,<br> Entonces debe indicar la ausencia de registros disponibles.</li> </ul> </td> </tr> </table>

US06 - Registrar de estado de ánimo
<table> <tr> <th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th> </tr> <tr><td>US06</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar estado de ánimo</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero comunicarle a mi profesional mi estado de ánimo para ver mi estado actual. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el paciente proporciona su estado emocional actual,<br> Cuando el sistema recibe y valida la información,<br> Entonces el sistema debe almacenar el registro de estado de ánimo y asociarlo al perfil del paciente.</li> <li><b>Escenario 2: Visualización del historial</b><br> Dado que el paciente cuenta con registros previos de estados de ánimo,<br> Cuando el sistema consulta el historial,<br> Entonces debe mostrar los registros anteriores organizados cronológicamente.</li> </ul> </td></tr> </table>

US07 - Registrar de funciones biológicas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US07</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar funciones biológicas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero registrar la calidad de mis funciones biológicas para que mi profesional conozca mi estado actual de salud. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro de funciones biológicas</b><br> Dado que el paciente proporciona información sobre sus niveles de sueño, hambre, energía e hidratación,<br> Cuando el sistema valida y procesa los datos,<br> Entonces debe almacenar las respuestas en el perfil del paciente,<br> Y permitir su posterior consulta por el profesional.</li> </ul> </td></tr> </table>

US08 - Registrar de medicamentos del paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US08</td><td>Profesional de la salud mental</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar medicamentos del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como profesional de la salud mental, quiero registrar los medicamentos del paciente para seguir adecuadamente su tratamiento farmacológico. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional proporciona toda la información requerida sobre el medicamento,<br> Cuando el sistema valida los datos,<br> Entonces debe registrar la información del medicamento y asociarla al paciente correspondiente.</li> <li><b>Escenario 2: Información incompleta</b><br> Dado que la información ingresada es incompleta o incorrecta,<br> Cuando el sistema valida los datos,<br> Entonces debe rechazar el registro,<br> Y notificar los campos que necesitan corrección.</li> </ul> </td></tr> </table>

US09 - Ver medicamentos
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US09</td><td>Paciente</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver medicamentos</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero poder ver los medicamentos que mi profesional de salud mental ha asignado para poder estar pendiente de cuáles consumir. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de medicamentos</b><br> Dado que existen medicamentos registrados por el profesional,<br> Cuando el sistema consulta la información del paciente,<br> Entonces debe mostrar la lista completa de medicamentos asociados y sus detalles.</li> <li><b>Escenario 2: Sin medicamentos registrados</b><br> Dado que no hay medicamentos asignados al paciente,<br> Cuando el sistema realiza la consulta,<br> Entonces debe mostrar un mensaje indicando la ausencia de registros.</li> </ul> </td></tr> </table>

US10 - Crear citas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US10</td><td>Profesional de la salud</td><td>2</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Crear citas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como profesional de la salud, quiero agendar las citas de mis pacientes. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Creación de cita</b><br> Dado que el profesional proporciona la información necesaria (fecha, hora, duración, paciente),<br> Cuando el sistema valida y registra la información,<br> Entonces debe crear la cita y asociarla al paciente correspondiente.</li> </ul> </td></tr> </table>

US11 - Ver citas médicas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US11</td><td>Paciente</td><td>2</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver citas médicas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero poder ver las citas médicas programadas para poder saber qué días asistir al consultorio del profesional de salud mental. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de citas</b><br> Dado que existen citas médicas registradas,<br> Cuando el sistema consulta las citas asociadas al paciente,<br> Entonces debe mostrar la lista con fecha, hora y profesional asignado.</li> <li><b>Escenario 2: Sin citas registradas</b><br> Dado que no existen citas programadas,<br> Cuando el sistema realiza la consulta,<br> Entonces debe indicar que no hay citas próximas.</li> </ul> </td></tr> </table>

## Historias de usuario para la aplicación Móvil

US12 - Iniciar sesión como paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US12</td><td>Paciente</td><td>8</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Iniciar Sesión como Paciente en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero iniciar sesión con mi usuario y contraseña para acceder a mi información personal y de salud dentro de la aplicación. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Inicio exitoso</b><br> Dado que el paciente proporciona credenciales válidas,<br> Cuando el sistema las valida,<br> Entonces debe permitir el acceso al entorno móvil del paciente y cargar su información personal.</li> <li><b>Escenario 2: Credenciales inválidas</b><br> Dado que el paciente proporciona credenciales incorrectas,<br> Cuando el sistema valida la información,<br> Entonces debe rechazar el acceso e informar el error.</li> <li><b>Escenario 3: Campos vacíos</b><br> Dado que faltan datos de autenticación,<br> Cuando el sistema valida la solicitud,<br> Entonces debe impedir el acceso e indicar la ausencia de datos requeridos.</li> </ul> </td></tr> </table>

US13 - Visualizar información de perfil
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US13</td><td>Paciente</td><td>3</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar Información de Perfil en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mi información personal para confirmar que mis datos sean correctos. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización del perfil</b><br> Dado que el paciente accede a su perfil,<br> Cuando el sistema recupera su información,<br> Entonces debe mostrar nombre, correo, dirección, ID de paciente y profesional asociado.</li> </ul> </td></tr> </table>

US14 - Cerrar sesión
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US14</td><td>Paciente</td><td>2</td><td>EP01</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Cerrar Sesión en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero cerrar mi sesión de forma segura para proteger mi privacidad. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Cierre exitoso</b><br> Dado que el paciente ha iniciado sesión,<br> Cuando solicita cerrar sesión,<br> Entonces el sistema debe finalizar la sesión activa y eliminar los datos temporales de autenticación.</li> </ul> </td></tr> </table>

US15 - Registrar mi estado de salud diario
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US15</td><td>Paciente</td><td>5</td><td>EP02</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar Mi Estado de Salud Diario en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero registrar mi estado de salud diario para llevar un seguimiento de mi bienestar. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el paciente proporciona su estado diario en todas las categorías requeridas,<br> Cuando el sistema valida y guarda la información,<br> Entonces debe registrar los datos de ese día y confirmar la acción.</li> <li><b>Escenario 2: Registro duplicado</b><br> Dado que el paciente ya registró su estado diario,<br> Cuando intenta volver a hacerlo,<br> Entonces el sistema debe impedir el registro duplicado y notificar que ya existe uno.</li> </ul> </td></tr> </table>

US16 - Consultar mi lista de medicamentos
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US16</td><td>Paciente</td><td>5</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Consultar Mi Lista de Medicamentos en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mi lista de medicamentos asignados con detalles de motivo, frecuencia e intervalo. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de medicamentos</b><br> Dado que existen medicamentos registrados,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar cada medicamento con su motivo, intervalo y cantidad.</li> </ul> </td></tr> </table>

US17 - Ver próximas citas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US17</td><td>Paciente</td><td>3</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Ver Próximas Citas en la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como paciente, quiero ver mis próximas citas médicas con sus detalles para planificar mi asistencia. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización de citas</b><br> Dado que existen citas futuras,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista con fecha, hora, duración y profesional asignado.</li> <li><b>Escenario 2: Cita actual</b><br> Dado que existe una cita para la fecha actual,<br> Entonces el sistema debe marcarla con una etiqueta distintiva.</li> </ul> </td></tr> </table>

## Historias de Usuario de la Landing Page (US18 - US20)

US18 - Encontrar información del propósito de la aplicación
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US18</td><td>Visitante de la Landing Page</td><td>1</td><td>EP05</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Encontrar información del propósito de la aplicación</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como visitante de la Landing Page, quiero entender claramente el propósito de la aplicación para saber cómo puede ayudarme. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Propósito visible</b><br> Dado que el visitante accede a la página principal,<br> Cuando el sistema carga el contenido,<br> Entonces debe mostrar información clara y concisa sobre el propósito de la aplicación.</li> </ul> </td></tr> </table>

US19 - Visualizar de imágenes y gráficos relevantes
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US19</td><td>Visitante de la Landing Page</td><td>1</td><td>EP05</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar imágenes y gráficos relevantes</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4"> Como visitante de la Landing Page, quiero ver imágenes y gráficos claros que complementen la información y despierten mi interés. </td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Imágenes relevantes</b><br> Dado que el visitante navega por la página,<br> Cuando el sistema presenta contenido visual,<br> Entonces las imágenes deben ser de alta calidad y coherentes con el mensaje del sitio.</li> <li><b>Escenario 2: Gráficos informativos</b><br> Dado que el visitante visualiza secciones con gráficos,<br> Cuando el sistema muestra estos elementos,<br> Entonces deben facilitar la comprensión del contenido textual.</li> </ul> </td></tr> </table>

US20 - Visualizar tipografía cómoda y agradable estéticamente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US20</td> <td>Visitante de la Landing Page</td> <td>1</td> <td>EP05</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar tipografía cómoda y agradable estéticamente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4"> Como visitante de la Landing Page, quiero que la tipografía sea legible y visualmente coherente para facilitar la lectura y mantener una experiencia estética agradable. </td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Legibilidad de la tipografía</b><br> Dado que el visitante accede a la Landing Page,<br> Cuando el sistema muestra el contenido textual,<br> Entonces debe utilizar una tipografía clara, con un tamaño adecuado y contraste suficiente para facilitar la lectura.</li>
  <li><b>Escenario 2: Consistencia tipográfica</b><br>
  Dado que el visitante navega entre diferentes secciones de la Landing Page,<br>
  Cuando el sistema renderiza los textos,<br>
  Entonces debe mantener una coherencia visual en los estilos tipográficos (fuente, tamaño y color) en toda la página.</li>
</ul>

</td> </tr> </table>

## Nuevas historias de usuario para la aplicación móvil (valor agregado):
US21 - Crear paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US21</td> <td>Profesional de la salud mental</td> <td>7</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Crear paciente desde la aplicación móvil</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional de la salud mental, quiero crear un nuevo paciente desde la aplicación móvil para registrarlo en mi cartera y poder gestionar su información desde cualquier lugar.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Creación exitosa</b><br> Dado que el profesional ingresa los datos requeridos del paciente,<br> Cuando el sistema valida la información,<br> Entonces debe registrar al paciente y generar sus credenciales de acceso.</li> <li><b>Escenario 2: Datos incompletos</b><br> Dado que el profesional no ingresa todos los campos requeridos,<br> Cuando el sistema valida los datos,<br> Entonces el sistema debe impedir la creación,<br> Y notificar qué información falta para completarlo.</li> </ul> </td> </tr> </table>

US22 - Visualizar lista de pacientes
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US22</td> <td>Profesional de la salud mental</td> <td>6</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar lista de pacientes</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero ver la lista de mis pacientes para acceder rápidamente a su información.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Listado exitoso</b><br> Dado que el profesional accede a la sección de pacientes,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista completa de pacientes asignados con nombre, ID y datos básicos.</li> </ul> </td> </tr> </table>

US23 - Editar información del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US23</td> <td>Profesional de la salud mental</td> <td>5</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Editar información del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero editar los datos de un paciente para corregir o actualizar su información.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Edición exitosa</b><br> Dado que el profesional modifica los datos del paciente,<br> Cuando el sistema valida la información,<br> Entonces debe actualizar los datos correctamente.</li> <li><b>Escenario 2: Datos incompletos o inválidos</b><br> Dado que existen errores en los campos editados,<br> Cuando el sistema los valida,<br> Entonces debe impedir la actualización,<br> Y notificar qué información requiere corrección.</li> </ul> </td> </tr> </table>

US24 - Eliminar paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US24</td> <td>Profesional de la salud mental</td> <td>4</td> <td>EP01</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Eliminar paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero eliminar un paciente de mi lista para mantener mi cartera actualizada.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Eliminación confirmada</b><br> Dado que el profesional solicita eliminar un paciente,<br> Cuando el sistema muestra una ventana de confirmación,<br> Entonces debe eliminar al paciente una vez confirmada la acción.</li> <li><b>Escenario 2: Cancelación</b><br> Dado que el profesional decide no borrar al paciente,<br> Cuando cancela la acción,<br> Entonces el sistema debe mantener intacta la información.</li> </ul> </td> </tr> </table>

US25 - Crear tarea para un paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US25</td> <td>Profesional de la salud mental</td> <td>6</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Crear tarea para un paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero asignar tareas a mis pacientes desde la aplicación móvil para apoyar su seguimiento terapéutico.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Creación exitosa</b><br> Dado que el profesional ingresa título, descripción y fecha,<br> Cuando el sistema valida los datos,<br> Entonces debe crear la tarea y asociarla al paciente seleccionado.</li> <li><b>Escenario 2: Datos incompletos</b><br> Dado que no se ingresaron todos los campos obligatorios,<br> Cuando el sistema valida la información,<br> Entonces debe impedir la creación y notificar qué falta completar.</li> </ul> </td> </tr> </table>

US26 - Visualizar tareas del paciente
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US26</td> <td>Profesional de la salud mental</td> <td>5</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar tareas del paciente</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero ver todas las tareas asignadas a un paciente para evaluar su progreso.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Tareas disponibles</b><br> Dado que el paciente tiene tareas asignadas,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista completa con estado (pendiente/completada).</li> <li><b>Escenario 2: Sin tareas</b><br> Dado que no existen tareas asignadas al paciente,<br> Cuando el sistema realiza la consulta,<br> Entonces debe mostrar un mensaje indicando que no hay tareas registradas.</li> </ul> </td> </tr> </table>

US27 - Editar tarea
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US27</td> <td>Profesional de la salud mental</td> <td>4</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Editar tarea asignada</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero modificar los detalles de una tarea previamente asignada al paciente.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Edición exitosa</b><br> Dado que el profesional actualiza título, descripción o fecha,<br> Cuando el sistema valida la información,<br> Entonces debe guardar los cambios correctamente.</li> <li><b>Escenario 2: Datos inválidos</b><br> Dado que existen errores en los datos actualizados,<br> Cuando el sistema los valida,<br> Entonces debe impedir la edición y notificar qué corregir.</li> </ul> </td> </tr> </table>

US28 - Eliminar tarea
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US28</td> <td>Profesional de la salud mental</td> <td>3</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Eliminar tarea</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como profesional, quiero eliminar una tarea asignada al paciente cuando ya no sea necesaria.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Eliminación confirmada</b><br> Dado que el profesional solicita eliminar una tarea,<br> Cuando el sistema muestra una confirmación,<br> Entonces debe eliminar la tarea tras la aceptación.</li> <li><b>Escenario 2: Cancelación</b><br> Dado que el profesional decide no continuar con la acción,<br> Cuando cancela,<br> Entonces el sistema debe conservar la tarea sin cambios.</li> </ul> </td> </tr> </table>

US29 - Ver tareas asignadas
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US29</td> <td>Paciente</td> <td>6</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Visualizar tareas asignadas</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como paciente, quiero ver las tareas que mi profesional me ha asignado.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Tareas disponibles</b><br> Dado que existen tareas asignadas,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista con título, descripción y estado.</li> <li><b>Escenario 2: Sin tareas</b><br> Dado que no existen tareas,<br> Cuando el sistema consulta,<br> Entonces debe mostrar un mensaje indicando que no hay tareas registradas.</li> </ul> </td> </tr> </table>

US30 - Marcar tarea como completada
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US30</td> <td>Paciente</td> <td>5</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Marcar tarea como completada</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como paciente, quiero marcar una tarea asignada como completada para reflejar mi progreso.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Marcado exitoso</b><br> Dado que el paciente selecciona una tarea pendiente,<br> Cuando el sistema actualiza su estado,<br> Entonces debe marcarla como completada.</li> </ul> </td> </tr> </table>

US31 - Desmarcar tarea como completada
<table> <tr> <th>Story ID</th> <th>User</th> <th>Priority</th> <th>Epic</th> </tr> <tr> <td>US31</td> <td>Paciente</td> <td>4</td> <td>EP02</td> </tr> <tr> <th colspan="4">Title</th> </tr> <tr> <td colspan="4">Desmarcar tarea completada</td> </tr> <tr> <th colspan="4">Description</th> </tr> <tr> <td colspan="4">Como paciente, quiero poder desmarcar una tarea que marqué por error como completada.</td> </tr> <tr> <th colspan="4">Acceptance Criteria</th> </tr> <tr> <td colspan="4"> <ul> <li><b>Escenario 1: Desmarcar exitoso</b><br> Dado que el paciente selecciona una tarea completada,<br> Cuando el sistema actualiza el estado,<br> Entonces debe volver a ponerla como pendiente.</li> </ul> </td> </tr> </table>

US32 - Crear cita
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US32</td><td>Profesional de la salud mental</td><td>5</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Crear cita médica desde la aplicación móvil</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional de la salud mental, quiero crear una cita médica desde la aplicación móvil para programar sesiones con mis pacientes de manera rápida.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Creación exitosa</b><br> Dado que el profesional ingresa fecha, hora, duración y paciente,<br> Cuando el sistema valida la información,<br> Entonces debe crear la cita y asociarla al paciente correspondiente.</li> <li><b>Escenario 2: Datos incompletos</b><br> Dado que faltan datos requeridos,<br> Cuando el sistema valida la solicitud,<br> Entonces debe impedir la creación,<br> Y notificar qué información falta.</li> </ul> </td></tr> </table>

US33 - Ver citas médicas
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US33</td><td>Profesional de la salud mental</td><td>4</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar citas médicas programadas</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero ver todas las citas programadas para gestionar mi calendario clínico desde la aplicación móvil.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Visualización exitosa</b><br> Dado que existen citas registradas,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista de citas con fecha, hora, duración y paciente.</li> <li><b>Escenario 2: Sin citas</b><br> Dado que no existen citas programadas,<br> Cuando el sistema realiza la consulta,<br> Entonces debe indicar que no hay citas registradas.</li> </ul> </td></tr> </table>

US34 - Editar cita médica
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US34</td><td>Profesional de la salud mental</td><td>3</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Editar cita médica</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero poder editar los detalles de una cita médica para corregir o reorganizar mi agenda desde el móvil.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Edición exitosa</b><br> Dado que el profesional actualiza la fecha, hora o duración,<br> Cuando el sistema valida los cambios,<br> Entonces debe guardar la información actualizada.</li> <li><b>Escenario 2: Datos inválidos</b><br> Dado que los datos editados son inconsistentes o incompletos,<br> Cuando el sistema los valida,<br> Entonces debe impedir la modificación y notificar el error.</li> </ul> </td></tr> </table>

US35 - Eliminar cita médica
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US35</td><td>Profesional de la salud mental</td><td>3</td><td>EP04</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Eliminar cita médica</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero eliminar una cita médica programada para mantener mi agenda actualizada.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Eliminación confirmada</b><br> Dado que el profesional solicita eliminar una cita,<br> Cuando confirma la acción,<br> Entonces el sistema debe eliminar la cita de forma definitiva.</li> <li><b>Escenario 2: Cancelación</b><br> Dado que el profesional cancela la acción de eliminar,<br> Cuando el sistema recibe la cancelación,<br> Entonces debe conservar la cita sin cambios.</li> </ul> </td></tr> </table>

US36 - Registrar medicamento para paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US36</td><td>Profesional de la salud mental</td><td>5</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Registrar medicamento del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero registrar medicamentos desde la aplicación móvil para llevar el control farmacológico de mis pacientes.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Registro exitoso</b><br> Dado que el profesional ingresa nombre, dosis, frecuencia e indicación,<br> Cuando el sistema valida la información,<br> Entonces debe registrar el medicamento y asociarlo al paciente.</li> <li><b>Escenario 2: Información incompleta</b><br> Dado que faltan datos requeridos,<br> Cuando el sistema valida la información,<br> Entonces debe rechazar el registro y notificar qué falta completar.</li> </ul> </td></tr> </table>

US37 - Ver medicamentos del paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US37</td><td>Profesional de la salud mental</td><td>4</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar medicamentos del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero visualizar todos los medicamentos asignados a un paciente para supervisar su tratamiento.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Medicamentos disponibles</b><br> Dado que existen medicamentos registrados,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar la lista completa con nombre, dosis, frecuencia e indicación.</li> <li><b>Escenario 2: Sin medicamentos</b><br> Dado que no existen medicamentos registrados,<br> Cuando el sistema realiza la consulta,<br> Entonces debe mostrar un mensaje indicando la ausencia de registros.</li> </ul> </td></tr> </table>

US38 - Editar medicamento del paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US38</td><td>Profesional de la salud mental</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Editar medicamento del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero editar la información de un medicamento registrado para ajustarlo al tratamiento actual del paciente.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Edición exitosa</b><br> Dado que el profesional actualiza dosis, frecuencia o indicación,<br> Cuando el sistema valida los cambios,<br> Entonces debe guardar la información actualizada.</li> <li><b>Escenario 2: Datos inválidos</b><br> Dado que los datos editados son incorrectos o incompletos,<br> Cuando el sistema valida,<br> Entonces debe impedir la modificación y notificar el error.</li> </ul> </td></tr> </table>

US39 - Eliminar medicamento del paciente
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US39</td><td>Profesional de la salud mental</td><td>3</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Eliminar medicamento del paciente</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como profesional, quiero eliminar un medicamento del paciente cuando ya no forme parte de su tratamiento.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Eliminación confirmada</b><br> Dado que el profesional solicita eliminar un medicamento,<br> Cuando confirma la acción,<br> Entonces el sistema debe borrar el registro de forma definitiva.</li> <li><b>Escenario 2: Cancelación</b><br> Dado que el profesional cancela la acción,<br> Cuando el sistema procesa la cancelación,<br> Entonces debe conservar el medicamento sin cambios.</li> </ul> </td></tr> </table>

US40 - Ver medicamentos asignados
<table> <tr><th>Story ID</th><th>User</th><th>Priority</th><th>Epic</th></tr> <tr><td>US40</td><td>Paciente</td><td>4</td><td>EP03</td></tr> <tr><th colspan="4">Title</th></tr> <tr><td colspan="4">Visualizar medicamentos asignados</td></tr> <tr><th colspan="4">Description</th></tr> <tr><td colspan="4">Como paciente, quiero ver mi lista de medicamentos registrados con sus detalles completos para seguir adecuadamente mi tratamiento.</td></tr> <tr><th colspan="4">Acceptance Criteria</th></tr> <tr><td colspan="4"> <ul> <li><b>Escenario 1: Medicamentos disponibles</b><br> Dado que existen medicamentos asociados al paciente,<br> Cuando el sistema recupera la información,<br> Entonces debe mostrar nombre, dosis, frecuencia, motivo e indicaciones.</li> <li><b>Escenario 2: Sin medicamentos</b><br> Dado que no existen medicamentos registrados,<br> Cuando el sistema realiza la consulta,<br> Entonces debe mostrar un mensaje indicando que no hay medicamentos asignados.</li> </ul> </td></tr> </table>

**Spike Stories**

| Story ID | User      | Priority | Epic                           | Title                                                                                                | Description                                                                                                                                                                                                             | Acceptance Criteria                                                                                                                                                                                                                                                                         |
|----------|-----------|----------|--------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SP-01    | Developer | Alta     | Autenticación                  | Investigar bibliotecas de autenticación y manejo de roles                                            | Como desarrollador quiero investigar bibliotecas y frameworks de autenticación (JWT) para determinar cuál es más adecuada para integrar autenticación segura y diferenciación de roles entre pacientes y profesionales. | Dado que se realiza la investigación de bibliotecas de autenticación<br>Cuando se evalúan criterios de compatibilidad, seguridad, persistencia de sesión y soporte multiplataforma<br>Entonces se entrega un documento técnico con la librería recomendada y un prototipo mínimo funcional. |
| SP-02    | Developer | Alta     | Sincronización móvil–backend   | Analizar mecanismos de sincronización de datos entre aplicación móvil y backend                      | Como desarrollador quiero investigar las opciones de sincronización de datos (online/offline) entre la aplicación móvil y el backend para garantizar consistencia de la información clínica y del paciente.             | Dado que se analizan distintas estrategias de sincronización (REST, local)<br>Cuando se evalúan la latencia, seguridad y manejo de errores<br>Entonces se presenta un documento técnico y un prototipo que demuestra la sincronización correcta de datos básicos del usuario.               |
| SP-03    | Developer | Media    | Gestión de información clínica | Definir modelo de datos y herramientas para visualización de estado emocional y funciones biológicas | Como desarrollador quiero definir la estructura de base de datos y las herramientas de visualización adecuadas para representar los estados de ánimo, funciones biológicas y medicamentos del paciente.                 | Dado que se analizan bases de datos SQL<br>Cuando se evalúan criterios de rendimiento, escalabilidad y compatibilidad con el backend<br>Entonces se entrega un esquema de datos propuesto y un prototipo visual básico de los registros del paciente.                                       |
| SP-04    | Developer | Media    | Sistema de citas               | Investigar opciones para la gestión y visualización de citas médicas                                 | Como desarrollador quiero investigar librerías y APIs que faciliten la creación, visualización y sincronización de citas médicas entre paciente y profesional.                                                          | Dado que se prueban distintas herramientas de calendarización<br>Cuando se evalúan sus capacidades de integración, manejo de conflictos y notificaciones<br>Entonces se documenta la opción más viable y se crea un prototipo que demuestre la creación de una cita básica.                 |
| SP-05    | Developer | Baja     | Web App                        | Investigar diseño visual, tipografía y accesibilidad para la Web App                                 | Como desarrollador quiero investigar lineamientos de diseño visual, tipografía y frameworks front-end para crear una Web App atractiva, legible y accesible.                                                            | Dado que se analizan frameworks como Angular Material y TailwindCSS<br>Cuando se evalúan los criterios de legibilidad, contraste, accesibilidad y consistencia visual<br>Entonces se entrega un prototipo de la Web App y una guía de estilos inicial para su implementación.               |

### 2.4.2 Impact Mapping.

### Segmento profesionales:
![Professionals_](/assets/professionals_IM.jpeg)

### Segmento pacientes:
![Patients_impactmapping](/assets/patients_IM.jpeg)

## 2.4.3 Product Backlog.

| # Orden | User Story ID | Título                                                        | Story Points |
|---------|---------------|---------------------------------------------------------------|--------------|
| 1       | US01          | Registrar como profesional de la salud mental                 | 8            |
| 2       | US02          | Iniciar sesión como paciente                                  | 8            |
| 3       | US03          | Iniciar sesión como profesional de la salud mental            | 8            |
| 4       | US12          | Iniciar sesión como paciente (móvil)                          | 8            |
| 5       | US21          | Crear paciente desde la aplicación móvil                      | 8            |
| 6       | US22          | Visualizar lista de pacientes                                 | 5            |
| 7       | US25          | Crear tarea para un paciente                                  | 5            |
| 8       | US29          | Visualizar tareas asignadas (paciente)                        | 5            |
| 9       | US04          | Registrar información personal del paciente                   | 5            |
| 10      | US06          | Registrar estado de ánimo                                     | 5            |
| 11      | US07          | Registrar funciones biológicas                                | 5            |
| 12      | US15          | Registrar estado de salud diario (móvil)                      | 5            |
| 13      | US16          | Consultar lista de medicamentos (móvil)                       | 5            |
| 14      | US23          | Editar información del paciente                               | 5            |
| 15      | US26          | Visualizar tareas del paciente (profesional)                  | 5            |
| 16      | US30          | Marcar tarea como completada                                  | 5            |
| 17      | US32          | Crear cita médica (móvil)                                     | 5            |
| 18      | US36          | Registrar medicamento del paciente (móvil)                    | 5            |
| 19      | US05          | Visualizar el estado actual de ánimo del paciente             | 3            |
| 20      | US08          | Registrar medicamentos del paciente                           | 3            |
| 21      | US09          | Ver medicamentos                                              | 3            |
| 22      | US17          | Ver próximas citas (móvil)                                    | 3            |
| 23      | US26          | Visualizar tareas del paciente (profesional)                  | 3            |
| 24      | US28          | Eliminar tarea                                                | 3            |
| 25      | US33          | Ver citas médicas (profesional móvil)                         | 3            |
| 26      | US34          | Editar cita médica                                            | 3            |
| 27      | US37          | Ver medicamentos del paciente (profesional)                   | 3            |
| 28      | US38          | Editar medicamento del paciente                               | 3            |
| 29      | US40          | Ver medicamentos asignados (paciente)                         | 3            |
| 30      | US24          | Eliminar paciente                                             | 3            |
| 31      | US27          | Editar tarea asignada                                         | 3            |
| 32      | US31          | Desmarcar tarea completada                                    | 3            |
| 33      | US35          | Eliminar cita médica                                          | 3            |
| 34      | US13          | Visualizar información de perfil (móvil)                      | 3            |
| 35      | US10          | Crear citas                                                   | 2            |
| 36      | US11          | Ver citas médicas                                             | 2            |
| 37      | US14          | Cerrar sesión (móvil)                                         | 2            |
| 38      | US18          | Informarse sobre el propósito de la aplicación (Landing Page) | 1            |
| 39      | US19          | Visualizar imágenes y gráficos relevantes (Landing Page)      | 1            |
| 40      | US20          | Visualizar tipografía cómoda y estética (Landing Page)        | 1            |


## 2.5. Strategic-Level Domain-Driven Design

El diseño estratégico de dominio permite identificar y delimitar los contextos acotados del sistema mediante técnicas colaborativas como EventStorming, establecer las relaciones entre contextos mediante Context Mapping, y definir la arquitectura de software a nivel estratégico utilizando diagramas C4.

### 2.5.1. EventStorming

EventStorming es una técnica colaborativa utilizada para descubrir el dominio del problema mediante la identificación de eventos de dominio, comandos, agregados y actores. Esta técnica permite visualizar el flujo de eventos en el sistema y establecer los límites naturales entre contextos acotados.

#### 2.5.1.1. Candidate Context Discovery

Mediante el análisis de eventos y agregados identificados en el EventStorming, se propusieron seis contextos acotados candidatos que agrupan conceptos del dominio relacionados: IAM (Identity and Access Management), Profiles, Clinical History, Appointment and Administration, Medication, y Patient Report. La agrupación se realizó considerando la cohesión funcional y las responsabilidades de cada contexto.

![WhatsApp Image 2025-11-14 at 5 52 24 AM](https://github.com/user-attachments/assets/4679543a-934e-4805-a19e-854516ce7721)

#### 2.5.1.2. Domain Message Flows Modeling

Los flujos de mensajes del dominio modelan la interacción entre contextos acotados mediante comandos, consultas y eventos. Estos diagramas documentan escenarios clave como la creación de perfiles de paciente, sesiones, asignación de tareas, registro de estados emocionales y asignación de medicamentos, mostrando la comunicación síncrona e asíncrona entre contextos.

![WhatsApp Image 2025-11-14 at 5 34 53 AM](https://github.com/user-attachments/assets/89107fdb-7bbb-4485-a317-794eabe6df1c)

![WhatsApp Image 2025-11-14 at 5 35 05 AM](https://github.com/user-attachments/assets/113788bf-5226-4ec4-8f93-d14ac1e9048e)

![WhatsApp Image 2025-11-14 at 5 38 20 AM](https://github.com/user-attachments/assets/c909c632-47b9-4f80-a515-73cd2659ec31)

![WhatsApp Image 2025-11-14 at 5 41 48 AM](https://github.com/user-attachments/assets/2df6eb69-3461-4dee-ab79-0223532c8fd4)

![WhatsApp Image 2025-11-14 at 5 44 14 AM (1)](https://github.com/user-attachments/assets/32be9e36-cfbb-421e-b02a-c392097f4cbc)


#### 2.5.1.3. Bounded Context Canvases

El Bounded Context Canvas documenta para cada contexto acotado su propósito, estrategia de clasificación, roles del dominio, lenguaje ubicuo, decisiones de negocio, comunicación entrante y saliente, supuestos y métricas de verificación. Estos canvas proporcionan una visión completa de las responsabilidades y relaciones de cada contexto.

![WhatsApp Image 2025-11-14 at 4 48 29 AM (1)](https://github.com/user-attachments/assets/e923843b-c342-4c2d-9171-4cf99b009151)

![WhatsApp Image 2025-11-14 at 5 05 17 AM](https://github.com/user-attachments/assets/9521c934-4d4a-4aeb-bcf0-8b29eac9778d)

![WhatsApp Image 2025-11-14 at 5 09 14 AM](https://github.com/user-attachments/assets/36e3b375-baf0-4dc9-8995-a0a6bf719ae8)

![WhatsApp Image 2025-11-14 at 5 20 00 AM](https://github.com/user-attachments/assets/7a988327-cb40-43c4-af15-54cf5e092e16)

![WhatsApp Image 2025-11-14 at 5 55 54 AM](https://github.com/user-attachments/assets/9c5fbfb9-0e79-49c8-b359-715bd6b9d0e8)

### 2.5.2. Context Mapping

El Context Mapping establece las relaciones entre los contextos acotados identificados. En este sistema, los contextos mantienen relaciones de colaboración y uso mediante comunicaciones síncronas (queries) y asíncronas (eventos). El contexto Profiles actúa como orquestador principal, coordinando la creación de recursos en IAM y Clinical History cuando se crea un perfil de paciente. Los contextos Appointment, Medication y Patient Report dependen de Profiles para validar la existencia de perfiles antes de realizar operaciones.

### 2.5.3. Software Architecture

La arquitectura de software del sistema se documenta utilizando la metodología C4, que proporciona diferentes niveles de abstracción: Context Level para visualizar el sistema en su entorno, Container Level para mostrar los componentes principales de despliegue, y Deployment Level para representar la infraestructura física de despliegue.

#### 2.5.3.1. Software Architecture Context Level Diagrams

El diagrama de contexto C4 muestra el sistema PSYMED y sus interacciones con actores externos (pacientes y profesionales), sistemas externos (bases de datos) y usuarios del sistema. Este diagrama proporciona una visión de alto nivel del sistema como una caja negra y su entorno operativo.

![WhatsApp Image 2025-11-13 at 10 23 47 PM](https://github.com/user-attachments/assets/a9bd679b-41b9-4783-84dd-aefb0c676868)


#### 2.5.3.2. Software Architecture Container Level Diagrams

El diagrama de contenedores C4 descompone el sistema en sus componentes principales de despliegue: aplicaciones móviles (Flutter y Android nativo), aplicación web Angular, backend Spring Boot, y base de datos PostgreSQL. Este nivel muestra las tecnologías utilizadas y las interacciones entre contenedores mediante protocolos y APIs.

![WhatsApp Image 2025-11-13 at 10 28 30 PM](https://github.com/user-attachments/assets/3c184514-5b6a-4a25-952d-ad5228386e5f)


#### 2.5.3.3. Software Architecture Deployment Diagrams

El diagrama de despliegue muestra la infraestructura física y virtual donde se despliega el sistema. El backend Spring Boot se despliega en Render como servicio web, utilizando Docker Hub para almacenar imágenes de contenedor. La base de datos PostgreSQL se aloja en Neon como base de datos serverless. Las aplicaciones móviles se despliegan en dispositivos Android e iOS de los usuarios.

![WhatsApp Image 2025-11-14 at 5 48 30 AM](https://github.com/user-attachments/assets/4a9c8ebe-820a-40d5-9b9d-aa66034eb3d2)

## 2.6. Tactical-Level Domain-Driven Design

## 2.6.1. Bounded Context: IAM (Identity and Access Management)

### 2.6.1.1. Domain Layer

#### Aggregates

##### Account
- **Propósito**: Representa una cuenta de usuario en el sistema. Es el agregado raíz del contexto IAM que encapsula la información de autenticación y autorización de un usuario.

**Atributos:**
- `userName` (String): Nombre de usuario único en el sistema. Validación: @NotBlank, @Size(max=20), @Column(unique = true)
- `password` (String): Contraseña del usuario. Validación: @NotBlank
- `role` (Roles): Rol del usuario en el sistema. Validación: @Enumerated(EnumType.STRING), @Column(length = 20, nullable = false)
- `profileId` (ProfileId): Identificador del perfil asociado. Tipo: Value Object embebido
- `id` (Long): Identificador único del agregado. Heredado de AuditableAbstractAggregateRoot
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `Account(SignUpCommand command)`: Constructor que crea una cuenta desde un comando de registro. Valida que el rol sea ROLE_PROFESSIONAL o ROLE_PATIENT
- `Account(SignUpCommand command, String hashedPassword)`: Constructor que crea una cuenta con contraseña ya hasheada
- `getRoleInString()`: Retorna el rol como String
- `getAllRoles()`: Retorna un Set con todos los roles disponibles

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<Account>` para obtener funcionalidades de auditoría
- Tiene una relación con `ProfileId` (Value Object embebido)
- Se relaciona con el enum `Roles` para definir el rol del usuario

#### Value Objects

##### Roles
- **Propósito**: Define los roles disponibles en el sistema.

**Valores:**
- `ROLE_PROFESSIONAL`: Rol para profesionales de la salud
- `ROLE_PATIENT`: Rol para pacientes

**Atributos:** Ninguno (enum)

**Métodos:** Ninguno (enum estándar)

##### ProfileId
- **Propósito**: Representa el identificador de un perfil de forma encapsulada.

**Atributos:**
- `profileId` (Long): Identificador del perfil

**Validaciones:**
- No puede ser null

**Métodos:**
- Constructor con validación de no nulidad

#### Commands

##### SignUpCommand
- **Propósito**: Comando para registrar un nuevo usuario en el sistema.

**Atributos:**
- `username` (String): Nombre de usuario
- `password` (String): Contraseña del usuario
- `role` (String): Rol del usuario (ROLE_PROFESSIONAL o ROLE_PATIENT)

##### SignInCommand
- **Propósito**: Comando para autenticar un usuario existente.

**Atributos:**
- `username` (String): Nombre de usuario
- `password` (String): Contraseña del usuario

##### SeedRolesCommand
- **Propósito**: Comando para inicializar roles en el sistema.

#### Queries

##### GetAccountByIdQuery
- **Propósito**: Consulta para obtener una cuenta por su identificador.

**Atributos:**
- `accountId` (Long): Identificador de la cuenta

#### Domain Services

##### AccountCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de cuentas.

**Métodos:**
- `handle(SignUpCommand command)`: Retorna `Optional<Account>`. Procesa el comando de registro de usuario
- `handle(SignInCommand command)`: Retorna `Optional<ImmutablePair<Account, String>>`. Procesa el comando de inicio de sesión y retorna la cuenta con su token

##### AccountQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de cuentas.

**Métodos:**
- `handle(GetAccountByIdQuery query)`: Retorna `Optional<Account>`. Obtiene una cuenta por su identificador

---

### 2.6.1.2. Interface Layer

#### Controllers

##### AuthenticationController
- **Propósito**: Controlador REST que maneja las operaciones de autenticación de usuarios.

**Endpoints:**
- `POST /api/v1/authentication/sign-in`: Autentica un usuario y retorna su cuenta con token JWT
    - Request Body: `SignInResource`
    - Response: `AuthenticatedAccountResource` (200 OK) o 404 Not Found
- `POST /api/v1/authentication/sign-up`: Registra un nuevo usuario en el sistema
    - Request Body: `SignUpResource`
    - Response: `AccountResource` (201 Created) o 400 Bad Request

**Dependencias:**
- `AccountCommandService`: Para procesar los comandos de autenticación

##### AccountsController
- **Propósito**: Controlador REST que maneja las operaciones de consulta de cuentas.

**Endpoints:**
- `GET /api/v1/accounts/{accountId}`: Obtiene una cuenta por su identificador
    - Path Variable: `accountId` (Long)
    - Response: `AccountResource` (200 OK) o 404 Not Found

**Dependencias:**
- `AccountQueryService`: Para procesar las consultas de cuentas

---

### 2.6.1.3. Application Layer

#### Command Handlers

##### AccountCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de cuenta. Maneja la lógica de registro e inicio de sesión.

**Dependencias:**
- `AccountRepository`: Para acceder a la persistencia de cuentas
- `HashingService`: Para el hashing de contraseñas
- `TokenService`: Para la generación de tokens JWT

**Métodos:**
- `handle(SignUpCommand command)`:
    - Valida que el usuario no exista
    - Hashea la contraseña
    - Crea y persiste la cuenta
    - Retorna `Optional<Account>`
- `handle(SignInCommand command)`:
    - Verifica que el usuario exista
    - Genera un token JWT
    - Retorna `Optional<ImmutablePair<Account, String>>`

#### Query Handlers

##### AccountQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de cuenta. Maneja la lógica de consulta de cuentas.

**Dependencias:**
- `AccountRepository`: Para acceder a la persistencia de cuentas

**Métodos:**
- `handle(GetAccountByIdQuery query)`: Obtiene una cuenta por su identificador usando el repositorio

---

### 2.6.1.4. Infrastructure Layer

#### Repositories

##### AccountRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de cuentas.

**Extiende:** `JpaRepository<Account, Long>`

**Métodos personalizados:**
- `existsByUserName(String username)`: Verifica si existe una cuenta con el nombre de usuario dado
- `findByUserName(String username)`: Busca una cuenta por su nombre de usuario

#### External Services

##### BCryptHashingService
- **Propósito**: Implementación del servicio de hashing de contraseñas usando BCrypt.

**Métodos:**
- `encode(String password)`: Hashea una contraseña usando BCrypt

##### TokenServiceImpl / BearerTokenService
- **Propósito**: Implementación del servicio de generación y validación de tokens JWT.

**Métodos:**
- `generateToken(String username)`: Genera un token JWT para el usuario dado
- `validateToken(String token)`: Valida un token JWT

##### WebSecurityConfiguration
- **Propósito**: Configuración de seguridad de Spring Security.

**Componentes:**
- `BearerAuthorizationRequestFilter`: Filtro que intercepta las peticiones y valida tokens JWT
- `UnauthorizedRequestHandlerEntryPoint`: Maneja las peticiones no autorizadas
- `UserDetailsServiceImpl`: Servicio para cargar detalles de usuario para Spring Security

---

### 2.6.1.5. Bounded Context Software Architecture Component Level Diagrams

![WhatsApp Image 2025-11-13 at 10 46 47 PM](https://github.com/user-attachments/assets/0c3e4d4f-506d-4a03-9e7e-8ad11d82b556)

### 2.6.1.6. Bounded Context Software Architecture Code Level Diagrams

#### 2.6.1.6.1. Bounded Context Domain Layer Class Diagrams

![WhatsApp Image 2025-11-14 at 3 14 38 AM](https://github.com/user-attachments/assets/6a2981c3-903c-45bf-b8db-2d325e57c34a)

#### 2.6.1.6.2. Bounded Context Database Design Diagram

![clases](https://github.com/user-attachments/assets/080e4bc0-4e8e-4df7-9940-f8af1e476d02)

![WhatsApp Image 2025-11-14 at 3 17 02 AM](https://github.com/user-attachments/assets/60c4d5b1-1d88-4d67-a6a1-be37e66fa3fe)

---

## 2.6.2. Bounded Context: Profiles

### 2.6.2.1. Domain Layer

#### Aggregates

##### PatientProfile
- **Propósito**: Representa el perfil de un paciente en el sistema. Es el agregado raíz para la gestión de información personal de pacientes.

**Atributos:**
- `personName` (PersonName): Nombre completo del paciente (Value Object embebido)
- `streetAddress` (StreetAddress): Dirección del paciente (Value Object embebido con mapeo personalizado)
- `email` (Email): Correo electrónico del paciente (Value Object embebido)
- `accountId` (AccountId): Identificador de la cuenta asociada (Value Object embebido)
- `professionalId` (Long): Identificador del profesional asignado
- `clinicalHistoryId` (ClinicalHistoryId): Identificador de la historia clínica asociada (Value Object embebido)
- `id` (Long): Identificador único. Heredado de AuditableAbstractAggregateRoot
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `PatientProfile(String firstName, String lastName, String street, String city, String country, String email)`: Constructor que crea un perfil de paciente desde valores primitivos
- `PatientProfile(CreatePatientProfileCommand command, AccountId accountId)`: Constructor que crea un perfil desde un comando
- `addClinicalHistory(Long id)`: Asocia una historia clínica al perfil
- `updateEmail(String email)`: Actualiza el correo electrónico del paciente
- `updateName(String firstName, String lastName)`: Actualiza el nombre del paciente
- `updateAddress(String street, String city, String country)`: Actualiza la dirección del paciente
- `getFullName()`: Retorna el nombre completo del paciente
- `getStreetAddress()`: Retorna la dirección completa como String
- `getEmail()`: Retorna el correo electrónico
- `getAccountId()`: Retorna el identificador de la cuenta
- `getProfessionalId()`: Retorna el identificador del profesional

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<PatientProfile>` para auditoría
- Tiene relación con `AccountId` (Value Object)
- Tiene relación con `ClinicalHistoryId` (Value Object)
- Se relaciona con múltiples Value Objects: `PersonName`, `StreetAddress`, `Email`

##### ProfessionalProfile
- **Propósito**: Representa el perfil de un profesional de la salud en el sistema. Es el agregado raíz para la gestión de información personal de profesionales.

**Atributos:**
- `personName` (PersonName): Nombre completo del profesional (Value Object embebido)
- `email` (Email): Correo electrónico del profesional (Value Object embebido)
- `accountId` (AccountId): Identificador de la cuenta asociada (Value Object embebido)
- `streetAddress` (StreetAddress): Dirección del profesional (Value Object embebido con mapeo personalizado)
- `id` (Long): Identificador único. Heredado de AuditableAbstractAggregateRoot
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `ProfessionalProfile(String firstName, String lastName, String street, String city, String country, String email)`: Constructor que crea un perfil de profesional desde valores primitivos
- `ProfessionalProfile(CreateProfessionalProfileCommand command, AccountId accountId)`: Constructor que crea un perfil desde un comando
- `updatePersonName(String firstName, String lastName)`: Actualiza el nombre del profesional
- `updateStreetAddress(String street, String city, String country)`: Actualiza la dirección del profesional
- `getFullName()`: Retorna el nombre completo del profesional
- `getStreetAddress()`: Retorna la dirección completa como String
- `getEmail()`: Retorna el correo electrónico
- `getAccountId()`: Retorna el identificador de la cuenta

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<ProfessionalProfile>` para auditoría
- Tiene relación con `AccountId` (Value Object)
- Se relaciona con múltiples Value Objects: `PersonName`, `StreetAddress`, `Email`

#### Value Objects

##### PersonName
- **Propósito**: Representa el nombre completo de una persona de forma encapsulada.

**Atributos:**
- `firstName` (String): Primer nombre. Validación: No puede ser null o vacío
- `lastName` (String): Apellido. Validación: No puede ser null o vacío

**Métodos:**
- `getFullName()`: Retorna el nombre completo en formato "firstName lastName"

##### Email
- **Propósito**: Representa una dirección de correo electrónico con validación.

**Atributos:**
- `email` (String): Dirección de correo electrónico

**Validaciones:**
- No puede ser null o vacío
- Debe cumplir con el formato de email válido (regex: `^[a-zA-Z0-9+_.-]+@[a-zA-Z0-9.-]+$`)

##### StreetAddress
- **Propósito**: Representa una dirección física completa.

**Atributos:**
- `street` (String): Calle y número
- `city` (String): Ciudad
- `country` (String): País

##### AccountId
- **Propósito**: Representa el identificador de una cuenta de forma encapsulada.

**Atributos:**
- `accountId` (Long): Identificador de la cuenta

##### ClinicalHistoryId
- **Propósito**: Representa el identificador de una historia clínica de forma encapsulada.

**Atributos:**
- `clinicalHistoryId` (Long): Identificador de la historia clínica

#### Commands

##### CreatePatientProfileCommand
- **Propósito**: Comando para crear un nuevo perfil de paciente.

**Atributos:**
- `firstName` (String): Primer nombre
- `lastName` (String): Apellido
- `street` (String): Calle
- `city` (String): Ciudad
- `country` (String): País
- `email` (String): Correo electrónico
- `username` (String): Nombre de usuario
- `password` (String): Contraseña
- `professionalId` (Long): Identificador del profesional asignado

##### UpdatePatientProfileCommand
- **Propósito**: Comando para actualizar un perfil de paciente existente.

**Atributos:**
- `profileId` (Long): Identificador del perfil
- `firstName` (String): Primer nombre (opcional)
- `lastName` (String): Apellido (opcional)
- `email` (String): Correo electrónico (opcional)
- `street` (String): Calle (opcional)
- `city` (String): Ciudad (opcional)
- `country` (String): País (opcional)

##### DeletePatientProfileCommand
- **Propósito**: Comando para eliminar un perfil de paciente.

**Atributos:**
- `profileId` (Long): Identificador del perfil a eliminar

##### CreateProfessionalProfileCommand
- **Propósito**: Comando para crear un nuevo perfil de profesional.

**Atributos:**
- `firstName` (String): Primer nombre
- `lastName` (String): Apellido
- `street` (String): Calle
- `city` (String): Ciudad
- `country` (String): País
- `email` (String): Correo electrónico
- `username` (String): Nombre de usuario
- `password` (String): Contraseña

##### UpdateProfessionalProfileCommand
- **Propósito**: Comando para actualizar un perfil de profesional existente.

**Atributos:**
- `profileId` (Long): Identificador del perfil
- `firstName` (String): Primer nombre (opcional)
- `lastName` (String): Apellido (opcional)
- `email` (String): Correo electrónico (opcional)
- `street` (String): Calle (opcional)
- `city` (String): Ciudad (opcional)
- `country` (String): País (opcional)

##### DeleteProfessionalProfileCommand
- **Propósito**: Comando para eliminar un perfil de profesional.

**Atributos:**
- `profileId` (Long): Identificador del perfil a eliminar

#### Queries

##### GetPatientProfileByIdQuery
- **Propósito**: Consulta para obtener un perfil de paciente por su identificador.

**Atributos:**
- `profileId` (Long): Identificador del perfil

##### GetPatientProfileByAccountIdQuery
- **Propósito**: Consulta para obtener un perfil de paciente por el identificador de su cuenta.

**Atributos:**
- `accountId` (AccountId): Identificador de la cuenta

##### GetPatientProfileByProfessionalIdQuery
- **Propósito**: Consulta para obtener todos los perfiles de pacientes asignados a un profesional.

**Atributos:**
- `professionalId` (Long): Identificador del profesional

##### GetAllPatientProfilesQuery
- **Propósito**: Consulta para obtener todos los perfiles de pacientes del sistema.

**Atributos:** Ninguno

##### GetProfessionalProfileByIdQuery
- **Propósito**: Consulta para obtener un perfil de profesional por su identificador.

**Atributos:**
- `profileId` (Long): Identificador del perfil

##### GetProfessionalProfileByAccountIdQuery
- **Propósito**: Consulta para obtener un perfil de profesional por el identificador de su cuenta.

**Atributos:**
- `accountId` (AccountId): Identificador de la cuenta

#### Domain Services

##### PatientProfileCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de perfiles de pacientes.

**Métodos:**
- `handle(CreatePatientProfileCommand command)`: Retorna `Optional<PatientProfile>`. Crea un nuevo perfil de paciente
- `handle(UpdatePatientProfileCommand command)`: Retorna `Optional<PatientProfile>`. Actualiza un perfil de paciente existente
- `handle(DeletePatientProfileCommand command)`: Elimina un perfil de paciente

##### PatientProfileQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de perfiles de pacientes.

**Métodos:**
- `handle(GetPatientProfileByIdQuery query)`: Retorna `Optional<PatientProfile>`. Obtiene un perfil por su identificador
- `handle(GetPatientProfileByAccountIdQuery query)`: Retorna `Optional<PatientProfile>`. Obtiene un perfil por el identificador de cuenta
- `handle(GetPatientProfileByProfessionalIdQuery query)`: Retorna `List<PatientProfile>`. Obtiene todos los perfiles de un profesional
- `handle(GetAllPatientProfilesQuery query)`: Retorna `List<PatientProfile>`. Obtiene todos los perfiles de pacientes

##### ProfessionalProfileCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de perfiles de profesionales.

**Métodos:**
- `handle(CreateProfessionalProfileCommand command)`: Retorna `Optional<ProfessionalProfile>`. Crea un nuevo perfil de profesional
- `handle(UpdateProfessionalProfileCommand command)`: Retorna `Optional<ProfessionalProfile>`. Actualiza un perfil de profesional existente
- `handle(DeleteProfessionalProfileCommand command)`: Elimina un perfil de profesional

##### ProfessionalProfileQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de perfiles de profesionales.

**Métodos:**
- `handle(GetProfessionalProfileByIdQuery query)`: Retorna `Optional<ProfessionalProfile>`. Obtiene un perfil por su identificador
- `handle(GetProfessionalProfileByAccountIdQuery query)`: Retorna `Optional<ProfessionalProfile>`. Obtiene un perfil por el identificador de cuenta

---

### 2.6.2.2. Interface Layer

#### Controllers

##### PatientProfileController
- **Propósito**: Controlador REST que maneja las operaciones de gestión de perfiles de pacientes.

**Endpoints:**
- `POST /api/v1/patient-profiles`: Crea un nuevo perfil de paciente
    - Request Body: `CreatePatientProfileResource`
    - Response: `ProfileResource` (201 Created) o 400 Bad Request
- `GET /api/v1/patient-profiles/{profileId}`: Obtiene un perfil por su identificador
    - Path Variable: `profileId` (Long)
    - Response: `ProfileResource` (200 OK) o 404 Not Found
- `GET /api/v1/patient-profiles/account/{accountId}`: Obtiene un perfil por el identificador de cuenta
    - Path Variable: `accountId` (Long)
    - Response: `ProfileResource` (200 OK) o 404 Not Found
- `GET /api/v1/patient-profiles/professional/{professionalId}`: Obtiene todos los perfiles asignados a un profesional
    - Path Variable: `professionalId` (Long)
    - Response: `List<ProfileResource>` (200 OK) o 404 Not Found
- `GET /api/v1/patient-profiles`: Obtiene todos los perfiles de pacientes
    - Response: `List<ProfileResource>` (200 OK)
- `PUT /api/v1/patient-profiles/{profileId}`: Actualiza un perfil de paciente
    - Path Variable: `profileId` (Long)
    - Request Body: `UpdatePatientProfileResource`
    - Response: `ProfileResource` (200 OK) o 400 Bad Request
- `DELETE /api/v1/patient-profiles/{profileId}`: Elimina un perfil de paciente
    - Path Variable: `profileId` (Long)
    - Response: 204 No Content

**Dependencias:**
- `PatientProfileCommandService`: Para procesar comandos
- `PatientProfileQueryService`: Para procesar consultas

##### ProfessionalProfileController
- **Propósito**: Controlador REST que maneja las operaciones de gestión de perfiles de profesionales.

**Endpoints:**
- `POST /api/v1/professional-profiles`: Crea un nuevo perfil de profesional
    - Request Body: `CreateProfessionalProfileResource`
    - Response: `ProfileResource` (201 Created) o 400 Bad Request
- `GET /api/v1/professional-profiles/{profileId}`: Obtiene un perfil por su identificador
    - Path Variable: `profileId` (Long)
    - Response: `ProfileResource` (200 OK) o 404 Not Found
- `GET /api/v1/professional-profiles/account/{accountId}`: Obtiene un perfil por el identificador de cuenta
    - Path Variable: `accountId` (Long)
    - Response: `ProfileResource` (200 OK) o 404 Not Found

**Dependencias:**
- `ProfessionalProfileCommandService`: Para procesar comandos
- `ProfessionalProfileQueryService`: Para procesar consultas

##### PatientClinicalHistoryController
- **Propósito**: Controlador REST que maneja las consultas relacionadas con historias clínicas de pacientes.

**Endpoints:**
- `GET /api/v1/patient-profiles/{patientId}/clinical-histories`: Obtiene la historia clínica de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `ClinicalHistoryResource` (200 OK) o 404 Not Found

**Dependencias:**
- `ClinicalHistoryQueryService`: Para procesar consultas de historias clínicas

#### ACL (Application Context Layer)

##### ProfilesContextFacade (Interface)
- **Propósito**: Facade que permite a otros bounded contexts interactuar con el contexto de Profiles.

**Métodos:**
- `verifyPatientProfile(Long patientId)`: Verifica si existe un perfil de paciente
- `verifyProfessionalProfile(Long professionalId)`: Verifica si existe un perfil de profesional
- `fetchClinicalHistoryIdByPatientId(Long patientId)`: Obtiene el identificador de historia clínica de un paciente

---

### 2.6.2.3. Application Layer

#### Command Handlers

##### PatientProfileCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de perfil de paciente. Maneja la lógica de creación, actualización y eliminación de perfiles de pacientes.

**Dependencias:**
- `PatientProfileRepository`: Para acceder a la persistencia
- `ExternalAccountService`: Para crear cuentas en el contexto IAM
- `ExternalClinicalHistoryService`: Para crear historias clínicas
- `ProfilesContextFacade`: Para validaciones internas

**Métodos:**
- `handle(CreatePatientProfileCommand command)`:
    - Crea una cuenta en el contexto IAM
    - Crea una historia clínica
    - Crea y persiste el perfil de paciente
    - Asocia la historia clínica al perfil
    - Retorna `Optional<PatientProfile>`
- `handle(UpdatePatientProfileCommand command)`: Actualiza un perfil existente
- `handle(DeletePatientProfileCommand command)`: Elimina un perfil

##### ProfessionalProfileCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de perfil de profesional. Maneja la lógica de creación, actualización y eliminación de perfiles de profesionales.

**Dependencias:**
- `ProfessionalProfileRepository`: Para acceder a la persistencia
- `ExternalAccountService`: Para crear cuentas en el contexto IAM

**Métodos:**
- `handle(CreateProfessionalProfileCommand command)`: Crea un nuevo perfil de profesional
- `handle(UpdateProfessionalProfileCommand command)`: Actualiza un perfil existente
- `handle(DeleteProfessionalProfileCommand command)`: Elimina un perfil

#### Query Handlers

##### PatientProfileQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de perfil de paciente.

**Dependencias:**
- `PatientProfileRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetPatientProfileByIdQuery query)`: Obtiene un perfil por ID
- `handle(GetPatientProfileByAccountIdQuery query)`: Obtiene un perfil por AccountId
- `handle(GetPatientProfileByProfessionalIdQuery query)`: Obtiene todos los perfiles de un profesional
- `handle(GetAllPatientProfilesQuery query)`: Obtiene todos los perfiles

##### ProfessionalProfileQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de perfil de profesional.

**Dependencias:**
- `ProfessionalProfileRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetProfessionalProfileByIdQuery query)`: Obtiene un perfil por ID
- `handle(GetProfessionalProfileByAccountIdQuery query)`: Obtiene un perfil por AccountId

#### Outbound Services

##### ExternalAccountService
- **Propósito**: Servicio para interactuar con el contexto IAM para crear cuentas.

**Métodos:**
- `createAccount(String username, String password, String role)`: Crea una cuenta en el contexto IAM

##### ExternalClinicalHistoryService
- **Propósito**: Servicio para interactuar con el contexto Clinical History para crear historias clínicas.

**Métodos:**
- `createClinicalHistory(String background, String consultationReason, LocalDate consultationDate)`: Crea una historia clínica

---

### 2.6.2.4. Infrastructure Layer

#### Repositories

##### PatientProfileRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de perfiles de pacientes.

**Extiende:** `JpaRepository<PatientProfile, Long>`

**Métodos personalizados:**
- `existsByEmail(Email emailAddress)`: Verifica si existe un perfil con el email dado
- `findByEmail(Email email)`: Busca un perfil por email
- `findByAccountId(AccountId accountId)`: Busca un perfil por AccountId
- `findClinicalHistoryIdById(Long patientId)`: Obtiene el ID de historia clínica de un paciente
- `findByProfessionalId(Long professionalId)`: Busca todos los perfiles de un profesional

##### ProfessionalProfileRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de perfiles de profesionales.

**Extiende:** `JpaRepository<ProfessionalProfile, Long>`

**Métodos personalizados:**
- `existsByEmail(Email emailAddress)`: Verifica si existe un perfil con el email dado
- `findByEmail(Email email)`: Busca un perfil por email
- `findByAccountId(AccountId accountId)`: Busca un perfil por AccountId

---

### 2.6.2.5. Bounded Context Software Architecture Component Level Diagrams

![WhatsApp Image 2025-11-13 at 10 43 24 PM](https://github.com/user-attachments/assets/c41fa460-2e56-47df-bac7-a4846bfde65f)

### 2.6.2.6. Bounded Context Software Architecture Code Level Diagrams

#### 2.6.2.6.1. Bounded Context Domain Layer Class Diagrams

![WhatsApp Image 2025-11-14 at 3 14 38 AM](https://github.com/user-attachments/assets/ff6ff023-e32a-47d1-ab82-d2e8d7fbf84b)

#### 2.6.2.6.2. Bounded Context Database Design Diagram

![WhatsApp Image 2025-11-14 at 3 19 05 AM](https://github.com/user-attachments/assets/055359c0-18ef-4ccc-a1b7-64b94eacd404)


---

## 2.6.3. Bounded Context: Appointment and Administration

### 2.6.3.1. Domain Layer

#### Aggregates

##### Session
- **Propósito**: Representa una sesión de atención entre un paciente y un profesional. Es el agregado raíz que encapsula la gestión de citas, notas y tareas.

**Atributos:**
- `id` (Long): Identificador único de la sesión
- `patientId` (PatientId): Identificador del paciente (Value Object embebido)
- `professionalId` (ProfessionalId): Identificador del profesional (Value Object embebido)
- `appointmentDate` (AppointmentDate): Fecha de la cita (Value Object embebido)
- `sessionTime` (SessionTime): Duración de la sesión en horas (Value Object embebido)
- `note` (Note): Nota asociada a la sesión (Entity, relación OneToOne)
- `tasks` (List<Task>): Lista de tareas asociadas a la sesión (Entity, relación OneToMany)
- `createdAt` (Date): Fecha de creación
- `updatedAt` (Date): Fecha de última actualización

**Métodos:**
- `Session(CreateSessionCommand command)`: Constructor que crea una sesión desde un comando
- `addNoteToSession(String title, String description)`: Agrega una nota a la sesión
- `addTaskToSession(String title, String description)`: Agrega una tarea a la sesión
- `getLastTask()`: Obtiene la última tarea agregada. Lanza excepción si no hay tareas
- `getTaskById(Long taskId)`: Obtiene una tarea por su identificador. Lanza excepción si no existe
- `updateTask(Long taskId, String title, String description)`: Actualiza una tarea existente
- `deleteTask(Long taskId)`: Elimina una tarea de la sesión
- `deleteNote()`: Elimina la nota de la sesión
- `reschedule(Date newAppointmentDate, double newSessionTime)`: Reprograma la sesión con nueva fecha y duración

**Relaciones:**
- Tiene una relación OneToOne con `Note`
- Tiene una relación OneToMany con `Task`
- Usa múltiples Value Objects: `PatientId`, `ProfessionalId`, `AppointmentDate`, `SessionTime`

#### Entities

##### Task
- **Propósito**: Representa una tarea asignada a un paciente dentro de una sesión.

**Atributos:**
- `id` (Long): Identificador único de la tarea
- `title` (String): Título de la tarea
- `description` (String): Descripción de la tarea
- `status` (TaskStatus): Estado de la tarea (Value Object embebido: INCOMPLETE=0, COMPLETE=1)
- `session` (Session): Sesión a la que pertenece la tarea (relación ManyToOne)
- `createdAt` (Date): Fecha de creación. Heredado de AuditableModel
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableModel

**Métodos:**
- `Task(Session session, String title, String description)`: Constructor que crea una tarea asociada a una sesión
- `completeTask()`: Marca la tarea como completada
- `incompleteTask()`: Marca la tarea como incompleta
- `updateTask(String title, String description)`: Actualiza el título y/o descripción de la tarea

**Relaciones:**
- Extiende de `AuditableModel` para auditoría
- Tiene una relación ManyToOne con `Session`
- Usa el Value Object `TaskStatus`

##### Note
- **Propósito**: Representa una nota privada asociada a una sesión, visible solo para el profesional.

**Atributos:**
- `id` (Long): Identificador único de la nota
- `title` (String): Título de la nota. Validación: @NotNull
- `description` (String): Descripción o contenido de la nota. Validación: @NotNull
- `createdAt` (Date): Fecha de creación. Heredado de AuditableModel
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableModel

**Métodos:**
- `Note(String title, String description)`: Constructor que crea una nota
- `updateNote(String title, String description)`: Actualiza el título y/o descripción de la nota

**Relaciones:**
- Extiende de `AuditableModel` para auditoría
- Tiene una relación OneToOne con `Session` (desde la perspectiva de Session)

#### Value Objects

##### PatientId
- **Propósito**: Representa el identificador de un paciente de forma encapsulada.

**Atributos:**
- `patientId` (Long): Identificador del paciente

##### ProfessionalId
- **Propósito**: Representa el identificador de un profesional de forma encapsulada.

**Atributos:**
- `professionalId` (Long): Identificador del profesional

##### AppointmentDate
- **Propósito**: Representa la fecha de una cita con validaciones.

**Atributos:**
- `appointmentDate` (Date): Fecha de la cita

##### SessionTime
- **Propósito**: Representa la duración de una sesión en horas.

**Atributos:**
- `sessionTime` (double): Duración de la sesión en horas

##### TaskStatus
- **Propósito**: Representa el estado de una tarea.

**Valores:**
- `INCOMPLETE` (0): Tarea incompleta
- `COMPLETE` (1): Tarea completada

**Métodos:**
- `changeToCompleted()`: Cambia el estado a completado
- `changeToIncomplete()`: Cambia el estado a incompleto

#### Commands

##### CreateSessionCommand
- **Propósito**: Comando para crear una nueva sesión.

**Atributos:**
- `patientId` (Long): Identificador del paciente
- `professionalId` (Long): Identificador del profesional
- `appointmentDate` (Date): Fecha de la cita
- `sessionTime` (double): Duración de la sesión

##### UpdateSessionCommand
- **Propósito**: Comando para actualizar una sesión existente.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `patientId` (Long): Identificador del paciente
- `professionalId` (Long): Identificador del profesional
- `appointmentDate` (Date): Nueva fecha de la cita
- `sessionTime` (double): Nueva duración de la sesión

##### DeleteSessionCommand
- **Propósito**: Comando para eliminar una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `patientId` (Long): Identificador del paciente
- `professionalId` (Long): Identificador del profesional

##### CreateTaskCommand
- **Propósito**: Comando para crear una nueva tarea en una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `title` (String): Título de la tarea
- `description` (String): Descripción de la tarea

##### UpdateTaskCommand
- **Propósito**: Comando para actualizar una tarea existente.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `taskId` (Long): Identificador de la tarea
- `title` (String): Nuevo título
- `description` (String): Nueva descripción

##### DeleteTaskCommand
- **Propósito**: Comando para eliminar una tarea.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `taskId` (Long): Identificador de la tarea

##### UpdateTaskStatusToCompleteCommand
- **Propósito**: Comando para marcar una tarea como completada.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `taskId` (Long): Identificador de la tarea

##### UpdateTaskStatusToIncompleteCommand
- **Propósito**: Comando para marcar una tarea como incompleta.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `taskId` (Long): Identificador de la tarea

##### CreateNoteCommand
- **Propósito**: Comando para crear una nota en una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `title` (String): Título de la nota
- `description` (String): Descripción de la nota

##### UpdateNoteCommand
- **Propósito**: Comando para actualizar una nota existente.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `title` (String): Nuevo título
- `description` (String): Nueva descripción

##### DeleteNoteFromSessionCommand
- **Propósito**: Comando para eliminar una nota de una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión

#### Queries

##### GetAllSessionsByPatientIdQuery
- **Propósito**: Consulta para obtener todas las sesiones de un paciente.

**Atributos:**
- `patientId` (PatientId): Identificador del paciente

##### GetAllSessionsByProfessionalIdQuery
- **Propósito**: Consulta para obtener todas las sesiones de un profesional.

**Atributos:**
- `professionalId` (ProfessionalId): Identificador del profesional

##### GetSessionByIdQuery
- **Propósito**: Consulta para obtener una sesión por su identificador.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión
- `patientId` (Long): Identificador del paciente
- `professionalId` (Long): Identificador del profesional

##### GetAllTasksByPatientIdQuery
- **Propósito**: Consulta para obtener todas las tareas de un paciente.

**Atributos:**
- `patientId` (Long): Identificador del paciente

##### GetAllTasksBySessionIdQuery
- **Propósito**: Consulta para obtener todas las tareas de una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión

##### GetNoteBySessionIdQuery
- **Propósito**: Consulta para obtener la nota de una sesión.

**Atributos:**
- `sessionId` (Long): Identificador de la sesión

#### Domain Services

##### SessionCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de sesiones.

**Métodos:**
- `handle(CreateSessionCommand command)`: Retorna `Optional<Session>`. Crea una nueva sesión
- `handle(UpdateSessionCommand command)`: Retorna `Optional<Session>`. Actualiza una sesión existente
- `handle(DeleteSessionCommand command)`: Elimina una sesión
- `handle(CreateTaskCommand command)`: Retorna `Optional<Task>`. Crea una nueva tarea
- `handle(UpdateTaskCommand command)`: Retorna `Optional<Task>`. Actualiza una tarea
- `handle(DeleteTaskCommand command)`: Elimina una tarea
- `handle(UpdateTaskStatusToCompleteCommand command)`: Marca una tarea como completada
- `handle(UpdateTaskStatusToIncompleteCommand command)`: Marca una tarea como incompleta
- `handle(CreateNoteCommand command)`: Retorna `Optional<Note>`. Crea una nueva nota
- `handle(UpdateNoteCommand command)`: Retorna `Optional<Note>`. Actualiza una nota
- `handle(DeleteNoteFromSessionCommand command)`: Elimina una nota

##### SessionQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de sesiones.

**Métodos:**
- `handle(GetAllSessionsByPatientIdQuery query)`: Retorna `List<Session>`. Obtiene todas las sesiones de un paciente
- `handle(GetAllSessionsByProfessionalIdQuery query)`: Retorna `List<Session>`. Obtiene todas las sesiones de un profesional
- `handle(GetSessionByIdQuery query)`: Retorna `Optional<Session>`. Obtiene una sesión por ID
- `handle(GetAllTasksByPatientIdQuery query)`: Retorna `List<Task>`. Obtiene todas las tareas de un paciente
- `handle(GetAllTasksBySessionIdQuery query)`: Retorna `List<Task>`. Obtiene todas las tareas de una sesión
- `handle(GetNoteBySessionIdQuery query)`: Retorna `Optional<Note>`. Obtiene la nota de una sesión

#### Domain Exceptions

##### PatientNotFoundException
- **Propósito**: Excepción lanzada cuando no se encuentra un paciente.

##### ProfessionalNotFoundException
- **Propósito**: Excepción lanzada cuando no se encuentra un profesional.

---

### 2.6.3.2. Interface Layer

#### Controllers

##### SessionReservationController
- **Propósito**: Controlador REST que maneja las operaciones de reserva de sesiones para profesionales.

**Endpoints:**
- `POST /api/v1/professionals/{professionalId}/patients/{patientId}/sessions`: Crea una nueva sesión
    - Path Variables: `professionalId` (Long), `patientId` (Long)
    - Request Body: `CreateSessionResource`
    - Response: `SessionResource` (201 Created) o 400 Bad Request
- `PUT /api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}`: Actualiza una sesión
    - Path Variables: `professionalId` (Long), `patientId` (Long), `sessionId` (Long)
    - Request Body: `UpdateSessionResource`
    - Response: `SessionResource` (200 OK), 404 Not Found, o 400 Bad Request
- `DELETE /api/v1/professionals/{professionalId}/patients/{patientId}/sessions/{sessionId}`: Elimina una sesión
    - Path Variables: `professionalId` (Long), `patientId` (Long), `sessionId` (Long)
    - Response: 204 No Content, 404 Not Found, o 400 Bad Request

**Dependencias:**
- `SessionCommandService`: Para procesar comandos
- `SessionQueryService`: Para procesar consultas

##### PatientSessionController
- **Propósito**: Controlador REST que maneja las operaciones de sesiones para pacientes.

**Endpoints:**
- `GET /api/v1/patients/{patientId}/sessions`: Obtiene todas las sesiones de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `List<SessionResource>` (200 OK)
- `GET /api/v1/patients/{patientId}/tasks`: Obtiene todas las tareas de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `List<TaskResource>` (200 OK)

**Dependencias:**
- `SessionQueryService`: Para procesar consultas

##### ProfessionalSessionController
- **Propósito**: Controlador REST que maneja las operaciones de sesiones para profesionales.

**Endpoints:**
- `GET /api/v1/professionals/{professionalId}/sessions`: Obtiene todas las sesiones de un profesional
    - Path Variable: `professionalId` (Long)
    - Response: `List<SessionResource>` (200 OK)

**Dependencias:**
- `SessionQueryService`: Para procesar consultas

##### SessionToolsController
- **Propósito**: Controlador REST que maneja las operaciones de tareas y notas de sesiones.

**Endpoints:**
- `POST /api/v1/sessions/{sessionId}/tasks`: Crea una nueva tarea en una sesión
    - Path Variable: `sessionId` (Long)
    - Request Body: `CreateTaskResource`
    - Response: `TaskResource` (201 Created) o 400 Bad Request
- `GET /api/v1/sessions/{sessionId}/tasks`: Obtiene todas las tareas de una sesión
    - Path Variable: `sessionId` (Long)
    - Response: `List<TaskResource>` (200 OK)
- `PUT /api/v1/sessions/{sessionId}/tasks/{taskId}`: Actualiza una tarea
    - Path Variables: `sessionId` (Long), `taskId` (Long)
    - Request Body: `UpdateTaskResource`
    - Response: `TaskResource` (200 OK) o 400 Bad Request
- `DELETE /api/v1/sessions/{sessionId}/tasks/{taskId}`: Elimina una tarea
    - Path Variables: `sessionId` (Long), `taskId` (Long)
    - Response: 204 No Content
- `POST /api/v1/sessions/{sessionId}/tasks/{taskId}/complete`: Marca una tarea como completada
    - Path Variables: `sessionId` (Long), `taskId` (Long)
    - Response: `TaskResource` (200 OK)
- `POST /api/v1/sessions/{sessionId}/tasks/{taskId}/incomplete`: Marca una tarea como incompleta
    - Path Variables: `sessionId` (Long), `taskId` (Long)
    - Response: `TaskResource` (200 OK)
- `POST /api/v1/sessions/{sessionId}/notes`: Crea una nueva nota en una sesión
    - Path Variable: `sessionId` (Long)
    - Request Body: `CreateNoteResource`
    - Response: `NoteResource` (201 Created) o 400 Bad Request
- `GET /api/v1/sessions/{sessionId}/notes`: Obtiene la nota de una sesión
    - Path Variable: `sessionId` (Long)
    - Response: `NoteResource` (200 OK) o 404 Not Found
- `PUT /api/v1/sessions/{sessionId}/notes`: Actualiza una nota
    - Path Variable: `sessionId` (Long)
    - Request Body: `UpdateNoteResource`
    - Response: `NoteResource` (200 OK) o 400 Bad Request
- `DELETE /api/v1/sessions/{sessionId}/notes`: Elimina una nota
    - Path Variable: `sessionId` (Long)
    - Response: 204 No Content

**Dependencias:**
- `SessionCommandService`: Para procesar comandos
- `SessionQueryService`: Para procesar consultas

---

### 2.6.3.3. Application Layer

#### Command Handlers

##### SessionCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de sesión. Maneja la lógica de creación, actualización y eliminación de sesiones, tareas y notas.

**Dependencias:**
- `SessionRepository`: Para acceder a la persistencia
- `AppointmentVersionOfExternalProfileService`: Para validar existencia de perfiles

**Métodos:**
- `handle(CreateSessionCommand command)`:
    - Valida que existan el paciente y profesional
    - Crea y persiste la sesión
    - Retorna `Optional<Session>`
- `handle(UpdateSessionCommand command)`: Actualiza una sesión existente
- `handle(DeleteSessionCommand command)`: Elimina una sesión
- `handle(CreateTaskCommand command)`: Crea una tarea en una sesión
- `handle(UpdateTaskCommand command)`: Actualiza una tarea
- `handle(DeleteTaskCommand command)`: Elimina una tarea
- `handle(UpdateTaskStatusToCompleteCommand command)`: Marca una tarea como completada
- `handle(UpdateTaskStatusToIncompleteCommand command)`: Marca una tarea como incompleta
- `handle(CreateNoteCommand command)`: Crea una nota en una sesión
- `handle(UpdateNoteCommand command)`: Actualiza una nota
- `handle(DeleteNoteFromSessionCommand command)`: Elimina una nota

#### Query Handlers

##### SessionQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de sesión.

**Dependencias:**
- `SessionRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetAllSessionsByPatientIdQuery query)`: Obtiene todas las sesiones de un paciente
- `handle(GetAllSessionsByProfessionalIdQuery query)`: Obtiene todas las sesiones de un profesional
- `handle(GetSessionByIdQuery query)`: Obtiene una sesión por ID
- `handle(GetAllTasksByPatientIdQuery query)`: Obtiene todas las tareas de un paciente
- `handle(GetAllTasksBySessionIdQuery query)`: Obtiene todas las tareas de una sesión
- `handle(GetNoteBySessionIdQuery query)`: Obtiene la nota de una sesión

#### Outbound Services

##### AppointmentVersionOfExternalProfileService
- **Propósito**: Servicio para validar la existencia de perfiles de paciente y profesional.

**Métodos:**
- `verifyPatientProfile(Long patientId)`: Verifica si existe un perfil de paciente
- `verifyProfessionalProfile(Long professionalId)`: Verifica si existe un perfil de profesional

---

### 2.6.3.4. Infrastructure Layer

#### Repositories

##### SessionRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de sesiones.

**Extiende:** `JpaRepository<Session, Long>`

**Métodos personalizados:**
- `findAllByPatientId(PatientId patientId)`: Busca todas las sesiones de un paciente
- `findAllByProfessionalId(ProfessionalId professionalId)`: Busca todas las sesiones de un profesional
- `findByPatientIdAndId(PatientId patientId, Long sessionId)`: Busca una sesión específica por paciente e ID
- `existsByNote(Note note)`: Verifica si existe una sesión con la nota dada

---

### 2.6.3.5. Bounded Context Software Architecture Component Level Diagrams

![WhatsApp Image 2025-11-13 at 10 41 15 PM](https://github.com/user-attachments/assets/0e3764c1-e9a7-4c88-b918-635f58fa1e15)

### 2.6.3.6. Bounded Context Software Architecture Code Level Diagrams

#### 2.6.3.6.1. Bounded Context Domain Layer Class Diagrams

![WhatsApp Image 2025-11-14 at 3 29 15 AM](https://github.com/user-attachments/assets/eb114717-9534-4047-8378-032239524401)

#### 2.6.3.6.2. Bounded Context Database Design Diagram

<img width="938" height="1157" alt="SecionsManagmentBc" src="https://github.com/user-attachments/assets/1a28a47d-d4ce-4aab-8e5c-dbe6e0de2d3c" />

---

## 2.6.4. Bounded Context: Medication

### 2.6.4.1. Domain Layer

#### Aggregates

##### Pills
- **Propósito**: Representa un registro de medicación (píldora) asignado a un paciente. Es el agregado raíz para la gestión de medicamentos.

**Atributos:**
- `id` (Long): Identificador único del medicamento
- `name` (String): Nombre del medicamento
- `description` (String): Descripción del medicamento
- `patientId` (Long): Identificador del paciente al que está asignado
- `interval` (String): Intervalo de dosificación (alias: `dosage` en base de datos)
- `quantity` (String): Cantidad del medicamento
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `Pills(String name, String description)`: Constructor básico que crea un medicamento con nombre y descripción
- `Pills(CreatePillsCommand command)`: Constructor que crea un medicamento desde un comando
- `updateInformation(String name, String description, String interval, String quantity)`: Actualiza la información del medicamento. Retorna `Pills`

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<Pills>` para auditoría
- Tiene una relación implícita con `PatientProfile` a través de `patientId`

#### Commands

##### CreatePillsCommand
- **Propósito**: Comando para crear un nuevo registro de medicación.

**Atributos:**
- `name` (String): Nombre del medicamento
- `description` (String): Descripción del medicamento
- `patientId` (Long): Identificador del paciente
- `interval` (String): Intervalo de dosificación
- `quantity` (String): Cantidad del medicamento

##### UpdatePillCommand
- **Propósito**: Comando para actualizar un registro de medicación existente.

**Atributos:**
- `pillId` (Long): Identificador del medicamento
- `name` (String): Nuevo nombre (opcional)
- `description` (String): Nueva descripción (opcional)
- `interval` (String): Nuevo intervalo (opcional)
- `quantity` (String): Nueva cantidad (opcional)

##### DeletePillsCommand
- **Propósito**: Comando para eliminar un registro de medicación.

**Atributos:**
- `pillId` (Long): Identificador del medicamento a eliminar

#### Queries

##### GetAllPillsQuery
- **Propósito**: Consulta para obtener todos los registros de medicación del sistema.

**Atributos:** Ninguno

##### GetPillsByIdQuery
- **Propósito**: Consulta para obtener un registro de medicación por su identificador.

**Atributos:**
- `pillId` (Long): Identificador del medicamento

##### GetPillsByPatientId
- **Propósito**: Consulta para obtener todos los registros de medicación de un paciente.

**Atributos:**
- `patientId` (Long): Identificador del paciente

#### Domain Services

##### PillCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de medicación.

**Métodos:**
- `handle(CreatePillsCommand command)`: Retorna `Long` (ID del medicamento creado). Crea un nuevo registro de medicación
- `handle(UpdatePillCommand command)`: Retorna `Optional<Pills>`. Actualiza un registro de medicación existente
- `handle(DeletePillsCommand command)`: Elimina un registro de medicación

##### PillQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de medicación.

**Métodos:**
- `handle(GetAllPillsQuery query)`: Retorna `List<Pills>`. Obtiene todos los registros de medicación
- `handle(GetPillsByIdQuery query)`: Retorna `Optional<Pills>`. Obtiene un registro por su identificador
- `handle(GetPillsByPatientId query)`: Retorna `List<Pills>`. Obtiene todos los registros de un paciente

---

### 2.6.4.2. Interface Layer

#### Controllers

##### PillController
- **Propósito**: Controlador REST que maneja las operaciones de gestión de medicación.

**Endpoints:**
- `POST /api/v1/pills`: Crea un nuevo registro de medicación
    - Request Body: `CreatePillResource`
    - Response: `PillResource` (201 Created), 400 Bad Request, o 404 Not Found
- `GET /api/v1/pills`: Obtiene todos los registros de medicación
    - Response: `List<PillResource>` (200 OK) o 404 Not Found
- `GET /api/v1/pills/patient/{patientId}`: Obtiene todos los registros de medicación de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `List<PillResource>` (200 OK) o 404 Not Found
- `PUT /api/v1/pills/{pillId}`: Actualiza un registro de medicación
    - Path Variable: `pillId` (Long)
    - Request Body: `UpdatePillResource`
    - Response: `PillResource` (200 OK), 400 Bad Request, o 404 Not Found
- `DELETE /api/v1/pills/{pillId}`: Elimina un registro de medicación
    - Path Variable: `pillId` (Long)
    - Response: `String` (200 OK) o 404 Not Found

**Dependencias:**
- `PillCommandService`: Para procesar comandos
- `PillQueryService`: Para procesar consultas

---

### 2.6.4.3. Application Layer

#### Command Handlers

##### PillCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de medicación. Maneja la lógica de creación, actualización y eliminación de registros de medicación.

**Dependencias:**
- `PillRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(CreatePillsCommand command)`:
    - Crea y persiste un nuevo registro de medicación
    - Retorna el ID del medicamento creado
- `handle(UpdatePillCommand command)`:
    - Actualiza un registro de medicación existente
    - Retorna `Optional<Pills>`
- `handle(DeletePillsCommand command)`: Elimina un registro de medicación

#### Query Handlers

##### PillQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de medicación.

**Dependencias:**
- `PillRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetAllPillsQuery query)`: Obtiene todos los registros de medicación
- `handle(GetPillsByIdQuery query)`: Obtiene un registro por ID
- `handle(GetPillsByPatientId query)`: Obtiene todos los registros de un paciente

---

### 2.6.4.4. Infrastructure Layer

#### Repositories

##### PillRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de registros de medicación.

**Extiende:** `JpaRepository<Pills, Long>`

**Métodos personalizados:** (Ninguno definido en el código revisado)

---

### 2.6.4.5. Bounded Context Software Architecture Component Level Diagrams

![WhatsApp Image 2025-11-13 at 10 50 34 PM](https://github.com/user-attachments/assets/c23f88f1-dcb4-439d-ac1c-aa4e86693c30)

### 2.6.4.6. Bounded Context Software Architecture Code Level Diagrams

#### 2.6.4.6.1. Bounded Context Domain Layer Class Diagrams

![DC-MedicationManagement](https://github.com/user-attachments/assets/995f0545-fb89-442e-bf6f-28049071bab1)

#### 2.6.4.6.2. Bounded Context Database Design Diagram

<img width="812" height="838" alt="MedicalManagmentBC" src="https://github.com/user-attachments/assets/52eff6d0-5245-4453-b664-f24c8570cd8f" />

---

## 2.6.5. Bounded Context: Patient Report

### 2.6.5.1. Domain Layer

#### Aggregates

##### MoodState
- **Propósito**: Representa el estado emocional (mood) de un paciente en un momento determinado. Es el agregado raíz para el registro de estados emocionales.

**Atributos:**
- `moodStatus` (MoodStatus): Estado emocional del paciente (Value Object embebido)
- `patientId` (PatientId): Identificador del paciente (Value Object embebido)
- `id` (Long): Identificador único. Heredado de AuditableAbstractAggregateRoot
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `MoodState(Long patientId, Integer moodStatus)`: Constructor que crea un estado emocional desde valores primitivos
- `validateRecordAvailability(MoodState lastMoodState)`: Valida que no se pueda registrar un estado emocional dos veces en el mismo día. Lanza excepción si se intenta
- `getStatus()`: Retorna el estado emocional como Integer (índice ordinal)
- `getLongPatientId()`: Retorna el identificador del paciente como Long

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<MoodState>` para auditoría
- Usa los Value Objects `MoodStatus` y `PatientId`

**Reglas de negocio:**
- No se puede registrar un estado emocional dos veces en el mismo día
- El estado emocional debe ser un valor entre 0 y 4 (inclusive)

##### BiologicalFunction
- **Propósito**: Representa las funciones biológicas básicas de un paciente (hambre, hidratación, sueño, energía) en un momento determinado. Es el agregado raíz para el registro de funciones biológicas.

**Atributos:**
- `status` (BiologicalFunctionStatus): Estado de las funciones biológicas (Value Object embebido)
- `patientId` (PatientId): Identificador del paciente (Value Object embebido)
- `id` (Long): Identificador único. Heredado de AuditableAbstractAggregateRoot
- `createdAt` (Date): Fecha de creación. Heredado de AuditableAbstractAggregateRoot
- `updatedAt` (Date): Fecha de última actualización. Heredado de AuditableAbstractAggregateRoot

**Métodos:**
- `BiologicalFunction(Integer hunger, Integer hydration, Integer sleep, Integer energy, Long patientId)`: Constructor que crea un registro desde valores primitivos
- `BiologicalFunction(CreateBiologicalFunctionRecordCommand command)`: Constructor que crea un registro desde un comando
- `validateRecordAvailability(BiologicalFunction lastBiologicalFunction)`: Valida que no se pueda registrar una función biológica dos veces en el mismo día. Lanza excepción si se intenta
- `getLongPatientId()`: Retorna el identificador del paciente como Long
- `getHunger()`: Retorna el valor de hambre
- `getHydration()`: Retorna el valor de hidratación
- `getSleep()`: Retorna el valor de sueño
- `getEnergy()`: Retorna el valor de energía

**Relaciones:**
- Extiende de `AuditableAbstractAggregateRoot<BiologicalFunction>` para auditoría
- Usa los Value Objects `BiologicalFunctionStatus` y `PatientId`

**Reglas de negocio:**
- No se puede registrar una función biológica dos veces en el mismo día

#### Value Objects

##### MoodStatus
- **Propósito**: Representa el estado emocional del paciente con valores predefinidos.

**Valores:**
- `SOSAD` (0): Muy triste
- `SAD` (1): Triste
- `NORMAL` (2): Normal
- `HAPPY` (3): Feliz
- `SOHAPPY` (4): Muy feliz

##### BiologicalFunctionStatus
- **Propósito**: Representa el estado de las funciones biológicas básicas del paciente.

**Atributos:**
- `hunger` (Integer): Nivel de hambre (probablemente escala 0-10)
- `hydration` (Integer): Nivel de hidratación (probablemente escala 0-10)
- `sleep` (Integer): Nivel de sueño (probablemente escala 0-10)
- `energy` (Integer): Nivel de energía (probablemente escala 0-10)

##### PatientId
- **Propósito**: Representa el identificador de un paciente de forma encapsulada.

**Atributos:**
- `patientId` (Long): Identificador del paciente

#### Commands

##### CreateMoodStateRecordCommand
- **Propósito**: Comando para crear un nuevo registro de estado emocional.

**Atributos:**
- `patientId` (Long): Identificador del paciente
- `moodStatus` (Integer): Estado emocional (0-4)

##### CreateBiologicalFunctionRecordCommand
- **Propósito**: Comando para crear un nuevo registro de función biológica.

**Atributos:**
- `patientId` (Long): Identificador del paciente
- `hunger` (Integer): Nivel de hambre
- `hydration` (Integer): Nivel de hidratación
- `sleep` (Integer): Nivel de sueño
- `energy` (Integer): Nivel de energía

#### Queries

##### GetAllMoodStatesByPatientIdQuery
- **Propósito**: Consulta para obtener todos los registros de estado emocional de un paciente.

**Atributos:**
- `patientId` (PatientId): Identificador del paciente

##### GetAllBiologicalFunctionsByPatientIdQuery
- **Propósito**: Consulta para obtener todos los registros de funciones biológicas de un paciente.

**Atributos:**
- `patientId` (PatientId): Identificador del paciente

#### Domain Services

##### MoodStateCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de estados emocionales.

**Métodos:**
- `handle(CreateMoodStateRecordCommand command)`: Retorna `Optional<MoodState>`. Crea un nuevo registro de estado emocional

##### MoodStateQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de estados emocionales.

**Métodos:**
- `handle(GetAllMoodStatesByPatientIdQuery query)`: Retorna `List<MoodState>`. Obtiene todos los registros de estado emocional de un paciente

##### BiologicalFunctionCommandService (Interface)
- **Propósito**: Interfaz que define los servicios de comando para la gestión de funciones biológicas.

**Métodos:**
- `handle(CreateBiologicalFunctionRecordCommand command)`: Retorna `Optional<BiologicalFunction>`. Crea un nuevo registro de función biológica

##### BiologicalFunctionQueryService (Interface)
- **Propósito**: Interfaz que define los servicios de consulta para la gestión de funciones biológicas.

**Métodos:**
- `handle(GetAllBiologicalFunctionsByPatientIdQuery query)`: Retorna `List<BiologicalFunction>`. Obtiene todos los registros de funciones biológicas de un paciente

#### Domain Exceptions

##### PatientNotFoundException
- **Propósito**: Excepción lanzada cuando no se encuentra un paciente al intentar crear un registro.

---

### 2.6.5.2. Interface Layer

#### Controllers

##### MoodStateController
- **Propósito**: Controlador REST que maneja las operaciones de registro de estados emocionales.

**Endpoints:**
- `POST /api/v1/patients/{patientId}/mood-states`: Crea un nuevo registro de estado emocional
    - Path Variable: `patientId` (Long)
    - Request Body: `CreateMoodStateRecordResource`
    - Response: `MoodStateResource` (201 Created) o 400 Bad Request
- `GET /api/v1/patients/{patientId}/mood-states`: Obtiene todos los registros de estado emocional de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `List<MoodStateResource>` (200 OK)

**Dependencias:**
- `MoodStateCommandService`: Para procesar comandos
- `MoodStateQueryService`: Para procesar consultas

##### BiologicalFunctionController
- **Propósito**: Controlador REST que maneja las operaciones de registro de funciones biológicas.

**Endpoints:**
- `POST /api/v1/patients/{patientId}/biological-functions`: Crea un nuevo registro de función biológica
    - Path Variable: `patientId` (Long)
    - Request Body: `CreateBiologicalFunctionRecordResource`
    - Response: `BiologicalFunctionResource` (201 Created) o 400 Bad Request
- `GET /api/v1/patients/{patientId}/biological-functions`: Obtiene todos los registros de funciones biológicas de un paciente
    - Path Variable: `patientId` (Long)
    - Response: `List<BiologicalFunctionResource>` (200 OK)

**Dependencias:**
- `BiologicalFunctionCommandService`: Para procesar comandos
- `BiologicalFunctionQueryService`: Para procesar consultas

---

### 2.6.5.3. Application Layer

#### Command Handlers

##### MoodStateCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de estado emocional. Maneja la lógica de creación de registros de estados emocionales.

**Dependencias:**
- `MoodStateRepository`: Para acceder a la persistencia
- `ExternalProfileService`: Para validar existencia de perfiles de paciente

**Métodos:**
- `handle(CreateMoodStateRecordCommand command)`:
    - Valida que exista el perfil del paciente
    - Verifica que no exista un registro para el día actual
    - Crea y persiste el registro de estado emocional
    - Retorna `Optional<MoodState>`

##### BiologicalFunctionCommandServiceImpl
- **Propósito**: Implementación del servicio de comandos de función biológica. Maneja la lógica de creación de registros de funciones biológicas.

**Dependencias:**
- `BiologicalFunctionRepository`: Para acceder a la persistencia
- `ExternalProfileService`: Para validar existencia de perfiles de paciente

**Métodos:**
- `handle(CreateBiologicalFunctionRecordCommand command)`:
    - Valida que exista el perfil del paciente
    - Verifica que no exista un registro para el día actual
    - Crea y persiste el registro de función biológica
    - Retorna `Optional<BiologicalFunction>`

#### Query Handlers

##### MoodStateQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de estado emocional.

**Dependencias:**
- `MoodStateRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetAllMoodStatesByPatientIdQuery query)`: Obtiene todos los registros de estado emocional de un paciente

##### BiologicalFunctionQueryServiceImpl
- **Propósito**: Implementación del servicio de consultas de función biológica.

**Dependencias:**
- `BiologicalFunctionRepository`: Para acceder a la persistencia

**Métodos:**
- `handle(GetAllBiologicalFunctionsByPatientIdQuery query)`: Obtiene todos los registros de funciones biológicas de un paciente

#### Outbound Services

##### ExternalProfileService
- **Propósito**: Servicio para validar la existencia de perfiles de paciente.

**Métodos:**
- `verifyPatientProfile(Long patientId)`: Verifica si existe un perfil de paciente. Lanza `PatientNotFoundException` si no existe

---

### 2.6.5.4. Infrastructure Layer

#### Repositories

##### MoodStateRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de registros de estados emocionales.

**Extiende:** `JpaRepository<MoodState, Long>`

**Métodos personalizados:** (Probablemente incluye métodos para obtener el último registro por paciente y fecha)

##### BiologicalFunctionRepository
- **Propósito**: Interfaz de repositorio JPA para la persistencia de registros de funciones biológicas.

**Extiende:** `JpaRepository<BiologicalFunction, Long>`

**Métodos personalizados:** (Probablemente incluye métodos para obtener el último registro por paciente y fecha)

---

### 2.6.5.5. Bounded Context Software Architecture Component Level Diagrams

![89a74bc7-d10f-4b31-8538-abdc8ad6d37a](https://github.com/user-attachments/assets/3cceb5c8-8797-4039-a731-bdb132a4bb50)

### 2.6.5.6. Bounded Context Software Architecture Code Level Diagrams

#### 2.6.5.6.1. Bounded Context Domain Layer Class Diagrams

![DC-PatientMoodStates](https://github.com/user-attachments/assets/3c51afce-e9cb-4b15-9f70-f7212abb856a)

#### 2.6.5.6.2. Bounded Context Database Design Diagram

<img width="1643" height="891" alt="PatientsManagmentBC" src="https://github.com/user-attachments/assets/3a723912-6e61-48db-ac0c-5e52d5dae1d3" />
