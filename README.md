# Hi, I'm Ayman Aboghonim 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayman-aboghonim)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/aymanaboghonim)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aymanaboghonim@gmail.com)

> **Senior AI Engineer | Multimodal & Vision Systems | LLM Reliability & MLOps**

Results-driven **Senior AI Engineer** with 5 years of experience owning the end-to-end lifecycle of production AI and computer vision systems—from business requirement scoping and data strategy to cloud deployment and executive reporting.

My work bridges high-resolution visual modeling with generative AI—architecting multimodal inspection pipelines (Vision + VLM), leading large-scale data operations, and engineering resource-efficient serving platforms governed by strict reliability contracts and full-stack observability.

---

### 🛠️ Core Competencies & Technical Architecture

| Domain | Core Stack & Frameworks |
| :--- | :--- |
| **AI & Multimodal Systems** | YOLOv8 / YOLOv11, PyTorch, Vision-Language Models (VLMs), RAG Architectures, Hybrid Search, Agentic Workflows (LangGraph), Spatial Inference (SAHI), OpenCV |
| **Software & Reliability** | Python 3.12, FastAPI, AsyncIO, RESTful APIs, Schema Governance (Pydantic v2), Deterministic Guardrails & AST Validation (`sqlglot`), SQL |
| **Cloud, MLOps & Serving** | GCP (Vertex AI, Kubeflow Pipelines), AWS, Azure DevOps, vLLM, Docker, Kubernetes (k3s) |
| **System & AI Observability** | OpenTelemetry (OTel), Grafana LGTM Stack (Loki, Grafana, Tempo, Mimir/Prometheus), LLM Tracing & Evaluation (Langfuse, DeepEval) |
| **Leadership & Delivery** | End-to-End Solution Ownership, Data Operations & QA Governance, Cross-Functional Collaboration, Cost Optimization |

---

### 🚀 Engineering Projects & Production Focus

#### 🛡️ [sql-circuit-guard | Deterministic LLM Guardrail Engine](https://github.com/aymanaboghonim/sql-circuit-guard)
*Open-source reliability layer enforcing AST-based query validation, read-only safety, and schema governance between LLMs and SQL engines.*
- **Deterministic AST Validation:** Traverses Abstract Syntax Trees (`sqlglot`) to deterministically block destructive commands (`DROP`, `DELETE`, `UPDATE`, `ALTER`) and malformed syntax prior to execution.
- **Self-Correcting Workflows:** Implements schema-aware reflection routines that guide local and cloud LLMs to resolve schema and column mismatches autonomously.
- **Strict Safety Contracts:** Backed by Pydantic v2 schema enforcement and asynchronous state machines for predictable production execution.

#### ⚡ [NanoServe | LLM Inference & Serving Benchmark](https://github.com/aymanaboghonim/nanoserve-llm)
*Lightweight model-serving environment engineered for low-latency, cost-controlled LLM inference under hardware constraints.*
- **Serving Architecture:** Deployed open-weight LLMs using vLLM, Docker, and single-node Kubernetes (k3s) with OpenAI-compatible API contracts.
- **Compute Optimization:** Benchmarked INT4 quantization, KV-cache utilization, and memory/latency trade-offs to prevent OOM bottlenecks under strict compute budgets.
- **End-to-End Observability:** Instrumented real-time telemetry, latency metrics, and LLM trace evaluation using OpenTelemetry (OTel), the Grafana LGTM stack, and Langfuse.

#### 🛰️ Enterprise Multimodal & Geospatial Vision Systems
*End-to-end production modeling, automated compliance auditing, and data strategy across large-scale municipal and satellite inspection initiatives.*
- **Multimodal AI Architecture:** Designed two-stage automated compliance pipelines coupling real-time object detection models with downstream Vision-Language Models (VLMs) using structured prompting and strict Pydantic schemas.
- **Spatial Optimization:** Led training and deployment across satellite and street-level imagery (building footprint extraction, agricultural segmentation, urban asset detection), integrating custom post-processing and SAHI to boost small-object recall without increasing training compute costs.
- **Data Strategy & Cloud MLOps:** Directed annotation operations and QA governance across 138K+ high-resolution images (8 municipal categories), while orchestrating cost-optimized batch training and evaluation pipelines on GCP Vertex AI and Kubeflow.

---

### 🏆 Certifications & Credentials

- **AWS Certified Machine Learning – Specialty** — Amazon Web Services
- **GitHub Copilot Certification (GH-300)** — Microsoft / GitHub
- **Microsoft Certified: Azure AI Fundamentals (AI-900)** — Microsoft

---

### 🤝 Technical Leadership & Community

- **Technical Community & Advisory Lead @ DevOps Visions & Elmentor Program:**
  - **Engineering Enablement:** Designed and delivered hands-on technical workshops for software engineers on integrating AI-assisted development workflows (GitHub Copilot across the SDLC) and cloud observability practices.
  - **Program Delivery & Mentorship:** Collaborated with industry leads and Microsoft MVPs to structure technical learning tracks via Azure DevOps, mentoring engineers on production Python standards, API design, and career progression.

---

### 📫 Connect & Collaborate

- **LinkedIn:** [linkedin.com/in/ayman-aboghonim](https://linkedin.com/in/ayman-aboghonim)
- **GitHub:** [github.com/aymanaboghonim](https://github.com/aymanaboghonim)
- **Email:** [aymanaboghonim@gmail.com](mailto:aymanaboghonim@gmail.com)
