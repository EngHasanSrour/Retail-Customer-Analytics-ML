# Retail Customer Analytics & Machine Learning Pipeline

This project implements a complete, production-style machine learning workflow to analyze, predict, and segment retail customer behavior based on campaign performance data. Built entirely within an isolated Scikit-Learn Pipeline architecture, the notebook ensures data leakage prevention and reproducible results.

## Key Pipeline Features

* **Data Preprocessing & Cleaning:** Managed missing attributes via robust median imputation, engineered structural behavioral columns (Age, Total Spending, Total Children), applied outlier constraints, and encoded multi-class categorical factors.
* **Supervised Regression:** Modeled continuous spending behavior across features, evaluating baseline Linear Regression, Ridge ($L_2$ Regularization) to control weight coefficients, and non-linear Decision Tree Regressors.
* **Supervised Classification:** Tackled a severe 85% to 15% target class distribution imbalance. Prioritized Class 1 Recall using an operationally balanced Logistic Regression layout to accurately flag prospective campaign responders.
* **Unsupervised Clustering:**, Determined an optimal group threshold ($k=3$) using a pipeline-driven Elbow Method. Segmented the market into distinct behavioral personas (Affluent Power Spenders, Mature Budget Families, and Younger Starters) mapped visually via 2D Principal Component Analysis (PCA).

## Video Walkthrough
You can view the 5 minute presentation video walkthrough of this project here:
[Watch the Project Presentation Video on Google Drive] (https://drive.google.com/file/d/1HObiFHvF0YMakMdf_mHOqGfIDWBqM7Rc/view?usp=sharing)
