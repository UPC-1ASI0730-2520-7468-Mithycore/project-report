# Informe de Trabajo Final  
**Curso:** 1ASI0730 Aplicaciones Web  
**Startup:** Mythicore  
**Producto:** [Nombre del producto]  
**Integrantes:** 
- Stanley Jeremy Gutierrez Tume (U202118152) – Team Leader  
- Juan José Meza Huanacune (U202320574) – Backend Engineer  
- Eduardo Fabián Chacaliaza Minaya (U202324129) – Frontend & UX/UI Engineer
- Fabricio Fabián Quispe Barzola (U202320442) – Data & IoT Integration Engineer
- Romero Meza Jhimy Pool (u202321510) - Frontend & UX/UI Engineer

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
| **Trabaja en equipo para proporcionar liderazgo en forma conjunta** | **Stanley Jeremy Gutierrez Tume (U202118152)** – TB1: asumió el rol de *Team Leader*. Organizó las primeras reuniones de coordinación, asignó responsabilidades iniciales y supervisó la creación del repositorio en GitHub. Dirigió la redacción del Capítulo I y validó la versión inicial del documento.<br><br>**Juan José Meza Huanacune (U202320574)** – TB1: apoyó en la definición de GitFlow y convenciones de commits, configuró la estructura inicial del repositorio y coordinó la parte técnica de backend. <br><br>**Eduardo Fabián Chacaliaza Minaya (U202324129)** – TB1: lideró el diseño UX/UI inicial del Landing Page y colaboró en la elaboración de los perfiles de los integrantes en el Capítulo I.<br><br>**Fabricio Fabián Quispe Barzola (U202320442)** – TB1: investigó y documentó la problemática con el método 5W2H, incorporando fuentes bibliográficas y referencias actualizadas. <br><br>**Jhimy Pool Romero Meza (U202321510)** – TB1: Diseño la estructura de la landing page mencionando y añadiendo la informacion mas relevante para que los usuarios puedan interactuar de una manera mas fluida y eficaz.| En TB1 logramos un liderazgo compartido y coordinado por Stanley, lo que permitió distribuir tareas de manera clara. Cada integrante asumió un área clave (liderazgo general, backend, frontend/UX, datos/IoT), y esto facilitó un inicio ordenado del proyecto. |
| **Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos** | **Stanley Jeremy Gutierrez Tume (U202118152)** – TB1: estableció las metas iniciales del sprint, promovió la participación de todos y organizó un cronograma de entregables. <br><br>**Juan José Meza Huanacune (U202320574)** – TB1: coordinó la creación de issues en GitHub, facilitó la organización del backlog inicial y propuso lineamientos técnicos de backend. <br><br>**Eduardo Fabián Chacaliaza Minaya (U202324129)** – TB1: definió criterios visuales iniciales y aportó en la planificación del Sprint 1, cuidando la consistencia de diseño. <br><br>**Fabricio Fabián Quispe Barzola (U202320442)** – TB1: colaboró en la construcción del backlog inicial y propuso herramientas colaborativas para documentación y entrevistas. <br><br>**Jhimy Pool Romero Meza (U202321510)** – TB1: Colaboro en la parte de diseño de la landing page cuidando los elementos visuales generando un diseño adecuado para el proyecto y se facilito la paleta de colores a trabajar. | En TB1 se generó un entorno inclusivo donde todos los miembros pudieron aportar sus habilidades. Se alcanzaron los objetivos iniciales: creación del repositorio, organización del flujo de trabajo, redacción del Capítulo I y definición del problema con sustento bibliográfico. Esto establece una base sólida para la colaboración en los próximos sprints. | 

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

### 1.1.2 Perfiles de los integrantes del equipo

| Foto | Nombre y Código | Rol | Descripción |
|------|-----------------|-----|-------------|
| ![Stanley](img/stanley.jpg) | **Stanley Jeremy Gutierrez Tume (U202118152)** | **Team Leader** | Estudiante de Ingeniería de Software, asume el rol de *Team Leader*. Su enfoque colaborativo le permite asignar tareas de manera eficiente, mientras que sus habilidades técnicas en HTML y CSS respaldan la capacidad para materializar ideas. Busca constantemente oportunidades de crecimiento y aprendizaje, y está comprometido con impulsar la innovación y el éxito en entornos de desarrollo de software. |
| ![Juan José](img/juan.jpg) | **Juan José Meza Huanacune (U202320574)** | **Backend Engineer** | Estudiante de Ingeniería de Software, asume el rol de *Backend Engineer*. Tiene experiencia en arquitecturas backend con C#, Java y Python, además del manejo de bases de datos relacionales. Su capacidad de organización, liderazgo y aplicación de metodologías ágiles le permite coordinar tareas y asegurar el cumplimiento de objetivos del equipo. |
| ![Eduardo](img/eduardo.jpg) | **Eduardo Fabián Chacaliaza Minaya (U202324129)** | **Frontend & UX/UI Engineer** | Estudiante de Ingeniería de Software, desempeña el rol de *Frontend & UX/UI Engineer*. Domina HTML5, CSS3 y JavaScript, junto con frameworks modernos como Vue.js y React. Se especializa en diseño de interfaces accesibles y centradas en el usuario, aportando creatividad y una visión enfocada en la experiencia de usuario para lograr aplicaciones intuitivas y atractivas. |
| ![Fabricio](img/fabricio.jpg) | **Fabricio Fabián Quispe Barzola (U202320442)** | **Data & IoT Integration Engineer** | Estudiante de Ingeniería de Software, cumple el rol de *Data & IoT Integration Engineer*. Cuenta con conocimientos en machine learning, procesamiento de datos y analítica con Python y R, además de experiencia en la integración de dispositivos IoT. Su aporte principal es implementar soluciones inteligentes que conecten sensores y servicios en la nube, garantizando un flujo de datos seguro y en tiempo real. |
| ![Fabricio](./img/Integrantes/JhimyRomeroMeza.png) | **Romero Meza Jhimy Pool (U202321510)** | **Frontend & UX/UI Engineer** | Estudiante de Ingeniería de Software, cumple el rol de UX/UI Designer & Frontend Engineer. Cuenta con conocimientos en diseño de interfaces, experiencia de usuario y desarrollo frontend con tecnologías modernas. Su aporte principal es la conceptualización y creación de wireframes, mockups y prototipos interactivos, asegurando que la experiencia del usuario sea clara, intuitiva y alineada con los objetivos del proyecto. Además, garantiza la coherencia visual del sistema y facilita la transición entre la fase de diseño y desarrollo.  |

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

Muy buenos días/tardes/noches, estamos contentos de que haya aceptado esta entrevista. Somos estudiantes de la carrera de Ingeniería de Software e Informática de la UPC. A nombre del grupo desarrollador de la Plataforma IoT para la Optimización de la Atención Neurológica, queremos conversar con usted sobre las dificultades y necesidades que enfrentan los pacientes con enfermedades neurológicas y los profesionales de la salud que los atienden.  

Nuestro objetivo es conocer su experiencia y su perspectiva, ya que buscamos validar y mejorar nuestro producto. Esta plataforma integra dispositivos IoT que recolectan datos neurológicos en tiempo real (EEG, EMG, actividad motora, calidad del sueño, etc.) con inteligencia artificial para generar reportes, alertas predictivas y facilitar el seguimiento remoto por parte de los médicos. Sus respuestas serán muy valiosas para construir una solución útil, accesible y empática.  

---

### Segmento #1: Pacientes con enfermedades neurológicas crónicas  

**Preguntas complementarias:**  
- ¿Cuál es tu nombre completo?  
- ¿Cuántos años tienes?  
- ¿Dónde resides actualmente?  
- ¿Vives solo o acompañado?  
- ¿Tienes algún diagnóstico neurológico específico?  
- ¿Has recibido tratamiento o seguimiento médico especializado anteriormente?  
- ¿Qué dispositivos tecnológicos usas con mayor frecuencia? 
- ¿Qué navegador web utilizas normalmente? 
- ¿Cuáles son los métodos que utilizas más para autenticarte o logearte en plataformas?  

**Preguntas principales:** *Obtener información sobre el impacto de la enfermedad, necesidades, expectativas y aceptación de nuevas tecnologías*  
- ¿Cómo ha impactado tu condición en tu vida diaria o en la de tus familiares?  
- ¿Qué dificultades enfrentas actualmente para llevar un control de tu enfermedad?  
- ¿Qué tan útil consideras que sería contar con un sistema que envíe alertas tempranas sobre crisis o anomalías?  
- ¿Qué información te gustaría poder consultar en una aplicación?  
- ¿Qué tan dispuesto estarías a usar dispositivos IoT para mejorar tu seguimiento médico?  
- ¿Cuáles serían tus principales preocupaciones respecto al uso de esta tecnología?  


### Segmento #2: Psicólogos clínicos / Neuropsicólogos  

**Preguntas complementarias:**  
- ¿Cuál es su nombre completo?  
- ¿Cuántos años tiene?  
- ¿Dónde ejerce actualmente su profesión? (clínica, hospital, consultorio privado, universidad, etc.)  
- ¿Cuántos años de experiencia tiene en el área de neurología / salud mental?  
- ¿Cuál es su especialidad o campo principal de trabajo? (neurología, neuropsicología, psicología clínica, terapia de rehabilitación, etc.)  
- ¿Con qué frecuencia atiende a pacientes con enfermedades neurológicas crónicas?  
- ¿Qué dispositivos tecnológicos utiliza con mayor frecuencia en su práctica profesional? (ejemplo: laptop, tablet, smartphone, dispositivos médicos digitales)  
- ¿Qué software o plataformas médicas emplea habitualmente? (ejemplo: historias clínicas electrónicas, Epic, Cerner, otros)  
- ¿Qué navegador web utiliza normalmente para su trabajo? (ejemplo: Chrome, Safari, Edge, Opera)  
- ¿Cuáles son los métodos que utiliza más para autenticarse en sistemas o plataformas profesionales? (ejemplo: correo institucional, Gmail, SMS, autenticación en dos pasos, otros)  

**Preguntas principales (Segmento 2 – Profesionales de la salud):**  
- ¿Cómo realiza actualmente el seguimiento de sus pacientes con epilepsia u otras condiciones neurológicas?  
- ¿Qué tan útil considera contar con una plataforma que integre registros de crisis, calidad de sueño y datos biométricos en tiempo real?  
- ¿Qué marcas o sistemas le generan más confianza para trabajar con este tipo de soluciones?  
- ¿Le sería útil acceder a los registros de sus pacientes desde una aplicación web conectada a la nube?  
- ¿Qué comunidades científicas sigue para mantenerse actualizado en este tema?  
- ¿Cómo cree que estas herramientas digitales impactarían en el sistema de salud en general?  
- ¿Cómo visualiza el futuro de la neurología con IoT y plataformas digitales integradas?  

### Segmento #3: Proveedores IoT

**Preguntas complementarias:**  
- ¿Cuál es el nombre de su empresa o marca?  
- ¿Cuál es su nombre completo y cargo dentro de la empresa?  
- ¿Cuántos años de experiencia tiene su empresa en el desarrollo de dispositivos IoT para el sector salud?  
- ¿Qué tipo de dispositivos IoT produce o distribuye actualmente? (ejemplo: bandas EEG, wearables, relojes inteligentes, sensores implantables, otros)  
- ¿En qué mercados o regiones tienen mayor presencia?  
- ¿Cuáles son los principales clientes a los que venden sus soluciones? (hospitales, clínicas, investigadores, aseguradoras, pacientes directamente)  
- ¿Qué dispositivos tecnológicos utilizan con mayor frecuencia en su operación diaria? (ejemplo: servidores, plataformas cloud, aplicaciones de monitoreo)  
- ¿Qué software o plataformas emplean para la gestión y seguridad de datos recolectados por sus dispositivos?  
- ¿Qué navegador web utilizan normalmente para el trabajo administrativo o de integración de plataformas?  
- ¿Cuáles son los métodos más utilizados para autenticar usuarios en sus dispositivos o plataformas? (ejemplo: correo institucional, Gmail, SMS, autenticación en dos pasos, biometría)  

**Preguntas principales:**  
- ¿Cómo desarrollan actualmente sus dispositivos IoT aplicados a la salud neurológica y cuáles son sus principales funcionalidades?  
- ¿Qué tan capacitado considera que está su equipo en la integración de dispositivos IoT con plataformas digitales de salud, como historias clínicas electrónicas o dashboards médicos?  
- ¿Qué marcas, certificaciones o estándares internacionales considera fundamentales para que los profesionales de la salud confíen en sus dispositivos? 
- ¿Le sería útil contar con alianzas estratégicas que permitan acceder a los datos de sus dispositivos desde aplicaciones web o plataformas en la nube utilizadas por médicos y hospitales?  
- ¿En qué comunidades profesionales o foros online participa su empresa para mantenerse actualizada sobre tendencias y regulaciones de IoT en el sector salud?  
- ¿Cómo cree que la adopción de dispositivos IoT impactará en hospitales, clínicas y aseguradoras que atienden a pacientes neurológicos?  
- ¿Cómo visualiza el futuro de los dispositivos IoT aplicados a la neurología en los próximos 5 a 10 años?  

---  

**Despedida:** 
Muchas gracias por tu tiempo hoy. Tu opinión y las ideas que compartiste nos ayudarán mucho a mejorar nuestro producto. Apreciamos tu sinceridad y disposición para participar. Si necesitas más información, no dudes en contactarnos. ¡Gracias!

- 2.2.2 Registro de entrevistas  

## Segmento 1: Pacientes con enfermedades neurológicas crónicas  

### Entrevista N°1  

- **Nombre:** Cesar Aaron Cornejo  
- **Sexo:** Masculino  
- **Edad:** 21  
- **Estado Civil:** Soltero
- **Condición:** Paciente diagnosticado con epilepsia  

**Detalles de la entrevista:**  
Cesar Aaron Cornejo es un joven de 21 años que reside en Lima. Durante la conversación compartió que una de las principales dificultades que enfrenta es la imprevisibilidad de sus crisis, las cuales generan ansiedad y preocupación, tanto en él como en su familia.  

Actualmente lleva un registro manual de sus episodios en un cuaderno, aunque reconoce que este método no siempre es preciso, ya que puede olvidar anotar detalles importantes. Señala que esta limitación dificulta que su neuróloga tenga información completa para ajustar su tratamiento.  

Aaron considera que recibir alertas tempranas sobre posibles crisis en tiempo real sería muy útil, pues le permitiría tomar precauciones inmediatas y dar mayor tranquilidad a su familia. Le interesaría consultar en una aplicación móvil datos como la frecuencia y duración de las crisis, la calidad de su sueño y los factores desencadenantes, presentados en gráficos y estadísticas fáciles de entender.  

En cuanto a tecnologías de monitoreo, se muestra abierto al uso de **wearables** como relojes inteligentes de marcas confiables (Garmin, Fitbit), y señala que aceptaría sensores implantables siempre que fueran seguros y validados médicamente. Para él, la posibilidad de que su neuróloga pueda acceder a sus datos a través de una aplicación web conectada a su historia clínica representaría un gran avance, reduciendo la necesidad de visitas presenciales.  

Finalmente, menciona que ha participado en comunidades online como foros de la **Epilepsy Foundation** o grupos de Facebook sobre epilepsia, los cuales le han ayudado a sentirse acompañado. Afirma que el uso de estas herramientas digitales le daría mayor independencia y mejoraría la calidad de vida tanto para él como para su familia.  

- **Duración:** 6 minutos con 45 segundos  

---

### Resumen de los puntos clave en la entrevista  

- El entrevistado se llama **Cesar Aaron Cornejo**, tiene 21 años, vive en Lima y está diagnosticado con epilepsia.  
- Su principal dificultad es la **imprevisibilidad de las crisis**, lo que genera ansiedad en él y preocupación en su familia.  
- Actualmente lleva un **registro manual** de sus episodios, pero reconoce que es incompleto y poco confiable.  
- Considera muy útil contar con **alertas tempranas** que detecten anomalías en tiempo real, para actuar con mayor seguridad.  
- Le gustaría consultar en una app móvil registros de crisis, calidad del sueño y factores desencadenantes, con **gráficos y estadísticas claras**.  
- Tiene **confianza en wearables** como Garmin y Fitbit, y aceptaría sensores implantables si son seguros y certificados.  
- Valora que su neuróloga pueda **acceder a sus datos desde una plataforma web** conectada a la historia clínica.  
- Ha participado en **comunidades online** de pacientes, lo que le ha dado apoyo emocional.  
- Cree que estas herramientas digitales le darían **independencia, seguridad y tranquilidad familiar**.  

---

### Registro visual de la entrevista  
![Evidencia de entrevista](img/aaron.png)  


---

### Registro visual de la entrevista  

![Evidencia de entrevista](img/aaron.png)


**Segmento #2: Profesionales de la salud en neurología**  

| | **Entrevistado N°1: Juan José Meza Galarza**  
| --- | ---  
|  | - **Sexo:** Masculino  
|  | - **Edad:** 56 años  
|  | - **Profesión:** Neurólogo Especialista
|  | - **Link:** __________________________  
|  | - **Instante en el que inicia:** ____  
|  | - **Duración:** ____  
|  | **Resumen de la entrevista:**  
|  | Se realizó una entrevista a Juan José Meza Galarza, neurólogo clínico con más de veinte años de experiencia en el tratamiento de pacientes con epilepsia y enfermedades neurodegenerativas. Durante la conversación compartió que una de las principales dificultades que enfrenta en su práctica es la falta de información continua y objetiva sobre la evolución de los síntomas en los pacientes, lo que limita la capacidad de ajustar los tratamientos en el momento oportuno.  
|  | El entrevistado señaló que, aunque los reportes verbales de familiares y pacientes aportan información valiosa, suelen estar sesgados o incompletos, lo que retrasa la identificación de patrones clínicos importantes. Destacó que contar con datos cuantitativos de manera sistemática sería una herramienta fundamental para la práctica clínica y la investigación.  
|  | Considera que una plataforma IoT con sensores portátiles y bases de datos integradas le permitiría obtener métricas más confiables sobre calidad de sueño, frecuencia de episodios y niveles de actividad de sus pacientes. Subrayó que la posibilidad de recibir reportes automatizados facilitaría tanto la toma de decisiones clínicas como la comunicación con familiares.  
|  | Finalmente, indicó que para que esta tecnología sea realmente útil debe garantizar la confidencialidad de los datos y presentarlos en un formato claro y fácil de interpretar, de manera que pueda integrarse sin dificultad a la práctica profesional diaria. También enfatizó que herramientas así podrían abrir nuevas oportunidades de investigación en neurociencias, al permitir trabajar con información más amplia y representativa de la vida cotidiana de los pacientes.

**Segmento #3: Terapeutas**   

| | **Entrevistado N°1: Jairo Chávez**  
| --- | ---  
|  | - **Sexo:** Masculino  
|  | - **Edad:** 23 años  
|  | - **Profesión:** Terapeuta en formación  
|  | - **Link:** [https://youtu.be/Nabxppg7DKQ](https://youtu.be/Nabxppg7DKQ)  
|  | - **Instante en el que inicia:** 0:00  
|  | - **Duración:** 2:45  
|  | **Resumen de la entrevista:**  
|  | Se realizó una entrevista a Jairo Chávez, joven terapeuta en formación de 23 años. Durante la conversación compartió que uno de los principales retos en su práctica es el limitado acceso a información objetiva y continua sobre la evolución de los pacientes con enfermedades neurológicas. Señaló que muchas veces los datos provienen únicamente de observaciones verbales o registros poco sistemáticos, lo que dificulta evaluar la eficacia de las terapias.  
|  | El entrevistado mencionó que considera fundamental contar con herramientas tecnológicas que permitan monitorear aspectos como la movilidad, la coordinación motora y la respuesta a ejercicios de rehabilitación en tiempo real. Subrayó que el uso de dispositivos IoT podría ofrecer métricas más precisas, ayudando a los terapeutas a adaptar las rutinas de manera personalizada.  
|  | Además, Jairo resaltó que la integración de plataformas digitales facilitaría la comunicación entre terapeutas, médicos y familiares, asegurando que todos manejen la misma información sobre el progreso del paciente. Manifestó que sería ideal que estos sistemas presenten datos en formatos visuales claros, fáciles de interpretar y aplicables directamente a las sesiones de terapia.  
|  | Finalmente, expresó que el éxito de estas herramientas dependerá de que sean accesibles, intuitivas y adaptables a distintos contextos clínicos, ya que muchos pacientes requieren soluciones sencillas y prácticas para garantizar su adherencia. Considera que la tecnología puede convertirse en un aliado clave en la rehabilitación neurológica, siempre que se mantenga el enfoque humano y empático en el tratamiento.  


- 2.2.3 Análisis de entrevistas  

**Segmento #1: Pacientes con enfermedades neurológicas crónicas**  

Las entrevistas con Cesar Aaron Cornejo y Xin Yu Shi Lin revelan que los pacientes y cuidadores de personas con enfermedades neurológicas enfrentan desafíos importantes relacionados con la imprevisibilidad de las crisis, la dificultad de transmitir con precisión los síntomas a los profesionales de la salud y la falta de herramientas que registren datos objetivos en la vida diaria. Ambos entrevistados coincidieron en que los controles médicos periódicos resultan insuficientes para reflejar la realidad cotidiana de los pacientes, lo que genera sentimientos de inseguridad, frustración y ansiedad tanto en ellos como en sus familias.  

Cesar señaló que la imposibilidad de anticipar sus crisis epilépticas genera miedo y limita su independencia, mientras que Xin Yu Shi Lin compartió que la preocupación constante por posibles caídas o episodios de rigidez de su hermana impacta directamente en su calidad de vida como cuidador. Ambos destacaron que los registros manuales o verbales actuales no son efectivos para apoyar decisiones clínicas.  

Entre las mejoras propuestas, se resaltan:  

- **Implementar plataformas digitales con recolección de datos en tiempo real** sobre episodios, calidad del sueño y niveles de actividad, que permitan anticipar crisis o detectar anomalías.  
- **Alertas automáticas para familiares y cuidadores**, que brinden tranquilidad y apoyo inmediato en caso de emergencias.  
- **Reportes visuales claros y confidenciales para médicos**, que faciliten el ajuste de tratamientos y mejoren la comunicación entre pacientes, cuidadores y profesionales de la salud.  

Los desafíos para implementar estas soluciones incluyen la aceptación de dispositivos IoT por parte de los pacientes, quienes priorizan la comodidad, la no invasividad y la facilidad de uso. También se destacó la importancia de garantizar la confidencialidad de los datos y de que la información recopilada se utilice exclusivamente con fines médicos.  

En conclusión, los entrevistados coincidieron en que contar con una plataforma IoT integrada y confiable podría marcar una diferencia significativa en sus vidas, al brindar seguridad, apoyo continuo y una mejor comunicación con el equipo médico. Este tipo de solución no solo reduciría la ansiedad y la incertidumbre en la vida diaria, sino que también mejoraría la calidad del tratamiento y la prevención de complicaciones.  


## 2.3 Needfinding
- 2.3.1 User Personas  
En esta parte del informe presentamos a los User Personas construidos a partir de entrevistas y análisis de los segmentos objetivo de Mythicore. Estas representaciones ficticias, pero basadas en datos reales, nos permiten comprender mejor cómo piensan, qué esperan y qué problemas enfrentan nuestros usuarios. Con esta información, el equipo puede diseñar una solución alineada a necesidades auténticas y no solo a supuestos.

User Persona – Segmento 1: Paciente(epilepsia crónica):

![User Persona - Paciente](img/userperson-segmentopaciente.png)

NEUROPSICÓLOGO:

![User Persona - Neuropsicólogo](img/USER%20PERSONA-NEUROPSICOLOGO.png)



- 2.3.2 User Task Matrix  

La siguiente matriz relaciona a los roles de usuario de la plataforma **Mythicore** con las principales tareas que realizan.  
Cada tarea está asociada a una **prioridad** (Alta, Media, Baja) y una **frecuencia de uso** (Alta, Media, Baja).  
Esto permite identificar qué funciones son críticas para cada segmento objetivo.

| Rol / Usuario | Tarea | Descripción | Prioridad | Frecuencia |
|---------------|-------|-------------|-----------|------------|
| **Paciente** | Usar dispositivo IoT | El paciente utiliza los sensores para registrar datos neurológicos. | Alta | Alta |
| **Paciente** | Revisar reportes de adherencia | El paciente consulta sus métricas de uso y evolución. | Media | Media |
| **Paciente** | Recibir recordatorios | El paciente recibe notificaciones para mantener la adherencia al tratamiento. | Alta | Alta |
| **Paciente** | Participar en teleconsulta | El paciente asiste a consultas virtuales con su médico desde la plataforma. | Alta | Media |
| **Paciente** | Consultar ensayos clínicos | El paciente revisa información sobre estudios relevantes a su condición. | Media | Baja |
| **Médico** | Visualizar datos IoT | El médico consulta las señales neurológicas capturadas en tiempo real. | Alta | Alta |
| **Médico** | Recibir alertas predictivas | El médico recibe notificaciones de crisis o riesgos detectados por la IA. | Alta | Alta |
| **Médico** | Consultar dashboard de riesgos | El médico revisa el estado de riesgo de todos sus pacientes. | Alta | Media |
| **Médico** | Atender teleconsultas | El médico realiza consultas virtuales con pacientes integrando datos IoT. | Alta | Media |
| **Médico** | Exportar reportes a EHR | El médico genera exportaciones en formato FHIR para integrarlas al sistema clínico. | Media | Baja |
| **Visitante (Landing Page)** | Revisar información general | El visitante accede al sitio para conocer misión, visión y beneficios de la plataforma. | Alta | Alta |
| **Visitante (Landing Page)** | Explorar servicios | El visitante consulta la sección de telemedicina y farmacia/dispositivos. | Media | Media |
| **Visitante (Landing Page)** | Revisar sección “Quiénes somos / Qué hacemos” | El visitante comprende la identidad y propuesta de valor del proyecto. | Media | Baja |
| **Visitante (Landing Page)** | Usar formulario de contacto | El visitante envía sus datos para recibir más información. | Alta | Media |
| **Developer (API)** | Registrar pacientes vía API | El developer usa el endpoint para crear pacientes en la plataforma. | Alta | Alta |
| **Developer (API)** | Consultar datos de monitoreo | El developer obtiene información neurológica desde la API en formato JSON. | Alta | Alta |
| **Developer (API)** | Manejar errores de la API | El developer recibe mensajes de error descriptivos en caso de requests inválidos. | Alta | Media |

- 2.3.3 User Journey Mapping  
- 2.3.4 Empathy Mapping  

PACIENTES:

![Empathy Map - Pacientes](img/Empathy%20map-pacientes.png)

NEUROPSICÓLOGOS:

![Mapa de empatía Psicólogos clínicos / Neuropsicólogo](img/Mapa%20de%20empatía%20Psicólogos%20clínicos%20_%20Neuropsicólogo.png)


## 2.4 Big Picture EventStorming  

## 2.5 Ubiquitous Language  

---

# Capítulo III: Requirements Specification

## 3.1 User Stories  
---

## User Stories y Epics basadas en entrevistas

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|--------------------------|---------------------------|
| **EP01** | Monitoreo IoT de pacientes | Implementar sensores IoT (EEG, EMG, acelerometría) para capturar datos neurológicos en tiempo real. | - DADO QUE un paciente usa un dispositivo IoT, CUANDO genera datos, ENTONCES se almacenan en la nube. <br> - DADO QUE ocurre una desconexión, CUANDO se restablece, ENTONCES los datos se reenvían automáticamente. | - |
| US01.1 | Registro de episodios | Como paciente quiero que mis crisis se registren automáticamente para evitar llevar un registro manual. | - DADO QUE un paciente experimenta una crisis, CUANDO el sensor la detecta, ENTONCES se guarda en su historial. <br> - DADO QUE ocurren varias crisis, CUANDO se consultan, ENTONCES aparecen ordenadas cronológicamente. | EP01 |
| US01.2 | Envío seguro de datos | Como sistema necesito transmitir datos encriptados para garantizar confidencialidad. | - DADO QUE un sensor genera datos, CUANDO se transmiten, ENTONCES viajan cifrados. <br> - DADO QUE se detecta un error, CUANDO los datos están corruptos, ENTONCES se rechazan. | EP01 |
| US01.3 | Integración con dispositivos cómodos | Como paciente quiero que el sistema sea compatible con wearables no invasivos para poder usarlos a diario. | - DADO QUE un paciente conecta un wearable, CUANDO inicia la sesión, ENTONCES el dispositivo se sincroniza. | EP01 |
| **EP02** | Analítica con IA y alertas | Desarrollar algoritmos que detecten patrones de riesgo y generen notificaciones preventivas. | - DADO QUE existen datos, CUANDO la IA procesa señales, ENTONCES identifica patrones anómalos. <br> - DADO QUE el riesgo es crítico, CUANDO se supera un umbral, ENTONCES se genera una alerta inmediata. | - |
| US02.1 | Alerta de crisis epiléptica | Como paciente quiero recibir alertas preventivas para sentirme más seguro. | - DADO QUE el sensor detecta riesgo, CUANDO la IA lo confirma, ENTONCES se envía notificación al paciente y familiares. | EP02 |
| US02.2 | Dashboard de riesgo | Como médico quiero ver un panel de riesgo para priorizar intervenciones. | - DADO QUE un médico consulta el dashboard, CUANDO hay un cambio, ENTONCES se actualiza en tiempo real. | EP02 |
| US02.3 | Notificación a familiares | Como familiar quiero recibir alertas cuando el paciente está en riesgo para apoyarlo de inmediato. | - DADO QUE el paciente sufre una anomalía, CUANDO se emite alerta, ENTONCES llega notificación al familiar registrado. | EP02 |
| **EP03** | Telemedicina segura | Habilitar consultas virtuales integradas con datos IoT. | - DADO QUE un paciente solicita cita, CUANDO se confirma, ENTONCES se guarda en agenda. <br> - DADO QUE inicia la teleconsulta, CUANDO se transmite audio/video, ENTONCES viajan cifrados. | - |
| US03.1 | Agenda de teleconsultas | Como paciente quiero programar consultas en línea para evitar traslados innecesarios. | - DADO QUE el paciente agenda cita, CUANDO se registra, ENTONCES aparece en el calendario compartido. | EP03 |
| US03.2 | Visualización en tiempo real | Como médico quiero ver datos IoT en la consulta para tomar mejores decisiones. | - DADO QUE se desarrolla la teleconsulta, CUANDO llegan lecturas IoT, ENTONCES se muestran en pantalla. | EP03 |
| **EP04** | Integración con EHR y servicios externos | Conectar la plataforma con historias clínicas electrónicas y bases de datos externas. | - DADO QUE se actualizan datos, CUANDO se sincronizan, ENTONCES aparecen en la historia clínica. | - |
| US04.1 | Exportación de datos FHIR | Como médico quiero exportar registros en formato FHIR para integrarlos al EHR. | - DADO QUE se genera un reporte, CUANDO se exporta, ENTONCES se valida que cumple con estándar FHIR. | EP04 |
| US04.2 | Ensayos clínicos | Como paciente quiero consultar ensayos clínicos relevantes para acceder a nuevas terapias. | - DADO QUE un paciente busca ensayos, CUANDO los filtra, ENTONCES el sistema devuelve resultados relevantes. | EP04 |
| **EP05** | Adherencia y feedback | Proveer recordatorios y reportes claros para motivar al paciente. | - DADO QUE existe historial, CUANDO el paciente lo consulta, ENTONCES visualiza porcentajes y evolución. | - |
| US05.1 | Recordatorios de uso | Como paciente quiero recibir notificaciones para no olvidar mis terapias. | - DADO QUE llega la hora, CUANDO el paciente no interactúa, ENTONCES el sistema registra falta de adherencia. | EP05 |
| US05.2 | Reporte de adherencia | Como paciente quiero ver un gráfico de mi adherencia para conocer mi evolución. | - DADO QUE accede a su perfil, CUANDO consulta adherencia, ENTONCES visualiza métricas y gráficas. | EP05 |
| **EP06** | Landing Page informativa | Diseñar un sitio web estático con información, servicios y contacto. | - DADO QUE un visitante accede, CUANDO navega, ENTONCES visualiza misión, visión y servicios. | - |
| US06.1 | Información general | Como visitante quiero leer misión y beneficios para conocer la propuesta. | - DADO QUE accede a landing, CUANDO revisa sección misión, ENTONCES ve información actualizada. | EP06 |
| US06.2 | Formulario de contacto | Como visitante quiero enviar mis datos para recibir más información. | - DADO QUE llena formulario, CUANDO lo envía, ENTONCES el sistema guarda sus datos. | EP06 |
| **EP07** | API RESTful | Construcción de endpoints para interoperabilidad y manejo de datos clínicos. | - DADO QUE un developer envía request válido, CUANDO la API procesa, ENTONCES responde con datos correctos. | - |
| US07.1 | Registro de pacientes vía API | Como developer quiero registrar pacientes mediante endpoint para integrarlos al sistema. | - DADO QUE se envía POST /patients válido, CUANDO la API procesa, ENTONCES responde con 201 y el ID. | EP07 |
| US07.2 | Consulta de datos vía API | Como developer quiero consultar datos de monitoreo para integrarlos a apps externas. | - DADO QUE se envía GET /monitoring/{id}, CUANDO existe paciente, ENTONCES responde con JSON válido. | EP07 |

## 3.2 Impact Mapping  

PACIENTES:

![Impact Maps - Pacientes](img/Impact%20maps%20-pacientes.png)


NEUROPSICÓLOGO:

![Impact Maps - Neuropsicólogo](img/Impact%20maps%20-neuropsicologo.png)



## 3.3 Product Backlog  

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|-----------------|--------|-------------|--------------------------|---------------------------|
| EP01 | Monitoreo IoT | Permitir que los pacientes registren y consulten sus datos neurológicos en tiempo real mediante dispositivos IoT. | - | - |
| US01.1 | Registro de señales IoT | Como **paciente**, quiero que mis dispositivos envíen datos automáticos a la plataforma para que mi médico pueda monitorearlos. | DADO QUE el paciente tiene un dispositivo IoT conectado, CUANDO el dispositivo registra señales neurológicas, ENTONCES los datos deben almacenarse y estar disponibles en la plataforma. | EP01 |
| US01.2 | Visualización de métricas | Como **médico**, quiero visualizar en un dashboard los datos IoT de mis pacientes para identificar patrones de riesgo. | DADO QUE el médico accede al panel, CUANDO selecciona un paciente, ENTONCES debe ver sus métricas neurológicas recientes en gráficos y tablas. | EP01 |
| US01.3 | Reportes para pacientes | Como **paciente**, quiero consultar reportes simples de mis métricas para entender mi estado de salud. | DADO QUE el paciente accede al portal, CUANDO solicita un reporte, ENTONCES se le debe mostrar un resumen claro de su estado. | EP01 |
| EP02 | Inteligencia Artificial Predictiva | Implementar un modelo de IA que identifique riesgos de crisis neurológicas a partir de los datos capturados. | - | - |
| US02.1 | Generación de alertas | Como **médico**, quiero recibir alertas automáticas de riesgo alto en mis pacientes para actuar preventivamente. | DADO QUE la IA detecta un patrón de riesgo, CUANDO el valor supere un umbral configurado, ENTONCES el sistema debe generar una alerta en tiempo real. | EP02 |
| US02.2 | Notificaciones al paciente | Como **paciente**, quiero recibir notificaciones de riesgo para poder actuar antes de una crisis. | DADO QUE la IA genera una alerta, CUANDO el paciente esté registrado, ENTONCES se debe enviar una notificación a su aplicación. | EP02 |
| EP03 | Telemedicina | Ofrecer consultas virtuales entre pacientes y médicos con integración de datos neurológicos. | - | - |
| US03.1 | Agendamiento de teleconsulta | Como **paciente**, quiero agendar una teleconsulta con mi médico para recibir atención remota. | DADO QUE el paciente necesita una consulta, CUANDO selecciona fecha y hora disponibles, ENTONCES la plataforma debe registrar y confirmar la cita. | EP03 |
| US03.2 | Consulta con datos integrados | Como **médico**, quiero tener acceso a los datos IoT del paciente durante la teleconsulta para tomar mejores decisiones. | DADO QUE la teleconsulta está en curso, CUANDO el médico accede al panel, ENTONCES los datos neurológicos deben estar visibles en tiempo real. | EP03 |
| EP04 | Landing Page | Proveer un sitio estático para visitantes donde se presente información clara sobre el producto y servicios. | - | - |
| US04.1 | Información del producto | Como **visitante**, quiero conocer la propuesta de valor de Mythicore para entender cómo funciona. | DADO QUE el visitante accede al sitio, CUANDO entra a la sección principal, ENTONCES debe ver un resumen del producto y sus beneficios. | EP04 |
| US04.2 | Servicios y segmentos | Como **visitante**, quiero explorar los servicios disponibles según mi perfil (paciente, médico, institución). | DADO QUE el visitante navega en el sitio, CUANDO selecciona una sección, ENTONCES se le muestra la información adaptada a su perfil. | EP04 |
| US04.3 | Contacto | Como **visitante**, quiero enviar un mensaje de contacto para obtener más información. | DADO QUE el visitante ingresa al formulario, CUANDO completa sus datos, ENTONCES la plataforma debe registrar y enviar el mensaje al equipo. | EP04 |
| EP05 | RESTful API | Brindar una API para integradores externos (hospitales, aseguradoras, investigadores). | - | - |
| US05.1 | Registro vía API | Como **developer**, quiero registrar pacientes mediante un endpoint para integrarlos al sistema. | DADO QUE el developer hace un POST válido, CUANDO envía los datos correctos, ENTONCES el sistema debe registrar al paciente y devolver un código 201. | EP05 |
| US05.2 | Consulta de datos IoT | Como **developer**, quiero consultar las métricas de un paciente en formato JSON para integrarlas en otro sistema. | DADO QUE el developer hace un GET válido, CUANDO incluye la autorización correcta, ENTONCES la API debe devolver los datos en JSON estructurado. | EP05 |
| US05.3 | Manejo de errores | Como **developer**, quiero recibir mensajes claros de error para poder corregir mis requests. | DADO QUE el developer envía un request inválido, CUANDO el sistema lo procesa, ENTONCES la API debe devolver un error con código y mensaje descriptivo. | EP05 |


---

# Capítulo IV: Product Design

## 4.1 Style Guidelines
### 4.1.1 General Style Guidelines  

**Branding**

El logo de Aura Neuro sintetiza la esencia de innovación y confianza en el cuidado neurológico remoto. La tipografía moderna en verde vital y negro sólido refleja equilibrio entre salud, tecnología y profesionalismo.  

El concepto de “aura” transmite cercanía y bienestar, mientras que “neuro” refuerza el enfoque científico en el sistema nervioso.  
La simplicidad del diseño asegura legibilidad en cualquier soporte digital o físico, desde dispositivos móviles hasta presentaciones clínicas.  

El conjunto proyecta confianza médica, innovación tecnológica y humanización de la salud digital.  

![Logo](./img/PaletaColores/Logo.png)  
![Logo](./img/PaletaColores/LogoFondoBlanco.png)  


**Variantes de logo**  

Logo original → Verde + negro sobre fondo blanco (uso principal en web).  
![Logo](./img/PaletaColores/Logo.png)  

Logo invertido → Blanco sobre fondo negro/azul (para headers o footers oscuros).  
![Logo](./img/PaletaColores/LogoFondoBlanco.png)  

Logo minimal → Solo “Aura” o solo el ícono (para favicon y apps móviles).  

**Typography**  

La tipografía de Aura Neuro debe transmitir tecnología, claridad y accesibilidad.  
Se recomienda usar fuentes sans-serif limpias que comuniquen modernidad y precisión científica:  

- Fuente principal: Poppins o Inter (para títulos y subtítulos).  

- Poppins Bold en H1 (ej. “La neurología a distancia ya está aquí”).  

- Poppins Medium en H2.  

- Fuente secundaria: Roboto (para cuerpo de texto).  

- Roboto Regular en descripciones.  

- Roboto Light en textos secundarios.  

- El contraste de peso permite jerarquizar fácilmente la información sin saturar la interfaz.  

El lenguaje debe ser profesional pero cercano, evitando tecnicismos innecesarios y usando un tono tranquilo y confiable, ideal para pacientes y médicos.  

**Paleta de colores**  
La paleta de Aura Neuro combina la confianza médica con la innovación tecnológica:  
![PaletaColores](./img/PaletaColores/PaletaColores.png)  

### 4.1.2 Web Style Guidelines  

El sistema integral de neurología digital incorporará un módulo de búsqueda y localización en tiempo real, cuya finalidad es permitir tanto a pacientes como a médicos identificar la disponibilidad de dispositivos médicos conectados y profesionales de la salud en la red. Este componente se constituye como un elemento esencial de la plataforma, ya que asegura la eficiencia en la localización de recursos médicos y optimiza el uso de la flota de dispositivos IoT disponibles.  

En primer lugar, la plataforma contará con un sistema de geolocalización en tiempo real. Cada dispositivo IoT, como sensores EEG portátiles, medidores de sueño o cascos de estimulación neurológica, transmitirá de manera constante su ubicación y los datos registrados hacia la plataforma central. De manera complementaria, los profesionales de la salud podrán habilitar su disponibilidad geolocalizada para consultas presenciales o híbridas, lo que garantiza un acceso más ágil y preciso a los servicios médicos.  

En la aplicación móvil, los usuarios dispondrán de un mapa interactivo que mostrará la ubicación de los dispositivos médicos disponibles para préstamo o uso clínico, así como la localización de centros de salud asociados y de profesionales cercanos diferenciados por especialidad. Este diseño asegura que la información sea presentada de forma clara, visual y accesible, facilitando la toma de decisiones en tiempo real.  

El sistema también integrará filtros de búsqueda avanzada que permitirán a los usuarios seleccionar según sus necesidades específicas. Entre estos criterios se incluirán el tipo de servicio requerido (consulta virtual, presencial o híbrida), la disponibilidad de dispositivos IoT como cascos EEG o wearables de monitoreo, la especialidad médica solicitada y la proximidad en relación con la ubicación actual del paciente. Estos filtros contribuyen a personalizar la experiencia de búsqueda y a agilizar el proceso de acceso a la atención.  

Una vez identificado el dispositivo o servicio, el usuario podrá seleccionarlo directamente en la aplicación y proceder a una reserva inmediata, recibiendo confirmación automática junto con las indicaciones necesarias para el uso del equipo o la consulta médica. Este mecanismo asegura rapidez y simplicidad en la interacción, factores determinantes para mejorar la experiencia de los pacientes.  

Finalmente, el sistema también contempla una optimización para empresas o instituciones educativas que adquieran suscripciones corporativas. En estos casos, el módulo de búsqueda permitirá a los empleados o estudiantes visualizar la disponibilidad de dispositivos médicos en oficinas o campus, acceder a médicos asociados en horarios de mayor demanda y garantizar la planificación de consultas grupales o chequeos preventivos.  

En conjunto, este enfoque convierte al módulo de búsqueda en un componente clave para la medicina personalizada y preventiva, ya que no solo facilita la localización de recursos en tiempo real, sino que también mejora la accesibilidad a especialistas y fomenta un uso más eficiente de la infraestructura tecnológica disponible.  

## 4.2 Information Architecture
- 4.2.1 Organization Systems  
- 4.2.2 Labeling Systems  
- 4.2.3 SEO Tags and Meta Tags  
- 4.2.4 Searching Systems  
- 4.2.5 Navigation Systems  

## 4.3 Landing Page UI Design
### 4.3.1 Landing Page Wireframe  

- Navbar Section  
![Navbar](./img/Wireframes/LandingPage/NavbarSection.png)

- Hero Section  
![Hero](./img/Wireframes/LandingPage/HeroSection.png)

- Functions Cards Section  
![Functions](./img/Wireframes/LandingPage/FunctionsSection.png)

- Manual Section  
![Manual](./img/Wireframes/LandingPage/ManualSection.png)

- About Section  
![About](./img/Wireframes/LandingPage/AboutSection.png)

- Benefits Section  
![Benefits](./img/Wireframes/LandingPage/BeneficiesSection.png)

- Contact Section  
![Contact](./img/Wireframes/LandingPage/ContacSection.png)

- Footer Section  
![Footer](./img/Wireframes/LandingPage/FooterSection.png)  

### 4.3.2 Landing Page Mock-up  

## 4.4 Web Applications UX/UI Design
### 4.4.1 Wireframes  
- Login Page  
![Login](./img/Wireframes/Application/LoginPage.png)  
- Insert Number Page  
![InserNumberPage](./img/Wireframes/Application/InsertNumberPage.png)   
- Verify Otp Page  
![VerifyOtpPage](./img/Wireframes/Application/VerifyOtpPage.png)   
- Insert Data User Page  
![InserDataUserPage](./img/Wireframes/Application/InsertDataPage.png)  
- Inicio Page  
![InicioPage](./img/Wireframes/Application/HomePage.png)  
- Data Page  
![DataPage](./img/Wireframes/Application/DataPage.png)  
- User Page  
![UserPage](./img/Wireframes/Application/UserPage.png)  
- Recetas Page  
![RecetasPage](./img/Wireframes/Application/RecetasPage.png)  
- Chats Page  
![ChatsPage](./img/Wireframes/Application/ChatsPage.png)  
- Map Page  
![MapPage](./img/Wireframes/Application/MapsPage.png)  

### 4.4.2 Wireflow Diagrams  
![WireflowDiagrams](./img/WireflowDiagrams/WireFlowDiagramsApp.png)  
### 4.4.3 Mock-ups  
- Login Page  
![Login](./img/Mock-ups/Application/LoginPage.png)  
- Insert Number Page  
![InserNumberPage](./img/Mock-ups/Application/InsertNumberPage.png)   
- Verify Otp Page  
![VerifyOtpPage](./img/Mock-ups/Application/VerifyOtpPage.png)   
- Insert Data User Page  
![InserDataUserPage](./img/Mock-ups/Application/InsertDataUserPage.png)  
- Inicio Page  
![InicioPage](./img/Mock-ups/Application/HomePage.png)  
- Data Page  
![DataPage](./img/Mock-ups/Application/DataPage.png)  
- User Page  
![UserPage](./img/Mock-ups/Application/UserPage.png)  
- Recetas Page  
![RecetasPage](./img/Mock-ups/Application/RecetasPage.png)  
- Chats Page  
![ChatsPage](./img/Mock-ups/Application/ChatsPage.png)  
- Map Page  
![MapPage](./img/Mock-ups/Application/MapsPage.png)  
### 4.4.4 User Flow Diagrams  
![WireflowDiagrams](./img/UserFlowDiagrams/image.png)  
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
