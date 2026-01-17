
# 🦠 COVID-19 Data Exploration – SQL Analytics Portfolio Project

## 📌 Project Overview
This project focuses on **exploratory data analysis of global COVID-19 data using SQL**, combining **case, death, and vaccination datasets** to uncover meaningful trends and insights.  
It demonstrates strong proficiency in **SQL querying, data aggregation, joins, window functions, and analytical thinking**, aligned with real-world **Data Analyst / BI Analyst** responsibilities.

**Tools Used:** SQL (T-SQL compatible)  
**Domain:** Healthcare Analytics | Public Health Data  
**Project Type:** SQL Data Exploration & Analysis

---

## 🎯 Business Objective
Governments, healthcare organizations, and analysts need to understand:
- How COVID-19 spread across countries
- Which regions were most affected
- How vaccination progress impacted populations over time

This project answers questions such as:
- Which countries had the highest infection and death rates?
- What percentage of the population was vaccinated over time?
- How do COVID outcomes relate to population and demographic data?
- How can this data be structured for reporting and dashboards?

---

## 🗂️ Datasets Used
- **CovidDeaths.csv**  
  Contains country-level COVID case counts, deaths, population, and dates
- **CovidVaccinations.csv**  
  Contains vaccination metrics by country and date

**Data Source:** Public global COVID-19 datasets (cleaned and structured for analysis)

---

## 🧱 Project Workflow

### 1️⃣ Data Understanding & Preparation
- Imported COVID deaths and vaccination datasets
- Filtered irrelevant records (e.g., non-country aggregates)
- Standardized date and country fields for accurate joins

### 2️⃣ Exploratory Data Analysis (SQL)
- Analyzed total cases, total deaths, and death percentages
- Compared infection rates relative to population
- Identified countries with highest impact

### 3️⃣ Advanced SQL Analysis
- Joined deaths and vaccination tables using country and date
- Used **window functions** to calculate rolling vaccination totals
- Calculated **percentage of population vaccinated**
- Built reusable SQL views for reporting and visualization

### 4️⃣ View Creation for BI Tools
- Created analytical views such as:
  - `PercentPopulationVaccinated`
- Optimized queries for easy integration with Power BI or Tableau

---

## 📊 Key SQL Techniques Used
- INNER JOIN
- Common Table Expressions (CTEs)
- Window Functions (`SUM() OVER (PARTITION BY ...)`)
- Aggregations (`SUM`, `MAX`, `AVG`)
- Calculated metrics and percentages
- SQL Views for reusable analysis

---

## 📈 Key Insights Generated
- Countries with highest COVID infection rates relative to population
- Death rate comparison across regions
- Vaccination progress trends over time
- Identification of highly affected countries and continents
- Structured datasets ready for dashboarding

---

## 📂 Repository Structure
```

COVID-19-Data-Exploration/
│
├── CovidDeaths.csv
├── CovidVaccinations.csv
├── Covid_Data_Exploration.sql
├── README.md
└── LICENSE

````

---

## ▶️ How to Use This Project
1. Clone the repository:
```bash
git clone https://github.com/Lavanya347/COVID-19-Data-Exploration.git
````

2. Import CSV files into your SQL environment
3. Execute queries from `Covid_Data_Exploration.sql`
4. Use created views for dashboards or further analysis

---

## 🧠 Skills Demonstrated

* SQL Data Analysis
* Exploratory Data Analysis (EDA)
* Business-oriented data questioning
* Analytical problem solving
* Healthcare & public data interpretation
* Data preparation for BI dashboards

---

## 📊 Use Cases

* SQL portfolio demonstration
* Power BI / Tableau dashboards
* Public health reporting
* Interview case study discussions
* Foundation for predictive modeling in Python

---

## 🛡️ License

This project is licensed under the **MIT License**.

---

## 👩‍💻 About the Author

I’m **Lavanya**, a **Data Analyst** with hands-on experience in **SQL, Python, Power BI, and data analytics projects**.
I enjoy analyzing real-world datasets and building portfolio projects that reflect industry-level analytical workflows.

---

## 🔗 Connect with Me

📄 **[View My Resume](https://lavanya347.github.io/Assets/Lavanya_Data_Analyst_Resume.pdf)**  
🔗 **[LinkedIn Profile](https://www.linkedin.com/in/lavanya-lk)**  
📧 **Email:** lavanya347@gmail.com  
🧑‍💻 **[Portfolio](https://lavanya347.github.io/)**

---
