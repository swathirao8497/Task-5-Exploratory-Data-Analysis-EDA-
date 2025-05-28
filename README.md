# Task-5-Exploratory-Data-Analysis-EDA-
# 🧪 Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

## 🎯 Objective
Perform Exploratory Data Analysis (EDA) to uncover patterns, trends, and anomalies in the **Titanic dataset** using Python libraries such as Pandas, Matplotlib, and Seaborn.

---

## 🛠️ Tools Used
- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Dataset
**Dataset:** Titanic Dataset  
- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)  
- Format: CSV  
- Sample Columns:
  - `PassengerId`
  - `Survived`
  - `Pclass`
  - `Name`
  - `Sex`
  - `Age`
  - `SibSp`
  - `Parch`
  - `Fare`
  - `Embarked`

---

## 🚀 How to Run

1. Clone or download the repo.
2. Open the `.ipynb` file (`titanic_eda.ipynb`) in Jupyter Notebook.
3. Make sure the dataset CSV file is in the same folder.
4. Run all cells to view analysis and plots.

---

## 🧭 EDA Workflow

### 📌 Step 1: Basic Exploration
- Use `.head()`, `.info()`, `.describe()`, `.value_counts()`  
- Identify missing values, data types, and distributions.

### 📌 Step 2: Univariate Analysis
- Histograms, count plots for individual columns like `Age`, `Survived`, `Pclass`, etc.

### 📌 Step 3: Bivariate Analysis
- Compare survival rates across `Sex`, `Pclass`, `Embarked` using bar charts.
- Use `sns.boxplot()` and `sns.violinplot()` to analyze `Fare` and `Age` by survival.

### 📌 Step 4: Multivariate Analysis
- Use `sns.pairplot()` to explore interactions.
- Use `sns.heatmap()` to visualize correlations.

---

## 📈 Visualizations Used
- Histogram
- Count Plot
- Box Plot
- Scatter Plot
- Heatmap
- Pairplot

---

## ✍️ Key Observations
- Female passengers had a higher survival rate.
- Passengers in 1st class were more likely to survive.
- Younger passengers had slightly higher survival chances.
- Some features like `Cabin` and `Age` had missing values that required handling.

---

## 📋 Deliverables
- ✅ Jupyter Notebook (`titanic_eda.ipynb`)
- ✅ PDF Export of Notebook (`titanic_eda_report.pdf`)
- ✅ Summary of findings with visual observations

---

## 🎯 Learning Outcome
- Learn how to analyze and visualize data
- Identify relationships, trends, and anomalies
- Prepare for interviews and real-world analysis tasks

---

## ❓ Sample Interview Questions
1. What does the correlation heatmap show about the Titanic dataset?
2. How did class and gender affect survival rate?
3. What would you do about missing values in a dataset like this?

---

