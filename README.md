<h1 align="center">Hi, I'm Umang Kumar 👋</h1>

<p align="center">
  <b>Software Developer · Python Backend &amp; LLM Features</b><br/>
  I build the backend and AI pieces of a production AI CRM: LLM chatbot and summarization workers,<br/>
  the data pipelines that feed them, and the APIs that serve them.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/umang-kumar-0546b71b5/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://umangkumar.netlify.app"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:umangkumarchaudhary5@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

### 🧑‍💻 What I do

- **Software Developer at Raam Group** (multi-brand automotive dealer group, 40 showrooms, Hyderabad). I work on the group's multi-tenant AI lead CRM used by 100+ staff.
- **LLM features in production:** a red-flag chatbot where managers ask about at-risk leads in plain language (requests are scoped to the manager's branches and team before they reach the LLM), and an LLM summarization pipeline for lead emails, WhatsApp chats and notes.
- **Backend:** Strawberry GraphQL APIs on async SQLAlchemy + PostgreSQL, background processing on Celery + RabbitMQ (scheduled jobs, parallel consumers), Redis, AWS S3.
- **Data:** bulk lead ingestion with validation, vectorized pandas de-duplication and PostgreSQL `COPY` loads.
- 🔎 **Open to:** AI Engineer · GenAI / LLM Developer · Python Backend roles.

> The CRM is company code, so it's private. The projects below are my own.

---

### 🚀 Featured projects

| Project | What it does | Stack |
|---|---|---|
| **[AeroRisk](https://github.com/umangkumarchaudhary/AeroRisk)** | Predicts whether an aviation accident turns severe, trained on 29.9k NTSB records. Used SHAP to catch **target leakage** in v1 and rebuilt it: **XGBoost ROC-AUC 0.70** on a 2020–26 time-based test set vs 0.64 logistic baseline. | Python · XGBoost · SHAP · PostgreSQL · Prefect · FastAPI |
| **[Medic](https://github.com/umangkumarchaudhary/Server-Failure-Prediction-System-MLops)** · [live API](https://server-failure-prediction-system-mlops.onrender.com/docs) | A Python agent streams server, Docker and log signals to a multi-tenant API; a risk engine scores 22 weighted signals to raise and resolve alerts, with per-tenant **data drift detection** (KS-test, PSI). | Python · FastAPI · PostgreSQL · Docker |
| **[SentinelMarket](https://github.com/umangkumarchaudhary/SentinelMarket-Backend)** · [live](https://sentinelmarket.netlify.app/) | ETL loads NSE/BSE price and volume data into PostgreSQL; 47 engineered features feed an **Isolation Forest** that scores each stock 0–100 for unusual trading. | Python · scikit-learn · PostgreSQL · FastAPI |
| **[TruthGuard](https://github.com/umangkumarchaudhary/TruthGuard---AI-Hallucination-Detection-Compliance-Platform)** · [live](https://truthguard-ai.vercel.app) | Checks LLM outputs for unsupported claims and policy issues and keeps an audit trail of each check. | FastAPI · Next.js · Gemini · Supabase |
| **[RiskAdvisor](https://github.com/umangkumarchaudhary/RiskAdvisor--ENTERPRISE-DECISION-INTELLIGENCE-PLATFORM)** | Decision layer on top of AeroRisk: integer linear programming (PuLP) and Monte Carlo simulation pick the safety measures that cut the most risk within a budget. | Python · PuLP · NumPy |

---

### 🛠️ Tech I use

**AI & ML**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LLM](https://img.shields.io/badge/LLM_integration-412991?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend**<br/>
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

**Data**<br/>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![Prefect](https://img.shields.io/badge/Prefect_ETL-024DFD?style=flat-square&logo=prefect&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Also built with:** React · Next.js · Node.js · TypeScript · Flutter (dealership websites, tracking systems and admin panels)

---

### 📌 A bit more

- 🎓 B.Tech, Computer Science & Engineering, Lovely Professional University (2024)
- 🧩 560+ LeetCode problems solved
- 📜 NLP Specialization (DeepLearning.AI) · Unsupervised Learning (Stanford) · Azure Fundamentals

