# Pranav Kumar Kaliaperumal

**Machine Learning Systems · Model Optimization · Scalable AI Infrastructure**

I am currently pursuing an M.S. in Computer Science and my main focus is Python development for machine learning systems, transformer optimization, and AI infrastructure with real applications. I combine machine learning research, backend engineering, and system design to create systems that are both reliable and useful.

Based in Aurora, CO.
---

## Research Highlight

### Activation Outliers in Transformer Quantization

[![arXiv](https://img.shields.io/badge/arXiv-2603.04308-b31b1b.svg)](https://arxiv.org/abs/2603.04308)

**Paper:** https://arxiv.org/abs/2603.04308

**Transformer Quantization Visualization**

In my research, I examine the failure modes that arise during post-training quantization (PTQ) of transformer models. I focus in particular on how structured activation outliers can lead to significant drops in model accuracy, which is a critical challenge for deploying efficient transformer-based systems.

In this study, I found that using global W8A8 quantization really hurts BERT’s accuracy, dropping it from 89.66% to 54.33%. The activations ended up having some wild outliers, with most of the energy packed into just a few channels. But switching to mixed-precision PTQ almost gets the accuracy back (89.42%), and PEG quantization also helps (up to 86.18%).

Basically, the main problem is that a few channels dominate because of how residual connections work. Fixing this needs smarter, channel-aware precision—not just simple clipping.

---
## Featured Projects

| Project                                        | Description                                                                                                                                                                                    |
| ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **NBA Player Simulation & Analytics Platform** | In-browser NBA draft and career simulator built with HTML, CSS, JavaScript, and in-browser SQLite (sql.js). The system is rule-based, data-driven, and runs fully client-side on GitHub Pages. |
| **Supply Chain Inventory API**                 | FastAPI-based supply chain inventory service with RESTful CRUD operations, SQLite storage, and a forecasting module that predicts days until stockout.                                         |
| **TatoOps — Optimization & Decision Support**  | Airline-style gate assignment optimization with disruption simulation using OR-Tools MILP structure and a Streamlit dashboard for decision support.                                            |
| **PeopleOS — AI Workflow Platform**            | Agentic AI orchestration system with policy enforcement, compliance logging, observability features, and enterprise deployment patterns.                                                       |
| **Workout Planner App**                        | React-based workout planner featuring GSAP micro-interactions and Zapier-powered automation, deployed via GitHub Pages.                                                                        |
| **AR Experience**                              | Interactive browser-based augmented reality system using MediaPipe Face Mesh to classify facial expressions in real time with user calibration and live confidence tracking.                   |

## Engineering Focus

I design and build machine learning systems and supporting infrastructure built for real-world deployment.

My main interests are things like making transformers run faster and smaller, testing and evaluating machine learning systems, building smart AI workflows, keeping backend infrastructure running smoothly, making sure pipelines are reliable, and figuring out how to boost overall performance.

I am also very interested in general Python development. Python was my first language, and I’ve since used it for everything from backend development to machine learning tasks, including for my transformer quantization project.

---

## Technical Stack

### Languages

* Python
* Java
* SQL
* C++

### Machine Learning

* Transformers
* Model Compression
* LoRA
* Sparse Attention

### Systems & Infrastructure

* FastAPI
* REST APIs
* Monitoring
* CI/CD

---

## Career Direction

I am interested in pursuing roles that involve several distinct but related areas:

* Machine learning engineering
* ML systems and infrastructure
* Model optimization and fast inference
* Building production AI platforms
* Developing scalable ML pipelines

---

## Links

Email: [pranavkkp4@gmail.com](mailto:pranavkkp4@gmail.com)
LinkedIn: https://www.linkedin.com/in/pranav-kumar-kaliaperumal
GitHub: https://github.com/pranavkkp4
arXiv: https://arxiv.org/abs/2603.04308
