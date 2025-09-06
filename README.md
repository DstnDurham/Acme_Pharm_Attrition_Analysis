# HR Employee Attrition Analysis
## Project Overview
This project aims to explore and understand the key factors contributing to employee attrition within an organization. By analyzing patterns in demographic, job-related, and satisfaction data, we seek to uncover actionable insights that can help improve employee retention strategies and overall workplace satisfaction.

### Objectives

* Diagnose attrition drivers: Identify which personal, professional, and environmental factors most strongly correlate with employees leaving the company.
* Determine which employee segments (e.g., departments, job roles, tenure groups) are at higher risk of attrition.
* Create interactive dashboards to highlight patterns in satisfaction, compensation, and work-life balance that may contribute to turnover
* Develop data-driven recommendations to improve employee retention and engagement.

An interactive Power BI dashboard can be downloaded [here](https://app.powerbi.com/reportEmbed?reportId=f5c699c7-bfdb-4c48-a313-d58e231b113c&autoAuth=true&ctid=704ce3d6-a4bf-4e09-8516-d52840c9f7a9) 

<img width="1930" height="1115" alt="image" src="https://github.com/user-attachments/assets/d1ef36f7-35f6-4ac6-a6bd-57f85bdccd46" />


# Data Source and Structure

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/jash312/hr-employee-attrition-datasets), contains detailed information on approximately 13,400 employees. Each record includes a wide range of features spanning demographics, job characteristics, compensation, performance, and satisfaction metrics. The central focus is the Attrition column, which indicates whether an employee has left the company ("Yes") or remained ("No").

### Data Structure Overview
* **Employee Demographics** - Age, Gender, Marital Status, Education Level, Education Field, Distance From Home
* **Employee Details** - Job Level, Department, Job Role, Years at Company, Years in Current Role, Years Since Last Promotion, Years with Current Manager
* **Compensation** - Monthly Income, Percent Salary Hike, Overtime Status
* **Performance and Engagement** - Performance Rating, Job Involvement, Job Satisfaction, Environment Satisfaction, Relatioship Satisfaction, Work-Life Balance, Training Frequency
* **Career History** - Total Working Years, Number of Companies Worked
* **Target Variable** - Attrition (Yes/No)

# Executive Summary: Employee Attrition and Satisfaction Analysis

The organization employs 13,423 individuals, with an overall attrition rate of 23.82%, indicating a significant turnover challenge. This level of attrition carries significant costs in recruitment, training, and lost institutional knowledge. Addressing the factors behind these departures will be critical to stabilizing and growing the organization.
**Attrition Trends**
* 2022 departures: 945 employees
* 2021 departures: 797 employees
* Layoffs in 2022: 181 employees
* Average tenure: 10.57 years
  These numbers reveal rising turnover year over year and a stable core workforce with long service. The spike in layoffs also suggests a need to review restructuring practices.

**Top Reasons for Leaving**
* Retirement: 312 employees
* Medical concerns: 311 employees
* Better pay elsewhere: 300 employees
* Returning to school: 297 employees
* Excessive work hours: 296 employees
While retirement and health-related exits are expected, compensation and workload pressures point to clear opportunities for targeted retention programs.

**High-Risk Segments**
* New hires: 1,344 left within their first year
* Married employees: accounted for 52.47% of exits
* Overtime workers: 64.29% attrition among those logging extra hours
* Lower-paid staff ($1K–$5K/month): 2,182 departed
These cohorts are especially vulnerable to turnover, underscoring the need for improved onboarding, work-life balance initiatives, and equitable pay structures.

**Employee Satisfaction**
Employee satisfaction levels show concerning trends across departments, with Sales leading in reported dissatisfaction:
* Sales: 188 employees rated their satisfaction at the lowest level (Level 1)
* Delivery: 176 employees at Level 1
* Human Resources: 171 employees at Level 1
* Product: 170 employees at Level 1
Across the organization, satisfaction ratings skew toward the lower end, with few employees reporting high satisfaction (Level 4). This pattern suggests widespread disengagement, particularly in frontline and customer-facing roles, and highlights the need for targeted morale and engagement initiatives.

# Recommendations
  * Reduce burnout by limiting overtime and offering flexible schedules and wellness programs.
  * Strengthen onboarding with mentorship and regular check-ins in the first year.
  * Promote career growth with clear paths, training, and phased retirement options.
  * Launch targeted support for high-risk groups (new hires, low-income staff, married employees).
