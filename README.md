# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository!

This project demonstrates an end-to-end data warehousing and analytics solution using **Microsoft SQL Server**. It covers the complete workflow from data ingestion and ETL processes to dimensional modeling and analytical reporting.

The project follows industry best practices in **Data Engineering**, **Data Warehousing**, and **Business Intelligence**, making it suitable as a portfolio project.

---

# Data Architecture

The solution follows the **Medallion Architecture**, consisting of three layers:

## Bronze Layer
- Stores raw data from source systems without modification.
- Imports data from **ERP** and **CRM** CSV files into SQL Server.
- Serves as the landing zone for all source data.

## Silver Layer
- Cleanses and transforms raw data.
- Standardizes data formats.
- Removes duplicates and resolves data quality issues.
- Prepares data for analytical processing.

## Gold Layer
- Stores business-ready data.
- Implements a **Star Schema** using Fact and Dimension tables.
- Optimized for reporting, dashboards, and analytical queries.

---

# Project Requirements

## Data Engineering

### Objective

Develop a modern data warehouse using **Microsoft SQL Server** to consolidate sales data from multiple source systems into a single analytical database.

### Specifications

- Import data from two source systems:
  - ERP
  - CRM
- Source files are provided in CSV format.
- Build ETL processes to load data into SQL Server.
- Perform data cleansing and resolve data quality issues.
- Standardize and integrate data from both systems.
- Create a user-friendly dimensional data model for analytics.
- Load only the latest available data (historical tracking is out of scope).
- Document the complete data model and ETL process.

---

## Data Analysis & Reporting

### Objective

Develop SQL-based analytical solutions to generate meaningful business insights.

### Analytics Areas

- Customer Behavior Analysis
- Product Performance Analysis
- Sales Trend Analysis

### Business Outcomes

The analytics solution provides stakeholders with insights that support:

- Better business decisions
- Sales performance monitoring
- Customer segmentation
- Product performance evaluation
- Trend analysis and forecasting
- Executive reporting

---

# Technologies Used

- Microsoft SQL Server
- T-SQL
- ETL
- Data Warehouse
- Star Schema
- Medallion Architecture
- SQL Analytics
- Git & GitHub

---

# Project Workflow

```
CSV Files (ERP + CRM)
        │
        ▼
 Bronze Layer (Raw Data)
        │
        ▼
Silver Layer (Data Cleaning & Transformation)
        │
        ▼
 Gold Layer (Star Schema)
        │
        ▼
 SQL Analytics & Reporting
```

---

# Repository Structure

```
Data-Warehouse-Project/
│
├── datasets/
│   ├── erp/
│   └── crm/
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   ├── gold/
│   └── analytics/
│
├── docs/
│
├── README.md
│
└── LICENSE
```
