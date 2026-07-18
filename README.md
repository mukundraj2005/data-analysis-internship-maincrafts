# 📊 Data Analysis with Python Internship
## Maincrafts Technology | Intern ID: MT5153

---

## 👤 About

**Intern:** Mukund Rajpurohit
**Intern ID:** MT5153
**Domain:** Data Analysis with Python
**Duration:** 20 May 2026 – 20 July 2026 (8 Weeks)
**Organization:** Maincrafts Technology
**Email:** mukundrajpurohit07@gmail.com
**LinkedIn:** [linkedin.com/in/mukund-rajpurohit-1b1104313](https://www.linkedin.com/in/mukund-rajpurohit-1b1104313/)

---

## 📁 Repository Structure

```
data-analysis-internship-maincrafts/
├── Task1_StudentPerformance_MukundRajpurohit.ipynb
├── Task2_TitanicDataset_MukundRajpurohit.ipynb
├── Task3_TitanicEDA_MukundRajpurohit.ipynb
├── Task4_VisualizationDashboard_MukundRajpurohit.ipynb
├── Task5_MLPipeline_MukundRajpurohit.ipynb
└── README.md
```

---

## ✅ Tasks Completed

### 📌 Task 1 — Student Performance Dataset Analysis
- Loaded and explored the Student Performance dataset (UCI ML Repository)
- Performed data cleaning — checked for 0 missing values and 0 duplicates
- Fixed G1, G2 columns stored as text using `pd.to_numeric()`
- Analyzed correlation between study time and final grade (r = 0.10)
- Identified 38 students who scored zero — likely non-attendance
- **Visualisations:** Histogram of final grades, Scatter plot (study time vs grade), Bar chart by gender
- **Libraries:** Pandas, Matplotlib, Seaborn

---

### 📌 Task 2 — Titanic Survival Analysis
- Loaded Titanic dataset (891 records) directly from URL
- Cleaned data: Age (median imputation), Cabin (dropped — 77% missing), Embarked (mode imputation)
- Answered 3 key questions: Gender vs Survival, Class vs Survival, Age Group vs Survival
- **Key Findings:**
  - Female survival rate: **74.20%** vs Male: **18.89%**
  - 1st Class: **62.96%** vs 3rd Class: **24.24%**
  - Children (0–12) had the highest survival rate
- **Visualisations:** 4 charts including paired bar charts and age histogram
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy

---

### 📌 Task 3 — Titanic Mini EDA (Exploratory Data Analysis)
- Deeper EDA on Titanic dataset with feature engineering
- Created `AgeGroup` using `pd.cut()` and `FamilySize = SibSp + Parch`
- Analyzed survival by Age Group, Family Size, and Embarkation Port
- **Key Findings:**
  - Small families (2–3 members) survived more than solo travellers
  - Cherbourg (C) port had highest survival rate (55.4%)
  - Pclass: r = −0.34 (strongest negative correlation with survival)
- **Visualisations:** Age KDE plot, Correlation Heatmap, Family Size bar chart, Age Group bar chart
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy

---

### 📌 Task 4 — Data Visualization Dashboard
- Built a complete 6-chart visualization dashboard on the Titanic dataset
- **Charts Created:**
  1. Histogram — Age distribution
  2. Bar Chart — Survival by Gender
  3. Bar Chart — Survival by Passenger Class
  4. Boxplot — Fare distribution by Class
  5. Scatterplot — Age vs Fare (colored by Survival)
  6. Heatmap — Correlation of numeric variables
  7. **Bonus:** Facet Grid — Survival by Class split by Gender
- **Key Finding:** Female 1st Class: **97% survival** vs Male 3rd Class: **14% survival**
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy

---

### 📌 Task 5 — Complete Machine Learning Pipeline
- Built a **full professional ML pipeline** using scikit-learn on the Titanic dataset
- **Pipeline Steps:**
  - Numeric: Median imputation → StandardScaler
  - Categorical: Most-frequent imputation → OneHotEncoder
  - Model: LogisticRegression (max_iter=1000)
- **Train/Test Split:** 80/20 stratified split
- **Evaluation Metrics:**
  - Test Accuracy: ~81%
  - ROC-AUC: ~0.87
  - Full Classification Report (Precision, Recall, F1)
  - Confusion Matrix
  - ROC Curve
- **5-Fold Cross-Validation:** CV ROC-AUC ~0.86 ± 0.03
- **Model Persistence:** Saved trained pipeline as `model.joblib`
- **Feature Importance:** Extracted Logistic Regression coefficients — Sex (female) was the strongest predictor
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Pandas | Data loading, cleaning, analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical plots |
| Scikit-learn | ML pipeline, preprocessing, modelling, evaluation |
| Joblib | Model persistence |
| Google Colab | Cloud Jupyter Notebook environment |
| GitHub | Version control & submission |

---

## 💡 Key Insights Across All Tasks

- **Study time ≠ good grades** — correlation with final grade was only r = 0.10 (Task 1)
- **Gender was the strongest survival factor** — females survived 4x more than males (Tasks 2, 3, 4, 5)
- **Wealth impacted survival** — 1st Class passengers survived at 2.6x the rate of 3rd Class (Tasks 2, 4, 5)
- **Small families survived more** — family size 2–3 had highest survival rate (Task 3)
- **Logistic Regression achieved ~81% accuracy** as a strong interpretable baseline (Task 5)
- **ROC-AUC of 0.87** means the model correctly ranks survivors above non-survivors 87% of the time (Task 5)

---

## 📬 Contact

**Email:** mukundrajpurohit07@gmail.com
**LinkedIn:** [linkedin.com/in/mukund-rajpurohit-1b1104313](https://www.linkedin.com/in/mukund-rajpurohit-1b1104313/)
**GitHub:** [github.com/mukundraj2005](https://github.com/mukundraj2005)
