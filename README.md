# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in data engineering and analytics.

---

## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:  


1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.  
2. **Silver Layer**: Includes data cleansing, standardization, and normalization processes to prepare data for analysis.  
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.  

---

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse using Medallion Architecture (Bronze, Silver, Gold).  
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.  
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.  
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.  

🎯 Skills highlighted in this project:
- SQL Development  
- Data Architecture  
- Data Engineering  
- ETL Pipeline Development  
- Data Modeling  
- Data Analytics  

---

## 🛠️ Important Links & Tools

- **Datasets**: CSV files as raw data sources.  
- **SQL Server Express**: Lightweight server for hosting SQL databases.  
- **SQL Server Management Studio (SSMS)**: GUI for managing and interacting with databases.  
- **GitHub Repository**: For version control and collaboration.  
- **Draw.io**: To design data architecture, models, flows, and diagrams.  
- **Notion**: Project documentation and task management.  

---

## 🚀 Project Requirements

### Building the Data Warehouse (Data Engineering)

**Objective**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.  

**Specifications**  
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.  
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.  
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.  
- **Scope**: Focus on the latest dataset only (no historization required).  
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.  

---

### BI: Analytics & Reporting (Data Analysis)

**Objective**  
Develop SQL-based analytics to deliver detailed insights into:  
- Customer Behavior  
- Product Performance  
- Sales Trends  

These insights empower stakeholders with key business metrics, enabling strategic decision-making.  

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/ # Raw datasets (ERP and CRM data)
│
├── docs/ # Project documentation and architecture details
│ ├── etl.drawio # ETL techniques and workflows
│ ├── data_architecture.drawio # Overall project architecture
│ ├── data_catalog.md # Dataset catalog and field descriptions
│ ├── data_flow.drawio # Data flow diagram
│ ├── data_models.drawio # Data models (star schema)
│ ├── naming-conventions.md # Naming guidelines for tables, columns, files
│
├── scripts/ # SQL scripts for ETL and transformations
│ ├── bronze/ # Extract and load raw data
│ ├── silver/ # Data cleansing and transformation
│ ├── gold/ # Analytical models and star schema
│
├── tests/ # Test scripts and quality checks
│
├── README.md # Project overview and instructions
├── LICENSE # License information
├── .gitignore # Ignored files
└── requirements.txt # Project dependencies


---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

