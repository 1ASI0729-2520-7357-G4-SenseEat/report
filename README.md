# report
# FreshSense

<div align="center">

<h3>Universidad Peruana de Ciencias Aplicadas</h3>

<img alt="upc-logo" src="assets/upc_logo_200x200_jao73r.png" width="200"/><br>

<strong>Ingeniería de Software - 2025-2</strong><br>
<strong>1ASI0729 - Desarrollo de Aplicaciones Open Source</strong><br>
<strong>NRC: 7357<br>
<strong>Profesor: Rafael Oswaldo Castro Veramendi</strong><br>

<br><strong>Informe del Trabajo Final</strong><br><br>

<strong>Startup: SenseEat</strong><br>
<strong>Producto: FreshSense</strong><br>



### Team Members:

|             Member              |   Code    |
|:-------------------------------:|:---------:|
|              |  |
|  |    ...    |
|    |    ...    |
|     |    ...    |
|  Tuesta Marin Romina Alejandra  |    U202211706   |

<strong> Setiembre 2025</strong><br>
</div>

# Registro de Versiones del Informe

| Versión | Fecha      | Autor        | Descripción de modificación                   |
|---------|------------|--------------|-----------------------------------------------|
| 1.0     | 05/09/2025 | Romina Tuesta | Creación de la estructura inicial del reporte |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |
|         |            |              |                                               |

# Project Report Collaboration Insights

---

## Contenido
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
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
        - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4. Empathy Mapping](#234-empathy-mapping)
        - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
        - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
        - [4.2.1. Organization Systems](#421-organization-systems)
        - [4.2.2. Labeling Systems](#422-labeling-systems)
        - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4. Searching Systems](#424-searching-systems)
        - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)
        - [4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)
    - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
        - [4.7.2. Class Dictionary](#472-class-dictionary)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**
**Criterio:** *Capacidad de comunicarse efectivamente con un rango de audiencias.*

En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 3.

| Criterio específico                                                                              | Acciones realizadas | Conclusiones |
|--------------------------------------------------------------------------------------------------|---------------------|--------------|
| Comunica oralmente con efectividad a diferentes rangos de audiencia.                                  |                     |              |
| Comunica por escrito con efectividad a diferentes rangos de audiencia |                     |              |


# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

|                             Miembro                             |                                                                                                                                                                                   Descripción                                                                                                                                                                                   |
|:---------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| ![About](assets/foto_romina.PNG)  |  Romina Tuesta Marin - u202211706 <br> Mi nombre es Romina Tuesta, tengo 20 años, estudio ingeniería de software y me encuentro en 7mo ciclo. Me considero una persona responsable y dispuesta a ayudar a quien necesite en mi grupo, tengo conocimiento en algunos lenguajes de programación como Python, C++, etc. Creo que la mejor manera de desarrollar un proyecto grupal es mantener buena comunicación y que todos se dediquen enteramente a entregar un buenproducto.  |
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
#### Business Assumptions
#### User Assumptions
##### 1.2.2.3. Lean UX Hypothesis Statements
##### 1.2.2.4. Lean UX Canvas
## 1.3. Segmentos objetivo
# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
### 2.1.1. Análisis competitivo
### 2.1.2. Estrategias y tácticas frente a competidores
## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

## Segmento 1: 
### Adultos jóvenes (25-40 años, dinámicos y ocupados)

#### Hábitos y problemas

1. ¿Qué tan seguido revisas el estado de tus alimentos en el refrigerador?

2. ¿Has tenido que botar comida en la última semana o mes? ¿Qué alimentos suelen desperdiciarse más?

3. ¿Qué sientes cuando tienes que desechar alimentos?

4. ¿Cómo gestionas actualmente tu inventario alimenticio? (listas, memoria, apps, nada).

5. ¿Qué dificultades encuentras al intentar consumir tus alimentos antes de que se malogren?

#### Uso de tecnología

6. ¿Qué aplicaciones o dispositivos usas en tu día a día para organizar tu vida (ejemplo: apps de compras, recordatorios, fitness, etc.)?
   
7. ¿Estarías dispuesto(a) a usar una app para monitorear tus alimentos? ¿Qué esperas que sea fácil o difícil en esa experiencia?

#### Valor y disposición
8. ¿Qué te motivaría a usar un sistema que te avise cuándo un alimento está por vencer o deteriorarse?
   
9. Si además de alertas recibieras recetas personalizadas con lo que tienes en el refrigerador, ¿lo encontrarías útil?
    
10. ¿Pagarías una suscripción mensual por este tipo de servicio? Si sí, ¿qué rango de precio considerarías razonable?


## Segmento 2: 
### Pequeños negocios / emprendedores de alimentos caseros

#### Hábitos y problemas

1. ¿Qué tipo de alimentos manejas en tu negocio y cuáles son más propensos a perderse o malograrse?

2. ¿Con qué frecuencia enfrentas pérdidas por deterioro de productos?

3. ¿Tienes actualmente un método para controlar la frescura de tus ingredientes (listas, hojas de Excel, memoria, otro)?

#### Necesidades

4. ¿Qué impacto tiene para tu negocio perder productos perecibles? (económico, reputación, tiempo, clientes).
5. ¿Qué importancia le das a la calidad y frescura de los alimentos que vendes?
6. ¿Qué tipo de alertas o reportes te gustaría recibir para mejorar tu control de inventario?

#### Valor y disposición
7. ¿Te resultaría útil tener un dispositivo que monitoree automáticamente el estado de los productos dentro de tu refrigerador?
8. ¿Qué características serían imprescindibles para que confíes en este tipo de solución?
9. ¿Pagarías por una herramienta que te ayude a reducir pérdidas y mantener la frescura? ¿Prefieres un pago único por el dispositivo o una suscripción mensual con funciones adicionales?
10. Si el sistema pudiera darte estadísticas de consumo, desperdicio y hasta proyecciones de compras, ¿te serviría para tu negocio?


### 2.2.2. Registro de entrevistas
### 2.2.3. Análisis de entrevistas
## 2.3. Needfinding
### 2.3.1. User Personas

#### SEGMENTO 1: Adultos jóvenes
<img alt="upc-logo" src="assets/José_userP1.png" width="600"/><br>

### SEGMENTO 2: Pequeños negocios / emprendedores de alimentos caseros
<img alt="upc-logo" src="assets/Luisa_userP2.png" width="600"/><br>
### 2.3.2. User Task Matrix
### 2.3.3. User Journey Mapping
### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
## 3.2. User Stories
## 3.3. Impact Mapping
## 3.4. Product Backlog

# Capítulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram
### 4.6.2. Software Architecture Container Diagrams
### 4.6.3. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
### 4.7.2. Class Dictionary
## 4.8. Database Design
### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

En esta sección se especifican los aspectos principales del Sprint Planning Meeting. La estructura a utilizar se presenta a continuación.

| Campo                               | Detalle                                                                                |
| ----------------------------------- | -------------------------------------------------------------------------------------- |
| **Date**                            | 2025-09-09                                                                             |
| **Time**                            | 10:00 AM                                                                               |
| **Location**                        | Sala virtual – Google Meet                                                             |
| **Prepared By**                     |  Vega Coronado, Fabricio Samir                                                         |
| **Attendees (to planning meeting)** | Romina Tuesta Marin / Vega Coronado, Fabricio Samir  / Villanueva Andrade, Ysaac Ligorio / Tumi Oliden, Manuel Ignacio / Valverde Portuguez, Natalia Ximena |
| **Sprint 1 – 1 Review Summary** | Este es el primer sprint, por lo que no hay resultados anteriores a revisar. El equipo está iniciando el desarrollo de la landing page de FreshSense.|
| **Sprint 1 – 1 Retrospective Summary** | No aplica, al ser el primer sprint. Se acordó establecer prácticas de comunicación diaria y seguimiento mediante Trello y reuniones cortas cada mañana.|

| Campo                   | Detalle                                                                                                                                                                        |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Sprint 1 Goal**       | Nuestro enfoque está en entregar una versión inicial de la landing page de FreshSense que muestre su propuesta de valor y beneficios principales. Creemos que esto generará claridad y confianza en los usuarios potenciales (jóvenes adultos y pequeños emprendedores de alimentos). Esto se confirmará cuando los visitantes puedan navegar la página, entender la solución y enviar un formulario de contacto. |
| **Sprint 1 Velocity**   | 26 Story Points (capacidad estimada para este sprint inicial)                                                                                                                  |
| **Sum of Story Points** | 26 Story Points                                                                                                                                                                |

**User Stories incluidas:**

HU01: Header con logo y nombre de FreshSense (2 SP)

HU02: Descripción breve de la plataforma (3 SP)

HU03: Sección de beneficios (5 SP)

HU04: Formulario de contacto (8 SP)

HU05: Diseño responsive (8 SP)


#### 5.2.1.2. Aspect Leaders and Collaborators


| Team Member (Last Name, First Name)   | Github Username        | wireframes y MockUps landing |  Visualización beneficios y características | Consultar planes y precios | Formulario de contacto | Sección de testimonios | Despliegue de servicio | Cambio de idioma |
|-----------|----------------------|-----------|----------------------|-----------|----------------------|-----------|-----------|-----------|
| Valverde Portuguez Natalia Ximena |        |    (L)   |     (C)     |    (C)      |   (L)   |     (C)     |    (C)      |   (C)      |
|  Romina Alejanda Tuesta Marin    |     Romimi1     |    (L)   |     (C)     |    (L)      |   (L)   |     (C)     |    (L)      |   (C)      |
|  Tumi Oliden Manuel Ignacio      |     |      (C)   |     (C)     |    (C)      |   (L)   |     (C)     |    (C)      |   (C)      |
|  Vega Coronado Fabricio Samir    |     |      (C)   |     (C)     |    (C)      |   (C)   |     (L)     |    (C)      |   (C)      |
|  Villanueva Andrade Ysaac Ligorio |     |      (C)   |     (C)     |    (C)      |   (L)   |     (C)     |    (C)      |   (L)      |

#### 5.2.1.3. Sprint Backlog 1
En este sprint se desarrollará y desplegará la Landing Page de EcoTrack, que servirá como punto de presentación del producto. Se crearán las secciones informativas clave (propuesta de valor, explicación del producto, beneficios, planes y precios, formulario de contacto y testimonios), estableciendo así las bases visuales y funcionales del proyecto.

Herramienta de control: Trello
<img alt="Trello" src="/assets/Trello_sprint1.PNG" /><br>
URL del Board: https://trello.com/b/ScNLfxb4/sprint1-freshsense

| User Story |                                | Work-Item / Task |                                 |                                                                           |                        |                     |                                                    |
| ---------- | ------------------------------ | ---------------- | ------------------------------- | ------------------------------------------------------------------------- | ---------------------- | ------------------- | -------------------------------------------------- |
| **Id**     | **Title**                      | **Id**           | **Title**                       | **Description**                                                           | **Estimation (Hours)** | **Assigned To**     | **Status** (To-do / In-Process / To-Review / Done) |
| US01       | Visualización propuesta        | T01              | Diseño del mensaje principal    | Redactar y diseñar mensaje principal y valor de la solución               | 3                      | Romina    | Done                                               |
|            |                                | T02              | Desarrollo del encabezado       | Implementar sección superior con mensaje y valor destacado                | 4                      |   Manuel     | In-Process                                         |
| US02       | Sección para pequeños negocios | T03              | Contenido de beneficios         | Redactar y diseñar beneficios específicos para emprendedores              | 3                      | Romina | To-Review                                          |
|            |                                | T04              | Desarrollo de sección           | Implementar sección con beneficios específicos para el perfil emprendedor | 4                      | Natalia    | To-do                                              |
| US03       | Formulario de contacto         | T05              | Diseño del formulario           | Diseñar formulario simple con campos mínimos requeridos                   | 2                      | Romina    | Done                                               |                                     
| US04       | CTA para suscripción           | T07              | Diseño del botón CTA            | Diseñar botón llamativo para suscripción o prueba                         | 2                      | Fabricio   | Done                                               |
|            |                                | T08              | Implementación del botón        | Añadir botón funcional que redirija a formulario o registro de prueba     | 3                      | Fabricio    | To-do                                              |
| US05       | Compatibilidad móvil           | T09              | Adaptación responsive           | Configurar CSS responsive para toda la landing page                       | 5                      | Ysaac      | In-Process                                         |
|            |                                | T10              | Pruebas en dispositivos móviles | Realizar pruebas de compatibilidad en distintos tamaños de pantalla       | 3                      | Natalia    | To-do                                              |

#### 5.2.1.4. Development Evidence for Sprint Review

En esta sección se presentan los avances en la implementación de la solución FreshSense, considerando los productos contemplados en el alcance del Sprint: Landing Page. Durante este periodo se trabajó principalmente en el desarrollo de la Landing Page, incorporando mejoras visuales, de usabilidad y funcionalidad. Entre los principales avances se encuentran la creación de la página principal, la integración de estilos y animaciones, la optimización del comportamiento de la navegación y la incorporación de nuevas funciones interactivas.

A continuación, se detallan los commits realizados en los repositorios vinculados a la implementación:

| Repository |   Branch    | Commit Id |  Commit Message  |   Commit Message Body    |   Commited on (Date)  |        
| ---------- | ----------- | --------- | ---------------- | ------------------------ | --------------------- | 
| Romini1/github.com/1ASI0729-2520-7357-G4-SenseEat/Landing-page-FreshSense/tree/develop | develop     |   d201420  |    chore: upload initial landingpage    |  Se creó el archivo index.html, css y main.js como la página principal de la landing, estructurando la base inicial del proyecto.                        |    18/09/25     | 
| YsaacVillanueva/github.com/1ASI0729-2520-7357-G4-SenseEat/Landing-page-FreshSense/tree/develop | develop     |  e44f923  |    feat: add translate.js        | Se creó la funcionalidad dinámica del cambio de idioma en la landing                         |    19/09/25     | 
| ManuelTumi2224/github.com/1ASI0729-2520-7357-G4-SenseEat/Landing-page-FreshSense/tree/develop  | develop     |  c5cfc27   |  feat: Updated Footer and Plans |  Se actualizó la sección planes y subscripciones            |   19/09/25       | 
| YsaacVillanueva/github.com/1ASI0729-2520-7357-G4-SenseEat/Landing-page-FreshSense/tree/develop | develop     |  827e63c |    Merge pull request #1 from 1ASI0729-2520-7357-G4-SenseEat/feature/sprint1-Ysaac         |   Se hizo un merge y pull request opara las secciones actualizadas en todos los archivos         |     19/09/25    | 


#### 5.2.1.5. Execution Evidence for Sprint Review


Durante este Sprint se avanzó de manera significativa en el desarrollo de la Landing Page del proyecto FreshSense, la cual constituye el primer punto de contacto con los usuarios. Se implementó la estructura base con la página principal, se integraron estilos y animaciones, y se añadieron funcionalidades interactivas como el slider y un scroll más fluido. Asimismo, se realizaron correcciones en la navegación para garantizar una experiencia más clara e intuitiva, además se implementó exitosamente la funcionalidad del cambio de idioma, de español a ingles.

Con estos avances, se ha logrado contar con una primera versión navegable de la landing page, lo que permite mostrar la propuesta de valor de FreshSense y establecer la base para siguientes mejoras visuales y técnicas.

<br>

*Figura 1.* Página principal con navbar y sección de bienvenida.

![Hero](assets/LP_1.PNG) 


*Figura 2.* Sección acerca de FreshSense.

![About](assets/LP2.PNG) 


*Figura 3.* Sección acerca de beneficios.

![Services](assets/LP_3.PNG) 


*Figura 4.* Sección de planes de subscripción.

![Testimonials](assets/LP4.PNG) 


*Figura 5.* Sección de testimonios.

![Plans](assets/LP5.PNG) 


*Figura 6.* Sección de formulario de contacto.

![Form](assets/LP6.PNG) 

#### Video demostrativo

Se preparó un video donde se ilustra la navegación en la landing page y se explican las funcionalidades desarrolladas en este Sprint:
![Form](link) 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

En este Sprint, el trabajo realizado se centró en el desarrollo de la Landing Page de FreshSense, implementada únicamente con HTML, CSS y JavaScript. Dado que se trata de una página estática cuyo alcance se limita a la presentación de información y a la interacción en el lado del cliente, no se definieron ni consumieron Web Services.

En consecuencia, durante este Sprint no corresponde la elaboración de documentación con OpenAPI (Swagger), ya que esta herramienta se utiliza exclusivamente para describir y documentar APIs REST que exponen endpoints de un backend. La integración con Web Services y su respectiva documentación será abordada en Sprints posteriores, cuando la solución incluya funcionalidades dinámicas que requieran intercambio de datos entre frontend y backend.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Durante este Sprint se avanzó en los procesos de Deployment relacionados con la solución EcoTrack, con el objetivo de asegurar la disponibilidad de los productos desarrollados para su validación y demostración. Dentro de este Sprint, el esfuerzo principal estuvo orientado al despliegue de la Landing Page, que fue implementada con HTML, CSS y JavaScript.

El despliegue se realizó utilizando GitHub Pages, lo que permitió contar con un entorno accesible de manera pública sin necesidad de un proveedor de cloud externo. Esta estrategia fue seleccionada por su facilidad de integración con los repositorios de GitHub y por brindar un proceso automatizado de publicación a partir de la rama develop del proyecto.

Acciones realizadas en el proceso de Deployment

1. Creación y configuración del repositorio en GitHub.
Se configuró el repositorio ecotrack-landingpage en la cuenta de GitHub del equipo.

2. Configuración de GitHub Pages.

- Se habilitó la opción de GitHub Pages en la sección de Settings.

- Se seleccionó la rama develop como fuente de publicación.

- Se configuró la carpeta raíz del proyecto como directorio base de la publicación.

3. Automatización de despliegue.
Gracias a la integración nativa de GitHub Pages, cada nuevo commit realizado en la rama develop se despliega automáticamente en la URL pública asignada.

4. Validación del despliegue.
Se realizó la verificación de la publicación, comprobando que la landing page se visualiza correctamente en la dirección generada por GitHub Pages.

#### Evidencia del Deployment

*Figura 1.* Configuración de GitHub Pages en el repositorio de la landing page.

![dev1](assets/dv_1.PNG) 


*Figura 2.* Se ingresó a setting y luego a pages.

![dev2](assets/dv_2.PNG) 

*Figura 3.* seleccionamos la rama en la que se encuentre alojado el proyecto.

![dev3](assets/dv3.PNG) 


*Figura 4.* Esperamos la URL autogenerada por githubpages.

![dev4](assets/dv_4.PNG) 


#### Link a continuación: 

https://1asi0729-2520-7357-g4-senseeat.github.io/Landing-page-FreshSense/

#### 5.2.1.8. Team Collaboration Insights during Sprint  



# Conclusiones

# Bibliografía

# Anexos
