<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3200&pause=900&color=6E7BF2&center=true&vCenter=true&width=760&lines=AI+Software+Engineer+%E2%80%A2+Agentic+Systems;Multi-Agent+Platforms+%C2%B7+LLM+Gateways+%C2%B7+RAG+at+Scale;I+take+agents+from+notebook+to+production" alt="AI Software Engineer — agentic systems, multi-agent platforms, LLM gateways, RAG at scale" />

### Aniket Wagh

**Most AI demos die on the way to production. I build the part that survives the trip.**

<a href="https://www.linkedin.com/in/aniket-s-wagh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:contact.aniketwagh@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<img src="https://img.shields.io/badge/AWS_Certified_Developer-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Developer – Associate" />
<img src="https://img.shields.io/badge/Pune,_India-34A853?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Pune, India" />

</div>

---

## The stack I actually ship

Anyone can wire an LLM to a prompt. The interesting engineering is everything *around* it — the layer that makes an enterprise willing to put it in front of real users:

```mermaid
flowchart LR
    U([User]) --> GW["🚪 LLM Gateway<br/>virtual keys · budgets · failover"]
    GW --> GR{"🛡️ Guardrails"}
    GR --> ORCH["🕸️ Agent Orchestrator<br/>LangGraph · CrewAI"]

    ORCH <--> MEM[("🧠 Memory<br/>& State")]
    ORCH <--> RAG["🔎 RAG Retrieval<br/>vector · rerank · cite"]
    ORCH <--> TOOLS["🔌 Tools / MCP<br/>sandboxed"]

    ORCH --> HITL{"👤 Human<br/>in the loop"}
    HITL -->|approved| OUT([Shipped])
    HITL -->|rejected| ORCH

    ORCH -.emits.-> OBS["📊 Traces · Evals · Cost"]

    style GW fill:#6E7BF2,stroke:#4C56C0,color:#fff
    style ORCH fill:#1C3C3C,stroke:#0f2424,color:#fff
    style HITL fill:#FF9900,stroke:#cc7a00,color:#fff
    style OBS fill:#16A34A,stroke:#0f7434,color:#fff
```

🔭 Currently building **[GarudaSDLC](https://github.com/aniketwaghh/GarudaSDLC)** and **[rag-studio](https://github.com/aniketwaghh/rag-studio)** &nbsp;·&nbsp; 🌱 contributing to the Python agent ecosystem &nbsp;·&nbsp; 💬 ask me about **making agents observable, governed and multi-tenant**

---

## What I'm building

<table>
<tr><th align="left">Repo</th><th align="left">What it does</th><th align="left">Stack</th></tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/GarudaSDLC"><b>GarudaSDLC</b></a></td>
  <td>AI "employees" that turn client meetings into shipped software. A silent bot joins the call, builds a searchable knowledge graph, drafts Jira tickets and runs impact analysis — humans approve everything, and every decision traces back to a video timestamp.</td>
  <td>Python · Agents · Pinecone · AWS</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/rag-studio"><b>rag-studio</b></a></td>
  <td>A visual builder for production RAG pipelines. <code>uv</code> workspace split into API and worker services, Turborepo React frontend, Kubernetes deployment path.</td>
  <td>FastAPI · TypeScript · K8s</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/sahayog-ai"><b>sahayog-ai</b></a></td>
  <td>SahayogAI product site — React + Vite with a Node backend, i18n, analytics and an Nginx deployment path.</td>
  <td>React · Vite · Node</td>
</tr>
<tr>
  <td><a href="https://github.com/aniketwaghh/blockbuy-marketplace"><b>blockbuy-marketplace</b></a></td>
  <td>Blockchain-powered marketplace — Flutter client backed by Ethereum smart contracts.</td>
  <td>Flutter · Solidity · Web3</td>
</tr>
</table>

---

## Open source

| Project | Contribution | |
| :-- | :-- | :-- |
| **[Chainlit](https://github.com/Chainlit/chainlit)** | [`feat(mcp): support mcp 2.x alongside 1.x`](https://github.com/Chainlit/chainlit/pull/3030) — introspected both MCP SDK majors directly, corrected two wrong assumptions in the tracking issue, and landed **one code path serving both** with no version sniffing | 🟢 Open |
| **[kana-dojo](https://github.com/lingdojo/kana-dojo)** | Content contribution to the Japanese-learning platform | ✅ Merged |

---

## Toolkit

<div align="center">

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/CrewAI-FF5A50?style=for-the-badge&logo=crewai&logoColor=white" alt="CrewAI" />
<img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" alt="Model Context Protocol" />
<img src="https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI Agents SDK" />
<img src="https://img.shields.io/badge/RAG_%2F_Vector_DBs-0EA5E9?style=for-the-badge&logo=databricks&logoColor=white" alt="RAG and Vector Databases" />

<img src="https://skillicons.dev/icons?i=python,fastapi,django,ts,js,java,react,redux,tailwind,vite&perline=10" alt="Python, FastAPI, Django, TypeScript, JavaScript, Java, React, Redux, Tailwind, Vite" />

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,postgres,redis,kafka,nginx,grafana,linux,git&perline=10" alt="AWS, Docker, Kubernetes, PostgreSQL, Redis, Kafka, Nginx, Grafana, Linux, Git" />

</div>

<details>
<summary><b>🎓 Credentials & recognition</b> — <i>click to expand</i></summary>

<br />

| | |
| :-- | :-- |
| 🏅 **AWS Certified Developer – Associate** (DVA-C02) | Amazon Web Services |
| 📜 **AI Engineer — Core Track** | LLM engineering, RAG, LoRA/QLoRA fine-tuning, evals, observability |
| 📜 **AI Engineer — Agentic Track** | Agentic design patterns, context engineering, MCP, CrewAI, LangGraph |
| 🏆 **AI Fiesta — Certificate of Appreciation** | Apexon — for driving AI adoption across teams |
| 🌟 **Budding Star Award, Q4** | Apexon — for exceptional performance and rapid learning |
| 🎓 **B.Tech, Computer Science & Engineering (AI)** | NCER Pune · 2024 · CGPA 8.28/10 |

</details>

---

## By the numbers

<div align="center">

<!-- Generated by a GitHub Action into this repo, so these never break when a
     third-party rendering service goes down or gets rate limited. -->
<img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="Profile details" width="88%" />

<img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repositories per language" width="44%" />
<img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="Contribution stats" width="44%" />

<img src="https://streak-stats.demolab.com?user=aniketwaghh&theme=github-dark-blue&hide_border=true&border_radius=8&date_format=j%20M%5B%20Y%5D" alt="Contribution streak" width="88%" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake.svg" />
  <img alt="Snake eating my contribution graph" src="https://raw.githubusercontent.com/aniketwaghh/aniketwaghh/output/github-snake.svg" width="92%" />
</picture>

<details>
<summary><i>more charts</i></summary>
<br />
<img src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most committed language" width="44%" />
<img src="./profile-summary-card-output/github_dark/4-productive-time.svg" alt="Most productive time of day" width="44%" />
</details>

</div>

---

<div align="center">

### Let's build something that actually ships

Open to talking **agentic AI platforms**, **LLM infrastructure** and **open-source collaboration**.

<a href="https://www.linkedin.com/in/aniket-s-wagh"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
<a href="mailto:contact.aniketwagh@gmail.com"><img src="https://img.shields.io/badge/Say_hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Say hello by email" /></a>

<sub>Stat cards are generated in-repo by GitHub Actions — no third-party uptime required.</sub>

</div>
