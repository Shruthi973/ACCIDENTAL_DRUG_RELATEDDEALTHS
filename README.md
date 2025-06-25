# ACCIDENTAL_DRUG_RELATEDDEALTHS
DRUG RELATED DEALTHS 
## Accidental Drug-Related Deaths (2012–2023) – Clustering & HPC Modeling

This project analyzes over a decade of overdose death data from Connecticut to uncover patterns in substance use across demographic groups. Using statistical models, clustering techniques, and high-performance computing optimizations, it provides insights into the opioid crisis.

### 🔍 Project Highlights
- **Data Source**: Office of the Chief Medical Examiner – CT | 11,982 records
- **Tools Used**: Python, Pandas, Scikit-learn, K-Means, Dask, HPC profiling (fread vs read.csv)
- **ML Models**: Linear Regression & Random Forests to predict opioid use patterns
- **Clustering**: K-Means clustering by age and substance involvement
- **Performance Comparison**: Trained Random Forest with & without Dask parallelization
- **Visualization**: Feature importance, flame graph profiling, Gini impurity-based decision trees

### 📂 What's Inside
- `accidental_ppt.pdf`: Final report summarizing data trends, substance roles, and clustering insights
- `Accidental_dataset.csv`: Cleaned dataset used for modeling
- `Accidental drug related death project.html`: Notebook HTML with full code, visualizations, and profiling results

### 📈 Key Insight
Young adults (20–30s) showed significantly higher Fentanyl involvement, while older groups had broader polysubstance patterns. Parallelization improved tree depth but not runtime significantly.
# Accidental Drug-Related Deaths – Predictive Modeling & Risk Profiling

This project focuses on analyzing and modeling accidental drug-related deaths using real-world data. We aim to uncover demographic and substance-use patterns associated with higher fatality risks and develop classification models to predict high-risk cases. This analysis is crucial for informing public health strategies and early intervention programs.

---

## 📊 Data Overview

- **Dataset:** Drug overdose fatality records with demographic and substance indicators
- **Features include:**
  - Age, sex, race
  - Location of death
  - Presence of substances: Heroin, Cocaine, Alcohol, Benzodiazepines, etc.
- **Target Variable:** Binary classification – Fatal or Non-fatal outcome (based on coded logic)

---

## 🧠 Machine Learning Workflow

### 🛠 Preprocessing
- Cleaned missing values
- Recoded categorical features
- Encoded binary drug indicators
- Scaled features for modeling

### 🔍 Exploratory Data Analysis
- Frequency plots of substances by age group
- Correlation matrix for drug combinations
- Bar charts of overdose locations vs. substance involvement

### 🧪 Modeling & Evaluation
| Model              | Accuracy | Precision | Recall | AUC   |
|-------------------|----------|-----------|--------|-------|
| Logistic Regression | ✅ High interpretability with balanced accuracy  
| Random Forest      | ✅ Best overall performance – robust feature importance  
| K-Nearest Neighbors | Moderate accuracy – sensitive to scaling  
| Naive Bayes        | Baseline model for substance co-occurrence patterns  

### ✅ Final Model: **Random Forest Classifier**
- Most predictive features: Heroin, Age, Cocaine, Benzodiazepines, Sex
- Confusion matrix and ROC AUC indicate strong classification performance

---

## 📈 Key Insights
- Heroin and Cocaine co-use drastically increases fatality risk
- Males aged 20–40 are at significantly higher risk
- Alcohol presence alone is not predictive without other opioids
- Deaths often occur at residence – indicating delayed emergency response

---

## 💡 Future Enhancements
- Incorporate time series trends over years/months
- Geospatial analysis with county-level overdose rates
- Survival modeling for overdose intervention efficacy

---

## 🧰 Tech Stack
- **Language:** Python 3.11  
- **Libraries:** pandas, matplotlib, seaborn, scikit-learn, numpy  
- **Notebook:** JupyterLab / Google Colab compatible  
- **Visualization:** ROC curves, heatmaps, bar charts, pair plots  

---

## 📁 Files
- `Accidental_Drug_Deaths_Analysis.ipynb` – main codebase
- `README.md` – detailed project overview

---

## 👤 Author
Shruthi Reddy Vudem  
_Machine Learning & Health Data Science | MS @ SLU_

📬 [LinkedIn](https://www.linkedin.com/in/shruthireddyvudem) • [GitHub](https://github.com/shruthivudem) • [Email](mailto:shruthivudem864@gmail.com)

---

> ⚠️ Disclaimer: This dataset is used strictly for educational and analytical purposes.
