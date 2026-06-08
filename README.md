# Employee Attrition & HR Analytics Dashboard

## 📌 Project Overview
This project is an *interactive Power BI dashboard* designed for HR teams and business leaders to analyze employee attrition, workforce demographics, satisfaction levels, and retention opportunities.

## 📊 Business Problem
High employee turnover increases hiring costs, reduces productivity, and impacts organizational morale. HR teams need data-driven insights to identify why employees leave and when to intervene.

## 🛠️ Tools Used
- Power BI Desktop (Data visualization, DAX measures)
- Power Query Editor (Data cleaning & transformation)
- GitHub (Portfolio hosting)

## 📁 Dataset Description
- *Source:* IBM HR Analytics (Kaggle)
- *Rows:* 1,470 employees
- *Columns:* 35 including Age, Attrition, Department, JobSatisfaction, MonthlyIncome, OverTime, YearsAtCompany, YearsSinceLastPromotion

## 📈 Key Performance Indicators (KPIs)
| KPI | Value |
|-----|-------|
| Attrition Rate | 16.12% |
| Retention Rate | 83.88% |
| Average Monthly Income | ₹6.50K |
| Average Job Satisfaction | 2.73/4 |
| Average Engagement Score | 2.73/4 |
| Overtime Rate | 28.30% |
| Promotion Rate | 39.52% |

## 📊 Dashboard Features
- *KPI Cards* – Top-level metrics at a glance
- *Department-wise Attrition* – Bar chart (Sales, R&D, HR)
- *Overtime vs Attrition* – % of grand total
- *Attrition by Gender* – Donut chart
- *Attrition by Years at Company* – Line chart (peak at 1-2 years)
- *High-Risk Employees Table* – Filters: JobSatisfaction <3, OverTime=Yes, YearsSinceLastPromotion>2
- *Slicers* – Department, Gender, OverTime (interactive filters)

## 🔍 Key Insights (From Dashboard)
1. *Overall attrition rate is 16.12%* – above industry average.
2. *Overtime employees are 2.5x more likely to leave* (28.30% overtime rate contributed to majority of attrition).
3. *Research & Development and Sales departments* have highest attrition counts (961 and 446 respectively).
4. *Most attrition happens within first 2 years* of joining – line chart shows peak at 1-2 years.
5. *Employees with job satisfaction <3 have 45% higher attrition risk*.
6. *Promotion gap >3 years* correlates with high risk in the high-risk table.

## ✅ Recommendations
- *Reduce overtime* – Hire additional headcount for overworked teams, implement overtime pay policies.
- *Strengthen onboarding* – 90-day mentorship programs for new hires, stay interviews at 6/12/18 months.
- *Improve job satisfaction* – Monthly manager 1-on-1 meetings, personalized development plans.
- *Clear promotion paths* – Ensure high performers get promoted within 2 years, transparent career documentation.

## 📸 Dashboard Screenshot
![Dashboard Overview](Screenshort%202026-06-08%20221929.png)

## 🚀 How to Use This Repository
1. Download the .pbix file.
2. Open with Power BI Desktop (free version).
3. Use slicers on the right to filter by department, gender, or overtime.
4. Hover on any visual to see detailed tooltips.

## 📬 Connect with Me
- *GitHub:* [Naziya-shamim](https://github.com/Naziya-shamim)
- *LinkedIn:* https://www.linkedin.com/in/naziya-shamim

## 📚 Acknowledgements
- IBM HR Analytics dataset (Kaggle)
- Power BI community for DAX references
