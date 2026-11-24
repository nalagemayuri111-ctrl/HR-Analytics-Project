# HR Analytics Dashboard

An interactive Power BI dashboard that analyzes employee attrition and shows which factors are linked to employees leaving.

## Project Overview

Employee attrition is costly for any company. In this project I analyzed an HR dataset of 1,470 employees to find out how many employees left and which factors, such as overtime, job satisfaction, age and job role, are linked to attrition.

## Dataset

- **Source:** IBM HR Analytics Employee Attrition & Performance dataset (a fictional dataset created by IBM data scientists for learning)
- **Records:** 1,470 employees

## Tools Used

- Microsoft Power BI
- Microsoft Excel

## Dashboard Preview

![HR Analytics Dashboard](images/dashboard.png)

## What the Dashboard Shows

**Key numbers (KPI cards)**
- Total employees: 1,470
- Total attrition: 237
- Attrition rate: 16.12%
- Average salary: about 6.5K

**Filters:** gender, department and job role

**Charts**
- Total attrition by job role
- Attrition rate by job satisfaction
- Employees and total attrition by age group
- Attrition rate by overtime

## Key Insights

- **Overtime is linked to much higher attrition.** The attrition rate is 30.53% for employees who work overtime and 10.44% for those who do not, about 3 times higher.
- **Lower job satisfaction goes with higher attrition.** The rate is 22.84% at satisfaction level 1 and 11.33% at level 4. Levels 2 and 3 are in between, at about 16.4% and 16.5%.
- **The youngest employees leave most often.** In the 18-25 age group, 44 of 123 employees left (about 36%). For ages 26-35, 116 of 606 left (about 19%), and for ages 36-45, 43 of 468 left (about 9%).
- **Most leavers come from three roles:** Laboratory Technician (62), Sales Executive (57) and Research Scientist (47), out of 237 in total.

## Recommendations

- Review overtime workloads, since overtime has the strongest link to attrition in this data.
- Track job satisfaction and follow up with employees who report low scores.
- Focus retention efforts, such as mentoring and career paths, on early-career employees.

*These are patterns in the data, not proof of cause. The job role chart shows the number of leavers, not the rate, so roles with more employees naturally show more leavers.*

## Repository Files

| File | Description |
|---|---|
| `HR Analytics.pbix` | Power BI dashboard (open in Power BI Desktop) |
| `images/` | Dashboard screenshot |

## How to Open

1. Download `HR Analytics.pbix`.
2. Open it in Power BI Desktop (free, Windows).

## Author

Mayuri Nalage | nalagemayuri111@gmail.com
