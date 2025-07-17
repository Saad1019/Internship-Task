# Data Science & Analytics Internship Tasks

**Overview**  
This repository contains my completed tasks for the **Data Science & Analytics Internship** at **DevelopersHub Corporation**. The tasks demonstrate skills in data exploration, visualization, and machine learning using Python libraries like `pandas`, `matplotlib`, `seaborn`, and `scikit-learn`.

---

## Task 1: Exploring and Visualizing the Iris Dataset

**Objective:**  
Understand and visualize the Iris Dataset to analyze relationships, distributions, and outliers.

**Approach:**
- Loaded the dataset using `seaborn.load_dataset('iris')`.
- Summarized the dataset structure using `pandas` methods (`shape`, `columns`, `head`).
- Created visualizations using `seaborn` and `matplotlib`:
  - Scatter plot of petal length vs. petal width, colored by species.
  - Histograms of all numerical features.
  - Box plots to show spread and outliers.
  - Bonus: pair plot for comprehensive relationships.

**Results and Insights:**
- Petal length and width are strongly correlated, with clear species separation (setosa has smaller petals, virginica larger).
- Sepal width has a few outliers; other features are tightly clustered.
- Petal measurements are more effective than sepal measurements for distinguishing species.

**File:** `Task1_Iris_Analysis.ipynb`

---

## Task 3: Customer Churn Prediction

**Objective:**  
Predict which bank customers are likely to churn using the **Churn Modelling Dataset**.

**Approach:**
- Loaded and cleaned the dataset, dropping irrelevant columns (`RowNumber`, `CustomerId`, `Surname`).
- Encoded categorical features (`Geography`, `Gender`) using One-Hot Encoding.
- Performed EDA with:
  - Bar plots (churn by Geography),
  - Histograms (Age by churn),
  - Correlation heatmap.
- Trained a **Logistic Regression** model.
- Evaluated the model with accuracy and a confusion matrix.
- Analyzed feature importance using model coefficients.

**Results and Insights:**
- The model achieved an accuracy of ~*81.1*%.
- Older customers and those with lower activity are more likely to churn.
- Key features influencing churn include *`Age`,`Geogrpahy_germany` * ,.
- The analysis helps banks target at-risk customers for retention.

**File:** `Task3_Churn_Prediction.ipynb`

---

## Task 5: Personal Loan Acceptance Prediction

**Objective:**  
Predict which customers will accept a personal loan offer using the **Bank Marketing Dataset**.

**Approach:**
- Loaded and cleaned the dataset:
  - Replaced “unknown” values with `NaN`,
  - Dropped rows with missing values,
  - Encoded categorical features (`job`, `marital`, etc.) using One-Hot Encoding.
- Performed EDA with:
  - Bar plots (`job`, `marital status`),
  - Histogram (`age`).
- Trained a **Logistic Regression** model.
- Evaluated the model with accuracy and a confusion matrix.
- Analyzed feature importance to identify customer groups likely to accept loans.

**Results and Insights:**
- The model achieved an accuracy of **92%**.
- Administrative and management jobs, younger customers, and effective campaign calls increase loan acceptance.
- Key features include `duration`, `poutcome_success`, and job type.
- The analysis helps banks target customers like young professionals for loan campaigns.

**File:** `Task5_Loan_Acceptance.ipynb`
