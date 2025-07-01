# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) project performed on the Titanic dataset, as part of the **Data Analyst Internship - Task 5** at Cognifyz Technologies.

---

## 📊 Objective

To analyze the Titanic dataset using Python and extract meaningful patterns, relationships, and insights using both statistical and visual methods.

---

## 📁 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data?select=train.csv)
- File Used: `train.csv`

---

## 🛠 Tools & Libraries Used

- **Python**
- **Jupyter Notebook**
- **Pandas** (data manipulation)
- **Matplotlib & Seaborn** (data visualization)

---

## 🔍 EDA Steps Performed

1. **Data Loading & Overview**
   - Used `.head()`, `.info()`, `.describe()` for basic understanding
   - Identified missing values

2. **Data Cleaning**
   - Filled missing values (e.g., Age with median, Embarked with mode)
   - Dropped the `Cabin` column due to excessive missing data

3. **Univariate Analysis**
   - Distribution of variables like Age, Gender, Pclass, Survived

4. **Bivariate & Multivariate Analysis**
   - Survival based on Gender, Class, Age
   - Correlation heatmap and pairplot

5. **Visualizations**
   - Count plots, Histograms, Boxplots, Heatmaps, Pairplots

6. **Observations**
   - Female passengers had a higher survival rate
   - First-class passengers had a better chance of survival
   - Age and Fare showed some correlation with survival

---

## 📌 Key Insights

- **Sex** and **Pclass** are strong indicators of survival.
- Younger passengers and those who paid higher fares were slightly more likely to survive.
- The dataset has imbalanced features (more males, more 3rd class passengers).

---

## 📄 Files Included

- `Titanic_EDA.ipynb` — Jupyter notebook with complete analysis
- `train.csv` — Dataset 
- `README.md` — Project overview and documentation
