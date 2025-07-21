# Customer Churn Prediction System

This project builds a machine learning model to predict customer churn using the **Telco Customer Churn** dataset from Kaggle. The goal is to identify customers who are likely to leave the telecom service, enabling proactive retention strategies.

---

##  Project Highlights

- Performed end-to-end **data preprocessing**, including:
  - Handling missing and incorrect values (e.g., `TotalCharges`)
  - Feature engineering (e.g., tenure-based features, service combinations)
  - Encoding categorical features (Label Encoding & One-Hot Encoding)
  - Addressing class imbalance using **SMOTE**

- Trained and compared multiple models:
  - **Decision Tree**
  - **Random Forest**
  - **XGBoost**

- **Random Forest** achieved the best performance with ~84% accuracy on the test set.

- Built a predictive system that can forecast churn for **new or unseen customer data**.

---

##  Tech Stack

- **Python** (Google Colab)
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **XGBoost**
- **Imbalanced-learn** (for SMOTE)

---

##  Results

| Model          | Accuracy |
|----------------|----------|
| Decision Tree  | ~78%     |
| XGBoost        | ~82%     |
| Random Forest  | **~84%** |
