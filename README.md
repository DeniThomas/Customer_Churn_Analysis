# Customer_Churn_Analysis

🚀 Overview

This project predicts customer churn using Logistic Regression, SMOTE, and XGBoost. We explored various models and found that XGBoost achieved the highest accuracy of 95.35%.
📊 Dataset

    Training Data: churn-bigml-80.csv
    Testing Data: churn-bigml-20.csv
    Features include customer service calls, international plan, total minutes, and more.

🔍 Models Used

    Baseline Logistic Regression (Accuracy: 71.06%)
    SMOTE-Enhanced Logistic Regression (Accuracy: 70.61%)
    XGBoost Model (Accuracy: 95.35% ✅ Best Model)

📈 Key Findings

    XGBoost outperformed other models with an F1-score of 83% on churn cases.
    Using SMOTE improved recall for minority class but slightly reduced overall accuracy.
    Customer service calls and international plan were key churn predictors.

📌 Visualizations

    Boxplots to detect outliers in total minutes/calls.
    Confusion Matrix to evaluate model predictions.
