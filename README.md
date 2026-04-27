<p align="center">
  <strong>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</strong>
</p>

<p align="center">
  <img src="./assets/logos/upc-logo.png" alt="UPC Logo" width="200"/>
</p>

<p align="center">
  Ingeniería de Software <br>
  1ASI0728 Arquitecturas De Software Emergentes <br>
  2026-10 <br>
  Profesor: <strong>Christian Luis De Los Rios Fernandez
</strong> <br><br>
  Report <br>
  CoWare – Producto: CoBox
</p>

<br>

<p align="center"><strong>Team Members:</strong></p>

<table align="center">
  <thead>
    <tr>
      <th>Member</th>
      <th>Código</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Ramiro Alexander Guzmán Chávez</td>
      <td>U202217062</td>
    </tr>
    <tr>
      <td>Diego Ivan Cabrera Buitron</td>
      <td>U20211B293</td>
    </tr>
    <tr>
      <td>Joaquín Pedraza Maldonado</td>
      <td>U202218514</td>
    </tr>
    <tr>
      <td>Jhon Alexander Galvez Chambi</td>
      <td>U202323270</td>
    </tr>
  </tbody>
</table>

<br><br>

<p align="center">
  <strong>Abril, 2026</strong> <br>
  <strong>URL del proyecto:</strong> 
  <a href="https://github.com/11770-Cobox-ArquitecturaEmergentes">
    https://github.com/11770-Cobox-ArquitecturaEmergentes
  </a>
</p>


---

## Registro de Versiones del Informe

| Versión | Fecha       | Autor                          | Descripción                                                                 |
|---------|-------------|--------------------------------|-----------------------------------------------------------------------------|
| TB1     | 09/04/2026  | Ramiro Alexander Guzmán Chávez |  |
| TB1     | 09/04/2026  |   Diego Ivan Cabrera Buitron   |  |
| TB1     | 04/04/2026  |  Jhon Alexander Galvez Chambi  |  |
| TB1     | 04/04/2026  |   Joaquín Pedraza Maldonado    |  |

## Project Report Collaboration Insights

| URL del repositorio del reporte |
| :-----------------------------------: |
| [https://github.com/11770-Cobox-ArquitecturaEmergentes/Documentacion](https://github.com/11770-Cobox-ArquitecturaEmergentes/Documentacion) |

**AV1:**

Para la elaboración de la entrega AV1 de este informe, el equipo se organizó mediante reuniones de coordinación a través de un canal de Discord. En estas reuniones se definió la distribución de actividades, se asignaron responsables por capítulo y se establecieron fechas de revisión periódica para asegurar el avance progresivo de cada integrante.

| Integrante | Usuario Github | Detalle de avance |
|------------|----------------|-------------------|
| Diego Ivan Cabrera Buitron | `omele7` |  |
| Joaquín Pedraza Maldonado | `JoaquinPedraza1` |  |
| Ramiro Alexander Guzmán Chávez | `RamiroGuzmanCh` | |
| Jhon Alexander Galvez Chambi | `Chaomeum` |  |

**Report Repository Insights:** 

En esta sección se presentan los analíticos de colaboración y los commits realizados en GitHub por los miembros del equipo dentro del repositorio del informe durante la fase AV1. Esta evidencia permite visualizar la participación de los integrantes y la evolución del trabajo colaborativo a lo largo del desarrollo del reporte.

- Report Contributors:
![Report Contributors](./assets/tb1/report_contributors.png)

- Report Network:
![Report Network](./assets/tb1/report_network.png)


## Contenido
#### Tabla de contenidos

- [Carátula](#carátula)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
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
      - [4.1.2.2. Quality Attribute Scenarios](#4122-quality-attribute-scenarios)
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


## Student Outcome

### ABET – EAC - Student Outcome 3

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describen las acciones realizadas y enunciados de conclusiones por parte del equipo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico | Acciones realizadas | Conclusiones |
|----------------------|---------------------|--------------|
| Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |
| Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería. | | |

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

CoWare es una startup tecnológica orientada a la transformación digital del sector logístico de transporte de carga, enfocada en mejorar la eficiencia operativa, la trazabilidad de los servicios y la confiabilidad de la información generada durante la ejecución de operaciones.

La iniciativa surge a partir de la identificación de una problemática recurrente en pequeñas y medianas empresas del sector: la dependencia de procesos manuales y herramientas no integradas como hojas de cálculo, registros físicos y aplicaciones de mensajería, lo cual genera fragmentación de la información, errores en el registro de datos y limitaciones para supervisar y auditar las operaciones de manera efectiva.


Misión: Desarrollar soluciones tecnológicas que permitan mejorar la eficiencia y trazabilidad de las operaciones logísticas del transporte de carga mediante la digitalización y automatización progresiva de sus procesos.

Visión: Consolidarse como una startup referente en soluciones digitales para el sector logístico, impulsando la modernización de la gestión del transporte de carga a través del uso de tecnologías innovadoras.

#### 1.1.2. Perfiles de integrantes del equipo

**Diego Cabrera -Ingeniería de Software**

Estudio Ing. Software. Me considero que soy una persona creativa, entusiasta en aprender cosas nuevas. Me gusta ayudar a los demás y aprender de manera constante  <br>
<img src="./assets/fotos/diego.png" alt="Diego Cabrera" height="150"/>

**Joaquin Pedraza Maldonado – Ingeniería de Software – U202218514**  
<img src="./assets/fotos/joaquin.png" alt="Joaquin Pedraza" height="200"/>

Estudio Ing. Software. Me considero que soy una persona perseverante, entusiasta en aprender cosas nuevas. Me gusta ayudar a los demás y sé trabajar en equipo. Cuento con conocimientos en lenguajes de Programación como C++, Python,CSS, JavaScript.


**Ramiro Alexander Guzman Chavez – Ingeniería de Software – U202217062**  
<img src="./assets/fotos/ramiro.png" alt="Ramiro Guzman" height="200"/>

Mi perfil se basa en ser una persona responsable, disciplinada en todo aspecto y comprometida con las actividades que me puedan tocar.
Considero que tengo una experiencia altamente capacitada para este tipo de tareas. Suelo desarrollarme de manera positiva en los trabajos grupales y tengo conocimientos en bases de datos, lo cual puede aportar de manera importante al equipo.
Además, cuento con conocimientos en lenguajes de programación como Java y JavaScript, lo que me permite desarrollar soluciones tanto del lado del backend como del frontend, contribuyendo a proyectos de desarrollo de software de manera integral.


**Jhon Alexander Galvez Chambi - Ingeniería de Software - U202323270**  
<img src="./assets/fotos/jhon.png" alt="Jhon Galvez" height="200"/>

Soy una persona responsable y comprometida con la consecución de los mejores resultados en trabajo en equipo. Poseo experiencia en diversos lenguajes de programación, incluyendo Python, JavaScript y C++, así como en varios de los frameworks asociados a estos lenguajes. Además, tengo conocimientos en tecnologías emergentes como Cloud Computing e Internet de las Cosas (IoT), y estoy dispuesto a aportar mi experiencia en estas áreas para contribuir al éxito de los proyectos en los que participo.


### 1.2. Solution Profile

CoWare desarrolla CoBox como su producto principal, una plataforma digital que permite centralizar la gestión de servicios logísticos, facilitando la planificación, el monitoreo de recorridos, el registro de eventos operativos y la generación de reportes.

A partir de esta base, el proyecto evoluciona hacia **CoBox Smart Vision**, una propuesta que introduce capacidades de automatización inteligente orientadas a reducir la intervención manual en el registro de información y mejorar la confiabilidad de los datos operativos. Esta evolución responde a la necesidad de avanzar desde la digitalización de procesos hacia mecanismos más robustos de validación de información en entornos logísticos.

Esta nueva propuesta considera las condiciones reales del entorno de operación, incluyendo escenarios de conectividad limitada y usuarios con distintos niveles de alfabetización digital, lo que implica priorizar simplicidad de uso, eficiencia en campo y consistencia en el registro de información.

#### 1.2.1 Antecedentes y problemática

En el sector logístico de transporte de carga, especialmente en pequeñas y medianas empresas, persiste una alta dependencia de procesos manuales y herramientas no integradas como hojas de cálculo, registros físicos y aplicaciones de mensajería. Esta situación genera fragmentación de la información, errores en el registro de datos y una limitada capacidad para auditar las operaciones de forma confiable.

Si bien soluciones como CoBox permiten digitalizar parcialmente estos procesos, aún existe una fuerte dependencia del ingreso manual de datos, lo que introduce riesgos significativos como errores humanos, inconsistencias en la información y posibles fraudes en el reporte de kilometraje y consumo de combustible.

En este contexto, el problema central evoluciona desde la falta de digitalización hacia la falta de **validación automática de la información operativa**, lo que limita la confiabilidad de los datos utilizados para la toma de decisiones.

Para estructurar la problemática, se aplica la técnica de las 5W + 2H:

| Elemento | Descripción |
|----------|------------|
| **Who** | Empresas de transporte de carga, gestores logísticos y conductores que registran y supervisan operaciones. |
| **What** | Registro manual de información crítica (kilometraje, combustible, entregas), susceptible a errores y manipulación. |
| **Where** | En oficinas de operación logística, empresas de transporte, y en campo a través de dispositivos móviles utilizados por los choferes. |
| **When** | Durante la ejecución de servicios logísticos y procesos de reporte posterior. |
| **Why** | Debido a la ausencia de herramientas que automaticen la captura y validación de datos operativos. |
| **How** | Mediante el uso de registros manuales, fotografías no validadas y sistemas desconectados. |
| **How Much** | Impacto en costos operativos, pérdida de eficiencia y riesgos de fraude (a validar en etapas de investigación). |

##### Objetivos de la solución

- Reducir la dependencia del ingreso manual de datos
- Incrementar la confiabilidad de la información operativa
- Automatizar la validación de evidencias en campo
- Mejorar la trazabilidad de los servicios logísticos

##### Restricciones del proyecto

- Operación en entornos con conectividad limitada
- Usuarios con bajo nivel de alfabetización digital
- Necesidad de integración con infraestructura cloud existente

En respuesta a esta problemática, se plantea la evolución hacia CoBox Smart Vision, una solución que incorpora inteligencia artificial de visión y procesamiento en el borde para validar automáticamente la información capturada en campo, eliminando la dependencia del ingreso manual y garantizando la integridad de los datos.

#### 1.2.2. Lean UX Process

##### 1.2.2.1 Lean UX Problem Statements

El dominio del problema se sitúa en la gestión operativa del transporte de carga, donde la captura, validación y uso de información en campo representan un factor crítico para la eficiencia y confiabilidad de las operaciones logísticas.

El segmento de clientes está compuesto principalmente por pequeñas y medianas empresas de transporte de carga, incluyendo gestores logísticos y conductores, quienes requieren herramientas que les permitan registrar, validar y supervisar información operativa de manera eficiente y confiable.

Los principales puntos de dolor identificados incluyen la alta dependencia del ingreso manual de datos, la existencia de errores humanos en registros críticos, la posibilidad de manipulación o fraude en reportes operativos y la falta de mecanismos de validación automática que aseguren la integridad de la información.

Existe una brecha significativa entre las soluciones actuales, enfocadas principalmente en la digitalización de procesos, y la necesidad de contar con sistemas que validen automáticamente la información capturada en campo mediante evidencia verificable.

En este contexto, la visión del producto es evolucionar hacia una solución que no solo registre información, sino que sea capaz de interpretarla y validarla automáticamente mediante el uso de tecnologías de inteligencia artificial, reduciendo la intervención humana y mejorando la confiabilidad de los datos.

La estrategia consiste en implementar un enfoque progresivo basado en captura de evidencia visual, procesamiento inteligente de datos y validación cruzada con información contextual, priorizando la usabilidad en campo y la adaptabilidad a entornos de conectividad limitada.

El segmento inicial se enfoca en empresas de transporte de carga con flotas pequeñas y medianas que presentan procesos manuales o semi-digitalizados y que requieren mejorar la trazabilidad y confiabilidad de sus operaciones.

##### 1.2.2.2 Lean UX Assumptions

###### Business Assumptions

1. Creemos que nuestros clientes necesitan una forma automatizada y confiable de gestionar las operaciones logísticas del transporte de carga, que reduzca la dependencia del ingreso manual de datos.
2. Estas necesidades se resuelven mediante una solución que no solo digitalice procesos, sino que valide automáticamente la información operativa a partir de evidencia visual y procesamiento inteligente.
3. Nuestros clientes iniciales serán pequeñas y medianas empresas de transporte de carga que buscan mejorar la confiabilidad de sus datos y reducir errores operativos y riesgos de fraude.
4. El valor más importante de lo que el cliente requiere de nuestro servicio es la trazabilidad verificable y la integridad de la información en cada servicio logístico realizado.
5. El cliente puede tener los siguientes beneficios adicionales: reducción de tiempo administrativo, validación automática de evidencias, disminución de conflictos operativos, y mejora en el control de desempeño de la flota.
6. Vamos a adquirir clientes mediante marketing directo a empresas de transporte, demostraciones del sistema enfocadas en reducción de fraude y eficiencia operativa, y recomendaciones de clientes satisfechos.
7. Haremos dinero a través de suscripciones mensuales basadas en el número de usuarios, vehículos y funcionalidades avanzadas de validación y analítica.
8. Nuestra competencia principal serán sistemas ERP logísticos tradicionales, hojas de cálculo y plataformas de gestión de flotas que no cuentan con validación automática de datos.
9. Los venceremos ya que nuestra plataforma se enfoca en la validación inteligente de información operativa mediante evidencia digital, con una experiencia de usuario simple y adaptada al trabajo en campo.
10. Nuestro mayor riesgo es que las empresas tradicionales se resistan a confiar en sistemas automatizados basados en inteligencia artificial o perciban la solución como compleja.
11. Resolveremos esto mediante interfaces ultra-simples, flujos de uso basados en captura de evidencia (en lugar de ingreso manual), funcionamiento offline y acompañamiento en la adopción.
12. ¿Qué otras suposiciones tenemos que, si resultan falsas, harán que nuestro negocio/proyecto fracase?
    * Que las empresas de transporte están dispuestas a adoptar soluciones que automaticen la validación de datos y reduzcan su control manual.
    * Que los conductores adoptarán un modelo basado en captura de evidencia visual en lugar de ingreso manual de información.
    * Que las empresas valoran la confiabilidad y verificabilidad de los datos por encima de mantener procesos manuales conocidos.

###### User Assumptions

1. ¿Quién será nuestro usuario?
   * El usuario principal de CoBox Smart Vision son gerentes y coordinadores de operaciones logísticas que necesitan información confiable y validada para supervisar su flota.
   * También está dirigido a conductores de carga que requieren una herramienta simple para registrar eventos mediante captura de evidencia sin procesos manuales complejos.

2. ¿Dónde encaja nuestro producto en su vida?
   * Se integra en la rutina diaria tanto en oficinas como en campo, siendo utilizado durante la ejecución de servicios para capturar y validar información operativa en tiempo real o de manera diferida.

3. ¿Qué problemas resuelve nuestro producto?
   * Se busca resolver la dependencia del ingreso manual de datos, la falta de confiabilidad en registros operativos y la ausencia de mecanismos de validación de evidencias.
   * Los procesos manuales generan errores, inconsistencias y conflictos entre conductores y gestores, debido a la falta de información verificable.

4. ¿Cómo y Cuándo es usado nuestro producto?
   * Es utilizado durante todas las etapas del proceso logístico, especialmente en campo mediante dispositivos móviles para captura de evidencia, y en oficinas para monitoreo y análisis.
   * Los gestores acceden principalmente desde aplicaciones web, mientras los conductores utilizan la aplicación móvil durante la ejecución del servicio.

5. ¿Qué características son importantes?
   * Captura de evidencia visual para registro de información operativa
   * Validación automática de datos mediante inteligencia artificial
   * Funcionamiento offline con sincronización posterior
   * Generación de reportes basados en datos validados
   * Interfaz simple con mínima interacción requerida

6. ¿Cómo luce y se comporta nuestro producto?
   * Presenta interfaces diferenciadas: dashboards analíticos para gestores y aplicación móvil con flujo simplificado para conductores.
   * Se comporta de forma eficiente en campo, priorizando rapidez, validación automática, confirmaciones claras y sincronización cuando existe conectividad.

##### 1.2.2.3 Lean UX Hypothesis Statements

Creemos que al reemplazar el ingreso manual de datos por un modelo basado en captura de evidencia visual, los conductores reducirán el tiempo requerido para registrar información operativa.
Sabremos que estamos en lo correcto cuando se observe una disminución en el tiempo promedio de registro por servicio y una reducción en la carga operativa percibida por los usuarios en campo.

Creemos que al incorporar validación automática de datos mediante inteligencia artificial, será posible reducir errores humanos y detectar inconsistencias en los registros operativos.
Sabremos que estamos en lo correcto cuando disminuyan las discrepancias en datos críticos como kilometraje y consumo de combustible, y se identifiquen automáticamente registros anómalos.

Creemos que al utilizar evidencia digital verificable en lugar de registros manuales, se incrementará la confianza de los gestores en la información operativa.
Sabremos que estamos en lo correcto cuando se reduzcan los conflictos entre conductores y coordinadores, y aumente la aceptación de los datos registrados como fuente confiable para auditoría.

Creemos que al diseñar una experiencia de usuario basada en flujos simples y mínima interacción, los conductores adoptarán la aplicación sin resistencia significativa.
Sabremos que estamos en lo correcto cuando se mantenga un alto nivel de uso activo de la aplicación y se reduzca la necesidad de soporte técnico durante la operación.

Creemos que al ofrecer información validada automáticamente y disponible de forma oportuna, los gestores podrán tomar decisiones más rápidas y efectivas.
Sabremos que estamos en lo correcto cuando se reduzcan los tiempos de respuesta ante incidencias operativas y se evidencie una mejora en indicadores de gestión logística.

##### 1.2.2.4. Lean UX Canvas

![Lean UX Canvas](./assets/tb1/lean_ux_canvas.png)

### 1.3. Segmentos Objetivo

CoWare identifica dos segmentos principales dentro del dominio del transporte de carga, los cuales cumplen roles diferenciados en la operación logística y presentan necesidades específicas frente a la evolución hacia soluciones basadas en validación automática de información.

#### Segmento Primario: Gestión de Operaciones Logísticas

Este segmento está conformado por gerentes, coordinadores y responsables de operaciones en pequeñas y medianas empresas de transporte de carga que administran flotas vehiculares y supervisan la ejecución de servicios logísticos.

- **Perfil organizacional**: Empresas con estructuras operativas tradicionales que han iniciado procesos de digitalización, pero aún presentan dependencia de registros manuales y herramientas no integradas.

- **Necesidades clave**: Requieren información confiable, consistente y oportuna para la toma de decisiones, así como mecanismos que les permitan validar la veracidad de los datos reportados desde campo.

- **Problemas relevantes**:
  - Inconsistencias en registros de kilometraje y consumo de combustible
  - Dificultad para auditar operaciones con evidencia verificable
  - Conflictos internos por discrepancias en datos reportados
  - Limitada trazabilidad en tiempo real

- **Motivaciones principales**:
  - Reducir riesgos de fraude y errores operativos
  - Mejorar la eficiencia en la gestión de flota
  - Contar con datos auditables para control y toma de decisiones

- **Relación con la solución**:
  Este segmento se beneficia directamente de la evolución hacia CoBox Smart Vision, al obtener información validada automáticamente mediante inteligencia artificial, lo que incrementa la confiabilidad de los datos y permite una gestión basada en evidencia.

---

#### Segmento Secundario: Conductores de Unidades de Carga

Este segmento está compuesto por los operadores de campo encargados de ejecutar los servicios de transporte y registrar eventos operativos durante el recorrido.

- **Perfil demográfico**: Conductores con experiencia en el sector, con niveles diversos de alfabetización digital, que operan en entornos de alta exigencia y condiciones variables de conectividad.

- **Responsabilidades operativas**:
  - Registrar kilometraje, consumo de combustible y eventos del servicio
  - Proporcionar evidencia de entregas y actividades realizadas
  - Mantener comunicación con el equipo de operaciones

- **Problemas relevantes**:
  - Carga operativa asociada al ingreso manual de datos
  - Riesgo de errores involuntarios en registros
  - Conflictos derivados de falta de evidencia objetiva
  - Dificultades para usar herramientas complejas en campo

- **Necesidades funcionales**:
  - Interacción simple y rápida durante la operación
  - Funcionamiento offline en zonas con baja conectividad
  - Reducción del esfuerzo necesario para registrar información

- **Motivaciones principales**:
  - Facilitar el cumplimiento de sus tareas operativas
  - Evitar conflictos con supervisores por discrepancias de datos
  - Contar con respaldo objetivo de su trabajo

- **Relación con la solución**:
  La evolución hacia CoBox Smart Vision introduce un cambio significativo en este segmento, reemplazando el ingreso manual de datos por un modelo basado en captura de evidencia visual, lo que reduce la carga operativa y mejora la precisión de los registros.

---

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

Se han identificado tres competidores relevantes dentro del dominio de soluciones digitales para gestión de flotas y operaciones logísticas, los cuales representan alternativas actuales en el mercado y permiten establecer un contraste con la propuesta de CoBox Smart Vision.

**Competidor 1: Samsara**  
Web: https://www.samsara.com/mx  

Plataforma líder en la Nube de Operaciones Conectadas que utiliza IA de vanguardia para transformar la seguridad y eficiencia operativa. Más allá de la telemática tradicional, destaca por sus cámaras con visión computacional que previenen accidentes en tiempo real y su ecosistema integral que centraliza datos de seguridad, cumplimiento (ELD) y mantenimiento en una sola interfaz inteligente.

**Competidor 2: Powerfleet**  
Web: https://www.fleetcomplete.com/es/  

Powerfleet es una solución global especializada en la unificación de datos de flotas mixtas. Su ventaja competitiva es la plataforma Unity, que integra datos de hardware propietario, sensores de terceros y sistemas originales de fabricantes (OEMs). Se enfoca en la visibilidad total del ciclo de vida del activo, permitiendo una integración profunda con ERPs corporativos mediante APIs robustas.

**Competidor 3: Driv.in**  
Web: https://driv.in/  

Driv.in es un TMS SaaS especializado en la optimización de la última milla y distribución urbana en Latinoamérica. Su núcleo es un potente algoritmo de ruteo dinámico que reduce costos logísticos y emisiones. Sobresale por su capacidad de gestionar la experiencia del cliente final (notificaciones y ETAs precisas) y herramientas de control de entregas (Proof of Delivery) adaptadas a la realidad operativa de la región.

A pesar de las capacidades de estos competidores, ninguno de ellos se enfoca de manera central en la validación automática de datos mediante inteligencia artificial a partir de evidencia visual, lo que representa una oportunidad de diferenciación para CoBox Smart Vision.

#### 2.1.1. Análisis competitivo

<table style="width:100%; border-collapse: collapse; font-family: sans-serif; font-size: 14px; border: 1px solid #000;">
    <thead>
        <tr style="background-color: #f2f2f2;">
            <th colspan="6" style="border: 1px solid #000; padding: 10px; text-align: left; font-size: 18px;">Competitive Analysis Landscape</th>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px; font-weight: bold; width: 15%;">¿Por qué llevar a cabo este análisis?</td>
            <td colspan="5" style="border: 1px solid #000; padding: 10px; vertical-align: top;">
                Identificar las capacidades, limitaciones y enfoques de soluciones actuales en el mercado de gestión logística, con el fin de determinar oportunidades de diferenciación para CoBox Smart Vision, especialmente en la validación automática de datos operativos mediante inteligencia artificial.
                <br><br>
            </td>
        </tr>
        <tr style="text-align: center; font-weight: bold; background-color: #fafafa;">
            <td colspan="2" style="border: 1px solid #000; padding: 10px; width: 30%;">Nombre y Logo</td>
            <td style="border: 1px solid #000; padding: 10px; width: 17.5%;">
                CoBox SV<br>
                <div style="height: 50px; margin-top: 5px; display: flex; align-items: center; justify-content: center;">
                    <img src="./assets/logos/cobox_sv_logo.webp" alt="Logo de su startup" style="max-height: 50px; max-width: 100%; object-fit: contain;" />
                </div>
            </td>
            <td style="border: 1px solid #000; padding: 10px; width: 17.5%;">
                Samsara<br>
                <div style="height: 50px; margin-top: 5px; display: flex; align-items: center; justify-content: center;">
                    <img src="./assets/logos/samsara_logo.png" alt="Logo de Samsara" style="max-height: 50px; max-width: 100%; object-fit: contain;" />
                </div>
            </td>
            <td style="border: 1px solid #000; padding: 10px; width: 17.5%;">
                Powerfleet<br>
                <div style="height: 50px; margin-top: 5px; display: flex; align-items: center; justify-content: center;">
                    <img src="./assets/logos/powerfleet_logo.png" alt="Logo de Powerfleet" style="max-height: 50px; max-width: 100%; object-fit: contain;" />
                </div>
            </td>
            <td style="border: 1px solid #000; padding: 10px; width: 17.5%;">
                Driv.in<br>
                <div style="height: 50px; margin-top: 5px; display: flex; align-items: center; justify-content: center;">
                    <img src="./assets/logos/drivin_logo.png" alt="Logo de Driv.in" style="max-height: 50px; max-width: 100%; object-fit: contain;" />
                </div>
            </td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2" style="border: 1px solid #000; padding: 10px; font-weight: bold; text-align: center; writing-mode: vertical-lr; transform: rotate(180deg);">Perfil</td>
            <td style="border: 1px solid #000; padding: 10px;">Overview</td>
            <td style="border: 1px solid #000;">Plataforma de auditoría logística basada en IA que valida automáticamente datos operativos mediante evidencia visual.</td>
            <td style="border: 1px solid #000;">Nube de Operaciones Conectadas con enfoque en seguridad proactiva e inteligencia de datos IoT.</td>
            <td style="border: 1px solid #000;">Ecosistema de Datos Unificados para activos mixtos, agnóstico al hardware y centrado en integración empresarial.</td>
            <td style="border: 1px solid #000;">TMS SaaS especializado en orquestación de última milla, ruteo dinámico y experiencia de entrega.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Ventaja competitiva ¿Qué valor ofrece a los clientes?</td>
            <td style="border: 1px solid #000;">Validación automática con IA sin hardware especializado, eliminando el error humano en auditorías.</td>
            <td style="border: 1px solid #000;">Seguridad preventiva basada en IA de visión y una experiencia de usuario (UX) líder en la industria.</td>
            <td style="border: 1px solid #000;">Interoperabilidad total (plataforma Unity) e integración nativa con fabricantes de vehículos (OEMs).</td>
            <td style="border: 1px solid #000;">Optimización logística profunda adaptada a las restricciones específicas de LATAM (barreras geográficas, pagos, etc.).</td>
        </tr>
        <tr>
            <td rowspan="2" style="border: 1px solid #000; padding: 10px; font-weight: bold; text-align: center; writing-mode: vertical-lr; transform: rotate(180deg); background-color: #f9f9f9;">Perfil de Marketing</td>
            <td style="border: 1px solid #000; padding: 10px; background-color: #f9f9f9;">Mercado objetivo</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">PyMES y contratistas logísticos con procesos manuales y alta rotación.</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Grandes corporativos (Enterprise) de transporte, construcción y servicios públicos.</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Flotas industriales mixtas, maquinaria pesada y empresas con infraestructura IT compleja (SAP/Oracle).</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Empresas de Retail, Consumo Masivo (CPG) y logística de distribución urbana en LATAM.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px; background-color: #f9f9f9;">Estrategias de marketing</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Enfoque en la "Verdad Operativa" y reducción inmediata de fraude/costos administrativos.</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Marketing basado en Seguridad y ROI a través de la prevención de accidentes y ahorro de combustible.</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Estrategia de "Data-First": eficiencia a través de la integración de silos de información corporativa.</td>
            <td style="border: 1px solid #000; background-color: #f9f9f9;">Crecimiento regional basado en la digitalización de la experiencia del cliente final y eficiencia de rutas.</td>
        </tr>
        <tr>
            <td rowspan="3" style="border: 1px solid #000; padding: 10px; font-weight: bold; text-align: center; writing-mode: vertical-lr; transform: rotate(180deg);">Perfil de Producto</td>
            <td style="border: 1px solid #000; padding: 10px;">Productos & Servicios</td>
            <td style="border: 1px solid #000;">IA de visión, validación de documentos/fotos, App móvil, Backend Cloud con trazabilidad.</td>
            <td style="border: 1px solid #000;">Dashcams con IA, Sensores de activos, ELD, Monitoreo de temperatura, Software de seguridad.</td>
            <td style="border: 1px solid #000;">Pasarela de datos Unity, Telemática para activos no motorizados, Integración API, Control de carga.</td>
            <td style="border: 1px solid #000;">Algoritmo de ruteo, Módulo de liquidación de fletes, App de conductor, Tracking en tiempo real para el cliente.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Precios & Costos</td>
            <td style="border: 1px solid #000;">Suscripción accesible SaaS Pure-Play (sin inversión inicial en equipos).</td>
            <td style="border: 1px solid #000;">Alto costo: Modelo de contrato multianual (Hardware + Licencia por unidad).</td>
            <td style="border: 1px solid #000;">Medio-Alto: Basado en volumen de activos e integraciones de software requeridas.</td>
            <td style="border: 1px solid #000;">Medio: Modelo SaaS escalable por número de usuarios o vehículos.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Canales de distribución (Web y/o Móvil)</td>
            <td style="border: 1px solid #000;">Web + Mobile (BYOD - Bring Your Own Device).</td>
            <td style="border: 1px solid #000;">Web + Hardware IoT propietario + Mobile.</td>
            <td style="border: 1px solid #000;">Web + Cloud Integration + Mobile.</td>
            <td style="border: 1px solid #000;">Web + Mobile + Integración con WhatsApp/SMS.</td>
        </tr>
        <tr>
            <td rowspan="5" style="border: 1px solid #000; padding: 10px; font-weight: bold; text-align: center; writing-mode: vertical-lr; transform: rotate(180deg); background-color: #fdfdfd;">Análisis SWOT</td>
            <td style="border: 1px solid #000; padding: 10px; font-size: 11px; background-color: #fdfdfd;" colspan="5">
                Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.
            </td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Fortalezas</td>
            <td style="border: 1px solid #000;">Agilidad, validación visual inteligente, no requiere instalación física.</td>
            <td style="border: 1px solid #000;">Precisión extrema de sensores, marca global consolidada, IA de cabina.</td>
            <td style="border: 1px solid #000;">Flexibilidad de datos, compatible con flotas pre-existentes, soporte Enterprise.</td>
            <td style="border: 1px solid #000;">Dominio del mercado regional, UX muy sencilla, integración de pagos locales.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Debilidades</td>
            <td style="border: 1px solid #000;">Dependencia de la calidad de cámara del usuario y conectividad móvil.</td>
            <td style="border: 1px solid #000;">Rigidez de hardware (cerrado), dependencia de red 5G/4G constante.</td>
            <td style="border: 1px solid #000;">Complejidad de configuración inicial para unificar datos dispersos.</td>
            <td style="border: 1px solid #000;">Menor enfoque en la validación profunda de integridad de datos (fraude).</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Oportunidades</td>
            <td style="border: 1px solid #000;">Automatización del "Checkout" logístico en empresas que hoy usan papel o Excel.</td>
            <td style="border: 1px solid #000;">Expansión hacia la automatización total de almacenes con drones/robots.</td>
            <td style="border: 1px solid #000;">Consolidación como el estándar de datos para seguros de flotas (Insurtech).</td>
            <td style="border: 1px solid #000;">Expansión a mercados emergentes fuera de LATAM con desafíos similares.</td>
        </tr>
        <tr>
            <td style="border: 1px solid #000; padding: 10px;">Amenazas</td>
            <td style="border: 1px solid #000;">Gigantes de IoT añadiendo capas de validación por software gratuitas.</td>
            <td style="border: 1px solid #000;">Regulaciones de privacidad de datos biométricos más estrictas a nivel global.</td>
            <td style="border: 1px solid #000;">Competidores que ofrezcan integración gratuita con APIs estandarizadas.</td>
            <td style="border: 1px solid #000;">Entrada de actores globales (como Uber Direct) al espacio de última milla.</td>
        </tr>
    </tbody>
</table>

#### 2.1.2. Estrategias y tácticas frente a competidores

**Estrategia de posicionamiento:**

CoBox Smart Vision se posiciona como una solución especializada en la validación automática de información operativa mediante inteligencia artificial, orientada a mejorar la confiabilidad de los datos en entornos logísticos.

A diferencia de plataformas de gestión de flotas o sistemas de planificación logística, la propuesta no busca reemplazar soluciones existentes, sino resolver una brecha específica relacionada con la integridad y verificabilidad de los datos, especialmente en escenarios donde el ingreso manual de información genera errores o inconsistencias.

Este posicionamiento permite enfocar la solución en segmentos que actualmente no cuentan con herramientas avanzadas de validación, particularmente pequeñas y medianas empresas de transporte de carga con procesos manuales o semi-digitalizados.

**Estrategias frente a competidores:**

1. _Estrategia de diferenciación por especialización:_
  En lugar de competir en amplitud funcional con plataformas como Samsara o Powerfleet, CoBox Smart Vision se enfoca en un dominio específico: la validación automática de datos operativos mediante evidencia visual.
  Esta especialización permite desarrollar capacidades profundas en el uso de inteligencia artificial aplicada a la interpretación de imágenes y documentos, generando un valor que no es ofrecido por soluciones tradicionales centradas en la gestión o monitoreo.

2. _Estrategia de entrada por segmento desatendido (PyMES):_
  La solución se orienta inicialmente a pequeñas y medianas empresas de transporte de carga, las cuales presentan altos niveles de dependencia de procesos manuales y menor acceso a soluciones avanzadas debido a costos o complejidad de implementación.
  Este segmento representa una oportunidad estratégica, ya que las soluciones existentes están principalmente diseñadas para empresas medianas y grandes con mayor capacidad de inversión en infraestructura y sistemas.

3. _Estrategia de reducción de fricción de adopción:_
  A diferencia de soluciones que requieren instalación de hardware especializado o procesos complejos de integración, CoBox Smart Vision prioriza un modelo basado en dispositivos móviles y captura de evidencia visual, reduciendo la barrera de entrada y facilitando la adopción por parte de usuarios en campo.
  Este enfoque permite validar rápidamente la propuesta de valor sin necesidad de inversiones iniciales elevadas.

**Tácticas frente a competidores**

1. _Enfoque en casos de uso críticos:_
  Priorizar escenarios específicos donde la validación automática de datos tenga mayor impacto, como el registro de kilometraje, validación de documentos logísticos y verificación de entregas, permitiendo demostrar valor tangible en etapas tempranas.

2. _Validación temprana con usuarios reales:_
  Realizar pruebas piloto con conductores y gestores logísticos para evaluar la facilidad de uso, la aceptación del modelo basado en evidencia visual y el impacto en la reducción de errores operativos.
  
3. _Simplificación extrema de la experiencia de usuario:_
  Diseñar interfaces con flujos mínimos de interacción, donde el usuario capture evidencia en lugar de ingresar datos manualmente, reduciendo la carga cognitiva y facilitando la adopción en campo.

4. _Enfoque en métricas de valor:_
  Medir el impacto de la solución mediante indicadores concretos como reducción de errores, disminución del tiempo de registro y mejora en la confiabilidad de los datos, permitiendo sustentar el valor frente a alternativas existentes.

### 2.2. Entrevistas

#### 2.2.1 Diseño de entrevistas

El diseño de entrevistas tiene como objetivo validar las hipótesis planteadas en el proceso Lean UX, particularmente aquellas relacionadas con la adopción de soluciones basadas en inteligencia artificial, la reducción del ingreso manual de datos y la confiabilidad de la información operativa.

Se han definido dos segmentos objetivo para la recolección de información: gestores de operaciones logísticas y conductores de unidades de carga.

---

**Segmento 1: Gestión de operaciones logísticas**

1. ¿Cuál es su rol dentro de la empresa y cuáles son sus principales responsabilidades en la gestión de la flota?  
2. ¿Cuántos vehículos administra y qué tipo de operaciones logísticas realiza (distribución, larga distancia, última milla)?  
3. ¿Cómo se registran actualmente los datos operativos como kilometraje, consumo de combustible y entregas?  
4. ¿Qué herramientas utiliza actualmente para gestionar y supervisar estas operaciones?  
5. ¿Qué problemas o inconsistencias ha identificado en los datos reportados por los conductores?  
6. ¿Qué impacto tienen estos errores o discrepancias en la operación y en la toma de decisiones?  
7. ¿Cómo valida actualmente la veracidad de la información reportada desde campo?  
8. ¿Qué tan importante es para usted contar con información verificable y auditada automáticamente?  
9. ¿Qué tan dispuesto estaría a utilizar una solución que valide automáticamente los datos mediante el análisis de imágenes o evidencia visual?  
10. ¿Qué preocupaciones tendría respecto al uso de sistemas automatizados basados en inteligencia artificial?  
11. ¿Qué beneficios esperaría obtener de una solución que elimine la necesidad de validar manualmente la información?  
12. ¿Qué factores serían determinantes para adoptar una nueva herramienta tecnológica en su operación (costo, facilidad de uso, precisión, integración, etc.)?  

---

**Segmento 2: Conductores / operadores de ruta**

1. ¿Cuánto tiempo lleva trabajando como conductor de transporte de carga y qué tipo de rutas realiza?  
2. ¿Cómo registra actualmente el inicio y fin de cada viaje?  
3. ¿Cómo registra el kilometraje y consumo de combustible durante sus recorridos?  
4. ¿Cuánto tiempo le toma completar estos registros al finalizar un servicio?  
5. ¿Qué dificultades ha tenido al registrar información durante o después de un viaje?  
6. ¿Ha tenido problemas o conflictos relacionados con errores en los datos que registra?  
7. ¿Qué tan cómodo se siente utilizando aplicaciones móviles en su trabajo diario?  
8. ¿Preferiría capturar una fotografía del odómetro o documento en lugar de ingresar los datos manualmente? ¿Por qué?  
9. ¿Qué tan fácil o difícil cree que sería utilizar una aplicación que valide automáticamente la información a partir de una imagen?  
10. ¿Qué condiciones podrían dificultar el uso de este tipo de aplicación (iluminación, conectividad, tiempo, etc.)?  
11. ¿Qué características considera importantes para que una aplicación sea fácil de usar durante sus rutas?  
12. ¿Qué lo motivaría a completar correctamente el registro de información en cada servicio?  

#### 2.2.2. Registro de entrevistas

**Segmento 1: Gestión de operaciones logísticas**

**Entrevista #1**

**Datos generales**

| Detalle       | Información                                      |
|---------------|--------------------------------------------------|
| Entrevistado  | Ricardo Valdivia Quispe                          |
| Rol           | Coordinador de Operaciones                       |
| Empresa       | Transportes Valdivia SAC                         |
| Edad          | 38 años                                          |
| Origen        | Huancayo, reside en Lima Norte                   |
| Flota         | 14 unidades — rutas Lima–Junín–Pasco             |

---

**Resumen de la entrevista**

Ricardo coordina una flota de 14 camiones en una empresa familiar de transporte interprovincial. Gestiona toda la operación con WhatsApp, Excel y llamadas telefónicas, sin herramientas integradas. Un intento previo de implementar GPS fue abandonado al año por costos de mensualidad.

Identifica inconsistencias frecuentes en el kilometraje reportado por los conductores —diferencias de 50 a 60 km sin justificación— y boletas de combustible que no corresponden a la fecha o ruta del servicio. No cuenta con ningún mecanismo real de auditoría: su única validación es cruzar manualmente los datos con Google Maps, lo que califica él mismo como "intuición, no auditoría".

El impacto más directo de estas discrepancias es doble: conflictos internos con conductores que no pueden resolverse por falta de evidencia, e incapacidad de proyectar costos de combustible con datos confiables para reportar al gerente general. Describe su situación con claridad: *"eso no es gestión, es adivinar"*.

Muestra disposición media-alta ante una solución de captura visual y validación automática, condicionada a que no le genere más carga operativa a él. El modelo que le genera mayor interés es el de alertas proactivas ante anomalías, no el de consulta activa. Sus principales objeciones son la precisión del sistema ante falsos positivos, la privacidad de los datos y la necesidad de un caso económico claro para convencer al dueño, dado el antecedente negativo con el GPS.

---

**Entrevista #2**

**Datos generales**

| Detalle       | Información                                          |
|---------------|------------------------------------------------------|
| Entrevistada  | Miriam Ccori Huanca                                  |
| Rol           | Jefa de Operaciones                                  |
| Empresa       | Grupo Ccori Logística EIRL                           |
| Edad          | 44 años                                              |
| Origen        | Cusco, reside en San Juan de Lurigancho              |
| Flota         | 22 unidades — distribución retail Lima Metropolitana |

---

**Resumen de la entrevista**

Miriam dirige las operaciones de una empresa de distribución retail fundada por su familia en Cusco, con 22 unidades activas en Lima. Reporta ante un directorio de tres socios, lo que le exige presentar datos operativos confiables de forma periódica. A pesar de contar con un TMS instalado hace tres años y GPS en todas las unidades, el sistema está subutilizado: los conductores siguen llenando papel y el equipo transcribe manualmente al sistema, generando doble trabajo para el mismo dato.

Sus problemas principales son la variabilidad inexplicable de consumo de combustible entre unidades similares —hasta un 30% de diferencia sin causa técnica identificada— y la incapacidad de resolver disputas con clientes por falta de evidencia de entrega. Ambos problemas le han generado consecuencias concretas: pérdida de un contrato de cliente corporativo que exigía trazabilidad formal, y cuestionamientos recurrentes del directorio ante márgenes operativos inconsistentes.

Su validación actual consiste en cruzar manualmente el registro GPS con los reportes del conductor solo cuando hay un reclamo puntual, lo que la deja con visibilidad reactiva y parcial sobre la operación. Describe la necesidad de datos auditables como urgente tanto para retener clientes como para sostener su posición ante los socios.

Muestra alta disposición hacia una solución de captura visual y validación automática, pero exige implementación gradual tras una mala experiencia previa con un TMS que fue lanzado sin soporte adecuado. Sus criterios de adopción incluyen integración con sistemas existentes, soporte postventa con SLA claro, gestión del cambio con conductores veteranos y resultados medibles en los primeros dos meses.

---

**Entrevista #3**

**Datos generales**

| Detalle       | Información                                           |
|---------------|-------------------------------------------------------|
| Entrevistado  | Jorge Mamani Apaza                                    |
| Rol           | Gerente General y fundador                            |
| Empresa       | Trans Mamani Cargo SAC                                |
| Edad          | 52 años                                               |
| Origen        | Puno, reside en Villa El Salvador                     |
| Flota         | 8 unidades propias + 6 en alquiler — rutas Lima–sur   |

---

**Resumen de la entrevista**

Jorge fundó su empresa en 2003 con un solo camión. Hoy administra 14 unidades operativas sin ningún sistema formal: usa cuaderno físico, WhatsApp y llamadas telefónicas para controlar toda la operación. Es el único decisor de la empresa, lo que simplifica el proceso de adopción pero también concentra en él todas las resistencias al cambio.

La transición de empresa pequeña a mediana le generó una pérdida de control que reconoce con preocupación: antes conocía cada detalle de la operación porque la manejaba personalmente, hoy no puede hacer seguimiento confiable de 14 unidades, especialmente de las 6 alquiladas cuyos conductores no son de su confianza directa. Ha tenido casos documentados de odómetros manipulados en unidades alquiladas y boletas de combustible de grifos que no corresponden a la ruta reportada.

El impacto económico es concreto: estima que hay un margen mensual inexplicable producto de kilómetros y combustible inflados, y perdió un cliente en Arequipa que solicitó reportes formales de cada servicio para su auditoría interna, algo que Jorge no pudo proveer. Señala con honestidad: *"me da vergüenza mostrarles mi cuaderno"*.

Su disposición ante tecnología es escéptica pero pragmática: no rechaza la solución, pero exige verla funcionar en una de sus unidades reales antes de comprometerse. El término "inteligencia artificial" le genera distancia; el valor debe comunicársele en lenguaje operativo concreto. Es el perfil de cierre más rápido si el piloto convence, ya que no necesita aprobación de ningún comité. Sus condiciones son simplicidad real de uso, precio accesible para una pyme y acompañamiento en el arranque.

---

**Segmento 2: Conductores / operadores de ruta**

**Entrevista #1**

**Datos generales**

| Detalle       | Información                                         |
|---------------|-----------------------------------------------------|
| Entrevistado  | Edilberto Poma Condori                              |
| Rol           | Conductor de larga distancia                        |
| Ruta          | Lima–Arequipa–Juliaca                               |
| Edad          | 46 años                                             |
| Origen        | Juliaca, reside en Villa María del Triunfo          |
| Experiencia   | 19 años — licencia AIII-C, récord limpio en SUTRAN  |

---

**Resumen de la entrevista**

Edilberto es conductor de larga distancia con 19 años de trayectoria, especializado en rutas al sur del país. Registra su operación en un cuadernillo propio que completa a mano durante el viaje y entrega al retorno, proceso que le toma entre una hora y hora y media al cierre de cada servicio. Reconoce abiertamente que el cansancio después de jornadas de 12 horas genera errores involuntarios en los registros numéricos.

Sus principales conflictos operativos se originan en eventos que no quedan documentados: desvíos por huaycos o bloqueos viales en rutas de sierra, tiempos de espera en almacenes de destino de hasta cuatro horas, y retenciones por controles policiales en carretera. Ninguno de estos eventos tiene canal formal de registro, lo que deriva en discrepancias de kilometraje que luego son cuestionadas por el coordinador sin posibilidad de defensa objetiva. Sufrió un descuento de viáticos injustificado por este motivo, episodio que recuerda con malestar acumulado: *"uno guarda esas cosas"*.

Usa WhatsApp con fluidez pero rechaza aplicaciones con múltiples pantallas; abandonó una app anterior tras dos semanas por complejidad de uso. Su aceptación de la captura visual es inmediata y entusiasta: identifica con precisión que la foto del odómetro es más rápida y prueba que el dato es real, lo que invierte la dinámica actual donde "el papel casi siempre gana". Sus condiciones técnicas son claras: funcionamiento offline en zonas sin señal de la sierra y el altiplano, botones grandes compatibles con uso con guantes, legibilidad bajo luz solar directa y confirmación visible de que el registro fue guardado.

Su motivación para adoptar la solución no es económica sino de justicia laboral: quiere que su trabajo bien hecho quede respaldado automáticamente, sin depender de que alguien le crea.

---

**Entrevista #2**

**Datos generales**

| Detalle       | Información                                          |
|---------------|------------------------------------------------------|
| Entrevistada  | Yadira Ríos Solano                                   |
| Rol           | Conductora de reparto urbano                         |
| Ruta          | Lima Metropolitana — reparto multípunto              |
| Edad          | 34 años                                              |
| Origen        | Piura, reside en San Martín de Porres                |
| Experiencia   | 5 años — licencia AIII-B, opera con ayudante         |

---

**Resumen de la entrevista**

Yadira realiza hasta 14 o 15 entregas diarias en Lima Metropolitana, lo que la convierte en el perfil con mayor volumen de registros por jornada entre los conductores entrevistados. El cierre administrativo del día le toma entre 40 minutos y una hora, parte del cual corresponde a transcripción duplicada: registra información en papel durante la ruta y luego la pasa al Excel del coordinador. Identifica este proceso como ineficiente desde hace tiempo y ya lo escaló internamente sin obtener respuesta.

El conflicto más frecuente que enfrenta es el de entregas rechazadas posteriormente por clientes que no firmaron o que niegan haber recibido la carga completa. Sin evidencia objetiva, la resolución depende de a quién le cree la empresa. Por iniciativa propia, Yadira comenzó a fotografiar cada entrega —producto descargado y guía firmada— y a enviarlas por WhatsApp al coordinador, práctica que ella misma diseñó sin que nadie se la pidiera y que la ha protegido en múltiples ocasiones. Es la usuaria que más claramente articula el valor de CoBox: la solución formaliza y organiza lo que ella ya hace de forma manual.

Su comodidad digital es alta: usa Google Maps, Waze y WhatsApp de forma habitual. Sus objeciones no son de capacidad sino de diseño: rechaza el onboarding largo, los flujos lentos y la falta de confirmación de guardado. Define con precisión el producto que necesita: foto georeferenciada asociada automáticamente a cada entrega, lista de pendientes del día consultable, y validación inmediata de la imagen con mensaje claro si algo salió mal.

Una observación de campo relevante que aporta: en algunos almacenes de mercados mayoristas no se permite el uso del celular en el interior, por lo que el registro debe hacerse fuera del recinto. Su motivación de adopción está ligada a la reciprocidad: usará el sistema si también ella puede consultar su propio historial, no solo la empresa.

---

**Entrevista #3**

**Datos generales**

| Detalle       | Información                                                  |
|---------------|--------------------------------------------------------------|
| Entrevistado  | Hipólito Ccama Luque                                         |
| Rol           | Conductor de carga pesada                                    |
| Ruta          | Lima–Ica–Nasca                                               |
| Edad          | 41 años                                                      |
| Origen        | Nasca, reside en Lurlurín desde hace 6 años                  |
| Experiencia   | 8 años — licencia AIII-C con habilitación mercancías peligrosas |

---

**Resumen de la entrevista**

Hipólito transporta insumos agroindustriales con habilitación para mercancías peligrosas en la ruta Lima–sur. La naturaleza regulada de su carga le exige documentación adicional con datos técnicos —temperatura, presión, volumen— que no siempre comprende en detalle, lo que le genera incertidumbre al momento de llenar formularios en campo. Tuvo un caso de error por confusión de unidades de medida (litros vs. galones) que derivó en un llamado de atención formal.

Su conflicto más significativo involucra una retención de SUTRAN en Cañete de aproximadamente una hora que no quedó documentada en ningún registro oficial. La demora causó un reclamo del cliente y una consulta de la empresa sin que él pudiera aportar más que su palabra. Desde entonces intenta solicitar el número de acta de intervención policial cuando lo retienen, pero no siempre lo obtienen con rapidez. Esta situación define con claridad su necesidad: el registro automático de hora y ubicación en paradas forzadas es el caso de uso de mayor valor para su perfil.

Describe desconfianza hacia las aplicaciones móviles no por incapacidad técnica sino por experiencias previas con apps que solicitaban permisos excesivos sin explicación. Esta barrera es psicológica y puede superarse con comunicación transparente sobre el uso de cada permiso. Su uso digital actual se limita a WhatsApp con mensajes de voz.

Sus requisitos de uso son precisos: modo offline obligatorio para tramos sin cobertura entre Cañete, Chincha y zonas de Ica; fallback manual si la foto no es reconocida por el sistema; mensajes de error descriptivos y accionables en lugar de alertas genéricas; autocompletado de datos conocidos como placa y ruta habitual; e interfaz mínima con instrucciones explícitas en cada paso. Su motivación de adopción es la seguridad: protección ante fiscalizaciones de SUTRAN, reducción de conflictos al retornar a Lima y tranquilidad de saber que su trabajo queda documentado. Resume su postura con una observación que aplica a todo el proceso de diseño del producto: *"quien diseña la app capaz no las piensa"*, en referencia a las condiciones reales de uso en campo que raramente llegan al equipo de desarrollo.

#### 2.2.3. Análisis de entrevistas

A partir de las entrevistas realizadas a los segmentos de gestión de operaciones logísticas y conductores de unidades de carga, se identificaron patrones consistentes en relación con los problemas operativos, la confiabilidad de los datos y la adopción de soluciones tecnológicas en el contexto del transporte de carga.

---

**1. Problemas recurrentes identificados**

Se evidenció una alta dependencia de procesos manuales para el registro de información operativa, incluyendo kilometraje, consumo de combustible y eventos de servicio. Estos procesos generan errores frecuentes, pérdida de información y retrasos en la disponibilidad de datos.

Asimismo, se identificaron inconsistencias recurrentes en los datos reportados, tales como diferencias de kilometraje sin justificación y registros de combustible que no corresponden al contexto operativo. Estas discrepancias impactan directamente en los costos y en la capacidad de planificación de las empresas.

Otro problema crítico identificado es la ausencia de mecanismos formales de validación de la información. La verificación de datos se realiza de manera manual y reactiva, generalmente solo cuando ocurre un conflicto, lo que limita la capacidad de control y auditoría de las operaciones.


**2. Impacto en la operación logística**

Los problemas identificados generan efectos directos en la gestión operativa, incluyendo:

- Conflictos entre conductores y gestores debido a la falta de evidencia objetiva
- Dificultades para tomar decisiones basadas en datos confiables
- Pérdida de clientes por falta de trazabilidad y evidencia de servicio
- Incremento de costos operativos debido a datos inconsistentes

Estos impactos reflejan que la problemática no es únicamente técnica, sino también organizacional, afectando la confianza interna y la relación con clientes.

---

**3. Comportamiento y necesidades de los usuarios**

En el segmento de gestión, se observa una necesidad clara de contar con información confiable, verificable y disponible en tiempo oportuno para la toma de decisiones. Los gestores priorizan la capacidad de auditar datos y detectar inconsistencias de manera proactiva.

En el segmento de conductores, se identificó una preferencia por soluciones simples, con mínima interacción, que no incrementen la carga operativa durante la ejecución de sus tareas. La captura de evidencia visual es percibida como una alternativa más práctica frente al ingreso manual de datos.

Asimismo, se identificaron condiciones operativas relevantes como la necesidad de funcionamiento offline, uso en entornos con iluminación variable y limitaciones en el uso de dispositivos móviles en ciertos contextos.

---

**4. Validación de hipótesis Lean UX**

Los resultados obtenidos permiten validar las siguientes hipótesis planteadas:

- La dependencia del ingreso manual de datos es una de las principales causas de errores e inconsistencias en la información operativa.
- Existe una necesidad real de contar con mecanismos de validación automática que permitan garantizar la confiabilidad de los datos.
- Los usuarios están dispuestos a adoptar soluciones basadas en captura de evidencia visual, siempre que estas no incrementen la complejidad de uso.
- La disponibilidad de información validada tiene un impacto directo en la toma de decisiones y en la eficiencia operativa.

Estas validaciones confirman la relevancia del problema identificado y la pertinencia de la propuesta de solución planteada.

---

**5. Riesgos y barreras de adopción**

A pesar de la disposición hacia soluciones tecnológicas, se identificaron riesgos relevantes que podrían afectar la adopción:

- Escepticismo hacia nuevas herramientas debido a experiencias previas fallidas
- Desconfianza en la precisión de sistemas automatizados
- Resistencia al cambio en usuarios con baja alfabetización digital
- Limitaciones operativas como conectividad intermitente y condiciones de uso en campo

Estos factores deben ser considerados en el diseño de la solución para asegurar su viabilidad en entornos reales.

---

**6. Oportunidad identificada**

El análisis evidencia una brecha clara en el mercado: la falta de soluciones que permitan validar automáticamente la información operativa en entornos logísticos.

Mientras que las herramientas actuales se enfocan en la captura y gestión de datos, no abordan de manera central la confiabilidad de la información registrada.

En este contexto, se identifica una oportunidad para desarrollar una solución que permita reducir la dependencia del ingreso manual y mejorar la integridad de los datos mediante mecanismos automatizados de validación, alineándose con las necesidades identificadas en ambos segmentos de usuarios.

### 2.3. Needfinding

#### 2.3.1 User Personas

A partir del análisis de entrevistas realizado en la sección 2.2.3, se definieron dos user personas representativas de los segmentos objetivo. Estos perfiles sintetizan patrones reales de comportamiento, necesidades y problemáticas identificadas en los usuarios entrevistados.

**Segmento 1: Gestión de operaciones logísticas**

User Persona: **Ricardo Lozano — Coordinador de Operaciones**

<img src="./assets/tb1/user_persona_1.png" alt="User Persona Coordinador de Operaciones" />

Este perfil representa a gestores que operan con herramientas fragmentadas, enfrentan inconsistencias en datos y requieren información confiable para la toma de decisiones.

---

**Segmento 2: Conductores de transporte**

User Persona: **Luis Soto — Conductor de larga distancia**

<img src="./assets/tb1/user_persona_2.png" alt="User Persona Conductor de larga distancia" />

Este perfil representa a conductores que trabajan en condiciones exigentes, con alta carga operativa, y que necesitan herramientas simples que reduzcan el esfuerzo de registro y respalden su trabajo con evidencia objetiva.


#### 2.3.2 User Task Matrix

A partir de los user personas definidos, se identificaron las tareas clave que cada perfil realiza dentro del proceso logístico, así como su frecuencia e importancia dentro de la operación.

| Tareas / User Persona              | Ricardo Lozano (Frec.) | Ricardo Lozano (Imp.) | Luis Soto (Frec.) | Luis Soto (Imp.) |
|----------------------------------|--------------------------|--------------------------|-------------------------|------------------------|
| Planificar rutas                 | Alta                     | Alta                     | N/A                     | N/A                    |
| Coordinar entregas              | Alta                     | Alta                     | Media                   | Alta                   |
| Registrar kilometraje           | Media                    | Alta                     | Alta                    | Alta                   |
| Reportar consumo de combustible | Media                    | Alta                     | Alta                    | Alta                   |
| Validar información operativa   | Alta                     | Alta                     | Baja                    | Alta                   |
| Consolidar datos                | Alta                     | Alta                     | N/A                     | N/A                    |
| Generar reportes               | Media                    | Alta                     | N/A                     | N/A                    |
| Capturar evidencia (odómetro / entrega) | Baja             | Alta                     | Alta                    | Alta                   |
| Usar aplicaciones móviles       | Media                    | Alta                     | Baja                    | Alta                   |
| Verificar entregas              | Alta                     | Alta                     | Media                   | Alta                   |
| Atender reclamos                | Media                    | Alta                     | Baja                    | Media                  |

**Conclusiones de la sección**

- Ambos perfiles dependen de tareas críticas relacionadas con el registro de kilometraje, consumo de combustible y verificación de entregas, las cuales presentan actualmente problemas de confiabilidad.

- El perfil de gestión (Ricardo Lozano) se enfoca en la consolidación, validación y análisis de la información, siendo altamente dependiente de la precisión de los datos para la toma de decisiones.

- El perfil operativo (Luis Soto) se enfoca en la ejecución del servicio, priorizando herramientas simples que reduzcan la carga de registro y permitan documentar eventos en campo de forma rápida.

- Se identifica como punto crítico compartido la necesidad de contar con evidencia verificable que respalde los datos registrados, reduciendo conflictos operativos y mejorando la trazabilidad.

- La solución debe priorizar la automatización del registro y validación de datos en campo, así como la disponibilidad de información confiable para el análisis operativo.

#### 2.3.3. Empathy Mapping

#### 2.3.4. As-is Scenario Mapping

<img src="./assets/tb1/asismapp1.png" alt="As Is Scenario Mapping" />
<img src="./assets/tb1/asismapp2.png" alt="As Is Scenario Mapping" />


### 2.4. Ubiquitous Language

| Término en Inglés         | Término en Español         | Definición                                                                                                                      |
|--------------------------|----------------------------|-------------------------------------------------------------------------------------------------------------------------------|
| Logistics Operation      | Operación logística        | Proceso de planificación, ejecución y control de servicios de transporte de carga, incluyendo rutas, entregas y registros.     |
| Fleet                   | Flota                      | Conjunto de vehículos gestionados por una empresa de transporte para realizar servicios logísticos.                            |
| Service Event           | Evento operativo           | Suceso relevante durante la operación logística (ej. inicio de ruta, carga, descarga, parada, incidente).                      |
| Evidence Capture        | Captura de evidencia       | Proceso de registrar información visual (fotos, documentos) para validar datos operativos en campo.                            |
| Smart Validation        | Validación inteligente     | Proceso automatizado de verificación de datos mediante inteligencia artificial, reduciendo errores y fraudes.                  |
| Field Operator          | Operador de campo          | Persona encargada de ejecutar servicios logísticos y registrar eventos durante el recorrido (conductor/a).                     |
| Operations Manager      | Gestor de operaciones      | Responsable de coordinar, supervisar y validar la información de las operaciones logísticas.                                   |
| Manual Entry            | Ingreso manual             | Registro de datos realizado por el usuario sin automatización, susceptible a errores humanos.                                  |
| Visual Evidence         | Evidencia visual           | Imagen o documento capturado para respaldar un evento operativo (ej. foto de odómetro, guía firmada).                         |
| Offline Mode            | Modo offline               | Funcionalidad que permite operar la aplicación sin conexión a internet, sincronizando datos posteriormente.                    |
| Route Traceability      | Trazabilidad de ruta       | Capacidad de seguir y auditar el recorrido y eventos de un servicio logístico.                                                 |
| Anomaly Alert           | Alerta de anomalía         | Notificación generada automáticamente ante detección de inconsistencias o posibles fraudes en los datos operativos.            |
| Dashboard               | Panel de control           | Vista gráfica que muestra indicadores clave, reportes y estado de las operaciones logísticas.                                  |
| Proof of Delivery       | Comprobante de entrega     | Evidencia (visual o documental) que certifica la realización exitosa de una entrega.                                           |
| Fuel Consumption        | Consumo de combustible     | Registro y control del uso de combustible por vehículo durante la operación.                                                   |
| Mileage                 | Kilometraje                | Distancia recorrida por un vehículo, registrada para control y auditoría.                                                      |
| User Persona            | Persona usuaria            | Perfil representativo de los usuarios objetivo, utilizado para guiar el diseño y validación de la solución.                    |
| Needfinding             | Identificación de necesidades | Proceso de descubrir y documentar los requerimientos y problemas reales de los usuarios.                                   |
| EventStorming           | EventStorming              | Técnica colaborativa para modelar procesos y eventos clave del dominio logístico.                                              |
| Bounded Context         | Contexto delimitado        | Área específica del dominio donde un modelo es válido y consistente, sin ambigüedades.                                         |
| Product Backlog         | Lista de producto          | Conjunto priorizado de funcionalidades, requisitos y tareas pendientes del producto.                                           |
| Impact Mapping          | Mapeo de impacto           | Técnica para visualizar cómo las funcionalidades contribuyen a los objetivos del negocio.                                      |
| Lean UX                 | Lean UX                    | Metodología ágil para diseñar experiencias de usuario centradas en la validación continua.                                     |
| Stakeholder             | Interesado                 | Persona o grupo que tiene interés o se ve afectado por el proyecto CoBox.                                                     |
| Compliance              | Cumplimiento normativo     | Adherencia a regulaciones y estándares aplicables al transporte y gestión de datos.                                            |
| Service Report          | Reporte de servicio        | Documento o registro que resume los eventos, incidencias y resultados de una operación logística.                              |
| Exception Handling      | Manejo de excepciones      | Proceso de registrar y gestionar eventos no planificados o incidentes durante la operación.                                   |
| Synchronization         | Sincronización             | Proceso de actualizar y consolidar datos entre dispositivos y la plataforma central.                                           |
| User Onboarding         | Incorporación de usuario   | Proceso de registro y capacitación inicial de nuevos usuarios en la plataforma.                                                |
| Field Constraints       | Restricciones de campo     | Condiciones reales que afectan la operación, como conectividad limitada o uso de dispositivos en ambientes adversos.           |
| Georeferenced Photo     | Foto georreferenciada      | Imagen capturada con información de ubicación, utilizada para validar eventos en campo.                                        |
| Audit Trail             | Registro de auditoría      | Historial detallado de acciones y cambios realizados en la plataforma para control y trazabilidad.                             |
| Service Assignment      | Asignación de servicio     | Proceso de designar rutas o tareas específicas a conductores o vehículos.                                                      |
| Mobile Application      | Aplicación móvil           | Herramienta digital utilizada en campo para registrar eventos y evidencias durante la operación.                               |
| Cloud Integration       | Integración en la nube     | Capacidad de la plataforma para conectarse y compartir datos con servicios cloud externos.                                     |
| Evidence Validation     | Validación de evidencia    | Proceso de confirmar la autenticidad y relevancia de la evidencia capturada.                                                  |
| Operational Efficiency  | Eficiencia operativa       | Medida de optimización de recursos y reducción de errores en la gestión logística.                                             |
| Service Schedule        | Programación de servicios  | Planificación anticipada de rutas, entregas y tareas logísticas.                                                              |
| Notification            | Notificación               | Mensaje enviado a usuarios para informar sobre eventos, alertas o tareas pendientes.                                           |
| Exception Report        | Reporte de excepción       | Documento que detalla incidentes o eventos fuera de lo planificado durante la operación.                                       |
| Evidence Sync           | Sincronización de evidencias| Proceso de actualizar y consolidar las evidencias capturadas entre dispositivos y la plataforma central.                      |


---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping
En esta sección se presenta el To-Be Scenario Mapping del sistema, el cual describe cómo se desarrollan las actividades de los usuarios en el escenario propuesto. Para su elaboración, el equipo partió del análisis del escenario actual (As-Is), realizando una etapa de preparación y lluvia de ideas individual, seguida de una revisión conjunta para identificar las fases del proceso y estructurarlas como columnas del mapa.

A partir de este proceso, se definieron las actividades (Doing), pensamientos (Thinking) y emociones (Feeling) de cada User Persona a lo largo de las distintas fases del servicio. El resultado refleja un cambio significativo en la forma de interacción con el sistema, donde se reemplaza el registro manual de información por un enfoque basado en captura de evidencia y validación automática de datos.

En comparación con el escenario actual, el To-Be Scenario introduce mejoras orientadas a reducir errores humanos, incrementar la confiabilidad de la información y facilitar la operación en campo, especialmente en entornos con conectividad limitada. Asimismo, se fortalece la trazabilidad de los servicios mediante el registro estructurado de evidencias, incidencias y estados operativos.

A continuación, se presentan los To-Be Scenario Mapping correspondientes a cada segmento de usuario.

#### Segmento 1: Gestión de Operaciones Logísticas
![To-Be Scenario Mapping - Gestor](assets/tb1/tobesegmento1.png)

#### Segmento 2: Conductores de Transporte
![To-Be Scenario Mapping - Conductor](assets/tb1/tobesegmento2.png)
### 3.2. User Stories
En esta sección se presentan los Epics y User Stories del proyecto, definidos a partir de las necesidades identificadas en los segmentos de gestión de operaciones logísticas y conductores de unidades de carga. Las historias cubren tanto las funcionalidades principales del producto digital como las necesidades del sitio web estático y los componentes técnicos requeridos para soportar la solución.  

La estructura considera historias orientadas a la planificación y seguimiento de servicios, captura y validación de evidencias, gestión de incidencias, generación de reportes y exposición de servicios mediante API, con el propósito de asegurar trazabilidad, confiabilidad de la información y una experiencia de uso adecuada para contextos operativos reales.

| Epic/Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------|--------|-------------|-------------------------|---------------------------|
| EP01 | Gestión operativa de servicios | Centraliza la planificación, consulta y seguimiento de servicios logísticos para gestores y conductores. | No aplica. | — |
| EP02 | Captura y validación inteligente | Automatiza el registro y validación de información operativa a partir de evidencia visual y datos contextuales. | No aplica. | — |
| EP03 | Incidencias y trazabilidad | Permite registrar eventos operativos, anomalías y evidencias para mejorar la auditoría y resolución de conflictos. | No aplica. | — |
| EP04 | Reportes y control operativo | Proporciona reportes, alertas e indicadores basados en datos validados para la toma de decisiones. | No aplica. | — |
| EP-LP | Sitio web estático | Presenta la propuesta de valor, beneficios, segmentos y mecanismos de contacto del producto. | No aplica. | — |
| EP-API | API RESTful e integración | Expone servicios interoperables para aplicaciones web, móvil e integraciones externas. | No aplica. | — |
| EP06 | Operación offline y sincronización | Asegura continuidad operativa en campo con conectividad limitada y sincronización posterior. | No aplica. | — |
| US-01 | Consultar servicios programados | Como gestor, deseo consultar los servicios logísticos programados para supervisar la operación diaria. | **Escenario 01: consulta de servicios**<br>Dado que el gestor accede a la información operativa<br>Cuando consulta los servicios de un periodo determinado<br>Entonces el sistema muestra la lista de servicios con unidad, conductor, ruta y estado.<br><br>**Escenario 02: filtrado por estado**<br>Dado que existen servicios en distintos estados<br>Cuando el gestor aplica un filtro por estado<br>Entonces el sistema presenta solo los servicios que cumplen la condición. | EP01 |
| US-02 | Asignar conductor y unidad a servicio | Como gestor, deseo asignar un conductor y una unidad a un servicio para organizar su ejecución. | **Escenario 01: asignación válida**<br>Dado que existe un servicio pendiente y recursos disponibles<br>Cuando el gestor registra la asignación<br>Entonces el sistema guarda la relación entre servicio, conductor y unidad.<br><br>**Escenario 02: recurso no disponible**<br>Dado que la unidad o el conductor ya están comprometidos en otro servicio superpuesto<br>Cuando el gestor intenta asignarlos<br>Entonces el sistema rechaza la operación e informa la inconsistencia. | EP01 |
| US-03 | Consultar servicios asignados del día | Como conductor, deseo consultar mis servicios asignados del día para planificar mi jornada. | **Escenario 01: consulta diaria**<br>Dado que el conductor tiene servicios asignados<br>Cuando accede a su información operativa<br>Entonces el sistema muestra los servicios del día con destino, horario y estado.<br><br>**Escenario 02: ausencia de asignaciones**<br>Dado que el conductor no tiene servicios asignados<br>Cuando consulta su jornada<br>Entonces el sistema informa que no existen servicios registrados para el periodo. | EP01 |
| US-04 | Registrar inicio de servicio | Como conductor, deseo registrar el inicio de un servicio para dejar constancia del momento de salida. | **Escenario 01: inicio válido**<br>Dado que el conductor tiene un servicio asignado en estado pendiente<br>Cuando registra el inicio del servicio<br>Entonces el sistema cambia el estado a en proceso y almacena la fecha y hora del registro.<br><br>**Escenario 02: servicio no asignado**<br>Dado que el conductor intenta iniciar un servicio no asignado a su perfil<br>Cuando procesa la acción<br>Entonces el sistema rechaza el registro. | EP01 |
| US-05 | Consultar historial de servicios | Como gestor, deseo consultar el historial de servicios ejecutados para revisar el desempeño operativo. | **Escenario 01: consulta histórica**<br>Dado que existen servicios registrados en el historial<br>Cuando el gestor consulta un rango de fechas<br>Entonces el sistema muestra los servicios con su resultado, evidencias y observaciones.<br><br>**Escenario 02: sin resultados**<br>Dado que no existen servicios en el rango solicitado<br>Cuando el gestor realiza la consulta<br>Entonces el sistema informa que no se encontraron registros. | EP01 |
| US-06 | Capturar evidencia de odómetro | Como conductor, deseo capturar una imagen del odómetro para registrar el kilometraje sin ingresarlo manualmente. | **Escenario 01: captura válida**<br>Dado que el conductor se encuentra en un punto de control del servicio<br>Cuando registra una fotografía del odómetro<br>Entonces el sistema almacena la evidencia y la asocia al servicio correspondiente.<br><br>**Escenario 02: evidencia no disponible**<br>Dado que no se adjunta una imagen válida<br>Cuando el conductor intenta continuar el proceso<br>Entonces el sistema informa que la evidencia requerida no ha sido registrada. | EP02 |
| US-07 | Extraer kilometraje automáticamente | Como gestor, deseo que el sistema extraiga automáticamente el kilometraje desde la evidencia visual para reducir errores humanos. | **Escenario 01: extracción exitosa**<br>Dado que existe una imagen legible del odómetro<br>Cuando el sistema procesa la evidencia<br>Entonces el sistema obtiene el valor de kilometraje y lo registra como dato validado.<br><br>**Escenario 02: extracción fallida**<br>Dado que la imagen no cumple condiciones mínimas de lectura<br>Cuando el sistema intenta procesarla<br>Entonces el sistema marca la evidencia como no validada y solicita una nueva captura o revisión. | EP02 |
| US-08 | Validar evidencia de entrega | Como gestor, deseo que el sistema valide automáticamente la evidencia de entrega para contar con respaldo verificable del servicio. | **Escenario 01: validación exitosa**<br>Dado que el conductor registra evidencia de una entrega<br>Cuando el sistema analiza la evidencia y el contexto del servicio<br>Entonces el sistema marca la entrega como validada.<br><br>**Escenario 02: inconsistencia detectada**<br>Dado que la evidencia registrada no coincide con el contexto del servicio<br>Cuando el sistema procesa la evidencia<br>Entonces el sistema marca la entrega como observada y genera una alerta de revisión. | EP02 |
| US-09 | Validar comprobante de combustible | Como gestor, deseo validar automáticamente comprobantes de combustible para detectar inconsistencias operativas. | **Escenario 01: comprobante coherente**<br>Dado que existe un comprobante asociado a un servicio activo<br>Cuando el sistema procesa la evidencia y contrasta fecha, unidad y contexto operativo<br>Entonces el sistema registra el comprobante como consistente.<br><br>**Escenario 02: comprobante inconsistente**<br>Dado que la evidencia presenta datos incompatibles con el servicio<br>Cuando el sistema ejecuta la validación<br>Entonces el sistema genera una observación y conserva trazabilidad del caso. | EP02 |
| US-10 | Registrar captura guiada de evidencia | Como conductor, deseo recibir validaciones básicas al momento de capturar una evidencia para evitar registros inválidos. | **Escenario 01: captura aceptada**<br>Dado que el conductor registra una imagen utilizable<br>Cuando el sistema revisa criterios mínimos de calidad<br>Entonces el sistema confirma el registro de la evidencia.<br><br>**Escenario 02: captura observada**<br>Dado que la imagen presenta problemas de calidad<br>Cuando el sistema verifica la evidencia<br>Entonces el sistema informa que la captura requiere repetición. | EP02 |
| US-11 | Registrar datos manuales de contingencia | Como conductor, deseo registrar datos manuales como contingencia cuando una evidencia no puede ser validada automáticamente para no detener la operación. | **Escenario 01: contingencia permitida**<br>Dado que el sistema no logra validar una evidencia<br>Cuando el conductor registra el dato manual con justificación<br>Entonces el sistema guarda la información con estado pendiente de revisión.<br><br>**Escenario 02: contingencia sin justificación**<br>Dado que el conductor omite la justificación requerida<br>Cuando intenta registrar el dato manual<br>Entonces el sistema rechaza el registro. | EP02 |
| US-12 | Detectar anomalías operativas | Como gestor, deseo que el sistema detecte anomalías en kilometraje, combustible o evidencias para intervenir oportunamente. | **Escenario 01: anomalía detectada**<br>Dado que existe una discrepancia significativa entre los datos operativos y el contexto del servicio<br>Cuando el sistema ejecuta la validación automática<br>Entonces el sistema genera una alerta de anomalía con trazabilidad del caso.<br><br>**Escenario 02: operación consistente**<br>Dado que los datos registrados son coherentes<br>Cuando el sistema finaliza la validación<br>Entonces el sistema no genera alertas. | EP02 |
| US-13 | Reportar incidencia operativa | Como conductor, deseo reportar incidencias durante un servicio para dejar constancia de eventos que afectan la operación. | **Escenario 01: registro exitoso**<br>Dado que ocurre un evento durante la ejecución del servicio<br>Cuando el conductor registra la incidencia con categoría y evidencia opcional<br>Entonces el sistema guarda la incidencia y la asocia al servicio.<br><br>**Escenario 02: datos incompletos**<br>Dado que falta la información mínima del incidente<br>Cuando el conductor intenta registrar la incidencia<br>Entonces el sistema rechaza la operación. | EP03 |
| US-14 | Registrar paradas no planificadas | Como conductor, deseo registrar paradas no planificadas para respaldar retrasos o desvíos ocurridos en ruta. | **Escenario 01: parada registrada**<br>Dado que el conductor se ve obligado a detener el recorrido<br>Cuando registra la parada con motivo<br>Entonces el sistema guarda la hora, ubicación disponible y justificación.<br><br>**Escenario 02: sincronización posterior**<br>Dado que la conectividad es limitada al momento del registro<br>Cuando la conexión se restablece<br>Entonces el sistema sincroniza la parada pendiente sin perder trazabilidad. | EP03 |
| US-15 | Consultar incidencias y observaciones | Como gestor, deseo consultar incidencias y observaciones operativas para priorizar acciones correctivas. | **Escenario 01: consulta de incidencias**<br>Dado que existen incidencias y observaciones registradas<br>Cuando el gestor accede al módulo correspondiente<br>Entonces el sistema muestra los casos con estado, severidad y servicio relacionado.<br><br>**Escenario 02: filtrado por prioridad**<br>Dado que existen múltiples casos abiertos<br>Cuando el gestor filtra por severidad o estado<br>Entonces el sistema presenta solo los registros que cumplen el filtro. | EP03 |
| US-16 | Resolver incidencia con trazabilidad | Como gestor, deseo registrar la resolución de una incidencia para mantener un historial auditable del caso. | **Escenario 01: cierre de incidencia**<br>Dado que una incidencia cuenta con análisis y acción correctiva<br>Cuando el gestor registra su resolución<br>Entonces el sistema cambia el estado a resuelta y almacena la evidencia de cierre.<br><br>**Escenario 02: cierre inválido**<br>Dado que la incidencia no contiene información mínima de resolución<br>Cuando el gestor intenta cerrarla<br>Entonces el sistema rechaza la operación. | EP03 |
| US-17 | Consultar trazabilidad completa del servicio | Como gestor, deseo consultar la trazabilidad completa de un servicio para auditar su ejecución con evidencias y eventos. | **Escenario 01: trazabilidad disponible**<br>Dado que un servicio tiene eventos registrados<br>Cuando el gestor consulta el detalle del servicio<br>Entonces el sistema muestra cronológicamente asignación, inicio, evidencias, incidencias, validaciones y cierre.<br><br>**Escenario 02: servicio con información parcial**<br>Dado que existen registros incompletos o pendientes<br>Cuando se consulta la trazabilidad<br>Entonces el sistema identifica los elementos faltantes o pendientes de revisión. | EP03 |
| US-18 | Visualizar alertas operativas | Como gestor, deseo visualizar alertas operativas para actuar rápidamente ante riesgos o inconsistencias. | **Escenario 01: alertas activas**<br>Dado que existen anomalías o incidencias relevantes<br>Cuando el gestor consulta el panel operativo<br>Entonces el sistema muestra las alertas activas priorizadas por severidad.<br><br>**Escenario 02: sin alertas**<br>Dado que no existen alertas activas<br>Cuando el gestor consulta el panel<br>Entonces el sistema informa el estado normal de la operación. | EP04 |
| US-19 | Consultar indicadores de confiabilidad | Como gestor, deseo consultar indicadores de confiabilidad de datos para evaluar la calidad del registro operativo. | **Escenario 01: indicadores disponibles**<br>Dado que existen servicios procesados en un periodo<br>Cuando el gestor consulta los indicadores<br>Entonces el sistema muestra métricas de validación, observaciones y registros en contingencia.<br><br>**Escenario 02: filtro temporal**<br>Dado que el gestor define un rango de fechas<br>Cuando se procesa la consulta<br>Entonces el sistema recalcula los indicadores para el periodo solicitado. | EP04 |
| US-20 | Generar reporte de servicios validados | Como gestor, deseo generar reportes de servicios validados para sustentar decisiones y auditorías internas. | **Escenario 01: generación de reporte**<br>Dado que existen datos validados en un periodo determinado<br>Cuando el gestor solicita un reporte<br>Entonces el sistema genera el consolidado correspondiente.<br><br>**Escenario 02: ausencia de datos**<br>Dado que no existen registros en el periodo solicitado<br>Cuando el gestor genera el reporte<br>Entonces el sistema informa que no hay información disponible. | EP04 |
| US-21 | Comparar desempeño por unidad y conductor | Como gestor, deseo comparar el desempeño por unidad y conductor para identificar patrones operativos y oportunidades de mejora. | **Escenario 01: comparación disponible**<br>Dado que existen registros suficientes de operación<br>Cuando el gestor consulta la comparación por periodo<br>Entonces el sistema muestra métricas comparativas entre unidades y conductores.<br><br>**Escenario 02: datos insuficientes**<br>Dado que no existen registros suficientes para la comparación<br>Cuando se solicita el análisis<br>Entonces el sistema informa la insuficiencia de datos. | EP04 |
| US-22 | Consultar propuesta de valor del producto | Como visitante, deseo conocer la propuesta de valor del producto para evaluar si se adapta a mi operación logística. | **Escenario 01: acceso a contenido principal**<br>Dado que el visitante accede al sitio web<br>Cuando consulta la información del producto<br>Entonces el sistema presenta el problema que resuelve, beneficios y diferenciadores de la solución.<br><br>**Escenario 02: navegación por secciones**<br>Dado que el visitante desea mayor detalle<br>Cuando accede a secciones informativas del sitio<br>Entonces el sistema presenta contenido coherente para cada segmento objetivo. | EP-LP |
| US-23 | Consultar funcionalidades clave | Como visitante del segmento logístico, deseo consultar las funcionalidades clave del producto para comprender cómo mejora la trazabilidad y validación operativa. | **Escenario 01: consulta de funcionalidades**<br>Dado que el visitante accede a la sección de funcionalidades<br>Cuando revisa la información disponible<br>Entonces el sistema presenta capacidades como captura visual, validación automática, operación offline y reportes.<br><br>**Escenario 02: contenido segmentado**<br>Dado que el visitante pertenece a un segmento específico<br>Cuando consulta casos de uso o beneficios<br>Entonces el sistema presenta contenido alineado a su contexto. | EP-LP |
| US-24 | Solicitar demostración comercial | Como visitante, deseo solicitar una demostración para conocer la solución aplicada a mi operación. | **Escenario 01: solicitud exitosa**<br>Dado que el visitante registra datos válidos de contacto<br>Cuando envía la solicitud de demostración<br>Entonces el sistema confirma la recepción de la solicitud.<br><br>**Escenario 02: datos inválidos**<br>Dado que faltan datos obligatorios en la solicitud<br>Cuando el sistema procesa el formulario<br>Entonces el sistema informa los errores detectados. | EP-LP |
| US-25 | Consultar evidencia de resultados y casos de uso | Como visitante, deseo consultar casos de uso y resultados esperados para confiar en la propuesta de la solución. | **Escenario 01: revisión de casos de uso**<br>Dado que el visitante accede a la sección correspondiente<br>Cuando consulta la información disponible<br>Entonces el sistema presenta escenarios de uso, beneficios y resultados esperados.<br><br>**Escenario 02: navegación temática**<br>Dado que el visitante busca un problema específico<br>Cuando explora el contenido del sitio<br>Entonces el sistema presenta información agrupada por necesidad o segmento. | EP-LP |
| US-26 | Contactar al equipo comercial | Como visitante, deseo contactar al equipo comercial para resolver dudas sobre adopción, integración o precios. | **Escenario 01: envío exitoso**<br>Dado que el visitante completa la información requerida<br>Cuando envía su consulta<br>Entonces el sistema registra el mensaje y confirma su recepción.<br><br>**Escenario 02: validación de campos**<br>Dado que el visitante omite información obligatoria<br>Cuando intenta enviar la consulta<br>Entonces el sistema informa los campos pendientes. | EP-LP |
| TS-01 | Autenticación y autorización API | Como Developer, deseo implementar autenticación y autorización seguras para proteger el acceso a los servicios de la plataforma. | **Escenario 01: autenticación válida**<br>Dado que se envían credenciales válidas a la API<br>Cuando el servicio procesa la solicitud<br>Entonces el sistema retorna un token de acceso y el estado correspondiente de éxito.<br><br>**Escenario 02: autenticación fallida**<br>Dado que las credenciales son inválidas<br>Cuando la API procesa la solicitud<br>Entonces el sistema retorna un error de autenticación.<br><br>**Escenario 03: acceso no autorizado**<br>Dado que el token no posee permisos suficientes para el recurso solicitado<br>Cuando se intenta acceder al endpoint<br>Entonces el sistema retorna una respuesta de acceso denegado. | EP-API |
| TS-02 | Gestión de servicios vía API | Como Developer, deseo consumir endpoints para registrar, consultar y actualizar servicios logísticos desde aplicaciones externas. | **Escenario 01: consulta de servicios**<br>Dado que existe una solicitud autorizada<br>Cuando se consulta el endpoint de servicios<br>Entonces la API retorna la información solicitada.<br><br>**Escenario 02: creación de servicio**<br>Dado que se envían datos válidos del servicio<br>Cuando la API procesa la solicitud<br>Entonces el sistema registra el servicio y retorna el identificador creado.<br><br>**Escenario 03: datos inválidos**<br>Dado que la solicitud contiene datos inconsistentes<br>Cuando la API valida la entrada<br>Entonces el sistema retorna una respuesta de error. | EP-API |
| TS-03 | Captura y validación de evidencias vía API | Como Developer, deseo consumir endpoints para cargar evidencias y consultar su estado de validación desde aplicaciones cliente. | **Escenario 01: carga exitosa de evidencia**<br>Dado que se envía una evidencia válida con metadatos requeridos<br>Cuando la API procesa la solicitud<br>Entonces el sistema almacena la evidencia y retorna su estado inicial.<br><br>**Escenario 02: consulta de validación**<br>Dado que la evidencia ya fue procesada<br>Cuando se consulta su estado<br>Entonces la API retorna el resultado de validación correspondiente.<br><br>**Escenario 03: evidencia inválida**<br>Dado que el archivo o metadato incumple las reglas del servicio<br>Cuando la API procesa la solicitud<br>Entonces el sistema retorna un error de validación. | EP-API |
| TS-04 | Gestión de incidencias y alertas vía API | Como Developer, deseo consumir endpoints para registrar incidencias y consultar alertas operativas integradas. | **Escenario 01: registro de incidencia**<br>Dado que se envían datos válidos de una incidencia<br>Cuando la API procesa la solicitud<br>Entonces el sistema registra el caso y retorna su identificador.<br><br>**Escenario 02: consulta de alertas**<br>Dado que existen alertas generadas por la operación<br>Cuando se consulta el endpoint correspondiente<br>Entonces la API retorna las alertas con su severidad y estado.<br><br>**Escenario 03: cierre de incidencia**<br>Dado que una incidencia contiene la información mínima de resolución<br>Cuando se envía la actualización<br>Entonces la API cambia el estado del caso a resuelto. | EP-API |
| TS-05 | Reportes e indicadores vía API | Como Developer, deseo consumir endpoints de indicadores y reportes para integrarlos con dashboards y servicios externos. | **Escenario 01: consulta de indicadores**<br>Dado que se envía una solicitud autorizada con filtros válidos<br>Cuando la API procesa la consulta<br>Entonces el sistema retorna métricas agregadas del periodo solicitado.<br><br>**Escenario 02: generación de reporte**<br>Dado que existen datos para el periodo requerido<br>Cuando se solicita un reporte<br>Entonces la API retorna el recurso generado o su referencia de descarga.<br><br>**Escenario 03: parámetros inválidos**<br>Dado que la solicitud contiene filtros inconsistentes<br>Cuando la API valida los parámetros<br>Entonces el sistema retorna un error. | EP-API |
| US-27 | Registrar evidencias sin conexión | Como conductor, deseo registrar evidencias y eventos sin conexión para continuar mi trabajo en zonas con cobertura limitada. | **Escenario 01: registro offline**<br>Dado que el dispositivo no cuenta con conectividad<br>Cuando el conductor registra una evidencia o evento<br>Entonces el sistema almacena la información localmente con estado pendiente de sincronización.<br><br>**Escenario 02: consulta de pendientes**<br>Dado que existen registros almacenados localmente<br>Cuando el conductor revisa el estado de sus registros<br>Entonces el sistema identifica cuáles permanecen pendientes de sincronizar. | EP06 |
| US-28 | Sincronizar registros pendientes | Como conductor, deseo sincronizar automáticamente mis registros pendientes cuando la conectividad se restablece para conservar la continuidad operativa. | **Escenario 01: sincronización exitosa**<br>Dado que existen registros pendientes y la conectividad se restablece<br>Cuando el sistema ejecuta la sincronización<br>Entonces el sistema envía los datos pendientes y actualiza su estado a sincronizado.<br><br>**Escenario 02: conflicto de sincronización**<br>Dado que ocurre un error durante el envío de un registro pendiente<br>Cuando el sistema procesa la sincronización<br>Entonces el sistema conserva el registro, informa el estado fallido y permite reintento. | EP06 |
| US-29 | Consultar estado de validación y sincronización | Como conductor, deseo consultar el estado de mis registros para saber si fueron guardados, sincronizados o observados. | **Escenario 01: estado visible del registro**<br>Dado que el conductor ha realizado registros durante el servicio<br>Cuando consulta el detalle de sus evidencias y eventos<br>Entonces el sistema muestra el estado de cada registro.<br><br>**Escenario 02: registro observado**<br>Dado que un registro fue marcado con observación o error<br>Cuando el conductor revisa su estado<br>Entonces el sistema identifica el motivo y mantiene la trazabilidad correspondiente. | EP06 |

### 3.3. Impact Mapping
En esta sección se presenta el Impact Mapping del sistema, el cual permite establecer la relación entre los objetivos de negocio, los actores involucrados, los cambios de comportamiento esperados y las funcionalidades necesarias para alcanzarlos.

El proceso de elaboración se basó en los User Personas previamente definidos, identificando cómo cada uno contribuye al logro de los objetivos del negocio. A partir de ello, se definieron los impactos deseados en su comportamiento, los entregables que permiten generar dichos impactos y las User Stories que materializan estas funcionalidades.

El Impact Mapping permite alinear el desarrollo del producto con los objetivos estratégicos, asegurando que cada funcionalidad aporte valor real al negocio y responda a las necesidades identificadas en el análisis previo.

#### Segmento 1: Gestión de Operaciones Logísticas
![To-Be Scenario Mapping - Gestor](assets/tb1/impactmap1.png)

#### Segmento 2: Conductores de Transporte
![To-Be Scenario Mapping - Conductor](assets/tb1/impactmap2.png)

### 3.4. Product Backlog
En esta sección se presenta el Product Backlog priorizado del proyecto. El orden de las historias responde al valor que aportan al negocio y al producto, priorizando primero aquellas que permiten comunicar la propuesta de valor, captar interés comercial y validar tempranamente el núcleo funcional de la solución.  

Asimismo, el backlog incorpora historias orientadas a la operación en campo, validación automática, trazabilidad y análisis operativo, junto con las historias técnicas necesarias para soportar la interoperabilidad y el funcionamiento integral de la plataforma.

| # Orden | User Story ID | Título | Descripción | Story Points (1/2/3/5/8) |
|---------|---------------|--------|-------------|--------------------------|
| 1 | US-22 | Consultar propuesta de valor del producto | Como visitante, deseo conocer la propuesta de valor del producto para evaluar si se adapta a mi operación logística. | 3 |
| 2 | US-24 | Solicitar demostración comercial | Como visitante, deseo solicitar una demostración para conocer la solución aplicada a mi operación. | 5 |
| 3 | US-23 | Consultar funcionalidades clave | Como visitante del segmento logístico, deseo consultar las funcionalidades clave del producto para comprender cómo mejora la trazabilidad y validación operativa. | 3 |
| 4 | US-26 | Contactar al equipo comercial | Como visitante, deseo contactar al equipo comercial para resolver dudas sobre adopción, integración o precios. | 2 |
| 5 | US-25 | Consultar evidencia de resultados y casos de uso | Como visitante, deseo consultar casos de uso y resultados esperados para confiar en la propuesta de la solución. | 3 |
| 6 | US-03 | Consultar servicios asignados del día | Como conductor, deseo consultar mis servicios asignados del día para planificar mi jornada. | 5 |
| 7 | US-04 | Registrar inicio de servicio | Como conductor, deseo registrar el inicio de un servicio para dejar constancia del momento de salida. | 3 |
| 8 | US-06 | Capturar evidencia de odómetro | Como conductor, deseo capturar una imagen del odómetro para registrar el kilometraje sin ingresarlo manualmente. | 5 |
| 9 | US-10 | Registrar captura guiada de evidencia | Como conductor, deseo recibir validaciones básicas al momento de capturar una evidencia para evitar registros inválidos. | 3 |
| 10 | US-27 | Registrar evidencias sin conexión | Como conductor, deseo registrar evidencias y eventos sin conexión para continuar mi trabajo en zonas con cobertura limitada. | 8 |
| 11 | US-28 | Sincronizar registros pendientes | Como conductor, deseo sincronizar automáticamente mis registros pendientes cuando la conectividad se restablece para conservar la continuidad operativa. | 5 |
| 12 | US-29 | Consultar estado de validación y sincronización | Como conductor, deseo consultar el estado de mis registros para saber si fueron guardados, sincronizados o observados. | 3 |
| 13 | US-11 | Registrar datos manuales de contingencia | Como conductor, deseo registrar datos manuales como contingencia cuando una evidencia no puede ser validada automáticamente para no detener la operación. | 3 |
| 14 | US-13 | Reportar incidencia operativa | Como conductor, deseo reportar incidencias durante un servicio para dejar constancia de eventos que afectan la operación. | 3 |
| 15 | US-14 | Registrar paradas no planificadas | Como conductor, deseo registrar paradas no planificadas para respaldar retrasos o desvíos ocurridos en ruta. | 5 |
| 16 | US-01 | Consultar servicios programados | Como gestor, deseo consultar los servicios logísticos programados para supervisar la operación diaria. | 5 |
| 17 | US-02 | Asignar conductor y unidad a servicio | Como gestor, deseo asignar un conductor y una unidad a un servicio para organizar su ejecución. | 5 |
| 18 | US-07 | Extraer kilometraje automáticamente | Como gestor, deseo que el sistema extraiga automáticamente el kilometraje desde la evidencia visual para reducir errores humanos. | 8 |
| 19 | US-08 | Validar evidencia de entrega | Como gestor, deseo que el sistema valide automáticamente la evidencia de entrega para contar con respaldo verificable del servicio. | 8 |
| 20 | US-09 | Validar comprobante de combustible | Como gestor, deseo validar automáticamente comprobantes de combustible para detectar inconsistencias operativas. | 8 |
| 21 | US-12 | Detectar anomalías operativas | Como gestor, deseo que el sistema detecte anomalías en kilometraje, combustible o evidencias para intervenir oportunamente. | 8 |
| 22 | US-15 | Consultar incidencias y observaciones | Como gestor, deseo consultar incidencias y observaciones operativas para priorizar acciones correctivas. | 5 |
| 23 | US-17 | Consultar trazabilidad completa del servicio | Como gestor, deseo consultar la trazabilidad completa de un servicio para auditar su ejecución con evidencias y eventos. | 8 |
| 24 | US-18 | Visualizar alertas operativas | Como gestor, deseo visualizar alertas operativas para actuar rápidamente ante riesgos o inconsistencias. | 5 |
| 25 | US-16 | Resolver incidencia con trazabilidad | Como gestor, deseo registrar la resolución de una incidencia para mantener un historial auditable del caso. | 3 |
| 26 | US-19 | Consultar indicadores de confiabilidad | Como gestor, deseo consultar indicadores de confiabilidad de datos para evaluar la calidad del registro operativo. | 5 |
| 27 | US-20 | Generar reporte de servicios validados | Como gestor, deseo generar reportes de servicios validados para sustentar decisiones y auditorías internas. | 5 |
| 28 | US-21 | Comparar desempeño por unidad y conductor | Como gestor, deseo comparar el desempeño por unidad y conductor para identificar patrones operativos y oportunidades de mejora. | 5 |
| 29 | US-05 | Consultar historial de servicios | Como gestor, deseo consultar el historial de servicios ejecutados para revisar el desempeño operativo. | 3 |
| 30 | TS-02 | Gestión de servicios vía API | Como Developer, deseo consumir endpoints para registrar, consultar y actualizar servicios logísticos desde aplicaciones externas. | 5 |
| 31 | TS-03 | Captura y validación de evidencias vía API | Como Developer, deseo consumir endpoints para cargar evidencias y consultar su estado de validación desde aplicaciones cliente. | 8 |
| 32 | TS-04 | Gestión de incidencias y alertas vía API | Como Developer, deseo consumir endpoints para registrar incidencias y consultar alertas operativas integradas. | 5 |
| 33 | TS-05 | Reportes e indicadores vía API | Como Developer, deseo consumir endpoints de indicadores y reportes para integrarlos con dashboards y servicios externos. | 5 |
| 34 | TS-01 | Autenticación y autorización API | Como Developer, deseo implementar autenticación y autorización seguras para proteger el acceso a los servicios de la plataforma. | 5 |

A continuación, se presenta el enlace al tablero de Trello donde se puede visualizar el Product Backlog de manera interactiva:

[Product Backlog en Trello](https://trello.com/invite/b/65483fffcafdad61c4da7629/ATTI3fc72917563f03e2b9eb1a1fd770af39A7368F5C/cobox)


## Capítulo IV: Strategic-Level Software Design

### 4.1. Strategic-Level Attribute-Driven Design
#### 4.1.1. Design Purpose
El objetivo supremo del diseño arquitectónico de **CoBox** es definir un entramado técnico descentralizado y resiliente que traduzca las exigencias del ecosistema logístico en componentes de software escalables. Este enfoque integra paradigmas emergentes con las severas limitaciones del trabajo de campo, tales como conectividad intermitente, restricciones de hardware y condiciones operativas adversas.

Para asegurar que la arquitectura soporte la eficiencia, seguridad y operatividad ininterrumpida, el propósito de diseño se estructura bajo los siguientes lineamientos fundamentales:<br>
**1. Operatividad Descentralizada mediante Inteligencia en el Borde (Edge AI)** 
Transformar la captura de datos en un proceso autónomo que no dependa de la conectividad constante a internet, resolviendo así las restricciones de las zonas rurales y las limitaciones del hardware móvil (Restricciones C-1, C-7 y C-9)
. El diseño estipula la migración del cómputo analítico directamente a los smartphones mediante Modelos de Lenguaje Pequeños (SLMs) y Modelos de Visión-Lenguaje Multimodales (como NaViT)
. Esto permite ejecutar tareas complejas —como la extracción óptica (OCR) de odómetros y validación de guías físicas— de manera estrictamente local, garantizando tiempos de respuesta inferiores a los 50 milisegundos y optimizando el consumo energético durante la conducción.<br><br>
**2. Prevención de Fraudes y Resiliencia Estructural con Multi-Nube y Blockchain** Satisfacer los drivers críticos de disponibilidad operativa y protección de información sensible. Para mitigar bloqueos de proveedores y latencias de red, la plataforma orquesta cargas de trabajo distribuidas simultáneamente entre Amazon Web Services (AWS) y Google Cloud Platform (GCP) apoyándose en enrutamiento simétrico
. Paralelamente, para erradicar las discrepancias manuales y cumplir con las normativas legales de trazabilidad documental (Restricción C-5), la arquitectura entrelaza redes neuronales con tecnología Blockchain, creando libros mayores inmutables que certifican la autenticidad de cada entrega o carga de combustible mediante evidencias fotográficas blindadas criptográficamente.<br><br>
.
**3. Modelado de Dominio (DDD) y Aislamiento de Funcionalidades Asegurar la coherencia y evolución del código fuente aplicando el Diseño Guiado por el Dominio (DDD).** El ecosistema se segmenta lógicamente en contextos autónomos (Manejo de Flota, Entregas, Incidencias, Mantenimiento y Analítica), los cuales se materializan como microservicios hexagonales independientes
. Para sortear los cuellos de botella de la comunicación síncrona, estos módulos interactúan a través de un bus de eventos (RabbitMQ)
. Asimismo, toda solicitud externa atraviesa un API Gateway centralizado que enruta el tráfico y aplica políticas de Control de Acceso Basado en Roles (RBAC), garantizando la privacidad de los datos según las leyes peruanas (Restricción C-8).<br><br>
.
**4. Validación Empírica Continua guiada por el Proceso ADD v3 Gobernar la evolución del sistema a través del método de Diseño Guiado por Atributos (ADD v3)**
 Las decisiones arquitectónicas y los límites de cada microservicio se modelan de manera exhaustiva empleando vistas formales de C4 y diagramas UML
. Para validar que estas decisiones cumplan con los escenarios de calidad exigidos (e.g., tolerancia a fallos, soporte para concurrencia masiva), el diseño impone una observabilidad integral mediante telemetría avanzada (Prometheus y Grafana), permitiendo adaptar la solución dinámicamente frente a las variaciones del entorno logístico sin interrumpir las operaciones en curso.<br><br>
#### 4.1.2. Attribute-Driven Design Inputs
#### 4.1.2.1. Primary Functionality (Primary User Stories)

##### 1. Inteligencia en el Borde (Edge AI) para la Extracción Automática Al analizar las historias US-07 (Extraer kilometraje automáticamente) y US-08 (Validar evidencia de entrega)
 El diseño descarta el procesamiento en la nube tradicional. Para evitar que la aplicación dependa de la red y colapse en zonas rurales, apliqué Inteligencia en el Borde. Esto significa que el procesamiento de visión artificial (OCR) se ejecuta localmente en el hardware del dispositivo móvil del transportista mediante Modelos de Lenguaje Pequeños (SLMs), permitiendo validar el kilometraje y las guías de remisión en milisegundos y con cero consumo de datos.
 
##### 2. Arquitectura Orientada a Eventos (Offline-First) Las funcionalidades de US-27 (Registrar evidencias sin conexión) y US-28 (Sincronizar registros pendientes)
 Exigían resolver la intermitencia de conectividad de la infraestructura de telecomunicaciones (Épica 06). Para ello, apliqué un paradigma de persistencia local descentralizada con sincronización asíncrona. El teléfono móvil actúa como un nodo autónomo; cuando no hay señal, guarda los metadatos y, al detectar red, orquesta automáticamente la transmisión de los paquetes retenidos a través de colas de mensajes distribuidas (Event-Driven), garantizando cero pérdida de información.

##### 3. Blockchain para Trazabilidad y No Repudio La auditoría operativa es estricta, lo que se refleja en la historia US-17 (Consultar trazabilidad completa del servicio). 
Para blindar cronológicamente eventos como asignación, inicio, validaciones e incidencias, apliqué la integración de bases de datos con libros mayores inmutables (Blockchain). Cada evidencia validada por la IA genera una firma criptográfica, haciendo que los registros sean a prueba de manipulaciones o fraudes, cumpliendo con las normativas legales de protección documental del sector transporte.
##### 4. Redes de Confianza Cero (Zero-Trust) y API Gateway Para el requisito TS-01 (Autenticación y autorización API)
Que permite el acceso a sistemas de terceros, el diseño perimetral se fundamentó en una arquitectura API-First bajo el modelo de Zero-Trust. Esto implementa pasarelas de seguridad (API Gateways) que exigen la validación estricta de tokens de acceso e identidades para cualquier solicitud que intente interactuar con el backend de la plataforma, denegando el acceso de forma determinista ante permisos insuficientes.
De esta forma, la selección de funcionalidades primarias (Primary User Stories) queda fusionada orgánicamente con los patrones de Edge Computing, Blockchain y sistemas distribuidos, dándole a CoBox el rigor de una arquitectura moderna, resiliente y de alta disponibilidad.

##### 4.1.2.2. Quality Attribute Scenarios


A continuación, se definen los escenarios de atributos de calidad (Quality Attribute Scenarios) priorizados para la plataforma **CoBox**, los cuales actuarán como drivers arquitectónicos clave para la toma de decisiones del sistema, alineando las necesidades operativas de la logística con capacidades de Edge AI.





| ID    | Atributo                      | Fuente                   | Estímulo                                      | Artefacto                          | Entorno                                      | Respuesta                                                                 | Medida                                             |
|-------|------------------------------|--------------------------|-----------------------------------------------|------------------------------------|----------------------------------------------|---------------------------------------------------------------------------|----------------------------------------------------|
| QA-01 | Disponibilidad / Resiliencia | Usuario (Conductor)      | Registro de evidencias sin conectividad       | Módulo Offline y Sincronización    | Operación en campo sin red                   | Almacena datos localmente y sincroniza al recuperar conexión              | 100% sincronización sin pérdida de datos           |
| QA-02 | Rendimiento (Performance)    | Gestor / Sistema         | Procesamiento de imagen (odómetro)            | Módulo Edge AI / OCR               | Ejecución en tiempo real en dispositivo      | Extrae kilometraje automáticamente y lo valida                            | Procesamiento < 2 segundos                         |
| QA-03 | Seguridad / Integridad       | Developer / App Externa  | Acceso a servicios de trazabilidad            | API Gateway + Autenticación        | Consumo de APIs por terceros                 | Valida credenciales y retorna token o acceso denegado                     | 0 accesos no autorizados; latencia < 1 s           |
| QA-04 | Interoperabilidad            | Sistema / Developer      | Solicitud externa de datos/logística          | API RESTful                        | Integración con sistemas externos (ERP)      | Procesa solicitudes en JSON y responde con datos o errores estructurados  | 100% solicitudes válidas atendidas                 |
| QA-05 | Usabilidad                   | Usuario (Conductor)      | Captura de imagen de evidencia                | Interfaz móvil (captura guiada)    | Uso en campo con presión operativa           | Valida calidad de imagen y solicita repetición si es necesario             | 90% éxito en el primer intento                     |
| QA-06 | Escalabilidad                | Múltiples Conductores    | Pico de envíos concurrentes                   | Backend asíncrono / clústeres      | Reconexiones masivas o cierre de turnos      | Procesa solicitudes concurrentes sin colapsar                             | Soporta hasta 3x usuarios sin latencia > 3 s       |

 Descripción Detallada de Escenarios

 QA-01: Disponibilidad / Resiliencia
El sistema garantiza operación offline, permitiendo capturar evidencias sin conexión. Los datos se almacenan localmente y se sincronizan automáticamente al restablecer conectividad, evitando pérdida de información.

 QA-02: Rendimiento (Edge AI)
El procesamiento de imágenes se ejecuta en el dispositivo (Edge AI), extrayendo automáticamente el kilometraje del odómetro en tiempo real, reduciendo latencia y errores humanos.

 QA-03: Seguridad / Integridad
El API Gateway controla el acceso mediante autenticación estricta. Solo solicitudes con credenciales válidas reciben acceso, bloqueando cualquier intento no autorizado.

 QA-04: Interoperabilidad
La API REST permite integración con sistemas externos (ERP, dashboards), procesando solicitudes en formato JSON y asegurando compatibilidad y manejo de errores.

 QA-05: Usabilidad
La app guía al usuario en la captura de evidencias, validando la calidad de imágenes en tiempo real y reduciendo errores operativos.

QA-06: Escalabilidad
El sistema maneja picos de carga mediante procesamiento asíncrono, soportando múltiples usuarios concurrentes sin degradación significativa del rendimiento.




##### 4.1.2.3. Constraints



A continuación, se presenta la reestructuración de las restricciones (constraints) del sistema, fundamentadas en paradigmas arquitectónicos modernos, redes distribuidas e Inteligencia Artificial descentralizada.


| ID   | Restricción Evolucionada (Constraint) | Justificación Científica / Tecnológica |
|------|--------------------------------------|----------------------------------------|
| **C-1** | **Autonomía Operativa Descentralizada (Edge Intelligence)** | El ecosistema debe ejecutar validaciones analíticas in situ sin depender de la nube. El uso de Modelos de Lenguaje Pequeños (SLMs) y arquitecturas multimodales (ej. OCR avanzado) permite procesar datos con latencias < 50 ms, operando como nodo autónomo. |
| **C-2** | **Eficiencia Financiera mediante Optimización Multi-Nube** | La orquestación con contenedores (Kubernetes) permite balancear cargas entre instancias spot y bajo demanda (AWS, GCP), evitando vendor lock-in y optimizando costos. |
| **C-3** | **Fusión de Sensores y Nodos Edge 6G** | La combinación de sensores y network slicing en 5G/6G permite decisiones en tiempo real sin depender de APIs externas, reduciendo vulnerabilidad y latencia. |
| **C-4** | **Interfaces Multimodales y NLP** | Modelos generativos transforman lenguaje natural en operaciones automatizadas, reduciendo fricción y facilitando adopción por usuarios con baja alfabetización digital. |
| **C-5** | **Trazabilidad Inmutable mediante Blockchain-IA** | Registros distribuidos + IA garantizan integridad, auditabilidad y cumplimiento normativo (ej. transporte farmacéutico), reduciendo fraude. |
| **C-6** | **Interoperabilidad Asíncrona (Event-Driven & API Gateway)** | Arquitectura basada en eventos permite integración con sistemas legacy sin afectar rendimiento, asegurando bajo acoplamiento. |
| **C-7** | **Compresión de Modelos ante Restricciones de Hardware** | Técnicas como cuantización (8 bits) y destilación de conocimiento reducen consumo de memoria, energía y calor en dispositivos móviles. |
| **C-8** | **Soberanía de Datos y Zero Trust** | Procesamiento en el edge evita exposición de datos sensibles. La arquitectura Zero Trust reduce riesgos de ciberataques y violaciones de privacidad. |
| **C-9** | **Transmisión Asíncrona de Datos Contenerizados** | Uso de data pipelines con caché local permite sincronización diferida cuando hay conectividad estable, garantizando integridad de datos. |
| **C-10** | **Despliegue Continuo (MLOps) y OTA** | Permite actualizaciones sin detener operaciones mediante despliegues OTA y pruebas A/B, asegurando evolución continua del sistema. |

---

## 4.1.3 Architectural Drivers Backlog

| Driver ID | Título | Descripción | Importancia | Architecture Technical Complexity |
| :--- | :--- | :--- | :--- | :--- |
| **DR-01** | **Disponibilidad (Alta Disponibilidad Multi-Nube)** | Capacidad del sistema logístico para mantener una operatividad ininterrumpida ante fallos de infraestructura, orquestando instancias redundantes en un entorno multi-nube (AWS y GCP). Requiere enrutamiento BGP simétrico y bases de datos distribuidas (ej. CockroachDB) para evitar el bloqueo de proveedores y garantizar el atributo de fiabilidad funcional (ISO 25010). | Alta | Alta |
| **DR-02** | **Rendimiento bajo Conectividad Limitada (Operatividad Offline / Edge AI)** | Capacidad de la aplicación móvil para ejecutar inferencias analíticas complejas in situ con latencias inferiores a 50 milisegundos. Cumpliendo con la eficiencia de desempeño (ISO 25010), el sistema debe procesar visión artificial multimodal (OCR) sin conexión a internet y sincronizar la telemetría asíncronamente mediante firmas criptográficas locales al recuperar la cobertura. | Alta | Alta |
| **DR-03** | **Seguridad y No Repudio (Trazabilidad inmutable)** | Grado en el que la plataforma mitiga la manipulación de datos sensibles (kilometraje, evidencias fotográficas) para cumplir con normativas estrictas del sector transporte. Exige la integración de redes neuronales con registros inmutables basados en Blockchain, asegurando la autenticidad, integridad y el no repudio de la información procesada (ISO 25010). | Alta | Alta |
| **DR-04** | **Mantenibilidad (Aislamiento Estructural y Modularidad)** | Capacidad del ecosistema para evolucionar sin disrupciones operativas, fundamentado en la mantenibilidad y modificabilidad (ISO 25010). Impone la partición estricta de la arquitectura bajo el paradigma de Diseño Guiado por el Dominio (DDD), aislando las lógicas de negocio en microservicios independientes (Contextos Delimitados) que interactúan asíncronamente mediante *message brokers* (ej. RabbitMQ). | Alta | Media |
| **DR-05** | **Interoperabilidad (Integración B2B y API-First)** | Capacidad técnica del sistema para intercambiar datos de manera eficiente con infraestructuras heredadas de clientes (sistemas ERP) y proveedores logísticos externos. Se sustenta en el estándar de compatibilidad e interoperabilidad (ISO 25010), requiriendo un patrón de *API Gateway* centralizado que enrute solicitudes, aplique límites de tasa (*rate limiting*) y estandarice contratos JSON/REST. | Media | Media |
| **DR-06** | **Observabilidad (Telemetría Distribuida y Analizabilidad)** | Atributo que permite el diagnóstico y monitoreo proactivo del estado interno de los microservicios en la topología multi-nube. Para garantizar la analizabilidad (ISO 25010), exige la inserción de agentes de telemetría (Prometheus, Grafana) para la recolección empírica de métricas de concurrencia, latencia y uso de recursos, facilitando la resolución de incidentes en tiempo real. | Alta | Media |
| **DR-07** | **Escalabilidad (Elasticidad Computacional)** | Capacidad de la arquitectura para absorber incrementos abruptos de carga transaccional o expansión en el volumen de la flota sin degradar los tiempos de respuesta. Implica la contenerización de las cargas de trabajo e implementación de autoescalado basado en orquestación, asegurando la resiliencia en la asignación dinámica de recursos de cómputo (ISO 25010). | Alta | Alta |
#### 4.1.4. Architectural Design Decisions
| Driver ID | Título                                    | Decisión Arquitectónica                       | Pros                                                                                                                                                                | Contras                                                                                                                                                                   |
| --------- | ----------------------------------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **AD-01** | Procesamiento Offline / Baja conectividad | **Edge AI (Procesamiento en el dispositivo)** | - Latencia mínima (milisegundos).<br>- No depende de conexión a internet.<br>- Reduce carga del backend.<br>- Alta disponibilidad en campo.                         | - Mayor complejidad (MLOps, optimización de modelos).<br>- Requiere hardware móvil con capacidad (NPU).<br>- Mayor consumo energético en dispositivos.                    |
| **AD-02** | Disponibilidad / Resiliencia              | **Arquitectura Event-Driven (Offline-First)** | - Sistema no se bloquea sin red.<br>- Persistencia local garantiza cero pérdida de datos.<br>- Escala bien ante reconexiones masivas.<br>- Alta disponibilidad.     | - Consistencia eventual (no inmediata).<br>- Alta complejidad (manejo de eventos, conflictos).<br>- Requiere infraestructura de mensajería (RabbitMQ).              |
| **AD-03** | Seguridad / Trazabilidad                  | **Blockchain para registros inmutables**      | - Integridad de datos garantizada.<br>- Previene fraude y manipulación.<br>- Trazabilidad completa (no repudio).                                                    | - Alta latencia en transacciones.<br>- Costos elevados de infraestructura.<br>- Escalabilidad limitada (crecimiento del ledger).<br>- Alta complejidad (smart contracts). |
| **AD-04** | Seguridad / Control de acceso             | **Zero-Trust + API Gateway**                  | - Seguridad perimetral robusta.<br>- Validación estricta de identidad (JWT).<br>- Control centralizado (RBAC, rate limiting).<br>- Protege contra ataques externos. | - Incremento de latencia (validaciones).<br>- Punto crítico (si el gateway falla, afecta todo).<br>- Complejidad media en configuración.                                  |
| **AD-05** | Escalabilidad / Mantenibilidad            | **Microservicios con DDD (Hexagonal)**        | - Escalabilidad independiente por servicio.<br>- Aislamiento de fallos.<br>- Alta mantenibilidad por bounded contexts.<br>- Flexibilidad tecnológica.               | - Complejidad muy alta (orquestación, comunicación).<br>- Costos mayores de infraestructura.<br>- Consistencia eventual.<br>- Necesidad de patrones distribuidos (Saga).  |


#### 4.1.5. Quality Attribute Scenario Refinements


| ID     | Atributo                     | Fuente                                      | Estímulo                                                                 | Artefacto                                                                 | Entorno                                                                 | Respuesta Refinada                                                                                                                                                                                                                                                                              | Medida Refinada                                                                                                                        |
|--------|-----------------------------|---------------------------------------------|--------------------------------------------------------------------------|--------------------------------------------------------------------------|-------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| QA-01  | Disponibilidad / Resiliencia | Dispositivo móvil del conductor (Nodo Edge) | Caída abrupta de la conexión de red (4G/3G) durante el registro         | Arquitectura Orientada a Eventos (Offline-First con almacenamiento local) | Operación en rutas rurales con conectividad intermitente                | El sistema persiste el evento en almacenamiento local embebido (SQLite/Realm) mediante patrón *Store-and-Forward*. Al restablecer conexión, sincroniza de forma asíncrona mediante un *Message Broker* evitando pérdida de datos.                                                               | Persistencia < 50 ms. Sincronización completa < 5 s. Pérdida de datos = 0%.                                                             |
| QA-02  | Rendimiento (Performance)   | Sistema / Usuario operario                  | Captura y procesamiento de imagen (odómetro o documento)                | Edge AI (Modelos SLM cuantificados)                                      | Dispositivo móvil con recursos limitados                               | El procesamiento se ejecuta localmente en la NPU del dispositivo usando modelos cuantificados (INT8), extrayendo texto sin enviar imágenes completas al backend.                                                                                                                                | Latencia < 150 ms. RAM < 200 MB. Precisión OCR ≥ 95%.                                                                                   |
| QA-03  | Seguridad / Integridad      | Actor malicioso / Usuario externo           | Intento de acceso no autorizado o manipulación de datos                 | Zero-Trust + API Gateway + Blockchain                                    | Redes públicas e integraciones externas                                | El API Gateway valida cada solicitud mediante JWT bajo modelo Zero-Trust. Cada transacción válida genera un hash criptográfico registrado en Blockchain, garantizando inmutabilidad.                                                                                                          | Validación < 50 ms. Integridad de datos garantizada (0% alteración post-registro).                                                     |
| QA-04  | Escalabilidad              | Sistema (Alta concurrencia)                 | Reconexión simultánea de múltiples nodos (flota completa)               | Microservicios + Orquestación (Kubernetes)                               | Pico de carga 3x superior a lo normal                                  | El sistema escala horizontalmente creando nuevas réplicas de microservicios y distribuyendo carga mediante colas de mensajería, evitando saturación del sistema.                                                                                                                               | Escalado < 60 s. Throughput > 5000 TPS. Latencia < 300 ms.                                                                             |
| QA-05  | Consistencia               | Microservicios internos                     | Actualización distribuida de estado de entrega                          | Event-Driven + DDD + Patrón Saga                                         | Sistema distribuido con múltiples contextos                            | El microservicio emite eventos de dominio mediante patrón *Outbox*. Otros servicios consumen eventos y actualizan estado de forma eventual. Se aplican compensaciones en caso de fallos.                                                                                                        | Consistencia eventual < 500 ms (p99). Inconsistencia = 0% con idempotencia y DLQ.                                                      |
| QA-06  | Usabilidad en Campo        | Conductor                                  | Registro de evidencia en condiciones adversas                           | Interfaz móvil + Edge AI                                                 | Campo operativo (fatiga, baja señal, estrés)                           | El sistema valida en tiempo real calidad de captura (iluminación, enfoque) y proporciona retroalimentación inmediata para corrección antes del envío.                                                                                                                                          | Feedback < 50 ms. Reducción de errores de captura < 2%.                                                                                 |

### Justificación de Impacto Arquitectónico

La refinación de los escenarios de atributos de calidad permite transformar requerimientos abstractos en criterios medibles y verificables, alineando directamente los drivers arquitectónicos con el comportamiento real del sistema.

El uso de Edge AI reduce la dependencia de la conectividad, mejorando la disponibilidad y el rendimiento en campo. La arquitectura orientada a eventos permite tolerancia a fallos de red mediante consistencia eventual controlada. La integración de Blockchain garantiza la integridad de la información, mientras que el enfoque Zero-Trust fortalece la seguridad perimetral.

Finalmente, la arquitectura de microservicios permite escalar el sistema de manera independiente según la carga, asumiendo como trade-off una mayor complejidad en la coordinación y consistencia distribuida.

Este enfoque asegura que CoBox no solo sea funcional, sino resiliente, escalable y alineado con las condiciones reales del entorno logístico.

### 4.2. Strategic-Level Domain-Driven Design
#### 4.2.1. EventStorming
![To-Be Scenario Mapping - Conductor](assets/tb1/eventstorming.png)
#### 4.2.2. Candidate Context Discovery

Se aplicó Event Storming para identificar los Bounded Contexts del sistema. El análisis se basó en funcionalidades, procesos y eventos clave del proyecto.

**Técnicas utilizadas**

 **Start-With-Value:**
Gestión operativa de servicios logísticos
Validación automática de evidencias
Gestión de incidencias y trazabilidad
Reportes y analítica operativa

 **Look-For-Pivotal-Events:**
• “Asignación de servicio a conductor”
• “Captura de evidencia (odómetro, entrega, combustible)”
• “Validación automática de datos”
• “Registro de incidencia operativa”
• “Sincronización offline de registros”
• “Generación de reporte validado”

 **Start-With-Simple:**
Los eventos se agruparon por afinidad funcional y coherencia de reglas, delimitando áreas independientes y evitando solapamientos entre procesos.

Finalmente, se delimitaron 5 bounded context:

**Fleet Management Context (Gestión de Flota)**

Descripción:
Este contexto se encarga de la administración completa de las unidades de transporte. Permite registrar vehículos, asignarlos a rutas, actualizar su estado (activo, mantenimiento) y consultar su historial operativo

**Delivery Management Context (Gestión de Entregas)**

Descripción:
Gestiona todo el ciclo de vida de las entregas realizadas por los conductores, incluyendo asignación, ejecución y validación mediante evidencia.<br>

•Incidencias: registro y seguimiento de eventos e incidencias<br>

Evidencias: captura y validación automática de datos operativos<br>



• Reportes: generación y consulta de reportes validados<br>


Cada contexto definido agrupa sus propios eventos, reglas y agregados, facilitando la evolución y el mantenimiento del sistema.

#### 4.2.3. Domain Message Flows Modeling

Se modelaron las interacciones entre los Bounded Contexts identificados en el sistema, con el objetivo de visualizar cómo colaboran para resolver escenarios clave del negocio logístico. El análisis considera comandos, eventos, reglas de negocio, agregados, vistas y la posible integración con sistemas externos.

Para este modelado se utilizó la técnica de Domain Storytelling, que permite representar de manera clara las acciones de los actores principales y los flujos de mensajes entre contextos, facilitando la comprensión de la dinámica operativa del sistema.

Enfoque utilizado:

- Se partió del modelo de Event Storming definido en etapas previas del proyecto.
- Se seleccionaron los casos de uso más relevantes, como la asignación de servicios, registro de evidencias y validación de información operativa.
- Se describieron los flujos considerando:<br>
o Actores: gestores de operaciones y conductores de carga.<br>
o Bounded Contexts: Flotas, Incidentes,mantenimiento , delivery.<br>
o Comandos: asignar servicio, registrar evidencia, reportar incidente.<br>
o Eventos: ServiceAssigned, EvidenceCaptured, EvidenceValidated, IncidentReported, ServiceCompleted.<br>
o Reglas: validación automática de evidencias, control de integridad de datos.<br>
o Vistas: dashboards analíticos para gestores, historial de servicios para conductores.<br>
o Integración: posible conexión con sistemas de gestión existentes y dispositivos móviles.<br>

Resultados:

- Se modelaron flujos representativos que cubren desde la asignación de un servicio hasta la validación y cierre del mismo.
- Se incluyeron los principales Bounded Contexts, reflejando la colaboración entre Gestión de Operaciones, Ejecución en Campo y Validación Automática.
- Se describió el flujo completo: el gestor asigna un servicio, el conductor registra evidencias en campo, el sistema valida automáticamente la información y se actualiza el estado del servicio.
- Se identificaron puntos de integración y transferencia de mensajes entre contextos, asegurando trazabilidad y consistencia de la información.

Este modelado aporta un mejor entendimiento del sistema, reduce el acoplamiento entre contextos y sienta las bases para el diseño de APIs, eventos y la arquitectura evolutiva del producto.

#### 4.2.4. Bounded Context Canvases
#### 4.2.5. Context Mapping
![To-Be Scenario Mapping - Conductor](assets/tb1/mermaidcontext.png)

### 4.3. Software Architecture
#### 4.3.1. Software Architecture System Landscape Diagram
#### 4.3.2. Software Architecture Context Level Diagrams
#### 4.3.3. Software Architecture Container Level Diagrams
#### 4.3.4. Software Architecture Deployment Diagrams
