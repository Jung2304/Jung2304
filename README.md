
<h1 align="center">Hi, I'm Jung Nguyen 👋</h1>

<p align="center">
  <strong>Aspiring Data Engineer | Information Systems Student at the University of Information Technology (UIT)</strong>
</p>

<p align="center">
  Building practical data pipelines with <strong>Apache Spark, Kafka, Airflow, Azure Databricks, and SQL</strong> — from ingestion and transformation to validated, analytics-ready datasets.
</p>

<p align="center">
  <a href="https://github.com/Jung2304">
    <img src="https://img.shields.io/badge/GitHub-Jung2304-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub Jung2304" />
  </a>
  <img src="https://img.shields.io/badge/Focus-Data%20Engineering-2563EB?style=flat-square" alt="Data Engineering" />
  <img src="https://img.shields.io/badge/Open%20to-Internship%20Opportunities-16A34A?style=flat-square" alt="Internship" />
</p>

## 👨‍💻 About Me

I'm an Information Systems student passionate about **data engineering, distributed data processing, and data warehouse design**.

I learn by building end-to-end projects, working with both **cloud-based lakehouse platforms** and **self-managed open-source data infrastructure**.

- 🎯 **Current goal:** Data Engineering Internship
- 🔧 **Working on:** Incremental ETL/ELT, data quality, dimensional modeling, and workflow orchestration
- 📚 **Exploring:** Open-source data ecosystems, distributed systems, and modern lakehouse architectures
- 🌏 **Based in:** Vietnam
- 🏅 **English:** TOEIC Listening & Reading — **930/990**

## 🛠️ Tech Stack

**Languages & Data Processing**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)

**Streaming, Databases & Storage**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Cassandra](https://img.shields.io/badge/Apache%20Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Confluent](https://img.shields.io/badge/Confluent-Schema%20Registry-173F5F?style=for-the-badge&logo=confluent&logoColor=white)

**Cloud & Lakehouse**

![Azure](https://img.shields.io/badge/Microsoft%20Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)

**Orchestration & Development Tools**

![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

**Web & Backend Development**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

## 🚀 Featured Projects

### 📊 Data Engineering

#### 1. [Adventure Works | End-to-End Azure Data Engineering](https://github.com/Jung2304/Azure-Adventure-Works-Project)

**Azure ADLS Gen2 · Databricks · PySpark · Delta Lake · Lakeflow · Databricks Asset Bundles**

- Built an end-to-end **Medallion Architecture** using Databricks Auto Loader and Lakeflow Declarative Pipelines, transforming raw sales data into validated Silver tables and a Gold **star schema**.
- Implemented incremental **Delta Lake MERGE** operations, record deduplication, and automated data quality checks, including reconciliation between fact tables and monthly sales aggregates.
- Orchestrated processing through a **five-task Databricks Job**, with infrastructure and workflow definitions managed using **Databricks Asset Bundles**.

#### 2. [Kafka-to-Cassandra | Micro-Batch Data Pipeline](https://github.com/Jung2304/realtime-data-streaming-pipeline)

**Apache Kafka (KRaft) · Spark Structured Streaming · Apache Airflow · Cassandra · Confluent Schema Registry · Docker**

- Built a **Dockerized micro-batch pipeline** that ingests API-generated events into a three-broker Kafka KRaft cluster, processes them with modular PySpark transformations, and persists validated records in Cassandra.
- Implemented **JSON Schema serialization**, checkpoint-based incremental processing, and five data quality rules with per-batch metrics, successfully identifying all five invalid events in a controlled six-record test.
- Orchestrated ingestion and processing through **Airflow cross-DAG dependencies**, using Deferrable Operators and Triggerer to release worker slots while waiting for downstream DAG execution.

#### 3. [Flights | End-to-End Databricks Data Engineering](https://github.com/Jung2304/Databricks-Flights-E2E-Project)

**Databricks · PySpark · Delta Lake · Auto Loader · Lakeflow / DLT · Dimensional Modeling**

- Developed an incremental **Bronze–Silver–Gold** data pipeline using Databricks Auto Loader and declarative data quality expectations.
- Designed metadata-driven **dimension and fact table builders**, using surrogate keys, CDC processing, and Delta Lake upserts to produce analytics-ready flight booking datasets.

#### 4. [Databricks Asset Bundles | Mini Project](https://github.com/Jung2304/DABs_mini_project)

**Databricks Asset Bundles · YAML · Lakeflow Pipelines**

- Practiced **deployment as code** by defining Databricks resources and workflow configurations in a version-controlled Asset Bundle.
- Configured separate **development and production targets** to understand environment-specific deployment and resource management.

### 🌐 Web & Backend Engineering

#### 5. [4Wheeler | Car Dealership Backend API](https://github.com/Jung2304/4Wheeler_BE/tree/main/Backend)

**Node.js · Express.js · MongoDB · Mongoose · JWT · Firebase · Cloudinary · Swagger · Gemini API**

- Developed **RESTful APIs** for vehicle discovery, filtering, pagination, favorites, and test-drive bookings using MongoDB and Mongoose.
- Implemented **JWT authentication**, protected admin CRUD operations, media uploads, and Gemini-powered vehicle comparisons, with Swagger API documentation.

## 📌 Current Focus

`Data Engineering` · `Apache Spark` · `Apache Kafka` · `Incremental ETL/ELT` · `Data Quality` · `Dimensional Modeling` · `Lakehouse Architecture` · `Workflow Orchestration`

---

<p align="center">
  <strong>Thanks for visiting!</strong><br>
  Feel free to explore my repositories and connect with me on
  <a href="https://github.com/Jung2304">GitHub</a>.
</p>
