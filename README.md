# Telco Customer Churn Prediction
Built a telecom customer churn prediction model using Python. Conducted data cleaning, EDA and visualization using Pandas, Seaborn and Matplotlib, and applied machine learning techniques to predict customer churn. Gained hands-on experience in data preprocessing, feature analysis and model evaluation.

## Objective
To analyze customer behavior and predict churn using data analysis and machine learning.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Machine Learning (Logistic Regression)
- Scikit-learn

## Key Insights
- Higher monthly charges increase churn probability  
- Customers with low tenure are more likely to leave  

## Model Evaluation

- **Accuracy:** ~77%  
- **ROC-AUC Score:** 0.80  

### Confusion Matrix Insights
- Model performs well in predicting non-churn customers  
- However, it has a high number of **False Negatives**, meaning many churn customers are not correctly identified  

## Problem Identified
- Low recall for churn class  
- Default threshold (0.5) is not optimal  
- Model misses a significant number of actual churn customers  

## Future Improvements
- Apply threshold tuning to improve recall  
- Handle class imbalance using class weights  
- Experiment with advanced models like Random Forest and XGBoost  

## Conclusion
The model shows good overall capability (AUC = 0.80), but requires improvement in detecting churn customers. Future work will focus on increasing recall and reducing missed churn cases to make the model more effective for real-world business use.
