# 🏥 Healthcare Data Analytics

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=230&section=header&text=Healthcare%20Data%20Analytics&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>
</p>

<p align="center">
  <b>📊 Power BI Dashboard</b> •
  <b>🗃️ SQL Analysis</b> •
  <b>💰 Billing Analytics</b> •
  <b>📈 Data Storytelling</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-SQL%20Analysis-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/DAX-Measures-512BD4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-Data%20Source-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-In%20Progress-orange?style=for-the-badge"/>
</p>

---

## 🏥 About The Project

**Healthcare Data Analytics** is an end-to-end data analytics project focused on analyzing healthcare billing and payment data.

The project combines **Excel/CSV, MySQL, Power BI, and DAX** to transform raw healthcare data into meaningful analytical insights and interactive visualizations.

### 🔄 Analytics Workflow

```text
Raw Healthcare Data
        ↓
   Data Cleaning
        ↓
   SQL Analysis
        ↓
   DAX Calculations
        ↓
   Power BI Dashboard
        ↓
 Business Insights
        ↓
 Data Storytelling
```

---

## 🎯 Project Objectives

| Objective              | Description                                     |
| ---------------------- | ----------------------------------------------- |
| 🏥 Healthcare Analysis | Analyze healthcare-related billing data         |
| 💰 Billing Analysis    | Understand billing amounts and payment patterns |
| 💳 Payment Analysis    | Analyze Completed and Pending payments          |
| 🏙️ City Analysis      | Compare billing across different cities         |
| 🗃️ SQL Analysis       | Solve practical healthcare business questions   |
| 📊 Visualization       | Build an interactive Power BI dashboard         |
| 🧠 Business Insights   | Convert data into meaningful insights           |

---

# 📊 Power BI Dashboard

## 🖼️ Dashboard Preview

<p align="center">
  <img src="images/healthcare-dashboard.png" width="100%"/>
</p>

<p align="center">
  <b>🏥 Interactive Healthcare Analytics Dashboard</b>
</p>

### ✨ Dashboard Highlights

<table>
<tr>
<td align="center">🏥<br><b>Healthcare KPIs</b></td>
<td align="center">💰<br><b>Billing Analysis</b></td>
<td align="center">💳<br><b>Payment Status</b></td>
<td align="center">🏙️<br><b>City Analysis</b></td>
</tr>
<tr>
<td align="center">📊<br><b>Interactive Charts</b></td>
<td align="center">🔎<br><b>Slicers</b></td>
<td align="center">📈<br><b>Data Trends</b></td>
<td align="center">🧠<br><b>Business Insights</b></td>
</tr>
</table>

---

# 📈 Dashboard Analysis

The Power BI dashboard focuses on important healthcare and billing metrics such as:

* 👥 Healthcare records analysis
* 💰 Total billing amount
* 📊 Average billing amount
* 💳 Payment status analysis
* 🏙️ City-wise billing analysis
* 🔎 Interactive filtering
* 📈 KPI-based visualization
* 🧠 Business-focused insights

---

# 🗃️ SQL Data Analysis

MySQL is used to analyze the healthcare dataset and answer practical business questions.

The SQL analysis includes **basic, intermediate, and advanced SQL concepts**.

## 🧠 SQL Concepts Practiced

<p align="center">

<img src="https://img.shields.io/badge/SELECT-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/WHERE-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/GROUP%20BY-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/HAVING-4479A1?style=flat-square"/>
<img src="https://img.shields.io/badge/CASE-FF9800?style=flat-square"/>
<img src="https://img.shields.io/badge/JOINS-00A67E?style=flat-square"/>
<img src="https://img.shields.io/badge/CTE-7B61FF?style=flat-square"/>
<img src="https://img.shields.io/badge/Window%20Functions-E91E63?style=flat-square"/>

</p>

### 📚 Topics

* `SELECT`
* `WHERE`
* `ORDER BY`
* `GROUP BY`
* `HAVING`
* Aggregate Functions
* `CASE`
* `JOIN`
* Subqueries
* `COALESCE`
* CTEs
* Window Functions
* `ROW_NUMBER()`
* `RANK()`
* `LAG()`
* `LEAD()`
* `SUM() OVER()`
* `PARTITION BY`

---

# 💡 Business Questions

The SQL analysis focuses on practical healthcare billing questions.

### 💰 Billing Analysis

> What is the total billing amount?

> What is the average billing amount?

> Which records have high billing amounts?

> What is the minimum and maximum billing amount?

### 💳 Payment Analysis

> How many payments are Completed?

> How many payments are Pending?

> What is the total billing amount for Completed payments?

> What is the total billing amount for Pending payments?

### 🏙️ City Analysis

> How many healthcare records are available for each city?

> What is the total billing amount by city?

> Which cities have higher billing amounts?

### 🧮 Conditional Analysis

> How can `CASE` be used to classify billing amounts?

> How can `SUM(CASE...)` count records based on conditions?

> How can `CASE` be combined with aggregate functions?

### 📈 Window Function Analysis

> How can billing amounts be ranked?

> How can `ROW_NUMBER()` be used?

> How can `RANK()` be used?

> How can `LAG()` compare previous values?

> How can `LEAD()` compare next values?

> How can `SUM() OVER()` calculate running totals?

---

# 🧮 DAX & Power BI

DAX is used to create calculated measures and support dashboard analysis.

### 📌 Example Measures

```DAX
Total Billing =
SUM(Healthcare[bill_amount])
```

```DAX
Average Billing =
AVERAGE(Healthcare[bill_amount])
```

```DAX
Completed Payments =
CALCULATE(
    COUNTROWS(Healthcare),
    Healthcare[payment_status] = "Completed"
)
```

### 🧠 DAX Concepts

* `SUM()`
* `AVERAGE()`
* `COUNT()`
* `COUNTROWS()`
* `CALCULATE()`
* `FILTER()`
* Conditional calculations
* KPI measures
* Dashboard calculations

---

# 🛠️ Tools & Technologies

<p align="center">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>

<img src="https://img.shields.io/badge/DAX-512BD4?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>

<img src="https://img.shields.io/badge/SQL-Data%20Analysis-336791?style=for-the-badge"/>

</p>

| Technology            | Usage                          |
| --------------------- | ------------------------------ |
| 📊 Power BI           | Dashboard & Data Visualization |
| 🗃️ MySQL             | SQL Data Analysis              |
| 🧮 DAX                | Measures & Calculations        |
| 📑 Excel / CSV        | Data Source                    |
| 📈 Data Visualization | Business Storytelling          |

---

# 🔍 Data Analytics Skills

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Exploratory Analysis
      ↓
SQL Analysis
      ↓
DAX Calculations
      ↓
Dashboard Development
      ↓
Business Insights
```

### 🧠 Skills Practiced

* 🧹 Data Cleaning
* 🔎 Exploratory Data Analysis
* 🗃️ SQL Query Writing
* 🧮 SQL CASE Analysis
* 📈 Window Functions
* 📊 Power BI
* 🧮 DAX
* 📈 Data Visualization
* 💼 Business Understanding
* 🧠 Problem Solving
* 📖 Data Storytelling

---

# 📂 Project Structure

```text
Healthcare-Data-Analytics/
│
├── 📊 Healthcare_Dashboard.pbix
│
├── 🖼️ images/
│   └── healthcare-dashboard.png
│
├── 🗃️ SQL/
│   └── healthcare_analysis.sql
│
└── 📄 README.md
```

---

# 🚀 Project Progress

| Component                | Status         |
| ------------------------ | -------------- |
| 📊 Power BI Dashboard    | ✅ Completed    |
| 🖼️ Dashboard Screenshot | ✅ Completed    |
| 🗃️ SQL Basic Analysis   | ✅ Completed    |
| 🧮 SQL CASE Analysis     | ✅ Practiced    |
| 📈 SQL Window Functions  | 🔄 In Progress |
| 🧮 DAX Measures          | 🔄 In Progress |
| 💡 Business Insights     | 🔄 In Progress |
| 📖 Documentation         | ✅ Completed    |

---

# 🌟 What I Learned

Through this project, I practiced how to:

> 📊 Convert raw healthcare data into meaningful dashboards.

> 🗃️ Use SQL to solve real-world analytical questions.

> 🧮 Use `CASE` with aggregate functions for conditional analysis.

> 📈 Apply SQL Window Functions for analytical calculations.

> 🧮 Create DAX measures for Power BI dashboards.

> 💰 Analyze healthcare billing and payment patterns.

> 🏙️ Perform city-wise data analysis.

> 📖 Present data using business-focused storytelling.

---

# 🔮 Future Improvements

* 🚀 Add more advanced SQL queries
* 🧮 Add advanced DAX measures
* 📊 Improve dashboard interactivity
* 🔎 Add deeper healthcare analysis
* 📈 Add more analytical KPIs
* 🧠 Improve data storytelling
* 🔄 Add automated data refresh
* 📊 Add more advanced Power BI visuals

---

# 👨‍💻 About Me

<p align="center">

### **Atharva Avhad**

🎓 B.Tech Artificial Intelligence & Data Science Student

📊 Aspiring Data Analyst

💻 SQL • Power BI • Excel • Python • Machine Learning

☁️ AWS Cloud Enthusiast

</p>

<p align="center">

<a href="https://github.com/atharva00771">
<img src="https://img.shields.io/badge/GitHub-atharva00771-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://www.linkedin.com/in/atharvaavhad07/">
<img src="https://img.shields.io/badge/LinkedIn-Atharva%20Avhad-0A66C2?style=for-the-badge&logo=linkedin"/>
</a>

</p>

---

# ⭐ Conclusion

This project represents my practical learning journey in **Data Analytics** using **Power BI, SQL, DAX, and Excel**.

It demonstrates how raw healthcare data can be transformed into:

**📊 Data → 🗃️ Analysis → 🧮 Calculations → 💡 Insights → 📈 Visualization**

<p align="center">
  <b>🚀 Learning Data Analytics, One Project at a Time!</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=120&section=footer"/>
</p>
