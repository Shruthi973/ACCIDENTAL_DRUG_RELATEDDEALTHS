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
