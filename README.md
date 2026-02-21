# Shrikanth V
Full-stack engineer focused on AI-enabled products and data-rich web applications—shipping stateless generation pipelines, workflow-orchestrated platforms, and analytics dashboards across Python and TypeScript.

---

## Tech Stack
| Category | Technologies |
|----------|-------------|
| Languages | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| Backend & APIs | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) |
| Frontend & UI | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) |
| Data & Storage | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) |
| ML & Analytics | ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) |
| DevOps & Cloud | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) |

---

## Featured Projects

### [confer-marketing-pipeline](https://github.com/shrikanthv15/confer-marketing-pipeline)
> Stateless AI marketing asset generator with a FastAPI orchestrator and Next.js 16 UI—BYOK key pass-through, parallel calls to multiple image/video model providers, and downloadable outputs.

![Stars](https://img.shields.io/github/stars/shrikanthv15/confer-marketing-pipeline?style=social)
![Language](https://img.shields.io/badge/Language-Python-3776AB?style=flat-square&logo=python&logoColor=white)

```mermaid
graph LR
  User[User] --> Web[Nextjs Web]
  Web --> Api[FastAPI API]
  Api --> Providers[Model Providers]
  Providers --> Api
  Api --> Web
```

| | |
|---|---|
| **Stack** | Python, FastAPI, TypeScript, Next.js |
| **Highlights** | Stateless architecture with no DB or accounts, BYOK via browser LocalStorage per-request, parallel multi-provider generation for images and video |

### [Git-Repo-Organizer](https://github.com/shrikanthv15/Git-Repo-Organizer)
> Full-stack Git repository analysis and organization platform: FastAPI backend with Temporal for long-running workflows, PostgreSQL persistence, and a Next.js dashboard—shipped with Docker Compose for end-to-end local orchestration.

![Stars](https://img.shields.io/github/stars/shrikanthv15/Git-Repo-Organizer?style=social)
![Language](https://img.shields.io/badge/Language-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

```mermaid
graph LR
  Client[Browser Client] --> Frontend[Nextjs Frontend]
  Frontend --> Api[FastAPI API]
  Api --> Temporal[Temporal Server]
  Temporal --> Worker[Temporal Worker]
  Worker --> Db[PostgreSQL]
  Api --> Db
```

| | |
|---|---|
| **Stack** | TypeScript, Next.js, Python, FastAPI, PostgreSQL, Docker |
| **Highlights** | Temporal-based workflow orchestration for long tasks, clear separation of UI vs API vs workers, compose-driven local dev environment |

### [los-app-staging](https://github.com/shrikanthv15/los-app-staging)
> Staging workspace for a Loan Origination System (LOS) monorepo with an explicit “two repo” strategy, strict architecture guidance, and PNPM-based development flow for rapid iteration.

![Stars](https://img.shields.io/github/stars/shrikanthv15/los-app-staging?style=social)
![Language](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

| | |
|---|---|
| **Stack** | JavaScript, pnpm |
| **Highlights** | Documentation-first engineering with architecture guide and roadmap, monorepo source-of-truth layout, workflow optimized for staging and iteration |

### [valorant-data-analysis](https://github.com/shrikanthv15/valorant-data-analysis)
> Analytics platform for Valorant Champions 2025 datasets with dedicated team/player pages, Plotly-powered charts, and a Python Flask backend for data processing and API delivery.

![Stars](https://img.shields.io/github/stars/shrikanthv15/valorant-data-analysis?style=social)
![Language](https://img.shields.io/badge/Language-CSS-1572B6?style=flat-square&logo=css3&logoColor=white)

```mermaid
graph LR
  Csv[CSV Data] --> Backend[Flask Backend]
  Backend --> Metrics[Analytics Metrics]
  Metrics --> Ui[Web UI]
```

| | |
|---|---|
| **Stack** | Python, Flask, Pandas, NumPy, TensorFlow, scikit-learn |
| **Highlights** | Team and player analytics pages, interactive visualization layer, ML-capable stack for modeling and feature engineering |

---

## GitHub Stats
```html
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shrikanthv15&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shrikanthv15&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>
```