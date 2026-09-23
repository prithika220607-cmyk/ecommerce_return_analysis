# ecommerce_return_analysis
analysis of e_commerce product return rates using python, pandas, and matplotlib
## 1. Problem Statement

The objective of this project is to investigate e-commerce product return rates and identify factors that may be associated with product returns.

## 2. Dataset Description

The dataset contains 5,005 records and 8 columns before data cleaning.

Main columns include:

- Order_ID
- Customer_ID
- Category
- Product_Price
- Discount
- Delivery_Days
- Customer_Rating
- Returned

Data cleaning was performed by removing duplicate rows and handling missing numerical values.

## 3. Statistical Methods

The following methods were used:

- Descriptive statistics
- Return rate calculation
- Category-wise return rate analysis
- Discount-wise return rate analysis
- Delivery-time return rate analysis
- Customer-rating return rate analysis
- Correlation analysis
- Product price outlier analysis using IQR

## 4. Return Findings

The cleaned dataset contains 5,000 orders.

- Returned orders: 1,108
- Overall return rate: 22.16%

Return rates were also analyzed based on product category, discount level, delivery time, and customer rating.

## 5. Visual Insights

The project includes visualizations for:

- Return Rate by Category
- Return Rate by Discount
- Return Rate by Delivery Days
- Return Rate by Customer Rating
- Product Price Outlier Analysis
- Correlation Heatmap

## 6. Business Recommendations

1. Monitor categories with higher return rates and investigate the reasons for frequent returns.

2. Review products with high return rates and improve product descriptions, images, and specifications.

3. Monitor the relationship between discounts and returns.

4. Improve delivery performance for orders with longer delivery times.

5. Monitor customer ratings and investigate products receiving lower ratings.

6. Regularly analyze return data to identify problem products and improve customer satisfaction.

## 7. Future Scope

- Build a machine learning model to predict product returns.
- Analyze customer feedback using sentiment analysis.
- Create an interactive dashboard using Power BI or Tableau.
- Develop a system to identify products with high return risk.
