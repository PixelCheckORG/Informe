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

En esta sección se describe cómo serían los escenarios ideales (To-Be) una vez implementada la solución PixelCheck propuesta por nuestro equipo. A partir de los problemas identificados en el análisis de detección de imágenes generadas por IA, se plantea una visión futura optimizada, en la que los usuarios pueden verificar la autenticidad de contenido visual de manera rápida y confiable.

Cada mapeo To-Be representa la experiencia del usuario mejorada, los escenarios están divididos por segmentos para mantener un enfoque claro y específico.

### Segmento 1: Usuarios Generales

**Enlace para visualizar el To-Be Scenario Map de Usuarios Generales realizado en Miro:** 

https://miro.com/welcomeonboard/bEhJWmdYV3h4bEtXTmRTN0NIZEx1WjIzRDBBd3NGdnBXZ3ZNZGUzUCs3V01ncW8zbmdZQmc1RGZoVlZ4MUVwY1NBY1l5aE5XUHlyTkpldHJQYTcxTnNuREFFVEF3QUU1c0ExaEQ3RHNLRTJoNjBHaFkxZWlUd3E1TUZIbkZTemRBd044SHFHaVlWYWk0d3NxeHNmeG9BPT0hdjE=?share_link_id=668820882265

### Brainstorming:

![Brainstorming](./assets/chapter-III/brainstorming.png)

### To-Be Scenario Mapping 

![to be](./assets/chapter-III/to-be-scenario.png)


## 3.2. User Stories

El apartado de User Stories permite identificar las diversas situaciones que experimenta el usuario al interactuar con las diferentes áreas del proyecto PixelCheck, desde la carga de imágenes hasta el análisis de detección de IA. Su relevancia radica en que facilita la creación de un product backlog y, mediante los criterios de aceptación, podemos comprobar si estas historias se han cumplido correctamente.

**Epics y User Stories de PixelCheck**

|**Epic / Story ID**|**Título**|**Descripción**|**Criterios de Aceptación**|**Relacionado con (Epic ID)**|
| - | - | - | - | - |
|**EP01**|**Image Analysis Core**|<p>**Como** usuario,</p><p>**Quiero** analizar imágenes para detectar si fueron generadas por IA</p><p>**Para** verificar la autenticidad de contenido visual.</p>|||
|**HU01**|**Cargar imagen para análisis**|<p>**Como** usuario,</p><p>**Quiero** cargar una imagen desde mi dispositivo</p><p>**Para** poder analizarla con el detector de IA.</p>|<p>**Escenario 1: Carga exitosa por arrastrar y soltar<br>Dado** que el usuario tiene una imagen en su dispositivo,<br>**Cuando** arrastra la imagen al área de carga,<br>**Entonces** el sistema muestra la imagen en vista previa y habilita el botón de análisis.</p><p>**Escenario 2: Carga exitosa por selección de archivo<br>Dado** que el usuario hace clic en el área de carga,<br>**Cuando** selecciona un archivo de imagen válido,<br>**Entonces** el sistema muestra la imagen en vista previa y habilita el botón de análisis.</p><p>**Escenario 3: Error por formato no válido<br>Dado** que el usuario intenta cargar un archivo que no es imagen,<br>**Cuando** selecciona el archivo,<br>**Entonces** el sistema muestra un mensaje de error y no procesa el archivo.</p>|**EP01**|
|**HU02**|**Analizar imagen con algoritmo ML**|<p>**Como** usuario,</p><p>**Quiero** ejecutar el análisis de detección de IA en mi imagen</p><p>**Para** obtener un resultado sobre su autenticidad.</p>|<p>**Escenario 1: Análisis exitoso de imagen real<br>Dado** que el usuario ha cargado una imagen fotográfica real,<br>**Cuando** hace clic en "Analizar con IA",<br>**Entonces** el sistema muestra "Imagen Real/Fotográfica" con alta confianza.</p><p>**Escenario 2: Análisis exitoso de imagen generada por IA<br>Dado** que el usuario ha cargado una imagen generada por IA,<br>**Cuando** hace clic en "Analizar con IA",<br>**Entonces** el sistema muestra "Imagen Generada por IA" con nivel de confianza apropiado.</p><p>**Escenario 3: Análisis de diseño gráfico<br>Dado** que el usuario ha cargado un diseño gráfico digital,<br>**Cuando** hace clic en "Analizar con IA",<br>**Entonces** el sistema muestra "Diseño Gráfico/Digital" como resultado.</p>|**EP01**|
|**HU03**|**Visualizar resultados detallados del análisis**|<p>**Como** usuario,</p><p>**Quiero** ver información detallada sobre el análisis realizado</p><p>**Para** entender los factores que influyeron en la clasificación.</p>|<p>**Escenario 1: Visualización de análisis de color<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario revisa los resultados,<br>**Entonces** puede ver el número de colores únicos detectados y la diversidad cromática.</p><p>**Escenario 2: Visualización de análisis de transparencia<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario revisa los resultados,<br>**Entonces** puede ver el porcentaje de píxeles transparentes detectados.</p><p>**Escenario 3: Visualización de análisis de ruido<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario revisa los resultados,<br>**Entonces** puede ver la interpretación del nivel de ruido fotográfico.</p>|**EP01**|
|**EP02**|**Technical Analysis Details**|<p>**Como** usuario técnico,</p><p>**Quiero** acceder a información técnica detallada del análisis</p><p>**Para** entender los algoritmos y características utilizadas.</p>|||
|**HU04**|**Ver probabilidades de clasificación ML**|<p>**Como** usuario técnico,</p><p>**Quiero** ver las probabilidades específicas de cada categoría</p><p>**Para** entender la confianza del modelo en cada clasificación.</p>|<p>**Escenario 1: Visualización de probabilidades<br>Dado** que el análisis ML se ha completado,<br>**Cuando** el usuario revisa la sección técnica,<br>**Entonces** puede ver los porcentajes para "Imagen Real", "Generada por IA" y "Diseño Gráfico".</p><p>**Escenario 2: Interpretación de confianza<br>Dado** que las probabilidades se muestran,<br>**Cuando** una categoría tiene probabilidad > 70%,<br>**Entonces** se muestra como "Alta Confianza".</p>|**EP02**|
|**HU05**|**Consultar características extraídas**|<p>**Como** usuario técnico,</p><p>**Quiero** ver los valores específicos de las características analizadas</p><p>**Para** entender qué aspectos técnicos influyeron en la decisión.</p>|<p>**Escenario 1: Visualización de características principales<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario revisa la sección técnica,<br>**Entonces** puede ver valores numéricos para diversidad de color, transparencia, nivel de ruido, nitidez de bordes, patrones y compresión.</p><p>**Escenario 2: Interpretación de valores<br>Dado** que se muestran las características,<br>**Cuando** un valor está cerca de 1.0,<br>**Entonces** indica alta presencia de esa característica en la imagen.</p>|**EP02**|
|**EP03**|**User Experience**|<p>**Como** usuario,</p><p>**Quiero** una interfaz intuitiva y responsiva</p><p>**Para** usar la aplicación de manera eficiente en cualquier dispositivo.</p>|||
|**HU06**|**Navegar con interfaz responsiva**|<p>**Como** usuario web,</p><p>**Quiero** usar la aplicación web desde diferentes tamaños de pantalla</p><p>**Para** analizar imágenes desde cualquier dispositivo con navegador web.</p>|<p>**Escenario 1: Adaptación a diferentes resoluciones<br>Dado** que el usuario accede desde diferentes tamaños de pantalla (desktop, tablet),<br>**Cuando** carga la página web,<br>**Entonces** la interfaz se adapta automáticamente al tamaño de pantalla manteniendo la funcionalidad.</p><p>**Escenario 2: Funcionalidad completa en navegador web<br>Dado** que el usuario está usando un navegador web moderno,<br>**Cuando** realiza todas las acciones (cargar, analizar, ver resultados),<br>**Entonces** todas las funcionalidades están disponibles y optimizadas para web.</p>|**EP03**|
|**HU07**|**Visualizar estado de carga durante análisis**|<p>**Como** usuario,</p><p>**Quiero** ver el progreso del análisis en tiempo real</p><p>**Para** saber que el sistema está procesando mi imagen.</p>|<p>**Escenario 1: Indicador de progreso visible<br>Dado** que el usuario inicia el análisis,<br>**Cuando** el sistema procesa la imagen,<br>**Entonces** se muestra un overlay de carga con spinner y mensajes de estado.</p><p>**Escenario 2: Mensajes de progreso específicos<br>Dado** que el análisis está en progreso,<br>**Cuando** cada etapa se completa,<br>**Entonces** el mensaje de estado se actualiza para reflejar la etapa actual.</p>|**EP03**|
|**HU08**|**Ver metadatos de la imagen**|<p>**Como** usuario,</p><p>**Quiero** ver información básica de la imagen cargada</p><p>**Para** conocer sus características técnicas.</p>|<p>**Escenario 1: Visualización de metadatos básicos<br>Dado** que el usuario ha cargado una imagen,<br>**Cuando** revisa la sección de metadatos,<br>**Entonces** puede ver formato, dimensiones, tamaño de archivo y nivel de compresión.</p><p>**Escenario 2: Interpretación de compresión<br>Dado** que se muestran los metadatos,<br>**Cuando** el formato es JPEG con alta compresión,<br>**Entonces** se indica "Alta compresión" en la interfaz.</p>|**EP01**|
|**HU09**|**Limpiar análisis anterior**|<p>**Como** usuario,</p><p>**Quiero** poder cargar una nueva imagen</p><p>**Para** realizar un nuevo análisis sin interferencias.</p>|<p>**Escenario 1: Reset automático al cargar nueva imagen<br>Dado** que el usuario tiene resultados de análisis previo,<br>**Cuando** carga una nueva imagen,<br>**Entonces** los resultados anteriores se ocultan automáticamente.</p><p>**Escenario 2: Botón de limpiar manual<br>Dado** que el usuario quiere limpiar los resultados,<br>**Cuando** hace clic en un botón "Nueva imagen",<br>**Entonces** se resetea la interfaz al estado inicial.</p>|**EP03**|
|**HU10**|**Copiar resultado al portapapeles**|<p>**Como** usuario,</p><p>**Quiero** copiar el resultado del análisis</p><p>**Para** compartirlo fácilmente en otros lugares.</p>|<p>**Escenario 1: Copia del resultado principal<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario hace clic en "Copiar resultado",<br>**Entonces** el texto del resultado se copia al portapapeles.</p><p>**Escenario 2: Confirmación de copia<br>Dado** que el usuario copia el resultado,<br>**Cuando** la copia es exitosa,<br>**Entonces** se muestra un mensaje de confirmación temporal.</p>|**EP03**|
|**HU11**|**Ver historial de análisis recientes**|<p>**Como** usuario,</p><p>**Quiero** ver las últimas imágenes analizadas</p><p>**Para** acceder rápidamente a análisis previos.</p>|<p>**Escenario 1: Lista de análisis recientes<br>Dado** que el usuario ha realizado varios análisis,<br>**Cuando** accede a la sección de historial,<br>**Entonces** puede ver una lista de las últimas 5 imágenes con sus resultados.</p><p>**Escenario 2: Selección de análisis previo<br>Dado** que existe historial de análisis,<br>**Cuando** el usuario hace clic en un análisis previo,<br>**Entonces** se muestran los resultados de esa imagen nuevamente.</p>|**EP01**|
|**HU12**|**Exportar resultados como imagen**|<p>**Como** usuario,</p><p>**Quiero** exportar el resultado del análisis como imagen</p><p>**Para** guardar o compartir el resultado visualmente.</p>|<p>**Escenario 1: Exportación exitosa<br>Dado** que el análisis se ha completado,<br>**Cuando** el usuario hace clic en "Exportar resultado",<br>**Entonces** se descarga una imagen PNG con el resultado y la imagen original.</p><p>**Escenario 2: Formato de exportación<br>Dado** que el usuario exporta el resultado,<br>**Cuando** se genera la imagen,<br>**Entonces** incluye el resultado, nivel de confianza y fecha del análisis.</p>|**EP03**|
|**HU13**|**Cambiar tema visual (claro/oscuro)**|<p>**Como** usuario,</p><p>**Quiero** cambiar entre tema claro y oscuro</p><p>**Para** usar la aplicación según mi preferencia visual.</p>|<p>**Escenario 1: Cambio a tema oscuro<br>Dado** que el usuario está en tema claro,<br>**Cuando** hace clic en el botón de cambio de tema,<br>**Entonces** la interfaz cambia a colores oscuros manteniendo la funcionalidad.</p><p>**Escenario 2: Persistencia del tema<br>Dado** que el usuario cambia el tema,<br>**Cuando** recarga la página,<br>**Entonces** se mantiene el tema seleccionado.</p>|**EP03**|
|**HU14**|**Ver información de ayuda**|<p>**Como** usuario nuevo,</p><p>**Quiero** acceder a información de ayuda</p><p>**Para** entender cómo usar la aplicación correctamente.</p>|<p>**Escenario 1: Acceso a ayuda<br>Dado** que el usuario necesita ayuda,<br>**Cuando** hace clic en el botón "Ayuda",<br>**Entonces** se muestra un modal con instrucciones paso a paso.</p><p>**Escenario 2: Cierre de ayuda<br>Dado** que el modal de ayuda está abierto,<br>**Cuando** el usuario hace clic en "Cerrar" o fuera del modal,<br>**Entonces** el modal se cierra y regresa a la interfaz principal.</p>|**EP03**|
|**HU15**|**Validar formato de imagen antes de análisis**|<p>**Como** usuario,</p><p>**Quiero** que el sistema valide el formato de imagen</p><p>**Para** evitar errores durante el análisis.</p>|<p>**Escenario 1: Validación de formato soportado<br>Dado** que el usuario carga una imagen,<br>**Cuando** el formato es JPG, PNG o WEBP,<br>**Entonces** el sistema permite continuar con el análisis.</p><p>**Escenario 2: Rechazo de formato no soportado<br>Dado** que el usuario carga un archivo no soportado,<br>**Cuando** el formato no es imagen válida,<br>**Entonces** se muestra un mensaje de error específico.</p>|**EP01**|
|**HU16**|**Mostrar tiempo de análisis**|<p>**Como** usuario,</p><p>**Quiero** ver cuánto tiempo tomó el análisis</p><p>**Para** conocer la eficiencia del sistema.</p>|<p>**Escenario 1: Tiempo de análisis visible<br>Dado** que el análisis se ha completado,<br>**Cuando** se muestran los resultados,<br>**Entonces** aparece el tiempo total de procesamiento en segundos.</p><p>**Escenario 2: Tiempo por etapa<br>Dado** que el análisis está en progreso,<br>**Cuando** cada etapa se completa,<br>**Entonces** se muestra el tiempo parcial de esa etapa.</p>|**EP02**|
|**HU17**|**Redimensionar imagen automáticamente**|<p>**Como** usuario,</p><p>**Quiero** que imágenes muy grandes se redimensionen</p><p>**Para** mejorar la velocidad de análisis.</p>|<p>**Escenario 1: Redimensionamiento automático<br>Dado** que el usuario carga una imagen mayor a 2048px,<br>**Cuando** se inicia el análisis,<br>**Entonces** la imagen se redimensiona automáticamente manteniendo la proporción.</p><p>**Escenario 2: Notificación de redimensionamiento<br>Dado** que la imagen fue redimensionada,<br>**Cuando** se muestra el resultado,<br>**Entonces** aparece una nota indicando que la imagen fue optimizada.</p>|**EP01**|
|**HU18**|**Comparar múltiples imágenes**|<p>**Como** usuario,</p><p>**Quiero** analizar hasta 3 imágenes simultáneamente</p><p>**Para** comparar resultados de diferentes imágenes.</p>|<p>**Escenario 1: Carga múltiple<br>Dado** que el usuario quiere comparar imágenes,<br>**Cuando** carga hasta 3 imágenes,<br>**Entonces** se muestran en una vista de comparación lado a lado.</p><p>**Escenario 2: Análisis comparativo<br>Dado** que hay múltiples imágenes cargadas,<br>**Cuando** se ejecuta el análisis,<br>**Entonces** se muestran los resultados de todas las imágenes en una tabla comparativa.</p>|**EP01**|
|**HU19**|**Guardar configuración de análisis**|<p>**Como** usuario frecuente,</p><p>**Quiero** guardar mis preferencias de análisis</p><p>**Para** no tener que configurar cada vez.</p>|<p>**Escenario 1: Guardado de preferencias<br>Dado** que el usuario ajusta configuraciones,<br>**Cuando** hace clic en "Guardar configuración",<br>**Entonces** las preferencias se almacenan en localStorage.</p><p>**Escenario 2: Carga de configuración<br>Dado** que existen configuraciones guardadas,<br>**Cuando** el usuario recarga la página,<br>**Entonces** se restauran automáticamente sus preferencias.</p>|**EP03**|
|**HU20**|**Ver estadísticas de uso**|<p>**Como** usuario,</p><p>**Quiero** ver estadísticas de mis análisis</p><p>**Para** conocer mis patrones de uso.</p>|<p>**Escenario 1: Estadísticas básicas<br>Dado** que el usuario ha realizado varios análisis,<br>**Cuando** accede a la sección de estadísticas,<br>**Entonces** puede ver total de análisis, tipos de imágenes más comunes y tiempo promedio.</p><p>**Escenario 2: Gráfico de distribución<br>Dado** que existen estadísticas,<br>**Cuando** se muestran los datos,<br>**Entonces** aparece un gráfico simple de distribución por tipo de imagen.</p>|**EP02**|

## 3.3. Impact Mapping

[Content for impact mapping]

## 3.4. Product Backlog

El Product Backlog es una lista priorizada de tareas, funcionalidades y requisitos necesarios para el desarrollo del proyecto PixelCheck, asegurando que se trabaje en los elementos más importantes y alineados con los objetivos del proyecto. Cada ítem del backlog incluye una descripción, prioridad y título.

<table>
  <thead>
    <tr>
      <th>Orden</th>
      <th>User Story Id</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>HU01</td>
      <td>Cargar imagen para análisis</td>
      <td>Como usuario, quiero cargar una imagen desde mi dispositivo para poder analizarla con el detector de IA.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>2</td>
      <td>HU02</td>
      <td>Analizar imagen con algoritmo ML</td>
      <td>Como usuario, quiero ejecutar el análisis de detección de IA en mi imagen para obtener un resultado sobre su autenticidad.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>3</td>
      <td>HU03</td>
      <td>Visualizar resultados detallados del análisis</td>
      <td>Como usuario, quiero ver información detallada sobre el análisis realizado para entender los factores que influyeron en la clasificación.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>4</td>
      <td>HU15</td>
      <td>Validar formato de imagen antes de análisis</td>
      <td>Como usuario, quiero que el sistema valide el formato de imagen para evitar errores durante el análisis.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>5</td>
      <td>HU08</td>
      <td>Ver metadatos de la imagen</td>
      <td>Como usuario, quiero ver información básica de la imagen cargada para conocer sus características técnicas.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>6</td>
      <td>HU07</td>
      <td>Visualizar estado de carga durante análisis</td>
      <td>Como usuario, quiero ver el progreso del análisis en tiempo real para saber que el sistema está procesando mi imagen.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>7</td>
      <td>HU06</td>
      <td>Navegar con interfaz responsiva</td>
      <td>Como usuario web, quiero usar la aplicación web desde diferentes tamaños de pantalla para analizar imágenes desde cualquier dispositivo con navegador web.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>8</td>
      <td>HU04</td>
      <td>Ver probabilidades de clasificación ML</td>
      <td>Como usuario técnico, quiero ver las probabilidades específicas de cada categoría para entender la confianza del modelo en cada clasificación.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>9</td>
      <td>HU05</td>
      <td>Consultar características extraídas</td>
      <td>Como usuario técnico, quiero ver los valores específicos de las características analizadas para entender qué aspectos técnicos influyeron en la decisión.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>10</td>
      <td>HU16</td>
      <td>Mostrar tiempo de análisis</td>
      <td>Como usuario, quiero ver cuánto tiempo tomó el análisis para conocer la eficiencia del sistema.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>11</td>
      <td>HU09</td>
      <td>Limpiar análisis anterior</td>
      <td>Como usuario, quiero poder cargar una nueva imagen para realizar un nuevo análisis sin interferencias.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>12</td>
      <td>HU10</td>
      <td>Copiar resultado al portapapeles</td>
      <td>Como usuario, quiero copiar el resultado del análisis para compartirlo fácilmente en otros lugares.</td>
      <td>1</td>
    </tr>
    <tr>
      <td>13</td>
      <td>HU17</td>
      <td>Redimensionar imagen automáticamente</td>
      <td>Como usuario, quiero que imágenes muy grandes se redimensionen para mejorar la velocidad de análisis.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>14</td>
      <td>HU13</td>
      <td>Cambiar tema visual (claro/oscuro)</td>
      <td>Como usuario, quiero cambiar entre tema claro y oscuro para usar la aplicación según mi preferencia visual.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>15</td>
      <td>HU14</td>
      <td>Ver información de ayuda</td>
      <td>Como usuario nuevo, quiero acceder a información de ayuda para entender cómo usar la aplicación correctamente.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>16</td>
      <td>HU11</td>
      <td>Ver historial de análisis recientes</td>
      <td>Como usuario, quiero ver las últimas imágenes analizadas para acceder rápidamente a análisis previos.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>17</td>
      <td>HU12</td>
      <td>Exportar resultados como imagen</td>
      <td>Como usuario, quiero exportar el resultado del análisis como imagen para guardar o compartir el resultado visualmente.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>18</td>
      <td>HU19</td>
      <td>Guardar configuración de análisis</td>
      <td>Como usuario frecuente, quiero guardar mis preferencias de análisis para no tener que configurar cada vez.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>19</td>
      <td>HU18</td>
      <td>Comparar múltiples imágenes</td>
      <td>Como usuario, quiero analizar hasta 3 imágenes simultáneamente para comparar resultados de diferentes imágenes.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>20</td>
      <td>HU20</td>
      <td>Ver estadísticas de uso</td>
      <td>Como usuario, quiero ver estadísticas de mis análisis para conocer mis patrones de uso.</td>
      <td>3</td>
    </tr>
  </tbody>
</table>

# Capítulo IV: Strategic-Level Software Design

## 4.1. Strategic-Level Attribute-Driven Design

### 4.1.1. Design Purpose

[Content for design purpose]

### 4.1.2. Attribute-Driven Design Inputs

#### 4.1.2.1. Primary Functionality (Primary User Stories)

[Content for primary functionality]

#### 4.1.2.2. Quality attribute Scenarios

[Content for quality attribute scenarios]

#### 4.1.2.3. Constraints

[Content for constraints]

### 4.1.3. Architectural Drivers Backlog

[Content for architectural drivers backlog]

### 4.1.4. Architectural Design Decisions

[Content for architectural design decisions]

### 4.1.5. Quality Attribute Scenario Refinements

[Content for quality attribute scenario refinements]

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

[Content for system landscape diagram]

### 4.3.2. Software Architecture Context Level Diagrams

[Content for context level diagrams]

### 4.3.3. Software Architecture Container Level Diagrams

[Content for container level diagrams]

### 4.3.4. Software Architecture Deployment Diagrams

[Content for deployment diagrams]

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
