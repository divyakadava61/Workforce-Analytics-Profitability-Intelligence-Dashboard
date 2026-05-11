# Workforce Analytics & Profitability Intelligence using Microsoft Excel
## Project Overview
This project involves a comprehensive end-to-end data analysis of a global workforce dataset consisting of 9,953 employees. The objective was to evaluate departmental performance, identify profitability drivers across job levels, and uncover hidden demographic trends to optimize operational efficiency.

By leveraging advanced Excel functions and interactive visualizations, I transformed raw HR and financial data into a dynamic Executive Dashboard that allows stakeholders to explore real-time insights via interactive slicers.
## The Dataset
The analysis was performed on a dataset containing the following attributes:

**Core Info:** Employee ID, Name, Email, Gender, DOB.

**Professional Info:** Level, Job Title, Office Location, Offering (Department), Hire Date.

**Financials:** Base Salary, Bonus %, Billable Hours worked/month, Rate per Hour.
## Data Engineering & Enhancement
Beyond the raw data, I engineered several calculated columns to drive deeper business insights:
- **Total Salary:** Base Salary + (Base Salary * Bonus %)

- **Revenue:** Billable Hours * Rate per hr

- **Net Profit Margin:** (Revenue - Total Cost) / Revenue

- **Tenure & Age:** Calculated using DAYS() to determine employee loyalty and demographic brackets.

- **Monthly Run Rate:** Standardized cost metrics for monthly forecasting.
## Technical Toolkit
I utilized a wide array of Excel functions to clean, manipulate, and analyze the data:
- **Lookup & Reference:** XLOOKUP, VLOOKUP, and UNIQUE for data mapping.
  
<img width="662" height="286" alt="image" src="https://github.com/user-attachments/assets/e983f9c3-959e-46c2-8585-5db2c4bdc527" />
<br>
<br>

- **Dynamic Arrays:** Used FILTER() and SORT() to create automated reports for specific criteria (e.g., Mumbai location records, high-earners in Modern Workplace, and current month birthdays).

<img width="1787" height="287" alt="image" src="https://github.com/user-attachments/assets/d9c92a4b-4213-4e4c-8575-ba5180a279e7" />
<br>
<br>

<img width="1675" height="313" alt="image" src="https://github.com/user-attachments/assets/5a811bf7-1d0f-442c-976d-2b1697e4c5e3" />

<br>
<br>
<img width="1270" height="378" alt="image" src="https://github.com/user-attachments/assets/dc0273af-19f5-450c-ab65-a56fd6aacd39" />
<br>
<br>

 - **Text Manipulation:** Cleaned and reorganized data using Flash Fill, Text-to-Columns, and the TEXTSPLIT function.

<img width="592" height="408" alt="image" src="https://github.com/user-attachments/assets/155d15e5-d9cc-4a4d-8b7d-2a5aea88be23" />
<br>
<br>

- **Descriptive Statistics:** Implemented SUMIFS, AVERAGEIFS, and MINIFS/MAXIFS to build a level-wise statistical profile.

<img width="837" height="371" alt="image" src="https://github.com/user-attachments/assets/8813c931-7967-4fe4-8be2-37d709608d3b" />
<br>
<br>

- **Pivot Tables & Calculated Fields:** Architected the backend of the dashboard to ensure "weighted" profit margins remained accurate when filtered.
  
## Key Business Insights
1. Financial Health at a Glance
- Headcount: 9,953 Employees

- Monthly Run Cost: ~2.41 Billion

- Monthly Revenue: ~6.13 Billion

- Overall Profit Margin: 60.69%

- Average Tenure: 14.9 Years (Indicating a highly stable and loyal workforce).

2. Departmental Performance
  
**Data & Analytics** and **Modern Workplace** emerged as the primary revenue engines. Interestingly, while these departments generate significantly higher revenue, the operational costs across all departments remain relatively uniform, making these two the most efficient "Value Centers."

3. The "Profitability Sweet Spot"

The data reveals that **Trainee** and **Analyst** level employees generate the highest profit margins **(89.52%).**

**Recommendation:** Scale the intake and training of these entry-to-mid-level roles. Investing in these levels offers the highest Return on Investment (ROI) due to the low cost-to-revenue ratio.

4. Effort vs. Recognition

The **Scatterplot Analysis** (Hours Worked vs. Rating) showed that performance ratings across the 1–5 scale all fell within the 120–175 hour range.
- **Finding:** Total billable hours is not a determining factor for a high rating.
- **Recommendation:** Management should focus on "Quality of Output" rather than "Volume of Hours" when discussing performance reviews with staff.

5. Revenue vs. Pay Equity
   
In **Sr. Manager** roles, a distinct trend was found: Male employees generate higher average revenue than their Female counterparts, despite having a lower average base salary.

- **Actionable Insight:** This discrepancy poses a significant Employee Churn Risk. Adjusting compensation structures to align better with revenue generation across genders is recommended to maintain talent equity.
  
## The Dashboard
The final output is an interactive dashboard featuring:

**KPI Scorecards:** Employee headcount, Real-time totals for Revenue, Cost, and Margin, average employee tenure.

**Interactive Slicers:** Filter the entire report by Office Location, Offering, Gender, and Job Title.

**Clustered Bar Charts:** Total revenue and cost by deparment (Data & Analytics, Modern Workforce deparments are top revenue contributors), Net profit margin by level (Trainee and Analyst levels are high profit margin levels), Average base salary and revenue generated by gender per level (identifying Sr. Manager roles, male employees generate higher average revenue than their female counterparts, dispite having lower base salary).

**Pie Chart:** Revenue distribution by Age Group (identifying "Old" age brackets as top revenue contributors).

**Dynamic Scatterplots:** Visualizing employee efficiency.

<img width="1442" height="888" alt="image" src="https://github.com/user-attachments/assets/cdde45ca-590d-4877-aada-3ad737776112" />

## How to Use

1. Download the .xlsx file.

2. Open the Dashboard sheet.

3. Use the Slicers on the left to filter the data by your specific region or department.

4. View the Calculations sheet (hidden) to see the Pivot Table architecture.

**Author:** Divya Kadava
**Tools:** Microsoft Excel (Advanced)
**Project Type:** HR & Financial Data Analytics
