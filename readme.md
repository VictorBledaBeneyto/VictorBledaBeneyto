Aquí tienes el perfil completo actualizado. He añadido Nexus a "Proyectos Destacados" y actualizado el stack para incluir Go, TypeScript, React y Redis que usas en ese proyecto:

---

# ¡Hola! Soy Víctor Bleda Beneyto 👋

### 👨‍💻 Desarrollador de Software | Especialista en IA & Big Data

Soy un desarrollador apasionado por crear soluciones tecnológicas eficientes, con especial enfoque en arquitecturas distribuidas y el análisis inteligente de datos. Actualmente, estoy cursando el **Máster en IA y Big Data** para integrar modelos de visión artificial y procesamiento de datos masivos en aplicaciones escalables.

---

### 🚀 Sobre mí

- 🎓 **Formación:** Máster en IA/Big Data, Grado Superior en DAM y Grado Medio en SMR.
- 🌍 **Experiencia Internacional:** Erasmus+ como Técnico Informático en la **Base Naval de Lisboa (CITAN)**, Portugal.
- 🏆 **Reconocimientos:** 3er Premio en la 3ª Edición de Premios de Transferencia del Conocimiento FP por el proyecto **VenarIQ**.
- 💼 **Perfil Híbrido:** Cuento con base en gestión administrativa, lo que me aporta una visión organizada y centrada en procesos de negocio.

---

### 🛠️ Stack Tecnológico

| Categoría | Tecnologías |
| :--- | :--- |
| **Lenguajes** | Go, Java, Kotlin, Python, TypeScript, PHP, SQL |
| **IA & Data Science** | PyTorch (ResNet), YOLOv8, NumPy, Pandas, PySpark, Scikit-learn, spaCy, Redes Neuronales (Keras/MLP) |
| **Arquitectura & Data** | Apache Kafka (Event-Driven), Apache Airflow, FastAPI, PostgreSQL, Redis, MinIO (S3), Firebase |
| **Mobile & Web** | React, Tailwind CSS, Flutter, WordPress, Flask (API REST), Streamlit |
| **Herramientas & IoT** | Git, Docker & Docker Compose, Power BI, Odoo, Home Assistant, MQTT |

---

### 📊 Proyectos Destacados

#### 💬 [Nexus — Plataforma de Mensajería en Tiempo Real](https://github.com/VictorBledaBeneyto/Nexus)
Plataforma de mensajería de nivel producción con workspaces, canales, hilos, reacciones, presencia e indicadores de escritura — arquitectura similar a Slack.
- **Backend:** API REST + WebSocket en **Go** (Chi, gorilla/websocket); Hub goroutine con fan-out eficiente y cero mutexes.
- **Tiempo real:** Escalado horizontal mediante **Redis Pub/Sub** — un mensaje enviado a una instancia llega a todos los clientes conectados a otras instancias.
- **Frontend:** SPA en **React + TypeScript + Tailwind CSS** con estado global en **Zustand**, actualizaciones optimistas y reconexión automática con backoff exponencial.
- **Búsqueda:** Full-text search con **PostgreSQL tsvector** y salto directo al mensaje con resaltado visual.
- **Infraestructura:** Presencia online/offline con **Redis Sorted Sets**, JWT (HMAC-SHA256), métricas **Prometheus** y trazas **OpenTelemetry → Jaeger**, desplegado con Docker Compose.

#### 🏥 [TriageIA — Priorización Médica Automática](https://github.com/VictorBledaBeneyto/TriageIA-Priorizaci-nM-dica-Autom-tica)
Sistema de soporte a la decisión clínica que transforma el relato del paciente en una prioridad Manchester (C1–C5) mediante modelos NLP entrenados localmente.
- **Dataset:** 272 entrevistas OSCE simuladas *(Fareez et al., 2022 — Nature Scientific Data)*.
- **Pipeline NLP:** Extracción de entidades con **spaCy**, normalización clínica EN/ES y clasificación Manchester con **scikit-learn**.
- **Infraestructura:** Orquestación con **Apache Airflow**, almacenamiento en **MinIO**, API de inferencia en **FastAPI** y dashboard clínico en **Streamlit**, desplegados con Docker Compose.
- **Auditoría ética:** Detección y rechazo automático de casos de under-triage (C2 clasificado como C3 o inferior).

#### 👤 [Detección y Pixelado de Rostros](https://github.com/VictorBledaBeneyto/DeteccionYPixeladoDeImagenes)
Sistema distribuido basado en eventos (Event-Driven) para el cumplimiento de privacidad en imágenes.
- **Arquitectura:** Microservicios coordinados mediante **Apache Kafka** (sin llamadas HTTP síncronas).
- **IA:** Pipeline de visión artificial con **YOLOv8** para detección y **ResNet-50 (PyTorch)** para estimación de edad.
- **Infraestructura:** Almacenamiento en **MinIO (S3)**, base de datos PostgreSQL y despliegue orquestado con **Docker Compose**.
- **Analítica:** Dashboard en **Power BI** para monitorizar el rendimiento del pipeline y métricas del modelo.

#### 🔋 [Eficiencia Energética - Aula IoT](https://github.com/VictorBledaBeneyto/Eficiencia-Energ-tica---Aula-IoT)
Sistema predictivo de derroche energético en entornos educativos.
- **Arquitectura:** Implementación de arquitectura Medallion (Bronze, Silver, Gold).
- **IA:** Creación de un "sensor virtual" de calefacción mediante ML y predicción de derroche a 1h vista con Redes Neuronales.
- **Despliegue:** API REST en Flask y monitorización en tiempo real con Grafana.

#### 🌟 3º Puesto [VenarIQ](https://fpempresa.net/iii-edicion-premios-transferencia-de-conocimiento-de-la-fp/)
Plataforma web premiada diseñada para visibilizar y promover el talento femenino en entornos profesionales.

#### 🤖 Chatbot IA - Flutter
Desarrollo de un asistente inteligente para la generación automatizada de presupuestos con integración en Firebase.

---

### 🎯 Skills & Competencias

- **Soft Skills:** Liderazgo (Delegado de clase), Trabajo en equipo, Resiliencia, Adaptabilidad y Orientación a resultados.
- **Idiomas:** Valenciano (Nativo), Español (Nativo), Inglés (B2).

---

### 📫 Conecta conmigo

- 💼 [LinkedIn](https://www.linkedin.com/in/victor-bleda-beneyto-4a9a90237)
- 🌐 [Mi Perfil de GitHub](https://github.com/VictorBledaBeneyto)
- 💻 [Web Personal](https://victorbledabeneyto.com/)

---

### ⚡ Fun Fact
Además de programar, tengo experiencia coordinando grupos como Monitor de Tiempo Libre, lo que me ha dado herramientas clave para la comunicación efectiva y la resolución de conflictos bajo presión.

---

Cambios realizados:
- **Stack:** añadidos Go, TypeScript, React, Tailwind CSS y Redis
- **Nexus:** insertado como primer proyecto (el más reciente y técnicamente complejo en backend)
