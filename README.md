<h1 align="center">Daniel Alejandro Coll Tejeda</h1>
<h4 align="center">Software Engineer · AI Products · Cloud & Distributed Systems</h4>
<p align="center">Building useful products. Making complex systems easier to use. Contributing upstream.</p>

<p align="center">
  <a href="https://macarronesc.github.io"><img alt="Explore my portfolio" src="https://img.shields.io/badge/Portfolio-181717?style=flat-square&logo=github&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/macarronesc/"><img alt="Connect on LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:alegandro2507@gmail.com"><img alt="Email Daniel" src="https://img.shields.io/badge/Let%27s_talk-0078D4?style=flat-square&logo=maildotru&logoColor=white" /></a>
</p>

<p align="center">
  <strong>Software Engineer at HP Barcelona</strong><br/>
  3DaaS — 3D Printers as a Service · Since June 2026
</p>

---

I build AI products, cloud platforms and open-source tools. My background spans cloud research at **Cloudlab (URV)**, serverless computing on **MareNostrum 5**, and applied AI. Today, my main personal projects are **Klipso** and **Invade.io**, which I continue to develop alongside my professional work.

**MSc in AI & Cybersecurity** · Speaker at **PyConES & EuroSciPy** · IEEE-published research · Barcelona 🇪🇸

## ✨ Featured Projects

### 🎬 [Klipso](https://klipso.dev) — AI-Powered Video Editing

AI-powered video editing for **TikTok, Instagram Reels and YouTube Shorts**. I built and continue to improve the full-stack product: highlight selection, speaker-aware reframing, captioned GPU rendering, a creator dashboard, credits and Stripe billing.

| Users | Clips generated | Video generated |
| :---: | :---: | :---: |
| **100+** | **1,000+** | **14+ hours** |

*Product milestones · October 2026.*

**The pipeline:** Captions / Whisper → Gemini highlights → Speaker-aware framing → FFmpeg → Download

Recent engineering work:
- **4 → 1 encoder passes per clip**, combining crop, upscale, subtitles and outro.
- **188.8 → 25.1 seconds** for worker dependency installation in the documented T4 comparison.
- **548.4 → 276.6 seconds** of worker elapsed time in a same-video, captions-enabled comparison; not a guaranteed total wait time.
- Recoverable job processing, idempotent status updates, automatic failure refunds and refresh-safe tracking.

`React` `TypeScript` `Python` `Whisper` `Gemini` `MediaPipe` `FFmpeg` `Firebase` `Cloudflare R2` `Stripe`

---

### 🎮 [Invade.io](https://github.com/macarronesc/invade.io) — Mobile Strategy & Conquest

[Google Play](https://play.google.com/store/apps/details?id=macarronesc.invadeio) · [Source code](https://github.com/macarronesc/invade.io)

A **mobile-first territorial strategy game** built with **Godot 4**. Capture bases, move troops and upgrade your army across a **30-level campaign**, with continent-specific rules, bosses, daily challenges and free-conquest expeditions.

I develop the gameplay, progression systems and mobile experience, including local save recovery, accessibility settings and Android/iOS build workflows. **Actively in development**; cloud saves and online leaderboards are not part of the current public version.

`Godot 4` `GDScript` `Mobile` `Real-time strategy` `Game systems`

---

## 🔬 Research & Cloud Platforms

### 🧠 LiteRAG — Algorithmic Graph Retrieval

📄 [LiteRAG: Cost-Efficient Graph-Based Retrieval-Augmented Generation — arXiv](https://arxiv.org/abs/2609.10239)

I designed and implemented a GraphRAG framework that replaces LLM-guided graph navigation with algorithms, exploring lower-cost, multi-hop retrieval.

**Reported benchmark:** 1.42s vs 142.04s on a 1,280-document corpus. **Paper submitted to EMNLP 2026.**

LiteRAG's navigation avoids LLM calls; answer generation and evaluation may still use models. Benchmark figures describe the evaluated setup, not a universal complexity or performance guarantee.

`Python` `PyTorch` `Neo4j` `NetworkX` `Sentence-Transformers`

### 🚀 [PyRun Cloud](https://pyrun.cloud/) — AI-Assisted Cloud Workspace

I led end-to-end development of a platform that helps researchers run distributed Python workloads on **AWS and IBM Cloud**: web workspace, automated runtime builds, cloud orchestration, execution dashboards and AI-assisted operations.

`React` `TypeScript` `Python` `AWS` `IBM Code Engine` `Docker` `MCP`

### ⚙️ [Lithops](https://lithops-cloud.github.io/) — Multi-Cloud & HPC Computing

[Website](https://lithops-cloud.github.io/) · [GitHub](https://github.com/lithops-cloud/lithops)

Open-source Python framework for parallel execution across cloud and HPC environments. My contributions include **Kubernetes/RabbitMQ work queues**, the **Singularity HPC backend** and execution reliability fixes, including work on **MareNostrum 5**.

📄 [Enhancing HPC with Serverless Computing: Lithops on MareNostrum5 — IEEE ICNP 2024](https://doi.org/10.1109/ICNP61940.2024.10858564)

`Python` `Kubernetes` `Singularity` `RabbitMQ` `AWS` `Dask`

### 🔊 [Soundless](https://github.com/Soundless-URV) — Citizen Science, Noise & Sleep

I led development across the **Android app, Fitbit integration, cloud ingestion and analysis workflow**, creating research infrastructure to study associations between environmental noise and sleep.

`Kotlin` `Fitbit API` `Firebase` `GCP` `BigQuery` `Python`

### 🏎️ F1 Oracle — Race-Ranking Research

I built an **LSTM-based race-ranking pipeline** with lap-by-lap feature engineering and FastF1 integration, exploring how race sequences can inform predictions.

`Python` `TensorFlow` `FastF1` `Pandas`

---

## 🛠️ More Public Projects

| Project | What it does |
| :--- | :--- |
| **[MedGround](https://github.com/macarronesc/MedGround)** | Medical-document RAG prototype with cited answers, hybrid retrieval and LLM-as-a-judge evaluation. Built for document exploration, not clinical decision-making. |
| **[Research to AI Video](https://github.com/macarronesc/research-to-ai-video)** | Prepares manually created NotebookLM videos for YouTube with Gemini-drafted metadata, human review and approved API uploads. |
| **[Spotify to Apple Music](https://github.com/macarronesc/Spotify_to_AppleMusic)** | Transfers playlists from Spotify to Apple Music with track matching, GitHub Actions and Telegram notifications. Builds on earlier open-source work credited in the repository. |

---

## 🐙 Open Source Contributions

Specific changes, not just forked repositories:

| Project | Contribution | Status |
| :--- | :--- | :--- |
| **Lithops** | [Kubernetes/RabbitMQ backend](https://github.com/lithops-cloud/lithops/pull/1170) · [Singularity backend](https://github.com/lithops-cloud/lithops/pull/1375) | Merged |
| **Dask CloudProvider** | [IBM Cloud support](https://github.com/dask/dask-cloudprovider/pull/434) · [Registry support and custom commands](https://github.com/dask/dask-cloudprovider/pull/450) | Merged |
| **Ollama** | [WebP image support in the desktop app](https://github.com/ollama/ollama/pull/12973) | Merged |
| **Gemini CLI** | [Fix `URL.parse` compatibility on Node.js <22](https://github.com/google-gemini/gemini-cli/pull/13698) | Merged |
| **GitHub MCP Server** | [Strict validation of unknown toolsets](https://github.com/github/github-mcp-server/pull/2184) | Open proposal |
| **Rechunker** | [Lithops executor](https://github.com/pangeo-data/rechunker/pull/152) | Open proposal |

*Contribution status checked in October 2026. Linked PRs remain the source of truth.*

---

## 🎤 Talks & Knowledge Sharing

- **[PyConES 2025 · Sevilla](https://pretalx.com/pycones-2025/speaker/TVZK37/)** — Multi-Cloud Serverless Parallel Programming in Python (Lithops).
- **[EuroSciPy 2025 · Kraków](https://pretalx.com/euroscipy-2025/speaker/TVZK37/)** — Processing Cloud-Optimized Data in Python (Dataplug).

<details>
<summary><strong>💻 Technologies & Engineering Toolkit</strong></summary>

| Area | Technologies used across my projects |
| :--- | :--- |
| **AI & retrieval** | PyTorch · TensorFlow · Gemini · Whisper · MediaPipe · ChromaDB · Neo4j · NetworkX |
| **Cloud & systems** | AWS · GCP · IBM Cloud · Kubernetes · Docker · Singularity · RabbitMQ · Lithops · Dask |
| **Product & interfaces** | React · TypeScript · Python · Kotlin · Godot/GDScript · FFmpeg · Firebase · Stripe |
| **Engineering practice** | API integration · CI/CD · Observability · Performance profiling · Automated testing · Accessibility |

</details>

---

**Explore the engineering behind these projects → [macarronesc.github.io](https://macarronesc.github.io)**
