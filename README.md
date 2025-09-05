# Customer-Churn-Analysis
## Introduction
This repository contains a comprehensive analysis of customer churn, exploring factors that influence customer retention and identifying patterns that lead to churn. The project utilizes PowerBI to provide actionable insights, empowering businesses to make data-driven decisions for improving customer retention strategies.
## Problem Statement
 A canadian bank provided a churn database containing six months of transactional and demographic data for 10,000 customers. The goal of this project is to analyze this dataset to identify key drivers of churn, build predictive models to anticipate customer behavior, and recommend actionable strategies to improve retention rates and overall customer satisfaction.
## Data Sourcing
The dataset contains 10,000 customer records collected over six months, including demographic, financial, and engagement attributes.
Dataset Features:
Demographics: Age, Gender, Geography, Tenure.<br>
Customer Information: Credit Score, Balance, Number of Products, Active/Inactive status.<br>
Target Variable: Churn indicator (1 = churned, 0 = retained).<br>
- Raw Churned Dataset<b>
<img width="1158" height="431" alt="image" src="https://github.com/user-attachments/assets/d14ec88b-7a38-40f3-be06-0d2a81221eaf" /><br>
[Data Dictionary](https://docs.google.com/document/d/1LujgftXUBdd7fEscYFml0meJq6xdREsph_pw--PRMeU/edit?usp=classroom_web&authuser=0)

## Data Cleaning & Transformation<br>
Steps performed to prepare the dataset:<br>
Handled missing values in demographic and financial attributes.<br>
Removed duplicate records.<br>
Standardized categorical fields (e.g., gender, geography).<br>
Created new grouped columns like:<br>
Age Group<br>
Credit Score Status<br>
Membership Status<br>
Credit Card Validation<br>
Customer Churn Status<br>
<img width="1155" height="419" alt="image" src="https://github.com/user-attachments/assets/9657363d-03f3-4e43-a856-ffec529ed4f7" /><br>

## Dashboard<br>

<img width="765" height="431" alt="image" src="https://github.com/user-attachments/assets/4817354c-0cab-4737-afed-2f81dbd13bbf" />

# Insights<br>

Key findings from the churn analysis:<br>
- Demographics: Younger customers churned more frequently.<br>

- Geography: Some regions showed disproportionately high churn.<br>

- Tenure: Customers with shorter tenure were more likely to churn.<br>

- Balance: Customers with very low or very high balances showed higher churn risk.<br>

- Product Usage: Single Credit card customers were significantly more likely to churn.<br>

- Engagement: Inactive customers had the highest churn rate.<br>

 # Recommendations<br>

To reduce churn and improve customer retention, the bank should:<br>

Target At-Risk Segments – focus campaigns on young customers, single-product holders, and inactive users.<br>

Enhance Engagement – loyalty programs, personalized offers, and proactive support*.<br>

Cross-Selling Opportunities – encourage multiple product adoption to increase stickiness.<br>

Improve Onboarding – support new customers with personalized services.<br>

Region-Specific Strategies – address high-churn geographies with tailored offers.<br>

Predictive Monitoring – implement churn prediction models for early intervention.<br>



