# Pranav Kumar Kaliaperumal

> Machine Learning Systems · Model Optimization · Scalable AI Infrastructure

M.S. Computer Science candidate focused on machine learning systems, transformer optimization, and production AI infrastructure. My work combines ML research, backend engineering, and performance-oriented system design to build reliable and deployable AI systems.

Based in Aurora, CO.

---

# Research Highlight

## Activation Outliers in Transformer Quantization

📄 Paper: https://arxiv.org/abs/2603.04308

![Transformer Quantization Visualization](assets/transformer_quantization_overview.png)

My research investigates failure modes in **post-training quantization (PTQ)** of transformer models, focusing on structured activation outliers that cause severe accuracy degradation.

Key findings:

- Global **W8A8 quantization reduces BERT accuracy from 89.66% → 54.33%**
- Activations exhibit **extreme heavy-tailed behavior** with kurtosis up to **271**
- ~**55% of activation energy concentrated in top 1% of channels**
- **Mixed-precision PTQ restores accuracy to 89.42%**
- **PEG quantization improves accuracy to 86.18%**

The work highlights that transformer PTQ failures are driven by **structured channel dominance amplified through residual connections**, requiring **channel-aware precision allocation rather than simple clipping**.

---

# Engineering Focus

I design and implement **machine learning systems and infrastructure built for real-world deployment**.

Core areas:

- Transformer optimization and model compression  
- ML system benchmarking and evaluation  
- Agentic AI workflows and LLM-based systems  
- Backend infrastructure for AI services  
- Observability, validation, and reliability for ML pipelines  
- Performance analysis and systems optimization  

---

# Flagship Systems

### PeopleOS — AI Workflow Platform
Enterprise-style AI orchestration system with policy gating, observability, and evaluation pipelines for agent workflows.

### TransformerTheory
Experimental transformer framework exploring **sparse attention, LoRA fine-tuning, and optimization dynamics**.

### TatoOps — Optimization & Decision Support
MILP-based airline gate assignment system with disruption simulation and decision-support dashboards.

### 5G KPI Root Cause Analysis
SQL-driven anomaly detection and root cause analysis pipeline simulating telecom-scale monitoring systems.

### Supply Chain Inventory API
FastAPI + SQL backend for forecasting, validation pipelines, and containerized deployment.

---

# Technical Stack

## Languages

![Python](https://img.shields.io/badge/Python-3A75B0?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-2F855A?style=for-the-badge)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

## Machine Learning

![Transformers](https://img.shields.io/badge/Transformers-7C3AED?style=for-the-badge)
![Model Compression](https://img.shields.io/badge/Model%20Compression-DC2626?style=for-the-badge)
![LoRA](https://img.shields.io/badge/LoRA-F59E0B?style=for-the-badge)
![Sparse Attention](https://img.shields.io/badge/Sparse%20Attention-059669?style=for-the-badge)

## Systems & Infrastructure

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-2563EB?style=for-the-badge)
![Monitoring](https://img.shields.io/badge/Monitoring%20%26%20Logging-475569?style=for-the-badge)
![CI/CD](https://img.shields.io/badge/CI/CD-F97316?style=for-the-badge)

---

# Career Direction

I am interested in roles involving:

- Machine Learning Engineering  
- ML Systems and Infrastructure  
- Model Optimization and Efficient Inference  
- Production AI platforms  
- Scalable ML pipelines  

---

📫 Email: pranavkkp4@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/pranav-kumar-kaliaperumal  
🔗 GitHub: https://github.com/pranavkkp4  
📄 arXiv: https://arxiv.org/abs/2603.04308
