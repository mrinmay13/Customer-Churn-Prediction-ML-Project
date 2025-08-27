Customer Churn Prediction ML Project

📌 Overview
Customer churn refers to when customers stop doing business with a company. This project aims to build a machine learning model that accurately predicts whether a customer is likely to churn based on various features such as demographic information, account details, and service usage.

By identifying at-risk customers, businesses can take proactive steps to retain them, improve customer satisfaction, and reduce revenue loss.

---

🎯 Problem Statement
Develop a classification model that predicts whether a customer will churn using data such as:

- Demographic info (e.g., gender, senior citizen status)
- Account details (e.g., tenure, contract type)
- Services used (e.g., internet service, online security, phone service)

The goal is to support business decisions and customer retention strategies using data-driven insights.

---

📊 Dataset
- **Name**: `Customer_data`
- **Source**: https://docs.google.com/document/d/1V-L3EdEnEEiYHhxppRY_CkPRbJ77ELYc/edit?tab=t.0
- **Features Include**:
  - CustomerID
  - Gender
  - SeniorCitizen
  - Partner
  - Dependents
  - Tenure
  - PhoneService
  - InternetService
  - OnlineSecurity
  - OnlineBackup
  - DeviceProtection
  - TechSupport
  - StreamingTV
  - StreamingMovies
  - Contract
  - PaperlessBilling
  - PaymentMethod
  - MonthlyCharges
  - TotalCharges
  - Churn (Target variable)

---

## ⚙️ Project Workflow

1. **Data Exploration & Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Normalize/standardize features
   - Exploratory Data Analysis (EDA)

2. **Model Building**
   - Models: Logistic Regression, Random Forest, XGBoost, etc.
   - Data split into train/test sets
   - Cross-validation
   - Hyperparameter tuning

3. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1 Score
   - Confusion Matrix
   - ROC-AUC Curve

4. **Insights & Interpretation**
   - Feature importance analysis
   - Business recommendations

5. **Final Presentation**
   - Summary video (< 5 minutes)
   - ZIP folder containing notebooks, reports, and models

---

✅ Success Criteria
- Effective model interpretation and actionable business insights
- Accurate churn predictions on new/unseen data
- A balanced model in terms of performance and interpretability

---

🛠 Tools & Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- XGBoost / LightGBM (optional for boosting models)

