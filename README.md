# Predictive Analytics for At-Risk Customer Identification

## Objective:
Develop a machine learning model to predict customer churn by selecting an appropriate algorithm, training and validating the model, and defining evaluation metrics to assess its performance. The goal is to generate actionable insights that help the business identify at-risk customers and inform strategies for customer retention.

## Project Summary:
This project involved end-to-end predictive analytics for customer churn at Lloyds. It uses demographic and behavioral data to predict at-risk customers. 

#### Tasks included:
- Data collection
- Data cleaning
- Data preprocessing
- Data integration
- Exploratory data analysis to understand customer behavior.

Random Forest classifier was used to predict churn risk based on demographic and behavioral features, with model performance evaluated using accuracy, precision, recall, F1-score, and precision-recall curves. Threshold calibration was also applied to accurately identify churners while minimizing misclassification of loyal customers, providing insights to support informed business decisions on customer retention strategies.

### Demographics, Spending and Correlation Insight:
- High-income customers dominate the customer base (35%), suggesting that revenue is concentrated among fewer, wealthier individuals. Marketing or retention strategies aimed at this segment could disproportionately affect overall revenue.

- Peaks in spending occur in May 2022, primarily from electronics and furniture, indicating seasonal purchasing behavior.

- Despite a nearly balanced gender distribution, men dominate the high-income bracket, implying male spending drives premium-category sales

- Customer engagement peaked in July 2022 due to feedback activity, suggesting that proactive feedback channels drive interaction spikes.

- Strong positive correlations were observed between total spend, number of transactions, and unique categories, suggesting that higher customer engagement leads to greater spend and a wider variety of products purchased.

### Predictive Modeling & Churn Insights:
- Model recall for churners is high (83%), while precision is low (42%), showing the model captures most at-risk customers but also flags some loyal ones.

- Lowering the prediction threshold increases recall but reduces precision, meaning it’s better to over-identify churners than miss them, aligning with a “better safe than sorry” retention approach

- Churn risk is higher among customers with lower transaction frequency, fewer product categories purchased, and unresolved interactions, as these behavioral factors are associated with decreased spending and engagement

## Tools and Technologies
    Python, Pandas, Scikit-learn, Matplotlib, Seaborn


