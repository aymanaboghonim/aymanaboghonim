# Hi, I'm Ayman Aboghonim 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/ayman-aboghonim)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/aymanaboghonim)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:aymanaboghonim@gmail.com)

> **AI Engineer | Computer Vision & Multimodal | Systems Inference & MLOps**

AI Engineer with 5 years of experience building and delivering production computer vision pipelines for geospatial and municipal intelligence. 

My work bridges high-resolution visual modeling with generative inference—designing hierarchical vision pipelines while engineering resource-constrained serving platforms governed by strict reliability contracts.

---

### 🛠️ Technical Stack & Architecture

| Domain | Core Stack & Frameworks |
| :--- | :--- |
| **Vision & Multimodal** | YOLOv8 / YOLOv11, SAHI, OpenCV, PyTorch, Vision-Language Models (VLMs) |
| **Inference & Systems** | vLLM, KServe, Envoy AI Gateway, AWQ INT4, FP8 KV-Cache, k3s, Docker |
| **MLOps & Data Engine** | Labelbox SDK, DeepEval, GCP Vertex AI, Kubeflow Pipelines (KFP v2), Prometheus, Grafana |
| **Backend & Contracts** | Python 3.12, FastAPI, LangGraph, AsyncIO, Pydantic v2, AST Parsing (sqlglot), SQL |

---

### 🚀 Systems R&D & Core Projects

#### ⚡ [NanoServe | Lightweight LLM Inference & Serving Platform](https://github.com/aymanaboghonim/nanoserve-llm)
*Kubernetes-native serving architecture engineered for low-latency, deterministic LLM inference under compute constraints.*
* **Architecture:** Single-node k3s cluster deploying KServe (`LLMInferenceService`), vLLM runtime, and Envoy AI Gateway with OpenAI-compatible API contracts.
* **Optimization:** Calibrated compute budgets using AWQ INT4 quantization, FP8 KV caching, prefix caching, and token-aware admission control to prevent OOM bottlenecks.
* **Telemetry & Delivery:** Instrumented real-time Time-To-First-Token (TTFT), inter-token latency, and KV-cache saturation via Prometheus/Grafana; deployed via hermetic GitOps pipelines.

#### 🛡️ [sql-circuit-guard | Deterministic Text-to-SQL Guardrail Engine](https://github.com/aymanaboghonim/sql-circuit-guard)
*Deterministic reliability bridge enforcing AST-based query validation, read-only safety, and schema inspection between LLMs and SQL engines.*
* **AST Validation:** Traverses Abstract Syntax Trees (`sqlglot`) to block destructive commands (DROP, DELETE, UPDATE, ALTER) and malformed syntax ahead of database execution.
* **Self-Correcting Loops:** Implements schema-aware reflection routines that guide local and cloud LLMs to resolve schema/column mismatches autonomously.
* **Predictable Contracts:** Backed by Pydantic v2 schema enforcement and async state machines for predictable execution paths.

#### 🛰️ Geospatial Vision & Hierarchical Multimodal Pipelines
*End-to-end production modeling and dataset engineering for large-scale aerial and satellite inspection.*
* **Backbones & SAHI:** Fine-tuning and benchmarking detector backbones (YOLOv8/v11, OpenCV) integrated with Slicing Aided Hyper Inference (SAHI) to resolve small-object recall bottlenecks across multi-gigapixel scenes.
* **Multimodal Compliance:** Designing two-stage architectures that extract localized visual patches via detector backbones to feed downstream Vision-Language Model (VLM) evaluation pipelines.
* **Data Operations:** Programmatic dataset conversion tooling, structured ontologies, and consensus auditing on Labelbox across 138K+ high-resolution scenes.

---

### 🏆 Certifications & Credentials

* **GitHub Copilot Individual Certification (GH-300)** — Microsoft / GitHub *(Active: 2025–2027)*
* **Microsoft Certified: Azure AI Fundamentals (AI-900)** — Microsoft *(Active: 2025)*
* **AWS Certified Machine Learning – Specialty** — Amazon Web Services *(Alumni: 2021)*

---

### 🤝 Leadership & Community Enablement

* **Technical Community Lead & Advisory Lead @ DevOps Visions:** Architecting proof-of-concept demonstrations focusing on cloud infrastructure patterns, automated data pipelines, and system observability.
* **Engineering Mentorship (Elmentor Program):** Mentoring peer engineers on production AI roadmaps, cloud architecture patterns, and transitioning into production engineering.
* **Technical Speaker:** Facilitated hands-on workshops and sessions on AI-assisted developer workflows (GitHub Copilot across the SDLC) and engineering metrics.

---

### 📫 Connect & Collaborate

* **LinkedIn:** [linkedin.com/in/ayman-aboghonim](https://linkedin.com/in/ayman-aboghonim)
* **GitHub:** [github.com/aymanaboghonim](https://github.com/aymanaboghonim)
* **Email:** [aymanaboghonim@gmail.com](mailto:aymanaboghonim@gmail.com)
