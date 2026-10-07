
# HR Analytics Dashboard Using Power BI

## 📌 Project Overview
This project focuses on analyzing employee data to identify key factors affecting employee attrition, workforce demographics, job satisfaction, and overall HR performance. The dashboard provides actionable insights that help HR teams make data-driven decisions to improve employee retention and organizational effectiveness.

## 🎯 Objectives
- Analyze employee attrition trends.
- Identify high-risk employee segments.
- Track workforce demographics.
- Measure job satisfaction levels.
- Support HR decision-making using data visualization.

## 🛠 Tools & Technologies
- **Power BI** – Data visualization and dashboard creation
- **Power Query** – Data cleaning and transformation
- **DAX (Data Analysis Expressions)** – KPI calculations
- **Excel/CSV** – Data source

## 📂 Dataset
The dataset contains employee information such as:
- Employee ID
- Age
- Gender
- Department
- Job Role
- Education
- Marital Status
- Monthly Income
- Years at Company
- Overtime
- Job Satisfaction
- Attrition

## 📊 Dashboard KPIs
- Total Employees
- Attrition Count
- Attrition Rate
- Average Age
- Average Salary
- Average Years at Company

## 📈 Dashboard Visuals
### 1. Attrition by Department
Shows which departments have the highest employee attrition.

### 2. Attrition by Job Role
Identifies job roles with higher turnover rates.

### 3. Attrition by Age Group
Analyzes attrition across different age categories.

### 4. Attrition by Overtime
Compares attrition between employees who work overtime and those who do not.

### 5. Job Satisfaction Analysis
Displays employee satisfaction levels by department and role.

## 🧮 DAX Measures

```DAX
Attrition Count =
CALCULATE(
    COUNT(Employee[EmployeeID]),
    Employee[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees]
) * 100

Average Salary =
AVERAGE(Employee[MonthlyIncome])

Total Employees =
COUNT(Employee[EmployeeID])
```

## 💡 Key Insights
- Employees working overtime show higher attrition rates.
- Certain job roles experience more turnover.
- Younger employees have relatively higher attrition.
- Job satisfaction impacts employee retention.

## 🚀 Business Impact
This dashboard helps HR teams:
- Improve employee retention strategies.
- Identify workforce trends.
- Reduce attrition costs.
- Make data-driven HR decisions.

## 📷 Dashboard Preview
(Add dashboard screenshots here)

## 🔗 GitHub Repository
Add your project files:
- Power BI (.pbix) file
- Dataset (.csv/.xlsx)
- Dashboard screenshots
- README.md

## 👤 Author
**Manikanta Rongala**
- GitHub: [GitHub Profile](https://github.com/manikantarongala00-ship-it?utm_source=chatgpt.com)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/manikanta-rongala-3351b5317/?utm_source=chatgpt.com)
