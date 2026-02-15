# Customer Churn Prediction Project

## Project Overview
This project builds a machine learning model to predict customer churn using behavioral and transactional data.  
The workflow includes feature engineering, clustering segmentation, XGBoost modeling, holdout scoring, and SHAP interpretation.

## Business Problem
Customer churn directly impacts revenue and long-term growth. This project identifies customers at risk of leaving so the company can intervene early with retention strategies.

## Model Performance
- Final model: XGBoost
- Evaluated using ROC-AUC
- Outperformed baseline models
- Selected for strong predictive accuracy and interpretability

## Key Results
- Customers with higher monthly fees and lower engagement showed highest churn risk  
- Feature importance and SHAP analysis identified actionable business drivers  
- Model enables targeted retention strategies

## Repository Structure
- GROUP_8_XGBOOST_MODEL.ipynb → main model training  
- GROUP_8_SCORED_HOLDOUT_CODES.ipynb → holdout scoring  
- featured_dataset_with_target.csv → dataset  
- individual/ → personal contributions  

## How to Run the Code
1. Install required Python libraries (pandas, numpy, sklearn, xgboost, shap)
2. Open the XGBoost notebook
3. Load the dataset
4. Run preprocessing and training cells
5. Generate predictions and evaluation plots

## Limitation
Model performance depends on historical customer behavior and may decrease if patterns change significantly.
