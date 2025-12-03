#  Credit Card Fraud Detection System — AMEX Risk & Data Science Use Case
This project demonstrates an end-to-end **fraud detection pipeline** closely aligned with real-world risk analytics used at **American Express Credit & Fraud Risk (CFR)** teams.
It focuses on building a scalable machine learning workflow to detect fraudulent transactions using supervised learning, feature engineering, and evaluation techniques used in financial risk modelling.
 **Business Problem**
Financial institutions handle millions of daily card transactions. Detecting fraud in real-time is challenging because:

- Fraudulent transactions are rare (**high class imbalance**).
- Fraud patterns evolve constantly.
- False declines negatively impact customer experience.

This project solves the above using a **Machine Learning + Risk Decisioning Pipeline** optimized for model interpretability and operational deployment.

** Project Objectives**

| Goal | Description |
|------|------------|
| Build fraud prediction model | Predict whether a transaction is fraudulent |
| Handle class imbalance | Use SMOTE and precision-recall optimization |
| Evaluate model performance | Measure Recall, AUC, Precision, F1 |
| Analyze business risk | Understand trade-offs between fraud catch rate & false positives |
| Ensure explainability | Use SHAP and feature importance for model transparency |


**Tech Stack
| Category | Tools |
|---------|-------|
| Programming | Python |
| ML Libraries | Scikit-learn, XGBoost, SMOTE, SHAP |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Deployment Ready | Pipeline + Model Serialization (Pickle) |



