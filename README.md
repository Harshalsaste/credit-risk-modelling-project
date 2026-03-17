Project name - Loan Default Prediction 

Problem statement:
Predict probability of borrower default.

Dataset:
Loan Prediction Dataset (Kaggle)

Features:
* Income
* Loan Amount
* Credit History
* Dependents

Feature Engineering:
* Loan-Income Ratio
* Income per Person

Models Used:
* Logistic Regression
* LightGBM


Results & Insights:

#Model Performance:
Logistic Regression - 0.78
LightGBM - 0.85    

#Best Model:
LightGBM performed the best with ROC-AUC of 0.85.

#Why LightGBM Performed Better:
* Captures non-linear relationships between features
* Handles feature interactions automatically
* Works well with tabular data
* Robust to outliers and missing values

#Key Insights:
* Credit History is the most important feature
* Loan-Income Ratio strongly impacts default risk
* Applicants with low income per dependent are riskier



#Business Impact:
* Banks can identify high-risk customers early
* Helps in reducing loan defaults
* Enables better credit decision making


Tech Stack:
Python, Scikit-learn, LightGBM

How to Run:
```bash
pip install -r requirements.txt
```

Author:
Harshal Saste



