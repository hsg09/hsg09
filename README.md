<img width="1288" height="419" alt="image" src="https://github.com/user-attachments/assets/2f92dc58-9146-4424-90ac-005de5fc3e80" />


# Hi, I'm Harnek Singh 👋
I’m a **Senior Data Engineer** with **12+ years of experience** working on large-scale data platforms, mostly around **Snowflake** and cloud (**AWS/Azure**).

Over the last few years, I’ve been focused on building reliable, production-grade data systems — the kind that actually hold up under scale, not just in design docs.

---

## 🛠️ What I usually work on

- **Designing ELT pipelines** that don’t rely on full reloads (incremental loading, CDC)
- **Fixing slow Snowflake queries** (optimizing clustering, partitioning, and pruning)
- **Building end-to-end data platforms** from ingestion → transformation → consumption
- **Setting up governance properly** (RBAC, dynamic data masking, access control policies)

---

## 💻 Tech Stack

- **Data Warehousing & Processing:** Snowflake, SQL, Python
- **Cloud Infrastructure:** AWS (S3, IAM), Azure (ADLS)
- **Orchestration & Transformation:** Airflow, Terraform, dbt
- **Architecture & Modeling:** Medallion Architecture, Dimensional Modeling (Kimball), Data Vault, Lakehouse patterns

---

## 🚀 Projects

I’ve started putting together a few sample projects here based on patterns I’ve used in real systems (mainly Snowflake, ELT, and platform design).

### [❄️ SnowVault Enterprise Data Platform](https://github.com/hsg09/SnowVault-Enterprise-Data-Platform)
A production-ready, multi-cloud Snowflake data platform architecture managed entirely via Infrastructure as Code (IaC).
* **Key Features:** Multi-environment deployments (Staging/Prod) via Terraform, automated RBAC governance, cross-region replication, Snowflake Dynamic Tables, and Iceberg integrations.
* **Stack:** Snowflake, Terraform, CI/CD.

### [🏢 Enterprise ELT Data Pipeline (AWS S3 → Snowflake → dbt)](https://github.com/hsg09/AWS_DBT_Snowflake)
A scalable, production-grade ELT pipeline that synchronizes transactional e-commerce data from AWS S3 into an analytical Star Schema in Snowflake.
* **Key Features:** Medallion Architecture, Zero-DDL dynamic ingestion with Snowpark, PII Masking & RBAC, 68+ automated dbt tests, Kimball dimensional modeling.
* **Stack:** Snowflake, AWS S3, dbt Core, Apache Airflow, Snowpark Python.

### [⚡ Snowflake Kafka Streaming Platform](https://github.com/hsg09/Snowflake-Streaming-Platform)
An enterprise-grade benchmark platform for evaluating Snowflake's two Kafka ingestion modes (Classic Snowpipe vs. Snowpipe Streaming).
* **Key Features:** Direct row insertion via Streaming API, real-time analytics pipeline, JMX metrics exported to Prometheus/Grafana, full comparison of throughput and p95 latency.
* **Stack:** Snowflake, Apache Kafka, Python, Docker, Prometheus, Grafana.

### [🏠 Airbnb End-to-End Data Engineering Project](https://github.com/hsg09/Airbnb_Snowflake_DBT_Data_Engineer_Project)
A complete end-to-end data engineering pipeline processing Airbnb listings, bookings, and hosts data through a medallion architecture.
* **Key Features:** Incremental loading, Slowly Changing Dimensions (SCD Type 2 snapshotting), dynamic SQL generation with Jinja, and intermediate ephemeral dbt models.
* **Stack:** Snowflake, dbt, AWS, Python.

### [🤖 Snowflake Cortex Slack Bot](https://github.com/hsg09/snowflake_slack_bot-slack_bot_with_graphs)
A Slack bot integrating Snowflake Cortex Agents to provide AI-powered data analysis, query performance insights, and cost optimization recommendations directly in Slack.
* **Key Features:** Natural language SQL querying, inline tabular data display, Vega-Lite chart rendering to PNG, and conversational memory.
* **Stack:** Python, Snowflake Cortex Agent API, Slack Bolt, pandas, Vega-Lite.

---

## 🎯 Currently

**Open to remote roles in:**
- Senior Data Engineering
- Snowflake / Data Platform roles

---

## 📫 Connect with me

- **LinkedIn:** [linkedin.com/in/hsg09](https://linkedin.com/in/hsg09)
