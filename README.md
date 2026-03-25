## Pranav Kumar Kaliaperumal
### Backend Systems · API Infrastructure · ML Assisted Optimization

**MS Computer Science | Published Researcher | Production Systems Builder**

I design backend infrastructure and data intensive applications where **performance, reliability, and algorithmic efficiency** matter. My work bridges software engineering and intelligent optimization, building REST APIs, deterministic simulation engines, and ML assisted decision systems that run in production environments.

Currently focused on systems that handle complex state management, real time calculations, and predictive analytics under resource constraints.

***

### Signature Systems 

**NBA Simulation Engine**, *Deterministic Career Modeling System*
* Built a rule based simulation platform processing multi variable career trajectories using **in browser SQLite (sql.js)** and vanilla JS
* Handles complex state persistence and statistical modeling entirely client side; deployed to **GitHub Pages with zero backend dependency**
* Demonstrates capability to build **self contained, algorithmically complex systems** with deterministic outcomes

**TatoOps Optimization Platform**, *Operations Research & Resource Allocation*
* **MILP based gate assignment solver** using Google OR Tools CP SAT for airline disruption management
* Real time constraint solving with **Streamlit decision support dashboard**, turning optimization outputs into actionable operations workflows
* Directly applicable to **resource allocation, routing optimization, and scheduling problems** at scale

**Supply Chain Inventory API**, *Production Grade FastAPI Service*
* **RESTful backend** with SQLite persistence, CRUD operations, and integrated **predictive stockout forecasting**
* Implements time series estimation for inventory management, similar patterns to **fraud detection and risk scoring workflows**
* Clean architecture separation between data layer, business logic, and API presentation

**PeopleOS**, *Enterprise AI Workflow Orchestration*
* **Agentic AI platform** with policy enforcement, compliance logging, and observability patterns
* Built with focus on **enterprise deployment concerns**: structured outputs, guardrails, audit trails, and system reliability
* Demonstrates understanding of **production ML system requirements**, beyond model training

***

### Published Research: Model Efficiency at Scale

**[Activation Outliers in Transformer Quantization](https://arxiv.org/abs/2603.04308)**, *arXiv 2603.04308*

Investigated failure modes in **Post Training Quantization (PTQ)** for transformer deployment, identifying how activation channel outliers cause accuracy degradation in W8A8 quantization schemes.

* **Key finding**: Global quantization drops BERT accuracy from 89.66% to 54.33%; channel aware mixed precision recovers to 89.42%
* **Impact**: Provides quantization strategies for **edge deployment and high throughput inference**, critical for reducing compute costs in production ML systems
* **Relevance**: Direct experience with **optimization tradeoffs** (speed vs. accuracy) that mirror production infrastructure decisions

***

### Engineering Philosophy

**Performance First Python**: I do not just write Python; I optimize it. From transformer quantization research to **C++/CUDA adjacent optimization awareness**, I think about memory layout, latency percentiles (p50/p95/p99), and computational efficiency.

**APIs as Products**: My FastAPI and REST work treats endpoints as contracts, focusing on **validation, error handling, documentation, and client ergonomics** rather than just functionality.

**Data Driven Decisions**: Whether it is airline gate assignments or NBA career trajectories, I build systems that use **algorithmic optimization and statistical analysis** to solve real operational problems.

***

### Technical Arsenal

**Backend & Infrastructure**
* **Python/FastAPI**: Production REST APIs, async handling, Pydantic validation
* **SQL & Data**: SQLite optimization, query performance, database schema design
* **Systems**: REST architecture, API design, microservices patterns, CI/CD awareness

**Optimization & ML Systems**
* **Model Efficiency**: Quantization (PTQ/W8A8), inference optimization, edge deployment
* **Operations Research**: MILP solvers, constraint programming (OR Tools), heuristic optimization
* **ML Pipeline Tools**: PyTorch, transformers, reproducible research practices

**Production Awareness**
* Deployment: GitHub Pages, Streamlit cloud, containerization ready architectures
* Observability: Logging, monitoring patterns, compliance auditing (from PeopleOS)
* Quality: Type hints, testing mindset, API documentation standards

***

### Current Pursuit

**MS Computer Science**, University of Colorado Denver  
Concentration in scalable system design and ML infrastructure. Coursework emphasizes **distributed systems, algorithm analysis, and high performance computing**.

***

### Connect

* **Email**: pranavkkp4@gmail.com  
* **LinkedIn**: https://www.linkedin.com/in/pranav-kumar-kaliaperumal  
* **GitHub**: https://github.com/pranavkkp4  
* **Research**: https://arxiv.org/abs/2603.04308
