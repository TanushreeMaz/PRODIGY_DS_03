

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

# Bank Marketing Subscription Prediction

[![Dataset](https://img.shields.io/badge/Dataset-UCI%20Repository-orange?style=for-the-badge)](https://archive.ics.uci.edu/dataset/222/bank+marketing)


## Machine Learning Workflow

### Data Preparation
- Loaded and explored the dataset
- Checked data types and missing values
- Encoded categorical variables

### Exploratory Data Analysis
- Customer demographics
- Campaign performance analysis
- Subscription distribution

### Model Development
- Train-Test Split
- Decision Tree Classifier
- Hyperparameter tuning

### Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

### Model Interpretation
- Feature Importance Analysis
- Decision Tree Visualization


## Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | XX% |
| Precision | XX% |
| Recall | XX% |
| F1 Score | XX% |


## Key Insights

- Previous campaign outcomes strongly influenced subscription decisions.
- Customers with longer call durations showed higher subscription rates.
- Certain job categories demonstrated higher acceptance rates.
- Housing and personal loan status impacted customer responses.
- Decision Tree rules provided clear and interpretable business insights.

PRODIGY_DS_03/                                         
│                                             
├── Data/                                          
│   └── bank.csv                                         
│                                                                        
├── Notebook/                                       
│   └── Bank_Marketing_DecisionTree.ipynb                                  
|                         
│                          
├── Images/                                              
│   ├── Decision_Tree.png                           
│   ├── Confusion_Matrix.png                       
│   ├── Feature_Importance.png                   
│   └── Subscription_Distribution.png                    
│                                         
├── README.md                                 
│                      
└── requirements.txt                    


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






