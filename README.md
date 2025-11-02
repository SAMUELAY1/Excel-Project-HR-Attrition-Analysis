## EXCEL - HR- ATTRITION - ANALYSIS

## OVERVIEW
This project explores employee attrition using an HR dataset from the IBM HR Analytics sample data. The goal is to identify key factors influencing employee turnover and provide actionable insights to improve retention.
The analysis was performed entirely in Microsoft Excel, using formulas, PivotTables, and visual dashboards to present insights clearly and interactively


## Objectives
•	Analyze employee attrition trends across demographics, departments, and job roles.
•	Identify correlations between attrition and factors such as income, satisfaction, and work-life balance.
•	Build an interactive HR dashboard summarizing key metrics and insights.


## Key Excel Features Used
•	VLOOKUP – for cross-referencing related employee information (if needed).
•	IF statements – for classifying data (e.g., attrition status).
•	COUNTIFS / AVERAGEIFS – to calculate KPIs such as total employees, attrition rate, and average income of employees who left.
•	PivotTables & PivotCharts – to summarize and visualize data by department, job role, and education field.
•	Slicers – for dynamic filtering of dashboards by gender, department, or job role.


## Dataset Description
The dataset contains 1,471 employee records and the following key columns:
Column    	Description
Age	        Employee’s age
Attrition 	Whether the employee left the company
Department	Department name (Sales, R&D, HR, etc.)
JobRole	     Employee’s job title
Gender	     Male or Female
MonthlyIncome	Monthly salary of the employee
EducationField	Field of education
EnvironmentSatisfaction	Satisfaction level with work environment
JobSatisfaction	Overall job satisfaction
WorkLifeBalance	Work-life balance rating
YearsAtCompany	Number of years spent in the company

## Dashboard Overview
The project includes the following dashboards:
1.	Attrition Summary Dashboard – overall attrition rate, total employees, and key metrics.
2.	Department-Level Dashboard – attrition by department and average satisfaction.
3.	Demographics Dashboard – insights by age group, gender, and job level.
 using PivotTables, slicers, and conditional formatting for interactivity

## Example KPI Calculations
Metric	Formula	Description
Total Employees	=COUNTA(J2:J1471)	Counts all employees
Total Attrition	=COUNTIFS(AJ2:AJ1471, "Yes")	Counts employees who left
Attrition Rate	=COUNTIFS(AJ2:AJ1471,"Yes") / COUNTA(J2:J1471)	Calculates turnover percentage
Average Monthly Income (Attrition)	=AVERAGEIFS(S2:S1471, AJ2:AJ1471, "Yes")	Average income of those who left

## Insights
•	Higher attrition observed among employees with lower satisfaction levels






