# yeon-uu

Backend developer (undergrad) building servers with **Python · FastAPI**.
Learning security from an attacker's perspective through a university security club.

> Currently building: MOFA contest, Library contest

## 🛠 Tech Stack

**Backend** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)

**Database** &nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**DevOps** &nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazonec2&logoColor=white)

**Tools** &nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)

## 🚀 Projects

### Backend (Team)

- **[Mo-lib](https://github.com/yeon-uu/Mo-lib)** — Cross-domain (movie · book · music) recommendation service powered by LLM-based sentiment & context analysis.
  - **Backend & infra** — Owned the backend foundation: scaffolding, CI, and JWT auth. Shipped automated EC2 deployment (CD), migrated the DB layer to async (fixing server 500s), and hardened CI with secret scanning (Gitleaks) + dependency audits (pip-audit). My contributions are documented in the fork README.
- **[Roame](https://github.com/yeon-uu/2026-AI-Powered)** — GPS-based app that automatically tracks your daily route and turns it into an AI-written blog, for everyday life and travel.
  - **Backend & DevOps** — Built the backend and CI from scratch, then implemented the core APIs (async blog generation, subscriptions, S3-compatible storage) and the AI-server integration. Coordinated API contracts across the front-end and AI teams.

### Full-stack (Sole developer)

- **[2026-tourapi](https://github.com/yeon-uu/2026-tourapi)** — AI-powered web app that turns a randomly drawn train station into a themed local mission and archives each visit as a stamp, weighted toward depopulation-risk regions. Sole developer on a 3-person team (planning/UI-design and prompt-engineering teammates) — built the entire codebase (backend · front-end · infra) for the Tourism Data Lab AI Promptathon (관광데이터랩 프롬프톤) — **finalist: top 15 of 574 teams (195 passed the preliminary round)**.
  - **Architecture & implementation** — Wrapped the public TourAPI in a TTL cache to respect rate limits, designed a weighted-scoring algorithm to surface depopulation-risk regions, and built the AI-driven mission/recommendation flow end to end. FastAPI · PostgreSQL · Docker.

## 📫 Contact

- Email: **dyu8765@gmail.com**

## 📊 GitHub Stats

![yeon-uu's GitHub stats](https://github-readme-stats.vercel.app/api?username=yeon-uu&show_icons=true&hide=stars&count_private=true&include_all_commits=true&hide_rank=true&theme=transparent&hide_border=true)
