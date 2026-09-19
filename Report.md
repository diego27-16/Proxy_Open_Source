# Carátula

![UPC](Recursos/images/upc.png)

**Universidad Peruana de Ciencias Aplicadas S.A.C.**

**Ingeniería de Software**

**Ciclo: 5**

**1ASI0729-2620**

**Desarrollo de Aplicaciones Open Source**

**NRC: 7760**

**Docente: Juan Antonio Flores Moroco**

---

### **Informe de Trabajo Final**

* **Nombre del Startup:** Proxy
* **Nombre del Producto:** BodeGo

---

### **Relación de Integrantes**

| Código | Apellidos y Nombres |
| :--- | :--- |
| U20241F385 | Blanco Medina, Jhorch Jhoseff |
| U20241G404 | Caldas Bravo, Mateo |
| U20241G610 | Chavez Sandoval, Dany Yohel |
| U202421082 | Saravia Hiso, Johan Alvaro |
| U202316162 | Trejo Espejo, Giordano Sebastian del Ángel |

---

* **Fecha:** 12/09/2026

---

# Registro de Versiones del Informe

* **Project Report Collaboration Insights**

---

# Contenido

## Tabla de Contenidos

* [Capítulo I: Introducción](#capítulo-i-introducción)

  * [1.1. Startup Profile](#11-startup-profile)

    * [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    * [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  * [1.2. Solution Profile](#12-solution-profile)

    * [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    * [1.2.2. Lean UX Process](#122-lean-ux-process)

      * [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      * [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      * [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      * [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  * [1.3. Segmentos objetivo](#13-segmentos-objetivo)

* [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)

  * [2.1. Competidores](#21-competidores)

    * [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    * [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  * [2.2. Entrevistas](#22-entrevistas)

    * [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    * [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    * [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  * [2.3. Needfinding](#23-needfinding)

    * [2.3.1. User Personas](#231-user-personas)
    * [2.3.2. User Task Matrix](#232-user-task-matrix)
    * [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    * [2.3.4. Empathy Mapping](#234-empathy-mapping)
  * [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
  * [2.5. Ubiquitous Language](#25-ubiquitous-language)

* [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)

  * [3.1. User Stories](#31-user-stories)
  * [3.2. Impact Mapping](#32-impact-mapping)
  * [3.3. Product Backlog](#33-product-backlog)

* [Capítulo IV: Product Design](#capítulo-iv-product-design)

  * [4.1. Style Guidelines](#41-style-guidelines)

    * [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    * [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  * [4.2. Information Architecture](#42-information-architecture)

    * [4.2.1. Organization Systems](#421-organization-systems)
    * [4.2.2. Labeling Systems](#422-labeling-systems)
    * [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    * [4.2.4. Searching Systems](#424-searching-systems)
    * [4.2.5. Navigation Systems](#425-navigation-systems)
  * [4.3. Landing Page UI Design](#43-landing-page-ui-design)

    * [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    * [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  * [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)

    * [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    * [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    * [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    * [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  * [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  * [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)

    * [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
    * [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    * [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    * [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  * [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)

    * [4.7.1. Class Diagrams](#471-class-diagrams)
  * [4.8. Database Design](#48-database-design)

    * [4.8.1. Database Diagrams](#481-database-diagrams)

* [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)

  * [5.1. Software Configuration Management](#51-software-configuration-management)

    * [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    * [5.1.2. Source Code Management](#512-source-code-management)
    * [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    * [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  * [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)

    * [5.2.1. Sprint n](#521-sprint-n)

      * [5.2.1.1. Sprint Planning n](#5211-sprint-planning-n)
      * [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      * [5.2.1.3. Sprint Backlog n](#5213-sprint-backlog-n)
      * [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      * [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      * [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      * [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      * [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
  * [5.3. Validation Interviews](#53-validation-interviews)

    * [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    * [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    * [5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)
  * [5.4. Video About-the-Product](#54-video-about-the-product)

* [Conclusiones](#conclusiones)

  * [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

* [Video About-the-Team](#video-about-the-team)

* [Bibliografía](#bibliografía)

* [Anexos](#anexos)


---

# Student Outcome

| **Criterio específico** | **Acciones realizadas** | **Conclusiones** |
| --- | --- | --- |
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Mateo Caldas Bravo** <br><br> AV1: Lideré la organización inicial del equipo mediante la coordinación de reuniones y distribución de actividades. Realicé aportes en la definición de la propuesta de valor de BodeGo, identificación del problema y revisión de los avances realizados durante esta primera etapa. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Realicé el análisis inicial del usuario objetivo y colaboré en la recopilación de información sobre las necesidades de los minimarkets. Aporté ideas que permitieron orientar la solución hacia una problemática real identificada. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Aporté conocimientos relacionados con la propuesta tecnológica del proyecto, analizando la estructura inicial de la plataforma y brindando ideas sobre los componentes necesarios para el desarrollo futuro de BodeGo. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Colaboré en la revisión de la propuesta inicial del proyecto, brindando observaciones y sugerencias para mejorar la definición de funcionalidades y características principales de la solución. <br><br> **Giordano Sebastian del Ángel Trejo Espejo** <br><br> AV1: Realicé la organización y revisión de la documentación inicial del proyecto, ayudando a mantener la información ordenada y alineada con los objetivos definidos por el equipo. | Durante la entrega AV1, logramos trabajar como un equipo organizado donde cada integrante asumió responsabilidades según sus habilidades. El liderazgo fue compartido mediante la comunicación constante, apoyo entre compañeros y participación conjunta en la toma de decisiones. <br><br> La colaboración permitió establecer una propuesta inicial sólida y definir las bases necesarias para continuar con el desarrollo del proyecto BodeGo. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Mateo Caldas Bravo** <br><br> AV1: Organicé reuniones de coordinación y participé en la planificación de actividades necesarias para cumplir con los objetivos de la primera entrega. Ayudé a establecer prioridades relacionadas con la definición del problema, propuesta de valor y estructura inicial del proyecto. <br><br> **Johan Alvaro Saravia Hiso** <br><br> AV1: Colaboré durante las reuniones del equipo aportando ideas obtenidas del análisis del usuario objetivo. Ayudé a organizar la información recopilada y definir los aspectos importantes que debían considerarse en la solución. <br><br> **Dany Yohel Chavez Sandoval** <br><br> AV1: Participé en la planificación de las actividades relacionadas con la propuesta tecnológica, aportando ideas sobre la estructura de la plataforma y los elementos necesarios para el desarrollo posterior del producto. <br><br> **Jhorch Jhoseff Blanco Medina** <br><br> AV1: Apoyé en la coordinación del trabajo grupal mediante la revisión de avances y planteamiento de mejoras. Colaboré con mis compañeros para mantener una organización adecuada de las tareas asignadas. <br><br> **Giordano Sebastian del Ángel Trejo Espejo** <br><br> AV1: Realicé seguimiento de los avances del equipo y colaboré en la revisión de documentos para asegurar que los entregables mantuvieran coherencia con los objetivos establecidos para esta etapa. | Durante la entrega AV1, establecimos un ambiente colaborativo donde cada integrante pudo expresar sus ideas y participar en la toma de decisiones. La planificación de actividades y comunicación constante permitió cumplir con los objetivos planteados para esta primera etapa del proyecto. <br><br> Como equipo logramos organizar nuestras responsabilidades y combinar nuestros conocimientos para desarrollar una propuesta alineada con las necesidades identificadas en BodeGo. |

---

# Capítulo I: Introducción
## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

**Nombre del Startup:** Proxy  

**Nombre del Producto:** BodeGo  

**Enfoque de Negocios:** Aplicación web para la gestión integral de inventario, mermas y control operativo interno en minimarkets.  

**Propuesta de Valor:** BodeGo es una solución web de gestión interna que optimiza el control de stock y reduce las mermas por productos perecibles mediante un sistema de doble rol operativo. La plataforma permite al Administrador visualizar reportes, configurar el sistema y lanzar ofertas estratégicas, mientras que facilita al Empleado la actualización rápida de stock y el registro de las operaciones diarias en el punto de venta.  

**Mercado Objetivo:** El producto está dirigido al personal operativo y directivo de minimarkets, dividiendo a sus usuarios en dos segmentos clave: Administradores (dueños o gestores del negocio) y Empleados (personal de atención y almacén).


### 1.1.2. Perfiles de integrantes del equipo
| **Mateo Caldas Bravo (U20241G404)** |
| :--- |
| Soy un estudiante de 19 años cursando el quinto ciclo de la carrera de Ingeniería de Software. Considero que mi capacidad de tener un enfoque analítico y la eficiencia de desarrollar una solución eficiente. Mis habilidades blandas me permiten empatizar con los usuarios y acompañado de mi resiliencia, compromiso y productividad me permiten realizar propuestas mas estructuradas y optimas. |
| ![Foto Mateo](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/mateofoto.jpg) |

| **Johan Alvaro Saravia Hiso (U202421082)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Johan](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/johanfoto.jpg) |

| **Chavez Sandoval, Dany Yohel (U20241G610)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Flujo Dany](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/danyfoto.jpg) |

| **Blanco Medina, Jhorch Jhoseff (U20241F385)** |
| :--- |
| Soy un estudiante de 20 años actualmente en el quinto ciclo de la carrera de Ingeniería de Software. Me considero una persona responsable y comprometida con los demás, especialmente al trabajar en equipo. Tengo facilidad para analizar problemas y buscar soluciones prácticas. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Jhorch](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/jhorch%20foto.jpg) |

| **Trejo Espejo, Giordano Sebastian del Ángel (U202316162)** |
| :--- |
| Soy un estudiante de 22 años actualmente en el sexto ciclo de la carrera de Ingeniería de Software. Me concidero una persona conciderada, responsable y que le gusta hacer las cosas bien, me gusta trabajar en equipo, se me facilita el poder resolver problemas y siento que voy a hacer un buen trabajo este ciclo. Además, procuro escuchar y comprender las ideas de mis compañeros para lograr un buen trabajo en conjunto. |
| ![Foto Diego](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/perfil-Diego.jpg) |

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática

En el sector del comercio minorista, específicamente en los minimarkets, la gestión operativa se realiza de manera empírica y manual. Esta falta de digitalización genera una baja visibilidad sobre el estado real de los inventarios, impactando directamente en la rentabilidad del negocio debido a la acumulación de mermas y a una deficiente comunicación interna entre el personal.

**Técnica de las 5 'W's y 2 'H's:**

**Who (¿Quién?):** Personal operativo y directivo de los minimarkets, dividido en dos roles clave: Administradores (dueños o gestores) y Empleados (personal de atención y almacén).  

**What (¿Qué?):** Deficiente gestión del inventario perecible que ocasiona mermas por productos vencidos, sumado a la falta de un sistema centralizado de control operativo y actualización de stock en tiempo real.  

**Where (¿Dónde?):** En las instalaciones, almacenes y puntos de venta de los minimarkets de Lima Metropolitana.  

**When (¿Cuándo?):** Ocurre de forma continua durante la operación diaria, intensificándose al momento de la recepción de mercadería, el despacho en caja y la rotación de productos en anaqueles.  

**Why (¿Por qué?):** Debido a la ausencia de herramientas digitales accesibles para el control de stock, la falta de asignación de permisos según el rol operativo y la dependencia de métodos manuales para identificar fechas de vencimiento y registrar operaciones.  

**How (¿Cómo?):** El Administrador gestiona el negocio sin visibilidad centralizada de reportes ni capacidad para lanzar ofertas estratégicas de liquidación. A su vez, el Empleado realiza el control de inventario mediante anotaciones físicas o de memoria, lo que dificulta detectar a tiempo los productos próximos a caducar e impide mantener el stock actualizado durante la jornada.  

**How Much (¿Cuánto?):** Pérdidas económicas constantes para el minimarket por mermas no detectadas a tiempo, descuadres de stock en el punto de venta y una reducción en el margen de ganancia al no poder liquidar estratégicamente la mercadería de baja rotación.

### 1.2.2 Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas. Esto ocasiona diferencias en el stock, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Los Administradores necesitan contar con información centralizada que les permita supervisar el inventario, consultar reportes y tomar decisiones frente a posibles mermas. Por otro lado, los Empleados necesitan una forma rápida y sencilla de actualizar el stock y registrar las operaciones realizadas durante la jornada.

BodeGo busca solucionar esta problemática mediante una plataforma web que centralice la gestión del inventario, permita controlar productos perecibles y diferencie las funcionalidades disponibles para Administradores y Empleados.

#### 1.2.2.2. Lean UX Assumptions

##### Business Assumptions

1. Existe una necesidad de mejorar la gestión de inventario en minimarkets que actualmente utilizan procesos manuales.
2. La reducción de mermas por productos vencidos puede generar un beneficio económico para el negocio.
3. Una plataforma web puede facilitar la gestión interna sin requerir herramientas especializadas.
4. La separación de funcionalidades entre Administradores y Empleados puede mejorar el control operativo.

##### User Assumptions

1. Los Administradores necesitan conocer rápidamente el estado general del inventario.
2. Los Administradores necesitan identificar productos próximos a vencer para tomar decisiones oportunas.
3. Los Empleados necesitan actualizar el stock de manera rápida y sencilla.
4. Los Empleados prefieren una interfaz simple para realizar sus tareas operativas.
5. Ambos usuarios necesitan acceder únicamente a las funcionalidades relacionadas con su rol.

##### Business Outcome Assumptions

1. Reducción de productos que vencen sin ser detectados previamente.
2. Mayor frecuencia de actualización del stock.
3. Disminución del uso de registros manuales para controlar el inventario.
4. Mayor visibilidad del estado del inventario para los Administradores.

##### User Outcome and Benefit Assumptions

1. Los Administradores podrán tener mayor control sobre el inventario y las mermas.
2. Los Administradores podrán tomar decisiones utilizando información organizada y actualizada.
3. Los Empleados podrán registrar cambios en el inventario con mayor facilidad.
4. Los Empleados podrán identificar rápidamente productos que requieren atención.
5. Ambos usuarios reducirán su dependencia de registros manuales.

##### Feature Assumptions

1. Un sistema de gestión de inventario permitirá mantener actualizado el stock de productos.
2. Las alertas de vencimiento permitirán identificar productos perecibles antes de que se conviertan en mermas.
3. Un dashboard con reportes permitirá al Administrador conocer rápidamente el estado del inventario.
4. La gestión de ofertas permitirá al Administrador impulsar la salida de productos próximos a vencer.
5. Un sistema de roles permitirá diferenciar las acciones disponibles para Administradores y Empleados.

#### 1.2.2.3. Lean UX Hypothesis Statements

##### Hypothesis Statement 1

Creemos que si implementamos un sistema de gestión de inventario, entonces los Administradores y Empleados podrán mantener el stock actualizado con mayor facilidad, reduciendo las diferencias entre el inventario registrado y el inventario disponible.

##### Hypothesis Statement 2

Creemos que si implementamos alertas para productos próximos a vencer, entonces los Administradores y Empleados podrán identificarlos con anticipación y reducir la cantidad de productos que se convierten en mermas.

##### Hypothesis Statement 3

Creemos que si proporcionamos un dashboard con reportes del inventario, entonces los Administradores podrán conocer rápidamente el estado del negocio y tomar decisiones utilizando información organizada.

##### Hypothesis Statement 4

Creemos que si implementamos una funcionalidad para crear ofertas sobre productos próximos a vencer, entonces los Administradores podrán promover su salida antes de que estos productos se conviertan en pérdidas.

##### Hypothesis Statement 5

Creemos que si implementamos un sistema de roles para Administradores y Empleados, entonces cada usuario podrá acceder únicamente a las funcionalidades correspondientes a sus responsabilidades, mejorando el control de las operaciones.

#### 1.2.2.4. Lean UX Canvas

<table>
<tr>
<td width="33%" valign="top">

### Business Problem

Actualmente, los minimarkets presentan dificultades para mantener un control adecuado de su inventario debido al uso de registros manuales o herramientas poco especializadas.

Esto genera diferencias entre el stock registrado y el stock real, poca visibilidad sobre los productos disponibles y dificultades para identificar productos próximos a vencer.

Como consecuencia, los Administradores tienen dificultades para supervisar el negocio y tomar decisiones oportunas, mientras que los Empleados presentan complicaciones para mantener actualizado el inventario durante las operaciones diarias.

---

### Users

- **Administradores:** dueños o gestores del minimarket encargados de supervisar el inventario, revisar reportes, configurar el sistema y tomar decisiones sobre productos y ofertas.

- **Empleados:** personal de atención y almacén encargado de actualizar el stock, registrar operaciones y controlar los productos durante la jornada.

</td>

<td width="34%" valign="top">

### Solutions

- **Gestión centralizada de inventario**, permitiendo registrar, consultar y actualizar la información de los productos.

- **Control de productos perecibles**, facilitando la identificación de productos próximos a vencer.

- **Alertas de vencimiento** que permitan actuar antes de que los productos se conviertan en mermas.

- **Dashboard y reportes** para que el Administrador pueda visualizar información relevante sobre el inventario.

- **Gestión de ofertas** para productos próximos a vencer o con poca rotación.

- **Sistema de roles y permisos**, diferenciando las funcionalidades disponibles para Administradores y Empleados.

</td>

<td width="33%" valign="top">

### Business Outcomes

- Reducir la cantidad de productos que vencen sin ser identificados previamente.

- Incrementar la frecuencia de actualización del inventario.

- Disminuir la dependencia de registros manuales.

- Mejorar la visibilidad del estado del inventario.

- Facilitar la toma de decisiones relacionadas con stock, mermas y productos próximos a vencer.

---

### User Outcomes & Benefits

- **Administradores:** mayor control y visibilidad del inventario, acceso a información organizada y mejor capacidad para tomar decisiones.

- **Empleados:** mayor facilidad para actualizar el stock, identificar productos que requieren atención y registrar operaciones.

- Reducción del esfuerzo requerido para realizar tareas relacionadas con el control del inventario.

- Mayor claridad sobre las funciones correspondientes a cada usuario.

</td>
</tr>
</table>

<br>

<table>
<tr>
<td width="34%" valign="top">

### Hypothesis

Creemos que si BodeGo proporciona una plataforma web que centralice el control del inventario, permita identificar productos próximos a vencer y diferencie las funciones de Administradores y Empleados, entonces será posible mejorar la gestión operativa del minimarket y reducir las pérdidas relacionadas con productos perecibles.

Consideraremos que esta propuesta genera resultados positivos cuando los usuarios logren mantener el stock actualizado con mayor frecuencia, identificar productos próximos a vencer antes de que se conviertan en mermas y reducir su dependencia de registros manuales.

</td>

<td width="33%" valign="top">

### What's the most important thing we need to learn first?

- ¿Los problemas relacionados con el control del stock ocurren con suficiente frecuencia en los minimarkets?

- ¿La pérdida de productos por vencimiento representa una preocupación importante para los Administradores?

- ¿Los Empleados estarían dispuestos a utilizar una plataforma web para registrar y actualizar el inventario?

- ¿Las alertas de vencimiento aportarían valor durante las operaciones diarias del minimarket?

</td>

<td width="33%" valign="top">

### What's the least amount of work we need to do to learn the next most important thing?

- Realizar entrevistas a Administradores y Empleados de minimarkets para conocer sus procesos actuales.

- Desarrollar un prototipo de baja fidelidad con las principales funciones de BodeGo.

- Realizar pruebas de usuario enfocadas en tareas como actualizar stock, buscar productos e identificar productos próximos a vencer.

- Recopilar comentarios de los usuarios para validar o modificar los supuestos planteados.

</td>
</tr>
</table>

## 1.3. Segmentos objetivo

BodeGo está dirigido al personal involucrado en la gestión y operación de minimarkets de Lima Metropolitana. Para el desarrollo de la solución se consideran dos segmentos principales: los **Administradores**, responsables de supervisar y gestionar el negocio, y los **Empleados**, encargados de las actividades operativas relacionadas con el inventario, almacén y atención.

### Segmento: Administradores de minimarkets

Este segmento está conformado por dueños, administradores o encargados de minimarkets que necesitan mantener control sobre el inventario, las mermas y las operaciones realizadas dentro del establecimiento.

- **Aspectos Demográficos:**
  - Edad: 31 a 60 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Dueños, administradores o gestores de minimarkets.
  - Nivel tecnológico: Medio, con uso frecuente de smartphones, computadoras y aplicaciones de gestión o comunicación.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Distritos urbanos con presencia de minimarkets y comercios minoristas.
  - Acceso: Usuarios con conexión a internet y acceso a dispositivos móviles o computadoras.

- **Aspectos Psicográficos:**
  - Interés por mejorar la organización y rentabilidad de su negocio.
  - Buscan reducir pérdidas ocasionadas por productos vencidos o de baja rotación.
  - Valoran tener mayor control sobre el inventario y las actividades de sus empleados.
  - Interés en herramientas que faciliten la toma de decisiones.
  - Preferencia por soluciones sencillas que no compliquen las operaciones del negocio.

### Segmento: Empleados de minimarkets

Este segmento está compuesto por trabajadores encargados de realizar actividades operativas dentro del minimarket, como la recepción de mercadería, reposición de productos, atención al cliente y actualización del inventario.

- **Aspectos Demográficos:**
  - Edad: 18 a 45 años.
  - Nivel educativo: Secundaria completa, formación técnica o universitaria.
  - Ocupación: Personal de atención, caja, almacén o reposición.
  - Nivel tecnológico: Medio, familiarizados principalmente con smartphones y aplicaciones de uso cotidiano.

- **Aspectos Geográficos:**
  - Ubicación: Lima Metropolitana.
  - Zona geográfica: Minimarkets ubicados principalmente en zonas urbanas y comerciales.
  - Acceso: Personal con acceso a internet y dispositivos disponibles dentro del establecimiento.

- **Aspectos Psicográficos:**
  - Buscan realizar sus actividades de manera rápida y sencilla.
  - Valoran herramientas que reduzcan el trabajo manual y repetitivo.
  - Prefieren interfaces intuitivas y fáciles de aprender.
  - Necesitan acceder rápidamente a información sobre stock y productos.
  - Valoran tener claridad sobre las tareas y responsabilidades asignadas.

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso de mercadería puede actualizar automáticamente el stock, por lo que compite con BodeGo en el control y seguimiento del inventario. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer, por lo que es uno de los competidores más cercanos a la propuesta de BodeGo. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. Se diferencia por tener un enfoque más amplio y empresarial que BodeGo. |
### 2.1.1. Análisis competitivo
| Competidor | Descripción |
|---|---|
| **Bsale** | Es una plataforma de gestión comercial orientada a pequeñas y medianas empresas. Integra punto de venta, facturación electrónica, control de inventario en tiempo real y reportes. Cada venta o ingreso puede actualizar automáticamente el stock. |
| **FácilVenta** | Es un software peruano dirigido a negocios como bodegas, minimarkets y tiendas. Integra punto de venta, facturación electrónica SUNAT y gestión de inventario. Para minimarkets incluye funciones como lector de códigos de barras, control de stock mínimo y alertas de productos próximos a vencer. |
| **Adiasoft** | Es un sistema ERP que cuenta con una solución específica para minimarkets, bodegas y retail. Ofrece punto de venta, inventario en tiempo real, códigos de barras, promociones, facturación electrónica, reportes y gestión de múltiples áreas del negocio. |
### 2.1.1. Análisis competitivo

| Categoría | Aspecto | **BodeGo** | **Bsale** | **FácilVenta** | **Adiasoft** |
|---|---|---|---|---|---|
| **Perfil** | **Overview** | BodeGo es una aplicación web pensada para ayudar a minimarkets a llevar un mejor control de su inventario. Busca facilitar tareas como registrar productos, controlar lotes, revisar vencimientos, registrar mermas. Además, diferencia las funciones que puede realizar un Administrador y un Empleado. | Bsale es una plataforma que reúne diferentes herramientas para manejar un negocio, como ventas, inventario, facturación electrónica y reportes. Permite que los movimientos realizados en el sistema actualicen el stock del negocio. | FácilVenta es un sistema peruano orientado a pequeños negocios como bodegas y minimarkets. Permite manejar ventas, inventario, facturación electrónica y productos próximos a vencer. | Adiasoft es un sistema de gestión empresarial que cuenta con soluciones para minimarkets y comercios. Permite manejar ventas, inventario, facturación, promociones y otras áreas del negocio. |
| **Perfil** | **Ventaja competitiva ¿Qué valor ofrece a los clientes?** | La principal propuesta de BodeGo es enfocarse en problemas comunes de los minimarkets, como diferencias de stock y productos que vencen sin ser detectados. Busca que el usuario pueda controlar lotes, recibir alertas y tomar acciones antes de que los productos se conviertan en pérdidas. | Su principal ventaja es que reúne varias funciones del negocio en una sola plataforma, permitiendo controlar ventas, inventario y facturación desde un mismo lugar. | Su ventaja es que está bastante orientado a bodegas y minimarkets peruanos. Incluye funciones útiles como control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Su ventaja es la cantidad de funciones que ofrece. Puede ser utilizado por negocios que necesitan controlar no solo inventario y ventas, sino también otras áreas de la empresa. |
| **Perfil de Marketing** | **Mercado objetivo** | Dueños, administradores y empleados de minimarkets, especialmente pequeños y medianos negocios que necesitan mejorar el control de sus productos. Inicialmente se busca trabajar con minimarkets de Lima Metropolitana. | Pequeñas y medianas empresas que necesitan controlar ventas, inventario y facturación. | Bodegas, minimarkets, tiendas y pequeños o medianos comercios del Perú. | Minimarkets, tiendas, comercios retail y empresas que necesitan una herramienta de gestión más completa. |
| **Perfil de Marketing** | **Estrategias de marketing** | BodeGo podría promocionarse mediante redes sociales, una landing page, demostraciones del sistema y pruebas con minimarkets. La comunicación estaría enfocada principalmente en mostrar cómo el sistema puede ayudar a reducir pérdidas y facilitar el trabajo diario. | Promociona sus diferentes soluciones mediante su página web, demostraciones, contenido informativo y períodos de prueba para que los negocios conozcan la plataforma. | Utiliza su página web, demostraciones del sistema y contacto directo con los clientes. También destaca que su producto está pensado para negocios peruanos y cumple con requerimientos de SUNAT. | Promociona diferentes versiones de su sistema según el tamaño y tipo de negocio. También ofrece demostraciones y contacto con asesores para explicar las funcionalidades de la plataforma. |
| **Perfil de Producto** | **Productos & Servicios** | Control de productos, categorías, stock, lotes, fechas de vencimiento, mermas, alertas, ofertas, reportes, movimientos de inventario y gestión de usuarios según su rol. | Punto de venta, inventario, facturación electrónica, reportes, códigos de barras, clientes, caja y herramientas para ventas online. | Punto de venta, inventario, facturación electrónica SUNAT, códigos de barras, control de vencimientos, stock mínimo, compras, proveedores y reportes. | Punto de venta, inventario, códigos de barras, lotes, vencimientos, promociones, facturación electrónica, reportes y otros módulos empresariales. |
| **Perfil de Producto** | **Precios & Costos** | Se propone comenzar con un precio aproximado de **S/80 al mes** para un minimarket. La idea sería mantener un precio accesible mientras BodeGo se encuentra en crecimiento. | Sus planes se encuentran aproximadamente desde **S/189 mensuales**, aumentando según las herramientas y características que necesite el negocio. | Cuenta con planes aproximadamente desde **S/140 mensuales**, con opciones de mayor precio que incluyen más características y capacidad. | Cuenta con diferentes planes según las necesidades del negocio, desde opciones básicas hasta planes más completos que pueden superar los **S/300 mensuales**. |
| **Perfil de Producto** | **Canales de distribución (Web y/o Móvil)** | BodeGo funcionará principalmente como una aplicación web responsiva, por lo que podrá utilizarse desde una computadora, tablet o celular mediante un navegador. | Se puede utilizar desde la web y también cuenta con opciones para dispositivos móviles. | Puede ser utilizado desde computadoras y diferentes dispositivos para realizar operaciones del negocio. | Su plataforma puede utilizarse mediante internet desde diferentes dispositivos dependiendo del servicio contratado. |
| **Análisis SWOT** | **Fortalezas** | Está pensado específicamente para los problemas de inventario de los minimarkets. Se enfoca en productos perecibles, vencimientos y mermas. También busca tener una interfaz sencilla y separar claramente las funciones del Administrador y del Empleado. | Es una plataforma conocida y con varias herramientas integradas. Cuenta con inventario, ventas, facturación electrónica y funciones móviles. | Está enfocado directamente en bodegas y minimarkets. Cuenta con control de vencimientos, códigos de barras, stock mínimo y facturación electrónica. | Cuenta con una gran variedad de funciones y puede cubrir diferentes áreas de un negocio desde una sola plataforma. |
| **Análisis SWOT** | **Debilidades** | BodeGo todavía está en desarrollo y no tiene reconocimiento en el mercado. Además, actualmente no busca cubrir funciones como facturación electrónica o un sistema completo de punto de venta. | Al contar con muchas funciones, puede ser más de lo necesario para un minimarket pequeño que solamente busca mejorar su inventario. Además, el costo puede ser elevado para algunos negocios pequeños. | Algunas funciones y capacidades dependen del plan contratado, por lo que un negocio puede necesitar pagar un plan mayor conforme crece. | Al ser un sistema más completo, puede resultar más complejo para un pequeño minimarket que solamente necesita controlar su inventario y operaciones básicas. |
| **Análisis SWOT** | **Oportunidades** | Muchos minimarkets todavía trabajan con cuadernos, Excel o registros poco organizados. Existe la oportunidad de ofrecer una herramienta sencilla y económica que ayude a reducir productos vencidos y errores de stock. | Puede continuar creciendo mediante nuevas integraciones, comercio electrónico y herramientas para empresas que venden por diferentes canales. | Puede seguir captando pequeños negocios que desean pasar de procesos manuales a una solución digital con facturación electrónica. | Puede crecer entre negocios que necesitan manejar varias sucursales o centralizar diferentes áreas dentro de un mismo sistema. |
| **Análisis SWOT** | **Amenazas** | Existen competidores que ya cuentan con experiencia, clientes y funciones similares. Además, algunos minimarkets podrían preferir soluciones que también incluyan facturación electrónica y punto de venta. | Existen soluciones más económicas y especializadas que pueden resultar más atractivas para pequeños negocios. | Tiene que competir con plataformas más conocidas y con otras soluciones locales que pueden ofrecer precios similares. | Los minimarkets pequeños pueden preferir soluciones más sencillas y económicas en lugar de utilizar un ERP con una gran cantidad de módulos. |

### 2.1.2. Estrategias y tácticas frente a competidores
BodeGo busca diferenciarse de Bsale, FácilVenta y Adiasoft siendo una opción más simple y pensada especialmente para minimarkets. La idea es que ayude a llevar un mejor control del stock, detectar productos que están por vencer y evitar pérdidas por mermas.
También se plantea que tenga un precio accesible, alrededor de **S/80 al mes**, y que pueda usarse desde computadora o celular. Además, cada usuario tendría funciones según su rol, para que el sistema sea más fácil de entender y usar.
Como parte de la estrategia, se realizarían pruebas con minimarkets para mostrar de forma clara cómo BodeGo puede ayudar a ahorrar tiempo, reducir errores y tener un mejor control de los productos.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

### Preguntas para el Segmento 1: Administrador (Dueño / Gestor del Minimarket)

1. ¿Cómo realiza actualmente el control del stock de productos en su minimarket?
2. ¿Qué dificultades tiene para conocer la cantidad real de productos disponibles?
3. ¿Cómo identifica actualmente los productos que están próximos a vencer?
4. ¿Con qué frecuencia tiene pérdidas por productos vencidos o que no se venden a tiempo?
5. ¿Cómo se informa sobre los cambios de stock realizados por sus empleados?
6. ¿Qué información considera importante para controlar mejor el inventario de su negocio?
7. ¿Qué acciones realiza cuando detecta productos próximos a vencer o con poca rotación?
8. ¿Cómo decide cuándo aplicar descuentos o promociones a determinados productos?
9. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock real?
10. ¿Qué funciones le gustaría encontrar en un sistema digital para gestionar su inventario?

### Preguntas para el Segmento 2: Empleado (Personal Operativo / Atención y Almacén)

1. ¿Cómo registra actualmente las entradas y salidas de productos durante su jornada?
2. ¿Qué tan fácil le resulta conocer la cantidad disponible de un producto? 
3. ¿Cómo revisa o identifica los productos que están próximos a vencer?
4. ¿Qué hace cuando encuentra un producto vencido o cercano a su fecha de vencimiento? 
5. ¿En qué momentos del día suelen presentarse más errores en el control del inventario?
6. ¿Cómo comunica al administrador los cambios de stock o problemas con los productos?
7. ¿Qué dificultades tiene al momento de registrar la llegada de nueva mercadería?
8. ¿Con qué frecuencia encuentra diferencias entre el stock registrado y el stock disponible?
9. ¿Qué herramienta o función facilitaría el registro de productos durante su trabajo?
10. ¿Qué actividad relacionada con el inventario le parece más lenta o complicada de realizar?

### 2.2.2. Registro de entrevistas
### Segmento Administradores

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin3-Entrevista.png) |
| **Nombres y apellidos:** Lucia <br>**Edad:** 28  <br>**Distrito:** San Martin de Porrez  <br>**Resumen de la entrevista:** Lucía, de 28 años, trabaja como administradora de un minimarket en San Martín de Porres. Ella comenta que el control del inventario se realiza mediante un sistema POS, reportes en Excel y conteos físicos en las góndolas y el almacén. Sin embargo, existen diferencias frecuentes entre el stock registrado en el sistema y la cantidad real de productos, principalmente porque algunos productos dañados o retirados no siempre son registrados correctamente. <br><br>El control de los productos próximos a vencer se realiza de forma manual, revisando las fechas y aplicando el método FEFO, que consiste en colocar adelante los productos que vencen primero. A pesar de esto, suelen tener pequeñas pérdidas semanales por productos vencidos, especialmente yogures, embutidos y pan de molde. Para reducir estas pérdidas, Lucía coloca los productos próximos a vencer en zonas más visibles y aplica descuentos cuando faltan pocos días para su vencimiento. <br><br>Además, la comunicación sobre incidencias del inventario se realiza mediante el sistema, guías de remisión y un grupo de WhatsApp. Lucía considera que sería muy útil contar con una aplicación móvil que permita escanear códigos de barras, revisar el stock, las fechas de vencimiento y los pedidos en camino, además de recibir alertas cuando un producto esté por agotarse o próximo a vencer. <br><br>**URL:** https://drive.google.com/file/d/1-8vfUZq2TVlsaK8B5TCyhvH-dXwfndUl/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin1-Entrevista.png) |
| **Nombres y apellidos:** Jimmy Ruiz <br>**Edad:** 31 <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen de la entrevista:**  <br>Jimmy, administrador de un pequeño minimarket, comenta que actualmente controla el inventario de forma mixta: registra diariamente los movimientos en un cuaderno y, al finalizar la semana, pasa la información a una plantilla de Excel. Sin embargo, uno de los principales problemas es que durante las horas de mayor venta no siempre se registran correctamente todos los productos, lo que genera diferencias entre el stock registrado y el stock real. <br><br>El control de los productos próximos a vencer se realiza de manera manual. Los trabajadores revisan los estantes y el almacén mientras reponen o limpian los productos. A pesar de estas revisiones, se presentan pérdidas una o dos veces al mes, principalmente en productos como lácteos y panes que pueden quedar poco visibles al fondo de los estantes. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, lo colocan cerca de la caja o en zonas más visibles para facilitar su venta. También aplican descuentos o promociones para intentar recuperar la inversión antes de que el producto venza. <br><br>Jimmy menciona que las diferencias de stock ocurren casi todas las semanas, especialmente en golosinas, galletas, cereales y gaseosas, debido a errores de registro o consumo del personal. <br><br>Finalmente, considera importante contar con un sistema digital, principalmente desde el celular, que permita recibir alertas automáticas de bajo stock y vencimientos, generar reportes de los productos más vendidos y conectarse con un lector de códigos de barras para registrar fácilmente productos, pérdidas o roturas. <br><br>**URL:** https://drive.google.com/file/d/1eAsgHwrdiH4P3uMjAwPBXgNagRQ5b_eY/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Admin2-Entrevista.png) |
| **Nombres y apellidos:** Silvia Bravo <br>**Edad:** 49  <br>**Distrito:** Independencia <br><br>**Resumen de la entrevista:**  <br>Silvia Bravo, de 49 años, participa en la administración de un minimarket y explica que el control del stock se realiza revisando y contando los productos disponibles. Una de las principales dificultades es que, en ocasiones, la cantidad real no coincide con la cantidad que deberían tener registrada, por lo que deben estar pendientes constantemente del inventario. <br><br>La identificación de productos próximos a vencer se realiza revisando manualmente las fechas de vencimiento. Las pérdidas por vencimiento ocurren con frecuencia, especialmente en productos como yogur, leche y panes, ya que tienen una duración más corta. Para mantenerse comunicados sobre los cambios en el inventario, utilizan principalmente WhatsApp y un registro donde anotan información importante, como las fechas de vencimiento y los productos que ingresan. <br><br>Cuando un producto está próximo a vencer o tiene poca rotación, realizan ofertas, por ejemplo, combinándolo con otro producto que sí tiene mayor salida y reduciendo el precio para facilitar su venta. Los descuentos se aplican principalmente cuando los productos están cerca de vencer. Finalmente, Silvia considera que sería útil contar con un sistema digital que envíe alertas sobre los productos próximos a vencer y que también brinde orientación sobre qué acciones tomar para evitar pérdidas. <br><br>**URL:** https://drive.google.com/file/d/1pg_DvKHgaqZ3YP34jLtGyl6jV7oni1yI/view?usp=drive_link |

### Segmento Empleados

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado3-Entrevista.png) |
| **Nombres y apellidos:** Joseph <br>**Edad:** 23 <br>**Distrito:** Puente Piedra <br><br>**Resumen:**  <br>Joseph trabaja en un minimarket realizando tareas de atención al cliente, registro de ventas, reposición de productos y control de almacén. Actualmente, las entradas y salidas de productos se registran manualmente en un cuaderno, lo que puede generar errores o confusiones, especialmente en las horas de mayor movimiento o cuando llega mercadería mientras se atiende a los clientes. <br><br>Para conocer el stock disponible, deben revisar y contar físicamente los productos en los estantes, lo cual puede resultar lento y complicado. La revisión de fechas de vencimiento también se realiza manualmente, generalmente cuando llega nueva mercadería. Si encuentran un producto vencido, lo retiran del estante y se lo comunican al administrador para evitar que llegue al cliente. <br><br>Joseph menciona que los errores en el inventario suelen ocurrir principalmente durante las horas de mayor venta, cuando hay más presión de trabajo. Los cambios de stock o problemas con los productos se comunican de forma verbal y mediante el cuaderno de registro. Además, considera que las tareas más tediosas son contar los productos y revisar uno por uno las fechas de vencimiento. <br><br>Finalmente, señala que sería útil contar con una herramienta digital sencilla que permita registrar entradas y salidas, consultar el stock disponible y facilitar el control del inventario, reduciendo así el tiempo y los errores del proceso manual. <br><br>**URL:** https://drive.google.com/file/d/1TD5vcQrjeOiQnoPlT7bziEpWkTBYGCBs/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado2-Entrevista.png) |
| **Nombres y apellidos:** Andres Marzano <br>**Edad:** 20  <br>**Distrito:** San Juan de Lurigancho <br><br>**Resumen:**  <br>Andrés Marzano, de 20 años, tiene experiencia trabajando en atención al cliente y almacén. Explica que las entradas de productos se registraban después de verificar que la mercadería recibida coincidiera con la información del documento de entrega, para luego ingresarla en el sistema. Las salidas, por su parte, se registraban mediante boletas electrónicas. <br><br>Uno de los principales problemas era conocer con precisión la cantidad disponible de productos, especialmente cuando se trataba de artículos pequeños, ya que podían cometerse errores al contarlos. Esta tarea se volvía más complicada cuando, al mismo tiempo, tenían que atender a los clientes. <br><br>Para controlar los productos próximos a vencer, colocaban adelante los que tenían menor tiempo de vida útil y dejaban al fondo los productos recién llegados. Además, revisaban las fechas de vencimiento en los turnos de día y noche. Cuando un producto estaba cerca de vencer, trataban de darle prioridad a su venta; si ya quedaban pocos días y no se lograba vender, se registraba como merma para calcular las pérdidas. <br><br>Finalmente, Andrés señala que los mayores errores en el control del inventario se presentaban principalmente durante las mañanas, cuando había mayor cantidad de clientes y debían dividir su atención entre las ventas y las tareas de inventario. <br><br>**URL:** https://drive.google.com/file/d/1BCO2lHzXeeZyN7DED3hQVZv_ULh0Zdx2/view?usp=drive_link |

| |
|---|
| ![Imagen de la entrevista](Recursos/images/Empleado1-Entrevista.png) |
| **Nombres y apellidos:** Pablo Moreno <br>**Edad:** 20  <br>**Distrito:** Callao <br><br>**Resumen:**  <br>Pablo Moreno, empleado de un minimarket, explica que las entradas y salidas de productos se registran principalmente de forma manual y, en algunos casos, mediante Excel. Este proceso no siempre se actualiza de inmediato, por lo que a veces existen diferencias entre el stock registrado y la cantidad real disponible, especialmente en productos de alta rotación o durante las horas de mayor atención. La revisión de productos próximos a vencer también se realiza manualmente, verificando las fechas directamente en los productos. Cuando un producto está vencido se retira de la venta, mientras que los productos próximos a vencer pueden colocarse en zonas más visibles o venderse con descuento. Pablo también menciona que los errores suelen ocurrir cuando hay muchos clientes o cuando llega bastante mercadería al mismo tiempo. Los problemas de stock se comunican personalmente o por WhatsApp, aunque la información puede perderse entre tantos mensajes. Finalmente, considera que sería útil contar con un sistema digital accesible desde el celular o computadora que permita registrar entradas y salidas, actualizar el stock rápidamente y recibir alertas sobre productos próximos a vencer. <br><br>**URL:** https://drive.google.com/file/d/1_V2W7VMWYRneIBc2ZAb0kEKlw-TLDnwO/view?usp=drive_link |



### 2.2.3. Análisis de entrevistas

## Análisis para el segmento de Administradores
A partir de las entrevistas realizadas a Lucía, Jimmy y Silvia, se pudo ver que los tres tienen problemas parecidos al momento de manejar el inventario de sus minimarkets.
Uno de los problemas que más se repite es la **diferencia entre el stock registrado y el stock real**, ya que el **100 % de los entrevistados** mencionó que en algún momento las cantidades no coinciden. Esto puede pasar por errores al registrar productos, pérdidas, productos dañados o movimientos que no se anotan correctamente.
También se encontró que el **100 % controla las fechas de vencimiento de forma manual**, revisando los productos directamente en los estantes o en el almacén. Esto hace que algunos productos puedan pasar desapercibidos y terminar venciendo, sobre todo los lácteos, yogures, leche y panes.
Por otro lado, los tres entrevistados comentaron que tienen pérdidas por productos vencidos. Para tratar de evitarlo, suelen hacer descuentos, promociones u ofertas. Además, el **66,7 % mencionó que coloca estos productos en lugares más visibles**, como cerca de la caja, para que se vendan más rápido.
En cuanto a las herramientas que utilizan, se puede ver que combinan métodos como Excel, sistemas POS, registros manuales y WhatsApp. Sin embargo, todavía sienten que la información no siempre está actualizada o reunida en un solo lugar.
Respecto a una posible solución, el **100 % considera útil recibir alertas de productos próximos a vencer**. Además, el **66,7 % mostró interés en funciones como alertas de bajo stock, uso desde el celular y registro de productos mediante códigos de barras**.

## Análisis para el segmento de Empleados
A partir de las entrevistas realizadas a Joseph, Andrés y Pablo, se pudo identificar que los tres tienen dificultades con tareas relacionadas con el inventario y el almacén del minimarket.
Uno de los principales problemas es el **registro y control del stock**. El **66,7 % de los entrevistados** mencionó que las entradas y salidas se registran principalmente de forma manual, utilizando cuadernos o Excel. Aunque Andrés trabajaba con un sistema digital, también señaló que podían existir errores al momento de contar los productos.
Otro aspecto que se repite es que los errores suelen aparecer cuando existe mayor carga de trabajo. El **100 % mencionó que los problemas de inventario aumentan durante las horas con mayor cantidad de clientes o cuando llega mercadería**.
La revisión de las **fechas de vencimiento también se realiza manualmente en el 100 % de los casos**. Los trabajadores revisan directamente cada producto y, cuando detectan uno próximo a vencer, tratan de darle mayor prioridad en la venta.
En cuanto a la comunicación, los problemas relacionados con el stock suelen informarse de forma verbal, mediante registros escritos o por WhatsApp. Sin embargo, este proceso puede generar confusiones.
Respecto a una posible solución, el **66,7 % mencionó directamente que sería útil contar con una herramienta digital de gestión**. Entre las funciones más importantes se encuentran el **registro de entradas y salidas, consulta rápida del stock y alertas de productos próximos a vencer**.

## 2.3. Needfinding
### 2.3.1. User Personas

---
Administrador

![User Persona Administrador](Recursos/images/UserPersona-Administrador.jpg)

---
Empleado

![User Persona Empleado](Recursos/images/UserPersona-Empleado.jpg)

### 2.3.2. User Task Matrix
---
 Administradores

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Revisar el estado general del inventario | Alta | Alta | El administrador necesita conocer el stock disponible y detectar diferencias entre el inventario registrado y el real. |
| Supervisar productos próximos a vencer | Alta | Alta | Los productos perecibles pueden generar pérdidas si no se identifican y gestionan antes de su vencimiento. |
| Revisar alertas de stock y vencimientos | Alta | Alta | Permite detectar rápidamente productos con stock crítico, bajo nivel de existencias o próximos a caducar. |
| Consultar reportes e indicadores | Media | Alta | Los reportes ayudan a conocer mermas, movimientos y comportamiento del inventario para tomar mejores decisiones. |
| Aplicar promociones u ofertas | Media | Alta | Las ofertas permiten liquidar productos próximos a vencer o con baja rotación antes de que se conviertan en merma. |
| Revisar las operaciones realizadas por empleados | Alta | Media | El administrador necesita mantener control sobre ingresos, salidas y mermas registradas durante la jornada. |
| Gestionar productos y datos del inventario | Media | Alta | Es necesario registrar, editar y mantener actualizada la información de los productos disponibles. |
| Gestionar empleados y permisos | Baja | Media | El administrador debe controlar qué empleados tienen acceso al sistema y las acciones que pueden realizar según su rol. |
| Configurar parámetros de stock y vencimiento | Baja | Media | Permite adaptar las alertas y reglas de inventario a las necesidades particulares del minimarket. |
| Identificar productos con mayor cantidad de mermas | Media | Alta | Conocer qué productos generan más pérdidas facilita tomar decisiones sobre compras, rotación y promociones. |
---
 Empleados

| Tareas identificadas | Frecuencia | Importancia | Evidencia / Justificación |
|---|---|---|---|
| Registrar el ingreso de mercadería | Alta | Alta | La recepción de productos ocurre regularmente y debe registrarse para mantener actualizado el inventario. |
| Registrar salidas de productos | Alta | Alta | Las salidas modifican constantemente las cantidades disponibles y deben reflejarse correctamente en el stock. |
| Consultar el stock disponible | Alta | Alta | El empleado necesita conocer rápidamente cuántas unidades quedan sin realizar revisiones manuales del almacén. |
| Registrar productos dañados, vencidos o perdidos como merma | Media | Alta | Registrar las mermas permite mantener el stock real y conocer las pérdidas generadas durante la operación. |
| Revisar productos próximos a vencer | Alta | Alta | Permite detectar productos perecibles antes de que caduquen y comunicar la situación al administrador. |
| Consultar información de un producto | Alta | Media | Durante la jornada puede necesitar verificar cantidades, categoría, estado o información relacionada con un producto. |
| Actualizar el stock después de una operación | Alta | Alta | Mantener las cantidades actualizadas evita diferencias entre el inventario físico y el registrado en el sistema. |
| Revisar sus operaciones realizadas durante el día | Media | Media | El historial permite verificar que los ingresos, salidas y mermas hayan sido registrados correctamente. |
| Comunicar incidencias de inventario | Media | Alta | El empleado debe informar situaciones como stock crítico, productos dañados o inconsistencias encontradas durante su jornada. |
| Buscar productos dentro del inventario | Alta | Media | Una búsqueda rápida reduce el tiempo necesario para localizar información entre una gran cantidad de productos. |

### 2.3.3. User Journey Mapping

## Administrador

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Supervisión inicial del negocio | Revisión del inventario | Detección de problemas | Toma de decisiones | Seguimiento de resultados |
| **User Goals** | Conocer el estado general del minimarket | Verificar stock y productos disponibles | Detectar stock crítico, mermas o vencimientos | Reducir pérdidas y mejorar la rotación | Comprobar si las acciones tomadas funcionaron |
| **Process** | Revisa ventas, stock y operaciones del día | Consulta cantidades y revisa productos | Identifica productos próximos a vencer o con poco stock | Aplica promociones, repone productos o toma acciones | Revisa reportes, movimientos y resultados |
| **Problems** | Información dispersa o poco actualizada | Diferencias entre stock registrado y real | Detección tardía de productos próximos a vencer | Falta de información para tomar decisiones rápidas | Dificultad para medir mermas y resultados |
| **Experience** | Expectativa | Atención | Preocupación | Decisión | Tranquilidad / Incertidumbre |
| **Ideas / Opportunities** | Dashboard con información resumida | Inventario actualizado y filtros | Alertas automáticas de stock y vencimiento | Recomendaciones y lanzamiento de ofertas | Reportes claros sobre inventario y mermas |

---

## Empleado

|  | Etapa 1 | Etapa 2 | Etapa 3 | Etapa 4 | Etapa 5 |
|---|---|---|---|---|---|
| **Title** | Inicio de la jornada | Recepción de mercadería | Actualización del inventario | Gestión de incidencias | Revisión de operaciones |
| **User Goals** | Conocer las tareas y estado del inventario | Registrar correctamente los productos recibidos | Mantener actualizado el stock durante el día | Registrar mermas y detectar productos próximos a vencer | Confirmar que sus operaciones fueron registradas correctamente |
| **Process** | Revisa productos, stock y pendientes | Recibe productos y verifica cantidades | Registra ingresos, salidas y consulta existencias | Informa o registra productos dañados, vencidos o faltantes | Consulta el historial de operaciones realizadas |
| **Problems** | Falta de información actualizada | Errores al registrar cantidades o lotes | Olvidar actualizar movimientos durante momentos de alta demanda | Dificultad para identificar vencimientos o comunicar incidencias | No saber si una operación fue registrada correctamente |
| **Experience** | Atención | Concentración | Presión | Preocupación | Alivio |
| **Ideas / Opportunities** | Dashboard simple con acciones rápidas | Registro sencillo de ingresos y lotes | Actualización rápida y automática del stock | Alertas y registro simplificado de mermas | Historial de operaciones fácil de consultar |

---

### 2.3.4. Empathy Mapping

## Administrador

![Empathy Map Administrador](Recursos/images/EmphathyMapping-Administrador.jpg)

## Empleado

![Empathy Map Empleado](Recursos/images/EmphathyMapping-Empleado.jpg)

## 2.4. Big Picture EventStorming

Nuestro equipo se enfocó en el dominio del negocio de los minimarkets, identificando los Domain Events más significativos a lo largo de la línea de tiempo operativo, desde que la mercadería ingresa al local hasta que es vendida o registrada como merma.
A continuación se identificaron los siguientes flujos principales a través de Domain Events.

![Big Picture EventStorming](Recursos/images/Bigpicture-eventstorming.png)

## 2.5. Ubiquitous Language

Para asegurar que entre los miembros del equipo y los stakeholders se comuniquen sin ambigüedades, se definieron los términos específicos correspondientes al Business Domain de BodeGo. Todos los términos tienen su nomenclatura en inglés.

- **Product:** Artículo físico que se comercializa en el minimarket. Contiene información general como nombre, código de barras y categoría.
- **Batch:** Conjunto de unidades de un mismo producto que ingresan al inventario en la misma fecha, también comparten la misma fecha de vencimiento.
- **Stock / Inventory:** Cantidad física actual disponible de un producto o lote específico dentro del minimarket.
- **Wastage:** Unidades de un producto que son retiradas del inventario, pudiendo ser por daño físico, vencimiento o robo.
- **Expiration Date:** Día límite establecido por el fabricante para el consumo seguro de un lote.
- **Threshold:** Límite preestablecido por el administrador que al ser sobrepasado, activa una alerta, como por ejemplo Stock mínimo o Días previos al vencimiento.
- **Inventory Movement:** Registro de auditoría que registra cualquier actualización en el Stock (Entrada, Salida, Ajuste o Merma).
- **Offer:** Descuento de precio aplicado a un lote específico que se encuentre próximo a su fecha de vencimiento para acelerar su rotación.
- **Role:** Conjunto de permisos asignados a un usuario, que puede ser Admin o Employee, que define a qué módulos y acciones tiene acceso dentro de BodeGo.

# Capítulo III: Requirements Specification

## 3.1. User Stories

Épicas

| **EPIC-01** | **Gestión de Presencia Digital y Landing Page** |
|-------------|--------------------------------------------------|
| **Descripción:** | **Como** negocio interesado en optimizar su operación, **quiero** conocer la propuesta de valor, funcionalidades y beneficios de BodeGo mediante una landing page clara y profesional **para** comprender cómo la plataforma ayuda a gestionar inventarios, reducir mermas y mejorar los procesos internos del minimarket. |

<br>

| **EPIC-02** | **Aplicación Web y Gestión Operativa** |
|-------------|-----------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** contar con una aplicación web intuitiva con módulos organizados según mis necesidades operativas **para** gestionar inventario, productos y actividades diarias de manera rápida, sencilla y eficiente. |

<br>

| **EPIC-03** | **Control de Inventario y Productos** |
|-------------|----------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** registrar, consultar y actualizar productos, cantidades, lotes y movimientos de inventario **para** mantener un control preciso del stock disponible y reducir diferencias entre el inventario físico y digital. |

<br>

| **EPIC-04** | **Gestión de Mermas, Alertas y Reportes Inteligentes** |
|-------------|---------------------------------------------------------|
| **Descripción:** | **Como** administrador, **quiero** visualizar alertas, indicadores y reportes sobre productos próximos a vencer, mermas y rotación de inventario **para** tomar decisiones oportunas que permitan reducir pérdidas y mejorar la rentabilidad del negocio. |

<br>

| **EPIC-05** | **Automatización de Procesos Operativos** |
|-------------|--------------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** disponer de funcionalidades automatizadas para registrar operaciones, controlar vencimientos y gestionar acciones sobre productos críticos **para** agilizar las tareas diarias y mejorar la eficiencia del establecimiento. |

<br>

| **EPIC-06** | **Gestión de Usuarios y Seguridad del Sistema** |
|-------------|-------------------------------------------------|
| **Descripción:** | **Como** administrador o empleado, **quiero** contar con un sistema seguro de acceso, roles y permisos **para** proteger la información del negocio y garantizar que cada usuario pueda utilizar únicamente las funcionalidades correspondientes a su responsabilidad. |

---

User Stories

| **Epic / Story ID** | **Título** | **Descripción** | **Criterios de Aceptación** | **Relacionado con (Epic ID)** |
|---|---|---|---|---|
| US01 | Visualización del Hero Principal | **Como** visitante, **quiero** visualizar una sección principal con la propuesta de valor de BodeGo, **para** comprender rápidamente cómo la plataforma ayuda a gestionar inventarios y reducir mermas en un minimarket. | **Scenario:** Visualizar información principal de BodeGo<br><br>**Given** el visitante ingresa a la landing page.<br>**When** la página termina de cargar.<br>**Then** el sistema muestra el nombre del producto, mensaje principal, descripción de valor y botón de acción.<br>**And** permite continuar navegando por las secciones informativas. | EPIC-01 |
| US02 | Visualización de Beneficios del Producto | **Como** visitante, **quiero** conocer los beneficios principales de BodeGo, **para** identificar las ventajas de utilizar una plataforma de gestión operativa para mi negocio. | **Scenario:** Consultar beneficios de la solución<br><br>**Given** el visitante se encuentra en la landing page.<br>**When** accede a la sección de beneficios.<br>**Then** el sistema muestra información sobre control de inventario, reducción de mermas y mejora operativa.<br>**And** presenta los beneficios de manera clara y organizada. | EPIC-01 |
| US03 | Presentación de Funcionalidades Principales | **Como** visitante, **quiero** visualizar las funcionalidades principales de BodeGo, **para** conocer las herramientas disponibles antes de utilizar la aplicación web. | **Scenario:** Revisar funcionalidades del sistema<br><br>**Given** el visitante accede a la sección de funcionalidades.<br>**When** revisa los módulos disponibles.<br>**Then** el sistema muestra funcionalidades relacionadas con inventario, alertas, reportes y control operativo.<br>**And** permite comprender el alcance general de la plataforma. | EPIC-01 |
| US04 | Visualización del Funcionamiento de BodeGo | **Como** visitante, **quiero** conocer cómo funciona BodeGo, **para** entender el flujo general de uso dentro de una bodega o minimarket. | **Scenario:** Consultar flujo de funcionamiento<br><br>**Given** el visitante desea conocer el proceso de uso del sistema.<br>**When** ingresa a la sección "Cómo funciona".<br>**Then** el sistema muestra los pasos principales de operación.<br>**And** explica la interacción entre Administrador y Empleado. | EPIC-01 |
| US05 | Formulario de Contacto Comercial | **Como** visitante, **quiero** enviar una solicitud de contacto, **para** recibir información adicional sobre BodeGo y sus funcionalidades. | **Scenario:** Registrar solicitud de contacto<br><br>**Given** el visitante está interesado en conocer más sobre BodeGo.<br>**When** completa el formulario con sus datos personales y de contacto.<br>**Then** el sistema valida la información ingresada.<br>**And** registra correctamente la solicitud enviada. | EPIC-01 |
| US06 | Visualización del Dashboard Administrativo | **Como** Administrador, **quiero** visualizar un dashboard con indicadores principales, **para** conocer rápidamente el estado operativo del negocio. | **Scenario:** Cargar panel principal<br><br>**Given** el Administrador accede correctamente a la aplicación web.<br>**When** ingresa al dashboard inicial.<br>**Then** el sistema muestra indicadores de inventario, productos críticos, vencimientos y movimientos recientes.<br>**And** presenta la información organizada visualmente. | EPIC-02 |
| US07 | Navegación entre Módulos del Sistema | **Como** usuario de BodeGo, **quiero** navegar entre los diferentes módulos disponibles, **para** acceder rápidamente a las funcionalidades necesarias para mi trabajo. | **Scenario:** Acceder a módulos principales<br><br>**Given** el usuario se encuentra dentro de la aplicación web.<br>**When** selecciona una opción del menú lateral.<br>**Then** el sistema carga el módulo correspondiente.<br>**And** muestra únicamente las opciones disponibles según su rol. | EPIC-02 |
| US08 | Visualización del Módulo de Inventario | **Como** Administrador o Empleado, **quiero** visualizar el inventario registrado, **para** conocer la disponibilidad actual de productos dentro del negocio. | **Scenario:** Consultar inventario general<br><br>**Given** el usuario ingresa al módulo de inventario.<br>**When** la vista termina de cargar.<br>**Then** el sistema muestra listado de productos, categorías, cantidades disponibles y estado del stock.<br>**And** permite consultar información actualizada. | EPIC-02 |
| US09 | Consulta del Detalle de Producto | **Como** Administrador o Empleado, **quiero** visualizar el detalle de un producto, **para** revisar información específica como stock, categoría y estado. | **Scenario:** Abrir detalle de producto<br><br>**Given** existe un producto registrado en el sistema.<br>**When** el usuario selecciona un producto del inventario.<br>**Then** el sistema muestra información detallada del producto.<br>**And** permite consultar datos asociados al inventario. | EPIC-02 |
| US10 | Visualización de Operaciones del Empleado | **Como** Empleado, **quiero** consultar mis operaciones realizadas, **para** verificar los movimientos registrados durante mi jornada laboral. | **Scenario:** Consultar historial operativo<br><br>**Given** el empleado tiene operaciones registradas.<br>**When** ingresa al módulo de operaciones.<br>**Then** el sistema muestra sus movimientos realizados.<br>**And** permite revisar información como fecha, tipo de operación y producto asociado. | EPIC-02 |
| US11 | Filtrado y Búsqueda de Productos | **Como** Administrador o Empleado, **quiero** buscar productos mediante filtros, **para** encontrar rápidamente los artículos que necesito gestionar dentro del inventario. | **Scenario:** Buscar productos en inventario<br><br>**Given** el usuario se encuentra dentro del módulo de inventario.<br>**When** ingresa un nombre, categoría o código de producto en el buscador.<br>**Then** el sistema muestra únicamente los productos que coinciden con los criterios ingresados.<br>**And** permite acceder al detalle del producto seleccionado. | EPIC-02 |
| US12 | Visualización de Alertas Operativas | **Como** Administrador, **quiero** visualizar alertas importantes dentro del dashboard, **para** identificar situaciones que requieren atención inmediata. | **Scenario:** Consultar alertas del negocio<br><br>**Given** existen productos con stock bajo o próximos a vencer.<br>**When** el Administrador ingresa al panel principal.<br>**Then** el sistema muestra las alertas generadas.<br>**And** permite acceder al detalle de cada situación detectada. | EPIC-02 |
| US13 | Visualización de Reportes en la Aplicación | **Como** Administrador, **quiero** acceder a reportes visuales, **para** analizar el comportamiento del inventario y las operaciones del negocio. | **Scenario:** Consultar reportes disponibles<br><br>**Given** existen registros operativos dentro del sistema.<br>**When** el Administrador ingresa al módulo de reportes.<br>**Then** el sistema muestra gráficos e indicadores relacionados al negocio.<br>**And** organiza la información para facilitar su interpretación. | EPIC-02 |
| US14 | Gestión Visual de Productos | **Como** Administrador, **quiero** visualizar opciones para gestionar productos, **para** administrar correctamente la información del catálogo interno. | **Scenario:** Acceder a acciones de producto<br><br>**Given** el Administrador visualiza el listado de productos.<br>**When** selecciona un producto registrado.<br>**Then** el sistema muestra opciones disponibles de gestión.<br>**And** permite ejecutar acciones autorizadas sobre el producto. | EPIC-02 |
| US15 | Visualización del Perfil del Negocio | **Como** Administrador, **quiero** consultar la información general del negocio, **para** verificar que los datos operativos estén correctamente configurados. | **Scenario:** Consultar información del negocio<br><br>**Given** el Administrador accede a la sección de configuración.<br>**When** visualiza los datos generales.<br>**Then** el sistema muestra nombre, información comercial y parámetros principales del establecimiento.<br>**And** permite identificar la configuración actual. | EPIC-02 |
| US16 | Registro de Productos | **Como** Administrador, **quiero** registrar nuevos productos en el sistema, **para** mantener actualizado el catálogo de inventario del negocio. | **Scenario:** Crear nuevo producto<br><br>**Given** el Administrador se encuentra en el módulo de productos.<br>**When** completa los datos obligatorios del producto y confirma el registro.<br>**Then** el sistema almacena la información del producto.<br>**And** el nuevo elemento aparece disponible en el inventario. | EPIC-03 |
| US17 | Edición de Información del Producto | **Como** Administrador, **quiero** modificar la información de un producto registrado, **para** mantener datos actualizados dentro del sistema. | **Scenario:** Actualizar producto existente<br><br>**Given** existe un producto registrado en BodeGo.<br>**When** el Administrador modifica sus datos y guarda los cambios.<br>**Then** el sistema actualiza la información del producto.<br>**And** conserva el historial de modificaciones realizadas. | EPIC-03 |
| US18 | Clasificación de Productos por Categoría | **Como** Administrador, **quiero** asignar categorías a los productos, **para** organizar el inventario y facilitar su búsqueda. | **Scenario:** Clasificar producto<br><br>**Given** existe un producto registrado sin categoría asignada.<br>**When** el Administrador selecciona una categoría disponible.<br>**Then** el sistema relaciona el producto con dicha categoría.<br>**And** permite filtrarlo mediante esa clasificación. | EPIC-03 |
| US19 | Registro de Ingreso de Inventario | **Como** Empleado, **quiero** registrar ingresos de productos al inventario, **para** mantener actualizado el stock disponible del negocio. | **Scenario:** Registrar entrada de mercadería<br><br>**Given** el Empleado recibe nuevos productos.<br>**When** registra cantidades, producto y datos del ingreso.<br>**Then** el sistema incrementa el stock correspondiente.<br>**And** genera un movimiento de entrada asociado al usuario responsable. | EPIC-03 |
| US20 | Gestión de Lotes y Fechas de Vencimiento | **Como** Empleado, **quiero** registrar lotes con fechas de vencimiento, **para** controlar productos perecibles y prevenir pérdidas por caducidad. | **Scenario:** Registrar lote de producto<br><br>**Given** existe un producto perecible registrado.<br>**When** el Empleado ingresa información del lote y fecha de vencimiento.<br>**Then** el sistema almacena la información asociada al producto.<br>**And** utiliza estos datos para futuros controles y alertas. | EPIC-03 |
| US21 | Consulta de Stock Actual | **Como** Administrador o Empleado, **quiero** consultar la cantidad disponible de cada producto, **para** conocer el estado actual del inventario antes de realizar operaciones. | **Scenario:** Consultar disponibilidad de producto<br><br>**Given** existen productos registrados en el sistema.<br>**When** el usuario consulta el inventario.<br>**Then** el sistema muestra la cantidad disponible de cada producto.<br>**And** indica el estado del stock según los parámetros configurados. | EPIC-03 |
| US22 | Actualización Automática de Stock | **Como** sistema, **quiero** actualizar automáticamente las cantidades disponibles después de cada movimiento, **para** mantener información precisa del inventario. | **Scenario:** Actualizar stock después de operación<br><br>**Given** existe una operación que modifica el inventario.<br>**When** la operación es confirmada.<br>**Then** el sistema recalcula la cantidad disponible del producto.<br>**And** registra el movimiento asociado. | EPIC-03 |
| US23 | Registro de Salida de Productos | **Como** Empleado, **quiero** registrar salidas de productos del inventario, **para** mantener actualizado el stock después de una venta u operación interna. | **Scenario:** Registrar salida de producto<br><br>**Given** existe stock disponible del producto seleccionado.<br>**When** el Empleado registra una salida indicando cantidad y motivo.<br>**Then** el sistema descuenta las unidades correspondientes.<br>**And** almacena el movimiento realizado. | EPIC-03 |
| US24 | Validación de Stock Disponible | **Como** sistema, **quiero** validar la disponibilidad de productos antes de una salida, **para** evitar cantidades negativas o inconsistencias en el inventario. | **Scenario:** Validar existencia antes de salida<br><br>**Given** el usuario intenta registrar una salida de producto.<br>**When** la cantidad solicitada supera el stock disponible.<br>**Then** el sistema rechaza la operación.<br>**And** muestra un mensaje indicando la cantidad disponible actual. | EPIC-03 |
| US25 | Ajuste Manual de Inventario | **Como** Administrador, **quiero** realizar ajustes manuales de inventario, **para** corregir diferencias entre el stock físico y el registrado en el sistema. | **Scenario:** Corregir diferencia de inventario<br><br>**Given** existe una diferencia detectada durante una revisión física.<br>**When** el Administrador registra un ajuste indicando cantidad y motivo.<br>**Then** el sistema actualiza el stock del producto.<br>**And** guarda el registro del ajuste realizado. | EPIC-03 |
| US26 | Historial de Movimientos de Inventario | **Como** Administrador, **quiero** consultar el historial de movimientos de productos, **para** conocer la trazabilidad de entradas y salidas realizadas. | **Scenario:** Consultar movimientos registrados<br><br>**Given** existen movimientos asociados a productos.<br>**When** el Administrador consulta el historial.<br>**Then** el sistema muestra fecha, tipo de movimiento, cantidad y usuario responsable.<br>**And** permite revisar el origen de los cambios realizados. | EPIC-03 |
| US27 | Control de Productos Próximos a Vencer | **Como** Administrador, **quiero** identificar productos próximos a vencer, **para** tomar acciones preventivas antes de generar pérdidas. | **Scenario:** Detectar productos próximos a vencer<br><br>**Given** existen productos con fecha de vencimiento registrada.<br>**When** el sistema evalúa las fechas configuradas.<br>**Then** identifica los productos dentro del rango de alerta.<br>**And** los muestra como productos próximos a vencer. | EPIC-03 |
| US28 | Priorización de Lotes por Vencimiento | **Como** Empleado, **quiero** conocer qué lote debe salir primero, **para** aplicar una rotación adecuada de productos perecibles. | **Scenario:** Priorizar lote de salida<br><br>**Given** un producto posee múltiples lotes registrados.<br>**When** el Empleado consulta la disponibilidad del producto.<br>**Then** el sistema recomienda utilizar el lote con vencimiento más cercano.<br>**And** facilita la rotación correcta del inventario. | EPIC-03 |
| US29 | Registro de Conteo Físico de Inventario | **Como** Administrador o Empleado autorizado, **quiero** registrar conteos físicos del inventario, **para** comparar las existencias reales contra las registradas en BodeGo. | **Scenario:** Realizar conteo físico<br><br>**Given** el usuario inicia una revisión de inventario.<br>**When** registra las cantidades encontradas físicamente.<br>**Then** el sistema compara los valores registrados con el stock actual.<br>**And** muestra diferencias encontradas. | EPIC-03 |
| US30 | Trazabilidad por Producto y Lote | **Como** Administrador, **quiero** consultar la trazabilidad completa de un producto y sus lotes, **para** conocer su historial dentro del negocio. | **Scenario:** Consultar trazabilidad del producto<br><br>**Given** existe un producto con movimientos registrados.<br>**When** el Administrador accede al historial detallado.<br>**Then** el sistema muestra ingresos, salidas, ajustes y lotes asociados.<br>**And** permite identificar cada cambio realizado sobre el producto. | EPIC-03 |
| US31 | Registro de Productos Dañados o Vencidos | **Como** Empleado, **quiero** registrar productos dañados o vencidos, **para** mantener actualizado el inventario y documentar las pérdidas generadas. | **Scenario:** Registrar producto como merma<br><br>**Given** existe un producto registrado dentro del inventario.<br>**When** el Empleado registra una pérdida indicando cantidad y motivo.<br>**Then** el sistema descuenta las unidades afectadas del stock disponible.<br>**And** genera un registro de merma asociado al producto. | EPIC-04 |
| US32 | Clasificación de Motivos de Merma | **Como** Administrador, **quiero** clasificar las causas de las mermas registradas, **para** identificar los principales motivos de pérdida dentro del negocio. | **Scenario:** Clasificar una merma registrada<br><br>**Given** existe un registro de merma generado.<br>**When** el Administrador revisa la información de pérdida.<br>**Then** el sistema permite asociar categorías como vencimiento, daño o deterioro.<br>**And** almacena la clasificación para futuros reportes. | EPIC-04 |
| US33 | Visualización de Productos con Riesgo de Merma | **Como** Administrador, **quiero** visualizar productos con riesgo de pérdida, **para** tomar acciones preventivas antes de generar desperdicios. | **Scenario:** Consultar productos en riesgo<br><br>**Given** existen productos próximos a vencer o con baja rotación.<br>**When** el Administrador ingresa al módulo de alertas.<br>**Then** el sistema muestra los productos identificados como riesgo.<br>**And** permite revisar información del producto afectado. | EPIC-04 |
| US34 | Generación de Alertas de Stock Bajo | **Como** Administrador, **quiero** recibir alertas cuando un producto tenga stock bajo, **para** anticipar necesidades de reposición. | **Scenario:** Detectar stock bajo<br><br>**Given** un producto alcanza el límite mínimo configurado.<br>**When** el sistema actualiza la información del inventario.<br>**Then** genera una alerta automática de stock bajo.<br>**And** muestra el producto que requiere atención. | EPIC-04 |
| US35 | Configuración de Parámetros de Alertas | **Como** Administrador, **quiero** configurar los valores mínimos de stock y días de vencimiento, **para** adaptar las alertas según las necesidades del negocio. | **Scenario:** Configurar parámetros operativos<br><br>**Given** el Administrador accede a la configuración del sistema.<br>**When** modifica los valores de alerta permitidos.<br>**Then** el sistema guarda los nuevos parámetros.<br>**And** los utiliza para generar futuras notificaciones. | EPIC-04 |
| US36 | Reporte de Productos Próximos a Vencer | **Como** Administrador, **quiero** consultar un reporte de productos próximos a vencer, **para** planificar acciones que reduzcan pérdidas. | **Scenario:** Generar reporte de vencimientos<br><br>**Given** existen productos con fechas de vencimiento registradas.<br>**When** el Administrador solicita el reporte.<br>**Then** el sistema muestra productos, cantidades y fechas próximas de vencimiento.<br>**And** permite identificar productos prioritarios. | EPIC-04 |
| US37 | Reporte de Mermas del Negocio | **Como** Administrador, **quiero** visualizar reportes de mermas, **para** analizar las pérdidas generadas en el establecimiento. | **Scenario:** Consultar reporte de mermas<br><br>**Given** existen registros de productos desperdiciados.<br>**When** el Administrador accede al módulo de reportes.<br>**Then** el sistema muestra cantidades, motivos y productos afectados.<br>**And** permite analizar tendencias de pérdida. | EPIC-04 |
| US38 | Reporte de Rotación de Productos | **Como** Administrador, **quiero** conocer la rotación de productos, **para** identificar cuáles tienen mayor o menor movimiento dentro del inventario. | **Scenario:** Analizar rotación de inventario<br><br>**Given** existen movimientos registrados de productos.<br>**When** el Administrador consulta el reporte de rotación.<br>**Then** el sistema calcula la frecuencia de salida de cada producto.<br>**And** muestra información ordenada según comportamiento de movimiento. | EPIC-04 |
| US39 | Dashboard de Indicadores del Negocio | **Como** Administrador, **quiero** visualizar indicadores generales del negocio, **para** tomar decisiones basadas en información actualizada. | **Scenario:** Consultar indicadores principales<br><br>**Given** existen datos registrados dentro de BodeGo.<br>**When** el Administrador ingresa al dashboard.<br>**Then** el sistema muestra indicadores de inventario, mermas, alertas y operaciones.<br>**And** presenta información resumida del estado actual del negocio. | EPIC-04 |
| US40 | Análisis de Productos de Alta Rotación | **Como** Administrador, **quiero** identificar productos con alta rotación, **para** mejorar la planificación de compras y organización del inventario. | **Scenario:** Consultar productos de alta rotación<br><br>**Given** existen movimientos históricos de inventario.<br>**When** el Administrador consulta el análisis de rotación.<br>**Then** el sistema identifica los productos con mayor frecuencia de salida.<br>**And** muestra información útil para la toma de decisiones. | EPIC-04 |
| US41 | Sugerencia Automática de Ofertas por Vencimiento | **Como** Administrador, **quiero** recibir sugerencias automáticas de ofertas para productos próximos a vencer, **para** reducir pérdidas y mejorar la rotación del inventario. | **Scenario:** Generar sugerencia automática de oferta<br><br>**Given** existen productos próximos a vencer con stock disponible.<br>**When** el sistema ejecuta la validación de productos críticos.<br>**Then** genera una sugerencia de oferta indicando producto, cantidad y fecha de vencimiento.<br>**And** permite al Administrador revisar la propuesta antes de activarla. | EPIC-05 |
| US42 | Creación de Ofertas Estratégicas | **Como** Administrador, **quiero** crear ofertas sobre productos seleccionados, **para** acelerar la salida de productos con baja rotación o próximos a vencer. | **Scenario:** Crear nueva oferta comercial<br><br>**Given** existe un producto disponible en inventario.<br>**When** el Administrador define descuento, vigencia y producto asociado.<br>**Then** el sistema registra la oferta correctamente.<br>**And** la deja disponible para su aplicación durante el período configurado. | EPIC-05 |
| US43 | Aplicación Automática de Reglas de Negocio | **Como** sistema, **quiero** ejecutar reglas automáticas sobre inventario y productos críticos, **para** mantener procesos operativos eficientes sin intervención constante del usuario. | **Scenario:** Ejecutar reglas automáticas<br><br>**Given** existen condiciones configuradas dentro del sistema.<br>**When** se cumple una regla de negocio establecida.<br>**Then** el sistema ejecuta la acción correspondiente.<br>**And** registra el resultado generado por la automatización. | EPIC-05 |
| US44 | Actualización Automática de Estados Operativos | **Como** Administrador, **quiero** que el sistema actualice estados de productos y alertas automáticamente, **para** mantener información operativa actualizada. | **Scenario:** Actualizar estados automáticamente<br><br>**Given** existen productos con cambios en su condición operativa.<br>**When** el sistema procesa la información registrada.<br>**Then** actualiza el estado correspondiente del producto.<br>**And** refleja los cambios en los módulos relacionados. | EPIC-05 |
| US45 | Generación Automática de Resúmenes Operativos | **Como** Administrador, **quiero** recibir resúmenes automáticos del estado del negocio, **para** revisar rápidamente la situación operativa del minimarket. | **Scenario:** Generar resumen operativo<br><br>**Given** existen movimientos registrados durante un período determinado.<br>**When** el sistema genera el resumen correspondiente.<br>**Then** muestra información relevante de inventario, mermas y operaciones.<br>**And** permite consultar los principales indicadores del negocio. | EPIC-05 |
| US46 | Registro de Usuarios del Sistema | **Como** Administrador, **quiero** registrar usuarios dentro de BodeGo, **para** permitir que empleados autorizados puedan utilizar la plataforma. | **Scenario:** Crear usuario nuevo<br><br>**Given** el Administrador tiene permisos de gestión de usuarios.<br>**When** registra los datos requeridos de un nuevo usuario.<br>**Then** el sistema valida la información ingresada.<br>**And** crea la cuenta asociada al rol correspondiente. | EPIC-06 |
| US47 | Gestión de Roles y Permisos | **Como** Administrador, **quiero** asignar roles y permisos a los usuarios, **para** controlar el acceso a las funcionalidades del sistema. | **Scenario:** Asignar permisos de usuario<br><br>**Given** existe un usuario registrado en la plataforma.<br>**When** el Administrador selecciona un rol disponible.<br>**Then** el sistema asigna los permisos correspondientes.<br>**And** limita el acceso según las responsabilidades definidas. | EPIC-06 |
| US48 | Inicio de Sesión Seguro | **Como** usuario registrado, **quiero** iniciar sesión mediante mis credenciales, **para** acceder de manera segura a las funcionalidades asignadas. | **Scenario:** Autenticar usuario<br><br>**Given** el usuario posee una cuenta activa en BodeGo.<br>**When** ingresa sus credenciales correctamente.<br>**Then** el sistema valida la información proporcionada.<br>**And** permite el acceso según el rol asignado. | EPIC-06 |
| US49 | Recuperación y Cambio de Contraseña | **Como** usuario, **quiero** recuperar o cambiar mi contraseña, **para** mantener protegido mi acceso a la plataforma. | **Scenario:** Actualizar contraseña de usuario<br><br>**Given** el usuario solicita modificar su contraseña.<br>**When** completa el proceso de recuperación o cambio establecido.<br>**Then** el sistema valida la solicitud.<br>**And** actualiza la contraseña de forma segura. | EPIC-06 |
| US50 | Cierre de Sesión y Protección de Cuenta | **Como** usuario, **quiero** cerrar mi sesión correctamente, **para** evitar accesos no autorizados a mi cuenta desde el dispositivo utilizado. | **Scenario:** Cerrar sesión del sistema<br><br>**Given** el usuario tiene una sesión activa en BodeGo.<br>**When** selecciona la opción de cerrar sesión.<br>**Then** el sistema invalida la sesión actual.<br>**And** redirige al usuario hacia la pantalla de acceso. | EPIC-06 |

## 3.2. Impact Mapping

---

| **Business Goals** | **Actors** | **Impact** | **Deliverables** | **User Stories** |
|---|---|---|---|---|
| **Goal N°1:**<br>**Captar el interés de negocios minoristas mediante una presencia digital clara que comunique la propuesta de valor de BodeGo durante los primeros 12 meses.** | Visitante / Cliente potencial | Conocer la solución BodeGo, comprender sus beneficios y solicitar información sobre la plataforma. | Landing Page comercial.<br><br>Secciones informativas del producto.<br><br>Formulario de contacto. | **US01: Visualización del Hero Principal.** Como visitante, quiero visualizar una sección principal con la propuesta de valor de BodeGo, para comprender cómo la plataforma ayuda a gestionar inventarios y reducir mermas.<br><br>**US02: Visualización de Beneficios del Producto.** Como visitante, quiero conocer los beneficios principales de BodeGo, para identificar las ventajas de utilizar una plataforma de gestión operativa.<br><br>**US03: Presentación de Funcionalidades Principales.** Como visitante, quiero visualizar las funcionalidades principales de BodeGo, para conocer las herramientas disponibles antes de utilizar la aplicación.<br><br>**US05: Formulario de Contacto Comercial.** Como visitante, quiero enviar una solicitud de contacto, para recibir información adicional sobre BodeGo. |
| | Visitante / Cliente potencial | Entender el funcionamiento general del producto antes de incorporarlo al negocio. | Sección explicativa del funcionamiento de la plataforma. | **US04: Visualización del Funcionamiento de BodeGo.** Como visitante, quiero conocer cómo funciona BodeGo, para entender el flujo general de uso dentro de una bodega o minimarket. |
| **Goal N°2:**<br>**Mejorar el control operativo del inventario reduciendo errores de registro manual en un 40% durante los primeros 12 meses.** | Administrador | Mantener productos correctamente registrados y organizados dentro del sistema. | Gestión de productos.<br><br>Categorías.<br><br>Detalle de productos. | **US16: Registro de Productos.** Como Administrador, quiero registrar nuevos productos, para mantener actualizado el catálogo de inventario.<br><br>**US17: Edición de Información del Producto.** Como Administrador, quiero modificar la información de un producto registrado, para mantener datos actualizados.<br><br>**US18: Clasificación de Productos por Categoría.** Como Administrador, quiero asignar categorías a los productos, para organizar el inventario y facilitar su búsqueda.<br><br>**US09: Consulta del Detalle de Producto.** Como Administrador o Empleado, quiero visualizar el detalle de un producto, para revisar información específica del artículo. |
| | Administrador / Empleado | Encontrar rápidamente productos y conocer su disponibilidad actual. | Buscador y filtros de inventario.<br><br>Visualización de inventario. | **US08: Visualización del Módulo de Inventario.** Como Administrador o Empleado, quiero visualizar el inventario registrado, para conocer la disponibilidad actual de productos.<br><br>**US11: Filtrado y Búsqueda de Productos.** Como Administrador o Empleado, quiero buscar productos mediante filtros, para encontrar rápidamente los artículos que necesito gestionar.<br><br>**US21: Consulta de Stock Actual.** Como Administrador o Empleado, quiero consultar la cantidad disponible de cada producto, para conocer el estado actual del inventario. |
| **Goal N°3:**<br>**Reducir en un 30% las pérdidas generadas por productos vencidos, dañados o deteriorados durante los primeros 10 meses.** | Administrador / Empleado | Controlar productos perecibles y actuar antes de generar pérdidas económicas. | Gestión de lotes.<br><br>Control de vencimientos.<br><br>Registro de mermas.<br><br>Alertas preventivas. | **US20: Gestión de Lotes y Fechas de Vencimiento.** Como Empleado, quiero registrar lotes con fechas de vencimiento, para controlar productos perecibles.<br><br>**US27: Control de Productos Próximos a Vencer.** Como Administrador, quiero identificar productos próximos a vencer, para tomar acciones preventivas.<br><br>**US31: Registro de Productos Dañados o Vencidos.** Como Empleado, quiero registrar productos dañados o vencidos, para mantener actualizado el inventario.<br><br>**US34: Generación de Alertas de Stock Bajo.** Como Administrador, quiero recibir alertas cuando un producto tenga stock bajo, para anticipar necesidades de reposición. |
| **Goal N°4:**<br>**Digitalizar el 80% de las operaciones diarias realizadas por empleados durante los primeros 6 meses de implementación.** | Empleado Operativo | Registrar correctamente ingresos, salidas y movimientos del inventario. | Registro de operaciones.<br><br>Actualización automática de stock.<br><br>Historial operativo. | **US19: Registro de Ingreso de Inventario.** Como Empleado, quiero registrar ingresos de productos al inventario, para mantener actualizado el stock disponible.<br><br>**US23: Registro de Salida de Productos.** Como Empleado, quiero registrar salidas de productos, para mantener actualizado el inventario.<br><br>**US26: Historial de Movimientos de Inventario.** Como Administrador, quiero consultar el historial de movimientos, para conocer la trazabilidad.<br><br>**US34: Visualización de Operaciones del Empleado.** Como Empleado, quiero consultar mis operaciones realizadas, para verificar movimientos registrados durante mi jornada. |
| **Goal N°5:**<br>**Mejorar la toma de decisiones del administrador mediante indicadores y reportes operativos durante los primeros 12 meses.** | Administrador | Analizar información del negocio para tomar decisiones estratégicas. | Dashboard administrativo.<br><br>Reportes analíticos.<br><br>Indicadores operativos. | **US37: Dashboard de Indicadores del Negocio.** Como Administrador, quiero visualizar indicadores generales del negocio, para conocer rápidamente el estado operativo.<br><br>**US38: Reporte de Rotación de Productos.** Como Administrador, quiero conocer la rotación de productos, para identificar comportamiento del inventario.<br><br>**US39: Reporte de Productos Próximos a Vencer.** Como Administrador, quiero consultar productos próximos a vencer, para planificar acciones preventivas.<br><br>**US40: Reporte de Mermas del Negocio.** Como Administrador, quiero visualizar reportes de mermas, para analizar pérdidas generadas. |
| **Goal N°6:**<br>**Garantizar que todos los accesos al sistema sean seguros mediante autenticación y permisos definidos durante la primera versión productiva.** | Administrador / Empleado | Acceder únicamente a las funcionalidades correspondientes según su responsabilidad. | Gestión de usuarios.<br><br>Roles y permisos.<br><br>Autenticación.<br><br>Gestión de contraseña. | **US46: Registro de Usuarios del Sistema.** Como Administrador, quiero registrar usuarios dentro de BodeGo, para permitir accesos autorizados.<br><br>**US47: Gestión de Roles y Permisos.** Como Administrador, quiero asignar roles y permisos, para controlar el acceso a funcionalidades.<br><br>**US48: Inicio de Sesión Seguro.** Como usuario registrado, quiero iniciar sesión mediante mis credenciales, para acceder de manera segura.<br><br>**US49: Recuperación y Cambio de Contraseña.** Como usuario, quiero recuperar o cambiar mi contraseña, para mantener protegido mi acceso.<br><br>**US50: Cierre de Sesión y Protección de Cuenta.** Como usuario, quiero cerrar mi sesión correctamente, para evitar accesos no autorizados. |

## 3.3. Product Backlog

# Product Backlog — BodeGo

| **# Orden** | **User Story ID** | **Título** | **Descripción** | **Story Points**<br>**(1 / 2 / 3 / 5 / 8)** |
|---:|:---:|---|---|---:|
| **1** | **US01** | Visualización del Hero Principal | **Como** visitante, **deseo** visualizar la propuesta de valor principal de BodeGo, **para** comprender cómo la plataforma ayuda a gestionar inventarios y reducir mermas en negocios minoristas. | **2** |
| **2** | **US02** | Visualización de Beneficios del Producto | **Como** visitante, **deseo** conocer los beneficios principales de BodeGo, **para** identificar el valor que aporta la solución a la gestión del negocio. | **2** |
| **3** | **US03** | Presentación de Funcionalidades Principales | **Como** visitante, **deseo** conocer las funcionalidades principales de BodeGo, **para** comprender las capacidades disponibles antes de utilizar la plataforma. | **3** |
| **4** | **US04** | Explicación del Funcionamiento de BodeGo | **Como** visitante, **deseo** conocer cómo funciona BodeGo, **para** entender el flujo general de uso dentro de una bodega o minimarket. | **2** |
| **5** | **US05** | Formulario de Contacto Comercial | **Como** visitante, **deseo** enviar una solicitud de contacto, **para** recibir información adicional sobre la solución BodeGo. | **3** |
| **6** | **US06** | Dashboard Administrativo | **Como** Administrador, **deseo** visualizar indicadores principales del negocio, **para** conocer rápidamente el estado operativo del establecimiento. | **5** |
| **7** | **US08** | Visualización del Inventario | **Como** Administrador o Empleado, **deseo** visualizar los productos registrados, **para** conocer la disponibilidad actual del inventario. | **3** |
| **8** | **US11** | Búsqueda y Filtrado de Productos | **Como** Administrador o Empleado, **deseo** buscar productos mediante filtros, **para** encontrar rápidamente los artículos que necesito gestionar. | **3** |
| **9** | **US09** | Consulta del Detalle del Producto | **Como** Administrador o Empleado, **deseo** visualizar la información detallada de un producto, **para** revisar sus características y estado actual. | **2** |
| **10** | **US07** | Navegación entre Módulos | **Como** usuario de BodeGo, **deseo** navegar entre módulos disponibles, **para** acceder rápidamente a las funcionalidades necesarias. | **3** |
| **11** | **US10** | Visualización de Operaciones del Empleado | **Como** Empleado, **deseo** consultar las operaciones que he realizado, **para** verificar los movimientos registrados durante mi jornada laboral. | **3** |
| **12** | **US12** | Visualización de Alertas Operativas | **Como** Administrador, **deseo** visualizar alertas importantes del negocio, **para** identificar situaciones que requieren atención inmediata dentro del inventario. | **5** |
| **13** | **US13** | Visualización de Reportes del Negocio | **Como** Administrador, **deseo** acceder a reportes visuales, **para** analizar el comportamiento del inventario y las operaciones realizadas. | **5** |
| **14** | **US14** | Gestión Visual de Productos | **Como** Administrador, **deseo** acceder a opciones de gestión de productos, **para** administrar correctamente la información del catálogo interno. | **3** |
| **15** | **US15** | Visualización de Información del Negocio | **Como** Administrador, **deseo** consultar la información general del establecimiento, **para** verificar que los datos operativos estén correctamente configurados. | **2** |
| **16** | **US16** | Registro de Productos | **Como** Administrador, **deseo** registrar nuevos productos dentro del sistema, **para** mantener actualizado el catálogo de inventario del negocio. | **3** |
| **17** | **US18** | Clasificación de Productos por Categoría | **Como** Administrador, **deseo** asignar categorías a los productos, **para** organizar el inventario y facilitar su búsqueda y análisis. | **2** |
| **18** | **US17** | Edición de Información del Producto | **Como** Administrador, **deseo** modificar la información de productos registrados, **para** mantener actualizados los datos utilizados por la operación. | **2** |
| **19** | **US19** | Registro de Ingreso de Inventario | **Como** Empleado, **deseo** registrar ingresos de productos al inventario, **para** mantener actualizado el stock disponible del negocio. | **5** |
| **20** | **US20** | Gestión de Lotes y Fechas de Vencimiento | **Como** Empleado, **deseo** registrar lotes con fechas de vencimiento, **para** controlar productos perecibles y prevenir pérdidas por caducidad. | **3** |
| **21** | **US21** | Consulta de Stock Actual | **Como** Administrador o Empleado, **deseo** consultar la cantidad disponible de cada producto, **para** conocer el estado actual del inventario antes de realizar operaciones. | **3** |
| **22** | **US23** | Registro de Salida de Productos | **Como** Empleado, **deseo** registrar salidas de productos del inventario, **para** mantener actualizado el stock después de una venta u operación interna. | **5** |
| **23** | **US22** | Actualización Automática de Stock | **Como** sistema, **deseo** actualizar automáticamente las cantidades disponibles después de cada movimiento, **para** mantener información precisa del inventario. | **5** |
| **24** | **US24** | Validación de Stock Disponible | **Como** sistema, **deseo** validar la disponibilidad de productos antes de una salida, **para** evitar cantidades negativas o inconsistencias en el inventario. | **3** |
| **25** | **US25** | Ajuste Manual de Inventario | **Como** Administrador, **deseo** realizar ajustes manuales de inventario, **para** corregir diferencias entre el stock físico y el registrado en el sistema. | **3** |
| **26** | **US26** | Historial de Movimientos de Inventario | **Como** Administrador, **deseo** consultar el historial de movimientos de productos, **para** conocer la trazabilidad de entradas y salidas realizadas. | **3** |
| **27** | **US29** | Registro de Conteo Físico de Inventario | **Como** Administrador o Empleado autorizado, **deseo** registrar conteos físicos del inventario, **para** comparar las existencias reales contra las registradas en BodeGo. | **5** |
| **28** | **US30** | Trazabilidad de Producto y Lotes | **Como** Administrador, **deseo** consultar la trazabilidad completa de un producto y sus lotes, **para** conocer su historial dentro del negocio. | **5** |
| **29** | **US27** | Control de Productos Próximos a Vencer | **Como** Administrador, **deseo** identificar productos próximos a vencer, **para** tomar acciones preventivas antes de generar pérdidas. | **5** |
| **30** | **US28** | Priorización de Lotes por Vencimiento | **Como** Empleado, **deseo** conocer qué lote debe salir primero, **para** aplicar una rotación adecuada de productos perecibles. | **5** |
| **31** | **US31** | Registro de Productos Dañados o Vencidos | **Como** Empleado, **deseo** registrar productos dañados o vencidos indicando la causa, **para** mantener actualizado el inventario y documentar las pérdidas generadas. | **3** |
| **32** | **US32** | Clasificación de Motivos de Merma | **Como** Administrador, **deseo** clasificar las causas de las mermas registradas, **para** identificar los principales motivos de pérdida dentro del negocio. | **3** |
| **33** | **US33** | Visualización de Productos con Riesgo de Merma | **Como** Administrador, **deseo** visualizar productos con riesgo de pérdida, **para** tomar acciones preventivas antes de generar desperdicios. | **5** |
| **34** | **US34** | Alertas de Stock Bajo | **Como** Administrador, **deseo** recibir alertas cuando un producto alcance un nivel crítico de stock, **para** anticipar necesidades de reposición. | **3** |
| **35** | **US35** | Configuración de Parámetros de Alertas | **Como** Administrador, **deseo** configurar los valores mínimos de stock y días de vencimiento, **para** adaptar las alertas según las necesidades del negocio. | **3** |
| **36** | **US36** | Reporte de Productos Próximos a Vencer | **Como** Administrador, **deseo** consultar reportes de productos próximos a vencer, **para** planificar acciones que reduzcan pérdidas por caducidad. | **5** |
| **37** | **US37** | Reporte de Mermas del Negocio | **Como** Administrador, **deseo** visualizar reportes de mermas, **para** analizar las pérdidas generadas dentro del establecimiento. | **5** |
| **38** | **US38** | Reporte de Rotación de Productos | **Como** Administrador, **deseo** conocer la rotación de productos, **para** identificar cuáles tienen mayor o menor movimiento dentro del inventario. | **5** |
| **39** | **US39** | Dashboard de Indicadores del Negocio | **Como** Administrador, **deseo** visualizar indicadores generales del negocio, **para** conocer rápidamente el estado del inventario y la operación. | **5** |
| **40** | **US40** | Análisis de Productos de Alta Rotación | **Como** Administrador, **deseo** identificar productos con mayor frecuencia de salida, **para** mejorar la planificación de compras y organización del inventario. | **5** |
| **41** | **US41** | Sugerencia Automática de Ofertas por Vencimiento | **Como** Administrador, **deseo** recibir sugerencias automáticas de ofertas para productos próximos a vencer, **para** reducir pérdidas y mejorar la rotación del inventario. | **8** |
| **42** | **US42** | Creación de Ofertas Estratégicas | **Como** Administrador, **deseo** crear ofertas sobre productos seleccionados, **para** acelerar la salida de productos con baja rotación o próximos a vencer. | **3** |
| **43** | **US43** | Ejecución Automática de Reglas de Negocio | **Como** sistema, **deseo** ejecutar reglas automáticas sobre inventario y productos críticos, **para** mantener procesos operativos eficientes sin intervención constante del usuario. | **8** |
| **44** | **US44** | Actualización Automática de Estados Operativos | **Como** Administrador, **deseo** que el sistema actualice automáticamente estados de productos y alertas, **para** mantener información operativa actualizada. | **5** |
| **45** | **US45** | Generación de Resúmenes Operativos | **Como** Administrador, **deseo** recibir resúmenes automáticos del estado del negocio, **para** revisar rápidamente la situación operativa del minimarket. | **5** |
| **46** | **US46** | Registro de Usuarios del Sistema | **Como** Administrador, **deseo** registrar usuarios dentro de BodeGo, **para** permitir accesos autorizados al sistema según las necesidades del negocio. | **3** |
| **47** | **US47** | Gestión de Roles y Permisos | **Como** Administrador, **deseo** asignar roles y permisos a los usuarios, **para** controlar el acceso a las funcionalidades según sus responsabilidades. | **5** |
| **48** | **US48** | Inicio de Sesión Seguro | **Como** usuario registrado, **deseo** iniciar sesión mediante mis credenciales, **para** acceder de manera segura a las funcionalidades asignadas dentro de BodeGo. | **3** |
| **49** | **US49** | Recuperación y Cambio de Contraseña | **Como** usuario, **deseo** recuperar o cambiar mi contraseña, **para** mantener protegido mi acceso a la plataforma. | **3** |
| **50** | **US50** | Cierre de Sesión y Protección de Cuenta | **Como** usuario, **deseo** cerrar mi sesión correctamente, **para** evitar accesos no autorizados desde el dispositivo utilizado. | **1** |

---

# Capítulo IV: Product Design

## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines

El sistema de diseño de **BodeGo** se basa en una estética moderna, limpia y funcional, orientada a facilitar la gestión diaria de inventarios en minimarkets. La interfaz busca mostrar la información de manera clara y ordenada, permitiendo que Administradores y Empleados puedan identificar rápidamente el estado del stock, los productos próximos a vencer y las operaciones realizadas.

- **Branding & Tono:**
  - **Tono:** Profesional, confiable y práctico.
  - **Lenguaje:** Claro, directo y orientado a las operaciones del minimarket.
  - **Personalidad:** BodeGo se presenta como una herramienta de apoyo para mantener el inventario organizado y reducir pérdidas por productos perecibles.
  - **Identidad:** Se prioriza la sensación de control, rapidez y seguridad en las operaciones.

- **Typography:**
  - **Fuente principal:** Hanken Grotesk.
  - **Títulos:** Uso de pesos Bold o SemiBold para destacar nombres de módulos, indicadores y datos importantes.
  - **Contenido:** Peso Regular para tablas, descripciones y textos informativos.
  - **Etiquetas:** Tamaño reducido para estados, categorías, fechas y datos secundarios.
  - Se mantiene una jerarquía visual clara entre títulos, subtítulos, indicadores y contenido.

- **Colors:**
  - **Principal:** Azul `#2563EB`, utilizado para botones, acciones principales, elementos seleccionados y enlaces.
  - **Secundario:** Azul oscuro `#0F172A`, empleado principalmente en textos importantes y elementos de alto contraste.
  - **Terciario:** Verde `#10B981`, utilizado para indicar estados correctos, productos activos, ingresos o acciones exitosas.
  - **Neutral:** Gris `#64748B`, empleado en información secundaria, iconos y etiquetas.
  - **Rojo:** Utilizado para alertas críticas, productos vencidos, stock crítico y errores.
  - **Amarillo/Naranja:** Utilizado para advertencias y productos próximos a vencer.

- **Spacing:**
  - Los módulos mantienen márgenes y separaciones constantes entre tarjetas, tablas y formularios.
  - Las tarjetas utilizan bordes suavemente redondeados.
  - La información se distribuye mediante bloques y columnas para evitar la saturación visual.
  - Los indicadores principales cuentan con mayor espacio para facilitar su identificación.

- **Iconografía:**
  - Se utilizan iconos simples acompañados de texto para facilitar la comprensión.
  - Los iconos permiten diferenciar rápidamente acciones como registrar ingreso, registrar salida, registrar merma, consultar inventario o acceder a reportes.
  - Los colores de los iconos también ayudan a comunicar el estado de cada operación.

---

### 4.1.2. Web Style Guidelines

BodeGo está diseñado principalmente como una **aplicación web de gestión interna**, por lo que la interfaz busca aprovechar el espacio disponible en computadoras utilizadas en caja, oficina o almacén.

Los diseños presentan una navegación lateral permanente y un área principal destinada a dashboards, tablas, gráficos y operaciones.

- **Diseño Responsivo:**
  - **En Computadora (Desktop):** Se mantiene un menú lateral fijo y el contenido se distribuye utilizando tarjetas, tablas y columnas.
  - **En Tablet:** El contenido puede reducir el número de columnas y reorganizar tarjetas de forma vertical.
  - **En Celular:** Las tarjetas y controles se presentan en una sola columna y el menú lateral puede transformarse en un menú desplegable.

- **Componentes Web:**
  - **Botón Primario:** Fondo azul para acciones principales como “Nuevo producto”, “Registrar operación” o “Lanzar oferta”.
  - **Botón Secundario:** Fondo claro o borde azul para acciones complementarias como editar, ver detalle o cancelar.
  - **Botón de Peligro:** Rojo para acciones relacionadas con eliminación, errores o estados críticos.

- **Tarjetas de Indicadores:**
  - Presentan información resumida como productos totales, stock crítico, productos por vencer y mermas.
  - Incluyen iconos y colores que ayudan a diferenciar cada indicador.
  - Se ubican principalmente en la parte superior de los dashboards.

- **Tablas:**
  - Se utilizan para mostrar productos, lotes, empleados y operaciones.
  - Presentan columnas claramente separadas.
  - Incorporan estados mediante etiquetas de colores como **Activo**, **Crítico**, **Próximo a vencer** o **Vencido**.
  - Pueden incluir buscadores, filtros y paginación.

- **Formularios:**
  - Campos de entrada con bordes simples y etiquetas visibles.
  - Los formularios deben mostrar mensajes claros cuando un dato sea incorrecto.
  - Las acciones de guardar o registrar deben destacar sobre las opciones secundarias.

- **Navegación:**
  - Barra lateral ubicada en el lado izquierdo.
  - Logo de BodeGo ubicado en la parte superior.
  - El módulo seleccionado se diferencia mediante color de fondo o texto destacado.
  - En la parte inferior se muestra información del usuario y la opción para cerrar sesión.

- **Interacción:**
  - Los cambios de estado deben mostrarse inmediatamente después de registrar una operación.
  - Las acciones importantes deben generar mensajes de confirmación.
  - Los elementos interactivos deben cambiar visualmente al pasar el cursor.
  - Los gráficos y tablas deben mantener una lectura sencilla sin sobrecargar la pantalla.

- **Accesibilidad:**
  - Alto contraste entre fondo y texto.
  - Los estados no deben identificarse únicamente mediante colores, sino también mediante texto o iconos.
  - Los botones principales deben tener un tamaño suficiente para ser identificados fácilmente.

---

## 4.2. Information Architecture
### 4.2.1. Organization Systems

La arquitectura de información de BodeGo se organiza mediante sistemas **jerárquicos, secuenciales y matriciales**, permitiendo que cada usuario pueda acceder rápidamente a las funciones correspondientes a su rol.

Los mockups muestran una clara separación entre el Dashboard del Administrador y el Dashboard del Empleado, además de módulos especializados para inventario, vencimientos, alertas, reportes, empleados y configuración.

- **Sistema Jerárquico:**
  - **Dashboard Administrador:** Primero se muestran indicadores generales como productos totales, stock crítico, productos por vencer y mermas. Después se muestran alertas, movimientos, productos vendidos y lotes próximos a vencer.
  - **Dashboard Empleado:** Primero se muestran ingresos, salidas y mermas del día; posteriormente aparecen las operaciones rápidas y el historial diario.
  - **Inventario:** Se muestra primero el catálogo general y posteriormente el detalle de cada producto.
  - **Vencimientos:** Se priorizan primero los productos vencidos o próximos a vencer.

- **Sistema Secuencial:**
  - **Registro de Producto:** Datos generales → categoría → stock → precio → información del lote → guardar.
  - **Registro de Ingreso:** Seleccionar producto → ingresar cantidad → registrar lote → confirmar.
  - **Registro de Salida:** Seleccionar producto → indicar cantidad → confirmar operación.
  - **Registro de Merma:** Seleccionar producto → cantidad → motivo → confirmar registro.
  - **Gestión de Vencimiento:** Identificar producto → revisar días restantes → seleccionar acción → actualizar inventario.

- **Sistema Matricial:**
  - **Inventario:** Producto + categoría + estado.
  - **Vencimientos:** Producto + lote + fecha de vencimiento + estado.
  - **Operaciones:** Tipo de operación + empleado + fecha + producto.
  - **Empleados:** Nombre + rol + turno + estado.
  - **Reportes:** Fecha + categoría + producto + tipo de movimiento.

- **Esquemas de Categorización:**
  - **Por Rol:** Administrador y Empleado.
  - **Por Función:** Dashboard, Inventario, Vencimientos, Alertas, Reportes, Empleados y Configuración.
  - **Por Estado:** Activo, stock bajo, stock crítico, próximo a vencer y vencido.
  - **Cronológico:** Las operaciones y alertas se presentan comenzando por las más recientes.
  - **Por Prioridad:** Los productos con mayor riesgo de vencimiento o falta de stock aparecen primero.

---

### 4.2.2. Labeling Systems

El sistema de etiquetado de BodeGo utiliza palabras breves y relacionadas directamente con las actividades realizadas en un minimarket. El objetivo es que Administradores y Empleados puedan reconocer cada función sin conocimientos técnicos.

## Etiquetas Principales de Navegación

- **Dashboard:** Resumen del estado actual del minimarket.
- **Inventario:** Gestión y consulta de productos y stock.
- **Vencimientos:** Control de productos y lotes próximos a caducar.
- **Alertas:** Notificaciones sobre situaciones que requieren atención.
- **Reportes:** Visualización de métricas e indicadores del negocio.
- **Empleados:** Gestión del personal y permisos.
- **Configuración:** Ajustes generales del sistema.

## Etiquetas de Acciones

- **“Nuevo producto”**: Registra un producto en el inventario.
- **“Registrar ingreso”**: Añade unidades al stock.
- **“Registrar salida”**: Registra productos que salen del inventario.
- **“Registrar merma”**: Registra productos perdidos, dañados o vencidos.
- **“Consultar inventario”**: Permite revisar productos disponibles.
- **“Lanzar oferta”**: Permite aplicar una estrategia de liquidación.
- **“Ver producto”**: Abre información detallada del producto.
- **“Editar”**: Permite modificar información registrada.

## Etiquetas Contextuales

- **Éxito:** “Operación registrada correctamente”.
- **Stock bajo:** “Quedan pocas unidades disponibles”.
- **Stock crítico:** “Producto con stock crítico”.
- **Próximo a vencer:** “Producto próximo a vencer”.
- **Vencido:** “Producto vencido”.
- **Error:** “No se pudo completar la operación. Inténtalo nuevamente”.

---

### 4.2.3. SEO Tags and Meta Tags

En esta sección se definen los principales **SEO Tags y Meta Tags** utilizados en BodeGo, tanto para la **Landing Page** como para las páginas principales de la **Web Application**.

El objetivo es mejorar la identificación del sitio en los motores de búsqueda y mantener una estructura clara en los títulos y descripciones de cada página. En el caso de las secciones internas de la aplicación, se evita su indexación debido a que contienen información privada del minimarket.

### Landing Page

La Landing Page es la página pública principal de BodeGo y está orientada a presentar la solución, sus beneficios y funcionalidades.

| Tag | Valor |
|---|---|
| **Title** | BodeGo \| Gestión de Inventario para Minimarkets |
| **Description** | BodeGo es una plataforma web que ayuda a los minimarkets a controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias. |
| **Keywords** | BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital |
| **Author** | Equipo BodeGo |
| **Robots** | index, follow |
| **Language** | es |
| **Viewport** | width=device-width, initial-scale=1.0 |

**Implementación:**

```html
<title>BodeGo | Gestión de Inventario para Minimarkets</title>

<meta
  name="description"
  content="BodeGo es una plataforma web que ayuda a los minimarkets a controlar su stock, gestionar productos perecibles, reducir mermas y supervisar sus operaciones diarias."
/>

<meta
  name="keywords"
  content="BodeGo, gestión de inventario, minimarket, control de stock, productos perecibles, control de vencimientos, mermas, inventario digital"
/>

<meta name="author" content="Equipo BodeGo" />
<meta name="robots" content="index, follow" />
<meta name="language" content="Spanish" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
```

---

### Web Application

Las páginas internas de BodeGo están orientadas al uso de Administradores y Empleados. Debido a que contienen información operativa y requieren autenticación, no deben ser indexadas por los motores de búsqueda.

| Página | Title | Description | Keywords | Author | Robots |
|---|---|---|---|---|---|
| **Inicio de Sesión** | Iniciar Sesión \| BodeGo | Accede a BodeGo para gestionar el inventario, productos, vencimientos y operaciones de tu minimarket. | BodeGo, iniciar sesión, inventario minimarket, gestión de stock | Equipo BodeGo | noindex, nofollow |
| **Dashboard Administrador** | Dashboard Administrador \| BodeGo | Visualiza el estado general del inventario, alertas, productos por vencer y operaciones del minimarket. | dashboard, BodeGo, inventario, stock, alertas, vencimientos | Equipo BodeGo | noindex, nofollow |
| **Inventario** | Inventario \| BodeGo | Consulta y administra los productos, categorías, stock y estado del inventario del minimarket. | inventario, productos, stock, BodeGo, minimarket | Equipo BodeGo | noindex, nofollow |
| **Vencimientos** | Control de Vencimientos \| BodeGo | Supervisa lotes y productos próximos a vencer para reducir pérdidas y mejorar la rotación del inventario. | vencimientos, productos perecibles, lotes, mermas, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Alertas** | Centro de Alertas \| BodeGo | Revisa alertas relacionadas con stock crítico, productos próximos a vencer y operaciones del minimarket. | alertas, stock crítico, vencimientos, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Reportes** | Reportes y Analítica \| BodeGo | Consulta reportes e indicadores sobre inventario, movimientos, productos y mermas del minimarket. | reportes, analítica, inventario, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Empleados** | Gestión de Empleados \| BodeGo | Administra empleados, roles, permisos y actividad operativa dentro del minimarket. | empleados, roles, permisos, personal, BodeGo | Equipo BodeGo | noindex, nofollow |
| **Dashboard Empleado** | Dashboard Empleado \| BodeGo | Consulta operaciones diarias y accede al registro de ingresos, salidas y mermas del inventario. | empleado, operaciones, inventario, ingresos, salidas, mermas | Equipo BodeGo | noindex, nofollow |
| **Operaciones** | Operaciones de Inventario \| BodeGo | Registra ingresos, salidas y mermas de productos para mantener actualizado el stock del minimarket. | operaciones, ingresos, salidas, mermas, stock, BodeGo | Equipo BodeGo | noindex, nofollow |

---

### Consideraciones de Indexación

La **Landing Page** utiliza:

```html
<meta name="robots" content="index, follow" />
```

Esto permite que los motores de búsqueda puedan encontrar y mostrar BodeGo en los resultados de búsqueda.

Por otro lado, las páginas internas de la **Web Application** utilizan:

```html
<meta name="robots" content="noindex, nofollow" />
```

Esto evita que páginas como Dashboard, Inventario, Empleados, Reportes u Operaciones sean indexadas, ya que contienen información interna y requieren autenticación para acceder.

---

### 4.2.4. Searching Systems

El sistema de búsqueda de BodeGo permite localizar rápidamente productos, lotes, empleados y operaciones, reduciendo el tiempo necesario para revisar grandes cantidades de información.

- **Herramientas de Búsqueda:**
  - **Barra de búsqueda:** Disponible principalmente en Inventario y otras pantallas con grandes cantidades de registros.
  - **Filtro por categoría:** Permite visualizar productos pertenecientes a una categoría determinada.
  - **Filtro por estado:** Permite mostrar productos activos, con stock bajo, críticos o vencidos.
  - **Filtro por fechas:** Utilizado en reportes, operaciones y vencimientos.
  - **Filtro por lote:** Facilita la identificación de productos perecibles.

- **Búsqueda en Inventario:**
  - Código del producto.
  - Nombre.
  - Categoría.
  - Estado.
  - Cantidad disponible.

- **Búsqueda en Vencimientos:**
  - Producto.
  - Número de lote.
  - Fecha de vencimiento.
  - Días restantes.
  - Nivel de prioridad.

- **Visualización de Resultados:**
  - Los resultados se presentan principalmente mediante tablas.
  - Los estados importantes se identifican mediante colores y etiquetas.
  - Los resultados pueden organizarse por prioridad o fecha de vencimiento.
  - Cuando no existan coincidencias se puede mostrar: **“No se encontraron resultados con los filtros seleccionados.”**

---

### 4.2.5. Navigation Systems

El sistema de navegación de BodeGo busca reducir la cantidad de pasos necesarios para acceder a las principales funciones del minimarket. La navegación se adapta de acuerdo con los permisos del Administrador y del Empleado.

## Estructura de Navegación del Administrador

La barra lateral puede incluir:

**Dashboard | Inventario | Vencimientos | Alertas | Reportes | Empleados | Configuración**

El Administrador tiene acceso a funciones de supervisión, análisis y configuración.

## Estructura de Navegación del Empleado

La navegación del Empleado debe concentrarse principalmente en las operaciones necesarias durante su jornada:

**Dashboard | Inventario | Operaciones**

Desde el Dashboard también dispone de accesos rápidos para:

- Registrar ingreso.
- Registrar salida.
- Registrar merma.
- Consultar inventario.

## Técnicas de Navegación

- **Menú lateral:** Permite desplazarse entre módulos sin regresar al inicio.
- **Acciones rápidas:** Permiten realizar las operaciones más frecuentes desde el Dashboard.
- **Breadcrumbs o rutas:** Facilitan regresar desde el detalle de un producto hacia el inventario.
- **Paginación:** Utilizada en tablas con gran cantidad de productos, empleados u operaciones.
- **Filtros:** Permiten reducir el contenido sin cambiar de pantalla.

## Estados de Navegación

- **Cargando:** Se muestran indicadores visuales mientras se obtiene la información.
- **Sin resultados:** Se informa cuando una búsqueda o filtro no tiene coincidencias.
- **Error:** Se muestra un mensaje indicando que no fue posible cargar la información.
- **Operación exitosa:** Se confirma inmediatamente después de registrar un ingreso, salida o merma.
- **Alerta crítica:** Los elementos que necesitan atención inmediata se destacan mediante rojo.
- **Advertencia:** Los productos próximos a vencer o con stock bajo se identifican con amarillo o naranja.

---

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

![WireframeL1](Recursos/images/Landing1.png)
---
![WireframeL2](Recursos/images/Landing2.png)
---
![WireframeL3](Recursos/images/Landing3.png)
---
![WireframeL4](Recursos/images/Landing4.png)
---
![WireframeL5](Recursos/images/Landing5.png)
---

### 4.3.2. Landing Page Mock-ups

![LPMock-Up1](Recursos/images/LandingPage-mockup1.jpg)
---

![LPMock-Up2](Recursos/images/LandingPage-mockup2.jpg)
---

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

![Wireframe 1](Recursos/images/WF1.png)

---

![Wireframe 2](Recursos/images/WF2.png)

---

![Wireframe 3](Recursos/images/WF3.png)

---

![Wireframe 4](Recursos/images/WF4.png)

---

![Wireframe 5](Recursos/images/WF5.png)

---

![Wireframe 6](Recursos/images/WF6.png)

---

![Wireframe 7](Recursos/images/WF7.png)

---

![Wireframe 8](Recursos/images/WF8.png)

---

![Wireframe 9](Recursos/images/WF9.png)

---

![Wireframe 10](Recursos/images/WF10.png)

---

![Wireframe 11](Recursos/images/WF11.png)

---

![Wireframe 12](Recursos/images/WF12.png)

---

![Wireframe 13](Recursos/images/WF13.png)

---

![Wireframe 14](Recursos/images/WF14.png)

---
enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1

### 4.4.2. Web Applications Wireflow Diagrams
![Wireflow 0](Recursos/images/Wireflow_App.png)

---

enlace: https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=9-8766&t=ZKhGhyVBP4tT2C8g-1

---

### 4.4.3. Web Applications Mock-ups
![Mockup App 1](Recursos/images/Mockup-App1.png)

---

![Mockup App 2](Recursos/images/Mockup-App2.png)

---

![Mockup App 3](Recursos/images/Mockup-App3.png)

---

![Mockup App 4](Recursos/images/Mockup-App4.png)

---

![Mockup App 5](Recursos/images/Mockup-App5.png)

---

![Mockup App 6](Recursos/images/Mockup-App6.png)

---

![Mockup App 7](Recursos/images/Mockup-App7.png)

---

![Mockup App 8](Recursos/images/Mockup-App8.png)

---

![Mockup App 9](Recursos/images/Mockup-App9.png)

---

![Mockup App 10](Recursos/images/Mockup-App10.png)

---

![Mockup App 11](Recursos/images/Mockup-App11.png)

---

![Mockup App 12](Recursos/images/Mockup-App12.png)

---

![Mockup App 13](Recursos/images/Mockup-App13.png)

---

![Mockup App 14](Recursos/images/Mockup-App14.png)

---
[Enlace de Figma](https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1)
---

### 4.4.4. Web Applications User Flow Diagrams

## LEYENDA

![Leyenda Flow Diagram](Recursos/images/LEYENDA.jpg)

## FLUJO DE USUARIO

![Flujo de Usuario Flow Diagram](Recursos/images/FLUJO%20DE%20USUARIO.jpg)

## FLUJO DE ADMINISTRADOR

![Flujo de Administrador Flow Diagram](Recursos/images/FLUJO%20DE%20ADMINISTRADOR.jpg)

## FLUJO DE EMPLEADO

![Flujo de Empleado Flow Diagram](Recursos/images/FLUJO%20DE%20EMPLEADO.jpg)

---

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level EventStorming
![Estructura / Captura 1](Recursos/images/es1.png)

---

![Estructura / Captura 2](Recursos/images/es2.png)

---

![Estructura / Captura 3](Recursos/images/es3.png)

---

![Estructura / Captura 4](Recursos/images/es4.png)

---

![Estructura / Captura 5](Recursos/images/es5.png)

---

![Estructura / Captura 6](Recursos/images/es6.png)

---

![Estructura / Captura 7](Recursos/images/es7.png)

---

![Estructura / Captura 8](Recursos/images/es8.png)

---

![Estructura / Captura 9](Recursos/images/es9.png)

---

![Estructura / Captura 9](Recursos/images/es91.png)

---

![Estructura / Captura 9](Recursos/images/es92.png)

---

![Estructura / Captura 9](Recursos/images/es93.png)

---
[Nuestro link del miro](https://miro.com/app/board/uXjVHm55KfI=/)
---

### 4.6.2. Software Architecture Context Diagram
![Context](Recursos/images/SystemContext.png)
### 4.6.3. Software Architecture Container Diagrams
![Container](Recursos/images/Containers.png)

### 4.6.4. Software Architecture Components Diagrams
![Components-Worker](Recursos/images/Components-Worker.png)

---

![Components-API](Recursos/images/Components-API.png)
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
![Class-Diagram](Recursos/images/DiagramaClases.jpg)
## 4.8. Database Design
Se presenta el diseño de la base de datos relacional que permitirá graficar la información para los objetos de cada Bounded Context identificados en la aplicación BodeGo.

### 4.8.1. Database Diagrams
El siguiente diagrama de base de datos Entity-Relationship contiene las tablas, columnas y tipos de datos que establecen las relaciones entre las entidades del sistema.
![Diagrama / Diseño 1](Recursos/images/d1.png)

---

![Diagrama / Diseño 2](Recursos/images/d2.png)

---

![Diagrama / Diseño 3](Recursos/images/d3.png)

---

![Diagrama / Diseño 4](Recursos/images/d4.png)

---

![Diagrama / Diseño 5](Recursos/images/d5.png)

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management
Para el desarrollo de BodeGo se establecerán un conjunto de herramientas que permitan mantener la consistencia del proyecto durante su ciclo de vida. Estas configuraciones permitirán que los integrantes del equipo trabajen bajo una misma estructura para el control de versiones, configuración del entorno de desarrollo y posterior despliegue de la aplicación.

### 5.1.1. Software Development Environment Configuration
## . Project Management

- **Discord:** Una herramienta de comunicación y coordinación del equipo. Permite organizar conversaciones por canales, realizar reuniones de voz, compartir avances, resolver dudas y coordinar las actividades relacionadas con el desarrollo de BodeGo.
---
![Imagen de la entrevista](Recursos/images/dc1.jpg)
---
[link de inicio sesion](https://discord.com/)

---

imagen para mostrar evidencia de uso: 

![imagen](Recursos/images/dc2.jpg)

## . Requirement Management

- **Miro:** Se utilizará como herramienta colaborativa para la gestión y análisis de requisitos de BodeGo. Permitirá organizar visualmente información obtenida durante la investigación, como User Personas, Empathy Maps, User Journey Maps e Impact Mapping.
---
![Imagen de la entrevista](Recursos/images/miro.png)

---

[link de inicio de sesion](https://miro.com/es/)

- **UXPressia:** Se utilizará para elaborar y documentar artefactos relacionados con la experiencia de usuario, como User Personas y User Journey Maps, permitiendo representar las características, necesidades, objetivos y experiencias de los segmentos de usuarios de BodeGo.
---
![Imagen de la entrevista](Recursos/images/ux.png)
---

[link de inicio de sesion](https://uxpressia.com/)

- **Structurizr:** Se utilizará para modelar y documentar la arquitectura de software de BodeGo mediante diagramas basados en el modelo C4. Permitirá representar la estructura general del sistema, sus principales contenedores, componentes y relaciones.
---
![Imagen de la entrevista](Recursos/images/struc.png)
---

## . Product UX/UI Design

- **Figma:** Una herramienta de colaboración que facilita el desarrollo conjunto de wireframes y mockups.
---
![Imagen de la entrevista](Recursos/images/figma.png)
---
[link de inicio de sesion](https://www.figma.com/es-la/)

- **LucidChart:** Una herramienta colaborativa que posibilita la creación conjunta de wireframes flow y mockups flow.
---
![Imagen de la entrevista](Recursos/images/lucid.png)
---
[link de inicio de sesion](https://lucid.co/es/lucidchart)

## . Software Development

- **HTML5:** Es un lenguaje de etiquetado utilizado para crear la estructura de una página web. Se empleará para incluir componentes como texto, imágenes, enlaces, botones y videos.
---
![Imagen de la entrevista](Recursos/images/html.png)
---
[informacion relacionada](https://www.esic.edu/rethink/tecnologia/html5-que-es-caracteristicas-y-como-funciona-c#:~:text=El%20HTML5%20es%20un%20est%C3%A1ndar,%2C%20estilo%20de%20letra%2C%20etc.)

- **CSS:** Es un lenguaje de diseño gráfico utilizado para dar formato y estilo a la presentación de los documentos HTML.
---
![Imagen de la entrevista](Recursos/images/css.png)
---
[informacion relacionada](https://developer.mozilla.org/es/docs/Web/CSS)

- **JavaScript:** Es un lenguaje de programación dinámico orientado a objetos que se utilizará para implementar funcionalidades e interactividad en la aplicación web.
---
![Imagen de la entrevista](Recursos/images/js.png)
---
[informacion relacionada](https://developer.mozilla.org/es/docs/Web/JavaScript)

- **intellJ IDEA** Es un entorno de desarrollo integrado (IDE) diseñado para programar en Java.
---
![Imagen de la entrevista](Recursos/images/intell.jpg)
---
[link de descarga](https://www.jetbrains.com/es-es/idea/download/?section=windows)

## . Software Testing

- **Lenguaje Gherkin:** Es un Lenguaje Específico de Dominio (DSL) diseñado para describir el comportamiento esperado del sistema mediante escenarios comprensibles tanto para desarrolladores como para otros integrantes del equipo.

## . Software Documentation

- **GitHub:** Es una plataforma utilizada para el alojamiento y control de versiones del código fuente de un proyecto. Facilita el trabajo colaborativo entre los integrantes del equipo y permite mantener un historial de los cambios realizados.
---
![Imagen de la entrevista](Recursos/images/gh6.jpgg)
---


## . Software Deployment

- **GitHub Pages:** Es una plataforma que permite realizar despliegues de aplicaciones web directamente desde un repositorio de GitHub.
---
![Imagen de la entrevista](Recursos/images/gh7.png)
---
[link de inicio](https://github.com/?locale=es-419)
---
[link de descarga](https://github.com/apps/desktop?locale=es-419)
---
[Nuestro repositorio de documentación](https://github.com/SirEthan04/Proxy_Open_Source)
---
[Nuestro repositorio de landingpage](https://github.com/SirEthan04/Proxy_Open_Source_LandingPage)
---
[Nuestro repositorio de frontend](https://github.com/SirEthan04/Proxy_Open_Source_Front-end)
---
[Nuestro repositorio de web aplication](https://github.com/SirEthan04/Proxy_Open_Source_Web-Application)
---
### 5.1.2. Source Code Management
---

![Estructura / Captura 9](Recursos/images/gh9.jpg)

---
## GitFlow Implementation
Para organizar el trabajo colaborativo del equipo se utilizará **GitFlow** como modelo de ramificación, empleando Git para el control de versiones.
Este modelo permitirá separar el código estable de BodeGo de las funcionalidades que se encuentren en desarrollo, facilitando que diferentes integrantes del equipo puedan trabajar simultáneamente en módulos como inventario, productos, lotes, mermas, ofertas, usuarios y reportes.

### Main Branch

La rama main será la rama principal y contendrá las versiones estables de BodeGo que se encuentren preparadas para producción.
No se desarrollarán funcionalidades directamente sobre esta rama. Los cambios llegarán a main mediante la integración de ramas release y hotfix.

## Develop Branch

La rama develop contendrá los cambios más recientes del proyecto que serán incluidos en próximas versiones de BodeGo.
Funcionará como punto de integración de las diferentes funcionalidades desarrolladas por el equipo. Antes de que una versión sea incorporada a main, las nuevas características serán integradas y verificadas previamente en develop.

## Feature Branch

Las ramas feature serán utilizadas para desarrollar nuevas funcionalidades de **BodeGo** de forma independiente.
Cada característica deberá contar con su propia rama, permitiendo que los integrantes del equipo trabajen en diferentes módulos sin modificar directamente la rama develop.

## Release Branch

Las ramas release serán utilizadas cuando las funcionalidades previstas para una nueva versión de BodeGo ya hayan sido integradas en develop.
Su objetivo será preparar una versión antes de pasarla a producción. Durante esta etapa podrán realizarse pruebas, ajustes menores y correcciones de errores sin impedir que el equipo continúe desarrollando nuevas características en develop.

## Hotfix Branch

Las ramas hotfix serán utilizadas para corregir errores importantes encontrados en una versión de BodeGo que ya se encuentre en producción.
Estas ramas permitirán solucionar rápidamente un problema sin interrumpir el desarrollo de nuevas funcionalidades que continúe realizándose en develop.

## Support Branch

Para la primera etapa del desarrollo de BodeGo no se utilizarán ramas supoort, debido a que el proyecto no contempla inicialmente el mantenimiento simultáneo de múltiples versiones antiguas del producto.
En caso de que en el futuro BodeGo deba mantener diferentes versiones en producción, podrán incorporarse ramas de soporte específicas.

## Conventional Commits

Para mantener un historial de cambios claro y comprensible, los mensajes de los commits del proyecto BodeGo seguirán la especificación Conventional Commits.

Esta convención permitirá identificar rápidamente el propósito de cada modificación realizada por los integrantes del equipo.¿

La estructura general será: git commit -m <type>[optional scope]: <title>“ -m “<description” 

### Tipos de Conventional Commits
- feat: Incorporación de una nueva funcionalidad.
- fix: Corrección de un error. 
- docs: Cambios en documentación. 
- style: Cambios de formato que no modifican el funcionamiento. 
- refactor: Reestructuración del código sin agregar funcionalidades ni corregir errores. 
- test: Adición o modificación de pruebas. 
- chore: Tareas de mantenimiento o configuración. 
- perf: Mejoras relacionadas con el rendimiento. 

### 5.1.3. Source Code Style Guide & Conventions
Como norma general, todo el código desarrollado para BodeGo deberá utilizar nombres en inglés. Esto incluye variables, funciones, métodos, clases, archivos, atributos y demás elementos utilizados durante el desarrollo.

La finalidad de estas reglas es mantener un código ordenado y fácil de entender para todos los integrantes del equipo.

---

HTML

Use Lowercase Element Names

Los elementos HTML se escribirán en minúsculas.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Close All HTML Elements

Todos los elementos HTML que necesiten una etiqueta de cierre deberán cerrarse correctamente.

```html
<section>
    <h2>Inventory</h2>
    <p>Available products</p>
</section>
```

Use Lowercase Attribute Names

Los atributos HTML también se escribirán en minúsculas.

```html
<a href="/inventory">View inventory</a>
```

Use Alternative Text for Images

Las imágenes utilizadas en BodeGo deberán incluir el atributo alt para indicar brevemente su contenido.

```html
<img
    src="assets/bodego-logo.png"
    alt="BodeGo logo">
```

Use Semantic HTML Elements

Cuando sea posible, se utilizarán etiquetas semánticas para organizar mejor las páginas.
Algunas de las etiquetas que se utilizarán son:

```text
header
nav
main
section
article
footer
```

Spaces and Equal Signs

No se utilizarán espacios innecesarios alrededor del signo igual en los atributos.

Correcto:

```html
<link rel="stylesheet" href="styles.css">
```

Incorrecto:

```html
<link rel = "stylesheet" href = "styles.css">
```


CSS

ID and Class Naming

Las clases e identificadores CSS deberán utilizar nombres claros y relacionados con el elemento que representan.

```css
#inventory {
}

#dashboard {
}

.product-card {
}

.stock-alert {
}
```
Se evitarán nombres poco descriptivos como:

```css
.box1 {
}

.element2 {
}
```

ID and Class Name Style

Para los nombres de clases e identificadores CSS se utilizará kebab-case.

```css
.product-card {
}

.inventory-table {
}

.stock-alert {
}
```

Shorthand Properties

Cuando sea posible, se utilizarán propiedades abreviadas para evitar código innecesario.

En lugar de:

```css
.product-card {
    margin-top: 16px;
    margin-right: 16px;
    margin-bottom: 16px;
    margin-left: 16px;
}
```

Se utilizará:

```css
.product-card {
    margin: 16px;
}
```

Declaration Order

Las propiedades CSS deberán mantenerse ordenadas para facilitar la lectura del código.

```css
.product-card {
    background: white;
    border: 1px solid #e5e7eb;
    border-radius: 8px;
    display: flex;
    margin: 16px;
    padding: 16px;
    text-align: left;
}
```

JavaScript

Use Expanded Syntax

El código JavaScript deberá escribirse de manera clara y ordenada, colocando cada instrucción en una línea diferente cuando sea necesario.

```javascript
function calculateAvailableStock() {
    console.log("Calculating available stock");
}
```
Variable Naming

Las variables utilizarán camelCase y deberán tener nombres descriptivos en inglés.

```javascript
let availableStock = 20;
let productName = "Milk";
let expirationDate = "2026-10-20";
let criticalStockThreshold = 5;
```

Se evitarán nombres poco claros como:

```javascript
let x;
let data1;
let thing;
```

Declaring Variables

Se utilizará const cuando el valor no necesite cambiar.

```javascript
const productId = 10;
const productName = "Milk";
```

Se utilizará let cuando el valor pueda modificarse.

```javascript
let availableStock = 20;

availableStock = availableStock - 1;
```

Function Naming

Las funciones utilizarán camelCase y sus nombres deberán indicar claramente la acción que realizan.

Ejemplos:

```javascript
function registerProduct() {
}
```

```javascript
function calculateStock() {
}
```

```javascript
function showExpirationAlert() {
}
```

Constants

Las constantes globales podrán utilizar UPPER_SNAKE_CASE.

Ejemplos:

```javascript
const MAX_LOGIN_ATTEMPTS = 5;
const DEFAULT_STOCK_THRESHOLD = 10;
```
Java

PascalCase

Las clases utilizarán PascalCase.

```java
public class ProductService {
}
```

```java
public class InventoryService {
}
```

```java
public class BatchService {
}
```

---

camelCase

Los métodos, variables locales, parámetros y atributos utilizarán camelCase.

```java
private int productId;
private String productName;
```
---
Clear Comments

Los comentarios se utilizarán cuando ayuden a entender partes del código que los demas integrantes del grupo no comprendan.

```java
// Checks whether the batch is close to its expiration date.
public boolean isNearExpiration(LocalDate expirationDate) {
    return expirationDate.isBefore(LocalDate.now().plusDays(7));
}
```

---

Single Responsibility

Cada clase deberá encargarse principalmente de una responsabilidad.

- ProductService se encargará de las operaciones relacionadas con productos.
- InventoryService se encargará de las operaciones relacionadas con inventario.
- BatchService se encargará de la gestión de lotes.
- WastageService se encargará del registro y gestión de mermas.

Gherkin

Los escenarios y criterios de aceptación de BodeGo deberán seguir una estructura uniforme y utilizar nombres en inglés.

escriptive and Concise Titles for Scenarios

Los escenarios deberán tener títulos claros que permitan entender rápidamente qué comportamiento se está evaluando.

```gherkin
Feature: User authentication

Scenario: Successful login
    Given the user has an active account
    When the user enters valid credentials
    Then the system should grant access according to the user role
```

Follow the Given-When-Then Structure Consistently

Los escenarios deberán utilizar la estructura Given, When y Then.

- Given: representa la condición inicial.
- When: representa la acción realizada.
- Then: representa el resultado esperado.


Focus on Business-Readable Language

Los escenarios deberán utilizar un lenguaje relacionado con las actividades del minimarket y evitar detalles técnicos de programación.

```gherkin
Scenario: Register damaged product as wastage

    Given the employee finds a damaged product
    When the employee registers the product as wastage
    Then the stock should be updated
    And the wastage should be recorded
```
Add Comments When Necessary

Se podrán agregar comentarios cuando sea necesario explicar el propósito de un escenario.

```gherkin
# This scenario checks the registration of expired products as wastage.

Scenario: Register expired product as wastage

    Given a product batch has expired
    When the employee registers the expired units
    Then the units should be recorded as wastage
    And the stock should be updated
```

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
## Sprint 1 - Desarrollo de la Landing Page de BodeGo
Durante el Sprint 1, el equipo se enfocó en desarrollar la primera versión funcional de la Landing Page de BodeGo.
El objetivo fue transformar los wireframes y diseños realizados previamente en una página web funcional que permitiera presentar de manera clara la solución propuesta para los minimarkets.

#### 5.2.1.1. Sprint Planning 1

El print Planning permitió organizar las actividades que serían desarrolladas durante el Sprint 1.
En esta reunión se definió como objetivo principal implementar la Landing Page de BodeGo.
| Sprint # | Sprint 1 |
|---|---|
| **Sprint Planning Background** | El Sprint tiene como objetivo desarrollar la primera versión funcional de la Landing Page de BodeGo. |
| **Date** | 2026-09-17 |
| **Time** | 5:00 pm |
| **Location** | Discord |
| **Prepared By** | Equipo de desarrollo BodeGo |
| **Attendees (to planning meeting)** | Day / Mateo / Yorch / Johan / Guior |
| **Sprint 0 Review Summary** | No existe sprint previo |
| **Sprint 0 Retrospective Summary** | No existe sprint previo |
| **Sprint Goal & User Stories** | |
| **Sprint 1 Goal** | Crear una Landing Page funcional para BodeGo que permita mostrar la información principal del producto, sus beneficios, funcionalidades y facilitar el contacto con potenciales usuarios mediante una interfaz clara y responsive. |
| **Sprint 1 Velocity** | 29 Story Points |
| **Sum of Story Points** | 29 Story Points |

#### 5.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1 se identificaron los principales aspectos de trabajo necesarios para implementar la Landing Page de BodeGo.

| Team Member (Last Name, First Name) | GitHub Username | Landing Page Structure & Navigation | Product Benefits & Impact | Product Features & Explanation | Contact & Footer Section | Responsive Design |
|---|---|---|---|---|---|---|
| Dany Chavez | Danysss-cmd | L | C | C | - | C |
| Mateo Caldas | Ethan.Matt | C | L | C | - | C |
| Yorch Blanco | Bleim-154 | C | C | L | - | C |
| Johan Saravia | yowuan | - | C | C | L | C |
| Giordano Trejo | igogriogriorgiori | C | C | C | C | L |

#### 5.2.1.3. Sprint Backlog 1

Durante el Sprint 1, las actividades estuvieron orientadas al desarrollo de la primera versión funcional de la Landing Page de BodeGo.

El objetivo principal fue transformar los wireframes y mockups previamente diseñados en una interfaz web funcional que permita comunicar la propuesta de valor del producto, presentar sus principales funcionalidades y captar potenciales usuarios interesados en la solución.

![Evidencia Sprint Backlog n1](https://github.com/SirEthan04/Proxy_Open_Source/blob/main/Recursos/images/EvidenciaSprintBacklog%20N1.jpg)
Enlace: https://trello.com/invite/b/6aac64ebaf51e9bfb4c107de/ATTI7980c4d39c19509f8439a763ed2f3081F674FEDD/bodego

---

| **User Story ID** | **Story Title** | **Task ID** | **Task Title** | **Description** | **Estimation (Hours)** | **Assigned To** | **Status** |
| --- | --- | --- | --- | --- | ---: | --- | --- |
| US01 | Visualización del Hero Principal | TSK001 | Create Landing Page structure | Crear la estructura inicial de la Landing Page basada en los wireframes definidos, configurando componentes, archivos y estilos generales. | 2 | Dany | Hecho |
| US01 | Visualización del Hero Principal | TSK002 | Implement navigation bar | Implementar la barra de navegación superior incluyendo logo de BodeGo, enlaces principales y botón de acción. | 2 | Dany | Hecho |
| US01 | Visualización del Hero Principal | TSK003 | Implement hero section | Desarrollar la sección principal con título, descripción de valor, imagen representativa y CTA orientado a captar usuarios interesados. | 3 | Dany | Hecho |
| US02 | Visualización de Beneficios del Producto | TSK004 | Implement benefits section | Implementar la sección de beneficios destacando el control de inventario, reducción de mermas y mejora de procesos operativos. | 4 | Mateo | Hecho |
| US03 | Presentación de Funcionalidades Principales | TSK005 | Implement solutions section | Implementar la sección de soluciones mostrando las principales capacidades de BodeGo como inventario, alertas, reportes y control operativo. | 3 | Yorch | Hecho |
| US04 | Explicación del Funcionamiento de BodeGo | TSK006 | Implement how it works section | Desarrollar la sección donde se explica el flujo general de funcionamiento de BodeGo y la interacción entre Administrador y Empleado. | 3 | Yorch | Hecho |
| US02 | Visualización de Beneficios del Producto | TSK007 | Implement impact section | Implementar la sección de impacto mostrando los beneficios esperados de utilizar BodeGo dentro del negocio. | 2 | Mateo | Hecho |
| US05 | Formulario de Contacto Comercial | TSK008 | Implement contact section | Implementar el formulario de contacto para que potenciales clientes puedan solicitar información sobre BodeGo. | 3 | Johan | Hecho |
| US03 | Presentación de Funcionalidades Principales | TSK009 | Implement footer section | Implementar el footer con información general del producto, enlaces y datos de contacto. | 2 | Guiordano | Hecho |
| US01 - US05 | Landing Page | TSK010 | Implement responsive design | Adaptar la Landing Page para dispositivos móviles, tablets y escritorio manteniendo la correcta visualización del diseño. | 5 | Giordano | Hecho |

#### 5.2.1.4. Development Evidence for Sprint Review
---

| Repository              | Branch                    | Commit ID | Commit Message                          | Commit Message Body                                                            | Committed on |
| ----------------------- | ------------------------- | --------- | --------------------------------------- | ------------------------------------------------------------------------------ | ------------ |
| Danysss-cmd/Landing Page Repository | feature/hero-section      | 371ee21   | feat: improve hero section design       | Implementación y mejora del diseño de la sección principal de la Landing Page. | 17/09/2026   |
| SirEthan04/Landing Page Repository | feature/value-proposition | fa49632   | feat: improve value proposition section | Desarrollo de la sección de beneficios y propuesta de valor del producto.      | 17/09/2026   |
| Bleim-154/Landing Page Repository | feature/solutions-section | 003f372   | feat: improve solutions section         | Implementación de la sección de soluciones y funcionalidades principales.      | 17/09/2026   |
| SirEthan04//Landing Page Repository | feature/impact-section    | 7182b63   | feat: improve impact section            | Desarrollo de la sección de impacto mostrando beneficios del producto.         | 17/09/2026   |
| yowuan/Landing Page Repository | feature/contact-form      | e281064   | feat: improve contact form              | Implementación del formulario de contacto comercial.                           | 17/09/2026   |
| giorgiorgiorgior/Landing Page Repository | feature/footer            | dfb92c0   | feat: improve footer section            | Implementación del footer con información general y enlaces.                   | 17/09/2026   |


---
#### 5.2.1.5. Execution Evidence for Sprint Review
---

![Estructura / Captura 9](Recursos/images/lpd1.jpg)

---
---

![Estructura / Captura 9](Recursos/images/lpd2.jpg)

---
---

![Estructura / Captura 9](Recursos/images/lpd3.jpg)

---
---

![Estructura / Captura 9](Recursos/images/lpd4.jpg)

---
---

[Landing Page Desplegada](https://sirethan04.github.io/Proxy_Open_Source_LandingPage/)

---

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
Se ha omitido la sección de la aplicación web debido a que solo se ha desarrollado la Landing Page. Se ofrecerá más información sobre la aplicación en
una etapa posterior del desarrollo.

#### 5.2.1.8. Team Collaboration Insights during Sprint
---

![Estructura / Captura 9](Recursos/images/gh8.png)

---
## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas

## 5.4. Video About-the-Product

---

# Conclusiones

## Conclusiones y recomendaciones
El proyecto BodeGo busca solucionar el problema de la falta de control y organización del inventario en los minimarkets, especialmente en la gestión de productos perecibles, diferencias de stock y pérdidas ocasionadas por vencimientos. A través de una plataforma web de gestión, se permite que los Administradores y Empleados puedan realizar sus actividades de manera más ordenada, rápida y eficiente.

Las validaciones realizadas permitieron confirmar que los usuarios presentan dificultades al utilizar métodos manuales como cuadernos, archivos de Excel o revisiones físicas constantes. Por ello, funcionalidades como el control de inventario, alertas de vencimiento, reportes y gestión de roles representan una solución alineada con las necesidades identificadas durante el proceso de investigación.

La aplicación busca ofrecer una experiencia sencilla e intuitiva, enfocándose en reducir el tiempo empleado en tareas operativas y mejorar la toma de decisiones dentro del minimarket. Entre sus principales características destacan:

- Control actualizado del inventario.
- Alertas sobre productos próximos a vencer.
- Reportes para conocer el estado del negocio.
- Gestión de usuarios según sus responsabilidades.

Estas funcionalidades están diseñadas para disminuir los errores en el registro de productos, evitar pérdidas innecesarias y brindar mayor visibilidad sobre el estado real del inventario. De esta manera, BodeGo permite que los Administradores puedan tomar decisiones más oportunas y que los Empleados puedan realizar sus tareas de forma rápida y organizada.

---

# Video About-the-Team

---

# Bibliografía

---

# Anexos
---
[Enlace de Figma](https://www.figma.com/design/lkkyQ42TCu70ZypY4hiuMi/Figma-Proxy?node-id=4-2&t=ZKhGhyVBP4tT2C8g-1)
---
[Nuestro link del miro](https://miro.com/app/board/uXjVHm55KfI=/)
---
[Nuestro repositorio de documentación](https://github.com/SirEthan04/Proxy_Open_Source)
---
[Nuestro repositorio de landingpage](https://github.com/SirEthan04/Proxy_Open_Source_LandingPage)
---
[Nuestro repositorio de frontend](https://github.com/SirEthan04/Proxy_Open_Source_Front-end)
---
[Nuestro repositorio de web aplication](https://github.com/SirEthan04/Proxy_Open_Source_Web-Application)
---
