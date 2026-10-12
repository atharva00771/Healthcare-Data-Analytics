# 🏥 Healthcare Data Analytics

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=230&section=header&text=Healthcare%20Data%20Analytics&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" width="100%"/>
</p>

<p align="center">
  <b>📊 Power BI Dashboard</b> •
  <b>🗃️ SQL Analysis</b> •
  <b>🧮 DAX Practice</b> •
  <b>💰 Billing Analytics</b>
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

**Healthcare Data Analytics** is an end-to-end data analytics project focused on healthcare billing, payment status, and city-wise analysis.

The project combines **Excel/CSV, MySQL, Power BI, and DAX** to transform raw healthcare data into meaningful analytical insights and interactive visualizations.

The goal is to develop practical data analytics skills by solving healthcare-related business questions, writing SQL queries, creating DAX calculations, and building interactive dashboards.

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

| Objective | Description |
|---|---|
| 🏥 Healthcare Analysis | Analyze healthcare billing records |
| 💰 Billing Analysis | Understand billing amounts and payment patterns |
| 💳 Payment Analysis | Compare Completed and Pending payments |
| 🏙️ City Analysis | Compare billing across different cities |
| 🗃️ SQL Analysis | Solve practical analytical questions |
| 🧮 DAX Calculations | Create measures and calculated columns |
| 📊 Visualization | Build an interactive Power BI dashboard |
| 🧠 Business Insights | Convert data into meaningful insights |

---

# 📊 Power BI Dashboard

## 🖼️ Dashboard Preview

<p align="center">
  <img src="images/healthcare-dashboard.png" width="100%" alt="Healthcare Data Analytics Power BI Dashboard"/>
</p>

<p align="center">
  <b>🏥 Interactive Healthcare Analytics Dashboard</b>
</p>

### ✨ Dashboard Highlights

<table>
<tr>
<td align="center">🏥<br><b>Healthcare Records</b></td>
<td align="center">💰<br><b>Billing KPIs</b></td>
<td align="center">💳<br><b>Payment Status</b></td>
<td align="center">🏙️<br><b>City Analysis</b></td>
</tr>
<tr>
<td align="center">📊<br><b>Interactive Charts</b></td>
<td align="center">🔎<br><b>Slicers & Filters</b></td>
<td align="center">📈<br><b>Data Comparison</b></td>
<td align="center">🧠<br><b>Business Insights</b></td>
</tr>
</table>

### 📈 Dashboard Analysis

The dashboard focuses on the following analytical metrics:

- 👥 Total healthcare records
- 💰 Total billing amount
- 📊 Average billing amount
- 💵 Minimum and maximum billing amounts
- 💳 Completed and Pending payment analysis
- 🏙️ City-wise billing comparison
- 🔎 Interactive slicers and filtering
- 📈 KPI-based visualization
- 🧠 Business-focused insights

---

# 🗃️ SQL Data Analysis

MySQL is used to analyze healthcare data and answer practical business questions.

The project covers basic, intermediate, and advanced SQL concepts, with a focus on aggregation, conditional analysis, transaction management, and analytical functions.

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
  <img src="https://img.shields.io/badge/Transactions-795548?style=flat-square"/>
</p>

## 📚 SQL Topics

### 1. Basic SQL

- `SELECT`
- `WHERE`
- `ORDER BY`
- `DISTINCT`
- `LIMIT`
- Comparison operators
- Logical operators: `AND`, `OR`, `NOT`

### 2. Aggregate Functions

- `SUM()`
- `AVG()`
- `COUNT()`
- `MIN()`
- `MAX()`
- `GROUP BY`
- `HAVING`

### 3. Conditional Analysis

- `CASE WHEN`
- `SUM(CASE WHEN...)`
- `COUNT(CASE WHEN...)`
- Conditional aggregation
- Billing amount classification

### 4. Advanced SQL

- `INNER JOIN`
- `LEFT JOIN`
- Subqueries
- `COALESCE()`
- Common Table Expressions (CTEs)
- Nested queries
- Aggregate functions with conditions

### 5. Window Functions

- `ROW_NUMBER()`
- `RANK()`
- `DENSE_RANK()`
- `LAG()`
- `LEAD()`
- `SUM() OVER()`
- `PARTITION BY`
- Running totals
- Ranking billing amounts
- Comparing previous and next records

### 6. SQL Transaction Management

- `START TRANSACTION`
- `COMMIT`
- `ROLLBACK`
- ACID properties
- Transaction isolation levels
- `READ UNCOMMITTED`
- `READ COMMITTED`
- `REPEATABLE READ`
- `SERIALIZABLE`
- Dirty reads
- Non-repeatable reads
- Phantom reads
- Concurrency control
- Deadlocks
- Serializability

*Transaction concepts are practiced separately from healthcare reporting queries to understand how databases maintain data consistency and manage concurrent operations.*

---

# 💡 Healthcare Business Questions

## 💰 Billing Analysis

- What is the total billing amount?
- What is the average billing amount?
- What are the minimum and maximum billing amounts?
- Which records have high billing amounts?
- How can billing amounts be classified into categories?
- Which cities have higher total billing amounts?

## 💳 Payment Analysis

- How many records have Completed payments?
- How many records have Pending payments?
- What is the total billing amount for Completed payments?
- What is the total billing amount for Pending payments?
- What percentage of records have Completed payments?
- How can conditional aggregation compare payment statuses?

## 🏙️ City Analysis

- How many healthcare records are available for each city?
- What is the total billing amount for each city?
- What is the average billing amount by city?
- Which city has the highest total billing amount?
- How can cities be ranked by billing amount?

## 🧮 Conditional SQL Analysis

- How can `CASE` classify billing amounts?
- How can `SUM(CASE WHEN...)` calculate conditional totals?
- How can `COUNT(CASE WHEN...)` count matching records?
- How can `HAVING` filter aggregated results?
- How can `COALESCE()` handle NULL values?

## 📈 Window Function Analysis

- How can billing amounts be ranked?
- What is the difference between `ROW_NUMBER()`, `RANK()`, and `DENSE_RANK()`?
- How can `LAG()` compare the current record with the previous record?
- How can `LEAD()` access the next record?
- How can `SUM() OVER()` calculate running totals?
- How can `PARTITION BY` calculate rankings separately for each city?

---

# 🧮 DAX & Power BI

DAX (Data Analysis Expressions) is used to create measures, calculated columns, and interactive analytical calculations in Power BI.

## 📌 Example DAX Measures

### 1. Total Billing

```DAX
Total Billing =
SUM(Healthcare[bill_amount])
```

**Purpose:** Calculates the total billing amount. Use this measure in a Card, chart, or table.

### 2. Average Billing

```DAX
Average Billing =
AVERAGE(Healthcare[bill_amount])
```

**Purpose:** Calculates the average billing amount.

### 3. Total Healthcare Records

```DAX
Total Records =
COUNTROWS(Healthcare)
```

**Purpose:** Counts the rows in the Healthcare table.

### 4. Completed Payments

```DAX
Completed Payments =
CALCULATE(
    COUNTROWS(Healthcare),
    Healthcare[payment_status] = "Completed"
)
```

**Purpose:** Counts records with Completed payment status.

### 5. Pending Payments

```DAX
Pending Payments =
CALCULATE(
    COUNTROWS(Healthcare),
    Healthcare[payment_status] = "Pending"
)
```

**Purpose:** Counts records with Pending payment status.

### 6. Total Pending Billing

```DAX
Pending Billing =
CALCULATE(
    SUM(Healthcare[bill_amount]),
    Healthcare[payment_status] = "Pending"
)
```

**Purpose:** Calculates the total billing amount for Pending records.

## 📚 DAX Concepts

### Basic DAX

- `SUM()`
- `AVERAGE()`
- `COUNT()`
- `COUNTROWS()`
- `MIN()`
- `MAX()`

### Filter Context & Calculations

- `CALCULATE()`
- `FILTER()`
- `ALL()`
- Conditional calculations
- Filter context
- Context transition

### Conditional DAX

- `IF()`
- `SWITCH()`
- `AND()`
- `OR()`
- `DIVIDE()`

### Calculated Columns

- Billing amount classification
- Conditional categories
- `IF()` with row-level conditions
- `SWITCH(TRUE(), ...)`

### Analytical Measures

- Total billing
- Average billing
- Completed payment count
- Pending payment count
- Pending billing amount
- Percentage calculations
- KPI measures

## 📌 Measures vs Calculated Columns

| Measures | Calculated Columns |
|---|---|
| Calculated when used in a visual | Calculated for each row during data processing or refresh |
| Respond to filter context | Store a value for each row |
| Suitable for totals and averages | Suitable for row-level classification |
| Commonly used in Cards and charts | Commonly used in table fields, slicers, and axes |

**Example measure:**

```DAX
Total Billing =
SUM(Healthcare[bill_amount])
```

**Example calculated column:**

```DAX
Billing Category =
IF(
    Healthcare[bill_amount] >= 5000,
    "High",
    "Low"
)
```

*Note: The threshold of 5000 is an example and should be adjusted to match the dataset.*

---

# 🛠️ Tools & Technologies

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/DAX-512BD4?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSV-239120?style=for-the-badge"/>
</p>

| Technology | Usage |
|---|---|
| 📊 Power BI | Dashboard and data visualization |
| 🗃️ MySQL | SQL queries and database analysis |
| 🧮 DAX | Measures and calculations |
| 📑 Excel / CSV | Data source and data preparation |
| 📈 Data Visualization | Presenting analytical findings |

---

# 🔍 Data Analytics Skills

```text
Data Collection
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Exploratory Data Analysis
      ↓
SQL Analysis
      ↓
DAX Calculations
      ↓
Dashboard Development
      ↓
Business Insights
      ↓
Data Storytelling
```

### 🧠 Skills Practiced

- 🧹 Data Cleaning
- 🔎 Exploratory Data Analysis
- 🗃️ SQL Query Writing
- 🧮 Conditional SQL Analysis
- 📈 SQL Window Functions
- 🔐 SQL Transaction Management
- 📊 Power BI Dashboard Development
- 🧮 DAX Measures and Calculated Columns
- 🔎 Filter Context and Conditional Calculations
- 📈 Data Visualization
- 💼 Business Understanding
- 🧠 Analytical Problem Solving
- 📖 Data Storytelling

---

# 📂 Project Structure

```text
Healthcare-Data-Analytics/
│
├── Healthcare_Dashboard.pbix
│
├── images/
│   └── healthcare-dashboard.png
│
├── SQL/
│   └── healthcare_analysis.sql
│
└── README.md
```

*The structure above represents the intended repository layout. Keep the filenames synchronized with the actual files in your GitHub repository.*

---

# 🚀 Project Progress

| Component | Status |
|---|---|
| 📊 Power BI Dashboard | ✅ Completed |
| 🖼️ Dashboard Screenshot | ✅ Completed |
| 🗃️ Basic SQL Analysis | ✅ Completed |
| 🧮 SQL CASE Analysis | ✅ Practiced |
| 📈 SQL Window Functions | 🔄 Learning & Practice |
| 🔐 SQL Transactions | 🔄 Learning & Practice |
| 🧮 Basic DAX Measures | 🔄 Learning & Practice |
| 🔎 DAX FILTER and ALL | 🔄 Learning & Practice |
| 💡 Business Insights | 🔄 In Progress |
| 📖 Project Documentation | ✅ README Prepared |

*Progress reflects the learning status described for this project. Update the table as each topic or deliverable is completed.*

---

# 🌟 What I Learned

Through this project and its associated practice, I am developing the ability to:

- 📊 Transform raw healthcare data into meaningful dashboards.
- 🗃️ Use SQL to answer healthcare-related analytical questions.
- 🧮 Apply conditional logic using `CASE`.
- 📈 Use window functions for ranking and analytical comparisons.
- 🔐 Understand transactions and database consistency.
- 🧮 Create DAX measures for Power BI reports.
- 🔎 Understand how `CALCULATE()`, `FILTER()`, and `ALL()` affect calculations.
- 💰 Analyze healthcare billing and payment patterns.
- 🏙️ Perform city-wise billing comparisons.
- 📖 Communicate data findings through business-focused storytelling.

---

# 🔮 Future Improvements

- 🚀 Expand the SQL analysis with additional business questions.
- 🧮 Practice advanced DAX calculations and filter context.
- 📊 Improve dashboard interactivity and visual design.
- 🔎 Add more healthcare billing KPIs.
- 📈 Include payment completion percentage and other relevant metrics.
- 🧠 Improve data storytelling with evidence-based findings.
- 🔄 Configure automated data refresh where supported.
- 📊 Add drill-through pages and advanced Power BI visuals.
- 📝 Document SQL queries with explanations and sample outputs.

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
    <img src="https://img.shields.io/badge/GitHub-atharva00771-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/atharvaavhad07/">
    <img src="https://img.shields.io/badge/LinkedIn-Atharva%20Avhad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

# ⭐ Conclusion

Healthcare Data Analytics represents my practical learning journey in data analytics using **Power BI, SQL, DAX, and Excel**.

The project combines healthcare billing analysis, payment status comparisons, SQL problem-solving, DAX calculations, and dashboard visualization.

The overall analytical process can be summarized as:

**📊 Data → 🗃️ Analysis → 🧮 Calculations → 💡 Insights → 📈 Visualization**

<p align="center">
  <b>🚀 Learning Data Analytics, One Project at a Time!</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:141E30,50:243B55,100:00B4DB&height=120&section=footer" width="100%"/>
</p>
