# Priyanka Bolem

**Machine Learning Engineer, Greater Seattle, WA.** I build agentic AI and RAG systems that run in production, and the MLOps on AWS and GCP that keeps them running.

Multi-step agent workflows, permission-aware retrieval, MCP tool integrations and LLM evaluation pipelines today, built on deep learning and prediction work over de-identified healthcare data.

**[Portfolio](https://priyankabolem.github.io)** · [priyankabolem93@gmail.com](mailto:priyankabolem93@gmail.com)

---

## Flagship projects

| Project | What it is | Measured result |
|---|---|---|
| **[financial-sentiment-mlops](https://github.com/priyankabolem/financial-sentiment-mlops)** | FinBERT sentiment platform for financial text: multi-source ingestion, DVC-versioned training, MLflow registry, FastAPI on Kubernetes, Prometheus/Grafana and Evidently drift monitoring. [Live demo](https://huggingface.co/spaces/Priyabolem/financial-sentiment-analysis) | **~0.85 F1** on the test set, served at **sub-100 ms p99** latency |
| **[fraud-detection-mlops](https://github.com/priyankabolem/fraud-detection-mlops)** | Fraud scoring on 284,807 transactions at 0.17% prevalence: chronological split, AUPRC-driven model selection, threshold frozen on validation, PSI drift monitoring written from scratch. | **test AUPRC 0.765** against a 0.718 logistic baseline, at a 0.90 precision budget |
| **[grocery-search-vertex](https://github.com/priyankabolem/grocery-search-vertex)** | Two-stage product search on Google Cloud: Vertex AI Search retrieves, a Vertex AI endpoint re-ranks by reorder propensity, FastAPI on Cloud Run blends the signals and degrades gracefully if the endpoint is down. | **152 ms p95** end to end on Cloud Run over **9,162 products**, re-ranker **27% lower MAE** than baseline |
| **[RAG-Chatbot-1](https://github.com/priyankabolem/RAG-Chatbot-1)** | Hybrid-retrieval Q&A over university data: a Neo4j knowledge graph for relationships plus OpenAI embeddings for semantic search, orchestrated with LangChain. [Live demo](https://nwmsu-rag-chatbot.streamlit.app) | **2 retrieval paths in one pipeline**, so relational queries (program to department to requirement) survive retrieval instead of being flattened |

## Tech stack

`Python` `SQL` · `Agentic workflows` `RAG` `MCP` `LLM evaluation` `LangChain` `LangGraph` · `PyTorch` `TensorFlow` `Scikit-learn` `XGBoost` `LightGBM` `Transformers` · `FastAPI` `Docker` `Kubernetes` `MLflow` `DVC` `Evidently` `GitHub Actions` · `AWS SageMaker` `Lambda` `S3` `CloudWatch` · `GCP Vertex AI` `BigQuery` `Cloud Run` · `Spark` `Airflow` `Databricks` `Neo4j` · `Power BI` `Tableau`

## Experience

- **Machine Learning Engineer, Adisys Corporation**, Greater Seattle, WA, Jun 2025 to present. Agentic AI assistant for an enterprise collaboration software client: multi-step agent workflows, RAG with permission-aware retrieval, MCP tool integrations, LLM evaluation pipelines in CI, Python and FastAPI services. Earlier, for a healthcare data platform client: chronic disease progression prediction on de-identified EHR data with TensorFlow, BERT embeddings and SageMaker Pipelines/Endpoints (+22% prediction accuracy, -35% data-prep time).

MS in Computer Science, Northwest Missouri State University, May 2025.

## Contact

Open to Machine Learning Engineer, AI Engineer, Agentic AI and Forward Deployed Engineer roles.

- Portfolio: [priyankabolem.github.io](https://priyankabolem.github.io)
- Email: [priyankabolem93@gmail.com](mailto:priyankabolem93@gmail.com)
