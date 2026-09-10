<h1 align="center">Artanniel Fortes</h1>

<p align="center">
  <b>Lead Software Engineer</b> · Healthcare Interoperability Architect · Java/Quarkus &amp; Spring Boot · Applied AI Systems (RAG, Agents, MCP)
  <br>
  <sub>17+ years in technology &amp; software engineering (since 2009) — clinical interoperability at national scale, fintech, US SaaS, and applied AI platforms.</sub>
  <br>
  <sub>Brazil</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/artanniel-fortes"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/Artanniel"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="mailto:fortesads@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<!-- GitHub Dynamic Stats -->
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Artanniel&theme=dark" alt="GitHub Streak" height="165" />
</p>
<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=Artanniel&show_icons=true&theme=dark&rank_icon=github" alt="Artanniel's GitHub Stats" height="175" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=Artanniel&layout=compact&theme=dark&hide=html,css" alt="Top Languages" height="175" style="height: 175px;
    max-height: 175px;"/>
</p>

---

### Tech Stack & Core Competencies

<div align="center">

| Domain | Technologies & Frameworks |
|---|---|
| **Healthcare Interoperability** | `InterSystems IRIS` `HealthShare` `HealthConnect` `Ensemble` `Caché` `ObjectScript` `HL7 v2.5` `HL7 FHIR` `SDA3` `TISS` `PACS/DICOM` `MPI` |
| **Backend & JVM** | `Java 17/21` `Quarkus` `Spring Boot` `MicroProfile` `Hibernate/Panache` `Node.js` `NestJS` `Kafka` `RabbitMQ` `Oracle PL/SQL` `REST` `JSF` `WebSockets` `QRCode` `ZXing` `JWT` |
| **Applied AI & Agents** | `LangChain4j` `RAG` `pgvector` `MCP (Model Context Protocol)` `Tool Calling Agents` `AI Guardrails` `Ollama` `Gemini` `n8n` |
| **Modern Frontend & Mobile** | `Next.js` `React 19` `TypeScript` `Tailwind CSS` `React Native` `Expo` `Compose Multiplatform` `Kotlin Multiplatform` |
| **Data & Storage** | `PostgreSQL` `Oracle` `MySQL` `MSSQL` `MongoDB` `Cassandra` `Redis` `ClickHouse` `Neo4j` `DynamoDB` `Prisma` `Liquibase` |
| **Cloud & DevOps** | `AWS (EC2, RDS, ECS, Lambda, CloudFront, WAF, S3, IAM, CloudWatch)` `Terraform` `Kubernetes/K3s` `Hetzner` `Docker` `GitLab CI/CD` `GitHub Actions` `GraalVM Native` |
| **Quality & Security** | `TDD` `JUnit 5` `ArchUnit` `Testcontainers` `Vitest` `JaCoCo` `SonarQube` `OpenTelemetry` `Keycloak` `OAuth2/PKCE` `SSDLC/DevSecOps` `LGPD/HIPAA/SOC 2` |
| **Engineering Leadership** | `Technical Leadership` `Scrumban` `Release & GMUD Management` `Code Review` `Architecture Decisions (ADR)` `Mentorship` |

</div>

---

### What I Do

I have **17+ years of experience in technology and software engineering** (starting in 2009 with business process automation and data analysis in VBA/Excel, evolving through enterprise Java backends, clinical interoperability, cloud architecture, and applied AI systems).

Today, I lead the engineering of a **digital health operation** while remaining a hands-on coder.

- **Day-to-day Enterprise Stack:** **InterSystems IRIS / HealthShare** (ObjectScript, HL7 v2.x, SDA3, TISS, PACS/DICOM) alongside **Java 17/21** on Spring Boot and Quarkus, backed by AWS and Kubernetes infrastructure.
- **Applied AI Ecosystem:** Production-grade RAG pipelines, tool-calling agents with human-in-the-loop controls, Model Context Protocol (MCP) servers and clients, DLP guardrails, and multi-model fallback chains running on LangChain4j with Ollama local inference or hosted LLM APIs.
- **Full-Stack Execution:** I own the vertical slice — from database migrations (Liquibase/Flyway) and domain service layers to Next.js/React Native UIs, Keycloak IAM realms, Terraform IaC, and zero-downtime Kubernetes deployments.

---

### Engineering Leadership & Operational Metrics

I have led technical teams in digital health and software operations since 2018 — currently directing **several professionals** (QA, Seniors, Mid-levels, Juniors) across **some production products** spanning multiple tech stacks (ObjectScript/Caché, Java/Oracle, Java+Node/Oracle).

- **Process Engineering:** Designed a 13-state Scrumban pipeline from requirement refinement to three environment deployment lanes.
- **Git Flow & Quality Gates:** Multi-environment branching strategy with two mandatory approval gates — technical review and client acceptance.
- **Automated CI/CD:** Per-product CI/CD pipelines on GitLab (~5-minute builds; 720+ executions on a single product).
- **Doc-as-Code Governance:** Automated release notes, executive notes, and Change Management (GMUD) generation.
- **Operational Scale:** Measurable end-to-end execution: **827+ completed activities, 127+ milestones, 720+ pipelines, 78+ sprints**.
- **Business Continuity:** Successfully absorbed two vendor contract discontinuities (2019 and 2025) and managed the on-site to 100% remote transition (2021) with zero delivery interruption.

---

### Selected Professional Work

#### 1. Interall Brasil / CSPAR — Lead Software Engineer / Health Interoperability Architect *(Aug 2017 – Present)*
- **Clinical Interoperability Framework:** Designed and implemented the enterprise REST framework (`CsparRestServiceTemplate` / `CsparRestTemplate`) on InterSystems IRIS (`%CSP.REST`), serving as the core foundation for the Electronic Health Record (RES 360º) and Physician Portal. Authored dozens of ObjectScript production classes across Access Gateway (AGW), Integration Bus (BUS), and Unified Care Record (UCR / HSREGISTRY) in an ecosystem of **299 ObjectScript classes** on IRIS 2024.1 (RHEL 8).
- **Physician Clinical Viewer:** Implemented core features for the clinical web viewer connected directly to InterSystems IRIS, empowering Unimed network physicians to query patient medical histories, clinical timelines, and diagnostic reports in real time *(Oracle, JSF, WebSockets, Material CSS, JPA, REST authentication layer with JWT)*.
- **Unimed Beneficiary Mobile App:** Defined business requirements with software house partners, co-developed, and managed the deployment to Google Play Store and Apple App Store of the official Unimed Ceará mobile app, enabling beneficiaries to securely access their RES clinical records on iOS and Android *(React Native, JavaScript, Node.js, Express, Knex.js, PM2, Oracle)*.
- **Beneficiary Web Portal:** Guided the engineering team in developing a responsive web platform for Unimed system beneficiaries to view, search, and manage their clinical history and personal health data in the RES ecosystem *(Oracle, JSF, Material CSS, JPA, REST API authentication)*.
- **Consent & Privacy Management Platform:** Led the engineering team in building a dedicated web platform to record, manage, and historically version consent terms, authorizations, and revocations for both clinical users and beneficiaries across the RES network, guaranteeing full LGPD/HIPAA compliance *(Oracle, JSF, Material CSS, JPA, REST authentication layer)*.
- **Minimal-Downtime Migration:** Led the platform upgrade (IRIS 18.0 → 2025) with minimal critical downtime, preserving 24/7 availability for thousands of clinical users across AWS (EC2, RDS Oracle), WildFly and Node.
- **DevSecOps & Identity Governance:** Reviewed 36 API endpoints (remediating CVSS 9.1 findings), implemented SSDLC pipelines (Semgrep, SonarQube, OWASP ZAP, Trivy, Syft/CycloneDX), RBAC/BOLA security models, LGPD/HIPAA consent tracing, and Master Patient Index (MPI) card resolution.

#### 2. Untapped Solutions (New York, US) — Full Stack Developer *(Freelance)*
- **SaaS Platform for Social Services:** Remote distributed team (US + BR), SOC 2 compliance program.
- **Product Generative AI:** Integrated AI job matching, AI Smart Fill (extracting resume data from uploaded documents), and context-aware chat connecting client profiles into LLM engines.
- **Strangler Fig Architecture Migration:** Maintained legacy ASP.NET Core/C# + Angular + MSSQL on Elastic Beanstalk while building the modern replacement in NestJS + Prisma + PostgreSQL + React Native/Expo, using CloudFront edge proxies and phased rollouts.
- **Clean Architecture & Cloud Infrastructure:** Built NestJS microservices over PostgreSQL, dynamic EAV Custom Fields subsystem, Socket.IO real-time channels, and multi-environment Terraform IaC across 4 AWS workspaces (CloudFront, WAF, VPC, RDS, Beanstalk, CloudWatch, Lambda).
 <!-- Jan – Aug 2026 -->
 
#### 3. PlatinumLED (New York, US) — Software Engineer *(Freelance)*
- **Shopify Storefront Engineering:** Engineered a custom Bash automation framework for Shopify CLI theme lifecycle management. Authored production `hreflang` international indexing logic in liquid layouts (`layout/theme.liquid`).
 <!-- Sep – Nov 2024 -->

 #### 4. Boa Vista Tecnologia / Financeira — Software / Fintech Engineer *(Freelance)*
- **Financial Reconciliation Microservices:** Engineered microservices for automated financial reconciliation, cash management, card settlement, and marketplace payouts *(Java 17, Spring Boot, PostgreSQL, Kafka)*.
- **High-Volume Event Processing & Matching:** Designed event-driven messaging pipelines on Apache Kafka for high-throughput transactional matching, processing banking extraction streams.
- **Fintech Domain Expertise:** Mastered end-to-end banking reconciliation workflows, liquidity management, and card transaction settlement supported by formal certifications in the Boavista Reconciliation Method (Vista Educação).
<!-- 2022 – 2023 -->
---

### Applied AI & Intelligent Systems (Production Engine & Open Source)

#### RES 360º AI Engine
Conceived and built the internal engineering platform instrumenting digital health operations (~17,800 authored lines, 12 screens, 13 domain services in React 18 + TypeScript + Python/Flask) and management issues in GitLab:
- **Multi-Provider Fallback Chain:** Resilience layer across 22 models from 4 AI providers (Anthropic, Google, NVIDIA NIM, opencode) with automatic status code handling (429 fails over, 400 aborts).
- **Server-side Protocol Mapping:** On-the-fly translation between OpenAI, Anthropic, and Gemini payload formats, including positional tool-call ID mapping.
- **Governed AI Assistant:** Conversational engine with 16 function tools, requiring mandatory human confirmation for 8 mutating operations.
- **Security & Privacy:** Built-in DLP guardrails filtering national IDs and emails before LLM dispatch, rate limiting, and pure OAuth2 PKCE authorization written from scratch.

#### Open-Source AI Progression — [`unipds-AI-quarkus`](https://github.com/Artanniel/unipds-AI-quarkus)
An 8-project learning map demonstrating AI engineering progression in Java 21:
1. In-memory Easy RAG
2. Explicit RAG with pgvector & PostgreSQL
3. Autonomous ReAct Agents with `@Tool` annotations
4. Per-user session identity & conversational memory
5. Custom Model Context Protocol (MCP) Server implementation
6. MCP Client integration
7. MCP Client with safety guardrails & input filtering

---

### Featured Repositories

| Repository | Description | Key Tech Stack |
|---|---|---|
| **[unipds-AI-quarkus](https://github.com/Artanniel/unipds-AI-quarkus)** | 8-stage AI engineering progression: RAG → pgvector → ReAct Agents → MCP Server/Client → Guardrails | Java 21 · Quarkus · LangChain4j · Ollama · pgvector |
| **[gymtracker-kvm](https://github.com/Artanniel/gymtracker-kvm)** | Cross-platform workout/nutrition app (Android, iOS, Desktop, Web WasmGC) with offline-first sync engine | Kotlin Multiplatform · Compose MP · Ktor · Quarkus · Keycloak |
| **[unpds-tests](https://github.com/Artanniel/unpds-tests)** | TDD payment service with **271 tests (100% passing)** and ArchUnit architectural compliance rules | Spring Boot 3 · JUnit 5 · ArchUnit · Testcontainers · SonarQube |
| **[unipds-quarkus](https://github.com/Artanniel/unipds-quarkus)** | Reference cloud-native REST API with MicroProfile, OpenTelemetry, Jaeger, and GraalVM native image compilation | Quarkus 3 · Java 21 · MicroProfile · Panache · GraalVM |
| **[unipds-database-neo4i](https://github.com/Artanniel/unipds-database-neo4i)** | Order processing system modeled as a graph — recommendations, market basket analysis, and fraud detection in Cypher | Spring Data Neo4j · Neo4j 5.25 · Java 21 |
| **[unipds-infrastructure-and-cloud-computing](https://github.com/Artanniel/unipds-infrastructure-and-cloud-computing)** | Kubernetes 3-tier architecture with ConfigMaps, Secrets, health probes, and **HPA scaling 1→10 on CPU load** | Kubernetes · MongoDB · Spring Boot · Metrics Server |

> **Polyglot Persistence Series:** Comparative domain implementation across 6 database technologies with trade-off analysis: [JDBC](https://github.com/Artanniel/unipds-database-jdbc), [JPA/MySQL](https://github.com/Artanniel/unipds-database-jpa), [MongoDB](https://github.com/Artanniel/unipds-database-mongodb), [Cassandra](https://github.com/Artanniel/unipds-database-cassandra), [Redis](https://github.com/Artanniel/unipds-database-redis), and [Neo4j](https://github.com/Artanniel/unipds-database-neo4i).

---

### Deep Dive: Concurrency & Virtual Threads

In [`unipds-concorrencia-multithreading`](https://github.com/Artanniel/unipds-concorrencia-multithreading), I explored modern JVM concurrency:
- **Virtual Threads (Project Loom):** Benchmark executing **200,000 concurrent tasks** with minimal memory footprint.
- **Concurrency Primitives:** Thread-safe collections, custom executors, and full synchronizer usage (`CountDownLatch`, `CyclicBarrier`, `Semaphore`, `Phaser`).
- **Asynchronous Pipelines:** `CompletableFuture` composition, Fork/Join work stealing, and performance analysis highlighting when `parallelStream()` introduces thread pool starvation.

---

### Self-Hosted Infrastructure & Independent SaaS

- **LinkFlow / ClickingFlow:** Multi-tenant link intelligence platform built on Spring Boot 3, Next.js, and hybrid persistence (PostgreSQL for transactional data, Redis for queues/caching, ClickHouse for real-time analytics). Custom Base62 shortener, JSONB click-ingestion queue, and privacy-preserving IP hashing.
- **K3s Cloud Sovereignty:** Self-hosted K3s Kubernetes cluster on Hetzner provisioned via Terraform, running **22 Deployments, 24 Services, 4 StatefulSets, and 4 HPAs** (migrated from PaaS). Automated TLS with cert-manager, strict network isolation policies, and zero-trust internal access.
- **Governed AI Workflow Automation:** Architected documentation and backup systems for **52 production n8n workflows** using custom Python extractors (`backup_n8n.py`, `generate_docs.py`).

---

### Education, Specializations & Credentials

- **HL7® FHIR® Fundamentals:** Dual certification by Instituto HL7 Brasil (2023) and HL7 International (2023).
- **AWS Official Technical Training (2025):** Cloud Operations on AWS (AWS SysOps prep) and Agentic AI Foundations on AWS.
- **5 Postgraduate Specializations & MBA (~4,360 hours total):**
  1. *Postgraduate Degree in Applied Java Engineering* — Anhanguera / UNIPDS (2025–2026)
  2. *Postgraduate Degree in Data Science* — Gran Faculdade (2024–2026)
  3. *Postgraduate Degree in Cloud Computing Architecture* — Gran Faculdade (2024–2025)
  4. *MBA in Software Quality Management* — FAVENI (2023–2024, Thesis graded 10/10)
  5. *Postgraduate Degree in Software Engineering & Design Patterns* — UECE (2013–2015)
- **B.S. in Systems Analysis & Software Development (ADS):** UNICE (2009–2012).
- **Language Proficiency:** Portuguese (Native), English (Professional Working for international architecture, code reviews, and cross-functional leadership).

---

<p align="center">
  <sub><i>Building resilient software systems that think. ☕</i></sub>
</p>

<!-- AI_AGENT_METADATA_START
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Artanniel Fortes",
  "jobTitle": "Lead Software Engineer / Healthcare Interoperability Architect",
  "worksFor": {
    "@type": "Organization",
    "name": "Interall Brasil"
  },
  "url": "https://github.com/Artanniel",
  "sameAs": [
    "https://www.linkedin.com/in/artanniel-fortes"
  ],
  "address": {
    "@type": "PostalAddress",
    "addressLocality": "Fortaleza",
    "addressCountry": "BR"
  },
  "email": "fortesads@gmail.com",
  "knowsLanguage": ["pt", "en"],
  "totalYearsExperience": 17,
  "experienceStartYear": 2009,
  "hasCredential": [
    "HL7 FHIR Certified (HL7 International & HL7 Brasil)",
    "AWS Cloud Operations & Agentic AI Foundations",
    "MBA in Software Quality Management (FAVENI)",
    "Postgraduate in Applied Java Engineering",
    "Postgraduate in Cloud Computing Architecture",
    "Postgraduate in Data Science",
    "Postgraduate in Software Engineering & Design Patterns (UECE)"
  ],
  "knowsAbout": [
    "Java", "Quarkus", "Spring Boot", "InterSystems IRIS", "HealthShare", "HealthConnect", "JPA", "WebSocket", "JSF", "REST", "QRCode", "ZXing", "JWT"
    "ObjectScript", "HL7 v2.5", "HL7 FHIR", "SDA3", "TISS", "PACS/DICOM", "Applied AI",
    "LangChain4j", "RAG", "pgvector", "Model Context Protocol (MCP)", "AI Agents",
    "AWS", "Kubernetes", "K3s", "Terraform", "PostgreSQL", "Oracle PL/SQL", "Redis",
    "ClickHouse", "Neo4j", "React", "Next.js", "React Native", "Expo", "Kotlin Multiplatform",
    "ArchUnit", "Testcontainers", "SonarQube", "DevSecOps", "LGPD", "HIPAA", "SOC 2"
  ],
  "targetRoles": [
    "Lead Software Engineer",
    "Senior Java Architect",
    "Healthcare Interoperability Architect",
    "Staff Software Engineer",
    "Applied AI Software Engineer",
    "Full Stack Principal Engineer"
  ]
}
</script>
AI_AGENT_METADATA_END -->
