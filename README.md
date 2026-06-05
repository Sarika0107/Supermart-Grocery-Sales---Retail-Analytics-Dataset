# Supermart Grocery Sales - Retail Analytics & Machine Learning

## Project Overview

Retail businesses generate large volumes of transactional data that can provide valuable insights into customer purchasing behavior, sales trends, and business performance. This project analyzes Supermart grocery sales data using Exploratory Data Analysis (EDA) and Machine Learning techniques to identify key sales patterns and predict future sales outcomes.

The project combines data preprocessing, feature engineering, visualization, and predictive modeling to help businesses make data-driven decisions and improve overall sales performance.

---

## Objectives

- Analyze sales performance across different product categories.
- Identify monthly and yearly sales trends.
- Determine the top-performing cities based on revenue.
- Study the relationship between sales, profit, and discounts.
- Perform exploratory data analysis (EDA).
- Build machine learning models for sales prediction.
- Compare model performance and derive business insights.

---

## Dataset

The dataset contains supermarket retail transaction records.

### Features Include

- Order Date
- Category
- City
- Sales
- Profit
- Discount
- Other transaction-related attributes

### Target Variable

- Sales

---

## Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records.
- Converted Order Date into datetime format.
- Extracted month and year features.
- Handled missing values.
- Encoded categorical variables using Label Encoding.
- Prepared data for machine learning modeling.

---

## Exploratory Data Analysis (EDA)

### Key Insights

- Certain product categories generate significantly higher revenue than others.
- Sales vary across different months, indicating seasonal purchasing behavior.
- Business performance differs across years.
- A small number of cities contribute a large portion of total sales.
- Discounts influence both sales and profit levels.

### Visualizations Performed

- Category-wise Sales Analysis
- Monthly Sales Trend
- Yearly Sales Distribution
- Top 5 Cities by Sales
- Correlation Heatmap
- Sales Prediction Evaluation

---

## Machine Learning Approach

### Models Implemented

- Linear Regression
- Random Forest Regressor

### Key Techniques

- Feature Engineering
- Label Encoding
- Train-Test Split
- Regression Modeling
- Model Comparison

---

## Model Evaluation

The models were evaluated using:

- R² Score
- Mean Squared Error (MSE)

### Performance Summary

- Linear Regression achieved an R² score of approximately 0.35.
- Random Forest Regressor achieved an R² score of approximately 0.33.
- Linear Regression slightly outperformed Random Forest on this dataset.

---

## Feature Importance

Important factors influencing sales prediction include:

- Product Category
- City
- Discount
- Profit
- Month
- Year

These variables significantly contribute to sales performance and prediction accuracy.

---

## Applications

This project can help:

- Retail Businesses
- Store Managers
- Business Analysts
- Sales Teams
- Decision Makers

Potential applications include:

- Sales Forecasting
- Revenue Planning
- Inventory Optimization
- Customer Purchase Analysis
- Business Performance Monitoring

---

## Limitations

- Dataset is limited to historical sales records.
- External factors such as market conditions and customer demographics are not included.
- Prediction accuracy depends on available features.
- Results should be interpreted as analytical insights rather than exact forecasts.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Contents

- Supermart(s).ipynb → Complete analysis and machine learning workflow
- Supermart Grocery Sales Dataset.csv → Dataset
- README.md → Project documentation

---

## Author

**Sarika T A**  
Aspiring Data Analyst / Data Scientist

---

## Conclusion

This project analyzed the Supermart Grocery Sales dataset to understand customer purchasing patterns, sales performance, and business trends. Through exploratory data analysis, important insights were obtained regarding category-wise sales, monthly and yearly revenue trends, top-performing cities, and the relationship between sales, profit, and discounts.

Machine learning models including Linear Regression and Random Forest Regressor were developed to predict sales values. The results showed that Linear Regression slightly outperformed Random Forest for this dataset, indicating that the available features exhibit relatively linear relationships with sales. The analysis demonstrates how data analytics and predictive modeling can support retail businesses in understanding customer behavior, optimizing operations, and improving strategic decision-making.

---

## Future Improvements

- Include customer demographic information for deeper analysis.
- Incorporate inventory and stock-level data.
- Apply advanced machine learning models such as XGBoost and Gradient Boosting.
- Perform hyperparameter tuning to improve prediction accuracy.
- Build interactive dashboards using Power BI or Tableau.
- Integrate real-time sales monitoring systems.
- Develop demand forecasting models for inventory management.
- Expand the dataset with additional business and customer-related features.

---
