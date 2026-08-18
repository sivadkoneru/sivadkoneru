# Siva Datta Koneru

**Senior Software Engineer — AI Platforms, Backend Systems & Distributed Data**
Hyderabad, India · Remote across US and APAC time zones

I build production AI platforms and the distributed systems underneath them. Nine years shipping backend
and full-stack software at **Bloomberg**, **Upland Software**, and **GoodNotes** — the last four focused on
retrieval-augmented generation, LLM orchestration, and agentic workflows that hold up under real traffic.

Most of my work is measured in what it saved rather than what it demoed.

---

## What I've shipped

**Enterprise RAG platform — Panviva / Upland Software**
Owned it end to end for **11,000+ users** in compliance-sensitive contact-center workflows: semantic
chunking, embedding retrieval, cosine ranking, context re-ranking, Azure OpenAI generation, and self-hosted
vLLM for inference cost control.

- **−35%** AI infrastructure cost and **−20%** inference latency through semantic caching, token-budget optimization, and request batching
- **~+60%** answer relevance and agent productivity, measured by resolved-query rate
- LLM-as-judge evaluation harness with golden datasets and groundedness scoring, gating releases
- Multi-stage guardrails flagging low-confidence and ungrounded answers before delivery

**Fixed-income analytics — Bloomberg TOMS**
Distributed analytics for sell-side trading desks over **100M+ market and trade records daily**.

- **−60%** analytics pipeline latency, rebuilding SQL Server aggregations onto Apache Druid
- Real-time ingestion, validation, and reconciliation; G-spread and Z-spread computed live
- Decommissioned 30+ legacy services while raising automated test coverage 20%

**AI product and agentic automation — GoodNotes**
Production AI image workflows across web, backend, and iOS; **−80% crashes** across 100+ resolved bugs.
Built MCP-based multi-agent automation over engineering tools that cut bug investigation and triage effort 30%.

---

## What I'm building in public

| Project | What it is |
| --- | --- |
| [enterprise-rag-platform](https://github.com/sivadkoneru/enterprise-rag-platform) | Pluggable RAG platform in .NET 10 — ingests from local disk, S3, and Azure Blob; chunks and embeds into a document store plus Elasticsearch; answers with grounded, cited responses through configurable LLM endpoints. Minimal API + CLI, provider packages for Cosmos, Mongo, S3, and Blob. |
| [market-intelligence-platform](https://github.com/sivadkoneru/market-intelligence-platform) | Multi-service Python platform streaming live market data and news through Azure Service Bus, computing technical indicators and RAG-driven insights, persisting time series to Apache Druid, and serving REST + WebSocket APIs. |
| [atlassian-hermes-connector](https://github.com/sivadkoneru/atlassian-hermes-connector) | Connects Jira through the Atlassian MCP server to a local Kanban board, git branches, and reviewed pull requests. |

---

## Stack

**AI/LLM** RAG · semantic chunking · embeddings · context re-ranking · Azure OpenAI · Claude · Gemini · vLLM · AutoGen · MCP · guardrails and groundedness evaluation

**Backend** Python · FastAPI · C# / .NET · ASP.NET Core · TypeScript · React · REST · microservices

**Data** PostgreSQL · SQL Server · Cosmos DB · Elasticsearch · Apache Druid · Redis · MongoDB · Azure Service Bus

**Cloud** Azure · AKS · Azure Functions · Docker · Kubernetes · CI/CD · New Relic · Grafana · Splunk

---

## Get in touch

[LinkedIn](https://linkedin.com/in/sdkoneru) · [sdkoneru.com](https://sdkoneru.com) · sivadattak7@gmail.com

Available for contract work through the Toptal network or directly.
