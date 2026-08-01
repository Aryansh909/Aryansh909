<div align="center">

# Aryan Sharma

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=58A6FF&center=true&vCenter=true&width=520&lines=AI+%2F+ML+Engineer;Computer+Vision+%7C+Predictive+Analytics;Building+AI+that+works+in+production)](https://github.com/Aryansh909)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-aryansharma72-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryansharma72)
[![Email](https://img.shields.io/badge/Email-sendtoaryansharma%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sendtoaryansharma@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Aryansh909-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Aryansh909)

📍 Jaipur, India &nbsp;·&nbsp; MCA — AI & ML, JECRC University

</div>

---

## About

MCA graduate in AI & ML from JECRC University with industry experience building computer vision systems, predictive analytics pipelines, and backend AI services. I've worked across the full lifecycle of AI projects — model training and evaluation, REST API design, system testing, and deployment — across both academic and professional settings.

My recent work includes a real-time multi-model proctoring system built during my ML internship at KvonTech, a crop disease detection and risk forecasting platform, and an ensemble-based project cost prediction system. I write production code: modular, documented, and tested.

Currently working on expanding into generative AI — specifically LLM fine-tuning and RAG architectures.

---

## Projects

### 🛡️ [ExamShield AI](https://github.com/Aryansh909/Examshield-AI) — Computer Vision Proctoring System

Built during my ML internship at KvonTech. The core challenge was running three CV models simultaneously — YOLOv8 object detection, MediaPipe 3D facial mesh, and dlib face verification — without dropping frames. Solved it with independent inference threads and a signal guard layer (debounce + hysteresis) that absorbs transient noise before anything gets flagged as a violation. Suspicion scores update every frame and push live to an admin dashboard over WebSockets. The whole thing is backed by a Flask REST API across 18 endpoints and a pytest suite that runs fully without a webcam attached.

`PyTorch` · `YOLOv8` · `MediaPipe` · `OpenCV` · `dlib` · `Flask` · `Flask-SocketIO` · `SQLite`

---

### 🌿 [FarmSight AI](https://github.com/Aryansh909/Farmsight-AI) — Crop Disease Detection & Risk Analytics

Two things running in parallel: a MobileNetV2 model classifying leaf diseases from field images, and a microclimate engine computing a Disease Risk Index from humidity, temperature, and rainfall readings. Diagnosed conditions map directly to a treatment database with active ingredients, dosage protocols, and pre-harvest intervals. The goal was actionable output — not just "disease detected" but a clear path to what to do about it.

`PyTorch` · `MobileNetV2` · `OpenCV` · `Flask` · `Chart.js` · `SQLite`

---

### 📈 [Project Risk Intelligence](https://github.com/Aryansh909/project-risk-intelligence) — Cost & Schedule Overrun Prediction

An ensemble ML system that forecasts project budget overruns and timeline delays before they happen. The models (XGBoost + LightGBM) were straightforward — the interesting part was the feature engineering: baseline budget variance, contractor performance scores, site complexity indices, and seasonal disruption factors. Predictions come with feature importance breakdowns and scenario simulation, so it functions as a planning tool, not just a risk score.

`Python` · `XGBoost` · `LightGBM` · `Scikit-Learn` · `Flask` · `SQLite`

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**Machine Learning & Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=flat-square&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21F?style=flat-square&logo=huggingface&logoColor=black)

**Computer Vision & NLP**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=flat-square&logoColor=black)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logoColor=white)
![dlib](https://img.shields.io/badge/dlib-008000?style=flat-square&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154f3c?style=flat-square&logoColor=white)

**Data & Visualization**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square&logoColor=white)

**Backend, Databases & Infrastructure**

![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

## 💼 Experience

**Machine Learning Intern** · KvonTech Consultancy Services &nbsp;`Feb 2026 – Jun 2026`

Built a production-grade proctoring system from scratch — object detection, face recognition, head pose estimation, and gaze tracking unified into a single real-time pipeline. Designed and deployed Flask REST APIs, implemented a weighted suspicion scoring system, and reduced false positives through signal guard mechanisms. Optimized inference throughput through multithreading and async processing.

**Program Executive** · Udbhav Vision Foundation &nbsp;`Aug 2023 – Jul 2024`

Managed backend operations for [DOLBI](https://play.google.com/store/apps/details?id=org.udbhavvision.dolbi) — a live digital accessibility platform for visually impaired students. Engineered 50+ screen-reader-compatible e-books and audiobooks. Handled user access provisioning, institutional onboarding, and digital content workflows.

---

## 🏆 Recognition

| | Award | Year |
|:---|:---|:---|
| 🥇 | Professional Excellence Recognition — KvonTech Consultancy Services | 2026 |
| 🏅 | Top 10 Finalist — Innov8 Hackathon (AI Precision Agriculture) | 2024 |
| ☁️ | Google Cloud Arcade — Cloud Skill Boost completion & rewards | 2024 |
| 🤝 | Certificate of Appreciation — Digital Literacy Workshop (DOLBI) | 2024 |

---

## 📜 Certifications

- Neural Networks and Deep Learning — *Samatrix.io* (2026)
- Machine Learning and Pattern Recognition — *Samatrix.io* (2025)
- Probabilistic Modeling and Reasoning with Python — *Samatrix.io* (2025)
- R Programming for Data Science and Analytics — *Samatrix.io* (2024)
- RDBMS & Software Engineering — *Infosys Springboard* (2024)

---

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/aryansharma72)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sendtoaryansharma@gmail.com)
