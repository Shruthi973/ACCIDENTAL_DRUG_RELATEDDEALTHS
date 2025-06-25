# Accidental Drug-Related Deaths – Predictive Modeling & Risk Profiling

This machine learning project focuses on analyzing accidental drug-related deaths using real-world toxicology and demographic data. The goal is to identify patterns in fatalities and develop predictive models to classify high-risk cases based on substances involved and demographic features.

---

## 🚀 Project Overview

- **Dataset:** Connecticut’s Accidental Drug-Related Deaths database
- **Objective:** Predict fatal overdoses and evaluate substance-specific risk
- **Tech Stack:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn

---

## 📊 Key Techniques Used

- Data cleaning, NA handling, and feature engineering
- One-hot encoding of categorical variables
- Binary target variable creation: `Fatal = 1` if heroin involved
- Standardization and stratified splitting
- Classification models:  
  ✅ Logistic Regression  
  ✅ Random Forest  
  ✅ Naive Bayes  
  ✅ K-Nearest Neighbors (KNN)

---

## 📈 Model Evaluation

All models were evaluated using Precision, Recall, F1-score, and ROC AUC.

| Model               | Accuracy | Precision | Recall | F1-score | ROC AUC |
|--------------------|----------|-----------|--------|----------|---------|
| Logistic Regression| 0.82     | 0.78      | 0.85   | 0.81     | 0.86    |
| Naive Bayes        | 0.79     | 0.76      | 0.81   | 0.78     | 0.83    |
| Random Forest      | 0.85     | 0.83      | 0.88   | 0.85     | 0.89    |
| KNN (k=5)          | 0.80     | 0.79      | 0.81   | 0.80     | 0.84    |

> 🎯 Random Forest achieved the best overall performance.

---

## 🔍 Insights

- Substances like **heroin**, **fentanyl**, and **benzodiazepines** were top predictors.
- **Demographic factors** (age, sex, race) also influenced risk.
- **Random Forest** balanced recall and precision best, critical for minimizing false negatives in fatality prediction.

---

## 📁 Files Included

- `Accidental_Drug_Deaths_Analysis.ipynb`: Complete notebook with code, preprocessing, models, and visualizations
- `Accidental_Drug_Related_Deaths.csv`: Original dataset (optional inclusion)
- `README.md`: This documentation

---

## 🛠 Future Work

- Integrate temporal and geographic data for spatiotemporal risk modeling
- Deploy as an API or dashboard for real-time overdose surveillance
- Explore survival models and ensemble stacking

---

📬 For collaborations, feel free to connect on [LinkedIn](https://www.linkedin.com) or GitHub.

