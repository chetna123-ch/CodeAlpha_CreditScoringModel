# CodeAlpha: Credit Scoring Model 💳🤖

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 📌 Project Overview
This project was developed as part of the **CodeAlpha Machine Learning Internship**. The objective is to build a robust machine learning classification pipeline to predict an individual's creditworthiness based on past financial history, income, debt levels, and repayment behavior. 

Accurate credit scoring allows financial institutions to minimize default risks while efficiently extending credit to creditworthy applicants.

---

## 🚀 Key Features & Approach

1. **Data Simulation & Preprocessing:**
   - Generated and cleaned a realistic financial dataset including key features such as annual income, existing debts, payment history score, credit utilization, and recent credit inquiries.
   - Handled missing values and applied `StandardScaler` to normalize features for distance-sensitive algorithms.

2. **Feature Engineering:**
   - **Debt-to-Income (DTI) Ratio:** $\text{Total Debts} / \text{Annual Income}$ to measure financial leverage.
   - **Credit Health Index:** Composite metric combining payment history and credit utilization to capture overall financial standing.

3. **Classification Models Benchmarked:**
   - **Logistic Regression:** Serves as a strong, interpretable linear baseline.
   - **Decision Tree Classifier:** Captures non-linear decision boundaries and feature interactions.
   - **Random Forest Classifier:** An ensemble method that improves generalization and mitigates overfitting.

4. **Rigorous Evaluation Metrics:**
   - Evaluated models using **Precision**, **Recall**, **F1-Score**, and **ROC-AUC** to effectively manage class imbalance and minimize financial risk (false positives/negatives).

---

## 🛠️ Tech Stack
* **Language:** Python 
* **Libraries:** Pandas, NumPy, Scikit-learn

---

## 📂 Repository Structure
```text
CodeAlpha_CreditScoringModel/
│
├── CodeAlpha_CreditScoringModel.ipynb  # Jupyter Notebook containing full pipeline
├── README.md                           # Project Documentation
└── requirements.txt                    # Required Python packages