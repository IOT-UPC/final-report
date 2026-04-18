<p align="center">
  <img src="https://github.com/Fundamentos-de-Arquitectura/final-project-report/blob/master/assets/logoupc.png?raw=true"  style="width:200px; height:auto;">
</p>

# <div style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas


## <div style="text-align: center;">Ingeniería de Software </div>
## <div style="text-align: center;"> 202610 </div>
## <div style="text-align: center;"> 1ASI0572 Desarrollo de Soluciones IOT </div>
## <div style="text-align: center;"> NRC: 6785 </div>
## <div style="text-align: center;"> Profesor: Marco Antonio Leon Baca </div>
## <div style="text-align: center;"> Informe del Trabajo Final</div>
## <div style="text-align: center;"> Nombre del Startup: Go8u </div>
## <div style="text-align: center;"> Nombre del Producto: PsyMed </div>

### <div style="text-align: center;"> Integrantes:</div>
<div style="display: flex; justify-content: center;">
    <table>
      <thead>
        <tr>
          <th style="background-color: #333; color: #fff;">Apellidos y Nombres</th>
          <th style="background-color: #333; color: #fff;">Código de Alumno</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Maita Falckenheiner, Romina Guadalupe</td>
          <td>U202213765</td>
        </tr>
        <tr>
          <td>Montañez Moreno, Luis Angel</td>
          <td>U202223811</td>
        </tr>
        <tr>
          <td>Rivera Ticllacuri, Omar Harold</td>
          <td>U202214214</td>
        </tr>
        <tr>
          <td>Sulca Silva, Melisa Sulca</td>
          <td>U20224602</td>
        </tr>
        <tr>
          <td>Torres Flores, Paolo Alessandro</td>
          <td>U20221F613</td>
        </tr>
      </tbody>
    </table> 
</div>


<div style="text-align: center;"> Abril 2026 </div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del informe

# Project Report Collaboration Insights

# Contenido 

Tabla de Contenidos

### [Capítulo I: Introducción](/chapter01.md)
- [1.1. Startup Profile](/chapter01.md#11-startup-profile)
    - [1.1.1. Descripción de la Startup](/chapter01.md#111-descripcion-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](/chapter01.md#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](/chapter01.md#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](/chapter01.md#121-antecedentes-y-problematica)
    - [1.2.2 Lean UX Process](/chapter01.md#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](/chapter01.md#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](/chapter01.md#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](/chapter01.md#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](/chapter01.md#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](/chapter01.md#13-segmentos-objetivo)

---

### [Capítulo II: Requirements Elicitation & Analysis](/chapter02.md)
- [2.1. Competidores](/chapter02.md#21-competidores)
    - [2.1.1. Análisis competitivo](/chapter02.md#211-analisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](/chapter02.md#212-estrategias-y-tacticas-frente-a-competidores)
- [2.2. Entrevistas](/chapter02.md#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](/chapter02.md#221-diseno-de-entrevistas)
    - [2.2.2. Registro de entrevistas](/chapter02.md#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](/chapter02.md#223-analisis-de-entrevistas)
- [2.3. Needfinding](/chapter02.md#23-needfinding)
    - [2.3.1. User Personas](/chapter02.md#231-user-personas)
    - [2.3.2. User Task Matrix](/chapter02.md#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](/chapter02.md#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](/chapter02.md#234-empathy-mapping)
- [2.4. Big Picture EventStorming](/chapter02.md#24-big-picture-eventstorming)
- [2.5. Ubiquitous Language](/chapter02.md#25-ubiquitous-language)

---

### [Capítulo III: Requirements Specification](/chapter03.md)
- [3.1. User Stories](/chapter03.md#31-user-stories)
- [3.2. Impact Mapping](/chapter03.md#32-impact-mapping)
- [3.3. Product Backlog](/chapter03.md#33-product-backlog)

---

### [Capítulo IV: Solution Software Design](/chapter04.md)
- [4.1. Strategic-Level Domain-Driven Design](/chapter04.md#41-strategic-level-domain-driven-design)
    - [4.1.1. Design-Level EventStorming](/chapter04.md#411-design-level-eventstorming)
        - [4.1.1.1 Candidate Context Discovery](/chapter04.md#4111-candidate-context-discovery)
        - [4.1.1.2 Domain Message Flows Modeling](/chapter04.md#4112-domain-message-flows-modeling)
        - [4.1.1.3 Bounded Context Canvases](/chapter04.md#4113-bounded-context-canvases)
    - [4.1.2. Context Mapping](/chapter04.md#412-context-mapping)
    - [4.1.3. Software Architecture](/chapter04.md#413-software-architecture)
        - [4.1.3.1. Software Architecture System Landscape Diagram](/chapter04.md#4131-system-landscape-diagram)
        - [4.1.3.2. Software Architecture Context Level Diagrams](/chapter04.md#4132-context-level-diagrams)
        - [4.1.3.2. Software Architecture Container Level Diagrams](/chapter04.md#4132-container-level-diagrams)
        - [4.1.3.3. Software Architecture Deployment Diagrams](/chapter04.md#4133-deployment-diagrams)

- [4.2. Tactical-Level Domain-Driven Design](/chapter04.md#42-tactical-level-domain-driven-design)
    - [4.2.X. Bounded Context: <Bounded Context Name>](/chapter04.md#42x-bounded-context)
        - [4.2.X.1. Domain Layer](/chapter04.md#42x1-domain-layer)
        - [4.2.X.2. Interface Layer](/chapter04.md#42x2-interface-layer)
        - [4.2.X.3. Application Layer](/chapter04.md#42x3-application-layer)
        - [4.2.X.4. Infrastructure Layer](/chapter04.md#42x4-infrastructure-layer)
        - [4.2.X.5. Component Level Diagrams](/chapter04.md#42x5-component-diagrams)
        - [4.2.X.6. Code Level Diagrams](/chapter04.md#42x6-code-diagrams)
            - [4.2.X.6.1. Domain Layer Class Diagrams](/chapter04.md#42x61-domain-class-diagrams)
            - [4.2.X.6.2. Database Design Diagram](/chapter04.md#42x62-database-diagram)

---

### [Capítulo V: Solution UI/UX Design](/chapter05.md)
- [5.1. Style Guidelines](/chapter05.md#51-style-guidelines)
    - [5.1.1. General Style Guidelines](/chapter05.md#511-general-style-guidelines)
    - [5.1.2. Web, Mobile and IoT Style Guidelines](/chapter05.md#512-web-mobile-iot)
- [5.2. Information Architecture](/chapter05.md#52-information-architecture)
    - [5.2.1. Organization Systems](/chapter05.md#521-organization-systems)
    - [5.2.2. Labeling Systems](/chapter05.md#522-labeling-systems)
    - [5.2.3. SEO Tags and Meta Tags](/chapter05.md#523-seo-tags)
    - [5.2.4. Searching Systems](/chapter05.md#524-searching-systems)
    - [5.2.5. Navigation Systems](/chapter05.md#525-navigation-systems)
- [5.3. Landing Page UI Design](/chapter05.md#53-landing-page)
    - [5.3.1. Landing Page Wireframe](/chapter05.md#531-wireframe)
    - [5.3.2. Landing Page Mock-up](/chapter05.md#532-mockup)
- [5.4. Applications UX/UI Design](/chapter05.md#54-applications-design)
    - [5.4.1. Applications Wireframes](/chapter05.md#541-wireframes)
    - [5.4.2. Applications Wireflow Diagrams](/chapter05.md#542-wireflows)
    - [5.4.2. Applications Mock-ups](/chapter05.md#542-mockups)
    - [5.4.3. Applications User Flow Diagrams](/chapter05.md#543-user-flows)
- [5.5. Applications Prototyping](/chapter05.md#55-prototyping)
- [5.6. IoT Device Design](/chapter05.md#56-iot-design)

---

### [Capítulo VI: Product Implementation, Validation & Deployment](/chapter06.md)
- [6.1. Software Configuration Management](/chapter06.md#61-scm)
    - [6.1.1. Software Development Environment Configuration](/chapter06.md#611-environment)
    - [6.1.2. Source Code Management](/chapter06.md#612-source-code)
    - [6.1.3. Source Code Style Guide & Conventions](/chapter06.md#613-style-guide)
    - [6.1.4. Software Deployment Configuration](/chapter06.md#614-deployment)
- [6.2. Implementation](/chapter06.md#62-implementation)
    - [6.2.X. Sprint n](/chapter06.md#62x-sprint)
        - [6.2.X.1. Sprint Planning](/chapter06.md#62x1-planning)
        - [6.2.X.2. Aspect Leaders and Collaborators](/chapter06.md#62x2-team)
        - [6.2.X.3. Sprint Backlog](/chapter06.md#62x3-backlog)
        - [6.2.X.4. Development Evidence](/chapter06.md#62x4-dev-evidence)
        - [6.2.X.5. Testing Evidence](/chapter06.md#62x5-testing)
        - [6.2.X.6. Execution Evidence](/chapter06.md#62x6-execution)
        - [6.2.X.7. Services Documentation](/chapter06.md#62x7-docs)
        - [6.2.X.8. Deployment Evidence](/chapter06.md#62x8-deployment)
        - [6.2.X.9. Team Insights](/chapter06.md#62x9-insights)
- [6.3. Validation Interviews](/chapter06.md#63-validation)
    - [6.3.1. Diseño de Entrevistas](/chapter06.md#631-diseno)
    - [6.3.2. Registro de Entrevistas](/chapter06.md#632-registro)
    - [6.3.3. Evaluaciones según heurísticas](/chapter06.md#633-heuristicas)
- [6.4. Video About-the-Product](/chapter06.md#64-video)

---

### [Conclusiones](/conclusions.md)
- [Conclusiones y recomendaciones](/conclusions.md#conclusiones)

### [Video About-the-Team](/team-video.md)

### [Bibliografía](/bibliography.md)

### [Anexos](/annexes.md)


# Student Outcome 

