<div align="center">

# Aryan Sharma

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=AI+%2F+ML+Engineer;Computer+Vision+Systems+Developer;Predictive+Analytics+Engineer;Building+Intelligent%2C+Production-Ready+AI)](https://github.com/Aryansh909)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Aryan%20Sharma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryansharma72)
[![Email](https://img.shields.io/badge/Email-sendtoaryansharma%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sendtoaryansharma@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Aryansh909-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aryansh909)

📍 Jaipur, India &nbsp;|&nbsp; 🎓 MCA — AI & ML, JECRC University

</div>

---

## 👨‍💻 About Me

I'm an AI/ML Engineer with a Master's in Computer Applications (AI & ML) and hands-on industry experience building end-to-end intelligent systems — from real-time computer vision pipelines and multi-threaded inference architectures to ensemble predictive models and production Flask APIs.

I believe good AI engineering isn't just about training a model — it's about designing systems that are modular, well-tested, and ready for production. Every project I build is backed by clean code, documented architecture, and automated test coverage.

Currently deepening my expertise in **Generative AI**, **LLM fine-tuning**, and **Retrieval-Augmented Generation (RAG)** as I move further into the foundation model space.

---

## 🚀 Featured Projects

### 🛡️ [ExamShield AI](https://github.com/Aryansh909/Examshield-AI) — Real-Time Computer Vision Proctoring System

> *Built during ML Internship at KvonTech Consultancy Services (2026)*

An end-to-end online proctoring engine that monitors candidate behavior in real time using a multi-threaded computer vision pipeline. Integrates **YOLOv8** (device & multi-person detection), **MediaPipe** 468-point 3D facial mesh (head pose, gaze, mouth state), and **dlib** 128-D face embeddings (continuous identity verification) — all running across independent threads to maintain video throughput without frame drops.

A **defensive signal guard system** eliminates false positives using time-window debouncing and clear-state hysteresis. Threat scores are computed via a weighted additive model with per-frame decay and pushed live over WebSockets to an administrative dashboard. Backed by a full **pytest** suite and a Flask REST API serving 18 endpoints.

`PyTorch` · `YOLOv8` · `MediaPipe` · `OpenCV` · `dlib` · `Flask` · `Flask-SocketIO` · `SQLite`

---

### 🌿 [FarmSight AI](https://github.com/Aryansh909/Farmsight-AI) — Crop Disease Detection & Microclimate Risk Analytics

An agricultural decision-support platform that classifies plant leaf diseases from field images and forecasts disease outbreak risk from microclimate telemetry data.

The computer vision module classifies leaf pathologies using a **MobileNetV2** deep learning backbone. In parallel, the microclimate engine computes a quantitative **Disease Risk Index (DRI)** from real-time humidity, temperature, and rainfall inputs. Diagnosed diseases are automatically mapped to a chemical and organic treatment recommendation database with active ingredient dosages and pre-harvest intervals. Interactive analytics delivered via **Chart.js** visualizations and a clean REST API.

`PyTorch` · `MobileNetV2` · `OpenCV` · `Flask` · `Chart.js` · `SQLite`

---

### 📊 [Project Risk Intelligence](https://github.com/Aryansh909/project-risk-intelligence) — Cost & Schedule Overrun Prediction Platform

A predictive analytics engine that forecasts construction and engineering project budget overruns and completion timeline delays using ensemble machine learning.

The system trains and evaluates **XGBoost** and **LightGBM** gradient boosting regressors through hyperparameter optimization and rigorous feature engineering — including baseline budget variance, site complexity indices, contractor performance scores, and seasonal weather disruption factors. Predictions include **explainable feature importance breakdowns** and **scenario-based forecasting**, making the system a decision intelligence tool rather than just a black-box predictor.

`Python` · `XGBoost` · `LightGBM` · `Scikit-Learn` · `Pandas` · `Flask` · `SQLite`

---

## 🛠️ Tech Stack

**AI & Machine Learning**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

**Backend & Databases**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)

**Developer Tools & Environment**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)

---

## 💼 Experience

**🏢 Machine Learning Intern** &nbsp;·&nbsp; *KvonTech Consultancy Services Pvt. Ltd.* &nbsp;·&nbsp; `Feb 2026 – Jun 2026`

- Built a production-grade AI proctoring system integrating YOLOv8, MediaPipe, face recognition, and weighted suspicion scoring into a unified real-time pipeline
- Developed Flask REST APIs connecting multiple AI models to a live monitoring dashboard with WebSocket-based telemetry
- Optimized inference throughput through multi-threading, asynchronous processing, and efficient frame handling to reduce detection latency
- Reduced false positive rates through implementation of debounce, hysteresis, and per-event cooldown mechanisms

---

**🏢 Program Executive** &nbsp;·&nbsp; *Udbhav Vision Foundation* &nbsp;·&nbsp; `Aug 2023 – Jul 2024`

- Administered user authentication, access control, content management, and institutional onboarding for the **DOLBI** platform — a digital accessibility ecosystem serving visually impaired students
- Engineered 50+ screen-reader-compatible e-books and audiobooks optimized for assistive technologies (NVDA, JAWS)
- Coordinated with cross-functional teams and CSR partners to onboard educational institutions and streamline digital content workflows

📱 DOLBI is live on [Google Play Store](https://play.google.com/store/apps/details?id=org.udbhavvision.dolbi)

---

## 🏆 Recognition & Awards

| Award | Organization | Year |
|:---|:---|:---|
| 🥇 Professional Excellence Recognition | KvonTech Consultancy Services | 2026 |
| 🏅 Top 10 Finalist — Innov8 Hackathon | AI-Powered Precision Agriculture (Computer Vision) | 2024 |
| ☁️ Google Cloud Arcade | Google Cloud Skill Boost — ML, Cloud Infrastructure & Computing Paths | 2024 |
| 🤝 Certificate of Appreciation | 7-Day Digital Literacy Workshop (DOLBI Initiative) | 2024 |

---

## 📜 Certifications

- **Neural Networks and Deep Learning** — Samatrix.io *(2026)*
- **Machine Learning and Pattern Recognition** — Samatrix.io *(2025)*
- **Probabilistic Modeling and Reasoning with Python** — Samatrix.io *(2025)*
- **R Programming for Data Science and Analytics** — Samatrix.io *(2024)*
- **RDBMS & Software Engineering** — Infosys Springboard *(2024)*

---

## 📊 Most Used Languages

<div align="center">

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Aryansh909&layout=compact&theme=github_dark&hide_border=true&langs_count=8&card_width=500)](https://github.com/Aryansh909)

</div>

---

## 📬 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryansharma72)
[![Email](https://img.shields.io/badge/Send%20an%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sendtoaryansharma@gmail.com)

</div>
