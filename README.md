<h1 align="center">Oleksandr Podynihlazov</h1>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=20&duration=3500&color=00F7FF&center=true&vCenter=true&width=640&lines=Software+Engineer+%E2%80%94+Python+%7C+Backend+%7C+Systems;BSc+Computing+with+AI+%26+ML+%40+TU+Dublin;Former+Intern+%40+Fidelity+Investments+%E2%80%94+ETF+Engine" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/oleksandrpodynihlazov">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:poduniglazov@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/>
  </a>
</p>

---

## About Me

Backend-focused software engineer, 3rd year **BSc Computing with AI & ML at TU Dublin**. I build systems that actually run in production — at scale, around the clock.

- Interned on the **ETF engine team at Fidelity Investments** (Java · Spring Boot · EKS · CI/CD)
- Built a **pharmacy data pipeline** that processes ~**40 million product records across 24 regions** in under 5 hours — running 24/7 for over a year with <1 h/month maintenance
- **Tech lead** on a 7-person volunteer project delivering a school-to-sponsor matching engine backed by Irish government datasets
- Designed and shipped **GoRide** — a full ride-sharing platform with a custom booking state machine, real-time WebSockets, maps, and async task processing

---

## Experience

| | |
|---|---|
| **Software Engineer Intern — Fidelity Investments** | *Jan – Aug 2026* |
| ETF engine team · Java · Spring Boot · Microservices · AWS EKS · CI/CD pipeline management | |
| **Tech Lead — Elephant in the Room** *(Volunteer)* | *2025 – 2026* |
| 7-person team · Python · Defined stack, requirements, data flows · Irish government dataset integration | |
| **Freelance Python Developer** | *2 years* |
| High-throughput scrapers & automation pipelines · Selenium · curl_cffi · asyncio · 40 M+ records | |

---

## Featured Projects

### Pharmacy Market Intelligence Pipeline &nbsp;*(Freelance)*

> Tracks price & availability across **4 500 SKUs × 24 regions ≈ 40 million records** per run, completing in **< 5 hours**

- **5 parallel Selenium workers**, each driving **20 async `curl_cffi` connections** simultaneously
- Staging table → deduplication → 2 GB TSV atomically synced to Dropbox every 15 minutes
- Deployed and self-healing — **24/7 uptime for 1 + year**, averaging **< 1 hour/month** of maintenance

`Python` `Selenium` `curl_cffi` `asyncio` `PostgreSQL` `Linux`

---

### [GoRide](https://github.com/Cursyy/GoRide) — Ride-Sharing Platform &nbsp;*(Personal / Team Project)*

> Full ride-sharing service built from scratch

- **Custom finite state machine** for the booking lifecycle — handles all edge cases of when a ride starts and how fare is calculated under varying conditions
- **WebSocket** channels for real-time support chat and push notifications
- Map layer via **OpenStreetMap** + third-party geocoding API
- Async email delivery (registration, auth confirmation) via **Celery + Redis**
- REST API, PostgreSQL schema design, query optimisation, Docker deployment

`Django` `Celery` `Redis` `PostgreSQL` `WebSockets` `Uvicorn` `Docker` `HTML/CSS`

---

### Elephant in the Room — School–Sponsor Matching Engine &nbsp;*(Volunteer, Tech Lead)*

> Connects Irish schools with potential corporate sponsors — built by a 7-person team I led technically

- Hydrates school records from Irish government datasets (Eircode, contact directories, address data)
- Applies configurable matching rules: geographic proximity, data completeness, sponsorship readiness score
- I owned architecture decisions, tech-stack selection, I/O format specs, and inter-module data flows

`Python` `Government open data` `Data pipelines` `Team leadership`

---

## Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/WebSockets-010101?style=flat"/>
  <img src="https://img.shields.io/badge/REST_APIs-009688?style=flat"/>
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
