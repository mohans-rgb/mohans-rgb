# 👋 Hi, I'm Mohan Sai Mathi

**B.Tech CSE Graduate | Aspiring GenAI Engineer | Building Multi-Agent AI Systems**

[![LinkedIn](https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohan-m-1133003a0/)
[![GitHub](https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mohans-rgb)

---

## About Me

I'm a **B.Tech CSE graduate** from **Vellore Institute of Technology**, focused on building **LLM-powered applications** and **multi-agent RAG systems**. I design end-to-end pipelines involving retrieval, orchestration, and secure multi-tenant architecture.

- 🎓 **B.Tech CSE** @ VIT (Vellore Institute of Technology) — CGPA 8.89
- 🔭 Currently building **multi-agent RAG systems** and **MCP servers** for AI agent tooling
- 🌱 Learning advanced **agentic architectures**, **hybrid retrieval**, and **cloud-native deployment**
- 💬 Ask me about RAG pipelines, LangGraph, FastAPI, AWS deployments, or MCP servers
- ⚡ Fun fact: I built an MCP server that lets any AI agent search flights and track my expenses

---

## Tech Stack

**AI / GenAI**
![LangGraph](https://img.shields.io/badge/LANGGRAPH-1C3C3C?style=for-the-badge) ![LangChain](https://img.shields.io/badge/LANGCHAIN-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white) ![Python](https://img.shields.io/badge/PYTHON-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Qdrant](https://img.shields.io/badge/QDRANT-DC244C?style=for-the-badge) ![Cohere](https://img.shields.io/badge/COHERE-39594C?style=for-the-badge)

**Backend & APIs**
![FastAPI](https://img.shields.io/badge/FASTAPI-005571?style=for-the-badge&logo=fastapi) ![Java](https://img.shields.io/badge/JAVA-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens)

**Database & Cloud**
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/POSTGRES-316192?style=for-the-badge&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/REDIS-DD0031?style=for-the-badge&logo=redis&logoColor=white) ![Docker](https://img.shields.io/badge/DOCKER-0db7ed?style=for-the-badge&logo=docker&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLITE-07405e?style=for-the-badge&logo=sqlite&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/GIT-F05033?style=for-the-badge&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GITHUB%20ACTIONS-2671E5?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Featured Projects

### 🔹 [AI Customer Support Agent — Multi-Agent RAG System](https://github.com/mohans-rgb/ecom-cust-support)
*LangGraph | Qdrant | Cohere | NeMo Guardrails | Redis | PostgreSQL*
- Designed a 5-node LangGraph state machine (guardrail → router → db/rag/ticket) routing queries to 3 specialized agents
- Implemented hybrid retrieval (dense + BM25 + RRF) with Cohere reranking and a Redis semantic cache
- Enforced per-user data isolation across all database tools via context-scoped variables

### 🔹 [Document Q&A API — RAG Service on AWS](https://github.com/mohans-rgb/rag-api-aws)
*FastAPI | AWS Bedrock | S3 | ECS Fargate | PostgreSQL | SQLAlchemy*
- Built an 8-endpoint FastAPI backend for authenticated PDF upload and RAG-powered chat
- Designed per-user document isolation using S3 metadata tagging, filtered at query time
- Shipped a full CI/CD pipeline: GitHub Actions → ECR → ECS Fargate on every push to main

### 🔹 [FinPilot — Personal Finance & Travel MCP Server](https://github.com/mohans-rgb/FinPilot)
*Python | FastMCP | SQLAlchemy | SerpAPI*
- Built an MCP server exposing 4 tools (expense logging, listing, deletion, flight search) to any MCP-compatible AI client
- Integrated a third-party flight-search API with structured error handling
- Supports both stdio and HTTP transports

---

## 📊 GitHub Stats
![](https://github-readme-stats.shion.dev/api?username=mohans-rgb&theme=default&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-stats.shion.dev/api/top-langs/?username=mohans-rgb&theme=default&hide_border=false&layout=compact)
