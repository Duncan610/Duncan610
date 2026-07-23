# Duncan Otieno

### Data Engineer | Databricks • Delta Lake • PySpark • dbt

*Building production-grade data pipelines, one medallion layer at a time*

[LinkedIn](https://linkedin.com/in/duncan-otieno) • [Email](mailto:otienoduncan99@gmail.com) • Nairobi, Kenya 🇰🇪 • Open to remote

---

## 👨🏾‍💻 What I Do

I build data pipelines that solve real problems, not tutorial problems. Currently deepening platform expertise on **Databricks**, with a focus on:

- **Lakehouse architecture** → Medallion (Bronze/Silver/Gold), Unity Catalog, Delta Lake, ACID + time travel
- **Batch & incremental processing** → PySpark, MERGE-based upserts, Structured Streaming
- **Analytics engineering** → dbt, dimensional modeling, automated testing
- **Orchestration & CI/CD** → Databricks Workflows, GitHub Actions
- **Cloud & warehousing** → AWS, Snowflake, DuckDB

## 🎯 Currently Building

A **fraud detection batch pipeline** on Databricks — Unity Catalog, medallion architecture, Databricks Workflows, and a Streamlit dashboard, unifying six data sources (transaction data, IP geolocation, FX rates, an SCD Type 2 IP blocklist, disposable-email detection, and a product catalog).

Also working through the Hugging Face LLM and AI Agents courses, building toward AI-focused data engineering roles.

---

## 🚀 Featured Work

### [EconMate](https://github.com/Duncan610/econmate)
**Vulnerability Index pipeline for 15 Sub-Saharan African countries**

Unifies economic, climate, food security, and population data into a composite Vulnerability Index — built as a real production system, not a toy dataset.

**Stack:** Databricks • PySpark • Delta Lake • Unity Catalog • Databricks SQL Dashboard

**Real engineering problems solved:**
- Handled API rate limiting with exponential backoff across multiple external data sources
- Migrated the entire pipeline's read/write layer to Unity Catalog paths mid-build after Databricks disabled DBFS root access
- Caught duplicate data from notebook re-runs via pre-write validation logic
- Diagnosed and fixed incomplete country coverage in the climate Bronze layer

Implements Bronze/Silver/Gold medallion architecture, MERGE INTO upserts, and window functions for time-series indexing.

---

### [UrbanPulse](https://github.com/Duncan610/urban-pulse-analytics-pipeline)
**Live NYC public data pipeline with idempotent ingestion**

Ingests live NYC public data from three sources, transforms it through a production-grade medallion architecture on Snowflake + dbt.

**Stack:** Snowflake • dbt • Python • CI/CD • Streamlit

**Highlights:**
- Idempotent MERGE-based ingestion from live APIs
- 57/57 passing dbt tests
- Custom dbt schema macro
- Deployed Streamlit dashboard for end-user analytics

---

### MentalHealthPulse
**Population-level mental health early-warning pipeline**

Ingests from Bluesky (AT Protocol), CDC WONDER, NOAA Climate, BLS, and SAMHSA to build an early-warning signal pipeline for population mental health trends.

**Stack:** dlt • DuckDB • dbt-duckdb • Docker • GitHub Actions

**Highlights:**
- Passing dbt models and test suite
- Containerized, reproducible pipeline via Docker
- CI/CD via GitHub Actions

---

## 💼 Technical Toolkit

**Lakehouse & Big Data:** Databricks • PySpark • Delta Lake • Unity Catalog • Structured Streaming

**Analytics Engineering:** dbt • Dimensional modeling • Data quality testing

**Warehousing:** Snowflake • DuckDB • PostgreSQL

**Languages:** Python • SQL • Bash

**Orchestration & CI/CD:** Databricks Workflows • Apache Airflow • GitHub Actions

**Cloud:** AWS (EC2, S3, RDS, Lambda) • AWS Certified Cloud Practitioner

**Ingestion:** dlt • REST APIs • Docker

**BI / Visualization:** Streamlit • Databricks SQL Dashboards • Tableau (basic)

---

## 🎓 Certifications & Learning

- **AWS Certified Cloud Practitioner** • 2025
- 
- **ALX Data Science Tech Program** • 1-Year Program • 2023–2024
- 
- Currently studying: **Hugging Face LLM Course** & **Hugging Face AI Agents Course**

---

## 📍 Now

*Last updated: July 2026*

- 🔨 Building: Fraud detection pipeline on Databricks
- 📚 Learning: LLM inference frameworks, AI agent architectures
- 🎯 Seeking: Junior/entry-level Data Engineer roles
- 🌍 Based in Nairobi, Kenya

---

## 🤝 Let's Connect

I'm actively looking for **junior/entry-level Data Engineer** roles

**Reach out if you're:**
- Hiring for data engineering roles
- Want to talk lakehouse architecture, Delta Lake internals, or dbt patterns
- Building something interesting in the data space

📧 **Email:** otienoduncan99@gmail.com
💼 **LinkedIn:** [duncan-otieno](https://linkedin.com/in/duncan-otieno)
📍 **Location:** Nairobi, Kenya (Open to remote)
🕐 **Timezone:** EAT

---

---

## 📈 GitHub Stats

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Duncan610&theme=tokyo-night&hide_border=true)

---

## 📊 GitHub Activity

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=duncan610&theme=tokyonight&hide_border=true)
