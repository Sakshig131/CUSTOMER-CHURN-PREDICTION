# 💳 Customer Churn Prediction

## 📌 Project Overview

This project focuses on predicting customer churn for a subscription-based business using Machine Learning techniques. Customer churn refers to when a customer stops using a company's service.

The goal is to build models that can identify customers who are likely to leave, helping businesses take preventive actions.

---

## 📂 Dataset

The dataset used in this project contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Membership
* Estimated Salary

**Target Variable:**

* `Exited` → 1 (Churned), 0 (Not Churned)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

## 🔍 Data Preprocessing

* Removed unnecessary columns (`RowNumber`, `CustomerId`, `Surname`)
* Converted categorical variables using One-Hot Encoding
* Feature scaling using StandardScaler
* Split data into training and testing sets

---

## 🤖 Models Used

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

---

## 📊 Model Performance

### 🔹 Logistic Regression

* Accuracy: **81.1%**
* Precision: 0.55
* Recall: 0.20
* F1 Score: 0.29

### 🔹 Random Forest (Best Model)

* Accuracy: **86.55%**
* Precision: 0.75
* Recall: 0.47
* F1 Score: 0.57

### 🔹 Gradient Boosting

* Accuracy: **85.95%**
* Precision: 0.74
* Recall: 0.43
* F1 Score: 0.54

---

## 📈 Conclusion

* Random Forest performed the best among all models.
* The dataset is slightly imbalanced, which affects recall.
* Further improvements can be made using:

  * SMOTE (for balancing data)
  * Hyperparameter tuning
  * Advanced models like XGBoost

---

## 🔗 GitHub Repository
[Click here to view the project](https://github.com/Sakshig131/CUSTOMER-CHURN-PREDICTION)

---

## 📌 Future Improvements

* Handle class imbalance
* Improve recall for churn prediction
* Deploy model using Flask or Streamlit

---

## 👩‍💻 Author

Sakshi G
