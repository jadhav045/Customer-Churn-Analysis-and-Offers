# 🚀 Customer Churn Analysis and Offers

A machine learning project focused on **predicting customer churn** in a telecommunications business.  
The goal is to identify customers who are likely to leave and enable **data-driven retention strategies** that reduce revenue loss and improve customer loyalty.

---

## 🧐 Project Overview

Customer churn is a critical problem for subscription-based companies. This project tackles churn prediction by building and comparing two strong machine learning models — **Random Forest** and **XGBoost** — using customer demographics, account information, and service usage data.

Rather than reacting after customers leave, the system helps businesses act **proactively** by identifying high-risk customers early, enabling targeted offers, better support, and personalized engagement.

---

## 🛠️ Methodology

The project follows a structured machine learning workflow:

- **Data Preparation**  
  Cleaned and preprocessed the dataset, handled missing values, and converted categorical features into numerical form using one-hot encoding.

- **Train-Test Split**  
  Split the data into training (80%) and testing (20%) sets to ensure unbiased model evaluation.

- **Model Development**  
  Trained two classification models:
  - Random Forest
  - XGBoost  
  Both models are well-suited for capturing complex, non-linear patterns in customer behavior.

- **Model Evaluation**  
  Evaluated performance on unseen data using standard classification metrics to measure how accurately churned customers were identified.

---

## 💻 Technologies Used

- **Python** – Core programming language  
- **Pandas** – Data cleaning and manipulation  
- **Scikit-learn** – Model training, evaluation, and utilities  
- **XGBoost** – High-performance gradient boosting model  

---

## 📈 Results & Conclusion

Both Random Forest and XGBoost achieved strong performance in predicting customer churn.  
Evaluation using **precision**, **recall**, and **F1-score** showed that the models can reliably identify customers at risk of leaving.

These insights can directly support business decisions, helping organizations focus retention efforts where they matter most and move from reactive to **predictive customer management**.
