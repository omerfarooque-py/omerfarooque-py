# Omer Farooque (Umer Farooque)
**AI & Python Backend Engineer**

Computer Science undergraduate (SZABIST, Class of 2027) building Python backend systems, deterministic agentic workflows, and semantic retrieval pipelines—focusing on low-latency tool routing, PostgreSQL state persistence, and clean relational APIs.

---

### Core Stack
* **Backend & APIs:** Python, FastAPI, Django, Django REST Framework (DRF), SQLAlchemy, Pydantic, Uvicorn/ASGI, SSE Streaming
* **AI & Agentic Systems:** LangGraph, LangChain, Model Context Protocol (MCP), RAG, pgvector, FAISS, Sentence Transformers, Classical ML (TF-IDF + Multinomial Naive Bayes)
* **Data, Queues & Infra:** PostgreSQL, SQLite, Redis, Celery, Docker, Linux, JWT Authentication, Git

---

### Featured Systems

#### 1. [JARVIS — AI Agentic Assistant](https://github.com/omerfarooque-py/Agentic-Assistant)
Multi-domain personal operations assistant built with **Django, LangGraph, MCP, PostgreSQL, and SSE**.

```text
User Request
     │
     ▼
Intent Classification (TF-IDF + Multinomial Naive Bayes)
     │
     ▼
LangGraph Orchestration ──► Relevant MCP Tools (Gmail, Calendar, Docs, Sheets, Slack, Web)
     │
     ▼
Human-in-the-Loop Approval + PostgreSQL State Persistence
     │
     ▼
SSE Response Streaming
```

* **Intent-Based Tool Routing:** Implemented a TF-IDF + Multinomial Naive Bayes classifier to filter incoming requests and expose only relevant MCP tools, reducing prompt bloat, token overhead, and unnecessary LLM calls.
* **Approval Gates & State Persistence:** Added LangGraph interrupts for sensitive external actions (such as sending emails) backed by PostgreSQL state persistence so interrupted workflows can be resumed reliably.
* **Real-Time Streaming:** Built Server-Sent Events (SSE) streaming for incremental responses across multi-step tool executions.

#### 2. [HireLens — AI Resume Analysis & Ranking](https://github.com/omerfarooque-py/HireLens)
Backend resume processing and candidate retrieval system built with **Python, Django REST Framework, Celery, FAISS, and LangChain**.
* **Async Ingestion Pipeline:** Offloads PDF text extraction, chunking, embedding generation, and vector-store caching to Celery background workers.
* **Batch Semantic Retrieval:** Indexes candidate resumes in FAISS and runs job-context similarity retrieval and LLM-assisted evaluation across candidate batches.

#### 3. [Content Management & Blogging API](https://github.com/omerfarooque-py/Personal-Blog-FastAPI)
Backend REST API built with **FastAPI, PostgreSQL, SQLAlchemy, and Streamlit**.
* **Auth & Data Modeling:** Implements JWT authentication, bcrypt password hashing, relational database modeling, Pydantic request/response validation, and user-isolated CRUD endpoints.

#### 4. [CLI AI Agent](https://github.com/omerfarooque-py/CLI-AI-AGENT) & [Algorithms](https://github.com/omerfarooque-py/neetcode-submissions)
* Terminal-based AI agent capable of directory inspection, Python script execution, and iterative error fixing.
* Ongoing data structures and algorithms practice on [LeetCode](https://leetcode.com/u/UHzD1p3a4u/) and NeetCode alongside **306+ GitHub contributions**.

---


### Experience & Education

* **Python Backend / AI Engineering Intern** — Clentro, Hyderabad *(July 2026 – October 2026)*

  * Developed and implemented LangGraph + MCP agent workflows, a TF-IDF/Naive Bayes intent router, LangGraph human-approval interrupts, PostgreSQL conversation persistence, SSE streaming, and Celery-backed resume processing pipelines.

  * **Agentic-Assistant:** Worked on benchmarking tool-routing accuracy, prompt token reduction, and end-to-end latency.

  * **HireLens:** Worked on retrieval evaluation metrics and background-task retry reliability.

  * **Testing & Reproducibility:** Built automated test coverage, edge-case validation, and one-command Docker setups across repositories.

* **B.S. in Computer Science (BSCS)** — SZABIST University *(2024 – 2027)*

---

### Connect
* **Email:** `omer.farooque@yahoo.com`
* **LinkedIn:** [linkedin.com/in/omer-farooque-b04825346](https://www.linkedin.com/in/omer-farooque-b04825346/)
* **Wellfound:** [wellfound.com/u/ummnaastar](https://wellfound.com/u/ummnaastar)
* **LeetCode:** [leetcode.com/u/UHzD1p3a4u](https://leetcode.com/u/UHzD1p3a4u/)
* **Work GitHub:** [github.com/omerfarooque-clentro](https://github.com/omerfarooque-clentro)