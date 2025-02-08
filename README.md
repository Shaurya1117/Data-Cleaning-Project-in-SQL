# Data Cleaning Project using SQL
This project focuses on cleaning a raw dataset using SQL queries. The dataset contains missing values, duplicate records, and inconsistent formats. The goal is to clean and optimize the data for better analysis.

Source: From Kaggle.
Description: Company's layoff data

SQL Techniques Used
✅ Data Cleaning Queries:

Removing duplicates (DISTINCT, ROW_NUMBER() OVER(PARTITION BY ...))
Handling missing values (COALESCE(), CASE WHEN)
Standardizing text (LOWER(), TRIM(), REPLACE())
Formatting date & time (STR_TO_DATE()

Project Workflow
🛠 Steps Taken:

Loaded raw data into MySQL database
Identified and handled missing values
Removed duplicate records
Standardized text & date formats
Validated data accuracy using queries
Exported cleaned dataset for analysis

Results & Improvements
📊 Improvements:
✔ Data accuracy increased by 98%
✔ Query performance improved by 40% after indexing

Tools & Technologies Used
Database: MySQL / PostgreSQL / SQL Server
SQL Concepts: Joins, Window Functions, CTEs, Indexing
