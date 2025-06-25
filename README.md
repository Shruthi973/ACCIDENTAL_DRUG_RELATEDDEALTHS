# Accidental Drug-Related Deaths – Predictive Modeling & Risk Profiling

This machine learning project analyzes accidental drug-related deaths using toxicology and demographic data. We develop predictive models to classify fatal overdose risks, focusing on substance-specific patterns and real-world public health indicators.

## 🚀 Project Overview

- **Dataset:** Connecticut’s Accidental Drug-Related Deaths dataset
- **Objective:** Predict whether a death involved heroin and evaluate risk based on demographic and substance variables
- **Tech Stack:** Python, Scikit-learn, Pandas, Matplotlib, Seaborn

## 📊 Key Techniques

- Data preprocessing & exploratory data analysis
- Target variable: `Fatal` defined as presence of heroin
- Model training using:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - K-Nearest Neighbors (KNN)
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix, AUC

## 🧪 Evaluation Metrics Summary

| Model               | Accuracy | Precision | Recall | F1-Score | AUC   |
|--------------------|----------|-----------|--------|----------|-------|
| Logistic Regression| 0.94     | 0.91      | 0.96   | 0.94     | 0.97  |
| Naive Bayes        | 0.88     | 0.89      | 0.84   | 0.86     | 0.91  |
| Random Forest      | 0.94     | 0.92      | 0.96   | 0.94     | 0.98  |
| KNN                | 0.90     | 0.88      | 0.92   | 0.90     | 0.94  |

> ROC AUC scores were calculated where applicable using the model's probability predictions.

## 🔍 Key Insights

- **Random Forest** achieved the best performance with high precision and recall.
- **Naive Bayes** underperformed due to strong feature independence assumptions.
- **Logistic Regression** offered strong interpretability with high accuracy.
- Feature engineering from substance names was crucial for signal extraction.

## 🧠 Learnings

- Preprocessing quality directly impacts model effectiveness.
- Ensemble methods mitigate overfitting and variance.
- Simpler models can offer more explainable decision boundaries in clinical/public health contexts.


## 🛠 Future Enhancements

- Add XGBoost or Gradient Boosted Trees for non-linear interactions
- Use NLP to parse free-text coroner notes (if available)
- Build an interactive dashboard with Streamlit or Flask


## 📁 Repository Structure
Accidental_Drug_Deaths/

# Cleaned and labeled Jupyter notebook
Accidental_Drug_Deaths_Analysis.ipynb2 
# Dataset 
Accidental_Drug_Related_Deaths.csv 
# Project summary and documentation
README.md 
