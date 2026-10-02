<!-- Header banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0ea5e9,100:1e293b&height=190&section=header&text=Robel%20Berhanu&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer%20%E2%80%A2%20API%20%26%20Microservices%20%E2%80%A2%20Travel%20%26%20FinTech&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Robel Berhanu — Full-Stack Developer" />

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=0EA5E9&center=true&vCenter=true&width=720&lines=Production+systems+for+travel+%26+financial+technology;Flight+booking+engines+%E2%80%A2+NDC+%26+GDS+integrations;Payment+platforms+%E2%80%A2+wallets+%E2%80%A2+ledgers+%E2%80%A2+POS;FastAPI+%E2%80%A2+React+%E2%80%A2+PostgreSQL+%E2%80%A2+GitHub+Actions" alt="Typing SVG" /></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/robel-berhanu-134b4a144/"><img src="https://img.shields.io/badge/LinkedIn-Robel%20Berhanu-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:robelberhanu89@gmail.com"><img src="https://img.shields.io/badge/Email-robelberhanu89%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://tasportals.com"><img src="https://img.shields.io/badge/Live-tasportals.com-0ea5e9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="TAS Portals live" /></a>
  <img src="https://komarev.com/ghpvc/?username=robelberhanu&style=for-the-badge&color=0ea5e9&label=Profile+views" alt="Profile views" />
</p>

### 👋 Hi there, I'm Robel!

#### 💼 Full-Stack Developer | API & Microservices | Travel & FinTech Solutions

Welcome to my GitHub profile! I'm a software developer with a focus on building scalable production systems for travel and financial technology domains — the kind of systems where money moves, airlines answer in XML, and the ledger has to balance to the cent.

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Travel%20Tech-0ea5e9?style=flat-square&logo=airbnb&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-FinTech-16a34a?style=flat-square&logo=cashapp&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-APIs%20%26%20Microservices-6366f1?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Focus-Cross--Platform-f59e0b?style=flat-square&logo=electron&logoColor=white" />
</p>

---

## 🎯 Professional Focus

I specialize in **end-to-end product development** — from API design and backend architecture to frontend implementation and deployment. My recent work spans:

| | Area | What that looks like in practice |
|---|---|---|
| 🛫 | **Travel Technology** | Flight booking systems, NDC & GDS integrations (Emirates, Ethiopian, Turkish, Amadeus), travel agent platforms |
| 💳 | **FinTech Solutions** | Payment processing, POS systems, agency wallets & double-entry ledgers, transaction management |
| 🔧 | **API & Microservices** | Scalable backend systems, SOAP/XML and REST data integration, real-time features |
| 📱 | **Cross-Platform Development** | Web, mobile (Capacitor), desktop (Electron) applications |

---

## 🌟 Featured Projects

### ✈️ **TAS Portals** — B2B Travel Agency Platform &nbsp;·&nbsp; [tasportals.com](https://tasportals.com)

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLAlchemy%202-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/React%2018-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white" />
</p>

A production **multi-tenant, multi-country** platform for travel agencies: an **agent portal** where agencies search, hold, issue, void and re-issue tickets, and an **admin console** for finance and operations — live for South African agencies.

- **Airline connectivity:** IATA **NDC 17.2** integrations with **Emirates** (Accelya/Farelogix), **Ethiopian Airlines** and **Turkish Airlines**, plus **Amadeus** classic (EDIFACT) and Amadeus NDC — one search fans out across all providers and merges whole-trip itineraries with mix-and-match one-way pieces.
- **Full ticket lifecycle:** AirShopping → OfferPrice → OrderCreate → OrderChange (issue) → void / refund / **exchange (re-issue)**, with per-passenger fare attribution, corporate deal codes, ancillaries (bags, seats, meals) and special service requests.
- **Money that balances:** agency **wallets with a double-entry ledger**, per-passenger charge and reversal lines, pricing rules (fees/discounts), pool-card settlement, idempotency keys, and a payment-safety reconciliation screen for airline-vs-ledger drift.
- **Documents:** WeasyPrint **e-ticket vouchers, invoices, credit notes and wallet statements** with per-passenger splits and tenant/agency branding.
- **Operations & safety:** admin locks, role-based permissions, audit log of every airline SOAP call (searchable XML drill-in), PAN encrypted at rest with key rotation, hash-locked dependencies, CI-built bundles with atomic deploys and rollback.
- **Stack:** Python 3.12 · FastAPI · SQLAlchemy 2 · Alembic · PostgreSQL · React 18 · Vite · Tailwind · Nginx · GitHub Actions → DigitalOcean.

### 💳 **KashPoint** — Enterprise Payment Platform

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI%20%2F%20Django-009688?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white" />
  <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
</p>

- **Multi-platform** desktop app, mobile (Capacitor), and web platform
- **Tech Stack:** Python backend (FastAPI/Django), JavaScript/TypeScript frontend, Electron, Capacitor
- **Repositories:**
  - [kashpoint-backend](https://github.com/Tesseractz/kashpoint-backend) — REST APIs and transaction processing
  - [kashpoint-frontend](https://github.com/Tesseractz/kashpoint-frontend) — React web application
  - [kashpoint-shells](https://github.com/Tesseractz/kashpoint-shells) — Mobile & desktop shells with Supabase
- **Features:** Cross-platform deployment, real-time data sync, secure transactions
- **Organization:** [Tesseractz](https://github.com/Tesseractz)

### 🎫 **AirVoucher** — Travel & Airline Platform

<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-6366f1?style=flat-square&logo=swagger&logoColor=white" />
</p>

- **Comprehensive travel ecosystem** with agent, retailer, terminal, admin, and mobile interfaces
- **Tech Stack:** TypeScript/Node.js backend, React frontend, Java mobile apps, REST APIs
- **Repositories:**
  - [airvoucher-api](https://github.com/TRPST/airvoucher-api) — Core API and business logic
  - [airvoucher-agent](https://github.com/TRPST/airvoucher-agent) — Agent platform (TypeScript)
  - [airvoucher-admin](https://github.com/TRPST/airvoucher-admin) — Admin dashboard
  - [airvoucher-terminal](https://github.com/TRPST/airvoucher-terminal) — POS terminal system
  - [airvoucher-mobile](https://github.com/TRPST/airvoucher-mobile) — Mobile app (Java)
  - [airvoucher-retailer](https://github.com/TRPST/airvoucher-retailer) — Retailer platform
  - [AirvoucherPOS](https://github.com/TRPST/AirvoucherPOS) — Point-of-sale system
- **Features:** Multi-role platform, real-time transaction handling, complex business workflows
- **Organization:** [TRPST](https://github.com/TRPST)

---

## 🛠️ Technology Stack

<p align="center">
  <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=python,fastapi,django,js,ts,nodejs,express,java,spring,react,vite,tailwind,html,css,postgres,supabase,sqlite,electron,docker,nginx,git,github,githubactions,postman,vscode,linux&perline=13" alt="Tech stack" /></a>
</p>

| Layer | Technologies |
|---|---|
| **Languages** | Python, JavaScript, TypeScript, Java, SQL |
| **Backend** | FastAPI, Django, Node.js/Express, Spring Boot, SQLAlchemy 2, Alembic, Pydantic |
| **Frontend** | React, Vite, Tailwind CSS, TanStack Query, HTML, CSS, TypeScript |
| **Databases** | PostgreSQL, Supabase, Electron/SQLite for desktop |
| **Integrations** | IATA NDC 17.2 (SOAP/XML), Amadeus Web Services (EDIFACT & NDC), payment gateways, SMTP |
| **Cross-Platform** | Capacitor (mobile), Electron (desktop), React Native considerations |
| **Tools & Platforms** | Git, Docker, Nginx, Postman, VS Code, GitHub Actions, DigitalOcean |
| **Architecture** | REST APIs, Microservices, Real-time data sync, Multi-tenant SaaS, Multi-platform deployment |

---

## 🧪 More Work

| Project | What it is | Stack |
|---|---|---|
| [ML_Algorithms_From_Scratch](https://github.com/robelberhanu/ML_Algorithms_From_Scratch) | The most common machine learning algorithms implemented from scratch | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |
| [content_based_product_recommender](https://github.com/robelberhanu/content_based_product_recommender) | Content-based product recommendations with cosine similarity | ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) |
| [chd_prediction_app](https://github.com/robelberhanu/chd_prediction_app) | Coronary heart disease prediction with logistic regression, deployed on GCP | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) |
| [animal_sound_classifier](https://github.com/robelberhanu/animal_sound_classifier) | Classifies animal sounds with a machine learning model | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| [MarsRoverApi-WebApp](https://github.com/robelberhanu/MarsRoverApi-WebApp) | Spring Boot app pulling Mars rover imagery from NASA's APIs | ![Spring](https://img.shields.io/badge/-Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) |
| [department-service](https://github.com/robelberhanu/department-service) | A Spring Boot microservice from a multi-service system | ![Java](https://img.shields.io/badge/-Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) |
| [social_media_aips](https://github.com/robelberhanu/social_media_aips) | Social-media style REST APIs | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) |

---

## 📚 Additional Expertise

- **Machine Learning & Data Science** — Python ML implementations, data analysis
- **System Design** — Scalable architectures, API design, database optimization
- **DevOps & Deployment** — Docker containerization, cloud deployment, CI/CD with hash-locked dependencies and atomic rollbacks
- **Security in production** — role-based permissions, encrypted card data at rest with key rotation, audited third-party calls

*See my [ML projects](https://github.com/robelberhanu?tab=repositories&q=ML) for more on this area.*

---

## 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=robelberhanu&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0ea5e9&icon_color=0ea5e9&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=robelberhanu&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=0ea5e9&langs_count=8" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=robelberhanu&theme=tokyonight&hide_border=true&background=0d1117&ring=0ea5e9&fire=0ea5e9&currStreakLabel=0ea5e9" alt="GitHub streak" />
</p>

---

## 📫 Let's Connect

- 🔗 **LinkedIn:** [robel-berhanu-134b4a144](https://www.linkedin.com/in/robel-berhanu-134b4a144/)
- 📧 **Email:** robelberhanu89@gmail.com
- 🌐 **Live work:** [tasportals.com](https://tasportals.com)
- 💬 **Open to:** Collaborations on fintech, travel tech, API design, and system architecture

---

<p align="center"><strong>Interested in production-grade systems? Check out the repositories above or reach out to discuss your project!</strong></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e293b,100:0ea5e9&height=100&section=footer" width="100%" alt="" />
