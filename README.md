# Credit-Card-Approval

# Objective:
  - The goal of this project is to develop a machine learning model to predict credit card approvals based on applicant information and credit history.
  - The model aims to help financial institutions make informed lending decisions by assessing creditworthiness.

# Dataset:
  - The project uses two datasets:
      - Application Records - Contains applicant details such as demographics, employment, and income information.
      - Credit Records - Contains historical credit behavior such as overdue payments and total months of credit activity.
  - The datasets are merged to form a comprehensive feature set for prediction.

# Data Preprocessing

  - Handling Missing Values: Missing values are visualized and appropriately handled.
  - Feature Engineering:
      - Encoding categorical features using label encoding.
      - Removing features that may cause data leakage (e.g., Delinquent_Months, Total_Months).
  - Handling Outliers: Identified using Interquartile Range (IQR) and treated accordingly.
  - Data Standardization: Features are standardized using StandardScaler to improve model performance.
  - Handling Class Imbalance: Techniques such as oversampling or undersampling are applied to balance the dataset.

# Model Training and Evaluation
Two models were trained and evaluated:
  - Gradient Boosting Classifier
      - Used for feature importance and preliminary evaluation.
  - XGBoost Classifier
      - A more optimized version of boosting, providing better accuracy and AUC scores.
   
# Performance Metrics
  - Accuracy: Measures overall correctness of predictions.
  - ROC-AUC Score: Evaluates the model’s ability to distinguish between approved and rejected applicants.
  - Classification Report: Provides precision, recall, and F1-score for each class.

# Libraries Used
  - pandas, numpy - Data manipulation and processing
  - sklearn - Machine learning models, preprocessing, and evaluation
  - matplotlib, seaborn - Data visualization
  - xgboost - Extreme Gradient Boosting algorithm

# Conclusion
  - This project successfully builds a machine learning pipeline for predicting credit card approvals.
  - XGBoost provides superior performance over Gradient Boosting, making it the preferred model.
  - The insights from this model can help financial institutions make data-driven credit approval decisions.
