# 📊 HR Analytics Dashboard – Power BI

## 📌 Project Overview
This project focuses on analyzing **employee attrition trends** and identifying **key factors driving employees to leave** the company. The dashboard presents HR insights through interactive visualizations, enabling data-driven decision-making for retention strategies.

Using **Power BI**, I built an end-to-end HR analytics dashboard, integrated **calculated measures** and **DAX formulas**, and designed KPIs that **tell a cohesive story** about workforce attrition.

---

## 🎯 Objectives
- Identify **primary factors** influencing employee attrition.
- Present **KPI-driven insights** to HR leadership for proactive retention strategies.
- Provide **drill-down views** by department, age group, education, salary slab, and job satisfaction.

---

## 🛠 Tools & Skills Used
- **Power BI Desktop** – Dashboard creation & data modeling
- **DAX (Data Analysis Expressions)** – Custom measures and calculated columns
- **Data Cleaning & Transformation** – Power Query
- **HR Analytics** – Attrition pattern analysis & KPI design

---

## 📈 Key Insights
- **Overall Attrition Rate:** 16.17% (229 out of 1,413 employees)
- Highest attrition observed among:
  - **Laboratory Technicians** (60 exits)
  - **Sales Executives** (55 exits)
  - **Research Scientists** (44 exits)
- **Salary Influence:** Majority attrition from employees earning **up to 5k** monthly.
- **Tenure Impact:** Attrition peaks within employees with **1–3 years of service**.
- **Age Factor:** Age group **26–35 years** shows highest attrition.

---

## 📌 KPIs Designed
- Total Employees
- Total Attrition & Attrition Rate
- Average Age of Employees
- Average Monthly Salary
- Average Years at Company

---

## 🧮 DAX Measures Created
- **Attrition Rate** = `DIVIDE([Attrition Count], [Total Employees])`
- **Average Salary** = `AVERAGE('HR Data'[MonthlyIncome])`
- **Tenure Buckets** for attrition analysis
- **Satisfaction Score Calculations** per job role

---

## 📊 Dashboard Preview
![HR Analytics Dashboard](PowerBI_project_HR_Analytics.png)

---

## 📂 Project Files
- **Dashboard PDF:** [View PDF](./PowerBI_project_HR_Analytics.pdf)
- **PBIX File:** [Download PBIX](./PowerBI_project_HR_Analytics.pbix)
- **Dataset:** [CSV File](./HR_Analytics.csv)

---

## 💡 Conclusion
The HR Analytics Dashboard enables HR teams to **visualize attrition patterns**, identify high-risk segments, and **make informed retention decisions** using KPI storytelling and DAX-powered insights.
