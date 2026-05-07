# Customer Churn Prediction & Retention Intelligence System

## Project Overview

This project focuses on predicting customer churn and enabling targeted retention strategies using Machine Learning and Power BI.

The solution combines:
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Predictive Modeling using XGBoost
- Risk Segmentation
- Interactive Power BI Dashboard
- Business Recommendations

---

## Business Objective

The objective of this project is to identify customers who are likely to churn and provide actionable insights that help businesses reduce customer loss and improve retention strategies.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Power BI
- Jupyter Notebook
- GitHub

---

## Machine Learning Approach

### Models Evaluated

- Logistic Regression
- Balanced Logistic Regression
- XGBoost

### Final Model

A calibrated XGBoost model with threshold tuning was selected as the final solution.

### Final Model Performance

| Metric | Value |
|---|---|
| Precision | 0.53 |
| Recall | 0.75 |
| Accuracy | 0.76 |

The model successfully identifies approximately 75% of churners while maintaining controlled false positives.

---

## Key Business Insights

### Contract Type
- 96% of high-risk customers were on month-to-month contracts
- Long-term contracts showed significantly lower churn risk

### Payment Method
- Electronic check users showed the highest churn concentration

### Internet Service
- Fiber optic customers demonstrated significantly higher churn risk

### Customer Behavior
- High-risk customers had:
  - Average tenure of ~23 months
  - Average monthly charges of ~81

---

## Business Recommendations

- Promote long-term contracts using discounts and bundled offers
- Encourage auto-pay and credit card payment methods
- Improve service quality for fiber optic customers
- Launch engagement campaigns for mid-tenure customers
- Offer personalized retention incentives for high-value customers

---

## Dashboard Features

The Power BI dashboard includes:

- KPI Cards
- Risk Segmentation
- Churn Driver Analysis
- Interactive Slicers
- High-Risk Customer Identification
- Business Insight Panels

---

## Repository Structure

```text
Customer-Churn-Analysis/
│
├── data/
├── notebook/
├── dashboard/
├── reports/
├── images/
├── README.md
└── requirements.txt
