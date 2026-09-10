# HR Analytics – Employee Attrition, Performance & Workforce Insights

## Project Overview

This project is an end-to-end HR Analytics project developed to analyse employee data and identify important patterns related to employee attrition, workforce structure, salary, job satisfaction, performance and employee experience.

The project follows a complete Data Analytics workflow starting from data preparation and exploratory data analysis to data visualization, Power BI dashboard development and business recommendations.

The main objective is to transform employee data into meaningful insights that can support HR decision-making and employee retention strategies.

---

## Problem Statement

Employee attrition is an important challenge for organizations because employee turnover can increase recruitment and training costs and can affect workforce productivity.

This project aims to analyse employee data to understand the factors and patterns associated with employee attrition.

The analysis focuses on questions such as:

- What is the overall employee attrition rate?
- Which departments have relatively higher attrition?
- Is overtime associated with employee attrition?
- How does job satisfaction relate to attrition?
- How does salary vary across different job roles?
- What are the major characteristics of the workforce?

---

## Dataset Description

The project uses the HR Analytics dataset stored in the `Dataset` folder.

**Dataset Name:** HR_Analytics.csv

**Domain:** Human Resources

**Records:** 1,480 employees

**Columns:** 38

The dataset contains employee-level information such as age, attrition, department, gender, job role, monthly income, overtime, job satisfaction, performance rating and work experience.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Git
- GitHub

---

## Data Cleaning Process

The dataset was inspected before performing analysis.

The following data preparation steps were performed:

1. Inspected the dataset structure, rows and columns.
2. Identified column names and data types.
3. Checked for missing values.
4. Handled missing values in the `YearsWithCurrManager` column.
5. Checked for duplicate records.
6. Removed duplicate records.
7. Performed basic data-quality and consistency checks.
8. Prepared the cleaned dataset for further analysis.

---

## Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the characteristics and patterns in the HR dataset.

The analysis included:

- Descriptive statistics
- Data inspection
- Attrition analysis
- Department-wise analysis
- Overtime vs Attrition analysis
- Job Satisfaction analysis
- Correlation analysis
- Outlier detection

Important patterns identified during EDA were used to create visualizations and the Power BI dashboard.

---

## Visualizations

The following visualizations were created using Python:

1. Employee Attrition Distribution
2. Department-wise Employee Attrition
3. Overtime vs Employee Attrition
4. Job Satisfaction vs Employee Attrition
5. Average Monthly Income by Job Role
6. Employee Age Distribution

These visualizations help communicate important trends, comparisons and relationships in the employee data.

---

## Power BI Dashboard

An interactive Power BI dashboard titled **HR Analytics Dashboard** was created to present important workforce metrics.

### KPI Cards

- Total Employee
- Attrition Rate
- Average Salary
- Average Tenure
- Performance Rate
- Average Performance

### Dashboard Visualizations

- Attrition Analysis
- Department Performance
- Monthly Income by Job Role
- Gender Diversity
- Age Group Distribution
- Job Satisfaction Heatmap

### Interactive Filters

- Department
- EmpID
- JobRole
- Gender
- SalarySlab

The dashboard allows users to interact with the data and analyse workforce metrics from different perspectives.

---

## Key Insights

1. The overall employee attrition rate is approximately 16.1%.

2. Sales shows relatively higher attrition compared with the other departments and therefore requires further retention analysis.

3. Employees who work overtime show substantially higher attrition than employees who do not work overtime.

4. Lower job satisfaction is associated with a higher proportion of employee attrition.

5. Monthly income varies significantly across different job roles.

6. The workforce contains more male employees than female employees.

7. The average employee tenure is approximately 7 years.

---

## Business Recommendations

1. Develop a targeted employee retention strategy for departments and employee groups showing higher attrition.

2. Monitor excessive overtime and review workload distribution to improve employee work-life balance.

3. Conduct a detailed retention analysis for the Sales department.

4. Regularly monitor job satisfaction and employee engagement.

5. Use the Power BI dashboard for continuous HR workforce monitoring and data-driven decision-making.

---

## Conclusion

The HR Analytics project demonstrates how employee data can be transformed into meaningful business insights using Python and Power BI.

The analysis identified important patterns related to employee attrition, overtime, job satisfaction, department, salary and workforce characteristics.

The Power BI dashboard provides an interactive way to monitor these metrics and supports data-driven HR decision-making.

Overall, the project demonstrates a complete Data Analytics workflow from data preparation and exploratory analysis to visualization, dashboard development and business recommendations.
