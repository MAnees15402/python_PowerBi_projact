# Sales Data Analysis

## Problem Statement
The objective of this project is to analyze sales data from an e-commerce store to identify key trends in revenue, order volume, and customer purchasing behavior. The insights derived can help optimize sales strategies, inventory management, and customer engagement.

## Tools Used
- **Python**: For data manipulation and analysis
- **Pandas**: To clean and structure data
- **Plotly**: For interactive visualizations
- **Power BI**: For dashboard creation and advanced analytics

## Data Analysis
### 1. Data Preparation
- Loaded the `Sample - Superstore.csv` dataset
- Converted date fields (`Order Date` and `Ship Date`) to datetime format
- Extracted new features: order month, year, and day of the week

### 2. Sales Trends
- Aggregated total sales per month to identify revenue trends
- Computed maximum and minimum monthly sales to detect peak and slow months
- Created line charts to visualize monthly sales patterns

### 3. Customer Behavior Analysis
- Examined order frequency per customer
- Identified top-selling products and categories
- Evaluated regional sales distribution

### 4. Shipping and Order Processing Insights
- Analyzed the average time between order and shipping date
- Compared sales performance across different shipping methods

## Insights
- **Sales Trends**: Certain months show significantly higher revenue, indicating seasonal trends.
- **Customer Purchases**: A small percentage of customers contribute to the majority of sales.
- **Product Performance**: Some product categories consistently outperform others.
- **Shipping Efficiency**: Delays in shipping can impact customer satisfaction and repeat purchases.

## How to Use
1. Clone this repository.
2. Install required Python libraries (`pandas`, `plotly`, etc.).
3. Load the dataset and run the Jupyter notebook to generate insights.
4. Use Power BI for further visual exploration and dashboard creation.

## Future Improvements
- Incorporate machine learning to predict future sales trends.
- Automate data updates for real-time analytics.
- Enhance Power BI dashboards with more interactive filters and KPIs.

---
This project provides a comprehensive analysis of sales data to help businesses make data-driven decisions.


