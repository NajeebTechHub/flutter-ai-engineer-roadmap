<div align="center">

# 🚀 Flutter AI Engineer Roadmap

### From Flutter Developer → AI Application Engineer → AI Mobile Developer

**A public, project-first log of building real AI-powered applications — not just tutorials.**

<br/>

[![Status](https://img.shields.io/badge/Status-In%20Progress-2ea44f?style=for-the-badge)](#-progress-tracker)
[![Phase](https://img.shields.io/badge/Current%20Phase-Phase%200-blue?style=for-the-badge)](#-roadmap-overview)
[![Days](https://img.shields.io/badge/Days%20Logged-000-informational?style=for-the-badge)](#-repository-statistics)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](#-license)

<br/>

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](#)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)](#)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)](#)
[![Gemini](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)](#)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)](#)
[![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)](#)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](#)

</div>

<br/>

> **Journey status:** 🟢 Actively building — this repository is updated continuously as I move through the roadmap, not written once and abandoned.

> **Learning philosophy:** *Build first, understand deeply, document publicly.* Every concept in this repo is paired with working code, not just notes.

---

## 📖 About This Repository

This repository is the single source of truth for my transition from **professional Flutter Developer** to **AI Application Engineer**, documented in public, end to end.

It is **not** a collection of course notes. It contains the actual artifacts of the work:

- 📅 Daily learning logs
- 🧪 Practice code and experiments
- 🧩 Mini, intermediate, advanced, and capstone projects
- 🖼️ Screenshots and 🎥 demo videos of working apps
- 📚 Curated notes and resource lists
- ❓ Interview questions I'm collecting along the way
- 📝 Homework and self-set challenges
- 🤖 AI experiments (LLMs, RAG, agents, MCP, on-device AI)
- 📱 Flutter + AI integrations — the actual intersection this repo is built around

**Who this is for:**
- Flutter/mobile developers considering a similar transition into AI engineering
- Recruiters and hiring managers evaluating hands-on, verifiable AI application experience
- Anyone who prefers **evidence of shipped work** over certificates

**Why I'm building this:** The AI job market rewards specialists who can *ship*, not generalists who only understand theory. I'm building the specific, underserved intersection of **production mobile development + applied LLM engineering** — and documenting every step so the progress is verifiable, not just claimed.

**My goal:** Become an engineer capable of independently designing, building, evaluating, and deploying complete AI-powered mobile applications and, eventually, AI products.

---

## 🎯 Career Goal

```
   Flutter Developer
         │
         ▼
   AI Application Engineer
         │
         ▼
   AI Mobile Developer
         │
         ▼
   GenAI Engineer
```

I am deliberately optimizing for **production AI application engineering** — integrating, orchestrating, evaluating, and shipping large language models, retrieval systems, and agents inside real products — **not** for becoming a Machine Learning Researcher. No custom model training, no research-paper-level math. The target is deployable, portfolio-grade, revenue-relevant AI software.

---

## 🗺️ Roadmap Overview

<div align="center">

| Phase | Focus | Goal | Key Projects | Outcome |
|:---:|---|---|---|---|
| **0** | 🐍 Python for AI | Get fluent in async, API-ready Python | CLI tools, FastAPI hello-world | Can script async API calls confidently |
| **1** | 💬 Prompt Engineering | Master reliable, structured prompting | Prompt playground, structured extractor | Predictable, structured model outputs |
| **2** | 🔌 LLM APIs & Function Calling | Wire LLMs into real app logic | Tool-calling chatbot, stateful Flutter app | Chat → real app actions |
| **3** | 📚 RAG & Vector Databases | Ground LLMs in real data | Document Q&A app, semantic search | "Chat with your data" pipeline |
| **4** | ➗ Applied Math & ML Literacy | Understand the concepts behind the tools | Toy classifier, similarity demo | Conceptual fluency, no gatekeeping theory |
| **5** | 🤖 AI Agents & MCP | Build autonomous, tool-using systems | Multi-tool agent, custom MCP server | Agents that plan, retrieve, and act |
| **6** | 🛡️ Evaluation & Guardrails | Make systems measurable and safe | Eval harness, prompt-injection defenses | Production-grade reliability |
| **7** | 👁️ Computer Vision | Add on-device vision to mobile apps | OCR scanner, MediaPipe detector | Vision + language fusion features |
| **8** | 🏆 Flutter + AI Capstone | Ship flagship, deployed AI apps | 3 portfolio-grade apps | Job-ready, interview-ready portfolio |

</div>

<details>
<summary><strong>📌 Click to expand full phase-by-phase breakdown</strong></summary>

<br/>

**Phase 0 — Python for AI**
- Goal: Async-first Python fluency for consuming AI SDKs
- Projects: REST CLI tool → CSV-to-webhook script → minimal FastAPI service
- Outcome: Comfortable writing 200-line async scripts without friction

**Phase 1 — Prompt Engineering**
- Goal: Reliable, reproducible prompting discipline
- Projects: Prompt playground app, structured-output extractor
- Outcome: Understands tokens, context windows, few-shot, chain-of-thought

**Phase 2 — LLM APIs & Function Calling**
- Goal: Turn chat into functioning app features
- Projects: Tool-calling assistant, Flutter state controlled by LLM output
- Outcome: Production-style structured outputs + function calling

**Phase 3 — RAG & Vector Databases**
- Goal: Ground answers in real, private data
- Projects: PDF/document Q&A app with citations, semantic search engine
- Outcome: Full embed → store → retrieve → generate pipeline

**Phase 4 — Applied Math & ML Literacy**
- Goal: Just enough theory to reason about the systems being built
- Projects: Toy scikit-learn classifier, cosine-similarity demo
- Outcome: Conceptual fluency without academic overhead

**Phase 5 — AI Agents & MCP**
- Goal: Build autonomous, multi-step, tool-using systems
- Projects: LangGraph multi-tool agent, custom MCP server exposing app tools
- Outcome: Agents with memory, planning, and real tool execution

**Phase 6 — Evaluation & Guardrails**
- Goal: Make AI systems measurable, safe, and production-ready
- Projects: RAGAS evaluation harness, prompt-injection defense layer
- Outcome: Verified, benchmarked systems — not just demos

**Phase 7 — Computer Vision (Mobile-Focused)**
- Goal: Add practical, on-device vision capabilities
- Projects: OCR receipt scanner, MediaPipe real-time detector
- Outcome: Vision output fused with LLM reasoning

**Phase 8 — Flutter + AI Capstone**
- Goal: Ship polished, deployed, evaluated flagship applications
- Projects: AI Document Assistant, On-device Privacy Assistant, Agentic App Assistant
- Outcome: A complete, demo-ready, recruiter-facing portfolio

</details>

---

## 📁 Repository Structure

```
flutter-ai-engineer-roadmap/
│
├── README.md
├── LICENSE
├── ROADMAP.md
│
├── 📂 phase-0-python/
│   └── readme.md
│   ├── day-01/
│            ├── day-01.py
│            ├── task.py
             ├── 📂 screenshots
             ├── demo.gif
│       ├── day-02/
│       └── ...    
│
├── 📂 phase-1-prompt-engineering/
│   ├── notes/
│   ├── practice/
│   ├── mini-projects/
│   └── daily/
│
├── 📂 phase-2-llm-apis/
│   ├── notes/
│   ├── function-calling/
│   ├── structured-output/
│   └── daily/
│
├── 📂 phase-3-rag/
│   ├── notes/
│   ├── embeddings/
│   ├── vector-db/
│   ├── projects/
│   └── daily/
│
├── 📂 phase-4-math-ml-literacy/
│   └── notes/
│
├── 📂 phase-5-agents-mcp/
│   ├── notes/
│   ├── langgraph/
│   ├── mcp-servers/
│   └── daily/
│
├── 📂 phase-6-evaluation-guardrails/
│   ├── notes/
│   └── eval-harness/
│
├── 📂 phase-7-computer-vision/
│   ├── notes/
│   ├── ocr/
│   ├── mediapipe/
│   └── daily/
│
├── 📂 phase-8-capstone/
│   ├── project-1-ai-document-assistant/
│   ├── project-2-on-device-privacy-assistant/
│   └── project-3-agentic-app-assistant/
│
├── 📂 interview-questions/
│   ├── python.md
│   ├── llm-fundamentals.md
│   ├── rag.md
│   ├── agents-mcp.md
│   └── flutter-ai.md
│
├── 📂 assignments/
│   └── weekly-homework/
│
└── 📂 challenges/
    └── 30-day-ai-build-challenge/
```

---

## 🛠️ Learning Stack

<div align="center">

| Category | Technologies |
|---|---|
| **Languages** | Python, Dart |
| **Mobile Framework** | Flutter (Provider, BLoC) |
| **AI / LLM Providers** | Gemini API, OpenAI API, Claude API |
| **AI Frameworks** | LangChain, LangGraph, Hugging Face |
| **Backend** | FastAPI |
| **Databases / Vector Stores** | Firebase / Firestore, Chroma, Qdrant, Pinecone |
| **Computer Vision** | Google ML Kit (OCR), MediaPipe, TFLite / LiteRT |
| **On-Device AI** | Gemini Nano, Apple Foundation Models, Gemma (`flutter_gemma`) |
| **Protocols / Standards** | MCP (Model Context Protocol), REST, SSE Streaming |
| **Deployment** | Docker, Firebase AI Logic, Render / Railway / Fly.io |
| **Tooling** | Cursor, Claude Code, GitHub Copilot, Ollama |
| **Version Control** | Git, GitHub |
| **IDE** | VS Code, Android Studio |

</div>

---

## 🧠 Skills Covered

<div align="center">

| Core AI Engineering | Flutter + Mobile AI | Infrastructure |
|---|---|---|
| Python (async, API-first) | Flutter AI integration patterns | FastAPI |
| Prompt Engineering | On-device AI (Gemini Nano, Gemma) | Docker |
| Function Calling | OCR (ML Kit) | Deployment (Render/Fly.io) |
| Structured Outputs | MediaPipe | GitHub / Git workflows |
| Embeddings | YOLO (TFLite export) | CI/CD basics |
| Vector Databases | Streaming AI responses | — |
| RAG (Retrieval-Augmented Generation) | Gemini API · OpenAI API · Claude API | — |
| LangChain / LangGraph | — | — |
| MCP (Model Context Protocol) | — | — |
| AI Agents & Multi-Agent Systems | — | — |
| Evaluation (RAGAS / LangSmith) | — | — |
| Guardrails & Prompt-Injection Defense | — | — |

</div>

---

## 🔁 Learning Philosophy

```
   Learn → Build → Break → Debug → Deploy → Document → Repeat
```

Every topic in this repository follows the same loop:

1. **Learn** the concept from official docs / a focused course module
2. **Build** something small immediately — no theory-only weeks
3. **Break** it on purpose to understand its failure modes
4. **Debug** it using real tools (logs, tracing, LangSmith, print debugging)
5. **Deploy** it whenever feasible — local-only projects don't count as done
6. **Document** what was learned, publicly, in this repo
7. **Repeat** at the next difficulty level

No topic is considered "complete" until it has shipped working, documented code.

---

## 📅 Daily Learning Structure

Each daily folder (`phase-X/daily/day-NN/`) follows a consistent format:

| Component | Description |
|---|---|
| 📖 **Theory** | Short notes — concept summary, not a copy of the docs |
| 💻 **Practice** | Hands-on code written that day |
| 🧩 **Mini Project** | A small, working artifact applying the day's concept |
| 📝 **Homework** | Self-assigned follow-up task for reinforcement |
| ❓ **Interview Questions** | Questions this topic could generate in an interview, with answers |
| 🖼️ **Screenshots** | Visual proof of working output |
| 🎥 **Demo Video** | Short clip when the output is interactive/visual |
| 🔀 **Git Commit** | Every day ends in at least one meaningful, atomic commit |
| 📄 **README** | Each project folder has its own local README |

---

## 📏 Project Rules

- 🚫 **No tutorial hell** — every tutorial followed is immediately modified, extended, or rebuilt from memory
- 🏗️ **Project-first learning** — concepts are learned by building, not by only reading/watching
- 📝 **Documentation is mandatory** — undocumented code is treated as unfinished code
- 🌳 **Clean Git history** — atomic, descriptive commits; no `"fix"` or `"update"` commit messages
- 🧹 **Readable code** — consistent formatting, meaningful names, no unexplained magic
- 📁 **Professional folder structure** — every project mirrors real-world repo conventions
- 🚀 **Deploy whenever possible** — a project isn't "done" until it's reachable outside localhost

---

## ✅ Progress Tracker

<details open>
<summary><strong>Phase 0 — Python for AI</strong></summary>

- [ ] Python async/await fundamentals
- [ ] REST API consumption (`requests` / `httpx`)
- [ ] Environment management (`venv`, `.env`)
- [ ] Mini project: CLI REST tool
- [ ] Mini project: FastAPI hello-world service

</details>

<details>
<summary><strong>Phase 1 — Prompt Engineering</strong></summary>

- [ ] System / user / assistant roles
- [ ] Few-shot prompting
- [ ] Chain-of-thought prompting
- [ ] Project: Prompt playground (Flutter)
- [ ] Project: Structured-output extractor

</details>

<details>
<summary><strong>Phase 2 — LLM APIs & Function Calling</strong></summary>

- [ ] Gemini API integration
- [ ] OpenAI API integration
- [ ] Claude API integration
- [ ] Function calling
- [ ] Structured outputs (JSON schema)
- [ ] Project: Tool-calling Flutter chatbot

</details>

<details>
<summary><strong>Phase 3 — RAG & Vector Databases</strong></summary>

- [ ] Embeddings fundamentals
- [ ] Chroma (local vector DB)
- [ ] Qdrant / Pinecone (production vector DB)
- [ ] Chunking strategies
- [ ] Project: Document Q&A app with citations

</details>

<details>
<summary><strong>Phase 4 — Applied Math & ML Literacy</strong></summary>

- [ ] Vectors, dot product, cosine similarity
- [ ] Precision / recall / basic statistics
- [ ] scikit-learn "getting started" pass

</details>

<details>
<summary><strong>Phase 5 — AI Agents & MCP</strong></summary>

- [ ] LangGraph fundamentals
- [ ] Memory (short-term / long-term)
- [ ] Model Context Protocol (client + server)
- [ ] Multi-agent orchestration
- [ ] Project: Custom MCP server + agent

</details>

<details>
<summary><strong>Phase 6 — Evaluation & Guardrails</strong></summary>

- [ ] RAGAS / LangSmith evaluation
- [ ] Hallucination / faithfulness scoring
- [ ] Prompt-injection defenses
- [ ] Guardrail implementation on live project

</details>

<details>
<summary><strong>Phase 7 — Computer Vision</strong></summary>

- [ ] OCR (Google ML Kit)
- [ ] MediaPipe integration
- [ ] YOLO via TFLite (optional)
- [ ] Project: Receipt scanner + LLM extraction

</details>

<details>
<summary><strong>Phase 8 — Flutter + AI Capstone</strong></summary>

- [ ] Capstone 1: AI Document Assistant (deployed)
- [ ] Capstone 2: On-device Privacy Assistant (offline-first)
- [ ] Capstone 3: Agentic App Assistant (MCP + tools)
- [ ] Portfolio polish (READMEs, demo videos, resume)

</details>

---

## 🏁 Milestones

- [ ] 🐣 First Python Script
- [ ] 🔌 First LLM API Call
- [ ] 💬 First AI Chat Interface
- [ ] 📚 First RAG Application
- [ ] 🤖 First Autonomous Agent
- [ ] 🔠 First OCR Application
- [ ] 🏆 First Capstone Shipped
- [ ] 💼 Job / Freelance Ready

---

## 📊 Repository Statistics

<div align="center">

| Metric | Count |
|---|:---:|
| 🧩 Projects Built | `0` |
| 📅 Days Logged | `0` |
| ⏱️ Hours Invested | `0` |
| 🔀 Commits | `0` |
| 🖼️ Screenshots | `0` |
| 🎥 Demo Videos | `0` |
| 📦 Related Repositories | `0` |
| 🧠 Technologies Used | `0` |

*Updated regularly as the roadmap progresses.*

</div>

---

## 🔮 Future Projects

Planned AI-powered Flutter applications beyond the core capstone set:

- 💬 **AI Chat Companion** — multi-provider chat app with memory
- 📄 **Resume Analyzer** — LLM-powered resume feedback and scoring
- 📚 **PDF Chat** — RAG-based document conversation app
- 🗒️ **AI Notes** — auto-summarizing, semantically searchable notes app
- 🌐 **AI Translator** — real-time multimodal translation
- 🎙️ **AI Voice Assistant** — streaming voice-first mobile assistant
- 📷 **AI Camera** — real-time on-device object/scene understanding
- 📴 **Offline AI Toolkit** — fully offline, privacy-first AI feature set
- 👨‍💻 **AI Coding Assistant** — in-app code helper using agentic tool calls
- 🎓 **AI Study Companion** — personalized, RAG-powered study assistant

---

## 📚 Resources

Every phase folder contains its own curated resource list, consistently structured:

- 📘 **Books**
- 📄 **Official Documentation**
- 🎓 **Courses** (free-first)
- ✍️ **Articles**
- 🎬 **Videos**
- 🧪 **Practice Platforms**

See [`/resources`](./resources) for the full, continuously updated master list.

---

## 🔗 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](#)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](#)

*(Replace the placeholder links above with your actual profiles.)*

</div>

---

## 📄 License

This repository is licensed under the **MIT License** — see [`LICENSE`](./LICENSE) for details.

---

<div align="center">

### 💬 Final Note

> *"Consistency compounds. A small, working project shipped every week will outpace a perfect roadmap that never leaves the notes app."*

<br/>

**⭐ If you're on a similar journey, feel free to fork this structure and follow along.**

</div>
