# HR Attrition Analysis Dashboard

An interactive Power BI dashboard analyzing employee attrition, retention risk, and promotion trends across a workforce of 1,470 employees. Built to help HR teams identify which employees are at risk of retrenchment, who's overdue for promotion, and how satisfaction/overtime factors correlate with attrition.

## Problem Statement

Organizations often struggle to spot attrition risk early and ensure promotion decisions are timely and fair. This dashboard consolidates workforce data into a single view to help HR and management identify at-risk employees by department, job role, service tenure, and satisfaction level — enabling proactive retention and promotion decisions.

## Tools Used
- **Power BI** — dashboard design & interactivity
- **DAX** — calculated measures (attrition %, promotion %, satisfaction breakdowns)
- **Power Query** — data cleaning and transformation
- **Excel / CSV** — source dataset (IBM HR Analytics Employee Attrition dataset)

## Key Insights

- Out of **1,470 total employees**, **882 (60%) are male** and **588 (40%) are female**.
- **117 employees (8%)** are flagged as at risk of retrenchment, while **1,353 (92%)** remain on stable service.
- **72 employees (4.9%)** are due for promotion, against **1,398 (92%)** not currently due.
- **5-year tenure** employees form the largest service-year group (196 employees), followed by 1-year tenure (171 employees).
- **Laboratory Technician** and **Manufacturing Director** roles show the highest headcount, while **Manager** and **Research Director** roles show a disproportionately high share of retrenchment risk relative to their size.
- **84.63%** of employees report high job satisfaction, while **15.37%** report low satisfaction — a useful early-warning signal layered against overtime status.
- Distance-from-work analysis shows **63.95%** of employees live "very far," which may correlate with retrenchment/attrition risk and is worth further investigation.

## Dashboard Preview

### Home – Overview KPIs
![Home Overview](screenshots/01_home_overview.png)

### Employee-Level Detail
![Employee Details](screenshots/02_employee_details.png)

### Department & Role Analysis
![Department Analysis](screenshots/03_department_analysis.png)

## Dataset
IBM HR Analytics Employee Attrition & Performance dataset (publicly available sample dataset).

## How to Use
1. Download `HR_Attrition_Dashboard.pbix` from this repository.
2. Open it in **Power BI Desktop** (free download from Microsoft).
3. Use the navigation panel (Home / Action / Details) to explore each view.
4. Filters and visuals are fully interactive — click any bar, slice, or donut segment to cross-filter the dashboard.

## Author
**Nisarga** — transitioning into Data Analytics from a Production Support background, with hands-on experience in SQL, Power BI, and DAX.

https://www.linkedin.com/in/nisargaml22 | https://github.com/Nisargaml22/hr-attrition-analysis-powerbi
