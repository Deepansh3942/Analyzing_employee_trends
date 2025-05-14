# Analyzing_employee_trends
A SQL-based analytical project to uncover employee trends in attrition, job satisfaction, and departmental dynamics using the `hrdata` dataset.

# 📊 Analyzing Employee Trends Using SQL

This SQL-based project explores workforce insights using a structured dataset named `hrdata`. It focuses on uncovering patterns related to employee demographics, job roles, education, attrition, and satisfaction through analytical queries. The goal is to help HR departments make data-driven decisions to improve retention, engagement, and workforce planning.

---

## 📁 Dataset Overview

The project uses a table `hrdata` containing fields like:
- `department`
- `age`, `age_band`
- `education`
- `job_role`
- `job_satisfaction`
- `attrition`
- `business_travel`
- `marital_status`

---

## 🧠 Key SQL Insights and Queries

Below are the insights drawn using SQL queries:

1. **Department-Wise Employee Count**  
   Count the number of employees in each department using `GROUP BY`.

2. **Average Age per Department**  
   Determine workforce maturity by computing average age department-wise.

3. **Most Common Job Roles**  
   Use grouped count and `ORDER BY` to identify popular roles within departments.

4. **Job Satisfaction by Education Level**  
   Analyze how education level correlates with job satisfaction.

5. **Age vs. Job Satisfaction**  
   Check if age influences how satisfied employees feel in their roles.

6. **Attrition Rate by Age Band**  
   Use conditional aggregation to calculate attrition percentages.

7. **Departments with Highest/Lowest Job Satisfaction**  
   Rank departments based on average satisfaction and identify the top.

8. **High Attrition Among Specific Education Levels and Age Bands**  
   Drill down into combinations of education level and age band with the highest attrition.

9. **Satisfaction of Frequent Travelers**  
   Evaluate how frequent business travel affects job satisfaction across education levels.

10. **Married Employees' Job Satisfaction by Age Band**  
    Discover which age group of married employees is most satisfied.

---

## ⚙️ How to Use

1. Make sure your RDBMS (MySQL, PostgreSQL, etc.) is running.
2. Import or connect to the database containing the `hrdata` table.
3. Run each SQL block sequentially to generate insights.
4. Modify `LIMIT` or `WHERE` clauses to customize the analysis as needed.

---

## 🔧 Technologies Used

- SQL (Structured Query Language)
- RDBMS: MySQL / PostgreSQL / SQLite (compatible with standard SQL)
- Data Source: `hrdata` table (synthetic or real-world HR data)

---

## 📈 Sample Insight

> The **Sales** department had the highest attrition among employees aged 26–35 with a bachelor's degree, while **Research & Development** showed the highest satisfaction among married employees aged 36–45.

---

## 📃 License

This project is open-source and intended for educational and analytical learning purposes.

---


