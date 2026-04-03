📊 E-Commerce Data Analysis using SQL

---
📌 Project Overview:
This project analyzes an e-commerce dataset using SQL to extract meaningful insights about customer behavior, order trends, delivery performance, and payment patterns.
---
🎯 Objectives:
- Perform Exploratory Data Analysis (EDA)
- Analyze order trends and seasonality
- Understand customer distribution across states
- Evaluate delivery performance
- Analyze payment methods and installments
--- 
🗂️ Dataset:
The dataset consists of the following tables:
- customers – Customer details (city, state)
- orders – Order timestamps and delivery information
- order_items – Product price and freight value
- payments – Payment type and installments
---
🔍 Key Analysis:
  
📈 Order Trends:
- Monthly order growth
- Seasonality patterns
- Orders by time of day
  
🌍 Customer Analysis:
- State-wise customer distribution
- Regional order patterns
  
💰 Business Analysis:
- Year-over-Year growth (2017 vs 2018)
- Total and average order value
- Freight cost analysis
  
🚚 Delivery Analysis:
- Delivery time calculation
- Estimated vs actual delivery comparison
- Fastest and slowest delivery states

💳 Payment Analysis:
- Orders by payment type
- Payment installments analysis
---
🛠️ Tech Stack:
- SQL (Joins, CTEs, Aggregations, Date Functions)
- Data Analysis
---
  📊 Sample Query:
  
</> SQL
  
-- Monthly Order Trend
SELECT DATE_TRUNC(order_purchase_timestamp, MONTH) AS month,
COUNT(order_id) AS total_orders
FROM orders
GROUP BY month
ORDER BY month;
---
📌 Key Insights:

- Identified trends in order growth over time
- Customer distribution varies across states
- Delivery efficiency differs by region
- Payment patterns show diverse customer behavior
---
  🚀 Conclusion:
  This project demonstrates how SQL can be used to transform raw data into actionable insights for better business decision-making in e-commerce.
---
  🔗 GitHub Repository:
👉 https://github.com/praveenasakthivel2005-cmd/My-Sql
---
🙌 Acknowledgement:
  Feel free to explore, give feedback, and ⭐ the repository if you found it useful!
---
  
