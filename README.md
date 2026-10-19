
# Predictive Churn Analysis

## Project Overview
This project uses Machine Learning to predict customer churn risk
using a customer churn dataset containing 800 records.

## Objective
Build and evaluate a classification model to identify customers
who may be at risk of leaving a service.

## Dataset
- Total records: 800
- Total columns: 13
- Missing values: 0
- Target variable: Churn

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Methodology
1. Data inspection and preprocessing
2. One-Hot Encoding for categorical features
3. MinMax scaling for numerical features
4. 80/20 train-test split
5. Logistic Regression model training
6. Model evaluation using Precision, Recall, F1-score and ROC-AUC
7. Customer churn probability prediction

## Model Evaluation
- Accuracy: 63.7%
- Precision: 57.6%
- Recall: 50.7%
- F1-score: 54.0%
- ROC-AUC: 0.681

These metrics are from the current test split and may vary if the
dataset or model settings change.

## Output Files
- Customer_Churn_Risk_Predictions.csv
- Churn_ROC_Curve.png
- Predictive_Churn_Analysis.ipynb

## Conclusion
The baseline Logistic Regression model provides an initial estimate
of customer churn risk. Further feature engineering and model
comparison may improve performance.

## Author
Student Machine Learning Project
