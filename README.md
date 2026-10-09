# KPI Dictionary & Data Quality Contract

## 1. Project Overview

The **KPI Dictionary & Data Quality Contract** project focuses on converting ambiguous business requirements into clearly defined, measurable Key Performance Indicators (KPIs) and establishing data quality validation rules for retail order data.

The project uses retail datasets to explore business metrics, document KPI definitions, identify potential data quality issues, and improve the reliability of business reporting.

## 2. Project Objectives

* Define business KPIs with clear meanings and calculation formulas.
* Explore and understand retail order datasets.
* Identify missing values and duplicate records.
* Validate data types, business rules, and data consistency.
* Document data quality checks and their results.
* Support reliable, consistent, and data-driven business decisions.

## 3. Datasets

This project uses two datasets:

* **Retail Orders Raw Dataset:** Used to explore retail order records and analyze business information.
* **Retail Data Dictionary Dataset:** Used to understand dataset fields, column meanings, and relevant business definitions.

The datasets are analyzed using Python in Google Colab.

## 4. Tools and Technologies

* **Python:** Data analysis and validation.
* **Pandas:** Data manipulation and quality checks.
* **Google Colab:** Cloud-based notebook execution.
* **GitHub:** Version control, project documentation, and code sharing.

## 5. KPI Dictionary

The project can include the following retail KPIs, subject to the available dataset columns and confirmed business definitions.

| KPI                 | Definition                             | Example Formula                                      |
| ------------------- | -------------------------------------- | ---------------------------------------------------- |
| Total Sales         | Total value of eligible sales          | Sum of sales amount                                  |
| Total Orders        | Number of unique orders                | Count of distinct order IDs                          |
| Average Order Value | Average sales value per order          | Total sales / Total orders                           |
| Total Quantity      | Total units sold                       | Sum of quantity                                      |
| Return Rate         | Percentage of orders or items returned | Returned orders or items / Corresponding total × 100 |

The formulas must be aligned with the actual column names, transaction grain, return rules, and business requirements before final use.

## 6. Data Quality Checks

The notebook can evaluate the following data quality dimensions:

* **Completeness:** Identify missing values in important fields.
* **Uniqueness:** Detect duplicate records or duplicate identifiers where uniqueness is expected.
* **Validity:** Check invalid quantities, sales values, dates, and categorical values.
* **Consistency:** Verify that related fields and business rules agree.
* **Accuracy of calculations:** Validate KPI calculations against their documented formulas.

Actual findings and pass/fail results should be recorded from the notebook outputs.

## 7. Project Workflow

1. Load both datasets into Google Colab.
2. Inspect rows, columns, data types, and dataset structure.
3. Review the data dictionary to understand field definitions.
4. Define KPIs and document their formulas.
5. Execute data quality validation checks.
6. Review findings and investigate data issues.
7. Summarize the results and recommendations.
8. Publish the notebook and documentation through GitHub.

## 8. Expected Deliverables

* Executed Google Colab notebook.
* Retail datasets used for analysis.
* KPI definitions and calculation formulas.
* Data quality validation results.
* Summary of findings and recommendations.

## 9. Business Value

A clearly defined KPI dictionary helps business teams interpret metrics consistently. Data quality contracts establish expectations for reliable data and make it easier to identify problems before they affect business reporting and decision-making.

## 10. Conclusion

This project demonstrates a structured approach to retail data analysis, KPI documentation, and data quality validation. It aims to improve consistency in business metrics and establish a foundation for trustworthy reporting.

## Author

**Ushasvi Gunda**

B.Tech — Artificial Intelligence and Data Science

Marwadi University

## Repository Contents

* `README.md` — Project documentation.
* Google Colab notebook (`.ipynb`) — Analysis and implementation.
* Retail datasets — Input data used for the project.

---

*Note: KPI formulas, validation rules, and findings must be confirmed against the actual datasets and executed notebook before the project is submitted.*
