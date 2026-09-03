<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Eduard Kharaev — Applied AI Engineer and AI Solutions Architect" />

<br/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=Production+Retrieval+%E2%80%A2+Computer+Vision+%E2%80%A2+LLM+Agents+%E2%80%A2+GPU+Inference;Building+AI+systems+that+survive+real+users+and+real+data;From+prototype+to+production+with+measurable+evaluation" alt="Typing SVG" /></a>

<br/>

[![Portfolio](https://img.shields.io/badge/AI_PORTFOLIO-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Telegram](https://img.shields.io/badge/TELEGRAM-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Edharaev)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:haraev87@gmail.com)

<br/>

![Remote](https://img.shields.io/badge/REMOTE-OPEN-238636?style=for-the-badge)
![Contract](https://img.shields.io/badge/CONTRACT-AVAILABLE-1F6FEB?style=for-the-badge)
![Relocation](https://img.shields.io/badge/RELOCATION-OPEN-8957E5?style=for-the-badge)

<br/>

<sub><b>Open to Senior Applied AI · Forward-Deployed Engineering · AI Solutions Architecture roles</b></sub>

<br/><br/>

**[Production](#-production-ai-end-to-end) · [Live system](#-what-production-looks-like) · [Engineering](#-featured-engineering) · [Stack](#-ai--ml-stack) · [Principles](#-engineering-dna) · [Repositories](#-repositories--recent-work)**

</div>

---

## ⚡ Production AI, end to end

I design, build and operate **production AI systems with end-to-end technical ownership** — from computer-vision models and GPU inference to LLM agents, business integrations, backend/data layers and product interfaces.

My bias is toward **measurable impact, honest evaluation and systems that stay reliable after the demo is over**.

<table>
<tr>
<td width="25%" align="center">
<h2>~3,800</h2>
<b>Retail outlets</b><br/>
<sub>~1,500 active monthly</sub>
</td>
<td width="25%" align="center">
<h2>9–11k</h2>
<b>Orders / month</b><br/>
<sub>98% via platform</sub>
</td>
<td width="25%" align="center">
<h2>0.91</h2>
<b>Detection F1</b><br/>
<sub>on unseen shelf images</sub>
</td>
<td width="25%" align="center">
<h2>95.8%</h2>
<b>Brand precision</b><br/>
<sub>confirmed end-to-end evaluation</sub>
</td>
</tr>
</table>

<table>
<tr>
<td width="25%" align="center"><b>🧠 20+ typed tools</b><br/><sub>production agent layer</sub></td>
<td width="25%" align="center"><b>⚡ NVIDIA H200</b><br/><sub>self-hosted AI inference</sub></td>
<td width="25%" align="center"><b>🤖 Self-hosted Qwen</b><br/><sub>Qwen2.5-VL 72B · Qwen3.6 35B<br/>served with vLLM</sub></td>
<td width="25%" align="center"><b>🎯 73.1% SKU precision</b><br/><sub>end-to-end retrieval + fusion</sub></td>
</tr>
</table>

> 🔒 **Most production code is private** because it runs inside commercial systems with proprietary data and business integrations. The public repositories below contain **sanitized case studies, architecture, metrics, evaluation methodology and runnable examples**.

## 👁 What production looks like

<div align="center">
<a href="https://github.com/swd07/retail-shelf-detection">
<img src="https://raw.githubusercontent.com/swd07/ai-platform-portfolio/master/assets/shelf-detection-live.jpg" width="92%" alt="Live retail shelf detection output" />
</a>

<sub>Real shelf photo through the production CV pipeline — detections, SKU labels, price-tag reads and explicit <code>Unknown</code> when evidence is insufficient.</sub>
</div>

## 🧩 One system, not isolated models

```mermaid
flowchart LR
    A[Retail shelf photo] --> B[GroundingDINO detection]
    B --> C[Product crops]
    C --> D[Qwen2.5-VL OCR / package evidence]
    D --> E[Qwen3-Embedding-8B]
    E --> F[Qdrant dense retrieval]
    C --> G[DINOv2 visual k-NN]
    C --> H[ArcFace metric retrieval]
    F --> I[Deterministic fusion + guardrails]
    G --> I
    H --> I
    D --> I
    I --> J{Enough evidence?}
    J -->|Yes| K[SKU / brand match]
    J -->|No| L[Unknown / abstain]
```

> **Production principle:** confidence is not correctness. A real AI system should be able to **abstain**, run in shadow before promotion, be evaluated on real populations and roll back cleanly.

## 🚀 Featured engineering

<table>
<tr>
<td width="33%" valign="top">

### 🧠 [AI Platform Portfolio →](https://github.com/swd07/ai-platform-portfolio)

Production case studies with **architecture, metrics, engineering decisions and evaluation methodology**.

`AI Platform` `Agents` `Architecture` `Voice AI` `Product Engineering`

**Includes:**
- FMCG commercial operating platform
- AI infrastructure control plane & security operations
- voice-first multi-agent orchestrator
- coaching / fitness product

</td>
<td width="33%" valign="top">

### 👁 [Retail Shelf Detection →](https://github.com/swd07/retail-shelf-detection)

Production-engineered **retrieval + computer-vision merchandising pipeline** with explicit uncertainty.

`Detection` `OCR` `VLM` `Qdrant` `DINOv2` `ArcFace`

**Evidence:**
- 95.8% brand precision
- 73.1% SKU precision
- 47k-box replay harness
- shadow → active rollout gates

</td>
<td width="33%" valign="top">

### 🤖 [Jarvis Agent Orchestrator →](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/jarvis.md)

Voice-first **executive and operations command center** that delegates bounded work across specialized agents and returns grounded results.

`WebRTC` `Agent Registry` `Command Queues` `Tool Calling` `Executive AI`

**Capabilities:**
- live agent heartbeat / task / queue state
- allowlisted agent-command dispatch
- project risks, deadlines & blockers
- safe voice-opened dashboards

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📈 [AI Marketing & Brand Growth →](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/marketing-platform.md)

Multi-source **marketing intelligence platform** connecting social, website, search and campaign analytics.

`Instagram API` `Search` `Traffic` `Content Intelligence` `AI Reporting`

**Measured window:**
- +2,859 Instagram followers
- +88% website visits
- 17.6% Google Search CTR
- 2.4 average search position

</td>
<td width="50%" valign="top">

### 🛡 [AI Infrastructure Control Plane →](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/infra-monitoring-agent.md)

Self-hosted **operations and security layer for production AI infrastructure** with deterministic detection and AI-assisted investigation.

`AIOps` `Security` `H200 Observability` `Qwen` `Tool Calling` `Incident Response`

**Production evidence:**
- 15+ detector types
- ~22 monitored endpoints
- 60-second autonomous watch loop
- 152 alerts recorded in Aug 2026

</td>
</tr>
</table>

## 🛠 AI / ML stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,postgres,docker,typescript,nextjs,redis,git,github,linux" alt="Core engineering stack" />

<br/><br/>

![Qwen](https://img.shields.io/badge/Qwen-self--hosted-6C5CE7?style=flat-square)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-111111?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-111111?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

`Computer Vision` · `OCR` · `Vision-Language Models` · `Dense Retrieval` · `Retrieval-Augmented Systems` · `Vector Search` · `LLM Agents` · `Multi-Agent Orchestration` · `Tool Calling` · `MCP` · `GPU Inference` · `Evaluation` · `Observability` · `Marketing Intelligence`

</div>

## 🧬 Engineering DNA

<table>
<tr>
<td width="25%" valign="top"><b>🎯 Evaluate first</b><br/><br/><sub>Golden-set regression, replay, acceptance gates and population-level validation before promotion.</sub></td>
<td width="25%" valign="top"><b>🛡 Safe rollout</b><br/><br/><sub>Shadow → measure → gate → active, with explicit rollback paths.</sub></td>
<td width="25%" valign="top"><b>⚙️ Deterministic where possible</b><br/><br/><sub>LLMs augment reliable systems; they do not replace reliable logic without reason.</sub></td>
<td width="25%" valign="top"><b>🏗 End-to-end ownership</b><br/><br/><sub>Model layer, backend, data, integrations, frontend, deployment and operations.</sub></td>
</tr>
</table>

## 📦 Repositories & recent work

<div align="center">

[![AI Platform Portfolio](https://img.shields.io/badge/AI_PLATFORM_PORTFOLIO-Production_Case_Studies-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Retail Shelf Detection](https://img.shields.io/badge/RETAIL_SHELF_DETECTION-Retrieval_%2B_CV-1F6FEB?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/retail-shelf-detection)
[![Jarvis](https://img.shields.io/badge/JARVIS-Agent_Orchestrator-0A84FF?style=for-the-badge)](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/jarvis.md)
[![Marketing Platform](https://img.shields.io/badge/MARKETING_INTELLIGENCE-Brand_Growth-8957E5?style=for-the-badge)](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/marketing-platform.md)
[![AI Infra Control Plane](https://img.shields.io/badge/AI_INFRA_CONTROL_PLANE-Security_%26_AIOps-E6522C?style=for-the-badge)](https://github.com/swd07/ai-platform-portfolio/blob/master/projects/infra-monitoring-agent.md)

<br/><br/>

[![GitHub Profile](https://img.shields.io/badge/GITHUB-swd07-238636?style=flat-square&logo=github&logoColor=white)](https://github.com/swd07)
[![Portfolio](https://img.shields.io/badge/CASE_STUDIES-Architecture_%C2%B7_Metrics_%C2%B7_Evaluation-8957E5?style=flat-square)](https://github.com/swd07/ai-platform-portfolio)

</div>

---

<div align="center">

### Building AI systems that actually reach production.

**Applied AI · Production Retrieval · Computer Vision · LLM Systems · Multi-Agent Orchestration · AI Infrastructure · Growth Systems · Product Engineering**

<br/>

[![Portfolio](https://img.shields.io/badge/EXPLORE_THE_PORTFOLIO-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Telegram](https://img.shields.io/badge/LET'S_TALK-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Edharaev)

</div>