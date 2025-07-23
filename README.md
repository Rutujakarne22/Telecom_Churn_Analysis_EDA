# Telecom Churn Analysis & Prediction

A machine learning project to analyze telecom customer behavior and predict churn using Python. The goal is to help telecom companies identify customers at risk of leaving and take proactive steps to retain them.

---

## Overview

Customer churn is a major concern in the telecom industry as acquiring new customers is more expensive than retaining existing ones. This project applies exploratory data analysis and classification models to identify factors driving churn and predict which customers are likely to leave.

---

## Problem Statement

Many telecom companies struggle with high churn rates but lack clarity on what features drive churn. This project aims to solve that by:

- Understanding customer behavior patterns
- Identifying the key drivers of churn
- Building a predictive model to flag churn-prone customers

---

## Objective

- Perform in-depth EDA to identify patterns in churn behavior.
- Build classification models to predict customer churn.
- Extract actionable business insights from key features and model performance.

---

## Tools & Technologies Used

- **Languages:** Python
- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn
- **Algorithms:** Logistic Regression, Random Forest
- **Other Techniques:** Outlier handling (IQR), Feature Importance, Evaluation Metrics

---

##  Key Insights

- Customers with **high MonthlyCharges** and **short tenure** are more likely to churn.
- **Contract type**, **TotalCharges**, and **OnlineSecurity** significantly affect churn behavior.
- Churn is higher among users with **month-to-month contracts** and **electronic payment methods**.

---

## Model Performance Summary

| Model               | Accuracy | Recall (Churn - Yes) | Notes                               |
|---------------------|----------|----------------------|--------------------------------------|
| Logistic Regression | 78.85%   | 51%                  | Good overall accuracy, weak on churn class |
| Random Forest       | 78.56%   | 49%                  | Similar accuracy, slightly lower recall |

> Both models show class imbalance issues — recall for churn class is low, indicating room for improvement via class balancing or advanced models.

---

## Conclusion & Recommendation

- The analysis shows that **cost-related features** (MonthlyCharges, TotalCharges) and **contract length** are major drivers of churn.
- To reduce churn, telecom companies should:
  - Offer **discounts** or **rewards** for long-term contracts.
  - Target high-risk users with **personalized retention strategies**.
  - Improve customer experience, especially for users with **high bills** and **short tenure**.
  


