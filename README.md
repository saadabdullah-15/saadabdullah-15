# Hi, I'm Saad 👋

**M.Sc. Data Science student at the University of Potsdam** focused on **data engineering, streaming systems, lakehouse architectures, and database-oriented ML systems**.

I build end-to-end data platforms that move from ingestion and processing to storage, orchestration, validation, observability, and analytics. My current work spans batch pipelines with PySpark and Airflow, real-time processing with Kafka and Flink, lakehouse storage with Iceberg and MinIO, and relational model-management research in PostgreSQL.

<p>
  <a href="https://www.linkedin.com/in/saadabdullah15"><img src="https://img.shields.io/badge/LinkedIn-Saad%20Abdullah-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:hi.saadabdullah@gmail.com"><img src="https://img.shields.io/badge/Email-hi.saadabdullah%40gmail.com-EA4335?logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Germany-black?logo=googlemaps&logoColor=white" alt="Location: Germany">
</p>

## Featured Projects

### [Real-Time Cold-Chain Sensor Data Lakehouse](https://github.com/saadabdullah-15/real-time-cold-chain-lakehouse)

A containerized streaming lakehouse for refrigerated-shipment telemetry. It generates sensor events, validates and enriches them with event-time semantics, handles late and invalid data, detects temperature breaches, and stores auditable Bronze, Silver, and Gold datasets in Apache Iceberg.

**Stack:** Kafka, Avro, Schema Registry, Apache Flink, Apache Iceberg, Trino, MinIO, PostgreSQL, Prometheus, Grafana, Docker Compose

### [End-to-End Batch Data Pipeline](https://github.com/saadabdullah-15/pyspark-batch-etl)

A production-shaped NYC taxi analytics pipeline that ingests and transforms Parquet data with PySpark, orchestrates the workflow with Airflow, enforces data-quality contracts, writes partitioned analytics datasets, and loads serving tables into PostgreSQL.

**Stack:** Python, PySpark, Spark SQL, Apache Airflow, PostgreSQL, Docker Compose, SQLAlchemy, pytest, Ruff

### [SQL Data Warehouse & Analytics](https://github.com/saadabdullah-15/sql-data-warehouse-analytics)

A reproducible SQL Server warehouse built with a Medallion architecture. It integrates CRM and ERP extracts through Bronze, Silver, and Gold layers, implements dimensional models, captures rejects and load metrics, and includes automated quality checks and documentation.

**Stack:** SQL Server, T-SQL, ETL/ELT, dimensional modeling, data-quality testing, Medallion architecture

## Master's Thesis

I am researching **drift-aware and system-aware management of decision-tree model pools inside a relational DBMS**.

The work investigates how PostgreSQL can represent precomputed decision trees, monitor their performance under changing data, estimate feature and execution impact, and support database-side decisions to **retain, switch, or trigger external retraining**.

**Research areas:** PostgreSQL, relational model representation, concept drift, model lifecycle management, decision trees, temporal evaluation, SQL-based monitoring

## Technical Skills

| Area | Technologies |
|---|---|
| **Languages** | Python, SQL, Bash, Java |
| **Batch Processing** | PySpark, Apache Spark, Spark SQL, pandas |
| **Streaming** | Apache Kafka, Apache Flink, Avro, Schema Registry, event-time processing |
| **Lakehouse & Query** | Apache Iceberg, Trino, MinIO, Parquet, Medallion architecture |
| **Orchestration & Transformation** | Apache Airflow, ETL/ELT, data modeling, data-quality validation |
| **Databases** | PostgreSQL, SQL Server, relational databases, dimensional modeling |
| **Engineering** | Docker, Docker Compose, Git, GitHub Actions, pytest, Ruff, SQLAlchemy |
| **Observability** | Prometheus, Grafana, operational verification and reconciliation |

## Current Focus

- Designing reliable batch and streaming data pipelines
- Building local, reproducible data platforms with Docker
- Working with event-time processing, schema evolution, and lakehouse table formats
- Developing database-side mechanisms for ML model monitoring and adaptation
- Preparing for Data Engineer, Analytics Engineer, ML Systems, and research-oriented roles

## Background

- M.Sc. Data Science — University of Potsdam, Germany
- Professional experience in software engineering and applied AI
- Interested in the intersection of data platforms, databases, distributed processing, and machine-learning systems

---

**Open to working-student, junior, internship, and research-assistant opportunities in Data Engineering, Analytics Engineering, Data Platforms, and ML Systems.**
