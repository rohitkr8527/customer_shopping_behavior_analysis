# Customer Shopping Behavior Analysis

End-to-End Data Analytics Project | <img src="https://www.python.org/static/community_logos/python-logo.png" alt="Python" height="40"/> <img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" alt="MySQL" height="40"/>   <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" height="40"/>

<p align="left">
  <img src="https://www.python.org/static/community_logos/python-logo.png" alt="Python" height="40"/>
  <img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" alt="MySQL" height="40"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI" height="40"/>
</p>

---

## Project Overview

This project analyzes **customer shopping behavior** for a retail business to uncover actionable insights that support **revenue growth, customer engagement, and retention strategies**.

Using a combination of **Python, SQL (MySQL/PostgreSQL), and Power BI**, the project demonstrates a complete analytics workflow — from raw data preprocessing to business-ready dashboards and recommendations.

---

## Business Objective

To answer the key question:

> How can consumer shopping data be leveraged to identify purchasing trends, improve customer engagement, and optimize marketing and product strategies?

---

## Dataset Summary

* **Records:** 3,900 customer transactions
* **Features:** 18 columns
* **Key Attributes:**

  * Customer demographics (age, gender, location, subscription status)
  * Purchase details (category, item, amount, season)
  * Behavioral signals (discount usage, frequency, reviews, shipping type)
* **Data Issues Handled:**

  * Missing values (review ratings)
  * Feature standardization
  * Redundant columns

---

## Tools & Technologies

* **Python:** Pandas, NumPy (EDA & preprocessing)
* **SQL:** MySQL / PostgreSQL (analytical queries, segmentation)
* **Power BI:** Interactive dashboard and KPI visualization
* **Jupyter Notebook:** Analysis and experimentation
* **Git & GitHub:** Version control and collaboration

---

## Project Workflow

1. **Data Preparation (Python)**

   * Data loading and inspection
   * Missing value treatment using category-wise median imputation
   * Feature engineering (age groups, purchase frequency)
   * Column standardization and consistency checks

2. **Exploratory Data Analysis (EDA)**

   * Descriptive statistics
   * Behavioral trend identification
   * Validation of assumptions for downstream analysis

3. **SQL Analysis (MySQL/PostgreSQL)**

   * Revenue analysis by demographics
   * Discount behavior and dependency analysis
   * Customer segmentation (New, Returning, Loyal)
   * Subscription vs non-subscription comparison
   * Product performance and ranking using window functions

4. **Dashboard Development (Power BI)**

   * Key KPIs (customers, revenue, ratings)
   * Revenue and sales by category and age group
   * Subscription and loyalty insights
   * Interactive slicers for stakeholder exploration

5. **Reporting & Business Recommendations**

   * Insight-driven conclusions
   * Actionable recommendations aligned with business goals

---

## Power BI Dashboard

The interactive dashboard enables stakeholders to:

* Monitor key performance indicators
* Compare customer segments
* Identify high-revenue products and demographics
* Analyze subscription and loyalty behavior

(Dashboard file: `customer_behavior_dashboard.pbix`)

---

## Key Insights

* Discount usage does not necessarily reduce high-value purchases
* Loyal and repeat customers contribute significantly to revenue
* Certain products show high discount dependency
* Subscription customers demonstrate stronger retention behavior
* Revenue contribution varies noticeably across age groups

---

## Business Recommendations

* Improve subscription conversion by targeting frequent buyers with exclusive benefits
* Optimize discount strategy to balance sales uplift with margin protection
* Strengthen loyalty programs to incentivize repeat purchases
* Improve product positioning by highlighting top-rated and high-demand products
* Focus targeted marketing efforts on high-revenue age segments and express-shipping users

---

## Repository Structure

```
├── shopping_behavior_analysis.ipynb   # Python EDA and preprocessing
├── sql_queries/                       # SQL analysis queries
├── customer_behavior_dashboard.pbix   # Power BI dashboard
├── Customer_Shopping_Behavior_Report.pdf
├── Business_Problem.pdf
└── README.md
```

---

## Skills Demonstrated

* Data cleaning and feature engineering
* Business-focused SQL analysis
* Dashboard storytelling with Power BI
* Translating data insights into business recommendations
* End-to-end analytics project execution

---

## Author

**Rohit**
Aspiring Data Scientist / Data Analyst
