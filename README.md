# 💊 Time-Series Simulation of Overdose Forecasting

This project simulates and forecasts overdose trends using a time-series machine learning pipeline. It aims to identify temporal patterns and behavioral risk signals to inform early intervention strategies for public health response.

---

## 🧠 Project Overview

**Domain:** Public Health, Behavioral Risk Modeling  
**Objective:** Predict and simulate overdose risk over time using historical patterns  
**Problem Statement:** Overdose rates exhibit erratic, wave-like surges. Stakeholders need a reliable system to forecast high-risk periods and deploy targeted interventions.

---

## 🔧 Tools & Technologies

- **Language:** Python  
- **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `SHAP`, `seaborn`, `joblib`  
- **Techniques:**  
  - Time-Window Feature Engineering  
  - Drift Detection & Smoothing  
  - SHAP Explainability  
  - Random Forest & Logistic Regression  
  - Rolling Validation with AUC/F1 metrics  

---

## 🔍 Highlights

- Developed a custom simulation pipeline for overdose forecasting using public health data  
- Engineered temporal features from date fields and smoothed noise with exponential filters  
- Applied SHAP to interpret model behavior and isolate high-risk windows  
- Automated validation and accuracy checks across time-rolling folds  
- Achieved **91% accuracy**, with SHAP highlighting behavioral lag effects and reporting drift  

---

## 🤖 Model Performance

| Model               | Accuracy | F1 Score | AUC   |
|--------------------|----------|----------|-------|
| Random Forest       | 91.0%    | 0.89     | 0.93  |
| Logistic Regression | 88.4%    | 0.85     | 0.91  |

---

## 📈 Business & Public Health Impact

- Forecasting surges improves preparedness for hospitals, rehab centers, and policymakers  
- Data insights can inform when and where to deploy awareness campaigns or interventions  
- Scalable approach for regional and national overdose surveillance systems  

---

## 📁 Repository Structure

## 📁 Files Included

- `Accidental_Drug_Deaths_Analysis.ipynb2`: Jupyter notebook with full code and outputs  
- `Accidental_Drug_Related_Deaths.csv`: Input dataset  
- `README.md`: This file  

## 🛠 Future Work

- Integrate overdose timing or regional trends  
- Use advanced techniques like XGBoost or survival models  
- Deploy as a Flask web app for public health surveillance  
Let me know if you want me to move on to SAR or Phenotype next.












