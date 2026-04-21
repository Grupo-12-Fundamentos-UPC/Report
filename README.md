# <p align="center" id="caratula"> Universidad Peruana de Ciencias Aplicadas </p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" alt="Logo UPC">
</div>

### <p align="center"> Informe Entrega 1 </p>

<br>
<div align="center">
  <p> Carrera: Ingeniería de Software </p>
  <br>
  <p> Ciclo: 2026-10 </p>
  <br>
  <p> Curso: Fundamentos de Arquitectura de Software </p>
  <br>
  <p> NRC: 7940 </p>
  <br>
  <p> Profesor: Daniel Enrique Mori Yzaguirre </p>
  <br>
  <p> Nombre del Startup: HairyPaws </p>
  <br>
  <p> Nombre del Producto: HairyPaws </p>
  <br>
  <p> Relación de Integrantes: </p>
  <p>  - . </p>
  <p>  - . </p>
  <p>  - . </p>
  <br>
  <p> Mes y Año: Abril del 2026 </p>
</div>

---

# Registro de Versiones del Informe

<table>
  <tr>
    <th style="text-align:center;">Versión</th>
    <th style="text-align:center;">Fecha</th>
    <th style="text-align:center;">Autor</th>
    <th style="text-align:center;">Descripción de la modificación</th>
  </tr>
  <tr>
    <td align="center">TB1</td>
    <td>//2026</td>
    <td> Integrante <br> Integrante <br> Integrante <br> Integrante <br> Integrante </td>
    <td> Realizamos los capítulos ... según la rúbrica de manera conjunta y eficiente.  </td>
  </tr>
</table>

---

# Tabla de contenidos

- [ Universidad Peruana de Ciencias Aplicadas ](#-universidad-peruana-de-ciencias-aplicadas-)
    - [ Informe de Trabajo Final ](#-informe-de-trabajo-final-)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Tabla de contenidos](#tabla-de-contenidos)
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1 Startup Profile](#11-startup-profile)
        - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Nombre del Producto](#121-nombre-del-producto)
        - [1.2.2. Antecedentes y problemática](#122-antecedentes-y-problemática)
        - [1.2.3. Lean UX Process](#123-lean-ux-process)
            - [1.2.3.1. Lean UX Problem Statements](#1231-lean-ux-problem-statements)
            - [1.2.3.2. Lean UX Assumptions](#1232-lean-ux-assumptions)
            - [1.2.3.3. Lean UX Hypothesis Statements](#1233-lean-ux-hypothesis-statements)
            - [1.2.3.4. Lean UX Canvas](#1234-lean-ux-canvas)
    - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements & Analysis](#capítulo-ii-requirements--analysis)
   - [2.1. Competidores](#21-competidores)
   - [2.1.1 Analisis competitivo](#211-analisis-competitivo)
   - [2.1.2 Estrategias y tacticas frente a competidores](#212-estrategias-y-tacticas-frente-a-competidores)
   - [2.2. Entrevistas](#22-entrevistas)
   - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
   - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
   - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
   - [2.3. Needfinding](#23-needfinding)
      - [2.3.1. User Personas](#231-user-personas)
      - [2.3.2. User Task Matrix](#232-user-task-matrix)
      - [2.3.3. User Journey Map](#233-user-journey-map)
      - [2.3.4. Empathy Mapping](#234-empathy-mapping)
      - [2.3.5. Big Picture EventStorming ](#235-big-picture-eventstorming)
      - [2.3.6. Ubiquitous Language](#236-ubiquitous-language)
   - [2.4. Requirements specification](#24-requirements-specification)
      - [2.4.1. User Stories](#241-user-stories)
      - [2.4.2. Impact Mapping](#242-impact-mapping)
      - [2.4.3. Product Backlog](#243-product-backlog)
   - [2.5. Strategic-Level Domain-Driven Design](#25-strategic-level-domain-driven-design)
      - [2.5.1. EventStorming](#251-eventstorming)
         - [2.5.1.1. Candidate Context Discovery](#2511-candidate-context-discovery)
         - [2.5.1.2. Domain Message Flows Modeling](#2512-domain-message-flows-modeling)
         - [2.5.1.3. Bounded Context Canvases](#2513-bounded-context-canvases)
      - [2.5.2. Context Mapping](#252-context-mapping)
      - [2.5.3. Software Architecture](#253-software-architecture)
         - [2.5.3.1. Software Architecture Context Level Diagrams](#2531-software-architecture-context-level-diagrams)
         - [2.5.3.2. Software Architecture Container Level Diagrams](#2532-software-architecture-container-level-diagrams)
         - [2.5.3.3. Software Architecture Deployment Diagrams](#2533-software-architecture-deployment-diagrams)
      - [2.6 Tactical-Level Domain-Driven Design](#26-technical-level-domain-driven-design)
         - [2.6.1 Bounded Context:Identity and Access Managment](#261-bounded-context-Identity-and-Access-Managment)
            - [2.6.1.1. Domain Layer](#2611-domain-layer)
            - [2.6.1.2. Interface Layer](#2612-interface-layer)
            - [2.6.1.3. Application Layer](#2613-application-layer)
            - [2.6.1.4 Infrastructure Layer](#2614-infrastructure-layer)
            - [2.6.1.5 Bounded Context Software Architecture Component Level Diagrams](#2615-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.1.6 Bounded Context Software Architecture Code Level Diagrams](#2616-bounded-context-software-architecture-code-level-diagrams)
            - [2.6.1.6.1. Bounded Context Domain Layer Class Diagrams](#26161-bounded-context-domain-layer-class-diagrams)
            - [2.6.1.6.2. Bounded Context Database Design Diagram](#26162-bounded-context-database-design-diagram)
         - [2.6.2 Bounded Context:Profile and Preferences Management](#262-bounded-context-Profile-and-Preferences-Management)
            - [2.6.2.1. Domain Layer](#2621-domain-layer)
            - [2.6.2.2. Interface Layer](#2622-interface-layer)
            - [2.6.2.3. Application Layer](#2623-application-layer)
            - [2.6.2.4 Infrastructure Layer](#2624-infrastructure-layer)
            - [2.6.2.5 Bounded Context Software Architecture Component Level Diagrams](#2625-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.2.6 Bounded Context Software Architecture Code Level Diagrams](#2626-bounded-context-software-architecture-code-level-diagrams)
            - [2.6.2.6.1. Bounded Context Domain Layer Class Diagrams](#26261-bounded-context-domain-layer-class-diagrams)
            - [2.6.2.6.2. Bounded Context Database Design Diagram](#26262-bounded-context-database-design-diagram)
         - [2.6.3 Bounded Context:Location Managment](#263-bounded-context-Location-Managment)
            - [2.6.3.1. Domain Layer](#2631-domain-layer)
            - [2.6.3.2. Interface Layer](#2632-interface-layer)
            - [2.6.3.3. Application Layer](#2633-application-layer)
            - [2.6.3.4 Infrastructure Layer](#2634-infrastructure-layer)
            - [2.6.3.5 Bounded Context Software Architecture Component Level Diagrams](#2635-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.3.6 Bounded Context Software Architecture Code Level Diagrams](#2636-bounded-context-software-architecture-code-level-diagrams)
            - [2.6.3.6.1. Bounded Context Domain Layer Class Diagrams](#26361-bounded-context-domain-layer-class-diagrams)
            - [2.6.3.6.2.  Bounded Context Database Design Diagram](#26362--bounded-context-database-design-diagram)
         - [2.6.4 Bounded Context:Report Managment](#264-bounded-context-Report-Managment)
            - [2.6.4.1. Domain Layer](#2641-domain-layer)
            - [2.6.4.2. Interface Layer](#2642-interface-layer)
            - [2.6.4.3. Application Layer](#2643-application-layer)
            - [2.6.4.4 Infrastructure Layer](#2644-infrastructure-layer)
            - [2.6.4.5 Bounded Context Software Architecture Component Level Diagrams](#2645-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.4.6 Bounded Context Software Architecture Code Level Diagrams](#2646-bounded-context-software-architecture-code-level-diagrams)
            - [2.6.4.6.1. Bounded Context Domain Layer Class Diagrams](#26461-bounded-context-domain-layer-class-diagrams)
            - [2.6.4.6.2. Bounded Context Database Design Diagram](#26462-bounded-context-database-design-diagram)
         - [2.6.5 Bounded Context:Notification Managment](#265-bounded-context-Notification-Managment)
            - [2.6.5.1. Domain Layer](#2651-domain-layer)
            - [2.6.5.2. Interface Layer](#2652-interface-layer)
            - [2.6.5.3. Application Layer](#2653-application-layer)
            - [2.6.5.4 Infrastructure Layer](#2654-infrastructure-layer)
            - [2.6.5.5 Bounded Context Software Architecture Component Level Diagrams](#2655-bounded-context-software-architecture-component-level-diagrams)
            - [2.6.5.6 Bounded Context Software Architecture Code Level Diagrams](#2656-bounded-context-software-architecture-code-level-diagrams)
            - [2.6.5.6.1. Bounded Context Domain Layer Class Diagrams](#26561-bounded-context-domain-layer-class-diagrams)
            - [2.6.5.6.2. Bounded Context Database Design Diagram](#26562-bounded-context-database-design-diagram)


# Student Outcome

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias de
aprendizaje apropiadas.

ABET -- EAC - Student Outcome 

<table>
<colgroup>
<col style="width: 30%" />
<col style="width: 40%" />
<col style="width: 30%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>Criterio específico</strong></th>
<th><strong>Acciones Realizadas</strong></th>
<th><strong>Conclusiones</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Actualiza conceptos y
conocimientos necesarios para su
desarrollo profesional y en especial
para su proyecto en soluciones de
software.</td>
<td>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>         
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
</td>
<td>
<em><strong>TB1</strong></em>
<br>Contenido
<br>

<em><strong>TB2</strong></em>
<br>Contenido
<br>
</td>
</tr>
<tr class="even">
<td>Reconoce la necesidad del
aprendizaje permanente para el
desempeño profesional y el
desarrollo de proyectos en
soluciones de software.</td>
<td>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
            <strong>Integrante</strong> <br>
            TB1 <br> Contenido <br>
            TB2 <br> Contenido <br>
            TP1 <br> Contenido <br>
</td>
<td>
<em><strong>TB1</strong></em>
<br>Contenido<br>
<br>
<em><strong>TB2</strong></em>
<br>Contenido<br>
<br>
</td>

</tr>
</tbody>
</table>

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup
