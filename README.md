<p align="center"><strong>English</strong> · <a href="https://github.com/IgorMitrofanov/IgorMitrofanov/blob/main/README.ru.md">Русский</a></p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;height=220&amp;color=0:0b1220,35:12304a,70:1f6f8b,100:38bdf8&amp;text=Igor%20Mitrofanov&amp;fontColor=f8fafc&amp;fontSize=52&amp;fontAlignY=38&amp;desc=Lead%20AI%20Systems%20Engineer&amp;descAlignY=58" alt="Igor Mitrofanov — Lead AI Systems Engineer" width="100%" />
  <p><strong>Agent systems · Knowledge engineering · Applied AI products</strong></p>
  <p>Kazan, Russia · Python &amp; Go · From problem discovery to working systems</p>
  <p>
    <a href="#engineering-focus">Engineering focus</a> ·
    <a href="#selected-work">Selected work</a> ·
    <a href="#toolbox">Toolbox</a> ·
    <a href="#public-code">Public code</a> ·
    <a href="#contact">Contact</a>
  </p>
</div>

## About

I build AI systems that work with real users, technical knowledge, and physical devices. My background is in nuclear physics, data analytics, and industrial R&D. Today, my main focus is **LLM applications, agent architecture, and the backend systems that make them usable and reliable**.

I take responsibility for the full engineering cycle: understanding the problem, designing the solution, building the service and its interfaces, evaluating behavior, deploying, and improving it. Alongside internal engineering projects, I work on commercial AI automation, including process discovery and implementation planning.

## Engineering focus

| Area | What I work on |
| --- | --- |
| **Agent and context engineering** | Conversation state, persistent memory, tool use, diagnostic steps, handling corrections, and keeping user statements separate from retrieved evidence. |
| **RAG and knowledge engineering** | Document ingestion, OCR, structured facts and procedures, source provenance, hybrid dense / lexical retrieval, reranking, and multilingual knowledge. |
| **Reliable AI backends** | Go and Python services, durable inputs, idempotent requests, transactional state updates, background processing, and recoverable event streams. |
| **Evaluation and observability** | Multi-turn scenarios, regression replay, version comparisons, execution traces, latency analysis, and tracing failures back to retrieval, context, or generation. |
| **Product delivery** | APIs, web interfaces, operator tools, multimodal input, integration contracts, technical documentation, and deployment workflows. |
| **Applied perception** | Computer vision, point clouds, geometric reconstruction, AR measurement, sensor data, and industrial analytics. |

## Selected work

Most of my current engineering work is in private repositories. These summaries describe the projects and my work on them; prototypes and ongoing development are marked explicitly.

### AI technical support

An assistant for industrial equipment support, with technical knowledge retrieval and conversation continuity across multiple turns. My work spans a Python implementation and an evolving Go backend: tracking diagnostic steps, retaining confirmed context, grounding answers in sources, handling text, images and speech, and handing cases over to human support.

The engineering work includes request persistence, recovery after reconnects, multilingual knowledge, answer checks, and evaluation against realistic support conversations.

### Technical knowledge pipelines

Turning multilingual documentation into a usable knowledge base: text, tables, illustrations, OCR, product facts, and step-by-step procedures. I work on reproducible extraction, stable identifiers, source revisions, quality checks, and retrieval that respects which product and situation a source actually describes.

### Document automation

A web application for generating documents from versioned templates and structured data, with dynamic forms and LLM-assisted autofill. The work also covers versioned product documentation and QR-linked publishing, using a Python backend and a React / TypeScript interface.

### AR tank measurement — in development

An Android prototype for reconstructing tank geometry and generating level-to-volume calibration tables from camera and depth observations. Work includes ARCore, point-cloud fusion, segmentation, robust geometric fitting, scan recovery, and recorded-session replay for regression checks.

### Coding-agent runtime — R&D prototype

A supervised agent runtime in Go, exploring typed tools, execution policies, persistent memory, repository inspection, approval and rollback workflows, and execution traces. This work informs how I use coding agents: explicit tasks, reviewable changes, and verification against actual behavior.

<details>
<summary><strong>Earlier work and broader experience</strong></summary>

- Interview and meeting analysis: recording upload, transcription, LLM analysis, reports, and history.
- Computer vision: industrial object detection, depth estimation, 3D reconstruction, and volume estimation.
- Industrial data: weather-station validation, telemetry analysis, sensor calibration, and data quality checks.
- Automation products: stateful Telegram bots, internal tools, APIs, and deployment workflows.

</details>

## How I approach engineering

- **Treat state as part of the product.** A conversation, a scan, or a document workflow must preserve progress and recover from interruptions.
- **Keep evidence traceable.** Preserve where information came from, what it applies to, and whether it is an observation, an inference, or a decision.
- **Evaluate complete workflows.** Inspect actual conversations, tool outcomes, and failure cases alongside quality, latency, and cost.
- **Make changes reviewable.** Use clear interfaces, reproducible scenarios, useful traces, and documented release decisions.
- **Keep complexity justified.** Add components when they solve an observed problem; simplify when they make the system harder to understand and operate.

## Toolbox

| Layer | Tools I use across projects |
| --- | --- |
| **Backend** | Python, Go, FastAPI, SQL |
| **LLM systems and retrieval** | LLM APIs, tool calling, structured outputs, LangGraph, Qdrant, embeddings, BM25, reranking |
| **Data and state** | PostgreSQL, Redis, SQLite, pandas |
| **Web and mobile** | TypeScript, React, Vite, Kotlin, Jetpack Compose, ARCore |
| **Vision and geometry** | OpenCV, PyTorch, YOLO, Open3D, point-cloud processing |
| **Delivery and operations** | Linux, Docker, GitHub Actions, tracing, regression and load testing |

## Public code

- [Meteorological verification data](https://github.com/IgorMitrofanov/global-meteostation-verefication-data) — an earlier Python project for collecting and analyzing weather-station verification records, with a dashboard.
- [Self-hosted automation setup](https://github.com/IgorMitrofanov/n8n-install-outline) — my fork of [kossakovsky/selfhost-ai](https://github.com/kossakovsky/selfhost-ai), a Docker Compose setup for self-hosted AI and automation tools.

## Contact

For applied AI systems, backend engineering, and business automation: [Telegram](https://t.me/igor_mtrfnv) · [Email](mailto:i.v.mitrofanov@ya.ru).

<details>
<summary>Contribution activity</summary>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/IgorMitrofanov/IgorMitrofanov/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/IgorMitrofanov/IgorMitrofanov/output/github-contribution-grid-snake.svg" />
    <img alt="GitHub contribution activity" src="https://raw.githubusercontent.com/IgorMitrofanov/IgorMitrofanov/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

</details>

---

**Build useful systems. Keep the evidence. Make the behavior understandable.**
