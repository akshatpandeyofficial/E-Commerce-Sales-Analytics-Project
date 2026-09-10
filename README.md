# E-Commerce-Sales-Analytics-Project
E-Commerce-Sales-Analytics This repository showcases an end-to-end data analytics workflow on a raw e-commerce sales dataset. As part of a data analyst portfolio project, this repository details the process of inspecting messy transactional records, performing extensive data cleaning, and producing reliable visualizations for business reporting.

# E-Commerce Sales Data Analysis & Cleaning

# Project Overview

This repository demonstrates an end-to-end data analytics workflow on a raw, messy e-commerce sales dataset. Designed as a data analyst portfolio project, it highlights the transition from unstructured transactional records to a clean, standardized dataset ready for business intelligence and visualization.

# Key Workflow & Steps

# 1. Exploratory Data Analysis (EDA)
•	Data Auditing: Analyzed dataset schema, missing value rates, and data type mismatches across all columns.
•	Anomaly Detection: Identified string noise in numerical fields , invalid negative quantities/totals, and non-standard date formats.
•	Categorical Inspection: Flagged spelling and casing variations across product categories.

# 2. Data Cleaning & Transformation
•	Header Normalization: Standardized column headers into lowercase snake_case.
•	Deduplication: Detected and removed exact duplicate transaction rows.
•	Data Parsing & Type Casting: Cleaned non-numeric characters from numeric columns (price, quantity), converted string fields to appropriate numeric data types, and parsed dates to YYYY-MM-DD.
•	Data Imputation & Logic Alignment: Handled missing categorical values, mapped inconsistent categories to clean labels, and recalculated total = price * quantity to eliminate calculation discrepancies.

# 3. Data Visualization
•	Order Status Distribution: Plotted visual breakdowns of orders across delivery statuses (Shipped, Delivered, Cancelled).
•	Payment Preference: Created visualizations tracking customer payment methods.
•	Category Metrics: Built clean distribution charts for revenue and order volume by product category.

# Repository Structure
•	data/: Contains raw CSV data (messy_ecommerce_sales_data.csv) and the final cleaned dataset.
•	notebooks/: Jupyter Notebook with step-by-step EDA, data cleaning code, and inline visualizations.
•	images/: Exported chart images for documentation.

# Tools & Libraries
•	Language: Python
•	Data Processing: Pandas, NumPy
•	Visualization: PowerBI
•	Environment: Jupyter Notebook


