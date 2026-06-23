# Bank Marketing Prediction

Machine Learning project to predict customer subscription to term deposit products using the Bank Marketing Dataset.

## Project Overview

This project aims to predict whether a customer will subscribe to a term deposit product based on demographic, financial, and marketing campaign information.

The objective is to help banks identify high-potential customers and improve the effectiveness of telemarketing campaigns through data-driven decision making.

---

## Business Problem

Banks often conduct telemarketing campaigns to promote term deposit products. However, contacting every customer is costly and inefficient.

By developing a predictive machine learning model, the bank can prioritize customers who are more likely to subscribe, improving campaign efficiency and reducing marketing costs.

---

## Dataset  

Source: UCI Machine Learning Repository - Bank Marketing Dataset

Dataset Characteristics:

* 45,211 customer records
* 16 input features
* Binary target variable (`y`)
* Target:

  * 0 = No Subscription
  * 1 = Subscription

---

## Project Workflow

1. Business Understanding
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Engineering
6. Model Development
7. Model Evaluation
8. Feature Importance Analysis
9. Business Insights
10. Business Recommendations

---

## Models Used

### Logistic Regression

* Accuracy: 90.12%
* Precision: 64.40%
* Recall: 34.88%
* F1 Score: 45.25%
* ROC-AUC: 90.54%

### Random Forest

* Accuracy: 90.49%
* Precision: 65.81%
* Recall: 38.94%
* F1 Score: 48.93%
* ROC-AUC: 92.72%

---

## Best Model

Random Forest achieved the best overall performance and was selected as the final model.

---

## Key Findings

* Call duration was the most influential feature.
* Customers with higher account balances were more likely to subscribe.
* Previous successful marketing outcomes strongly increased subscription probability.
* Students and retired customers showed higher conversion rates.
* Contact method influenced campaign effectiveness.

---

## Business Recommendations

* Prioritize customers with previous successful campaign outcomes.
* Focus marketing efforts on high-conversion customer segments.
* Improve customer contact information quality.
* Optimize telemarketing strategies to increase customer engagement.
* Incorporate financial indicators into campaign targeting strategies.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Project Structure

```
bank-marketing-prediction/
│
├── bank_marketing_prediction.ipynb
├── bank-full.csv
├── requirements.txt
└── README.md
```
