Telco Customer Churn Analysis

This project focuses on analyzing customer churn for a telecom company using SQL for exploratory analysis and Power BI for interactive visualization. The goal is to uncover insights into customer behavior, identify churn drivers, and highlight business areas where retention strategies can be applied.

Project Structure

SQL.txt → Contains SQL queries used for data exploration and churn analysis.

Churn Dashboard.pbix → Power BI dashboard with interactive visualizations.

Tools & Technologies

SQL → Data querying and feature-level churn analysis

Power BI → Visualization and dashboard creation

Dataset → Telco Customer Churn dataset (commonly available on Kaggle
)

Key SQL Insights

Some important findings derived from SQL analysis:

Overall churn rate: ~27% of customers have churned.

Tenure effect: Customers with longer tenure are less likely to churn.

Contract type: Month-to-month contracts have the highest churn, while longer-term contracts reduce churn.

Billing preference: Customers with paperless billing are twice as likely to churn.

Internet service: Fiber optic customers churn more compared to DSL or no internet.

Payment method: Customers using electronic checks churn at the highest rate; credit card users churn the least.

Monthly charges: Customers paying higher monthly charges are more likely to churn.

Service bundles: Having multiple services does not necessarily reduce churn—customers with only one service show the lowest churn rate.

Security & backup: Lack of online security and backup services increases churn likelihood.

Revenue impact: Average monthly revenue loss per churned customer is ~$75.

Power BI Dashboard

The Power BI dashboard provides an interactive view of churn patterns, including:

KPIs: Overall churn rate, total churned customers, revenue loss.

Filters/Slicers: Gender, contract type, payment method, internet service.

Visuals:

Churn by tenure groups

Churn by contract type & payment method

Churn by monthly charges distribution

Customer segments by services subscribed

(You can add screenshots of your dashboard here for better presentation.)


Business Takeaways

Moving customers from month-to-month to long-term contracts can reduce churn.

Encouraging non-electronic payment methods may improve retention.

Offering discounts or loyalty benefits to high-charge customers may reduce churn.

Promoting security and backup services could improve customer stickiness.
