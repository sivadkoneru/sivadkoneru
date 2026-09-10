# Siva Datta Koneru

**Senior AI Platform Engineer — LLM Systems, RAG & Backend**

Hyderabad, India · Remote across US and APAC time zones

Senior software engineer with 9+ years of experience building AI platforms, backend services, distributed data systems, and React applications. My professional impact comes from work at Panviva, Bloomberg, and GoodNotes; the pinned repositories provide public, runnable reference implementations of relevant engineering practices.

## Production Impact

- **Panviva / Upland Software:** Architected an enterprise RAG platform serving **11,000+ users**. Implemented prompt caching that reduced AI infrastructure cost by **35%** and average response time by **20%**; owned LLM workflows for prompt enhancement, answer generation, title generation, and hallucination checks.
- **Bloomberg TOMS:** Built Python fixed-income analytics for workflows processing **100M+ market and trade records daily**; contributed to a **60%** reduction in analytics latency through Apache Druid.
- **Bloomberg Internal Sales:** Contributed to C#/.NET systems and an ASP.NET-to-.NET Core modernization that improved screen-load performance by **70%** and reduced infrastructure costs by **30%**.
- **GoodNotes:** Built MCP-based workflow tooling connecting Jira-backed work, local Kanban state, Git branches, and reviewed pull-request workflows, reducing task-preparation and triage effort by **40%**.

## Featured Open-Source Projects

### [enterprise-rag-platform](https://github.com/sivadkoneru/enterprise-rag-platform)

.NET platform for document ingestion and grounded, cited question answering. Demonstrates dependency-injected parser, chunking, document-store, vector-store, and LLM-provider boundaries; async ingestion; API and CLI interfaces; S3 and Azure Blob sources; Elasticsearch retrieval; and local Docker services.

Includes a deterministic **50-question retrieval evaluation** that compares four chunking strategies on the same corpus. Evaluation results are committed, regression-tested, and regenerated in CI.

### [market-intelligence-platform](https://github.com/sivadkoneru/market-intelligence-platform)

Multi-service Python reference platform for ingesting market and news events, streaming them through Azure Service Bus, calculating indicators, generating RAG-driven explanations, and serving alerts through FastAPI REST and WebSocket APIs.

Demonstrates asynchronous services, Apache Druid, Elasticsearch kNN, PostgreSQL, Redis, Docker Compose, deterministic offline mocks, benchmark tooling, and automated lint, type-check, test, and container-build gates. Educational project only; not for trading or financial advice.

### [atlassian-hermes-connector](https://github.com/sivadkoneru/atlassian-hermes-connector)

Python Hermes plugin for Jira-backed Kanban work, repository resolution, local Git workflows, and reviewed GitHub or Bitbucket pull-request planning.

Demonstrates provider-neutral Atlassian MCP tool discovery, deterministic Jira-status mapping, blocker handling, explainable repository selection, branch naming, and explicit review gates before pull-request planning. The official Atlassian MCP server and credentials are configured externally.

## Public Engineering Evidence

- Automated unit, integration, and evaluation tests in `enterprise-rag-platform`, with CI validation of build output, tests, and published evaluation results.
- Ruff, Mypy, Pytest, Docker Compose validation, and Docker image-build checks in `market-intelligence-platform` CI.
- Automated workflow tests in `atlassian-hermes-connector` covering MCP discovery, Jira status mapping, repository resolution, branch creation, and PR guardrails.

## Technical Focus

**AI systems:** RAG architecture · retrieval evaluation · LLM orchestration · MCP/tool integration · guardrails

**Backend:** Python · FastAPI · C# · .NET · ASP.NET Core · REST APIs · distributed systems · TypeScript · React

**Data and delivery:** PostgreSQL · Redis · Elasticsearch · Apache Druid · Azure · Docker · CI/CD · observability

[LinkedIn](https://linkedin.com/in/sdkoneru) · [Portfolio](https://sdkoneru.com) · [Email](mailto:sivadattak7@gmail.com)