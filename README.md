📊 Olist E-Commerce Analytics Dashboard
📌 Project Overview

This project presents an interactive E-Commerce Sales Analytics Dashboard built using Power BI and the Olist Brazilian E-Commerce Dataset. The dashboard provides insights into revenue, customer behavior, order trends, payment preferences, product performance, and geographical sales distribution.

The goal of this project is to demonstrate data cleaning, data modeling, DAX calculations, and business intelligence skills required for a Data Analyst role.

🎯 Business Objectives
Analyze overall business performance.
Identify top-performing product categories.
Understand customer purchasing behavior.
Track order fulfillment status.
Analyze payment method preferences.
Discover high-revenue states and regions.
Generate actionable business insights.
🛠️ Tools & Technologies Used
Power BI
SQL
DAX
Microsoft Excel
CSV Dataset
Data Cleaning & Transformation
Business Intelligence & Visualization
📂 Dataset Information

Dataset: Olist Brazilian E-Commerce Dataset

The dataset contains information about:

Customers
Orders
Products
Payments
Reviews
Sellers
Geolocation Data
📈 Dashboard Features
1️⃣ Revenue Trend Analysis

Tracks total revenue over time to identify sales patterns and seasonal trends.

2️⃣ Payment Method Analysis

Visualizes revenue contribution by:

Credit Card
Boleto
Voucher
Debit Card
3️⃣ Order Status Distribution

Shows order lifecycle performance including:

Delivered
Shipped
Processing
Approved
Cancelled
Unavailable
4️⃣ KPI Cards

Key business metrics:

KPI	Value
Total Revenue	12.72M+
Total Customers	74K+
Total Orders	76K+
5️⃣ Product Category Performance

Top-performing categories based on revenue generation:

Health & Beauty
Watches & Gifts
Bed Bath & Table
Sports & Leisure
Computers Accessories
6️⃣ State-wise Revenue Analysis

Analyze revenue contribution across Brazilian states to identify high-performing regions.

7️⃣ Revenue vs Orders Analysis

Scatter plot analysis showing the relationship between:

Revenue
Orders
Customers
📊 Key Insights
💰 Revenue Performance
Generated over 12.7 Million in total revenue.
Majority of transactions were completed using Credit Cards.
📦 Order Fulfillment
More than 97% of orders were successfully delivered.
Cancellation and unavailable orders represent a very small percentage.
🛍️ Product Performance
Health & Beauty emerged as the highest revenue-generating category.
Lifestyle and home-related products consistently perform well.
🌎 Geographic Analysis
Certain Brazilian states contribute significantly higher revenue compared to others.
Revenue concentration indicates strong regional demand patterns.
📸 Dashboard Preview
<img width="100%" alt="Dashboard Preview" src="/dashboard/dashboard1.png">
🧮 DAX Measures Used
Total Revenue
Total_Revenue =
SUM(payments[payment_value])
Total Orders
Total_Orders =
DISTINCTCOUNT(orders[order_id])
Total Customers
Total_Customers =
DISTINCTCOUNT(customers[customer_unique_id])
Revenue Per Customer
Revenue_Per_Customer =
DIVIDE(
    [Total_Revenue],
    [Total_Customers]
)
🚀 Project Outcomes

This project demonstrates:

✔ Data Cleaning & Preparation

✔ Data Modeling

✔ DAX Calculations

✔ Business KPI Development

✔ Dashboard Design

✔ Data Visualization

✔ Business Insight Generation
## 📊 Power BI Dashboard

### Dashboard Overview

This interactive dashboard provides insights into:

- Revenue Trends
- Customer Analysis
- Order Performance
- Payment Preferences
- Product Category Performance
- State-wise Revenue Distribution

### Dashboard Preview

<p align="center">
  <img src="../dashboard/dashboard1.png" alt="Olist Ecommerce Dashboard" width="100%">
</p>
📁 Repository Structure
Olist-Ecommerce-Dashboard/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── dashboard/
│   ├── dashboard.pbix
│   └── dashboard_preview.png
│
├── sql/
│   └── ecommerce_analysis.sql
│
├── README.md
👩‍💻 Author

Yashika Garg

Data Analytics | SQL | Power BI | Python

GitHub: https://github.com/yashika-34

⭐ If you found this project useful, don't forget to star the repository! ⭐

This dashboard showcases end-to-end Data Analytics workflow from data preparation to business intelligence reporting. 🚀