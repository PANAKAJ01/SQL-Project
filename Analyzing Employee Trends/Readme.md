# ![SQL Logo](https://img.icons8.com/color/48/mysql-logo.png) SQL Projects

These projects demonstrate my proficiency in SQL and my ability to analyze complex data. They showcase my skills in data investigation, visualization, and deriving actionable insights.

---

## 1. Analyzing Employee Trends
[Analyzing Employee Trends.sql](Analyzing Employee Trends.sql) | [Dataset CSV](Analyzing Employee Trends.csv)

**Project Description:**  
This project involved extensive analysis of HR employee data to uncover insights and trends. The data contained information on employees across departments, including demographics, job roles, satisfaction, attrition, and more.  

I utilized SQL to explore the data and answer key business questions to derive actionable insights.

**Tasks Performed:**  
- Performed general data exploration and validation checks on the HR dataset  
- Wrote SQL queries to analyze employee counts, averages, and distributions across dimensions like department, age, and education  
- Identified top job roles and satisfaction levels by department to understand trends  
- Calculated employee attrition rates by age band to pinpoint high-risk groups  
- Analyzed factors related to attrition like age, education, and job satisfaction  
- Compared averages and aggregates across different employee segments  
- Identified top and bottom performers on key metrics like satisfaction and attrition  
- Used SQL techniques like `JOIN`s, `GROUP BY`, `HAVING`, and `CASE` statements for complex analysis  
- Organized and presented findings clearly for leadership consumption  

---

## 2. Exploring Trends in Automotive Industry
[Exploring Trends in Automotive Industry.sql](Exploring Trends in Automotive Industry.sql) | [Dataset CSV](Exploring Trends in Automotive Industry.csv)

**Project Description:**  
This project analyzed a database of car sales information to uncover insights into pricing trends, model performance, and other attributes. The data contained details on car models, pricing history, mileage, transmission types, and more.  

I utilized SQL to explore the data and derive insights to guide pricing, inventory, and marketing strategies.

**Tasks Performed:**  
- Performed general data exploration and validation checks on the cars dataset  
- Analyzed average selling prices by transmission, fuel type, ownership, etc., to reveal pricing patterns  
- Identified highest mileage models to understand durability and maintenance costs  
- Computed price variability within and across models to guide pricing strategy  
- Compared pricing and mileage metrics vs overall averages to find outliers  
- Generated cumulative price trends over time and year-over-year comparisons  
- Computed iterative analytics like moving averages for price smoothing  
- Summarized total mileage by transmission for maintenance planning  
- Ranked models by selling price and analyzed historical averages for top models  
- Used SQL techniques like `WINDOW` functions, `CTE`s, and `JOIN`s for advanced analysis  
- Presented findings in a clear format for stakeholders  

---

## 3. Call Center Data Cleaning
[call_center.sql](call center.sql) | [Dataset CSV](call_center.csv)

**Project Description:**  
This project involved analysis of call center data to gain insights into call volume, customer satisfaction, and service performance. The data was stored in a MySQL table `call_center` within the `call_centerdata` schema.

**Tasks Performed:**  
- Imported the `call_center` table data into MySQL for analysis  
- Performed initial data cleaning:
  - Standardized date format to `YYYY-MM-DD`  
  - Updated blank `csat_score` values to `NULL`  
- Generated table summary statistics:
  - Counted total rows and columns  
  - Analyzed distinct values for sentiment, city, and call_center columns  
- Analyzed call volume:
  - Calculated call counts by day of week  
  - Identified maximum call duration by day  
- Analyzed customer satisfaction:
  - Calculated minimum, maximum, and average CSAT scores  
  - Removed scores of 0 from average calculation  
- Analyzed service performance:
  - Calculated response time counts by call center  
  - Identified best and worst performing centers  

---

## About SQL

SQL (Structured Query Language) is a programming language used to interact with relational databases. Key capabilities include:  
- **CRUD Operations** – Create, Read, Update, Delete data  
- **Joins** – Combine data from multiple tables  
- **Aggregate Functions** – Summations, counts, averages, etc.  
- **Subqueries** – Nested queries for advanced operations  
- **Stored Procedures** – Reusable routines for logic  
- **Window Functions** – Analytics functions for rankings, running totals, and more  

For these examples, Microsoft SQL Server Management Studio was used.

---

## Usage

1. Install a SQL database such as SQL Server Express.  
2. Import any `.sql` files to run the queries.  
3. Modify queries to fit your own database as needed.  
