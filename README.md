<div align="center">

# Omar Farooq

### AI/ML Engineer + Data Scientist

**Applied AI · Agentic Systems · Speech AI · Computer Vision · ML Infrastructure · Developer Tooling · Data Science & Analytics**

# 📫 Connect

Open to conversations around **AI/ML engineering, applied AI, speech systems, agentic AI, MLOps, data science and developer tooling**.

[![GitHub](https://img.shields.io/badge/GitHub-omardoesdata-181717?style=for-the-badge&logo=github)](https://github.com/omardoesdata)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/omar-farooq-7388a0201/)
[![Medium](https://img.shields.io/badge/Medium-Read_My_Writing-000000?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@omarfarooqq957)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:omarfarooqq957@gmail.com)
[![Resume](https://img.shields.io/badge/Resume-Download_PDF-2563EB?style=for-the-badge&logo=adobeacrobatreader&logoColor=white)](./assets/Omar_Farooq_Resume.pdf)

---

<div align="center">

### `Build → Measure → Break → Improve → Ship`

**AI systems should survive contact with the real world.**

</div>

---

## `whoami`

I'm an **AI/ML Engineer** working on production-oriented artificial intelligence systems.

My work spans:

- 🧠 Machine Learning & Deep Learning
- 🤖 Agentic AI & LLM Systems
- 🎙️ Speech Recognition / Urdu ASR
- 👁️ Computer Vision
- 🛡️ AI & Developer Safety Tooling
- ⚙️ MLOps, evaluation and ML infrastructure
- 📊 Data Science & Analytics

I currently work at **Punjab Information Technology Board (PITB)**, contributing to applied AI systems and government-scale technology projects.

Outside my organizational work, I build open-source developer tooling. My current flagship public project is **[OhMyDB](https://github.com/omardoesdata/ohmydb-proxy)** — a fail-closed database safety proxy designed to catch risky SQL before it reaches the backend.

What interests me most is the part of AI that comes after:

```python
model.fit()
```

The real engineering starts with:

```text
data
  ↓
experimentation
  ↓
evaluation
  ↓
deployment
  ↓
monitoring
  ↓
human feedback
  ↓
continuous improvement
```

---

# ⚡ Featured Engineering

## 🛡️ OhMyDB

> **A fail-closed safety proxy for your database.**  
> Catch dangerous SQL before your database has to.

[![GitHub](https://img.shields.io/badge/GitHub-ohmydb--proxy-181717?style=flat-square&logo=github)](https://github.com/omardoesdata/ohmydb-proxy)
[![Release](https://img.shields.io/github/v/release/omardoesdata/ohmydb-proxy?style=flat-square&label=release)](https://github.com/omardoesdata/ohmydb-proxy/releases/latest)
[![CI](https://github.com/omardoesdata/ohmydb-proxy/actions/workflows/ci.yml/badge.svg)](https://github.com/omardoesdata/ohmydb-proxy/actions)

**OhMyDB** is an open-source database safety proxy built to intercept risky SQL operations **before they reach the backend** while failing safely when behavior is malformed, ambiguous, or unsupported.

`Python` · `PostgreSQL` · `MySQL/MariaDB` · `AsyncIO` · `SQLGlot` · `Docker`

### What it does

- Fail-closed SQL policy enforcement
- Impact estimation for risky mutations
- Prepared-statement inspection
- Transaction-state tracking and recovery
- Structural and multi-statement protection
- Audit logging and sanitization
- PostgreSQL and MySQL/MariaDB adapter architecture
- Dockerized non-root runtime

### Engineering quality

- **341 automated tests**
- Python **3.11 / 3.12 / 3.13** CI
- Real PostgreSQL client/driver end-to-end validation
- Fresh-wheel installation validation
- Docker build and non-root runtime validation
- Stable wheel + source distribution artifacts
- SHA256 release checksums
- Backward-compatible legacy `sql-safety-proxy` CLI

### Current stable release

**`v1.1.0`**

Primary CLI: **`ohmydb`**

👉 [Explore OhMyDB](https://github.com/omardoesdata/ohmydb-proxy) · [Latest Release](https://github.com/omardoesdata/ohmydb-proxy/releases/tag/v1.1.0)

---

## 🎙️ Urdu Automatic Speech Recognition

One of my major applied ML engineering efforts has been building and improving an **Urdu ASR ecosystem** around Whisper.

`Whisper` · `PyTorch` · `Hugging Face` · `MLflow` · `CUDA` · `Linux`

### Work included

- Built an ASR pipeline from scratch to understand the full speech stack
- Created and expanded custom Urdu speech datasets
- Built audio preprocessing and transcription workflows
- Managed annotation and validation pipelines
- Led annotators and data-collection efforts
- Combined Common Voice, FLEURS, custom Urdu podcast data and collected live speech
- Grew the training corpus beyond **150 hours**
- Fine-tuned Whisper Small, Medium and Large V3
- Built repeatable MLflow-based training and evaluation workflows
- Benchmarked models and tracked promotion-quality metrics

### Best results achieved

**Whisper Large V3 → 13.61% WER**

**Whisper Medium → 17.91% WER**

This work lives inside organizational GitLab infrastructure, so the repository is not publicly linked here.

---

## 👁️ Human-in-the-Loop Computer Vision

Built and worked on a **YOLO + Label Studio + MLflow** human-in-the-loop pipeline for continuously improving object detection systems.

`YOLO` · `Label Studio` · `MLflow` · `Python`

### Focus

- Model-assisted annotation
- Human validation loops
- Immutable annotation exports
- Dataset versioning
- Scheduled retraining
- Candidate/champion model comparison
- Model promotion gates
- Deployment-oriented CV workflows

The implementation is maintained in organizational GitLab infrastructure.

---

## 📑 AI Compliance & Document Intelligence

Worked on an AI system for evaluating technical reports against structured **SOP / compliance requirements**.

`LLMs` · `RAG` · `OCR` · `FastAPI` · `LangGraph` · `LlamaIndex`

### System responsibilities

- OCR and document parsing
- Structured SOP rule extraction
- Applicability filtering
- Evidence retrieval
- Rule-level compliance evaluation
- Source-grounded findings
- Human review workflows
- Query-letter generation
- Evaluation matrices
- Audit-ready outputs

The project is maintained in organizational GitLab infrastructure.

---

## 🤖 Agentic AI & Intelligent Systems

I’m actively building and learning deeper into modern agentic AI systems.

Areas include:

- Tool-using AI agents
- Structured LLM workflows
- Model Context Protocol (MCP)
- RAG and knowledge retrieval
- Prompt engineering
- Local LLM deployment
- AI evaluation pipelines
- Multi-step reasoning workflows
- Production-oriented agent architectures

---

# 🧭 What I'm Working On Now

```text
Speech AI           → Urdu ASR optimization & model evaluation
Agentic AI          → Agents, MCP and tool-using systems
LLM Systems         → RAG, structured workflows and evaluation
Computer Vision     → Human-in-the-loop model improvement
AI Security         → Safer ML / LLM / developer workflows
MLOps               → Reproducible training and promotion pipelines
Developer Tooling   → OhMyDB & safer database operations
```

---

# 🎓 Certifications & Continuous Learning

## 🤖 AI Engineer Agentic Track

**The Complete Agent & MCP Course — Udemy**

**Instructors:** Ed Donner · Ligency  
**Completed:** August 2026  
**Duration:** 21 hours

Focused on:

- AI agents
- Tool use
- Agentic workflows
- Model Context Protocol
- Modern AI engineering patterns

---

## 📊 Data Science & Machine Learning using Python

**Lahore University of Management Sciences — LUMS**

**Completed:** May 2025

Focused on applied:

- Data Science
- Machine Learning
- Python
- Data analysis
- Model development

---

# 💼 Experience

## AI/ML Engineer · PITB

`2026 → Present`

Working across applied AI research, ML engineering and production-oriented AI systems.

Current areas:

`Speech AI` · `LLM Systems` · `Computer Vision` · `Agentic AI` · `MLOps` · `AI Evaluation`

---

## Junior Data Analyst · Game District

`2025 → 2026`

Worked on analytics automation, experimentation and monetization analysis.

### Highlights

- Automated reporting workflows using Python
- Reduced a recurring analysis workflow from hours to seconds
- Built Power BI data pipelines
- Performed EDA across hundreds of datasets
- Designed and analyzed A/B tests
- Worked across multiple ad networks
- Contributed to measurable monetization improvements

---

# 🧰 Tech Stack

### AI / Machine Learning

`Python`  
`PyTorch`  
`TensorFlow`  
`Scikit-learn`  
`Hugging Face`  
`Whisper`  
`YOLO`  
`OpenCV`

### Agentic / LLM Systems

`LangGraph`  
`LlamaIndex`  
`RAG`  
`MCP`  
`Ollama`  
`Structured Outputs`  
`Prompt Engineering`

### ML Infrastructure

`MLflow`  
`Docker`  
`Linux`  
`CUDA`  
`GitHub Actions`  
`GitLab`

### Backend / Data

`FastAPI`  
`Flask`  
`PostgreSQL`  
`SQL`  
`REST APIs`

### Analytics

`Pandas`  
`NumPy`  
`Power BI`  
`Matplotlib`  
`Excel`

---

# 📌 Selected Work

| Project / Workstream | Area | Public |
|---|---|---|
| **[OhMyDB](https://github.com/omardoesdata/ohmydb-proxy)** | Database safety / developer tooling | ✅ Public |
| **Urdu Whisper ASR** | Speech AI / fine-tuning | Organizational repo |
| **YOLO HITL Pipeline** | Computer vision / continuous learning | Organizational repo |
| **AI SOP Evaluator** | LLM document intelligence | Organizational repo |
| **Adaptive Learning Tutor** | Conversational AI / education | Organizational work |
| **AI Data Analyst Agent** | Agentic analytics | Selected work |
| **Local LLM Applications** | Ollama / prompt engineering | Selected work |
| **Fraud Detection & ML Projects** | Applied ML / Data Science | Selected repos |

---

<details>
<summary><b>📦 Earlier Projects & Experiments</b></summary>

<br>

- Banking Fraud Detection
- Diabetes Prediction
- Exploratory Data Analysis projects
- Feature engineering projects
- Power BI analytics workflows
- Local chatbot experiments
- AI Data Analyst Agent
- Traditional ML experimentation
- Data visualization projects

</details>

---

# 🧠 Engineering Philosophy

I’m especially interested in systems where **AI meets engineering**.

Not just models that work in a notebook.

But systems that are:

```text
measurable
deployable
observable
reproducible
testable
safe
```

Enough to operate in the real world.

---

# 📫 Connect

[![GitHub](https://img.shields.io/badge/GitHub-omardoesdata-181717?style=for-the-badge&logo=github)](https://github.com/omardoesdata)


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/omar-farooq-7388a0201/)

[![Medium](https://img.shields.io/badge/Medium-Read_My_Writing-000000?style=for-the-badge&logo=medium)](https://medium.com/@omarfarooqq957)

---

<div align="center">

### `Build → Measure → Break → Improve → Ship`

**AI systems should survive contact with the real world.**

</div>
