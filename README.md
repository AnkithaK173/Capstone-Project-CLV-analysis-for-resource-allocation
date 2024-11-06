# Project Title: "Optimizing Inventory and Sales Strategies for AmazingMartEU2: A Data-Driven Solution for Enhanced Business Logistics"

## Project Overview

This project aims to enhance the logistics and sales strategies for AmazingMartEU2 by analyzing historical data to make data-driven decisions on inventory management, customer segmentation, and sales forecasting. The project provides insights into seasonal sales trends, customer purchasing behavior, and the impact of discounts on profitability.

## Purpose

The primary objective is to:
- Optimize inventory levels by understanding product demand.
- Segment customers for tailored marketing and retention strategies.
- Forecast sales to adjust seasonal inventory and promotions.
- Evaluate discount strategies to maintain profit margins.

## Dataset Overview

The dataset includes transaction-level data with details on:
- **Order Date** and **Sales**: Key for trend analysis and forecasting.
- **Discounts** and **Profit**: For analyzing discount impact on profit margins.
- **Region** and **Product Category**: Useful for regional and categorical sales trends.
- **Shipping Cost**: Helps evaluate logistical costs by region.

---

## Project Steps

### Step 1: Data Preprocessing and Exploration
- **Loading and Inspecting Data**: Used Python `Pandas` to load data and inspect columns.
- **Data Cleaning**: Handled missing values and standardized column names for consistency.

### Step 2: SQL Queries for Data Extraction
Example queries used:
- Top products by sales and regions with highest demand.
- Average monthly sales by category.
- Customer segmentation by purchase frequency and average order value.

### Step 3: Exploratory Data Analysis (EDA)
- **Trend Analysis**: Monthly sales trends were visualized to identify seasonal peaks.
- **Inventory Insights**: Stock levels were compared to demand to highlight high and low turnover products.
- **Profit and Discount Analysis**: Impact of discounts on sales volume and profit margins.

### Step 4: Machine Learning Models
#### Regression for Sales Forecasting
- **Algorithm Used**: Linear regression to predict future sales based on historical patterns.
- **Purpose**: To adjust stock levels in advance for high-demand periods.

#### Classification for Inventory Replenishment
- **Algorithm Used**: Random Forest to classify products based on demand levels (high, medium, low).
- **Purpose**: Helps prioritize inventory replenishment for popular items.

#### Customer Segmentation (Clustering)
- **Algorithm Used**: K-means clustering on Recency, Frequency, Monetary (RFM) values.
- **Purpose**: Enables targeted marketing strategies for different customer segments.

### Step 5: Visualizations and Dashboard Creation
- **Tableau Dashboards**: Interactive dashboards displaying KPIs like sales, profit margins, and high-demand regions.
- **Python Visualizations**: Bar charts, line graphs, and scatter plots to illustrate key trends and insights.

### Step 6: Insights, Recommendations, and Conclusion

- **Inventory Optimization**: Recommendations on replenishing stocks based on high-demand regions and seasonal trends.
- **Customer Retention**: Identifying high-value customer segments to target with loyalty programs.
- **Discount Strategy**: Suggested optimal discount levels to increase sales without sacrificing profit margins.

---

## Algorithms Used

1. **Regression (Sales Forecasting)**:
   - **Goal**: Predicting monthly sales to maintain optimal inventory levels.
   - **Benefit**: Helps manage seasonal stock variations.

2. **Classification (Inventory Prioritization)**:
   - **Goal**: Classify products by demand level to prioritize inventory replenishment.
   - **Benefit**: Minimizes stockouts and reduces excess inventory.

3. **Clustering (Customer Segmentation)**:
   - **Goal**: Segment customers based on RFM values for targeted marketing.
   - **Benefit**: Tailored strategies to improve customer retention and sales.

---

## Conclusion

This project provides actionable insights that help AmazingMartEU2 improve its logistics, inventory, and customer engagement strategies. By leveraging data analytics, AmazingMartEU2 can make informed decisions on stock levels, discounting, and customer retention. The predictive analysis further allows the business to plan for future demand, ultimately contributing to better resource allocation and profitability.

---

