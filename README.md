<img width="100%" src="https://capsule-render.vercel.app/api?type=slice&color=0:0d1117,100:39FF14&height=200&section=header&text=Ritika%20Muruganandam&fontSize=44&fontColor=ffffff&fontAlign=38&fontAlignY=45&desc=Agentic%20AI%20Engineer%20%7C%20Full%20Stack%20Developer&descAlign=38&descAlignY=62&descSize=17&descColor=0d1117&animation=fadeIn&reversal=false" />

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=3000&pause=1000&color=39FF14&center=true&vCenter=true&repeat=true&width=900&height=45&lines=%24+role%3A+agentic+AI+engineer+%2B+full+stack+developer;%24+stack%3A+crewai+%7C+langchain+%7C+fastapi+%7C+react+%7C+postgres;%24+focus%3A+multi-agent+%7C+RAG+%7C+LLM+tool+use+%7C+full-stack;%24+highlights%3A+LlamaIndex+%7C+3+projects+%7C+2x+national+winner" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ritika-muruganandam/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Ritikadevi/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://ritika.xyz/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://ritika.xyz/#contact">
    <img src="https://img.shields.io/badge/Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<br/>

```yaml
# ═══════════════════════════════════════════════════════════
#  SYSTEM PROMPT — agent/ritika-muruganandam
#  model: full-stack-agentic-v2.0
#  last_deployed: 2025
#  context_window: 3y
#  hallucination_rate: 0.0
# ═══════════════════════════════════════════════════════════

role: Full Stack Developer × Agentic AI Engineer

agent_directive: >
  plan → act → observe → iterate. build the full loop, not just the prompt

skills:
  - agentic: multi-agent orchestration · advanced RAG · LLM tool use · checkpointer · HITL
  - full-stack: react · express.js · node.js · postgreSQL · mongodb · jwt · fastapi

tools: >
  [CrewAI, LangChain, LlamaIndex, ChromaDB, OpenAI, Claude, Gemini, Azure OpenAI, Tavily]

available_functions:
  - build_agent(framework: CrewAI | LangChain, memory: bool, streaming: bool) -> Pipeline
  - query_db(nl_input: str, schema: dict) -> SQL + StreamedResult
  - ship_feature(stack: fullstack, deadline: tight) -> PR

training_data:
  - national hackathons × 2
  - open source contributions (LlamaIndex)
  - shipped products in production

constraints:
  - no isolated demos without real data
  - no prompting without architecture
  - no shipping without understanding the system

open_source: >
  LlamaIndex - OpenAILikeResponses class · Responses API + Chat Completions for
  3rd party provider compatible with OpenAI API (PR #21246 open)

temperature: 0.9  # creative but grounded

structured_output: agentic systems with clear architecture

status: actively building | open to AI, backend, and full-stack roles
```

---

## Four Projects That Represent Me Best


### 1. Multi-Agent Research Engine

Repo: [Architecture & Demo](https://github.com/Ritikamuruganandam06/multi-agent-research-engine-crewai)

<img src="https://img.shields.io/badge/CrewAI-1a1a2e?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Tavily-00B4D8?style=flat-square" />
<img src="https://img.shields.io/badge/litellm-0A0A0A?style=flat-square" />
<img src="https://img.shields.io/badge/SSE-E34F26?style=flat-square" />
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />

A real **four-stage specialist-agent pipeline** built with **CrewAI** - query in, fact-checked cited report out, streamed live.

**Agents:** `Subtopic Generator` → `Web Researcher` → `Summarizer` → `Fact Checker` → `Report Writer`

- Each agent receives the previous agent's output as context and has one job. No shared state, no manager LLM.
- Dedicated fact-checking pass for output reliability over raw generation speed
- Every stage transition, search query, and sub-topic event pushed to the browser live via **SSE** - not polling, not WebSockets
- Supports **Gemini** and **Azure OpenAI** via litellm with a single env switch

**What it signals**

Orchestration over prompting, each agent has a clear role and hands off deliberately.

---

### 2. Query Genie

Repo: [Architecture & Demo](https://github.com/Ritikamuruganandam06/query-genie)

<img src="https://img.shields.io/badge/LangChain-FF6B6B?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/SSE-E34F26?style=flat-square" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Claude_(Anthropic)-D97706?style=flat-square" />
<img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
<img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />

**Not a chatbot. An agent.** Talk to your PostgreSQL database in natural language - it plans, writes SQL, executes it, and streams everything back to the UI live.

- **Schema in the system prompt** - the agent always knows your current schema; DDL changes update it automatically so it never reasons on stale structure
- **Checkpointer-based memory** - conversations persist across sessions; the agent picks up where you left off
- **Multi-LLM via one env var** - OpenAI, Gemini, Claude, Azure OpenAI; same agent, different brain
- **Live tool visibility** - every SQL query and tool call shows up in the UI as it happens; nothing is hidden

**What it signals**

Tools, memory, live database, streaming UI - all wired together, not an isolated demo.

---

### 3. Portfolio + Personal Blog

Visit: [Personal Blog](https://ritika.xyz/blogs)  
Repo: [Architecture & Demo](https://github.com/Ritikamuruganandam06/portfolio-ritika)

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square" />
<img src="https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white" />
<img src="https://img.shields.io/badge/YAML_Frontmatter-CB171E?style=flat-square" />

Not just a portfolio - a **custom blog engine** built from scratch with no CMS, database, or third-party content tools.

- **Custom Vite plugin** reads Markdown files at build time - no runtime fetching or APIs  
- **YAML frontmatter** used for title, tags, date, and reading-time metadata  
- Posts are **lazy-loaded**, each as its own content chunk  
- Includes pagination, navigation, dark/light theme, and custom Markdown rendering  
- Writing flow is simple: add a `.md` file and commit  

**What it signals**

I build what I need instead of relying on existing tools, with full ownership of the system.

---

### 4. Web-Based IoT Dashboard  

Repo: [Architecture & Demo](https://github.com/Ritikamuruganandam06/CDAC-IOT-WEB-DASHBOARD)

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white" />

A real-time **IoT dashboard** that simplifies connecting hardware devices to a web interface, making it easier for beginners to build and monitor IoT projects.

**Core system:** Device data → backend → real-time updates → dashboard

- Real-time updates using **Socket.IO** for low-latency data streaming  
- Simplifies hardware integration through a clean web interface  
- Separate **admin and user dashboards** for monitoring and control  
- **Alert system** for tracking important events and thresholds  
- Includes guided workflows to help users understand and manage their setup

**What it signals**

Ability to build real-time systems and make complex hardware integrations easy to use.

---

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:39FF14&height=50&section=header&text=🔓%20Open%20Source%20Contribution&fontSize=20&fontColor=ffffff&fontAlignY=65&animation=fadeIn" />

### LlamaIndex

`feat: OpenAILikeResponses integration` &nbsp;·&nbsp; [View PR #21246](https://github.com/run-llama/llama_index/pull/21246) &nbsp;·&nbsp; ![open](https://img.shields.io/badge/PR-open-green?style=flat-square)

LlamaIndex's `llama-index-llms-openai-like` package only supported Chat Completions - not OpenAI's newer **Responses API**. I added `OpenAILikeResponses` to close that gap.

- New class `OpenAILikeResponses`- configurable context window, tokenizer, and metadata
- Exported alongside the existing `OpenAILike` with proper package wiring

**Why this matters**

Not a docs fix. It's a real integration - I read an existing codebase, understood the abstraction layer, and shipped something that's actually useful to other developers.

---

## Recent Writing

| Post | Link | Tags | Date |
|------|-----|------|------|
| Most RAG setups quietly give wrong answers on anything beyond simple questions. | [Why Your RAG Pipeline Is Broken](https://ritika.xyz/blogs/why-your-rag-pipeline-is-broken) | `RAG` `Re-Ranker` `Embeddings` | Mar 27 · 8 min |
| When agents add value and when deterministic is the better choice. | [When Not to Use Agentic AI](https://ritika.xyz/blogs/getting-started) | `Agents` `Architecture` `LLM` | Mar 6 · 8 min |

All posts on **[ritika.xyz/blogs](https://ritika.xyz/blogs)**

---

## Engineering Labs

Every repo here was me going - I want to build this myself and see how it actually works.

| Area | Repo | What I built |
|------|------|-------------|
| AI | [AI-Practice](https://github.com/Ritikamuruganandam06/AI-Practice) | RAG pipelines, ChromaDB, agentic retrieval, LLM persistence - Python notebooks |
| OAuth | [OAuth](https://github.com/Ritikamuruganandam06/OAuth) | Google OAuth 2.0 from scratch - token exchange, JWT stored in HttpOnly cookies with credentials enabled, React + Express |
| Backend | [Backend](https://github.com/Ritikamuruganandam06/Backend) | REST APIs, file uploads, Sequelize ORM, relational schema with migrations |
| Auth | [dev-node](https://github.com/Ritikamuruganandam06/dev-node) | JWT auth, route-level middleware, MongoDB + PostgreSQL |
| ORM | [sequelize-orm](https://github.com/Ritikamuruganandam06/sequelize-orm) | Associations, migrations, query patterns - Sequelize deep dive |

---

## Skills

<table>
  <tr>
    <td valign="top"><strong>AI & Agents</strong></td>
    <td>
      <img src="https://img.shields.io/badge/LangChain-FF6B6B?style=flat-square" />
      <img src="https://img.shields.io/badge/CrewAI-1a1a2e?style=flat-square" />
      <img src="https://img.shields.io/badge/LlamaIndex-FF6B35?style=flat-square" />
      <img src="https://img.shields.io/badge/RAG-2E8B57?style=flat-square" />
      <img src="https://img.shields.io/badge/Tool_Use-6C3483?style=flat-square" />
      <img src="https://img.shields.io/badge/SSE_Streaming-E34F26?style=flat-square" />
      <img src="https://img.shields.io/badge/ChromaDB-5B3DF5?style=flat-square" />
      <img src="https://img.shields.io/badge/litellm-0A0A0A?style=flat-square" />
      <img src="https://img.shields.io/badge/Tavily-00B4D8?style=flat-square" />
      <img src="https://img.shields.io/badge/LangSmith-F4A261?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>LLM APIs</strong></td>
    <td>
      <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/Claude_(Anthropic)-D97706?style=flat-square" />
      <img src="https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white" />
      <img src="https://img.shields.io/badge/Azure_OpenAI-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Backend</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=python,fastapi,nodejs,express&theme=dark" />
      <img src="https://img.shields.io/badge/REST_APIs-0F172A?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Frontend</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=react,ts,js,html,css,vite&theme=dark" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Databases</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql&theme=dark" />
      <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white" />
      <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Auth</strong></td>
    <td>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" />
      <img src="https://img.shields.io/badge/Google_OAuth_2.0-4285F4?style=flat-square&logo=google&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Languages</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=python,js,ts,java,c&theme=dark" />
    </td>
  </tr>
  <tr>
    <td valign="top"><strong>Tools</strong></td>
    <td>
      <img src="https://skillicons.dev/icons?i=git,github,figma,postman,vscode&theme=dark" />
      <img src="https://img.shields.io/badge/pgAdmin-336791?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/MySQL_Workbench-4479A1?style=flat-square&logo=mysql&logoColor=white" />
    </td>
  </tr>
</table>

---

## Certifications

| | |
|---|---|
| ![Anthropic](https://img.shields.io/badge/Anthropic-D97706?style=flat-square) | **Building with the Claude API** |
| ![Anthropic](https://img.shields.io/badge/Anthropic-D97706?style=flat-square) | **Introduction to Model Context Protocol (MCP)** |
| ![Google](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=google&logoColor=white) | **Introduction to Generative AI** - Google Cloud Skills Boost |

---

## Achievements

<table>
  <tr>
    <td>🥈</td>
    <td><strong>CDAC – National Urban IoT Challenge (Smart City 2.0)</strong><br/>Runner-Up &nbsp;·&nbsp; Real-Time IoT Dashboard &nbsp;·&nbsp; <strong>₹25,000 cash prize</strong></td>
  </tr>
  <tr>
    <td>🥉</td>
    <td><strong>IntelliMobility Ideathon – ARAI</strong><br/>2nd Runner-Up &nbsp;·&nbsp; Active Safety for Two-Wheelers using Advanced Rider Assistance &nbsp;·&nbsp; <strong>₹10,000 cash prize</strong></td>
  </tr>
  <tr>
    <td>🏅</td>
    <td><strong>Neonexus '25 – Ballari Institute of Technology</strong><br/>Top 5 (5th Place) &nbsp;·&nbsp; Pedestrian Detection System</td>
  </tr>
</table>

---

## GitHub Stats

<div align="center">

**🔥 Contribution Streak**

<img src="https://streak-stats.demolab.com/?user=Ritikamuruganandam06&hide_border=true&background=0D1117&stroke=30363d&ring=e8912d&fire=e8912d&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=e8912d&sideLabels=e8912d&dates=8b949e" alt="Contribution Streak" />

<br/>

**🏆 GitHub Trophies**

<img src="https://github-profile-trophy.vercel.app/?username=Ritikamuruganandam06&theme=onedark&no-frame=false&no-bg=true&margin-w=4&row=2&column=7" alt="GitHub Trophies" />



**📈 Contribution Graph**

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ritikamuruganandam06&bg_color=0d1117&color=e8912d&line=e8912d&point=c9d1d9&area=true&hide_border=true" alt="Contribution Graph" />

</div>

---

<p align="center">
  <a href="https://www.linkedin.com/in/ritika-muruganandam/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Ritikadevi/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" />
  </a>
  <a href="https://ritika.xyz/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="https://ritika.xyz/#contact">
    <img src="https://img.shields.io/badge/Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<p align="center">
  <i>Open to full-stack and AI engineering roles.<br/>Most interested in problems where the AI component actually has to reason.</i>
</p>
