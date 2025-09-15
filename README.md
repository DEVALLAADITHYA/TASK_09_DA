# TASK_09_DA

📊 Sales Trend Analysis

Objective:
Perform monthly sales trend analysis to identify peak revenue periods and understand customer buying patterns over time.

Approach:

Extracted YEAR() and MONTH() from order_date

Aggregated monthly revenue using SUM(amount)

Counted unique orders using COUNT(DISTINCT order_id)

Grouped by YEAR-MONTH and sorted chronologically

Identified top 5 months by revenue using ORDER BY total_revenue DESC LIMIT 5

Key Insights:

Peak Months: Highest sales occurred in November & December, indicating strong festive season demand.

Seasonality: Q1 (Jan–Mar) had lower sales volume, suggesting seasonal purchasing patterns.

Revenue vs. Orders: Some months had fewer orders but higher revenue, indicating higher-value purchases.

Actionable Insight: Businesses can plan inventory & marketing campaigns for Q4 to maximize revenue.


<img width="732" height="620" alt="SQL TASK 9 1" src="https://github.com/user-attachments/assets/093d56d4-71f4-4534-abaf-dcba1138f139" />


<img width="931" height="645" alt="SQL TASK 9 2" src="https://github.com/user-attachments/assets/199ec0d0-dab6-4dab-af8c-318ab64ebc58" />


<img width="936" height="646" alt="SQL TASK 9 3" src="https://github.com/user-attachments/assets/125dbf6a-3668-44bb-899b-69058aa50787" />


<img width="1276" height="661" alt="SQL TASK 9 4" src="https://github.com/user-attachments/assets/a7aae08b-994d-483b-a1e1-6fdca45a0ad7" />





