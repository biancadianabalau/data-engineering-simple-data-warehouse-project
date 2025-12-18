Simple Data Warehouse and Analytics Project

This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
<img width="638" height="808" alt="Diagramă" src="https://github.com/user-attachments/assets/f2287e16-8cef-4d19-a48f-22091e15dc7b" />

Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled required for reporting and analytics.

📖 Project Overview

This project involves:

Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
Data Modeling: Developing fact and dimension tables optimized for analytical queries.
Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights.

🚀 Project Requirements

Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications

Data Sources: https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset

Data Quality: Cleanse and resolve data quality issues prior to analysis.

Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.

Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.



📂 Repository Structure

data-engineering-simple-data-warehouse-project

├── datasets/

├── docs/
│   └── diagram_data_warehouse.drawio

├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/

└── README.md
