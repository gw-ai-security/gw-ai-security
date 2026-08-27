# Georg Wiesmüller

**Business Informatics · Data Engineering · Data Platforms · Data Quality & Governance-aware Engineering**

I am completing a **BSc in Business Informatics at FH Technikum Wien** and build reproducible data and integration systems with an emphasis on **data quality, reliability, traceability, explicit system boundaries, and clear engineering evidence**.

My technical direction is **Data Engineering → Data/ML Platform Engineering**, with security and governance treated as engineering constraints that strengthen implementation rather than replace it.

**Open to internship, working-student and junior opportunities in Austria across Data Engineering, Data Platforms, Data Quality, Automation/Integration, and technical Data/AI Governance.**

## Current Engineering Evidence

| Area | What I can show in the repositories |
|---|---|
| **SQL & Data Warehousing** | SQL Server, T-SQL, Bronze/Silver/Gold, batch loading, cleansing, integration, dimensional modeling, star schemas, data quality checks, lineage and data catalog documentation |
| **Batch & Streaming Data Engineering** | Python, PostgreSQL, Kafka, Spark Structured Streaming, Parquet, REST ingestion, MongoDB, deterministic validation and deduplication |
| **Data Quality & Modeling** | explicit schemas, grain, identifiers, source precedence, cardinality checks, fact/dimension design, data contracts and curated reporting boundaries |
| **Automation & Integration** | FastAPI, REST APIs, webhooks, n8n, Microsoft Power Automate, RabbitMQ, HMAC verification, idempotency and replay protection |
| **Backend & Distributed Systems** | Java, Spring Boot, PostgreSQL, Flyway, Docker Compose, asynchronous messaging, service boundaries and persistence ownership |
| **Reporting & Governance** | Power BI, DAX, lineage, traceability, auditability, evidence-oriented workflows and controlled human-in-the-loop AI review |
| **Engineering Practice** | Git/GitHub, automated tests, CI, architecture documentation, reproducible environments, explicit limitations and separation of implemented vs. planned capability |

## Featured Engineering Projects

### 1. [SQL Data Engineering Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio)

A connected SQL Server portfolio track covering **data warehousing, exploratory data analysis, and advanced SQL analytics**. The first project — the complete data warehouse — is implemented and documented; the analytics projects remain explicitly marked as planned until completed.

**Completed SQL Data Warehouse**

- consolidates CRM and ERP CSV sources into a SQL Server warehouse
- Bronze layer with six source-aligned tables and a batch load procedure
- Silver layer with cleansing, standardization, data-type correction and integration-key preparation
- Gold analytical views for `dim_customers`, `dim_products`, and `fact_sales`
- dimensional model with documented grain and source precedence
- separate Bronze, Silver and Gold validation scripts
- documented source-to-Gold lineage, integration models and architecture decisions
- column-level Gold data catalog and engineering learning journal
- validated snapshot: **18,484 customers, 295 current products, 60,398 sales lines**

The project is intentionally explicit about its learning-project constraints: full-refresh loading, view-based Gold, snapshot-scoped surrogate keys, no orchestration/CDC/SCD infrastructure, and no claim of production readiness.

The scenario and learning sequence are based on **Data with Baraa's SQL project materials**; the repository separates that baseline from my version-controlled implementation, validation, documentation and targeted refinements.

---

### 2. [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects)

Broader Data Engineering portfolio covering implemented batch, streaming, relational, NoSQL and analytical pipelines, plus an actively developed AWS-oriented platform project.

**Euro Air Quality Pipeline — strongest implemented end-to-end pipeline evidence**

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

### 3. [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)

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

### 4. [Energy Community — Event-Driven Distributed System](https://github.com/gw-ai-security/energy-community)

Academic distributed-systems project demonstrating backend and platform-engineering fundamentals beyond Python-only data pipelines.

- **six independently startable applications**
- Java 25 and Spring Boot 4.0.3
- RabbitMQ asynchronous JSON messaging
- PostgreSQL 17, Spring Data JPA and Flyway migrations
- dedicated processing-service ownership of business calculations
- read-only REST API boundary and JavaFX client
- Open-Meteo integration with defined fallback behavior
- Docker Compose infrastructure and documented end-to-end verification

This repository provides evidence for **event-driven architecture, service boundaries, asynchronous processing, persistence ownership, API design, and integration resilience**.

## Selected Additional Work

- [AI Process Automation](https://github.com/gw-ai-security/ai-process-automation) — FastAPI/PostgreSQL integration and workflow projects with signed webhooks, idempotency, replay protection, audit logging, persisted workflow state and bounded AI-assisted processing.
- [Secure AI Fraud Detection Pipeline](https://github.com/gw-ai-security/secure-ai-fraud-detection-pipeline) — synthetic-data ML engineering project with feature engineering, model evaluation, API scoring, STRIDE threat modeling and governance documentation.
- [Healthcare AI Governance Assessment](https://github.com/gw-ai-security/healthcare-ai-governance-assessment) — Streamlit educational governance prototype with role-specific views and lightweight interaction logging.
- [Agentic AI Projects](https://github.com/gw-ai-security/agentic-ai-projects) — bounded AI prototypes focused on controlled tool use, structured outputs, explainability and security-aware design.
- [AWS Data Engineering Floci Lab](https://github.com/gw-ai-security/aws-data-engineering-floci-lab) — local AWS-compatible hands-on lab with explicit separation between emulated behavior and capabilities requiring validation in real AWS.

## Current Learning Direction

My current build sequence is deliberately cumulative:

```text
SQL & Data Warehousing
        ↓
Advanced SQL Analytics
        ↓
Python Data Engineering
        ↓
Data Modeling & Pipeline Engineering
        ↓
AWS / Data Platform Engineering
        ↓
Production Thinking: testing · observability · reliability · security · governance
```

The next work in the SQL portfolio is **Exploratory Data Analysis**, followed by **Advanced Data Analytics**. Until those projects are implemented and validated, they remain marked as planned.

## Technical Focus

```text
SQL & Data Warehousing
SQL Server · T-SQL · ETL · Bronze/Silver/Gold · dimensional modeling · star schemas · data quality · lineage

Data Engineering
Python · PostgreSQL · MongoDB · Kafka · Spark Structured Streaming · Parquet · batch/streaming pipelines

Data Architecture & Quality
schemas · grain · source precedence · data contracts · lineage · deterministic DQ · analytical boundaries

APIs & Automation
FastAPI · REST · webhooks · n8n · Power Automate · RabbitMQ · HMAC · idempotency · replay protection

Backend & Infrastructure
Java · Spring Boot · PostgreSQL · Flyway · Docker Compose · event-driven systems

Analytics & Governance
Power BI · DAX · auditability · evidence workflows · controlled AI review · human-in-the-loop governance

Engineering Practice
Git/GitHub · automated testing · CI · architecture documentation · reproducible environments · explicit limitations
```

## How I Build

Across the portfolio I use a consistent engineering standard:

1. define the business question, data grain, ownership and trust boundaries before implementation,
2. preserve source facts before transformation and avoid silent semantic repair,
3. make Data Quality explicit and independently observable,
4. validate joins, cardinality, row preservation and failure paths rather than only happy paths,
5. keep implemented capability, simulated integration, planned architecture and production experience clearly separated,
6. document architecture decisions, lineage, limitations and handover paths so another engineer can review the system without reverse engineering it.

## Background

My earlier professional experience spans **education and technical live-production environments**. It contributes practical strengths in structured communication, requirements translation, documentation, handover, troubleshooting, and reliability under time pressure.

I use GitHub as **engineering evidence**, not as a course-completion log. The strongest repositories show what is implemented, how it is validated, what remains planned, and where the technical limits are.

---

[LinkedIn](https://www.linkedin.com/in/georg-w-8a7b11374/) · [SQL Data Engineering Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio) · [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects) · [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)
