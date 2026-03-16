# Customer Churn Prediction & Market Basket Analysis

**Author:** Marlon Suero  
**Tools Used:** Python, pandas, mlxtend, matplotlib, seaborn, scikit-learn  
**Dataset:** Online Retail II Dataset / Telco Customer Churn Dataset  
**Project Type:** Predictive Analytics / Market Basket Analysis

---

## Project Objective
1. Predict which customers are at risk of churning using a Random Forest classifier.  
2. Identify frequently purchased product combinations for cross-selling and bundling opportunities.

---

## Business Questions
1. Which products are purchased most frequently?  
2. Which products generate the most revenue?  
3. Which products are commonly purchased together?  
4. Which customers are likely to churn and require intervention?  
5. How can these patterns inform cross-selling or bundling strategies?

---

## Key Features
- Data cleaning and preprocessing of transactional and churn datasets  
- Encoding categorical variables for machine learning  
- Exploratory visualizations (churn distribution, tenure trends, correlations)  
- Random Forest model for churn prediction  
- Feature importance analysis  
- Top product analysis for revenue and market basket insights

---

## How to Run
1. Open `customer_churn_market_basket.ipynb` in Jupyter Notebook or VS Code.  
2. Install Python 3.x and required packages:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn
   - mlxtend
3. Place the respective datasets (`online_retail_II.xlsx` and `WA_Fn-UseC_-Telco-Customer-Churn.csv`) in the project folder.  
4. Run all cells sequentially to reproduce the analysis and model results.

---

## Key Insights
- Customers with short tenure and multiple services are more likely to churn.  
- Paperless billing and high monthly charges correlate with churn.  
- Random Forest model achieves high accuracy for early identification of at-risk customers.  
- Market basket analysis reveals actionable product relationships for cross-selling.

---

## Conclusion
This project demonstrates the integration of predictive analytics and product insights.  
Companies can use these findings to retain at-risk customers, optimize product offerings, and drive revenue growth.
