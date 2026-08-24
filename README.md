<div align="center">

# Eduard Kharaev

### Applied AI Engineer · Forward-Deployed Engineer · AI Platform Architect

**I build production AI systems end-to-end — from models and GPU inference to business workflows and full-stack products.**

[![Portfolio](https://img.shields.io/badge/AI_Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/swd07/ai-platform-portfolio)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Edharaev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:haraev87@gmail.com)

</div>

---

## What I build

I design, build and operate **production AI systems as the sole technical owner** — computer vision pipelines, LLM agents, GPU inference infrastructure, ERP/business integrations and full-stack AI products.

My focus is not demo-only AI. I care about **measurable production impact, evaluation discipline, observability, safe rollout gates and systems that survive real users and real data**.

<table>
<tr>
<td width="25%" align="center"><b>👁 Computer Vision</b><br/>Detection · OCR · VLM · embeddings</td>
<td width="25%" align="center"><b>🧠 LLM Systems</b><br/>Agents · tools · MCP · RAG</td>
<td width="25%" align="center"><b>⚡ AI Infrastructure</b><br/>H200 · vLLM · self-hosted inference</td>
<td width="25%" align="center"><b>🏗 Product Engineering</b><br/>Backend · data · web · mobile</td>
</tr>
</table>

## Selected impact

| Production result | Impact |
|---|---:|
| AI sales & merchandising platform | **~2,000 retail outlets · 500–700 orders/day** |
| AI-driven order channel | **~60% of orders** |
| Shelf detection on unseen images | **F1 0.68 → 0.91** |
| SKU recognition | **95.8% accuracy** |
| Production agent layer | **20+ typed tools** |
| GPU inference | **NVIDIA H200 · 72B AWQ · 35B FP8** |

## Production AI architecture

```mermaid
flowchart LR
    A[Retail shelf photo] --> B[Object detection]
    B --> C[Product crops]
    C --> D[OCR / Vision-Language Model]
    C --> E[DINOv2 embeddings]
    E --> F[Qdrant / KNN retrieval]
    D --> G[Signal fusion + guardrails]
    F --> G
    G --> H{Enough evidence?}
    H -->|Yes| I[SKU match]
    H -->|No| J[Unknown / abstain]
```

**Engineering principle:** confidence is not correctness. Production AI should be able to **abstain**, be evaluated against real populations, run in shadow before promotion, and roll back cleanly.

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [AI Platform Portfolio](https://github.com/swd07/ai-platform-portfolio)

Sanitized production case studies with architectures, metrics, technical decisions and honest write-ups — including changes that **failed acceptance gates and were not promoted**.

**Includes:**
- Commercial AI operating system for FMCG
- Shelf-recognition CV platform
- Real-time voice assistant
- AIOps monitoring agent
- Social intelligence platform
- Fitness coaching platform

</td>
<td width="50%" valign="top">

### 👁 [Retail Shelf Detection](https://github.com/swd07/retail-shelf-detection)

Public case study and runnable examples for a production computer-vision merchandising pipeline.

**Pipeline:**
- detection + crop extraction
- OCR / VLM text reading
- DINOv2 visual embeddings
- vector retrieval / SKU matching
- guardrails and explicit `Unknown`
- production evaluation methodology

</td>
</tr>
</table>

## AI / ML stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,fastapi,postgres,docker,kubernetes,typescript,nextjs,git,github,linux" alt="Core engineering stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/vLLM-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/Langfuse-000000?style=flat-square" />
  <img src="https://img.shields.io/badge/MCP-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" />
</p>

### Core areas

`Computer Vision` · `OCR` · `Vision-Language Models` · `LLM Agents` · `Tool Calling` · `MCP` · `RAG` · `Vector Search` · `GPU Inference` · `Evaluation` · `Observability` · `Production Architecture`

## How I engineer AI systems

- **Production first** — architecture is shaped by latency, failure modes, cost, observability and operational reality.
- **Evaluation before promotion** — golden-set regression, replay, pre-registered acceptance gates and population-level validation.
- **Safe rollout** — shadow → measure → gate → active, with explicit rollback paths.
- **Deterministic where possible** — LLMs augment systems; they do not replace reliable logic where reliable logic is available.
- **End-to-end ownership** — model layer, backend, data, integrations, frontend, deployment and production operations.

## GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=swd07&show_icons=true&hide_title=true&hide_border=true&theme=github_dark&include_all_commits=true" alt="Eduard's GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=swd07&layout=compact&hide_border=true&theme=github_dark" alt="Top languages" />

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=swd07&theme=github-compact&hide_border=true" alt="GitHub activity graph" />

</div>

---

<div align="center">

### Open to senior Applied AI / Forward-Deployed Engineering and AI Platform Architecture roles

**Production AI · Computer Vision · LLM Systems · AI Infrastructure**

[Portfolio](https://github.com/swd07/ai-platform-portfolio) · [Telegram](https://t.me/Edharaev) · [Email](mailto:haraev87@gmail.com)

</div>
