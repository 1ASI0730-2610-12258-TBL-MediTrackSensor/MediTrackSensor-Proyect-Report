# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup
Somos TechnoByteLambders, un equipo de estudiantes de la Universidad Peruana de Ciencias Aplicadas comprometidos con el uso de la tecnología para mejorar la conservación y monitoreo de medicamentos en el sector salud, enfocados en el desarrollo de soluciones innovadoras orientadas al control de condiciones ambientales en el Perú.
Nuestra misión es diseñar soluciones tecnológicas que permitan garantizar el almacenamiento adecuado de medicamentos mediante el monitoreo en tiempo real de variables como temperatura, humedad y luz, mejorando la seguridad, la eficiencia y la toma de decisiones en organizaciones del sector salud.
Nuestra visión es contribuir a la modernización de la gestión del almacenamiento y transporte de medicamentos en el país, impulsando el uso de tecnologías como IoT y plataformas digitales para lograr un control más eficiente, confiable y basado en datos.
Nuestro producto principal es MediTrack Sensor, una plataforma web que permite a clínicas, farmacias, hospitales y entidades de distribución supervisar en tiempo real las condiciones ambientales de los medicamentos, generando alertas, almacenando datos históricos y facilitando la gestión de la conservación. Esta solución reemplaza procesos manuales y limitados, ofreciendo un sistema centralizado que mejora la trazabilidad y reduce riesgos en la calidad de los productos farmacéuticos.

### 1.1.2. Perfiles de integrantes del equipo

---

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
#### Who (¿Quiénes son los involucrados?)
Los principales involucrados son hospitales, clínicas, farmacias, almacenes farmacéuticos y entidades del Estado encargadas de la distribución de medicamentos en el Perú. Asimismo, los pacientes se ven directamente afectados, ya que dependen de que los medicamentos se conserven en condiciones adecuadas para garantizar su efectividad y seguridad.

#### What (¿Qué se necesita?)
Existe la necesidad de un sistema que permita monitorear en tiempo real las condiciones ambientales de almacenamiento de medicamentos, como temperatura, humedad y exposición a la luz, debido a la falta de control continuo y herramientas tecnológicas que aseguren su correcta conservación.

#### Where (¿Dónde ocurre el problema?)
El problema se presenta en hospitales y almacenes de medicamentos a nivel nacional, especialmente en zonas de provincias como Tingo María, así como en centros de distribución donde no se cuenta con infraestructura adecuada para el almacenamiento de productos farmacéuticos.

#### When (¿Cuándo surge esta necesidad?)
Esta necesidad surge de manera constante durante todo el proceso de almacenamiento y distribución de medicamentos, especialmente en contextos donde no existen sistemas automatizados de monitoreo y control, lo que hace que el problema sea continuo y vigente en la actualidad.

#### Why (¿Por qué existe esta necesidad?)
La problemática se origina debido a la falta de infraestructura adecuada, deficiencias en la gestión de almacenes y ausencia de sistemas de monitoreo en tiempo real. Según reportes de la Contraloría General de la República, se han identificado casos de almacenamiento inadecuado en hospitales, mientras que el Estado ha reconocido la necesidad de mejorar la infraestructura de almacenamiento, lo que evidencia que las condiciones actuales no garantizan la correcta conservación de medicamentos.

#### How (¿Cómo se manifiesta el problema?)
El problema se manifiesta mediante el almacenamiento de medicamentos en condiciones inadecuadas, como exposición al sol, humedad, polvo o cercanía a zonas contaminantes. Además, se observa la falta de control de temperatura y la ausencia de sistemas automatizados, lo que obliga a depender de procesos manuales e improvisados que incrementan el riesgo de deterioro de los productos farmacéuticos.

#### How Much (¿Cuánto cuesta o qué magnitud tiene el problema?)
El problema tiene un impacto significativo en el sistema de salud, generando pérdidas económicas por medicamentos deteriorados, riesgos para la salud de los pacientes y deficiencias en la atención médica. La magnitud es considerable, ya que afecta a múltiples establecimientos de salud a nivel nacional y evidencia la necesidad de implementar soluciones tecnológicas que mejoren el control y la trazabilidad de los medicamentos.

---

#### Descripción de la Problemática

En el Perú, el almacenamiento inadecuado de medicamentos representa una problemática vigente en el sistema de salud. Según reportes de la Contraloría General de la República, en el Hospital de Tingo María se evidenciaron deficiencias en el almacenamiento, como medicamentos ubicados en pasadizos, expuestos a condiciones no adecuadas y sin control ambiental, lo que compromete su calidad y efectividad.

Asimismo, el diario oficial El Peruano señala que el Estado ha identificado limitaciones en la infraestructura de almacenamiento de medicamentos, lo que ha llevado a la implementación de mejoras y nuevos almacenes especializados. Esto evidencia que previamente no se contaba con condiciones óptimas para la conservación de productos farmacéuticos, especialmente aquellos que requieren control de temperatura y humedad.

Esta situación refleja una problemática estructural caracterizada por la falta de monitoreo en tiempo real, deficiencias en infraestructura y dependencia de procesos manuales, lo que incrementa el riesgo de deterioro de los medicamentos. Como consecuencia, se generan pérdidas económicas, desabastecimiento y, principalmente, riesgos para la salud de los pacientes, evidenciando la necesidad de implementar soluciones tecnológicas que permitan supervisar de manera eficiente las condiciones de almacenamiento.
### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
### Dominio y Alcance del Problema
El proyecto se enmarca en el sector salud, específicamente en la gestión y almacenamiento de medicamentos dentro de hospitales, centros de distribución y almacenes farmacéuticos en el Perú. A pesar de la importancia crítica de mantener condiciones adecuadas de conservación, la supervisión de variables como temperatura, humedad y luz aún presenta deficiencias debido a procesos manuales, infraestructura limitada y ausencia de monitoreo en tiempo real.

El problema se presenta a nivel nacional, con énfasis en hospitales públicos y centros de distribución de medicamentos, incluyendo almacenes estratégicos como los de Lurín. Afecta tanto a zonas urbanas como rurales, donde las limitaciones tecnológicas y de infraestructura dificultan el control adecuado de las condiciones de almacenamiento.

---

### Actores Involucrados (Segmentos de Cliente)
- Personal encargado de almacenes farmacéuticos (operarios, técnicos y responsables de control): responsables directos del almacenamiento y conservación de medicamentos.
- Personal de salud (farmacéuticos, administradores hospitalarios): supervisan el uso y disponibilidad de medicamentos.
- Entidades del Estado (MINSA, redes de salud): responsables de la distribución y cumplimiento de normativas.
- Pacientes: usuarios finales afectados por la calidad de los medicamentos.

---

### Problemas, Puntos de Dolor y Causas
**Puntos de dolor**
- Falta de herramientas tecnológicas para monitoreo en tiempo real.
- Dificultad para detectar variaciones de temperatura o humedad.
- Falta de alertas automáticas.
- Baja trazabilidad de los medicamentos.
- Pérdidas económicas por deterioro o vencimiento.

**Causas raíz**
- Infraestructura insuficiente.
- Ausencia de sistemas automatizados.
- Procesos manuales propensos a errores.
- Falta de integración tecnológica.
- Supervisión limitada y no continua.

---

### Brecha, Impactos e Indicadores
**Brecha detectada**  
No existe un sistema digital integrado que permita monitorear en tiempo real las condiciones ambientales de almacenamiento de medicamentos, generando alertas y registros históricos confiables.

**Impactos y riesgos**
- Deterioro de medicamentos.
- Riesgos para la salud.
- Pérdidas económicas.
- Incumplimiento normativo.
- Desabastecimiento.

**Indicadores**
- Número de incidencias.
- Tiempo de detección de fallas.
- % de medicamentos deteriorados.
- Nivel de cumplimiento.
- Tiempo de respuesta.
- Disponibilidad de datos históricos.

#### 1.2.2.2. Lean UX Assumptions
**Sobre usuarios (personal de almacenes, farmacéuticos, administradores de salud)**
- Asumimos que el personal encargado del almacenamiento prioriza mantener condiciones adecuadas de temperatura, humedad y luz para conservar los medicamentos.
- Asumimos que necesitan información en tiempo real sobre las condiciones ambientales para tomar decisiones rápidas.
- Asumimos que valoran sistemas simples y fáciles de usar, debido a la carga operativa diaria.
- Asumimos que toleran poca complejidad en el uso de nuevas tecnologías, por lo que requieren interfaces intuitivas.
- Asumimos que consideran importante recibir alertas inmediatas ante cualquier variación crítica en las condiciones de almacenamiento.
- Asumimos que una parte del personal depende aún de registros manuales, como cuadernos o Excel.
- Asumimos que existe interés en digitalizar procesos si esto reduce errores y facilita su trabajo.
- Asumimos que el personal valora la trazabilidad de los datos para auditorías y cumplimiento de normativas.

**Sobre entidades de salud (hospitales, MINSA, centros de distribución como Lurín)**
- Asumimos que muchas entidades gestionan el almacenamiento de medicamentos con procesos manuales o parcialmente digitalizados.
- Asumimos que carecen de monitoreo continuo y automatizado de condiciones ambientales.
- Asumimos que necesitan garantizar el cumplimiento de normativas sanitarias relacionadas al almacenamiento.
- Asumimos que requieren información histórica para auditorías y toma de decisiones.
- Asumimos que buscan reducir pérdidas económicas por medicamentos deteriorados o vencidos.
- Asumimos que la centralización de información facilitaría la gestión de múltiples almacenes o sedes.
- Asumimos que existe interés en soluciones tecnológicas que mejoren la eficiencia operativa.

**Sobre comportamiento y riesgos**
- Asumimos que la falta de monitoreo en tiempo real incrementa el riesgo de deterioro de medicamentos.
- Asumimos que errores humanos en registros manuales pueden generar información inexacta.
- Asumimos que la ausencia de alertas inmediatas retrasa la respuesta ante condiciones críticas.
- Asumimos que condiciones ambientales inadecuadas pueden pasar desapercibidas durante largos periodos.
- Asumimos que la falta de trazabilidad dificulta identificar responsabilidades ante incidentes.

**Sobre tecnología y datos**
- Asumimos que las entidades están dispuestas a implementar sensores IoT si estos mejoran el control y monitoreo.
- Asumimos que existe disponibilidad de conexión a internet en la mayoría de almacenes principales.
- Asumimos que los datos de temperatura, humedad y luz pueden ser recolectados y procesados en tiempo real.
- Asumimos que la visualización de datos en dashboards facilita la toma de decisiones.
- Asumimos que el registro histórico de datos permitirá análisis y mejora continua del proceso.
- Asumimos que la automatización mediante alertas reducirá la dependencia de la supervisión manual.

#### 1.2.2.3. Lean UX Hypothesis Statements

#### 1.2.2.4. Lean UX Canvas

---

## 1.3. Segmentos objetivo
