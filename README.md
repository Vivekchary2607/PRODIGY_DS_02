# 🧠 PRODIGY_DS_02 – Task 02: Data Cleaning & EDA

## 📌 Task Description  
**Objective**: Perform **data cleaning** and **exploratory data analysis (EDA)** on a dataset of your choice (Titanic dataset). The focus is on exploring variable relationships, handling missing or inconsistent data, and uncovering trends and patterns that can inform predictive modeling.

---

## 📁 Dataset Used

**Dataset**: `Titanic.csv` (Kaggle Titanic Survival Data)  
**Records**: 891 entries  
**Features**:
- **Target**: `Survived` (0 = No, 1 = Yes)  
- **Categorical**: `Sex`, `Embarked`, `Pclass`  
- **Numerical**: `Age`, `Fare`, `SibSp`, `Parch`

---

## 🧹 Data Cleaning Steps

- ✅ Handled **missing values**:
  - Filled missing `Age` using **median imputation**
  - Dropped records with missing `Embarked`
- ✅ Converted **categorical columns** to numeric:
  - Used **Label Encoding** on `Sex` and `Embarked`
- ✅ Removed irrelevant or high-missing-value columns like `Cabin` and `Ticket`
- ✅ Checked and corrected **data types** for numerical operations

---

## 📊 Exploratory Data Analysis (EDA)

To understand variable distributions and relationships, various plots and analyses were performed:

- 🔸 **Survival Rate by Gender**  
- 🔸 **Survival Rate by Pclass (Passenger Class)**  
- 🔸 **Age Distribution of Survivors vs Non-Survivors**  
- 🔸 **Embarked Port and Survival Correlation**  
- 🔸 **Fare Analysis by Class and Survival**  
- 🔸 **Heatmap of Correlation Matrix** to identify linear dependencies

---

## 🛠️ Libraries Used

- `pandas` – Data wrangling  
- `numpy` – Numeric operations  
- `seaborn` & `matplotlib` – Visualizations  
- `sklearn.preprocessing` – Label Encoding

---

## 📌 Summary

> The analysis revealed that features like **gender**, **passenger class**, and **age** have a strong relationship with survival.  
> Female passengers and first-class passengers had significantly higher survival rates.  
> Children and younger individuals also showed better survival odds.

---

## 📷 Visual Outputs

- 📊 Gender vs Survival (bar plot)  
- 📉 Age Distribution by Survival (histogram + KDE)  
- 💰 Fare vs Pclass vs Survival (boxplot)  
- 🗺️ Embarked Port Survival Rate  
- 🔥 Correlation Heatmap

---

## ✅ Outcome

- Cleaned and structured dataset ready for modeling  
- Gained insights into **key influencing features**  
- Uncovered imbalances in target and classes  
- Set a foundation for future classification or prediction tasks
