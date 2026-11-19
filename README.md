# Adecco HR Analytics – Boosting Retention with Data Insights at Adecco India

## Project Overview

This project analyzes employee attrition and workforce characteristics using the IBM HR Analytics Employee Attrition & Performance dataset. The dataset contains 1,470 employees and 35 analytical fields covering demographics, compensation, job characteristics, satisfaction, performance, work-life balance, and attrition.

The analysis was designed to identify patterns associated with employee turnover and provide data-driven insights that can support employee retention strategies.

## Objectives

1. Measure the overall employee attrition rate.
2. Identify departments and job roles with higher attrition.
3. Analyze the relationship between compensation, age, tenure, and attrition.
4. Examine how overtime, job involvement, marital status, business travel, and stock options relate to attrition.
5. Analyze employee satisfaction and performance patterns.
6. Identify factors that may help HR teams prioritize retention efforts.
7. Develop an interactive Excel dashboard to present key HR metrics and analytical findings.

## Tools & Techniques Used

- Microsoft Excel
- Data cleaning and validation
- Excel formulas
- PivotTables and PivotCharts
- Conditional analysis
- Correlation analysis
- Scatter plots and trendlines
- AVERAGEIF, AVERAGE, COUNTIF, and COUNTA
- IF-based helper fields
- Sorting and filtering
- Data visualization
- Excel Dashboard Development
- Interactive Slicers and KPI Cards

## Process

### 1. Data Preparation

- Reviewed the dataset structure and 35 fields.
- Checked data types and categorical values.
- Created an Attrition Numeric helper field to convert Yes/No attrition into 1/0 for quantitative analysis.
- Used formulas, filters, and PivotTables to prepare the data for analysis.

### 2. Exploratory Analysis

- Calculated overall attrition.
- Compared attrition across departments, job roles, gender, marital status, overtime, business travel, and stock option levels.
- Analyzed average age and monthly income of employees who left.
- Examined satisfaction, performance, training, and work-life balance.

### 3. Statistical Analysis

Correlation analysis was used to examine relationships between attrition and selected numerical variables.

**Key correlations with attrition:**

| Variable | Correlation |
|---|---:|
| Age | -0.159 |
| Monthly Income | -0.160 |
| Years at Company | -0.134 |

The correlations were negative but relatively weak, indicating that these variables alone do not explain employee attrition.

Scatter plots with trendlines were also used to investigate relationships such as:

- Age vs Average Job Satisfaction
- Work-Life Balance vs Average Performance Rating
- Years at Company vs Average Job Satisfaction
- Years Since Last Promotion vs Average Performance Rating
- Distance from Home vs Attrition Rate

### 4. Excel Dashboard Development

Developed an Excel dashboard to bring together important HR metrics and visualizations in a single, interactive reporting interface.

**Key Performance Indicators (KPIs)**

The dashboard presents four key metrics:

- Total Employees
- Total Attrition
- Overall Attrition Rate
- Average Employee Age

**Dashboard Visualizations**

Five charts were selected to highlight important workforce patterns:

| No. | Chart Title | Purpose |
|---:|---|---|
| 1 | Attrition Rate by Department | Identifies departments experiencing higher employee turnover. |
| 2 | Performance Rating Distribution | Shows the distribution of employee performance ratings. |
| 3 | Distance from Home vs Attrition Rate | Examines how attrition varies across commuting distances. |
| 4 | Work-Life Balance vs Average Performance Rating | Explores the relationship between work-life balance and performance ratings. |
| 5 | Stock Option Level vs Attrition Rate | Compares employee attrition across different stock option levels. |

**Dashboard Interactivity**

The dashboard is designed to support interactive filtering through Excel Slicers:

- Department
- Gender
- Business Travel
- Job Role

These filters allow users to explore workforce metrics across different employee groups. Connected PivotTables and PivotCharts can respond to slicer selections, making the dashboard more useful for comparative analysis.

**Dashboard Design**

- Organized KPI cards at the top for quick performance monitoring.
- Arranged charts in a structured layout for easier comparison.
- Used consistent formatting, colors, and chart titles.
- Consolidated important findings into one dashboard for convenient HR reporting.

## Key Insights

- Overall employee attrition was approximately **16.1%**.
- Sales had the highest departmental attrition at approximately **20.6%**.
- Sales Representatives showed particularly high attrition at approximately **39.8%**.
- Employees working overtime had substantially higher attrition (30.5%) than those who did not (10.4%).
- Single employees had higher attrition (25.5%) than married (12.5%) or divorced employees (10.1%).
- Employees with no stock option had higher attrition (24.4%) than most employees with stock options.
- The average age of employees who left was approximately **33.6 years**.
- The average monthly income of employees who left was approximately **4,787**.
- Frequent business travel was associated with higher attrition than non-travel.
- The correlations with Age, Monthly Income, and Years at Company were negative but relatively weak, indicating that these variables alone do not explain attrition.

## Business Takeaway

The analysis indicates that employee attrition is associated with multiple workforce factors rather than a single variable. Overtime, job role, marital status, stock options, business travel, and employee involvement provide useful areas for HR teams to investigate when designing retention initiatives.

The Excel dashboard brings these findings together through KPI cards, charts, and interactive filtering, helping HR teams monitor workforce patterns, compare employee groups, and identify areas that may require further investigation.

Overall, the project demonstrates how Excel-based data analysis and visualization can transform raw HR data into meaningful insights that support data-driven workforce and employee retention decisions.
