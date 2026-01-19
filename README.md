
# Credit Risk Classification

## 📌 Project Overview
This project builds a supervised machine learning model to classify loan applicants as **Healthy Loan** or **High-Risk Loan** based on financial and credit-related attributes. The goal is to assist financial institutions in assessing credit risk and making data-driven lending decisions.

## 📊 Dataset Features
- loan_size  
- interest_rate  
- borrower_income  
- debt_to_income  
- num_of_accounts  
- derogatory_marks  
- total_debt  
- loan_status (target)

## ⚙️ Methodology
- Applied **Logistic Regression** for binary classification  
- Built two models:
  1. Model trained on original dataset  
  2. Model trained on resampled data using **Random Over Sampler** to handle class imbalance  
- Evaluated models using precision, recall, and classification reports  

## 📈 Results
- **Original Model:**  
  - Healthy Loans: 100% Precision & Recall  
  - Risky Loans: 87% Precision, 91% Recall  

- **Resampled Model:**  
  - Improved Risky Loan Recall from **91% → 99%**  
  - Slight trade-off in Healthy Loan Recall  

## 🏆 Conclusion
The original model provides maximum reliability for predicting healthy loans, while the resampled model significantly improves detection of high-risk loans. This demonstrates how data balancing techniques enhance credit risk prediction.

## 🛠️ Tech Stack
Python • Scikit-learn • Pandas • Logistic Regression • RandomOverSampler • Classification Metrics

## 🚀 Future Improvements
- Experiment with ensemble models (Random Forest, XGBoost)  
- Deploy as a REST API for real-time loan risk prediction  
