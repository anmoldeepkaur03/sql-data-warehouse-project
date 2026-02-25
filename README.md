# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** respository!   
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project highlights best practices in data engineering and analytics.

---

# Project Overview

This project involves:
  1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver** and     **Gold** layers.
  2. **ETL Pipelines**: Extracting, transforming and loading data from source system into the warehouse.
  3. **Data Modelling**: Developing fact and dimension tables optimised for analytical queries.
  4. **Analytical & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## Project Reqirements

## Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision making.

**Specifications**:
- **Data Sources**: Import data from two sources systems(ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into single, user friendly data model designed for analytical queries.
- **Scope**: Focus on latest dataset only, historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

  ### BI: Analytics & Reporting

  ### Objective
  Develop SQL-based analytics to deliver insights into :
  - **Customer Behaviour**
  - **Product Performance**
  - **Sales Trends**
 
  These insights empowere stakeholders with key businessmetrics, enabling strategic decision-making. 

  ---
  ### Data Architecture 
  
The data architecture for this project follows Medallion Architecture Bronze, Silver and Gold layers:
<img width="3284" height="2004" alt="image" src="https://github.com/user-attachments/assets/692b861f-eb0b-4572-b4c2-c14ce36b8bcd" />

1. **Bronze Layer**: Store raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleaning, standaradisation, and normalisation processes to prepare data for analysis.
3. **Gold Layer**: Houses business ready data modeled into a star schema required for reporting and analytics.

---

### Data Analysis

A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more. This repository contains SQL queries designed to help data analysts and BI professionals quickly explore, segment, and analyze data within a relational database. Each script focuses on a specific analytical theme and demonstrates best practices for SQL queries.

---

### About Me

Hi! I'm Anmoldeep Kaur. I am a aspiring Data analyst seeking new oppertunities.    
Let's stay in touch through:
1. **Linkedin**:https://www.linkedin.com/in/anmoldeep-kaur-6525102b4
2. **Tableau**: https://public.tableau.com/app/profile/anmoldeep.kaur2351/vizzes
3. **E-Mail**: anmolchahal2002@gmail.com

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── data_integration.md             # File shows how data integrated at different layers
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow                       # File for the data flow diagram
│   ├── data_model                      # File for data models (star schema)
│   ├── naming_conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
|   ├── data_analysis/                  # Scripts for exploratory data analysis
│   
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository

```
---


