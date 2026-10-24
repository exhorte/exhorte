# Exhorte Mboumba

### Software Engineer · AI Engineer · Intelligent Systems & Automation

I engineer software and AI systems that turn complex problems into practical, reliable solutions.

My focus is on building products that **automate repetitive work, improve decision-making, simplify complex workflows, and make software more useful in real-world environments.**

I work across the entire engineering lifecycle: understanding the problem, designing the architecture, building the product, validating its behaviour, and preparing it for deployment.

**Core interests:** AI agents · Applied AI · Workflow Automation · Backend Engineering · Intelligent Applications

[Portfolio](https://exhorte.dev) · [LinkedIn](https://www.linkedin.com/in/exhorte-baboka-boumba) · [Featured Work](#selected-projects)

---

## What I Build

I approach engineering from the perspective of the problem being solved, not just the technology being used.

| Area                       | What I Focus On                                                                                                           |
| -------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| **AI Engineering**         | Building AI-powered applications, agent workflows, and systems that use context and evidence to produce useful outputs.   |
| **Intelligent Automation** | Turning repetitive, time-consuming processes into structured, automated workflows.                                        |
| **Software Architecture**  | Designing maintainable applications with clear boundaries, reliable APIs, and explicit system responsibilities.           |
| **Knowledge Systems**      | Making information accessible through retrieval-augmented generation, source-grounded answers, and document intelligence. |
| **Product Engineering**    | Taking an idea from problem definition to implementation, testing, and deployment.                                        |

My goal is to build systems that are not only functional, but also **understandable, testable, maintainable, and useful beyond a demo.**

---

## Selected Projects

The projects below illustrate the engineering problems I am exploring, the systems I am building, and the technical decisions behind them.

### 01. AI Software Architect

**From an idea to structured engineering deliverables.**

[Repository](https://github.com/exhorte/ai-software-architect)

**The problem**

Turning an early-stage product idea into a coherent technical plan requires substantial work across requirements, architecture, data modelling, API design, testing, and project planning.

**The approach**

Building a multi-agent platform that coordinates specialised agents to transform project requirements into structured engineering artifacts.

- Coordinates specialised agents through schema-validated shared state.
- Connects generated artifacts to the requirements they address.
- Supports architecture decisions, UML/C4/ERD diagrams, API design, database modelling, and roadmaps.
- Uses a collaborative canvas to work with diagrams in real time.
- Tests orchestration, shared memory, and real-time components.

**Engineering stack:** Next.js · TypeScript · PostgreSQL · Prisma · Vercel AI SDK · Trigger.dev · Liveblocks · Vitest

**Status:** In active development.

---

### 02. Vozel

**Private, cross-application voice dictation for Windows.**

[Repository](https://github.com/exhorte/vozel) · [Website](https://vozelwebsite.vercel.app)

**The problem**

Voice dictation should work wherever someone writes, without requiring audio to be sent to a cloud service by default.

**The approach**

Building a desktop dictation application that captures speech, transcribes it locally, and inserts the resulting text into the active application.

- Rust-based audio capture and voice-activity detection.
- On-device speech recognition using Parakeet-TDT and ONNX Runtime.
- A global push-to-talk shortcut and cross-application text insertion.
- Optional cloud transcription instead of mandatory cloud processing.
- A desktop interface built with Tauri and React.
- SQLite persistence and Rust unit tests.

**Engineering stack:** Rust · Tauri 2 · React · TypeScript · ONNX Runtime · SQLite

**Status:** In development.

---

### 03. HRagentAssistant

**An HR assistant grounded in company documentation.**

[Repository](https://github.com/exhorte/HRagentAssistant)

**The problem**

Employees need reliable answers about company policies. An AI assistant that invents an answer, ignores conflicting documents, or exposes restricted information creates operational and security risks.

**The approach**

Building a local HR assistant that answers questions using loaded documents, provides source citations, and acknowledges when the available evidence is insufficient.

- Retrieval-based question answering over HR documentation.
- Verifiable citations and abstention when evidence is missing.
- Detection of conflicting document versions.
- Backend-enforced role-based access control.
- Tests for access-control violations, prompt injection, and data leakage.
- A document-grounded answer validation layer.

The system is designed to make answers traceable to the available evidence rather than relying on model confidence alone.

**Engineering stack:** Python · LangChain · Qdrant · Streamlit · SQLite · pytest

**Status:** Working prototype using synthetic data.

---

### 04. Tontyn

**Digital infrastructure for community savings groups.**

[Repository](https://github.com/exhorte/TontyneApp) · [Live Demo](https://tontyn-frontend.vercel.app)

**The problem**

Community savings groups need digital tools to manage their activities while keeping each group's data and operations separated from those of other groups.

**The approach**

Building a web and mobile platform for managing community savings circles, commonly known as tontines.

- Three-tier application architecture.
- Spring Boot REST API with JWT authentication and two-factor authentication.
- Per-tontine authorization and PostgreSQL persistence.
- React web interface and Flutter mobile application.
- Docker-based development and deployment infrastructure.
- An integrated AI assistant with rate limiting and integration tests.

**Engineering stack:** Java 17 · Spring Boot 3 · PostgreSQL · React · Flutter · Docker

**Status:** In active development.

---

### Additional Engineering Work

- **[medicalAgent](https://github.com/exhorte/medicalAgent)** — A document-question-answering application built around uploaded PDFs, retrieval, FastAPI, and Pinecone.
- **[Fryle](https://github.com/exhorte/Fryle)** — A Next.js storefront with Stripe Checkout and database-backed application state.

---

## Technical Capabilities

My technical toolkit spans application development, AI integration, data systems, and software quality.

**Languages**

- TypeScript / JavaScript
- Python
- Java
- Rust
- C#

**Application Engineering**

- React, Next.js, Tailwind CSS, shadcn/ui
- Spring Boot and REST API development
- FastAPI
- Flutter
- Tauri desktop applications

**AI & Intelligent Systems**

- Large language model integration
- Retrieval-Augmented Generation (RAG)
- LangChain and LangGraph
- Qdrant and Pinecone
- Vercel AI SDK
- Agent orchestration and structured shared state
- Source-grounded question answering

**Data & Infrastructure**

- PostgreSQL and SQLite
- Prisma and Supabase
- Docker
- Vercel and Render
- Trigger.dev

**Testing & Reliability**

- Vitest
- pytest
- JUnit
- API and integration testing
- Authentication and authorization testing
- Failure-case and security-oriented testing

_These technologies reflect my work across different projects; they do not imply equal depth or production experience with every tool._

---

## Engineering Principles

**Solve the actual problem.**
Understand the user, the workflow, and the constraints before choosing a technical solution.

**Prefer clarity over unnecessary complexity.**
Build systems with explicit responsibilities, maintainable boundaries, and understandable decisions.

**Treat reliability as a design requirement.**
Test meaningful behaviour, validate assumptions, and account for failure cases and misuse.

**Make AI accountable to evidence.**
Where factual answers matter, prioritise traceable sources, explicit limitations, and predictable behaviour.

**Measure before optimising.**
Use evidence to guide performance improvements rather than adding complexity prematurely.

**Build for continued evolution.**
Document important decisions and create foundations that can be tested, extended, and maintained.

---

## Current Exploration

Areas I am actively exploring and developing further:

- Multi-agent systems and agent orchestration.
- Reliable AI applications with evaluation and validation layers.
- GraphRAG and knowledge-intensive applications.
- Multi-LLM architectures, abstraction, and fallback strategies.
- Practical AI automation for business workflows.

---

## Let's Build Something Useful

I am interested in engineering challenges where software, AI, and automation can create measurable practical value.

I welcome conversations about:

- AI engineering and intelligent applications.
- Software architecture and full-stack development.
- Workflow automation and AI-powered business tools.
- Engineering collaborations and meaningful software projects.

**Portfolio:** [exhorte.dev](https://exhorte.dev)
**LinkedIn:** [Connect with me](https://www.linkedin.com/in/exhorte-baboka-boumba)
**Company:** [ExponentValue](https://exponentvalue.com) — AI-powered business solutions and intelligent automation.

---

_I believe good engineering is measured not by the number of technologies used, but by the problems solved and the reliability of the solutions delivered._
