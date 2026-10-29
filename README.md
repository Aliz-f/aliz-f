# Alireza Fadaei

**Full-Stack Software Engineer | Java · React · Python | Applied AI, Secure Distributed Systems & Research**

Based in Oulu, Finland. I am an M.Sc. student in Software Engineering and Information Systems at the University of Oulu (2026–present), with an earlier M.Sc. in Software Engineering from Azad University, Najafabad Branch. My work brings together full-stack delivery, applied AI, cybersecurity and distributed systems: from Java endpoint agents and React/Python services to reproducible intrusion-detection experiments. I have delivered industry software across security platforms, SaaS and scientific data systems, and my federated-learning work has appeared in *The Journal of Supercomputing*.

## What I build

### Full-stack applications and architecture

I design and deliver React and JavaScript interfaces, Python REST services, data models and deployment workflows. My experience includes modular service design, API/data contracts, integration testing and customer-facing operational systems.

### AI and agentic integrations

I build bounded, observable automation into product workflows: web crawling, Pydantic validation, resumable processing and optional LLM-assisted resolution where it helps resolve genuinely ambiguous records.

### Security and distributed systems

At Fardaad (2022–2024), I helped build a hierarchical patch and vulnerability-management platform: Python services and queues, CVE enrichment and matching, dashboards, and Java agents for Windows and Linux endpoints. The delivery process used GitLab CI/CD; recent public work uses GitHub Actions where present.

### ML and optimisation research

My research code covers federated and centralised intrusion detection on Edge-IIoTset, plus an operations-research pipeline for constrained TV-advertising scheduling. These are separate research strands: the latter is optimisation, not machine learning.

## Featured engineering work

- [**Company Domain + Contact Enrichment**](https://github.com/Aliz-f/company-domain-contact-enrichment) — a Dockerised Python pipeline that normalises company records, resolves domains with DNS/HTTP checks, crawls sites for contacts and persists phase checkpoints. Pydantic schemas, idempotent phases and a capped optional LLM step make interrupted runs inspectable and resumable. It is a public technical demonstration related to my past 2026 work at Aminyx, not a release of company IP.
- [**BrassicaLNC**](https://brassica.arfadaei.ir/) — a scientific research database containing 1,852 curated lncRNAs from 2,361 RNA-Seq libraries. I contributed React exploration interfaces, Django REST APIs, data models and deployment/operations; the public [backend repository](https://github.com/Aliz-f/BrassicaLnc-Backend) documents the code that is available.
- [**Matchline MVP**](https://github.com/Aliz-f/matchline-mvp) — a public React/TypeScript/Vite product prototype with Zustand and Leaflet. It uses fictional/local data and is not presented as a production sports-data or payment service.

## Research and reproducible code

### Intrusion detection in dew/IIoT environments

[**Federated Intrusion Detection**](https://github.com/Aliz-f/edge-web-attack-detection-federated) is the Flower-based research implementation connected to my M.Sc. thesis and 2026 paper. A server coordinates aggregation of local 1D-CNN updates; experiments cover IID and non-IID client-data configurations on Edge-IIoTset, without centralising raw traffic. See the peer-reviewed paper: [Fadaei & Barekatain, *The Journal of Supercomputing* (2026), DOI 10.1007/s11227-026-08314-x](https://doi.org/10.1007/s11227-026-08314-x).

[**Centralised Intrusion Detection**](https://github.com/Aliz-f/edge-web-attack-detection-centralized) is the comparative baseline code, including 1D-CNN and LightGBM experiments for binary, 6-class and 15-class tasks and evaluation measures documented in the repository. It complements the federated work; it is not a separate publication.

### TV Advertisement Scheduling Optimisation (2024)

This one research collaboration supported a master's thesis project at Sharif University of Technology, Tehran; it was not a Sharif degree, appointment or my own Sharif thesis. The public code is intentionally split into a navigable pipeline:

1. [**Synthetic data generator**](https://github.com/Aliz-f/tv-ad-scheduling-data-generator) creates constrained scheduling instances: breaks, budgets, reach targets, release/deadline windows and advertiser conflicts.
2. [**MILP model**](https://github.com/Aliz-f/tv-ad-scheduling-milp-model) consumes those instances in Python with DOcplex/IBM CPLEX to seek exact solutions subject to capacity, timing and allocation constraints.
3. [**Metaheuristics**](https://github.com/Aliz-f/tv-ad-scheduling-metaheuristics) provides NSGA-II, genetic-algorithm, simulated-annealing and tabu-search alternatives.

CPLEX is commercial software, so availability of the repository does not by itself promise solver-independent reproduction.

## Commercial work (selected)

- **CNC Process Management System (2025)** — independently built and customer-deployed for a manufacturing workflow; the application is in active production use. [Project entry](https://erp.arfadaei.ir) · **Closed-source**.
- **Psychological Clinic CRM (2026)** — independently built and customer-deployed for appointments, clinician schedules, patient records, sessions and billing. [Project entry](https://psy.arfadaei.ir) · **Closed-source; no patient data or screenshots are published here**.

These are deployed customer products, not public GitHub repositories. Their links are public entry points supplied by my portfolio/CV; access and any demonstration account remain subject to the product owner’s authorisation.

## Focused stack

| Area | Tools and practices |
| --- | --- |
| Endpoint and frontend | Java endpoint agents for Windows/Linux; React, JavaScript, HTML and CSS |
| Services and APIs | Python, FastAPI, Django REST, Flask, Node.js, REST APIs and Pydantic validation |
| Data and delivery | SQL/PostgreSQL, Redis, Docker, Docker Compose, Linux, Nginx, testing and integration work |
| Secure delivery | Distributed client-server systems, queue-based processing, GitLab CI/CD at Fardaad and GitHub Actions in recent projects |
| Research tooling | Flower, TensorFlow, LightGBM, scikit-learn, NumPy; CPLEX/DOcplex and optimisation algorithms |

## Publication, teaching and mentoring

**Publication.** Fadaei, A. & Barekatain, B. (2026). “A novel intrusion detection system for dew computing environments based on an enhanced federated deep learning model.” *The Journal of Supercomputing*, 82, Article 172. [DOI](https://doi.org/10.1007/s11227-026-08314-x).

I have also taught practical programming and software-development projects through Iran TVTO (2024–2026), led backend-development workshops at Dana Cup (2024–2025), and taught an applied Python workshop at Isfahan University of Technology (2021).

## Links

[Portfolio](https://arfadaei.ir/) · [LinkedIn](https://www.linkedin.com/in/aliz-f/) · [ORCID](https://orcid.org/0009-0007-1187-7288) · [Academic CV](https://arfadaei.ir/assets/pdf/AlirezaFadaei-Academic-CV.pdf?v=20261022-6) · [Industry CV](https://arfadaei.ir/assets/pdf/AlirezaFadaei-Industry-CV.pdf?v=20261022-5)
