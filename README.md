# Adidas Sales Data Analysis (2020-2021)

![Adidas Logo](https://upload.wikimedia.org/wikipedia/commons/2/20/Adidas_Logo.svg)

## 📊 Project Overview

This project analyzes the Adidas US sales dataset for 2020-2021 to derive actionable business insights. Using Databricks for data engineering and analytics, the project uncovers key trends, performance factors, and growth opportunities through an interactive dashboard.

## 🎯 Objectives

- Understand the primary factors driving sales performance
- Identify seasonal patterns and regional sales trends
- Highlight opportunities for business growth and operational improvements
- Create an interactive dashboard to visualize key business metrics

## 📈 Business Metrics Analyzed

![01](https://github.com/user-attachments/assets/f08713e9-27c8-4d79-8fab-b15d31c323b5)

![Screenshot_1](https://github.com/user-attachments/assets/0cabb174-3679-45b4-9def-472046d359a7)

![Screenshot_2](https://github.com/user-attachments/assets/a5292a50-f06c-4862-9e46-5390a0be7e35)

![Screenshot_3](https://github.com/user-attachments/assets/5b6b39e9-31b3-4f40-b70a-8a8bef8b26ac)


The analysis focuses on the following key performance indicators:

| Metric | Description |
|--------|-------------|
| Total Sales | Overall revenue generated across all channels |
| Total Profit | Net profit across all sales transactions |
| Average Price per Unit | Mean selling price per item |
| Total Units Sold | Aggregate quantity of units sold |
| Monthly Sales Trend | Sales performance patterns over time |
| State-wise Sales | Sales distribution across different states |
| Regional Performance | Sales comparison by geographic regions |
| Product Performance | Sales breakdown by product type |
| Retailer Analysis | Sales contribution by retail partner |
| Category & Gender Analysis | Units sold by product category and gender type |
| City Profitability | Top performing cities ranked by profit |

## 🛠️ Technologies Used

- **Databricks**: Primary platform for data processing, analysis, and dashboard creation
- **Python**: Core programming language for data manipulation and visualization
- **SQL**: For querying and aggregating the sales dataset
- **Visualization Tools**: Built-in Databricks visualization capabilities

## 📁 Dataset

The analysis is based on the Adidas US Sales Dataset containing detailed sales records for 2020 and 2021.

**File Path**: `/FileStore/tables/Adidas_US_Sales_Datasets.csv`

**Key Attributes**:
- Sales amount
- Profit
- Units sold
- Product details
- Retailer information
- Geographic data (region, state, city)

## 📋 Project Structure

```
adidas-sales-analysis/
├── notebooks/
│   └── adidas_sales_analysis.ipynb        # Main Databricks notebook
├── data/
│   └── Adidas_US_Sales_Datasets.csv       # Dataset (reference)
├── screenshots/
│   ├── dashboard.png                      # Dashboard screenshot
│   └── key_insights.png                   # Key findings visualization
├── README.md                              # Project documentation
└── LICENSE                                # License information
```

## ⚙️ Implementation Steps

1. **Data Ingestion**: 
   - Loading the dataset into Databricks
   - Initial data quality assessment
   - Data cleaning and preprocessing

2. **Data Processing**:
   - Feature engineering and aggregation
   - Computing business metrics
   - Temporal and geographic analysis

3. **Analysis & Insights**:
   - Identifying sales patterns and trends
   - Determining key performance drivers
   - Correlation analysis between different factors

4. **Dashboard Creation**:
   - Building interactive visualizations
   - Configuring dashboard parameters
   - Creating drill-down capabilities

## 📝 Key Findings

*Note: This section will be updated after complete analysis*

- Seasonal sales patterns showing peak periods
- Regional performance variations and growth opportunities
- Product category performance insights
- Retailer contribution analysis

## 🔮 Future Work

- Predictive modeling for sales forecasting
- Customer segmentation analysis
- Inventory optimization recommendations
- Marketing effectiveness assessment
