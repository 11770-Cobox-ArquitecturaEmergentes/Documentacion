<p align="center">
  <strong>UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS</strong>
</p>

<p align="center">
  <img src="./assets/upc-logo.png" alt="UPC Logo" width="200"/>
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

### 1.2.1 Antecedentes y problemática

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

### Objetivos de la solución

- Reducir la dependencia del ingreso manual de datos
- Incrementar la confiabilidad de la información operativa
- Automatizar la validación de evidencias en campo
- Mejorar la trazabilidad de los servicios logísticos

### Restricciones del proyecto

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

#### 2.1.1. Análisis competitivo

#### 2.1.2. Estrategias y tácticas frente a competidores

### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
#### 2.2.2. Registro de entrevistas
#### 2.2.3. Análisis de entrevistas

### 2.3. Needfinding
#### 2.3.1. User Personas
#### 2.3.2. User Task Matrix
#### 2.3.3. Empathy Mapping
#### 2.3.4. As-is Scenario Mapping

### 2.4. Ubiquitous Language

---

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping
### 3.2. User Stories
### 3.3. Impact Mapping
### 3.4. Product Backlog

---

## Capítulo IV: Strategic-Level Software Design

### 4.1. Strategic-Level Attribute-Driven Design
#### 4.1.1. Design Purpose
#### 4.1.2. Attribute-Driven Design Inputs
##### 4.1.2.1. Primary Functionality (Primary User Stories)
##### 4.1.2.2. Quality Attribute Scenarios
##### 4.1.2.3. Constraints
#### 4.1.3. Architectural Drivers Backlog
#### 4.1.4. Architectural Design Decisions
#### 4.1.5. Quality Attribute Scenario Refinements

### 4.2. Strategic-Level Domain-Driven Design
#### 4.2.1. EventStorming
#### 4.2.2. Candidate Context Discovery
#### 4.2.3. Domain Message Flows Modeling
#### 4.2.4. Bounded Context Canvases
#### 4.2.5. Context Mapping

### 4.3. Software Architecture
#### 4.3.1. Software Architecture System Landscape Diagram
#### 4.3.2. Software Architecture Context Level Diagrams
#### 4.3.3. Software Architecture Container Level Diagrams
#### 4.3.4. Software Architecture Deployment Diagrams
