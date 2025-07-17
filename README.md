# Data Science & Analytics Internship Tasks

## Overview

This repository contains my completed tasks for the **Data Science & Analytics Internship at DevelopersHub Corporation**, due **August 2, 2025**. The tasks demonstrate skills in data exploration, visualization, and machine learning using Python libraries like `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

---

## Task 1: Exploring and Visualizing the Iris Dataset

**Objective:**  
Understand and visualize the Iris dataset to analyze relationships, distributions, and outliers.

**Approach:**
- Loaded the dataset using `seaborn.load_dataset('iris')`.
- Summarized the dataset using pandas methods (`shape`, `columns`, `head`).
- Created visualizations using seaborn and matplotlib:
  - Scatter plot of petal length vs. petal width, colored by species.
  - Histograms of all numerical features.
  - Box plots to show spread and outliers.
  - Bonus: Pair plot for comprehensive feature relationships.

**Results and Insights:**
- **Petal length and width** are strongly correlated, with clear species separation.
- **Setosa** has the smallest petals, **Virginica** the largest.
- **Sepal width** contains a few outliers; other features are more tightly clustered.
- **Petal measurements** are more effective than sepal measurements for distinguishing species.

📁 **File:** `Task_one_iris_data.html`

---

## Task 3: Customer Churn Prediction

**Objective:**  
Predict which bank customers are likely to churn using the Churn Modelling Dataset.

**Approach:**
- Loaded and cleaned the dataset:
  - Dropped irrelevant columns: `RowNumber`, `CustomerId`, `Surname`.
  - Applied One-Hot Encoding to categorical variables (`Geography`, `Gender`).
- Performed EDA using:
  - Bar plots (churn by geography).
  - Histograms (age distribution by churn status).
  - Correlation heatmap.
- Trained a **Logistic Regression** model and evaluated with:
  - **Accuracy score**
  - **Confusion matrix**
  - **Classification report**
- Analyzed feature importance using model coefficients.

**Results and Insights:**
- The model achieved an accuracy of **~81%**.
- **Older customers** and those with **lower activity** are more likely to churn.
- Key features influencing churn include:
  - `Age`
  - `IsActiveMember`
  - `Geography_Germany`
- This analysis helps banks identify and retain at-risk customers.

📁 **File:** `Task3_Churn_Prediction.html`

---

## Future Tasks

This repository will be updated with additional tasks as they are completed, such as:

- ✅ Personal Loan Acceptance Prediction (coming soon)
- ✅ Time Series Forecasting
- ✅ Deep Learning (Image or NLP-based)

Stay tuned for updates!
