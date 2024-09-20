# Customer Churn Analysis By Python
This repository contains an analysis of customer churn using a dataset that includes customer demographics, services used, and payment details. The goal is to identify key factors that influence customer churn and visualize those metrics to better understand the churn behavior.

## Table of Contents
- Introduction
- Data Overview
- Analysis and Visualizations
- Key Findings
- Conclusion

## Introduction
Customer churn refers to the loss of customers over a given period. It is a critical metric for companies that rely on subscription-based services, and understanding the reasons for churn can help organizations improve customer retention.

This analysis explores patterns in customer behavior, service usage, and demographic characteristics to predict and understand churn.


## Data Overview
The dataset consists of customer data from a telecommunications company. Each record represents a customer with the following attributes:

- Demographic Information: Gender, Senior Citizen, Partner, Dependents
- Service Information: Type of services used such as Phone, Internet, Streaming services
- Account Information: Contract type, Payment method, Monthly charges, Total charges
- Churn: Whether the customer has churned (Yes/No)


## Analysis and Visualizations
### 1. Churn Rate
- Churn Rate: A basic visualization of how many customers have churned.
- Bar Plot: Visualizing churn by demographic attributes like gender, senior citizen status, and dependents.

### 2. Service Usage and Churn
- Internet Service: Analyzing how different types of internet services (DSL, Fiber optic) affect churn.
- Contract Type: Investigating whether customers with month-to-month contracts are more likely to churn.
- Streaming Services: Understanding how services like streaming TV or movies impact churn behavior.

### 3. Payment Metrics
- Monthly and Total Charges: Correlation between higher charges and churn rates.
- Payment Method: Investigating if certain payment methods (e.g., automatic bank transfer) are associated with lower churn.

### 4. Tenure Analysis
- Tenure vs. Churn: Exploring the relationship between the length of time a customer stays with the company and their likelihood to churn.

#### Visualizations
- Churn Distribution
- Monthly Charges vs. Churn
- Contract Type vs. Churn
- Internet Service vs. Churn
 
The visualizations help uncover insights into customer behavior and the factors that are associated with higher churn rates.


## Key Findings
- Month-to-Month Contracts: Customers with month-to-month contracts have a significantly higher churn rate compared to those with longer-term contracts.
- Senior Citizens: Senior citizens are more likely to churn, especially when paying higher monthly charges.
- Internet Service: Fiber optic internet users churn more compared to DSL users.
- Payment Methods: Customers who use automatic payments tend to churn less.



## Conclusion
This analysis provides valuable insights into the factors influencing customer churn. By focusing on long-term contracts and promoting automatic payment methods, the company can potentially reduce churn. Further predictive modeling and feature engineering could enhance the accuracy of churn prediction.
