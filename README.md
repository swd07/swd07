<div align="center">

<img src="./assets/profile-hero.svg" width="100%" alt="Eduard Kharaev — Applied AI Engineer and AI Platform Architect" />

<br/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=Production+AI+%E2%80%A2+Computer+Vision+%E2%80%A2+LLM+Agents+%E2%80%A2+GPU+Inference;Building+systems+that+survive+real+users+and+real+data;From+prototype+to+production+with+measurable+impact" alt="Typing SVG" /></a>

<br/>

[![Portfolio](https://img.shields.io/badge/AI_PORTFOLIO-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Telegram](https://img.shields.io/badge/TELEGRAM-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Edharaev)
[![Email](https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:haraev87@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=swd07&label=PROFILE+VIEWS&color=238636&style=for-the-badge)

</div>

---

## ⚡ Production AI, end to end

I design, build and operate **production AI systems as the sole technical owner** — from computer-vision models and GPU inference to LLM agents, business integrations, backend/data layers and product interfaces.

My bias is toward **measurable impact, honest evaluation and systems that stay reliable after the demo is over**.

<table>
<tr>
<td width="25%" align="center">
<h2>~2,000</h2>
<b>Retail outlets</b><br/>
<sub>connected to the AI sales platform</sub>
</td>
<td width="25%" align="center">
<h2>500–700</h2>
<b>Orders / day</b><br/>
<sub>through production workflows</sub>
</td>
<td width="25%" align="center">
<h2>0.68 → 0.91</h2>
<b>Detection F1</b><br/>
<sub>on unseen shelf images</sub>
</td>
<td width="25%" align="center">
<h2>95.8%</h2>
<b>SKU recognition</b><br/>
<sub>production recognition accuracy</sub>
</td>
</tr>
</table>

<table>
<tr>
<td width="25%" align="center"><b>🧠 20+ typed tools</b><br/><sub>production agent layer</sub></td>
<td width="25%" align="center"><b>⚡ NVIDIA H200</b><br/><sub>self-hosted AI inference</sub></td>
<td width="25%" align="center"><b>🤖 72B AWQ / 35B FP8</b><br/><sub>served with vLLM</sub></td>
<td width="25%" align="center"><b>📈 ~60% AI channel</b><br/><sub>share of production orders</sub></td>
</tr>
</table>

## 👁 What production looks like

<div align="center">
<a href="https://github.com/swd07/ai-platform-portfolio/blob/master/projects/shelf-detection.md">
<img src="https://raw.githubusercontent.com/swd07/ai-platform-portfolio/master/assets/shelf-detection-live.jpg" width="92%" alt="Live retail shelf detection output" />
</a>

<sub>Real shelf photo through the production CV pipeline — detections, SKU labels, price-tag reads and explicit <code>Unknown</code> when evidence is insufficient.</sub>
</div>

## 🧩 One system, not isolated models

```mermaid
flowchart LR
    A[Retail shelf photo] --> B[Object detection]
    B --> C[Product crops]
    C --> D[OCR / VLM]
    C --> E[DINOv2 embeddings]
    E --> F[Qdrant / KNN retrieval]
    D --> G[Signal fusion + guardrails]
    F --> G
    G --> H{Enough evidence?}
    H -->|Yes| I[SKU match]
    H -->|No| J[Unknown / abstain]
```

> **Production principle:** confidence is not correctness. A real AI system should be able to **abstain**, run in shadow before promotion, be evaluated on real populations and roll back cleanly.

## 🚀 Featured engineering

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [AI Platform Portfolio →](https://github.com/swd07/ai-platform-portfolio)

Production case studies with **architecture, metrics, engineering decisions and evaluation methodology** — sanitized for public access.

`Computer Vision` `LLM Agents` `Voice AI` `AIOps` `Full-stack AI`

**Inside:**
- FMCG commercial AI operating system
- retail shelf-recognition platform
- real-time voice assistant
- infrastructure monitoring agent
- social-media intelligence
- coaching / fitness platform

</td>
<td width="50%" valign="top">

### 👁 [Retail Shelf Detection →](https://github.com/swd07/retail-shelf-detection)

Public case study and runnable examples for a **production computer-vision merchandising pipeline**.

`Detection` `OCR` `VLM` `DINOv2` `Qdrant` `Guardrails`

**Pipeline:**
- object detection + crop extraction
- OCR / vision-language text reading
- visual embeddings + vector retrieval
- SKU fusion / disambiguation
- explicit `Unknown` instead of confident errors
- production evaluation and rollout gates

</td>
</tr>
</table>

<div align="center">

<a href="https://github.com/swd07/ai-platform-portfolio">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=swd07&repo=ai-platform-portfolio&theme=github_dark&hide_border=true" width="47%" alt="AI Platform Portfolio" />
</a>
<a href="https://github.com/swd07/retail-shelf-detection">
<img src="https://github-readme-stats.vercel.app/api/pin/?username=swd07&repo=retail-shelf-detection&theme=github_dark&hide_border=true" width="47%" alt="Retail Shelf Detection" />
</a>

</div>

## 🛠 AI / ML stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,postgres,docker,kubernetes,typescript,nextjs,redis,git,github,linux" alt="Core engineering stack" />

<br/><br/>

![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-111111?style=flat-square)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Langfuse](https://img.shields.io/badge/Langfuse-111111?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-111111?style=flat-square)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

`Computer Vision` · `OCR` · `Vision-Language Models` · `LLM Agents` · `Tool Calling` · `MCP` · `RAG` · `Vector Search` · `GPU Inference` · `Evaluation` · `Observability`

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

## 📊 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=swd07&show_icons=true&hide_title=true&hide_border=true&theme=github_dark&include_all_commits=true" alt="Eduard's GitHub stats" />
<img height="165" src="https://streak-stats.demolab.com?user=swd07&theme=github-dark-blue&hide_border=true" alt="GitHub streak" />

<br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=swd07&theme=github-compact&hide_border=true&area=true" alt="GitHub activity graph" />

</div>

---

<div align="center">

### Building AI systems that actually reach production.

**Applied AI · Computer Vision · LLM Systems · AI Infrastructure · Product Engineering**

<br/>

[![Portfolio](https://img.shields.io/badge/EXPLORE_THE_PORTFOLIO-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Telegram](https://img.shields.io/badge/LET'S_TALK-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Edharaev)

</div>
