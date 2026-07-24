<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Adib%20Rahman&fontSize=44&fontColor=ffffff&fontAlignY=34&desc=Software%20Engineer%20%E2%80%94%20Dhaka,%20Bangladesh&descAlignY=55&descSize=15" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&width=760&lines=Full-stack+engineer+building+applied+AI+systems;RAG+pipelines+%C2%B7+realtime+infra+%C2%B7+healthcare+tech;Fine-tuning+NLP+models+for+Bangla+%26+Banglish" alt="Typing intro" />

<br/>

<a href="https://www.linkedin.com/in/adib-rahman51/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:adibrahman44@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>


</div>

---

I build production-shaped web systems and wire real AI into them — retrieval pipelines over vector databases, multi-model LLM orchestration, and realtime infrastructure. Most of my work lands in **healthcare**, **team collaboration**, and **Bangla / Banglish language products**.

- Software Engineering undergrad at **Islamic University of Technology** 
- Shipped production frontend and backend as a **Software Engineer Intern at ADN DigiNet Ltd.**
- Two independent RAG systems in production projects — **ChromaDB** and **pgvector + IVFFlat**
- Fine-tuned **XLM-RoBERTa** on a custom Banglish dataset, because off-the-shelf models don't understand how Bangladesh actually types



---

## Stack

| | |
|:--|:--|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Java](https://img.shields.io/badge/Java-E76F00?style=flat-square&logo=openjdk&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |
| **Frontend** | ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square&logo=databricks&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **AI / ML** | ![Gemini](https://img.shields.io/badge/Gemini_2.5-8E75B2?style=flat-square&logo=googlegemini&logoColor=white) ![Groq](https://img.shields.io/badge/Groq_·_LLaMA_4-F55036?style=flat-square&logo=meta&logoColor=white) ![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![RAG](https://img.shields.io/badge/RAG_·_pgvector-4169E1?style=flat-square&logo=vectorworks&logoColor=white) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![LiveKit](https://img.shields.io/badge/LiveKit_·_WebRTC-1B1B1B?style=flat-square&logo=webrtc&logoColor=white) |

---

## Selected Work

### ◆ Backfire OS — adversarial brand simulation engine
*Champion track entry, Infinity AI Buildfest 2026 · MarTech*

Stress-tests a marketing campaign **before** launch by fanning it out to six parallel AI red-team personas that attack it from different angles.

- **Banglish RAG pipeline** over ~20K BnSentMix embeddings (pgvector + IVFFlat) for culturally grounded Bangladeshi sentiment analysis
- **Boardroom Mode** — four synthetic personas debate the campaign turn-by-turn on a hybrid Groq architecture (`llama-4-scout` + `groq/compound`) and close with a greenlight / revise / kill verdict
- **Regulatory Pre-Mortem Generator** — writes the forward-dated incident report and public apology the brand would be forced to publish
- Counterfactual branching ("Git for campaigns"), a geo-demographic cultural stress heatmap, and an AI meme mutation simulator

`Next.js 16` `React 19` `Supabase (pgvector)` `Gemini` `Groq` `Tailwind 4`

[**Live Demo**](https://backfire-phi.vercel.app/) · [**Code**](https://github.com/adibqt/BackfireOS)

<br/>

### ◆ MedNexus — full-stack healthcare platform
Connects patients, doctors, pharmacies, clinics/labs, and administrators in one system.

- **AI consultation module** on Gemini 2.5 Flash with a RAG pipeline over a ChromaDB medical knowledge base, plus voice-based symptom input
- **HD video consultations** via LiveKit (WebRTC) with WebSocket call signalling
- E-prescription PDF generation (ReportLab), appointment booking with email notifications, pharmacy/lab quotation modules
- Multi-role JWT auth with Bcrypt hashing, and an admin analytics dashboard in Recharts

`React` `FastAPI` `PostgreSQL` `SQLAlchemy` `ChromaDB` `LiveKit` `FFmpeg`

[**Code**](https://github.com/adibqt/MedNexus)

<br/>

### ◆ Team Hub — collaborative team workspace
Shared goals and milestones, rich-text announcements, and action items on a drag-and-drop Kanban board.

- **Optimistic UI with rollback** and **offline support** — a localStorage read cache plus a replayable write queue
- Socket.io realtime updates with presence and @mention notifications
- JWT auth with httpOnly cookie refresh tokens; role-based workspaces with Brevo email invitations
- Immutable audit log with CSV export, Swagger API docs, Jest test suites
- Architected as a Turborepo + pnpm monorepo, deployed on Railway

`Next.js 14` `Express` `PostgreSQL` `Prisma` `Socket.io` `Zustand` `Docker`

 [**Code**](https://github.com/adibqt/team_hub)

<br/>

<details>
<summary><b>More projects</b></summary>

<br/>



**MachMangsho** — MERN grocery delivery app
Product catalog across dairy, bakery, grains, instant foods, vegetables and beverages; order management with realtime tracking and cash-on-delivery; seller dashboard with live sales statistics; Stripe payments, Cloudinary image hosting, JWT/Bcrypt role-based auth.
`React` `Express` `MongoDB` `Stripe` `Cloudinary` — [Live Demo](https://mach-mangsho.vercel.app/) · [Code](https://github.com/adibqt/MachMangsho)

</details>

---

## Experience

**Software Engineer Intern** — ADN DigiNet Ltd., Dhaka *(onsite · Oct–Nov 2025)*

- Developed the web version of **Click & Care**, an AI-powered telemedicine platform for a Malaysian healthcare client, contributing across frontend and backend
- Built and optimized frontend modules for **Business 360**, an enterprise business management platform, improving UI consistency and performance across modules
- Worked with cross-functional teams on requirement analysis, code reviews, and component-based architecture in React and FastAPI

---

## Competitions

| Result | Event |
|:--|:--|
| **Champion** | CloudCamp Infinity AI Buildfest 2026 — VCP |
| **Finalist** | CloudCamp Infinity AI Buildfest 2026 — Hackathon |
| **18th worldwide** | University Rover Challenge 2025, USA — on-site finalist |
| **Top 15 / 51 teams** | IIUC NextGen Hackathon 2025 — finalist |
| **On-site finalist** | BUBT InnovateX Hackathon 2025 |
| **Finalist** | CUET Sciblitz 2.0 AI Hackathon- On-site Finalist. |

---

## Beyond the code

**Assistant Head of Marketing** — IUT Robotics Society *(2026 – present)*
Lead planning and execution of **Techathon Nationals 2026**, coordinating both the Hackathon and E-Sports segments. Driving sponsorship outreach, promotional strategy, and stakeholder communication.

**Senior Member, Management Sub-team** — Project Altair *(2024 – present)*
Documentation and PR, plus internal coordination across multiple sub-teams.

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR-GITHUB-USERNAME&show_icons=true&count_private=true&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8&icon_color=38BDF8" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR-GITHUB-USERNAME&layout=compact&langs_count=8&hide_border=true&theme=tokyonight&bg_color=0D1117&title_color=38BDF8" alt="Top languages" />

<br/><br/>



<a href="mailto:adibrahman44@gmail.com"><img src="https://img.shields.io/badge/adibrahman44@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/adib-rahman51/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

</div>
