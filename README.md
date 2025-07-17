# 💼 Data Science & Analytics Internship Tasks

**📍 Internship Organization:** DevelopersHub Corporation  
**📅 Submission Deadline:** August 2, 2025  
**📊 Domain:** Data Science & Machine Learning  
**🔧 Tools Used:** `Python`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🧠 Overview

This repository contains completed tasks for the **Data Science & Analytics Internship** at **DevelopersHub Corporation**. Each task demonstrates practical skills in data analysis, visualization, and predictive modeling using real-world datasets.

---

## 🌸 Task 1: Exploring and Visualizing the Iris Dataset

### 🎯 Objective  
Understand and visualize the **Iris Dataset** to analyze relationships, distributions, and outliers.

### 🛠️ Approach
- Loaded the dataset using `seaborn.load_dataset('iris')`
- Explored structure using `pandas` (`shape`, `columns`, `head`)
- Created visualizations using `seaborn` and `matplotlib`:
  - 🌿 Scatter plot: Petal length vs. Petal width by species
  - 📊 Histograms for all numeric features
  - 📦 Box plots for outlier detection
  - 🔁 Pair plot for complete feature relationships

### 📌 Insights
- Petal length and width are **strongly correlated**, showing **clear separation by species**.
- Setosa has **smaller petals**, while virginica has **larger** ones.
- **Petal measurements** are better for classification than sepal measurements.

📁 **File:** `Task1_Iris_Analysis.ipynb`

---

## 🔁 Task 3: Customer Churn Prediction

### 🎯 Objective  
Predict which **bank customers are likely to churn** using the Churn Modelling Dataset.

### 🛠️ Approach
- Cleaned dataset: Removed irrelevant columns (`RowNumber`, `CustomerId`, `Surname`)
- Encoded categorical variables: `Geography`, `Gender`
- Performed EDA:
  - 📉 Churn distribution by `Geography`
  - 📊 Age distribution by churn status
  - 🧮 Correlation heatmap
- Trained a **Logistic Regression** model
- Evaluated with:
  - ✅ Accuracy score
  - 📉 Confusion matrix
  - 📌 Feature importance

### 📌 Insights
- Model accuracy: **~81.1%**
- Customers who are **older** and from **Germany** (`Geography_Germany`) are more likely to churn.
- Helps banks **target at-risk customers** for **retention strategies**.

📁 **File:** `Task3_Churn_Prediction.ipynb`

---

## 💰 Task 5: Personal Loan Acceptance Prediction

### 🎯 Objective  
Predict which customers are likely to **accept a personal loan offer** using the Bank Marketing Dataset.

### 🛠️ Approach
- Cleaned data:
  - Replaced `"unknown"` with `NaN`
  - Dropped missing rows
  - One-Hot Encoded categorical features (`job`, `marital`, etc.)
- Performed EDA:
  - 📊 Bar plots for `job`, `marital status`
  - ⏳ Histogram for `age`
- Trained a **Logistic Regression** model
- Evaluated performance and analyzed key influencing factors

### 📌 Insights
- Model accuracy: **✅ 92%**
- High likelihood of loan acceptance among:
  - 👔 Customers with **administrative** and **management** jobs
  - 🧑‍💼 Younger customers
  - 📞 Successful campaign call outcomes
- Helps banks design **targeted loan marketing campaigns**

📁 **File:** `Task5_Loan_Acceptance.ipynb`

---

## 📂 Repository Structure

```bash
.
├── Task1_Iris_Analysis.ipynb
├── Task3_Churn_Prediction.ipynb
└── Task5_Loan_Acceptance.ipynb
