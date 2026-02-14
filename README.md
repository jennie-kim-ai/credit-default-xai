![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/MachineLearning-Project-green)
![XAI](https://img.shields.io/badge/XAI-SHAP%20%7C%20DiCE-orange)

# 📊 Explainable Credit Default Prediction (SHAP + DiCE)

## 📌 Overview
This project explores explainable machine learning for credit card default prediction using two complementary XAI approaches:

- SHAP for feature attribution (Logistic Regression model)
- DiCE for counterfactual explanations (XGBoost model)

The goal is to understand both:
1. Why a prediction was made
2. How a prediction could change

---

## 🎯 Objectives
- Train machine learning models for credit default prediction
- Compare explanation methods across models
- Interpret feature importance globally and locally
- Generate counterfactual scenarios to understand decision boundaries

---

## 📂 Project Structure
```
├── SHAP_for_Credit_Card_Default.ipynb
├── DiCE_for_Credit_Card_Default.ipynb
└── README.md
```

---

## 🧠 Methodology

### SHAP — Model Interpretation (Logistic Regression)
- Feature importance ranking
- Global summary plot
- Individual prediction explanation
- Analysis of feature impact direction

---

### DiCE — Counterfactual Explanations (XGBoost)
- Generates alternative feature values
- Shows minimal changes required to flip prediction
- Demonstrates decision boundary behavior
- Provides actionable scenario analysis

---

## 🔍 Why Two Models?

Different explanation methods work better with different model types.

| Model | Strength |
|------|--------|
Logistic Regression | Interpretable baseline |
XGBoost | Strong nonlinear modeling |

Using both helps compare:
- linear vs nonlinear decision boundaries
- attribution vs counterfactual explanations

---

## 🛠 Tech Stack
- Python
- Scikit-learn
- XGBoost
- SHAP
- DiCE
- Pandas
- NumPy
- Matplotlib

---

## 📊 Dataset
UCI Machine Learning Repository  
Default of Credit Card Clients Dataset

---

## 🧠 Key Learning Outcomes
- Understanding model transparency techniques
- Comparing explanation paradigms
- Interpreting model decision logic
- Evaluating prediction reliability

---

## 👤 Author
Jinhee Kim
M.S. Artificial Intelligence Student  
