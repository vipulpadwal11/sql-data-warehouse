# Data Warehouse and Analytics Project

## Overview
This project demonstrates the design and implementation of a SQL-based Data Warehouse using the Bronze, Silver, and Gold architecture. It covers data ingestion, cleansing, transformation, dimensional modeling, and analytical views using Microsoft SQL Server.

This project was recreated for learning purposes based on the SQL Data Warehouse project by Data With Baraa, with the goal of gaining hands-on experience in ETL pipelines, data modeling, and SQL best practices.

---

## Tech Stack

- Microsoft SQL Server
- Draw.io 
- CSV datasets

---

## Architecture

Bronze Layer:
- Raw data ingestion using BULK INSERT

Silver Layer:
- Data cleansing
- Standardization
- Null handling
- Data quality checks

Gold Layer:
- Star schema
- Dimension tables
- Fact table
- Business-ready analytical views

![Data Flow](https://github.com/vipulpadwal11/sql-data-warehouse/blob/main/docs/data_flow.png?raw=true)

---

## Project Workflow

1. Created the Data Warehouse database.
2. Created Bronze, Silver, and Gold schemas.
3. Loaded raw CSV files using BULK INSERT.
4. Cleaned and transformed raw data.
5. Built dimension and fact tables.
6. Created analytical views for reporting.

---

## SQL Concepts Practiced

- CTEs
- Window Functions
- ROW_NUMBER()
- CASE
- COALESCE
- JOINs
- Aggregate Functions
- Data Cleansing
- Views
- Stored Procedures
- BULK INSERT
- Star Schema
- ETL Pipeline

---

## Key Learnings

- Building a multi-layer data warehouse
- Implementing ETL workflows in SQL Server
- Designing dimensional models
- Writing maintainable SQL queries
- Performing data validation and cleansing
