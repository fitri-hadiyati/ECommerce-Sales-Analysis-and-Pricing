# ECommerce-Sales-Analysis-and-Pricing
## 📌 Project Overview
This project aims to analyze e-commerce sales data to uncover business insights that can help increase revenue and improve the efficiency of marketing strategies.
---

## 🎯 Objectives
- Analyzing monthly sales trends.
- Identifying top-selling products.
- Analyzing top revenue contributors.
---

## 📂 Dataset
https://www.kaggle.com/datasets/carrie1/ecommerce-data
---

## Dataset parameter:
- Invoice
- Product
- Quantity
- Price
- Customer ID
- Invoice Date
---

## 🛠 Tools Used
- Postgres SQL
- Power BI 
- GitHub
---

## 🧹 Data Cleaning
Beberapa langkah yang dilakukan:
- Removing duplicate data
- Handling missing values.
- Converting date formats.
- Filter data invalid (quantity <= 0 and unit price <=0)
---

## 📊 Key Insights
### 1. Sales Trend
Analyzing monthly sales to identify seasonal patterns.
- Revenue Trend: Revenue shows a relatively stable trend from the beginning to mid-year, starts increasing in September, peaks in November, and then declines in December. 
                 The patterns of quantity and number of customers are aligned with the revenue trend.
- Customer Trend: The number of customers tends to increase throughout the year, with a significant spike in October–November, followed by a sharp decline in December.
- Seasonality Pattern: There is a clear seasonal pattern in Q4 (especially October–November), which represents the best-performing period. 
                       This is likely influenced by year-end campaigns such as 11.11 and 12.12 promotions.
### 2. Top Products
Identifying products with the highest revenue contribution.
### 3. Revenue contributors
- Revenue is driven by a mix of premium products (high price) and volume products (high quantity)
- The top revenue comes from either very high priced items or very high volume items.
- Main revenue contributors : 
  --High price - low quantity - high revenue. This indicates a premium product with strong revenue per unit.
  --Low price - high quantity - high revenue. This is likely a volume driver product.
---

## 🚀 Recommendations
    1.Use the Top 10 revenue by product data to optimize promotions and related product bundling strategies
    2.December Decline Evaluation: Analyze whether the drop in revenue and number of customers in December is due to reduced promotions, changes in consumer behavior, or stock shortages.
    3.Focus on maintaining volume leaders and optimizing pricing or positioning for mid-tier products to increase contribution.
    4.Mid quantity - low price products (product around 10K-50K in quantity with low average price) contribute moderately to revenue.Opportunity exists to increase either volume or pricing to grow revenue.
    5.Customer Retention: Leverage the surge in customers during Q4 to implement retention strategies, encouraging them to return and make purchases at the beginning of the year.
---

