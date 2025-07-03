
# Employee Attrition Prediction and Clustering Using ML

This project focuses on analyzing and predicting employee attrition using machine learning. It involves comprehensive data preprocessing, feature engineering, exploratory data analysis (EDA), clustering of employees who left, handling class imbalance using SMOTE, and training multiple ML models with cross-validation to predict attrition.

## Dataset
- Source: HR analytics dataset (1688640705_hr_comma_sep.xlsx)
- Size: 14,999 entries, 10 columns
- Features: satisfaction_level, last_evaluation, number_project, average_monthly_hours, time_spend_company, etc.

## Techniques Used
- EDA & Visualization (matplotlib, seaborn)
- Encoding: OneHotEncoding (sales), LabelEncoding (salary)
- Scaling: MinMaxScaler
- Outlier Detection: IQR method + Boxplots
- Clustering: KMeans on employees who left
- Imbalance Handling: SMOTE (Synthetic Minority Oversampling Technique)
- Modeling:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Evaluation:
  - 5-Fold Cross-Validation
  - Classification Report (Precision, Recall, F1)
  - Confusion Matrix

Best F1-score: ~0.99 (Random Forest)
