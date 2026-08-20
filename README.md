# Georg Wiesmüller

**Business Informatics · Data Engineering · Automation · Security & AI Governance**

I build portfolio systems that make data flows more reliable, traceable, and reviewable. My work emphasizes explicit data contracts, data quality, automated testing, security controls, and clearly documented scope boundaries.

## Featured engineering work

### [Cyber Governance Automation Lab](https://github.com/gw-ai-security/cyber-governance-automation-lab)

A Python-based proof of concept for recurring security-control evidence processes.

- Executable extract, normalize, validate, transform, derive, and load pipeline
- Explicit raw and curated data contracts
- Deterministic data-quality rules `DQ-001` through `DQ-010`
- Source-row lineage and reproducible time-based metrics
- Data-minimized AI review queue builder with advisory-only AI scope
- Automated unit, regression, CLI, and end-to-end verification

The implemented scope is intentionally separated from planned Power Automate, Power BI, external AI runtime, and REST API components.

### [AI Process Automation](https://github.com/gw-ai-security/AI-Process-Automation)

A portfolio of automation and integration projects. Its REST API Integration Hub demonstrates:

- FastAPI, PostgreSQL, Docker Compose, and n8n orchestration
- HMAC webhook verification
- Idempotency and replay protection
- Structured audit logging and a Dead Letter Queue
- Mock CRM and Jira/Confluence-style integrations

The repository uses simulated services and contains no real third-party credentials.

### [Secure AI Fraud Detection Pipeline](https://github.com/gw-ai-security/secure-ai-fraud-detection-pipeline)

A synthetic-data portfolio and learning project for security- and privacy-aware ML engineering.

- Python, pandas, scikit-learn, and notebook-based experimentation
- Data preparation, feature engineering, model training, and evaluation
- STRIDE threat modeling and risk documentation
- Data minimization, pseudonymization, and governance-oriented documentation
- Explicitly no real customer data or PII

## Engineering focus

- **Data pipelines and quality:** contracts, validation, lineage, deterministic processing, reproducibility
- **APIs and automation:** Python backends, webhooks, orchestration, integration safeguards
- **Security and governance:** auditability, traceability, privacy-aware design, controlled AI workflows
- **ML systems foundations:** feature engineering, evaluation, threat modeling, governance documentation

## Currently building

### [CloudOps Insight Lake](https://github.com/gw-ai-security/data-engineering-projects/tree/main/cloudops-insight-lake)

**Current phase: Phase 0 — Architecture and Scope Freeze**

An incrementally developed serverless AWS data-engineering project for correlating Lambda cost, resource inventory, and operational metrics. The documented target architecture includes S3 raw and curated layers, Glue-based ETL, Parquet datasets, the Glue Data Catalog, Athena analytics, pipeline observability, and least-privilege IAM controls. These implementation areas are planned and are not presented as completed.

---

My repositories use synthetic or mock data where stated. Each project documents its implemented scope, limitations, and next development steps.
