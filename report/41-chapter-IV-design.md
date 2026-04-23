# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

---

## 4.2. Information Architecture

### 4.2.1. Organization Systems

En la plataforma MediTrack Sensor, se emplean distintos sistemas de organización de contenido con el objetivo
de optimizar la supervisión y gestión de las condiciones ambientales en almacenes farmacéuticos. Estos sistemas permiten estructurar la información de manera clara y accesible, facilitando el monitoreo en tiempo real y la toma de decisiones tanto para el personal operativo como para las entidades de salud. A continuación, se describen los enfoques utilizados:

#### Organización Visual del Contenido

**Jerárquica (Visual Hierarchy):**

La organización jerárquica se aplica en dashboards, paneles de monitoreo y módulos de alertas, priorizando
visualmente información crítica como variaciones de temperatura, humedad y exposición a la luz. Elementos como alertas activas, indicadores de riesgo y estados de sensores destacan mediante el uso de colores, tamaños y distribución visual, permitiendo que los usuarios identifiquen rápidamente situaciones que requieren atención inmediata.

**Secuencial (Step-by-Step to Accomplish):**

En procesos como el registro de sensores, configuración de almacenes o gestión de alertas, la plataforma 
utiliza una estructura secuencial que guía al usuario paso a paso. Esto facilita la correcta configuración del sistema y reduce errores durante procesos operativos importantes.

Esquemas de Categorización de Contenido

**Por Audiencia (Roles de Usuario):**

MediTrack Sensor distingue principalmente entre dos tipos de usuarios: personal operativo de almacenes
farmacéuticos y entidades de salud o gestores farmacéuticos.

El personal operativo accede a funcionalidades enfocadas en el monitoreo en tiempo real, visualización de 
condiciones ambientales, recepción de alertas y registro de incidencias.
Las entidades de salud y gestores farmacéuticos cuentan con herramientas orientadas a la supervisión c
entralizada, análisis de datos históricos, generación de reportes y control de múltiples sedes o almacenes.

La interfaz adapta la navegación y funcionalidades según el rol del usuario, mostrando únicamente las h
erramientas relevantes para cada segmento y mejorando la experiencia de uso.

**Por Tópicos:**

El contenido de la plataforma también se organiza en categorías funcionales que facilitan la navegación y 
localización de información. Entre las principales categorías se encuentran:

- Monitoreo ambiental
- Gestión de sensores
- Alertas e incidencias
- Reportes e historial de datos
- Gestión de almacenes y sedes
- Configuración y soporte

Esta organización permite que los usuarios encuentren rápidamente la información o funcionalidad requerida 
dentro del sistema.

**Implementación en la Interfaz**

La organización jerárquica y secuencial se refleja en dashboards estructurados, formularios progresivos y 
paneles de monitoreo donde la información crítica se presenta de manera priorizada y comprensible.

Por otro lado, la categorización por audiencia y tópicos se implementa mediante menús de navegación 
diferenciados, vistas adaptadas según el tipo de usuario y módulos organizados por funcionalidades 
específicas. El uso de tarjetas, gráficos, tablas y estados visuales facilita la interpretación rápida de 
las condiciones ambientales y eventos registrados por el sistema.

Este enfoque permite que MediTrack Sensor ofrezca una experiencia intuitiva, organizada y alineada con 
las necesidades operativas del sector salud, facilitando el monitoreo eficiente y la gestión centralizada
de medicamentos.


### 4.2.2. Labeling Systems

En MediTrack Sensor, el sistema de etiquetado ha sido diseñado priorizando la claridad, simplicidad y rápida 
comprensión de la información por parte del personal operativo y las entidades de salud. Las etiquetas 
utilizadas dentro de la plataforma buscan reducir la carga cognitiva de los usuarios, facilitando la navegación
y el acceso inmediato a funcionalidades críticas relacionadas al monitoreo ambiental de medicamentos.

##### 1. Landing Page Labels

Las etiquetas del sitio web estático están orientadas a comunicar la propuesta de valor del producto y 
facilitar el acceso a la información principal de la plataforma.

-**Home**: Representa la página principal y presenta una visión general de MediTrack Sensor y su propuesta de
valor.

-**Technology**: Agrupa la información relacionada al funcionamiento del sistema, sensores IoT y monitoreo en
tiempo real.

-**Benefits**: Presenta las ventajas y beneficios que ofrece la plataforma para el control y conservación de
medicamentos.

-**Sectors**: Muestra los distintos sectores y tipos de instituciones donde el sistema puede ser implementado.

-**About Us**: Incluye información sobre el equipo responsable del desarrollo de MediTrack Sensor, así como 
la misión y visión del proyecto.

-**Pricing**: Agrupa los planes de suscripción y características disponibles según las necesidades de cada 
institución.

-**Contact**: Representa la sección destinada a la comunicación directa con el equipo mediante formularios 
o información de contacto.

##### 2. Web Application Labels (Dashboard & Navigation)

Las etiquetas dentro de la aplicación web están orientadas a facilitar el acceso rápido a funciones 
operativas y de supervisión a ambos sectores objetivos.

-**Dashboard**: Representa el panel principal con información resumida sobre sensores, condiciones 
ambientales y alertas activas.

-**Sensors**: Agrupa la gestión y visualización de sensores conectados al sistema.

-**Alerts**: Incluye las alertas generadas ante variaciones críticas de temperatura, humedad o luz.

-**Warehouses**: Representa la gestión de almacenes, sedes o áreas monitoreadas.

-**Reports**: Agrupa reportes históricos, métricas y análisis relacionados a las condiciones ambientales 
registradas.

-**Incidents**: Permite visualizar y registrar incidencias relacionadas al almacenamiento de medicamentos.

-**Settings**: Incluye configuraciones generales del sistema, preferencias y administración de cuentas.

##### 3. Status Labels (Estados del Sistema)

Para mejorar la comprensión rápida del estado de las condiciones ambientales y eventos del sistema, 
se utilizan etiquetas estandarizadas:

-**Normal**: Las condiciones ambientales se encuentran dentro de los rangos permitidos.

-**Warning**: Se detecta una variación cercana al límite permitido y requiere supervisión.

-**Critical**: Las condiciones ambientales exceden los rangos seguros establecidos.

-**Offline**: El sensor o dispositivo no se encuentra conectado o disponible.

-**Resolved**: La incidencia o alerta ha sido atendida y solucionada correctamente.

Este sistema de etiquetado permite que la navegación y comprensión de la plataforma sean más intuitivas, 
facilitando la supervisión y gestión eficiente de las condiciones de almacenamiento dentro del sector salud.


### 4.2.3. SEO Tags and Meta Tags

En MediTrack Sensor, se implementan etiquetas SEO (Search Engine Optimization) y Meta Tags dentro del 
< head > del sitio web con el objetivo de mejorar la visibilidad de la plataforma en motores de búsqueda 
como Google, así como optimizar la experiencia de navegación en distintos dispositivos y contextos de uso.

Estas etiquetas permiten describir el contenido de la plataforma, mejorar su indexación y facilitar que 
instituciones de salud, hospitales, clínicas y almacenes farmacéuticos encuentren soluciones relacionadas 
con el monitoreo ambiental y la conservación de medicamentos. Porque aparentemente hoy en día si tu web no 
tiene SEO, Google la manda al vacío cósmico donde viven las tareas entregadas fuera de fecha.

A continuación, se describen las principales etiquetas utilizadas:

**Meta Tags Básicas**

- charset="utf-8": Define la codificación de caracteres, permitiendo que el contenido se visualice correctamente, incluyendo caracteres especiales y acentos.
- viewport: Permite que la página sea responsive y se adapte correctamente a dispositivos móviles, tablets y computadoras.

**SEO Tags**

- title: Define el título de la página mostrado en los resultados de búsqueda. Resume la propuesta de valor de MediTrack Sensor.
- meta description: Proporciona un resumen breve del contenido del sitio web, destacando el monitoreo en tiempo real de medicamentos y la gestión de condiciones ambientales.
- meta keywords: Incluye palabras clave relacionadas con monitoreo farmacéutico, sensores IoT, temperatura, humedad y almacenamiento de medicamentos.
- meta author: Identifica al equipo responsable del desarrollo de la plataforma.

**Optimización de Recursos**
- Preconnect (Google Fonts): Mejora el rendimiento estableciendo conexiones anticipadas con servidores externos utilizados por las tipografías.
- CSS e íconos: Se integran librerías visuales para mantener consistencia gráfica y facilitar el diseño responsive de la plataforma.
- Favicon: Representa visualmente a MediTrack Sensor en pestañas del navegador y marcadores.

Codigo de ejemplo del head con SEO y Meta Tags:

    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
    
      <title>MediTrack Sensor - Monitoreo inteligente de medicamentos</title>
    
      <meta name="description" content="MediTrack Sensor permite monitorear en tiempo real temperatura, 
        humedad y luz en almacenes farmacéuticos mediante sensores IoT y dashboards inteligentes.">
    
      <meta name="keywords" content="MediTrack Sensor, monitoreo farmacéutico, IoT salud, temperatura 
        medicamentos, humedad almacenes, conservación de medicamentos, hospitales, farmacias, sensores IoT">
    
      <meta name="author" content="Equipo TechnoByteLambders">
    
      <!-- CSS & Icons -->
      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
    
      <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    
      <!-- Fonts -->
      <link rel="preconnect" href="https://fonts.googleapis.com">
    
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    
      <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
      <!-- Custom Styles -->
      <link rel="stylesheet" href="css/style.css">
    
      <!-- Favicon -->
      <link rel="icon" href="/assets/MediTrack.png">
    </head>


### 4.2.4. Searching Systems

En MediTrack Sensor, se implementa un sistema de búsqueda y filtrado que permite a los usuarios acceder 
rápidamente a información relevante relacionada con el monitoreo ambiental de medicamentos. Este sistema 
busca reducir el tiempo de búsqueda, facilitar la supervisión de condiciones críticas y mejorar la toma de 
decisiones dentro de la plataforma. Porque claramente revisar veinte tablas manualmente mientras un lote de 
medicamentos se cocina lentamente a 32°C no es precisamente eficiencia operativa.

El sistema está diseñado considerando los dos segmentos principales de usuarios: personal operativo de 
almacenes farmacéuticos y entidades de salud o gestores farmacéuticos, adaptando las opciones de búsqueda 
según sus necesidades específicas.

#### Búsqueda y filtros en monitoreo de almacenes

**Personal operativo de almacenes farmacéuticos**

- Búsqueda por almacén o área: Permite localizar rápidamente un almacén, sala o zona específica dentro de la institución.
- Filtrar por estado ambiental: Permite visualizar áreas según su estado actual, como “Normal”, “Alerta” o “Crítico”.
- Filtrar por tipo de variable: Facilita consultar registros relacionados con temperatura, humedad o exposición a la luz.
- Filtrar por rango de fechas: Permite revisar incidencias o registros históricos dentro de un periodo determinado.
- Historial de alertas: Acceso a eventos previos relacionados con variaciones ambientales y condiciones fuera de rango.

**Entidades de salud y gestores farmacéuticos**

- Filtrar por sede o institución: Permite supervisar múltiples almacenes o establecimientos desde un único entorno centralizado.
- Filtrar por estado de monitoreo: Visualización rápida de sedes con incidencias activas o condiciones críticas.
- Filtrar por rango de fechas: Facilita el análisis histórico y la generación de reportes para auditorías o control interno.
- Búsqueda de registros históricos: Permite acceder a datos almacenados relacionados con temperatura, humedad y luz en diferentes sedes.
- Filtrar por tipo de incidencia: Permite identificar eventos específicos asociados a fallas ambientales o incumplimientos de condiciones de almacenamiento.


#### Búsqueda en módulos adicionales

- Alertas: Búsqueda y filtrado de alertas según prioridad, fecha o estado.
- Reportes: Localización de reportes históricos por sede, fecha o tipo de variable monitoreada.
- Usuarios y sedes: Búsqueda de usuarios registrados o almacenes asociados a la institución.

**Visualización de resultados**

Los resultados de búsqueda se presentan mediante tablas y paneles organizados que muestran información clave como estado ambiental, fecha del registro, sede asociada y nivel de alerta.
Cada resultado permite acceder a una vista detallada donde el usuario puede revisar información específica sobre las condiciones monitoreadas y el historial relacionado.
En caso de no existir coincidencias, el sistema muestra mensajes informativos como “No se encontraron resultados”, evitando confusión y mejorando la experiencia de navegación. Un pequeño gesto de humanidad digital en medio del sufrimiento académico colectivo.

#### Flujo de búsqueda**

El sistema de búsqueda se encuentra integrado dentro de los módulos principales de monitoreo, alertas y reportes mediante barras de búsqueda y filtros visibles e intuitivos.
Los usuarios pueden aplicar, combinar o eliminar filtros fácilmente, permitiendo una navegación fluida y facilitando el acceso rápido a la información más relevante dentro de la plataforma.

### 4.2.5. Navigation Systems

En MediTrack Sensor, la navegación ha sido diseñada para ser clara, intuitiva y eficiente tanto en la Landing 
Page como en la Web Application. La estructura de navegación busca facilitar el acceso rápido a información 
crítica relacionada con el monitoreo ambiental de medicamentos, reduciendo la complejidad operativa y mejorando
la experiencia de uso para los distintos segmentos del sistema. Porque si alguien tiene que encontrar una alerta
crítica escondida entre veinte menús desplegables, el verdadero peligro ya no es la humedad. Es el diseñador.

#### Navegación en la Landing Page

La Landing Page guía a los visitantes a través de la propuesta de valor de MediTrack Sensor, permitiéndoles 
comprender rápidamente el problema, la solución tecnológica y los beneficios del sistema.

**Elementos de navegación**

**Menú de navegación superior**

Incluye accesos directos a las principales secciones de la página:

- Inicio
- Tecnología
- Beneficios
- Sectores
- Nosotros
- Planes
- Contacto

**Llamadas a la acción (CTAs)**

Se implementan botones visibles orientados a incentivar la interacción del usuario, tales como:

- “Solicitar información”
- “Conocer más”
- “Ver planes”

**Desplazamiento fluido**

La navegación entre secciones se realiza mediante desplazamiento continuo dentro de la misma página, 
permitiendo una experiencia fluida y evitando interrupciones innecesarias durante la exploración del contenido.

#### Navegación en la Web Application

La navegación dentro de la aplicación web se adapta según las necesidades de los dos segmentos principales 
de usuarios: personal operativo de almacenes farmacéuticos y entidades de salud o gestores farmacéuticos.

**Para personal operativo de almacenes farmacéuticos**

**Menú lateral fijo con opciones principales**

- Dashboard
- Monitoreo en tiempo real
- Alertas
- Historial de registros
- Reportes
- Configuración

**Accesos rápidos**

Se incorporan botones de acceso inmediato para acciones frecuentes como:

- Revisar alertas críticas
- Visualizar condiciones actuales
- Consultar historial reciente

**Para entidades de salud y gestores farmacéuticos**

**Menú lateral de supervisión centralizada**

- Dashboard general
- Gestión de sedes
- Reportes históricos
- Alertas globales
- Usuarios
- Configuración institucional

**Navegación entre sedes**

El sistema permite alternar rápidamente entre diferentes almacenes o sedes monitoreadas mediante filtros y 
paneles de selección.

**Visualización centralizada**

Las entidades pueden acceder a vistas generales que resumen el estado ambiental de múltiples almacenes en 
tiempo real, facilitando la supervisión integral.

#### Interacción con el sistema

**Accesibilidad**

La navegación utiliza etiquetas claras, iconografía comprensible y estructuras visuales organizadas para 
facilitar el uso de la plataforma por distintos perfiles de usuario.

**Navegación de búsqueda**

Se integran filtros rápidos y barras de búsqueda para localizar sedes, alertas, registros o reportes 
específicos de manera eficiente.

**Ayuda y soporte**

La plataforma incorpora secciones de asistencia y orientación para apoyar al usuario en la comprensión de
las funcionalidades principales del sistema y reducir la dificultad de adopción tecnológica. 

---

## 4.3. Landing Page UI Design

El diseño de la interfaz de usuario (UI) de la página de inicio de MediTrack Sensor
es fundamental para captar la atención de los visitantes y comunicar de forma clara 
su propuesta de valor: el monitoreo en tiempo real de las condiciones ambientales en el 
almacenamiento de medicamentos. El enfoque del diseño se centra en ofrecer una experiencia 
intuitiva, estructurada y orientada a la toma de decisiones, garantizando que cada elemento
sea comprensible y fácil de utilizar, reflejando el compromiso del producto con la eficiencia,
la precisión y la confiabilidad en el sector salud.

### 4.3.1. Landing Page Wireframe

El wireframe de la página de inicio funciona como un mapa visual que define la estructura, 
jerarquía y flujo de la información. Este esquema asegura una disposición lógica de los componentes
, facilitando la navegación y destacando la propuesta de valor de MediTrack Sensor. Las secciones
están diseñadas para guiar al usuario desde la comprensión del problema hasta el interés por la solución.

**Nav y Hero**

La sección inicial presenta el logotipo de MediTrack Sensor junto con un eslogan orientado a la precisión 
y el control en el almacenamiento de medicamentos. La barra de navegación permite acceder a secciones
clave como Tecnología, Sectores, Nosotros y Planes. El área principal comunica de forma inmediata el
propósito del sistema: monitorear variables críticas como temperatura, humedad y luz en tiempo real.
Se incluye un llamado a la acción visible que incentiva al usuario a obtener más información o 
establecer contacto. Un recurso visual relacionado al entorno farmacéutico refuerza el contexto del producto.

<img src="../assets/navYHero.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">

**Tecnología (How It Works)**

En esta sección se explica el funcionamiento del sistema, destacando la integración de sensores IoT
con la plataforma web. Se presentan las variables monitoreadas (temperatura, humedad y luz), así 
como el flujo de datos hacia dashboards en tiempo real. La información se organiza de manera clara 
para que el usuario comprenda cómo el sistema captura, procesa y presenta los datos.

<img src="../assets/tecnologia.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Beneficios del sistema**

Esta sección describe el valor que ofrece MediTrack Sensor, enfocándose en la reducción de pérdidas 
por deterioro de medicamentos, la mejora en la trazabilidad y el cumplimiento de normativas sanitarias.
Se resaltan beneficios como alertas automáticas, acceso a información en tiempo real y disponibilidad 
de datos históricos para auditorías y toma de decisiones.

<img src="../assets/sobrePlataforma.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">

<img src="../assets/comoFunciona.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Sectores (Aplicación del sistema)**

Aquí se presentan los distintos contextos donde el sistema puede ser aplicado, como hospitales, clínicas,
farmacias y centros de distribución. Cada segmento se describe brevemente, permitiendo que el usuario
identifique rápidamente cómo el producto se adapta a su entorno.

<img src="../assets/paraQuien.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Sobre el Equipo (Nosotros)**

Esta sección muestra al equipo detrás de MediTrack Sensor, incluyendo información relevante sobre sus 
integrantes. Su objetivo es generar confianza y credibilidad, humanizando la solución y mostrando el 
compromiso del equipo con el desarrollo del producto.

<img src="../assets/quienesSomos.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Planes (Pricing)**

La sección de planes presenta las opciones de suscripción del sistema, organizadas según el número de 
sedes y funcionalidades disponibles. Se describen características como monitoreo en tiempo real, alertas,
acceso a historial y gestión centralizada, permitiendo al usuario identificar la opción más adecuada
según sus necesidades.

<img src="../assets/planesPagos.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Contacto**

En esta sección, los usuarios pueden establecer contacto directo con el equipo de MediTrack Sensor
para solicitar información adicional, resolver dudas o explorar oportunidades de implementación 
en sus instituciones. Se busca ofrecer un canal claro, accesible y confiable que facilite la comunicación
y permita a los interesados dar el siguiente paso hacia la adopción de una solución de monitoreo 
eficiente y adaptada al sector salud.

<img src="../assets/contacto.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


**Footer**

El pie de página incluye enlaces a información relevante como términos de servicio, políticas de privacidad
y medios de contacto. Este elemento proporciona un cierre estructurado a la página, permitiendo acceso 
rápido a información adicional sin afectar la claridad del diseño principal.

<img src="../assets/footer.png" alt="Landing Page Wireframe" style="max-width: 100%; height: auto;">


Este wireframe establece las bases para un diseño que no solo comunica la propuesta de valor de manera
efectiva, sino que también guía al usuario a través de una experiencia clara, funcional y alineada 
con las necesidades del sector salud.

### 4.3.2. Landing Page Mock-up

Los mockups de MediTrack Sensor representan la versión visual de alta fidelidad de la Landing Page, 
incorporando la identidad gráfica, paleta de colores y estilo visual del producto. La propuesta utiliza
como colores principales el azul oscuro #1B304C, asociado a confianza y estabilidad, y el naranja #E87239,
utilizado para resaltar información importante y llamados a la acción.

Asimismo, se incorporan imágenes relacionadas al entorno farmacéutico y al monitoreo de medicamentos, 
reforzando visualmente el enfoque del sistema en la seguridad, supervisión y control dentro del sector salud.

**Nav y Hero**

La sección principal presenta una interfaz moderna y limpia que comunica rápidamente la propuesta de valor 
de MediTrack Sensor. Se prioriza un mensaje claro sobre el monitoreo en tiempo real y se utiliza un llamado 
a la acción visible acompañado de elementos visuales relacionados al almacenamiento farmacéutico.

<img src="../assets/navMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">

**Tecnología (How It Works)**

El mockup de esta sección muestra de forma visual el funcionamiento del sistema y la integración con sensores
IoT. Se utilizan íconos, tarjetas informativas y una estructura clara para facilitar la comprensión del flujo 
de monitoreo y procesamiento de datos.

<img src="../assets/tecMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Beneficios del sistema**

Esta sección resalta los beneficios principales mediante elementos visuales organizados y fáciles de identificar.
El diseño enfatiza conceptos como monitoreo continuo, alertas automáticas y trazabilidad de información.

<img src="../assets/sobrePlataformaMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">

<img src="../assets/comoFuncionaMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Sectores (Aplicación del sistema)**

El diseño presenta los diferentes entornos donde MediTrack Sensor puede ser implementado, utilizando imágenes y 
bloques visuales que ayudan a identificar rápidamente cada sector objetivo.

<img src="../assets/paraQuienMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Sobre el Equipo (Nosotros)**

Esta sección utiliza un diseño cercano y profesional para presentar a los integrantes del equipo. Se busca 
transmitir confianza y compromiso mediante fotografías y descripciones breves.

<img src="../assets/quienesSomosMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Planes (Pricing)**

El mockup de planes organiza la información de manera clara y visualmente diferenciada, permitiendo comparar 
características y funcionalidades entre las distintas opciones de suscripción.

<img src="../assets/planesPagosMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Contacto**

La sección de contacto presenta un diseño accesible y ordenado que facilita la comunicación entre los usuarios 
y el equipo de MediTrack Sensor, manteniendo coherencia visual con el resto de la plataforma.

<img src="../assets/contactoMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


**Footer**

El footer mantiene una estructura limpia y funcional, integrando accesos rápidos a información relevante, 
enlaces de soporte y elementos de identidad institucional.

<img src="../assets/footerMU.png" alt="Landing Page Mock Up" style="max-width: 100%; height: auto;">


---

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

En esta sección se presentan los wireframes de la versión web de MediTrack Sensor,
organizados según los dos perfiles principales de usuario: personal operativo de almacenes
farmacéuticos y entidades de salud. Cada diseño está orientado a ofrecer una experiencia
clara, coherente y centrada en las necesidades de cada segmento, facilitando la supervisión
de condiciones ambientales, el acceso a información relevante y la toma de decisiones.
Asimismo, se busca asegurar una navegación intuitiva y fluida a lo largo de la plataforma.

<img src="./../assets/WebApplicationWireframes.png" alt="WebApp Wireframes" width="700">

### 4.4.2. Web Applications Wireflow Diagrams

En esta sección se presentan los diagramas de flujo de interacción (wireflows) de 
la aplicación web de MediTrack Sensor, los cuales ilustran la navegación y las 
principales acciones que pueden realizar los distintos segmentos de usuarios dentro 
de la plataforma. Estos diagramas permiten visualizar cómo los usuarios interactúan con el sistema, 
facilitando la comprensión de la estructura funcional y de la experiencia de uso orientada al 
monitoreo de condiciones ambientales en tiempo real.

**Flujo tras inicio de sesión de Segmento Personal Operativo**

Este flujo representa el recorrido del personal operativo de almacenes farmacéuticos, enfocado en
la supervisión en tiempo real de condiciones ambientales. El usuario visualiza variables como 
temperatura, humedad y luz, detecta variaciones fuera de rango y registra incidencias.

<img src="./../assets/SegmentoPersonalOperativo.png" alt="Wireflow Personal Operativo" width="700">

**Flujo tras inicio de sesión de Segmento Entidades de Salud**

Este flujo describe la experiencia de entidades de salud y gestores farmacéuticos, quienes 
requieren una visión estratégica del sistema. Desde su panel, supervisan múltiples almacenes, 
acceden a datos históricos, analizan tendencias y apoyan la toma de decisiones.

<img src="./../assets/SegmentoEntidadSalud.png" alt="Wireflow Entidad Salud" width="700">


### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

---

## 4.5. Web Applications Prototyping

---

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level EventStorming

En esta sección se presenta el Design-Level EventStorming realizado para el sistema MediTrack Sensor. A través de esta actividad, se identificaron detalladamente los eventos de dominio, comandos, actores, políticas y vistas que conforman cada Bounded Context, desde la ingesta de telemetría IoT hasta la gestión de cumplimiento regulatorio. El resultado permite visualizar la dinámica interna de la solución y la interacción entre sus componentes, facilitando un entendimiento profundo del dominio farmacéutico y garantizando una arquitectura reactiva capaz de mitigar riesgos críticos en tiempo real.

<img src="../assets/Design-Level EventStorming.jpg"/>

Link del miro: 

https://miro.com/welcomeonboard/SVV1K0dFRzEyVTVDdUcyWnlZaldBTHRyTkxMTWorOXlLaXNRbmQ1czlsZkJuOFROVHh3YWkzN2JsT01wRHRKQXJUaW5LQXJ0cEovUkdzR2VWaCtiTFZ2YUJkTW5YRUthaW8wL1grTXh3MnBEdDhDQjc0SENoOXYxQ0pGd2VHeU1yVmtkMG5hNDA3dVlncnBvRVB2ZXBnPT0hdjE=?share_link_id=632091220772

### 4.6.2. Software Architecture Context Diagram

A continuación, se presenta el diagrama de contexto para el sistema MediTrack Sensor. Este nivel muestra cómo la plataforma se relaciona con los segmentos objetivo principales: el personal operativo, encargado de supervisar las condiciones ambientales en almacenes, y los gestores farmacéuticos, que analizan reportes históricos y cumplimiento normativo. Asimismo, se ilustra la interacción con los sensores IoT que proveen la telemetría en tiempo real y los sistemas externos de notificaciones y regulación que aseguran la trazabilidad y seguridad de los productos farmacéuticos.

<img src="../assets/Context-Diagram.png"/>

### 4.6.3. Software Architecture Container Diagrams

A continuación, se presenta el diagrama de contenedores de MediTrack Sensor. El sistema se compone de una Web Application desarrollada en Vue.js, que ofrece una interfaz reactiva para los usuarios, y una API Application que centraliza la lógica de negocio y la ingesta de datos IoT. Finalmente, se utiliza SQL Server como base de datos para garantizar la persistencia de registros históricos y perfiles, permitiendo una comunicación fluida entre el monitoreo en tiempo real y el almacenamiento seguro.

<img src="../assets/Container-Diagram.png"/>

### 4.6.4. Software Architecture Components Diagrams

A continuación, se presenta el diagrama de componentes para la API Application de MediTrack Sensor. Este nivel detalla los módulos internos responsables de gestionar los flujos críticos del sistema. Se incluyen el Auth Component para la seguridad mediante JWT, el Monitoring Controller que expone los servicios de telemetría y el Environment Service como núcleo de la lógica para el control de variables ambientales. Asimismo, se integran el Data Repository para la persistencia en SQL Server, y adaptadores específicos para la comunicación con el servicio de alertas y los sistemas regulatorios. Este diagrama refleja cómo la arquitectura interna garantiza la escalabilidad y el monitoreo eficiente de los medicamentos.

<img src="../assets/Component-Diagram.png"/>

---

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

<img src="../assets/Meditrack - class diagram.jpg"/>

---

## 4.8. Database Design

### 4.8.1. Database Diagrams

<img src="../assets/Meditrack - database_diagram.png" alt="Meditack-datababase-diagram"/>
