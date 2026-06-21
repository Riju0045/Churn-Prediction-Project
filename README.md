# Customer Churn Prediction in Telecommunication Services

## Project Overview

Customer churn is one of the major challenges faced by telecommunication companies. Retaining existing customers is often more cost-effective than acquiring new ones. This project aims to analyze customer behavior and develop machine learning models to predict whether a customer is likely to leave the company's services.

The study combines **statistical analysis** and **machine learning techniques** to identify important factors influencing churn and build predictive models capable of identifying high-risk customers.

---

## Dataset

The project uses the **Telco Customer Churn Dataset**, which contains information related to:

* Customer demographics
* Account information
* Service subscriptions
* Billing details
* Customer churn status

Each observation represents an individual customer, while the target variable (**Churn**) indicates whether the customer left the company.

---

## Project Workflow

1. Data Collection and Preprocessing
2. Exploratory Data Analysis (EDA)
3. Statistical Analysis

   * Chi-Square Test
   * One-Way ANOVA
   * Tukey's HSD Test
4. Feature Engineering
5. Handling Class Imbalance using SMOTE
6. Model Development
7. Model Evaluation and Comparison

---

## Exploratory Data Analysis

EDA was performed to understand customer behavior and identify factors associated with churn. The analysis explored:

* Distribution of churned customers
* Service usage patterns
* Gender-wise churn analysis
* Customer tenure analysis
* Relationship between contract type and churn

---

## Machine Learning Models Used

The following machine learning algorithms were implemented:

* Logistic Regression
* Random Forest Classifier
* XGBoost Classifier

---

## Model Performance

| Model               | Accuracy   | Cross Validation Score |
| ------------------- | ---------- | ---------------------- |
| Logistic Regression | 75.73%     | 77.27%                 |
| Random Forest       | 78.64%     | 85.56%                 |
| XGBoost             | **78.85%** | 84.03%                 |

Among the implemented models, **XGBoost achieved the highest testing accuracy**, while **Random Forest demonstrated the best cross-validation performance**.

---

## Key Findings

* Customer tenure has a strong influence on churn behavior.
* Contract type is significantly associated with customer churn.
* Customers with month-to-month contracts are more likely to churn.
* Service-related features play a crucial role in customer retention.
* Gender has little influence on customer attrition.

---

## Technologies and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)
* SciPy
* Statsmodels

---

## Future Improvements

* Incorporate deep learning techniques for improved predictive performance.
* Develop a real-time churn prediction system.
* Include additional customer behavioral variables such as complaint history and customer satisfaction scores.
* Deploy the model as a web application for business use.

---

## Author

**Amrit Basak**

M.Sc. Statistics
