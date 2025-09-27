# Predicting 30-Day Hospital Readmissions with Machine Learning

## 📌 Project Overview
This project explores whether we can predict which patients are at highest risk
of hospital readmission within 30 days, using data from **130 US hospitals (1999–2008)**.
The dataset includes demographics, labs, diagnoses, and medication data.

## 🎯 Goals
- Build baseline models (Logistic Regression, Random Forest, XGBoost).
- Handle imbalanced classes (<20% readmissions).
- Evaluate using AUC, Precision-Recall, and F1-score.
- Use SHAP for model interpretability.
- Explore fairness across race, gender, and age.

## 🗂 Repo Structure
- `data/` — raw & processed datasets
- `notebooks/` — Jupyter notebooks for analysis
- `src/` — reusable code modules
- `results/` — plots and evaluation outputs

## 📊 Dataset
**Diabetes 130-US hospitals dataset (UCI / Kaggle)**
- ~100,000 hospital encounters
- Features: demographics, diagnoses, medications, lab results
- Target: readmission within 30 days

## ⚙️ Installation
```bash
git clone https://github.com/zaourid1/ml-hospital-readmission.git
cd ml-hospital-readmission
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
