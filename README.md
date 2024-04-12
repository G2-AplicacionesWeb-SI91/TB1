# TB1
---

# Carátula
- **Universidad**: UPC
- **Carrera**: Ingeniería de Software
- **Curso**: Desarrollo de Aplicaciones Open Source
- **Sección**: SI91
- **Profesor**: 

---

# Informe de Trabajo Final
- **Nombre del Startup**: a
- **Nombre del Producto**: TrackMyRoute
- **Relación de Integrantes**:
- - Ramirez Mendoza, Carlos Arian (u202020108)
- - Valenzuela Vallejos, Alessandro Stefano(u202214695)
- - Rivas Sarango, David Alejandro (U20191E831)
- **Mes y Año**: Abril del 2024

---

# Registro de Versiones del Informe
El objetivo de esta sección es resumir las modificaciones relevantes que se realizan al informe durante el ciclo de vida del proyecto. Esta sección inicia en una página nueva y se incluye un cuadro con la siguiente estructura:

| **Versión** | **Fecha** | **Autor** | **Descripción de Modificación** |
|-------------|-----------|-----------|---------------------------------|
| ...         | ...       | ...       | ...                             |

---
# Project Report Collaboration Insights 



---

# Tabla de contenidos
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1 Startup Profile](#11-startup-profile)
        - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
	    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2 Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3 Lean UX Hypothesis Statements](#1211-lean-ux-hyphotesis-statements)
            - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
        - [1.3 Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1 Competidores](#21-competidores)
        - [2.1.1 Análisis competitivo](#211-análisis-competitivo)
        - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2 Entrevistas](#22-entrevistas)
        - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
        - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)
        - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)
    - [2.3 Needfinding](#23-needfinding)
        - [2.3.1 User Personas](#231-user-personas)
        - [2.3.2 User Task Matrix](#232-user-task-matrix)
        - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
        - [2.3.4 Empathy Mapping](#234-empathy-mapping)
        - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [2.4 Ubiquitous Language](#24-ubiquitous-language)

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2 User Stories](#32-user-stories)
    - [3.3 Impact Mapping](#33-impact-mapping)
    - [3.4 Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1 Style Guidelines](#41-style-guidelines)
        - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
        - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
    - [4.2 Information Architecture](#42-information-architecture)
        - [4.2.1 Organization Systems](#421-organization-systems)
        - [4.2.2 Labeling Systems](#422-labeling-systems)
        - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
        - [4.2.4 Searching Systems](#424-searching-systems)
        - [4.2.5 Navigation Systems](#425-navigation-systems)
    - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
        - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
        - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
        - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
        - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
        - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
        - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
    - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
    - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
        - [4.6.1 Software Architecture Context Diagram](#461-software-architecture-context-diagram)
        - [4.6.2 Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
        - [4.6.3 Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
    - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1 Class Diagrams](#471-class-diagrams)
        - [4.7.2 Class Dictionary](#472-class-dictionary)
    - [4.8 Database Design](#48-database-design)
        - [4.8.1 Database Diagram](#481-database-diagram)

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation-deployment)
    - [5.1 Software Configuration Management](#51-software-configuration-management)
        - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2 Source Code Management](#512-source-code-management)
        - 5.1.3 Source Code Style Guide & Conventions
        - 5.1.4 Software Deployment Configuration
    - [5.2 Landing Page, Services & Applications Implementation](#52-landing-page-services-applications-implementation)
        - [5.2.1 Sprint 1](#521-sprint-1)
            - [5.2.1.1 Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2 Sprint Backlog 1](#5212-sprint-backlog-1)
            - [5.2.1.3 Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
            - [5.2.1.4 Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
            - [5.2.1.5 Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
                       - [5.2.1.6 Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7 Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8 Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
        - [5.2.2 Sprint 2](#522-sprint-2)
            - [5.2.2.1 Sprint Planning 2](#5221-sprint-planning-2)
            - [5.2.2.2 Sprint Backlog 2](#5222-sprint-backlog-2)
            - [5.2.2.3 Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
            - [5.2.2.4 Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
            - [5.2.2.5 Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
            - [5.2.2.6 Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
            - [5.2.2.7 Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
            - [5.2.2.8 Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
        - [5.2.3 Sprint 3](#523-sprint-3)
            - [5.2.3.1 Sprint Planning 3](#5231-sprint-planning-3)
            - [5.2.3.2 Sprint Backlog 3](#5232-sprint-backlog-3)
            - [5.2.3.3 Development Evidence for Sprint Review](#5233-development-evidence-for-sprint-review)
            - [5.2.3.4 Testing Suite Evidence for Sprint Review](#5234-testing-suite-evidence-for-sprint-review)
            - [5.2.3.5 Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
            - [5.2.3.6 Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
            - [5.2.3.7 Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
            - [5.2.3.8 Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    - [5.3 Validation Interviews](#53-validation-interviews)
        - [5.3.1 Diseño de Entrevistas](#531-diseño-entrevistas)
        - [5.3.2 Registro de Entrevistas](#532-registro-entrevistas)
        - [5.3.3 Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
    - [5.4 Video About-the-Product](#54-video-about-the-product)


---


# Capítulo I: Introducción
## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

### 1.1.2 Perfiles de integrantes del equipo

---

## 1.2 Solution Profile


### 1.2.1 Antecedentes y problemática


### 1.2.2 Lean UX Process


#### 1.2.2.1 Lean UX Problem Statements


#### 1.2.2.2 Lean UX Assumptions


#### 1.2.2.3 Lean UX Hypothesis Statements


#### 1.2.2.4 Lean UX Canvas


---

## 1.3 Segmentos objetivo

---
# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores


### 2.1.1 Análisis competitivo


### 2.1.2 Estrategias y tácticas frente a competidores


## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas


## 2.3 Needfinding
### 2.3.1 User Personas
[Poner información aquí]

### 2.3.2 User Task Matrix
[Poner información aquí]

### 2.3.3 User Journey Mapping
[Poner información aquí]

### 2.3.4 Empathy Mapping
[Poner información aquí]

### 2.3.5 As-is Scenario Mapping
[Poner información aquí]

---

## 2.4 Ubiquitous Language
[Poner información aquí]

---

# Capítulo III: Requirements Specification
## 3.1 To-Be Scenario Mapping

## 3.2 User Stories


### Technical Stories

## 3.3 Impact Mapping
[Poner información aquí]

## 3.4 Product Backlog
[Poner información aquí]

---
# Capítulo IV: Product Design
## 4.1 Style Guidelines

- ### 4.1.1 General Style Guidelines

- ### 4.1.2 Web Style Guidelines

## 4.2 Information Architecture
- ### 4.2.1 Organization Systems
 [Poner información aquí]
 
- ### 4.2.2 Labeling Systems
  [Poner información aquí]
  
- ### 4.2.3 SEO Tags and Meta Tags
  [Poner información aquí]
  
- ### 4.2.4 Searching Systems
  [Poner información aquí]
  
- ### 4.2.5 Navigation Systems
  [Poner información aquí]

## 4.3 Landing Page UI Design
- ### 4.3.1 Landing Page Wireframe
  [Poner información aquí]
  
- ### 4.3.2 Landing Page Mock-up
  [Poner información aquí]

## 4.4 Web Applications UX/UI Design
- ### 4.4.1 Web Applications Wireframes
  [Poner información aquí]
  
- ### 4.4.2 Web Applications Wireflow Diagrams
  [Poner información aquí]
  
- ### 4.4.3 Web Applications Mock-ups
  [Poner información aquí]
  
- ### 4.4.4 Web Applications User Flow Diagrams
  [Poner información aquí]

## 4.5 Web Applications Prototyping

[Poner información aquí]

## 4.6 Domain-Driven Software Architecture
Para el modelo de negocio que utilizaremos para desarrollar nuestro software complejo que se centra en la problematica que abordamos. para ello utilizaremos la tecnica de modelado C4 Model.

#### 4.6.1. Software Architecture Context Diagram
Este es el diagrama de Contexto de nuestro sistema:
<a href="https://ibb.co/6sR9D3q"><img src="https://i.ibb.co/9Y9KyFd/Diagrama-de-contexto.png" alt="Diagrama-de-contexto" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

#### 4.6.2. Software Architecture Container Diagram
Este es el diagrama de Contenedores de nuestro sistema:
<a href="https://ibb.co/WGG7WvQ"><img src="https://i.ibb.co/rFFqG2g/Diagrama-de-Contenedores.png" alt="Diagrama-de-Contenedores" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

### 4.6.3 Software Architecture Components Diagrams
Esto son los diagramas de componentes de nuestro sistema:
##### Diagrama de componentes #1:
<a href="https://ibb.co/fY8VnbZ"><img src="https://i.ibb.co/RphGB1t/Diagrama-de-Componentes-1.png" alt="Diagrama-de-Componentes-1" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

##### Diagrama de componentes #2:
<a href="https://ibb.co/16Fq7d3"><img src="https://i.ibb.co/FVRwm09/Diagrama-de-Componentes-2.png" alt="Diagrama-de-Componentes-2" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

##### Diagrama de componentes #3:
<a href="https://ibb.co/ZK3KrfR"><img src="https://i.ibb.co/J2N2TcW/Diagrama-de-Componentes-3.png" alt="Diagrama-de-Componentes-3" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

##### Diagrama de componentes #4:
<a href="https://ibb.co/0qRCjGF"><img src="https://i.ibb.co/cJS6crC/Diagrama-de-Componentes-4.png" alt="Diagrama-de-Componentes-4" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

## 4.7 Software Object-Oriented Design
### 4.7.1 Class Diagrams

Para nuestro sistema, hemos implementado un diagrama de clases. Este diagrama visualiza la estructura estática del software, mostrando las clases, sus atributos y las relaciones entre ellas. Es una herramienta esencial que nos ayuda a comprender cómo se organizan y comunican las diferentes partes de nuestro sistema de software.

Diagramas de clases por módulo:

- User Interface:

<a href="https://ibb.co/dBRPs3p"><img src="https://i.ibb.co/SNztD1m/Register-user.png" alt="Register-user" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

- Subscription:

<a href="https://ibb.co/7SFX1G9"><img src="https://i.ibb.co/3TH7C0J/Subscription.png" alt="Subscription" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

- FAQ:

<a href="https://ibb.co/swKY5Km"><img src="https://i.ibb.co/0MCbBCD/FAQ.png" alt="FAQ" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

- Track Route:

<a href="https://ibb.co/VWL1F4z"><img src="https://i.ibb.co/ccyBWnZ/TRACK-ROUTE.png" alt="TRACK-ROUTE" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

### 4.7.2 Class Dictionary
Explicacion del funcionamiento de cada funcion por módulo.
Módulos:

- User Interface:
Para explicar nuestro sistema de usuario este tendra que registrarse para luego iniciar sesion en su cuenta, donde este recibira un correo para confirmar su creacion, todo esto en una clase llamada UserInterface que recibira toda la información.

<a href="https://ibb.co/GTyXMmL"><img src="https://i.ibb.co/C2gq9LZ/1.png" alt="1" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>

- Subscription:
Este modulo de clases es referido a la eleccion que tenga el usuario sobre la subscripcion que desea poseer.
<a href="https://imgbb.com/"><img src="https://i.ibb.co/gDHP4gp/Captura-de-pantalla-2024-04-12-012158.png" alt="Captura-de-pantalla-2024-04-12-012158" border="0"></a>

- FAQ:
Esta esta dirigido a una parte mas de dudas que tenga el usuario sobre el uso o funcionamiento de la aplicación.
<a href="https://imgbb.com/"><img src="https://i.ibb.co/41KRfZJ/Captura-de-pantalla-2024-04-12-012114.png" alt="Captura-de-pantalla-2024-04-12-012114" border="0"></a>

- Track Route:
Esta es el modulo que explica el funcionamiento principal de la aplicacion, nos mostrara la ruta de los buses y como de acuerdo a las preferencias del usuario puede variar, ademas de una funcionalidad para pagar el servicio del bus que este desee tomar.

<a href="https://ibb.co/VWL1F4z"><img src="https://i.ibb.co/ccyBWnZ/TRACK-ROUTE.png" alt="TRACK-ROUTE" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>
## 4.8 Database Design
### 4.8.1 Database Diagram

Para explicar el sistema de nuestra aplicacion comenzemos por las entidades como buses company y customers cada una de ellas se refiere a los usuarios tanto de buses como el cliente que se transporta(Este de acuerdo a la subscripcion que posea tiene distintos beneficios)

(IMAGEN ESPACIO)


Tenemos una entidad llamada tracMyRouteBuses esta se refiere a la data que va recibir sobre las rutas que van a tomar los distintos servicios de buses.
(IMAGEN ESPACIO)

Estas pueden ser personalizadas por el usuario
<a href="https://imgbb.com/"><img src="https://i.ibb.co/RbR8SC8/Captura-de-pantalla-2024-04-12-011834.png" alt="Captura-de-pantalla-2024-04-12-011834" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>
Para que este verifique si es valido la ruta que ah sido escogida y el status es un dato uqe se mandara a la entidad "Status_TrackRouteBuses"
<a href="https://imgbb.com/"><img src="https://i.ibb.co/H2ttRPK/Captura-de-pantalla-2024-04-12-011940.png" alt="Captura-de-pantalla-2024-04-12-011940" border="0"></a><br /><a target='_blank' href='https://es.imgbb.com/'>
---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
- ### Software Development Environment Configuration
   **Project Management**

Para la organizacion del proyecto necesitabamos una planificación en cuanto a tareas asignadas, un punto de reunión y un repositorio donde trabajaramos en conjunto cada avance del proyecto, es por esto que elegimos las siguientes herramientas:

* Centro de organización de trabajo: Github
    
* Planificación de tareas: Trello
    
* Reuniones con el equipo: Google Meet
    
**Requirements Management**

Para realizar las actividades del proyecto necesitábamos designarlas a cada integrante del grupo en caso de revisión o cambios, esta lista de asignaciones fue realizada en Trello:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.trello.com/</td>
        </tr>
    </tbody>
</table>

**Product UX/UI Design**

Para el diseño de los wireframe y mockups, además de un prototipo de Web App se utilizó Figma:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.figma.com/</td>
        </tr>
    </tbody>
</table>

**Software Development**

La herramienta para la implementación del proyecto es WebStorm de Jetbrains:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.jetbrains.com/es-es/webstorm/</td>
        </tr>
    </tbody>
</table>
La herramienta para la implementación del proyecto es Rider de Jetbrains:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://www.jetbrains.com/es-es/rider/</td>
        </tr>
    </tbody>
</table>
**Software Testing**

Gherkin es un sistema de etiquetado utilizado para detallar como se comporta el software de manera legible.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://cucumber.io/docs/gherkin/</td>
        </tr>
    </tbody>
</table>

**Software Deployment**

Se ha utilizado Github para desplegar la landing page con Github Pages:

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://pages.github.com/</td>
        </tr>
    </tbody>
</table>
**Software Documentation**

Se ha utilizado Github para alojar los distintos repositorios creados por los miembros del equipo para la colaboración en tiempo real mientras se codifican distintas áreas del proyecto.

<table>
    <tbody>
        <tr>
            <td>Link de referencia: </td>
            <td>https://github.com/</td>
        </tr>
    </tbody>
</table>

- ### Source Code Management
   <table>
    <tbody>
        <tr>
            <td>Link Landing Page:</td>
            <td> https://github.com/G2-AplicacionesWeb-SI91/Landing </td>
        </tr>
        <tr>
            <td> Backend Services: </td>
            <td> https://github.com/G2-AplicacionesWeb-SI91/Backend </td>
        </tr>
        <tr>
            <td>Link Front Web Applications: </td>
            <td> https://github.com/G2-AplicacionesWeb-SI91/FrontEnd </td>
        </tr>
    </tbody>
</table>

**Flujo de trabajo GitFlow**

<img src="https://nvie.com/img/git-model@2x.png" width="60%" alt="Ejemplo flujo de Gitflow"/>

Usaremos el flujo de trabajo planteado por Vincent Driessen en "A successful Git branching model" con los siguientes parámetros:
 * Una rama de producción.
 * Una rama de pruebas.
 * Una rama en la que se solucionen los bugs rapidamente y vuelvan a producción.
 * Ramas de features a implementar.
 * Cada cambio en producción debe establecerse como una nueva versión.
 * Para este proyecto en concreto consideramos que los cambios en la rama de producción y de pruebas deben tener autorización de un compa­ñero de equipo.
   
Teniendo en cuenta la información anterior nos inclinamos por este tipo de organización en los branches:
* **Main branch:** Esta rama esta destinada a la producción de la aplicación, cada cambio deberá tener autorización de un compañero de equipo para evitar cambios sin verificar.
* **Hotfix branch:** En esta rama se incluirán todas las versiones que poseen errores identificados y que con cada arreglo de este se despliegue otra vez a Main Branch además de implementarla en lo que será Develop Branch.
* **Release branch:** Esta rama se utilizará para una previa a lo que será el Main Branch, aquí se seguirá de cerca a la aplicación en otros ambientes en busca de bugs.
* **Develop branch:** Esta rama está destinada a las constantes implementaciones en caliente de los features, 
* **Features branch:** Cada feature poseerá su respectiva rama, una vez que se encuentre correctamente implementada será fusionada con Develop branch.

Con cada deployment de la aplicación debe establecerse como una nueva versión.

- ### Source Code Style Guide & Conventions
   Usaremos buenas prácticas en cuanto al código de manera que sea coherente y sostenible.

  
- ### Software Deployment Configuration
   [Poner información aquí]
  
## 5.2 Landing Page, Services & Applications Implementation.
- ### 5.2.1 Sprint 1
- #### 5.2.1.1. Sprint Planning 1
   [Poner información aquí]
  
- #### 5.2.1.2. Sprint Backlog 1
   [Poner información aquí]
  
- #### 5.2.1.3. Development Evidence for Sprint Review
   [Poner información aquí]
   
- #### 5.2.1.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
   
- #### 5.2.1.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.1.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.1.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]

- #### 5.2.1.8. Team Collaboration Insights during Sprint
   [Poner información aquí]
  

- ### 5.2.2 Sprint 2
- #### 5.2.2.1. Sprint Planning 2
   [Poner información aquí]
  
- #### 5.2.2.2. Sprint Backlog 2
   [Poner información aquí]
  
- #### 5.2.2.3. Development Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.2.8. Team Collaboration Insights during Sprint
   [Poner información aquí]
  

- ### 5.2.3 Sprint 3
- #### 5.2.3.1. Sprint Planning 3
   [Poner información aquí]
  
- #### 5.2.3.2. Sprint Backlog 3
   [Poner información aquí]
  
- #### 5.2.3.3. Development Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.4. Testing Suite Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.5. Execution Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.6. Services Documentation Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.7. Software Deployment Evidence for Sprint Review
   [Poner información aquí]
  
- #### 5.2.3.8. Team Collaboration Insights during Sprint
   [Poner información aquí]

## 5.3 Validation Interviews
- ### 5.3.1. Diseño de Entrevistas
   [Poner información aquí]
  
- ### 5.3.2. Registro de Entrevistas
   [Poner información aquí]
  
- ### 5.3.3. Evaluaciones según heurísticas
   [Poner información aquí]
  

## 5.4 Video About-the-Product

   [Poner información aquí]
