# Employee Attrition Dashboard Report
The goal of this dashboard is to analyze employee attrition trends and uncover key insights from HR data to support data-driven workforce planning. The dashboard provides a comprehensive view of attrition patterns by gender, age, education, job role, and time — helping HR teams and management make informed decisions to improve employee retention.

# Key Metrics & Features
Attrition Rate (%)
Overall percentage of employees who exited the company (16.1%).

Active vs Attrition Employee Count
Comparison of employees currently active vs. those who exited.

Demographic Breakdown
Attrition rates segmented by:

Gender (e.g., 17% Male vs. 14.8% Female)

Age Groups (highest attrition: under 25 age group - 35.8%)

Education (highest attrition among High School graduates)

Job Role (Sales Representatives showed the highest attrition: 39.8%)

Attrition Trend Over Time
A running total line graph visualizing employee exit patterns over time, highlighting spikes in attrition.

Department Filter
Slicers for department-level analysis (HR, R&D, Sales) to drill down into specific business units.

# Insights
Younger employees (<25) had the highest attrition rate, indicating a need for early-career engagement strategies.

Sales roles showed the most turnover, suggesting possible stress points or job dissatisfaction in client-facing roles.

Lower education levels correlate with higher attrition, possibly due to lower pay scales or growth opportunities.

Attrition is consistent across genders, but male employees have a slightly higher exit rate in this dataset.

# Tech Stack Used
Power BI

DAX for Measures and Insights

Data Preparation: Filter context, calculated columns vs. measures, group bins, running totals, and dynamic narratives.

Interactive slicers and tooltips for enhanced UX.

# How to Use
Filter by Department to drill down on attrition performance.

Hover over visuals to explore tooltips for specific age groups, education levels, or job roles.

Use this dashboard to inform retention strategies, employee engagement plans, and HR interventions.


# Personal Learnings

### Power BI & DAX Technical Implementation
Designed a robust data model using Power BI, managing relationships across employee data, date tables, and derived dimensions.

Applied measures vs calculated columns effectively to balance performance with functional requirements in dashboard interactivity.

Utilized advanced DAX expressions including CALCULATE, FILTER, REMOVEFILTERS, ALLSELECTED, and DIVIDE for dynamic and contextual metrics.

Developed custom KPIs using AVERAGEX, SWITCH(TRUE()), and other row and filter context-aware functions.

Leveraged functions like ROUNDUP, MAX, and RANKX to produce formatted, business-aligned outputs across cards and visuals.

