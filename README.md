### Hi, I'm Vinod Maddela 👋

**Engineering leader for data platforms, reliability and AI automation.** 20+ years building and running large-scale systems, including 12+ years at Amazon Finance Technology, where I led a 30+ engineer organisation across Data Engineering, Systems/Platform, and AI/ML & Quality. I stay hands-on: I design the architecture, review the code, and carry the pager alongside my teams.

---

#### 🏗️ What I've built at scale

> The production code below is proprietary. This profile holds public, from-scratch reference implementations of the same patterns.

- **DICES (Document Ingestion, Compliance & Extraction System).** Cloud-native re-architecture of paper-invoice ingestion for Procure-to-Pay across 70+ countries and 15+ business units, covering 40M+ documents.
  - $5.5M combined savings ($1.5M infrastructure consolidation + $3.5M re-architecture), 100+ FTE productivity gains
  - OCR/ML extraction accuracy from 45% to 88% with an actor-critic validation layer around Textract
  - Business onboarding cut from 8 weeks to under 1 week
- **Platform reliability.** Owned observability and incident management across 3,000+ servers: MTTR from 14 hrs to under 2 hrs (−85.7%), 99.9% uptime.
- **Release automation.** 425+ CI/CD pipelines on CDK/CodePipeline with automated rollback and validation gates: 50% faster deployment cycles, ~20 SDE-years of maintenance saved.
- **SDLC Scorecard.** Org-wide DORA and CI/CD metrics across 70+ services, selected for the Amazon DevCon Seattle 2025 Tools Fair.

#### 🧩 Patterns I work in

`event-driven ingestion` · `agentic root-cause analysis` · `Step Functions orchestration` · `DynamoDB optimistic concurrency` · `CDC → search/audit (Streams → OpenSearch)` · `Iceberg lakehouse / medallion layers` · `IaC-first delivery` · `SLOs, MTTR & DORA metrics` · `human-in-the-loop ML validation`

#### 🛠️ Stack

| Area | Tools |
|---|---|
| Cloud & IaC | AWS (Lambda, ECS/EKS, Step Functions, S3, DynamoDB, RDS, Glue, Redshift), CDK, CloudFormation, Terraform |
| Data | Python, SQL, PySpark, Apache Iceberg, Delta Lake, Databricks, Glue Catalog |
| Reliability | CloudWatch, Prometheus, Grafana, incident management, SLO/SLA design |
| AI / GenAI | Amazon Bedrock, Amazon Q, LangChain, RAG (FAISS/Chroma), prompt engineering |
| Languages | Python, Java, TypeScript, Node.js, SQL |
| Front end | React, TypeScript, Vite, TanStack Query |

#### 📂 On this GitHub

| Repo | What it shows |
|---|---|
| [document-ingestion-reference](https://github.com/10vin10-cmd/document-ingestion-reference) | Serverless ingestion on AWS (Lambda, Step Functions, DynamoDB optimistic concurrency, CDK) with a React + TypeScript reviewer app for human-in-the-loop review: Cognito sign-in, review claims, CloudFront hosting. 100+ tests |
| [cicd-automation](https://github.com/10vin10-cmd/cicd-automation) | CI/CD that explains its own failures: selective build and test, policy-based auto-merge, canary deploys with automatic rollback (local and ECS), and root-cause agents (Bedrock, Anthropic API or offline) that trace a failure from the service that reported it to the one that caused it, citing evidence. Evaluated on six real fault scenarios in CI |
| [ops-automation](https://github.com/10vin10-cmd/ops-automation) | Platform operations with guardrails: Terraform/CloudFormation drift remediation by policy, a DORA scorecard from GitHub, alarm-triggered runbooks with approvals, cooldowns and audit trail (CDK), and cost and hygiene cleanup |
| [ai-projects](https://github.com/10vin10-cmd/ai-projects) | Hands-on GenAI work: RAG pipelines, tool-calling agents, vector search, speech and vision apps, CI on GitHub Actions |
| ↳ [PDF tutor](https://github.com/10vin10-cmd/ai-projects/blob/main/src/ai_toolbox/gradio/pdf_tutor.py) | RAG over PDFs: OCR ingestion, FAISS, LangChain on local Ollama, Gradio UI |
| ↳ [Agent & retrieval labs](https://github.com/10vin10-cmd/ai-projects/tree/main/JL) | Tool-calling agents, LCEL, LlamaIndex advanced retrievers |

#### 🏆 Recognition

- Co-presented GenAI document-automation research at the **Amazon Machine Learning Conference (AMLC) Workshop 2024**
- Three platforms (DICES, Hybrid Automation Framework, SDLC Scorecard) at the **DevCon Seattle 2025 Tools Fair**
- **Team of the Year 2024**, Amazon (70+ country migration framework)

#### 📚 Currently

- M.Tech, IIT Patna (in progress, 2028)
- Teaching a hands-on *Data Engineering on AWS* course to final-year engineering students

---

📫 [linkedin.com/in/vinodmaddela](https://www.linkedin.com/in/vinodmaddela) · Hyderabad, India
