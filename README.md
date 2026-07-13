# Airline Data Engineering Project

## Overview

This project demonstrates an end-to-end Data Engineering pipeline built on Databricks using the Medallion Architecture (Bronze, Silver, Gold). Flight operations data is ingested, transformed, aggregated into business KPIs, validated through data quality checks, and visualized using interactive dashboards.

## Architecture

Bronze Layer → Silver Layer → Gold Layer → SQL Analytics → Executive Dashboard

- **Bronze:** Raw flight data ingestion
- **Silver:** Data cleaning and transformation
- **Gold:** Business KPI generation
- **SQL Analytics:** Analytical queries and views
- **Dashboard:** Executive KPI visualization

## Technologies Used

- Databricks
- Apache Spark (PySpark)
- Spark SQL
- Delta Lake
- Unity Catalog
- Databricks SQL Dashboard
- GitHub

## Project Structure

```
Airline-Data-Engineering-Project/
│
├── notebooks/
│   ├── 01_Bronze_Ingestion.dbc
│   ├── 02_Silver_Transformation.dbc
│   ├── 03_Gold_Business_KPIs.dbc
│   ├── 04_SQL_Analytics.dbc
│   ├── 05_Data_Quality_Checks.dbc
│   └── 06_Executive_Dashboard.dbc
```

## Pipeline Flow

1. Ingest raw airline flight data into Bronze tables.
2. Clean and standardize records in the Silver layer.
3. Generate business KPIs in the Gold layer.
4. Build SQL views for analytical reporting.
5. Create executive dashboards for business insights.
6. Track end-to-end data lineage using Unity Catalog.

## Executive KPIs

- Average Delay by Airline
- Flights by Delay Reason
- Average Delay by Route
- Average Delay by Aircraft Type
- Cancelled Flights by Airline

## Skills Demonstrated

- Data Engineering
- ETL Pipeline Development
- Medallion Architecture
- PySpark
- Spark SQL
- Delta Lake
- Data Quality Validation
- Dashboard Development
- Unity Catalog Lineage
- Git Version Control

## Future Enhancements

- Streaming ingestion with Auto Loader
- Scheduled pipeline orchestration
- CI/CD deployment
- Automated monitoring and alerting
- Machine Learning-based delay prediction
