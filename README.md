# 🏥 Medical Insurance Cost Prediction — Predictive Modeling

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange) ![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

> End-to-end predictive modeling pipeline on medical insurance data — regression to predict charges, classification to identify high-risk profiles.

## 📌 Overview

This project applies supervised machine learning to a real-world insurance dataset to:
- **Predict insurance costs** (regression) based on lifestyle and demographic factors
- **Classify high-cost patients** (classification) to support risk modeling use cases
- Demonstrate a full ML pipeline from raw data to actionable business insights

## 🎯 Results

| Model | Task | Score |
|---|---|---|
| Linear Regression (baseline) | Regression | R² = ~0.75 |
| Ridge / Lasso | Regression | Improved via regularization |
| Random Forest | Classification | F1 improved +15% vs baseline |
| Logistic Regression | Classification | Precision / Recall reported |

> Cross-validation + hyperparameter tuning (GridSearchCV) improved model accuracy by **over 15%** compared to baseline.

## 🔍 Key Features Engineered
- BMI category (underweight / normal / overweight / obese)
- Smoker × BMI interaction term
- Age group binning

## 🛠️ Tech Stack
`Python` · `pandas` · `NumPy` · `scikit-learn` · `Matplotlib` · `Seaborn` · `Google Colab`

## 📂 Dataset
[Kaggle — Medical Insurance Cost Prediction](https://www.kaggle.com/mirichoi0218/insurance)  
Features: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`

## 💼 Business Applications
- Actuarial risk scoring for insurance underwriting
- HR analytics for employee health benefit planning
- Cost forecasting for healthcare providers

## 🚀 Run Locally
```bash
git clone https://github.com/aichalf/Predictive-Analysis-Medical-Insurance-Cost-Prediction
# Open notebook in Jupyter or Google Colab
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 👩‍💻 Author
**Aicha Lfakir** · [LinkedIn](https://linkedin.com/in/aicha-lfakir) · [GitHub](https://github.com/aichalf)
