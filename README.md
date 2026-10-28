# Customer Churn Data Warehouse

## Project Overview
This project focuses on preparing customer churn data for analytical reporting using Python and Pandas. The workflow includes data inspection, data cleaning, missing value handling, dimensional table development, and CSV export.

The prepared datasets support customer churn analysis and interactive dashboards built with Looker Studio.

## Objectives
- Inspect and prepare customer churn data.
- Handle missing values and validate data quality.
- Develop customer, location, payment, contract, and service dimension tables.
- Prepare a customer churn fact table.
- Export the resulting tables to CSV for analytical use.
- Present customer churn insights through interactive dashboards.

## Tools & Technologies
- Python
- Pandas
- Jupyter Notebook
- CSV
- Looker Studio

## Data Preparation & ETL
The workflow includes:
1. **Extract:** Load the source customer churn dataset into a Pandas DataFrame.
2. **Transform:** Inspect data types, check missing values, handle missing churn reasons, and prepare dimension and fact tables.
3. **Load:** Export the resulting tables as CSV files for downstream analysis and dashboard reporting.

## Data Model Preparation
The project includes the following tables, subject to the final exported files:

- `dim_customer.csv`
- `dim_location.csv`
- `dim_payment_billing.csv`
- `dim_contract.csv`
- `dim_service.csv`
- `dim_service_package.csv`
- `fact_churn.csv`

## Dashboards
Interactive Looker Studio dashboards explore:
- Customer overview and churn patterns
- Contract and service package analysis
- Customer service usage and churn insights

## Project Scope
This project demonstrates Python-based ETL and dimensional table preparation. The tables are exported as CSV files; a physical data warehouse database is not claimed as part of this implementation.

