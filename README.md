<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f172a,100:6366f1&text=Nikolai%20Tatianenko&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=Engineering%20Leader%20%C2%B7%20Hands-on%20Architect%20%C2%B7%20AI-Driven%20Engineering%20Transformation&descAlignY=58&descSize=18" alt="header" />

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=20&pause=1200&color=6366F1&center=true&vCenter=true&width=620&lines=Engineering+Leader+%7C+Hands-on+Architect;AI+Adoption+%26+Engineering+Transformation;Multi-agent+systems%2C+RAG%2C+MCP;18%2B+years%2C+12%2B+in+engineering+leadership" alt="Typing SVG" /></a>

📍 San Diego &nbsp;·&nbsp; [LinkedIn](#)

</div>

---

### 👋 About

Engineering leader with 18+ years in software engineering and 12+ in leadership. I combine enterprise engineering foundations with startup speed and ownership, and I stay hands-on as an architect.

- 🏗️ **Architect:** modular TypeScript monorepos, microservices and microfrontends, design systems, provider-independent AI platforms
- 🤖 **AI adoption:** tool evaluation and rollout, hands-on training, workflow redesign, AI engineering standards and safeguards
- 🧠 **Agentic systems:** multi-agent orchestration, RAG, MCP, internal developer plugins, observability and evals for AI
- 👥 **Leadership:** engineering strategy, hiring, coaching technical leads, growing engineers into leaders, delivery and production reliability
- ⚙️ **Engineering practice:** CI/CD, automated testing, developer experience, reusable platform foundations

---

### 🧰 Tech stack

<div align="center">

**Languages**<br>
<img src="https://skillicons.dev/icons?i=ts,js,python,c,cs,html,css&perline=7" /><br><br>
**Frontend & Build**<br>
<img src="https://skillicons.dev/icons?i=react,nextjs,vite,webpack,tailwind,graphql,apollo&perline=7" /><br><br>
**Mobile**<br>
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=ios&logoColor=white" />
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" /><br>
<img src="https://skillicons.dev/icons?i=swift,kotlin,androidstudio&perline=3" /><br><br>
**Desktop & Games**<br>
<img src="https://skillicons.dev/icons?i=electron,tauri,unity,cs&perline=4" /><br><br>
**Backend & Data**<br>
<img src="https://skillicons.dev/icons?i=nodejs,nestjs,postgres,sqlite,mongodb,redis&perline=6" /><br><br>
**Cloud & DevOps**<br>
<img src="https://skillicons.dev/icons?i=aws,gcp,docker,kubernetes,terraform,githubactions,gitlab,git,github&perline=9" /><br><br>
**AI Platforms & Models**<br>
<img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=claude&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white" />
<img src="https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge" />
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /><br><br>
**AI & Tooling**<br>
<img src="https://skillicons.dev/icons?i=tensorflow,figma,vercel&perline=3" />

</div>

---

### 🚦 Featured project: QualityGate

**[QualityGate](https://github.com/nikolai-tatianenko/quality-gates)** runs the checks a project already has (lint, types, tests, Lighthouse, scanners) and turns them into **one PASS / BLOCK decision** with findings you can act on and evidence you can inspect. The same declared checks run locally, in Git hooks, in CI and from an AI coding agent over MCP, so a person and an agent get the same verdict.

**Why I built it:** lint, tests and scanners are scattered across scripts, CI jobs and agent prompts, and a green pipeline can hide a tool that crashed, timed out or never ran. QualityGate makes failures explicit: a broken tool, a missing report or a timeout can never turn into a pass.

| | |
|---|---|
| 🔌 **Interfaces** | CLI · MCP server for agents (Claude Code demo included) · React dashboard · static HTML report |
| 🧩 **Plugins** | Command gates, report parsers (JUnit, NUnit, Playwright, ESLint, axe-core, Unity) and ecosystem detectors for Node, Python, Unity, Playwright and Maestro |
| ⚙️ **Setup** | `qualitygate setup` reads a repo (including pnpm monorepos) and proposes gates; slow or browser-bound ones are listed as "found but not enabled" |
| ⚡ **Speed** | Parallel gates with dependencies, `--only`, `--changed` and an input-hash cache |
| 🛡️ **Trust** | Exit-code contract (PASS, BLOCK, error, timeout, interrupted), a step registry that says how many checks actually ran, read-only shared dashboards, a documented threat model |
| 🔁 **CI** | GitHub, GitLab and Bitbucket templates, commit status, sticky PR comment, Slack alerts, SARIF export for code scanning |
| ✅ **Quality** | TypeScript strict · ~200 tests · 100% line coverage · tried on a real pnpm monorepo with Vitest and Playwright |

**Check → read the cause → fix → check again.** In progress: run history and trends, dependency and secret scanner parsers, a live terminal view, plugin signing; desktop (Tauri) and Chrome extension clients are planned. MIT licensed.

[Repository](https://github.com/nikolai-tatianenko/quality-gates) · [Quickstart](https://github.com/nikolai-tatianenko/quality-gates#try-it-locally) · [Roadmap](https://github.com/nikolai-tatianenko/quality-gates/blob/main/docs/QUALITYGATE_DETAILED_ROADMAP.md)

---

### 📦 Open source

| Repo | Stack |
|---|---|
| [Quality Gates](https://github.com/nikolai-tatianenko/quality-gates) | TypeScript · Node.js · CLI · MCP · React · CI/CD |
| [microfrontends-examples](https://github.com/nikolai-tatianenko/microfrontends-examples) | Microfrontends |
| [realtime-examples](https://github.com/nikolai-tatianenko/realtime-examples) | WebSockets · Realtime |
| [nosql_presentation](https://github.com/nikolai-tatianenko/nosql_presentation) | NoSQL |

---

<div align="center">


<img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:6366f1,100:0f172a&section=footer" />

</div>
