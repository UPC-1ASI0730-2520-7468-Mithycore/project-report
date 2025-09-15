# Informe de Trabajo Final  
**Curso:** 1ASI0730 Aplicaciones Web  
**Startup:** Mythicore  
**Producto:** [Nombre del producto]  
**Integrantes:** 
- Stanley Jeremy Gutierrez Tume (U202118152) – Team Leader  
- Juan José Meza Huanacune (U202320574) – Backend Engineer  
- Eduardo Fabián Chacaliaza Minaya (U202324129) – Frontend & UX/UI Engineer
- Fabricio Fabián Quispe Barzola (U202320442) – Data & IoT Integration Engineer  

---

## Registro de Versiones del Informe
| Versión | Fecha | Autor | Descripción |
|---------|-------|-------|-------------|
| 0.1     | 2025-09-13 | Equipo Mythicore | Versión inicial del README.md con capítulos I–V |

---

## Project Report Collaboration Insights
📌 URL del repositorio: https://github.com/upc-2025-1asi0730-MithyCore/project-report
📌 Evidencia de commits y colaboración (capturas y explicación).  

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
9. [Anexos](#anexos)  

---

# Student Outcome

El curso contribuye al cumplimiento del **ABET – EAC - Student Outcome 5**:  
*“La capacidad de funcionar efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo, establecen objetivos, planifican tareas y cumplen objetivos.”*

En la siguiente tabla se describen las acciones realizadas y las conclusiones del equipo en relación a este Outcome.  
La información se irá ampliando en cada entrega (TB1, TP1, TB2, TF1).

| Criterio específico | Acciones realizadas | Conclusiones |
|----------------------|---------------------|--------------|
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Stanley Jeremy Gutierrez Tume (U202118152)** – TB1: asumió el rol de *Team Leader*. Organizó las primeras reuniones de coordinación, asignó responsabilidades iniciales y supervisó la creación del repositorio en GitHub. Dirigió la redacción del Capítulo I y validó la versión inicial del documento.<br><br>**Juan José Meza Huanacune (U202320574)** – TB1: apoyó en la definición de GitFlow y convenciones de commits, configuró la estructura inicial del repositorio y coordinó la parte técnica de backend. <br><br>**Eduardo Fabián Chacaliaza Minaya (U202324129)** – TB1: lideró el diseño UX/UI inicial del Landing Page y colaboró en la elaboración de los perfiles de los integrantes en el Capítulo I.<br><br>**Fabricio Fabián Quispe Barzola (U202320442)** – TB1: investigó y documentó la problemática con el método 5W2H, incorporando fuentes bibliográficas y referencias actualizadas. | En TB1 logramos un liderazgo compartido y coordinado por Stanley, lo que permitió distribuir tareas de manera clara. Cada integrante asumió un área clave (liderazgo general, backend, frontend/UX, datos/IoT), y esto facilitó un inicio ordenado del proyecto. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Stanley Jeremy Gutierrez Tume (U202118152)** – TB1: estableció las metas iniciales del sprint, promovió la participación de todos y organizó un cronograma de entregables. <br><br>**Juan José Meza Huanacune (U202320574)** – TB1: coordinó la creación de issues en GitHub, facilitó la organización del backlog inicial y propuso lineamientos técnicos de backend. <br><br>**Eduardo Fabián Chacaliaza Minaya (U202324129)** – TB1: definió criterios visuales iniciales y aportó en la planificación del Sprint 1, cuidando la consistencia de diseño. <br><br>**Fabricio Fabián Quispe Barzola (U202320442)** – TB1: colaboró en la construcción del backlog inicial y propuso herramientas colaborativas para documentación y entrevistas. | En TB1 se generó un entorno inclusivo donde todos los miembros pudieron aportar sus habilidades. Se alcanzaron los objetivos iniciales: creación del repositorio, organización del flujo de trabajo, redacción del Capítulo I y definición del problema con sustento bibliográfico. Esto establece una base sólida para la colaboración en los próximos sprints. |

---

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la startup
**Mythicore** es una plataforma digital para atención neurológica que integra dispositivos IoT y analítica de IA.  
Su propósito es mejorar el diagnóstico temprano, monitorear en tiempo real a pacientes con enfermedades crónicas y facilitar la telemedicina mediante datos objetivos, reduciendo hospitalizaciones y optimizando la calidad de vida.

- **Misión**  
Brindar atención neurológica personalizada mediante IoT e inteligencia artificial, mejorando el diagnóstico, el seguimiento y la prevención de crisis en pacientes.  

- **Visión**  
Convertirse en la plataforma líder en salud neurológica digital, integrando monitoreo continuo y telemedicina segura a nivel global.  

### 1.1.2 Perfiles de integrantes del equipo

| Foto | Nombre y Código | Rol | Descripción |
|------|-----------------|-----|-------------|
| ![Stanley](img/stanley.jpg) | **Stanley Jeremy Gutierrez Tume (U202118152)** | **Team Leader** | Estudiante de Ingeniería de Software, asume el rol de *Team Leader*. Su enfoque colaborativo le permite asignar tareas de manera eficiente, mientras que sus habilidades técnicas en HTML y CSS respaldan la capacidad para materializar ideas. Busca constantemente oportunidades de crecimiento y aprendizaje, y está comprometido con impulsar la innovación y el éxito en entornos de desarrollo de software. |
| ![Juan José](img/juan.jpg) | **Juan José Meza Huanacune (U202320574)** | **Backend Engineer** | Estudiante de Ingeniería de Software, asume el rol de *Backend Engineer*. Tiene experiencia en arquitecturas backend con C#, Java y Python, además del manejo de bases de datos relacionales. Su capacidad de organización, liderazgo y aplicación de metodologías ágiles le permite coordinar tareas y asegurar el cumplimiento de objetivos del equipo. |
| ![Eduardo](img/eduardo.jpg) | **Eduardo Fabián Chacaliaza Minaya (U202324129)** | **Frontend & UX/UI Engineer** | Estudiante de Ingeniería de Software, desempeña el rol de *Frontend & UX/UI Engineer*. Domina HTML5, CSS3 y JavaScript, junto con frameworks modernos como Vue.js y React. Se especializa en diseño de interfaces accesibles y centradas en el usuario, aportando creatividad y una visión enfocada en la experiencia de usuario para lograr aplicaciones intuitivas y atractivas. |
| ![Fabricio](img/fabricio.jpg) | **Fabricio Fabián Quispe Barzola (U202320442)** | **Data & IoT Integration Engineer** | Estudiante de Ingeniería de Software, cumple el rol de *Data & IoT Integration Engineer*. Cuenta con conocimientos en machine learning, procesamiento de datos y analítica con Python y R, además de experiencia en la integración de dispositivos IoT. Su aporte principal es implementar soluciones inteligentes que conecten sensores y servicios en la nube, garantizando un flujo de datos seguro y en tiempo real. |

---

## 1.2 Solution Profile

### 1.2.1 Antecedentes y problemática
La atención neurológica enfrenta un problema central: la falta de herramientas que permitan un monitoreo continuo y objetivo del estado de los pacientes.  
Actualmente, los diagnósticos suelen basarse en consultas periódicas y registros dispersos, lo que provoca detecciones tardías, tratamientos poco precisos y hospitalizaciones evitables.  

**Mythicore** busca resolver esta brecha integrando IoT e inteligencia artificial para capturar y analizar datos en tiempo real, apoyando así la toma de decisiones clínicas basadas en biomarcadores y reduciendo complicaciones.  

#### 5W2H del problema
- **Who (Quiénes):** Pacientes con enfermedades neurológicas crónicas, en rehabilitación o en riesgo; neurólogos y especialistas; hospitales y aseguradoras.  
- **What (Qué):** Falta de monitoreo neurológico continuo y objetivo → diagnósticos tardíos, tratamientos poco precisos.  
- **Where (Dónde):** Clínicas, hospitales y entornos domiciliarios.  
- **When (Cuándo):** Entre citas médicas y durante crisis críticas.  
- **Why (Por qué):** Métodos actuales generan duplicidad de información, errores y falta de continuidad.  
- **How (Cómo):** Sensores portátiles conectados a la nube + IA integrados en la historia clínica digital.  
- **How much (Cuánto):**  
  - EEG continuo reduce mortalidad intrahospitalaria.  
  - Monitoreo remoto reduce 59% de hospitalizaciones.  
  - EEG portátil reduce hasta 4 días de estancia en UCI.  

---
## 1.2.2. Lean UX Process

### 1.2.2.1. Lean UX Problem Statements

**Domain**  
Plataforma de salud neurológica digital con IoT, IA y telemedicina, integrada a historias clínicas electrónicas (EHR) y apoyada en un servicio externo gratuito para enriquecer datos clínicos.

**Customer segments**  
- Pacientes neurológicos y sus cuidadores.  
- Profesionales de salud (neurólogos, fisioterapeutas, psicólogos clínicos).  
- Instituciones y aseguradoras que buscan reducir costos y complicaciones.  
- Centros de investigación y biotecnología interesados en ensayos clínicos.  

**Pain points**  
- Diagnósticos tardíos por datos intermitentes.  
- Información dispersa y poco interoperable entre dispositivos y EHR.  
- Dificultad para evaluar adherencia y ajustar tratamientos a tiempo.  
- Falta de evidencias objetivas que respalden las decisiones clínicas rápidas.  

**Gap**  
Las soluciones actuales suelen ofrecer solo piezas aisladas (wearables, teleconsulta o apps), pero no una integración completa de señales neurológicas en tiempo real con analítica de IA, telemedicina y servicios externos relevantes para la práctica clínica.

**Vision / Strategy**  
Unificar en una plataforma única:  
1. Captura de señales IoT (EEG, EMG, acelerometría).  
2. Analítica con IA para detección, predicción y alertas.  
3. Telemedicina segura entre paciente y médico.  
4. Registro automático en EHR.  
5. Enriquecimiento con servicio externo gratuito (ej. ClinicalTrials.gov o RxNorm).  

**Initial segment**  
- Pacientes con epilepsia atendidos en servicios de neurología hospitalaria, y neurólogos que requieren datos objetivos y alertas predictivas.  

---

### 1.2.2.2. Lean UX Assumptions

**Business Assumptions**  
- Si demostramos reducción en hospitalizaciones y mortalidad, las instituciones adoptarán la plataforma.  
- Si integramos un servicio externo de valor (ej. ensayos clínicos o validación de medicamentos), los médicos percibirán diferenciación frente a otras soluciones.  
- Si ofrecemos un modelo SaaS con costos bajos, la plataforma será sostenible y escalable.  

**User Assumptions**  
- Si los pacientes reciben alertas y feedback, se motivarán a usar los dispositivos IoT de forma continua.  
- Si los médicos tienen dashboards integrados con datos confiables y externos, confiarán y usarán la herramienta de manera rutinaria.  
- Si los pacientes ven resultados claros sobre adherencia y evolución, incrementarán su confianza en el sistema.  

**Technical Assumptions**  
- Si logramos procesar señales IoT en la nube con baja latencia, podremos generar alertas en tiempo real.  
- Si nuestra API RESTful orquesta datos internos y externos, la integración será viable y estable.  
- Si el servicio externo gratuito mantiene un SLA aceptable, podremos garantizar disponibilidad sin costo adicional.  

---

### 1.2.2.3. Lean UX Hypothesis Statements

- “Si ofrecemos a los pacientes alertas predictivas personalizadas, entonces aumentará su adherencia al tratamiento en al menos un 15%, lo sabremos al medir cumplimiento en la aplicación.”  
- “Si proporcionamos a los neurólogos dashboards integrados con datos IoT y servicios externos, entonces incrementará su uso regular de la plataforma, lo sabremos al registrar frecuencia de acceso y duración de sesiones.”  
- “Si garantizamos la integración con EHR y un servicio externo, entonces mejorará la confianza en la información clínica, lo sabremos al obtener retroalimentación positiva en pruebas piloto.”  
- “Si desarrollamos un API RESTful que procese datos con menos de 500 ms de latencia en el 95% de las llamadas, entonces lograremos mantener la experiencia en tiempo real, lo sabremos al monitorear métricas de rendimiento.”  

---
### 1.2.2.4. Lean UX Canvas
<div align="left">
  <img src="img/Ceribell.png" alt="Ceribell" width="100"/>
</div>

# Capítulo II: Requirements Elicitation & Analysis
  
La recolección y análisis de requisitos es una etapa fundamental en el desarrollo de cualquier proyecto. Este proceso implica identificar, comprender y documentar las necesidades y expectativas de los stakeholders, así como los objetivos y restricciones del proyecto.  

A través de entrevistas, encuestas y estudios de mercado, se busca obtener una comprensión clara de los requerimientos de la solución. En este capítulo se incluyen los competidores directos e indirectos de la plataforma, para entender el estado del arte y definir nuestras fortalezas frente a ellos.  

---

## 2.1. Competidores

En esta sección se presentan algunos competidores relevantes en el ámbito del monitoreo neurológico y la telemedicina, así como un análisis de las características que nuestra plataforma IoT busca superar.

---

<div align="left">
  <img src="img/Ceribell.png" alt="Ceribell" width="100"/>
</div>
Ceribell: Es una empresa especializada en electroencefalografía portátil para cuidados intensivos. Su sistema permite obtener resultados de EEG en minutos, facilitando diagnósticos rápidos en emergencias neurológicas. Sin embargo, su enfoque está limitado al ámbito hospitalario y no ofrece un ecosistema integral de seguimiento remoto para pacientes crónicos.  

---

<div align="left">
  <img src="img/Empatica.png" alt="Empatica" width="100"/>
</div>
Empatica: Fabricante de dispositivos wearables biomédicos como el EmbracePlus, que mide actividad eléctrica de la piel, frecuencia cardíaca y patrones de sueño. Sus soluciones están dirigidas principalmente a investigación clínica y monitoreo de epilepsia, pero carecen de una plataforma analítica avanzada para predicción personalizada de crisis en pacientes.  

---

<div align="left">
  <img src="img/NeuroPace.png" alt="NeuroPace" width="100"/>
</div>
NeuroPace: Ofrece el RNS System, un dispositivo implantable que detecta y responde a actividad cerebral anormal en pacientes con epilepsia. Es una solución pionera en estimulación cerebral, aunque presenta un alto costo y está limitado a casos muy específicos, sin opciones de integración con telemedicina ni con monitoreo cotidiano de calidad de vida.  

---

## Fortalezas de Nuestra Plataforma IoT  
- Combina **sensores portátiles e implantables** en un mismo ecosistema.  
- Permite un **monitoreo continuo y remoto**, más allá del entorno hospitalario.  
- Integra **inteligencia artificial** para predicción de crisis y episodios neurológicos.  
- Ofrece una **interfaz multiplataforma** (app móvil para pacientes, dashboard web para médicos).  
- Incluye un **módulo de investigación** con exportación de datos anonimizados para ensayos clínicos.  

---
### 2.1.1. Análisis competitivo  

El análisis competitivo nos brinda una visión clara de cómo nos comparamos con nuestros competidores en el mercado. Nos ayuda a identificar áreas en las que podemos mejorar, así como oportunidades para diferenciarnos y destacar. Esta comprensión nos permite desarrollar estrategias más efectivas como grupo, lo que nos ayuda a alcanzar nuestros objetivos y mantenernos competitivos en el mercado.  

---

#### Competitive Analysis Landscape  

| ¿Por qué llevar a cabo este análisis? | Llevar a cabo este análisis nos brindará información crítica que nos permitirá tomar decisiones más informadas y estratégicas para el desarrollo, comercialización y crecimiento de nuestra plataforma. |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

| Perfil | Nuestro Proyecto (Plataforma IoT) | Ceribell | Empatica | NeuroPace |
|--------|------------------------------------|----------|----------|-----------|
| **Overview** | Plataforma IoT y de telemedicina para monitoreo neurológico continuo, integración de datos en la nube y analítica avanzada con IA. | EEG portátil para emergencias hospitalarias, diagnóstico rápido en UCI. | Wearables biomédicos para investigación clínica y monitoreo de epilepsia. | Dispositivo implantable (RNS System) para epilepsia resistente, con estimulación cerebral adaptativa. |
| **Ventaja competitiva / Valor al cliente** | Seguimiento remoto 24/7, alertas predictivas y telemedicina integrada. | Diagnóstico rápido y portátil. | Datos fisiológicos continuos y validados para investigación. | Detección y respuesta automática a actividad cerebral anómala. |
| **Mercado objetivo** | Pacientes con enfermedades neurológicas crónicas, hospitales, clínicas e investigadores. | Hospitales y UCIs. | Centros de investigación y pacientes con epilepsia. | Pacientes con epilepsia severa, candidatos a implantes. |
| **Estrategias de marketing** | Posicionamiento como plataforma integral de prevención y personalización médica. | Marketing B2B enfocado en hospitales. | Alianzas con universidades e instituciones médicas. | Difusión clínica en epileptología y neurocirugía. |
| **Productos y Servicios** | App móvil para pacientes y familiares, dashboard web para médicos, integración con EHR, módulo de investigación. | Dispositivo EEG portátil y software de análisis. | Pulsera *EmbracePlus* y plataforma de datos biomédicos. | RNS System (implante cerebral y software). |
| **Precios y Costos** | Modelo de suscripción mensual/anual para pacientes e instituciones. | Venta directa de hardware y licencias. | Venta de dispositivos + servicios de análisis. | Alto costo quirúrgico + mantenimiento de hardware. |
| **Canales de distribución** | Plataforma web y móvil, integración con hospitales, clínicas y aseguradoras. | Venta hospitalaria y distribuidores médicos. | Online y a través de centros de investigación. | Cirugías especializadas en hospitales de referencia. |

---

#### Análisis SWOT  

| Factor | Nuestro Proyecto | Ceribell | Empatica | NeuroPace |
|--------|------------------|----------|----------|-----------|
| **Fortalezas** | Integración completa IoT + IA + telemedicina; multiplataforma; datos anonimizados para investigación. | Resultados de EEG inmediatos en UCI. | Wearables validados científicamente. | Estimulación cerebral adaptativa altamente innovadora. |
| **Debilidades** | Proyecto en fase inicial, necesidad de certificaciones médicas y financiamiento. | Limitado a entornos hospitalarios, no es continuo ni remoto. | Carece de analítica avanzada predictiva. | Alto costo y aplicable solo a pacientes con epilepsia refractaria. |
| **Oportunidades** | Creciente demanda de telemedicina, prevención y salud digital; alianzas con hospitales y aseguradoras. | Expansión a hospitales de menor escala. | Expansión en mercados de salud digital y bienestar. | Integración con sistemas de monitoreo remoto en el futuro. |
| **Amenazas** | Competencia de grandes empresas tecnológicas y dispositivos médicos consolidados. | Aparición de nuevas soluciones de EEG portátiles. | Competidores en el área de wearables de salud. | Nuevas técnicas no invasivas que reduzcan su uso. |

### 2.1.2. Estrategias y Tácticas frente a Competidores

**Objetivo.** Definir cómo competiremos y ganaremos tracción frente a soluciones existentes (hospitalarias, wearables clínicos e implantes), priorizando diferenciadores de **monitoreo continuo remoto**, **IA predictiva** e **integración clínica**. (Según plantilla se debe incluir esta sección). 

#### a) Estrategias por competidor

| Competidor | Fortalezas clave | Debilidades / brechas | Nuestra estrategia | Tácticas concretas | Métricas/KPI |
|---|---|---|---|---|---|
| **Ceribell** (EEG portátil UCI) | EEG rápido en emergencias; validación clínica hospitalaria | Enfoque intra-hospitalario; sin seguimiento remoto longitudinal | **Extender el cuidado post-alta** con **RPM** (Remote Patient Monitoring) y alertas en casa | • Kits de alta con sensores + app <br>• Integración **EHR/HL7-FHIR** para continuidad de cuidados <br>• Protocolos de alerta temprana a neurología | Adopción post-alta (% pacientes activos a 30/90 días) <br>Tiempo respuesta ante alerta <br># de hospitales integrados |
| **Empatica** (wearables biomédicos) | Wearables validados; datos fisiológicos continuos | Foco investigación; analítica predictiva limitada al usuario | **Diferenciación en IA clínica**: predicción de crisis y episodios motores con panel médico | • Modelos ML multiseñal (EEG/EMG/actigrafía/sueño) <br>• Panel clínico con riesgo minuto-a-minuto <br>• Programa de “co-desarrollo” con centros de epilepsia | AUC/Se/Sp en predicción de crisis <br>Reducción de eventos no detectados <br># acuerdos de investigación |
| **NeuroPace** (RNS implantable) | Respuesta adaptativa a actividad anómala; resultados en epilepsia refractaria | Invasivo y costoso; nicho de pacientes | **Alternativa no invasiva** en etapas tempranas y triage pre-implante | • Protocolos de triage: usar nuestra plataforma antes de implante <br>• Reportes de evolución para comités de epilepsia <br>• Detección de patrones pre-ictales para evitar progresión | % pacientes que evitan implante <br>Reducción de crisis/mes <br>Satisfacción de comité (NPS clínico) |

#### b) Estrategias transversales (producto, GTM y cumplimiento)

| Frente | Tácticas | Métricas/KPI |
|---|---|---|
| **Producto & IA** | Algoritmos de detección temprana (convulsiones, bradicinesia/temblor, alteraciones de sueño), explicación de modelos para uso clínico | AUC/Se/Sp por patología; tiempo de inferencia; % explicaciones aceptadas por médicos |
| **Integración clínica** | APIs **FHIR/HL7**, interoperabilidad con EHR y PACS; flujos de telemedicina con historial en contexto | # integraciones activas; tiempo de onboarding hospital; % consultas con datos embebidos |
| **Seguridad & cumplimiento** | Cifrado E2E; anonimización para investigación; roadmap HIPAA/GDPR/ISO 27001 | Incidentes de seguridad (0); auditorías aprobadas; % datasets anonimizados |
| **GTM (go-to-market)** | Pilotos con hospitales neurológicos y aseguradoras (RPM); casos de uso por línea (Epilepsia, Parkinson, EM) | # pilotos activos; tasa de conversión piloto→contrato; costo de adquisición por institución |
| **Modelo de negocio** | Suscripción por paciente/mes (RPM) y licencias B2B para instituciones; tier de investigación | ARPU por segmento; churn; margen por institución |
| **Evidencia clínica** | Estudios observacionales + publicaciones conjuntas con centros; dataset abierto anonimizado | # publicaciones; # citaciones; # descargas de dataset |
| **Soporte al paciente** | Educación y adherencia (recordatorios, coaching), canal para cuidadores con alertas graduadas | Adherencia al uso (>80%/90 días); tiempo de respuesta cuidador; NPS paciente/caregiver |

#### c) Tácticas de corto plazo (TB1 → TP1)

1. **Piloto de telemetría** con 10–20 pacientes de epilepsia y Parkinson (app + sensores, dashboard mínimo).  
2. **Primeras reglas de alerta** (umbral + tendencia) mientras se entrena el modelo predictivo.  
3. **Integración EHR “light”** (exportación FHIR y resúmenes PDF) para consulta médica.  
4. **Acuerdo de investigación** con 1 centro de neurociencias (data-sharing anonimizado).  
5. **MVP de panel clínico**: lista de pacientes, alertas, evolución de crisis/temblor y “riesgo próximo” básico.

## 2.2 Entrevistas
- 2.2.1. Diseño de entrevistas  

Muy buenos (as) días/tardes/noches, estamos contentos de que haya aceptado esta entrevista. Somos estudiantes de la carrera de Ingeniería de Software e Informática de la UPC. A nombre del grupo desarrollador de la Plataforma IoT para la Optimización de la Atención Neurológica, queremos conversar con usted sobre las dificultades y necesidades que enfrentan los pacientes con enfermedades neurológicas y los profesionales de la salud que los atienden.  

Nuestro objetivo es conocer su experiencia y su perspectiva, ya que buscamos validar y mejorar nuestro producto. Esta plataforma integra dispositivos IoT que recolectan datos neurológicos en tiempo real (EEG, EMG, actividad motora, calidad del sueño, etc.) con inteligencia artificial para generar reportes, alertas predictivas y facilitar el seguimiento remoto por parte de los médicos. Sus respuestas serán muy valiosas para construir una solución útil, accesible y empática.  

---

### Segmento #1: Pacientes con enfermedades neurológicas crónicas  

**Preguntas complementarias:**  
- ¿Cuál es tu nombre completo?  
- ¿Cuántos años tienes?  
- ¿Dónde resides actualmente?  
- ¿Vives solo o acompañado?  
- ¿Tienes algún diagnóstico neurológico específico (epilepsia, Parkinson, Alzheimer, otro)?  
- ¿Has recibido tratamiento o seguimiento médico especializado anteriormente?  

**Preguntas principales:** *Obtener información sobre el impacto de la enfermedad, necesidades, expectativas y aceptación de nuevas tecnologías*  
- ¿Cómo ha impactado tu condición en tu vida diaria o en la de tus familiares?  
- ¿Qué dificultades enfrentas actualmente para llevar un control de tu enfermedad?  
- ¿Qué tan útil consideras que sería contar con un sistema que envíe alertas tempranas sobre crisis o anomalías?  
- ¿Qué información te gustaría poder consultar en una aplicación (ejemplo: frecuencia de crisis, calidad de sueño, evolución del tratamiento)?  
- ¿Qué tan dispuesto estarías a usar dispositivos IoT (como pulseras, bandas EEG o sensores implantables) para mejorar tu seguimiento médico?  
- ¿Cuáles serían tus principales preocupaciones respecto al uso de esta tecnología?  

---

### Segmento #2: Psicólogos clínicos / Neuropsicólogos  

**Preguntas complementarias:**  
- ¿Cuál es su nombre completo?  
- ¿Cuántos años de experiencia tiene en su campo?  
- ¿En qué institución trabaja actualmente?  
- ¿Ha tratado pacientes con enfermedades neurológicas en su práctica clínica?  
- ¿Con qué frecuencia utiliza herramientas tecnológicas en la evaluación o seguimiento de sus pacientes?  

**Preguntas principales:** *Obtener información sobre prácticas clínicas, necesidades de apoyo tecnológico, uso de datos objetivos*  
- ¿Cuáles son los mayores retos que enfrenta al evaluar pacientes con enfermedades neurológicas desde el área psicológica o neuropsicológica?  
- ¿Qué métodos utiliza actualmente para recopilar información entre una consulta y otra?  
- ¿Qué tan útil sería contar con datos objetivos y en tiempo real sobre sueño, estrés o actividad neurológica de sus pacientes?  
- ¿Qué tipo de visualización de datos le resultaría más práctica (gráficas, reportes automáticos, indicadores de riesgo)?  
- ¿Cuáles son sus preocupaciones respecto al uso de dispositivos IoT en la evaluación y seguimiento de pacientes?  
- ¿Qué características debería tener una plataforma digital para que realmente apoye su práctica clínica y no incremente su carga de trabajo?  

---  

**Despedida:** 
Muchas gracias por tu tiempo hoy. Tu opinión y las ideas que compartiste nos ayudarán mucho a mejorar nuestro producto. Apreciamos tu sinceridad y disposición para participar. Si necesitas más información, no dudes en contactarnos. ¡Gracias!

- 2.2.2 Registro de entrevistas  

**Segmento #1: Pacientes con enfermedades neurológicas crónicas**  

| **Entrevistado N°1: Cesar Aaron Cornejo** |   
| --- | ---  
|  | - **Sexo:** Masculino  
|  | - **Edad:** 21 años  
|  | - **Link:** [https://youtu.be/pNVfW7jVm5M](https://youtu.be/pNVfW7jVm5M)  
|  | - **Instante en el que inicia:** 0:22  
|  | - **Duración:** 4:15  
|  | **Resumen de la entrevista:**  
|  | Se realizó una entrevista a Cesar Aaron Cornejo, un joven de 21 años diagnosticado con epilepsia, que reside en Lima. Durante la conversación compartió que una de las principales dificultades que enfrenta es la imprevisibilidad de sus crisis, las cuales generan miedo e inseguridad tanto en él como en su familia. Comentó que ha asistido a controles médicos periódicos, pero que muchas veces siente que el seguimiento no es suficiente, ya que entre consultas pueden ocurrir episodios importantes que no quedan registrados de manera formal.  
|  | Cesar señaló que, aunque su familia y amigos lo apoyan, existe una falta de comprensión sobre la magnitud de su condición. Expresó que, en ocasiones, se siente frustrado porque no logra transmitir con exactitud cómo se siente antes o después de una crisis. Además, mencionó que suele llevar un registro manual de sus episodios, pero que este método es tedioso y poco preciso, lo que dificulta que sus médicos tengan información completa para ajustar el tratamiento.  
|  | El entrevistado considera que contar con una plataforma digital que recopile datos en tiempo real, como frecuencia de crisis, calidad del sueño y niveles de actividad, sería de gran utilidad para mejorar su calidad de vida. También destacó el valor de recibir alertas tempranas que avisen a sus familiares cuando se detecta una anomalía, ya que eso le daría mayor tranquilidad y seguridad en su día a día. Finalmente, manifestó que estaría dispuesto a utilizar dispositivos IoT como pulseras o bandas EEG, siempre que fueran cómodos y no invasivos, y resaltó la importancia de que la información recopilada se maneje con confidencialidad y se use únicamente para fines médicos.  


  
- 2.2.3 Análisis de entrevistas  

## 2.3 Needfinding
- 2.3.1 User Personas  
- 2.3.2 User Task Matrix  
- 2.3.3 User Journey Mapping  
- 2.3.4 Empathy Mapping  

## 2.4 Big Picture EventStorming  

## 2.5 Ubiquitous Language  

---

# Capítulo III: Requirements Specification

## 3.1 User Stories  
## 3.2 Impact Mapping  
## 3.3 Product Backlog  

---

# Capítulo IV: Product Design

## 4.1 Style Guidelines
- 4.1.1 General Style Guidelines  
- 4.1.2 Web Style Guidelines  

## 4.2 Information Architecture
- 4.2.1 Organization Systems  
- 4.2.2 Labeling Systems  
- 4.2.3 SEO Tags and Meta Tags  
- 4.2.4 Searching Systems  
- 4.2.5 Navigation Systems  

## 4.3 Landing Page UI Design
- 4.3.1 Landing Page Wireframe  
- 4.3.2 Landing Page Mock-up  

## 4.4 Web Applications UX/UI Design
- 4.4.1 Wireframes  
- 4.4.2 Wireflow Diagrams  
- 4.4.3 Mock-ups  
- 4.4.4 User Flow Diagrams  

## 4.5 Web Applications Prototyping  

## 4.6 Domain-Driven Software Architecture
- 4.6.1 Design-Level EventStorming  
- 4.6.2 Context Diagram  
- 4.6.3 Container Diagrams  
- 4.6.4 Component Diagrams  

## 4.7 Software Object-Oriented Design
- 4.7.1 Class Diagrams  

## 4.8 Database Design
- 4.8.1 Database Diagrams  

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management
- 5.1.1 Development Environment Configuration  
- 5.1.2 Source Code Management  
- 5.1.3 Style Guide & Coding Conventions  
- 5.1.4 Deployment Configuration  

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1
- 5.2.1.1 Sprint Planning 1  
- 5.2.1.2 Aspect Leaders and Collaborators  
- 5.2.1.3 Sprint Backlog 1  
- 5.2.1.4 Development Evidence for Sprint Review  
- 5.2.1.5 Execution Evidence for Sprint Review  
- 5.2.1.6 Services Documentation Evidence for Sprint Review  
- 5.2.1.7 Software Deployment Evidence for Sprint Review  
- 5.2.1.8 Team Collaboration Insights during Sprint  

---

# Conclusiones
(Se completará al final del Sprint 1).  

---

# Bibliografía  

- Ceribell. (2024). Evaluating the impact of point-of-care electroencephalography on length of stay in the ICU: SAFER-EEG trial sub-analysis. Neurocritical Care. [Enlace](https://link.springer.com/article/10.1007/s12028-024-02039-6)  

- Claassen, J., Hirsch, L. J., Foreman, B., Mayer, S. A., & Vespa, P. M. (2024). Utility and rationale for continuous EEG monitoring: A primer for the general intensivist. *Critical Care, 28*(1), 45. [Enlace](https://ccforum.biomedcentral.com/articles/10.1186/s13054-024-04986-0)  

- Rodriguez Ruiz, A., et al. (2025). Survey on neurological monitoring practices and clinician perspectives. *Journal of Clinical Neurophysiology, 42*(1), 56–65. [Enlace](https://www.sciencedirect.com/science/article/pii/S1052305725000266)  

- *Frontiers in Neurology*. (2023). Multimodal monitoring: Practical recommendations in neurocritical care. [Enlace](https://www.frontiersin.org/journals/neurology/articles/10.3389/fneur.2023.1135406/full)  

- Michigan Medicine. (2023). At-home monitoring cuts hospital admissions by nearly 60%. *Medical Economics*. [Enlace](https://www.medicaleconomics.com/view/at-home-monitoring-cuts-hospital-admissions-by-nearly-60-study-finds)  

- Ceribell. (2022). Reduction in length of ICU stays with point-of-care EEG. *Ceribell Press Release*. [Enlace](https://ceribell.com/press_releases/reduction-in-length-of-icu-stays)  



# Anexos
- Videos de exposición.  
- Documentos complementarios.  
