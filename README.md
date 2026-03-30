<h1 align="center">Hi, I'm Kiet 👋</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=17&duration=2800&pause=800&color=00C2FF&center=true&vCenter=true&width=900&lines=Full-stack+%26+AI+Engineer+%E2%80%94+Building+AI-powered+products+for+real+business+problems;From+contract+extraction+pipelines+to+smart+city+traffic+platforms;Research+%E2%86%92+Design+%E2%86%92+Ship+%E2%86%92+Scale" alt="Typing SVG" />
</p>

<p align="center">
  <a href="mailto:trinhkiet2005@gmail.com"><img src="https://img.shields.io/badge/Email-trinhkiet2005%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/YOUR_SLUG_HERE"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</p>

---

## 👨‍💻 About Me

I'm a **Full-stack & AI engineer** based in Vietnam, focused on turning real business problems into production-grade software.

- 🔍 I research market gaps and identify high-ROI automation opportunities
- 🤖 I build AI-enabled systems: LLM pipelines, RAG architectures, agent workflows
- 🏗️ I deliver end-to-end solutions — from schema design to deployed UI
- 🚀 I ship MVPs fast, then harden them toward production

> Currently building an **AI-powered contract management platform** for petrochemical turnaround projects — see below.

---

## 🔨 Currently Building

### TAR Contract Management Platform
> *Hackathon → production-ready MVP · 2026 Q1 · Solo*

An AI-powered contract intelligence system for high-stakes petrochemical turnaround (TAR) projects.

**The problem:** Engineering contracts run 50–200 pages each. Procurement teams manually review milestones, penalties, and payment triggers — taking 2–4 hours per contract, with high risk of missed obligations.

**What I built:**
- 📄 **AI Extraction Pipeline** — Upload PDF/DOCX → Claude Sonnet extracts structured milestones, obligations, penalties, and payment triggers with confidence scoring. Items below 0.9 confidence are auto-flagged for human review, with exact source clause as evidence.
- 🔍 **Contract Diff Engine** — Word-level comparison with side-by-side PDF text-layer highlighting (additions / deletions / modifications) and synced scrolling.
- ✅ **Approval Workflow + SLA** — Role-based routing (TAR Manager → PMO → Contract Manager), 24h countdown timers, auto-escalation via background worker.
- 📊 **RAG Health Dashboard** — Red/Amber/Green status per contract based on cost burn rate and milestone risk (overdue or due ≤ 3 days).
- 🔒 **Multi-org Isolation** — Row-Level Security in PostgreSQL + middleware ensures each party only sees their relevant data.

**Impact:**
| Metric | Before | After |
|---|---|---|
| Contract review time | 2–4 hours/contract | ~2–3 minutes (~95% reduction) |
| Missed deadline detection | Manual, reactive | Auto-alerts 3 days before deadline |
| Audit trail | Partial | 100% logged (timestamp + actor) |

**Stack:** Next.js 14 · Fastify 5 · PostgreSQL 16 · Prisma · BullMQ + Redis · Claude Sonnet (Anthropic) · Clerk (RBAC) · AWS S3 · Turborepo · Docker

---

## 📌 Other Projects

<table>
  <tr>
    <td width="50%">
      <h3>🤖 Nova AI</h3>
      <p>Python-first AI automation platform with modular LLM pipeline design — input normalization → context assembly → model execution → structured output. Built for reliability: retry logic, timeout handling, fallback strategies, and schema-validated outputs.</p>
      <p><strong>Stack:</strong> Python · LLM orchestration · Modular pipeline architecture</p>
      <a href="https://github.com/KietIT/nova-ai">🔗 View Repository</a>
    </td>
    <td width="50%">
      <h3>🚦 Techno-Traffix Platform</h3>
      <p>Smart traffic management platform combining Python data pipelines with a web dashboard for real-time monitoring and analytics. Enables incident-aware decision support and scalable experimentation for urban traffic operations.</p>
      <p><strong>Stack:</strong> Python (47%) · JavaScript/HTML/CSS (44%) · Jupyter Notebook · C++</p>
      <a href="https://github.com/KietIT/Techno-Traffix-Platform">🔗 View Repository</a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎓 Edu-Tech OJT Platform</h3>
      <p>Python-based education workflow backend with clean service layer architecture. Designed for maintainability and extensibility — structured to support AI-assisted academic features in future phases.</p>
      <p><strong>Stack:</strong> Python · Modular service architecture</p>
      <a href="https://github.com/KietIT/Edu-Tech-OJT">🔗 View Repository</a>
    </td>
    <td width="50%">
      <h3>🎯 Automated Attendance (Face Recognition)</h3>
      <p>Computer vision system for automated attendance tracking using facial recognition. End-to-end pipeline from camera feed to attendance record.</p>
      <a href="https://github.com/KietIT/-Automated-Attendance-System-with-Face-Recognition">🔗 View Repository</a>
    </td>
  </tr>
</table>

---

## 🛠️ Tech Stack

**AI / LLM**
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-LLM_Pipelines-8A2BE2?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Vector_Search-6A0DAD?style=flat-square)
![AI Agents](https://img.shields.io/badge/Agent_Workflows-Orchestration-5B2C6F?style=flat-square)

**Frontend**
![Next.js](https://img.shields.io/badge/Next.js_14-App_Router-000000?style=flat-square&logo=next.js)
![React](https://img.shields.io/badge/React-TypeScript-61DAFB?style=flat-square&logo=react&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-shadcn%2Fui-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![Python](https://img.shields.io/badge/Python-FastAPI_%2F_Service_Arch-3776AB?style=flat-square&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-Fastify-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Prisma_ORM-336791?style=flat-square&logo=postgresql&logoColor=white)

**Infrastructure**
![Redis](https://img.shields.io/badge/Redis-BullMQ-DC382D?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-S3_%2B_Presigned_URLs-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose_%2F_CI%2FCD-2496ED?style=flat-square&logo=docker&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-Monorepo-EF4444?style=flat-square)

---

## 📈 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=KietIT&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KietIT&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=KietIT&theme=tokyonight&hide_border=true" />
</p>

---

## 💼 How I Work With Businesses

| Engagement | Timeline | What you get |
|---|---|---|
| **Discovery Sprint** | 7–10 days | High-ROI use case mapping + delivery roadmap |
| **MVP Sprint** | 4–6 weeks | Deployed MVP with real users |
| **Custom Enterprise Build** | 8+ weeks | Tailored AI/full-stack system, production-ready |

I specialize in **AI integration for operational workflows** — contract management, document processing, workflow automation, and decision-support dashboards.

---

## 📣 Let's Work Together

If your company needs a custom AI or full-stack solution, I can take you from problem → architecture → production with a clear delivery roadmap.

📩 **Email:** trinhkiet2005@gmail.com  
💼 **LinkedIn:** https://www.linkedin.com/in/trinh-vy-kiet-4451213ba/
