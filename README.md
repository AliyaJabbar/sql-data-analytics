# sql-data-analytics
SQL analytics project built on cleaned data from my data warehouse, focusing on business insights, performance analysis, and reporting.
# SQL Data Analytics Project

This repository contains a collection of SQL scripts built on top of my **Data Warehouse Project**, which follows the **Bronze–Silver–Gold layer architecture**.  
The scripts in this repo focus on exploring the **cleaned (Silver/Gold)** data to perform **business analysis, data segmentation, performance tracking, and reporting**.

---

## 🧱 Project Context

This project is a continuation of my [Data Warehouse Project](../data-warehouse-project), where:
- **Bronze Layer**: Raw ERP and CRM data were extracted.
- **Silver Layer**: Data was cleaned, transformed, and standardized.
- **Gold Layer**: Analytical models were created for reporting.

This repository represents the **analytics stage**, where SQL is used to generate insights from the cleaned (Gold) data.

---

## 📂 Repository Structure

| File | Description |
|------|--------------|
| `00_init_database.sql` | Initializes database schema and loads clean tables |
| `01_database_exploration.sql` | Basic structure and completeness checks |
| `02_dimensions_exploration.sql` | Exploration of customer, product, and sales dimensions |
| `03_date_range_exploration.sql` | Analysis of available date ranges and trends |
| `04_measures_exploration.sql` | Calculates metrics such as revenue, profit, and sales count |
| `05_magnitude_analysis.sql` | Quantifies overall business performance |
| `06_ranking_analysis.sql` | Ranks top-performing products, customers, and regions |
| `07_change_over_time_analysis.sql` | Tracks performance trends over time |
| `08_cumulative_analysis.sql` | Computes running totals and growth metrics |
| `09_performance_analysis.sql` | Evaluates KPIs and sales efficiency |
| `10_data_segmentation.sql` | Segments customers and products for deeper insights |
| `11_part_to_whole_analysis.sql` | Calculates contribution of categories to total sales |
| `12_report_customers.sql` | Generates customer-level summary reports |
| `13_report_products.sql` | Generates product-level summary reports |

---

## 🧠 Skills Demonstrated

- **SQL Querying** – Joins, CTEs, Window functions, Grouping  
- **Data Modeling** – Star schema, Fact-Dimension relationships  
- **ETL Concepts** – Using Cleaned Silver and Gold layer data  
- **Data Analytics** – Ranking, segmentation, and time-based analysis  
- **Reporting & Visualization** – Data prepared for Power BI / Excel dashboards

---

## 📊 Possible Extensions

- Connect SQL outputs to **Power BI dashboards**
- Add a **“business_insights.md”** summary
- Implement automated refresh using Python or Airflow

---

## 💡 About

This project represents the analytics layer of my end-to-end data pipeline — transforming raw data into business insights using SQL and BI tools.  
It demonstrates the transition from data engineering (ETL) to data analytics (insight generation).

---

👩‍💻 **Author:** Aliya Jabbar  
 Data Enthusiast | SQL | Power BI | Python  
🔗 [LinkedIn Profile](#)

