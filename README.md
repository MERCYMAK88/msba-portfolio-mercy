# Customer Churn Prediction Project

## Business Problem
Customer churn directly impacts revenue and long-term growth. This project builds a predictive machine learning model to identify customers at risk of leaving so the company can intervene early with retention strategies.

## Key Results
- XGBoost achieved the strongest predictive performance compared to baseline models
- Customers with higher monthly fees and lower engagement showed the highest churn risk
- Feature importance and SHAP analysis helped identify actionable business drivers of churn

## How to Run the Code
1. Open the XGBoost notebook
2. Install required Python libraries (pandas, numpy, sklearn, xgboost, shap)
3. Load the dataset file
4. Run preprocessing cells
5. Train the model
6. Generate predictions and evaluation plots

## Limitation
Model performance depends on historical customer behavior and may decrease if customer patterns change significantly in the future.
