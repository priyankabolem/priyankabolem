# Priyanka Bolem: AI and Machine Learning Engineer

Production AI and ML for regulated, high-volume businesses: LLM assistants, chatbots and voicebots on Microsoft Foundry, predictive and probabilistic models on AWS SageMaker, and the MLOps that keeps them running (Airflow, MLflow, Docker, Kubernetes, drift monitoring).
6+ years in software engineering, 5+ of them shipping production ML and AI systems for healthcare, enterprise and banking clients. MS Computer Science, Northwest Missouri State University (Dec 2024).

**Currently:** AI Engineer in the Seattle area, leading the AI automation of a member contact center: an LLM-based representative assist that cut average handle time about 30 percent, plus a chatbot and an IVR voicebot driven by an intent model.

**Portfolio:** [priyankabolem.github.io](https://priyankabolem.github.io) · **Resume:** [Download](https://priyankabolem.github.io/resume.pdf)

---

## Featured projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **Financial Sentiment MLOps Platform** | End-to-end sentiment platform for financial text: FinBERT fine-tune, multi-source ingestion (News API / Alpha Vantage / Reddit), DVC-versioned training, MLflow registry, containerized FastAPI service, K8s HPA manifests, Prometheus/Grafana + Evidently drift monitoring, GitHub Actions CI/CD with pytest. | FinBERT · Transformers · DVC · MLflow · FastAPI · Docker · Kubernetes · Prometheus · Grafana · Evidently · GitHub Actions | [Repo](https://github.com/priyankabolem/financial-sentiment-mlops) · [Live demo](https://huggingface.co/spaces/Priyabolem/financial-sentiment-analysis) |
| **Grocery Product Search and Re-ranking on Google Cloud** | Two-stage product search over an Instacart catalog in BigQuery: Vertex AI Search retrieval, a gradient boosting re-ranker served from a Vertex AI endpoint scoring reorder propensity, and a FastAPI service on Cloud Run blending both into the final ranking with a retrieval-order fallback; Docker, unit tests, GitHub Actions CI. | Vertex AI Search · Vertex AI Endpoints · BigQuery · Cloud Run · scikit-learn · FastAPI · Docker · GitHub Actions | [Repo](https://github.com/priyankabolem/grocery-search-vertex) |
| **Credit Card Fraud Detection: Production MLOps** | Fraud scoring on 284,807 transactions / 0.17% fraud with a chronological split: XGBoost vs logistic baseline (test AUPRC 0.765 vs 0.718, ROC-AUC 0.979), threshold set for a 0.90 precision budget, MLflow tracking, FastAPI serving of the exact evaluated artifact, PSI drift monitoring that flags the day-over-day feature shift, Docker, CI with 10 tests. | XGBoost · MLflow · FastAPI · Docker · PSI drift monitoring · GitHub Actions · pytest | [Repo](https://github.com/priyankabolem/fraud-detection-mlops) |
| **NWMSU RAG Chatbot** | Hybrid retrieval (Neo4j knowledge graph + OpenAI embeddings) over university information, orchestrated with LangChain, served in Streamlit. | Neo4j · OpenAI embeddings · LangChain · Streamlit | [Repo](https://github.com/priyankabolem/RAG-Chatbot-1) · [Live demo](https://nwmsu-rag-chatbot.streamlit.app) (free tier, may be asleep) |
| **Plant Disease Detection** *(demo weights, architecture showcase)* | Custom TensorFlow/Keras CNN, 38 classes across 14 species, Grad-CAM explanations, Docker + CI. Weights are demo-grade pending a full training run (see MODEL_STATUS in repo). | TensorFlow · Keras · Grad-CAM · Docker · CI | [Repo](https://github.com/priyankabolem/plant-disease-detection) · [Live demo](https://huggingface.co/spaces/Priyabolem/plant-disease-detection) |
| **Lending Club Loan Default Prediction** | ~38k loans; Logistic Regression / Decision Tree / Random Forest / XGBoost; ~84% accuracy, ROC-AUC > 0.85; class-imbalance handling and threshold tuning. | Scikit-learn · XGBoost · Pandas | [Repo](https://github.com/priyankabolem/lendingclub-loan-default-prediction) |
| **NutriGuide+** | AI nutrition assistant: TensorFlow food-image classification plus nutrition insights, Streamlit UI. | TensorFlow · Streamlit | [Repo](https://github.com/priyankabolem/nutriguide-plus) |

## Experience

Employers and clients are named on the [resume](https://priyankabolem.github.io/resume.pdf).

- **AI Engineer, health insurer, member contact center**, Seattle area, Jul 2026 - Present. Intent classification over historical inquiries; a representative assist that summarizes claims, billing and member data during the call (average handle time from about 13 minutes to about 9); automated post-call documentation; chatbot and IVR voicebot through Genesys APIs; Portkey to Microsoft Foundry, Redis, Dynamics CRM and AWS.
- **Machine Learning Engineer, global technology manufacturer**, Remote, Dec 2025 - Jun 2026. Sales and service application over an internal system of millions of records, wired through APIs to Microsoft Foundry; LinkedIn data in Dataverse with AI recommendations so sales representatives close deals faster; AI analytics dashboards for leadership.
- **Machine Learning Engineer, healthcare data platform**, Seattle, WA, Feb 2025 - Nov 2025. SageMaker Pipelines/Endpoints + CloudWatch for real-time risk scoring on de-identified EHR data; TensorFlow disease-progression models; Bayesian Optimization + Monte Carlo uncertainty quantification; GA + RL hybrid optimization (+22% outcome-prediction accuracy); BERT embeddings over clinical text; 35% less training/data-prep time.
- **Machine Learning Engineer, banking and financial services**, India, Apr 2019 - Nov 2022. Credit default / delinquency / fraud models (Scikit-learn, XGBoost, LightGBM) embedded in origination, collections and fraud triage (25% shorter loan decision cycle); automated ETL (40% less data-prep time); Azure Databricks; Airflow; drift/accuracy monitoring (20% fewer false positives).
- **Junior Software Engineer, Android application development**, India, Feb 2018 - Mar 2019. Java, Python and Android application development.

## Skills

- **Languages:** Python, SQL, Java, R
- **ML / DL:** PyTorch, TensorFlow, Keras, Scikit-learn, XGBoost, LightGBM, Hugging Face Transformers, OpenCV
- **Modeling:** Bayesian Optimization, Monte Carlo, Genetic Algorithms, Reinforcement Learning, calibration, uncertainty estimation
- **GenAI / NLP:** LLM assistants, Microsoft Foundry, Portkey, intent classification, summarization, chatbots and voicebots, Genesys, RAG, LangChain, LangGraph, BERT/FinBERT, GPT-4, LLaMA, vector DBs, Neo4j
- **Data / Pipelines:** Spark, Kafka, Airflow, Databricks, Redis, Dataverse, DVC, ETL
- **MLOps:** SageMaker (Pipelines/Endpoints), MLflow, Docker, Kubernetes, FastAPI, GitHub Actions, Evidently, Prometheus/Grafana, CloudWatch
- **Cloud:** AWS (SageMaker, Lambda, EC2, ECS, S3), Azure (ML Studio, Databricks), Microsoft Foundry, GCP (Vertex AI, BigQuery, Cloud Run)
- **Visualization:** Tableau, Power BI, Plotly

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) ![AWS](https://img.shields.io/badge/AWS_SageMaker-232F3E?logo=amazonwebservices&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)

## Contact

- Email: [priyankabolem93@gmail.com](mailto:priyankabolem93@gmail.com)
- LinkedIn: [linkedin.com/in/priyanka-bolem](https://www.linkedin.com/in/priyanka-bolem)
- Hugging Face: [huggingface.co/Priyabolem](https://huggingface.co/Priyabolem)
- Website: [priyankabolem.github.io](https://priyankabolem.github.io)
- Greater Seattle, WA · +1 206-305-6760
