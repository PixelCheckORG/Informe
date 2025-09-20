# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Arquitecturas De Software Emergentes - 7295</strong><br>
    <strong>Profesor: Royer Edelwer Rojas Malasquez </strong><br>
    <br><strong>INFORME</strong>
</p>
<h4 style="text-align: center;"><strong>Startup: Pixel Dev</strong></h4>

<h4 style="text-align: center;"><strong>Product: PixelCheck</strong></h4>


<div style="text-align: center;">


<h5 style="text-align: center;"> Team Members</h5>

<table style="margin-left: auto; margin-right: auto; text-align: center;">
  <thead>
    <tr>
      <th>Member</th>
      <th>Code</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Carmelino Dueñas, Michael Stefano</td>
      <td>U202212760</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
    <tr>
      <td>Párraga Gamarra, Paolo Gonzalo</td>
      <td>U202219186</td>
    </tr>
    <tr>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>

</div>

<div style="page-break-after: always;"></div>

# Registro de Versiones del Informe

<div align="center">


|**Versión**|**Fecha**|**Autor**|                                   **Descripción de modificación**                                   |
| :-: | :-: | :-: |:---------------------------------------------------------------------------------------------------:|
|1\.0|9/10/2025|Paolo Gonzalo Parraga Gamarra|                                 Redacción del perfil de la Startup.                                 |


</div>

# Project Report Collaboration Insights

## Repositorios:

- Informe: https://github.com/PixelCheckORG/Informe

<div style="page-break-after: always;"></div>

# Contenido

## Tabla de contenidos

- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integradores-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. Empathy Mapping](#233-empathy-mapping)
    - [2.3.4. As-is Scenario Mapping](#234-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Strategic-Level Software Design](#capítulo-iv-strategic-level-software-design)
  - [4.1. Strategic-Level Attribute-Driven Design](#41-strategic-level-attribute-driven-design)
    - [4.1.1. Design Purpose](#411-design-purpose)
    - [4.1.2. Attribute-Driven Design Inputs](#412-attribute-driven-design-inputs)
      - [4.1.2.1. Primary Functionality (Primary User Stories)](#4121-primary-functionality-primary-user-stories)
      - [4.1.2.2. Quality attribute Scenarios](#4122-quality-attribute-scenarios)
      - [4.1.2.3. Constraints](#4123-constraints)
    - [4.1.3. Architectural Drivers Backlog](#413-architectural-drivers-backlog)
    - [4.1.4. Architectural Design Decisions](#414-architectural-design-decisions)
    - [4.1.5. Quality Attribute Scenario Refinements](#415-quality-attribute-scenario-refinements)
  - [4.2. Strategic-Level Domain-Driven Design](#42-strategic-level-domain-driven-design)
    - [4.2.1. EventStorming](#421-eventstorming)
    - [4.2.2. Candidate Context Discovery](#422-candidate-context-discovery)
    - [4.2.3. Domain Message Flows Modeling](#423-domain-message-flows-modeling)
    - [4.2.4. Bounded Context Canvases](#424-bounded-context-canvases)
    - [4.2.5. Context Mapping](#425-context-mapping)
  - [4.3. Software Architecture](#43-software-architecture)
    - [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
    - [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
    - [4.3.3. Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
    - [4.3.4. Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)
- [Capítulo V: Tactical-Level Software Design](#capítulo-v-tactical-level-software-design)
  - [5.X. Bounded Context: [Bounded Context Name]](#5x-bounded-context-bounded-context-name)
    - [5.X.1. Domain Layer](#5x1-domain-layer)
    - [5.X.2. Interface Layer](#5x2-interface-layer)
    - [5.X.3. Application Layer](#5x3-application-layer)
    - [5.X.4. Infrastructure Layer](#5x4-infrastructure-layer)
    - [5.X.5. Bounded Context Software Architecture Component Level Diagrams](#5x5-bounded-context-software-architecture-component-level-diagrams)
    - [5.X.6. Bounded Context Software Architecture Code Level Diagrams](#5x6-bounded-context-software-architecture-code-level-diagrams)
      - [5.X.6.1. Bounded Context Domain Layer Class Diagrams](#5x61-bounded-context-domain-layer-class-diagrams)
      - [5.X.6.2. Bounded Context Database Design Diagram](#5x62-bounded-context-database-design-diagram)
- [Capítulo VI: Solution UX Design](#capítulo-vi-solution-ux-design)
  - [6.1. Style Guidelines](#61-style-guidelines)
    - [6.1.1. General Style Guidelines](#611-general-style-guidelines)
    - [6.1.2. Web, Mobile & Devices Style Guidelines](#612-web-mobile--devices-style-guidelines)
  - [6.2. Information Architecture](#62-information-architecture)
    - [6.2.1. Labeling Systems](#621-labeling-systems)
    - [6.2.2. Searching Systems](#622-searching-systems)
    - [6.2.3. SEO Tags and Meta Tags](#623-seo-tags-and-meta-tags)
    - [6.2.4. Navigation Systems](#624-navigation-systems)
  - [6.3. Landing Page UI Design](#63-landing-page-ui-design)
    - [6.3.1. Landing Page Wireframe](#631-landing-page-wireframe)
    - [6.3.2. Landing Page Mock-up](#632-landing-page-mock-up)
  - [6.4. Applications UX/UI Design](#64-applications-uxui-design)
    - [6.4.1. Applications Wireframes](#641-applications-wireframes)
    - [6.4.2. Applications Wireflow Diagrams](#642-applications-wireflow-diagrams)
    - [6.4.3. Applications Mock-ups](#643-applications-mock-ups)
    - [6.4.4. Applications User Flow Diagrams](#644-applications-user-flow-diagrams)
  - [6.5. Applications Prototyping](#65-applications-prototyping)
- [Capítulo VII: Product Implementation, Validation & Deployment](#capítulo-vii-product-implementation-validation--deployment)
  - [7.1. Software Configuration Management](#71-software-configuration-management)
    - [7.1.1. Software Development Environment Configuration](#711-software-development-environment-configuration)
    - [7.1.2. Source Code Management](#712-source-code-management)
    - [7.1.3. Source Code Style Guide & Conventions](#713-source-code-style-guide--conventions)
    - [7.1.4. Software Deployment Configuration](#714-software-deployment-configuration)
  - [7.2. Solution Implementation](#72-solution-implementation)
    - [7.2.X. Sprint n](#72x-sprint-n)
      - [7.2.X.1. Sprint Planning n](#72x1-sprint-planning-n)
      - [7.2.X.2. Sprint Backlog n](#72x2-sprint-backlog-n)
      - [7.2.X.3. Development Evidence for Sprint Review](#72x3-development-evidence-for-sprint-review)
      - [7.2.X.4. Testing Suite Evidence for Sprint Review](#72x4-testing-suite-evidence-for-sprint-review)
      - [7.2.X.5. Execution Evidence for Sprint Review](#72x5-execution-evidence-for-sprint-review)
      - [7.2.X.6. Services Documentation Evidence for Sprint Review](#72x6-services-documentation-evidence-for-sprint-review)
      - [7.2.X.7. Software Deployment Evidence for Sprint Review](#72x7-software-deployment-evidence-for-sprint-review)
      - [7.2.X.8. Team Collaboration Insights during Sprint](#72x8-team-collaboration-insights-during-sprint)
  - [7.3. Validation Interviews](#73-validation-interviews)
    - [7.3.1. Diseño de Entrevistas](#731-diseño-de-entrevistas)
    - [7.3.2. Registro de Entrevistas](#732-registro-de-entrevistas)
    - [7.3.3. Evaluaciones según heurísticas](#733-evaluaciones-según-heurísticas)
  - [7.4. Video About-the-Product](#74-video-about-the-product)

<div style="page-break-after: always;"></div>

# Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

Criterio: Capacidad de comunicarse efectivamente con un rango de audiencias.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

| **Criterio Específico** | **Acciones Realizadas** | **Conclusiones** |
|-------------------------|-------------------------|------------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. |  <br>**TB1:**<br>  <br>**TP1:**<br>  <br>**TB2:**<br>  <br>**TF1:**<br>| |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. |  <br>**TB1:**<br>  <br>**TP1:**<br>  <br>**TB2:**<br>  <br>**TF1:**<br>|  |

<div style="page-break-after: always;"></div>

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

[Content for startup description]

### 1.1.2. Perfiles de integrantes del equipo

[Content for team member profiles]

## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

[Content for background and problem statement]

### 1.2.2. Lean UX Process

#### 1.2.2.1. Lean UX Problem Statements

[Content for Lean UX problem statements]

#### 1.2.2.2. Lean UX Assumptions

[Content for Lean UX assumptions]

#### 1.2.2.3. Lean UX Hypothesis Statements

[Content for Lean UX hypothesis statements]

#### 1.2.2.4. Lean UX Canvas

[Content for Lean UX canvas]

## 1.3. Segmentos objetivo

[Content for target segments]

<div style="page-break-after: always;"></div>

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo

[Content for competitive analysis]

### 2.1.2. Estrategias y tácticas frente a competidores

[Content for competitive strategies and tactics]

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

[Content for interview design]

### 2.2.2. Registro de entrevistas

[Content for interview records]

### 2.2.3. Análisis de entrevistas

[Content for interview analysis]

## 2.3. Needfinding

### 2.3.1. User Personas

[Content for user personas]

### 2.3.2. User Task Matrix

[Content for user task matrix]

### 2.3.3. Empathy Mapping

[Content for empathy mapping]

### 2.3.4. As-is Scenario Mapping

[Content for as-is scenario mapping]

## 2.4. Ubiquitous Language

[Content for ubiquitous language]

<div style="page-break-after: always;"></div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping

[Content for to-be scenario mapping]

## 3.2. User Stories

[Content for user stories]

## 3.3. Impact Mapping

[Content for impact mapping]

## 3.4. Product Backlog

[Content for product backlog]

<div style="page-break-after: always;"></div>

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

En esta sección se evidencia el proceso de Attribute-Driven Design (ADD) aplicado a PixelCheck bajo un enfoque Domain-Driven. Se conectan las necesidades del negocio y de los segmentos objetivo con decisiones arquitectónicas. Se documenta el propósito del diseño, los Inputs (funcionales y de calidad), los drivers arquitectónicos, decisiones clave, escenarios de calidad y se referencia las vistas iniciales de arquitectura de alto nivel.

### 4.1.1. Design Purpose

El propósito del proceso de diseño de PixelCheck es desarrollar una arquitectura de software robusta y escalable que aborde la problemática crítica de la verificación de autenticidad de imágenes en el contexto actual de proliferación de contenido generado por inteligencia artificial.
La arquitectura debe estar orientada a satisfacer las necesidades específicas de dos segmentos objetivo claramente diferenciados: los usuarios generales de internet que requieren verificación rápida y simple de contenido visual, y los profesionales de medios y comunicación que necesitan herramientas avanzadas de análisis y documentación.
El proceso de diseño busca crear una solución que combine eficiencia operativa con precisión técnica, garantizando que la detección de imágenes generadas por IA sea accesible para usuarios sin conocimientos técnicos, mientras proporciona la profundidad analítica requerida por profesionales del sector mediático. La arquitectura resultante debe soportar el crecimiento del negocio y la evolución tecnológica, manteniendo la confiabilidad y seguridad necesarias para generar credibilidad en un dominio donde la veracidad de la información es fundamental.

### 4.1.2. Attribute-Driven Design Inputs

Esta sección presenta los tres tipos de inputs fundamentales para el proceso de diseño con ADD: la funcionalidad primaria derivada de los requisitos más críticos del sistema, los escenarios de atributos de calidad que determinan las características no funcionales, y las restricciones técnicas y de negocio que delimitan el espacio de solución.

#### 4.1.2.1. Primary Functionality (Primary User Stories)

Los requisitos funcionales seleccionados representan las capacidades core del sistema PixelCheck, priorizadas por su impacto directo en la arquitectura y su criticidad para el éxito de la solución. Estas funcionalidades abarcan desde las operaciones básicas de análisis hasta las capacidades avanzadas requeridas por usuarios profesionales.

A continuación se listan las historias / epics que tienen mayor impacto en la arquitectura

<table>
  <thead>
    <tr>
      <th>Epic / User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HU01</td>
      <td>Cargar imagen para análisis</td>
      <td>El sistema debe aceptar imágenes subidas por usuarios (móvil/desktop) y entregarlas al pipeline de análisis.</td>
      <td>POST /images acepta JPG/PNG/WEBP, devuelve jobId o resultado, respuesta inicial &lt; 2s.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU02</td>
      <td>Analizar imagen con algoritmo ML</td>
      <td>Ejecutar inferencia (modelo) y devolver probabilidad y artefactos explicativos.</td>
      <td>Resultado con % confianza y explain artifacts; p95 latency ≤ 10s (MVP objetivo).</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU03</td>
      <td>Visualizar resultados detallados</td>
      <td>Mostrar resultado, % confianza y explicación (mapa de calor, features, metadatos).</td>
      <td>UI muestra resultado legible y artefactos descargables; endpoint /results/{id} disponible.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU21 / HU22</td>
      <td>Registro / Inicio de sesión</td>
      <td>Gestión de cuentas y sesiones (IAM).</td>
      <td>Registro, login, JWT; roles general / profesional; endpoints auth protegidos.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU15</td>
      <td>Validar formato antes de análisis</td>
      <td>Validación previa de formato y tamaño para evitar overloading del pipeline.</td>
      <td>Rechazo con mensaje claro si &gt;10MB o formato no soportado.</td>
      <td>EP01 / TS01</td>
    </tr>
    <tr>
      <td>HU18</td>
      <td>Análisis por lotes</td>
      <td>Capacidad de análisis en lote para profesionales.</td>
      <td>Enqueue de hasta N imágenes; status por item; throughput medible.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>HU19</td>
      <td>Reportes profesionales</td>
      <td>Generación de reportes PDF con metadata y evidencias.</td>
      <td>Endpoint para generar/reportar; export PDF con datos y fecha.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Logging y observabilidad</td>
      <td>Sistema central de logs y métricas.</td>
      <td>Application Insights integrado; logs estructurados y alertas.</td>
      <td>—</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Compresión automática</td>
      <td>Redimensionado y compresión para imágenes grandes.</td>
      <td>Imagen &gt;1920x1080 autocoms; calidad min 85%; tiempo de preprocessing &lt; 1s.</td>
      <td>—</td>
    </tr>
  </tbody>
</table>


A continuación se listan las historias / epics que tienen mayor impacto en la arquitectura

<table>
  <thead>
    <tr>
      <th>Epic / User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>HU01</td>
      <td>Cargar imagen para análisis</td>
      <td>El sistema debe aceptar imágenes subidas por usuarios (móvil/desktop) y entregarlas al pipeline de análisis.</td>
      <td>POST /images acepta JPG/PNG/WEBP, devuelve jobId o resultado, respuesta inicial &lt; 2s.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU02</td>
      <td>Analizar imagen con algoritmo ML</td>
      <td>Ejecutar inferencia (modelo) y devolver probabilidad y artefactos explicativos.</td>
      <td>Resultado con % confianza y explain artifacts; p95 latency ≤ 10s (MVP objetivo).</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU03</td>
      <td>Visualizar resultados detallados</td>
      <td>Mostrar resultado, % confianza y explicación (mapa de calor, features, metadatos).</td>
      <td>UI muestra resultado legible y artefactos descargables; endpoint /results/{id} disponible.</td>
      <td>EP01</td>
    </tr>
    <tr>
      <td>HU21 / HU22</td>
      <td>Registro / Inicio de sesión</td>
      <td>Gestión de cuentas y sesiones (IAM).</td>
      <td>Registro, login, JWT; roles general / profesional; endpoints auth protegidos.</td>
      <td>EP04</td>
    </tr>
    <tr>
      <td>HU15</td>
      <td>Validar formato antes de análisis</td>
      <td>Validación previa de formato y tamaño para evitar overloading del pipeline.</td>
      <td>Rechazo con mensaje claro si &gt;10MB o formato no soportado.</td>
      <td>EP01 / TS01</td>
    </tr>
    <tr>
      <td>HU18</td>
      <td>Análisis por lotes</td>
      <td>Capacidad de análisis en lote para profesionales.</td>
      <td>Enqueue de hasta N imágenes; status por item; throughput medible.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>HU19</td>
      <td>Reportes profesionales</td>
      <td>Generación de reportes PDF con metadata y evidencias.</td>
      <td>Endpoint para generar/reportar; export PDF con datos y fecha.</td>
      <td>EP02</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Logging y observabilidad</td>
      <td>Sistema central de logs y métricas.</td>
      <td>Application Insights integrado; logs estructurados y alertas.</td>
      <td>—</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Compresión automática</td>
      <td>Redimensionado y compresión para imágenes grandes.</td>
      <td>Imagen &gt;1920x1080 autocoms; calidad min 85%; tiempo de preprocessing &lt; 1s.</td>
      <td>—</td>
    </tr>
  </tbody>
</table>


#### 4.1.2.2. Quality attribute Scenarios

A continuación se definen los escenarios de atributos de calidad.

Tabla de Quality Attribute Scenarios:

<table>
  <thead>
    <tr>
      <th>Atributo</th>
      <th>Fuente</th>
      <th>Estímulo</th>
      <th>Artefacto</th>
      <th>Entorno</th>
      <th>Respuesta</th>
      <th>Medida</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Latencia (Rendimiento)</td>
      <td>Usuario final</td>
      <td>Subida de imagen (≤ 8MB) y petición de análisis</td>
      <td>Endpoint /analyze</td>
      <td>Condición normal (no pico)</td>
      <td>Crear job y devolver resultado en ≤10s</td>
      <td>p95 latency ≤ 10s</td>
    </tr>
    <tr>
      <td>Escalabilidad</td>
      <td>Varios usuarios</td>
      <td>100 requests concurrentes de análisis</td>
      <td>Worker pool / API</td>
      <td>Picos de tráfico</td>
      <td>Scale horizontal del backend/workers; jobs encolados</td>
      <td>Throughput / latencia p95 &lt; 20s</td>
    </tr>
    <tr>
      <td>Disponibilidad</td>
      <td>Usuario</td>
      <td>Petición a /results</td>
      <td>Backend API</td>
      <td>Falla de instancia</td>
      <td>Failover a instancias saludables; mantener servicio</td>
      <td>Uptime ≥ 99.5%</td>
    </tr>
    <tr>
      <td>Seguridad</td>
      <td>Atacante externo</td>
      <td>Petición no autorizada a /history</td>
      <td>API + BD</td>
      <td>Producción</td>
      <td>Rechazar petición; log y alert</td>
      <td>0 accesos no autorizados; registro de intento</td>
    </tr>
    <tr>
      <td>Precisión (ML)</td>
      <td>Equipo de QA</td>
      <td>Dataset de validación</td>
      <td>Modelo ML</td>
      <td>Condiciones controladas</td>
      <td>Modelo clasifica IA vs real</td>
      <td>Objetivo inicial prec. ≥ 90% en dataset</td>
    </tr>
    <tr>
      <td>Observabilidad</td>
      <td>Operaciones</td>
      <td>Picos de latencia / errores</td>
      <td>Monitoring</td>
      <td>Producción</td>
      <td>Alertas y trazas; RCA en &lt; 30 min</td>
      <td>—</td>
    </tr>
  </tbody>
</table>

#### 4.1.2.3. Constraints

Eestas restricciones son impuestas por alcance del proyecto, presupuesto y decisiones de infraestructura.

<table>
  <thead>
    <tr>
      <th>Technical Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>C01</td>
      <td>Stack Backend</td>
      <td>Backend en Python (Django) para acelerar IAM y APIs</td>
      <td>Repositorio con Django + DRF; endpoints auth listos</td>
      <td>HU21/HU22</td>
    </tr>
    <tr>
      <td>C02</td>
      <td>Persistencia única (MVP)</td>
      <td>Usar Azure Database for MySQL como BD principal</td>
      <td>DB disponible en Azure; tablas users, images, analysis</td>
      <td>HU01 / HU02</td>
    </tr>
    <tr>
      <td>C03</td>
      <td>ML embebido (MVP)</td>
      <td>El modelo ML se despliega en App Service inicialmente</td>
      <td>Inference en App Service sin servicio externo</td>
      <td>HU02</td>
    </tr>
    <tr>
      <td>C04</td>
      <td>No GPUs dedicadas (fase 1)</td>
      <td>No provisionar GPU en MVP (cost constraint)</td>
      <td>Inferencia CPU; tiempos medidos aceptables</td>
      <td>HU02</td>
    </tr>
    <tr>
      <td>C05</td>
      <td>CI/CD obligatorio</td>
      <td>Usar GitHub Actions para build/deploy</td>
      <td>Pipelines que despliegan a App Service / Firebase / GH Pages</td>
      <td>TS03</td>
    </tr>
    <tr>
      <td>C06</td>
      <td>Protección de secretos</td>
      <td>Usar KeyVault/Environment vars para secrets</td>
      <td>Credenciales no en repositorio; tests de secrets fail</td>
      <td>TS03</td>
    </tr>
  </tbody>
</table>


### 4.1.3. Architectural Drivers Backlog

El backlog recoge drivers funcionales, drivers de calidad y constraints, ordenados por importancia e impacto.

<table>
  <thead>
    <tr>
      <th>Driver ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Importancia (Stakeholders)</th>
      <th>Impacto en Complexity</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>D1</td>
      <td>Análisis rápido (latencia)</td>
      <td>Responder análisis en ≤10s p95</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>D2</td>
      <td>Precisión del detector</td>
      <td>Modelo objetivo ≥ 90% en dataset</td>
      <td>High</td>
      <td>High</td>
    </tr>
    <tr>
      <td>D3</td>
      <td>Explicabilidad y reportes</td>
      <td>Generar artefactos explicativos y PDFs</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D4</td>
      <td>Escalabilidad por demanda</td>
      <td>Soportar cargas concurrentes (batch)</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D5</td>
      <td>Seguridad y privacidad</td>
      <td>Autenticación, cifrado y control de roles</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D6</td>
      <td>Observabilidad y operabilidad</td>
      <td>Logs, métricas y alertas</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D7</td>
      <td>Simplicidad operacional (cost)</td>
      <td>Mantener coste razonable en MVP</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D8</td>
      <td>Evolución hacia ML servicio</td>
      <td>Capacidad de extraer ML a servicio dedicado</td>
      <td>Medium</td>
      <td>Medium</td>
    </tr>
    <tr>
      <td>D9</td>
      <td>Persistencia y consistencia</td>
      <td>Integridad de historiales y reportes</td>
      <td>High</td>
      <td>Medium</td>
    </tr>
  </tbody>
</table>


### 4.1.4. Architectural Design Decisions

Para cada driver clave evaluamos patrones candidatos (3 por driver relevante) y elegimos la opción que cumple los trade-offs del MVP y la evolución futura.

**Decisión global (resumen)**

- **Backend:** Django + Django REST Framework por rapidez en desarrollo, soluciones out-of-the-box para IAM y ORM.

- **ML:** modelo inicialmente embebido en App Service (menor complejidad). Diseño modular para extraerlo a servicio (ACI / Azure ML) cuando sea necesario.

- **Procesamiento asíncrono:** Celery + Redis para jobs de inferencia y generación de reports (desvincula tiempos de HTTP).

- **Persistencia:** Azure MySQL para entidades; en producción se recomienda usar Blob Storage para imágenes grandes y una colección JSON para features si se requiere.

- **CI/CD:** GitHub Actions pipelines (landing → GitHub Pages, frontend → Firebase, backend → Azure App Service).

<h3>Candidate Pattern Evaluation Matrix (selección de 3 drivers clave)</h3>

<h4>Driver D1 — Análisis rápido (latencia)</h4>
<table>
  <thead>
    <tr>
      <th>Pattern</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>A. Modelo embebido en App Service (single process)</td>
      <td>Menor latencia por llamada local; despliegue simple</td>
      <td>Carga en App Service; menos flexible para escalar GPU</td>
    </tr>
    <tr>
      <td>B. Servicio ML separado (microservicio en Flask/FastAPI)</td>
      <td>Independencia, posibilidad de escalar por separado</td>
      <td>Comunicación HTTP extra → latencia; mayor complejidad</td>
    </tr>
    <tr>
      <td>C. Serverless inference (Function / Azure ML endpoint)</td>
      <td>Auto-scaling y pay-per-use</td>
      <td>Cold starts, integración más compleja, coste variable</td>
    </tr>
  </tbody>
</table>
<p><strong>Decisión:</strong> A para MVP (embebido) por simplicidad y menor overhead; diseño modular para migrar a B o C si escala.</p>

<h4>Driver D2 — Escalabilidad / Batch processing</h4>
<table>
  <thead>
    <tr>
      <th>Pattern</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>A. Celery + Redis (workers)</td>
      <td>Control de concurrency, retrys, priorización</td>
      <td>Requiere infraestructura adicional (Redis)</td>
    </tr>
    <tr>
      <td>B. Threaded worker dentro del proceso web</td>
      <td>Simple, menos infra</td>
      <td>Bloqueo de requests, mala escalabilidad</td>
    </tr>
    <tr>
      <td>C. Serverless jobs (cloud functions)</td>
      <td>Escala automática</td>
      <td>Mayor complejidad en orchestration y tracking</td>
    </tr>
  </tbody>
</table>
<p><strong>Decisión:</strong> A Celery + Redis (balance entre control y complejidad) para manejar lotes y jobs asíncronos; permite medir y priorizar.</p>

<h4>Driver D3 — Almacenamiento de artefactos y features</h4>
<table>
  <thead>
    <tr>
      <th>Pattern</th>
      <th>Pro</th>
      <th>Con</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>A. MySQL + JSON columns</td>
      <td>Fácil gestión, single DB</td>
      <td>No óptimo para vectores/embeddings grandes</td>
    </tr>
    <tr>
      <td>B. MySQL + Blob Storage (imágenes)</td>
      <td>Eficiente en almacenamiento de binarios</td>
      <td>Gestión adicional de storage/ACL</td>
    </tr>
    <tr>
      <td>C. MySQL + NoSQL (Mongo/Elastic)</td>
      <td>Flexible para features y búsquedas</td>
      <td>Complejidad en consistencia y operaciones</td>
    </tr>
  </tbody>
</table>
<p><strong>Decisión:</strong> B (MySQL como fuente de verdad + Blob Storage para imágenes) en producción; en MVP usar MySQL (referencias) y dejar Blob Storage como próxima iteración si el tamaño/volumen lo exige.</p>


### 4.1.5. Quality Attribute Scenario Refinements

Tras el taller de atributos de calidad se priorizó favorecer la experiencia interactiva (baja latencia) y la precisión / explicabilidad del detector, seguido por la capacidad de procesamiento por lotes para profesionales y la seguridad de acceso a historiales. Las decisiones resultantes favorecen una arquitectura con inferencia rápida (modelo embebido en MVP), procesamiento asíncrono (cola + workers) y trazabilidad/artefactos explicativos almacenados junto al resultado.

<section>
  <h3>Scenario Refinement for Scenario 1 — Latencia interactiva</h3>
  <table>
    <thead>
      <tr>
        <th>Campo</th>
        <th>Detalle</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Scenario(s):</td>
        <td>Respuesta de análisis interactivo para usuario general (HU01, HU02, HU03).</td>
      </tr>
      <tr>
        <td>Business Goals:</td>
        <td>Ofrecer una experiencia inmediata que permita a usuarios generales obtener veredicto y confianza en el resultado sin esperar.</td>
      </tr>
      <tr>
        <td>Relevant Quality Attributes:</td>
        <td>Performance / Latency, Availability, Usability.</td>
      </tr>
      <tr>
        <td>Stimulus:</td>
        <td>Usuario sube una imagen ≤ 8 MB y solicita análisis.</td>
      </tr>
      <tr>
        <td>Scenario Components:</td>
        <td>Stimulus Source: Navegador (usuario general).</td>
      </tr>
      <tr>
        <td>Environment:</td>
        <td>Condiciones normales (carga media, no pico extremo).</td>
      </tr>
      <tr>
        <td>Artifact (if Known):</td>
        <td>Endpoint <code>POST /analyze</code>, servicio Backend API, worker de inferencia ML.</td>
      </tr>
      <tr>
        <td>Response:</td>
        <td>El sistema encola (o procesa) y entrega resultado (probabilidad + explicación breve) y/o jobId; UI muestra progreso. Resultado final disponible en tiempo interactivo.</td>
      </tr>
      <tr>
        <td>Response Measure:</td>
        <td>p95 latency ≤ 10 segundos; success rate ≥ 95% (jobs completados sin error).</td>
      </tr>
      <tr>
        <td>Questions:</td>
        <td>
          <ul>
            <li>¿Resultado síncrono o asíncrono por defecto?</li>
            <li>¿Tolerancia de UX a respuestas parciales?</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Issues:</td>
        <td>
          <ul>
            <li>Inferencia sin GPU puede limitar latencia.</li>
            <li>Trade-off entre explicación rica (mapas de calor) y tiempo de respuesta.</li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</section>

<section>
  <h3>Scenario Refinement for Scenario 2 — Precisión y Explicabilidad (para profesionales)</h3>
  <table>
    <thead>
      <tr>
        <th>Campo</th>
        <th>Detalle</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Scenario(s):</td>
        <td>Revisión editorial de imagen para publicación, donde el profesional requiere evidencia (HU02, HU03, HU19).</td>
      </tr>
      <tr>
        <td>Business Goals:</td>
        <td>Entregar una decisión con nivel de confianza y evidencia suficiente para que un profesional tome una decisión editorial informada.</td>
      </tr>
      <tr>
        <td>Relevant Quality Attributes:</td>
        <td>Accuracy (Precision), Explainability, Traceability.</td>
      </tr>
      <tr>
        <td>Stimulus:</td>
        <td>Un profesional solicita análisis detallado de una imagen (single o lote pequeño) y requiere reporte descargable.</td>
      </tr>
      <tr>
        <td>Scenario Components:</td>
        <td>Stimulus Source: Usuario Profesional (WebApp autenticado con rol).</td>
      </tr>
      <tr>
        <td>Environment:</td>
        <td>Entorno de edición / flujo editorial (no necesariamente bajo pico).</td>
      </tr>
      <tr>
        <td>Artifact (if Known):</td>
        <td>Image Analysis (ML) BC, Results &amp; Reporting BC; generación de explain artifacts (heatmap, features list) y PDF de reporte.</td>
      </tr>
      <tr>
        <td>Response:</td>
        <td>Modelo devuelve % confianza, versión de modelo, features determinantes y artefactos explicativos; Results genera reporte con metadatos y evidencia.</td>
      </tr>
      <tr>
        <td>Response Measure:</td>
        <td>Precisión objetivo inicial ≥ 90% en dataset de validación; reporte contiene mínimo 2 features explicativos + metadatos; tiempo de generación del reporte ≤ 30s (MVP objetivo para single image).</td>
      </tr>
      <tr>
        <td>Questions:</td>
        <td>
          <ul>
            <li>¿Qué formato mínimo de evidencia aceptan los profesionales?</li>
            <li>¿Necesitamos certificación/firmado en reportes?</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Issues:</td>
        <td>
          <ul>
            <li>Explicabilidad puede requerir cálculos adicionales que aumentan latencia.</li>
            <li>Mantener versioning del modelo para trazabilidad.</li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</section>

<section>
  <h3>Scenario Refinement for Scenario 3 — Procesamiento por Lotes (Profesionales)</h3>
  <table>
    <thead>
      <tr>
        <th>Campo</th>
        <th>Detalle</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Scenario(s):</td>
        <td>Envío de lote de imágenes (ej. 20–100) para análisis por parte de un profesional o equipo (HU18, HU19).</td>
      </tr>
      <tr>
        <td>Business Goals:</td>
        <td>Permitir procesar volúmenes medios de imágenes con trazabilidad por item y generación de reportes agregados.</td>
      </tr>
      <tr>
        <td>Relevant Quality Attributes:</td>
        <td>Scalability, Throughput, Reliability.</td>
      </tr>
      <tr>
        <td>Stimulus:</td>
        <td>Usuario profesional sube un lote de N imágenes y solicita procesamiento por lotes.</td>
      </tr>
      <tr>
        <td>Scenario Components:</td>
        <td>Stimulus Source: WebApp autenticada (Usuario Profesional).</td>
      </tr>
      <tr>
        <td>Environment:</td>
        <td>Horario laboral con picos (varios usuarios enviando lotes).</td>
      </tr>
      <tr>
        <td>Artifact (if Known):</td>
        <td>Ingestion BC encola ImageValidated por imagen; Celery + Redis como cola; pool de workers (Analysis BC).</td>
      </tr>
      <tr>
        <td>Response:</td>
        <td>El sistema encola cada imagen como job; workers procesan en paralelo; Results actualiza estado por imagen; al finalizar se genera reporte por lote (PDF/CSV).</td>
      </tr>
      <tr>
        <td>Response Measure:</td>
        <td>Throughput objetivo inicial: ~5 imágenes / worker / minuto; todos los items deben completar con estado (processed/failed) y con posibilidad de retry; tiempo total depende de workers asignados pero UI debe mostrar progresos y ETA.</td>
      </tr>
      <tr>
        <td>Questions:</td>
        <td>
          <ul>
            <li>¿Cuál es el tamaño máximo del lote por request?</li>
            <li>¿Prioridad entre jobs?</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Issues:</td>
        <td>
          <ul>
            <li>Coste de escalado de workers.</li>
            <li>Idempotencia y manejo de retries.</li>
            <li>Necesidad de monitoreo de cola para evitar backlogs.</li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</section>

<section>
  <h3>Scenario Refinement for Scenario 4 — Seguridad: Acceso a Historial</h3>
  <table>
    <thead>
      <tr>
        <th>Campo</th>
        <th>Detalle</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Scenario(s):</td>
        <td>Intento de acceso no autorizado al historial de análisis o reportes (HU11, HU23, HU25).</td>
      </tr>
      <tr>
        <td>Business Goals:</td>
        <td>Proteger datos sensibles y asegurar que sólo usuarios con rol adecuado puedan ver historiales y reportes; auditar accesos.</td>
      </tr>
      <tr>
        <td>Relevant Quality Attributes:</td>
        <td>Security, Privacy, Auditability.</td>
      </tr>
      <tr>
        <td>Stimulus:</td>
        <td>Petición a <code>GET /history</code> o <code>GET /reports/{id}</code> con token inválido o rol insuficiente.</td>
      </tr>
      <tr>
        <td>Scenario Components:</td>
        <td>Stimulus Source: Cliente/Atacante (petición HTTP).</td>
      </tr>
      <tr>
        <td>Environment:</td>
        <td>Producción (exposición pública).</td>
      </tr>
      <tr>
        <td>Artifact (if Known):</td>
        <td>IAM BC (auth/authorization), Backend API, DB MySQL (results/reports).</td>
      </tr>
      <tr>
        <td>Response:</td>
        <td>Rechazar con 401/403; registrar evento en System Management (logs) con user/token/ip; si patrón anómalo, disparar alerta a ops.</td>
      </tr>
      <tr>
        <td>Response Measure:</td>
        <td>100% de accesos no autorizados denegados; todos los intentos registrados con timestamp y metadata; alertas generadas en caso de umbral de intentos anómalos.</td>
      </tr>
      <tr>
        <td>Questions:</td>
        <td>
          <ul>
            <li>¿Periodo de retención de logs?</li>
            <li>¿Necesidad de cumplimiento legal (p. ej. GDPR) para datos de usuarios?</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td>Issues:</td>
        <td>
          <ul>
            <li>Gestión segura de secrets (KeyVault) y rotación.</li>
            <li>Tasa de falsos positivos en detección de anomalías que puede generar ruido en alertas.</li>
          </ul>
        </td>
      </tr>
    </tbody>
  </table>
</section>

## 4.2. Strategic-Level Domain-Driven Design

### 4.2.1. EventStorming

[Content for event storming]

### 4.2.2. Candidate Context Discovery

[Content for candidate context discovery]

### 4.2.3. Domain Message Flows Modeling

[Content for domain message flows modeling]

### 4.2.4. Bounded Context Canvases

[Content for bounded context canvases]

### 4.2.5. Context Mapping

[Content for context mapping]

## 4.3. Software Architecture

### 4.3.1. Software Architecture System Landscape Diagram

Este diagrama muestra que el sistema PixelCheck opera en un ecosistema compuesto por dos tipos de usuarios: Usuarios Generales y Profesionales de Medios. Los Usuarios Generales interactúan con la plataforma subiendo imágenes para verificar su autenticidad, recibiendo resultados básicos que indican si la imagen fue generada por inteligencia artificial o no. Por otro lado, los Profesionales de Medios utilizan el sistema para acceder a funcionalidades avanzadas, como análisis detallados, reportes personalizados y visualización de metadatos, lo que les permite contar con información más completa y confiable para su trabajo. Ambos perfiles acceden a PixelCheck a través de la plataforma web, que centraliza la lógica de verificación y adapta las funcionalidades de acuerdo con el tipo de usuario.

<img src="https://i.ibb.co/jZZTnkPs/Ladnscape-Pixel.png" alt="Ladnscape-Pixel" border="0">

### 4.3.2. Software Architecture Context Level Diagrams

Este diagrama muestra que el sistema PixelCheck (representado como una única entidad) interactúa con dos tipos de usuarios principales:

- Usuario General, que sube imágenes a la plataforma web y recibe resultados básicos sobre su autenticidad (si fue generada por inteligencia artificial o si es una imagen real).

- Profesional de Medios, que requiere un análisis más avanzado y la generación de reportes detallados que le permitan validar la confiabilidad de material gráfico antes de su difusión o uso en investigaciones.

De esta forma, el diagrama de contexto refleja cómo los distintos tipos de usuarios se relacionan con PixelCheck, manteniendo una visión general sin entrar aún en los detalles de los contenedores internos.

<img src="https://i.ibb.co/kgw6hLXG/contexto.png" alt="context-c4" border="0">


### 4.3.3. Software Architecture Container Level Diagrams

Este diagrama muestra que el sistema PixelCheck está compuesto por varios contenedores principales que trabajan en conjunto para ofrecer la verificación de imágenes:

- Landing Page, desarrollada en HTML, CSS y JavaScript, sirve como la puerta de entrada al sistema. Presenta el producto, informa a los usuarios sobre las funcionalidades de PixelCheck y redirige hacia la aplicación principal.

- Aplicación Web, construida con un framework moderno de frontend (React/Vue/Angular), que provee una interfaz responsiva para que los usuarios suban imágenes, consulten resultados básicos o generen reportes avanzados.

- Backend API, implementada en Python con Django, que concentra la lógica de negocio del sistema. Dentro de esta API se encuentran los bounded contexts encargados de:

  - Procesar imágenes y ejecutar el modelo de Machine Learning.

  - Gestionar usuarios, sesiones y permisos.

  - Generar y almacenar reportes de verificación.

- Base de Datos MySQL, que almacena usuarios, metadatos, resultados de los análisis y el historial de verificaciones realizadas.

Los usuarios acceden primero a la Landing Page, desde la cual se redirigen a la Web App. Esta se comunica con la Backend API a través de llamadas REST/JSON, y la API, a su vez, interactúa con la Base de Datos para leer o almacenar información según sea necesario.

<img src="https://i.ibb.co/zVCpdG1q/contianer-pixel.png" alt="contaner-c4" border="0">

### 4.3.4. Software Architecture Deployment Diagrams

Este diagrama muestra cómo el sistema PixelCheck se despliega en diferentes entornos y servicios de infraestructura en la nube:

- En Microsoft Azure, se utiliza un App Service para desplegar el Backend API desarrollado en Python Django, el cual contiene la lógica de negocio y el modelo de Machine Learning encargado de verificar imágenes. Además, en el mismo entorno se encuentra el servicio Azure Database for MySQL, que aloja la base de datos donde se almacenan usuarios, resultados de análisis e historial de reportes.

- En la capa de Frontends, la aplicación web (PixelCheck WebApp), desarrollada con React, se aloja en Firebase Hosting, permitiendo a los usuarios interactuar de manera responsiva desde navegadores. A su vez, la Landing Page, estática y ligera (HTML, CSS, JS), se encuentra desplegada en GitHub Pages, funcionando como puerta de entrada para dar a conocer el servicio antes de redirigir al usuario hacia la aplicación principal.

- Para la automatización del ciclo de vida del software, el proyecto utiliza un flujo CI/CD basado en GitHub Actions. El código fuente reside en un GitHub Repository, desde donde se ejecutan pipelines de despliegue hacia los tres entornos: el Backend API en Azure App Service, la aplicación web en Firebase Hosting y la Landing Page en GitHub Pages.

- Finalmente, los usuarios generales acceden a la plataforma para subir imágenes y recibir resultados básicos de detección, mientras que los profesionales de medios pueden acceder a análisis avanzados y reportes detallados, todo a través de la WebApp.

De esta manera, el despliegue asegura integración continua, disponibilidad en la nube y separación clara entre backend, frontend y landing page, garantizando una arquitectura escalable y mantenible.

<img src="https://i.ibb.co/0R54zB1R/diagram-deploy.png" alt="diagram-deploy" border="0">

<div style="page-break-after: always;"></div>

# Capítulo V: Tactical-Level Software Design

## 5.X. Bounded Context: [Bounded Context Name]

### 5.X.1. Domain Layer

[Content for domain layer]

### 5.X.2. Interface Layer

[Content for interface layer]

### 5.X.3. Application Layer

[Content for application layer]

### 5.X.4. Infrastructure Layer

[Content for infrastructure layer]

### 5.X.5. Bounded Context Software Architecture Component Level Diagrams

[Content for component level diagrams]

### 5.X.6. Bounded Context Software Architecture Code Level Diagrams

#### 5.X.6.1. Bounded Context Domain Layer Class Diagrams

[Content for domain layer class diagrams]

#### 5.X.6.2. Bounded Context Database Design Diagram

[Content for database design diagram]

<div style="page-break-after: always;"></div>

# Capítulo VI: Solution UX Design

## 6.1. Style Guidelines

### 6.1.1. General Style Guidelines

[Content for general style guidelines]

### 6.1.2. Web, Mobile & Devices Style Guidelines

[Content for web, mobile & devices style guidelines]

## 6.2. Information Architecture

### 6.2.1. Labeling Systems

[Content for labeling systems]

### 6.2.2. Searching Systems

[Content for searching systems]

### 6.2.3. SEO Tags and Meta Tags

[Content for SEO tags and meta tags]

### 6.2.4. Navigation Systems

[Content for navigation systems]

## 6.3. Landing Page UI Design

### 6.3.1. Landing Page Wireframe

[Content for landing page wireframe]

### 6.3.2. Landing Page Mock-up

[Content for landing page mock-up]

## 6.4. Applications UX/UI Design

### 6.4.1. Applications Wireframes

[Content for applications wireframes]

### 6.4.2. Applications Wireflow Diagrams

[Content for applications wireflow diagrams]

### 6.4.3. Applications Mock-ups

[Content for applications mock-ups]

### 6.4.4. Applications User Flow Diagrams

[Content for applications user flow diagrams]

## 6.5. Applications Prototyping

[Content for applications prototyping]

<div style="page-break-after: always;"></div>

# Capítulo VII: Product Implementation, Validation & Deployment

## 7.1. Software Configuration Management

### 7.1.1. Software Development Environment Configuration

[Content for development environment configuration]

### 7.1.2. Source Code Management

[Content for source code management]

### 7.1.3. Source Code Style Guide & Conventions

[Content for source code style guide & conventions]

### 7.1.4. Software Deployment Configuration

[Content for software deployment configuration]

## 7.2. Solution Implementation

### 7.2.X. Sprint n

#### 7.2.X.1. Sprint Planning n

[Content for sprint planning]

#### 7.2.X.2. Sprint Backlog n

[Content for sprint backlog]

#### 7.2.X.3. Development Evidence for Sprint Review

[Content for development evidence]

#### 7.2.X.4. Testing Suite Evidence for Sprint Review

[Content for testing suite evidence]

#### 7.2.X.5. Execution Evidence for Sprint Review

[Content for execution evidence]

#### 7.2.X.6. Services Documentation Evidence for Sprint Review

[Content for services documentation evidence]

#### 7.2.X.7. Software Deployment Evidence for Sprint Review

[Content for software deployment evidence]

#### 7.2.X.8. Team Collaboration Insights during Sprint

[Content for team collaboration insights]

## 7.3. Validation Interviews

### 7.3.1. Diseño de Entrevistas

[Content for interview design]

### 7.3.2. Registro de Entrevistas

[Content for interview records]

### 7.3.3. Evaluaciones según heurísticas

[Content for heuristic evaluations]

## 7.4. Video About-the-Product

[Content for video about the product]

---

## Bibliografía

[Bibliography content]

---

## Anexos

[Annexes content]
