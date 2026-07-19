# Databricks Lakehouse

A hands-on Data Engineering project implementing a modern **Lakehouse Architecture** using **Databricks**, **PySpark**, and **Delta Lake**. This repository demonstrates how raw data is ingested, transformed, and prepared for analytics using the Medallion Architecture (Bronze, Silver, and Gold).

> **Note:** This project was created as part of my Data Engineering learning journey by following the **Data with Baraa** Databricks tutorial series. The implementation has been recreated, studied, and modified for educational purposes.

---

## Project Overview

The project simulates a real-world data pipeline by ingesting data from multiple source systems, storing it in Delta Lake, applying data quality transformations, and producing business-ready datasets.

### Medallion Architecture

```text
Source Data
     │
     ▼
Bronze Layer
(Raw Data Ingestion)
     │
     ▼
Silver Layer
(Data Cleaning & Transformation)
     │
     ▼
Gold Layer
(Business-Ready Data)
```

### Bronze Layer

* Ingest raw data from source systems
* Store data in Delta format
* Preserve original data with minimal transformations

### Silver Layer

* Clean and standardize data
* Trim unnecessary whitespace
* Handle null values
* Remove duplicate records
* Apply data type conversions
* Improve overall data quality

### Gold Layer

* Create business-ready datasets
* Prepare data for reporting and analytics
* Generate curated tables for downstream consumers

---

## Technologies Used

* Databricks
* Apache Spark (PySpark)
* Delta Lake
* SQL
* Git & GitHub

---

## Repository Structure

```text
Databricks-Lakehouse/
├── Bronze/
├── Silver/
├── Gold/
├── datasets/
├── README.md
├── LICENSE
└── .gitignore
```

---

## Learning Objectives

Through this project, I am gaining practical experience with:

* Lakehouse Architecture
* Medallion Architecture
* PySpark DataFrame API
* Delta Lake
* ETL/ELT Pipelines
* Data Cleaning & Transformation
* Databricks Workflows
* Git & Version Control

---

## Acknowledgements

This project is based on the **Data with Baraa** Databricks tutorial series created by **Baraa Khatib Salkini**.

The implementation in this repository has been recreated and adapted as part of my personal learning journey. Credit goes to the original author for the course structure, concepts, and educational content.

##
