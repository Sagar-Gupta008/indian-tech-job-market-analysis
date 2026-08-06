# 📊 Indian Tech Job Market Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange?logo=mysql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![SQL](https://img.shields.io/badge/SQL-Analytics-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

> ### 🚀 An end-to-end Data Analytics project that analyzes hiring trends, salary patterns, technical skills, work modes, and experience requirements across the Indian technology job market using **Python, MySQL, SQL, and Power BI**.

---

# 📌 Project Overview

The Indian technology industry continues to experience rapid growth, creating strong demand for professionals across domains such as Data Analytics, Artificial Intelligence, Machine Learning, Cloud Computing, Business Intelligence, and Data Engineering.

Understanding this evolving job market requires more than simply counting job postings. Recruiters, job seekers, and business leaders need meaningful insights into hiring demand, salary trends, required technical skills, preferred work modes, and experience expectations.

This project transforms raw technology job posting data into a comprehensive Business Intelligence solution by implementing a complete data analytics workflow consisting of:

* ✅ Data Ingestion
* ✅ Data Cleaning & Preprocessing
* ✅ Feature Engineering
* ✅ Star Schema Data Warehouse Design
* ✅ SQL-Based Business Analysis
* ✅ Interactive Power BI Dashboards
* ✅ Business Insights & Recommendations

The final solution enables users to explore hiring patterns, compare salary trends, identify in-demand skills, and derive actionable business insights from the Indian technology job market.

---

# ❓ Problem Statement

Technology job postings contain valuable information regarding hiring demand, salary ranges, required technical skills, work arrangements, and experience expectations. However, this information is often fragmented and difficult to analyze without a structured analytical approach.

The objective of this project is to transform raw job posting data into meaningful business insights by designing an end-to-end analytics solution that supports data-driven decision-making for recruiters, job seekers, and business stakeholders.

---

# 🎯 Project Objectives

This project aims to:

* Analyze hiring demand across major technology roles.
* Identify the highest-paying job roles and technical domains.
* Examine salary progression across different experience levels.
* Compare Remote, Hybrid, and On-site hiring trends.
* Analyze hiring demand across Indian cities.
* Identify the most in-demand technical skill domains.
* Design a dimensional data warehouse using a Star Schema.
* Develop interactive dashboards using Power BI.
* Demonstrate an end-to-end Data Analytics workflow using industry-standard tools.

## 📋 Project Information

| Category               | Details                                     |
| ---------------------- | ------------------------------------------- |
| **Project Name**       | Indian Tech Job Market Analysis             |
| **Domain**             | Data Analytics                              |
| **Industry**           | Information Technology                      |
| **Dataset**            | Indian Technology Job Postings              |
| **Tools Used**         | Python, Pandas, NumPy, MySQL, SQL, Power BI |
| **Data Warehouse**     | Star Schema                                 |
| **Visualization Tool** | Power BI Desktop                            |
| **Project Type**       | End-to-End Data Analytics Project           |
| **Status**             | ✅ Completed                                 |

# 🛠️ Tech Stack

### Programming & Analysis

* Python
* SQL

### Python Libraries

* Pandas
* NumPy
* Matplotlib

### Database

* MySQL

### Business Intelligence

* Power BI Desktop

### Development Environment

* Jupyter Notebook

### Version Control

* Git & GitHub

# 🔄 Project Workflow

The project follows a complete end-to-end Data Analytics workflow:

1. **Data Collection**

   * Imported the raw Indian technology job postings dataset.

2. **Data Cleaning & Preprocessing**

   * Handled missing values.
   * Removed inconsistencies.
   * Standardized categorical values.
   * Created derived features for analysis.

3. **Data Warehouse Development**

   * Designed a Star Schema.
   * Created dimension tables.
   * Built the central fact table.
   * Loaded transformed data into MySQL.

4. **SQL Business Analysis**

   * Performed analytical SQL queries.
   * Validated warehouse consistency.
   * Generated business metrics.

5. **Power BI Dashboard Development**

   * Built interactive dashboards.
   * Created DAX measures.
   * Added slicers and cross-filtering.
   * Designed business-friendly visualizations.

6. **Business Insights**

   * Identified hiring trends.
   * Analyzed salary patterns.
   * Examined experience requirements.
   * Evaluated work mode preferences.
   * Identified high-demand technical skills.

# 📂 Dataset Overview

The analysis is based on a dataset containing technology job postings across India.

The dataset includes information such as:

* Job Role
* Company Name
* City
* Work Mode
* Experience Required
* Technical Skills
* Salary Information
* Skill Domain

The dataset was cleaned, transformed, and modeled into a Star Schema before performing SQL analysis and Power BI visualization.

# ⭐ Star Schema Design

A dimensional data warehouse was designed using the **Star Schema** approach to improve analytical performance and simplify reporting.

The model consists of one central fact table connected to multiple dimension tables.

![Star Schema](Images/star_schema.png)

