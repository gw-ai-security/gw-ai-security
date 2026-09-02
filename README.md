# Georg Wiesmüller

**Business Informatics · Data Engineering · Dimensional Modeling · Data Quality · Automation**

Business Informatics student at **FH Technikum Wien** building reliable data pipelines, warehouses, semantic models and automation systems. My portfolio emphasizes **clear grain, reproducible transformations, Data Quality, testing, traceability and explicit engineering boundaries**.

**Open to internship, working-student and junior opportunities in Austria across Data Engineering, Data Platforms, Analytics Engineering, Data Quality and technical automation.**

Current focus: strengthening independent **Python for Data Engineering**, then expanding into **AWS / data-platform engineering**.

## Featured Projects

| Project | Business / engineering problem | Evidence | Core stack |
|---|---|---|---|
| **[Data Engineering Portfolio](https://github.com/gw-ai-security/data-engineering-projects)** | Build reproducible batch and streaming pipelines from heterogeneous sources | Kafka + Spark streaming, Bronze/Silver/Gold, Parquet, Data Quality, API/NoSQL pipelines | Python, Kafka, Spark, PostgreSQL, MongoDB, Docker |
| **[SQL Data Engineering Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio)** | Turn fragmented CRM/ERP source data into a validated analytical warehouse | Bronze/Silver/Gold, star schema, lineage, Data Quality, EDA, advanced SQL analytics | SQL Server, T-SQL |
| **[Dimensional Data Modeling Portfolio](https://github.com/gw-ai-security/dimensional-data-modeling-portfolio)** | Redesign a deliberately broken analytical model into a trustworthy semantic layer | 6 dimensions + 6 facts, explicit grain, role-playing dimensions, reconciliation, Dynamic RLS | Power BI, Power Query, DAX, PBIP/TMDL |
| **[Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)** | Make recurring security-control evidence measurable, testable and reviewable | deterministic DQ, workflow automation, Power BI, controlled AI review, 84 automated tests | Python, Power Automate, Power BI, FastAPI, pytest |

## Selected Engineering Evidence

### Data Engineering Portfolio

The strongest pipeline combines historical batch sources and live API events into a layered analytical flow:

```text
Batch sources ───────────────┐
REST API → Kafka → Spark ────┼─> Bronze → Silver → Gold → Analysis
Metadata source ─────────────┘                 ↓
                                         Data Quality
```

Evidence includes explicit schemas, deterministic event IDs, deduplication, Spark Structured Streaming, Parquet persistence and reproducible local infrastructure.

→ **[Review the Data Engineering portfolio](https://github.com/gw-ai-security/data-engineering-projects)**

### SQL Data Engineering Portfolio

A completed SQL Server portfolio spanning **Data Warehouse → Exploratory Data Analysis → Advanced Analytics**.

Validated warehouse snapshot:

- **18,484 customers**
- **295 current products**
- **60,398 sales lines**
- Gold star-schema views with explicit grain and source precedence
- Data Quality checks across Bronze, Silver and Gold
- reusable customer/product analytical reporting views

→ **[Review the SQL portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio)**

### Dimensional Data Modeling Portfolio

A completed Power BI semantic-model project that transforms a dense, error-prone source model into a validated **Star/Galaxy Schema**.

Key evidence:

- six dimensions and six facts with explicit business grains
- shared and role-playing Date/Geo relationships
- grain-aware measures and Dynamic Row-Level Security
- reconciliation against **526,643.91 Total Sales / 80 Orders / 47 active customers**
- a merge fan-out defect diagnosed at **97 rows for 80 Orders** and corrected back to the intended **80 / 80** order grain
- PBIP/TMDL source control plus a focused Business Overview report

→ **[Review the dimensional-modeling portfolio](https://github.com/gw-ai-security/dimensional-data-modeling-portfolio)**

### Cyber Governance Automation Lab

A completed proof of concept for recurring cybersecurity-control evidence, follow-up, reporting and controlled AI-assisted review.

Key evidence:

- deterministic Python pipeline with **10 explicit Data Quality rules**
- source-controlled Power BI model with **21 DAX measures**
- minimized AI review queue with schema/correlation validation and mandatory human review
- read-only FastAPI boundary
- **84 automated tests** in the accepted baseline
- explicit PoC-to-production gap and security-boundary documentation

→ **[Review the Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)**

## Technical Focus

| Area | Current evidence |
|---|---|
| **Data Engineering** | batch/stream ingestion, ETL/ELT, layered architectures, schemas, Data Quality, Parquet |
| **SQL & Warehousing** | T-SQL, SQL Server, CTEs, window functions, stored procedures, Bronze/Silver/Gold, star schemas |
| **Data Modeling / BI** | dimensional modeling, grain, facts/dimensions, Power BI, Power Query, DAX, RLS, reconciliation |
| **Python** | applied in pipeline/automation projects; currently strengthening independent implementation, debugging and testing |
| **Streaming / Storage** | Kafka, Spark Structured Streaming, PostgreSQL, MongoDB |
| **Engineering Practices** | Git/GitHub, Docker Compose, pytest, explicit failure handling, validation, documentation |
| **Automation / Integration** | REST APIs, FastAPI, webhooks, Power Automate, workflow state and bounded AI-assisted processing |
| **Cloud direction** | AWS data-engineering and data-platform skills in active development; production cloud experience is not claimed |

## Current Build

### [Python Data Engineering Learning](https://github.com/gw-ai-security/python-data-engineering-learning)

Practice-first repository focused on independently implementing and debugging Python for Data Engineering rather than collecting syntax knowledge.

Target outcome:

```text
REST API
   ↓
Raw JSON
   ↓
Validation + Standardization
   ↓
Business Transformation
   ↓
PostgreSQL + Parquet
   ↓
Data Quality + Logging + Tests
```

The current learning path deliberately keeps cloud/orchestration complexity out until the local Python pipeline is understandable, testable and reproducible.

## Additional Work

- **[AI Process Automation](https://github.com/gw-ai-security/ai-process-automation)** — signed webhooks, HMAC validation, idempotency/replay protection, workflow persistence, n8n and bounded AI extraction.
- **[Energy Community](https://github.com/gw-ai-security/energy-community)** — Java/Spring Boot event-driven system with RabbitMQ, PostgreSQL, REST and Docker Compose.
- **[Secure AI Fraud Detection Pipeline](https://github.com/gw-ai-security/secure-ai-fraud-detection-pipeline)** — synthetic-data ML pipeline with model serving, threat modeling and governance documentation.
- **[Healthcare AI Governance Assessment](https://github.com/gw-ai-security/healthcare-ai-governance-assessment)** — evidence-oriented AI governance / GDPR assessment work.

## Engineering Principles

Across the portfolio I try to make the following reviewable rather than implicit:

1. **Business event and grain first** — define what one row means before joins, measures or relationships.
2. **Data Quality is separate from successful execution** — pipelines can run while producing wrong data.
3. **Validate failure paths, cardinality and row preservation** — a technically successful merge can still violate business semantics.
4. **Keep evidence levels honest** — implemented, simulated, planned and production experience are not interchangeable.
5. **Make projects easy to review** — architecture, tests, limitations and technical review paths should be visible without reverse engineering the repository.

## Background

My earlier professional experience spans **education and technical live-production environments**. It contributes transferable strengths in troubleshooting, structured communication, documentation, handover and reliability under time pressure.

---

[LinkedIn](https://www.linkedin.com/in/georg-w-8a7b11374/) · [Data Engineering](https://github.com/gw-ai-security/data-engineering-projects) · [SQL Portfolio](https://github.com/gw-ai-security/sql-data-engineering-portfolio) · [Dimensional Modeling](https://github.com/gw-ai-security/dimensional-data-modeling-portfolio)
