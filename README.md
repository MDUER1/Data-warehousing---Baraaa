# 🏢 SQL Data Warehouse Project - Inspiration from Data With Baraa

## 📌 Overview
This project demonstrates the design and implementation of a **relational Data Warehouse** using **SQL Server**.  

The project focuses on learning skills like:
- ETL/ELT Processing
- Data Architecture
- Data Integration
- Data cleansing
- Data Load
- Data Modeling
---

## 🎯 What is a Data Warehouse & ETL?
A data warehouse is a subject-oriented, integrated, time-variant and non-volatile collection of data in support of management's decision-making process.

We are going to be creating an ETL Procees (Extract-Transform-Load), which is a process that collects and transforms data automatically from the sources into the data warehouse.

This is to avoid the problem of employees collecting data from the sources in different time periods, and thus getting different data for reports that distort the big picture for management.

This is also faster and more cost-effective.

---

## 🏗️ Project Plan
Almost 50% of data warehouse projects fail, so in order to succeed, I will be making a detailed project plan to follow. Below is the overall plan.

### Requirements Analysis
- Analyse and Understand the Requirements
### Design Data Architecture
- Choose Data Management Approach
- Brainstorm and design the layers
- Draw the Data Architecture (Draw.io)
### Project Initialization
- Create Detailed Project Tasks in Notion
- Create a Git Repo & Prepare The Structure
- Create DB and Schemas


### Layers Explained
- **Source Layer** – Raw data from transactional systems or flat files  
- **Staging Layer** – Minimal transformations, data validation, and cleansing  
- **Data Warehouse Layer** – Star schema with fact and dimension tables  
- **Analytics Layer** – Optimized queries for reporting and insights  

---

## 🧩Requirement analysis
The objective is to develop a modern data warehouse using SQL Server to consolidate sales data and thus enabling analytical reporting and informed decision-making.

**Specifications for building the Data Warehouse (Data Engineering)**
- **Data sources** - Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality** - Cleanse and resolve data quality issues before the analysis.
- **Integration** - Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope** - Focus on the latest dataset only; historization of data is not required.
- **Documentation** Provide clear documentation of the data model to support both business stakeholders and analytics teams.



---

## 🔄 ETL Process
The ETL logic is implemented entirely in **SQL**.

**Extract**  
- Load raw data into staging tables  

**Transform**  
- Data type conversions  
- Handling missing values  
- Business rule application  
- Deduplication  

**Load**  
- Insert clean data into dimension tables  
- Populate fact tables with foreign keys  

ETL scripts are **idempotent**, allowing safe re-execution.

---

## 🛠️ Tech Stack
- SQL Server  
- T-SQL  
- SQL Server Management Studio (SSMS)  

Planned extensions:
- Python for orchestration  
- Power BI for visualization  

---

## 📁 Repository Structure
