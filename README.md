# Telco Customer Churn Prediction

Machine learning project to predict telecom customer churn using the IBM Telco dataset (7,032 records, 19 features). Focused on solving class imbalance (~27% churn) and optimizing minority-class performance for real retention use cases.

## Overview
• Binary classification: Churn vs No-Churn  
• Built preprocessing pipeline (encoding, scaling, feature engineering)  
• Compared Logistic Regression, Random Forest, XGBoost  
• Applied threshold tuning to improve churn detection  

## Results (Test Set)
• Best Model: Logistic Regression  
• Churn Recall: 0.79  
• Churn F1-Score: 0.61  
• Significant improvement from baseline (~0.55 F1)

## Key Features Engineered
• tenure_group  
• charges_per_month  
• has_fiber  
• month_to_month  

## Techniques Used
• Scikit-learn Pipeline + ColumnTransformer  
• class_weight balancing  
• Train / Validation / Test split (no leakage)  
• Confusion matrix and feature importance analysis  

## Business Impact
Model identifies ~79% of churn-risk customers, enabling targeted retention strategies.

## Tools
Python • Pandas • Scikit-learn • XGBoost • Matplotlib

## Future Improvements
• Hyperparameter tuning  
• SMOTE integration  
• Streamlit deployment  

## Author
Sameer  
Junior Data Analyst
