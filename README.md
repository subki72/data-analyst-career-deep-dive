#  Data Analyst Career Deep Dive: Salary & Growth Analysis

![Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/SQL-SQLite-blue)
![Language](https://img.shields.io/badge/Python-Pandas%20%7C%20Seaborn-green)

## Project Overview
Unlike general data science market analyses, this project provides a **targeted deep dive** into the **Data Analyst** career path. Using a real-world dataset (`ds_salaries.csv`), I simulated a relational database environment in Python to execute specific SQL queries aimed at answering critical career questions for aspiring analysts.

## Key Objectives
* **Role-Specific Analysis:** Focusing strictly on "Data Analyst" job titles to avoid generalization bias.
* **Salary Estimation (IDR):** Converting and estimating monthly salaries in Indonesian Rupiah to provide local context.
* **Career Progression:** Measuring the financial leap from Mid-level to Executive positions.
* **Global Hotspots:** Identifying top countries for entry-level analysts.

## Technical Implementation
This project utilizes a **Hybrid Workflow**:
1.  **SQL (SQLite):** Used for all data manipulation, including:
    * `CTE (Common Table Expressions)` for calculating salary gaps.
    * `GROUP BY` & `HAVING` for regional analysis.
    * `Data Cleaning` (NULL checks).
2.  **Python (Pandas & Seaborn):** Used for:
    * Database connection & ingestion.
    * Visualizing salary trends and distributions.

## Key Findings
* **Significant Growth:** There is a substantial salary gap between **Mid-level** and **Executive** roles, confirming a high ceiling for career growth in this path.
* **Global Opportunities:** While the US dominates, specific countries offer competitive salaries >$20k/year even for Entry-level roles.
* **Employment Type:** Full-time (FT) roles provide the most stability and highest average compensation compared to contract work.

## Files in This Repository
* `Portfolio_V2_DeepDive_Analyst.ipynb`: The main notebook containing the code, queries, and visualizations.
* `ds_salaries.csv`: The dataset used for analysis.
* `Script Modul 11.sql`: Reference SQL script containing the original business questions.

---
*Created by Subki as part of Data Science Portfolio.*
