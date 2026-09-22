# 🏥 Healthcare Data Analytics

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=230&section=header&text=Healthcare%20Data%20Analytics&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>
</p>

<p align="center">
  <b>📊 Power BI Dashboard</b> •
  <b>🗃️ SQL Analysis</b> •
  <b>🏥 Healthcare Insights</b> •
  <b>📈 Data Storytelling</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-SQL%20Analysis-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/DAX-Measures-512BD4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-Data%20Source-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
</p>

---

## 🏥 About The Project

**Healthcare Data Analytics** is an end-to-end data analytics project focused on understanding healthcare, patient, billing, and financial data.

The project combines **Power BI + SQL + DAX + Excel/CSV** to transform raw healthcare data into meaningful business insights.

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

| Objective              | Description                                    |
| ---------------------- | ---------------------------------------------- |
| 🏥 Healthcare Analysis | Analyze patient and healthcare-related data    |
| 💰 Billing Analysis    | Understand billing and payment patterns        |
| 📊 Visualization       | Build interactive Power BI dashboards          |
| 🗃️ SQL Analysis       | Solve real-world healthcare business questions |
| 🧠 Business Insights   | Convert data into actionable insights          |
| 📈 Data Storytelling   | Present findings through meaningful visuals    |

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
<td align="center">👥<br><b>Patient Analysis</b></td>
<td align="center">💰<br><b>Billing Analysis</b></td>
<td align="center">📊<br><b>Interactive Charts</b></td>
</tr>
<tr>
<td align="center">🔎<br><b>Slicers</b></td>
<td align="center">📅<br><b>Date Analysis</b></td>
<td align="center">📈<br><b>Trend Analysis</b></td>
<td align="center">🧠<br><b>Business Insights</b></td>
</tr>
</table>

---

# 📈 Dashboard Analysis

The dashboard focuses on important healthcare metrics such as:

* 👥 Patient-related analysis
* 💰 Total billing amount
* 💳 Payment status
* 🏙️ City-wise healthcare analysis
* 📅 Date-based trends
* 📊 Billing distribution
* 🔎 Interactive filtering

---

# 🗃️ SQL Data Analysis

SQL is used to answer practical healthcare business questions from the dataset.

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

The SQL analysis focuses on questions such as:

### 💰 Billing

> What is the total billing amount?

> What is the average bill per patient?

> Which patients have high billing amounts?

### 👥 Patients

> How many visits does each patient have?

> Which patients have multiple visits?

### 📈 Previous & Next Bills

> What was the previous bill for each patient?

> What is the next visit's bill?

> What is the difference between current and previous bills?

### 🏙️ Location Analysis

> Which cities generate higher billing amounts?

> How many patients are associated with each city?

---

# 🧮 DAX & Power BI

DAX is used to create calculated measures and support dashboard analysis.

### 📌 Examples

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
| 🗃️ SQL Analysis         | 🔄 In Progress |
| 🧮 DAX Measures          | 🔄 In Progress |
| 📈 Business Insights     | 🔄 In Progress |
| 📖 Documentation         | ✅ Completed    |

---

# 🌟 What I Learned

Through this project, I practiced how to:

> 📊 Convert raw data into meaningful dashboards.

> 🗃️ Use SQL to answer business questions.

> 🧮 Create calculations using DAX.

> 🔎 Analyze healthcare and billing patterns.

> 💡 Present data-driven insights.

> 📖 Build a complete analytics workflow.

---

# 🔮 Future Improvements

* 🚀 Add more advanced SQL queries
* 🧮 Add advanced DAX measures
* 📊 Improve dashboard interactivity
* 🔎 Add deeper patient analysis
* 📈 Add trend-based insights
* 🧠 Improve data storytelling
* 🔄 Add automated data refresh

---

# 👨‍💻 About Me

<p align="center">

### **Atharva Avhad**

🎓 B.Tech Artificial Intelligence & Data Science Student

📊 Aspiring Data Analyst

💻 SQL • Power BI • Excel • Python • Machine Learning

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

This project represents my practical learning journey in **Data Analytics** using Power BI and SQL.

It demonstrates how raw healthcare data can be transformed into:

**📊 Visualizations → 🗃️ Analysis → 💡 Insights → 💼 Business Understanding**

<p align="center">
  <b>🚀 Learning Data Analytics, One Project at a Time!</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=120&section=footer"/>
</p>
