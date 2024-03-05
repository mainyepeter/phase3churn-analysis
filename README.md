# churn-analysis
# Overview
This dataset contains information about customers of a telecom company and whether they churned or not. Churn refers to the phenomenon of customers leaving a service or product. The dataset includes various features that can be used to predict churn behavior

## Problem statement:
The problem we aim to address in this project is predicting customer churn in a telecom dataset. By analyzing customer data such as usage patterns, demographics, and customer service interactions, we aim to develop a predictive model that can accurately identify customers who are likely to churn. This model will enable telecom companies to proactively intervene and implement retention strategies to reduce churn rates

## Business Understanding:

The telecom industry is highly competitive, with customer churn being a significant concern for telecom companies. Customer churn refers to the phenomenon where customers switch from one service provider to another or discontinue services altogether. High churn rates can result in revenue loss, decreased market share, and increased marketing costs to acquire new customers.

Understanding the factors that contribute to churn is essential for telecom companies to develop effective retention strategies. By analyzing customer data, telecom companies can identify patterns and behaviors that are associated with churn. This understanding enables them to take proactive measures to retain customers, improve satisfaction, and enhance the overall customer experience.

# Data Understanding:
The dataset comprises both numerical and categorical features.
The target variable is 'Churn', which indicates whether a customer churned or not.
Features like 'International Plan', 'Voice Mail Plan' provide information about additional services subscribed by the customers.
Call-related features such as 'Total Day Minutes', 'Total Eve Minutes', etc., provide insights into customer behavior.
'Customer Service Calls' could be indicative of customer satisfaction or dissatisfaction.

The dataset contains information about telecom customers and various features that might influence their decision to churn. Here are the key attributes:

State: The state in which the customer resides (categorical).

Account Length: The number of days the customer has been with the telecom company (numerical).

Area Code: The area code of the customer's phone number (categorical).

Phone Number: The customer's phone number (categorical).

International Plan: Whether the customer has an international calling plan (categorical: 'yes' or 'no').

Voice Mail Plan: Whether the customer has a voice mail plan (categorical: 'yes' or 'no').

Number of Vmail Messages: The number of voice mail messages the customer has (numerical).

Total Day Minutes: Total minutes of day calls (numerical).

Total Day Calls: Total number of day calls (numerical).

Total Day Charge: Total charge for day calls (numerical).

Total Eve Minutes: Total minutes of evening calls (numerical).

Total Eve Calls: Total number of evening calls (numerical).

Total Eve Charge: Total charge for evening calls (numerical).

Total Night Minutes: Total minutes of night calls (numerical).

Total Night Calls: Total number of night calls (numerical).

Total Night Charge: Total charge for night calls (numerical).

Total Intl Minutes: Total minutes of international calls (numerical).

Total Intl Calls: Total number of international calls (numerical).

Total Intl Charge: Total charge for international calls (numerical).

Customer Service Calls: Number of customer service calls made by the customer (numerical).

Churn: The target variable indicating whether the customer churned or not (categorical: 'yes' or 'no').

##  Main Objective
Build a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company

## Visualisations
# The percentage of loyal customers 
![image](https://github.com/mainyepeter/phase3churn-analysis/assets/151636772/f0a0df70-f911-4185-a542-53c6cf5690d2)

85.5% are loyal customers 

## Relationship between the number of calls to the call center and Churn
![image](https://github.com/mainyepeter/phase3churn-analysis/assets/151636772/350dfaa1-551a-43ab-8ada-f7faa51835e0)

From the plot, it's evident that most customers have made fewer customer service calls, with a decreasing number of customers as the count of calls increases





