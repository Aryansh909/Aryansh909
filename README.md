# Aryan Sharma

**AI/ML Engineer** · Computer Vision · Predictive Analytics · Intelligent Systems

Jaipur, India · [LinkedIn](https://linkedin.com/in/aryansharma72) · [Email](mailto:sendtoaryansharma@gmail.com)

---

### 🧠 About

I'm an AI/ML Engineer with a Master's in Computer Applications (AI & ML) and hands-on experience turning research-grade ideas into production-ready intelligent systems.

My work spans real-time computer vision pipelines, ensemble predictive models, and backend AI services — built to handle real constraints like low-latency inference, noisy sensor data, and concurrent request loads. I care about writing clean, modular, and tested code as much as I care about getting the model right.

I've worked across the full lifecycle: problem framing, model selection and training, API design, deployment, and documentation. I've built systems that run in production, not just Jupyter notebooks.

Currently exploring **LLM fine-tuning**, **retrieval-augmented generation (RAG)**, and **generative AI system design** as I expand into the broader foundation model ecosystem.

---

### ⚙️ Featured Projects

#### 🛡️ [ExamShield AI](https://github.com/Aryansh909/Examshield-AI)
> **Real-Time Computer Vision Proctoring System**

An end-to-end online examination proctoring engine that monitors candidate behavior in real time using a multi-threaded computer vision pipeline.

The system fuses YOLOv8 object detection (unauthorized devices, multiple persons), MediaPipe's 468-point 3D facial mesh (head pose, eye gaze, mouth state), and dlib 128-D face embeddings (continuous identity verification) — running across three independent threads to maintain smooth video throughput.

A defensive signal guard system eliminates false positives through time-window debouncing and clear-state hysteresis before violations are logged. Threat scores are computed using a weighted additive model with per-frame decay, broadcast in real time over WebSockets to an administrative monitoring dashboard.

`PyTorch` · `YOLOv8` · `MediaPipe` · `OpenCV` · `dlib` · `Flask` · `Flask-SocketIO` · `SQLite`

---

#### 🌿 [FarmSight AI](https://github.com/Aryansh909/Farmsight-AI)
> **Crop Disease Detection & Microclimate Risk Analytics**

An agricultural decision-support platform designed to assist farmers and agronomists in early disease detection and proactive crop management.

The platform accepts leaf images for pathology classification using deep learning vision models (MobileNetV2 backbone). In parallel, it evaluates real-time microclimate telemetry — temperature, relative humidity, and rainfall — to compute a quantitative Disease Risk Index (DRI) forecasting outbreak probability. Diagnosed diseases are automatically mapped to a chemical and organic treatment recommendation database covering active ingredients, dosage protocols, and pre-harvest intervals.

Built with a clean REST API, an interactive analytics dashboard (Chart.js), and SQLite-backed diagnostic history.

`PyTorch` · `MobileNetV2` · `OpenCV` · `Flask` · `Chart.js` · `SQLite`

---

#### 📈 [Project Risk Intelligence](https://github.com/Aryansh909/project-risk-intelligence)
> **Cost & Schedule Overrun Prediction Platform**

A predictive analytics engine that forecasts construction and engineering project budget overruns and completion timeline delays before they occur.

The system uses an ensemble of XGBoost and LightGBM gradient boosted regression models trained on project attributes including baseline budget, team composition, site complexity, contractor performance ratings, and seasonal weather disruption indices. Predictions come with feature importance breakdowns and scenario simulation to support resource planning decisions — not just a black-box output.

Built on a REST API that accepts structured project parameters and returns risk levels, estimated overrun ranges, and actionable mitigation insights.

`Python` · `XGBoost` · `LightGBM` · `Scikit-Learn` · `Flask` · `SQLite`

---

### 🔭 Technical Stack

**AI / Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Backend & Infrastructure**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

### 🏆 Recognition

- **Top 10 Finalist** — Innov8 Hackathon 2024 · Recognized among top teams for an AI-powered precision agriculture solution using Computer Vision
- **Professional Excellence Award** — KvonTech Consultancy Services 2026 · Awarded for outstanding discipline and technical contribution during the AI/ML internship

---

### 📌 Industry Experience

**Machine Learning Intern** — *KvonTech Consultancy Services* `Feb 2026 – Jun 2026`

Built a production-grade computer vision proctoring system from the ground up — integrating object detection, face recognition, head pose estimation, and eye gaze tracking into a unified real-time pipeline. Designed Flask REST APIs to serve AI predictions to a live monitoring dashboard. Implemented a weighted suspicion scoring mechanism and optimized inference throughput through multithreading and asynchronous processing.

**Program Executive** — *Udbhav Vision Foundation* `Aug 2023 – Jul 2024`

Managed backend operations and content engineering for **DOLBI** (Digital Online Library for the Blind in India) — a live accessibility platform serving visually impaired students across institutions. Administered user verification, access provisioning, and digital content distribution. Engineered 50+ screen-reader-compatible e-books and audiobooks to ensure assistive technology compatibility.

Platform available on [Google Play Store](https://play.google.com/store/apps/details?id=org.udbhavvision.dolbi).

---

### 📋 Certifications

- Neural Networks and Deep Learning — *Samatrix.io* (2026)
- Machine Learning and Pattern Recognition — *Samatrix.io* (2025)
- Probabilistic Modeling and Reasoning with Python — *Samatrix.io* (2025)
- Google Cloud Arcade '24 — *Google Cloud Skill Boost* (2024)

---

### 📬 Let's Connect

[LinkedIn](https://linkedin.com/in/aryansharma72) · [Email](mailto:sendtoaryansharma@gmail.com)
