# Comprehensive Sales Analysis for Retail Data

📊 Project Overview

This project is a thorough analysis of retail sales data to uncover insights on sales trends, customer behaviors, product performance, and more. The goal is to leverage data analytics and machine learning techniques to extract actionable insights that can help optimize business strategies and enhance decision-making.

🛠 Features

- Data Cleaning: Removing duplicates, handling missing values, and converting data types for seamless analysis.

- Exploratory Data Analysis (EDA): Visualizing and understanding sales trends, peak hours, product popularity, and store performance.

- Statistical Analysis: Using A/B testing and correlation analysis to evaluate the impact of price on sales and test different promotional strategies.

- Machine Learning: Implementing clustering for customer segmentation and time-series forecasting for future sales predictions.

- Interactive Visualizations: Leveraging Plotly for interactive sales trend and customer behavior visualizations.

📝 Key Analysis Sections

1. Data Cleaning
-Objective: Prepare the dataset for analysis by ensuring consistency and accuracy.
-Tasks:
  * Remove duplicate rows.
  * Handle missing values.
  * Convert date columns to the appropriate format.
2. Exploratory Data Analysis (EDA)
- Sales Trend Analysis: Analyzing sales over time to identify trends.
- Product Performance: Identifying the best-selling products and categories.
- Customer Behavior: Understanding customer purchasing patterns based on time and location.
- Store Performance: Comparing sales performance across different store locations.
3. Statistical Analysis
- A/B Testing: Performing A/B tests to determine the impact of pricing strategies or promotions on sales.
- Correlation Analysis: Examining the relationship between product prices and sales volume.
4. Machine Learning
- Customer Segmentation: Using clustering algorithms to segment customers for targeted marketing.
- Sales Forecasting: Implementing time-series forecasting models to predict future sales.
5. Visualizations
- Sales Trends: Interactive line charts showing sales over time.
- Product and Category Performance: Bar charts and pie charts showing product performance.
- Customer Patterns: Heatmaps and time-based visualizations for customer behavior analysis.


🚀 Getting Started

Prerequisites
Python 3.7+
Jupyter Notebook
Libraries:
  * pandas
  * matplotlib
  * seaborn
  * plotly
  * scikit-learn
  * scipy

Installation
1. Clone this repository:
git clone https://github.com/yourusername/retail-sales-analysis.git
cd retail-sales-analysis

2. Install required libraries:
pip install -r requirements.txt

3. Start Jupyter Notebook:
jupyter notebook

4. Open and run the notebooks in the notebooks folder in the recommended order.

🧪 Example Usage
Here’s a quick example of how to use the sales trend plot function:

from src.eda import plot_sales_trend
data = pd.read_csv("data/cleaned_sales_data.csv")
data['transaction_date'] = pd.to_datetime(data['transaction_date'], format='%d-%m-%Y')
plot_sales_trend(data, 'transaction_date', 'Total_Bill')

📈 Results
This analysis provided insights into:

Key Sales Trends: Identified peak sales periods and factors influencing sales volume.
Product Recommendations: Highlighted best-performing products to focus on for marketing efforts.
Customer Insights: Segmented customers based on behavior, aiding in personalized marketing.
Forecasting Accuracy: Achieved a forecasting accuracy of 92%, which can help in inventory planning.

💡 Insights and Recommendations

- Increase Inventory for Best-Sellers: Based on product performance analysis, we recommend increasing stock for high-demand products.

- Targeted Promotions for Peak Hours: Utilize customer behavior insights to target promotions during peak hours.

- Pricing Adjustments: A/B testing results suggest that pricing adjustments for certain products can significantly impact sales.

👤 Author
Andre M
