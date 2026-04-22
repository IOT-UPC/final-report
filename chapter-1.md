# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

PsyMed es una plataforma web diseñada para optimizar la gestión y el seguimiento de personas que van a centros psiquiátricos o consultorios, debido a que comienzan a manifestar síntomas de trastornos mentales como estrés, ansiedad o depresión tras atravesar situaciones complejas en su vida. Esta aplicación se enfoca en aquellos individuos en sus primeras etapas de desarrollo de síntomas, ofreciendo monitoreo preventivo y seguimiento continuo. Además, facilita la comunicación continua entre profesionales de la salud mental y estos pacientes, permitiendo un monitoreo integral del progreso, un seguimiento personalizado de tratamientos, y la gestión eficiente de citas clínicas en un entorno seguro y accesible. <br>

Este proyecto incorpora una pulsera inteligente IoT para permitir el monitoreo continuo de signos vitales, como frecuencia cardiaca y variabilidad de la frecuencia cardiaca. Los niveles elevados de ansiedad, estrés o depresión pueden reflejarse en un aumento de la frecuencia cardíaca, una disminución en la variabilidad de la frecuencia cardíaca (HRV) debido a las respuestas fisiológicas a trastornos mentales. Cuando el dispositivo IoT detecta estos cambios, se activa un motor de vibración háptica como actuador físico relajante para intervenir para reducir la ansiedad, estrés o la depresión. <br>

Cabe destacar, que PsyMed se enfoca en mejorar la calidad de la atención al proporcionar herramientas que permiten a los profesionales de la salud mental mantenerse conectados con sus pacientes de manera efectiva y con información actualizada en todo momento. <br>

**Misión:** Proporcionar herramientas accesibles y efectivas para el monitoreo de trastornos mentales. De esta manera, se logrará prevenir el deterioro de la salud mental mediante el uso de tecnologías innovadoras y la intervención a través de actuadores físicos. <br>
   
**Visión:** Ser líderes en prevenir el deterioro de la salud mental proporcionando a las personas  que comienzan a presentar trastornos mentales las herramientas necesarias para monitorear su salud y bienestar y recibir intervenciones a tiempo. Logrando así, mejorar su calidad de vida y acceso a la atención para todos. 


### 1.1.2. Perfiles de integrantes del equipo

| Foto                                                                                        | Apellido y Nombre                                 | Carrera                | Acerca de                                                                                                                                                                                          | Habilidades                                                                                                                                                                        |
|---------------------------------------------------------------------------------------------|---------------------------------------------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| <img src="https://github.com/user-attachments/assets/c599d27d-6f43-4c78-a826-a5f409c6b0f4"> | Maita Falckenheimer, Romina Guadalupe (u20213765) | Ingeniería de Software | Soy estudiante de Ingeniería de Software, actualmente estoy haciendo prácticas como desarrolladora Full Stack para un proyecto de Django. Me apasiona la tecnología y la música.                   | Liderazgo, competitividad y organización.                                                                                                                                          |
| <img src="https://github.com/user-attachments/assets/0134cdb5-f7b4-48d2-b695-e1207c311cbc"> | Torres Flores, Paolo Alessandro (u202211f613)     | Ingeniería de Software | Soy un estudiante de 7mo ciclo con afán de mejorar cada día que pasa. Tengo muchas aspiraciones, ya sea en mi carrera como personalmente, y lucho diariamente para acercarme cada vez más a ellas. | Me considero una persona adaptable al entorno, sé trabajar en equipo y aprendo rápido. Mentalidad para resolver problemas. Conocimiento básico de las funcionalidades de software. |
|                                                                                             | Montañez Moreno, Luis Angel (u202223811)          | Ingeniería de Software | sdsd                                                                                                                                                                                               | dsd                                                                                                                                                                                |
| <img src="https://github.com/user-attachments/assets/318ea659-7659-4a8a-ad27-d2476f0435fb"> | Rivera Ticllacuri, Omar Harold (u202214214)       | Ingeniería de Software | Soy estudiante de Ingeniería de Software en sexto ciclo, con 20 años. Me caracterizo por mi disciplina y responsabilidad en el desarrollo de proyectos, y cuento con experiencia en software de entretenimiento. Estoy comprometido con aportar activamente al equipo.                                                                                                                                                                                               | Cuento con habilidades para la resolución de problemas y el pensamiento lógico, lo que me permite desarrollar soluciones eficientes. Además, soy una persona creativa, adaptable y orientada al desarrollo de software.                                                                                                                                                                                |
| <img src="https://i.imgur.com/p9GVr4j.png">  | Sulca Silva, Melisa Sulca (u20224602)             | Ingeniería de Software | Estudio la carrera de Ingeniería de Software y me interesa la tecnología, la música, los deportes y los videojuegos. Me motiva mucho aprender nuevos lenguajes de programación.  | Suelo trabajar bien en equipo, muestro compromiso con el grupo y  aplico perseverancia para superar los obstáculos y alcanzar mis objetivos.                                                                                                                                                                                |

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática


- **Who:** El problema afecta a los profesionales de la salud mental, pacientes que están empezando a mostrar síntomas de trastornos mentales, y al sistema de salud en general.

- **What:** A pesar de las políticas de salud pública que han dado mayor importancia a la salud mental, el sistema sigue siendo incapaz de atender a la gran mayoría de la población afectada por trastornos mentales, como la depresión y la ansiedad.

- **Where:** Esta problemática es particularmente visible en Perú, donde el Ministerio de Salud y la Defensoría del Pueblo han documentado una grave falta de recursos en las instituciones de salud mental para tratar a personas que muestran dichos síntomas.

 - **When:** El déficit en la atención de la salud mental ha sido un problema desde al menos 2016, y se ha agravado en los últimos años, especialmente desde 2021, cuando se reportaron más de un millón de casos de problemas de salud mental según el Diario El Peruano (2023).
 
 - **Why:** La saturación del sistema de salud y la falta de recursos humanos y financieros son las principales causas de este problema, lo que resulta en que, de acuerdo con la Defensoría del Pueblo, 8 de cada 10 personas no reciban la atención que necesitan (2018).
 
 - **How:** El déficit se manifiesta en la escasez de profesionales especializados en salud mental y en la carga administrativa que enfrenta el personal médico, lo que dificulta aún más la prestación de atención adecuada. Según la Defensoría del Pueblo, en el 2020, el Perú tenía solo 3 psiquiatras y 10 psicólogos por cada 100,000 habitantes
 
 - **How Much:** La magnitud del problema es alarmante, con más de 1 millón de personas afectadas que no reciben la atención requerida por problemas de percepción a los servicios sanitarios como las limitaciones del sistema de atención, lo que representa un desafío urgente para el sistema de salud (Centro Peruano de Estudios Gubernamentales - CEPEG, 2026). 
 
 <br>

**Descripción de la Problemática:** <br>

El sistema de salud mental en Perú enfrenta una crisis debido a la sobrecarga administrativa que limita la capacidad de los profesionales para atender a los pacientes. La creciente demanda de atención en salud mental, impulsada por trastornos como estrés, depresión y ansiedad, ha llevado a un sistema que lucha por gestionar de manera eficiente las citas, los historiales clínicos y la comunicación entre médicos y pacientes.
Para superar este desafío, es esencial implementar soluciones tecnológicas que optimicen la gestión de personas en las primeras etapas de los trastornos mentales. Automatizar tareas y utilizar dispositivos IoT de monitoreo continuo, como la pulsera inteligente, permitirá liberar tiempo a los profesionales de la salud, ayudándoles a enfocarse más en la atención directa y mejorando así el acceso y la calidad de la atención en salud mental en Perú

<br>

¿Cómo pueden las soluciones tecnológicas mejorar la gestión y administración del servicio de salud mental en Perú?


### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

El sistema de salud mental en Perú se enfrenta a una crisis debido a la sobrecarga administrativa que limita la capacidad de los profesionales para brindar atención directa a sus pacientes. La creciente demanda de
servicios de salud mental, impulsada por trastornos como la depresión y la ansiedad, ha generado un colapso en la gestión de citas, historiales clínicos y comunicación entre médicos y pacientes. Esta situación ha resultado en una reducción en la calidad del servicio y en el acceso oportuno a la atención que los pacientes necesitan. <br>

¿Cómo podríamos desarrollar una solución tecnológica que automatice las tareas administrativas, incluya un dispositivo IoT para monitoreo continuo, libere tiempo para los profesionales de salud mental y, en última instancia, mejore el acceso y la calidad de la atención en el sistema de salud mental en Perú? <br>

Nuestra plataforma debe ser fácil de usar, integrando de manera eficiente la gestión de citas, historiales médicos, comunicación entre médicos y pacientes, y que incorpore un dispositivo IoT correctamente para transferir datos fisiológicos importantes a la plataforma para mejorar los tratamientos. Esto permitirá a los profesionales de salud mental enfocarse en lo que más importa: brindar atención de calidad a sus pacientes. <br>
<br> 

**Customer Segments**

Los usuarios principales de esta plataforma serán los profesionales de la salud mental, y otros especialistas
que trabajan en instituciones médicas dedicadas a la salud mental. También incluye al personal administrativo encargado de la gestión de citas y la organización de información clínica.


**Pain Points**

Las herramientas tecnológicas actuales en estas instituciones no cumplen con las necesidades específicas de gestión y monitoreo, resultando en un manejo fragmentado de los datos clínicos. Esto causa dificultades para organizar y acceder a la información relevante durante las consultas y problemas para programar y gestionar citas de manera eficiente. Esta situación genera una carga administrativa adicional para los profesionales de la salud mental, aumenta el riesgo de errores en el manejo de la información clínica, y limita la capacidad de ofrecer un enfoque de tratamiento multidisciplinario.


**Gap** 

Existe una brecha significativa en el mercado en cuanto a soluciones tecnológicas integradas y especializadas para la gestión de información en instituciones de salud mental. Aunque muchas instituciones han adoptado herramientas básicas como agendas en línea, aún no se ha implementado una plataforma que centralice el monitoreo continuo de signos vitales y que integre todas las funcionalidades necesarias para la gestión eficiente y segura de la información clínica.


**Vision/Strategy**

Nuestra visión es desarrollar una plataforma que centralice todas las funcionalidades necesarias para la
gestión diaria en un solo lugar, asegurando que sea segura, fácil de usar, y capaz de mejorar la organización de consultas, el acceso a la información, y la coordinación entre los diferentes profesionales. La estrategia
incluye integrar funcionalidades como la gestión de citas, acceso a datos clínicos, soporte para tratamientos multidisciplinarios, y dispositivos IoT dentro de las instituciones.


**Initial Segment** 

El segmento inicial para la implementación de esta plataforma estará compuesto por instituciones médicas de salud mental en Lima Metropolitana que ya muestran un interés en modernizar su gestión interna y que han adoptado parcialmente herramientas digitales, pero carecen de una solución integrada que cubra todas sus
necesidades como, por ejemplo, monitoreo continuo de personas con trastornos mentales.


#### 1.2.2.2. Lean UX Assumptions.

**Business Assumptions**
1. **Creemos que nuestros clientes tienen la necesidad de:** organizar y gestionar de manera eficiente la información de los pacientes, citas, y datos clínicos.

2. **Estas necesidades se pueden satisfacer con:** una plataforma centralizada y específica para las instituciones de salud mental, que optimice sus procesos internos, monitoree continuamente los signos vitales de los pacientes con dispositivos IoT, reduzca errores y mejore la calidad de la atención.

3. **Nuestros clientes iniciales son (o serán):** instituciones de salud mental que buscan modernizar y centralizar su gestión de información.

4. **El valor principal que un cliente quiere obtener de nuestro servicio es:** eficiencia operativa y reducción de errores en la gestión de información clínica.

5. **Los clientes también pueden obtener estos beneficios adicionales:** mejora en la calidad del servicio, mayor seguridad de los datos y una mejor coordinación entre profesionales.

6. **Adquiriremos a la mayoría de nuestros clientes a través de:** enfocarnos en demostrar a los clientes potenciales, como instituciones de salud mental y profesionales independientes, sobre los beneficios que la plataforma PsyMed. Esta aplicación no solo posee el monitoreo continuo de signos vitales, sino también incluye retroalimentación física que sirve como una herramienta de intervención que ayuda a los pacientes a reducir trastornos mentales. Este sistema puede prevenir el agravamiento de trastornos mentales, específicamente a los pacientes que están en las primeras etapas de síntomas de algunos trastornos como la ansiedad, estrés o  depresión. Para ello, se realizará una campaña de marketing con presentaciones personalizadas y demostraciones de la plataforma a nuestros clientes.

7. **Ganaremos dinero mediante:** ofreciendo módulos adicionales de la plataforma, como la integración con sistemas de facturación o la expansión de la capacidad de almacenamiento de datos para gestionar la información recolectada de manera continua, mediante los sensores de frecuencia cardíaca, HRV y frecuencia cardiaca. PsyMed tendrá un modelo de suscripción de dos tipos: la primera es una suscripción básica y la otra es una suscripción premium. La primera tendrá acceso completo a nuestra aplicación web y móvil, donde los usuarios pueden gestionar citas, los profesionales de la salud mental pueden acceder a información de pacientes y realizar un seguimiento de sus pacientes, pero sin el dispositivo IoT (pulsera inteligente que incluye motor de vibración háptico). La segunda incluye todos los beneficios de la suscripción básica más la pulsera inteligente con retroalimentación física (vibración háptica) para intervenir en momentos de estrés o ansiedad. Este dispositivo IoT será un componente importante para un seguimiento más efectivo entre pacientes y profesionales de la salud mental.

8. **Nuestra competencia principal en el mercado será:** plataformas de gestión médica que se centran en la salud mental y que no están especializadas en el monitoreo de los pacientes con trastornos mentales no crónicos. Las demás plataformas que son nuestra competencia usualmente ofrecen funcionalidades generales para la administración de la salud de sus pacientes, sin embargo, no cuentan con un dispositivo IoT de monitoreo continuo que integre un actuador físico (vibración háptica) para intervenir directamente, por ejemplo, en momentos de estrés, depresión o ansiedad, como si lo hace PsyMed con su sistema especializado.

9. **Les superaremos debido a:** nuestro enfoque especializado en personas con trastornos mentales en etapa inicial y las funcionalidades integradas que abordan las necesidades específicas de las instituciones de salud mental. Además nuestro factor diferencial es la pulsera inteligente, que es un dispositivo IoT capaz de realizar un monitoreo continuo de datos fisiológicos y proporcionar retroalimentación física a través de vibraciones hápticas para intervenir en momentos de síntomas de trastornos mentales, lo cual generalmente otras plataformas de gestión médica no ofrecen a sus pacientes.

10. **El mayor riesgo para nuestro producto es:** que la funcionalidad de gestión de citas y el monitoreo continuo de datos fisiológicos no se integre correctamente con el resto de la plataforma o que las instituciones no perciban un valor claro en la adopción de una nueva plataforma tecnológica.

<br>

**User Assumptions**

1. **¿Quién es el usuario?** <br>
Los usuarios son profesionales de la salud mental, como psiquiatras y psicólogos, que necesitan gestionar la información de sus pacientes de manera eficiente. También, los pacientes son usuarios clave, debido a que la plataforma está enfocada en brindarles un monitoreo continuo de signos vitales y proporcionar un actuador físico cuando, por ejemplo, se detectan niveles elevados de estrés o ansiedad. 

2. **¿Dónde encaja nuestro producto en su trabajo o vida?** <br>
Nuestro producto encaja en su trabajo diario, ayudando en la gestión de citas, seguimiento de tratamientos, acceso a datos clínicos y proporción de monitoreo continuo de signos vitales que incluye retroalimentación física mediante vibración háptica cuando detectan niveles elevados de ansiedad.

3. **¿Qué problemas resuelve nuestro producto?** <br>
Resuelve la gestión fragmentada de la información, la dificultad en la programación de citas, y mejora la coordinación entre profesionales. Además, facilita el seguimiento en tiempo real, brindando una intervención inmediata a través del actuador físico cuando se detectan síntomas de estrés o ansiedad.

4. **¿Cuándo y cómo se utiliza nuestro producto?** <br>
Se utiliza diariamente para gestionar citas y consultas, así como para la coordinación entre profesionales. También, se usa para monitorear signos vitales y detectar cambios en la salud emocional a través de los parámetros fisiológicos activando así la vibración háptica cuando se requiera.

5. **¿Qué características son importantes?** <br>
La integración de datos clínicos, la programación de citas, las notificaciones automáticas, la seguridad en la información, una interfaz intuitiva que permita un acceso rápido y seguro a la información
durante la programación de consultas, y monitoreo continuo de signos vitales.

6. **¿Cómo debería verse y comportarse nuestro producto?** <br>
Debe ser intuitivo, fácil de usar, con una interfaz limpia y opciones de personalización para diferentes tipos de usuarios. La plataforma debe ser accesible desde múltiples dispositivos como móvil o web  y debe permitir gestionar los datos clínicos de forma efectiva.

7. **El valor principal que un usuario quiere obtener de nuestra funcionalidad es:** reducción de errores administrativos y una gestión más eficiente de los horarios. Además, la gestión continua de signos vitales permite detectar signos de estrés o ansiedad en tiempo real.

8. **Los usuarios también pueden obtener estos beneficios adicionales:** acceso rápido y seguro a la información durante la programación de consultas. La plataforma permite monitorear la evolución del paciente, gestionar intervenciones preventivas cuando se detectan niveles elevados de ansiedad ayudando a los profesionales de la salud a mejorar el tratamiento. 

9. **El mayor riesgo para el usuario es:** que los profesionales encuentren la plataforma difícil de usar o que no se ajuste a su flujo de trabajo diario. También, existe el riesgo de que no se comprenda completamente el valor de las funcionalidades innovadoras (el monitoreo continuo de signos vitales y la retroalimentación háptica a través de la pulsera inteligente) o que no se transmita correctamente los datos a la plataforma. 

<br>

**User Outcomes:**

**Acceso a Asistencia Especializada:** Los usuarios, tanto psiquiatras como otros profesionales de la salud mental, buscan un acceso fácil y rápido a herramientas que les permitan gestionar de manera eficiente la información de sus pacientes y poder monitorear su estado de manera continua. Este outcome se centra en la capacidad de los usuarios para acceder a una plataforma integrada que optimice la organización de citas y tratamientos, facilite el monitoreo continuo de datos fisiológicos y proporcione retroalimentación física cuando se presente niveles elevados de ansiedad, estrés o depresión. Esto les proporciona confianza y apoyo en la prestación de un cuidado de calidad.

<br>

**Mejora en la Atención al Paciente:** Para los pacientes, el outcome deseado es recibir una atención más organizada y eficiente, facilitada por una plataforma que centraliza toda la información relevante sobre su tratamiento. Esto incluye el seguimiento de citas, acceso a su historial clínico, y una comunicación más efectiva con sus proveedores de salud mental. El monitoreo continuo y el actuador físico también contribuyen a mejorar el bienestar emocional del paciente. El éxito se mide por la satisfacción del paciente y la mejora en la calidad del cuidado recibido.

<br>

**Colaboración y Coordinación Profesional:** Para los profesionales de la salud mental que trabajan en equipo, el outcome deseado es una mejor colaboración y coordinación en el tratamiento multidisciplinario de los
pacientes. Esto incluye la organización eficiente de citas conjuntas, y la capacidad de monitorear el progreso de los pacientes en tiempo real mediante el seguimiento continuo de signos vitales. El éxito se evalúa por la eficiencia en la coordinación de tratamientos y la satisfacción de los profesionales con la colaboración facilitada por la plataforma.

<br>

**Business Outcomes:** 

**Desarrollo de una Comunidad Especializada:** Con una base de usuarios en instituciones de salud mental, esperamos que el 10% de ellos inicie sesión dentro del primer mes después del lanzamiento de la plataforma.
Al proporcionar herramientas especializadas para la gestión de la salud mental, la plataforma puede convertirse en un punto de referencia para psiquiatras, psicólogos, y otros profesionales interesados en mejorar la eficiencia operativa y la calidad del cuidado. Esto puede fomentar el intercambio de conocimientos y mejores prácticas dentro de la comunidad de salud mental.

<br>

**Generación de Ingresos Sostenibles:** Esperamos que, dentro de los primeros seis meses después del lanzamiento, al menos el 25% de las instituciones de salud mental y profesionales independientes que utilicen la versión gratuita de la plataforma se conviertan en suscriptores de pago. Este éxito se medirá a través de la tasa de conversión de usuarios gratuitos a usuarios pagos y por el aumento en los ingresos recurrentes mensuales provenientes de las licencias de uso del software y módulos adicionales. La satisfacción del usuario y la retención de suscripciones a largo plazo serán indicadores clave para evaluar la sostenibilidad financiera de la plataforma.

<br>

**Impacto Positivo en la Salud Mental:** A lo largo del primer año de operación, se espera que el uso de la plataforma reduzca la carga administrativa en un 30% para los profesionales de salud mental que la utilicen activamente, medido a través de encuestas de usuario y estudios de tiempo dedicados a tareas
administrativas antes y después de la adopción de la plataforma. Además, se busca que al menos el 20% de los pacientes tratados a través de la plataforma reporten mejoras en la satisfacción con la atención recibida, lo que se evaluará mediante encuestas periódicas a los pacientes. La intervención temprana proporcionada a través de la pulsera inteligente (dispositivo IoT) contribuirá significativamente a la mejora de la calidad del cuidado y la satisfacción del paciente con su respectivo tratamiento.  

<br>

**Features Assumptions:**

1. **Acceso a Herramientas de Gestión Especializadas:** <br>
    - **Gestión de Citas y Tratamientos:** Implementar una funcionalidad que permita a los usuarios organizar y gestionar citas de manera eficiente, directamente integrada con los registros de los pacientes. Esto facilitará la planificación y el seguimiento de los tratamientos, reduciendo la posibilidad de errores administrativos. <br>

    - **Historial Clínico Accesible:** Desarrollar una funcionalidad que permita a los profesionales de la salud mental acceder de manera rápida y segura al historial clínico completo de los pacientes, garantizando que toda la información relevante esté disponible durante las consultas. <br>

    - **Monitoreo Continuo de signos vitales y actuador físico mediante vibración háptica:** Integrar una funcionalidad que permita a los profesionales de la salud mental monitorear continuamente los datos fisiológicos de los pacientes a través de un dispositivo IoT para detectar niveles elevados de ansiedad, estrés o depresión. Cuando se detecte ese cambio de nivel el sistema debe activar un motor de vibración háptica como actuador físico relajante para intervenir en tiempo real, de manera que los pacientes puedan reducir, por ejemplo, su estrés y mejorar su bienestar emocional. <br>

2. **Mejora en la Atención al Paciente:** <br>
    - **Portal de Pacientes:** Crear un portal dedicado para los pacientes donde puedan revisar su historial, seguir sus tratamientos, y comunicarse con sus psiquiatras y otros profesionales de manera segura. Este portal incluirá recordatorios de citas, acceso a recursos educativos sobre su salud mental, visualización de datos de monitoreo continuo de su salud y las notificaciones recibidas cuando la pulsera inteligente detecta cambios de niveles emocionales extremos. <br>

    - **Encuestas de Satisfacción:** Implementar encuestas automatizadas que se envíen a los pacientes después de las consultas o tratamientos, permitiendo a los profesionales de la salud mental recopilar retroalimentación directa y mejorar la calidad de la atención. Además, estas encuestas incluyen preguntas sobre la experiencia del paciente con el monitoreo continuo y la efectividad de la retroalimentación física. Esto permitirá mejorar la calidad de la atención y ajustar la frecuencia de intervención según las necesidades del paciente. <br>

3. **Colaboración y Coordinación Profesional:**
    - **Panel de Control para Seguimiento:** Crear un panel de control que permita a los profesionales monitorear el progreso de los pacientes en tiempo real, facilitando la coordinación y el seguimiento de los tratamientos multidisciplinarios. Este panel mostrará la información clínica tradicional con los datos fisiológicos obtenidos a través de los sensores de monitoreo continuo. También, incluirá las alertas automáticas  cuando se detecten altos niveles de estrés, ansiedad o depresión, lo que permitirá una intervención inmediata. <br><br>

#### 1.2.2.3. Lean UX Hypothesis Statements.

1. **Creemos que lograremos** un aumento en la aceptación de nuestra plataforma y una mejor satisfacción del usuario si los problemas de gestión de la información de los pacientes se ven solucionados o
atendidos. **Al ofrecer** una plataforma centralizada que permita a los profesionales de la salud mental gestionar toda la información de los pacientes de manera integrada y eficiente, **con la
implementación** de funcionalidades específicas para la gestión de citas, seguimiento de tratamientos y monitoreo continuo de signos vitales, y la vibración háptica cuando se detecte niveles elevados de estrés, ansiedad o depresión, se podrá mejorar significativamente la organización y el acceso a los datos clínicos. <br>

2. **Creemos que lograremos** una mayor retención de usuarios y una mayor rentabilidad del negocio si los profesionales de la salud mental valoran la facilidad de uso y la seguridad en la gestión de la información. **Al proporcionar** una interfaz intuitiva y accesible desde cualquier dispositivo, con opciones de personalización para diferentes tipos de usuarios y con soporte técnico constante, además de **optimizar** la usabilidad después de realizar pruebas piloto con diferentes flujos de trabajo y entender las necesidades de los usuarios, se facilitará la adopción y el uso continuo de la plataforma.

3. **Creemos que lograremos** fortalecer nuestra posición en el mercado y aumentaremos la confianza de los usuarios si estos perciben que nuestra plataforma ofrece valor adicional a través de integraciones tecnológicas avanzadas. **Al establecer** integraciones con otros sistemas utilizados en las instituciones de salud mental, como sistemas de facturación o de registro médico electrónico, **con la identificación** y el desarrollo de módulos adicionales que integren monitoreo continuo y vibración háptica, se realizará pruebas piloto para garantizar la compatibilidad, y se ofrecerá un valor añadido que diferenciará a nuestra plataforma de las opciones existentes.

4. **Creemos que lograremos** aumentar la satisfacción del usuario, la fidelidad a nuestra plataforma y el boca a boca positivo si los usuarios experimentan una reducción en la carga administrativa y una mejora en la coordinación entre profesionales. **Al mejorar** la funcionalidad de gestión de citas y la visualización de información clínica de manera integrada y proporcionar monitoreo continuo de los pacientes mediante la pulsera inteligente junto con la retroalimentación física, basándonos en pruebas de usabilidad y recopilación de testimonios directos de usuarios, **con la implementación** de mejoras que simplifiquen las tareas administrativas y fomenten la colaboración multidisciplinaria, se mejorará la experiencia general del usuario y aumentará la satisfacción tanto de los profesionales de la salud como de los pacientes. <br>

5. **Creemos que** impulsaremos el crecimiento de nuestra base de usuarios y la expansión de nuestra plataforma si los profesionales de la salud mental se familiarizan con nuestra solución a través de campañas de marketing dirigidas. **Al realizar** campañas de marketing piloto dirigidas a instituciones de salud mental y profesionales independientes, **con el desarrollo** de presentaciones en conferencias y la adaptación de nuestra estrategia de marketing según los resultados obtenidos, se logrará una mayor adopción de la plataforma. <br>


#### 1.2.2.4. Lean UX Canvas.

<p align="center">
  <img src="https://i.imgur.com/IeyLZKd.png" alt="e23" width="500">
</p>
<p align="center">
  <img src="https://i.imgur.com/nRGyXXe.png" alt="e23" width="500">
</p>

<p align="center">
  <img src="https://i.imgur.com/jVdVbDB.png" alt="e23" width="500">
</p>

- Link: https://docs.google.com/document/d/14WNELxIteT5xwQ8DHbio67ipneiY8khm/edit?usp=sharing&ouid=108981375820684358664&rtpof=true&sd=true 

## 1.3. Segmentos objetivo.

- **Profesionales de la Salud Mental:** Psiquiatras y psicólogos, que trabajan tanto en el sector público como en el privado en Lima. En Perú, según la OMS, por cada 100 mil habitantes solo se cuenta con 3 psiquiatras y 10 psicólogos, lo que impide una adecuada atención. Además, en el 2016 solo había 264 psiquiatras que trabajaban en el Ministerio de Salud (Defensoría del Pueblo, 2020). Esta escasez genera una sobrecarga de trabajo, afectando la calidad de la atención y la eficiencia en el manejo de casos clínicos. <br>

- **Pacientes con Trastornos Mentales:** Individuos de todas las edades y géneros, pero con un mayor enfoque en adultos jóvenes (18-35 años) y mujeres, quienes son más propensos a experimentar síntomas de trastornos mentales como el estrés, la depresión y la ansiedad debido a situaciones complejas de su vida. En Lima, un estudio realizado por el Instituto Nacional de la Salud Mental detalla que 1 de cada 8 personas, que es un 11,8% de la población, ha padecido algún trastorno mental durante el año 2020 (Gobierno del Perú, 2021). Los casos han aumentado significativamente desde 2021 debido a la pandemia, reflejando la gravedad de la crisis en la salud mental en el país (Gobierno del Perú, 2023). <br>
