# **Employee Data Analysis & SQL Project**

## 📌 Project Overview
  This project focuses on **analyzing employee data** using SQL for business intelligence and decision-making.  
  The database used is `employees_mod`, which contains multiple tables such as:

  - `employees`
  - `departments`
  - `dept_emp`
  - `dept_manager`
  - `titles`
  - `salaries`

The goal of this project was to:
  - Perform **detailed exploratory data analysis (EDA)** on the employee dataset.
  - Build **complex SQL queries** to answer real-world business questions.
  - Create **stored procedures, triggers, and functions** for automation.
  - Generate actionable **insights and Tableau dashboards** for HR and management.

---

## 🗂 Dataset
The dataset is a modified version of the popular **MySQL Employees sample database**.  
It includes:
  - Employee demographics (name, gender, hire date, etc.)
  - Salaries and job titles over time
  - Department assignments and manager histories

> **File:** `employees_mod_db.pdf`  
> This file contains the complete schema and structure of the database used.

---

## 🚀 Key Features & Analysis
  The project consists of two major parts:

### **1. Detailed Data Analysis**
Performed deep exploration of each table:
  - Employee distribution by gender, department, and title.
  - Salary trends over time and across departments.
  - Department staffing changes and patterns.
  - Managerial history and assignments.

### **2. Solving 10 Final SQL Challenges**
  Implemented advanced SQL queries to answer real-world HR and organizational questions, including:
  
  | **Exercise** | **Description** |
  |--------------|----------------|
  | **1** | Calculate the average salary of male and female employees in each department. |
  | **2** | Identify the lowest and highest department numbers in `dept_emp`. |
  | **3** | Assign managers based on employee number ranges using a `CASE` statement. |
  | **4** | Retrieve employees hired in the year 2000. |
  | **5** | Filter engineers and senior engineers using `LIKE`. |
  | **6** | Create a **stored procedure** to fetch the last department of an employee. |
  | **7** | Count salary contracts lasting more than a year with salaries ≥ $100,000. |
  | **8** | Implement a **trigger** to prevent future hire dates. |
  | **9** | Write functions to return highest and lowest salary contracts per employee. |
  | **10** | Build a dynamic function to calculate min, max, or salary difference. |

All solutions are documented in:
  - `10-Practice-SQL-Final-Query-Questions.pdf`

---

## 📂 Project Structure
Employee-Data-Analytics-SQL/
│
├── employees_mod_db.pdf # Database schema and structure
├── 10-Practice-SQL-Final-Query-Questions.pdf # Problem set
├── Complete_Analysis.sql # Full SQL analysis script
├── employees_mod.sql # Base SQL dump
├── employees.sql # Original SQL dump
├── Employees_Data_Analysis_Report.twbx # Tableau visualization
└── README.md # Project documentation

markdown
Copy code

---

## ⚙️ Technologies Used
  - **Database:** MySQL  
  - **Visualization:** Tableau  
  - **Tools:** MySQL Workbench, VS Code  
  - **Version Control:** Git & GitHub  

---

## 📊 Tableau Dashboard Guide
  To visualize the insights, this project includes a **Tableau workbook** (`Employees_Data_Analysis_Report.twbx`).

### **Steps to Open the Dashboard**
  1. Install [Tableau Public](https://public.tableau.com/) or Tableau Desktop.
  2. Download the `Employees_Data_Analysis_Report.twbx` file from this repo.
  3. Open Tableau → `File` → `Open` → select the `.twbx` file.
  4. Explore the pre-built dashboards, which include:
     - **Employee Distribution by Department**
     - **Salary Trends by Year**
     - **Gender Diversity Metrics**
     - **Managerial Assignments and Performance**

> **Pro Tip:** You can connect Tableau directly to your MySQL database for live data updates.

---

## 📝 How to Run the Project

### **1. Setup the Database**
`SQL`
 `-- Create a new database`
  `CREATE DATABASE employees_mod;`
  
  `-- Use the database`
  `USE employees_mod;`
  
  `-- Import the schema`
  `SOURCE employees_mod.sql;`
  
  `-- (Optional) Import additional data`
  `SOURCE employees.sql;`
2. Run the Analysis
  Open Complete_Analysis.sql in MySQL Workbench and execute it step by step to replicate the full analysis.
  
  💡 Insights Gained
  Key findings from the analysis include:
  
  Departments with higher salary growth trends over time.
  
  Gender disparities in specific technical roles and departments.
  
  Influence of managerial assignments on department performance.
  
  Detection of salary anomalies using triggers and functions.

🌟 Future Improvements
  Automate reports and KPIs using advanced stored procedures.
  
  Develop a real-time Power BI dashboard integrated with MySQL.
  
  Enhance analytics using Python and Machine Learning models.

👨‍💻 Author
  Chirag Hooda
  
  B.Tech, Civil Engineering @ IIT Guwahati
  
  Passionate about Data Analytics, AI/ML, and Business Intelligence
  
  GitHub: [ChiragHooda](https://github.com/ChiragHooda)
  
  LinkedIn: [linkedin.com/in/chiraghooda](https://www.linkedin.com/in/chirag-choudhary-64a420265/)
  
  Portfolio: [chiragcbsc.wixsite.com/chiragaiportfolio-1](Portfolio)

📜 License
  This project is licensed under the MIT License.
  Feel free to use and modify it with proper attribution.
