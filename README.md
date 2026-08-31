# Georg Wiesmüller

**Business Informatics · Data Engineering · Data Platforms · Data Quality & Governance-aware Engineering**

I am completing a **BSc in Business Informatics at FH Technikum Wien** and build reproducible data and integration systems with an emphasis on **data quality, reliability, traceability, explicit system boundaries, and honest engineering evidence**.

My technical direction is **Data Engineering → Data/ML Platform Engineering**. Security and governance are treated as engineering constraints that strengthen implementation rather than replace it.

**Open to internship, working-student and junior opportunities in Austria across Data Engineering, Data Platforms, Data Quality, Automation/Integration, and technical Data/AI Governance.**

## Featured Engineering Evidence

### 1. [SQL Data Engineering Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio)

**SQL Server · T-SQL · Data Warehousing · Dimensional Modeling · Data Quality · Advanced SQL Analytics**

A completed end-to-end SQL portfolio that moves CRM and ERP source data through a validated Bronze/Silver/Gold warehouse into exploratory analysis, advanced analytics and reusable reporting views.

**Implemented evidence:**

- CRM + ERP CSV ingestion into a Bronze/Silver/Gold SQL Server architecture
- six Bronze source-aligned tables and batch loading
- Silver cleansing, standardization and integration-key preparation
- Gold `dim_customers`, `dim_products` and `fact_sales` analytical views
- explicit grain, source precedence, star-schema modeling, lineage and column-level data catalog
- Bronze, Silver and Gold Data Quality validation
- six-step Exploratory Data Analysis workflow across metadata, dimensions, dates, measures, magnitude and ranking
- change-over-time, cumulative, performance and part-to-whole analysis
- CTEs, window functions and `LAG`-based historical comparison
- customer and product segmentation
- reusable `gold.report_customers` and `gold.report_products` views
- report-grain and fact-reconciliation validation
- validated warehouse snapshot: **18,484 customers · 295 current products · 60,398 sales lines**

The repository explicitly documents learning-project constraints instead of presenting the implementation as production experience.

→ **[Review the SQL portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio)**

---

### 2. [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects)

**Python · Kafka · Spark Structured Streaming · PostgreSQL · MongoDB · Parquet · Docker**

The strongest implemented end-to-end pipeline is the **Euro Air Quality Pipeline**:

```text
Batch sources ───────────────┐
REST API → Kafka → Spark ────┼─> Bronze → Silver → Gold → Analysis
Metadata source ─────────────┘                 ↓
                                         Data Quality
```

It demonstrates multi-source batch and streaming ingestion, explicit schemas, deterministic event IDs, deduplication, Data Quality checks, Parquet persistence and reproducible local infrastructure.

The same repository also contains **Weather Air Vienna** and the actively developed **CloudOps Insight Lake**, with planned AWS architecture kept clearly separate from implemented capability.

→ **[Review the Data Engineering portfolio](https://github.com/gw-ai-security/data-engineering-projects)**

---

### 3. [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)

**Python · Power Automate · Power BI · FastAPI · Data Quality · Controlled AI Review · CI**

A completed 11-phase proof of concept for recurring cybersecurity-control evidence, follow-up, reporting and controlled AI-assisted review.

**Engineering evidence:**

- deterministic Python pipeline with **10 explicit Data Quality rules**
- controlled operational snapshot → curated reporting boundary
- Power BI PBIP/PBIR/TMDL project with **21 DAX measures**
- minimized AI review queue with JSON Schema validation and mandatory human review
- local read-only FastAPI projection
- reproducible locked Python environment and GitHub Actions CI
- **84 automated tests passing** in the final accepted baseline
- explicit Security Considerations and PoC-to-production gap assessment

The project keeps **evidence presence, compliance, timeliness, workflow state, Data Quality, AI advice and REST exposure** as separate concepts.

→ **[Review the Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)**

## Additional Work

- [Energy Community](https://github.com/gw-ai-security/energy-community) — Java/Spring Boot event-driven system with RabbitMQ, PostgreSQL, REST and Docker Compose.
- [AI Process Automation](https://github.com/gw-ai-security/ai-process-automation) — signed webhooks, idempotency, workflow persistence and bounded AI-assisted automation.
- [Secure AI Fraud Detection Pipeline](https://github.com/gw-ai-security/secure-ai-fraud-detection-pipeline) — synthetic-data ML pipeline with model serving, threat modeling and governance documentation.

## Current Build Direction

Completed foundations:

```text
SQL & Data Warehousing
        ↓
Exploratory + Advanced SQL Analytics
```

Next build focus:

```text
Python Data Engineering
        ↓
Data Modeling & Pipeline Engineering
        ↓
AWS / Data Platform Engineering
        ↓
Production Thinking
(testing · observability · reliability · security · governance)
```

## Engineering Standard

Across the portfolio I try to make the following reviewable rather than implicit:

1. **Problem and grain before implementation** — define the business question, data grain, ownership and system boundary first.
2. **Source facts before semantic repair** — preserve raw evidence and make transformations explicit.
3. **Data Quality as a separate concern** — successful execution is not proof of correct data.
4. **Failure paths and cardinality matter** — validate joins, row preservation, error handling and edge cases.
5. **Evidence levels stay separate** — implemented, simulated, planned and production experience are not interchangeable.
6. **A reviewer should not need to reverse engineer the project** — architecture, limitations, tests and handover paths are documented.

## Background

My earlier professional experience spans **education and technical live-production environments**. It contributes practical strengths in structured communication, requirements translation, documentation, handover, troubleshooting and reliability under time pressure.

---

[LinkedIn](https://www.linkedin.com/in/georg-w-8a7b11374/) · [SQL Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio) · [Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects) · [Cyber Governance Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)
