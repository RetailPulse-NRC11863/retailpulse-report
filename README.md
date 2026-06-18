![Logo UPC](assets/images/logo-upc.png)

**Nombre de la Universidad:** Universidad Peruana de Ciencias Aplicadas
**Facultad:** Ingeniería  
**Carrera:** Ingeniería de Software
**Ciclo:** 2026-10  

**Código del curso:** 1ASI0729  
**Nombre del curso:** Desarrollo de Aplicaciones Open Source
**NRC:** 11863  
**Nombre del profesor:** Iván Robles Fernández

**"Informe de Trabajo: TB1"**
**Nombre del startup:** RetailPulse

**Relación de integrantes:**

* U20241B331 - Faustino Hurtado, Anghelo Edwin
* U202319178 - Franco del Carpio, José María
* U20251C350 - Godoy Santillan, Jesus Andres
* U202310349 - Rubio Ortiz, Luis Sebastián
* U20211D989 - Vallejo Trujillo, Fabio Cesar

##### Abril, 2026

---

## Registro de Versiones del Informe

| Avance | Fecha | Autor | Descripción de Modificación |
|--------|------|------|-----------------------------|
| AV1 | 23/04/2026 | Equipo RetailPulse (Fabio Vallejo, Jesus Godoy, Luis Rubio, Anghelo Hurtado, José del Carpio) | Elaboración completa del informe incluyendo: Carátula, Project Report Collaboration Insights, Student Outcome, Capítulo I (Introducción), Capítulo II (Requirements Elicitation & Analysis), Capítulo III (Requirements Specification), Capítulo IV (Product Design), Capítulo V (Product Implementation, Validation & Deployment), Software Configuration Management, Software Development Environment Configuration, Source Code Management, Source Code Style Guide & Conventions, Software Deployment Configuration, Sprint Planning 1, Aspect Leaders and Collaborators, Sprint Backlog 1, Development Evidence, Execution Evidence, Services Documentation Evidence, Software Deployment Evidence, Team Collaboration Insights, Conclusiones, Bibliografía y Anexos. |
| TB1 | 12/05/2026 | Equipo RetailPulse (Fabio Vallejo, Jesus Godoy, Luis Rubio, Anghelo Hurtado, José del Carpio) | Actualización del informe para el Stage Review – Semana 7, incluyendo versión corregida y mejorada de los artefactos presentados previamente, actualización del Registro de Versiones del Informe, Project Report Collaboration Insights y Student Outcome. Se incorporó la nueva versión desplegada del Landing Page, la primera versión desplegada de Frontend Web Applications, el desarrollo de la sección 5.2.2 Sprint 2, Sprint Planning 2, Aspect Leaders and Collaborators, Sprint Backlog 2, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review, Team Collaboration Insights during Sprint, Conclusiones, Bibliografía y Anexos. Además, se consideran los archivos complementarios correspondientes, como proyectos de software, videos, documentos adicionales y archivo .zip de entrega. |
| AV2 | 18/06/2026 | Equipo RetailPulse (Fabio Vallejo, Jesus Godoy, Luis Rubio, Anghelo Hurtado, José del Carpio) | Actualización del informe para el Partial TF – Semana 11, incluyendo versión corregida y mejorada de los artefactos presentados previamente, actualización del Registro de Versiones del Informe, Project Report Collaboration Insights y Student Outcome. Se incorporó el desarrollo de la sección 5.2.3 Sprint 3, Sprint Planning 3, Aspect Leaders and Collaborators, Sprint Backlog 3, Development Evidence for Sprint Review, Execution Evidence for Sprint Review, Services Documentation Evidence for Sprint Review, Software Deployment Evidence for Sprint Review y Team Collaboration Insights during Sprint. Además, se añadieron las secciones de Validation Interviews, Diseño de Entrevistas, Registro de Entrevistas, Evaluaciones según heurísticas y Video About-the-Product. También se documentó la primera versión real de los Web Services de RetailPulse desarrollados con Java y Spring Boot, la migración progresiva desde JSON Server hacia endpoints REST reales, la documentación con Swagger/OpenAPI, el despliegue del frontend y backend, y la integración progresiva de la aplicación web con la API REST. |

---

## Project Report Collaboration Insights

El equipo ha utilizado un flujo de trabajo en github: [retailpulse-report](https://github.com/RetailPulse-NRC11863/retailpulse-report)

---

## Contenido

1. [Student Outcome](#student-outcome)
2. [Capítulo I: Introducción](#capítulo-i-introducción)
3. [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
4. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
5. [Capítulo IV: Product Design](#capítulo-iv-product-design)
6. [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
7. [Conclusiones](#conclusiones)
8. [Bibliografía](#bibliografía)

---

## Student Outcome

**ABET - EAC - Student Outcome 3:** Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio específico | Acciones realizadas | Conclusiones |
| --- | --- | --- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.** | **Faustino Hurtado, Anghelo Edwin**<br>**AV1:** Participó en la explicación de los artefactos de Lean UX, incluyendo assumptions, hypothesis statements y Lean UX Canvas. Asimismo, sustentó el análisis competitivo, las estrategias frente a competidores, los lineamientos visuales, la arquitectura de organización y las User Stories asignadas.<br>**TB1:** Participó en la comunicación de mejoras visuales relacionadas con los wireframes y mockups de la aplicación web. Su aporte permitió explicar parte de la evolución visual del sistema y la intención de mejorar la representación de la experiencia del usuario.<br>**AV2:** Participó en la comunicación de avances relacionados con Store Operations, especialmente en la explicación de alertas operativas y tareas priorizadas para el personal de tienda. Su aporte permitió presentar cómo RetailPulse puede apoyar la operación diaria del staff mediante información clara y accionable.<br><br>**Franco del Carpio, José María**<br>**AV1:** Explicó la construcción del Ubiquitous Language, el Product Backlog y los sistemas de arquitectura de información, incluyendo labeling, SEO tags, searching y navigation systems. También participó en la sustentación del registro de entrevistas y User Stories.<br>**TB1:** Tuvo responsabilidades asignadas relacionadas con Trello, Sprint 2, CRUD de productos y revisión de consistencia visual. Sin embargo, su participación oral en la sustentación del avance fue limitada, debido a que no se evidenció cumplimiento efectivo de sus tareas asignadas para esta entrega.<br>**AV2:** Participó en la explicación de actividades relacionadas con entrevistas de validación, revisión funcional y retroalimentación de usuarios. Su aporte permitió comunicar cómo los usuarios objetivo perciben la propuesta de valor, la utilidad de las funcionalidades y las oportunidades de mejora identificadas durante la validación.<br><br>**Godoy Santillan, Jesus Andres**<br>**AV1:** Presentó los antecedentes y la problemática, los segmentos objetivo y los artefactos de needfinding, como User Personas y User Task Matrix. Además, explicó el Landing Page Wireframe, el Container Diagram, los Class Diagrams y la configuración del entorno de desarrollo.<br>**TB1:** Comunicó avances relacionados con la mejora del Landing Page y participó parcialmente en la explicación de prototipos de la aplicación web. Su aporte contribuyó a presentar la evolución visual y comercial del producto frente a los requerimientos de la entrega.<br>**AV2:** Participó en la sustentación de funcionalidades relacionadas con productos, inventario y búsqueda dentro del sistema. Su aporte permitió explicar cómo el kiosko y las vistas administrativas pueden consultar información relevante como stock, ubicación y datos del catálogo.<br><br>**Rubio Ortiz, Luis Sebastián**<br>**AV1:** Sustentó el Impact Mapping, el Landing Page Mock-up, los Web Applications Mock-ups y el prototipo de la aplicación web. También explicó los Component Diagrams, las convenciones de estilo de código, la configuración de despliegue y las User Stories asignadas.<br>**TB1:** Participó en la comunicación de mejoras relacionadas con los mockups de la landing, prototipos de aplicación web y mejoras del Landing Page. Su participación permitió reforzar la explicación visual del producto y su orientación hacia usuarios del segmento retail.<br>**AV2:** Participó en la comunicación de avances relacionados con recomendaciones comerciales, desempeño de productos, planes de suscripción y material audiovisual del producto. Su aporte ayudó a explicar el valor comercial de RetailPulse y su orientación hacia negocios retail que requieren tomar decisiones basadas en datos.<br><br>**Vallejo Trujillo, Fabio Cesar**<br>**AV1:** Presentó la descripción de la startup, los Lean UX Problem Statements, el Context Diagram, el diseño de base de datos, la gestión del código fuente, los User Flow Diagrams, el Big Picture Event Storming, el Design-Level Event Storming y el registro de entrevistas.<br>**TB1:** Lideró la comunicación de los principales avances técnicos y de dominio, incluyendo la arquitectura base de la aplicación web, configuración de JSON Server, vistas principales, correcciones de DDD en Event Storming, diagramas de clases y base de datos, corrección de User Stories y despliegue de la aplicación web.<br>**AV2:** Lideró la comunicación de los principales avances técnicos del Sprint 3, especialmente la migración desde JSON Server hacia Web Services reales desarrollados con Java y Spring Boot. Explicó la organización del backend mediante bounded contexts, la documentación con Swagger/OpenAPI, los endpoints REST disponibles, el despliegue y la integración progresiva con la aplicación web. | **AV1:**<br>Durante el AV1, el equipo desarrolló la capacidad de comunicar oralmente los principales avances del proyecto RetailPulse a distintos tipos de audiencia. Las exposiciones permitieron explicar tanto aspectos de negocio, como la problemática, segmentos y propuesta de valor, como aspectos técnicos, incluyendo arquitectura, diseño de base de datos, prototipos y artefactos de DDD. La distribución de responsabilidades favoreció que cada integrante pudiera sustentar una parte específica del proceso de ingeniería y comunicar su aporte con claridad.<br><br>**TB1:**<br>Durante el TB1, la comunicación oral del equipo se enfocó en presentar la evolución del proyecto desde una propuesta inicial hacia una primera versión funcional de la aplicación web. Se explicó la mejora del Landing Page, los prototipos, la aplicación frontend, la arquitectura base, el uso de JSON Server, el despliegue y las correcciones realizadas a partir del feedback recibido. La exposición permitió evidenciar avances técnicos y de producto, aunque también mostró diferencias en el nivel de participación y cumplimiento de los integrantes.<br><br>**AV2:**<br>Durante el AV2, la comunicación oral del equipo se enfocó en presentar la evolución de RetailPulse hacia una solución con Web Services reales. Se explicó la migración progresiva desde JSON Server hacia una API REST desarrollada con Java y Spring Boot, la organización del backend por bounded contexts, la documentación con Swagger/OpenAPI, el despliegue de la solución y la integración progresiva con el frontend. Además, los testimonios individuales permitieron evidenciar las actividades realizadas, los outcomes alcanzados y el desarrollo de competencias durante el Sprint 3. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Faustino Hurtado, Anghelo Edwin**<br>**AV1:** Redactó y documentó secciones relacionadas con Lean UX Assumptions, Lean UX Hypothesis Statements, Lean UX Canvas, análisis de competidores, estrategias frente a competidores, General Style Guidelines, Web Applications Wireframes, Organization Systems y User Stories.<br>**TB1:** Contribuyó con mejoras en los wireframes y mockups de la aplicación web. Estas acciones aportaron a la documentación visual del producto y a la representación escrita y gráfica de la experiencia esperada para los usuarios.<br>**AV2:** Contribuyó con la documentación de funcionalidades asociadas a Store Operations, incluyendo alertas operativas, tareas priorizadas y su relación con el dashboard del personal de tienda. Su aporte permitió describir de manera clara cómo estas funcionalidades apoyan la gestión operativa dentro del local.<br><br>**Franco del Carpio, José María**<br>**AV1:** Elaboró documentación vinculada al Ubiquitous Language, Product Backlog, Labeling Systems, SEO Tags and Meta Tags, Searching Systems, Navigation Systems, registro de entrevista y User Stories, contribuyendo a la claridad del informe técnico y funcional.<br>**TB1:** Tuvo asignadas tareas de documentación y soporte al informe, como Trello de Sprint 1, Sprint 2, CRUD de productos y revisión de consistencia con los General Style Guidelines. Sin embargo, no se registró una contribución efectiva en estas secciones para el entregable TB1.<br>**AV2:** Contribuyó con información relacionada con las entrevistas de validación, el registro de hallazgos y la evaluación de la experiencia de usuario. Su participación ayudó a documentar la percepción de usuarios internos y compradores frente a la aplicación web y el kiosko de RetailPulse.<br><br>**Godoy Santillan, Jesus Andres**<br>**AV1:** Documentó los antecedentes y la problemática, segmentos objetivo, User Personas, User Task Matrix, Landing Page Wireframe, Software Architecture Container Diagrams, Class Diagrams y Software Development Environment Configuration.<br>**TB1:** Documentó y mejoró aspectos relacionados con el Landing Page y participó parcialmente en la elaboración de prototipos de la aplicación web. También tuvo asignadas secciones de evidencia de servicios, login, registro y configuración inicial de cuenta, aunque estas no fueron completadas en su totalidad.<br>**AV2:** Contribuyó con documentación funcional relacionada con productos, inventario y búsqueda de productos. Su aporte permitió explicar cómo los servicios de Inventory Intelligence apoyan el flujo del kiosko y la administración del catálogo.<br><br>**Rubio Ortiz, Luis Sebastián**<br>**AV1:** Redactó y documentó el Impact Mapping, Landing Page Mock-up, Web Applications Mock-ups, Web Applications Prototyping, Software Architecture Components Diagrams, Source Code Style Guide and Conventions, Software Deployment Configuration y User Stories.<br>**TB1:** Contribuyó con mejoras en los mockups de la landing, prototipos de aplicación web y mejoras del Landing Page. También tuvo asignadas tareas relacionadas con evidencia de despliegue, implementación de suscripción y planes, y registro de entrevista adicional, aunque no todas fueron completadas.<br>**AV2:** Contribuyó con documentación relacionada con recomendaciones comerciales, productos críticos, planes SaaS y material audiovisual. Su aporte permitió reforzar la comunicación escrita sobre el valor comercial de RetailPulse y su aplicación en contextos retail.<br><br>**Vallejo Trujillo, Fabio Cesar**<br>**AV1:** Elaboró la documentación de la descripción de la startup, Lean UX Problem Statements, Software Architecture Context Diagram, Database Diagrams, Source Code Management, Web Applications User Flow Diagrams, Big Picture Event Storming, Design-Level Event Storming y registro de entrevistas.<br>**TB1:** Documentó y corrigió los principales artefactos técnicos y de dominio del proyecto, incluyendo la arquitectura base de la aplicación web, configuración de JSON Server, vistas principales, correcciones de DDD en Event Storming, diagramas de clases, base de datos, User Stories y despliegue de la aplicación web.<br>**AV2:** Documentó los principales avances técnicos del Sprint 3, incluyendo la estructura backend con Spring Boot, la organización por bounded contexts, la documentación de endpoints con Swagger/OpenAPI, la evidencia de desarrollo, el despliegue, la integración progresiva con frontend y la actualización de secciones del informe correspondientes a Product Implementation, Validation & Deployment. | **AV1:**<br>En el AV1, el equipo evidenció comunicación escrita efectiva mediante la elaboración colaborativa del informe del proyecto. La documentación permitió organizar de manera clara los fundamentos del negocio, los hallazgos de investigación, los requisitos, el diseño UX/UI, la arquitectura de software, el diseño orientado a objetos, la base de datos y la gestión del desarrollo. Esto permitió presentar RetailPulse de forma comprensible para audiencias técnicas y no técnicas, manteniendo coherencia entre el problema, la solución, los artefactos de diseño y las decisiones arquitectónicas.<br><br>**TB1:**<br>En el TB1, la comunicación escrita se fortaleció mediante la actualización y corrección del informe a partir del feedback recibido. Se mejoraron artefactos previamente presentados, especialmente aquellos vinculados a DDD, Event Storming, diagramas de clases, base de datos, User Stories y Product Backlog. Además, se documentó la primera versión funcional de la aplicación web, el despliegue, el uso de JSON Server y las evidencias del Sprint 2. La documentación permitió comunicar con mayor claridad la evolución del proyecto, aunque el nivel de contribución escrita no fue uniforme entre todos los integrantes.<br><br>**AV2:**<br>En el AV2, la comunicación escrita se enfocó en documentar la evolución de RetailPulse hacia una arquitectura backend más completa. Se incorporó la documentación del Sprint 3, la primera versión real de Web Services, los endpoints REST organizados por bounded contexts, la documentación Swagger/OpenAPI, las evidencias de desarrollo, ejecución y despliegue, las entrevistas de validación, la evaluación heurística y el Video About-the-Product. Esta actualización permitió comunicar el avance del proyecto tanto a una audiencia técnica, interesada en la arquitectura y servicios REST, como a una audiencia funcional, interesada en el valor de RetailPulse para administradores, personal de tienda y compradores. |

---

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

RetailPulse es una startup tecnológica conformada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), orientada al desarrollo de soluciones digitales para mejorar la gestión comercial y la experiencia de compra en tiendas físicas del sector retail. La problematica surge a partir de que el comercio electrónico cuenta con métricas detalladas sobre el comportamiento de sus usuarios, muchos negocios físicos todavía operan con información limitada, tomando decisiones comerciales en función de intuición, experiencia previa o únicamente datos de venta.

La propuesta de valor de RetailPulse se materializa en una plataforma web SaaS que conecta la analítica de comportamiento en tienda con herramientas de apoyo operativo y experiencia asistida para el cliente. Por un lado, permite a boutiques, minimarkets y tiendas de conveniencia visualizar información como zonas de mayor tráfico, tiempo de permanencia, productos con alta interacción y baja conversión, y patrones de circulación dentro del local. Por otro lado, incorpora una interfaz web de consulta para el cliente en tienda, mediante la cual puede buscar productos, verificar disponibilidad, ubicar artículos dentro del local y acceder a promociones o recomendaciones durante su recorrido.

RetailPulse no se limita a mostrar datos, sino que los transforma en acciones concretas para el negocio. A partir de la información capturada, la plataforma puede generar recomendaciones para optimizar la distribución del local, activar promociones en zonas estratégicas, emitir alertas al personal cuando una zona requiere atención y facilitar decisiones relacionadas con exhibición, stock y conversión. De esta manera, RetailPulse busca llevar al retail físico un nivel de inteligencia operativa similar al del comercio electrónico, ayudando a los negocios a vender con mayor precisión y a los clientes a comprar con menos fricción.

#### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <td rowspan="3"><img src="assets/images/Perfil_Jesus.png" alt="Jesús Godoy" width="800"></td>
    <td>Jesús Andres Godoy Santillan (U20251C350)</td>
  </tr>
  <tr>
    <td>Ingeniería de Software</td>
  </tr>
  <tr>
    <td>Soy Jesús, tengo 23 años. Me apasiona la programación desde temprana edad, habiendo desarrollado proyectos que van desde videojuegos hasta plataformas para eventos online con creadores de contenido. Cuento con experiencia en el desarrollo de sistemas personalizados para el sector agroindustrial y brindo asesoría técnica en soluciones tecnológicas y resolución de problemas.</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="assets/images/perfil-anghelo.png" alt="Anghelo Faustino" width="180"></td>
    <td>Faustino Hurtado, Anghelo Edwin (U20241B331)</td>
  </tr>
  <tr>
    <td>Ingeniería de Software</td>
  </tr>
  <tr>
    <td>Tengo 20 años. Me interesa el aprendizaje de nuevas tecnologías y el desarrollo de aplicaciones. Me considero una persona responsable, con capacidad para el razonamiento lógico y buena disposición para el trabajo en equipo en proyectos colaborativos.
</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="assets/images/perfil-jose.png" alt="José María Franco" width="800"></td>
    <td>Franco del Carpio, José María (U202319178)</td>
  </tr>
  <tr>
    <td>Ingeniería de Software</td>
  </tr>
  <tr>
    <td>[Insertar biografía aquí]</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="assets/images/perfil-luis.png" alt="Luis Rubio" width="800"></td>
    <td>Rubio Ortiz, Luis Sebastián (U202310349)</td>
  </tr>
  <tr>
    <td>Ingeniería de Software</td>
  </tr>
  <tr>
    <td>Soy Luis Sebastián, tengo 20 años. Cuando empecé a aprender cada vez más sobre las computadoras desde pequeño, supe que este era mi camino. Me gusta aprender cosas nuevas, y tengo experiencia trabajando en equipo no solo en el contexto universitario, sino también en ambientes laborales.</td>
  </tr>
  <tr>
    <td rowspan="3"><img src="assets/images/perfil-fabio-vallejo.png" alt="Fabio Vallejo" width="800"></td>
    <td>Vallejo Trujillo, Fabio Cesar (U20211D989)</td>
  </tr>
  <tr>
    <td>Ingeniería de Software</td>
  </tr>
  <tr>
    <td>Soy Fabio, estudiante de ingenieria de software en quinto ciclo. Tengo 22 años, me gusta aprender nuevas tecnologías de programación y mantener buenas prácticas. Puedo aportar al proyecto manteniendo al grupo organizado con los entregables y con mis conocimientos técnicos en las multiples areas de programación, modelado de base de datos y arquitectura de software.</td>
  </tr>
</table>

### 1.2. Solution Profile

#### 1.2.1 Antecedentes y problemática

What?

Muchos negocios minoristas físicos operan actualmente con información limitada sobre lo que sucede dentro de sus locales. A diferencia del comercio electrónico, que posee métricas detalladas del usuario, el retail físico toma decisiones basadas en la intuición o únicamente en datos de venta final, ignorando el comportamiento previo a la conversión.

When?

La problemática se manifiesta durante todo el horario de atención comercial, especialmente cuando se acumula tráfico en zonas específicas sin que el personal lo note o cuando un cliente no encuentra un producto y abandona la tienda por falta de asistencia inmediata.

Where?

El problema se localiza en el interior de tiendas físicas como boutiques, minimarkets y tiendas de conveniencia. Estas carecen de herramientas para visualizar patrones de circulación o para ofrecer consultas digitales de stock en el mismo punto de venta.

Who?

Los afectados son los dueños y administradores de negocios retail, quienes no pueden optimizar su rentabilidad por zona, y los compradores, quienes experimentan fricciones al buscar productos o promociones.

Why?

La causa principal es la ausencia de una infraestructura digital que conecte sensores de monitoreo con interfaces de usuario, lo que genera exclusión de datos valiosos y limitaciones en la atención al cliente.

How?

La solución se implementará mediante una arquitectura distribuida que incluye un RESTful API en Java y una Web Application en Angular. Esta plataforma capturará eventos de interacción, generará mapas de calor para el administrador y ofrecerá un quiosco web de consulta para el comprador.

How much?

¿Cuánto afecta este problema?: Afecta al 100% de la eficiencia operativa del local, ya que las zonas de baja conversión no son identificadas ni corregidas a tiempo.

¿Cuánto costará resolver este problema?: El costo se define por el desarrollo de la arquitectura Open Source, el despliegue en la nube y el mantenimiento de los servicios de analítica.

¿Cuántas personas se beneficiarán?: Se beneficiarán tanto el personal operativo (mejor coordinación) como los cientos de clientes diarios que encontrarán una tienda más organizada y asistida.

Conclusiones de 5w y 2h:

En conclusión, el análisis identifica una desconexión crítica entre el potencial de venta del local y el conocimiento real del cliente. Retailplus implementará una solución innovadora que lleva la inteligencia del mundo online al entorno físico, eliminando la fricción para el comprador y maximizando la precisión operativa para el negocio.


#### 1.2.2 Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

En el retail físico, especialmente en boutiques y minimarkets, los negocios enfrentan una desventaja importante frente al comercio electrónico ya que no cuentan con herramientas que les permitan comprender con claridad qué ocurre dentro del local antes de que se concrete una venta. En la mayoría de los casos, los dueños o administradores solo pueden apoyarse en reportes de ventas, observación informal del comportamiento del cliente o criterios empíricos para decidir cómo distribuir productos, dónde colocar promociones, que promociones enviar a sus clientes o qué zonas del local requieren mayor atención.

Hemos identificado que este problema afecta directamente a dos segmentos clave. Por un lado, los dueños y administradores de tiendas necesitan visibilidad sobre el comportamiento de los clientes dentro del espacio físico para tomar decisiones comerciales mejor fundamentadas. Por otro lado, los propios compradores dentro de la tienda no siempre cuentan con una experiencia ágil para ubicar productos, promociones irresistibles, consultar stock o acceder a información útil durante su recorrido, lo que puede generar fricción, pérdida de tiempo y oportunidades desaprovechadas de venta.

Actualmente, ambas necesidades permanecen desconectadas. Mientras el negocio no dispone de información suficiente para optimizar su operación y mejorar la conversión, el cliente tampoco recibe apoyo inmediato dentro del local para encontrar lo que necesita o descubrir oportunidades y ofertas relevantes. Como consecuencia, se pierden posibilidades de mejorar la experiencia en tienda, aumentar ventas, optimizar la atención del personal y fomentar la fidelización.

¿Cómo podríamos desarrollar una plataforma web que permita a los dueños y administradores de tiendas físicas entender mejor el comportamiento de los clientes dentro del local y, al mismo tiempo, ofrecer a los compradores una experiencia de consulta asistida que reduzca fricción, facilite la compra y contribuya al incremento de la conversión y la fidelización?

##### 1.2.2.2. Lean UX Assumptions

**A. Business Assumptions**

1. Creemos que nuestros clientes necesitan reducir la pérdida de ventas por quiebres de stock y entender el flujo de clientes en su tienda.
2. Estas necesidades se resuelven con una plataforma SaaS que integre analítica de mapas de calor y un quiosco web de asistencia al comprador.
3. Nuestros primeros clientes serán administradores y dueños de minimarkets y tiendas de conveniencia urbanas.
4. **Valor #1 esperado:** visibilidad del tráfico en tiempo real y reducción de fricción en la compra.
5. **Beneficios adicionales:** optimización de la distribución del local, reposición ágil de productos, mejora en la experiencia del cliente.
6. **Adquisición:** referencias boca-a-boca, visitas comerciales a locales físicos y alianzas con gremios de retail.
7. **Ingresos:** suscripción mensual escalonada basada en el tamaño del local o número de zonas monitoreadas.
8. **Competencia principal:** RetailNext, Dor, Sensormatic Solutions.
9. **Ventaja competitiva:** integración de analítica operativa con asistencia directa al cliente, precio accesible y arquitectura open source.
10. **Mayor riesgo de producto:** rechazo a la instalación de sensores o cámaras por percepción de complejidad.
11. **Mitigación:** ofrecer un plan piloto inicial de bajo impacto, onboarding guiado y mostrar métricas accionables en la primera semana.
12. **Otros supuestos críticos:** conectividad a internet estable dentro de los locales comerciales; disposición de los clientes a usar pantallas interactivas.

**B. User Assumptions**

* **¿Quién es el usuario?** Administradores de tiendas físicas, personal operativo y compradores finales.
* **¿Dónde encaja el producto?** En el ecosistema físico de la tienda (oficina para el admin, pasillos para el personal y quiosco para el cliente).
* **Problema a resolver:** toma de decisiones empíricas → zonas de baja conversión y saturación de consultas al personal.
* **Uso típico:** revisar mapas de calor, recibir alertas de reposición, buscar la ubicación de un producto en el quiosco.
* **Características importantes:** analítica en tiempo real, alertas operativas, buscador interactivo de productos, UI intuitiva.
* **Look & feel:** dashboards oscuros (dark mode) para contraste de datos analíticos; UI limpia, clara y amigable con botones grandes para el quiosco web.

**C. User Outcome & Benefit Assumptions**

* Distribución de productos optimizada basada en datos reales, no en intuición.
* Menos consultas repetitivas al personal, permitiendo enfoque en tareas clave.
* Compradores encuentran productos y promociones de forma rápida y autónoma.
* Reducción de ventas perdidas por alertas preventivas de falta de stock.

**D. Business Outcome Assumptions (métricas objetivo)**

* Aumentar en un 25 % la tasa de conversión en zonas optimizadas en 3 meses.
* Reducir en un 30 % el tiempo promedio de búsqueda de productos por parte de los clientes.
* Disminuir a menos de 5 minutos el tiempo de respuesta del personal ante alertas de zonas desatendidas.
* Lograr la adopción de la plataforma en 10 locales piloto en los primeros 3 meses (2026).

**E. Feature Assumptions**

1. **Dashboard de analítica y mapas de calor** permite a la gerencia optimizar el layout de la tienda.
2. **Quiosco web interactivo** acelera la búsqueda de productos y mejora la experiencia de compra autónoma.
3. **Sistema de alertas operativas** notifica al personal sobre quiebres de stock para reposición inmediata.
4. **Módulo de promociones personalizadas** fideliza al cliente y aumenta las ventas cruzadas en zonas estratégicas.

##### 1.2.2.3. Lean UX Hypothesis Statements

**1. Dashboard de analítica y mapas de calor**
> Creemos que al ofrecer un dashboard con mapas de calor en tiempo real incrementaremos la tasa de conversión de las tiendas en un 25 %. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado: administradores reportan que "ahora sé exactamente qué pasillos son los más rentables y cómo distribuir mis productos" y/o los dashboards muestran un aumento del 25 % en ventas en las zonas optimizadas del local.

**2. Quiosco web interactivo**
> Creemos que implementar un quiosco web interactivo para la búsqueda autónoma de stock reducirá el tiempo de búsqueda del cliente en un 30 %. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado: compradores comentan que "fue muy fácil y rápido encontrar el pasillo de mi producto sin tener que buscar a un vendedor" y/o el sistema registra que más del 80 % de las consultas en pantalla terminan en una búsqueda exitosa en menos de 1 minuto.

**3. Sistema de alertas operativas**
> Creemos que incorporar notificaciones móviles sobre quiebres de stock o zonas desatendidas reducirá el tiempo de respuesta del personal a menos de 5 minutos. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado: el personal de piso expresa que "las alertas me permiten reponer los productos antes de que el estante quede vacío" y/o se observa una reducción de más del 40 % en el tiempo en que un anaquel reporta falta de inventario.

**4. Módulo de promociones personalizadas**
> Creemos que mostrar sugerencias y promociones cruzadas directamente en el quiosco web aumentará las ventas de productos complementarios en un 20 %. Sabremos que estamos bien cuando veamos los siguientes comentarios del mercado: dueños de negocio afirman que "las promociones en pantalla realmente impulsan las compras impulsivas de los clientes" y/o el número de cupones o promociones canjeadas en caja crece de manera sostenida más del 20 % mensual.

##### 1.2.2.4. Lean UX Canvas

<table>
  <tr>
    <td valign="top" width="33%">
      <b>1. Problema de negocios</b><br><br>
      El estado actual del sector retail físico ha dependido principalmente de la intuición y la observación visual por parte de administradores para distribuir el local. Utilizan reportes de ventas finales sin entender el comportamiento previo. Esto genera zonas muertas, pérdida de ventas y falta de control operativo. Lo que los productos actuales no resuelven es la necesidad de una solución de analítica de tráfico accesible que integre asistencia directa al comprador sin requerir hardware excesivamente costoso.<br><br>
      Nuestro producto abordará esta brecha mediante una plataforma web SaaS que mapea el tráfico (mapas de calor), emite alertas operativas y asiste al cliente mediante quioscos interactivos. Nuestro enfoque inicial estará dirigido a administradores de minimarkets urbanos, personal de tienda y compradores finales.<br><br>
      Sabremos que hemos tenido éxito cuando veamos una optimización del layout basada en datos, una reducción en las consultas operativas repetitivas y un uso recurrente del quiosco por parte de los compradores.
    </td>
    <td rowspan="2" valign="top" width="33%">
      <b>5. Ideas de las soluciones</b><br><br>
      - <b>Dashboard de analítica y mapas de calor:</b> Implementar un panel web interactivo para gerencia que permita visualizar las zonas de mayor y menor tráfico dentro de la tienda, cruzando estos datos con métricas de ventas en tiempo real para optimizar la distribución.<br><br>
      - <b>Quiosco web interactivo:</b> Desarrollar una interfaz táctil en el local para la búsqueda autónoma de stock, ubicación exacta del producto y visualización de promociones personalizadas (mediante ingreso de DNI).<br><br>
      - <b>Sistema de alertas operativas:</b> Crear un panel móvil responsivo que notifique al personal de piso en tiempo real sobre quiebres de stock en pasillos o zonas con alta aglomeración de clientes que requieran atención inmediata.
    </td>
    <td valign="top" width="33%">
      <b>2. Resultados comerciales</b><br><br>
      - Aumentar en un 25 % la tasa de conversión en las zonas optimizadas por el administrador en los primeros 3 meses.<br><br>
      - Reducir en un 30 % el tiempo promedio de búsqueda de productos por parte de los clientes usando los quioscos.<br><br>
      - Disminuir a menos de 5 minutos el tiempo de respuesta del personal ante alertas de zonas desatendidas o sin stock.<br><br>
      - Lograr la adopción de la plataforma en 10 locales piloto en los primeros 3 meses de 2026.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>3. Usuarios y Clientes</b><br><br>
      - <b>Administradores o dueños de retail:</b> Dueños de minimarkets y tiendas de conveniencia que buscan optimizar la rentabilidad de su espacio físico y mejorar la conversión de visitantes a compradores.<br><br>
      - <b>Personal de tienda:</b> Trabajadores operativos encargados de reponer stock, ordenar pasillos y atender consultas recurrentes en piso.<br><br>
      - <b>Compradores físicos:</b> Clientes que visitan la tienda buscando encontrar productos rápidamente, confirmar precios y aprovechar promociones sin fricciones.
    </td>
    <td valign="top">
      <b>4. Beneficios del usuario</b><br><br>
      - Toma de decisiones basada en datos precisos de tráfico y no en la intuición.<br>
      - Mayor autonomía y agilidad para el comprador en su recorrido.<br>
      - Reducción de frustración por no encontrar productos o no saber el precio.<br>
      - Personal de piso menos saturado de consultas repetitivas y mejor coordinado.<br>
      - Comunicación clara de promociones cruzadas directamente en el punto de decisión.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>6. Hipótesis</b><br><br>
      - Creemos que al ofrecer un dashboard con mapas de calor incrementaremos la tasa de conversión en un 25 %. Sabremos que estamos bien cuando los dashboards muestren un aumento del 25 % en ventas en las zonas optimizadas.<br><br>
      - Creemos que el quiosco web interactivo reducirá el tiempo de búsqueda en un 30 %. Sabremos que estamos bien cuando más del 80 % de las consultas terminen de forma exitosa en menos de 1 minuto.<br><br>
      - Creemos que las notificaciones móviles reducirán el tiempo de respuesta a menos de 5 minutos. Sabremos que estamos bien cuando el tiempo en que un anaquel reporta falta de inventario baje un 40 %.<br><br>
      - Creemos que las promociones en el quiosco aumentarán las ventas cruzadas en un 20 %. Sabremos que estamos bien cuando el número de cupones canjeados crezca un 20 % mensual.
    </td>
    <td valign="top">
      <b>7. ¿Qué es lo más importante que necesitamos aprender primero?</b><br><br>
      - Si el sistema analítico no es capaz de procesar datos de tráfico de manera clara, los dueños de negocios no confiarán en los mapas de calor para cambiar la distribución física de su local.<br><br>
      - Si la interfaz del quiosco web es lenta o compleja, los compradores la ignorarán y seguirán interrumpiendo al personal de tienda, anulando el propósito de la autonomía.<br><br>
      - Si las alertas operativas generan mucho ruido o falsos positivos, el personal de tienda las ignorará y el tiempo de reposición de stock no mejorará en la práctica.
    </td>
    <td valign="top">
      <b>8. ¿Cuál es la menor cantidad de trabajo que necesitamos hacer para resolver las dudas y para hacer siguiente más importante?</b><br><br>
      - <b>Entrevistas a Usuarios:</b> Realizar entrevistas a dueños de minimarkets y compradores para validar las fricciones actuales y la disposición a usar quioscos interactivos en tienda.<br><br>
      - <b>Pruebas de Usabilidad con Prototipos:</b> Diseñar wireframes funcionales de las tres vistas (Admin, Personal, Comprador) y realizar testeos con usuarios reales para iterar la interfaz antes de programar.<br><br>
      - <b>Realizar una prueba piloto local:</b> Implementar un MVP (Minimum Viable Product) de la plataforma en un solo minimarket de prueba para medir si la infraestructura de captura de datos funciona establemente.
    </td>
  </tr>
</table>

### 1.3. Segmentos objetivo

De acuerdo con el Boletín de Indicadores de Sector Comercio publicado por el Ministerio de la Producción (PRODUCE), el sector retail minorista en el Perú muestra una recuperación dinámica, aunque persisten brechas tecnológicas en la medición del comportamiento del consumidor en locales físicos. Asimismo, reportes del Gremio de Retail de la Cámara de Comercio de Lima (CCL), resaltan que el 70% de las decisiones de compra aún se concretan en el punto de venta físico, lo que subraya la necesidad de herramientas como RetailPulse.

Nuestros principales segmentos objetivo son:

##### Negocios retail físicos (Administradores y Dueños):

Este segmento representa a los clientes directos de la plataforma SaaS de Retailplus. Incluye a dueños de boutiques y minimarkets que buscan optimizar su rentabilidad mediante decisiones basadas en datos de tráfico y conversión por zona. Para este grupo, el sistema ofrece una solución de analítica avanzada que sustituye la gestión basada en la intuición por métricas precisas.

##### Compradores en tiendas físicas:

Representan el segmento de usuarios finales que interactuará con el quiosco web. Este perfil busca eficiencia y autonomía durante su recorrido en la tienda. RetailPulse les otorga la capacidad de consultar disponibilidad de productos y promociones de forma inmediata mediante su identificación (DNI), reduciendo la fricción en la búsqueda de artículos y mejorando su experiencia de compra general.

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

Luego de realizar una investigación del mercado peruano e internacional de soluciones tecnológicas para la optimización de puntos de venta y análisis del comportamiento del consumidor, hemos identificado los siguientes competidores potenciales para Retailplus:

- **RetailNext:** Es una plataforma líder a nivel global en analítica de retail que utiliza sensores de video e inteligencia artificial para rastrear el comportamiento del cliente en el local.
- **Dor:** Es una solución SaaS basada en hardware térmico que se especializa en el conteo de tráfico de personas para tiendas minoristas.
- **Sensormatic Solutions:** Es una de las empresas líderes a nivel global y local en inteligencia de inventario y análisis de tráfico de compradores a través de su plataforma ShopperTrak.

#### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="16" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="9" valign="top">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="7" valign="top">Este análisis tiene como finalidad identificar a nuestros potenciales competidores en el mercado de analítica de retail y asistencia digital en Perú. Buscamos idear estrategias y tácticas para diferenciarnos mediante la integración de un ecosistema que conecte la analítica operativa con la experiencia del comprador final, aprovechando una arquitectura Open Source escalable.</td>
  </tr>
  <tr>
    <td colspan="6" valign="top"><p><b>Nombre</b></p><p></p></td>
    <td colspan="3" valign="top"><b>RetailPulse (Nuestro producto)</b></td>
    <td colspan="3" valign="top"><b>RetailNext</b></td>
    <td colspan="3" valign="top"><b>Dor</b></td>
    <td valign="top"><b>Sensormatic Solutions</b></td>
  </tr>
  <tr>
    <td colspan="3" rowspan="4" valign="top"><b>Perfil</b></td>
    <td colspan="3" rowspan="2" valign="top"><b>Overview</b></td>
    <td colspan="3" rowspan="2" valign="top">RetailPulse es una plataforma SaaS que conecta la analítica de comportamiento en tienda, la asistencia digital al comprador mediante quioscos web y la coordinación operativa del personal en un solo ecosistema digital.</td>
    <td colspan="3" rowspan="2" valign="top">Plataforma global de analítica de retail basada en sensores de video e inteligencia artificial. Rastrea el comportamiento individual del cliente y ofrece métricas de tráfico y conversión para grandes corporaciones.</td>
    <td colspan="3" rowspan="2" valign="top">Solución SaaS enfocada en el conteo de tráfico de personas utilizando hardware térmico. Proporciona métricas simplificadas de entradas y salidas para pequeños y medianos negocios.</td>
    <td rowspan="2" valign="top">Ecosistema integral de inteligencia de inventario y prevención de pérdidas que utiliza ShopperTrak para analizar el tráfico de compradores y el rendimiento operativo en tiendas físicas.</td>
  </tr>
  <tr></tr>
  <tr>
    <td colspan="3" rowspan="2" valign="top"><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td colspan="3" rowspan="2" valign="top">Integración de analítica operativa y asistencia directa al comprador bajo una arquitectura abierta. Ofrece una solución integral para reducir la fricción en la compra y optimizar el personal simultáneamente.</td>
    <td colspan="3" rowspan="2" valign="top">Extrema precisión en el seguimiento de trayectorias mediante IA y madurez tecnológica en el mercado internacional de retail de lujo.</td>
    <td colspan="3" rowspan="2" valign="top">Instalación "plug-and-play" inmediata y total privacidad para los clientes al no utilizar cámaras, ideal para locales con alta sensibilidad a la privacidad.</td>
    <td rowspan="2" valign="top">Capacidad masiva de integrar datos de inventario en tiempo real con el tráfico de personas y sistemas de seguridad física ya existentes.</td>
  </tr>
  <tr></tr>
  <tr>
    <td colspan="3" rowspan="2" valign="top"><b>Perfil de Marketing</b></td>
    <td colspan="3" valign="top"><b>Mercado objetivo</b></td>
    <td colspan="3" valign="top">Boutiques, minimarkets y tiendas de conveniencia en Perú que buscan digitalizar su operación y mejorar la atención autónoma al cliente.</td>
    <td colspan="3" valign="top">Grandes cadenas minoristas internacionales, tiendas de departamento y centros comerciales de alto volumen.</td>
    <td colspan="3" valign="top">Pequeños comercios independientes y negocios retail locales que requieren métricas básicas de tráfico sin inversión en hardware complejo.</td>
    <td valign="top">Hipermercados, farmacias de cadena y retailers con necesidad crítica de control de inventario y prevención de pérdidas.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Estrategias de Marketing</b></td>
    <td colspan="3" valign="top">Marketing digital enfocado en democratización de datos para PYMES, alianzas con gremios de retail local y demostraciones de impacto en conversión.</td>
    <td colspan="3" valign="top">Participación en ferias internacionales de retail tech, marketing B2B de alto nivel y casos de éxito con marcas globales de lujo.</td>
    <td colspan="3" valign="top">Publicidad directa en redes sociales resaltando la simplicidad y el bajo costo de suscripción mensual.</td>
    <td valign="top">Venta directa institucional y consultoría técnica personalizada para grandes superficies y seguridad corporativa.</td>
  </tr>
  <tr>
    <td colspan="3" rowspan="3" valign="top"><b>Perfil de producto</b></td>
    <td colspan="3" valign="top"><b>Productos y Servicios</b></td>
    <td colspan="3" valign="top">Dashboards de tráfico, mapas de calor, quioscos web interactivos para búsqueda de stock y panel de alertas para el personal de tienda.</td>
    <td colspan="3" valign="top">Analítica de video avanzada, optimización de staff mediante IA y mapas de calor precisos basados en trayectorias.</td>
    <td colspan="3" valign="top">Sensores térmicos de puerta, reportes básicos de tráfico y dashboards de tasa de conversión simplificados.</td>
    <td valign="top">Software ShopperTrak, etiquetas inteligentes RFID, sensores de seguridad y plataformas de análisis de prevención de pérdidas.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Precios y Costos</b></td>
    <td colspan="3" valign="top">Modelo de suscripción SaaS escalable basado en planes según el tamaño de la tienda y número de zonas monitoreadas.</td>
    <td colspan="3" valign="top">Costos elevados por licencias enterprise, hardware propietario de video y servicios de consultoría e implementación.</td>
    <td colspan="3" valign="top">Costo de hardware inicial accesible y una suscripción mensual fija por dispositivo de bajo costo.</td>
    <td valign="top">Inversión inicial muy alta en infraestructura de red y seguridad, con contratos de mantenimiento a largo plazo.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Canales de distribución</b></td>
    <td colspan="3" valign="top">Distribución directa mediante plataforma web oficial y servicios en la nube (AWS/Azure) con soporte técnico local en Perú.</td>
    <td colspan="3" valign="top">Red global de socios tecnológicos certificados y venta directa para cuentas corporativas.</td>
    <td colspan="3" valign="top">Venta directa a través de sitio web con envío de hardware a nivel internacional y activación remota de SaaS.</td>
    <td valign="top">Fuerza de ventas corporativa directa y distribuidores especializados en seguridad electrónica y retail masivo.</td>
  </tr>
  <tr>
    <td colspan="3" rowspan="4" valign="top"><b>Análisis FODA</b></td>
    <td colspan="3" valign="top"><b>Fortalezas</b></td>
    <td colspan="3" valign="top">- Única solución que integra asistencia al comprador con analítica.<br>- Arquitectura Open Source adaptable.<br>- Enfoque específico en el mercado minorista peruano.</td>
    <td colspan="3" valign="top">- Líder mundial reconocido.<br>- Tecnología de IA altamente precisa.<br>- Robustez en el procesamiento de grandes volúmenes de datos.</td>
    <td colspan="3" valign="top">- Extrema simplicidad y privacidad.<br>- Bajo costo de hardware.<br>- Modelo de negocio escalable para pequeñas tiendas.</td>
    <td valign="top">- Sólida integración con prevención de pérdidas.<br>- Ecosistema de hardware RFID líder.<br>- Soporte global y local establecido.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Debilidades</b></td>
    <td colspan="3" valign="top">- Producto en fase de desarrollo académico inicial.<br>- Necesidad de validar la precisión de sensores de bajo costo frente a competidores.</td>
    <td colspan="3" valign="top">- Precios prohibitivos para el sector minorista peruano (PYMES).<br>- Curva de aprendizaje técnica muy elevada.</td>
    <td colspan="3" valign="top">- Funcionalidad limitada al conteo básico.<br>- No ofrece mapas de calor ni asistencia directa al cliente.</td>
    <td valign="top">- Ecosistema de hardware cerrado y propietario.<br>- Dificultad para integrar con bibliotecas de terceros y soluciones open source.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Oportunidades</b></td>
    <td colspan="3" valign="top">- Alta brecha digital en el retail peruano.<br>- Incremento en la demanda de experiencias de compra sin fricción.<br>- Alianzas con asociaciones de comercio locales.</td>
    <td colspan="3" valign="top">- Expansión de servicios mediante modelos de suscripción para mercados emergentes.</td>
    <td colspan="3" valign="top">- Integración de sus datos con sistemas POS de terceros para reportes más completos.</td>
    <td valign="top">- Potencial para integrar analítica predictiva avanzada basada en patrones de inventario.</td>
  </tr>
  <tr>
    <td colspan="3" valign="top"><b>Amenazas</b></td>
    <td colspan="3" valign="top">- Entrada de competidores internacionales con mayor capital.<br>- Resistencia cultural al monitoreo físico en locales tradicionales.</td>
    <td colspan="3" valign="top">- Crecimiento de soluciones SaaS ligeras que no requieren hardware costoso.</td>
    <td colspan="3" valign="top">- Competencia de aplicaciones móviles de conteo gratuito y manual.</td>
    <td valign="top">- Cambios en regulaciones de privacidad de datos que limiten el uso de sensores físicos.</td>
  </tr>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

**Diferenciación de Producto:**
- **Estrategia:** Retailplus se enfocará en la integración única de analítica operativa para el negocio y asistencia digital directa para el comprador final, bajo una arquitectura abierta y escalable que no requiere hardware propietario costoso.
- **Tácticas:** Se desarrollará un motor de analítica capaz de procesar eventos en tiempo real, se implementará una interfaz de quiosco web altamente intuitiva para la búsqueda autónoma de productos y stock.

**Desarrollo Continuo:**
- **Estrategia:** La startup se compromete a la mejora constante de la plataforma mediante la integración de bibliotecas de código abierto y servicios en la nube.
- **Tácticas:** Se establecerá un ciclo de retroalimentación con administradores de tiendas locales y se implementará un flujo de integración continua.

**Colaboraciones Estratégicas:**
- **Estrategia:** Se buscarán asociaciones con gremios de comercio locales y proveedores de infraestructura tecnológica.
- **Tácticas:** Se desarrollará un programa de "tiendas piloto" en diversos distritos de Lima.

### 2.2. Entrevistas

#### 2.2.1. Diseño de entrevistas

Con el objetivo de comprender las necesidades, frustraciones y expectativas de los segmentos definidos para RetailPulse, se diseñaron preguntas de entrevista diferenciadas para cada uno de los dos segmentos objetivo:

#### Preguntas para el segmento 1: Negocios retail físicos (dueños o administradores)

1. ¿Cómo tomas actualmente decisiones sobre la distribución de productos dentro de tu tienda?
2. ¿Qué tipo de información utilizas para saber qué productos funcionan mejor o peor?
3. ¿Te resulta fácil identificar qué zonas de tu tienda atraen más clientes? ¿Por qué?
4. ¿En qué situaciones sientes que pierdes ventas sin saber exactamente qué ocurrió?
5. ¿Cómo detectas si un cliente mostró interés en un producto pero finalmente no lo compró?
6. ¿Qué dificultades tiene tu personal para atender a los clientes dentro del local?
7. ¿Cómo decides cuándo cambiar la ubicación de un producto o activar una promoción?
8. ¿Qué herramientas digitales utilizas actualmente para gestionar tu tienda?
9. Si pudieras ver con mayor claridad cómo se comportan los clientes dentro del local, ¿cómo usarías esa información?
10. ¿Qué tipo de alertas, reportes o recomendaciones te ayudarían más a mejorar tus ventas?

#### Preguntas para el segmento 2: Compradores en tienda

1. Cuando ingresas a una tienda, ¿sueles encontrar fácilmente lo que estás buscando? ¿Por qué?
2. ¿Qué haces normalmente cuando no encuentras un producto dentro del local?
3. ¿Con qué frecuencia necesitas pedir ayuda a un vendedor para ubicar un producto?
4. ¿Te suele pasar que te interesa un producto pero finalmente no lo compras? ¿Qué te detiene?
5. ¿Qué tan importante es para ti saber si un producto tiene stock antes de buscarlo?
6. ¿Te parecería útil contar con una pantalla o quiosco dentro de la tienda para buscar productos? ¿Por qué?
7. ¿Qué información te gustaría ver al consultar un producto dentro de la tienda?
8. ¿Qué tan relevantes te resultan las promociones mientras estás comprando en una tienda física?
9. ¿Qué cosas te hacen perder más tiempo o te generan más frustración al comprar en tienda?
10. ¿Qué mejoraría tu experiencia de compra para que sea más rápida, cómoda o útil?

#### 2.2.2. Registro de entrevistas

##### Segmento 1: Dueños o administradores de negocios retail fisicos

###### Entrevista 1

* Nombre: Andy Pillaca
* Edad: 27
* Distrito: San Borja
* Timing: 0:02-3:50

![Entrevista](assets/images/entrevista-andy-pillaca.png)

**Resumen:**
Andy gestiona la distribución de productos en base a experiencia y observación, apoyándose en reportes de ventas y comentarios del personal. Sin embargo, no cuenta con datos precisos sobre el tráfico por zonas ni sobre el comportamiento de los clientes dentro del local, lo que dificulta entender por qué algunos productos no se venden (ubicación, precio o atención).

Actualmente, no puede identificar si un cliente interactúa con un producto y no lo compra, y en horas pico el personal no logra cubrir todas las áreas. Las decisiones como promociones o reubicación de productos se toman de forma reactiva, cuando las ventas son bajas o el stock no rota.

Utiliza únicamente un sistema POS y Excel. Considera que tener visibilidad del comportamiento del cliente le permitiría mejorar la distribución, la conversión y la atención. Le resultan especialmente útiles alertas de zonas con alto tráfico y baja conversión, identificación de productos con alta interacción sin venta y recomendaciones automáticas de acciones comerciales.

**Enlace:** [Enlace de Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQDP_YW2rY8ATJE47ANirMtLAW-v6aBYZvqO543KRLxJGAQ?e=9Lfbcy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

##### Segmento 1: Dueños o administradores de negocios retail físicos

###### Entrevista 2

* **Nombre:** Andrés de la Cruz
* **Edad:** 21
* **Distrito:** San Juan de Lurigancho
* **Timing:** 3:48-8:40

![Entrevista](assets/images/entrevista-andres-cruz.png)

**Resumen:**
Andrés gestiona la distribución de su local basándose principalmente en la intuición y la observación directa, apoyándose únicamente en los reportes de ventas finales para evaluar el éxito de sus productos. Esta falta de datos precisos le impide entender el comportamiento del cliente antes de llegar a la caja, especialmente en pasillos que quedan fuera de su vista durante el día.

Actualmente, enfrenta dificultades para identificar por qué el alto flujo de personas los fines de semana no se traduce siempre en ventas, y le resulta casi imposible detectar cuando un cliente muestra interés en un producto pero decide no comprarlo. Además, el personal de tienda presenta ineficiencias al aglomerarse en ciertas áreas, dejando zonas críticas sin atención. Las decisiones de reubicación de mercadería o promociones son reactivas, ejecutándose solo cuando el stock está estancado o por vencer.

Su ecosistema tecnológico es limitado, compuesto por un sistema POS básico, Excel y cámaras de seguridad convencionales que no aportan métricas. Andrés considera que contar con mapas de calor y alertas en tiempo real sobre zonas desatendidas transformaría su gestión, permitiéndole optimizar los turnos del personal y recibir recomendaciones automáticas para mejorar el layout y la rentabilidad del local.

**Enlace:** [Enlace de Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQDP_YW2rY8ATJE47ANirMtLAW-v6aBYZvqO543KRLxJGAQ?e=9Lfbcy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


##### Segmento 2: Compradores frecuentes en tiendas fisicas

###### Entrevista 1

* Nombre: Andy Nuñez
* Edad: 26
* Distrito: Lurigancho-Chosica
* Timing: 8:40-13:15

![Entrevista](assets/images/entrevista-andy-nunez.png)

**Resumen**: Andy Nuñez es un comprador frecuente en tiendas físicas y su experiencia depende mucho de la organización del local. En tiendas grandes o desconocidas, le resulta difícil encontrar productos debido a la falta de señalización y orden, por lo que suele recorrer toda la tienda antes de pedir ayuda, ya que los vendedores suelen estar ocupados.

Si no encuentra lo que busca, puede abandonar la tienda y buscar otra alternativa. No suele interactuar con el personal, prefiriendo tiendas donde ya conoce la distribución. Cuando no compra un producto que le interesó, generalmente se debe al precio, falta de necesidad o desconfianza en la calidad.

Valora mucho conocer rápidamente el stock de un producto para no perder tiempo ni generar frustración. Considera útil la presencia de pantallas en tienda que le permitan buscar productos, ver disponibilidad, ubicación y promociones al ingresar.

Sus principales frustraciones al comprar son no encontrar productos, perder tiempo, desorden en el local, mala señalización, precios incorrectos y largas colas.

**Enlace:** [Enlace de Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQDP_YW2rY8ATJE47ANirMtLAW-v6aBYZvqO543KRLxJGAQ?e=9Lfbcy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

###### Entrevista 2

* Nombre: Sra. Flores Aliaga
* Edad: 50 años
* Distrito: Santiago de Surco
* Timing: 13:15-20:45

![Entrevista](assets/images/entrevista-flores-aliaga.png)

Resumen: La Sra. Flores suele encontrar lo que busca en una tienda física porque ya sabe a qué pasillo o sección ir, pero cuando no encuentra un producto busca a un dependiente para preguntar si hay o dónde está. A veces decide no comprar un producto por el precio (más alto de lo esperado) o porque encuentra otra marca que le parece mejor. No considera muy importante saber el stock antes de ir, aunque sí ve valor en herramientas como una pantalla de búsqueda para personas más jóvenes, mientras que para ella podría ser más difícil por temas de tecnología. Valora información como fecha de caducidad, precio, información nutricional y componentes, y considera las promociones importantes porque pueden cambiar lo que compra. Sus principales frustraciones son los cambios en la disposición de productos, las colas largas por pocas cajas y la falta de precios visibles; para mejorar, propone mantener la distribución estable, que el personal tenga información clara y habilitar más cajas en horas de alta demanda.

**Enlace:** [Enlace de Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQDP_YW2rY8ATJE47ANirMtLAW-v6aBYZvqO543KRLxJGAQ?e=9Lfbcy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)


###### Entrevista 3

* Nombre: Giancarlo Castañeda
* Edad: 20
* Distrito: Santiago de Surco
* Timing: 20:46-25:35

![Entrevista](assets/images/entrevista-giancarlo-castaneda.png)

**Resumen**: Giancarlo Castañeda es un comprador recurrente, siempre visita distintas tiendas y acepta que hay problemas con la organización. Siente que puede perderse al busca un producto en especifico, y la posibilidad de saber si hay stock o no es imposible a menos que pregunte o no encuentre directamente el producto.

Siente que al buscar el producto y no encontrarlo donde deberia es una perdida de tiempo y dinero, en caso no encuentre lo que busca suele preguntar a los trabajadores, pero no siempre estan libres.

Considera que seria bueno tener una pantalla donde pueda consultar los precios o descripciones sobre los productos que busca, para que en el caso no haya stock, no pierda el tiempo buscando, ni esperando que un trabajador venga a ayudarlo.

**Enlace:** [Enlace de Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQDP_YW2rY8ATJE47ANirMtLAW-v6aBYZvqO543KRLxJGAQ?e=9Lfbcy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

#### 2.2.3. Análisis de entrevistas

## Análisis de Entrevistas por Segmento

---

### Segmento 1: Dueños o Administradores de Negocios Retail Físicos

El análisis conjunto de las entrevistas evidencia una problemática estructural en la gestión de tiendas físicas que es la falta de visibilidad sobre el comportamiento del cliente dentro del local. A partir de los testimonios recolectados, se identifican los siguientes hallazgos clave:

1. **Ausencia de analítica de comportamiento en tienda (Validación de Heatmaps y Tracking):**  
   Los administradores dependen de intuición, observación directa y reportes de ventas finales, lo que genera una visión incompleta del recorrido del cliente. No existen datos sobre tráfico por zonas ni sobre interacción con productos, lo que valida la necesidad de mapas de calor y analítica de movimiento.

2. **Desconexión del embudo de conversión físico:**  
   Existe una brecha entre el interés del cliente (interacción con productos) y la compra final. Los administradores no pueden identificar por qué productos con alto flujo o interacción no se venden, lo que limita la toma de decisiones estratégicas.

3. **Gestión reactiva en lugar de predictiva (Validación de Recomendaciones):**  
   Las decisiones comerciales, como promociones o reubicación de productos, se toman únicamente cuando el problema ya es evidente (baja rotación o sobrestock). Esto valida la necesidad de un sistema que genere recomendaciones automáticas basadas en datos.

4. **Ineficiencia operativa del personal (Validación de Alertas en Tiempo Real):**  
   Durante horas pico, el personal no logra cubrir todas las zonas del local, generando áreas desatendidas y pérdida de oportunidades de venta. La necesidad de alertas en tiempo real sobre concentración de clientes o zonas críticas es recurrente.

5. **Limitaciones tecnológicas actuales:**  
   El ecosistema digital de muchas tiendas fisicas está limitado a POS, Excel y cámaras de seguridad sin capacidad analítica. Esto refuerza la oportunidad de RetailPulse como solución que integra datos operativos y comportamiento del cliente en una sola plataforma.

En conjunto, este segmento valida directamente el núcleo de valor de RetailPulse, que es transformar datos de interacción en decisiones accionables que mejoren la conversión, la distribución del espacio y la eficiencia operativa.

---

### Segmento 2: Compradores Frecuentes en Tiendas Físicas

El análisis de los compradores revela fricciones claras en la experiencia de compra dentro de tiendas físicas, principalmente relacionadas con la búsqueda de productos, la disponibilidad de información y la eficiencia del recorrido. Los hallazgos principales son:

1. **Dificultad para encontrar productos (Validación del Kiosco y Mapa Interactivo):**  
   En tiendas grandes o desconocidas, los usuarios experimentan desorientación debido a la falta de señalización clara y organización del espacio. Esto genera recorridos innecesarios y pérdida de tiempo, validando la necesidad de herramientas de búsqueda y ubicación de productos en tienda.

2. **Baja interacción con el personal:**  
   Los compradores prefieren no depender de vendedores, ya sea por falta de disponibilidad o por preferencia personal. Esto refuerza la importancia de soluciones de autoservicio como kioscos digitales.

3. **Abandono de compra por fricción en la experiencia:**  
   Los usuarios pueden abandonar la tienda si no encuentran lo que buscan o si el proceso resulta demasiado complejo o lento. Factores como desorden, mala señalización o largas colas impactan directamente en la conversión.

4. **Necesidad de información inmediata (Validación de Stock en Tiempo Real):**  
   La disponibilidad de stock es un factor crítico para evitar frustración. Los usuarios valoran saber rápidamente si un producto está disponible antes de buscarlo físicamente.

5. **Factores de decisión de compra:**  
   El precio, la percepción de necesidad, la confianza en la marca y las promociones influyen directamente en la decisión final. Esto valida la importancia de mostrar información relevante y sugerencias dentro del punto de venta.

6. **Brecha generacional en adopción tecnológica:**  
   Mientras algunos usuarios valoran herramientas digitales como kioscos, otros pueden tener dificultades en su uso. Esto implica que la solución debe ser intuitiva y accesible para distintos perfiles de usuario.

En conjunto, este segmento valida la propuesta de RetailPulse desde la perspectiva del cliente final, que es mejorar la experiencia de compra mediante acceso rápido a información, navegación asistida y reducción de fricciones dentro del local.

### 2.3. Needfinding

#### 2.3.1. User Personas

Basados en la información recopilada durante nuestras entrevistas y análisis competitivo, hemos desarrollado User Personas representativas de nuestros segmentos objetivo.

##### Segmento 1: Negocios retail físicos (Administradores y Dueños)

![Entrevista](assets/images/user-persona-1.png)

##### Segmento 2: Compradores en tiendas físicas:

![Entrevista](assets/images/user-persona-2.png)


#### 2.3.2. User Task Matrix

En esta sección se describen las tareas realizadas por los distintos segmentos objetivos dentro de la plataforma RetailPulse.

---

### Segmento 1: Negocios retail físicos (Administradores y Dueños)

| Tarea | Frecuencia | Importancia |
|------|-----------|-------------|
| Analizar dashboards de tráfico y permanencia en tiempo real | Alta | Alta |
| Monitorear mapas de calor para identificar zonas muertas | Alta | Crítica |
| Configurar el layout digital de la tienda y definir zonas | Baja | Alta |
| Gestionar alertas operativas para el personal de piso | Alta | Alta |
| Revisar reportes de conversión de productos por zona | Media | Alta |
| Administrar el catálogo de productos y stock disponible | Media | Alta |
| Gestionar la suscripción SaaS y roles de usuarios (Staff) | Baja | Media |
| Evaluar la efectividad de promociones en puntos de venta | Media | Alta |
| Recibir recomendaciones automáticas para optimización de local | Media | Media |
| Monitorear interacciones de los clientes con los quioscos | Alta | Media |

---

### Segmento 2: Compradores en tiendas físicas

| Tarea | Frecuencia | Importancia |
|------|-----------|-------------|
| Buscar la ubicación exacta de un producto en la tienda | Alta | Alta |
| Consultar la disponibilidad de stock en tiempo real | Alta | Crítica |
| Identificarse mediante DNI para acceder a beneficios | Media | Alta |
| Visualizar el mapa interactivo para navegación en tienda | Media | Media |
| Consultar promociones y descuentos vigentes | Alta | Alta |
| Solicitar asistencia técnica o personal mediante el quiosco | Baja | Media |
| Verificar precios y características de productos | Alta | Alta |
| Escanear códigos de productos para obtener información | Media | Media |
| Recibir sugerencias de productos complementarios | Media | Baja |
| Evaluar la experiencia de compra a través de la interfaz | Baja | Baja |

#### 2.3.3. User Journey Mapping

##### Segmento 1: Administradores de tienda

<img src="assets/images/journey-map-administradores.png" width="100%">

##### Segmento 2: Compradores en tienda

<img src="assets/images/journey-map-compradores.png" width="100%">


#### 2.3.4. Empathy Mapping

##### Segmento 1: Administradores de tienda

<img src="assets/images/empathy-mapping-administradores.png" width="100%">

##### Segmento 2: Compradores en tienda

<img src="assets/images/empathy-mapping-compradores.png" width="100%">

### 2.4. Big Picture Event Storming

En esta sección, se presenta el desarrollo y los resultados de la sesión de Event Storming realizada por el equipo para el proyecto RetailPulse. Este proceso consistió en una actividad colaborativa de modelado del dominio, orientada a comprender de manera integral el funcionamiento del negocio de analítica en tiendas físicas.

A través de esta dinámica, se identificaron los actores principales, los eventos de dominio más relevantes y su relación dentro del flujo de valor del sistema, desde la adopción de la plataforma hasta la generación de alertas y recomendaciones en tienda. Esto permitió construir una visión clara del comportamiento del sistema en un nivel de negocio (Big Picture), así como una base estructurada para el diseño detallado posterior mediante el Design-Level Event Storming.

<img src="assets/images/big-picture-event-storming-retailpulse.png" width="100%">

**Enlace de Visualización:** https://miro.com/app/board/uXjVHd0j6Lc=/?share_link_id=737912347927


### 2.5. Ubiquitous Language

El **Ubiquitous Language** define un conjunto de términos compartidos entre los miembros del equipo de desarrollo, stakeholders y usuarios del sistema RetailPulse. Este lenguaje permite establecer una comunicación clara, consistente y sin ambigüedades a lo largo del diseño, desarrollo e implementación de la plataforma.

Dado que RetailPulse está basado en principios de **Domain-Driven Design (DDD)**, los términos definidos a continuación se alinean con los distintos **Bounded Contexts** del sistema, tales como *Store Configuration*, *Simulation & In-Store Monitoring*, *Buyer Assistance*, *Sales & Conversion* y *Alerts & Recommendations*.

---

#### 2.5.1. Términos del Dominio de Negocio

| Término | Definición |
|--------|-----------|
| **RetailPulse** | Plataforma SaaS orientada a la analítica de comportamiento en tiendas físicas y asistencia digital al comprador. |
| **Tienda (Store)** | Establecimiento físico donde se implementa RetailPulse para analizar el comportamiento de los clientes. |
| **Administrador** | Usuario responsable de la gestión de la tienda, toma de decisiones y análisis de métricas. |
| **Personal de tienda** | Empleados encargados de la operación diaria, reposición de productos y atención al cliente. |
| **Comprador** | Cliente final que interactúa con la tienda física y el quiosco digital. |
| **Suscripción** | Plan contratado por una tienda para acceder a las funcionalidades de RetailPulse. |
| **Plan** | Nivel de servicio ofrecido (básico, intermedio, avanzado) que define capacidades del sistema. |

---

#### 2.5.2. Términos de Configuración de Tienda

| Término | Definición |
|--------|-----------|
| **Zona (Zone)** | Área específica dentro de la tienda (pasillos, secciones, entradas, cajas). |
| **Estante (Shelf)** | Estructura física donde se ubican productos dentro de una zona. |
| **Producto (Product)** | Ítem disponible para la venta dentro de la tienda. |
| **Ubicación de producto** | Relación entre un producto y su posición exacta dentro de la tienda. |
| **Catálogo** | Conjunto de productos registrados en el sistema. |

---

#### 2.5.3. Términos de Analítica y Monitoreo

| Término | Definición |
|--------|-----------|
| **Evento** | Registro de una acción o interacción del cliente dentro de la tienda (movimiento, permanencia, interacción). |
| **Sesión de visita** | Conjunto de eventos asociados a un cliente durante su recorrido en la tienda. |
| **Mapa de calor (Heatmap)** | Visualización que representa la intensidad de tráfico o interacción en distintas zonas. |
| **Tráfico** | Cantidad de personas que transitan por una zona determinada. |
| **Tiempo de permanencia** | Duración que un cliente permanece en una zona específica. |
| **Interacción** | Acción del cliente relacionada con un producto o zona (detenerse, observar, consultar). |

---

#### 2.5.4. Términos de Asistencia al Comprador

| Término | Definición |
|--------|-----------|
| **Quiosco Web** | Interfaz interactiva en tienda que permite al comprador buscar productos y consultar información. |
| **Búsqueda de producto** | Proceso mediante el cual el comprador consulta un producto en el sistema. |
| **Disponibilidad** | Estado que indica si un producto se encuentra en stock. |
| **Ubicación del producto** | Información que indica en qué zona o estante se encuentra un producto. |
| **Promoción** | Oferta o incentivo asociado a un producto para incentivar su compra. |
| **Sesión de quiosco** | Interacción completa de un comprador con el quiosco web. |

---

#### 2.5.5. Términos de Ventas y Conversión

| Término | Definición |
|--------|-----------|
| **Venta** | Transacción en la que uno o más productos son adquiridos por el cliente. |
| **Conversión** | Relación entre interacción del cliente y compra efectiva. |
| **Tasa de conversión** | Métrica que indica el porcentaje de visitantes que realizan una compra. |
| **Producto de alta interacción** | Producto que recibe muchas consultas o interés, pero no necesariamente ventas. |
| **Zona de baja conversión** | Área con alto tráfico pero bajo nivel de compras. |

---

#### 2.5.6. Términos de Alertas y Operación

| Término | Definición |
|--------|-----------|
| **Alerta operativa** | Notificación generada por el sistema ante una condición relevante (alta demanda, falta de stock, zona desatendida). |
| **Tarea operativa** | Acción asignada al personal de tienda como respuesta a una alerta. |
| **Prioridad** | Nivel de urgencia asignado a una alerta o tarea. |
| **Recomendación** | Sugerencia generada por el sistema para optimizar la operación o la distribución de la tienda. |

---

#### 2.5.7. Consistencia del Lenguaje

Para asegurar la correcta aplicación del Ubiquitous Language en el proyecto:

- Todos los términos definidos deben ser utilizados de manera consistente en:
  - User Stories  
  - Diagramas de arquitectura  
  - Código fuente (nombres de clases, variables, servicios)  
  - Interfaces de usuario  

- Se evita el uso de sinónimos para un mismo concepto (por ejemplo, no alternar entre “cliente” y “comprador” si se ha definido uno como estándar).

- Los términos en inglés se mantienen únicamente cuando forman parte del lenguaje técnico (por ejemplo, *Heatmap*, *Dashboard*, *Stock*).


---

## Capítulo III: Requirements Specification

### 3.1. User Stories

| Epic ID | Título | Descripción |
|---|---|---|
| EP-01 | Traffic Analytics & Store Operations | Agrupa las capacidades que permiten detectar patrones de circulación, zonas críticas, congestión, alertas operativas y tareas del personal dentro de la tienda física. |
| EP-02 | Assisted Shopping Experience | Agrupa las capacidades orientadas a reducir la fricción del comprador dentro de la tienda, permitiendo buscar productos, validar disponibilidad, ubicar artículos y recibir promociones relevantes. |
| EP-03 | Inventory Intelligence & Promotion Optimization | Agrupa las capacidades que permiten detectar stock crítico, productos con baja conversión, oportunidades comerciales y recomendaciones para mejorar ventas y distribución. |
| EP-04 | SaaS Platform & Access Management | Agrupa las capacidades de soporte de la plataforma, como planes SaaS, acceso por roles, configuración inicial de tienda y habilitación de funcionalidades según suscripción. |

| Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con |
|---|---|---|---|---|
| US-01 | Evaluar propuesta de valor y planes SaaS | Como administrador retail visitante, quiero conocer los planes, beneficios y casos de uso de RetailPulse, para decidir si la solución puede mejorar la operación de mi tienda. | **Escenario 1:** Given el visitante accede al landing page, When revisa la propuesta de valor, Then el sistema presenta beneficios relacionados con tráfico, operación, inventario y conversión.<br><br>**Escenario 2:** Given el visitante consulta los planes, When compara sus beneficios, Then el sistema muestra diferencias claras entre Starter, Growth y Premium.<br><br>**Escenario 3:** Given el visitante selecciona un plan, When inicia el flujo de suscripción, Then el sistema lo dirige al registro o checkout simulado. | EP-04 |
| US-02 | Identificar zonas de baja conversión | Como administrador retail, quiero identificar zonas con alta interacción y baja conversión, para redistribuir productos estratégicamente y mejorar el rendimiento del local. | **Escenario 1:** Given existen métricas de interacción y ventas por zona, When el administrador consulta el análisis, Then el sistema muestra zonas con brechas de conversión.<br><br>**Escenario 2:** Given una zona tiene alta interacción y baja conversión, When el sistema calcula la brecha, Then marca la zona como oportunidad comercial.<br><br>**Escenario 3:** Given no existen datos suficientes, When el administrador consulta el análisis, Then el sistema informa que no hay información disponible para calcular la brecha. | EP-01 |
| US-03 | Recibir alertas de congestión operativa | Como supervisor de tienda, quiero recibir alertas cuando una zona supere niveles críticos de tráfico, para redistribuir personal antes de afectar la experiencia del comprador. | **Escenario 1:** Given una zona supera el umbral de tráfico definido, When el sistema detecta congestión, Then genera una alerta operativa.<br><br>**Escenario 2:** Given existen varias alertas activas, When el personal consulta su panel, Then el sistema las ordena por prioridad.<br><br>**Escenario 3:** Given una alerta no es atendida en el tiempo esperado, When vence el umbral de atención, Then el sistema cambia su prioridad o la marca como escalada. | EP-01 |
| US-04 | Encontrar productos rápidamente en tienda | Como comprador en tienda, quiero encontrar productos rápidamente mediante el quiosco, para evitar recorrer pasillos innecesarios o abandonar la compra por frustración. | **Escenario 1:** Given el producto existe y tiene stock, When el comprador lo busca, Then el sistema muestra disponibilidad, zona y referencia de estante.<br><br>**Escenario 2:** Given el producto existe pero no tiene stock, When el comprador lo consulta, Then el sistema informa la falta de disponibilidad.<br><br>**Escenario 3:** Given no hay coincidencias, When el comprador realiza la búsqueda, Then el sistema muestra un mensaje claro y permite intentar otra búsqueda. | EP-02 |
| US-05 | Atender tareas operativas priorizadas | Como colaborador de piso, quiero consultar tareas operativas priorizadas, para atender zonas, reposiciones o incidencias según su impacto en la experiencia del comprador. | **Escenario 1:** Given existen tareas activas, When el colaborador accede a su vista operativa, Then el sistema muestra tareas con prioridad, zona y estado.<br><br>**Escenario 2:** Given una tarea está pendiente, When el colaborador la completa, Then el sistema actualiza su estado como resuelta.<br><br>**Escenario 3:** Given una tarea vencida sigue pendiente, When el sistema evalúa su antigüedad, Then la marca como atrasada o prioritaria. | EP-01 |
| US-06 | Detectar zonas calientes y zonas muertas | Como administrador retail, quiero identificar zonas calientes y zonas muertas dentro del local, para ajustar la distribución comercial con base en comportamiento real. | **Escenario 1:** Given existen métricas de tráfico por zona, When el administrador consulta el mapa de calor, Then el sistema representa la intensidad de actividad por zona.<br><br>**Escenario 2:** Given una zona tiene baja intensidad y bajo tráfico, When el sistema analiza el layout, Then la identifica como posible zona muerta.<br><br>**Escenario 3:** Given una zona tiene intensidad alta, When el sistema calcula su nivel de calor, Then la muestra como zona caliente. | EP-01 |
| US-07 | Recibir recomendaciones de optimización comercial | Como administrador retail, quiero recibir recomendaciones basadas en tráfico, stock e interacción, para tomar acciones correctivas sobre productos, zonas o promociones. | **Escenario 1:** Given el sistema detecta una zona con baja conversión, When genera una recomendación, Then muestra una acción sugerida con prioridad.<br><br>**Escenario 2:** Given un producto tiene alta interacción y baja venta, When el sistema analiza su desempeño, Then recomienda promoción, reubicación o mejora de visibilidad.<br><br>**Escenario 3:** Given una recomendación es aplicada, When el administrador la marca como ejecutada, Then el sistema actualiza su estado. | EP-03 |
| US-08 | Detectar patrones de circulación | Como administrador retail, quiero detectar patrones de circulación de clientes, para optimizar el layout comercial y mejorar el flujo de compra dentro del local. | **Escenario 1:** Given existen eventos de visita por zona, When el sistema procesa el recorrido, Then muestra patrones frecuentes de circulación.<br><br>**Escenario 2:** Given un patrón concentra tráfico en pocas zonas, When el administrador lo revisa, Then el sistema permite identificar puntos de saturación o zonas ignoradas.<br><br>**Escenario 3:** Given no existen recorridos registrados, When se consulta el análisis, Then el sistema informa que no hay datos suficientes. | EP-01 |
| US-09 | Recibir promociones relevantes durante la búsqueda | Como comprador en tienda, quiero recibir promociones relevantes mientras busco productos, para descubrir ofertas útiles sin interrumpir mi recorrido de compra. | **Escenario 1:** Given el producto consultado tiene una promoción activa, When el comprador revisa su información, Then el sistema muestra la promoción relacionada.<br><br>**Escenario 2:** Given el comprador consulta productos de una categoría específica, When existen promociones relacionadas, Then el sistema las muestra como sugerencias relevantes.<br><br>**Escenario 3:** Given no existen promociones disponibles, When el comprador consulta el producto, Then el sistema no muestra ofertas irrelevantes. | EP-02 |
| US-10 | Activar alerta por quiebre de stock consultado | Como colaborador de piso, quiero recibir alertas cuando un comprador consulta un producto sin stock, para actuar rápidamente y evitar quiebres visibles al cliente. | **Escenario 1:** Given un comprador busca un producto sin stock, When el sistema detecta la condición, Then genera una alerta de reposición o revisión.<br><br>**Escenario 2:** Given el personal atiende la alerta, When repone o confirma el estado del producto, Then el sistema permite marcar la alerta como resuelta.<br><br>**Escenario 3:** Given el producto vuelve a estar disponible, When se actualiza el inventario, Then el sistema deja de mostrarlo como no disponible. | EP-03 |
| US-11 | Registrar eventos de movimiento en tienda | Como sistema de analítica, quiero registrar eventos de movimiento por zona, para alimentar el cálculo de tráfico, congestión y mapas de calor. | **Escenario 1:** Given se recibe un evento válido de zona, When el sistema lo procesa, Then lo registra asociado a la tienda y zona correspondiente.<br><br>**Escenario 2:** Given el evento no tiene zona válida, When se intenta registrar, Then el sistema rechaza el evento o lo marca como inválido.<br><br>**Escenario 3:** Given existen eventos acumulados, When se procesa la analítica, Then el sistema puede calcular intensidad de tráfico por zona. | EP-01 |
| US-12 | Calcular métricas de calor y conversión | Como sistema de analítica, quiero calcular métricas de tráfico, permanencia e interacción, para generar insights accionables sobre el comportamiento dentro de la tienda. | **Escenario 1:** Given existen eventos de tráfico e interacción, When el sistema calcula métricas, Then genera indicadores por zona.<br><br>**Escenario 2:** Given una zona supera el umbral de intensidad, When se procesan las métricas, Then el sistema puede marcarla como zona caliente o congestionada.<br><br>**Escenario 3:** Given una zona tiene baja actividad sostenida, When se calculan los indicadores, Then el sistema puede marcarla como zona fría o muerta. | EP-01 |
| US-13 | Mantener catálogo y ubicación de productos | Como administrador retail, quiero mantener productos con stock, zona y referencia de estante, para que compradores y personal trabajen con información confiable dentro de la tienda. | **Escenario 1:** Given el administrador registra un producto con datos válidos, When guarda la información, Then el sistema lo incorpora al catálogo de la tienda.<br><br>**Escenario 2:** Given un producto cambia de zona o estante, When el administrador actualiza su ubicación, Then el sistema refleja el cambio en el quiosco y en inventario.<br><br>**Escenario 3:** Given un producto queda inactivo, When se actualiza su estado, Then el sistema evita mostrarlo como disponible para el comprador. | EP-03 |
| US-14 | Acceder a información según rol operativo | Como administrador o personal autorizado, quiero acceder únicamente a las funcionalidades correspondientes a mi rol, para proteger métricas sensibles y separar responsabilidades operativas. | **Escenario 1:** Given el usuario selecciona o inicia sesión con rol administrador, When accede al sistema, Then puede ver métricas, configuración y suscripción.<br><br>**Escenario 2:** Given el usuario accede como personal de tienda, When ingresa al sistema, Then solo visualiza alertas y tareas operativas.<br><br>**Escenario 3:** Given un usuario sin permisos intenta entrar a una vista restringida, When realiza la acción, Then el sistema bloquea o redirige el acceso. | EP-04 |
| US-15 | Configurar tienda y funcionalidades disponibles | Como administrador retail, quiero configurar los datos iniciales de mi tienda y las funcionalidades habilitadas por mi plan, para operar RetailPulse según el alcance contratado. | **Escenario 1:** Given el administrador registra una tienda, When completa sus datos principales, Then el sistema guarda nombre, rubro, dirección y configuración base.<br><br>**Escenario 2:** Given la cuenta tiene un plan activo, When el administrador accede a funcionalidades avanzadas, Then el sistema valida si están disponibles según su suscripción.<br><br>**Escenario 3:** Given el plan cambia, When se actualiza la suscripción, Then el sistema actualiza las funcionalidades disponibles. | EP-04 |
| US-16 | Comprender impacto operativo de RetailPulse | Como visitante de página, quiero comprender cómo RetailPulse reduce fricción operativa y mejora decisiones comerciales, para evaluar su valor más allá de sus funcionalidades visuales. | **Escenario 1:** Given el visitante revisa la sección de beneficios, When consulta el contenido, Then el sistema explica mejoras en tráfico, stock, atención y conversión.<br><br>**Escenario 2:** Given el visitante pertenece a un negocio retail físico, When explora casos de uso, Then el sistema muestra ejemplos aplicados a tiendas reales.<br><br>**Escenario 3:** Given el visitante desea profundizar, When revisa demostraciones, Then el sistema muestra escenarios de uso conectados a problemas reales del negocio. | EP-02 |
| US-17 | Visualizar demostraciones orientadas a outcomes | Como visitante de página, quiero visualizar demostraciones de RetailPulse aplicadas a situaciones reales de tienda, para entender cómo la plataforma transforma eventos del local en acciones operativas y comerciales. | **Escenario 1:** Given el visitante accede a la sección de demostraciones, When revisa el contenido, Then el sistema muestra ejemplos de congestión, quiebre de stock, búsqueda en quiosco y recomendaciones.<br><br>**Escenario 2:** Given el visitante selecciona una demostración, When la visualiza, Then el sistema explica el problema detectado y la acción sugerida.<br><br>**Escenario 3:** Given una demostración no está disponible, When el visitante intenta acceder, Then el sistema informa la situación y mantiene la navegación dentro del landing page. | EP-02 |
| US-18 | Detectar automáticamente congestión crítica | Como supervisor operativo, quiero que el sistema detecte automáticamente zonas con alta congestión, para redistribuir personal antes de afectar la experiencia del comprador. | **Escenario 1:** Given una zona supera el umbral de tráfico permitido, When el sistema procesa sus métricas, Then detecta congestión crítica automáticamente.<br><br>**Escenario 2:** Given se detecta congestión crítica, When el sistema genera la alerta, Then asigna prioridad alta o crítica según la intensidad registrada.<br><br>**Escenario 3:** Given la congestión disminuye, When las métricas vuelven a niveles normales, Then el sistema permite resolver o cerrar la alerta operativa. | EP-01 |
| US-19 | Detectar productos con alta interacción y baja conversión | Como gerente retail, quiero identificar productos con alta interacción y baja conversión, para ejecutar acciones correctivas antes de generar sobrestock o pérdida de oportunidades comerciales. | **Escenario 1:** Given un producto registra muchas interacciones y pocas ventas, When el sistema calcula su desempeño, Then lo marca como producto con baja conversión.<br><br>**Escenario 2:** Given un producto es marcado con baja conversión, When el gerente revisa las recomendaciones, Then el sistema sugiere promoción, reubicación o mejora de visibilidad.<br><br>**Escenario 3:** Given se aplica una acción correctiva, When se actualiza la recomendación, Then el sistema cambia su estado a aplicada. | EP-03 |
| US-20 | Recibir promociones dinámicas según comportamiento | Como comprador frecuente, quiero recibir promociones dinámicas según mi comportamiento dentro del local, para descubrir productos relevantes sin interrumpir mi recorrido. | **Escenario 1:** Given el comprador consulta o interactúa con productos de una categoría, When existen promociones relacionadas, Then el sistema muestra promociones relevantes.<br><br>**Escenario 2:** Given el comprador se encuentra asociado a una zona o producto con oportunidad comercial, When el sistema detecta el contexto, Then muestra una promoción dinámica en el quiosco.<br><br>**Escenario 3:** Given no existen promociones relevantes, When el comprador continúa navegando, Then el sistema evita mostrar recomendaciones irrelevantes. | EP-02 |

### 3.2. Impact Mapping

![Impact Mapping](assets/images/impact-mapping.png)

### 3.3. Product Backlog

A continuación, se presenta el Product Backlog actualizado de RetailPulse, el cual organiza las User Stories en función de su valor para el negocio y su prioridad dentro del desarrollo del producto. Se mantiene la estructura general del backlog anterior, incorporando únicamente las historias avanzadas agregadas para responder al feedback recibido sobre automatización inteligente, workflows operacionales, eventos críticos y comportamiento del dominio.

| # Orden | User Story ID | Título | Descripción | Prioridad | Story Points |
|--------|---------------|--------|-------------|-----------|--------------|
| 1 | US-01 | Evaluar propuesta de valor y planes SaaS | Como administrador retail visitante, quiero conocer los planes, beneficios y casos de uso de RetailPulse, para decidir si la solución puede mejorar la operación de mi tienda. | Alta | 3 |
| 2 | US-16 | Comprender impacto operativo de RetailPulse | Como visitante de página, quiero comprender cómo RetailPulse reduce fricción operativa y mejora decisiones comerciales, para evaluar su valor más allá de sus funcionalidades visuales. | Alta | 3 |
| 3 | US-17 | Visualizar demostraciones orientadas a outcomes | Como visitante de página, quiero visualizar demostraciones de RetailPulse aplicadas a situaciones reales de tienda, para entender cómo la plataforma transforma eventos del local en acciones operativas y comerciales. | Alta | 5 |
| 4 | US-04 | Encontrar productos rápidamente en tienda | Como comprador en tienda, quiero encontrar productos rápidamente mediante el quiosco, para evitar recorrer pasillos innecesarios o abandonar la compra por frustración. | Alta | 5 |
| 5 | US-09 | Recibir promociones relevantes durante la búsqueda | Como comprador en tienda, quiero recibir promociones relevantes mientras busco productos, para descubrir ofertas útiles sin interrumpir mi recorrido de compra. | Media | 3 |
| 6 | US-20 | Recibir promociones dinámicas según comportamiento | Como comprador frecuente, quiero recibir promociones dinámicas según mi comportamiento dentro del local, para descubrir productos relevantes sin interrumpir mi recorrido. | Media | 5 |
| 7 | US-05 | Atender tareas operativas priorizadas | Como colaborador de piso, quiero consultar tareas operativas priorizadas, para atender zonas, reposiciones o incidencias según su impacto en la experiencia del comprador. | Alta | 3 |
| 8 | US-03 | Recibir alertas de congestión operativa | Como supervisor de tienda, quiero recibir alertas cuando una zona supere niveles críticos de tráfico, para redistribuir personal antes de afectar la experiencia del comprador. | Alta | 3 |
| 9 | US-18 | Detectar automáticamente congestión crítica | Como supervisor operativo, quiero que el sistema detecte automáticamente zonas con alta congestión, para redistribuir personal antes de afectar la experiencia del comprador. | Alta | 5 |
| 10 | US-10 | Activar alerta por quiebre de stock consultado | Como colaborador de piso, quiero recibir alertas cuando un comprador consulta un producto sin stock, para actuar rápidamente y evitar quiebres visibles al cliente. | Alta | 5 |
| 11 | US-02 | Identificar zonas de baja conversión | Como administrador retail, quiero identificar zonas con alta interacción y baja conversión, para redistribuir productos estratégicamente y mejorar el rendimiento del local. | Alta | 8 |
| 12 | US-06 | Detectar zonas calientes y zonas muertas | Como administrador retail, quiero identificar zonas calientes y zonas muertas dentro del local, para ajustar la distribución comercial con base en comportamiento real. | Alta | 8 |
| 13 | US-08 | Detectar patrones de circulación | Como administrador retail, quiero detectar patrones de circulación de clientes, para optimizar el layout comercial y mejorar el flujo de compra dentro del local. | Media | 8 |
| 14 | US-19 | Detectar productos con alta interacción y baja conversión | Como gerente retail, quiero identificar productos con alta interacción y baja conversión, para ejecutar acciones correctivas antes de generar sobrestock o pérdida de oportunidades comerciales. | Alta | 5 |
| 15 | US-07 | Recibir recomendaciones de optimización comercial | Como administrador retail, quiero recibir recomendaciones basadas en tráfico, stock e interacción, para tomar acciones correctivas sobre productos, zonas o promociones. | Media | 5 |
| 16 | US-13 | Mantener catálogo y ubicación de productos | Como administrador retail, quiero mantener productos con stock, zona y referencia de estante, para que compradores y personal trabajen con información confiable dentro de la tienda. | Alta | 5 |
| 17 | US-11 | Registrar eventos de movimiento en tienda | Como sistema de analítica, quiero registrar eventos de movimiento por zona, para alimentar el cálculo de tráfico, congestión y mapas de calor. | Media | 5 |
| 18 | US-12 | Calcular métricas de calor y conversión | Como sistema de analítica, quiero calcular métricas de tráfico, permanencia e interacción, para generar insights accionables sobre el comportamiento dentro de la tienda. | Alta | 5 |
| 19 | US-15 | Configurar tienda y funcionalidades disponibles | Como administrador retail, quiero configurar los datos iniciales de mi tienda y las funcionalidades habilitadas por mi plan, para operar RetailPulse según el alcance contratado. | Media | 5 |
| 20 | US-14 | Acceder a información según rol operativo | Como administrador o personal autorizado, quiero acceder únicamente a las funcionalidades correspondientes a mi rol, para proteger métricas sensibles y separar responsabilidades operativas. | Media | 3 |

**Total Story Points:** 97

---

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

En esta sección se definen los pilares visuales que rigen la identidad de marca de **RetailPulse**. Estas directrices garantizan la consistencia en todos los puntos de contacto de la plataforma, desde el informe técnico hasta la interfaz de la aplicación web, transmitiendo los valores de innovación, precisión analítica y profesionalismo premium.

**A. Brand Persona**

La identidad visual de RetailPulse proyecta la imagen de una *startup* tecnológica sofisticada y confiable. Se prioriza la claridad de los datos, el minimalismo y una estética de interfaz limpia, diseñada para facilitar la toma de decisiones gerenciales mediante visualizaciones precisas.

**B. Tipografía**

Se ha seleccionado una familia tipográfica *sans-serif* moderna, optimizada para la legibilidad en pantallas de alta densidad y compatible con estándares de desarrollo web.

* **Fuentes Principales:** `Inter` o `Poppins` (Pesos: Light 300, Regular 400, Semibold 600, Bold 700, Black 900).
* **Jerarquía Tipográfica:**
    * **Títulos (H1/H2):** Peso Bold o Black, color Deep Tech Navy Blue (`#0A2540`).
    * **Cuerpo de Texto:** Peso Regular para una lectura fluida.
    * **Monospace (APIs y Backend):** `Fira Code` o `Roboto Mono` para la documentación técnica de las US-11 a US-15.

**C. Paleta de Colores**

La paleta se compone de tonos que equilibran la seriedad corporativa con el dinamismo tecnológico de la analítica de datos.

1. **Azul Marino Profundo (Deep Tech Navy Blue):**
    * **HEX:** `#0A2540`
    * **Función:** Base corporativa que transmite confianza. Se utiliza en el texto principal, encabezados y elementos estructurales.

2. **Cian Eléctrico Vibrante (Vibrant Electric Cyan):**
    * **HEX:** `#00D2FF`
    * **Función:** Acento tecnológico y moderno. Se utiliza para resaltar elementos de analítica (líneas de pulso, gráficos), botones de acción y estados activos.

3. **Blanco Puro:**
    * **HEX:** `#FFFFFF`
    * **Función:** Fondo principal para mantener un diseño minimalista, limpio y con alto contraste.

**D. Directrices del Logotipo**

<img src="assets/images/logo-retailpulse.png" alt="Logo de RetailPulse" width="350">

El logotipo debe presentarse siempre de forma legible, respetando su composición y colores originales:

* **Símbolo:** Representa la unión entre el sector retail (bolsa de compras con líneas sólidas) y la analítica (línea de pulso en cian).
* **Composición:** La palabra "Retail" se presenta en Deep Tech Navy Blue y "Pulse" en Vibrant Electric Cyan, reforzando la identidad dual de la herramienta.
* **Uso en Fondos:** Sobre fondo blanco se utiliza la versión a color. En fondos oscuros, se prefiere la versión monocromática blanca o con el acento cian resaltado.

**E. Principios de Layout y Espaciado**

* **Sistema de Grillas:** Basado en múltiplos de 8px para garantizar la armonía visual en todos los componentes de la UI.
* **Espacio Negativo:** Uso extensivo del blanco puro para reducir la carga cognitiva y destacar los KPIs críticos de la tienda.
* **Bordes:** Redondeado moderno (entre 4px y 8px) para suavizar la estética tecnológica y mejorar la experiencia de usuario.

#### 4.1.2. Web Style Guidelines

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

En el sistema RetailPulse, se emplea la organización jerárquica para priorizar la visualización de datos críticos, como los mapas de calor (*heatmaps*), alertas de zonas desatendidas y los Key Performance Indicators (KPIs) de conversión en el dashboard gerencial. Esta jerarquía visual permite que el usuario identifique de forma inmediata la información más relevante sobre el comportamiento físico de la tienda.

También se aplica una organización secuencial en procesos que requieren una guía paso a paso, como la configuración de nuevas zonas dentro del local (pasillos/góndolas), la vinculación de productos al catálogo espacial o la creación de campañas promocionales. Estos flujos siguen una progresión lógica para evitar errores de ingreso de datos y facilitar la operatividad del administrador.

En cuanto a los esquemas de categorización, no se prioriza una organización alfabética general ni matricial. Sin embargo, sí se emplea una organización cronológica para visualizar datos analíticos históricos, como los reportes comparativos de tráfico diario, el historial de interacciones por producto y el registro de incidencias del personal. Además, el contenido se clasifica estrictamente según el tipo de usuario: los Administradores acceden a módulos de analítica profunda y configuración, el Personal Operativo cuenta con paneles de tareas orientados a la acción rápida, y los Compradores (clientes) acceden a una interfaz visual de navegación interactiva en los quioscos físicos.


#### 4.2.2. Labeling Systems

El **Labeling System** define la forma en que se nombran y presentan los elementos dentro de la interfaz de usuario de RetailPulse. Su objetivo es garantizar que los usuarios comprendan de manera inmediata las funcionalidades del sistema, reduciendo la carga cognitiva y facilitando la navegación.

Dado que RetailPulse cuenta con múltiples tipos de usuario (administrador, personal de tienda y comprador), el sistema de etiquetado ha sido diseñado considerando el contexto, nivel técnico y necesidades específicas de cada uno.

---

##### 4.2.2.1. Principios de Etiquetado

Para asegurar la consistencia y claridad del sistema, se establecen los siguientes principios:

- **Claridad:** Los términos deben ser comprensibles para el usuario final sin necesidad de explicación adicional.
- **Consistencia:** Se debe utilizar el mismo término para referirse a un mismo concepto en todo el sistema.
- **Relevancia:** Las etiquetas deben estar alineadas con las tareas principales del usuario.
- **Concisión:** Se priorizan etiquetas cortas y directas.
- **Contextualización:** Las etiquetas pueden adaptarse según el tipo de usuario (administrador, personal, comprador).

---

##### 4.2.2.2. Convenciones Generales

- Se utiliza **español** como idioma principal en la interfaz.
- Se mantienen términos técnicos en inglés cuando son estándar del dominio (*Dashboard*, *Heatmap*, *Stock*).
- Se emplea **capitalización tipo oración** (solo la primera palabra en mayúscula).
- Se evita el uso de abreviaciones ambiguas.
- Los verbos en botones se presentan en forma de acción (ejemplo: "Buscar", "Ver detalle").

---

##### 4.2.2.3. Etiquetado para Administrador

| Tipo de elemento | Etiqueta | Descripción |
|-----------------|----------|------------|
| Menú principal | Dashboard | Vista general de métricas y analítica de la tienda |
| Menú principal | Mapas de calor | Visualización de tráfico por zonas |
| Menú principal | Alertas | Notificaciones operativas del sistema |
| Menú principal | Reportes | Análisis de métricas históricas |
| Menú principal | Configuración de tienda | Gestión de zonas, estantes y productos |
| Botón | Ver detalle | Accede a información específica |
| Botón | Filtrar | Permite aplicar filtros a los datos |
| Botón | Exportar | Descarga reportes en formato digital |

---

##### 4.2.2.4. Etiquetado para Personal de Tienda

| Tipo de elemento | Etiqueta | Descripción |
|-----------------|----------|------------|
| Menú principal | Tareas | Lista de tareas operativas asignadas |
| Menú principal | Alertas | Notificaciones de zonas críticas o sin stock |
| Estado | Pendiente | Tarea aún no iniciada |
| Estado | En progreso | Tarea en ejecución |
| Estado | Completado | Tarea finalizada |
| Botón | Atender | Inicia la atención de una tarea |
| Botón | Finalizar | Marca una tarea como completada |

---

##### 4.2.2.5. Etiquetado para Comprador (Quiosco Web)

| Tipo de elemento | Etiqueta | Descripción |
|-----------------|----------|------------|
| Campo de búsqueda | Buscar producto | Permite ingresar el nombre del producto |
| Resultado | Disponible | Producto en stock |
| Resultado | Sin stock | Producto no disponible |
| Información | Ubicación | Indica la zona o estante del producto |
| Información | Promoción | Muestra ofertas asociadas |
| Botón | Ver ubicación | Muestra dónde encontrar el producto |
| Botón | Nueva búsqueda | Reinicia la consulta |

---

##### 4.2.2.6. Etiquetado de Navegación Global

| Elemento | Etiqueta |
|----------|----------|
| Inicio | Inicio |
| Menú principal | Menú |
| Perfil de usuario | Mi cuenta |
| Cerrar sesión | Cerrar sesión |

---

##### 4.2.2.7. Consistencia con el Ubiquitous Language

El sistema de etiquetado se encuentra alineado con el **Ubiquitous Language** definido en la sección 2.5, asegurando que los términos utilizados en la interfaz coincidan con los conceptos del dominio.

Por ejemplo:

- "Zona" se utiliza en lugar de sinónimos como "sección" o "área".
- "Producto" se mantiene como término estándar en todo el sistema.
- "Alerta" y "Tarea operativa" conservan su significado definido en el dominio.

Esta alineación permite una integración coherente entre diseño, desarrollo y documentación, facilitando la comprensión del sistema tanto para usuarios como para el equipo técnico.

#### 4.2.3. SEO Tags and Meta Tags

El uso de **SEO Tags y Meta Tags** en RetailPulse tiene como objetivo mejorar la visibilidad de la plataforma en motores de búsqueda, facilitar la indexación del contenido y optimizar la experiencia de usuario en el acceso al landing page.

Dado que RetailPulse es una solución SaaS orientada a negocios retail, la estrategia SEO se enfoca en atraer a administradores de tiendas, emprendedores y pequeñas empresas interesadas en mejorar su operación mediante herramientas digitales.

---

##### 4.2.3.1. Objetivos de SEO

- Incrementar la visibilidad del landing page en buscadores como Google.
- Atraer tráfico orgánico de negocios retail.
- Posicionar a RetailPulse como solución innovadora en analítica de tiendas físicas.
- Mejorar la tasa de conversión mediante descripciones claras y relevantes.

---

##### 4.2.3.2. Meta Tags Principales

A continuación, se definen las etiquetas principales utilizadas en el landing page:

| Meta Tag | Descripción |
|----------|------------|
| **title** | Define el título de la página que aparece en los resultados de búsqueda. |
| **description** | Proporciona un resumen del contenido de la página. |
| **keywords** | Lista de palabras clave relevantes para el posicionamiento. |
| **viewport** | Permite la correcta visualización en dispositivos móviles. |
| **author** | Indica el autor o la organización responsable del sitio. |

---

##### 4.2.3.3. Ejemplo de Implementación

```html
<head>
  <title>RetailPulse - Analítica inteligente para tiendas físicas</title>
  <meta name="description" content="Optimiza tu tienda física con analítica de tráfico, mapas de calor y asistencia digital al cliente con RetailPulse.">
  <meta name="keywords" content="retail, analítica de tiendas, mapas de calor, SaaS retail, optimización de ventas, quiosco digital">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="author" content="RetailPulse Team">
</head>
```

#### 4.2.4. Searching Systems

El **Searching System** de RetailPulse define los mecanismos que permiten a los usuarios localizar información dentro de la plataforma de manera eficiente, precisa y sin fricción.

Dado que el sistema está orientado a distintos tipos de usuario (administrador, personal de tienda y comprador), la funcionalidad de búsqueda se adapta a cada contexto, priorizando la rapidez en el quiosco web y la precisión en los entornos de gestión.

---

##### 4.2.4.1. Objetivos del Sistema de Búsqueda

- Permitir a los compradores encontrar productos de forma rápida dentro de la tienda.
- Facilitar el acceso a información relevante para el personal y administradores.
- Reducir el tiempo necesario para completar tareas dentro del sistema.
- Minimizar errores mediante sugerencias y validaciones.

---

##### 4.2.4.2. Tipos de Búsqueda

RetailPulse implementa distintos tipos de búsqueda según el contexto de uso:

- **Búsqueda por texto:** permite ingresar el nombre de un producto o palabra clave.
- **Búsqueda asistida:** sugiere resultados automáticamente durante la escritura.
- **Búsqueda por categorías:** organiza los productos en grupos para facilitar la exploración.
- **Búsqueda contextual:** filtra resultados según la tienda, zona o disponibilidad.

---

##### 4.2.4.3. Búsqueda en el Quiosco Web

El quiosco web constituye el principal punto de interacción del comprador con el sistema, por lo que la búsqueda se diseña para ser rápida e intuitiva.

**Características principales:**

- Campo de búsqueda visible desde la pantalla principal.
- Sugerencias automáticas en tiempo real.
- Resultados claros que incluyen:
  - Nombre del producto
  - Disponibilidad
  - Ubicación dentro de la tienda
  - Promociones asociadas
- Acceso directo a la visualización de la ubicación del producto.

**Flujo de búsqueda:**

1. El usuario ingresa el nombre del producto.
2. El sistema muestra sugerencias relacionadas.
3. El usuario selecciona un resultado.
4. Se presenta la información detallada del producto.

---

##### 4.2.4.4. Búsqueda para Administrador

En el entorno administrativo, la búsqueda está orientada a la gestión y análisis de información.

**Características principales:**

- Búsqueda de productos dentro del catálogo.
- Aplicación de filtros por zona, tráfico, conversión y periodo.
- Acceso rápido a reportes y métricas específicas.

Esta funcionalidad permite al administrador tomar decisiones basadas en datos de manera eficiente.

---

##### 4.2.4.5. Búsqueda para Personal de Tienda

El personal de tienda utiliza la búsqueda para la gestión operativa diaria.

**Características principales:**

- Búsqueda de tareas asignadas.
- Filtro por estado (pendiente, en progreso, completado).
- Acceso a alertas relacionadas con productos o zonas.

---

##### 4.2.4.6. Manejo de Resultados y Errores

El sistema contempla distintos escenarios para mejorar la experiencia de usuario:

- **Sin resultados:** se informa al usuario y se sugieren alternativas.
- **Errores de escritura:** se ofrecen sugerencias automáticas.
- **Resultados ambiguos:** se priorizan los resultados más relevantes.

---

##### 4.2.4.7. Optimización del Sistema

Para garantizar un rendimiento adecuado, se consideran las siguientes prácticas:

- Uso de índices para acelerar la búsqueda.
- Implementación de caché en consultas frecuentes.
- Priorización de resultados según disponibilidad, relevancia y frecuencia de uso.

---

##### 4.2.4.8. Impacto en la Experiencia de Usuario

El sistema de búsqueda es un componente clave en RetailPulse, ya que:

- Reduce el tiempo de búsqueda de productos.
- Disminuye la dependencia del personal de tienda.
- Mejora la eficiencia operativa.
- Incrementa la probabilidad de conversión.

De esta manera, el Searching System contribuye directamente a la propuesta de valor de la plataforma.

#### 4.2.5. Navigation Systems

El **Navigation System** de RetailPulse define la estructura mediante la cual los usuarios se desplazan a través de la plataforma, permitiendo acceder de forma intuitiva a las distintas funcionalidades del sistema.

Dado que RetailPulse cuenta con múltiples tipos de usuario (administrador, personal de tienda y comprador), la navegación ha sido diseñada de manera diferenciada, adaptándose a las necesidades, contexto y objetivos de cada perfil.

---

##### 4.2.5.1. Objetivos del Sistema de Navegación

- Facilitar el acceso rápido a las funcionalidades principales del sistema.
- Reducir la cantidad de pasos necesarios para completar una tarea.
- Garantizar una experiencia intuitiva para todos los tipos de usuario.
- Mantener consistencia en la estructura de navegación en toda la plataforma.

---

##### 4.2.5.2. Tipos de Navegación

RetailPulse implementa los siguientes tipos de navegación:

**a. Navegación global**  
Presente en todas las vistas del sistema, permite acceder a las secciones principales.

**b. Navegación contextual**  
Se adapta según la funcionalidad que el usuario está utilizando.

**c. Navegación jerárquica**  
Organiza la información en niveles (ejemplo: Dashboard → Reportes → Detalle).

**d. Navegación por tareas**  
Orienta al usuario a completar acciones específicas de forma directa.

---

##### 4.2.5.3. Navegación para Administrador

El administrador accede a una navegación estructurada orientada al análisis y gestión de la tienda.

**Estructura principal:**

- Dashboard  
- Mapas de calor  
- Alertas  
- Reportes  
- Configuración de tienda  

**Características:**

- Menú lateral persistente para acceso rápido.
- Jerarquía clara de información.
- Acceso a vistas detalladas desde métricas generales.

---

##### 4.2.5.4. Navegación para Personal de Tienda

El personal de tienda requiere una navegación simple y enfocada en tareas operativas.

**Estructura principal:**

- Tareas  
- Alertas  

**Características:**

- Interfaz simplificada.
- Acceso directo a tareas prioritarias.
- Navegación orientada a acciones (atender, finalizar).

---

##### 4.2.5.5. Navegación para Comprador (Quiosco Web)

La navegación del comprador está diseñada para ser rápida, intuitiva y sin fricción.

**Características principales:**

- Pantalla inicial con buscador destacado.
- Navegación centrada en la búsqueda de productos.
- Flujo directo: búsqueda → resultado → ubicación.
- Interfaz táctil con botones grandes y claros.

**Estructura:**

- Pantalla principal (búsqueda)
- Resultados de búsqueda
- Detalle de producto
- Visualización de ubicación

---

##### 4.2.5.6. Elementos de Navegación

| Elemento | Descripción |
|----------|------------|
| Menú lateral | Permite acceder a las secciones principales del sistema |
| Barra superior | Contiene acceso a perfil y acciones generales |
| Breadcrumbs | Indican la ubicación actual del usuario dentro del sistema |
| Botones de acción | Permiten ejecutar tareas específicas |
| Enlaces internos | Facilitan la navegación entre secciones relacionadas |

---

##### 4.2.5.7. Consistencia y Usabilidad

Para garantizar una navegación efectiva, se aplican las siguientes prácticas:

- Estructura consistente en todas las vistas.
- Uso de etiquetas claras alineadas con el Ubiquitous Language.
- Reducción de niveles de navegación innecesarios.
- Retroalimentación visual al usuario (indicadores de sección activa).
- Diseño responsive adaptable a distintos dispositivos.

---

##### 4.2.5.8. Impacto en la Experiencia de Usuario

Un sistema de navegación bien diseñado permite:

- Reducir el tiempo necesario para completar tareas.
- Minimizar errores de interacción.
- Mejorar la eficiencia del personal de tienda.
- Facilitar la experiencia de compra del usuario final.

De esta manera, la navegación se convierte en un componente clave para garantizar la usabilidad y efectividad de la plataforma RetailPulse.

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

A continuación, se presentan los wireframes de las principales secciones de la landing page de RetailPulse. Cada imagen ilustra el diseño propuesto para las diferentes funcionalidades, flujos de navegación y elementos de interacción orientados tanto a dueños de negocios como a compradores finales.

---

## Principios Aplicados

**Jerarquía visual clara:**  
Los contenidos se ordenan priorizando la propuesta de valor en la parte superior (Hero Section) y distribuyendo de manera progresiva los beneficios analíticos, testimonios de éxito, preguntas frecuentes, tutoriales de configuración, contacto y descarga de reportes.

**Contraste y accesibilidad:**  
Se aseguraron contrastes adecuados entre texto y fondo para favorecer la legibilidad, especialmente en dashboards de datos, así como tamaños de fuente óptimos para usuarios con diferentes capacidades visuales.

**Optimización para dispositivos móviles:**  
Los wireframes contemplan un diseño adaptable (Responsive), reorganizando los componentes en una estructura vertical, botones de mayor tamaño para el personal operativo y menús accesibles para pantallas táctiles.

**Diseño inclusivo:**  
Cada sección permite navegación intuitiva mediante teclado y está pensada para ser compatible con tecnologías de asistencia, asegurando que los quioscos web sean fáciles de usar para todos los compradores.

---

## Versión Desktop Web Browser

En esta sección se presenta la pantalla Home de la landing page, donde se observa un botón call-to-action (CTA) principal: **"Optimiza tu tienda ahora"**. Para los administradores recurrentes, se aprecia el botón de **"Sign in"** en el toolbar superior derecho.

<img src="assets/images/landing-page-wireframe-1.png" width="90%">

---

### Flujo de acceso y secciones clave

**Inicio de sesión:**  
Interfaz limpia con campos para credenciales y acceso directo mediante Google.

<img src="assets/images/landing-page-wireframe-2.png" width="90%">

---

**Registro:**  
Formulario para nuevos administradores de retail solicitando datos del negocio.

<img src="assets/images/landing-page-wireframe-3.png" width="90%">

---

**Olvido de contraseña:**  
Flujo de recuperación mediante correo electrónico vinculado a la cuenta corporativa.

<img src="assets/images/landing-page-wireframe-4.png" width="90%">

---

**Sección de propuesta de valor:**  
Presentación de cómo RetailPulse transforma datos de tráfico en decisiones comerciales mediante analítica avanzada y asistencia al cliente.

<img src="assets/images/landing-page-wireframe-5.png" width="90%">

---

**Sección de integrantes del equipo:**  
Fichas de los 5 desarrolladores (Jesús, Anghelo, José, Luis, Fabio) con enlaces a sus perfiles profesionales.

<img src="assets/images/landing-page-wireframe-6.png" width="90%">

---

**Beneficios por segmento:**  
Frames que detallan las ventajas para el Administrador (mapas de calor, alertas) y para el Comprador (autonomía, ubicación de productos).

<img src="assets/images/landing-page-wireframe-7.png" width="90%">

---

**Sección de testimonios:**  
Comentarios simulados de gerentes de tiendas y compradores que evidencian mejoras en la experiencia de compra.

<img src="assets/images/landing-page-wireframe-8.png" width="90%">

---

**Sección de preguntas frecuentes (FAQ):**  
Desplegables con información sobre costos, integración de sensores y seguridad de datos.

<img src="assets/images/landing-page-wireframe-9.png" width="90%">

---

**Sección de contacto:**  
Formulario para consultas comerciales personalizadas y soporte técnico.

<img src="assets/images/landing-page-wireframe-10.png" width="90%">

---

**Footer:**  
Enlaces legales, mapa del sitio y redes sociales de la startup.

<img src="assets/images/landing-page-wireframe-11.png" width="90%">

#### 4.3.2. Landing Page Mock-up

## Versión Desktop Web Browser

<img src="assets/images/landing-mockup-1.png" width="90%">

---

### Flujo de acceso y secciones clave

**Inicio de sesión:**  

<img src="assets/images/landing-mockup-2.png" width="90%">

---

**Registro:**  

<img src="assets/images/landing-mockup-3.png" width="90%">

---

**Olvido de contraseña:**  

<img src="assets/images/landing-mockup-4.png" width="90%">

---

**Sección de propuesta de valor:**  

<img src="assets/images/landing-mockup-5.png" width="90%">

---

**Sección de integrantes del equipo:**  

<img src="assets/images/landing-mockup-6.png" width="90%">

---

**Beneficios por segmento:**  

<img src="assets/images/landing-mockup-7.png" width="90%">

---

**Sección de testimonios:**  

<img src="assets/images/landing-mockup-8.png" width="90%">

---

**Sección de preguntas frecuentes (FAQ):**  

<img src="assets/images/landing-mockup-9.png" width="90%">

---

**Sección de contacto:**  

<img src="assets/images/landing-mockup-10.png" width="90%">

---

**Footer:**  

<img src="assets/images/landing-mockup-11.png" width="90%">

### 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

Los wireframes de baja fidelidad para la aplicación web se diseñaron para establecer la estructura y funcionalidad básica de las principales vistas: Dashboard, Gestión de Zonas, Inventario de Productos, Suscripciones, Configuración de Tienda, Panel de Alertas Operativas y Quiosco de Consulta.

*Figura 1. Dashboard principal con métricas de tráfico y conversión.*
<img src="assets/images/wireframe1.png" alt="Dashboard principal con métricas" width="800">


*Figura 2. Configuración de la tienda y ubicación.*
<img src="assets/images/wireframe2.png" alt="Planes de Suscripción" width="800">


*Figura 3. Inventario de productos con métricas de interacción por ítem.*
<img src="assets/images/wireframe3.png" alt="Gestión de Zonas" width="800">


*Figura 4. Gestión de Zonas para la configuración del layout físico de la tienda.*
<img src="assets/images/wireframe4.png" alt="Inventario de Productos" width="800">


*Figura 5. Selección de planes de suscripción para el modelo SaaS.*
<img src="assets/images/wireframe5.png" alt="Configuración de Tienda" width="800">


*Figura 6. Panel de Alertas Operativas para el personal de tienda.*
<img src="assets/images/wireframe6.png" alt="Panel de Alertas Operativas" width="800">


*Figura 7. Quiosco web para búsqueda de productos y promociones.*
<img src="assets/images/wireframe7.png" alt="Quiosco de Consulta" width="800">


### 4.4.2. Web Applications Wireflow Diagrams

User Goal 1: Como usuario, quiero seleccionar mi perfil de acceso para ingresar a la experiencia adecuada del sistema y garantizar la seguridad de la información según mi rol.

<img src="assets/images/wireflow1.png" alt="User Goal 1" width="800">

User Goal 2: Como administrador, quiero configurar las zonas y productos de mi tienda para mantener actualizado el layout comercial y asegurar una recolección de datos precisa.

<img src="assets/images/wireflow2.png" alt="User Goal 2" width="800">

User Goal 3: Como administrador, quiero analizar el comportamiento de los clientes en cada zona para identificar puntos críticos de interacción que permitan mejorar la tasa de conversión.

<img src="assets/images/wireflow3.png" alt="User Goal 3" width="800">

User Goal 4: Como administrador, quiero revisar y comparar los planes de suscripción para elegir el que mejor se adapte a la escala de mi negocio y optimizar mis costos operativos.

<img src="assets/images/wireflow4.png" alt="User Goal 4" width="800">

User Goal 5: Como personal de tienda, quiero atender las alertas y tareas operativas en tiempo real para resolver congestiones y mantener el flujo eficiente de clientes.

<img src="assets/images/wireflow5.png" alt="User Goal 5" width="800">

User Goal 6: Como cliente, quiero buscar un producto en el quiosco para conocer su ubicación, disponibilidad y promociones de forma autónoma, optimizando mi tiempo de compra.

<img src="assets/images/wireflow6.png" alt="User Goal 6" width="800">

---

### 4.4.3. Web Applications Mock-ups

Los mock-ups de alta fidelidad para la aplicación web presentan una visión detallada de la interfaz de usuario final de RetailPulse. En estas pantallas, se ha aplicado el esquema de colores institucional, la tipografía y los componentes visuales definitivos para proporcionar una representación precisa de cómo se verá la aplicación en producción. Esto incluye las vistas del dashboard analítico, la gestión del layout de la tienda, el panel de alertas operativas, la interfaz del quiosco para compradores, el inventario detallado y la gestión del modelo SaaS.

**Mock-up 1:**

<img src="assets/images/mockup1.png" alt="Mock-up 1" width="800">


**Mock-up 2:**

<img src="assets/images/mockup2.png" alt="Mock-up 2" width="800">


**Mock-up 3:**

<img src="assets/images/mockup3.png" alt="Mock-up 3" width="800">


**Mock-up 4:**

<img src="assets/images/mockup4.png" alt="Mock-up 4" width="800">


**Mock-up 5:**

<img src="assets/images/mockup5.png" alt="Mock-up 5" width="800">


**Mock-up 6:**

<img src="assets/images/mockup6.png" alt="Mock-up 6" width="800">


**Mock-up 7:**

<img src="assets/images/mockup7.png" alt="Mock-up 7" width="800">


---

### 4.4.4. Web Applications User Flow Diagrams

User Goal 1: Como usuario, quiero seleccionar mi perfil de acceso para ingresar a la experiencia adecuada del sistema y garantizar la seguridad de la información según mi rol.

<img src="assets/images/userflow1.png" alt="User Goal 1" width="800">

User Goal 2: Como administrador, quiero configurar las zonas y productos de mi tienda para mantener actualizado el layout comercial y asegurar una recolección de datos precisa.

<img src="assets/images/userflow2.png" alt="User Goal 2" width="800">

User Goal 3: Como administrador, quiero analizar el comportamiento de los clientes en cada zona para identificar puntos críticos de interacción que permitan mejorar la tasa de conversión.

<img src="assets/images/userflow3.png" alt="User Goal 3" width="800">

User Goal 4: Como administrador, quiero revisar y comparar los planes de suscripción para elegir el que mejor se adapte a la escala de mi negocio y optimizar mis costos operativos.

<img src="assets/images/userflow4.png" alt="User Goal 4" width="800">

User Goal 5: Como personal de tienda, quiero atender las alertas y tareas operativas en tiempo real para resolver congestiones y mantener el flujo eficiente de clientes.

<img src="assets/images/userflow5.png" alt="User Goal 5" width="800">

User Goal 6: Como cliente, quiero buscar un producto en el quiosco para conocer su ubicación, disponibilidad y promociones de forma autónoma, optimizando mi tiempo de compra.

<img src="assets/images/userflow6.png" alt="User Goal 6" width="800">

---

### 4.5. Web Applications Prototyping

Para el prototipo de RetailPulse se adoptaron los siguientes criterios de interacción. El acceso al sistema comienza con una pantalla selectora de perfiles que divide la experiencia en tres flujos principales según el rol del usuario (Administrador, Personal de tienda o Cliente en quiosco).

La navegación principal para el perfil de Administrador se centraliza en un menú lateral izquierdo (sidebar) con acceso directo a las secciones de Dashboard, Configuración de tienda, Conversión, Mapa de calor y Suscripción. Las transiciones entre pantallas se diseñaron de forma lineal y directa para mantener la experiencia enfocada en el contexto de cada usuario, asegurando una navegación intuitiva y una carga visual limpia sin interrumpir el flujo principal de trabajo.

A continuación, se presenta el flujo de interacción del prototipo elaborado en Figma:

<img src="assets/images/prototyping.png" alt="Web Applications Prototyping" width="800">

Enlace al prototipo en Figma:https://www.figma.com/proto/G09z9SLcGBIqnB5xNAsgEW/WEB-APLICATION?node-id=43-9750&t=Y3G3ksXy61OqMGsm-0&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=41%3A6978&show-proto-sidebar=1

### 4.6. Domain-Driven Software Architecture

#### 4.6.1. Design-Level Event Storming

<img src="assets/images/event-storming-0.png" width="100%">

##### 1.	Unstructured Exploration

<img src="assets/images/event-storming-1.png" width="100%">

En esta fase inicial se identificaron los eventos de dominio principales de RetailPulse, sin priorizar aún un orden cronológico. Estos eventos representan los hitos clave del negocio, desde la configuración de la tienda hasta la simulación del comportamiento del cliente, la asistencia en tienda y la generación de alertas y recomendaciones.

##### 2.	Timelines

<img src="assets/images/event-storming-2.png" width="100%">

En esta fase los eventos se organizan en líneas de tiempo que representan los flujos principales del sistema: configuración del negocio, monitoreo del comportamiento en tienda, asistencia al comprador, registro de ventas y generación de inteligencia operativa. Estas secuencias permiten visualizar cómo fluye la información desde la interacción del cliente hasta la generación de decisiones accionables dentro del negocio.

##### 3.	Pain Points 

<img src="assets/images/event-storming-3.png" width="100%">

En esta fase se identifican los puntos de fricción. Estos pain points representan fallos, demoras o vacíos de información que afectan la operación del sistema, como la falta de trazabilidad de una interacción, errores en la ubicación de productos o la ausencia de alertas oportunas. Su propósito es evidenciar dónde el flujo de negocio pierde eficiencia y cómo la solución propuesta puede corregirlo.

##### 4.	Pivotal Points

<img src="assets/images/event-storming-4.png" width="100%">

Los pivotal points representan eventos determinantes dentro del ciclo de vida del sistema. Estos hitos marcan cambios relevantes, como la activación del servicio, el inicio de una sesión de monitoreo, la detección de interacción con un producto o la generación de una alerta. Son puntos críticos porque habilitan nuevas capacidades operativas o analíticas dentro de la plataforma.

##### 5.	Commands

<img src="assets/images/event-storming-5.png" width="100%">

Los comandos representan las acciones ejecutadas por un actor o por el propio sistema que desencadenan eventos dentro del dominio. Estos comandos permiten modelar la intención de negocio y enlazan las interacciones de los usuarios con las respuestas del sistema.

##### 6.	Policies

<img src="assets/images/event-storming-6.png" width="100%">

Las políticas automatizan la lógica del sistema a partir de eventos relevantes. Su función es garantizar coherencia y reacción automática frente a situaciones del negocio, como la activación del servicio, la generación de alertas por alta demanda o la emisión de recomendaciones cuando se detecta interacción sin conversión.

##### 7.	Read Models

<img src="assets/images/event-storming-7.png" width="100%">

Los read models representan las vistas del sistema que permiten consumir la información ya procesada por la lógica del dominio. En RetailPulse, estas vistas incluyen la landing page comercial, la página de registro, los paneles de suscripción, las alertas operativas y la experiencia de asistencia al comprador mediante el quiosco.

##### 8.	External Systems

<img src="assets/images/event-storming-8.png" width="100%">

Los sistemas externos representan servicios que complementan el funcionamiento de RetailPulse sin formar parte de su dominio central. En este caso, se consideran la pasarela de pago para la activación de suscripciones y el servicio de correo para el envío de notificaciones relacionadas con la operación y la cuenta del negocio.

##### 9.	Aggregates

<img src="assets/images/event-storming-9.png" width="100%">

Los aggregates representan las estructuras principales del dominio que encapsulan la lógica de negocio y mantienen la consistencia de los datos. En RetailPulse, estos agregados permiten modelar la suscripción del negocio, la configuración del local, el monitoreo de visitas, la asistencia al comprador, el registro de ventas y la generación de alertas y recomendaciones.

##### 10.	Bounded Contexts

<img src="assets/images/event-storming-10.png" width="100%">
<img src="assets/images/event-storming-11.png" width="100%">

Los bounded contexts organizan el dominio de RetailPulse en áreas funcionales independientes, cada una con su propia responsabilidad y lenguaje de negocio. Esta separación permite estructurar la solución de manera coherente, escalable y alineada con la arquitectura del sistema, conectando el Event Storming con el modelo C4 y el diseño de la base de datos.

**Enlace de Visualización:** https://miro.com/app/board/uXjVHe0Bh8Q=/?share_link_id=570174974504


#### 4.6.2. Software Architecture Context Diagram

![RetailPulse Context Diagram](assets/images/retailpulse-context-diagram.png)

#### 4.6.3. Software Architecture Container Diagrams

![RetailPulse Container Diagram](assets/images/retailpulse-container-diagram.png)

#### 4.6.4. Software Architecture Components Diagrams

![RetailPulse Container Diagram](assets/images/retailpulse-component-diagram-webservice.png)

![RetailPulse Container Diagram](assets/images/retailpulse-component-diagram-webapp.png)

### 4.7. Software Object-Oriented Design

#### 4.7.1. Class Diagrams

##### 1. Traffic Analytics Context

<img src="assets/images/class-diagram-1.png" width="100%">

Este bounded context modela el análisis del comportamiento físico dentro de la tienda. Permite representar el layout comercial, zonas de tráfico, métricas de calor, zonas muertas y congestión, alineándose con la retroalimentación que pedía un dominio más orientado a eventos, comportamiento e invariantes.

##### 2. Store Operations Context

<img src="assets/images/class-diagram-2.png" width="100%">

Este bounded context representa la operación diaria del personal de tienda. Modela alertas, tareas operativas, escalamiento, asignación de personal y resolución de incidencias, evitando que el sistema se limite a mostrar una pantalla de alertas.

##### 3. Assisted Shopping Context

<img src="assets/images/class-diagram-3.png" width="100%">

Este bounded context modela la experiencia del comprador dentro del quiosco web. Representa búsquedas asistidas, productos consultados, disponibilidad, ubicación, promociones y abandono de sesión, alineándose con el objetivo de reducir fricción durante la compra.

##### 4. Inventory Intelligence Context

<img src="assets/images/class-diagram-4.png" width="100%">

Este bounded context representa la inteligencia de inventario. Permite modelar productos disponibles, stock crítico, quiebre de stock, reposición y ubicación física, evitando que el inventario sea tratado solo como CRUD.

##### 5. Promotion Optimization Context

<img src="assets/images/class-diagram-5.png" width="100%">

Este bounded context modela recomendaciones comerciales basadas en interacción, conversión y desempeño de productos. Su objetivo es convertir datos de comportamiento en acciones como promociones, reubicaciones o recomendaciones estratégicas.

##### 6. Subscription Context

<img src="assets/images/class-diagram-6.png" width="100%">

Este bounded context se mantiene como contexto de soporte del modelo SaaS. Permite gestionar la cuenta, los planes, el estado de suscripción y el cambio de plan, pero no representa el core domain principal de RetailPulse.


### 4.8. Database Design

#### 4.8.1. Database Diagrams

![RetailPulse Database](assets/images/retailpulse-database.png)

##### Bounded Context: Subscription

Este contexto representa el modelo SaaS de RetailPulse. Permite gestionar las cuentas de negocio, usuarios, planes disponibles y suscripciones activas. Se considera un contexto de soporte, ya que no representa la ventaja principal del dominio retail, pero permite controlar el acceso a funcionalidades según el plan contratado.

![RetailPulse Subscription Context Database](assets/images/retailpulse-database-subscription-context.png)

##### Bounded Context: Store Foundation

Este contexto contiene la estructura base de la tienda física. Modela la tienda, su layout, zonas comerciales y productos registrados. Aunque no es un core domain por sí mismo, sirve como base para que los demás contextos puedan analizar tráfico, ubicar productos, generar alertas y construir recomendaciones.

![RetailPulse Store Foundation Context Database](assets/images/retailpulse-database-store-foundation-context.png)

##### Bounded Context: Traffic Analytics

Este contexto permite analizar el comportamiento físico de los compradores dentro de la tienda. Registra métricas de heatmap, métricas por zona, recorridos simulados de clientes e interacciones con productos. Su propósito es convertir el movimiento dentro del local en información útil para la toma de decisiones.

![RetailPulse Traffic Analytics Context Database](assets/images/retailpulse-database-traffic-analytics-context.png)

##### Bounded Context: Assisted Shopping

Este contexto representa la experiencia del comprador dentro del quiosco web. Permite registrar sesiones de búsqueda y consultas de productos, ayudando al comprador a encontrar disponibilidad, ubicación y promociones dentro de la tienda.

![RetailPulse Assisted Shopping Context Database](assets/images/retailpulse-database-assisted-shopping-context.png)

##### Bounded Context: Inventory Intelligence

Este contexto administra la disponibilidad de productos dentro de la tienda. Modela el stock actual, umbrales críticos, estado de inventario, ubicación por zona y promoción asociada. Su objetivo es detectar productos sin stock o con stock crítico para activar acciones operativas.

![RetailPulse Inventory Intelligence Context Database](assets/images/retailpulse-database-inventory-intelligence-context.png)

##### Bounded Context: Store Operations

Este contexto representa la operación diaria del personal de tienda. Permite gestionar alertas operativas y tareas asignadas, relacionadas con congestión de zonas, reposición de productos o atención de incidencias. Su objetivo es convertir eventos relevantes del sistema en acciones concretas para el personal.

![RetailPulse Store Operations Context Database](assets/images/retailpulse-database-store-operations-context.png)

##### Bounded Context: Promotion Optimization

Este contexto representa la inteligencia comercial de RetailPulse. Modela brechas de conversión, desempeño de productos, promociones y recomendaciones comerciales. Su objetivo es detectar productos con alta interacción y baja conversión para sugerir acciones que mejoren las ventas.

![RetailPulse Promotion Optimization Context Database](assets/images/retailpulse-database-promotion-optimization-context.png)

---

## Capítulo V: Product Implementation, Validation & Deployment

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration

En esta sección se describen las herramientas, tecnologías y entornos utilizados para el desarrollo del proyecto RetailPulse, considerando todas las actividades del ciclo de vida: diseño, desarrollo, colaboración y despliegue.

---

#### UX/UI Design

**Figma**  
Herramienta de diseño colaborativo utilizada para la creación de wireframes, mockups, prototipos y flujos de usuario. Permite validar tempranamente la experiencia del usuario y asegurar consistencia visual entre el Landing Page y la Web Application.

---

#### Software Development

**Visual Studio Code**  
Editor de código utilizado como entorno principal de desarrollo tanto para el frontend como para configuraciones generales del proyecto. Destaca por su ligereza, extensibilidad mediante plugins y soporte para múltiples lenguajes.

**WebStorm**  
IDE especializado en desarrollo frontend utilizado para trabajar con Angular, facilitando la navegación del proyecto, debugging y gestión de componentes.

**GitHub**  
Plataforma de control de versiones utilizada para la gestión del código fuente y colaboración del equipo. Se implementa la estrategia GitFlow, junto con Conventional Commits, para mantener un historial ordenado y trazable del desarrollo.

---

#### Frontend Development

**HTML5**  
Lenguaje de marcado utilizado para estructurar las interfaces de usuario del sistema.

**CSS3**  
Lenguaje de estilos utilizado para el diseño visual, layout y adaptación responsive de la aplicación.

**TypeScript**  
Lenguaje utilizado en el desarrollo frontend, proporcionando tipado estático y mejor mantenibilidad del código.

**Angular**  
Framework principal para el desarrollo de la Web Application. Permite construir interfaces dinámicas, modulares y escalables mediante componentes reutilizables, servicios y manejo de estados.

---

#### Backend Development

**Java**  
Lenguaje de programación utilizado para el desarrollo de la lógica del lado servidor.

**Spring Boot**  
Framework utilizado para la construcción del RESTful API. Permite desarrollar servicios robustos, escalables y desacoplados, facilitando la creación de endpoints, manejo de dependencias e integración con bases de datos.

#### Software Deployment

**GitHub Pages**  
Servicio utilizado para el despliegue del Landing Page del proyecto, permitiendo su acceso público como punto de entrada al modelo de negocio.

**Vercel / Netlify (Frontend)**  
Plataforma utilizada para el despliegue del frontend desarrollado en Angular, facilitando integración continua, builds automáticos y distribución global.

**Railway / Azure Web Apps (Backend)**  
Plataforma utilizada para el despliegue del RESTful API desarrollado en Spring Boot, permitiendo exponer servicios en la nube y gestionar variables de entorno.

---


#### 5.1.2. Source Code Management

Para la gestión del código fuente del proyecto RetailPulse, el equipo utiliza GitHub como plataforma central de control de versiones y colaboración entre los miembros. Se ha optado por trabajar con una organización que agrupa múltiples repositorios, cada uno enfocado en un componente específico del sistema. A continuación, se detallan los repositorios utilizados:

* Organización: <https://github.com/RetailPulse-NRC11863>
* Repositorio de Landing Page: <https://github.com/RetailPulse-NRC11863/retailpulse-landing-page>
* Repositorio del Informe: <https://github.com/RetailPulse-NRC11863/retailpulse-report>
* Repositorio del Frontend: <https://github.com/RetailPulse-NRC11863/retailpulse-web-application>
* Repositorio del Backend: <https://github.com/RetailPulse-NRC11863/retailpulse-web-services>

En el repositorio del informe se implementa un flujo de trabajo basado en GitFlow. La rama `main` se utiliza para almacenar versiones estables del documento correspondientes a cada entrega del proyecto del curso, mientras que la rama `develop` actúa como punto de integración de los avances realizados por los integrantes del equipo. A partir de `develop`, cada miembro del equipo crea ramas de tipo `feature/...` para desarrollar las secciones asignadas del informe.

Las ramas feature siguen una nomenclatura relacionada al contenido trabajado, por ejemplo: `feature/chapter-1-introduction` o `feature/chapter-5-software-management`. Esta convención facilita la organización del trabajo, permite identificar rápidamente el alcance de cada rama y reduce conflictos durante la integración.

En los repositorios correspondientes a la Landing Page, Frontend y Backend también se aplica GitFlow. En estos casos, la rama `main` representa versiones funcionales y estables del producto, mientras que `develop` se utiliza como rama de integración continua del desarrollo. Las ramas `feature/...` se crean a partir de `develop`, pero a diferencia del informe, su nomenclatura está orientada a funcionalidades específicas del sistema, tales como `feature/heatmap-dashboard`, `feature/store-configuration` o `feature/sensor-integration`.

Se establece como regla que no se realizarán cambios directos sobre la rama `main`, ya que esta debe contener únicamente versiones validadas. Asimismo, el trabajo diario no se realiza directamente sobre `develop`, sino mediante ramas `feature`, las cuales posteriormente son integradas a `develop` y finalmente consolidadas en `main` una vez revisadas. De esta manera, el flujo de trabajo definido es: `feature → develop → main`, siguiendo las buenas prácticas de GitFlow.

Adicionalmente, en caso de requerirse correcciones urgentes sobre versiones estables, se emplearán ramas `hotfix/...`, y para la preparación de entregables se podrán utilizar ramas `release/...`, manteniendo coherencia con el flujo establecido.

Para el control de versiones, el equipo adopta la convención de Conventional Commits, lo que permite mantener un historial de cambios claro, consistente y fácil de auditar. Los principales prefijos utilizados son:

* feat: incorporación de nuevas funcionalidades
* fix: corrección de errores
* docs: cambios en documentación
* style: ajustes de formato o estilo sin afectar la lógica
* refactor: reestructuración del código sin cambios funcionales
* test: adición o modificación de pruebas
* chore: tareas de mantenimiento o configuración

En el repositorio del informe se emplean mensajes como `docs(report): add project cover page` o `docs: add startup profile and lean ux process for chapter 1`. En los repositorios de software se utilizan mensajes como `feat: implement heatmap visualization`, `feat: add sensor event tracking` o `fix: correct authentication validation`. Esta práctica asegura que el historial de commits refleje de manera clara el trabajo realizado por cada integrante del equipo.

#### 5.1.3. Source Code Style Guide & Conventions

**HTML5 (Angular Templates)**

En este proyecto de RetailPulse (Angular), la estructura de la landing page se define en templates HTML (app.html) con enfoque semántico, accesible y mantenible.

- Usar etiquetas semánticas como header, main, section y footer para organizar claramente la página.
- Mantener etiquetas y atributos en minúsculas.
- Cerrar correctamente todas las etiquetas.
- Respetar la jerarquía de títulos h1, h2 y h3 por sección.
- Incluir alt en imágenes y aria-label en botones o iconos cuando corresponda.
- Usar rutas estáticas consistentes para assets, como /assets/images/.
- Evitar texto hardcodeado cuando ya existe i18n; preferir bindings desde copy() para traducciones.
- Usar la sintaxis de control de Angular (@for, @if) de forma clara y legible.
- Evitar estructuras de marcado innecesariamente complejas.

**CSS**

Los estilos se gestionan principalmente en app.css con variables, layout responsive y soporte de tema claro y oscuro.

- Usar nombres de clase descriptivos y consistentes con el componente, como brand-*, benefit-* y contact-*.
- Centralizar colores y tokens en variables CSS, por ejemplo en :host y :host.theme-dark.
- Mantener indentación uniforme y bloques agrupados por sección visual.
- Reutilizar estilos comunes como button, grids y cards para evitar duplicación.
- Priorizar diseño responsive con breakpoints definidos, por ejemplo 960px y 640px.
- Evitar selectores excesivamente específicos.
- Mantener reglas de estado claras, como .active y .visible.
- Controlar la experiencia de formularios con estilos de foco visibles.
- Usar resize: none en textarea cuando se busque un layout fijo.

**TypeScript (Angular)**

En este proyecto, la lógica está implementada en TypeScript (app.ts, i18n.service.ts, translations.ts), no en JavaScript puro.

- Nombrar variables y métodos en camelCase.
- Mantener tipado explícito, como Theme, Language y Record.
- Preferir readonly y encapsulación private o protected cuando aplique.
- Mantener funciones cortas y con una sola responsabilidad.
- Usar Signals de Angular para estado reactivo.
- Usar constantes para keys de localStorage, como THEME_STORAGE_KEY.
- Evitar acceso directo al DOM sin inyección; usar DOCUMENT cuando sea necesario.
- Manejar cleanup de recursos, como timers, en ngOnDestroy.
- Para formularios de la landing, interceptar submit con preventDefault si aún no existe backend.
- Mantener la lógica de i18n centralizada en traducciones y servicio, no en el template.

**Gherkin**

Para documentar el comportamiento funcional de la landing, se deben usar escenarios claros y trazables a user stories.

- Redactar escenarios cortos y directos.
- Usar la estructura estándar Given, When y Then.
- Definir un escenario por funcionalidad principal.
- Evitar redundancias entre escenarios.
- Cubrir funcionalidades actuales del proyecto, como:
  - cambio de idioma (ES/EN),
  - cambio de tema (claro/oscuro) y persistencia,
  - envío simulado del formulario con toast de confirmación,
  - render correcto de imágenes en header, equipo y beneficios,
  - comportamiento responsive en desktop y móvil.

#### 5.1.4. Software Deployment Configuration

Para la publicación en línea del proyecto **RetailPulse Landing Page**, se implementó un proceso de despliegue automatizado utilizando **Netlify** como plataforma principal de hosting y **GitHub** como repositorio central del código fuente. Esta configuración permite una integración continua (CI) y despliegue continuo (CD), asegurando la disponibilidad, rendimiento y actualización constante del sitio web.


### Proceso de Despliegue

**1. Integración con Repositorios Git**  
El repositorio del proyecto se encuentra alojado en GitHub. Netlify se conecta directamente al repositorio, lo que permite que cada vez que se realiza un *push* o un *merge* a la rama principal (`main`), se ejecute automáticamente el proceso de construcción y despliegue del sitio.

**2. Compilación Automatizada**  
Durante el proceso de build, Netlify ejecuta el comando `npm run build`.

Esto permite compilar la aplicación Angular y generar una versión optimizada para producción. Este proceso incluye:

- Minificación de archivos HTML, CSS y JavaScript.  
- Optimización de recursos estáticos (imágenes, fuentes).  
- Generación de archivos listos para despliegue en el directorio `/dist/RetailPulse/browser`.

**3. Despliegue en Netlify**  
Una vez finalizada la compilación, Netlify distribuye automáticamente el contenido en su red global de entrega de contenido (CDN), garantizando tiempos de carga rápidos y alta disponibilidad desde cualquier ubicación.

**4. Vistas Previas por Rama (Deploy Previews)**  
Netlify genera automáticamente una vista previa del sitio por cada rama o Pull Request. Esto permite al equipo revisar los cambios antes de ser integrados a la rama principal, facilitando la detección temprana de errores y validación visual.

**5. Despliegue Continuo (Continuous Deployment)**  
Cada vez que se realiza un merge a la rama `main`, Netlify actualiza automáticamente la versión en producción. De esta manera, el sitio siempre refleja la versión más reciente y estable del proyecto.


### Productos Desplegados

- **Landing Page de RetailPulse:** Aplicación web desarrollada en Angular y desplegada en Netlify, accesible públicamente mediante una URL generada automáticamente por la plataforma.

### 5.2. Landing Page, Services & Applications Implementation

#### 5.2.1. Sprint 1

##### 5.2.1.1. Sprint Planning 1

A continuación, se presenta la planificación correspondiente al Sprint 1 del proyecto RetailPulse, el cual tiene como enfoque principal la validación de la propuesta de valor mediante la implementación del landing page y una primera funcionalidad básica de búsqueda de productos en tienda. En esta etapa inicial, el equipo definió el objetivo del sprint, seleccionó las historias de usuario más relevantes y estableció los entregables clave que permitirán construir una primera versión funcional y visualmente clara del sistema.

<table>
  <tr>
    <th>Sprint #</th>
    <th>Sprint 1</th>
  </tr>

  <tr>
    <td><strong>Sprint Planning Background</strong></td>
    <td>Primera planificación del proyecto enfocada en validar la propuesta de valor del sistema RetailPulse.</td>
  </tr>

  <tr>
    <td>Date</td>
    <td>2026-04-23</td>
  </tr>

  <tr>
    <td>Time</td>
    <td>23:00 pm (GMT-5)</td>
  </tr>

  <tr>
    <td>Location</td>
    <td>Modalidad remota mediante la plataforma Discord</td>
  </tr>

  <tr>
    <td>Prepared By</td>
    <td>Vallejo Trujillo, Fabio Cesar</td>
  </tr>

  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>
      Faustino Hurtado, Anghelo Edwin / Franco del Carpio, José María / Godoy Santillan, Jesus Andres / Rubio Ortiz, Luis Sebastián / Vallejo Trujillo, Fabio Cesar
    </td>
  </tr>

  <tr>
    <td>Sprint 0 Review Summary</td>
    <td>Dado que este es el sprint inicial del proyecto, no se cuenta con un sprint previo a evaluar.</td>
  </tr>

  <tr>
    <td>Sprint 0 Retrospective Summary</td>
    <td>Al tratarse del primer sprint, no se dispone de retroalimentación previa.</td>
  </tr>

  <tr>
    <td><strong>Sprint Goal & User Stories</strong></td>
    <td></td>
  </tr>

  <tr>
    <td>Sprint 1 Goal</td>
    <td>
      El objetivo del Sprint 1 es validar la propuesta de valor de RetailPulse mediante la implementación del landing page y una funcionalidad básica de búsqueda de productos en tienda.
      <br><br>
      Se busca que los usuarios comprendan claramente el valor del sistema, puedan visualizar sus beneficios y explorar una simulación inicial de interacción dentro del entorno de tienda.
    </td>
  </tr>

  <tr>
    <td>Sprint 1 Velocity</td>
    <td>19 puntos</td>
  </tr>

  <tr>
    <td>Sum of Story Points</td>
    <td>19 puntos</td>
  </tr>
</table>

##### 5.2.1.2. Aspect Leaders and Collaborators

Durante el Sprint 1, el equipo se enfocó exclusivamente en la validación de la propuesta de valor de RetailPulse mediante el desarrollo del Landing Page. En este contexto, se definieron los principales aspectos relacionados al diseño, contenido y experiencia de usuario de la página.

Para asegurar una correcta organización del equipo, se elaboró la matriz LACX (Leader and Collaborators), asignando a cada integrante un rol de liderazgo (L) en un aspecto específico del landing page y participación como colaborador (C) en los demás.

| Team Member (Last Name, First Name) | GitHub Username | Hero Section & Value Proposition | About Us | Benefits | Demonstrations | Contact |
|-----------------------------------|----------------|----------------------------------|----------|----------|----------------|---------|
| Vallejo Trujillo, Fabio Cesar     | fabiovallejo   | L                                | C        | C        | C              | C       |
| Godoy Santillan, Jesus Andres     | JesusGodoyS    | C                                | L        | C        | C              | C       |
| Rubio Ortiz, Luis Sebastián       | notoriussxd    | C                                | C        | L        | C              | C       |
| Faustino Hurtado, Anghelo Edwin   | Limos05        | C                                | C        | C        | L              | C       |
| Franco del Carpio, José María     | VoltTrd        | C                                | C        | C        | C              | L       |

##### 5.2.1.3. Sprint Backlog 1
![Sprint Backlog 1](assets/images/sprint_backlog_1.png)

**Duración:** 2 semanas

**Objetivo del Sprint:**  
Validar la propuesta de valor de RetailPulse mediante la implementación del landing page y habilitar la funcionalidad básica de búsqueda de productos en tienda.

<table>
<tr>
  <th>Sprint #</th>
  <th colspan="7">Sprint 1</th>
</tr>

<tr>
  <th colspan="2">User Story</th>
  <th colspan="6">Work-Item / Task</th>
</tr>

<tr>
  <th>Id</th>
  <th>Title</th>
  <th>Id</th>
  <th>Title</th>
  <th>Description</th>
  <th>Estimation (Hours)</th>
  <th>Assigned To</th>
  <th>Status</th>
</tr>

<tr>
  <td rowspan="2">US-01</td>
  <td rowspan="2">Evaluar propuesta de valor y planes SaaS</td>
  <td>T-01</td>
  <td>Redactar contenido del landing</td>
  <td>Definir textos de valor, beneficios y casos de uso de RetailPulse orientados a operación, inventario, tráfico y conversión.</td>
  <td>5</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-02</td>
  <td>Diseñar sección de planes SaaS</td>
  <td>Construir la visualización de planes, beneficios y diferencias entre Starter, Growth y Premium.</td>
  <td>5</td>
  <td>Godoy Santillan, Jesus Andres</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-16</td>
  <td rowspan="2">Comprender impacto operativo de RetailPulse</td>
  <td>T-03</td>
  <td>Sección de impacto operativo</td>
  <td>Mostrar cómo RetailPulse reduce fricción operativa, mejora la atención, optimiza stock y apoya decisiones comerciales.</td>
  <td>5</td>
  <td>Franco del Carpio, José María</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-04</td>
  <td>Casos de uso en tienda</td>
  <td>Ejemplificar escenarios reales como congestión, quiebre de stock, búsqueda de productos y recomendaciones comerciales.</td>
  <td>4</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-17</td>
  <td rowspan="2">Visualizar demostraciones orientadas a outcomes</td>
  <td>T-05</td>
  <td>Diseñar demos visuales</td>
  <td>Crear mockups o secciones visuales que representen heatmap, alertas, quiosco y recomendaciones aplicadas a situaciones reales.</td>
  <td>6</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-06</td>
  <td>Integrar demos en landing</td>
  <td>Incorporar las demostraciones dentro del flujo del landing page, explicando el problema detectado y la acción sugerida.</td>
  <td>4</td>
  <td>Godoy Santillan, Jesus Andres</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-04</td>
  <td rowspan="2">Encontrar productos rápidamente en tienda</td>
  <td>T-07</td>
  <td>Formulario de búsqueda en quiosco</td>
  <td>Implementar input y lógica básica para que el comprador pueda buscar productos dentro de la tienda.</td>
  <td>6</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-08</td>
  <td>Resultados de búsqueda</td>
  <td>Mostrar productos encontrados con disponibilidad, zona, referencia de estante y datos simulados.</td>
  <td>5</td>
  <td>Franco del Carpio, José María</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-09</td>
  <td rowspan="2">Recibir promociones relevantes durante la búsqueda</td>
  <td>T-09</td>
  <td>Panel de promociones relevantes</td>
  <td>Diseñar el módulo visual de promociones relacionadas al producto o categoría consultada.</td>
  <td>4</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-10</td>
  <td>Integración de promociones en búsqueda</td>
  <td>Mostrar promociones relevantes dentro del flujo de búsqueda del quiosco, evitando ofertas irrelevantes.</td>
  <td>4</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

</table>

**Total Story Points:** 19

---

##### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo trabajó bajo la metodología GitFlow, utilizando múltiples ramas feature para desarrollar de forma paralela cada sección del informe y funcionalidades del sistema. La integración se realizó progresivamente hacia la rama **develop**, evidenciando un flujo continuo de commits y contribuciones por parte de todos los integrantes del equipo.

A continuación, se presenta el registro completo de commits realizados durante el desarrollo del Sprint 1.


<table>
<tr>
<th>Repository</th>
<th>Branch</th>
<th>Commit Message</th>
<th>Author</th>
<th>Date</th>
</tr>

<!-- APR 23 -->
<tr><td>RetailPulse/report</td><td>feature/student-outcome</td><td>docs: added student outcome for the project</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-5-aspect-leaders-and-collaborators</td><td>docs: added aspect leaders and collaborators for chapter 5</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-5-sprint-1</td><td>refactor(sprint-1): modified sprint backlog 1 for chapter 5</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-5-sprint-1</td><td>docs: added sprint planning 1 and sprint backlog 1</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3-impact-mapping</td><td>Merge pull request feature/chapter-3-impact-mapping</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs(chapter1): update Luis profile</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>assets</td><td>docs(assets): add profile picture for Luis</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/conclusiones</td><td>docs: added conclusions for the project</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>docs: added second segment interview</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>docs(report): add impact mapping image reference</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4-class-diagrams</td><td>docs: added class diagrams for chapter 4</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>assets</td><td>docs(assets): add impact mapping diagram</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-5</td><td>docs: added software environment configuration</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3-user-stories-luis</td><td>Merge pull request feature/chapter-3-user-stories-luis</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>docs: add user stories 6-10</td><td>notoriussxd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>docs: added big picture event storming</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: added design level event storming</td><td>fabiovallejo</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: added navigation systems</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: added searching systems</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: added seo tags and meta tags</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: added labeling systems</td><td>VoltTrd</td><td>23-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>added product backlog</td><td>VoltTrd</td><td>23-04-2026</td></tr>

<!-- APR 22 -->
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>added ubiquitous language</td><td>VoltTrd</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs: added antecedentes y problematica</td><td>ItsFlaZer</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs: added target segments</td><td>fabiovallejo</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>docs: added user stories 16 and 17</td><td>fabiovallejo</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>docs: add interviews</td><td>fabiovallejo</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: add style guidelines</td><td>limozz05</td><td>22-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>docs: update user stories backend focus</td><td>limozz05</td><td>22-04-2026</td></tr>

<!-- APR 21 -->
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: software architecture components diagrams</td><td>fabiovallejo</td><td>21-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: software architecture container diagram</td><td>fabiovallejo</td><td>21-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>develop</td><td>Merge branch feature/chapter-4-database-design</td><td>fabiovallejo</td><td>21-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>refactor(database): normalize schema</td><td>fabiovallejo</td><td>21-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>docs: add competitors and analysis</td><td>limozz05</td><td>21-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs: lean ux</td><td>limozz05</td><td>21-04-2026</td></tr>

<!-- APR 20 -->
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: add C4 context diagram</td><td>fabiovallejo</td><td>20-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-4</td><td>docs: add database diagrams</td><td>fabiovallejo</td><td>20-04-2026</td></tr>

<!-- APR 19 -->
<tr><td>RetailPulse/report</td><td>feature/chapter-3</td><td>docs: add user stories 1-5</td><td>fabiovallejo</td><td>19-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-2</td><td>docs: add interview questions</td><td>fabiovallejo</td><td>19-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-5</td><td>docs: add source code management</td><td>fabiovallejo</td><td>19-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs: add lean ux problem statements</td><td>fabiovallejo</td><td>19-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>feature/chapter-1</td><td>docs: add startup profile</td><td>fabiovallejo</td><td>19-04-2026</td></tr>
<tr><td>RetailPulse/report</td><td>main</td><td>docs: initialize project report structure</td><td>fabiovallejo</td><td>19-04-2026</td></tr>

<!-- FRONTEND -->
<tr><td>RetailPulse/frontend</td><td>feature/chapter-5-code</td><td>feat(landing): add initial landing page implementation</td><td>notoriussxd</td><td>23-04-2026</td></tr>

</table>

<br>

<h6>Branches utilizadas durante el Sprint 1</h6>

<table>
<tr>
<th>Branch</th>
<th>Descripción</th>
</tr>

<tr><td>main</td><td>Versión estable del repositorio</td></tr>
<tr><td>develop</td><td>Rama de integración principal</td></tr>

<tr><td>feature/chapter-1-*</td><td>Startup, Lean UX, Problem Statements</td></tr>
<tr><td>feature/chapter-2-*</td><td>Entrevistas, Event Storming, Competidores</td></tr>
<tr><td>feature/chapter-3-*</td><td>User Stories, Impact Mapping, Backlog</td></tr>
<tr><td>feature/chapter-4-*</td><td>C4, Base de Datos, DDD, Class Diagrams</td></tr>
<tr><td>feature/chapter-5-*</td><td>Sprint Planning, Spring Backlog, Evidence</td></tr>
<tr><td>feature/conclusiones</td><td>Conclusiones del proyecto</td></tr>
<tr><td>feature/student-outcome</td><td>Evaluación del equipo</td></tr>

</table>

##### 5.2.1.5. Execution Evidence for Sprint Review

Durante el primer sprint, se lograron avances importantes en el desarrollo de la landing page de **RetailPulse**. A continuación, se presentan las evidencias de ejecución relacionadas con la implementación, organización del repositorio y visualización de las secciones principales del sitio web.

#### Evidencias del Sprint

- **Establecimiento del repositorio:**  
  Se creó y configuró el repositorio del proyecto en GitHub para gestionar el código fuente de la landing page, permitiendo mantener un control de versiones adecuado y facilitar el trabajo colaborativo del equipo.

  **Evidencia:**  
  _Insertar imagen del repositorio en GitHub._

  ![Repositorio del proyecto](assets/images/imagen-repositorio.png)

- **Implementación de la Landing Page:**  
  Se diseñó y desarrolló la landing page de **RetailPulse**, orientada a una plataforma SaaS para retail físico, integrando secciones informativas que presentan la propuesta de valor, funcionalidades principales, beneficios y canales de contacto.

#### Imágenes del Landing Page

- **Inicio:**  
  Sección principal de bienvenida donde se presenta la propuesta de valor de RetailPulse, destacando la digitalización de tiendas físicas mediante inteligencia de e-commerce.

  ![Sección Inicio](assets/images/imagen-inicio.png)

- **Nosotros:**  
  Sección informativa donde se describe el propósito de RetailPulse y el enfoque de la solución para mejorar la experiencia de compra en tiendas físicas.

  ![Sección Nosotros](assets/images/imagen-nosotros.png)

- **Beneficios:**  
  Sección donde se muestran las funcionalidades clave y beneficios principales de la plataforma, como monitoreo en tiempo real, mapas de calor y asistencia al comprador.

  ![Sección Beneficios](assets/images/imagen-beneficios.png)

- **Preguntas frecuentes:**  
  Sección destinada a resolver dudas comunes de los usuarios sobre el funcionamiento, alcance y uso de RetailPulse.

  ![Sección Preguntas Frecuentes](assets/images/imagen-preguntas-frecuentes.png)

- **Contacto:**  
  Sección final del landing page que permite al usuario visualizar los medios de contacto o solicitar información adicional sobre la solución.

  ![Sección Contacto](assets/images/imagen-contacto.png)

##### 5.2.1.6. Services Documentation Evidence for Sprint Review
  Durante este sprint se completó el diseño e implementación del Landing Page de la plataforma RetailPulse, el cual constituye el punto de entrada fundamental para nuestros dos segmentos objetivos: administradores de tiendas físicas y compradores finales.

  Aunque en esta etapa inicial del desarrollo no se implementaron endpoints de tipo REST para la lógica de negocio (Backend), se documenta a continuación la URL del recurso estático publicado, junto con la evidencia de su despliegue en producción y el repositorio de control de versiones correspondiente.

-	Implementación del Landing Page: Desarrollo de la interfaz responsiva con secciones de propuesta de valor, beneficios por segmento, equipo y planes SaaS.
-	Deployment del Recurso: Despliegue exitoso a través de GitHub Pages para su visualización pública.

### Recursos del Sprint

| Recurso      | Acción implementada   | Método HTTP | URL / Endpoint                                                              | Link de repositorio                                                         |
| ------------ | ---------------------- | ------------ | --------------------------------------------------------------------------- | --------------------------------------------------------------------------- |
| Landing Page | Visualización inicial | GET          | https://retailpulselandingpage.netlify.app/ | https://github.com/RetailPulse-NRC11863/retailpulse-landing-page |

##### 5.2.1.7. Software Deployment Evidence for Sprint Review

Este punto se encarga de registrar la evidencia del despliegue realizado durante el Sprint, incluyendo la configuración del repositorio, la configuración del sitio en Netlify y la verificación del despliegue en producción.

**Creación de Repositorios y Configuración en GitHub**

- Se creó una organización en GitHub para alojar todos los repositorios referentes al trabajo, este incluyendo el reporte y la Landing Page.
- Se subió el código fuente del proyecto en su respectivo repositorio para poder realizar luego un despliegue con la herramienta **Netlify**.
- Se verificó la trazabilidad de cambios mediante commits y creación de ramas extra para poder genera un orden en el desarrollo de cada punto o capítulo.

![GitHub - Vista del repositorio RetailPulse](assets/images/01-github-repo.png)

![GitHub - Historial de commits](assets/images/02-github-commits.png)

**Configuración de despliegue en Netlify**
- En Netlify, se seleccionó **"Add new project" -> Import a Git repository**.
- Se eligió el proveedor de **GitHub** y se autorizó el acceso a la organización.
- Se seleccionó el repositorio de **retailpulse-landing-page** para crear el sitio.

![Netlify - Importar proyecto desde GitHub](assets/images/03-netlify-import.png)

**Build settings**
| Campo | Valor |
|---|---|
| Base directory | `/` |
| Build command | `npm run build` |
| Publish directory | `dist/RetailPulse/browser` |

**Deployment**
- Se habilitó el despliegue automático desde la rama configurada `main`.
- Al realizar `push` al repositorio, Netlify ejecutó el pipeline de build y generó un deploy.

![Netlify - Lista de deploys](assets/images/04-netlify-deploys.png)

![Netlify - Logs del deploy](assets/images/05-netlify-deploy-logs.png)

**Publicación y verificación del sitio desplegado**

- **URL pública (Netlify): https://retailpulselandingpage.netlify.app/**

![RetailPulse - Sitio publicado en Netlify](assets/images/06-production-site.png)

##### 5.2.1.8. Team Collaboration Insights during Sprint

#### Desarrollo de las Actividades de Implementación

Durante el Sprint 1, el equipo de RetailPulse trabajó de manera colaborativa en la construcción del informe del proyecto y la validación de la propuesta de valor mediante el desarrollo inicial del Landing Page. A diferencia de un desarrollo tradicional centrado únicamente en código, este Sprint involucró actividades de análisis, diseño, modelado y documentación técnica.

Las actividades se llevaron a cabo de la siguiente manera:

- Se utilizó la metodología GitFlow, creando ramas específicas para cada capítulo y funcionalidad del proyecto (feature/chapter-x-*), lo que permitió un trabajo paralelo organizado.
- Cada integrante asumió la responsabilidad de desarrollar secciones específicas del informe, incluyendo Lean UX, entrevistas, User Stories, arquitectura C4, Event Storming, base de datos y artefactos ágiles.
- Se realizaron commits frecuentes, registrando avances de manera continua en cada sección del proyecto.
- Los cambios fueron integrados mediante merges y Pull Requests hacia la rama develop, consolidando el trabajo del equipo.
- Se mantuvo comunicación constante mediante Discord para coordinar avances, resolver dudas y asegurar coherencia en el desarrollo del informe.
- Se aplicaron buenas prácticas de control de versiones, organización del repositorio y estructuración del trabajo por módulos.

Gracias a esta organización, el equipo logró avanzar de manera simultánea en múltiples frentes del proyecto, asegurando que todos los integrantes contribuyeran activamente en la construcción del producto y del informe.

<img src="assets/images/commits.png" width="100%">

---

#### Evidencia de Colaboración en GitHub

Se presenta a continuación la evidencia de colaboración obtenida a partir de los insights del repositorio de GitHub correspondientes al Sprint 1:

**Insights:**

- 5 autores contribuyendo activamente al repositorio.
- 44 commits realizados en el periodo del Sprint (excluyendo merges).
- Uso consistente de ramas feature para el desarrollo paralelo.
- Integración centralizada en la rama develop siguiendo GitFlow.
- Participación activa de todos los miembros del equipo en distintas áreas del proyecto.

Estos resultados evidencian una colaboración efectiva del equipo, con una distribución equilibrada del trabajo y una adecuada gestión del código fuente durante el desarrollo del Sprint 1.

---

#### 5.2.2. Sprint 2

##### 5.2.2.1. Sprint Planning 2

<table>
  <tr>
    <th>Sprint #</th>
    <th>Sprint 2</th>
  </tr>

  <tr>
    <td><strong>Sprint Planning Background</strong></td>
    <td>Segunda planificación del proyecto enfocada en mejorar la experiencia interactiva del sistema RetailPulse y complementar las funcionalidades del quiosco inteligente.</td>
  </tr>

  <tr>
    <td>Date</td>
    <td>2026-05-01</td>
  </tr>

  <tr>
    <td>Time</td>
    <td>22:00 pm (GMT-5)</td>
  </tr>

  <tr>
    <td>Location</td>
    <td>Modalidad remota mediante la plataforma Discord</td>
  </tr>

  <tr>
    <td>Prepared By</td>
    <td>Vallejo Trujillo, Fabio Cesar</td>
  </tr>

  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>
      Faustino Hurtado, Anghelo Edwin / Franco del Carpio, José María / Godoy Santillan, Jesus Andres / Rubio Ortiz, Luis Sebastián / Vallejo Trujillo, Fabio Cesar
    </td>
  </tr>

  <tr>
    <td>Sprint 1 Review Summary</td>
    <td>
      Durante el Sprint 1 se validó la propuesta de valor del sistema RetailPulse mediante el desarrollo del landing page y funcionalidades iniciales de búsqueda de productos.
    </td>
  </tr>

  <tr>
    <td>Sprint 1 Retrospective Summary</td>
    <td>
      El equipo identificó la necesidad de mejorar la integración visual del quiosco inteligente y fortalecer la experiencia interactiva del usuario dentro de tienda.
    </td>
  </tr>

  <tr>
    <td><strong>Sprint Goal & User Stories</strong></td>
    <td></td>
  </tr>

  <tr>
    <td>Sprint 2 Goal</td>
    <td>
      El objetivo del Sprint 2 es implementar demostraciones visuales avanzadas del sistema RetailPulse y mejorar la experiencia de búsqueda mediante promociones relevantes y simulaciones interactivas del quiosco inteligente.
      <br><br>
      Se busca que los usuarios puedan visualizar de forma más clara el funcionamiento del sistema dentro del entorno retail y comprender cómo RetailPulse optimiza la conversión y experiencia en tienda.
    </td>
  </tr>

  <tr>
    <td>Sprint 2 Velocity</td>
    <td>19 puntos</td>
  </tr>

  <tr>
    <td>Sum of Story Points</td>
    <td>19 puntos</td>
  </tr>
</table>


##### 5.2.2.2. Aspect Leaders and Collaborators.
Durante el Sprint 2, el equipo se enfocó en la evolución del diseño del sistema y el desarrollo de las funcionalidades core de la aplicación web de RetailPulse. Esto incluyó la mejora de los prototipos de alta fidelidad, la estructuración de los dashboards analíticos y la implementación de la gestión del layout de la tienda (CRUD de zonas).
Para asegurar una correcta organización del equipo, se elaboró la matriz LACX (Leader and Collaborators), asignando a cada integrante un rol de liderazgo (L) en un aspecto específico y participación como colaborador (C) en los demás.
| Team Member (Last Name, First Name) | GitHub Username | CRUD de Zonas (Layout) | Web Prototyping & Flow | Dashboard Analytics | Roles & Suscripciones |
| :--- | :--- | :---: | :---: | :---: | :---: |
| Faustino Hurtado, Anghelo Edwin | Limos05 | C | L | C | C |
| Vallejo Trujillo, Fabio Cesar | fabiovallejo | L | C | L | C |
| Godoy Santillan, Jesus Andres | JesusGodoyS | C | C | C | L |
| Rubio Ortiz, Luis Sebastián | notoriussxd | C | C | C | C |
| Franco del Carpio, José María | VoltTrd | C | C | C | C |

##### 5.2.2.3. Sprint Backlog 2
![Sprint Backlog 2](assets/images/sprint_backlog_2.png)

**Duración:** 2 semanas

**Objetivo del Sprint:**  
Implementar funcionalidades analíticas y operativas clave de RetailPulse para mejorar la toma de decisiones comerciales, el control operativo y la experiencia inteligente dentro de la tienda.

<table>
<tr>
  <th>Sprint #</th>
  <th colspan="7">Sprint 2</th>
</tr>

<tr>
  <th colspan="2">User Story</th>
  <th colspan="6">Work-Item / Task</th>
</tr>

<tr>
  <th>Id</th>
  <th>Title</th>
  <th>Id</th>
  <th>Title</th>
  <th>Description</th>
  <th>Estimation (Hours)</th>
  <th>Assigned To</th>
  <th>Status</th>
</tr>

<tr>
  <td rowspan="2">US-02</td>
  <td rowspan="2">Identificar zonas de baja conversión</td>
  <td>T-11</td>
  <td>Métricas de interacción por zona</td>
  <td>Implementar visualización de tráfico, permanencia e interacción para detectar zonas con baja conversión.</td>
  <td>8</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-12</td>
  <td>Dashboard de conversión</td>
  <td>Diseñar panel analítico para identificar oportunidades de redistribución comercial dentro de la tienda.</td>
  <td>6</td>
  <td>Godoy Santillan, Jesus Andres</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-06</td>
  <td rowspan="2">Detectar zonas calientes y zonas muertas</td>
  <td>T-13</td>
  <td>Mapa de calor interactivo</td>
  <td>Desarrollar visualización heatmap para identificar zonas de alta y baja actividad dentro del local.</td>
  <td>8</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-14</td>
  <td>Análisis de comportamiento</td>
  <td>Procesar métricas de interacción y comportamiento para optimizar la distribución comercial.</td>
  <td>5</td>
  <td>Franco del Carpio, José María</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-09</td>
  <td rowspan="2">Recibir promociones relevantes durante la búsqueda</td>
  <td>T-15</td>
  <td>Panel de promociones inteligentes</td>
  <td>Diseñar promociones dinámicas relacionadas al producto o categoría consultada por el comprador.</td>
  <td>4</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-16</td>
  <td>Integración de promociones</td>
  <td>Integrar promociones relevantes dentro del flujo de búsqueda del quiosco inteligente.</td>
  <td>4</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-13</td>
  <td rowspan="2">Mantener catálogo y ubicación de productos</td>
  <td>T-17</td>
  <td>Gestión CRUD de productos</td>
  <td>Implementar operaciones de creación, edición y eliminación de productos dentro del catálogo.</td>
  <td>6</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-18</td>
  <td>Asignación de zonas y stock</td>
  <td>Permitir registrar stock, zonas y referencias de estante para productos del sistema.</td>
  <td>5</td>
  <td>Franco del Carpio, José María</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-19</td>
  <td rowspan="2">Detectar productos con alta interacción y baja conversión</td>
  <td>T-19</td>
  <td>Análisis de productos críticos</td>
  <td>Detectar productos con alta interacción pero baja conversión para prevenir pérdidas comerciales.</td>
  <td>5</td>
  <td>Godoy Santillan, Jesus Andres</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-20</td>
  <td>Alertas comerciales</td>
  <td>Generar alertas y recomendaciones sobre productos con bajo rendimiento comercial.</td>
  <td>4</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

</table>

**Total Story Points:** 29

##### 5.2.2.4. Development Evidence for Sprint Review
A continuación, se presenta el registro de commits destacados realizados durante el desarrollo del Sprint 2, evidenciando el trabajo integral del equipo en ambos frentes:
| Repository | Branch | Commit Message | Author |
| :--- | :--- | :--- | :--- |
| RetailPulse/frontend | feature/product-search | feat(catalog): implement product search functionality | fabiovallejo |
| RetailPulse/frontend | feature/admin-registration | feat(auth): add admin registration form and validation | fabiovallejo |
| RetailPulse/frontend | feature/branding | style(ui): integrate institutional logo across main views | fabiovallejo |
| RetailPulse/frontend | feature/product-crud | feat(catalog): implement product registration and editing (US-05 to 08) | JesusGodoyS |
| RetailPulse/frontend | feature/zone-layout | feat(layout): implement zone editing for layout simulation | Limos05 |
| RetailPulse/frontend | feature/dashboard-ui | feat(analytics): implement conversion and heatmap UI components | VoltTrd |
| RetailPulse/report | feature/web-prototyping | docs: add web applications prototyping and figma flows | Limos05 |

##### 5.2.2.5. Execution Evidence for Sprint Review

Durante este segundo Sprint, el equipo avanzó en la implementación de la aplicación web frontend, logrando una interfaz interactiva, visualmente coherente y adaptable a las necesidades de gestión y analítica de tiendas físicas. A continuación, se muestra la evidencia visual de las secciones desplegadas, mostrando la navegación de la plataforma.

**1. Dashboard - Panel Principal (Analytics):**
Vista principal del administrador que consolida las métricas de tráfico, interacción y tasas de conversión en tiempo real, incluyendo la visualización del mapa de calor de la tienda.
<img src="assets/images/mockup1.png" alt="Dashboard Panel Principal" width="800">

**2. Gestión de Zonas y Productos (Store Configuration):**
Interfaz que permite al administrador realizar el CRUD de zonas físicas y asociar productos a ubicaciones específicas (estantes y pasillos), fundamental para la recolección de datos.
<img src="assets/images/mockup2.png" alt="Gestión de Zonas y Productos" width="800">

**3. Insights de Conversión (Performance):**
Panel analítico detallado que cruza las interacciones físicas con las ventas reales, permitiendo identificar productos con alta interacción pero baja conversión.
<img src="assets/images/mockup3.png" alt="Insights de Conversión" width="800">

**4. Panel Operativo y Alertas (Communication):**
Vista diseñada para el personal de tienda, donde se reciben notificaciones automáticas y tareas pendientes, como quiebres de stock o zonas congestionadas.
<img src="assets/images/mockup4.png" alt="Panel Operativo y Alertas" width="800">

**5. Gestión de Suscripciones SaaS (Profile/Billing):**
Sección donde el administrador del negocio puede visualizar el estado de su plan actual, comparar características y gestionar mejoras en la plataforma.
<img src="assets/images/mockup5.png" alt="Gestión de Suscripciones SaaS" width="800">

##### 5.2.2.6. Services Documentation Evidence for Sprint Review.

Durante este sprint se consolidó la primera versión funcional de la aplicación web de RetailPulse, estableciendo su estructura visual, diseño responsivo y las funcionalidades de navegación principales (menú lateral y ruteo). Asimismo, se avanzó de forma significativa en la construcción del frontend del sistema, incluyendo componentes clave como el dashboard de analítica, el módulo de gestión del catálogo de productos, la configuración del layout físico (zonas) y la arquitectura modular en Angular.

Aunque no se desplegaron endpoints REST definitivos en el backend aún, se configuró un entorno simulado utilizando JSON Server (Fake API) para gestionar la persistencia temporal de los datos. A continuación, se documentan los recursos y avances relevantes del sprint en cuanto a la integración de servicios:

**Descripción de los Logros:**
* Implementación de la estructura de frontend modular iniciada (menú sidebar, dashboard interactivo y componentes base).
* Configuración de servicios en Angular (`ProductService`, `ZoneService`, etc.) para simular el consumo asíncrono de datos.
* Despliegue de Fake API (JSON Server) que permite probar las peticiones HTTP (GET, POST, PUT, DELETE) requeridas para los módulos operativos.
* Aplicación de buenas prácticas de organización modular y separación de la lógica de negocio en el frontend.
* Integración visual consolidada basada en Angular y Angular Material, aplicando el branding institucional del sistema.

##### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para asegurar que las funcionalidades desarrolladas durante el Sprint 2 puedan ser validadas y probadas en un entorno real, el equipo llevó a cabo el despliegue tanto de la aplicación web frontend como de la API simulada (Fake API) utilizando plataformas en la nube.

**1. Despliegue del Frontend (Azure Static Web Apps)**
La aplicación web desarrollada en Angular fue desplegada exitosamente utilizando Azure Static Web Apps. Este entorno de producción permite acceder a la interfaz de usuario de RetailPulse mediante una URL pública, garantizando integración continua a partir de la rama `main`.

* **Enlace de Producción (Frontend):** [https://polite-sea-0e075210f.7.azurestaticapps.net/](https://polite-sea-0e075210f.7.azurestaticapps.net/)

<img src="assets/images/retailpulse-deploy-frontend.png" alt="Despliegue del Frontend en Azure Static Web Apps" width="800">

**2. Despliegue de la API Simulada (Railway)**
Para respaldar el funcionamiento del frontend sin depender de datos en memoria local, se configuró y desplegó un servidor JSON (Fake API) en la plataforma Railway. Este servicio provee los endpoints necesarios para las operaciones CRUD del sprint y simula la persistencia de datos en un entorno remoto.

* **Enlace de Producción (Fake API):** [https://retailpulse-fake-api-production.up.railway.app/](https://retailpulse-fake-api-production.up.railway.app/)

<img src="assets/images/deployment-railway.jpg" alt="Despliegue del Fake API en Railway" width="800">

##### 5.2.2.8. Team Collaboration Insights during Sprint.

**Desarrollo de las Actividades de Implementación**

Durante el Sprint 2, la colaboración del equipo se centró en unificar el diseño visual con la implementación técnica en múltiples módulos de RetailPulse. Las actividades se llevaron a cabo de la siguiente manera:
* Se mantuvo la disciplina de GitFlow, operando simultáneamente en ramas específicas para el catálogo y para la configuración de tienda.
* Se realizó un esfuerzo conjunto para que la gestión de productos y autenticación conviviera armónicamente con los nuevos prototipos de analítica y diseño visual.
* La comunicación constante del equipo permitió que la integración del branding institucional (logo) se aplicara de manera uniforme en los componentes desarrollados por los distintos integrantes.

**Evidencia de Colaboración en GitHub**

Se presenta a continuación la evidencia de colaboración obtenida a partir de los insights del repositorio correspondientes al Sprint 2:

<img src="assets/images/github-insights-sprint2.jpg" alt="GitHub Insights Sprint 2" width="800">

**Insights del Sprint 2:**
* **6 autores** contribuyeron al repositorio, reflejando la participación activa de todo el equipo en sus frentes asignados.
* Se realizaron **78 commits** en todas las ramas durante el periodo del Sprint (excluyendo merges), lo que evidencia un alto volumen de trabajo concurrente.
* Se registró **1 commit directo a `main`**, correspondiente a la consolidación y despliegue final de la primera versión funcional del sistema.
* El gráfico de "Top Committers" refleja una colaboración continua y un esfuerzo distribuido entre los desarrolladores.

---

#### 5.2.3. Sprint 3

##### 5.2.3.1. Sprint Planning 3

<table>
  <tr>
    <th>Sprint #</th>
    <th>Sprint 3</th>
  </tr>

  <tr>
    <td><strong>Sprint Planning Background</strong></td>
    <td>
      Tercera planificación del proyecto enfocada en la migración progresiva desde una Fake API basada en JSON Server hacia una primera versión real de Web Services desarrollada con Java y Spring Boot. Asimismo, se consideró la preparación de evidencias técnicas, validaciones con usuarios y material audiovisual requerido para la entrega AV2.
    </td>
  </tr>

  <tr>
    <td>Date</td>
    <td>2026-06-10</td>
  </tr>

  <tr>
    <td>Time</td>
    <td>22:00 pm (GMT-5)</td>
  </tr>

  <tr>
    <td>Location</td>
    <td>Modalidad remota mediante la plataforma Discord</td>
  </tr>

  <tr>
    <td>Prepared By</td>
    <td>Vallejo Trujillo, Fabio Cesar</td>
  </tr>

  <tr>
    <td>Attendees (to planning meeting)</td>
    <td>
      Faustino Hurtado, Anghelo Edwin / Franco del Carpio, José María / Godoy Santillan, Jesus Andres / Rubio Ortiz, Luis Sebastián / Vallejo Trujillo, Fabio Cesar
    </td>
  </tr>

  <tr>
    <td>Sprint 2 Review Summary</td>
    <td>
      Durante el Sprint 2 se consolidó una primera versión funcional de la aplicación web de RetailPulse, incluyendo vistas administrativas, simulación de dashboard analítico, gestión de productos, layout de tienda, promociones y consumo de datos mediante una Fake API basada en JSON Server.
    </td>
  </tr>

  <tr>
    <td>Sprint 2 Retrospective Summary</td>
    <td>
      El equipo identificó la necesidad de reemplazar la simulación de datos por una primera versión real de Web Services, con el fin de fortalecer la arquitectura del proyecto, documentar endpoints y preparar una integración más cercana a un entorno de producción.
    </td>
  </tr>

  <tr>
    <td><strong>Sprint Goal & User Stories</strong></td>
    <td></td>
  </tr>

  <tr>
    <td>Sprint 3 Goal</td>
    <td>
      El objetivo del Sprint 3 es implementar la primera versión real de los Web Services de RetailPulse utilizando Java y Spring Boot, reemplazando progresivamente el uso de JSON Server como fuente de datos simulada.
      <br><br>
      Se busca que la aplicación web pueda consumir servicios backend reales para funcionalidades clave como layout de tienda, métricas de heatmap, productos, inventario, alertas operativas, recomendaciones comerciales y planes de suscripción. Además, el sprint contempla la documentación de servicios, evidencias de despliegue, entrevistas de validación y material audiovisual requerido para la revisión del producto.
    </td>
  </tr>

  <tr>
    <td>Sprint 3 Velocity</td>
    <td>23 puntos</td>
  </tr>

  <tr>
    <td>Sum of Story Points</td>
    <td>23 puntos</td>
  </tr>
</table>


##### 5.2.3.2. Aspect Leaders and Collaborators.

Durante el Sprint 3, el equipo se enfocó en la implementación de la primera versión real de los Web Services de RetailPulse, la integración progresiva con la aplicación web Angular y la preparación de las evidencias requeridas para la entrega AV2. Para asegurar una correcta organización, se ha asignando a cada integrante un rol de liderazgo (L) en un aspecto específico y participación como colaborador (C) en los demás.

| Team Member (Last Name, First Name) | GitHub Username | Backend Base & Deployment | Traffic Analytics | Inventory & Product Services | Store Operations | Promotion & Subscription | Validation & Report Evidence | Product/Team Videos |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| Vallejo Trujillo, Fabio Cesar | fabiovallejo | L | L | C | C | C | C | C |
| Faustino Hurtado, Anghelo Edwin | Limos05 | C | C | C | L | C | C | C |
| Franco del Carpio, José María | VoltTrd | C | C | L | C | C | L | C |
| Godoy Santillan, Jesus Andres | JesusGodoyS | C | C | L | C | C | C | C |
| Rubio Ortiz, Luis Sebastián | notoriussxd | C | C | C | C | L | C | L |


##### 5.2.3.3. Sprint Backlog 3

![Sprint Backlog 3](assets/images/sprint_backlog_3.png)

**Duración:** 2 semanas

**Objetivo del Sprint:**  
Implementar la primera versión real de Web Services de RetailPulse mediante Spring Boot, integrando progresivamente el frontend Angular con endpoints reales y preparando las evidencias de servicios, despliegue, validación y presentación del producto para AV2.

<table>
<tr>
  <th>Sprint #</th>
  <th colspan="7">Sprint 3</th>
</tr>

<tr>
  <th colspan="2">User Story</th>
  <th colspan="6">Work-Item / Task</th>
</tr>

<tr>
  <th>Id</th>
  <th>Title</th>
  <th>Id</th>
  <th>Title</th>
  <th>Description</th>
  <th>Estimation (Hours)</th>
  <th>Assigned To</th>
  <th>Status</th>
</tr>

<tr>
  <td rowspan="2">US-11</td>
  <td rowspan="2">Registrar eventos de movimiento en tienda</td>
  <td>T-21</td>
  <td>Estructura base de Web Services</td>
  <td>Crear la estructura inicial del backend en Spring Boot siguiendo un enfoque DDD por bounded contexts, separando capas de dominio, aplicación, infraestructura e interfaces.</td>
  <td>4</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-22</td>
  <td>Servicios de eventos y métricas de tráfico</td>
  <td>Implementar la base de servicios para registrar y consultar información relacionada con movimiento, zonas y comportamiento dentro de tienda.</td>
  <td>5</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-12</td>
  <td rowspan="2">Calcular métricas de calor y conversión</td>
  <td>T-23</td>
  <td>Endpoints de heatmap metrics</td>
  <td>Implementar endpoints REST para consultar métricas de heatmap utilizadas por el dashboard administrativo.</td>
  <td>5</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-24</td>
  <td>Documentación de servicios de analítica</td>
  <td>Documentar los endpoints de Traffic Analytics mediante Swagger/OpenAPI y registrar evidencias para la sección de Services Documentation Evidence.</td>
  <td>4</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-05</td>
  <td rowspan="2">Atender tareas operativas priorizadas</td>
  <td>T-29</td>
  <td>Servicios de alertas operativas</td>
  <td>Implementar endpoints para consultar, crear o actualizar alertas operativas asociadas a zonas, quiebres de stock o incidencias dentro de tienda.</td>
  <td>5</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-30</td>
  <td>Servicios de tareas operativas</td>
  <td>Implementar endpoints para consultar y actualizar el estado de tareas priorizadas para el personal de tienda.</td>
  <td>5</td>
  <td>Faustino Hurtado, Anghelo Edwin</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-07</td>
  <td rowspan="2">Recibir recomendaciones de optimización comercial</td>
  <td>T-31</td>
  <td>Servicios de recomendaciones comerciales</td>
  <td>Implementar endpoints para listar recomendaciones comerciales basadas en tráfico, interacción, inventario o conversión.</td>
  <td>6</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-32</td>
  <td>Servicios de planes de suscripción</td>
  <td>Implementar endpoints para consultar planes SaaS, plan activo y funcionalidades disponibles según el alcance contratado.</td>
  <td>6</td>
  <td>Rubio Ortiz, Luis Sebastián</td>
  <td>Done</td>
</tr>

<tr>
  <td rowspan="2">US-15</td>
  <td rowspan="2">Configurar tienda y funcionalidades disponibles</td>
  <td>T-33</td>
  <td>Despliegue de backend</td>
  <td>Desplegar la primera versión de Web Services en una plataforma cloud y verificar el acceso público a la API y Swagger/OpenAPI.</td>
  <td>6</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

<tr>
  <td>T-34</td>
  <td>Despliegue y ajuste de frontend</td>
  <td>Publicar o actualizar la aplicación web frontend y validar su consumo progresivo del backend real.</td>
  <td>6</td>
  <td>Vallejo Trujillo, Fabio Cesar</td>
  <td>Done</td>
</tr>

</table>

**Total Story Points: 23** 


##### 5.2.3.4. Development Evidence for Sprint Review

A continuación, se presenta el registro de commits destacados realizados durante el desarrollo del Sprint 3, evidenciando el trabajo del equipo en la construcción de la primera versión real de Web Services y su integración progresiva con la aplicación web.

| Repository | Branch | Commit Message | Author |
| :--- | :--- | :--- | :--- |
| retailpulse-web-services | develop | chore: initialize Spring Boot DDD backend structure | fabiovallejo |
| retailpulse-web-services | develop | feat(traffic-analytics): add domain and persistence model | fabiovallejo |
| retailpulse-web-services | develop | feat(traffic-analytics): add application services and seed data | fabiovallejo |
| retailpulse-web-services | develop | feat(traffic-analytics): expose layout and heatmap REST endpoints | fabiovallejo |
| retailpulse-web-services | feature/promotion-subscription | feat: add promotion and subscription endpoints | notoriussxd |
| retailpulse-web-services | develop | Merge pull request #1 from RetailPulse-NRC11863/feature/promotion-subscription | notoriussxd |
| retailpulse-web-services | develop | feat(inventory): add product domain persistence and services | fabiovallejo |
| retailpulse-web-services | develop | feat(inventory): expose product REST endpoints | fabiovallejo |
| retailpulse-web-services | develop | feat(store-operations): add alerts and tasks domain services | fabiovallejo |
| retailpulse-web-services | develop | feat(store-operations): expose alerts and tasks REST endpoints | fabiovallejo |
| retailpulse-web-services | develop | feat: added docker config for Azure deploy | fabiovallejo |

##### 5.2.3.5. Execution Evidence for Sprint Review

Durante el Sprint 3, el equipo trabajó en la implementación e integración de los servicios backend reales de RetailPulse, orientados a reemplazar progresivamente la Fake API usada en sprints anteriores. En esta sección se deben incluir las evidencias visuales de las funcionalidades ejecutándose desde la aplicación web y consumiendo Web Services reales.

**1. Backend Spring Boot en ejecución local:**

<img src="" alt="Backend Spring Boot en ejecución local" width="800">

**2. Swagger/OpenAPI con endpoints disponibles:**

<img src="" alt="Swagger OpenAPI Sprint 3" width="800">

**3. Vista de layout y heatmap consumiendo backend real:**

<img src="" alt="Layout y heatmap consumiendo backend real" width="800">

**4. Vista de productos o inventario consumiendo backend real:**

<img src="" alt="Productos e inventario consumiendo backend real" width="800">

**5. Vista de alertas, tareas o recomendaciones operativas:**

<img src="" alt="Alertas y recomendaciones operativas" width="800">


##### 5.2.3.6. Services Documentation Evidence for Sprint Review.

Durante este sprint se documentó la primera versión real de los Web Services de RetailPulse, desarrollados con Java y Spring Boot. A diferencia del sprint anterior, donde se utilizó JSON Server como Fake API para simular persistencia y consumo de datos, en el Sprint 3 se realizó la migración progresiva hacia endpoints REST reales organizados según bounded contexts.

La documentación de servicios fue realizada mediante Swagger/OpenAPI, permitiendo visualizar los recursos disponibles, los métodos HTTP soportados, los esquemas de request/response y la relación de cada endpoint con las funcionalidades implementadas en la aplicación web.

**Descripción de los Logros:**

* Implementación de una primera versión real del backend con Java y Spring Boot.
* Organización del backend por bounded contexts y capas: dominio, aplicación, infraestructura e interfaces REST.
* Exposición de endpoints REST bajo la ruta base `/api/v1`.
* Configuración de Swagger/OpenAPI para documentar y probar los servicios disponibles.
* Implementación de endpoints compatibles con recursos previamente simulados en JSON Server.
* Integración progresiva entre la aplicación Angular y los nuevos Web Services.
* Incorporación de endpoints de compatibilidad para facilitar la migración desde la Fake API hacia la API REST real.

**Endpoints documentados durante el Sprint 3:**

| Bounded Context / Módulo | Endpoint | Métodos | Funcionalidad relacionada | Estado |
| :--- | :--- | :--- | :--- | :--- |
| Base Spring Boot | `/api/v1/health` | GET | Verificación del estado general de la API | Implementado y documentado |
| Traffic Analytics | `/api/v1/zones` | GET, POST | Consulta y creación de zonas del layout de tienda | Implementado y documentado |
| Traffic Analytics | `/api/v1/zones/{zoneId}` | GET, PUT | Consulta y actualización de una zona específica | Implementado y documentado |
| Traffic Analytics | `/api/v1/layouts` | GET, POST | Consulta y creación de layouts de tienda | Implementado y documentado |
| Traffic Analytics | `/api/v1/layouts/{layoutId}` | GET, PUT | Consulta y actualización de un layout específico | Implementado y documentado |
| Traffic Analytics | `/api/v1/layouts/current` | GET | Consulta del layout activo de la tienda | Implementado y documentado |
| Traffic Analytics | `/api/v1/heatmap-metrics` | GET, POST | Consulta y creación de métricas de heatmap | Implementado y documentado |
| Traffic Analytics | `/api/v1/heatmap-metrics/{metricId}` | GET, PUT | Consulta y actualización de una métrica de heatmap específica | Implementado y documentado |
| Traffic Analytics | `/api/v1/heatmap-metrics/by-zone/{zoneId}` | GET | Consulta de métricas de heatmap por zona | Implementado y documentado |
| Traffic Analytics | `/api/v1/traffic/movement-events` | POST | Registro de eventos de movimiento dentro de tienda | Implementado y documentado |
| Traffic Analytics | `/api/v1/traffic/zones/metrics` | GET | Consulta de métricas de tráfico por zonas | Implementado y documentado |
| Traffic Analytics | `/api/v1/traffic/heatmap` | GET | Consulta de métricas para visualización de heatmap | Implementado y documentado |
| Traffic Analytics | `/api/v1/traffic/congestion` | GET | Consulta de métricas de congestión operativa | Implementado y documentado |
| Traffic Analytics Compatibility | `/api/v1/storeLayoutZones` | GET | Endpoint de compatibilidad con la colección legacy de JSON Server para zonas del layout | Implementado y documentado |
| Traffic Analytics Compatibility | `/api/v1/heatmapMetrics` | GET | Endpoint de compatibilidad con la colección legacy de JSON Server para métricas de heatmap | Implementado y documentado |
| Store Foundation | `/api/v1/stores` | GET, POST | Consulta y creación de tiendas | Implementado y documentado |
| Store Foundation | `/api/v1/stores/{storeId}` | GET | Consulta de una tienda específica | Implementado y documentado |
| Store Foundation | `/api/v1/store-foundation/zones` | GET, POST | Consulta y creación de zonas base de tienda | Implementado y documentado |
| Store Foundation | `/api/v1/store-foundation/zones/{zoneId}` | GET, PUT, DELETE | Consulta, actualización y eliminación de zonas base de tienda | Implementado y documentado |
| Store Foundation | `/api/v1/store-foundation/products` | GET, POST | Consulta y creación de productos desde Store Foundation | Implementado y documentado |
| Store Foundation | `/api/v1/store-foundation/products/{productId}` | GET, PUT, DELETE | Consulta, actualización y eliminación de productos desde Store Foundation | Implementado y documentado |
| Store Foundation | `/api/v1/store-foundation/products/search` | GET | Búsqueda de productos desde Store Foundation | Implementado y documentado |
| Inventory Intelligence | `/api/v1/products` | GET, POST | Consulta y creación de productos para kiosko y administración | Implementado y documentado |
| Inventory Intelligence | `/api/v1/products/search` | GET | Búsqueda de productos por nombre, categoría o zona | Implementado y documentado |
| Inventory Intelligence | `/api/v1/products/{id}` | GET, PUT, DELETE | Consulta, actualización y eliminación de productos | Implementado y documentado |
| Inventory Intelligence | `/api/v1/inventory/items` | GET, POST | Consulta y creación de ítems de inventario | Implementado y documentado |
| Inventory Intelligence | `/api/v1/inventory/items/{productId}/stock` | PATCH | Actualización del stock de un producto | Implementado y documentado |
| Inventory Intelligence | `/api/v1/inventory/items/product/{productId}` | GET | Consulta de inventario por producto | Implementado y documentado |
| Inventory Intelligence | `/api/v1/inventory/items/critical` | GET | Consulta de productos con inventario crítico | Implementado y documentado |
| Assisted Shopping / Kiosk | `/api/v1/kiosk/products/search` | GET | Búsqueda de productos desde el kiosko | Implementado y documentado |
| Assisted Shopping / Kiosk | `/api/v1/kiosk/products/{productId}` | GET | Consulta de producto específico desde el kiosko | Implementado y documentado |
| Assisted Shopping / Kiosk | `/api/v1/kiosk/sessions` | POST | Inicio de sesión de búsqueda en kiosko | Implementado y documentado |
| Assisted Shopping / Kiosk | `/api/v1/kiosk/sessions/{sessionId}` | GET | Consulta de una sesión de kiosko | Implementado y documentado |
| Assisted Shopping / Kiosk | `/api/v1/kiosk/sessions/{sessionId}/searches` | POST | Registro de búsquedas realizadas en el kiosko | Implementado y documentado |
| Store Operations | `/api/v1/operational-alerts` | GET, POST | Consulta y creación de alertas operativas | Implementado y documentado |
| Store Operations | `/api/v1/operational-alerts/{id}` | GET, PUT | Consulta y actualización de una alerta operativa | Implementado y documentado |
| Store Operations | `/api/v1/operational-alerts/{id}/status` | PATCH | Cambio de estado de una alerta operativa | Implementado y documentado |
| Store Operations | `/api/v1/operational-alerts/active` | GET | Consulta de alertas operativas activas | Implementado y documentado |
| Store Operations | `/api/v1/operational-tasks` | GET, POST | Consulta y creación de tareas operativas | Implementado y documentado |
| Store Operations | `/api/v1/operational-tasks/{id}` | GET, PUT | Consulta y actualización de una tarea operativa | Implementado y documentado |
| Store Operations | `/api/v1/operational-tasks/{id}/status` | PATCH | Cambio de estado de una tarea operativa | Implementado y documentado |
| Store Operations | `/api/v1/operational-tasks/pending` | GET | Consulta de tareas operativas pendientes | Implementado y documentado |
| Store Operations Compatibility | `/api/v1/alerts` | GET | Endpoint de compatibilidad con la colección legacy de JSON Server para alertas | Implementado y documentado |
| Store Operations Compatibility | `/api/v1/alerts/{id}` | GET | Consulta de alerta usando ruta legacy de JSON Server | Implementado y documentado |
| Store Operations Compatibility | `/api/v1/operationalTasks` | GET | Endpoint de compatibilidad con la colección legacy de JSON Server para tareas operativas | Implementado y documentado |
| Store Operations Compatibility | `/api/v1/operationalTasks/{id}` | GET | Consulta de tarea usando ruta legacy de JSON Server | Implementado y documentado |
| Promotion Optimization | `/api/v1/recommendations` | GET, POST | Consulta y creación de recomendaciones comerciales | Implementado y documentado |
| Promotion Optimization | `/api/v1/recommendations/active` | GET | Consulta de recomendaciones comerciales activas | Implementado y documentado |
| Promotion Optimization | `/api/v1/recommendations/{recommendationId}/apply` | PATCH | Aplicación de una recomendación comercial | Implementado y documentado |
| Promotion Optimization | `/api/v1/recommendations/product-opportunities` | GET | Consulta de oportunidades comerciales por productos críticos | Implementado y documentado |
| Promotion Optimization | `/api/v1/promotion-recommendations` | GET, POST | Consulta y creación de recomendaciones comerciales usando ruta del bounded context | Implementado y documentado |
| Promotion Optimization | `/api/v1/promotion-recommendations/active` | GET | Consulta de recomendaciones activas usando ruta del bounded context | Implementado y documentado |
| Promotion Optimization | `/api/v1/promotion-recommendations/{recommendationId}/apply` | PATCH | Aplicación de recomendación usando ruta del bounded context | Implementado y documentado |
| Promotion Optimization | `/api/v1/promotion-recommendations/product-opportunities` | GET | Consulta de oportunidades comerciales usando ruta del bounded context | Implementado y documentado |
| Promotion Optimization | `/api/v1/product-performance` | GET | Consulta de productos con baja conversión o bajo desempeño comercial | Implementado y documentado |
| Subscription | `/api/v1/subscription-plans` | GET, POST | Consulta y creación de planes SaaS | Implementado y documentado |
| Subscription | `/api/v1/subscription-plans/{planId}` | GET | Consulta de un plan SaaS específico | Implementado y documentado |
| Subscription | `/api/v1/subscription/plans` | GET, POST | Consulta y creación de planes SaaS usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/subscription/plans/{planId}` | GET | Consulta de plan SaaS usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/accounts/current-plan` | GET, PUT, PATCH | Consulta y cambio del plan actual simulado | Implementado y documentado |
| Subscription | `/api/v1/accounts` | POST | Creación de cuenta SaaS | Implementado y documentado |
| Subscription | `/api/v1/accounts/current` | GET | Consulta de la cuenta SaaS actual | Implementado y documentado |
| Subscription | `/api/v1/accounts/{accountId}` | GET | Consulta de una cuenta SaaS por ID | Implementado y documentado |
| Subscription | `/api/v1/accounts/{accountId}/change-plan` | PATCH | Cambio de plan de una cuenta SaaS | Implementado y documentado |
| Subscription | `/api/v1/subscription/accounts/current-plan` | GET, PUT, PATCH | Consulta y cambio del plan actual simulado usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/subscription/accounts` | POST | Creación de cuenta SaaS usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/subscription/accounts/current` | GET | Consulta de cuenta SaaS actual usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/subscription/accounts/{accountId}` | GET | Consulta de cuenta SaaS por ID usando ruta del bounded context | Implementado y documentado |
| Subscription | `/api/v1/subscription/accounts/{accountId}/change-plan` | PATCH | Cambio de plan usando ruta del bounded context | Implementado y documentado |

**Evidencia de Swagger/OpenAPI:**

<img src="assets/images/retailpulse-swagger.png" alt="Swagger OpenAPI Services Documentation Sprint 3" width="800">

##### 5.2.3.7. Software Deployment Evidence for Sprint Review.

**1. Despliegue del Frontend**

* **Plataforma: Azure Static Web Apps** 
* **Enlace de Producción (Frontend): https://polite-sea-0e075210f.7.azurestaticapps.net** 

<img src="assets/images/retailpulse-frontend-deploy.png" alt="Despliegue del Frontend Sprint 3" width="800">

**2. Despliegue del Backend / Web Services**

* **Plataforma: Azure Web Apps** 
* **Enlace de Producción (Backend): https://retailpulse-api-fabio-dgb7etencqega8g8.centralus-01.azurewebsites.net/swagger-ui/swagger-ui/index.html**

<img src="assets/images/retailpulse-backend-deploy.png" alt="Despliegue del Backend Sprint 3" width="800">

**3. Verificación de consumo de Web Services desde el frontend**

<img src="assets/images/retailpulse-frontend-backend-connection.png" alt="Frontend consumiendo Web Services Sprint 3" width="800">

##### 5.2.3.8. Team Collaboration Insights during Sprint.

**Desarrollo de las Actividades de Implementación**

Durante el Sprint 3, la colaboración del equipo se orientó a la construcción de la primera versión real de Web Services, la integración progresiva del frontend con backend y la preparación de evidencias necesarias para AV2. Las actividades colaborativas deben evidenciar el uso de ramas, commits, pull requests y coordinación entre los integrantes.

**Evidencia de Colaboración en GitHub**

Se presenta a continuación la evidencia de colaboración obtenida a partir de los insights del repositorio correspondientes al Sprint 3:

<img src="assets/images/team-collaboration-insights-sprint-3.png" alt="GitHub Insights Sprint 3" width="800">

#### 5.3. Validation Interviews.

En esta sección, el equipo registra y explica las actividades de entrevistas de validación realizadas durante el proyecto. Las entrevistas de validación tienen como finalidad obtener retroalimentación de usuarios pertenecientes a los segmentos objetivo, quienes interactúan con el landing page y con la aplicación web de RetailPulse.

El proceso de validación considera dos segmentos principales:
* Administradores, supervisores o personal de tienda.
* Clientes o compradores que podrían utilizar la experiencia de búsqueda y asistencia dentro de tienda.


##### 5.3.1. Diseño de Entrevistas.

Las entrevistas de validación fueron diseñadas para evaluar la claridad de la propuesta de valor, la facilidad de uso de la aplicación, la utilidad de las funcionalidades implementadas y la percepción de valor de RetailPulse frente a problemas reales del entorno retail.

**A. Entrevista para Administradores, Supervisores y Personal de Tienda**

1. ¿Qué tan clara te pareció la propuesta de valor de RetailPulse?
2. ¿Qué tan fácil fue navegar por el dashboard o las vistas administrativas?
3. ¿La información mostrada sobre zonas, productos, inventario o métricas te pareció clara y útil?
4. ¿El mapa de calor o visualización de zonas te ayuda a identificar oportunidades de mejora dentro de la tienda?
5. ¿Consideras útil recibir alertas o tareas operativas priorizadas para el personal de tienda?
6. ¿La información sobre productos, stock y ubicación sería suficiente para apoyar la operación diaria?
7. ¿Qué tan útil te parece contar con recomendaciones comerciales basadas en tráfico, interacción o conversión?
8. ¿Qué funcionalidades consideras más importantes para un negocio retail?
9. ¿Qué dificultades o aspectos confusos encontraste durante el uso de la aplicación?
10. ¿Recomendarías RetailPulse a un negocio retail? ¿Por qué?

**B. Entrevista para Clientes / Compradores**

1. ¿Qué tan fácil fue comprender para qué sirve RetailPulse?
2. ¿Qué tan fácil fue usar la experiencia de búsqueda de productos?
3. ¿Pudiste identificar información relevante como stock, ubicación o referencia del producto?
4. ¿Las promociones o recomendaciones mostradas te parecieron útiles?
5. ¿La interfaz te pareció clara, intuitiva y agradable?
6. ¿Consideras que esta solución podría ayudarte a ahorrar tiempo dentro de una tienda?
7. ¿Qué fue lo que más te gustó de la experiencia?
8. ¿Qué aspecto mejorarías de la aplicación o del flujo de búsqueda?
9. ¿Usarías una solución similar en una tienda física real?
10. ¿Recomendarías RetailPulse a otras personas? ¿Por qué?


##### 5.3.2. Registro de Entrevistas.

A continuación, se debe registrar la información correspondiente a las entrevistas de validación realizadas durante el Sprint 3.

##### Segmento 1: Dueños o administradores de negocios retail fisicos

###### Entrevista 1

* Nombre: Andy Pillaca
* Edad: 27
* Distrito: San Borja
* Timing: 

![Entrevista](assets/images/entrevista-validacion-andy-pillaca.png)

**Resumen:** El entrevistado señaló que la propuesta de valor de RetailPulse fue clara, ya que permite centralizar información relevante para mejorar la operación de una tienda retail. Consideró que la navegación por el dashboard fue sencilla y que la información sobre productos, inventario, zonas y métricas resulta útil para tomar decisiones más rápidas. También destacó el valor del mapa de calor para identificar zonas con mayor o menor actividad, así como la utilidad de las alertas y tareas priorizadas para apoyar al personal de tienda. En general, indicó que recomendaría RetailPulse a negocios retail porque ayuda a ordenar la operación, detectar problemas y optimizar la gestión comercial.

**Enlace:** 

##### Segmento 2: Compradores frecuentes en tiendas fisicas

###### Entrevista 1

* Nombre: Andy Nuñez
* Edad: 26
* Distrito: Lurigancho-Chosica
* Timing: 

![Entrevista](assets/images/entrevista-validacion-arturo-nunez.png)

**Resumen**: El entrevistado comprendió fácilmente la finalidad de RetailPulse y valoró positivamente la experiencia de búsqueda desde el kiosko, destacando que permite encontrar productos de manera rápida y consultar información útil como stock, ubicación, referencia de estante y promociones disponibles. Además, consideró que la interfaz es clara e intuitiva, y que la solución puede ayudar a ahorrar tiempo dentro de una tienda física al evitar recorridos innecesarios. Como principal mejora, sugirió incorporar sugerencias automáticas en el buscador y filtros por categoría para hacer la búsqueda aún más eficiente. En general, manifestó que sí usaría y recomendaría RetailPulse, ya que facilita el proceso de compra y mejora la experiencia del cliente.

**Enlace:**


**Resumen de hallazgos - Administradores, Supervisores y Personal de Tienda**

* 
* 
* 

**Resumen de hallazgos - Clientes / Compradores**

* 
* 
* 

### 5.3.3. Evaluaciones según heurísticas

En esta sección se debe registrar la evaluación heurística aplicada al landing page y a la aplicación web de RetailPulse, considerando los criterios definidos para el proyecto.

**Carrera:** Ingeniería de Software  
**Curso:** Desarrollo de Aplicaciones Open Source  
**Sección:** NRC 11863  
**Profesores:** Iván Robles Fernández  
**Auditor:** Jesus Andres Godoy Santillan  
**Cliente(s):** Administradores de tiendas físicas, Compradores en tiendas físicas y Personal de tienda  

**Site o App a evaluar:** RetailPulse  

**ESCALA DE SEVERIDAD:**

Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

<table>
    <tr>
        <td><b>Nivel</b></td>
        <td><b>Descripción</b></td>
    </tr>
    <tr>
        <td>1</td>
        <td><b>Problema superficial:</b> puede ser fácilmente superado por el usuario u ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.</td>
    </tr>
    <tr>
        <td>2</td>
        <td><b>Problema menor:</b> puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release.</td>
    </tr>
    <tr>
        <td>3</td>
        <td><b>Problema mayor:</b> ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.</td>
    </tr>
    <tr>
        <td>4</td>
        <td><b>Problema muy grave:</b> un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.</td>
    </tr>
</table>

**Tareas evaluadas:**

1. Búsqueda de productos e interacción en el Quiosco Web.
2. Visualización de métricas y mapas de calor en el Dashboard.
3. Gestión de alertas operativas por el personal de tienda.
4. Configuración del layout (zonas) y catálogo de productos.
5. Proceso de registro y selección de planes SaaS.

---

**TABLA RESUMEN**

| # | Heurística evaluada | Hallazgo | Severidad | Recomendación |
| :--- | :--- | :--- | :---: | :--- |
| **1** | **Visibilidad del estatus del sistema** | Flujo de regreso desde el Quiosco al Login es poco visible, lo que genera confusión sobre el estado actual de la pantalla para el administrador que configuró la tablet. | 2 | Mejorar el contraste del botón de salida e implementar un requerimiento de clic prolongado o doble tap para evitar salidas accidentales. |
| **2** | **Alineación entre el sistema y el mundo real** | Falta de explicaciones en términos técnicos de los planes SaaS (ej. "Analítica Predictiva"), lo que puede confundir a dueños de minimarkets tradicionales. | 1 | Añadir iconos de tooltips junto a características complejas que expliquen el beneficio de forma sencilla y en lenguaje de negocio. |
| **3** | **Control y libertad para el usuario** | Cambio de idioma (EN/ES) en el Quiosco reinicia la pantalla actual y borra la barra de búsqueda, obligando al cliente a tipear de nuevo si se equivoca. | 3 | Mantener el estado del componente de búsqueda y los resultados actuales al momento de ejecutar el cambio de idioma en el servicio. |
| **4** | **Consistencia y estándares** | Alertas de prioridad alta y media en la vista Staff dependen solo del color (rojo/amarillo), ignorando los estándares modernos de accesibilidad visual. | 2 | Acompañar el color con iconos distintivos y fijos (ej. un triángulo de advertencia para rojo, un círculo de información para amarillo). |
| **5** | **Reconocimiento antes que reacción** | Búsqueda en el Quiosco no guarda el historial reciente. Los compradores deben volver a tipear la palabra completa desde cero si salen de la vista. | 1 | Desplegar un pequeño menú inferior con las últimas 3 búsquedas realizadas localmente al hacer clic en el input de búsqueda. |
| **6** | **Prevención de errores** | Botón "Marcar como atendido" en la vista de Staff no pide confirmación, facilitando descartes accidentales de tareas críticas por clics erróneos. | 2 | Implementar un modal rápido de confirmación o un mensaje tipo "Toast" en la parte inferior con la opción visual de "Deshacer" (Undo). |
| **7** | **Flexibilidad y eficiencia de uso** | Falta de breadcrumbs (migas de pan) en la configuración de la tienda. El Administrador debe usar forzosamente el menú lateral para regresar, perdiendo agilidad. | 2 | Añadir breadcrumbs jerárquicos (Ej: Dashboard > Settings > Store Profile) en la cabecera superior de todas las vistas administrativas. |
| **8** | **Estética y diseño minimalista** | El botón del Modo Quiosco genera clics accidentales en el Login por su proximidad con los enlaces de registro, saturando la zona visual principal. | 2 | Separar visualmente el acceso al Quiosco ubicándolo en una franja inferior aislada o con un diseño (outline) marcadamente distinto. |
| **9** | **Ayudar a los usuarios con los errores** | Errores en el checkout de suscripción (pasarela Stripe) muestran un mensaje de error genérico en lugar de señalar exactamente qué campo del formulario falló. | 3 | Usar validación reactiva en tiempo real por campo, resaltando en texto rojo el input específico que contiene el error antes de permitir el pago. |
| **10** | **Ayuda y documentación** | Validación del formato del RUC ocurre solo al enviar el formulario. Falta ayuda contextual dinámica durante la escritura de los datos iniciales de la tienda. | 2 | Implementar validaciones en Angular que avisen al usuario de la longitud o formato incorrecto de forma dinámica mientras escribe. |

---

**DESCRIPCIÓN DE PROBLEMAS**

**PROBLEMA #1: Flujo de regreso desde el Quiosco al Login es poco visible** **Severidad:** 2  
**Heurística violada:** Visibilidad del estatus del sistema  
**Problema:** Existe un botón para "Volver al login" desde la interfaz del Quiosco, pero su ubicación y bajo contraste sobre la barra superior oscura hacen que pase desapercibido para el personal que configuró la tablet.  
**Evidencia:** Entrevistados de mayor edad mencionaron que las herramientas tecnológicas pueden ser confusas si los botones de navegación principales no resaltan.  
**Recomendación:** Mejorar el contraste del botón de salida e implementar un requerimiento de clic prolongado o doble tap (ej. un candado) para evitar que los compradores salgan de la vista pública por accidente.

**PROBLEMA #2: Falta de explicaciones en términos técnicos de los planes SaaS** **Severidad:** 1  
**Heurística violada:** Alineación entre el sistema y el mundo real  
**Problema:** En la vista de registro (Paso 2), el plan Premium menciona beneficios como "Mapas de Calor (Heatmaps)" o "Analítica Predictiva", términos que podrían no ser del todo claros para un administrador de tienda tradicional.  
**Evidencia:** En las entrevistas, algunos dueños de minimarkets mostraron desconocimiento sobre términos analíticos avanzados si no se les explica en lenguaje de negocio.  
**Recomendación:** Añadir iconos de tooltips (signo de interrogación) junto a las características complejas que expliquen el beneficio de forma sencilla (ej. "Visualiza qué pasillos tienen más visitantes").

**PROBLEMA #3: Cambio de idioma en el Quiosco reinicia la búsqueda actual** **Severidad:** 3  
**Heurística violada:** Control y libertad para el usuario  
**Problema:** Cuando un comprador está buscando un producto en el Quiosco y presiona el botón de idioma (EN/ES), la pantalla se refresca y borra el texto de la barra de búsqueda, obligando al cliente a empezar de nuevo.  
**Evidencia:** Durante las pruebas, los usuarios que cambiaron el idioma a la mitad de una consulta perdieron su progreso, generando frustración al tener que volver a tipear.  
**Recomendación:** Mantener el estado del componente de búsqueda (estado de Angular) y los resultados actuales al momento de ejecutar el cambio de idioma en el servicio de traducción.

**PROBLEMA #4: Alertas de prioridad alta y media dependen solo del color** **Severidad:** 2  
**Heurística violada:** Consistencia y estándares  
**Problema:** En la vista de Staff, las alertas de "OUT OF STOCK" y "LOW STOCK" se diferencian visualmente por marcos rojos y amarillos. Usuarios con daltonismo pueden tener problemas para priorizarlas rápidamente.  
**Evidencia:** Depender exclusivamente de las variaciones de color no cumple con los estándares de accesibilidad visual modernos.  
**Recomendación:** Acompañar el color con iconos distintivos y fijos (ej. un triángulo de advertencia para rojo, un círculo de información para amarillo).

**PROBLEMA #5: Búsqueda en el Quiosco no guarda el historial reciente** **Severidad:** 1  
**Heurística violada:** Reconocimiento antes que reacción  
**Problema:** Los compradores a menudo buscan el mismo producto si se distraen o si otra persona usa el quiosco rápidamente, pero deben volver a tipear la palabra completa desde cero porque el input siempre inicia vacío.  
**Evidencia:** Entrevistados como Giancarlo indicaron que perder tiempo buscando el mismo producto genera fricción en la experiencia de la tienda física.  
**Recomendación:** Desplegar un pequeño menú inferior con las últimas 3 búsquedas realizadas localmente al hacer clic en el input de búsqueda.

**PROBLEMA #6: Botón "Marcar como atendido" en Staff no pide confirmación** **Severidad:** 2  
**Heurística violada:** Prevención de errores  
**Problema:** En el panel operativo del personal, hacer clic en "Mark as Attended" en una tarea pendiente mueve la alerta inmediatamente al historial sin un cuadro de confirmación, lo que puede causar que se descarten tareas críticas por accidente.  
**Evidencia:** El personal de tienda opera en entornos rápidos (a menudo en pantallas táctiles), donde los toques accidentales son muy comunes al caminar por los pasillos.  
**Recomendación:** Implementar un modal rápido de confirmación o un mensaje tipo "Toast" en la parte inferior con la opción de "Deshacer" (Undo) visible por 5 segundos.

**PROBLEMA #7: Falta de breadcrumbs (migas de pan) en la configuración de la tienda** **Severidad:** 2  
**Heurística violada:** Flexibilidad y eficiencia de uso  
**Problema:** Cuando el Administrador navega hacia vistas profundas (ej. editando los detalles de una Zona o el Horario), no hay una ruta jerárquica en la parte superior que le indique en qué sección exacta se encuentra.  
**Evidencia:** Para regresar a la vista general, el usuario debe utilizar forzosamente el menú lateral principal en lugar de subir un nivel de forma intuitiva.  
**Recomendación:** Añadir breadcrumbs jerárquicos (Ej: Dashboard > Settings > Store Profile) en la cabecera superior de las vistas administrativas.

**PROBLEMA #8: El botón del Modo Quiosco genera clics accidentales en el Login** **Severidad:** 2  
**Heurística violada:** Estética y diseño minimalista  
**Problema:** El botón de "Abrir modo quiosco" está ubicado muy cerca del enlace de "Regístrate" y del botón principal de Login, lo que puede derivar en que el administrador o el staff entre a la vista pública por error.  
**Evidencia:** La proximidad de las zonas interactivas en el diseño actual aumenta el riesgo de "misclicks", especialmente en dispositivos con pantallas pequeñas.  
**Recomendación:** Separar visualmente el acceso al Quiosco ubicándolo en una franja inferior aislada o con un diseño visual (outline) marcadamente distinto.

**PROBLEMA #9: Errores en el checkout de suscripción no son específicos** **Severidad:** 3  
**Heurística violada:** Ayudar a los usuarios con los errores  
**Problema:** Si el administrador ingresa mal la fecha de expiración o el CVC en la pasarela simulada de Stripe, el sistema muestra un mensaje de error genérico en lugar de señalar exactamente qué campo del formulario falló.  
**Evidencia:** El usuario debe adivinar cuál de los datos ingresados en la tarjeta es el incorrecto, lo cual retrasa el onboarding a la plataforma.  
**Recomendación:** Usar validación reactiva en tiempo real por campo, resaltando en texto rojo el input específico que contiene el error antes de permitir hacer clic en "Pagar".

**PROBLEMA #10: Validación del formato del RUC ocurre solo al enviar el formulario** **Severidad:** 2  
**Heurística violada:** Ayuda y documentación  
**Problema:** En el paso de "Configuración de la tienda", si el usuario ingresa un RUC con menos de 11 dígitos, el sistema espera a que presione "Finalizar" para mostrar el error, interrumpiendo el flujo.  
**Evidencia:** Los usuarios pueden creer que ya terminaron su registro hasta que se topan con el error de validación final.  
**Recomendación:** Implementar validación en Angular (`Validators.pattern`) que avise al usuario de la longitud incorrecta de forma dinámica mientras escribe en el campo.

#### 5.4. Video About-the-Product.

En esta sección se presenta la primera versión del video About-the-Product, orientado a explicar la propuesta de valor de RetailPulse, sus principales funcionalidades, los segmentos objetivo y la forma en que la plataforma transforma eventos de tienda en acciones operativas y comerciales.

**Resumen del video:**
**Guion – About the Product**

### Introducción

* Plataforma de analítica para retail.
* Transforma datos de ventas en información útil.
* Apoya la toma de decisiones empresariales.
* Dashboards, análisis y recomendaciones.

### Modelo de negocio

* Empresas cargan datos de ventas.
* Procesamiento y análisis de información.
* Generación de reportes y visualizaciones.
* Soporte para decisiones comerciales.

### Características principales

* Dashboard interactivo.
* Reportes automáticos.
* Análisis predictivo.
* Análisis prescriptivo.
* Procesamiento con Databricks.

### Beneficios

* Identificación de patrones de compra.
* Decisiones basadas en datos.
* Ahorro de tiempo en análisis.
* Mejora de ventas y operaciones.

**URL de la versión publicada en Microsoft Stream:**

[Video About-the-Product - Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202310349_upc_edu_pe/IQBrOnJJU_MkTL4CGkC0d8lIAc8mXpNImVidVC8DSX7uJj8?e=Rl3OJ8)

**URL de la versión publicada en YouTube:**

[Video About-the-Product - YouTube](https://youtu.be/IugIQcvcHa4)

**Cuadro representativo del video:**

<img src="" alt="Video About-the-Product Sprint 3" width="800">

## Conclusiones

### Conclusiones y recomendaciones

El desarrollo del proyecto RetailPulse permitió abordar de manera integral el proceso de construcción de una aplicación open source, desde la identificación de una problemática real en el sector retail hasta la propuesta de una solución tecnológica estructurada y viable. El proyecto partió de la necesidad de mejorar la experiencia de compra en tiendas físicas, así como optimizar la operación interna mediante el uso de datos y herramientas digitales.

A lo largo del trabajo, se definió una propuesta clara de valor respaldada por el diseño de un landing page orientado a comunicar los beneficios del sistema, captar usuarios potenciales y validar la solución en el mercado. Este enfoque permitió comprender la importancia de no solo desarrollar funcionalidades, sino también de presentar adecuadamente el producto.

En el ámbito del diseño del sistema, la aplicación de Domain-Driven Design (DDD) permitió estructurar la solución en base al dominio del problema, destacando la definición del Ubiquitous Language como un elemento clave para mantener consistencia entre el análisis, diseño y desarrollo. Asimismo, la organización en distintos contextos facilitó una visión modular y escalable del sistema.

Por otro lado, la incorporación de principios de experiencia de usuario, mediante el desarrollo de sistemas de etiquetado, navegación y búsqueda, permitió diseñar una interacción intuitiva y eficiente para los diferentes tipos de usuario del sistema. Esto evidencia la importancia de la arquitectura de información en la construcción de aplicaciones modernas.

En cuanto a la gestión del desarrollo, la elaboración del Product Backlog y la planificación de los sprints permitió organizar el trabajo de manera incremental, priorizando funcionalidades en función del valor de negocio. Este enfoque facilitó una evolución progresiva del sistema, comenzando con la validación del producto, seguido de la operación en tienda y culminando con la implementación de capacidades analíticas avanzadas.

Finalmente, RetailPulse se consolida como una propuesta innovadora que integra analítica de comportamiento, asistencia al comprador y optimización operativa en un solo sistema, demostrando el potencial de las tecnologías open source para resolver problemáticas reales. En conjunto, el proyecto evidencia una correcta integración entre análisis, diseño, experiencia de usuario y planificación ágil, dando como resultado una solución coherente, bien fundamentada y con potencial de aplicación en un entorno real.

## Bibliografía

* Oracle. (2026). Java Documentation. https://docs.oracle.com/en/java/
* Angular. (2026). Angular Documentation. https://angular.dev/
* Spring. (2026). Spring Boot Reference Documentation. https://spring.io/projects/spring-boot
* OpenAPI Initiative. (2026). OpenAPI Specification. https://swagger.io/specification/
* Amazon Web Services. (2026). AWS Documentation. https://docs.aws.amazon.com/
* Microsoft Azure. (2026). Azure Documentation. https://learn.microsoft.com/azure/
* W3Schools. (2026). Java Tutorial. https://www.w3schools.com/java/
* RetailNext. (2026). Retail Analytics Platform. https://retailnext.net/
*	Dor Technologies. (2026). Retail Traffic Analytics. https://www.getdor.com/
*	Sensormatic Solutions. (2026). ShopperTrak Analytics. https://www.sensormatic.com/
*	Cámara de Comercio de Lima. (2026). Reportes del Gremio Retail y Distribución.


## Anexos
