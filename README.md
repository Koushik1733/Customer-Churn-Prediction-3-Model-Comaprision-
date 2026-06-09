# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn refers to customers discontinuing a company's service. Predicting customer churn is important because retaining existing customers is often more cost-effective than acquiring new ones.

In this project, machine learning techniques were used to analyze customer data and predict whether a customer is likely to churn. The project follows a complete machine learning workflow including data understanding, exploratory data analysis (EDA), preprocessing, model building, evaluation, and comparison.

---

## Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Number of Records:** 7043

**Number of Features:** 21

**Target Variable:**

* Yes → Customer churned
* No → Customer retained

The dataset contains customer demographic information, service subscriptions, billing details, contract information, and payment methods.

---

## Project Workflow

### Phase 1: Understanding the Dataset

* Examined dataset structure and features
* Identified target variable
* Checked data types and missing values

### Phase 2: Exploratory Data Analysis (EDA)

* Analyzed churn distribution
* Studied the relationship between churn and important features
* Identified patterns affecting customer churn

### Phase 3: Data Preprocessing

* Converted categorical variables into numerical format
* Processed the target variable
* Removed unnecessary features
* Prepared data for machine learning models

### Phase 4: Logistic Regression

* Trained a baseline classification model
* Evaluated using accuracy, precision, recall, and F1-score

### Phase 5: Random Forest

* Built an ensemble learning model
* Compared performance with Logistic Regression

### Phase 6: XGBoost

* Trained a gradient boosting model
* Evaluated performance on the test dataset

### Phase 7: Model Comparison

* Compared all models
* Selected the best-performing model

---

## Key Findings from EDA

* Customers with lower tenure showed higher churn.
* Customers with month-to-month contracts exhibited higher churn.
* Higher monthly charges were associated with increased churn.
* Fiber optic customers showed relatively higher churn.
* Electronic check users showed higher churn compared to other payment methods.

---

## Models Used

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier

---

## Evaluation Metrics

The following metrics were used to evaluate model performance:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Results

| Model               | Accuracy                  |
| ------------------- | ------------------------- |
| Logistic Regression | 82.2%                     |
| Random Forest       | 78.9%                     |
| XGBoost             | (Update with your result) |

Among the evaluated models, Logistic Regression achieved the best overall performance on the dataset.

---

## Important Features

The most influential features identified during the analysis were:

* TotalCharges
* tenure
* MonthlyCharges
* Contract Type
* Internet Service Type
* Payment Method

These features played a significant role in predicting customer churn.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Jupyter Notebook

---

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn and identify factors associated with customer retention. Through exploratory data analysis and model comparison, meaningful insights were obtained regarding customer behavior and churn patterns. The final model achieved strong predictive performance and can assist businesses in identifying customers who may be at risk of leaving the service.

---

## Future Improvements

* Hyperparameter tuning
* Additional feature engineering
* Cross-validation
* Deployment using Streamlit
* Real-time prediction system
