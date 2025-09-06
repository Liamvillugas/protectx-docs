<!--* Carátula -->

<div align="center">

# Informe de Trabajo Final 📙

<img src="./resources/Banner-UPC.png" alt="Banner UPC">

### Universidad Peruana de Ciencias Aplicadas ♨️

🧑‍💻 **Carrera:** Ingeniería de Software – 2025-02  

**Código y nombre del curso:** [1ASI0729] - [Desarrollo de Aplicaciones Open Source]  

**Sección:** 7414  

**Docente:** Rafael Oswaldo Castro Veramendi  

**Startup:** ProtectX

**Producto:** [Nombre del Producto]  

<div align='left'>  

~~~C#
static string[] Integrantes() {
    return new string[] {
        "🧑‍💻 Ruiz Huisa, Daniel Elias - 202210764",
        "🧑‍💻 Villugas Jeronimo , Liam Anderson - 202211634",
        "👨‍💻 Apellidos, Nombres - Código",
        "👩‍💻 Apellidos, Nombres - Código",       
        "👩‍💻 Apellidos, Nombres - Código", 
    };
}
~~~

</div>

Agosto del 2025 🗓️  

</div>

---

## Registro de Versiones del Informe
| Versión | Fecha | Descripción | Responsable |
|---------|-------|-------------|-------------|
| 1.0     | 01/09/2025 | Versión inicial | Daniel Ruiz |
| 1.1     | dd/mm/yyyy | Ajustes sección II | Integrante Y |

---

## Project Report Collaboration Insights
> Aquí se registran observaciones del trabajo colaborativo, contribuciones por sprint y aprendizajes.

---

## Contenido del Informe

- [Informe de Trabajo Final 📙](#informe-de-trabajo-final-)
    - [Universidad Peruana de Ciencias Aplicadas ♨️](#universidad-peruana-de-ciencias-aplicadas-️)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido del Informe](#contenido-del-informe)
  - [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile 📌](#11-startup-profile-)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
      - [5W’s + 2H’s](#5ws--2hs)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas 💼](#22-entrevistas-)
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
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
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
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.X. Sprint n](#52x-sprint-n)
      - [5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)
      - [5.2.X.2. Aspect Leaders and Collaborators](#52x2-aspect-leaders-and-collaborators)
      - [5.2.X.3. Sprint Backlog n](#52x3-sprint-backlog-n)
      - [5.2.X.4. Development Evidence for Sprint Review](#52x4-development-evidence-for-sprint-review)
      - [5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)
      - [5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)
      - [5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)
      - [5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews](#53-validation-interviews)
    - [5.3.1. Diseño de entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

---

## Student Outcome
> Describir los resultados de aprendizaje y cómo se alinean con el curso.

---

# Capítulo I: Introducción  



## 1.1. Startup Profile 📌
### 1.1.1. Descripción de la Startup
ProtectX es una startup del sector seguridad que busca responder al problema de la creciente inseguridad ciudadana en Lima y sus alrededores. Ofrece un servicio innovador basado en IoT que, ante cualquier irregularidad, envía una alerta inmediata a la entidad policial más cercana. Su propuesta combina sensores, alarmas y cámaras inteligentes, gestionadas desde una aplicación móvil que centraliza la información. El modelo de negocio se sustenta en un sistema de suscripción por niveles, que permite a los usuarios acceder a mayor cantidad de sensores según sus necesidades. Dirigida a personas que viven solas o que sienten temor por la inseguridad, ProtectX busca proporcionar un ambiente más seguro y fortalecer la protección de cada vivienda.
### 1.1.2. Perfiles de integrantes del equipo  
<div align='center'>
   <!--TODO: integrante 1 -->
  > 🧑‍💻 <strong>Daniel Elias Ruiz Huisa</strong> 
   

   <div align='center'>
     
   <img src="resources/members/daniel.png" alt="imagen Daniel" width="100" align='right'>

   ~~~txt
   Soy estudiante de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas (UPC), actualmente cursando el 6to ciclo de la carrera.
   
   Durante mi formación he adquirido conocimientos en diversas tecnologías y buenas prácticas de desarrollo. Mis principales fortalezas se encuentran lenguajes con orientados fuertemente a la POO como C++ y Java. 

   Adicionalmente, he trabajado con PGAdmin, MongoAtlas, MySQLlite como gestores de bases de datos, y con tecnologías web que me permiten tener una visión integral del desarrollo de software.

   ~~~

   </div>


   <div align='center'>
   <!--TODO: integrante 2 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/members/[name].png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>


    <div align='center'>
   <!--TODO: integrante 3 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/members/[name].png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>

      <div align='center'>
   <!--TODO: integrante 4 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/members/[name].png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>

      <div align='center'>
   <!--TODO: integrante 5 -->
  > 🧑‍💻 <strong>[Complete Name]</strong> 
   

   <div align='center'>
     
   <img src="resources/members/[name].png" alt="imagen [name]" width="100" align='right'>

   ~~~txt
[descripcion]

   ~~~

   </div>

---
<div align='left'>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática  

<b>Problemática general</b>
En Lima y sus alrededores, la inseguridad ciudadana se ha convertido en una de las principales preocupaciones de la población. El aumento de robos, asaltos y delitos contra la propiedad ha superado la efectividad de los métodos tradicionales de protección, como rejas o rondas vecinales, generando una creciente sensación de vulnerabilidad. Este escenario plantea la necesidad de soluciones más eficientes que respondan a la magnitud del problema.

<b>Dimensión social</b>
La inseguridad no solo afecta el patrimonio de los ciudadanos, sino también su bienestar emocional. Muchas personas viven con miedo constante, lo que reduce su calidad de vida y limita su libertad de movimiento, especialmente en sectores donde los índices delictivos son más altos. Este clima de temor generalizado genera desconfianza en la comunidad, debilitando los lazos sociales y reforzando la percepción de que los hogares no son espacios plenamente seguros.

<b>Dimensión económica</b>
El impacto económico de la inseguridad se refleja en pérdidas materiales por robos, daños en las viviendas y el gasto recurrente en medidas de protección tradicionales que resultan insuficientes. Además, obliga a las familias a destinar recursos adicionales a reforzar la seguridad, lo que representa una carga financiera significativa. En conjunto, estos costos reducen la capacidad de ahorro y afectan la economía doméstica, evidenciando que la inseguridad es también un problema que compromete la estabilidad financiera de los hogares.

#### 5W’s + 2H’s
 🟢 **WHAT (Qué)**  
  Creciente ola de inseguridad ciudadana caracterizada por robos, asaltos y delitos contra la propiedad.  

 🟢 **WHEN (Cuándo)**  
  Actualmente, con mayor incidencia en los últimos años debido al incremento sostenido de la criminalidad.  

 🟢 **WHERE (Dónde)**  
  Principalmente en Lima Metropolitana y zonas aledañas con altos índices delictivos.  

 🟢 **WHO (Quién)**  
  Ciudadanos en general, con especial impacto en personas que viven solas o con temor frente a la inseguridad.  

 🟢 **WHY (Por qué)**  
  Falta de respuestas rápidas y efectivas ante emergencias, limitada capacidad de cobertura policial y deficiencia en las medidas tradicionales de seguridad.  

 🟢 **HOW (Cómo)**  
  Las personas recurren a rejas, cerraduras, cámaras convencionales o rondas vecinales, pero estas acciones resultan insuficientes frente a la magnitud del problema.  

 🟢 **HOW MUCH (Cuánto)**   
 El costo se refleja en pérdidas materiales por robos, daños en viviendas y una carga financiera extra para las familias, además del impacto social derivado del miedo y la desconfianza.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements  
#### 1.2.2.2. Lean UX Assumptions  
- Business Outcomes  
- User Outcomes  
#### 1.2.2.3. Lean UX Hypothesis Statements  
#### 1.2.2.4. Lean UX Canvas  
---
## 1.3. Segmentos objetivo  

---

# Capítulo II: Requirements Elicitation & Analysis  

## 2.1. Competidores
### 2.1.1. Análisis competitivo  
### 2.1.2. Estrategias y tácticas frente a competidores  
---
## 2.2. Entrevistas 💼
### 2.2.1. Diseño de entrevistas  
### 2.2.2. Registro de entrevistas  
### 2.2.3. Análisis de entrevistas  
---
## 2.3. Needfinding
### 2.3.1. User Personas  
### 2.3.2. User Task Matrix  
### 2.3.3. User Journey Mapping  
### 2.3.4. Empathy Mapping  
### 2.3.5. As-is Scenario Mapping  
---
## 2.4. Ubiquitous Language  

---

# Capítulo III: Requirements Specification  

## 3.1. To-Be Scenario Mapping  
## 3.2. User Stories  
## 3.3. Impact Mapping  
## 3.4. Product Backlog  

---

# Capítulo IV: Product Design  

## 4.1. Style Guidelines  
### 4.1.1. General Style Guidelines  
### 4.1.2. Web Style Guidelines  
---
## 4.2. Information Architecture  
### 4.2.1. Organization Systems  
### 4.2.2. Labeling Systems  
### 4.2.3. SEO Tags and Meta Tags  
### 4.2.4. Searching Systems  
### 4.2.5. Navigation Systems  
---
## 4.3. Landing Page UI Design  
### 4.3.1. Landing Page Wireframe  
### 4.3.2. Landing Page Mock-up  
---
## 4.4. Web Applications UX/UI Design  
### 4.4.1. Web Applications Wireframes  
### 4.4.2. Web Applications Wireflow Diagrams  
### 4.4.3. Web Applications Mock-ups  
### 4.4.4. Web Applications User Flow Diagrams  
---
## 4.5. Web Applications Prototyping  
---
## 4.6. Domain-Driven Software Architecture  
### 4.6.1. Software Architecture Context Diagram  
### 4.6.2. Software Architecture Container Diagrams  
### 4.6.3. Software Architecture Components Diagrams  
---
## 4.7. Software Object-Oriented Design  
### 4.7.1. Class Diagrams  
### 4.7.2. Class Dictionary  
---
## 4.8. Database Design  
### 4.8.1. Database Diagram  

---

# Capítulo V: Product Implementation, Validation & Deployment  

## 5.1. Software Configuration Management  
### 5.1.1. Software Development Environment Configuration  
### 5.1.2. Source Code Management  
### 5.1.3. Source Code Style Guide & Conventions  
### 5.1.4. Software Deployment Configuration  
---
## 5.2. Landing Page, Services & Applications Implementation  
### 5.2.X. Sprint n  
#### 5.2.X.1. Sprint Planning n  
#### 5.2.X.2. Aspect Leaders and Collaborators  
#### 5.2.X.3. Sprint Backlog n  
#### 5.2.X.4. Development Evidence for Sprint Review  
#### 5.2.X.5. Execution Evidence for Sprint Review  
#### 5.2.X.6. Services Documentation Evidence for Sprint Review  
#### 5.2.X.7. Software Deployment Evidence for Sprint Review  
#### 5.2.X.8. Team Collaboration Insights during Sprint  
---
## 5.3. Validation Interviews  
### 5.3.1. Diseño de entrevistas  
### 5.3.2. Registro de entrevistas  
### 5.3.3. Evaluaciones según heurísticas  
---
## 5.4. Video About-the-Product  

---

# Conclusiones  

## Conclusiones y recomendaciones  

## Video About-the-Team  

---

# Bibliografía  
> Referencias en formato APA.  

---

# Anexos  
> Evidencias, capturas, diagramas adicionales.  
</div>
