# Rishikesh Pandey

**Data Engineer · Lakehouse and streaming pipelines**

Data Engineering Intern at HDFC Securities in Bengaluru. I build batch and streaming pipelines, ETL/ELT workflows and lakehouse platforms on Spark, Databricks, Delta Lake, Kafka, Apache Iceberg and Trino.

Open to full-time data engineering roles, onsite or remote.

[Portfolio](https://rishikeshpandeyportfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/rishikesh-pandey-119064346) · [LeetCode](https://leetcode.com/u/rishikesh8pandey/)

## Experience

**Data Engineering Intern, HDFC Securities** · Jul 2026 – Present · Bengaluru

- Build and operate a production federated query lakehouse: Trino federating SQL across Apache Iceberg tables on AWS S3 and relational sources (Oracle, PostgreSQL), with Apache Superset for BI and Apache Ranger for authorization, deployed on an air-gapped RHEL host.
- Cut Databricks compute spend by about 40% by routing reporting and ad-hoc analytical queries through Trino on the lakehouse.
- Traced a 2–3% revenue reconciliation gap to duplicated rows in the silver layer, then rebuilt the bronze-to-gold pipeline in PySpark and Delta Lake on Databricks Workflows. It now runs in production.

**Data Engineering Intern, Lumiq.ai** · Feb 2026 – Jun 2026 · Noida

- Built a Dockerised real-time analytics pipeline that ingests live Binance WebSocket trades into Apache Kafka and processes them with PySpark Structured Streaming, using schema validation, watermarking and windowed aggregations.
- Built a multi-tenant FMCG lakehouse on Delta Lake with bronze, silver and gold layers, full and incremental loads, data quality checks and a dimensional model for group reporting.

## Projects

| Project | What it does | Stack |
| --- | --- | --- |
| [Real-Time Crypto Analytics Platform](https://github.com/rishikesh8pandey/real_time_crypto_analytics_platform) | Streams live Binance trades through Kafka, aggregates them with Spark Structured Streaming and serves Grafana dashboards from PostgreSQL. | Python, Kafka, PySpark, PostgreSQL, Grafana, Docker |
| [Multi-Tenant FMCG Lakehouse](https://github.com/rishikesh8pandey/FMCG-Parent-child-data-pipeline) | Consolidates sales, customer and product data from multiple child companies into parent-level reporting using a medallion architecture. | PySpark, Delta Lake, Databricks, SQL |
| [Real-Time Kafka E-Commerce Analytics](https://github.com/rishikesh8pandey/real_time_kafka_ecom) | Event streaming, ingestion and transformation pipeline that lands e-commerce data in Snowflake for KPI analytics. | Python, Kafka, Snowflake, SQL |
| [Kafka Email Notification System](https://github.com/rishikesh8pandey/kafka-email-notification-system) | Event-driven email notifications with Kafka producers and consumers and asynchronous message processing. | Python, Kafka |
| [Talent Scout Hub](https://github.com/rishikesh8pandey/talent-scout-hub) | Recruitment system for managing candidates, job applications and survey responses with role-based access. | Flask, MongoDB, TypeScript |

## Tech stack

| Area | Tools |
| --- | --- |
| Languages | Python, SQL, Shell scripting |
| Big data and lakehouse | Apache Spark, PySpark, Spark Structured Streaming, Apache Kafka, Databricks, Delta Lake, Apache Iceberg, Trino, Hadoop |
| Data engineering | ETL/ELT, batch and streaming pipelines, medallion architecture, dimensional modelling, incremental loads, data quality |
| Cloud and operations | AWS S3, Docker, RHEL/Linux, Databricks Workflows, Apache Ranger, Cron, Git |
| Databases and BI | PostgreSQL, Oracle, MongoDB, Snowflake, Apache Superset, Grafana |

## Education and certifications

- B.Sc. Mathematics, Siddharth University (2022 – 2025), CGPA 8.6/10
- HackerRank: SQL (Basic, Intermediate), Python (Basic), Problem Solving (Basic)
- LeetCode: SQL 50 badge
