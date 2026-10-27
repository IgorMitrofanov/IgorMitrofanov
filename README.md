<p align="center"><strong>English</strong> · <a href="https://github.com/IgorMitrofanov/IgorMitrofanov/blob/main/README.ru.md">Русский</a></p>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&amp;height=220&amp;color=0:0b1220,35:12304a,70:1f6f8b,100:38bdf8&amp;text=Igor%20Mitrofanov&amp;fontColor=f8fafc&amp;fontSize=52&amp;fontAlignY=38&amp;desc=Lead%20AI%20Systems%20Engineer&amp;descAlignY=58" alt="Igor Mitrofanov — Lead AI Systems Engineer" width="100%" />
  <p><strong>Agent systems · Knowledge engineering · Applied AI products</strong></p>
  <p>Kazan, Russia · Python &amp; Go · From problem discovery to working systems</p>
  <p>
    <a href="#engineering-focus">Engineering focus</a> ·
    <a href="#selected-work">Selected work</a> ·
    <a href="#toolbox">Toolbox</a> ·
    <a href="#contact">Contact</a>
  </p>
</div>

## About

I build AI systems that work with real users, technical knowledge, and physical devices. I work as Lead AI Systems Engineer at Techautomatics LLC. Today, my main focus is **LLM applications, agent architecture, and the backend systems that make them usable and reliable**.

I take responsibility for the full engineering cycle: understanding the problem, designing the solution, building the service and its interfaces, evaluating behavior, deploying, and improving it. Alongside internal engineering projects, I work on commercial AI automation, including process discovery and implementation planning.

I founded **dev-decisions**, an independent engineering practice for applied AI and business automation. I run the business while remaining hands-on in development: finding clients, clarifying requirements, estimating scope and cost, agreeing commercial terms, and managing delivery. I also design the architecture and write the code.

For specific tasks, I bring in developers from my pool of collaborators and have also worked with UI/UX designers. I define tasks, coordinate their work and review the results.

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

### Industrial programming stations

Software for tabletop and gantry stations that automate in-circuit microcontroller programming. My work covers the operator interface, device communication, programming and diagnostics workflows. This combines Python application development with industrial hardware integration.

### Device management and telemetry

Backend services for managing devices, users and telemetry: REST APIs, authorization, data collection, event logging and Telegram notifications. The stack includes FastAPI, SQLAlchemy, asyncio, PostgreSQL and Docker.

### Inspection-robot video system

Multi-camera video streaming and recording software with an operator interface. I worked on concurrent video processing and stream control using Python, GStreamer, OpenCV and PyQt.

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
- Desktop engineering tools: device configuration, serial communication, measurement plots and packaging applications for operators.
- Data science: exploratory analysis and classical ML experiments, including a public customer-churn study project.
- Engineering calculations: Excel and VBA tools for numerical calculations and processing experimental data.
- Automation products: stateful Telegram bots, internal tools, APIs, and deployment workflows.

</details>

## How I approach engineering

- **Treat state as part of the product.** A conversation, a scan, or a document workflow must preserve progress and recover from interruptions.
- **Keep evidence traceable.** Preserve where information came from, what it applies to, and whether it is an observation, an inference, or a decision.
- **Evaluate complete workflows.** Inspect actual conversations, tool outcomes, and failure cases alongside quality, latency, and cost.
- **Make changes reviewable.** Use clear interfaces, reproducible scenarios, useful traces, and documented release decisions.
- **Keep complexity justified.** Add components when they solve an observed problem; simplify when they make the system harder to understand and operate.

## Toolbox

| Area | Tools and methods used across projects |
| --- | --- |
| **Backend and APIs** | Python, Go, FastAPI, SQLAlchemy, asyncio, REST APIs |
| **LLM applications** | LLM APIs, tool calling, structured outputs, LangGraph, Whisper |
| **Search and knowledge** | Qdrant, pgvector, embeddings, BM25, hybrid retrieval, reranking, OCR |
| **Databases and application state** | PostgreSQL, Supabase, Redis, SQLite |
| **Data analysis and statistics** | pandas, NumPy, statsmodels, exploratory analysis, calibration |
| **Classical ML — study and experimental work** | scikit-learn, CatBoost, logistic regression, random forests, cross-validation |
| **Dashboards and plots** | Dash, Plotly, Matplotlib, seaborn |
| **Workflow automation** | n8n, Telegram bots, API integrations |
| **Web interfaces** | TypeScript, React, Vite |
| **Android and AR** | Kotlin, Jetpack Compose, ARCore |
| **Desktop applications** | PyQt, Tkinter, ttkbootstrap, PySimpleGUI, PyInstaller |
| **Vision, geometry and video** | OpenCV, PyTorch, YOLO, Open3D, GStreamer, concurrent video processing |
| **Hardware integration** | C, pySerial, Modbus, RS-485, device programming and diagnostics |
| **Engineering calculations** | Excel, VBA, numerical calculations, approximation methods |
| **Delivery and verification** | Linux, Docker, GitHub Actions, tracing, regression and load testing |

The list covers tools used across professional, personal and study projects. It does not imply equal depth in every tool or production deployment of every method.

## Scientific work

I worked as a reactor physicist at the Research Institute of Atomic Reactors (RIAR). I took part in the modernization of the SM-3 research reactor in 2020, developed methods for calculating its neutronic characteristics, and led experiments.

I hold licenses authorizing work in the field of nuclear energy as a reactor physicist, valid until July 2027. I have co-authored scientific publications.

[Author profile and publications on eLIBRARY](https://www.elibrary.ru/author_profile.asp?authorid=1087867).

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

