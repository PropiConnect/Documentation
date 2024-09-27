# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software</strong><br>
    <strong>Desarrollo de Aplicaciones Open Source - SV51</strong><br>
    <strong>Profesor: Hugo Allan Mori Paiva</strong><br>
    <br>INFORME TRABAJO FINAL
</p>

<center>

#### Startup: **PropiConnect**
#### Product: **InmoShare**

</center>

### <center>Team  Members:</center>
<center>


| Member                           | Code       |
|----------------------------------|------------|
|Antayhua Castillo Oscar Josué     | U20191E414 |
|Del Castillo Bueno Daniel Mateo   | U202211212 |
|Poma Espinoza Gustavo Arturo      | U20221C138 |
|Sanchez Montero Carlos            | U202015274 |
|Ruiz Huisa Daniel Elias           | U202210764 |


<br> AGOSTO 2024
</center> 


# Registro de Versiones del Informe
<center>

| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 25/08/2024 |Grupo 1 |Se crea el documento |  
| 1.0 | 01/09/2024 |Daniel Del Castillo|Finaliza el capitulo I|
| 1.1 | 02/09/2024 | Carlos Sanchez | Finaliza el Capitulo II|
| 1.2 | 05/09/2024 | Daniel Ruiz y Oscar Antayhua | Finaliza el capitulo IV|
| 1.3 | 07/09/2024 | Gustavo Poma| Finaliza el Capitulo III|
| 1.4 | 07/09/2024 | Gustavo Poma| Finaliza el Capitulo V|
| 1.5| 27/09/2024| Daniel Del Castillo |Sprint II|

</center>

# Project Report Collaboration Insights
[URL del repositorio](https://github.com/PropiConnect)

TB1:
<img src="./assets/Insights/Captura de pantalla 2024-09-27 011626.png" alt="">
TP:
<img src="./assets/Insights/Captura de pantalla 2024-09-27 011554.png" alt="">



# Contenido



[Registro de Versiones del Informe](#registro-de-versiones-del-informe)

[Project Report Collaboration Insights](#project-report-collaboration-insights)

[Student Outcome](#student-outcome)

[Capítulo I: Introducción](#capítulo-i-introducción)

[1.1 Startup Profile](#11-startup-profile)  
[1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)  
[1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  

[1.2. Solution Profile](#12-solution-profile)  
[1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
[1.2.2 Lean UX Process.](#122-lean-ux-process)  
[1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)  
[1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)  
[1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)  
[1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)  

[1.3. Segmentos objetivo.](#13-segmentos-objetivo)  

[Capítulo II: Requirements Elicitation & Analysi](#capítulo-ii-requirements-elicitation--analysis)  

[2.1. Competidores](#21-competidores)  
[2.1.1. Análisis competitivo](#211-análisis-competitivo)  
[2.1.2. Estrategias y tácticas frente a competidores](#211-análisis-competitivo)  

[2.2. Entrevistas](#22-entrevistas)  
[2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)  
[2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)  
[2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)  

[2.3. Needfinding](#23-needfinding)  
[2.3.1. User Personas](#231-user-personas)  
[2.3.2. User Task Matrix](#232-user-task-matrix)  
[2.3.3. User Journey Mapping](#233-user-journey-mapping)  
[2.3.4. Empathy Mapping](#234-empathy-mapping)  
[2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping) 

[2.4. Ubiquitous Language](#24-ubiquitous-language)  

[Capítulo III: Requirements Specificatio](#capítulo-iii-requirements-specification)  

[3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)    
[3.2. User Stories](#32-user-stories)  
[3.3. Impact Mapping](#33-impact-mapping)  
[3.4. Product Backlog](#34-product-backlog)  

[Capítulo IV: Product Desig](#capítulo-iv-product-design)  

[4.1. Style Guidelines](#41-style-guidelines)  
[4.1.1. General Style Guidelines](#411-general-style-guidelines)  
[4.1.2. Web Style Guidelines](#412-web-style-guidelines)  

[4.2. Information Architecture](#42-information-architecture)  
[4.2.1. Organization Systems](#421-organization-systems)  
[4.2.2. Labeling Systems](#422-labeling-systems)  
[4.2.3. SEO Tags and Meta Tag](#423-seo-tags-and-meta-tags)  
[4.2.4. Searching Systems](#424-searching-systems)   
[4.2.5. Navigation Systems](#425-navigation-systems)  

[4.3. Landing Page UI Design](#43-landing-page-ui-design)   
[4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)  
[4.3.2. Landing Page Mock-up](#432-landing-page-mock-up) 

[4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)  
[4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)  
[4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)  
[4.4.2. Web Applications Mock-ups](#442-web-applications-mock-ups)   
[4.4.3. Web Applications User Flow Diagrams](#443-web-applications-user-flow-diagrams)  

[4.5. Web Applications Prototyping](#45-web-applications-prototyping)  

[4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)  
[4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)  
[4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)  
[4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)  

[4.7. Software Object-Oriented Design](#47-software-object-oriented-design)  
[4.7.1. Class Diagrams](#471-class-diagrams)  
[4.7.2. Class Dictionary](#472-class-dictionary)  

[4.8. Database Design](#48-database-design)  
[4.8.1. Database Diagram](#481-database-diagram)  

[Capítulo V: Product Implementation, Validation & Deploymen](#capítulo-v-product-implementation-validation--deployment)  

[5.1. Software Configuration Management](#51-software-configuration-management)  
[5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)  
[5.1.2. Source Code Management](#512-source-code-management)  
[5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
[5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)  

[5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)  
[5.2.X. Sprint ](#52x-sprint-n)  
[5.2.X.1. Sprint Planning n](#52x1-sprint-planning-n)  
[5.2.X.2. Sprint Backlog n](#52x2-sprint-backlog-n)  
[5.2.X.3. Development Evidence for Sprint Review](#52x3-development-evidence-for-sprint-review)  
[5.2.X.4. Testing Suite Evidence for Sprint Review](#52x4-testing-suite-evidence-for-sprint-review)  
[5.2.X.5. Execution Evidence for Sprint Review](#52x5-execution-evidence-for-sprint-review)  
[5.2.X.6. Services Documentation Evidence for Sprint Review](#52x6-services-documentation-evidence-for-sprint-review)  
[5.2.X.7. Software Deployment Evidence for Sprint Review](#52x7-software-deployment-evidence-for-sprint-review)  
[5.2.X.8. Team Collaboration Insights during Sprint](#52x8-team-collaboration-insights-during-sprint)  

[5.3. Validation Interviews](#53-validation-interviews)  
[5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)  
[5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)  
[5.3.3. Evaluaciones según heurísticas](#533-evaluaciones-según-heurísticas)  

[5.4. Video About-the-Product](#54-video-about-the-product)  

[Conclusiones](#conclusiones)  
[Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
[Video About-the-Team](#video-about-the-team)  
[Bibliografía](#bibliografía)  
[Anexos](#anexos)  

# Student Outcome


| **Criterio Específico**                                                     | **Acciones Realizadas por los Integrantes**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | **Conclusiones**                                                                                                                                                                                                 |
| --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia**     | **Gustavo Arturo Poma Espinoza(TB1):** Durante las reuniones de equipo, Gustavo se encargó de presentar los avances en la definición de escenarios de usuario y la planificación del backlog. Adaptó su comunicación tanto para el equipo técnico como para los stakeholders no técnicos, logrando transmitir de manera efectiva los puntos clave del proyecto.<br><br> **Gustavo Arturo Poma Espinoza(TP):** Durante las reuniones de equipo, Gustavo presentó el flujo de autenticación de usuarios, explicando con claridad el funcionamiento de la ventana de login y registro, y cómo se recuperan los datos del usuario a través de su ID. Su comunicación fue efectiva tanto para el equipo técnico, detallando aspectos clave como la validación de credenciales y manejo de sesiones, como para stakeholders no técnicos, asegurando que comprendieran cómo estos procesos mejorarían la experiencia de usuario y la seguridad de la plataforma. <br><br> **Daniel Del Castillo(TB1):** Daniel lideró la metodología Lean UX, organizando presentaciones para guiar al equipo en la orientación del producto hacia la experiencia de usuario, logrando explicar con claridad los conceptos clave a audiencias técnicas y no técnicas. <br><br> **Oscar Antayhua(TB1):** Oscar presentó sus avances en el desarrollo de los mockups y wireframes, explicando cómo estos se alineaban con las necesidades de los usuarios finales. Durante las reuniones, comunicó con claridad cómo las interfaces diseñadas facilitarían la experiencia de usuario. <br><br> **Carlos Sanchez(TB1):** Carlos realizó presentaciones sobre los análisis de competidores, el journey mapping y los user personas, explicando de forma clara los hallazgos y cómo estos impactaban en la dirección del proyecto. <br><br> **Daniel Ruiz(TB1):** Durante la presentación de los diagramas de contexto y la propuesta de estilo de diseño, Daniel utilizó un lenguaje claro y técnico para explicar las decisiones que impactarían el desarrollo del producto. | Los integrantes del equipo lograron comunicar de manera efectiva sus ideas, ajustando su discurso según la audiencia. Esto facilitó una mayor comprensión de las necesidades y avances del proyecto entre los diferentes involucrados. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia**   | **Gustavo Arturo Poma Espinoza(TB1):** Gustavo elaboró la documentación de los escenarios de usuario y el backlog, utilizando un lenguaje claro y estructurado. Presentó los criterios de aceptación de forma comprensible tanto para desarrolladores como para stakeholders no técnicos. <br><br> **Gustavo Arturo Poma Espinoza(TP):** Gustavo elaboró la documentación técnica del módulo de autenticación, detallando los endpoints utilizados para el login, registro y recuperación de datos del usuario. Redactó las instrucciones de implementación y prueba de manera clara y estructurada, facilitando la comprensión tanto para los desarrolladores, como para los testers. Además, presentó un resumen de alto nivel para los stakeholders no técnicos, describiendo los beneficios y mejoras que este módulo aportaría a la plataforma en términos de seguridad y usabilidad. <br><br> **Daniel Del Castillo(TB1):** Daniel fue responsable de documentar el proceso Lean UX, asegurándose de que los conceptos y resultados fueran comprensibles para todos los miembros del equipo, y redactando hipótesis y outcomes de manera clara. <br><br> **Oscar Antayhua(TB1):** Oscar documentó los mockups, wireframes y diagramas de flujo de usuario, presentando de manera visual y escrita cómo la interfaz reflejaría las necesidades del usuario final. <br><br> **Carlos Sanchez(TB1):** Carlos redactó informes sobre el análisis de competidores, journey mapping y user personas, cuidando que fueran claros y accesibles para todos los integrantes del equipo, independientemente de su nivel técnico. <br><br> **Daniel Ruiz(TB1):** Daniel fue responsable de la documentación de los diagramas de contexto y las bases de datos, asegurándose de que los desarrolladores y diseñadores comprendieran su estructura.                           | La comunicación escrita de los integrantes fue clara y adecuada para diferentes audiencias, permitiendo que tanto miembros técnicos como no técnicos del equipo comprendieran los avances del proyecto y los requerimientos.                         |



# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup

Dentro del constante cambio del mercado inmobiliario, con propietarios presentando dificultades para conseguir ganancias y personas interesadas en la adquisión de inmuebles siendo sofocados por pésimas opciones de vivienda, surge una necesidad de establecer un vinculo adecuado para concretar esta transacción. 

PropiConnect es una startup diseñada para ser el nexo entre nuestros usuarios, vimos en esta problematica una oportunidad de negocio en la que podemos beneficiar exponencialmente a nuestros usuarios mediante la creación de aplicaciones web dedicadas a conectar nuestro público para que puedan concretar contratos de arrendamiento o venta de propiedades. Nuestra empresa dedicará alma y cuerpo para brindar herramientas utiles para nuestros clientes

**Misión:**

Empoderar a propietarios y compradores mediante una plataforma intuitiva y accesible que facilite la compra, venta y alquiler de inmuebles, al tiempo que fomente la inversión colectiva en bienes raíces. Buscamos simplificar el proceso inmobiliario, ofreciendo herramientas avanzadas y oportunidades de inversión para una experiencia inmobiliaria más equitativa y eficiente.

**Visión:**

Convertirnos en la plataforma líder en el mercado inmobiliario, reconocida por nuestra capacidad para conectar eficientemente a propietarios y compradores, revolucionando la forma en que se gestionan y se invierte en propiedades. Aspiramos a democratizar el acceso al mercado inmobiliario y a proporcionar una solución integral que impulse la transparencia, la colaboración y el éxito en el sector."



#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
|Daniel Mateo del Castillo Bueno ![Teocchiii](./assets/Chap-I/Foto-u202211212.png) | u202211212 | Ingenieria de Software | SQL, Angular, Redis, Python, SpringBoot, React, Arduino |
|Oscar Josué Antayhua Castillo 	![Oscar](./assets/Chap-I/Oscar.png)|U20191e414|Ingenieria de software|C++, python, Arduino, SQL |
|Gustavo Arturo Poma Espinoza 	![image](https://github.com/user-attachments/assets/1cbdef43-4d88-4454-b559-9e3621dac534)|U20221C138|Ingenieria de software|C++, piton , Java, Angular, SprintBoot, MySql, Mongodb, .Net|
|Carlos Sanchez Montero 	![carlos](./assets/Chap-I/carlos.jpg)|U202015274|Ingenieria de software|C++, C , JavaScript, SQL, Python .etc|
|Daniel Elias Ruiz Huisa ![Daniel](./assets/Chap-I/Daniel.jpg)|U202210764|Ingenieria de software|C++, Python, SQL|

## 1.2. Solution Profile
### 1.2.1 Antecedentes y problemática
**Antecedentes**

El proceso de compra, venta y alquiler de propiedades suele ser complejo, el volumen de procesos burocráticos obligatorios para conseguir un inmueble es preoupante. La falta de transparencia puede llevar a posibles compradores o arrendados a ser estafados con una vivienda que no existe o está en litigio.

Este sector cuenta tecnología para comprar y vender propiedades, sin embargo ninguno de estos productos brinda una solución integral, por lo que el mercado está abierto a nuevas propuestas de solución de software.


**Problematica**

La necesidad de simplificar el proceso inmobiliario y ofrecer mayores oportunidades de inversión es evidente. La falta de herramientas integradas y transparentes genera una gestión fragmentada y procesos ineficaces que afectan la experiencia del usuario y limitan el acceso a oportunidades de inversión para muchos. Esta situación no solo resulta en una experiencia frustrante para los usuarios, sino que también perpetúa desigualdades en el acceso a la inversión inmobiliaria. La plataforma InmoShare aborda directamente estos desafíos al proporcionar una solución integral que facilita la compra, venta y alquiler de propiedades, al tiempo que ofrece oportunidades de inversión colectiva, democratizando el acceso al mercado inmobiliario y mejorando la eficiencia del proceso.

A continuación utilizaremos el método de "5W 2H" para delimitar las funciones y rango de funciones

 ***What?*** 

 ¿Qué aspectos del proceso de compra y venta de 
 inmuebles buscan mejorar con su solución?

  - La compra y arrendamiento de una propiedad
  - La venta y alquiler de una propiedad

  ***Why?***

 ¿Por qúe es importante una solución como la nuestra en el contexto inmobiliario?

  - Es importante una solución integral como la nuestra, ya que además de la confiabilidad de los usuarios inscritos, las funcionalidades de las demás aplicaciones del mercado acaban antes de que te reunas con el dueño del inmueble. Esto será diferente en nuestro producto debido a que acompañaremos a los usuarios durante más etapas del proceso.

  ***Who?***
  
 ¿Quienes serán nuestros clientes?

  - Interesados en una vivienda (compra o venta).
  - Vendedores o arrendadores de una vivienda

  ***Where?***

 ¿Dónde se implementará nuestra solución para abordar la problemática?

  - Comenzaremos implementando en todo Lima metropolitana.

  ***When?***

 ¿Cúando implementaremos nuestra solución?
  - Tan pronto como el mercado inmobiliario decida que necesitan una alternativa nueva a las soluciones que tienen

 
  ***How?***
 ¿Cómo beneficiamos a los usuarios con nuestra solución?

  - Mediante la implementación de herramientas de publicación y gestión de propiedades, búsqueda y filtros avanzados. Estas herramientas especificas unidas en una sola aplicación web resultarán en una solución integral que evitará que los usuarios se encuentren afectados

  ***How Much?***
 ¿Cuanto costará la aplicación?
  - Obtendremos recursos mediante una suscripción "Pro" y "Enterprise" ambas opciones cuentan con funcionalidades completas, sin embargo la suscripción de enterprise contará con enfoque de valoración de mercado y generación de reportes del mismo

  
 

### 1.2.2 Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.

El estado actual del sector de compra y venta de inmuebles se ha centrado principalmente en el manejo de propiedades de manera superficial, de ese modo permitiendo riesgos de estafa por ambas partes.

Los productos que se encuentran en el mercado no logran solucionar esta problematica, solo limitan la interacción de los usuarios.

Nuestro producto abordará este problema mediante una solución, una aplicación web, que permite a los usuarios llevar un mejor manejo de las propiedades de las que son responsables.

Nuestro enfoque inicial serán los dueños de inmuebles y sus clientes potenciales ya sean arrendadores o compradores.

Sabremos que tenemos éxito cuando veamos un aumento en el número de propiedades contactadas, además de un incremento en los usuarios que partician en las oportunidades de inversión colectiva.

#### 1.2.2.2. Lean UX Assumptions.

***Business Assumptions***

  1. Creo que mis clientes necesitan mayor soporte para que puedan desarrollar su proceso de compra/venta de inmuebles de manera más sencilla.
  2. Estas necesidades puedens er satisfechas con una aplicación web, que ofreza una automatización de pedidos
  3. Nuestros clientes iniciales serán vendedores y compradores de inmuebles
  4. El aspecto más importante que se buscará en mi producto, es la gestión de inmuebles y de inquilinos
  5. Nuestro método de generación de recursos será mediante suscripciones con dos planes.
  6. El cliente podrá adquirir beneficios adicionales con la mejora de su suscripción
  7. Voy a conseguir mis clientes mediante publicidad dirigida. 
  8. La competencia en el mercado serán aplicaciones de compra y venta de inmuebles.
  9. Nos destacaremos entre la competencia por nuestra solución moderna, robusta, completa y enfocada en las necesidades de nuestros clientes.
  10. Nuestro mayor riesgo es ser desestimado por la similitud superficial con respecto a otras soluciones del mercado.
  11. Solucionaremos el riesgo mediante la diferenciación del producto. 

***User Assumptions***

  12. Nuestros usuarios serán principalmente dueños de inmuebles que busquen obtener recursos a través de venta o alquiler de estos, además de los posibles inquilinos de los mismos. 
  13. Nuestro producto aborda la necesidad de ambos de nuestros usuarios, por llegar a un acuerdo, mediante nuestra aplicación brindaremos ese vinculo además de encargarnos de las finanzas internas del contrato.
  14. El usuario utilizará nuestro producto antes, durante y despúes del proceso de compra de inmueble.
  15. Las características más importantes de nuestro producto son la interfaz accesible y las herramientas hechas a medida para solucionar los problemas.
  16. Nuestros clientes deben sentirse atraídos por la apariencia de nuestro producto por ello tendremos una interfaz profesional además de ser completamente funcional. 

***Business Outcome Assumptions***
   
  - Conseguir una tasa de renovación de membresías del 70% mensualmente.
  - Aumentar en el número de inmuebles listados en la plataforma en un 50% con respecto al semestre anterior durante el primer año.
  - Conseguir una mejora del 30% a los planes "Enterprise" en el segundo semestre del año de lanzamiento.
  - Recibir una puntuación sobresaliente en el 100% de las encuestas de satisfacción enviadas a los usuarios finalizado el primer año de lanzamiento
 
***User Outcome Assumptions***



  - Cumplir las fechas de pagos relacionados a la vivienda
  - Disminución en el estrés relacionado a las pocas ofertas recibidas por su inmueble
  - Dedicar menos tiempo a la revisión de sus inmuebles
  - Obtener una mejor calidad de vida en un mejor inmueble 
  

***Features***

  - Gestión de pagos relacionados a la vivienda 
  - Gestión nuevos inmuebles
  - Gestión de propiedades 
  - Método de compra compartida
  
#### 1.2.2.3. Lean UX Hypothesis Statements.

***Hypothesis 1:***

**Creemos que lograremos** conseguir una tasa de renovación de membresías del 70% mensualmente

**Si** los buscadores de propiedades

**Logran** cumplir con las fechas del pago relacionado a la vivienda como cuotas, o mensualidades para los inquilinos. 

**Con** la gestión de pagos de alquiler de nuestra aplicación web


***Hypothesis 2:***

**Creemos que lograremos** Aumentar en el número de inmuebles listados en la plataforma en un 50% con respecto al semestre anterior durante el primer año

**Si** los propietarios

**Logran** disminuir el estrés relacionado a las pocas ofertas recibidas por su inmueble

**Con** la gestion de nuevos inmuebles


***Hypothesis 3:***

**Creemos que lograremos** conseguir una mejora del 30% a los planes "Enterprise" en el segundo semestre del año de lanzamiento

**Si** los propietarios

**Logran** Dedicar menos tiempo a la revisión de sus inmuebles

**Con** la gestión de propiedades 



***Hypothesis 4:***

**Creemos que lograremos** recibir una puntuación sobresaliente en el 100% de las encuestas de satisfacción enviadas a los usuarios

**Si** los buscadores de propiedades

**Logran** obtener una mejor calidad de vida en un mejor inmueble 

**Con** método de compra compartida



#### 1.2.2.4. Lean UX Canvas.
![Lean UX Canvas](./assets/Chap-I/UX-Canvas.png)
## 1.3. Segmentos objetivo.
***Segmento #1:Propietarios de inmuebles***

Aspectos demográficos:
 - Sexo: Masculino o Femenino.
 - Edad: 40-60 años.
 - Estado civil: Variado.

Aspectos geográficos:
 - Que resida y tenga sus viviendas en Lima metropolitana.


Aspectos psicologicos:
 - Intereses: Un comprador honesto con el que pueda llegar a un acuerdo beneficioso para ambos.
 - Valores: Puntualidad, Responsabilidad, Paciencia, Humildad, Asertividad.


***Segmento #2:Buscadores de viviendas***

Aspectos demográficos:
 - Sexo: Masculino o Femenino
 - Edad: 22-35 años
 - Estado civil: Soltero o Casado

Aspectos geográficos:
 - Ubicación de vivienda anterior: Cualquier ciudad del Perú.
 - Ubicación deseada de proxima vivienda: Lima metropolitana, Perú.
 

Aspectos psicologicos:
 - Intereses: Independizarse o mejorar de su antigua vivienda, trabajo
 - Valores: Honestidad, Autosuficiencia, Nula conflictividad,Puntualidad.


---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

**1. AdondeVivir**
<p>Adondevivir es una de las plataformas inmobiliarias más grandes y populares en Perú. Permite a los usuarios buscar propiedades en venta y alquiler, incluyendo departamentos, casas, terrenos, oficinas y locales comerciales.</p>


**2. Urbania**
<p>Urbania es una plataforma líder en el mercado inmobiliario peruano, especializada en la venta y alquiler de inmuebles. Es conocida por su interfaz amigable y su amplia gama de opciones de propiedades.</p>



### 2.1.1. Análisis competitivo.

<table style="text-align:center">
    <tr>
        <th colspan="5">Competitive Analysis Landscape</th>
    </tr>
    <tr>
        <td style="font-weight:bold">¿Por qué llevar a cabo este análisis?</td>
        <td colspan="4">El objetivo de este análisis es entender las características que ofrecen las demás empresas que ofrecen servicios similares al nuestro y así poder compararnos de una manera más clara
        </td>
    </tr>
    <tr>
        <th colspan="2">Competidores</th>
        <th>InmoShare</th>
        <th>AdondeVivir</th>
        <th>Urbania</th>
    </tr>
    <tr>
        <td rowspan="2">Perfil</td>
        <td>Overview</td>
        <td>Nuestra empresa se especializa en el desarrollo de una aplicación web revolucionaria diseñada para simplificar la compra y venta de departamentos. Conectamos compradores y vendedores de manera segura y eficiente, brindando herramientas avanzadas para optimizar cada paso del proceso inmobiliario.</td>
        <td>Adondevivir es una plataforma peruana para comprar y alquilar propiedades, destacada por su amplio catálogo y búsqueda avanzada. Ofrece servicios adicionales como cálculo de hipotecas y simulaciones de préstamos.</td>
        <td>Urbania es una plataforma inmobiliaria en Perú, parte de Navent Group, que ofrece propiedades en venta y alquiler con una interfaz intuitiva y mapas interactivos. Dispone de opciones premium para agentes inmobiliarios.</td>
    </tr>
    <tr>
        <td>Ventaja Competitiva</td>
        <td>Ofrecemos una variedad de alianzas para ofrecer los mejores inmuebles a los mejores precios, además de la opción de compra entre más de una persona</td>
        <td>Ofrece una amplia variedad de propiedades, opciones de publicidad destacada para agentes, herramientas de búsqueda personalizadas y una plataforma consolidada que facilita la conexión rápida entre compradores y vendedores.</td>
        <td>Se destaca por su extenso catálogo de propiedades, interfaz fácil de usar, herramientas de búsqueda avanzadas y contenido informativo que atrae a usuarios interesados en comprar o vender inmuebles en Perú.</td>
    </tr>
    <tr>
        <td rowspan="2">Perfil de Marketing</td>
        <td>Estrategias de Marketing</td>
        <td>Nuestras estrategias de marketing incluyen campañas en redes sociales, SEO, contenido educativo en blogs, alianzas con inmobiliarias, publicidad segmentada y promociones exclusivas para captar y retener usuarios en nuestra plataforma.</td>
        <td>Se enfoca en marketing digital con anuncios en redes sociales y Google Ads. Utiliza contenido informativo sobre el mercado inmobiliario para atraer y educar a los usuarios, además de SEO.</td>
        <td>Utiliza marketing digital con publicidad dirigida y optimización SEO, destacando en redes sociales y motores de búsqueda. También ofrece servicios publicitarios y de marketing para aumentar la visibilidad de las propiedades.</td>
    </tr>
    <tr>
        <td>Mercado Objetivo</td>
        <td>Nuestro mercado objetivo incluye compradores y vendedores de departamentos, tanto nuevos como experimentados, jóvenes profesionales, familias urbanas, inversores inmobiliarios y agentes que buscan una plataforma moderna y eficiente para transacciones inmobiliarias.</td>
        <td>Se dirige a personas en Perú interesadas en comprar o alquilar propiedades, incluyendo jóvenes profesionales, familias y empresarios, así como a agentes y desarrolladores inmobiliarios que buscan promocionar sus ofertas.</td>
        <td>Apunta a compradores y arrendatarios en Perú que buscan propiedades residenciales y comerciales, así como a agentes inmobiliarios y desarrolladores que necesitan visibilidad para sus anuncios y servicios.</td>
    </tr>
    <tr>
        <td rowspan="3">Perfil de Producto</td>
        <td>Productos y Servicios</td>
        <td>Ofrecemos una plataforma intuitiva para la compra y venta de departamentos, con herramientas avanzadas como la opción de poder alquilar o comprar un departamento entre 2 a más amigos.</td>
        <td>Proporciona anuncios inmobiliarios, herramientas de búsqueda avanzada, servicios de cálculo hipotecario, y simulaciones de préstamos para compradores y arrendatarios.</td>
        <td>Ofrece anuncios de venta y alquiler de propiedades, servicios publicitarios premium para agentes, y herramientas de búsqueda avanzada con mapas interactivos.</td>
    </tr>
    <tr>
        <td>Precios y Costos</td>
        <td>Contamos con opciones de publicación gratuitas asi como opciones de paga los cuales ayudan al vendedor a tener publicaciones con mayor visibilidad.</td>
        <td>Tiene opciones de publicación gratuitas y de pago, con tarifas para destacar propiedades y servicios adicionales</td>
        <td>Ofrece publicaciones gratuitas limitadas y paquetes premium de pago para mayor visibilidad de anuncios.</td>
    </tr>
    <tr>
        <td>Canales de Distribución</td>
        <td>Disponible en versión web</td>
        <td>Aplicación móvil y aplicación web</td>
        <td>Aplicación móvil y web</td>
    </tr>
    <tr>
        <td rowspan="4">Analisis SWOT</td>
        <td>Fortalezas</td>
        <td>Plataforma innovadora que facilita la compra y venta de inmuebles, incluyendo la opción de adquirir propiedades en grupo. Ofrece una experiencia de usuario intuitiva y herramientas avanzadas para la gestión de transacciones.</td>
        <td>Amplia variedad de propiedades y fuerte reconocimiento de marca, junto con opciones de publicidad destacada que atraen a agentes y desarrolladores inmobiliarios.</td>
        <td>Amplio catálogo de propiedades y herramientas avanzadas de búsqueda que mejoran la experiencia del usuario, consolidando su posición en el mercado inmobiliario peruano.</td>
    </tr>
    <tr>
        <td>Debilidades</td>
        <td>La novedad del modelo de compra compartida puede generar desconfianza. Requiere un desarrollo tecnológico robusto y costoso, y la necesidad de asegurar la protección legal en transacciones compartidas.</td>
        <td>Alta dependencia del mercado inmobiliario peruano y costos de mantenimiento tecnológico pueden limitar su capacidad de adaptarse a cambios del mercado.</td>
        <td>Competencia intensa y dependencia de la publicidad limitan su crecimiento y capacidad de diferenciación en un mercado saturado de plataformas similares.</td>
    </tr>
    <tr>
        <td>Oportunidades</td>
        <td>Expansión a mercados con alta demanda de bienes raíces y posibilidad de asociarse con agencias y desarrolladores para ofrecer listados exclusivos. Innovación en el mercado inmobiliario y potencial para capturar un segmento nuevo de compradores.</td>
        <td>Innovación en servicios digitales y expansión en América Latina, junto con alianzas estratégicas con agencias inmobiliarias para ofrecer propiedades exclusivas.</td>
        <td>Expansión a mercados latinoamericanos y adopción de tecnologías innovadoras como realidad virtual para ofrecer recorridos virtuales y listados exclusivos de propiedades.</td>
    </tr>
    <tr>
        <td>Amenazas</td>
        <td>Competencia de plataformas establecidas y nuevas startups en el mercado inmobiliario. Riesgos asociados con la legalidad y la gestión de propiedad compartida, así como fluctuaciones económicas que afectan la compra de inmuebles.</td>
        <td>Creciente competencia de nuevos actores y cambios en las preferencias del consumidor, además de la inestabilidad económica que afecta el mercado de bienes raíces.</td>
        <td>Cambios regulatorios y fluctuaciones económicas en el mercado inmobiliario podrían impactar negativamente en su modelo de negocio y rentabilidad.</td>
    </tr>
</table>




### 2.1.2. Estrategias y tácticas frente a competidores.

<ul>
    <li>
        <b>Diferenciación mediante propiedad compartida:</b> Otorgaremos la opción única de comprar inmuebles entre dos o más personas, un servicio que Urbania y Adondevivir no ofrecen. Desarrollaremos campañas de marketing enfocadas en el beneficio de compartir costos y accesibilidad a propiedades que serían inaccesibles para compradores individuales.
    </li>
    <li>
        <b>Mejora de la experiencia del usuario:</b> Invertiremos en una interfaz intuitiva y herramientas avanzadas, como recorridos virtuales en 3D y calculadoras de financiamiento compartido. Esto no solo atraerá a usuarios que buscan innovaciones tecnológicas, sino que también mejorará la retención al ofrecer una experiencia superior.
    </li>
    <li>
        <b>Alianzas estratégicas y listados exclusivos:</b> Colaboraremos con agencias inmobiliarias, desarrolladores, y bancos para obtener listados exclusivos y financiamientos especiales. Ofreceremos incentivos a los agentes para que utilicen la plataforma, diferenciándola por la calidad y exclusividad de las propiedades listadas.
    </li>
</ul>


## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 

**Preguntas para vendedores**
1. ¿Cuales son los mayores desafíos que enfentas al vender propiedades actualmente?
2. ¿Cómo te gustaría que una plataforma digital te ayudara a encontrar y conectar con potenciales compradores?
3. ¿Qué características te harían preferir una nueva aplicación sobre las plataformas que usas actualmente?
4. ¿Qué información adicional te gustaría tener sobre los compradores antes de interactuar con ellos?
5. ¿Qué tan frecuente es la venta de propiedades entre varias personas, y cómo se maneja ese proceso actualmente?
6. ¿Hay algo que consideras que falta en las plataformas inmobiliarias actuales? 

**Preguntas para compradores**
1. ¿Qué características te gustaría ver en una plataforma de compra de inmuebles que te facilitarían la búsqueda y decisión de compra? 
2. ¿Qué tan importante es la posibilidad de comprar una propiedad en conjunto con otras personas?
3. ¿Qué tipo de información prefieres tener disponible cuando exploras una propiedad en línea?
4. ¿Qué factores influyen más en tu decisión de comprar una propiedad?
5. ¿Qué problemas has encontrado al utilizar otras plataformas de compra de inmuebles?

### 2.2.2. Registro de entrevistas.

**Segmento Propietario**
**Entrevista 1**

**Nombre:** Yndira Bueno
**Edad:** 54 años 
**Ocupación:**Arquitecta

![Entrevista1-1](./assets/Chap-II/Entrevista%20Yndira%20Bueno.jpg)
**URL:**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u202211212_upc_edu_pe/EbmxJZjmCu5HkDj1U1ce6awBlMXGa-HZFAOfeRNVgaP1ew?e=EPTgK9&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D


**Segmento Inquilinos** 

**Entrevista 1**

**Nombre:** Mateo Vilchez
**Edad:** 19 años 
**Ocupación:** Estudiante de Ingeniería de Software
**URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202015274_upc_edu_pe/EQdnVlI8nNNGisxHQgn-wXMB7hVaug2-vp_JxjA_vVMv3A?e=2prSu4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 

<img src="assets/Chap-II/Entrevista Mateo Vilchez.png">

**Entrevista 2**

**Nombre**: Aldair Chuman
**Edad**: 22 años 
**Ocupación**: Ingeniero de Software  
**URL**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e414_upc_edu_pe/ERYcC5TRz7lNgGgBlwIfcxgBluAvlZV4BrmAMOJg2lKB8g?e=gdnUAp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

<img src="./assets/Chap-II/entrevista-aldair.png">


### 2.2.3. Análisis de entrevistas.
**Segmento Inquilinos**

En las entrevistas realizadas a los inquilinos, surgieron varias sugerencias sobre cómo mejorar la aplicación, así como un gran interés en la función de compra compartida. Los entrevistados, compuestos por jóvenes profesionales y emprendedores, valoraron la interfaz intuitiva de la plataforma, pero expresaron que sería útil contar con más opciones de filtros personalizados para facilitar la búsqueda de propiedades. Por ejemplo, sugirieron añadir filtros que permitan seleccionar inmuebles por cercanía a sus lugares de trabajo, acceso a transporte público, y servicios como supermercados y gimnasios. Además, muchos destacaron la necesidad de recorridos virtuales en 3D más detallados, ya que esto les permitiría evaluar mejor los espacios sin necesidad de visitarlos físicamente. También se mencionó la importancia de agregar herramientas de comparación entre propiedades y calculadoras de financiamiento más avanzadas que incluyan simulaciones de pagos mensuales y distribución de costos.

Los entrevistados también señalaron que la integración de reseñas de otros inquilinos sería muy útil para conocer las experiencias previas en las propiedades, así como la confiabilidad de los propietarios y agentes. Otro punto relevante fue la sugerencia de implementar un chat en vivo dentro de la aplicación, que permita resolver dudas en tiempo real y mejorar la atención al usuario. Respecto a la función de compra compartida, todos coincidieron en que se trata de una característica innovadora y esencial, especialmente para quienes buscan acceder al mercado inmobiliario sin asumir un compromiso financiero individualmente. Para estos inquilinos, la posibilidad de adquirir una propiedad junto a amigos, familiares o socios les abre la puerta a viviendas de mayor valor que de otro modo serían inalcanzables. Esta función no solo les permitiría compartir costos, sino también diversificar sus inversiones y reducir el riesgo financiero. En conclusión, los entrevistados consideran que la compra compartida aporta un valor diferencial significativo a la aplicación, haciéndola más atractiva y accesible para un público joven y dinámico que busca formas alternativas de acceder a la vivienda y al mercado inmobiliario.

**Segmento Propietarios:**

En las entrevistas con propietarios, surgieron varias sugerencias y comentarios sobre cómo mejorar la aplicación y la relevancia de la función de compra compartida. Los propietarios valoraron la interfaz intuitiva, pero propusieron la integración de opciones de publicidad destacada para aumentar la visibilidad de sus propiedades y atraer a más inquilinos potenciales. También sugirieron mejoras en las herramientas de gestión, como un sistema para facilitar la comunicación y administración de contratos con los inquilinos, y opciones para evaluar mejor a los posibles arrendatarios.

Respecto a la función de compra compartida, los propietarios la consideraron una adición valiosa, ya que podría atraer a un grupo más amplio de compradores y diversificar sus opciones de venta. Vieron la posibilidad de dividir la compra entre varios compradores como una forma de acceder a un mercado más amplio y acelerar la venta de propiedades que, de otro modo, podrían tardar más en encontrar un comprador. Esta función también podría ofrecerles una ventaja competitiva en el mercado, al permitirles atraer a compradores que buscan compartir costos y reducir su compromiso financiero individual. En resumen, los propietarios valoran las mejoras en la gestión y visibilidad de sus propiedades y consideran la compra compartida como una herramienta innovadora que puede facilitar las transacciones y ampliar su base de clientes potenciales.

## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento Inquilino**  

<img src="assets/Chap-II/User Persona - Inquilino.png">

**Segmento Propietario**

<img src="assets/Chap-II/User Persona - Propietario.png">

### 2.3.2. User Task Matrix.
<table>
    <tr>
    <th colspan="3">User Persona: Propietarios</th>
    </tr>
    <tr>
        <th>Tarea</th>
        <th>Frecuencia</th>
        <th>Importancia</th>
    </tr>
    <tr>
        <td>Crear perfil</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Gestionar múltiples listados</td>
        <td>Often</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Recibir notificaciones</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Filtrar compradores</td>
        <td>Sometimes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Agendar visitas</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Ver analíticas</td>
        <td>Often</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Ver recomendaciones de precios</td>
        <td>Sometimes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Recibir reseñas</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Ver historial de transacciones</td>
        <td>Always</td>
        <td>High</td>
    </tr>
</table>

<table>
    <tr>
    <th colspan="3">User Persona: Inquilinos</th>
    </tr>
    <tr>
        <th>Tarea</th>
        <th>Frecuencia</th>
        <th>Importancia</th>
    </tr>
    <tr>
        <td>Buscar propiedades</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Guardar propiedades favoritas</td>
        <td>Often</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Comparar propiedades</td>
        <td>Sometimes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Calcular financiamiento</td>
        <td>Often</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Comprar en grupo</td>
        <td>Often</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Recibir notificaciones</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Ver recomendaciones personalizadas</td>
        <td>Always</td>
        <td>High</td>
    </tr>
    <tr>
        <td>Gestionar documentos</td>
        <td>Sometimes</td>
        <td>Medium</td>
    </tr>
    <tr>
        <td>Ver historial de búsqueda</td>
        <td>Always</td>
        <td>Medium</td>
    </tr>
</table>

### 2.3.3. User Journey Mapping.

A continuación, se muestran los User Journey Mapping por cada segmento objetivo.

**Segmento Objetivo Propietarios**
<img src="assets/Chap-II/User Journey Map - Comprador.png">

**Segmento Objetivo: Inquilinos**
<img src="assets/Chap-II/User Journey Map - Vendedor.png">

### 2.3.4. Empathy Mapping.

**Segmento: Inquilinos**

<img src="assets/Chap-II/Mapa de Empatía - Mateo Vilchez.png">


**Segmento: Propietarios**

<img src="assets/Chap-II/Mapa de Empatía - Ana Gomez.png">

### 2.3.5. As-is Scenario Mapping.

**Segmento: Inquilino**  

<img src="assets/Chap-II/As - Is Inquilino.jpg">

**Segmento: Propietario**  

<img src="assets/Chap-II/As - Is Propietario.jpg">


## 2.4. Ubiquitous Language.

**1. Propietario:** Persona que posee una propiedad y está interesada en vender o alquilar su inmueble. Sus objetivos son maximizar la rentabilidad y minimizar el tiempo de vacancia de la propiedad.

**2. Inquilino:** Persona que busca alquilar una propiedad para uso residencial o comercial. En nuestro contexto, también se interesa en funciones innovadoras como la compra compartida y recorridos virtuales.

**3. Comprador:** Usuario que busca adquirir una propiedad, ya sea para habitarla, invertir o compartir la compra con otros. Puede ser un comprador individual o un comprador conjunto.

**4. Compra Compartida:** Función que permite a dos o más personas adquirir una propiedad juntos, compartiendo los costos de compra y financiamiento, haciendo accesibles propiedades de mayor valor.

**5. Agente Inmobiliario:** Profesional que facilita el proceso de compra, venta o alquiler de propiedades, actuando como intermediario entre compradores y vendedores. Ofrece servicios de listado, publicidad destacada y asesoría.

**6. Plataforma Inmobiliaria:** Aplicación o sitio web que conecta a compradores, vendedores, inquilinos y agentes, ofreciendo herramientas avanzadas para la búsqueda, negociación y cierre de transacciones inmobiliarias.

**7. Filtro Personalizado:** Herramienta en la plataforma que permite a los usuarios ajustar sus criterios de búsqueda, como ubicación, precio, tipo de propiedad y cercanía a servicios, para encontrar la opción que mejor se adapte a sus necesidades.

**8. Financiamiento Compartido:** Modelo de financiamiento que permite dividir los costos de compra de una propiedad entre múltiples compradores, facilitando el acceso a préstamos y condiciones de pago más flexibles.

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

Segmento 1:

| Fases                          | Publicar Propiedad | Administrar Propiedades                                       | Crear Contrato de Arrendamiento                              | Generar Informes Financieros                                      |
| ------------------------------ | ------------------ | ------------------------------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------------------------- |
| Doing                         | Subiendo fotos, ingresando descripción y detalles de la propiedad. | Supervisando pagos, renovaciones, y contratos. Gestionando el mantenimiento de las propiedades. | Redactando y revisando los términos del contrato.                 | Reuniendo información financiera para análisis y planificación.  |
| Thinking                      |¿Cómo puedo mostrar mi propiedad de la mejor manera? ¿Será fácil encontrar compradores o arrendatarios? | ¿Todo está al día? ¿Necesito tomar alguna acción? ¿Cómo puedo optimizar la gestión de mis propiedades? | ¿Este contrato cubre todas las situaciones posibles? ¿Será legalmente válido? | ¿Cómo están los ingresos y gastos de mis propiedades? ¿Necesito ajustar mis estrategias de inversión o alquiler? |
| Feeling                       |  Motivado por las posibilidades de generar ingresos.            | Seguro y en control de sus activos. Tranquilo al tener visibilidad completa. | Tranquilo al formalizar el acuerdo con el arrendatario.             | Informado y en control de las finanzas. Preocupado si los informes muestran resultados inesperados.              |


Segmento 2:
| Fases                          | Buscar Propiedad para Alquilar                        | Comprar Propiedad Colectivamente                                  | Recibir Notificaciones de Pago                                      | Renovar Contrato de Alquiler                                       |
| ------------------------------ | ------------------------------------------------------ | --------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| Doing                         | Explorando diferentes propiedades y comparando precios y características. | Evaluando opciones de inversión y calculando retornos potenciales. | Recibiendo y revisando notificaciones, realizando el pago.          | Revisando y negociando los términos del nuevo contrato.            |
| Thinking                      | ¿Esta propiedad cumple con mis necesidades? ¿Es el precio justo? | ¿Esta inversión será rentable? ¿Puedo confiar en los otros compradores? | ¿He recibido la notificación a tiempo? ¿Todo está en orden con los pagos? | ¿Los nuevos términos son justos? ¿Quiero seguir alquilando esta propiedad? |
| Feeling                       | Emocionado por encontrar un lugar adecuado para vivir. | Confiado al invertir en una propiedad con buenas perspectivas.     | Tranquilo al mantenerse al día con los pagos.                       | Decidido si está satisfecho con los términos. Inseguro si los términos no son favorables.                |


## 3.2. User Stories.

## Epic/Story ID: EPIC-001 - Gestión de Propiedades

| **ID**      | **Título**                 | **Descripción**                                                | **Criterios de Aceptación**                                                                                                                                           | **Relacionado con (Epic ID)** |
|-------------|----------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EPIC-001** | Gestión de Propiedades     | Permitir a los propietarios gestionar sus propiedades, incluyendo el alquiler y la venta. | Given un propietario ha accedido al sistema, when selecciona la opción de gestión de propiedades, then el sistema debe permitirle alquilar o vender la propiedad. |                               |
| **US-001-001** | Alquilar Propiedad          | Como propietario, quiero poder alquilar mi propiedad para recibir ingresos regulares. | Given el propietario tiene una propiedad disponible para alquiler, when selecciona la opción de alquilar, then el sistema debe permitirle fijar el precio del alquiler y establecer las condiciones del contrato. | EPIC-001                      |
| **US-001-002** | Vender Propiedad            | Como propietario, quiero poder vender mi propiedad.            | Given el propietario tiene una propiedad disponible para venta, when selecciona la opción de vender, then el sistema debe permitirle fijar el precio de venta y publicar el anuncio de la propiedad. | EPIC-001                      |
| **US-001-003** | Administrar Pagos de Alquiler | Como propietario, quiero poder verificar si los alquileres se han pagado y recibir recordatorios de pago. | Given el propietario tiene una propiedad en alquiler, when consulta el estado de los pagos, then el sistema debe mostrar los pagos realizados y pendientes, y enviar recordatorios de pago próximos a la fecha. | EPIC-001                      |
| **US-001-004** | Crear Contratos de Alquiler | Como propietario, quiero poder crear contratos para los alquileres de mis propiedades. | Given el propietario ha acordado un alquiler con un inquilino, when crea un contrato, then el sistema debe permitirle generar un contrato que incluya términos de alquiler y condiciones. | EPIC-001                      |
| **US-001-005** | Ver Historial de Contratos | Como propietario, quiero ver el historial de contratos de alquiler para una propiedad. | Given el propietario tiene varios contratos de alquiler, when consulta el historial de contratos, then el sistema debe mostrar una lista de todos los contratos anteriores y sus detalles. | EPIC-001                      |
| **US-001-006** | Editar Detalles de Propiedad | Como propietario, quiero editar los detalles de mi propiedad (ej. descripción, fotos) después de publicarla. | Given el propietario tiene una propiedad publicada, when selecciona la opción de editar, then el sistema debe permitirle modificar los detalles de la propiedad y actualizar la información publicada. | EPIC-001                      |
| **US-001-007** | Verificar Disponibilidad de Propiedad | Como propietario, quiero verificar la disponibilidad de mi propiedad para alquilarla o venderla. | Given el propietario ha publicado una propiedad, when consulta su disponibilidad, then el sistema debe mostrar si la propiedad está disponible para alquiler o venta. | EPIC-001                      |

## Epic/Story ID: EPIC-002 - Gestión de Inquilinos

| **ID**      | **Título**                 | **Descripción**                                                | **Criterios de Aceptación**                                                                                                                                           | **Relacionado con (Epic ID)** |
|-------------|----------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EPIC-002** | Gestión de Inquilinos      | Permitir a los inquilinos gestionar sus alquileres, incluyendo el pago de alquileres y la recepción de notificaciones. | Given un inquilino ha accedido al sistema, when selecciona la opción de gestión de alquiler, then el sistema debe permitirle pagar el alquiler y recibir notificaciones de pago. |                               |
| **US-002-001** | Pagar Alquiler              | Como inquilino, quiero poder pagar el alquiler de la propiedad que estoy alquilando. | Given el inquilino tiene un alquiler pendiente, when selecciona la opción de pagar, then el sistema debe permitirle realizar el pago de manera segura y confirmar la transacción. | EPIC-002                      |
| **US-002-002** | Recibir Notificaciones de Pago | Como inquilino, quiero recibir notificaciones cuando se acerque la fecha de pago del alquiler y los servicios. | Given el inquilino tiene una fecha de pago próxima, when se acerca la fecha, then el sistema debe enviar notificaciones recordatorias del pago de alquiler y servicios. | EPIC-002                      |
| **US-002-003** | Ver Historial de Pagos      | Como inquilino, quiero ver el historial de mis pagos para asegurarme de que todos los pagos han sido realizados correctamente. | Given el inquilino ha realizado varios pagos, when consulta el historial de pagos, then el sistema debe mostrar todos los pagos realizados y su estado. | EPIC-002                      |
| **US-002-004** | Solicitar Mantenimiento     | Como inquilino, quiero poder solicitar mantenimiento para problemas en la propiedad que estoy alquilando. | Given el inquilino detecta un problema en la propiedad, when solicita mantenimiento, then el sistema debe permitirle enviar una solicitud que incluya detalles del problema. | EPIC-002                      |
| **US-002-005** | Confirmar Recepción de Solicitud de Mantenimiento | Como inquilino, quiero recibir confirmación de que mi solicitud de mantenimiento ha sido recibida y está siendo gestionada. | Given el inquilino ha enviado una solicitud de mantenimiento, when la solicitud es recibida, then el sistema debe enviar una confirmación al inquilino indicando que la solicitud está en proceso. | EPIC-002                      |

## Epic/Story ID: EPIC-003 - Compra Compartida de Propiedad

| **ID**      | **Título**                 | **Descripción**                                                | **Criterios de Aceptación**                                                                                                                                           | **Relacionado con (Epic ID)** |
|-------------|----------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EPIC-003** | Compra Compartida de Propiedad | Permitir a múltiples personas comprar una propiedad en conjunto y compartir los ingresos de alquiler. | Given un grupo de personas quiere comprar una propiedad en conjunto, when deciden la compra, then el sistema debe permitirles establecer porcentajes de propiedad y distribuir las ganancias de alquiler de acuerdo a estos porcentajes. |                               |
| **US-003-001** | Dividir Propiedad para Compra | Como grupo de compradores, queremos dividir la propiedad en porcentajes de propiedad. | Given un grupo ha decidido comprar una propiedad en conjunto, when definen los porcentajes, then el sistema debe registrar estos porcentajes y asociarlos a cada comprador. | EPIC-003                      |
| **US-003-002** | Distribuir Ganancias de Alquiler | Como grupo de propietarios compartidos, queremos recibir ganancias de alquiler basadas en nuestros porcentajes de propiedad. | Given la propiedad compartida está alquilada, when se recibe el alquiler, then el sistema debe calcular y distribuir las ganancias según los porcentajes establecidos. | EPIC-003                      |
| **US-003-003** | Ver Historial de Distribución de Ganancias | Como grupo de propietarios compartidos, quiero ver un historial de la distribución de las ganancias de alquiler. | Given el grupo de propietarios ha recibido varias distribuciones de ganancias, when consulta el historial, then el sistema debe mostrar un registro detallado de cada distribución realizada. | EPIC-003                      |
| **US-003-004** | Ajustar Porcentajes de Propiedad | Como grupo de compradores compartidos, queremos ajustar los porcentajes de propiedad si es necesario. | Given el grupo de compradores desea ajustar los porcentajes de propiedad, when realizan el ajuste, then el sistema debe actualizar los porcentajes y recalcular la distribución de ganancias. | EPIC-003                      |

## Epic/Story ID: EPIC-004 - Sitio Web Estático

| **ID**      | **Título**                 | **Descripción**                                                | **Criterios de Aceptación**                                                                                                                                           | **Relacionado con (Epic ID)** |
|-------------|----------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EPIC-004** | Sitio Web Estático         | Crear una landing page que informe a los visitantes sobre el proyecto y las opciones disponibles. | Given un visitante accede a la landing page, when navega por la página, then debe encontrar información clara sobre la compra, alquiler y gestión de propiedades. |                               |
| **US-004-001** | Información sobre Compra y Alquiler | Como visitante, quiero encontrar información sobre cómo comprar o alquilar una propiedad. | Given un visitante accede a la landing page, when navega por la sección de compra y alquiler, then debe encontrar información detallada sobre cómo proceder con cada opción. | EPIC-004                      |
| **US-004-002** | Información de Contacto y Soporte | Como visitante, quiero tener acceso a información de contacto y soporte para resolver dudas. | Given un visitante necesita soporte, when busca información de contacto en la landing page, then debe encontrar datos de contacto y opciones para recibir ayuda. | EPIC-004                      |
| **US-004-003** | Suscripción a Newsletter    | Como visitante, quiero suscribirme a un boletín informativo para recibir actualizaciones y noticias sobre propiedades. | Given un visitante quiere recibir actualizaciones, when se suscribe al boletín informativo, then el sistema debe añadir su dirección de correo a la lista de suscriptores y enviar confirmación de la suscripción. | EPIC-004                      |

### EPIC-005 - Gestión de Nuevos Inmuebles

| **ID**        | **Título**                          | **Descripción**                                                  | **Criterios de Aceptación**                                                                                                                                                                                                                                                                  | **Relacionado con (Epic ID)** |
|---------------|-------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------|
| **EPIC-005**  | Gestión de Nuevos Inmuebles          | Permitir a los usuarios agregar nuevos inmuebles al sistema, gestionar documentos legales, actualizar propietarios y realizar un seguimiento de la valorización. | Given un usuario (administrador o propietario) desea agregar un nuevo inmueble al sistema, when completa el formulario de creación del inmueble, then el sistema debe permitirle ingresar toda la información relevante, cargar documentos legales, actualizar información de propietarios y realizar un seguimiento de la valorización del inmueble. |                               |
| **US-005-001** | Agregar Nuevo Inmueble              | Como usuario, quiero agregar un nuevo inmueble al sistema con toda la información relevante. | Given un usuario desea agregar un nuevo inmueble, when completa el formulario de creación del inmueble, then el sistema debe registrar el inmueble con todos los detalles proporcionados, incluyendo dirección, características y fotos. | EPIC-005                      |
| **US-005-002** | Cargar Documentos Legales para Inmueble | Como usuario, quiero cargar documentos legales relacionados con el nuevo inmueble. | Given un usuario ha agregado un nuevo inmueble, when selecciona la opción de cargar documentos legales, then el sistema debe permitirle subir y asociar documentos legales relevantes al inmueble, como escrituras, contratos, etc. | EPIC-005                      |
| **US-005-003** | Actualizar Información de Propietarios | Como usuario, quiero poder actualizar la información de los propietarios de un inmueble si se vende. | Given un inmueble ha sido vendido y tiene nuevos propietarios, when el usuario actualiza la información de propietarios, then el sistema debe permitir modificar la información de los propietarios y actualizar los registros en el sistema. | EPIC-005                      |
| **US-005-004** | Seguimiento de Valorización del Inmueble | Como propietario o administrador, quiero realizar un seguimiento de la valorización del inmueble a lo largo del tiempo. | Given un inmueble está registrado en el sistema, when se ingresan datos de valorización periódicos, then el sistema debe calcular y mostrar un historial de valorización y una tendencia de valorización a lo largo del tiempo, incluyendo gráficos y proyecciones futuras. | EPIC-005                      |
| **US-005-005** | Generar Reportes de Valorización     | Como propietario, quiero generar reportes sobre la valorización histórica del inmueble. | Given un propietario o administrador desea ver el historial de valorización, when solicita un reporte, then el sistema debe generar un informe detallado que muestre la valorización histórica del inmueble, incluyendo gráficos y análisis. | EPIC-005                      |
| **US-005-006** | Notificaciones de Documentación Legal | Como usuario, quiero recibir notificaciones cuando los documentos legales del inmueble necesiten actualización o revisión. | Given documentos legales están asociados a un inmueble, when se acerca la fecha de expiración o revisión de estos documentos, then el sistema debe enviar notificaciones al usuario correspondiente para asegurarse de que se mantengan actualizados. | EPIC-005                      |



## 3.3. Impact Mapping.

![image](https://github.com/user-attachments/assets/4db097b7-65ed-4fc6-8df3-97495232aa3f)
![image](https://github.com/user-attachments/assets/550fa130-99be-4580-ae0c-ce4ca54066a5)
![image](https://github.com/user-attachments/assets/b811ab91-1171-4cb7-9661-98cac16d93f0)
![image](https://github.com/user-attachments/assets/632a85c3-8ff3-431a-8d21-cf85e678793b)

## 3.4. Product Backlog.

# Product Backlog

| #Orden | Epic/Story ID | Título                                 | Descripción                                                                                     | Criterios de Aceptación                                                                                                        | Story Points |
|--------|---------------|----------------------------------------|-------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1      | EPIC-001       | Gestión de Propiedades                 | Permitir a los propietarios gestionar sus propiedades, incluyendo el alquiler y la venta.       | Given un propietario ha accedido al sistema, when selecciona la opción de gestión de propiedades, then el sistema debe permitirle alquilar o vender la propiedad. | -            |
| 2      | US-001-001     | Alquilar Propiedad                     | Como propietario, quiero poder alquilar mi propiedad para recibir ingresos regulares.            | Given el propietario tiene una propiedad disponible para alquiler, when selecciona la opción de alquilar, then el sistema debe permitirle fijar el precio del alquiler y establecer las condiciones del contrato. | 5            |
| 3      | US-001-002     | Vender Propiedad                       | Como propietario, quiero poder vender mi propiedad.                                              | Given el propietario tiene una propiedad disponible para venta, when selecciona la opción de vender, then el sistema debe permitirle fijar el precio de venta y publicar el anuncio de la propiedad. | 3            |
| 4      | US-001-003     | Administrar Pagos de Alquiler           | Como propietario, quiero poder verificar si los alquileres se han pagado y recibir recordatorios de pago. | Given el propietario tiene una propiedad en alquiler, when consulta el estado de los pagos, then el sistema debe mostrar los pagos realizados y pendientes, y enviar recordatorios de pago próximos a la fecha. | 8            |
| 5      | US-001-004     | Crear Contratos de Alquiler            | Como propietario, quiero poder crear contratos para los alquileres de mis propiedades.             | Given el propietario ha acordado un alquiler con un inquilino, when crea un contrato, then el sistema debe permitirle generar un contrato que incluya términos de alquiler y condiciones. | 5            |
| 6      | US-001-005     | Ver Historial de Contratos             | Como propietario, quiero ver el historial de contratos de alquiler para una propiedad.            | Given el propietario tiene varios contratos de alquiler, when consulta el historial de contratos, then el sistema debe mostrar una lista de todos los contratos anteriores y sus detalles. | 3            |
| 7      | US-001-006     | Editar Detalles de Propiedad            | Como propietario, quiero editar los detalles de mi propiedad (ej. descripción, fotos) después de publicarla. | Given el propietario tiene una propiedad publicada, when selecciona la opción de editar, then el sistema debe permitirle modificar los detalles de la propiedad y actualizar la información publicada. | 5            |
| 8      | US-001-007     | Verificar Disponibilidad de Propiedad  | Como propietario, quiero verificar la disponibilidad de mi propiedad para alquilarla o venderla.  | Given el propietario ha publicado una propiedad, when consulta su disponibilidad, then el sistema debe mostrar si la propiedad está disponible para alquiler o venta. | 3            |
| 9      | EPIC-002       | Gestión de Inquilinos                  | Permitir a los inquilinos gestionar sus alquileres, incluyendo el pago de alquileres y la recepción de notificaciones. | Given un inquilino ha accedido al sistema, when selecciona la opción de gestión de alquiler, then el sistema debe permitirle pagar el alquiler y recibir notificaciones de pago. | -            |
| 10     | US-002-001     | Pagar Alquiler                         | Como inquilino, quiero poder pagar el alquiler de la propiedad que estoy alquilando.              | Given el inquilino tiene un alquiler pendiente, when selecciona la opción de pagar, then el sistema debe permitirle realizar el pago de manera segura y confirmar la transacción. | 5            |
| 11     | US-002-002     | Recibir Notificaciones de Pago         | Como inquilino, quiero recibir notificaciones cuando se acerque la fecha de pago del alquiler y los servicios. | Given el inquilino tiene una fecha de pago próxima, when se acerca la fecha, then el sistema debe enviar notificaciones recordatorias del pago de alquiler y servicios. | 3            |
| 12     | US-002-003     | Ver Historial de Pagos                 | Como inquilino, quiero ver el historial de mis pagos para asegurarme de que todos los pagos han sido realizados correctamente. | Given el inquilino ha realizado varios pagos, when consulta el historial de pagos, then el sistema debe mostrar todos los pagos realizados y su estado. | 5            |
| 13     | US-002-004     | Solicitar Mantenimiento                | Como inquilino, quiero poder solicitar mantenimiento para problemas en la propiedad que estoy alquilando. | Given el inquilino detecta un problema en la propiedad, when solicita mantenimiento, then el sistema debe permitirle enviar una solicitud que incluya detalles del problema. | 5            |
| 14     | US-002-005     | Confirmar Recepción de Solicitud de Mantenimiento | Como inquilino, quiero recibir confirmación de que mi solicitud de mantenimiento ha sido recibida y está siendo gestionada. | Given el inquilino ha enviado una solicitud de mantenimiento, when la solicitud es recibida, then el sistema debe enviar una confirmación al inquilino indicando que la solicitud está en proceso. | 3            |
| 15     | EPIC-003       | Compra Compartida de Propiedad         | Permitir a múltiples personas comprar una propiedad en conjunto y compartir los ingresos de alquiler. | Given un grupo de personas quiere comprar una propiedad en conjunto, when deciden la compra, then el sistema debe permitirles establecer porcentajes de propiedad y distribuir las ganancias de alquiler de acuerdo a estos porcentajes. | -            |
| 16     | US-003-001     | Dividir Propiedad para Compra          | Como grupo de compradores, queremos dividir la propiedad en porcentajes de propiedad.              | Given un grupo ha decidido comprar una propiedad en conjunto, when definen los porcentajes, then el sistema debe registrar estos porcentajes y asociarlos a cada comprador. | 5            |
| 17     | US-003-002     | Distribuir Ganancias de Alquiler       | Como grupo de propietarios compartidos, queremos recibir ganancias de alquiler basadas en nuestros porcentajes de propiedad. | Given la propiedad compartida está alquilada, when se recibe el alquiler, then el sistema debe calcular y distribuir las ganancias según los porcentajes establecidos. | 8            |
| 18     | US-003-003     | Ver Historial de Distribución de Ganancias | Como grupo de propietarios compartidos, quiero ver un historial de la distribución de las ganancias de alquiler. | Given el grupo de propietarios ha recibido varias distribuciones de ganancias, when consulta el historial, then el sistema debe mostrar un registro detallado de cada distribución realizada. | 5            |
| 19     | US-003-004     | Ajustar Porcentajes de Propiedad       | Como grupo de compradores compartidos, queremos ajustar los porcentajes de propiedad si es necesario. | Given el grupo de compradores desea ajustar los porcentajes de propiedad, when realizan el ajuste, then el sistema debe actualizar los porcentajes y recalcular la distribución de ganancias. | 5            |
| 20     | EPIC-004       | Sitio Web Estático                     | Crear una landing page que informe a los visitantes sobre el proyecto y las opciones disponibles. | Given un visitante accede a la landing page, when navega por la página, then debe encontrar información clara sobre la compra, alquiler y gestión de propiedades. | -            |
| 21     | US-004-001     | Información sobre Compra y Alquiler   | Como visitante, quiero encontrar información sobre cómo comprar o alquilar una propiedad.          | Given un visitante accede a la landing page, when navega por la sección de compra y alquiler, then debe encontrar información detallada sobre cómo proceder con cada opción. | 3            |
| 22     | US-004-002     | Información de Contacto y Soporte      | Como visitante, quiero tener acceso a información de contacto y soporte para resolver dudas.      | Given un visitante necesita soporte, when busca información de contacto en la landing page, then debe encontrar datos de contacto y opciones para recibir ayuda. | 3            |
| 23     | US-004-003     | Suscripción a Newsletter               | Como visitante, quiero suscribirme a un boletín informativo para recibir actualizaciones y noticias sobre propiedades. | Given un visitante quiere recibir actualizaciones, when se suscribe al boletín informativo, then el sistema debe añadir su dirección de correo a la lista de suscriptores y enviar confirmación de la suscripción. | 3            |
| 24     | EPIC-005       | Gestión de Nuevos Inmuebles            | Permitir a los usuarios agregar nuevos inmuebles al sistema, gestionar documentos legales, actualizar propietarios y realizar un seguimiento de la valorización. | Given un usuario (administrador o propietario) desea agregar un nuevo inmueble al sistema, when completa el formulario de creación del inmueble, then el sistema debe permitirle ingresar toda la información relevante, cargar documentos legales, actualizar información de propietarios y realizar un seguimiento de la valorización del inmueble. | -            |
| 25     | US-005-001     | Agregar Nuevo Inmueble                 | Como usuario, quiero agregar un nuevo inmueble al sistema con toda la información relevante.       | Given el usuario desea agregar un nuevo inmueble, when completa el formulario de creación, then el sistema debe permitirle ingresar detalles como ubicación, características, fotos, y documentos legales. | 8            |
| 26     | US-005-002     | Actualizar Información de Propietario  | Como usuario, quiero actualizar la información del propietario del inmueble en el sistema.         | Given el usuario necesita actualizar información del propietario, when realiza los cambios, then el sistema debe guardar y reflejar los nuevos datos del propietario. | 5            |
| 27     | US-005-003     | Gestionar Documentos Legales           | Como usuario, quiero gestionar los documentos legales asociados con los inmuebles.                 | Given el usuario tiene documentos legales para un inmueble, when sube o actualiza estos documentos, then el sistema debe permitirle gestionar y visualizar estos documentos de manera segura. | 5            |
| 28     | US-005-004     | Seguimiento de Valorización            | Como usuario, quiero realizar un seguimiento de la valorización de mis inmuebles a lo largo del tiempo. | Given el usuario quiere monitorear la valorización de un inmueble, when consulta el historial de valorización, then el sistema debe mostrar la evolución del valor del inmueble con gráficos e informes. | 5            |



# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
Descripcion del porque estos elementos seran importantes

**Color:** Se escogieron colores en tonalidadesa azules que buscan representar seguridad y confianza. Estos colores se alinean con el tipo de servicio que brindamos y el tipo de usuario que buscamos.

<div text-align="center">
    <img width="501"  alt="image" src="https://github.com/user-attachments/assets/92dde2f0-29e9-4e55-9ffb-b5397e55c25f">

</div>

**Tipografia:** Montserrat es una fuente que tiene un estilo contemporáneo con formas geométricas suaves, perfecta para proyectos modernos y elegantes. Estos aspectos son perfectos para transmitir confianza en los usuarios sin perder estilo.

<img src="./assets/Chap-IV/Tipografia1.png" width="200" height="300">

**Branding:** El nombre del producto es PropiConnect, el cual cuenta con un logo representado por el icono de una vivienda con tonos de azul rodeandola. El color azul busca transmitir confianza y seguirdad, por esto mismo, ilumina a la vivienda.

<div text-align="center">
<img width="512" alt="image" src="https://github.com/user-attachments/assets/46950447-9d21-4f2d-a377-47ee27fd011f">

</div>

### 4.1.2. Web Style Guidelines.
Descripcion de los elementos que se utilizaran en el web app

**Background:** Para los colores del fondo optamos por realizar un contraste entre blancos y negros para que nuestros colores azules resulten mas llamativos e intensos. 

<div text-align="center">
    <img width="494" alt="image" src="https://github.com/user-attachments/assets/8f855683-ed55-4e2b-8def-8c47df0f12ca">

</div>

**Text Styles:** 

<div text-align="center">
<img src="./assets/Chap-IV/Tipografia1.png" width="200" height="300">
</div>

**Button Styles:** Para el estilo de los botones se eligio un azul mas vivo que los demas, que se torna a un tono mas oscuro cuando se mantiene el mouse encima.

<div text-align="center">
<img width="844" alt="image" src="https://github.com/user-attachments/assets/3c50fde5-3852-4c63-9dcf-3ccf817ba17e">

</div>

**Icons:** Los iconos a utilizar estan relaciionados a elementos interactivos como botones. Esto buscando que los botones y sus funcionalidades sean mas llmativos.

<div text-align="center">
<img width="197" alt="image" src="https://github.com/user-attachments/assets/424ae182-b005-4894-af60-1c4a046490ca">

</div>

## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
El Sistema de Organización planteado tiene como objetivo facilitar la interacción entre el usuario y la aplicación web y garantizar todos los servicios que ofrece PropiConnect. En cuanto a la organización visual del contenido será de forma jerárquica (visual hierarchy). En la landing page se busca destacar elementos claves como el registrar propiedad o el alquilar una.

Además, se utilizarán organización secuencial (step-by-step to accomplish) en procesos como el registro del usuario y configuración del perfil.

En cuanto la organización matricial se aplicará filtros de búsqueda respecto a ubicacion geografica, tipo de propiedad (casa, departamento, etc), costo, cantidad de habitaciones, camas o baños, si tiene cochera o si se encuentra a la venta o para alquilar.

La categorización de audiencias se va a dividir en dos por los roles del usuario como propietario e inquilino.

### 4.2.2. Labeling Systems.
En PropiConnect, el sistema de etiquetas será diseñado para que los usuarios encuentren fácilmente la información que buscan, haciéndolo muy intuitivo y accesible.

### Etiquetas:

Inicio: Boton que te redirige a la pagina principal en el logo

Servicios: Se muestran los servicios que ofrece el aplicativo

Equipo: Seccion que habla del equipo

Planes: Son una suscripción mensual donde te brindan
diferentes beneficios según tu tipo de plan

Testimonios: Muestra reseñas y experiencias positivas que los usuarios se han llevado con el servicio

### 4.2.3. SEO Tags and Meta Tags

En esta sección, se describen las etiquetas SEO y Meta que se utilizarán para identificar y posicionar el sitio web y landing page de ArtCollab de manera única en internet. Estas etiquetas son fundamentales para que el sitio sea fácilmente encontrado por los usuarios a través de los motores de búsqueda como Google, Bing y otros. La optimización de estas etiquetas aumenta la visibilidad del sitio y mejora su posicionamiento en los resultados de búsqueda, lo que puede atraer más visitantes interesados en nuestro aplicativo.

\<title\>PropiConnect Oficial Landing Page\</title\>

\<meta name="description" content="PropiConnect Landing Page where you can
find a presentation of all the main features of our app."\>

\<meta name="keywords" content="tennant, homeowner, writers, rent, house, department, vacation"\>


  

### 4.2.4. Searching Systems.

Dada la necesidad del usuario a buscar diversas propiedades segun sus preferencias, ya sea ubicacion o precio como las habitaciones que contiene.Al realizar una busqueda, el usuario recibira una lista de opciones que varian segun las magnitudes seleccionadas en su busqueda. De esta forma, el usuario puede visualizar el contenido que ofrece el usuario de fora ordenada sin sentirse saturado. La interfaz de busqueda planteada permite al usuario filtrar la propiedad por sus necesidades de espacio, su ubicacion georgafica y su sustento econoico.


### 4.2.5. Navigation Systems.
La Navegacion utiliza un Hierarchical Navigation System, que busca hacer las funciones vitales de acceso inmediato. De esta forma el usuario obtendra una respuesta rapida a sus busquedas mas rapidas dentro de la aplicaccion, sin perder la oportunidad de utilizar funciones mas complejas. 
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.

#### Inicio
<img src="./assets/Chap-IV/Landing-Wireframe-inicio.png">


#### Servicios
<img src="./assets/Chap-IV/Landing-Wireframe-servicio.png">


#### Equipo 
<img src="./assets/Chap-IV/Landing-Wireframe-equipo.png">


#### Planes
<img src="./assets/Chap-IV/Landing-Wireframe-planes.png">



### 4.3.2. Landing Page Mock-up.

<img src="./assets/Chap-IV/Landing-Mockup-1.png">
<img src="./assets/Chap-IV/Landing-Mockup-2.png">
<img src="./assets/Chap-IV/Landing-Mockup-3.png">
<img src="./assets/Chap-IV/Landing-Mockup-4.png">
<img src="./assets/Chap-IV/Landing-Mockup-5.png">

## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
[Link del figma](https://www.figma.com/design/PFdQCAPgkfxaQWl5HyvFuQ/Wireframe?node-id=0-1&t=1whP4kfGbQn51RYv-1)
<img src="./assets/Chap-IV/WireFrame.png">

<!-- ![Web Aplication Wireframe](image.jpg) -->
### 4.4.2. Web Applications Wireflow Diagrams.
[Link del LucidChart](https://lucid.app/lucidchart/ab81aedc-cdc3-4a19-8bb2-e78e3361f809/edit?viewport_loc=1995%2C-1401%2C4234%2C1967%2C0_0&invitationId=inv_0049bcb4-df36-4563-a1f4-200ffa80cb12)
<img src="./assets/Chap-IV/Wireflow.png">

<!-- ![Web Aplication Wireflow](image.jpg) -->
### 4.4.2. Web Applications Mock-ups.
[Link del figma](https://www.figma.com/design/CNycCh372SSE8sK0AYKVXD/MockUP?t=AQnl5jmqddVnLFiv-1)
<img src="./assets/Chap-IV/Mockup.png">

### 4.4.3. Web Applications User Flow Diagrams.
[Link del LucidCharp](https://lucid.app/lucidchart/93df40ef-a106-4551-8566-efd152394f37/edit?viewport_loc=105%2C86%2C4490%2C2086%2C0_0&invitationId=inv_36f3bd38-1c4a-4f3f-97bd-9039b7660e43)

<img src="./assets/Chap-IV/Diagrama_de_flujo.jpeg">

## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://www.figma.com/design/CNycCh372SSE8sK0AYKVXD/MockUP?t=AQnl5jmqddVnLFiv-1)
[URL del video demostrativo Propotipo](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e414_upc_edu_pe/Ed6aAlSBz-dFs9flYGyWdAYB3Lj7ZsznefoC3gwDrZPebg?e=Lfpz0Z&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)
[URL del video demostrativo de la Landing Page](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e414_upc_edu_pe/EbY4GmAm4ytCs2vozXOX7QIBxFYHk7sACTJyRimxy5S2dQ?e=vzSloV&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<img src="./assets/Chap-IV/prototipo.png">

## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

<img src="./assets/Chap-IV/ContextDiagram.png">

### 4.6.2. Software Architecture Container Diagram.

<img src="./assets/Chap-IV/ContainerDiagram.png">

### 4.6.3. Software Architecture Component Diagram.

API Rest Component Diagram:

<img src="./assets/Chap-IV/API_Rest_Component_Diagram.png">

User Bounded Context Component Diagram:

<img src="./assets/Chap-IV/User_Bounded_Context_Component_Diagram.png">

Content Bounded Context Component Diagram:

<img src="./assets/Chap-IV/Content_Bounded_Context_Component_Diagram.png">

Service Bounded Context Component Diagram:

<img src="./assets/Chap-IV/Service_Bounded_Context_Component_Diagram.png">

Monetization Bounded Context Component Diagram:

<img src="./assets/Chap-IV/Monetization_Bounded_Context_Component_Diagram.png">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
User Bounded Context

   <img src="./assets/Chap-IV/PropiConnect_UserContext.png">
Content Bounded Context

   <img src="./assets/Chap-IV/PropiConnect_UserContext.png">

Collaboration Bounded Context

   <img src="./assets/Chap-IV/PropiConnect_MonetizationContext.png">

Monetization Bounded Context

   <img src="./assets/Chap-IV/PropiConnect_ServiceContext.png">

### 4.7.2. Class Dictionary.
<hr>
<br>

**User Bounded Context** 

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">User</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase User es una clase abstracta que representa a los usuarios de la aplicación. Tiene una relación de asociación con UserFactory y Account.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">HomeOwner</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase HomeOwner representa a los escritores de la aplicación. Tiene una relación de asociación con HomeOwnerFactory.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Tennant</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Tennant representa a los inquilinos de la aplicación. Tiene una relación de asociación con TennantFactory.</td>
  </tr>
<table>


<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserFactory es una clase abstracta hija de UserManager. Se encarga de definir la creación de los usuarios del sistema. Tiene una relación de asociación con User.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que define la creación de nuevos tipos de objetos.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">HomeOwnerFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase HomeOwnerFactory es una clase hija de UserFactory. Se encarga de la creación de los usuarios propietarios en la aplicación. Tiene una relación de asociación con HomeOwner.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo HomeOwner.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">TennantFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase TennantFactory es una clase hija de UserFactory. Se encarga de la creación de los usuarios inquilinos en la aplicación. Tiene una relación de asociación con Tennant.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo Illustrator.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserManager</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserManager se encarga de la gestión de los usuarios en el sistema.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createUser()</td>
    <td colspan="2" valign="top">Método que crea nuevos objetos de tipo User.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">getUser()</td>
    <td colspan="2" valign="top">Método que obtiene el identificador de un usuario.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">updateUser()</td>
    <td colspan="2" valign="top">Método que actualiza los atributos de un usuario.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top">deleteUser()</td>
    <td colspan="2" valign="top">Método que elimina a un usuario del sistema.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Account</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Account representa la cuenta de los usuarios de la aplicación. Tiene una relación de asociación con Subscription y User.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Subscription</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Subscription representa la suscripción a un plan de la aplicación.Tiene una relación de asociación con Account y Plan.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Plan</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Plan representa a los planes de suscripción de la aplicación. Tiene una relación de asociación con Subscription.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">Observer</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Observer es una clase abstracta que se encarga de definir el comportamiento de UserObserver y SuscriptionObserver. Tiene una relación de herencia con estás mismas.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que define el comportamiento cuando ocurren cambios de estado en los sujetos observados.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">SuscriptionObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase SuscriptionObserver es una clase hija de Observer. Se encarga de gestionar el estado de las suscripciones del sistema. Se encuentra asociada a Subscription.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que recibe la notificación y responde al cambio en el estado de Subscription.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">UserObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase UserObserver es una clase hija de Observer. Se encarga de gestionar los estados de los usuarios en el sistema. Se encuentra en una asociación con UserManager.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">update()</td>
    <td colspan="2" valign="top">Método que recibe la notificación y responde al cambio en el estado de UserManager.</td>
  </tr>
<table>

<br>

**Content Bounded Context**

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Property </td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Property representa las obras que se encuentran en la aplicación. Tiene una relación de asociación con Property Factory, de composición con LegalDocument y Value.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">LegalDocument</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase LegalDocument representa los documentos legales relacionados a una Propiedad. Tiene una relación de composición con Property.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Value</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Value Los valores que toma la propiedad a lo largo del tiempo. Tiene una relación de composición con Property.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ContentFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ContentFactory es una clase abstracta, padre de PropertyFactory, encargada de definir la creación del contenido de la aplicación. </td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createContent()</td>
    <td colspan="2" valign="top">Método que define la creación de objetos de un tipo de contenido.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">PropertyFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase PropertyFactoryes una clase hija de ContentFactory. Se encarga de registrar nuevas propiedades en la plataforma. Tiene una relación de asociación con Property.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createBook()</td>
    <td colspan="2" valign="top">Método que crea objetos del tipo Property</td>
  </tr>
<table>


<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ViewStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ViewStrategy es una clase abstracta que define las estrategias para visualizar el contenido de la Web Application. Tiene una relación de generalización con PropertyViewStrategy.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">viewContent()</td>
    <td colspan="2" valign="top">Método que define la estrategia en la que se visualizan las propiedades.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">PropertyViewStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase PropertyViewStrategyes una clase hija de ViewStrategy. Es una interfaz que permite visualizar las caracteristicas de las propiedades mediante estrategias. Tiene una relación de generalización con ListViewStrategy, DetailedViewStrategy y ThumbnailViewStrategy y una de asociación con Property.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">viewContent()</td>
    <td colspan="2" valign="top">Método que define la estrategia en la que se visualizan las propiedades, más no su lógica.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ListViewStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ListViewStrategy es una clase hija de PropertyViewStrategy. Es una de las estrategias de visualización de las propiedades.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">viewContent()</td>
    <td colspan="2" valign="top">Método que permite ver las propiedades como una lista.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">DetailedViewStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase DetailedViewStrategy es una clase hija de PropertyViewStrategy. Es una de las estrategias de visualización de las propiedades.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">viewContent()</td>
    <td colspan="2" valign="top">Método que permite visualizar de manera más detallada las caracteristicas de una propiedad.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ThumbnailViewStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ThumbnailViewStrategy es una clase hija de PropertyViewStrategy. Es una de las estrategias de visualización de las propiedades.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">viewContent()</td>
    <td colspan="2" valign="top">Método que permite visualizar en forma de miniaturas la propiedad en cuestion, informacion suficiente como para llamar la antencion pero no demsiada como para saturarse.</td>
  </tr>
<table>

<br>

**ServiceBounded Context**

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Contract</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Contract representa el medio legal de intercambio de derechos de uso de una propiedad. </td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">HomeOwner</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase HomeOwner representa a los propietarios dentro de la aplicación. Tiene una relación de asociación con Contract.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Tennant</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Tennant representa a los inquilinos de la aplicación. Tiene una relación de asociación con Contract y una de agregacion con TennantGroup.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">ContractHistory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ContractHistory representa el historial de contratos del Usuario. Tiene una relación de agregación con Contract.</td>
  </tr>
<table>


<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">TennantGroup</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase TennantGroup es una clase abstracta que Gestiona la funcionalidad de los multiples compradores interesados en una misma propiedad que comparten un porcentaje del gasto total.. Tiene una relación de asociacion con Contract y GroupFactory.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">AddTennant()</td>
    <td colspan="2" valign="top">Método que agrega un comprador a la lista de compradores en el contrato.</td>
  </tr>
<table>



<table border="1" width="40%">
  <tr>
ServiceFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ServiceFactory es una clase abstracta que define la creación de objetos de colaboración. Tiene una relación de agregación con GroupFactory y ContractFactory.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">GroupFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase GroupFactory es una clase hija de ServiceFactory. Se encarga de la creación de nuevos grupos de compra en la aplicación. Tiene una relación de asociación con TennantGroup.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createGroup()</td>
    <td colspan="2" valign="top">Método que crea objetos de tipo TennantGroup.</td>
  </tr>
<table>

<table border="1" width="50%">
  <tr>
    <td colspan="2" valign="top">ContractFactory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase ContractFactory es una clase hija de ServiceFactory. Se encarga de crear los nuevos contratos de propiedad dentro de la aplicación. Tiene una relación de asociación con Contract.</td>
  </tr>
  <tr>
    <td colspan="1" valign="top" width="40%">Método</td>
    <td colspan="2" valign="top">Descripción</td>
  </tr>
   <tr>
    <td colspan="1" valign="top">createContract()</td>
    <td colspan="2" valign="top">Método que crea objetos de tipo Contract.</td>
  </tr>
<table>



<br>

**Monetization Bounded Context**

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">Subscription</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Subscription representa la suscripción a un plan de la aplicación. Tiene una relación de asociación con SubscriptionObserver, SubscriptionHistory, Plan y SubscriptionManager</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">SubscriptionHistory</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase SubscriptionHistory representa el historial de Subscription. Tiene una relación de asociación con Payment.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Plan</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Plan representa los planes de suscripción de la aplicación. Tiene una relación de asociación con Subscription.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Payment</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Payment representa la información de los pagos de la aplicación. Tiene una relación de asociación con PaymentObserver, Subscription y PaymentFacade.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">PaymentFacade</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase PaymentFacade facilita la interacción con los componentes y servicios que conforman los pagos en la plataforma.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">Observer</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Observer es una clase abstracta que define el comportamiento de SubscriptionObserver y PaymentObserver.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">SubscriptionObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Observer es una clase hija de Observer. Se encarga de observar los cambios de estado de Subscription. Tiene una relación de asociación con Subscription.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">PaymentObserver</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Observer es una clase hija de Observer. Se encarga de observar los cambios de estado de Payment. Tiene una relación de asociación con PaymentObserver.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">Commission</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Commission representa las comisiones que se pueden realizar en la aplicación. Tiene una relación de asociación con Writer, Reader, Illustrator y Payment.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">HomeOwner</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase HomeOwner representa a los propietarios dentro de la aplicación. Tiene una relación de asociación con Rent y SubscriptionManager.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="1" valign="top">Tennant</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase Tennant representa a los inquilinos dentro de la aplicación. Tiene una relación de asociación con Rent y SubscriptionManager.</td>
  </tr>
<table>



<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">SubscriptionManager</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase SubscriptionManager realiza la gestión de los objetos tipo Subscription.</td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">SuscriptionStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase SuscriptionStrategy es una interfaz la cual permite visualizar las suscripciones por usuario mediante distintas estrategias. Tiene una relación de tipo asociación con SubscriptionManager y tres de generalización con TennantSuscriptionStrategy y HomeOwnerSuscriptionStrategy.</<td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">TennantSuscriptionStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase TennantSuscriptionStrategy es una clase hija de SuscriptionStrategy. Es una de las estrategias de visualización de suscripción
    para los inquilinos.</<td>
  </tr>
<table>

<table border="1" width="40%">
  <tr>
    <td colspan="2" valign="top">HomeOwnerSuscriptionStrategy</td>
  </tr>
    <tr>
    <td colspan="2" valign="top">La clase HomeOwnerSuscriptionStrategy es una clase hija de SuscriptionStrategy. Es una de las estrategias de visualización de suscripción
    para los propietarios.</<td>
  </tr>
<table>
    
## 4.8. Database Design.
    
### 4.8.1. Database Diagram.
<div style="display:flex; justify-content:center; flex-direction:column;">
   <p>A continuación se detalla el modelo físico realizado para esta entrega, donde se consideró los requerimientos necesarios para el negocio.</p>
    <img width="938" alt="image" src="https://github.com/user-attachments/assets/2b3fbade-80d3-4e87-bfa9-77ef4cd4d1d4">
</div>


**Capítulo V: Product Implementation, Validation & Deployment**

**5.1. Software Configuration Management.**

**5.1.1. Software Development Environment Configuration.**

A continuación, presentaremos los programas de software que hemos utilizado en el desarrollo de nuestro proyecto.

**Project Management**

- **Whatsapp:** <https://web.whatsapp.com/>

  Se utilizó la plataforma de WhatsApp para organizar las tareas del equipo y proporcionar apoyo mutuo durante el trabajo.

**Product UX/UI Design**

- **Miro:** <https://miro.com/es/>

  Empleamos Miro para desarrollar el Lean UX Canvas.

- **Uxpressia:**  <https://uxpressia.com/>

  Utilizamos Uxpressia para crear User Personas, Empathy maps y Journey maps.

- **Figma: <https://www.figma.com>**

  Figma fue nuestra herramienta principal para diseñar wireframes, wireflows, mockups del landing page y para la creación de prototipos de aplicaciones web.

- **LucidChart:** <https://www.lucidchart.com/pages/>

  Para crear los Impact maps

**Software Development**




- **Landing Page:** Para la creación de nuestra página de inicio, hemos empleado HTML5, CSS y Javascript.

**Software Testing**

Hemos realizado pruebas de software en el landing page y la aplicación web utilizando las herramientas de desarrollo de los navegadores web como Google Chrome y Brave.

**IDE's de desarrollo**

- **Webstorm: <https://www.jetbrains.com/webstorm/>**

  Utilizamos Webstorm, un IDE centrado en el desarrollo frontend, por su variedad de herramientas que agilizan el proceso de desarrollo.

**Software Deployment**

- **Github Pages:** <https://pages.github.com/>

  Utilizamos Github Pages para desplegar nuestro landing page, vinculando el repositorio de GitHub para que se encargue automáticamente del despliegue.

**Software Documentation**

- **Google Docs: <https://docs.google.com/document/u/0/>**

  Esta plataforma fue utilizada para enviar el progreso de las tareas asignadas. Semanalmente se enviaban las asignaciones de cada integrante para el informe final.




- **Github: <https://github.com/>**

  Utilizamos GitHub para la documentación del proyecto y el landing page, aprovechando su capacidad de desarrollo colaborativo y su registro de commits para demostrar la contribución de cada miembro.




- **Visual Paradigm:** Utilizamos Visual Paradigm para crear diagramas C4 de nuestro proyecto.




- **Vertabelo:** <https://vertabelo.com/>

  Vertabelo fue utilizado para diseñar la estructura de nuestra base de datos, siendo una aplicación web colaborativa.

### 5.1.2. Source Code Management

La administración y estructuración de las múltiples modificaciones se realizaron mediante la creación de un repositorio en GitHub para el proyecto. Nuestra organización se estructuró de la siguiente manera:

**Organización:**

<https://github.com/PropiConnect/Documentation>

**LandinPage:**

<https://propiconnect.github.io/LandingPage/>

**Ramas principales:**

**Rama “main”:** En esta rama se almacenan las versiones oficiales de nuestro repositorio para pasarlas a producción. Rama “develop”: Esta rama se utilizará como punto de integración para las ramas de “feature”. Una vez que el  “head” sea estable y el equipo lo considere listo para el lanzamiento, se fusionará con la rama “release”.

**Ramas auxiliares:**

- **Rama “release”:** La rama “release” se emplea para la preparación del lanzamiento de una nueva versión en la rama “main” ayudando a controlar las versiones de código. Aquí se pueden solucionar errores menores y preparar los datos para la versión. Esta rama permitirá liberar a la rama “develop” de est as tareas preparatorias y evita demoras en el desarrollo mientras se prepara para el lanzamiento. 
- **Rama “feature”:** En las ramas “feature” se desarrollan las características generales que se integrarán en la rama “develop”. Estas características son aquellas funcionalidades solicitadas por los usuarios tanto en la página de inicio como en la aplicación web. Por ejemplo, la rama feature/navbar.
- **Rama “hotfix”:** Esta rama se utiliza para corregir urgentemente errores en la última versión de la rama “main” que no pueden esperar hasta el próximo lanzamiento para ser solucionados.

**5.1.3. Source Code Style Guide & Conventions**

Para garantizar la coherencia y calidad en el desarrollo de nuestra Landing Page y la aplicación web, adoptaremos convenciones específicas para cada uno de los lenguajes y tecnologías utilizados:

**HTML**

- **Tipo de Documento:** Declararemos el tipo de documento al comienzo de cada archivo HTML usando <!DOCTYPE html>.
- **Minúsculas en Etiquetas y Atributos**: Todas las etiquetas y atributos se escribirán en minúsculas, como <body> y <p>.
- **Cierre de Etiquetas**: Todas las etiquetas deben cerrarse adecuadamente para mantener la estructura del documento.
- **Uso de Comillas:** Utilizaremos comillas en los valores de los atributos para asegurar que sean interpretados correctamente, por ejemplo, <a href="https://example.com">.
- **Especificación de Imágenes:** Incluir atributos como alt, width y height en las etiquetas de imagen para mejorar la accesibilidad y el diseño.
- *Evitar Espacios en Atributos:* No se dejarán espacios alrededor del signo igual en los atributos, como en <link rel="stylesheet" href="styles.css">.
- **Elemento:** No omitiremos el elemento , ya que es crucial para la optimización del motor de búsqueda y la usabilidad del sitio.
- **Atributos de Idioma y Codificación:** Utilizaremos el atributo lang para especificar el idioma del documento y <meta charset="UTF-8"> para definir la codificación de caracteres.

**CSS**

- **Uso de HTTPS:** Todos los recursos externos, como fuentes y multimedia, se cargarán mediante HTTPS para garantizar la seguridad. Ejemplo: @import 'https://fonts.googleapis.com/css?family=Open+Sans';.
- **Nomenclatura en Minúsculas:** Todos los nombres de elementos, atributos, y valores de atributos deberán estar en minúsculas para mantener la uniformidad, ej.: color: #e5e5e5;.
- **Nombres de Clases Descriptivos:** Las clases deben nombrarse de manera que describan su función claramente y de forma breve, utilizando guiones para separar palabras, ej.: .barra-navegacion, .autor-articulo.
- **Propiedades Abreviadas**: Donde sea posible, se utilizarán formas abreviadas de propiedades CSS para reducir el código y mejorar la legibilidad, ej.: border-top: 0;.
- **Colores Hexadecimales Cortos:** Usaremos la notación hexadecimal de tres caracteres cuando sea posible, ej.: color: #ebc;.
- **Orden Alfabético:** Las declaraciones dentro de un bloque CSS se ordenarán alfabéticamente para facilitar la búsqueda y el mantenimiento.
- **Uso de Punto y Coma:** Cada declaración debe terminar con un punto y coma para evitar errores en la interpretación del código, ej.: display: block;.
- **Espaciado en Declaraciones:** Se incluirá un espacio después de los dos puntos en cada declaración y entre las propiedades y las llaves que abren el bloque, ej.: font-weight: bold;.
- **Comillas Simples para Valores de Atributos:** Utilizaremos comillas simples para encerrar los valores de los atributos en CSS, ej.: font-family: 'Open Sans', Arial, sans-serif;.

**Gherkin**

- **Estructura de Archivos:** Los archivos .feature contendrán las historias de usuario y describirán las características de la aplicación de manera estructurada.
- **Palabra Clave 'Feature':** Se utilizará para introducir y agrupar funcionalidades relacionadas dentro del archivo.
- **Escenarios y Ejemplos:** Utilizaremos Scenario para definir situaciones específicas y Example para casos de uso concretos.
- **Pasos Dado, Cuando, Entonces:** Given establece el contexto, When describe la acción o evento, y Then define el resultado esperado. And se usa para añadir pasos adicionales sin repetir el contexto o acción.
- **Tablas de Datos:** Emplearemos el carácter | para crear tablas de datos que permitan pasar múltiples valores en las pruebas, facilitando así la definición de múltiples escenarios en un solo paso.

**JavaScript y TypeScript**

- **Convenciones de Nombres**: Seguiremos las convenciones de camelCase para variables y funciones, PascalCase para clases en TypeScript, y UPPER\_CASE\_WITH\_UNDERSCORES para constantes en ambos lenguajes.
- **Uso de let y const:** Preferimos let y const sobre var para declarar variables.
- **Punto y Coma:** Incluir un punto y coma al final de cada instrucción para evitar errores de compilación.

**Angular**

- **Nomenclatura de Archivos:** Usaremos kebab-case para los nombres de archivos, como mi-componente.component.ts.
- **Clases y Componentes:** Nombraremos las clases y componentes usando UpperCamelCase, por ejemplo, MiComponente.
- **Evitar Dependencias Circulares:** Evitaremos dependencias circulares para mantener la modularidad y reusabilidad del código.
- **Modo Estricto en TypeScript:** Activaremos el modo estricto en TypeScript para mejorar la verificación de tipos y la calidad del código.

**5.1.4. Software Deployment Configuration.**

**Markdown:**

Creamos un repositorio en la organización de nuestro grupo en GitHub y subimos los

archivos necesarios para que el servidor pueda mostrar la landing page. Utilizamos

Github Pages para el despliegue.

1. Cargamos los archivos necesarios para subirlo al repositorio.

2. Posteriormente nos dirigimos a settings y ubicamos el apartado, Pages. En Branch seleccionamos la rama main y posteriormente, guardar. 

3. Luego de cierto tiempo, github nos envía el enlace de nuestra página.


### 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1
Para el primer sprint, se planificó la creación de la landing page de la plataforma, junto con la implementación básica de la navegación entre las secciones de la página. El objetivo principal era desarrollar una interfaz atractiva que permita a los usuarios obtener una introducción clara de la plataforma y sus funcionalidades.

#### 5.2.1.2. Sprint Backlog 1
Las tareas incluidas en el Sprint Backlog para este sprint fueron:

- Crear el diseño inicial de la landing page.
- Implementar las secciones de presentación de la empresa, servicios, equipo y planes.
- Crear un menú de navegación con enlaces a todas las secciones.
- Desarrollar la funcionalidad de registro e inicio de sesión.
- Configurar el repositorio en GitHub y desplegar la landing page usando GitHub Pages.

#### 5.2.1.3. Development Evidence for Sprint Review
Durante el desarrollo de la landing page, implementamos un diseño responsivo utilizando HTML y CSS, asegurándonos de que las secciones fueran accesibles tanto en dispositivos móviles como de escritorio. Además, se incluyó un menú de navegación con las secciones principales: Inicio, Servicios, Equipos, Planes y Testimonios.

#### 5.2.1.4. Testing Suite Evidence for Sprint Review
Para validar la funcionalidad de la landing page, se realizaron pruebas de navegación y visualización en diferentes dispositivos y tamaños de pantalla. Se verificó que todos los enlaces y botones fueran funcionales y que el diseño se mantuviera consistente en diferentes navegadores.

#### 5.2.1.5. Execution Evidence for Sprint Review
Lo que hicimos fue crear un repositorio en GitHub y aprovechamos el servicio de GitHub Pages para desplegar la landing page directamente desde ese repositorio. Esto nos permitió realizar pruebas de acceso en tiempo real y asegurarnos de que el sitio estuviera disponible públicamente.

#### 5.2.1.6. Services Documentation Evidence for Sprint Review
Se documentaron los servicios ofrecidos en la landing page, incluyendo:

1. **Gestión de Propiedades**: Alquiler y venta de propiedades, administración de pagos, creación y gestión de contratos.
2. **Gestión de Inquilinos**: Pago de alquileres, notificaciones de pago, historial de pagos.
3. **Compra Compartida de Propiedad**: División de propiedad, distribución de ganancias.
4. **Gestión de Nuevos Inmuebles**: Registro y actualización de inmuebles, seguimiento de valorización.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review
La landing page fue desplegada en GitHub Pages. Se configuró el dominio proporcionado por GitHub y se vinculó directamente al repositorio para facilitar futuras actualizaciones del código.

#### 5.2.1.8. Team Collaboration Insights during Sprint
El equipo trabajó de manera colaborativa utilizando GitHub como sistema de control de versiones, lo que permitió que cada miembro pudiera realizar cambios y revisiones en el código de manera ágil. La integración continua de los cambios en GitHub facilitó el seguimiento del progreso y la resolución de conflictos.


### 5.2.2. Sprint 2
Durante este sprint realizamos la aplicación web en la que mostraremos los datos del dominio del negocio

#### 5.2.2.1. Sprint Planning 2

Para el primer sprint el equipo estableció que el desarrollo de las tareas serían unas 20 horas.

| Sprint #        | Sprint 1           |
|-----------------|--------------------|
| **Sprint Planning Background** | **Información del Sprint**  |
| **Date**        | 2024/09/20         |
| **Time**        | 10:30 PM           |
| **Location**    | Google Meet        |
| **Prepared by** | Gustavo Poma       |
| **Attendees** (to planning meeting) |  - Gustavo Poma  <br>- Daniel del Castillo  <br>- Carlos Sánchez  <br>- Daniel Ruiz  <br>- Oscar Antayhua  |
| **Sprint 1 Review Summary** | Este es el segundo sprint a realizar por el equipo. |
| **Sprint 1 Retrospective Summary** | Acuerdo de la implementación de la aplicacion web|
| **Sprint Goal & User Stories**|
| Sprint 2 Goal |  - Desarrollar una landing page usando HTML, CSS y JavaScript.  - Landing page responsive.  |
| Sprint 2 Velocity | 25 |
| **Sum of Story Points** | 25 |

#### 5.2.2.2. Sprint Backlog 2

| ID     | Código         | User Story                             | Descripción                                                                                           | Story Points  |
|--------|----------------|----------------------------------------|-------------------------------------------------------------------------------------------------------|---------------|
| 2      | US-001-001     | Alquilar Propiedad                     | Como propietario, quiero poder alquilar mi propiedad para recibir ingresos regulares.                 | 3             |
| 3      | US-001-002     | Vender Propiedad                       | Como propietario, quiero poder vender mi propiedad.                                                   | 1             |
| 4      | US-001-003     | Administrar Pagos de Alquiler          | Como propietario, quiero poder verificar si los alquileres se han pagado y recibir recordatorios de pago. | 1             |
| 5      | US-001-004     | Crear Contratos de Alquiler            | Como propietario, quiero poder crear contratos para los alquileres de mis propiedades.                | 2             |
| 6      | US-001-005     | Ver Historial de Contratos             | Como propietario, quiero ver el historial de contratos de alquiler para una propiedad.                | 3             |
| 7      | US-001-006     | Editar Detalles de Propiedad           | Como propietario, quiero editar los detalles de mi propiedad (ej. descripción, fotos) después de publicarla. | 2             |
| 8      | US-001-007     | Verificar Disponibilidad de Propiedad  | Como propietario, quiero verificar la disponibilidad de mi propiedad para alquilarla o venderla.      | 3             |
| 9      | EPIC-002       | Gestión de Inquilinos                  | Permitir a los inquilinos gestionar sus alquileres, incluyendo el pago de alquileres y la recepción de notificaciones. |       2     |
| 10     | US-002-001     | Pagar Alquiler                         | Como inquilino, quiero poder pagar el alquiler de la propiedad que estoy alquilando.                  | 3           |
| 11     | US-002-002     | Recibir Notificaciones de Pago         | Como inquilino, quiero recibir notificaciones cuando se acerque la fecha de pago del alquiler y los servicios. | 3             |
| 12     | US-002-003     | Ver Historial de Pagos                 | Como inquilino, quiero ver el historial de mis pagos para asegurarme de que todos los pagos han sido realizados correctamente. | 2             |
| 13     | US-002-004     | Solicitar Mantenimiento                | Como inquilino, quiero poder solicitar mantenimiento para problemas en la propiedad que estoy alquilando. | 3             |



#### 5.2.2.3. Development Evidence for Sprint Review
<img src="./assets/Insights/Captura de pantalla 2024-09-27 011554.png">

#### 5.2.2.4. Testing Suite Evidence for Sprint Review
Para validar la funcionalidad de la web aplication, se realizaron pruebas de navegación y visualización en diferentes dispositivos y tamaños de pantalla. Se verificó que todos los enlaces y botones fueran funcionales y que el diseño se mantuviera consistente en diferentes navegadores.

#### 5.2.2.5. Execution Evidence for Sprint Review
Lo que hicimos fue crear un repositorio en Github y aprovechamos el servicio de Firebase tools para desplegar la web aplication directamente desde ese repositorio. Esto nos permitió realizar pruebas de acceso en tiempo real y asegurarnos de que el sitio estuviera disponible públicamente.

#### 5.2.2.6. Services Documentation Evidence for Sprint Review
Se documentaron los componentes para realizar las siguientes paginas

1. **Gestión de Propiedades**: Alquiler y venta de propiedades, administración de pagos, creación y gestión de contratos.
2. **Gestión de Inquilinos**: Pago de alquileres, notificaciones de pago, historial de pagos.
3. **Compra Compartida de Propiedad**: División de propiedad, distribución de ganancias.
4. **Gestión de Nuevos Inmuebles**: Registro y actualización de inmuebles, seguimiento de valorización.

#### 5.2.2.7. Software Deployment Evidence for Sprint Review
La landing page fue desplegada en Firebase. Se configuró el dominio proporcionado por Firebase y se vinculó directamente al repositorio para facilitar futuras actualizaciones del código.

[URL de la aplicacion web en firebase](https://propiconnect.web.app)

#### 5.2.2.8. Team Collaboration Insights during Sprint
El equipo trabajó de manera colaborativa utilizando GitHub como sistema de control de versiones, lo que permitió que cada miembro pudiera realizar cambios y revisiones en el código de manera ágil. La integración continua de los cambios en GitHub facilitó el seguimiento del progreso y la resolución de conflictos.



## 5.3. Validation Interviews.
### 5.3.1. Diseño de Entrevistas.
**Preguntas generales:**

1. ¿Cuál es su nombre? 
2. ¿Qué edad tiene? 
3. ¿A qué se dedica? 

**Preguntas para Segmento 1 (Propietarios)**
1. ¿Cuales son los mayores desafíos que enfentas al vender propiedades actualmente?
2. ¿Cómo te gustaría que una plataforma digital te ayudara a encontrar y conectar con potenciales compradores?
3. ¿Qué características te harían preferir una nueva aplicación sobre las plataformas que usas actualmente?
4. ¿Qué información adicional te gustaría tener sobre los compradores antes de interactuar con ellos?
5. ¿Qué tan frecuente es la venta de propiedades entre varias personas, y cómo se maneja ese proceso actualmente?
6. ¿Hay algo que consideras que falta en las plataformas inmobiliarias actuales? 

**Preguntas para Segmento 2 (Inquilinos/Compradores)**
1. ¿Qué características te gustaría ver en una plataforma de compra de inmuebles que te facilitarían la búsqueda y decisión de compra? 
2. ¿Qué tan importante es la posibilidad de comprar una propiedad en conjunto con otras personas?
3. ¿Qué tipo de información prefieres tener disponible cuando exploras una propiedad en línea?
4. ¿Qué factores influyen más en tu decisión de comprar una propiedad?
5. ¿Qué problemas has encontrado al utilizar otras plataformas de compra de inmuebles?
**Segmento 1**  
**Entrevista 1**

**Nombre:** Mateo Vilchez
**Edad:** 19 años 
**Ocupación:** Estudiante de Ingeniería de Software
**URL:** https://upcedupe-my.sharepoint.com/:v:/g/personal/u202015274_upc_edu_pe/EQdnVlI8nNNGisxHQgn-wXMB7hVaug2-vp_JxjA_vVMv3A?e=2prSu4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D 

<img src="assets/Chap-II/Entrevista Mateo Vilchez.png">


**Segmento 2**  
Entrevista 1
**Nombre**: Aldair Chuman
**Edad**: 22 años 
**Ocupación**: Ingeniero de Software  
**URL**: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e414_upc_edu_pe/ERYcC5TRz7lNgGgBlwIfcxgBluAvlZV4BrmAMOJg2lKB8g?e=gdnUAp&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D

<img src="./assets/Chap-II/entrevista-aldair.png">



### 5.3.3. Evaluaciones según heurísticas.
| HEURÍSTICA   | EVALUACIÓN  | NOTA      |
| --------------------------------------------- | ---------- | --------- |
| Visibilidad del estado del sistema            |            | {texto}   |
| Coincidencia entre el sistema y el mundo real |            | {texto}   |
| Control y libertad del usuario                |            | {texto}   |
| Consistencia y estándares                     |            | {texto}   |
| Prevención de errores                         |            | {texto}   |
| Mostrar antes que recordar                    |            | {texto}   |
| Flexibilidad y eficiencia de uso              |            | {texto}   |
| Diseño estético y minimalista                 |            | {texto}   |
| Comunicar errores con facilidad               |            | {texto}   |
| Ayuda y documentación                         |            | {texto}   |
## 5.4. Video About-the-Product.
[URL del video about the product](https://www.example.com)
# Conclusiones
{texto}
# Conclusiones y recomendaciones.
{texto}
# Video About-the-Team.
[URL del video about the team](https://www.example.com)

# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores


Colocar Imagen




#
