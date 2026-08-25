# Georg Wiesmüller

**Business Informatics · Data Engineering · Data/ML Platforms · Automation & Security-aware Systems**

I am completing a **BSc in Business Informatics at FH Technikum Wien** and build reproducible data and automation systems with an emphasis on **data quality, reliability, traceability, clear system boundaries, and governance**.

My technical direction is **Data Engineering → Data/ML Platform Engineering**, with security and governance treated as engineering constraints rather than substitutes for implementation evidence.

**Open to internship, working-student and junior opportunities in Austria across Data Engineering, Data Platforms, Data Quality, Automation/Integration, and technical Data/AI Governance.**

## Snapshot

| Area | Current engineering evidence |
|---|---|
| **Data Engineering** | Python, SQL, PostgreSQL, MongoDB, Kafka, Spark Structured Streaming, Parquet, batch/streaming pipelines, Bronze/Silver/Gold architecture |
| **Data Quality & Modeling** | explicit schemas, deterministic validation, deduplication, grain, identifiers, data contracts, curated reporting boundaries |
| **Automation & Integration** | FastAPI, REST APIs, webhooks, n8n, Microsoft Power Automate, RabbitMQ, HMAC verification, idempotency, replay protection |
| **Systems Engineering** | Java, Spring Boot, PostgreSQL, Flyway, Docker Compose, event-driven processing, service boundaries, persistence ownership |
| **Reporting & Governance** | Power BI, DAX, lineage, traceability, auditability, evidence-oriented workflows, human-in-the-loop governance |
| **Engineering Practice** | Git/GitHub, pull-request workflows, automated tests, CI, architecture documentation, explicit scope and production-gap documentation |

## Featured Projects

### [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects)

My primary Data Engineering portfolio, covering implemented batch, streaming, relational, NoSQL, and analytical pipelines plus an actively developed AWS-oriented platform project.

**Euro Air Quality Pipeline — strongest implemented pipeline evidence**

- multi-source batch and streaming ingestion
- Python, PostgreSQL, Apache Kafka and Spark Structured Streaming
- Bronze / Silver / Gold architecture with Apache Parquet
- explicit schemas, deterministic event IDs, deduplication and Data Quality checks
- reproducible local infrastructure with Docker Compose

**Weather Air Vienna**

- REST API ingestion from Open-Meteo
- MongoDB raw persistence
- cleaning, staging, deduplication and daily aggregation
- Python Map / Shuffle / Reduce implementation
- reproducible Docker Compose environment

**CloudOps Insight Lake — active development**

- AWS-oriented serverless data-platform architecture
- explicit source contracts, data grain and canonical resource identity
- planned audit/DQ model, observability, IAM least privilege and negative permission tests
- implementation status is kept separate from planned AWS architecture

---

### [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)

Completed **11-phase portfolio proof of concept** for recurring cybersecurity-control evidence, follow-up, reporting, controlled AI review, and read-only integration.

- Microsoft Forms and Power Automate evidence-intake and reminder workflows
- deterministic Python ETL with **10 explicit Data Quality rules**
- controlled operational snapshot → curated reporting boundary
- source-controlled Power BI **PBIP / PBIR / TMDL** project
- **21 version-controlled DAX measures** across three primary report pages
- minimized AI-review queue with JSON Schema validation and mandatory human Governance Review
- local read-only FastAPI projection with two business GET endpoints
- reproducible locked Python environment and GitHub Actions CI
- **84 automated tests passing** in the final accepted baseline
- explicit security boundaries, production-gap assessment, evidence index and technical handover

The project deliberately keeps **evidence presence, compliance, timeliness, workflow state, Data Quality, AI advice, and REST exposure** as separate concepts.

---

### [Energy Community — Event-Driven Distributed System](https://github.com/gw-ai-security/energy-community)

Academic distributed-systems project demonstrating broader backend and platform-engineering fundamentals.

- **six independently startable applications**
- Java 25 and Spring Boot 4.0.3
- RabbitMQ asynchronous JSON messaging
- PostgreSQL 17, Spring Data JPA and Flyway migrations
- dedicated processing-service ownership of business calculations
- read-only REST API boundary and JavaFX client
- Open-Meteo integration with defined fallback behavior
- Docker Compose infrastructure and documented end-to-end verification

This repository provides evidence for **event-driven architecture, service boundaries, asynchronous processing, persistence ownership, API design, and integration resilience** beyond Python-only data pipelines.

---

### [AI Process Automation](https://github.com/gw-ai-security/ai-process-automation)

Implemented local automation and integration projects focused on APIs, webhooks, persistence, auditability, and bounded AI-assisted processing.

**REST API Integration Hub**

- FastAPI, PostgreSQL, Docker Compose and n8n
- signed webhook intake with HMAC verification
- idempotency and replay protection
- validation, transformation, audit logging and DLQ-style error handling
- mocked downstream CRM / Jira / Confluence integrations

**AI Workflow Automation Engine**

- webhook-driven operational intake
- structured LLM extraction with deterministic mock mode and adapter mode
- persisted workflow state, events, errors and metrics in PostgreSQL
- n8n branching with mock Jira / Slack targets
- bounded AI assistance rather than autonomous authority

External systems are simulated and are not presented as production deployments.

## Technical Focus

```text
Data Engineering
Python · SQL · PostgreSQL · MongoDB · Kafka · Spark Structured Streaming · Parquet

Data Architecture & Quality
ETL · batch/streaming · Bronze/Silver/Gold · schemas · grain · data contracts · lineage · deterministic DQ

APIs & Automation
FastAPI · REST · webhooks · n8n · Power Automate · RabbitMQ · HMAC · idempotency · replay protection

Backend & Infrastructure
Java · Spring Boot · PostgreSQL · Flyway · Docker Compose · event-driven systems

Analytics & Governance
Power BI · DAX · auditability · evidence workflows · controlled AI review · human-in-the-loop governance

Engineering Practice
Git/GitHub · automated testing · CI · architecture documentation · reproducible environments · explicit limitations
```

## Selected Additional Work

- [Secure AI Fraud Detection Pipeline](https://github.com/gw-ai-security/secure-ai-fraud-detection-pipeline) — synthetic-data ML engineering project with feature engineering, model evaluation, API scoring, STRIDE threat modeling, and governance documentation.
- [Healthcare AI Governance Assessment](https://github.com/gw-ai-security/healthcare-ai-governance-assessment) — Streamlit educational governance prototype with CISO, DPO, SOC Analyst and Auditor views plus lightweight interaction logging.
- [Agentic AI Projects](https://github.com/gw-ai-security/agentic-ai-projects) — bounded AI prototypes focused on controlled tool use, structured outputs, explainability and security-aware design; the Mini Incident Analysis Agent is implemented.
- [AWS Data Engineering Floci Lab](https://github.com/gw-ai-security/aws-data-engineering-floci-lab) — local AWS-compatible hands-on lab with explicit separation between emulated AWS behavior and capabilities that require validation in real AWS.

## How I Build

Across the portfolio I use a consistent engineering standard:

1. define the business question, data grain, ownership and trust boundaries before implementation,
2. preserve raw facts before transformation and avoid silent semantic repair,
3. make Data Quality deterministic and independently observable,
4. test failure paths and integration boundaries rather than only happy paths,
5. keep implemented capability, simulated integration, planned architecture and production experience clearly separated,
6. document architecture decisions, limitations, security assumptions and handover paths so another engineer can review the system without reverse engineering it.

## Background

My earlier professional experience spans **education and technical live-production environments**. It contributes practical strengths in structured communication, requirements translation, documentation, handover, troubleshooting, and reliability under time pressure.

I use GitHub as **engineering evidence**, not as a course-completion log. The strongest repositories show what is implemented, how it is verified, what remains planned, and where the technical limits are.

---

[LinkedIn](https://www.linkedin.com/in/georg-w-8a7b11374/) · [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects) · [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)
