# HR-Analytics-PowerBI
Interactive HR Analytics Dashboard built using Microsoft Power BI to analyse workforce demographics, employee attrition, salary distribution, job satisfaction, and departmental performance. Features interactive filters and KPIs to support data-driven HR decision-making.
## Dashboard Preview

![HR Analytics Dashboard](hr-dashboard.png)
## Project Objective

To analyse employee attrition and workforce patterns through interactive visualisations, identify trends across departments and job roles, and support data-driven HR planning and employee retention strategies.
## Dataset

The dataset is a publicly available HR analytics dataset sourced from a YouTube tutorial. The raw file contains **1,480 records and 37 columns**, including:

- **Demographics:** Age, AgeGroup, Gender, MaritalStatus, Education
- **Job details:** Department, JobRole, JobLevel, BusinessTravel, OverTime
- **Compensation:** MonthlyIncome, SalarySlab, SalaryHike %
- **Satisfaction and performance:** JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance, PerformanceRating
- **Experience:** TotalExperience (Years), YearsatCompany, YearsSincePromotion
- **Target:** Attrition (Yes/No)

After cleaning in Power Query, the final dashboard analyses **1,417 employee records**.
## Data Cleaning (Power Query)

- Removed duplicate employee records
- Handled missing values
- Corrected data types
- Created derived columns such as AgeGroup and SalarySlab
- Filtered the data down to 1,417 valid records for analysis
> Dataset source: [Vedakarna]([link to video](https://www.youtube.com/watch?v=QcTeeBrL6EY))
## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---|
| Total Employees | 1,417 |
| Active Employees | 1,186 |
| Attrition Count | 231 |
| Attrition Rate | 16.3% |
| Average Age | 36.94 years |
| Average Experience | 7.04 years |

## Key Insights

- **Administration** has the highest attrition at 36% of all leavers, followed by **Sales** at 23%.
- The **26-35** age group is the largest in the workforce (588 employees), followed by 36-45 (446).
- **Male employees** account for 63.2% of attrition.
- Attrition is concentrated among employees with **under ~10 years of experience**.
- Employees in the **6-10 LPA** salary slab show the highest attrition count.
  
## Dashboard Features

- Employee attrition analysis by department
- Attrition by salary slab and job role
- Job satisfaction analysis
- Employee distribution by age group and gender
- Attrition trends by years of experience
- Department-wise employee analysis
- Interactive filters for department and age group

## Tools and Technologies

- **Microsoft Power BI**
- **Power Query** for data cleaning and transformation
- **DAX** for calculations and KPIs
- **Data modelling**
- **Data visualisation and dashboard design**

## How to Use

1. Download the `.pbix` file from this repository.
2. Open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Use the Department and Age Group filters to explore the data.

