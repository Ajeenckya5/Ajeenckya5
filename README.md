<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=6E40C9&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Ajeenckya+Mahadik+%F0%9F%91%8B;AI+%2F+ML+Engineer;LLM+%7C+RAG+%7C+Agentic+Systems;Building+from+Scratch+%E2%80%94+No+Frameworks" alt="Typing intro" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ajeenckya-mahadik)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Ajeenckya5)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=googlechrome&logoColor=white)](https://ajeenckya5.github.io/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ajeenckyam@gmail.com)

</div>

---

## 🧠 About Me

I'm an **AI/ML Engineer** with an MS from **UW–Madison**, specializing in building production-grade **LLM systems**, **agentic pipelines**, and **RAG architectures** from scratch.

- 🔬 Currently building: **self-improving LLM agents** with QLoRA fine-tuning and RLAIF feedback loops
- 🏗️ I write raw API calls over frameworks — my agents don't use LangChain, AutoGen, or CrewAI
- 🤖 Deep focus on **fine-tuning**, **knowledge distillation**, and **multi-modal AI**
- 🎯 Open to: **ML Engineer · AI Engineer · MLOps · Research Engineer** roles

---

## 🛠️ Tech Stack

**LLMs & Agents**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-6E40C9?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Vector DBs & RAG**

![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Mistral 7B](https://img.shields.io/badge/Mistral%207B-FA8B00?style=flat-square)
![LLaMA 3](https://img.shields.io/badge/LLaMA%203-0467DF?style=flat-square)

**Computer Vision & Fine-Tuning**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Vision Transformer](https://img.shields.io/badge/Vision%20Transformer-2E8B57?style=flat-square)
![QLoRA Fine-Tuning](https://img.shields.io/badge/QLoRA%20Fine--Tuning-E34F62?style=flat-square)

**Backend & Infra**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Self-Improving LLM Agent](https://github.com/Ajeenckya5/self-improving-llm-agent)

**Full self-improving long-horizon agent — strategy memory + distillation**

- Failure-trace analysis → corrective strategies → ChromaDB strategy memory · **90% on Tau Bench**
- Grok-4 teacher labels → QLoRA fine-tunes LLaMA-3.2-1B student
- **95% inference cost reduction** vs teacher at matched quality

`QLoRA` `DPO` `Knowledge-Distillation` `ChromaDB` `LLaMA-3`

</td>
<td width="50%" valign="top">

### 🖥️ [CodeCraft CLI Agent](https://github.com/Ajeenckya5/codecraft-cli-agent)

**Production CLI coding agent — zero framework dependencies**

- ReAct loop + 11 workspace tools, raw HTTPS to xAI/OpenAI
- RLAIF scoring via Grok 4 · JSONL tracing · cross-session memory
- **7.5× faster** than comparable LangChain baseline

`ReAct` `RLAIF` `Tool-Calling` `xAI` `Python`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📧 [Multi-User Email RAG](https://github.com/Ajeenckya5/multi-user-email-rag)

**E5-small-v2 + Mistral 7B over 10K+ indexed emails**

- JWT auth with SQL-enforced per-user isolation at the pgvector layer
- Embedding caching + batched retrieval · **sub-80ms** retrieval latency
- Precision@5 = **0.84** · Answer faithfulness = **0.79**

`RAG` `pgvector` `Mistral-7B` `FastAPI` `JWT`

</td>
<td width="50%" valign="top">

### 🗺️ [Multimodal Optimization Framework](https://github.com/Ajeenckya5/multimodal-optimization-framework)

**MILP cost–time optimal routing across bus, train & flight networks**

- Exact Mixed-Integer Linear Program: flow conservation, stopover limits, mode feasibility
- Tested on **2,040 routes** from a central U.S. hub
- Cost–time Pareto trade-offs for multimodal journeys

`MILP` `Optimization` `Routing` `Operations-Research` `NumPy`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚙️ [OptiCode AgentR](https://github.com/Ajeenckya5/opticode-agentr)

**MINLP-controlled LLM code generation**

- Six-module pipeline selects optimal code candidates
- Solves a Mixed-Integer Nonlinear Program under latency, cost & accuracy constraints
- Optimization-meets-LLM: Julia (JuMP) + Python

`MINLP` `Optimization` `Code-Generation` `Julia` `Streamlit`

</td>
<td width="50%" valign="top">

### 😊 [Facial Expression Recognition](https://github.com/Ajeenckya5/facial-expression-recognition)

**CNN vs ViT transfer learning on FER2013 (7-class)**

- 5-model comparative study: CNN → ResNet → ViT → Hybrid → Domain ViT
- **71.4% accuracy** with trpakov/vit-face-expression
- Full ablation study + per-class precision/recall/F1

`ViT` `CNN` `PyTorch` `Transfer-Learning` `FER2013`

</td>
</tr>
</table>

<details>
<summary><b>➕ More: Operations Research & Optimization</b></summary>
<br/>

- 🎲 [**Adaptive Two-Stage Stochastic Routing**](https://github.com/Ajeenckya5/adaptive-two-stage-stochastic-routing) — routing under travel-time uncertainty with recourse
- 📈 [**Stock Signal Scanner**](https://github.com/Ajeenckya5/stock-signal-scanner) — technical-analysis BUY/SELL scanner for NSE equities with web UI + REST API
- ⚡ [**Perf Sweep Decider**](https://github.com/Ajeenckya5/perf-sweep-decider-live) — interactive dashboard for LLM inference throughput sweeps

</details>

---

<div align="center">

*"Build it from scratch. Understand every layer. That's how you ship reliable AI."*

🌐 **[ajeenckya5.github.io](https://ajeenckya5.github.io/) — run my models live in your browser**

![Profile Views](https://komarev.com/ghpvc/?username=Ajeenckya5&color=6E40C9&style=flat-square&label=Profile+Views)

</div>
