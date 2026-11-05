<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║    BI Engineer @ Tkxel  →  Data & AI Engineer @ Hazen    ║
║         Raw data in. Answers you can trust out.          ║
╚══════════════════════════════════════════════════════════╝
```

<h1>Hey 👋 I'm Faizan Tanveer</h1>

<a href="https://github.com/faizantanveeer">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=6E40C9&center=true&vCenter=true&width=620&lines=Data+Engineer+%C2%B7+AI+Engineer;Pipelines+%E2%86%92+Warehouses+%E2%86%92+LLM+Systems;dbt+%C2%B7+Snowflake+%C2%B7+Databricks+%C2%B7+Airflow;RAG+%C2%B7+Agentic+AI+%C2%B7+MCP" alt="Typing SVG" />
</a>

<p><em>Data & AI Engineer · Data Pipelines · Generative AI · Legal, Health & Insurance Tech · Lahore, Pakistan</em></p>

[![LinkedIn](https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0A66C2&logoColor=white&labelColor=&style=for-the-badge)](https://linkedin.com/in/faizantanveerr)
[![Gmail](https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=EA4335&logoColor=white&labelColor=&style=for-the-badge)](mailto:faizantanveerai@gmail.com)
[![GitHub](https://img.shields.io/static/v1?message=GitHub&logo=github&label=&color=171515&logoColor=white&labelColor=&style=for-the-badge)](https://github.com/faizantanveeer)

</div>

<table>
<tr>
<td width="55%" valign="top">

### `$ whoami`

I'm a Data & AI Engineer from Lahore, and my work sits right where data engineering meets AI.

On the data side, I build pipelines that take messy sources and turn them into warehouse tables people can trust. On the AI side, I build retrieval and agent systems that answer questions from that data and show exactly where each answer came from.

I started out in BI, and that habit stuck: I always think about the person reading the output at the end. One set of dashboards I built gave a team back more than 35 hours a week. A retrieval system I rebuilt became 60% more accurate.

</td>
<td width="45%" valign="top">

### `$ cat now.txt`

```text
▸ Data pipelines and AI quality
  tracking for an insurance
  claims platform

▸ Microsoft Fabric data workloads

▸ FinCite AI: question answering
  over annual reports, with a
  page citation for every answer

▸ SimpLedger: finding lost revenue
  for US trucking carriers
```

</td>
</tr>
</table>

## ⚡ Impact at a Glance

| What changed | Result | What changed | Result |
|:---|:---:|:---|:---:|
| 🕐 Manual reporting removed | **35+ hrs / week** | 🎯 RAG retrieval accuracy | **60%+ better** |
| 📦 Data moved through ETL | **2TB+** | ⚡ Query latency | **35% lower** |
| ⚙️ Data prep time | **40% less** | 🚀 Reporting speed | **30% faster** |
| 📊 KPI accuracy | **25% higher** | 🧪 Automated dbt data tests (ClaimPulse) | **17** |

## 🛠️ Tech Stack

<table>
<tr>
<td width="22%"><b>Data Engineering</b></td>
<td><img src="https://go-skill-icons.vercel.app/api/icons?theme=dark&i=snowflake,databricks,dbtlabs,airflow,bigquery,fabric,s3,postgresql,pandas,selenium" height="44" alt="Data Engineering" /></td>
</tr>
<tr>
<td width="22%"><b>BI & Automation</b></td>
<td><img src="https://go-skill-icons.vercel.app/api/icons?theme=dark&i=pbi,tableau,looker,powerautomate,excel" height="44" alt="BI & Automation" /></td>
</tr>
<tr>
<td width="22%"><b>AI & LLMs</b></td>
<td><img src="https://go-skill-icons.vercel.app/api/icons?theme=dark&i=langchain,huggingface,pytorch,tensorflow,chatgpt,pinecone,qdrant,mcp" height="44" alt="AI & LLMs" /></td>
</tr>
<tr>
<td width="22%"><b>Cloud & Dev</b></td>
<td><img src="https://go-skill-icons.vercel.app/api/icons?theme=dark&i=python,fastapi,flask,react,nextjs,docker,git,azure,aws,gcp,vercel" height="44" alt="Cloud & Dev" /></td>
</tr>
</table>

## 🔬 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🏗️ [ClaimPulse](https://github.com/faizantanveeer/claimpulse)
<sub>`Python` · `S3` · `Snowflake` · `dbt` · `Airflow` · `Docker` · `Looker Studio`</sub>

**Situation:** In PIP insurance, every letter a carrier sends comes with a response deadline. Miss one and a provider can lose the right to get paid.

**Task:** Build a layer that spots claims about to breach a deadline before they turn into denials.

**Action:** Generated deliberately messy synthetic claims data, landed it in S3, loaded it into Snowflake, modeled it in dbt across staging, intermediate and marts, and scheduled the whole run daily with Airflow in Docker.

**Result:** A daily pipeline guarded by 17 automated data tests, feeding a public dashboard.

🔗 [Repo](https://github.com/faizantanveeer/claimpulse) · [Live dashboard](https://datastudio.google.com/reporting/c3ce75b3-dd2b-4a36-8bff-649c4ef0fa98)

</td>
<td width="50%" valign="top">

### 📑 [FinCite AI](https://github.com/faizantanveeer/filinglens-analyst-companion)
<sub>`FastAPI` · `Next.js` · `Qdrant` · `Hybrid RAG` · `Postgres` · `Vercel`</sub>

**Situation:** Annual reports and SEC filings run to hundreds of pages, and general chatbots will happily invent numbers from them.

**Task:** Answer questions about a filing so that every figure can be traced back to its page.

**Action:** Combined dense and keyword search with a reranker, had Python do all the math instead of the LLM, and added a checker that matches every number in an answer against its cited source before showing it.

**Result:** Live on Vercel. When the documents don't support an answer, it says so instead of guessing.

🔗 [Repo](https://github.com/faizantanveeer/filinglens-analyst-companion) · [Live app](https://fincite.vercel.app)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚚 SimpLedger
<sub>`SaaS` · `Solo founder` · `Revenue audit`</sub>

**Situation:** Small US trucking carriers run their billing on paperwork and spreadsheets, and money slips through the gaps without anyone noticing.

**Task:** Find that lost revenue and show carriers exactly where it went.

**Action:** Designed and built SimpLedger on my own as a revenue leak audit tool for carrier billing.

**Result:** Version 1 is live, and I'm now running free Leak Audits with the first carriers.

</td>
<td width="50%" valign="top">

### 🤖 Multi Agent RAG Platform
<sub>`LangChain` · `MCP` · `FAISS` · `Pinecone`</sub>

**Situation:** Legal and health tech teams needed answers from dense documents, and the old static retrieval pipeline was slow and often missed.

**Task:** Make retrieval more accurate and faster without starting from zero.

**Action:** Rebuilt it as an agentic system with MCP support, where agents plan their reasoning step by step and choose the right tool as they go.

**Result:** Retrieval accuracy went up by more than 60% and latency dropped by 35%.

<sub>🔒 Built at work, code is private.</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚖️ Legal AI Intake System
<sub>`Azure Document Intelligence` · `LLMs` · `REST API`</sub>

**Situation:** A law firm's intake team was copying patient details out of medical ledgers by hand.

**Task:** Automate that extraction and feed it straight into case intake.

**Action:** Used Azure Document Intelligence and LLMs to pull structured patient data from the ledgers, served through production REST APIs.

**Result:** The system now runs inside the firm's legal processing pipeline.

<sub>🔒 Built at work, code is private.</sub>

</td>
<td width="50%" valign="top">

### 📱 [InstaSum](https://github.com/faizantanveeer/InstaSum)
<sub>`Flask` · `React` · `Whisper` · `Azure OpenAI` · `Postgres`</sub>

**Situation:** Getting the useful bits out of a creator's reels means sitting through every single video.

**Task:** Turn any public Instagram profile into a library you can search instead of watch.

**Action:** Built three fallback layers for fetching reels, local Whisper transcription, AI summaries, background workers for batch jobs, and Postgres full text search behind a React frontend.

**Result:** Paste a username and get every reel transcribed, summarized, searchable and exportable as JSON or CSV.

🔗 [Repo](https://github.com/faizantanveeer/InstaSum)

</td>
</tr>
</table>

## 📊 GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com?user=faizantanveeer&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" height="165" alt="streak stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=faizantanveeer&theme=dracula" height="165" alt="top languages" />

</div>

### 🐍 Contribution Graph

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/faizantanveeer/faizantanveeer/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/faizantanveeer/faizantanveeer/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/faizantanveeer/faizantanveeer/output/pacman-contribution-graph.svg">
</picture>

</div>

<div align="center">

*"Get the data right first. The smart part gets much easier after that."*

![Profile Views](https://komarev.com/ghpvc/?username=faizantanveeer&style=flat-square&color=6e40c9)

</div>
