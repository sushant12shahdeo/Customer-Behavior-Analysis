# Customer Behavior Analysis

Analyzed 3,900 customer transactions using SQL, Python, and Power BI to uncover 
revenue drivers, customer segments, and purchasing patterns for an e-commerce dataset.

## Tools
- Python (Pandas, NumPy) — data cleaning & feature engineering
- MySQL — business insight queries
- Power BI — interactive dashboard
- Excel — reporting

## Key Insights
- Male customers generated 68% of total revenue ($157,890 of $233,081)
- Clothing and Accessories drove over 75% of revenue and sales volume
- 80% of customers are "Loyal" (10+ previous purchases) — a highly retained base
- Only 27% of customers are subscribed, yet subscribers and non-subscribers spend 
  nearly the same per order ($59.49 vs $59.87) — subscription isn't tied to higher spend
- Young Adults are the top-spending age group (~$62K revenue)
- Hats, Sneakers, and Coats have the highest discount rates (~48-50%), signaling 
  price sensitivity in these categories

## Dashboard


![Dashboard Screenshot](dashboard_screenshot.png)



Interactive Power BI dashboard with filters for subscription status, gender, 
category, and shipping type — tracking KPIs, revenue by category, and revenue 
by age group.

## How to Run
1. Load `customer_shopping_behavior.csv`, run the notebook to clean and export to MySQL
2. Execute `queries.sql` for business insights
3. Open `Customer_Behavior_Dashboard.pbix` in Power BI
