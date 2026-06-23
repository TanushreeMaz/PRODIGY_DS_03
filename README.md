<p align="center">
  <img src="Banner.jpg" width="100%">
</p>

# Bank Marketing Subscription Prediction

A machine learning project focused on predicting whether a customer will subscribe to a term deposit using the Bank Marketing dataset from the UCI Machine Learning Repository. The project combines data preprocessing, exploratory analysis, feature engineering, and Decision Tree modeling to identify the demographic and behavioral factors that influence customer subscription decisions.

The objective is to transform raw campaign data into actionable insights that can help financial institutions improve marketing efficiency and target potential customers more effectively.

# Project Overview

Direct marketing campaigns are widely used by banks to promote financial products, but contacting every customer can be costly and inefficient. This project analyzes 45,211 customer records from a Portuguese banking institution to understand the factors that drive subscription decisions and build a predictive model for customer targeting.

The analysis focuses on answering key questions:

• Which customer groups are most likely to subscribe to a term deposit?

• How do demographic factors such as age, job, education, and marital status influence outcomes?

• What impact do previous marketing campaigns have on customer decisions?

• Which financial and behavioral attributes are the strongest predictors of subscription?

• Can a Decision Tree model accurately predict customer responses and support marketing strategies?


# Problem Statement

Financial institutions conduct marketing campaigns to promote term deposits. However, contacting every customer can be costly and inefficient.

The objective of this project is to build a Decision Tree Classifier that predicts whether a customer will subscribe to a term deposit based on demographic information and previous campaign interactions.


# Dataset Overview

The Bank Marketing dataset was obtained from the UCI Machine Learning Repository. It contains information collected from direct marketing campaigns conducted by a Portuguese banking institution. The objective is to predict whether a client will subscribe to a term deposit based on demographic, financial, and campaign-related attributes.



## Project Objectives

- Understand customer characteristics influencing term deposit subscriptions
- Perform exploratory data analysis to identify patterns and trends
- Preprocess and encode categorical features
- Build and evaluate a Decision Tree classification model
- Identify the most influential features affecting subscription decisions


# Workflow

Data Loading
      ↓
Basic Data Exploration
      ↓
Exploratory Data Analysis
      ↓
Data Preprocessing
      ↓
Feature Encoding
      ↓
Train-Test Split
      ↓
Decision Tree Training
      ↓
Model Evaluation
      ↓
Confusion Matrix Visualization
      ↓
Decision Tree Visualization
      ↓
Feature Importance Analysis


## Dataset Information

| Attribute |	Value |
|----------|----------|
| Source | UCI Machine Learning Repository |
| Dataset Name | Bank Marketing |
| Task Type |	Classification |
| Records |	45,211 |
| Features | 16 Input Features + 1 Target Variable |
| Target | Variable	Subscription (y) |
| Data Type |	Multivariate |
| Missing Values | No |
| Domain | Banking & Marketing |


## Key Feature Categories
• Demographic: Age, Job, Marital Status, Education
• Financial: Balance, Housing Loan, Personal Loan, Credit Default
• Campaign Information: Contact Type, Month, Duration, Campaign Contacts
• Previous Marketing Activity: Previous Contacts, Previous Outcome, Days Since Last Contact
• Target Variable: Whether the client subscribed to a term deposit (Yes/No)


# Exploratory Data Analysis

## Target Distribution

<img width="488" height="394" alt="image" src="https://github.com/user-attachments/assets/e0758851-fa56-4f05-bd8e-df671b3253e0" />

The target variable is imbalanced, with non-subscribers significantly outnumbering subscribers.


## Correlation Heatmap

<img width="738" height="586" alt="image" src="https://github.com/user-attachments/assets/9aa50809-8d03-480d-b32e-d444e539f423" />


## Model Insights

### Feature importance

<img width="786" height="495" alt="image" src="https://github.com/user-attachments/assets/656b3c1a-a48e-47ba-acd4-b68abea338fa" />

Campaign-related features contributed most to the Decision Tree model's predictions.

### Confusion matrix

<img width="469" height="389" alt="image" src="https://github.com/user-attachments/assets/af832961-e450-4065-b310-883e6014d520" />

The heatmap highlights relationships among numerical variables and helps identify potential predictors.

### Decision Tree

<img width="1705" height="840" alt="Screenshot 2026-06-22 223803" src="https://github.com/user-attachments/assets/088d233f-70a8-4b22-b2ce-9c4dc52d3bea" />



## Key Insights

- Previous campaign success was one of the strongest indicators of future subscription.
- Customers contacted during specific months showed higher conversion rates.
- Financial indicators such as account balance influenced subscription behavior.
- Campaign-related variables ranked among the most important predictors.
- The Decision Tree model provided interpretable rules for customer targeting.


## Project Structure

```text
PRODIGY_DS_03/
│
├── Data/
│   └── bank.csv
│
├── Notebook/
│   └── Bank_Marketing_DecisionTree.ipynb
│
├── Reports/
│   ├── Bank_Marketing_Analysis.pdf
│
├── Images/
│   ├── Subscription_Distribution.png
│   ├── Correlation_Heatmap.png
│   ├── Feature_Importance.png
│   ├── Confusion_Matrix.png
│   └── Decision_Tree.png
│
│
├── README.md
│
└── requirements.txt
```      
                   

## Detailed Report

A complete analysis including data preprocessing, exploratory data analysis, model development, and business insights is available in:

Bank_Marketing_Analysis.pdf



## Tools & Technologies

| Category | Tools |
|----------|----------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Development | Jupyter Notebook |
| Version Control | Git & GitHub |


## Conclusion

The Decision Tree Classifier successfully identified patterns influencing customer subscription behavior. The model provided interpretable decision rules and highlighted the most influential demographic and behavioral factors. This project demonstrates how machine learning can support targeted marketing strategies and improve campaign efficiency.


# About

**Tanushree Mazumdar**
Data Analyst | Data Science Intern @ Prodigy InfoTech
Simplilearn & IBM Certified Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tanushree-mazumdar2195)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tanushreemaz)
[![Portfolio](https://img.shields.io/badge/Portfolio-0B3C5D?style=for-the-badge&logo=google-chrome&logoColor=white)](https://tanushreemaz.github.io)






