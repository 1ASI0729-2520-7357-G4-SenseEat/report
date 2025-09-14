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
|  Valverde Portuguez Natalia Ximena  | u20231a816 |
|  Tumi Oliden Manuel Ignacio  |    u20241c134    |
|  Vega Coronado Fabricio Samir  |    u202317000    |
|  Villanueva Andrade Ysaac Ligorio   |    u20231c168    |
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

Sense Eat es una startup enfocada en el desarrollo de soluciones tecnológicas para reducir el desperdicio de alimentos en los hogares. A través de la innovación, busca generar un impacto positivo en el cuidado del medio ambiente y la economía familiar, facilitando un mejor control y gestión del inventario alimenticio.

Nuestro producto principal, FreshSense, consiste en un dispositivo equipado con sensores que se coloca dentro del refrigerador para medir la temperatura, humedad y la concentración de gas etileno (indicador clave en el proceso de maduración y descomposición de frutas y verduras). Esta información es enviada a una aplicación web donde los usuarios pueden visualizar el estado de sus alimentos y recibir alertas anticipadas sobre su posible deterioro.

El modelo del negocio de Sense Eat está basado en la venta directa del dispositivo sensor y una suscripción mensual que ofrece funciones premium, como análisis detallado del inventario alimenticio y sugerencias de recetas personalizadas basadas en los productos disponibles, promoviendo así un consumo más eficiente y reducción de desperdicios.
    
### 1.1.2. Perfiles de integrantes del equipo

    

|                             Miembro                             |                                                                                                                                                                                   Descripción                                                                                                                                                                                   |
|:---------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|            |  <br>  |
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 |   
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 
|                                                                 |                                                                                                                                                                                                                                                                                                                                                                                 | 

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

#### Las 5W's y 2H's

#### What? (¿Qué?)
El desperdicio de alimentos en hogares consiste en la pérdida o desecho de productos alimenticios que podrían ser consumidos, debido a su descomposición, mala gestión o desconocimiento del estado real.

#### Why? (¿Por qué?)
La falta de información precisa y oportuna sobre las condiciones reales dentro del refrigerador (temperatura, humedad, gas etileno) hace que los usuarios no puedan anticipar la descomposición de alimentos, resultando en desperdicio y pérdidas económicas.

#### Where? (¿Dónde?)
En la mayoría de los hogares, principalmente dentro de refrigeradores donde se almacenan frutas, verduras y otros productos perecederos.

#### When? (¿Dónde?)
El desperdicio ocurre frecuentemente cuando los alimentos permanecen almacenados por tiempos prolongados sin monitoreo adecuado, intensificándose en días o semanas, según el tipo de alimento.

#### Who? (¿Quién?)
Usuarios domésticos, principalmente familias, adultos jóvenes, y personas preocupadas por la economía y la sostenibilidad ambiental.

#### How? (¿Cómo?)
Por falta de monitoreo tecnológico que detecte condiciones que aceleran la maduración y deterioro, así como por ausencia de alertas personalizadas para consumir a tiempo.

#### How much? (¿Cuánto?)
Se estima que un tercio de los alimentos producidos se desperdician globalmente. En términos económicos, esto representa pérdidas significativas para los hogares, además de impactos ambientales como generación de residuos y emisiones contaminantes.

##### 1.2.2.1. Lean UX Problem Statements

 - Los usuarios desperdician alimentos porque no tienen información precisa ni anticipada sobre la descomposición de la comida almacenada en sus refrigeradores.
 - La falta de una herramienta accesible que monitoree factores críticos como temperatura, humedad y gas etileno conduce a una gestión ineficiente del inventario alimenticio en hogares.
 - Las personas pierden dinero y contribuyen al impacto ambiental negativo debido a estas ineficientes y falta de alertas preventivas.

##### 1.2.2.2. Lean UX Assumptions
#### Business Assumptions
- Se asume que la implementación de FreshSense permitirá reducir significativamente el desperdicio alimentario en hogares, generando ahorro económico para los usuarios.

- Se espera que al ofrecer análisis avanzado de inventario y recetas personalizadas mediante suscripción, se genera un flujo constante de ingresos recurrentes para la startup.

- Se considera que el mercado doméstico está dispuesto a adoptar tecnología accesible para optimizar lagestión de alimentos, siendo un nicho rentable y escalable.

- Se supone que la facilidad de uso e integración del dispositivo con el app fomentará una alta retención y satisfacción del cliente.
#### User Assumptions
- Se asume que los usuarios valoran recibir alertas tempranas sobre el est ado de sus alimentos para evitar pérdidas innecesarias.

- Se espera que los usuarios quieran ahorrar dinero consumiendo alimentos antes de que se descompongan gracias a la información precisa del dispositivo.

- Se considera que los usuarios usarán activamente la app web para monitorear el estado de su refrigerador y aprovecharán las recetas personalizadas para maximizar la utilización de sus ingredientes.

- Se supone que la simplicidad y utilidad de la solución motivarán a los usuarios a recomendar FreshSense a otras personas preocupadas por reducir desperdicios.

##### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que ofrecer alertas anticipadas basadas en datos de temperatura, humedad y gas etileno ayudará a los usuarios a consumir sus alimentos antes de que se descompongan, reduciendo así el desperdicio de comida en sus hogares. Sabremos que esto es cierto cuando el porcentaje de alimentos reportados como consumidos antes de la fecha de alerta supere el 70% durante el primer mes de uso. 

- Creemos que permitir el acceso a la aplicación web desde múltiples dispositivos (PC, tablet, móvil) facilitará que los usuarios monitoreen el estado de sus alimentos en cualquier momento y lugar, aumentando la interacción con la plataforma. Sabremos que esto es cierto cuando al menos el 50% de los usuarios activos inicien sesión desde dos o más tipos de dispositivos en la primera semana tras la adopción.

- Creemos que agregar funciones premium como análisis detallado de inventario y recetas personalizadas incentivará a los usuarios a suscribirse y usar el sistema con mayor frecuencia. Sabremos que esto es cierto cuando al menos el 30% de los usuarios activos se suscriban al plan premium dentro de los tres primeros meses de uso.

- Creemos que la inclusión de recetas personalizadas basadas en los alimentos disponibles en el refrigerador motivará a los usuarios a aprovechar mejor sus ingredientes y reducir el desperdicio. Sabremos que esto es cierto cuando al menos el 40% de los usuarios utilicen las recetas sugeridas al menos una vez por semana durante el primer mes de uso.

##### 1.2.2.4. Lean UX Canvas
![alt text](assets/LeanUXCanvas_FreshSense.jpg)

## 1.3. Segmentos objetivo

Para el proyecto FreshSense se han seleccionado dos segmentos principales de usuarios a los cuales la solución aporta un valor claro y adaptado a sus necesidades específicas:

##Adultos jóvenes 
 - Edad: 25 a 40 años
 - Estilo de vida: Dinámico y ocupado.
 - Uso de tecnología: Frecuente.
 - Necesidad principal: Gestionar el inventario alimenticio de forma sencilla y eficiente sin dedicar mucho tiempo.
 - Beneficios buscados: Alertas oportunas y recomendaciones para evitar desperdicios y optimizar el consumo.

##Pequeños negocios o emprendedores de alimentos caseros
 - Perfil: Personas que elaboran y venden alimentos desde casa.
 - Necesidad principal: Controlar la frescura de sus productos para garantizar calidad y minimizar pérdidas.
 - Beneficios buscados: Solución económica y accesible para monitorear productos perecederos y manejar inventario eficientemente.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores
Conocer a los competidores es clave para identificar oportunidades y definir una estrategia efectiva para FreshSense. Este análisis considera tanto competidores directos, que ofrecen soluciones similares, como indirectos que abordan el problema del desperdicio alimentario desde otras perspectivas. Comprender sus fortalezas y debilidades permitirá posicionar mejor nuestra propuesta y diferenciarla en el mercado.

### 2.1.1. Análisis competitivo
![alt text](assets/AnalisisCompetitivo_FreshSense.png)
![alt text](assets/FODA_FreshSense.png)

El análisis competitivo realizado permite comprender con claridad el panorama actual del mercado y la posición que ocupa FreshSense frente a competidores relevantes como Orbisk, OneThird y Too Good To Go. Si bien cada actor tiene enfoques y modelos distintos, el valor diferencial de FreshSense radica en su enfoque específico para hogares con una solución tecnológica accesible, combinando hardware y app con un modelo freemium atractivo para el mercado objetivo.

Además, este análisis enfatiza las fortalezas de FreshSense en innovación, precio y marketing educativo, pero también revela áreas de mejora y desafíos potenciales frente a competidores consolidados en segmentos industriales o de consumo masivo. Las oportunidades de crecimiento incluyen el aumento en la conciencia ambiental y las alianzas estratégicas que pueden amplificar su alcance.

En conclusión, FreshSense tiene un posicionamiento sólido pero debe continuar innovando en experiencia de usuario y escalabilidad para consolidarse como líder en la categoría doméstica de control y reducción del desperdicio alimentario.
### 2.1.2. Estrategias y tácticas frente a competidores

FreshSense adoptará una estrategia centrada en diferenciarse por su enfoque específico en hogares, ofreciendo una solución accesible y fácil de usar para el control del desperdicio alimentario en refrigeradores domésticos. Para lograrlo, se aplicarán las siguientes tácticas:

- Campañas de marketing digital y contenidos educativos para sensibilizar sobre el desperdicio alimentario y los beneficios de una gestión eficiente del inventario doméstico.
- Ofrecer un hardware con precio competitivo y acceso gratuito a funciones básicas, incentivando la suscripción a planes premium que agreguen valor con análisis avanzados y recetas personalizadas.
- En redes sociales, producción de contenido útil y atractivo, incluyendo recetas, consejos de conservación y testimonios, que fomenten la comunidad y el engagement.
- Colaboraciones con supermercados, apps de recetas y plataformas de sostenibilidad para ampliar el alcance y la confianza en la marca.
- Desarrollo continuo de la app para maximizar su intuición, usabilidad y valor agregado mediante notificaciones y alertas personalizadas.
- Programas de soporte, encuestas de satisfacción y recompensas para fortalecer la lealtad y generar recomendaciones boca a boca.

Estas estrategias buscan posicionar a FreshSense no solo como un producto tecnológico, sino como un aliado en la reducción del desperdicio de alimentos con impacto positivo en la economía y el medio ambiente de los hogares.

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
### Segmento #1: Adultos jóvenes (25-40 años, dinámicos y ocupados)

| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 1                     | **Nombre:** Piero Tapia  <br> **Edad:** 26  <br> **Distrito:** Jesús María <br><br> **Resumen:** Piero Tapia, trabajador del sector salud, comentó que revisa el refrigerador un par de veces por semana, pero aun así suele botar embutidos y nuggets que no consume a tiempo. Su mayor preocupación es el impacto económico y la incomodidad de desperdiciar comida que otros podrían aprovechar. No utiliza ninguna aplicación ni listas, y reconoce que muchas veces termina comprando lo mismo y aburriéndose de su dieta. Cree que una aplicación le sería útil si cuenta con tutoriales accesibles en cualquier momento, alertas de alimentos por vencer y recetas que le ayuden a variar. Considera justo un costo entre 15 y 25 soles mensuales, similar a una plataforma de streaming, aunque advierte que las notificaciones excesivas podrían volverse molestas | ![Evidencia](assets/Entrevista%20Piero.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/15M_YnFO5NuGaYNpKAQJbU-r_Xq8Rc27l/view?usp=drive_link) 0-5:36 |


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 2                     | **Nombre:** Alvaro Yagui  <br> **Edad:** 26  <br> **Distrito:** Jesús María <br><br> **Resumen:** Álvaro Yagui, dedicado al área de ventas, señaló que la falta de tiempo y el cansancio hacen que olvide cocinar lo que compra, lo que provoca que carnes, plátanos y paltas se malogren con frecuencia. Asocia estas pérdidas con frustración y descuido, pues implican desperdicio de dinero. No usa aplicaciones para control, salvo alarmas en el celular, pero reconoce que resulta tedioso. Valora la idea de una aplicación que facilite el registro de alimentos mediante voz o escáner, acompañada de notificaciones claras y recetas para combinar los ingredientes disponibles. Está dispuesto a pagar entre 15 y 20 soles mensuales, un rango que equipara al de una suscripción de Spotify | ![Evidencia](assets/Entrevista%20Yagui.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/15M_YnFO5NuGaYNpKAQJbU-r_Xq8Rc27l/view?usp=drive_link) 5:36-13:41|


| Número de entrevista | Datos del entrevistado                                                                 | Evidencia de entrevista |
|-----------------------|-----------------------------------------------------------------------------------------|--------------------------|
| 3                     | **Nombre:** Gabriela Vasquez  <br> **Edad:** 25  <br> **Distrito:** Pueblo Libre <br><br> **Resumen:** Gabriela Vázquez, de 25 años, reconoció que suele revisar el refrigerador solo una vez por semana, lo que la lleva a olvidar alimentos y desperdiciar principalmente frutas y verduras. Este hábito le genera frustración y la sensación de estar perdiendo dinero. Aunque utiliza notas y calendario para organizarse, no aplica ninguna herramienta específica para gestionar la comida. Considera valiosa una aplicación siempre que sea intuitiva, atractiva y con recordatorios confiables, además de que le ofrezca recetas para aprovechar mejor lo que ya tiene. En cuanto al costo, ve razonable un plan grupal parecido al de Spotify, alrededor de 30 soles compartidos entre varias personas | ![Evidencia](assets/Entrevista%20Gabriela.jpg) <br> [📂 Ver entrevista](https://drive.google.com/file/d/15M_YnFO5NuGaYNpKAQJbU-r_Xq8Rc27l/view?usp=drive_link) 13:41-19:37|

### 2.2.3. Análisis de entrevistas
### Segmento #1: Adultos jóvenes (25-40 años, dinámicos y ocupados)
---
### Hallazgos :
## 👨 Piero Tapia

Revisa su refrigerador dos veces por semana, pero desecha embutidos y nuggets. Percibe el desperdicio como un problema económico y también ético/social, pues otros podrían aprovechar la comida. No utiliza apps ni listas, y menciona aburrimiento por consumir lo mismo cada semana.

**Puntos clave:**
- Valora el impacto **económico, ambiental y social** de reducir desperdicios.  
- Necesita un **tutorial claro y repetible** dentro de la app.  
- Ve las **recetas como un “gancho”** para mantenerse en la plataforma.  
- Estima justo pagar entre **15 y 25 soles mensuales**, similar a un servicio de streaming.  
- Advierte sobre **notificaciones excesivas**, por lo que se requieren alertas inteligentes.  


## 👨 Álvaro Yagui

Lleva un estilo de vida ocupado y reconoce que carnes, plátanos y paltas suelen malograrse porque olvida cocinarlos. Siente frustración y descuido al desperdiciar dinero. No usa apps de control, solo alarmas, que considera tediosas.

**Puntos clave:**
- El problema está ligado a la **falta de tiempo y energía**.  
- Sugiere un **registro automatizado** (voz o escáner con IA).  
- Interés en **recetas que eviten la monotonía**.  
- Dispuesto a pagar entre **15 y 20 soles mensuales**, comparable a Spotify.  

## 👩 Gabriela Vázquez (25 años)

Revisa el refrigerador solo una vez por semana, lo que ocasiona que olvide alimentos y termine botando principalmente frutas y verduras. Esto le genera frustración y sensación de pérdida económica. Se organiza con notas y calendario, pero no con herramientas específicas para alimentos.

**Puntos clave:**
- Necesita **alertas tempranas** sobre alimentos por vencer.  
- Busca una aplicación **intuitiva y atractiva** en su diseño.  
- Le interesan **recetas personalizadas** para aprovechar ingredientes.  
- Estaría dispuesta a pagar bajo un modelo **familiar** (~30 soles compartidos, estilo Spotify).  
---
### Segmento #2: Pequeños negocios / emprendedores de alimentos caseros
## 2.3. Needfinding
### 2.3.1. User Personas

#### SEGMENTO 1: Adultos jóvenes
<img alt="upc-logo" src="assets/José_userP1.png" width="600"/><br>

### SEGMENTO 2: Pequeños negocios / emprendedores de alimentos caseros
<img alt="upc-logo" src="assets/Luisa_userP2.png" width="600"/><br>
### 2.3.2. User Task Matrix
![alt text](assets/UserMatrix_Open.jpg)
Las tareas más frecuentes para los perfiles de usuario en FreshSense muestran claras diferencias según el rol y las necesidades de cada segmento.

José Jiménez, como adulto joven con poco tiempo libre, usa la aplicación principalmente para consultar el estado de sus alimentos y recibir alertas de vencimiento, funciones que considera muy importantes para evitar pérdidas y ahorrar dinero. Además, interactúa ocasionalmente con las recetas sugeridas para variar su dieta y con la función de compartir logros en redes sociales, aunque estas últimas no son prioritarias en su experiencia.

En contraste, Luisa Pérez, como emprendedora de alimentos caseros, enfoca su uso en el control detallado del inventario y en la revisión de reportes y proyecciones de compra, funciones que tienen gran importancia para asegurar la calidad de sus productos y reducir mermas en su negocio. Aunque consulta recetas con poca frecuencia, valora más la gestión manual del inventario y los reportes para planificar mejor la producción.
### 2.3.3. User Journey Mapping
Segmento 1:

Mediante este artefacto se explicará y comprenderá cómo los usuarios del segmento 1 realizan sus actividades para gestionar sus alimentos y evitar desperdicios desde su propia perspectiva. Este segmento representa a personas con un estilo de vida dinámico, que suelen olvidar revisar con frecuencia su refrigerador y terminan desechando productos en mal estado. Valoran soluciones tecnológicas simples y rápidas que les permitan recibir alertas oportunas, optimizar el consumo mediante recetas prácticas y tener un mayor control de su inventario sin invertir tiempo adicional.
![alt text](assets/Jose_Segmento1_Map.png)

Segmento 2: 

Mediante este artefacto se explicará y comprenderá cómo los usuarios del segmento 2 realizan sus actividades para mantener el control de sus insumos y asegurar la frescura de los productos que ofrecen a sus clientes. Este segmento representa a pequeños negocios que trabajan desde casa y enfrentan pérdidas económicas por caducidad de insumos debido a la gestión manual. Valoran herramientas que automaticen el monitoreo de la frescura, brinden reportes y proyecciones de compra, y contribuyan a mantener la calidad y la confianza de sus clientes, garantizando así la sostenibilidad de su negocio.
![alt text](assets/Luisa_Segmento2_Map.png)

### 2.3.4. Empathy Mapping
### 2.3.5. As-is Scenario Mapping
Segmento 1:

Mediante este artefacto, se ha realizado la elaboración del As-is Scenario Mapping para el primer segmento (Adultos jóvenes). Este escenario refleja cómo los usuarios con un estilo de vida ocupado gestionan actualmente sus alimentos, dependiendo en gran medida de la memoria o revisiones esporádicas del refrigerador. Se evidencian las dificultades que enfrentan al olvidar productos, los gastos innecesarios por alimentos desperdiciados y la frustración al no contar con un sistema que los apoye en la organización. Asimismo, se muestran las percepciones y emociones que experimentan en cada etapa de su recorrido, desde la compra hasta el descarte de los productos.
![alt text](assets/Segmento1_AsIs_Open.png)

Segmento 2:

Mediante este artefacto, se ha llevado a cabo la elaboración del As-is Scenario Mapping para el segundo segmento (Emprendedores de alimentos caseros). Este escenario refleja cómo los usuarios que producen y venden alimentos gestionan sus insumos de manera manual, utilizando cuadernos o archivos de Excel para llevar el control de su inventario. Se identifican las dificultades que enfrentan por pérdidas de productos caducados, la incertidumbre al no contar con alertas oportunas y el impacto económico negativo en su negocio. Asimismo, se destacan las percepciones y emociones que surgen en cada etapa, como el estrés por la gestión manual, la preocupación por mantener la calidad y la satisfacción de los clientes, y la presión constante de evitar pérdidas que afectan sus ingresos.
![alt text](assets/Segmento2_AsIs_Open.png)
## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping
### Segmento #1 : Adultos jóvenes
![alt text](assets/ToBe_Scenario_Seg1.jpeg)
### Segmento #2 : Pequeños negocios / emprendedores de alimentos caseros
![alt text](assets/ToBe_Scenario_Seg2.jpeg)
## 3.2. User Stories

| Epic / User Story ID | Título                         | Descripción                                                                 | Criterios de Aceptación                                                                                                                                                                                                                                                                                               | Relacionado con (Epic ID) |
|-----------------------|--------------------------------|-----------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------|
| US01                 | Monitoreo de alimentos         | Como usuario, quiero que el sensor mida temperatura, humedad y etileno para conocer el estado real de mis alimentos. | **Escenario 1:** Registro de datos exitoso. <br> Dado que el sensor está activo <br> Cuando detecta variaciones <br> Entonces la información debe enviarse a la app en tiempo real. <br><br> **Escenario 2:** Error de conexión. <br> Dado que el sensor pierde conexión <br> Entonces la app debe mostrar un error y sugerir reconexión. | EP01 |
| US02                 | Visualización de inventario    | Como usuario, quiero ver en la app el estado de cada alimento para identificar cuáles están en riesgo. | **Escenario 1:** Vista general con colores. <br> Dado que accedo al panel <br> Cuando abro la app <br> Entonces debo ver estado (verde, amarillo, rojo). <br><br> **Escenario 2:** Detalle. <br> Dado que selecciono un alimento <br> Entonces debo ver fecha estimada de caducidad y condiciones actuales. | EP01 |
| US03                 | Alertas anticipadas            | Como usuario, quiero recibir alertas cuando un alimento esté por vencer para consumirlo a tiempo. | **Escenario 1:** Activación de alerta. <br> Dado que un alimento está próximo a caducar <br> Entonces el sistema debe notificarme. <br><br> **Escenario 2:** No generar alerta sin riesgo. <br> Dado que no hay alimentos en riesgo <br> Entonces no deben aparecer notificaciones. | EP02 |
| US04                 | Configuración de notificaciones| Como usuario, quiero configurar la hora y frecuencia de las notificaciones para que no sean invasivas. | **Escenario 1:** Configuración exitosa. <br> Dado que ingreso parámetros válidos <br> Entonces el sistema debe aplicarlos. <br><br> **Escenario 2:** Error en configuración. <br> Dado que ingreso valores inválidos <br> Entonces el sistema debe mostrar un mensaje de error. | EP02 |
| US05                 | Registro automático de alimentos | Como usuario, quiero registrar mis alimentos mediante voz o escáner para ahorrar tiempo. | **Escenario 1:** Registro por voz. <br> Dado que digo “compré pollo y plátanos” <br> Entonces la app debe registrar esos productos. <br><br> **Escenario 2:** Registro por escaneo. <br> Dado que escaneo un código válido <br> Entonces el producto debe registrarse automáticamente. | EP03 |
| US06                 | Edición de inventario          | Como usuario, quiero editar manualmente mi inventario para mantenerlo actualizado. | **Escenario 1:** Edición exitosa. <br> Dado que modifico cantidad o fecha <br> Entonces la app debe guardar los cambios. <br><br> **Escenario 2:** Error en edición. <br> Dado que ingreso datos inválidos <br> Entonces la app debe mostrar un mensaje de error. | EP03 |
| US07                 | Resumen semanal                | Como usuario, quiero recibir un reporte semanal de mis alimentos consumidos y desperdiciados. | **Escenario 1:** Generación de reporte. <br> Dado que ha pasado una semana <br> Entonces debo ver un resumen con métricas de consumo. <br><br> **Escenario 2:** Envío por correo. <br> Dado que activo esa opción <br> Entonces debo recibir el reporte por email. | EP03 |
| US08                 | Recetas personalizadas         | Como usuario, quiero recibir recetas basadas en los alimentos que están próximos a caducar. | **Escenario 1:** Recetas con ingredientes en riesgo. <br> Dado que tengo productos próximos a vencer <br> Entonces la app debe mostrar recetas con ellos. <br><br> **Escenario 2:** Sin riesgo. <br> Dado que no hay productos en riesgo <br> Entonces la app debe mostrar recetas generales. | EP04 |
| US09                 | Filtros de recetas             | Como usuario, quiero filtrar recetas por dificultad, tiempo o dieta para adaptarlas a mi estilo de vida. | **Escenario 1:** Filtro aplicado. <br> Dado que selecciono “rápido” <br> Entonces la app debe mostrar recetas de menos de 30 min. <br><br> **Escenario 2:** Sin coincidencias. <br> Dado que no hay recetas bajo un filtro <br> Entonces la app debe mostrar un mensaje “no se encontraron recetas”. | EP04 |
| US10                 | Tutorial interactivo           | Como usuario, quiero un tutorial inicial y repetible para aprender a usar la app. | **Escenario 1:** Tutorial visible. <br> Dado que soy nuevo usuario <br> Entonces debo ver un tutorial al iniciar la app. <br><br> **Escenario 2:** Repetir tutorial. <br> Dado que ya he usado la app <br> Cuando accedo a “Ayuda” <br> Entonces debo poder repetir el tutorial. | EP05 |
| US11                 | Interfaz atractiva             | Como usuario, quiero una interfaz visual sencilla y atractiva que me motive a usar la aplicación. | **Escenario 1:** Diseño usable. <br> Dado que navego por la app <br> Entonces los menús deben ser claros y accesibles. <br><br> **Escenario 2:** Error de usabilidad. <br> Dado que un botón está mal configurado <br> Entonces la app debe notificarlo al equipo técnico. | EP05 |
| US12                 | Análisis detallado de inventario | Como usuario premium, quiero acceder a un análisis detallado de mis alimentos para optimizar mis compras. | **Escenario 1:** Reporte avanzado. <br> Dado que soy usuario premium <br> Entonces debo ver métricas detalladas de inventario. <br><br> **Escenario 2:** Sin acceso. <br> Dado que no soy premium <br> Entonces debo ver un aviso de “Función disponible en plan premium”. | EP06 |
| US13                 | Estadísticas de ahorro         | Como usuario premium, quiero ver estadísticas de ahorro económico y reducción de desperdicio. | **Escenario 1:** Estadísticas visibles. <br> Dado que accedo a mi perfil <br> Entonces debo ver mi ahorro acumulado. <br><br> **Escenario 2:** Sin datos. <br> Dado que soy nuevo usuario premium <br> Entonces la app debe mostrar un mensaje “aún no hay estadísticas”. | EP06 |
| US14                 | Recetas exclusivas premium     | Como usuario premium, quiero tener acceso a recetas avanzadas para aprovechar mis ingredientes. | **Escenario 1:** Acceso permitido. <br> Dado que soy premium <br> Entonces debo ver recetas exclusivas. <br><br> **Escenario 2:** Acceso restringido. <br> Dado que no soy premium <br> Entonces no debo ver recetas exclusivas. | EP06 |
| US15                 | Reporte de impacto ambiental   | Como usuario, quiero ver un reporte mensual del impacto ambiental evitado (ej. kg de CO₂ ahorrados). | **Escenario 1:** Reporte generado. <br> Dado que accedo a mi perfil <br> Entonces debo ver el impacto ambiental acumulado. <br><br> **Escenario 2:** Sin datos. <br> Dado que no he registrado consumo <br> Entonces la app debe mostrar “aún no hay datos”. | EP07 |
| US16                 | Compartir logros en redes      | Como usuario, quiero compartir mis logros de reducción de desperdicio en redes sociales. | **Escenario 1:** Compartir exitoso. <br> Dado que selecciono “Compartir” <br> Entonces la app debe publicar mi logro en la red seleccionada. <br><br> **Escenario 2:** Error de conexión. <br> Dado que la red no responde <br> Entonces la app debe mostrar un mensaje de error. | EP07 |
| US17                 | Sincronización con smart fridges | Como usuario, quiero que FreshSense se integre con refrigeradores inteligentes para recibir datos combinados y mejorar la precisión. | **Escenario 1:** Integración exitosa. <br> Dado que el frigorífico es compatible <br> Cuando la integración está activada <br> Entonces debe sincronizar datos de sensores automáticamente. <br><br> **Escenario 2:** Visualización combinada. <br> Dado que los datos son sincronizados <br> Entonces la app debe mostrar estado combinado de alimentos. <br><br> **Escenario 3:** Error de integración. <br> Dado que la integración falla <br> Entonces la app debe notificar el error al usuario. | EP08                       |
| US18                 | Control por voz con asistentes  | Como usuario, quiero poder controlar funciones básicas de FreshSense con asistentes de voz (Alexa, Google). | **Escenario 1:** Comando de voz exitoso. <br> Dado que el usuario emite comando <br> Cuando el sistema lo recibe <br> Entonces confirma con respuesta audible o visual. <br><br> **Escenario 2:** Funcionalidad configurada. <br> Dado que el usuario configura integración de voz <br> Entonces la función queda habilitada. <br><br> **Escenario 3:** Sin integración configurada. <br> Dado que la integración no está activa <br> Entonces no se acepta comando de voz. | EP08                       |
| US19                 | Notificaciones personalizadas   | Como usuario, quiero configurar qué notificaciones recibir y a qué dispositivo para no ser molestado. | **Escenario 1:** Selección de preferencias. <br> Dado que el usuario abre configuración <br> Cuando selecciona tipos y horarios <br> Entonces la app guarda preferencias. <br><br> **Escenario 2:** Envío filtrado. <br> Dado que preferencias están guardadas <br> Entonces notificaciones se envían solo a dispositivos configurados. <br><br> **Escenario 3:** Activar/desactivar alertas. <br> Dado que el usuario cambia estado de alertas <br> Entonces la app aplica el cambio correctamente. | EP08                       |
| US20                 | Logros y recompensas            | Como usuario, quiero ganar logros por uso frecuente y reducción de desperdicio para motivarme. | **Escenario 1:** Seguimiento de progreso. <br> Dado que el usuario usa la app regularmente <br> Cuando cumple metas <br> Entonces se otorgan badges o puntos. <br><br> **Escenario 2:** Visualización de logros. <br> Dado que se han obtenido logros <br> Entonces estos aparecen en perfil del usuario. <br><br> **Escenario 3:** Notificación de nuevo logro. <br> Dado que se gana un logro <br> Entonces se notifica al usuario. | EP09                       |
| US21                 | Compartir en redes sociales     | Como usuario, quiero compartir mis logros en redes sociales para inspirar a otros. | **Escenario 1:** Selección de compartir. <br> Dado que el usuario presiona "Compartir" <br> Cuando se genera contenido visual <br> Entonces se publica en la red social seleccionada. <br><br> **Escenario 2:** Error de conexión. <br> Dado que la red social no responde <br> Entonces se muestra mensaje de error y opción de reintentar. | EP09                       |
| US22                 | Retos y competencias            | Como usuario, quiero participar en retos con otros usuarios para reducir desperdicio y ganar premios. | **Escenario 1:** Inscripción en retos. <br> Dado que la app ofrece retos <br> Cuando el usuario se inscribe <br> Entonces puede participar y ver su progreso. <br><br> **Escenario 2:** Visualizar ranking. <br> Dado que el reto está activo <br> Entonces la app muestra tabla con posiciones. <br><br> **Escenario 3:** Salir del reto. <br> Dado que el usuario decide salir <br> Entonces la app lo elimina del reto. | EP09                       |
| US23                 | Categorías personalizadas       | Como usuario, quiero crear y asignar categorías propias para organizar mis alimentos según mi preferencia. | **Escenario 1:** Crear categoría. <br> Dado que el usuario solicita nueva categoría <br> Cuando ingresa nombre válido <br> Entonces se crea y guarda categoría. <br><br> **Escenario 2:** Asignar categoría. <br> Dado que categoría existe <br> Entonces se puede asignar a alimentos. <br><br> **Escenario 3:** Persistencia. <br> Dado que se guarda la estructura <br> Entonces esta se mantiene visible al volver a la app. | EP10                       |
| US24                 | Historial de consumo            | Como usuario, quiero consultar un historial de consumo para analizar mis hábitos alimenticios y ajustar compras. | **Escenario 1:** Registro de consumo. <br> Dado que un alimento se consume o descarta <br> Entonces se registra la fecha en historial. <br><br> **Escenario 2:** Visualizar histórico. <br> Dado que hay datos registrados <br> Entonces se muestra listado o gráfica ordenada. <br><br> **Escenario 3:** Filtrar y exportar. <br> Dado que el usuario aplica filtros <br> Entonces puede exportar datos en formato común. | EP10                       |
| US25                 | Sugerencias de compra           | Como usuario, quiero recibir sugerencias de compra basadas en inventario y consumo para evitar faltantes o exceso. | **Escenario 1:** Análisis de inventario. <br> Dado que hay datos disponibles <br> Cuando la app realiza análisis <br> Entonces genera recomendaciones. <br><br> **Escenario 2:** Notificación periódica. <br> Dado que el usuario habilita notificaciones <br> Entonces recibe sugerencias semanales o mensuales. <br><br> **Escenario 3:** Personalización. <br> Dado que el usuario modifica sugerencias <br> Entonces la app ajusta recomendaciones futuras. | EP10 |

## Epics

| Epic ID | Título                               | Descripción                                                                                     |
|---------|---------------------------------------|-------------------------------------------------------------------------------------------------|
| EP01    | Monitoreo de alimentos                | Gestionar en tiempo real el estado de frutas, verduras y perecibles con sensores de temperatura, humedad y gas etileno. |
| EP02    | Alertas y notificaciones inteligentes | Avisar a los usuarios cuando un alimento esté próximo a vencer o deteriorarse.                  |
| EP03    | Gestión de inventario alimenticio     | Permitir registrar, visualizar y organizar los alimentos disponibles en el refrigerador.        |
| EP04    | Recetas personalizadas                | Recomendar preparaciones basadas en los ingredientes disponibles para fomentar su consumo.      |
| EP05    | Experiencia de usuario y accesibilidad| Garantizar una app intuitiva, atractiva, con tutoriales y facilidad de uso.                     |
| EP06    | Modelo de suscripción premium         | Ofrecer planes pagos con funciones avanzadas como análisis detallado, estadísticas y recetas premium. |
| EP07    | Impacto ambiental y sostenibilidad    | Promover la reducción del desperdicio y concientizar al usuario sobre el ahorro económico y ecológico. |
| EP08    | Integración con dispositivos inteligentes | Facilitar la conexión y sincronización de FreshSense con refrigeradores inteligentes y asistentes de voz para mejorar el control y la experiencia del usuario. |
| EP09    | Comunidad y gamificación     | Fomentar la motivación y el compromiso del usuario a través de logros, retos y la posibilidad de compartir sus avances en redes sociales. |
| EP10    | Gestión avanzada de inventario | Proveer herramientas avanzadas para la organización, análisis y optimización del inventario alimenticio personal mediante categorías, historial y recomendaciones. |

## 3.3. Impact Mapping

## 3.4. Product Backlog
| # Orden | User Story ID | Título                          | Descripción                                                                 | Story Points (1 / 2 / 3 / 5 / 8) |
|---------|---------------|----------------------------------|-----------------------------------------------------------------------------|----------------------------------|
| 1       | US01          | Monitoreo de alimentos           | Como usuario, quiero que el sensor mida temperatura, humedad y etileno para conocer el estado real de mis alimentos. | 5 |
| 2       | US02          | Visualización de inventario      | Como usuario, quiero ver en la app el estado de cada alimento para identificar cuáles están en riesgo. | 3 |
| 3       | US03          | Alertas anticipadas              | Como usuario, quiero recibir alertas cuando un alimento esté por vencer para poder consumirlo a tiempo. | 5 |
| 4       | US04          | Configuración de notificaciones  | Como usuario, quiero configurar la hora y frecuencia de las notificaciones para que no sean invasivas. | 3 |
| 5       | US05          | Registro automático de alimentos | Como usuario, quiero registrar mis alimentos mediante voz o escáner para ahorrar tiempo. | 5 |
| 6       | US06          | Edición de inventario            | Como usuario, quiero editar manualmente mi inventario para mantenerlo actualizado. | 2 |
| 7       | US07          | Resumen semanal                  | Como usuario, quiero recibir un reporte semanal de mis alimentos consumidos y desperdiciados. | 3 |
| 8       | US08          | Recetas personalizadas           | Como usuario, quiero recibir recetas basadas en los alimentos que están próximos a caducar. | 5 |
| 9       | US09          | Filtros de recetas               | Como usuario, quiero filtrar recetas por dificultad, tiempo o dieta para adaptarlas a mi estilo de vida. | 3 |
| 10      | US10          | Tutorial interactivo             | Como usuario, quiero un tutorial inicial y repetible para aprender a usar la app. | 2 |
| 11      | US11          | Interfaz atractiva               | Como usuario, quiero una interfaz visual sencilla y atractiva que me motive a usar la aplicación. | 3 |
| 12      | US12          | Análisis detallado de inventario | Como usuario premium, quiero acceder a un análisis detallado de mis alimentos para optimizar mis compras. | 5 |
| 13      | US13          | Estadísticas de ahorro           | Como usuario premium, quiero ver estadísticas de ahorro económico y reducción de desperdicio. | 3 |
| 14      | US14          | Recetas exclusivas premium       | Como usuario premium, quiero tener acceso a recetas avanzadas para aprovechar mis ingredientes. | 2 |
| 15      | US15          | Reporte de impacto ambiental     | Como usuario, quiero ver un reporte mensual del impacto ambiental evitado (ej. kg de CO₂ ahorrados). | 3 |
| 16      | US16          | Compartir logros en redes        | Como usuario, quiero compartir mis logros de reducción de desperdicio en redes sociales. | 2 |
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
#### 5.2.1.2. Aspect Leaders and Collaborators
#### 5.2.1.3. Sprint Backlog 1
#### 5.2.1.4. Development Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint  



# Conclusiones

# Bibliografía

# Anexos
