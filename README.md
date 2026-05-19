# 📊 Employee Engagement - Exploratory Data Analysis (EDA)

Welcome to the **Thiranex EDA** project! This repository focuses on analyzing employee engagement data to uncover key workforce trends, understand correlations between variables, and identify factors affecting workplace satisfaction and performance.

---

## 🚀 Project Overview

Exploratory Data Analysis (EDA) is the crucial first step in our data science workflow. Before jumping into predictive modeling, we use EDA to "listen to the data," identify patterns, spot anomalies, and form hypotheses based on visual and summary statistics.

### 🎯 Key Objectives
* **Understand Workforce Demographics:** Analyze variables like `Years_At_Company` and `Department` distributions.
* **Analyze Compensation & Performance:** Evaluate how `Monthly_Salary_USD` relates to performance scores.
* **Investigate Burnout & Satisfaction:** Examine the impact of `Overtime_Hours_Mth` on employee `Satisfaction_Score`.

---

## 🛠️ Tech Stack & Dependencies

This analysis is built using **Python 3.12** and the core data science ecosystem:

* **Pandas:** For data manipulation and structural analysis.
* **NumPy:** For efficient numerical operations.
* **Matplotlib & Seaborn:** For generating clean, high-quality statistical visualizations.

> 💡 **Note for VS Code / Codespaces Users:** If you see Pylance missing module warnings (`reportMissingModuleSource`), ensure your local virtual environment or kernel has the dependencies installed via pip.

---

## 📊 Key Insights from the Data

Based on our initial descriptive statistics, here is what the workforce landscape looks like:

### 1. Descriptive Summary
| Metric | Mean | Median (50%) | Range |
| :--- | :--- | :--- | :--- |
| **Years at Company** | 5.23 years | 5.30 years | 0.5 - 10.0 years |
| **Monthly Salary** | $7,409.74 | $7,411.24 | $4,204.49 - $10,930.64 |
| **Monthly Overtime** | 19.65 hours | 18.00 hours |