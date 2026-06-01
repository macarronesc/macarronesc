# Daniel Coll Tejeda 🚀
### **Software Engineer — Cloud, AI & Distributed Systems**

Building high-performance distributed systems, state-of-the-art AI architectures, and cloud-native serverless platforms. Blending academic research with production-grade engineering.

---

<div align="center">
  <a href="https://macarronesc.github.io">
    <img src="https://img.shields.io/badge/Portfolio-macarronesc.github.io-0078d4?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://linkedin.com/in/macarronesc">
    <img src="https://img.shields.io/badge/LinkedIn-macarronesc-0077b5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://github.com/macarronesc">
    <img src="https://img.shields.io/badge/GitHub-macarronesc-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</div>

---

## ⚡ Quick Highlights

*   🧠 **LiteRAG (EMNLP 2026):** Architected a Zero-LLM GraphRAG framework achieving **99.9% cost reduction** and **100x lower latency** than Microsoft GraphRAG.
*   🎬 **Klipso (SaaS):** Scaled a multi-modal AI video editing platform to **50+ active paying subscribers** and **2,500+ clips generated** in production.
*   🚀 **PyRun Cloud:** Led a full-stack serverless PaaS with Agentic AI (MCP), automating AWS/IBM deployments for **50+ researchers** (99.98% SLA, 80% faster setups).
*   🌐 **Lithops (Core Contributor):** Engineered high-performance serverless backends for **MareNostrum 5 (BSC)** supercomputer and Kubernetes (7x cold-start improvement).
*   📱 **Soundless (IEEE 2025):** Deployed Fitbit & Android citizen-science platforms evaluating physiological impacts of noise pollution on sleep health.

---

## 🛠️ Featured Projects & Research

### 1. **LiteRAG — Adaptive Graph-Native Search** *(Research)*
Next-generation GraphRAG framework solving the "prohibitive cost" problem of graph-based retrieval via a **Zero-LLM mathematical navigation engine**. Decouples retrieval from global graph size to maintain constant-time $O(1)$ latency.
*   **The Breakthrough (on a 1,280-document corpus):**
    | Metric | **LiteRAG (Ours)** | GraphRAG (DRIFT) | Improvement |
    | :--- | :--- | :--- | :--- |
    | **Cost** | **€0.01** | €25.28 | **99.9% Reduction** |
    | **Latency** | **1.42s** | 142.04s | **100x Faster** |
    | **Accuracy** | **0.798** | 0.657 | **+21.4% Better** |
*   **Tech Stack:** `Python` · `PyTorch` · `NetworkX` · `Neo4j` · `Sentence-Transformers` · `Gemini`
*   *Status: Submitted to **EMNLP 2026**.*

### 2. **Klipso — AI-Powered Viral Clip Platform** *(SaaS)*
A full-stack, automated video editing SaaS. Fuses audio processing, natural language understanding, and computer vision to autonomously transform long YouTube videos into viral, speaker-focused vertical clips.
*   **Features:** Multi-modal AI pipeline (Whisper transcribes, Gemini parses "hooks," PyAnnote + MediaPipe performs speaker-aware face tracking, FFmpeg hardware-renders transitions & subtitles).
*   **Cloud Architecture:** React 19, Vercel Python serverless API, Firebase Realtime DB job queue, Cloudflare R2 storage, Stripe subscription billing.
*   **Traction:** Active paying customers, **2,500+ clips generated** in production.
*   **Tech Stack:** `React 19` · `TypeScript` · `Python` · `OpenAI Whisper` · `Gemini API` · `MediaPipe` · `PyAnnote` · `FFmpeg` · `Firebase` · `Stripe` · `Cloudflare R2`
*   *🌐 Website: [klipso.vercel.app](https://klipso.vercel.app/)*

### 3. **PyRun Cloud — AI-Assisted Serverless PaaS** *(Tech Lead)*
A comprehensive developer-focused PaaS eliminating the operational friction between researchers and cloud infrastructure. Provides an intuitive web-based IDE with Agentic AI to dynamically build, deploy, and monitor distributed workloads.
*   **Key Contributions:** Integrated Agentic AI via **Model Context Protocol (MCP)** allowing natural-language cloud deployments; automated AWS CodeBuild/CodePipeline CI/CD image builds; designed a dynamic byte-range dataset partitioner (*Dataplug*).
*   **Traction:** Used by **50+ active researchers**, reducing infrastructure setup times by **80%** (99.98% SLA).
*   **Tech Stack:** `React` · `TypeScript` · `Python` · `AWS (Amplify, Cognito, DynamoDB, CodeBuild, CloudFormation)` · `IBM Code Engine` · `Kubernetes` · `Docker`
*   *🌐 Website: [pyrun.cloud](https://pyrun.cloud)*

### 4. **Lithops — Multi-Cloud Serverless Computing** *(Core Contributor)*
Open-source Python framework executing scale-out parallel workloads across thousands of cloud functions with zero provider boilerplate.
*   **Key Contributions:** 
    *   **HPC Serverless Engine:** Architected a Singularity & RabbitMQ backend on the **MareNostrum 5 (BSC)** supercomputer, enabling serverless semantics on HPC nodes (*Published at IEEE 2024*).
    *   **Kubernetes Work-Queue:** Engineered a RabbitMQ-backed pod pooling engine delivering **7x cold-start improvements** under high API server loads.
    *   **AWS EC2 Standalone Backend:** Built a custom compute backend from scratch supporting dynamic VM lifecycle modes (`Create`/`Reuse`/`Consume`).
*   **Tech Stack:** `Python` · `AWS EC2/Lambda` · `Kubernetes` · `Singularity` · `RabbitMQ` · `Docker` · `Dask`

### 5. **Soundless — Citizen Science Wearable Platform** *(Lead Developer)*
Investigating the physiological impact of urban noise pollution on sleep quality and cardiovascular health. Deployed to 50 residents in Tarragona, Spain.
*   **Architected System:** Mobile App (Kotlin/Android) sampling sleep audio and calling Fitbit API to sync heart rate, HRV, and sleep stages; BigQuery analytics running custom Z-score dispersion algorithms.
*   **Edge Computing Research:** Engineered mechanisms to run cloud-native serverless functions directly on smartphones to protect sensitive biometric audio data (*Published at IEEE 2025*).
*   **Tech Stack:** `Kotlin` · `Android SDK` · `Fitbit API` · `GCP (BigQuery, Storage)` · `Firebase` · `Python`

---

## 🐙 Core Open Source Contributions

I believe in giving back to foundational libraries that build the modern developer ecosystem:

*   **[Ollama](https://github.com/ollama/ollama) (Go):** Engineered low-level runtime optimizations inside the core inference pipeline to drastically reduce local model loading latency.
*   **[Google Gemini CLI](https://github.com/google-gemini/gemini-cli) (TypeScript):** Overhauled the tool orchestration layer to streamline external tool execution during complex autonomous agentic workflows.
*   **[Dask CloudProvider](https://github.com/dask/dask-cloudprovider) (Python):** Engineered a high-performance IBM Cloud Code Engine backend for distributed Dask clusters, beating commercial managed alternatives in provisioning speed.

---

## 💻 Tech Stack & Tooling

<div align="center">
  <table>
    <tr>
      <td valign="top" width="25%">
        <strong>🤖 AI / ML</strong><br />
        • PyTorch<br />
        • TensorFlow / Keras<br />
        • Neo4j (Graph Indexing)<br />
        • LLMs (Gemini, Ollama)<br />
        • Whisper & PyAnnote<br />
        • MediaPipe & CV
      </td>
      <td valign="top" width="25%">
        <strong>☁️ Cloud & Infra</strong><br />
        • AWS Lambda / EC2 / Cognito<br />
        • GCP BigQuery / Storage<br />
        • IBM Cloud Engine<br />
        • Kubernetes & Docker<br />
        • Serverless / CI/CD<br />
        • Cloudflare R2
      </td>
      <td valign="top" width="25%">
        <strong>💻 Programming</strong><br />
        • Python<br />
        • Go<br />
        • TypeScript<br />
        • Kotlin<br />
        • Swift / Java<br />
        • SQL
      </td>
      <td valign="top" width="25%">
        <strong>🛠️ Tools & Ecosystem</strong><br />
        • React 19 & Vite<br />
        • Firebase<br />
        • RabbitMQ<br />
        • FFmpeg<br />
        • Dask & NetworkX<br />
        • Stripe Integration
      </td>
    </tr>
  </table>
</div>

---

## 📢 Technical Speaking

I enjoy demystifying complex distributed systems and cloud architectures for the developer community:
*   **PyConEs 2025** *(Sevilla, Spain)* — *Multi-Cloud Serverless Parallel Programming in Python* 🐍
*   **EuroSciPy 2025** *(Poland)* — *Processing Cloud-Optimized Data in Python* (introducing Dataplug for genomic & geospatial parallel I/O) 📊

---

## 📩 Let's Connect!

I am always open to discussing distributed systems, AI application architecture, high-performance RAG, and cloud-native scaling.

*   💬 Ask me about **GraphRAG, serverless parallel frameworks, or dynamic face tracking**!
*   👔 Connect with me on [**LinkedIn**](https://linkedin.com/in/macarronesc)
*   💻 Discover more at: [**macarronesc.github.io**](https://macarronesc.github.io)
