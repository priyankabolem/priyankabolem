# Priyanka Bolem: Machine Learning Engineer

Production ML over high-volume, real-time data: predictive and probabilistic modeling, uncertainty estimation, large-scale feature engineering, and the MLOps to keep it running: low-latency inference on AWS SageMaker, distributed pipelines (Spark, Databricks, Airflow), and drift/decay monitoring in production.
4+ years shipping models in healthcare (Truveta) and banking (Capgemini). MS Computer Science, Northwest Missouri State University (May 2025).

**Currently:** Machine Learning Engineer at Truveta, Seattle: predictive and probabilistic models and ML pipelines over de-identified EHR data.

**Portfolio:** [priyankabolem.github.io](https://priyankabolem.github.io) · **Resume:** [Download](https://priyankabolem.github.io/resume.pdf)

---

## Featured projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| **Financial Sentiment MLOps Platform** | End-to-end sentiment platform for financial text: FinBERT fine-tune, multi-source ingestion (News API / Alpha Vantage / Reddit), DVC-versioned training, MLflow registry, containerized FastAPI service, K8s HPA manifests, Prometheus/Grafana + Evidently drift monitoring, GitHub Actions CI/CD with pytest. | FinBERT · Transformers · DVC · MLflow · FastAPI · Docker · Kubernetes · Prometheus · Grafana · Evidently · GitHub Actions | [Repo](https://github.com/priyankabolem/financial-sentiment-mlops) · [Live demo](https://huggingface.co/spaces/Priyabolem/financial-sentiment-analysis) |
| **Credit Card Fraud Detection: Production MLOps** *(in active development)* | Fraud scoring on 284,807 transactions / 0.17% fraud, AUPRC-driven evaluation, XGBoost, MLflow registry, Airflow retraining, Evidently drift, FastAPI on AWS ECR → ECS Fargate with S3 + CloudWatch, Claude-API RAG explainability layer, uv + pyproject. | XGBoost · MLflow · Airflow · Evidently · FastAPI · AWS ECS Fargate · S3 · CloudWatch · RAG | [Repo](https://github.com/priyankabolem/fraud-detection-mlops) |
| **NWMSU RAG Chatbot** | Hybrid retrieval (Neo4j knowledge graph + OpenAI embeddings) over university information, orchestrated with LangChain, served in Streamlit. | Neo4j · OpenAI embeddings · LangChain · Streamlit | [Repo](https://github.com/priyankabolem/RAG-Chatbot-1) · [Live demo](https://nwmsu-rag-chatbot.streamlit.app) (free tier, may be asleep) |
| **Plant Disease Detection** *(demo weights, architecture showcase)* | Custom TensorFlow/Keras CNN, 38 classes across 14 species, Grad-CAM explanations, Docker + CI. Weights are demo-grade pending a full training run (see MODEL_STATUS in repo). | TensorFlow · Keras · Grad-CAM · Docker · CI | [Repo](https://github.com/priyankabolem/plant-disease-detection) · [Live demo](https://huggingface.co/spaces/Priyabolem/plant-disease-detection) |
| **Lending Club Loan Default Prediction** | ~38k loans; Logistic Regression / Decision Tree / Random Forest / XGBoost; ~84% accuracy, ROC-AUC > 0.85; class-imbalance handling and threshold tuning. | Scikit-learn · XGBoost · Pandas | [Repo](https://github.com/priyankabolem/lendingclub-loan-default-prediction) |
| **NutriGuide+** | AI nutrition assistant: TensorFlow food-image classification plus nutrition insights, Streamlit UI. | TensorFlow · Streamlit | [Repo](https://github.com/priyankabolem/nutriguide-plus) |

## Experience

- **Machine Learning Engineer, Truveta**, Seattle, WA, Jun 2025 - Present. SageMaker Pipelines/Endpoints + CloudWatch for real-time risk scoring on de-identified EHR data; TensorFlow disease-progression models; Bayesian Optimization + Monte Carlo uncertainty quantification; GA + RL hybrid optimization (+22% outcome-prediction accuracy); BERT embeddings over clinical text; −35% training/data-prep time via SQL and pipeline optimization.
- **Machine Learning Engineer, Capgemini**, India, Apr 2019 - Nov 2022. Credit default / delinquency / fraud models (Scikit-learn, XGBoost, LightGBM) embedded in origination, collections and fraud triage (−25% loan decision cycle time); automated ETL (−40% data-prep time); Azure Databricks distributed training; Airflow orchestration; drift/accuracy monitoring (−20% false positives).

## Skills

- **Languages:** Python, SQL, R
- **ML / DL:** PyTorch, TensorFlow, Keras, Scikit-learn, XGBoost, LightGBM, Hugging Face Transformers, OpenCV
- **Modeling:** Bayesian Optimization, Monte Carlo, Genetic Algorithms, Reinforcement Learning, calibration, uncertainty estimation
- **GenAI / NLP:** BERT/FinBERT, LLaMA, GPT-4, LangChain, LangGraph, RAG, vector DBs, Neo4j
- **Data / Pipelines:** Spark, Kafka, Airflow, Databricks, DVC, ETL
- **MLOps:** SageMaker (Pipelines/Endpoints), MLflow, Docker, Kubernetes, FastAPI, GitHub Actions, Evidently, Prometheus/Grafana, CloudWatch
- **Cloud:** AWS (SageMaker, Lambda, EC2, ECS, S3), Azure (ML Studio, Databricks)
- **Visualization:** Tableau, Power BI, Plotly

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) ![AWS](https://img.shields.io/badge/AWS_SageMaker-232F3E?logo=amazonwebservices&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-0194E2?logo=mlflow&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white)

## Contact

- Email: [priyankabolem93@gmail.com](mailto:priyankabolem93@gmail.com)
- LinkedIn: [linkedin.com/in/priyanka-bolem](https://www.linkedin.com/in/priyanka-bolem)
- Hugging Face: [huggingface.co/Priyabolem](https://huggingface.co/Priyabolem)
- Website: [priyankabolem.github.io](https://priyankabolem.github.io)
- Greater Seattle, WA · +1 206-305-6760
