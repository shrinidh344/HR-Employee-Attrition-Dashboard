# HR-Employee-Attrition-Dashboard
Interactive Power BI dashboard analyzing employee attrition by department, job role, job satisfaction, experience, overtime, and exit reasons.

## Project Overview

The dashboard brings key workforce metrics and attrition-related analysis into one report. Interactive filters let viewers examine different employee segments and compare attrition patterns across organisational dimensions.

## Dashboard Highlights

### Key Performance Indicators
- **Total Employees** — employee population in the selected view
- **Attrition Count** — number of employees recorded as having left
- **Attrition Rate** — attrition as a percentage of the selected employee population
- **Current Employees** — employees remaining after accounting for attrition

### Analysis Views
- Attrition rate by department
- Attrition by job satisfaction rating
- Attrition by experience category
- Attrition by overtime status
- Attrition by job role
- Recorded exit reasons
- Department-level attrition summary

### Interactive Filters
- Department
- Job role
- Gender
- Job level
- Overtime

## Data Model

The report is organised around employee and attrition information, supported by dimension tables for employee details, departments, and dates.

- `Dim_Employee`
- `Dim_Department`
- `Dim_Date`
- `Fact_Attrition`

## Tools and Technologies

- **Microsoft Power BI Desktop** — report development and visualisation
- **DAX** — KPI and attrition calculations
- **Power Query** — data preparation
- **Dimensional data modelling** — organising employee, department, date, and attrition information

## Project File

- `HR-Attrition-Dashboard.pbix` — Power BI report

## Project Objective

Present workforce attrition information in a clear, interactive format to support exploration of employee turnover patterns and comparisons across HR dimensions.
