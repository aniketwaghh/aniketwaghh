<div align="center">

<a href="https://www.linkedin.com/in/aniket-s-wagh">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3200&pause=900&color=6E7BF2&center=true&vCenter=true&width=760&lines=AI+Software+Engineer+%E2%80%A2+Agentic+Systems;Multi-Agent+Platforms+%C2%B7+LLM+Gateways+%C2%B7+RAG+at+Scale;Guardrails%2C+Observability+and+Governance+from+Day+One" alt="AI Software Engineer — agentic systems, multi-agent platforms, LLM gateways, RAG at scale" />
</a>

### Aniket Wagh

**I ship production agentic AI systems — and the governance layer that makes enterprises trust them.**

<a href="https://www.linkedin.com/in/aniket-s-wagh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:contact.aniketwagh@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://github.com/aniketwaghh?tab=repositories"><img src="https://img.shields.io/badge/Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Projects" /></a>
<img src="https://img.shields.io/badge/AWS_Certified_Developer-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Developer – Associate" />
<img src="https://img.shields.io/badge/Pune,_India-34A853?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Pune, India" />

</div>

---

## About

I'm an **AI Software Engineer at [Apexon](https://www.apexon.com)** with ~2 years owning agentic AI systems end to end — from discovery and technical scoping through production rollout and client adoption.

Most "AI demos" die on the way to production. My work is the part that survives the trip: **multi-agent orchestration**, **retrieval that holds up at petabyte scale**, and the **guardrails, observability, RBAC and cost controls** that let a CXO actually sign off on shipping it.

```text
 Discovery  →  Scoping  →  Agent design  →  Guardrails + evals  →  Rollout  →  Adoption
              ↑                                                                    │
              └──────────────── I own this whole line, not a slice ────────────────┘
```

- 🧠 **Deep in** — LangGraph, CrewAI, MCP server development, context engineering, agent sandboxing, human-in-the-loop design
- 🏗️ **Currently building** — an open **[RAG Pipeline Studio](https://github.com/aniketwaghh/rag-studio)** and **[GarudaSDLC](https://github.com/aniketwaghh/GarudaSDLC)**, an agentic SDLC that turns client meetings into shipped software
- 🌱 **Contributing to** — the Python AI/agent open-source stack ([Chainlit](https://github.com/Chainlit/chainlit), MCP tooling)
- 💬 **Ask me about** — taking an agent from notebook to a governed, observable, multi-tenant production service
- 📫 **Reach me** — [contact.aniketwagh@gmail.com](mailto:contact.aniketwagh@gmail.com) · [LinkedIn](https://www.linkedin.com/in/aniket-s-wagh)

---

## Work I've shipped

Production systems built for enterprise clients at Apexon. These codebases are proprietary, so what's here is the problem, the architecture and the measured outcome.

<table>
<tr>
<td width="50%" valign="top">

### 🔎 DocAIQ — Enterprise RAG Platform
*Python · FastAPI · pgvector · S3 · React · AWS · Docker*

Enterprise knowledge scattered across massive repositories made retrieval slow and insecure. Built a distributed, **multi-tenant multimodal RAG platform** for citation-backed AI search.

- Distributed ingestion + retrieval over **petabyte-scale** knowledge bases and GB-sized multimodal files, event-driven on AWS
- Tenant-aware **RBAC/ABAC**, metadata-filtered retrieval, vector search, reranking and citations
- Auto-scaling microservices sustaining **200+ queries/sec** with low-latency semantic search

</td>
<td width="50%" valign="top">

### 🕸️ AgentRise — Low-Code Multi-Agent Platform
*Python · FastAPI · LangGraph · CrewAI · React · AWS*

Teams needed to ship AI agents without deep framework expertise. Built a **drag-and-drop multi-agent workflow builder** targeting multiple runtimes.

- Visual builder supporting **LangGraph and CrewAI** runtimes — agent development cut from **days to hours**
- RBAC, guardrails, LLM observability and gateway integration → secure rollout to **10+ engineering teams**
- Cloud-native on AWS with Docker + CI/CD at **99%+ availability**
- Led client demos and POCs, translating stakeholder needs into platform features

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚪 Enterprise LLM Gateway
*Python · FastAPI · Multi-Provider LLM APIs · PostgreSQL · AWS*

Model access was scattered across untracked integrations. Built the **centralized, governed gateway** every team now routes through.

- Multi-provider access with **virtual keys**, team-level budgeting, cost controls, observability and guardrails
- **Provider-agnostic API** — switch LLM providers with zero code changes
- CXO-level spend/usage dashboards; new model onboarding cut from **weeks to hours**

</td>
<td width="50%" valign="top">

### 📞 Employee Experience Voice AI Agent
*Python · STT/TTS · LLMs · Telephony*

HR surveys had low participation and slow manual follow-up. Launched a **voice agent that calls employees** and turns conversations into structured insight.

- Designed the conversation flow, prompting and **escalation paths** for human follow-up on flagged responses
- Raised feedback response rates by **75%+**
- Near real-time sentiment dashboards for HR leadership and CXO stakeholders

</td>
</tr>
</table>

> **Spec-Driven Development adoption** — introduced GitHub Spec Kit on a client brownfield platform, encoding standards in a project constitution and running `specify → plan → tasks → implement` with human-in-the-loop approval gates. **First-pass code acceptance improved 70%**, with clear stakeholder visibility before implementation.

---

## Open source

| Project | Contribution | Status |
| :-- | :-- | :-- |
| **[Chainlit](https://github.com/Chainlit/chainlit)** | [`feat(mcp): support mcp 2.x alongside 1.x`](https://github.com/Chainlit/chainlit/pull/3030) — verified the MCP 1.x/2.x API surface by introspecting the SDKs directly, corrected two wrong assumptions in the tracking issue, and landed one code path that serves both majors with no version sniffing | 🟢 Open |
| **[kana-dojo](https://github.com/lingdojo/kana-dojo)** | Content contribution to the Japanese-learning platform | ✅ Merged |

---

## Featured repositories

<table>
<tr><th align="left">Repository</th><th align="left">What it is</th><th align="left">Stack</th></tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/GarudaSDLC"><b>GarudaSDLC</b></a></td>
  <td>AI "employees" that turn client meetings into shipped software — a silent bot joins the call, builds a searchable knowledge graph, drafts Jira tickets and runs impact analysis. Humans approve everything; every decision traces back to a video timestamp.</td>
  <td>Python · Agents · Pinecone · Slack/Jira APIs · AWS</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/rag-studio"><b>rag-studio</b></a></td>
  <td>RAG Pipeline Studio — a visual builder for production RAG pipelines. <code>uv</code> workspace backend split into API and worker services, Turborepo React frontend, Kubernetes deployment path.</td>
  <td>Python · FastAPI · TypeScript · Turborepo · K8s</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/sahayog-ai"><b>sahayog-ai</b></a></td>
  <td>SahayogAI product site — React + Vite frontend with a Node backend, internationalisation, analytics and an Nginx deployment path.</td>
  <td>React · Vite · Node · Tailwind · Nginx</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/llm-learning-lab"><b>llm-learning-lab</b></a></td>
  <td>Building and optimising LLMs from scratch — fine-tuning, quantisation (LoRA/QLoRA) and experiments with new GenAI techniques.</td>
  <td>Python · PyTorch · Transformers</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/blockbuy-marketplace"><b>blockbuy-marketplace</b></a></td>
  <td>Blockchain-powered marketplace — Flutter cross-platform client backed by Ethereum smart contracts, built for security, transparency and decentralised trust.</td>
  <td>Dart · Flutter · Solidity · Web3</td>
</tr>
</table>

---

## Stack

**Agentic AI & LLM Engineering**

<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=crewai&logoColor=white" alt="CrewAI" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol" />
  <img src="https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI Agents SDK" />
  <img src="https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google ADK" />
  <img src="https://img.shields.io/badge/RAG_%2F_Vector_DBs-0EA5E9?style=for-the-badge&logo=databricks&logoColor=white" alt="RAG and Vector Databases" />
  <img src="https://img.shields.io/badge/LoRA_%2F_QLoRA-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="LoRA and QLoRA fine-tuning" />
  <img src="https://img.shields.io/badge/Evals_%26_Guardrails-16A34A?style=for-the-badge&logo=checkmarx&logoColor=white" alt="Evals and Guardrails" />
  <img src="https://img.shields.io/badge/Spec_Kit-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Spec Kit" />
</p>

**Languages, Backend & Frontend**

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,ts,js,java,react,redux,tailwind,materialui,vite&perline=12" alt="Python, FastAPI, Django, Flask, TypeScript, JavaScript, Java, React, Redux, Tailwind, Material UI, Vite" />
</p>

**Cloud, Data & Platform**

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,postgres,redis,kafka,nginx,grafana,linux,git,github,nodejs&perline=12" alt="AWS, Docker, Kubernetes, PostgreSQL, Redis, Kafka, Nginx, Grafana, Linux, Git, GitHub, Node.js" />
</p>

---

## By the numbers

<div align="center">

<!-- These cards are generated by a GitHub Action into this repo, so they never break
     when a third-party rendering service goes down or gets rate limited. -->
<img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="Profile details" width="88%" />

<img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repositories per language" width="44%" />
<img src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most committed language" width="44%" />

<img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="Contribution stats" width="44%" />
<img src="./profile-summary-card-output/github_dark/4-productive-time.svg" alt="Most productive time of day" width="44%" />

<img src="https://streak-stats.demolab.com?user=aniketwaghh&theme=github-dark-blue&hide_border=true&border_radius=8&date_format=j%20M%5B%20Y%5D" alt="Contribution streak" width="88%" />

</div>

### Contribution graph

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake.svg" />
    <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake.svg" width="95%" />
  </picture>
</div>

---

## Certifications & recognition

| | |
| :-- | :-- |
| 🏅 **AWS Certified Developer – Associate** (DVA-C02) | Amazon Web Services |
| 📜 **AI Engineer — Core Track** | LLM engineering, RAG pipelines, LoRA/QLoRA fine-tuning, evaluation, observability *(Udemy · Ed Donner)* |
| 📜 **AI Engineer — Agentic Track** | Agentic design patterns, context engineering, MCP, CrewAI, LangGraph, OpenAI Agents SDK *(Udemy · Ed Donner)* |
| 🏆 **AI Fiesta — Certificate of Appreciation** | Apexon — for driving AI adoption and an AI-first engineering mindset across teams |
| 🌟 **Budding Star Award, Q4** | Apexon — for exceptional performance and rapid learning |
| 🎓 **B.Tech, Computer Science & Engineering (AI)** | Nutan College of Engineering and Research, Pune · 2024 · CGPA 8.28/10 |

---

<div align="center">

### Let's build something that actually ships

Open to conversations about **agentic AI platforms**, **LLM infrastructure and governance**, and **open-source collaboration**.

<a href="https://www.linkedin.com/in/aniket-s-wagh"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="mailto:contact.aniketwagh@gmail.com"><img src="https://img.shields.io/badge/Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Say hello by email" /></a>

<sub>Profile stat cards are generated in-repo by GitHub Actions — no third-party uptime required.</sub>

</div>
