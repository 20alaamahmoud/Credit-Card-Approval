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
