# HR Analytics Dashboard (Power BI)

This repository contains an interactive HR Analytics Dashboard built in Power BI. The report provides deep insights into workforce data, employee performance, attrition patterns, diversity metrics, and key HR KPIs. It is designed to help HR teams and decision-makers identify trends, reduce attrition, and improve workforce management.

# File Included

HR Analytics.pbix — Complete Power BI dashboard file

# Dashboard Overview

The HR Analytics dashboard helps answer critical organizational questions such as:

What is the overall employee attrition rate?

Which departments have the highest attrition?

What factors contribute most to employee turnover?

How does employee performance vary across roles and experience levels?

What are the key demographic insights (education, age group, gender)?

How satisfied are employees across different departments?
# Data Cleaning & Transformation

Data preparation was done using Power Query, including:

Removed duplicates and irrelevant rows

Standardized column names and formats

Handled missing values

Extracted date components (Year, Month, Tenure categories)

Created conditional columns

Built a clean star-schema model for analysis

# DAX Measures Included

Some of the important DAX measures used:

Total Employees = COUNT(Employee[EmployeeID])

Attrition Count = CALCULATE(COUNT(Employee[EmployeeID]), Employee[Attrition] = "Yes")

Attrition Rate = DIVIDE([Attrition Count], [Total Employees], 0)

Avg Salary = AVERAGE(Employee[MonthlyIncome])


(You can add more based on what you created.)

# Key Features

Attrition Analysis (age, gender, department, salary, job role)

Employee Performance Insights

Satisfaction Level Analysis

Diversity & Demographics Overview

KPIs for HR Monitoring
(Attrition %, Total Employees, Average Salary, Hiring Trend, etc.)

Interactive Filters for deep analysis

🚀 How to Use

Download HR Analytics.pbix

Open in Power BI Desktop

Refresh, customize, or connect to new HR datasets

Explore visuals using slicers for role, education, age, department, and more

# Ideal For

HR Managers

Business Analysts

Workforce Planning Teams

Data Analysts showcasing portfolio dashboards

Organizations analyzing employee behavior & retention

# Author

Gajendra Sawant
Data Analyst | Power BI | SQL | Python
