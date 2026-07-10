<h1 align="center">Oleksandr Podynihlazov</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=20&duration=3500&color=00F7FF&center=true&vCenter=true&width=680&lines=Backend+Engineer+%E2%80%94+Distributed+Systems+%7C+Python+%7C+Java;BSc+Computing+AI+%26+ML+%40+TU+Dublin+%E2%80%94+GPA+3.6%2F4.0;Software+Engineer+Intern+%40+Fidelity+Investments" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/oleksandrpodynihlazov">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:poduniglazov@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <img src="https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Oracle-Java_Certified-F80000?style=flat&logo=oracle&logoColor=white"/>
</p>

---

## About Me

Data-driven backend engineer with **3 years of commercial experience** architecting distributed data ingestion systems at scale (**200M+ records/day**). Currently a **Software Engineering Intern at Fidelity Investments** on the Asset Management Platform team, overseeing 15+ enterprise microservices. Final year of **BSc Computing with AI & ML at TU Dublin (GPA 3.6/4.0)**.

I build systems that run in production — reliably, at scale, around the clock.

---

## Experience

**Software Engineering Intern — Fidelity Investments** · *Dublin* · *Jan 2026 – Present*
> Asset Management Platform Team

- Maintain **15+ Java 17 / Spring Boot microservices**; debugged stale cache synchronisation and cross-service data propagation errors; **1,500-line code refactoring** to decommission legacy endpoints and feature flags
- Enforced enterprise cloud governance via **Amazon EKS OPA** security policy modifications
- Built **Cucumber integration test suites** to enforce the corporate **80%+ code coverage** mandate

---

**Contract Backend & Data Engineer** · *Remote (Freelance)* · *2024 – Present*

- Built a **distributed ETL pipeline** scaling to **200M+ records/day** using PostgreSQL WAL mode, Selenium, and Python — transaction batches exceeding **100k records** per commit
- Designed a **self-healing worker orchestration layer** with async proxy-rotation; eliminated I/O bottlenecks on **2 GB+ TSV files** via memory chunking + atomic copies to meet a **15-min SLA**
- Developed API-driven middleware and data mappers for automated sync loops with **Horoshop SaaS**

---

**Technical Lead — Elephant in the Room** · *Volunteer* · *2026*

- Led a **7-person team** building a school-to-corporate sponsor matching engine
- Directed architecture, end-to-end workflow integrations, and I/O format specs using Irish government datasets (Eircode, school contacts, address data)

---

## Projects

### Parser 3.0 — Autonomous SaaS Ingestion Engine &nbsp;*(Founder & Lead Developer, 2026 – Present)*

> LLM-powered web-scraping engine with **self-healing selector extraction** — no manual selector maintenance

- Integrates LLMs to detect DOM changes and automatically re-derive CSS/XPath selectors
- Multi-step **mathematical data validation pipelines** to ensure output integrity at scale

`Python` `LLMs` `Scrapy` `Playwright` `FastAPI` `PostgreSQL`

---

### [GoRide](https://github.com/Cursyy/GoRide) — Real-Time Vehicle Rental Platform &nbsp;*(2025)*

> Full-stack ride-sharing service built from scratch — backend, real-time infra, billing, maps, and DevOps

- **Custom billing Finite State Machine** (Celery/Redis) — models all lifecycle states of a rental with fare calculation under varying conditions
- **WebSocket** channels for real-time support chat and push notifications
- **Geospatial map clustering** via OpenStreetMap + third-party geocoding API
- Async email delivery (auth confirmation), REST API, Docker deployment workflows

`Django` `Celery` `Redis` `PostgreSQL` `WebSockets` `Uvicorn` `Docker` `HTML/CSS`

---

### Pharmacy Market Intelligence Pipeline &nbsp;*(Freelance, 2024)*

> Continuous price & availability tracking engine — the foundation of the 200M+ records/day system

- **5 parallel Selenium workers × 20 async `curl_cffi` connections** per worker
- Staging table → deduplication → **2 GB TSV** atomically synced to Dropbox every **15 minutes**
- **24/7 uptime for 1+ year** · average maintenance: **< 1 hour/month**

`Python` `Selenium` `curl_cffi` `asyncio` `PostgreSQL WAL`

---

## Achievements

**Tallaght University Hospital Hackathons** · *Lead Backend & Full-Stack Developer* · *2024 – 2025*
- **2025 — IoT / Smart Campus**: Co-developed an edge-computing sensor network using Raspberry Pi & FastAPI edge servers to process live environmental data
- **2024 — Digital Health**: Delivered an e-library MVP portal for hospital staff (Django, SQLite, full UI integration)

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scrapy-60A839?style=flat"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat"/>
  <img src="https://img.shields.io/badge/Java_17-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat"/>
</p>

---

## GitHub Stats

<p align="center">
  <img src="https://nirzak-streak-stats.vercel.app/?user=OleksandrPodynihlazov&theme=radical&hide_border=false" height="155" alt="GitHub Streak"/>
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=OleksandrPodynihlazov&theme=github-compact" height="200"/>
</p>

---

<p align="center">
  <sub>Open to Software Engineer new-grad / graduate roles · Dublin & remote</sub>
</p>
