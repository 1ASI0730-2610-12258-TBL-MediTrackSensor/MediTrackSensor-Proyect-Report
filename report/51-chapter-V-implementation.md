# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

A continuación, se describen los productos de software empleados en el desarrollo del proyecto. Esta sección tiene como objetivo facilitar la comprensión y continuidad
del trabajo a los actuales y futuros desarrolladores, asegurando una colaboración efectiva a lo largo del ciclo de vida del producto digital.

**Project Management**
- Trello – https://trello.com/<br>
  Se ha utilizado Trello como herramienta principal de gestión de tareas. Esta plataforma permite visualizar el progreso de cada etapa del proyecto mediante
  tableros personalizables, facilitando la organización de pendientes, tareas en desarrollo y actividades finalizadas. Además, su interfaz intuitiva y accesibilidad
  desde cualquier navegador con una cuenta registrada la convierten en una solución ágil para el seguimiento de proyectos en equipo.

**Requirements Management**
- Google Docs – https://docs.google.com/<br>
  Para la redacción, gestión y revisión de los requisitos del sistema se ha empleado Google Docs. Su funcionalidad de edición colaborativa en tiempo real ha
  permitido que todos los integrantes del equipo puedan aportar, comentar y revisar los documentos desde cualquier dispositivo.

**Product UX/UI Design**
- Figma – https://www.figma.com/<br>
  Figma ha sido fundamental para el diseño de interfaces y la creación de prototipos interactivos. Permite que varios usuarios trabajen simultáneamente en los
  wireframes y mockups, lo que ha facilitado una comunicación más eficiente entre el equipo de diseño y desarrollo.
- Miro https://miro.com/es/<br> 
  Pizarra digital colaborativa utilizada para sesiones de Big Picture EventStorming y Design-Level EventStorming, facilitando la identificación de Bounded Contexts, Events, Commands y Aggregates del dominio.
- LucidChart https://www.lucidchart.com/pages/es <br>
  Aplicación de diagramación colaborativa para la creación de Wireflows, User Flows, diagramas UML (Class Diagrams) y Database Diagrams de la arquitectura del software.


**Software Development**
- Landing Page y Frontend (HTML, CSS, JS) – https://www.jetbrains.com/idea/<br>
  Desarrollada con HTML5, CSS3, JavaScript y Tailwind CSS. El entorno de desarrollo fue IntelliJ IDEA Ultimate por sus herramientas avanzadas de depuración y control de versiones.
- Web Services (.NET Core) – https://www.jetbrains.com/rider/<br>
  Desarrollado en ASP.NET Core con C#, usando JetBrains Rider. Se requiere el SDK de .NET disponible en https://dotnet.microsoft.com/en-us/download.

**Software Documentation**
- Google Docs y GitHub README <br>
  La documentación del software se ha centralizado en Google Docs. El archivo README en GitHub incluye instrucciones de despliegue, estructura del repositorio y
  requerimientos técnicos.
- Markdown https://www.markdownguide.org/ <br>
  Lenguaje de marcado ligero para la elaboración del Project Report en el repositorio GitHub. Permite estructurar documentación con formato consistente y compatible con control de versiones.


**Deployment & Hosting**
- Vercel <br>
  **Descripción**: Plataforma cloud enfocada en el despliegue y hosting de aplicaciones frontend, especialmente optimizada para frameworks modernos como
  Vue.js, React y Next.js. Proporciona CDN global, despliegues automáticos y SSL integrado. <br>
  **Uso**: Se utiliza para desplegar la aplicación web desarrollada con Vue.js. Cada push al repositorio activa automáticamente un pipeline de build y
  deployment, publicando la aplicación en producción con distribución global mediante CDN y certificado HTTPS automático. Además, permite previsualizaciones por rama para validar cambios antes de su integración final. <br>


### 5.1.2. Source Code Management

En esta sección se establece el medio y esquema de organización
que el equipo aplicará para el seguimiento y control de
modificaciones en el código fuente. Para ello se utiliza
**GitHub** como plataforma de control de versiones, organizado
bajo la organización pública **1ASI0730-2610-12258-TBL-MediTrackSensor**.

Se aplica **GitFlow** como workflow de control de versiones,
**Conventional Commits** para los mensajes de commit y
**Semantic Versioning** para el nombramiento de releases.

A continuación se presentan los repositorios correspondientes
a cada producto de la solución:

| Producto                 | Repositorio                                                                                   |
|--------------------------|-----------------------------------------------------------------------------------------------|
| Project Report           | https://github.com/1ASI0730-2610-12258-TBL-MediTrackSensor/MediTrackSensor-Proyect-Report.git |
| Landing Page             | https://github.com/1ASI0730-2610-12258-TBL-MediTrackSensor/MediTrackSensor-Landing-Page.git   |
| Frontend Web Application | https://github.com/1ASI0730-2610-12258-TBL-MediTrackSensor/MediTrackSensor-Frontend.git       |
| Web Services             | https://github.com/1ASI0730-2610-12258-TBL-MediTrackSensor/MediTrackSensor-Backend.git        |

### GitFlow Workflow

El equipo implementa GitFlow como workflow de control de versiones.
Las ramas definidas son las siguientes:

**Ramas principales:**
- `main` — rama principal que contiene la versión estable y desplegada
  del producto. Solo se actualiza mediante merges de ramas release.
- `develop` — rama de integración donde se consolidan las features
  completadas antes de pasar a producción.

**Ramas de soporte:**
- `feature/<nombre>` — una rama por cada funcionalidad o sección
  en desarrollo. Se crean desde `develop` y se fusionan de vuelta a `develop`
  al completarse.
- `release/<version>` — se crean desde `develop` cuando se prepara
  una entrega. Se fusionan a `main` y `develop` al finalizarse.

**Convenciones de nomenclatura para ramas:**

| Tipo | Convención | Ejemplo |
|------|-----------|---------|
| Feature | `feature/<nombre-descriptivo>` | `feature/login-view` |
| Release | `release/<version>` | `release/1.0.0` |

### Conventional Commits

Los mensajes de commit siguen la especificación de Conventional Commits
con la siguiente estructura:

`<type>(<scope>): <description>`

Los tipos permitidos son:

| Tipo | Uso |
|------|-----|
| `feat` | Nueva funcionalidad |
| `fix` | Corrección de errores |
| `docs` | Cambios en documentación |
| `style` | Cambios de formato sin afectar lógica |
| `refactor` | Refactorización de código |
| `test` | Añadir o modificar pruebas |
| `chore` | Tareas de mantenimiento |

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration

---

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

En este Sprint se desarrolló e implementó la primera versión
del Landing Page de MediTrack Sensor, incluyendo su despliegue
en un entorno accesible públicamente.

#### 5.2.1.1. Sprint Planning 1

A continuación se presenta el resumen del Sprint Planning Meeting
realizado para el Sprint 1.

| Sprint # | Sprint 1                                                                                                                                                                                                                                                                                                                             |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Sprint Planning Background** |                                                                                                                                                                                                                                                                                                                                      |
| Date | 2026-04-15                                                                                                                                                                                                                                                                                                                           |
| Time | 04:30 PM                                                                                                                                                                                                                                                                                                                             |
| Location | Reunión virtual vía Google Meet                                                                                                                                                                                                                                                                                                      |
| Prepared By | Rioja Nuñez, Franco Diego                                                                                                                                                                                                                                                                                                            |
| Attendees | Herrera Enriquez, Diego Fernando / Mallqui Vilca, Dhilsen Armil / Rioja Nuñez, Franco Diego / Tufiño Argüelles, Luis Angel / Urviola Condori, Mateo Sebastián                                                                                                                                                                        |
| **Sprint Goal & User Stories** |                                                                                                                                                                                                                                                                                                                                      |
| Sprint 1 Goal | Our focus is on establishing the project foundation and delivering the first version of the Landing Page. We believe it delivers a clear understanding of MediTrack Sensor's value proposition to potential visitors. This will be confirmed when the Landing Page is publicly deployed and covers content for both target segments. |
| Sprint 1 Velocity | 21                                                                                                                                                                                                                                                                                                                                   |
| Sum of Story Points | 21                                                                                                                                                                                                                                                                                                                                   |

#### 5.2.1.2. Aspect Leaders and Collaborators

En esta sección se detalla la matriz de liderazgo y colaboración (LACX) para el Sprint 1. Cada aspecto representa una fase crítica de la entrega, donde se designa un líder (L) responsable de la dirección del entregable y colaboradores (C) que apoyaron en su ejecución, cumpliendo con el objetivo de proporcionar liderazgo conjunto y un entorno colaborativo (ABET Student Outcome 5).

| Team Member (Last Name, First Name) | GitHub Username | Idea de Negocio y Bases | Diseño de App Web (Figma) | Contenido y Despliegue Landing | User Stories y Funciones | Análisis de Usuario y Needfinding |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: |
| Tufiño Argüelles, Luis Angel | LuisTufino2 | **L** | C | C | C | C |
| Rioja Nuñez, Franco Diego | FrancoDiegoR | C | **L** | C | C | C |
| Mallqui Vilca, Dhilsen Armil | Dhilsen18 | C | C | **L** | C | C |
| Herrera Enriquez, Diego Fernando | DerDFHE | C | C | C | **L** | C |
| Urviola Condori, Mateo Sebastián | BeyaminUv | C | C | C | C | **L** |

---

**Sustento de los Aspectos de Liderazgo:**

* **Luis Tufiño (Idea de Negocio y Bases):** Proporcionó liderazgo en la fase de concepción, estableciendo la visión estratégica de MediTrack Sensor y definiendo el modelo de negocio inicial que guía el proyecto.
* **Franco Rioja (Diseño de App Web):** Lideró la arquitectura visual y experiencia de usuario del software, siendo responsable de los prototipos de alta fidelidad en Figma para la plataforma web.
* **Dhilsen Mallqui (Contenido y Despliegue Landing):** Responsable de la presencia web del producto, liderando la implementación técnica y el despliegue de la Landing Page en Vercel para la comunicación con los interesados.
* **Diego Herrera (User Stories y Funciones):** Lideró la traducción de necesidades en requerimientos técnicos, definiendo las historias de usuario y el alcance funcional de la aplicación.
* **Mateo Urviola (Análisis de Usuario):** Lideró el proceso de investigación empática, dirigiendo la creación de User Personas, Empathy Maps y el análisis de los procesos actuales de los usuarios en su entorno laboral.

#### 5.2.1.3. Sprint Backlog 1

Durante el primer sprint backlog, nuestro equipo tuvo como objetivo principal diseñar la Aplicación Web y Landing Page, completando esta última en el proceso. Para la organización y gestión de los miembros se utilizó Trello, lo que permitió dividir las user stories en tareas manejables y asignarlas a cada integrante según sus habilidades. El propósito de este sprint fue construir en su totalidad la landing page, asegurando que fuera atractiva, funcional y alineada con la propuesta de valor de TBL.

<img src="assets/Sprint Backlog 1.png" alt="Sprint Backlog 1" />

Enlace de Trello: https://trello.com/invite/b/69e9e940d5d58b559007b0af/ATTIbc7fef21e3ae9af5f9b1524a8311a897E9406869/meditrack-sensor

#### 5.2.1.4. Development Evidence for Sprint Review

Durante el Sprint 1, el equipo utilizó GitHub como sistema de control de versiones, siguiendo el flujo de trabajo GitFlow para asegurar una integración ordenada del código. A continuación, se presenta el registro de los commits más relevantes que evidencian el desarrollo de la Landing Page y la colaboración del equipo.

**Repository:** 1ASI0730-2610-12258-TBL-MediTrackSensor/MediTrackSensor-Landing-Page

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| `MediTrackSensor-Landing-Page` | `main` | `cf30ba5` | `feat: implement team section` | `Added specific content and layout for the startup team profiles.` | 19/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `e6420c0` | `chore: finalize landing page structure` | `Final adjustments to the HTML structure for the initial release.` | 12/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `965dc26` | `fix: resolve remaining layout issues` | `Ensured all sections are correctly aligned after final review.` | 11/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `03e62cb` | `fix: clean up code and remove errors` | `General debugging of CSS and HTML validation issues.` | 11/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `5d82cf0` | `docs: add project readme file` | `Initial documentation of the repository and project description.` | 11/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `4c8156b` | `feat: update landing page and design` | `Applied general style updates and design refinements for UX.` | 11/04/2026 |
| `MediTrackSensor-Landing-Page` | `main` | `74dba14` | `chore: initial commit` | `Initial repository setup with base project files.` | 10/04/2026 |


#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

En esta sección se presenta la evidencia de la ejecución del Sprint 1, demostrando el cumplimiento de los objetivos establecidos y el despliegue del producto en un entorno de producción accesible.

<img src="assets/Landing pAge EVIDENCE.png"/>

**Enlace del Landing Page:** [https://meditrack-sensor.vercel.app/](https://meditrack-sensor.vercel.app/)

**Evidencia de Despliegue (Vercel):**

A continuación, se presenta la captura del dashboard de Vercel que confirma el despliegue exitoso (Production Deployment) de la Landing Page desde el repositorio oficial de GitHub.

<img src="assets/Deploy Landing.jpeg" />

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Para el presente Sprint 1, el alcance se centró exclusivamente en la implementación y despliegue del Landing Page (sitio web estático). Por lo tanto, no se han desarrollado servicios RESTful API en esta etapa. La documentación detallada de los endpoints mediante OpenAPI (Swagger) se incluirá en los informes correspondientes a los siguientes Sprints, una vez iniciada la fase de implementación de los Web Services.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

El deploy de la Landing Page se hizo en Vercel de la siguiente manera

### Paso 1: Se agregó el proyecto

<img src="assets/Agregar proyecto.png" />

### Paso 2: Se agregó el repositorio

<img src="assets/Agregar repositorio.png" />

### Paso 3: Se hace deploy con html, css y javascript

<img src="assets/Deploy Landing.jpeg" />

#### 5.2.1.8. Team Collaboration Insights during Sprint

La implementación de la entrega AV1 fue un esfuerzo conjunto que integró el desarrollo técnico de la Landing Page y la elaboración del reporte de ingeniería. El equipo aplicó un liderazgo compartido donde cada integrante fue responsable de la calidad de sus respectivos apartados, manteniendo una comunicación constante para asegurar la coherencia entre el diseño, los requerimientos y el producto desplegado.

A continuación, se presentan las evidencias de colaboración extraídas de los analíticos de GitHub, las cuales muestran la participación activa de todos los miembros tanto en el repositorio del código fuente como en el repositorio del informe del proyecto.

**Evidencia de Contribuciones en el Código (Landing Page):**

<img src="assets/Deploy Contributors del repositorio de la Landing Page.png" />

**Evidencia de Contribuciones en el Reporte (Documentation):**

<img src="assets/Contributors del repositorio del informe.png" />
---

## 5.3. Validation Interviews

### 5.3.1. Diseño de Entrevistas

### 5.3.2. Registro de Entrevistas

### 5.3.3. Evaluaciones según heurísticas

---

## 5.4. Video About-the-Product

---

# Conclusiones

## Conclusiones y recomendaciones

## Conclusiones

* El equipo ha logrado establecer una base sólida para el proyecto **MediTrack Sensor**, definiendo con claridad los segmentos objetivo (almacenes farmacéuticos y entidades de salud) y sus necesidades críticas de monitoreo ambiental. La alineación entre el Startup Profile y la solución propuesta garantiza que el producto final tenga un valor real en el sector salud peruano.

* Se ha cumplido satisfactoriamente con la implementación y despliegue de la primera versión de la **Landing Page** utilizando **Vercel** y tecnologías open-source. Este entregable no solo sirve como carta de presentación profesional, sino que valida la arquitectura de información y la capacidad técnica del equipo para publicar soluciones en entornos de nube accesibles.

* La aplicación del marco de trabajo ágil durante el Sprint 1 permitió una distribución de liderazgo efectiva, cumpliendo con el **ABET Student Outcome 5**. A través de la matriz de responsabilidades (LACX) y el uso de herramientas como Trello y GitHub, se demostró que el equipo puede establecer objetivos, planificar tareas técnicas y colaborar de manera inclusiva para cumplir con los hitos de la entrega.

* El diseño de la interfaz web en **Figma** y la especificación de las **User Stories** proporcionan una hoja de ruta clara para los siguientes Sprints. La trazabilidad mantenida desde la identificación de problemas hasta la creación de prototipos asegura que el desarrollo futuro de la Web Application y la API Application se mantenga enfocado en resolver las deficiencias actuales de la cadena de frío farmacéutica.

## Video About-the-Team
