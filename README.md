# Data Science & Analytics - Advanced Internship Tasks
This repository contains my solutions for the Advanced Data Science Internship at Developers Hub Corporation. 

## Task 1: Term Deposit Subscription Prediction (Bank Marketing)
* **Objective:** Predict whether a bank customer will subscribe to a term deposit.
* **Approach:** Encoded categorical features, split the data, and trained a Random Forest Classifier. Evaluated using F1-Score, ROC Curve, and Explainable AI (SHAP) for model interpretability.
* **Results:** The model successfully classified customers. SHAP summary plots revealed the most important features driving the customer's decision.

## Task 2: Customer Segmentation Using Unsupervised Learning
* **Objective:** Cluster mall customers based on their annual income and spending score to propose marketing strategies.
* **Approach:** Conducted EDA, applied K-Means Clustering (Optimal K=5 using Elbow Method), and used PCA to reduce dimensions and visualize the clusters in a 2D space.
* **Results:** Identified 5 distinct customer segments (e.g., High Income/High Spenders, Low Income/Sensible Spenders) and proposed tailored marketing strategies for each.

## Task 4: Loan Default Risk with Business Cost Optimization
* **Objective:** Predict loan default likelihood and optimize the decision threshold to minimize the bank's total business cost (False Positives vs. False Negatives).
* **Approach:** Cleaned data, trained a Logistic Regression model, and simulated a cost-benefit analysis by assigning penalty values to False Positives and False Negatives across different thresholds.
* **Results:** Found the optimal probability threshold that minimizes the estimated business cost, demonstrating that adjusting the threshold is more profitable than just relying on default accuracy.
