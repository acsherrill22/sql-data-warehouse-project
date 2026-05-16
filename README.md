# Data Warehouse and Analytics Project

An enterprise-grade, end-to-end data platform built to demonstrate production-ready data engineering and analytics paradigms. This project showcases the ingestion, transformation, and optimization of raw transactional and operational data into highly performant, business-ready analytical assets using a multi-layered modern data stack architecture.

## 🏗️ Architecture & Paradigms

The platform implements a **Medallion Architecture** to guarantee data cleanliness, schema enforcement, and structured progression of business logic:

* **Bronze Layer (Raw Ingestion):** An append-only landing zone capturing source data in its native format. Focuses on high-throughput ingestion, preserving data history, and eliminating upstream friction with a strict "no transformation" rule.
* **Silver Layer (Cleaned & Conformed):** The source-of-truth layer where data cleansing, deduplication, schema enforcement, and enrichment take place. Standardizes structural data types, maps uniform schemas, and resolves structural anomalies to prepare data for cross-functional utilization.
* **Gold Layer (Curated Business Insights):** Heavily aggregated, business-level analytical models optimized for corporate performance. Implements structural dimensional modeling architectures (Star Schemas) utilizing Fact and Dimension tables designed for sub-second business intelligence querying.

---

# 🚀 Project Requirements

## Building the Data Warehouse (Data Engineering)

### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

### Specifications
* **Data Sources:** Import data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
* **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
* **Scope:** Focus on the latest dataset only; historization of data is not required.
* **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

## BI: Analytics & Reporting (Data Analysis)

### Objective
Develop SQL-based analytics to deliver detailed insights into:
* Customer Behavior
* Product Performance
* Sales Trends

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

## License

🛡️This project is licensed under the [MIT License](LICENSE). You are free to use, modify and share this project with proper attribution
