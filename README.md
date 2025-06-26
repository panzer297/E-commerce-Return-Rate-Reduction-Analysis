# E-commerce Return Rate Reduction Analysis

This project was built during my internship to analyze and reduce product return rates for an e-commerce platform using real-world Olist data.

## Objective
Identify why customers return products and how return rates vary by category, location, and payment method. Build a predictive model and dashboard to visualize risks.

## 🛠Tools & Tech
- **Python (Google Colab)** – Data cleaning, analysis, logistic regression
- **Power BI** – Interactive dashboard with KPIs and filters
- **Pandas, Scikit-learn** – For feature engineering and modeling
- **Kaggle Olist Dataset** – Brazilian e-commerce data

## Dashboard Features
- Return % by product category, state, and payment method
- Filters for category, state, and channel
- High-risk flagged products from logistic regression
- Summary KPIs: total returns, return rate

## Files Included
- *return_analysis_data.csv** – Cleaned dataset
- *return_rate_by_category.csv*, *return_rate_by_seller.csv* – EDA outputs
- *high_risk_returns.csv* – Predicted return risks
- *E_commerce_Return_Rate_Reduction.ipynb* – Colab notebook
- *return_dashboard.pbix* – Power BI dashboard

## Sample Insights
-  Some categories have 2× higher return risk than others
-  Prepaid orders return less than COD
-  Certain regions show consistent return spikes

## Learning Outcome
Complete lifecycle of a real-world data science project, from messy data to insights and dashboards.
