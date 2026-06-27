---

## ✅ Tasks Completed

### 📌 Task 1 — Student Performance Dataset Analysis
- Loaded and explored the Student Performance dataset (UCI ML Repository — 395 students, 33 features)
- Performed data cleaning and handled missing values (zero missing confirmed)
- Fixed G1, G2 columns stored as text → converted using `pd.to_numeric()`
- Analyzed factors affecting student final grades (gender, study time, parental education)
- Visualized score distributions using Matplotlib & Seaborn
- Generated key statistics: average final grade G3 = 10.42/20, male avg 10.91 vs female 9.97
- **Libraries:** Pandas, Matplotlib, Seaborn

---

### 📌 Task 2 — Titanic Dataset Survival Analysis
- Loaded the Titanic dataset directly from URL (no Kaggle login needed)
- Cleaned missing values (Age filled with median, Cabin dropped — 77% missing, Embarked filled with mode)
- Answered key business questions:
  - Who survived more — Males or Females?
  - Did passenger class affect survival chances?
  - What was the survival rate by age group?
- Created 4 visualizations:
  - Bar chart — Survival rate by Gender (with % labels)
  - Bar chart — Survival rate by Passenger Class
  - Histogram — Passenger Age Distribution (survived vs not survived)
  - Bar chart — Survival rate by Age Group (Bonus)
- Generated a final summary report with all key insights
- **Libraries:** Pandas, Matplotlib, Seaborn, NumPy

---

### 📌 Task 3 — Mini Exploratory Data Analysis (EDA) on Titanic Dataset
- Performed a deeper EDA on the Titanic dataset, building on Task 2 with refined imputation and additional engineered features
- Cleaned missing values (Age filled with mean, Embarked filled with mode, Cabin dropped)
- Engineered new features:
  - **AgeGroup** — binned into Child, Teen, Young Adult, Adult, and Senior using `pd.cut()`
  - **FamilySize** — combined SibSp and Parch into a single feature
- Answered key analysis questions using groupby-based insights:
  - Survival rate by Age Group
  - Survival rate by Embarkation Port
  - Survival rate by Family Size
- Created 4 visualizations:
  - Histogram with KDE — Age Distribution of Passengers
  - Correlation Heatmap — relationships between numeric features
  - Bar chart — Survival Rate by Family Size
  - Bar chart — Survival Rate by Age Group
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

### 📌 Task 4 — Mini Visualization Dashboard (Matplotlib + Seaborn)
- Built a complete mini data visualization dashboard inside a single Jupyter Notebook
- Cleaned missing values and engineered features (AgeGroup + FamilySize) from scratch
- Created **6 distinct chart types** with clear markdown insight under each chart
- Added a Bonus Facet Grid to compare survival across gender and class simultaneously
- Charts included:
  - **Histogram** — Age distribution of all passengers (split by survival)
  - **Bar Chart** — Survival rate by Gender (with % annotations)
  - **Bar Chart** — Survival rate by Passenger Class
  - **Boxplot** — Fare distribution by Passenger Class (with survival hue)
  - **Scatterplot** — Age vs Fare colored by Survival outcome
  - **Heatmap** — Correlation matrix + feature-vs-survival bar chart
  - **Bonus Facet Grid** — Survival rate by Class split across Gender
- Generated a final dashboard summary report with all chart takeaways
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core programming language |
| Pandas | Data loading, cleaning, analysis |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| NumPy | Numerical operations |
| Google Colab | Cloud Jupyter Notebook environment |

---

## 💡 Key Insights from Task 2 (Titanic Survival Analysis)
- **Females** survived at ~74% vs **Males** at only ~19%
- **1st Class** passengers had the highest survival rate (~63%)
- **3rd Class** passengers had the lowest survival rate (~24%)
- **Children (0–12)** had the highest survival among all age groups
- Most passengers were between **20–35 years old**

---

## 💡 Key Insights from Task 3 (Titanic Mini EDA)
- **Age Group:** Children had the highest survival rate, reflecting the "women and children first" evacuation priority
- **Embarkation Port:** Passengers boarding from Cherbourg (C) had a higher survival rate than those from Southampton (S), possibly linked to class distribution at each port
- **Family Size:** Passengers with small families (1–3 members) survived at higher rates than solo travelers or those with very large families
- **Correlation Heatmap:** `Pclass` showed a negative correlation with survival, while `Fare` showed a positive correlation

---

## 💡 Key Insights from Task 4 (Visualization Dashboard)
- **Gender** was the strongest survival factor — females were 4× more likely to survive than males
- **Fare** correlated positively (+0.26) with survival — higher fare = better cabin location = closer to lifeboats
- **Female 1st Class** passengers had ~97% survival rate vs **Male 3rd Class** at only ~14%
- `Pclass` (–0.34) and `Fare` (+0.26) were the strongest numeric predictors of survival
- Age had minimal direct linear correlation with survival as a standalone variable

---

## 📬 Contact

**Email:** mukundrajpurohit07@gmail.com  
**LinkedIn:** [linkedin.com/in/mukund-rajpurohit-1b1104313](https://www.linkedin.com/in/mukund-rajpurohit-1b1104313/)  
**GitHub:** [github.com/mukundraj2005](https://github.com/mukundraj2005)
