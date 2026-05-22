<h1 align="center">Ajeenckya Mahadik</h1>

<p align="center">
  <strong>AI/ML Engineer &nbsp;·&nbsp; M.S. AI/ML, UW-Madison (May 2026)</strong><br/>
  RAG systems &nbsp;·&nbsp; LLM agents &nbsp;·&nbsp; Bayesian ML &nbsp;·&nbsp; MLOps<br/>
  Madison, WI &nbsp;·&nbsp;
  <a href="mailto:ajeenckyam@gmail.com">ajeenckyam@gmail.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/ajeenckya-mahadik">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://ajeenckya5.github.io">Portfolio</a>
</p>

---

## About

I build end-to-end AI/ML systems — from calibrated probabilistic models to production RAG pipelines and self-improving agents. My work sits at the intersection of model quality and operational impact: I care about eval metrics, retrieval isolation, uncertainty quantification, and the monitoring loops that keep systems honest after deployment.

**Currently:** finishing M.S. in Industrial Engineering (AI/ML specialization) at UW-Madison, May 2026. Open to full-time ML/AI engineering roles.

---

## Selected Projects

### [Autonomous CLI Coding Agent](https://github.com/Ajeenckya5/CLI_AI_Agent)
`python` `llm` `react-agent` `tool-calling` `rlaif` `dpo`

Built a production-grade coding agent from scratch — **zero framework dependencies** (no LangChain, AutoGen, or CrewAI). Raw HTTP to the LLM API, 11 real tools, ReAct planning, cross-session memory, JSONL run tracing, and an RLAIF scoring loop that collects DPO preference pairs via Grok 4.

**Results:** 100% task completion (5/5), 14/14 unit tests passing, **7.5× lower per-task latency** than LangChain equivalent (0.8 ms vs 5.7 ms), zero cold-start overhead.

---

### [Self-Improving LLM Agent](https://github.com/Ajeenckya5/Self_Improving_LLM_Agent)
`llm` `qlora` `llama` `chromadb` `knowledge-distillation` `agent-evaluation`

Closed-loop self-improvement system: Grok 4 (teacher) annotates failure traces → QLoRA fine-tunes LLaMA-3.2-1B (student) → corrective strategies stored in ChromaDB → retrieved on the next similar task.

**Results:** **90% task completion vs 71% baseline** on Tau Bench / WebArena. Student model achieves Grok 4 annotation quality at **60% memory reduction** via 4-bit NF4 quantization.

---

### [Multi-User Email RAG (LLM_RAG)](https://github.com/Ajeenckya5/LLM_RAG)
`rag` `fastapi` `pgvector` `mistral` `jwt` `postgresql`

Local-first RAG system over 10,000+ emails. JWT auth with **SQL-enforced per-user retrieval isolation** (`WHERE user_id = :uid` runs before cosine ranking — User B cannot surface User A's chunks). E5-small-v2 embeddings, Mistral 7B GGUF via llama-cpp, pgvector cosine search.

---

### [FER Vision Transformer Study](https://github.com/Ajeenckya5/Facial_Expressions_Recognation)
`pytorch` `vision-transformer` `fer2013` `transfer-learning` `computer-vision`

Comparative study of CNN baseline vs ViT transfer learning vs CNN-Transformer hybrid on FER2013 (7-class, ~36K images). Key finding: **ViT with pretraining significantly outperforms from-scratch CNN** — the data-hungry regime makes pretraining essential at this scale.

---

## Research — UW-Madison GRA

**Bayesian Calibration for Probabilistic Forecasting**

Built a two-stage model: a deterministic SNN policy model (99 features, 3-way output) followed by a Bayesian output head with Monte Carlo sampling for uncertainty quantification.

**Brier score: 0.176 — 26.7% improvement over the climatological baseline.** Evaluated with ECE, log-loss, reliability diagrams, and McNemar's test for statistical comparison of model variants (with/without weather features).

---

## Work Experience

| Role | Company | Focus |
|---|---|---|
| Graduate Research Assistant | UW-Madison | Bayesian calibration, SNN/BNN, probabilistic forecasting |
| Graduate Associate Engineer | Fiat India | ML-ready datasets, delay prediction, AWS-backed pipelines |
| Analytics Engineer | Powertrac | Predictive maintenance, risk scoring, model monitoring |
| Graduate Engineer | Tata Motors | Anomaly detection, process optimization (Kaizen Award) |

---

## Stack

**Languages:** Python · SQL · Bash  
**ML/DL:** PyTorch · scikit-learn · XGBoost · HuggingFace · LoRA/QLoRA  
**LLM/AI:** LangChain · LlamaIndex · Mistral · LLaMA · Grok · RAG pipelines  
**Infra:** FastAPI · Docker · Kubernetes · AWS (EC2/S3/RDS/SageMaker) · PostgreSQL · pgvector · Redis · Celery  
**MLOps:** MLflow · GitHub Actions · CI/CD · model monitoring  

---

<p align="center">
  <a href="https://ajeenckya5.github.io">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/ajeenckya-mahadik">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:ajeenckyam@gmail.com">Email</a>
</p>
