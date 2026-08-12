# Swiggy_Analysis_Project
Swiggy analysis using SQL and Power Bi

## SQL Techniques

- CTEs (Common Table Expressions)
- Window Functions: `ROW_NUMBER()`, `RANK()`, `DENSE_RANK()`, `NTILE()`, `LAG()`, `LEAD()`
- Running Totals & Rolling Analysis
- Date & Time Analysis
- Subqueries
- Conditional Aggregation
- Customer Segmentation
- Ranking & Comparative Analysis
- Consecutive-Month Customer Analysis
- Revenue Growth & Trend Analysis

## Key Analysis

- Analyzed **25K+ food orders** across **500 customers** to evaluate revenue, order volume, customer behaviour, restaurant performance, and delivery operations.

- Identified **high-value customers** and analyzed customer revenue contribution using CTEs, window functions, customer segmentation, and Pareto analysis.

- Calculated **Month-over-Month (MoM) revenue growth** and running/rolling revenue to identify monthly business growth trends and revenue fluctuations.

- Analyzed **restaurant performance** using order volume, revenue, average order value, customer ratings, and restaurant-level rankings to identify top-performing restaurants.

- Performed **location-level analysis** to compare number of restaurants, deliveries, orders, and total revenue across different locations and identify high-performing demand zones.

- Identified **new vs returning customers** by analyzing customers' first-order dates and subsequent purchase activity to measure customer acquisition and repeat behavior.

- Calculated **average time between customer orders** using `LAG()` and date/time functions to measure purchase frequency and identify customers with longer gaps between orders.

- Performed **customer churn analysis** by identifying customers who had not placed an order in the previous **60 days**, enabling monthly churn-rate tracking and retention analysis.

- Analyzed **delivery performance** using average delivery time, delivery volume, estimated delivery time, and location-level performance to identify operational inefficiencies.

- Analyzed **cuisine preferences** using order volume, customer distribution, and revenue contribution to identify high-demand and high-performing cuisine categories.

- Analyzed **payment-method preferences** across customers and orders to identify the most frequently used payment channels and understand customer transaction behavior.

- Used **conditional aggregation** to calculate KPIs such as delivered orders, cancelled orders, cancellation rate, revenue contribution, and customer activity.


- Ranked **top restaurants, customers, locations, and revenue-generating segments** using `RANK()`, `DENSE_RANK()`, and `ROW_NUMBER()` for comparative performance analysis.

- Used **NTILE()** to segment customers into value-based groups and identify the highest-value customer segments based on revenue/order contribution.
