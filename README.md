# Hi, I'm Bennet Dyani 👋
 
### Agentic AI Engineer · I build AI agents that connect to real systems, with the guardrails businesses need
 
I design and build **AI agents, RAG systems and backend services** that do real work: investigating financial risk, answering questions from enterprise documents, and automating business workflows. I build them with the controls enterprises need: grounded answers, human approval for consequential actions, and audit trails.
 
- 🏢 **Enterprise experience:** built and tested AI agents on **BMC Helix / HelixGPT** at New Island Technologies
- 🏆 **Latest build:** [TrustAgent](https://github.com/BennetDyani/aws_hackathon), a Claude-powered financial risk investigation agent (AWS Hackathon 2026)
- 🎯 **Open to:** Junior–Intermediate **AI Engineer / AI Solutions Engineer** roles · Gauteng, hybrid or remote
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/bennet-dyani-543b03288/) · bennetdyani@gmail.com
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=flat&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20Bedrock-232F3E?style=flat&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" />
</p>
---
 
## ⭐ Featured projects
 
### 🔍 [TrustAgent](https://github.com/BennetDyani/aws_hackathon): AI financial risk investigation agent
`TypeScript` `Next.js` `Amazon Bedrock` `Claude Sonnet 4.6` `Server-Sent Events`
 
Most fraud systems stop at raising an alert. **TrustAgent carries out the investigation too.** Given a suspicious invoice, a Claude agent works through **8 specialised tools** (invoice analysis, supplier lookup, transaction history, policy checks and more), collects evidence, and recommends an action.
 
- **Deterministic risk scoring (0–100):** the score is calculated in code, not by the LLM, so it's reproducible and explainable
- **Human-in-the-loop:** the agent can recommend holding a payment but can't execute any financial decision without approval
- **Full audit trail:** every finding records its source, severity and risk contribution, and a live activity feed streams each step as it happens
- Built with a full requirements document, system design, test plan and deployment guide
### 🏠 AI Property Rental Management Platform *(in progress)*
`Python` `LangGraph` `FastAPI` `PostgreSQL + pgvector` `Docker` `n8n`
 
A multi-agent platform where an **intent router** sends each request to one of **4 specialist agents** (Tenant, Payment, Maintenance, Forecasting). The agents use tools, RAG over leases and records, and persistent conversation state.
 
```
n8n → FastAPI → LangGraph router → specialist agents → tools → PostgreSQL / pgvector
```
 
It supports switching between Groq and local Ollama models based on cost, performance and privacy needs.
 
### 📨 AI Property Management Front Desk
`n8n` `OpenAI` `Airtable` `Gmail` `Telegram`
 
A production-style automation that takes tenant messages from **3 channels**, normalises them into a single schema, classifies intent with structured LLM outputs, and routes each request to the right workflow.
 
- Owner commands are authorised by **identity, not by the LLM's interpretation**
- Scheduled jobs are idempotent and handle errors centrally
- **Debugging story:** traced a production self-triggering email loop through the n8n execution history and fixed it with a filter for self-sent messages
### 📄 Document Intelligence Hub
`Python` `LangChain` `ChromaDB` `Hugging Face` `Streamlit`
 
A RAG platform that turns PDF, DOCX and TXT files into searchable knowledge. It covers ingestion, chunking, embeddings, citation-aware Q&A, compliance/risk flagging, audit logging, and retrieval diagnostics with a keyword-search fallback.
 
---
 
## 💼 Experience
 
**Agentic AI Engineering Intern, New Island Technologies** · *Feb 2026 – Jul 2026*
 
- Built AI agents on **BMC Helix Innovation Studio and HelixGPT** that search enterprise knowledge bases, read documents, call APIs and complete defined business tasks
- Configured knowledge sources, tools, permissions and guardrails to keep answers grounded in approved information
- Tested agents with normal, out-of-scope and adversarial inputs to find loopholes, validate guardrails and verify task completion
**Software Developer Intern, Plum Systems** · *Jan 2025 – Dec 2025*
 
- Built features for web and mobile apps with React, React Native and Firebase in an Agile team
---
 
## 🛠️ Tech stack
 
| Area | Tools |
| --- | --- |
| **Agentic AI & LLMs** | LangGraph, LangChain, tool calling, RAG, structured outputs, Claude, OpenAI, Gemini, Groq, Ollama, Hugging Face, Amazon Bedrock |
| **Retrieval** | PostgreSQL + pgvector, ChromaDB, Sentence Transformers, semantic and keyword search |
| **Backend** | Python, FastAPI, TypeScript, Next.js, Java, Spring Boot, REST APIs, SQL, SQLAlchemy |
| **Automation** | n8n, webhooks, API integrations, scheduled workflows |
| **Quality & Ops** | LangSmith, Pytest, JUnit, Docker, Docker Compose, Git, Linux |
 
---
 
## 🌱 Currently deepening
 
LLM evaluation and observability · AI security (prompt injection, tool permissions) · MCP · production deployment and CI/CD
 
## 🎓 Education & certifications
 
**Diploma in ICT: Application Development**, Cape Peninsula University of Technology (2023–2025)
AWS AI Practitioner Challenge (AWS × Udacity) · Google AI Essentials · ALX AI Career Essentials · Cisco Linux Unhatched · Cisco IT Customer Support Basics
