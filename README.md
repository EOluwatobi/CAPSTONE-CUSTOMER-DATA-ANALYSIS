# CAPSTONE-CUSTOMER-DATA-ANALYSIS

[Introduction](introduction)


[Data Overview](#data-overview)


[Data Cleaning and Methodology](#data-cleaning-and-methodology)


[Explorative Data Analysis](#explorative-data-analysis)


[Dashboard Overview](#dashboard-overview)



## Introduction
---
This project focuses on analyzing customer data to understand the subscripton patterns of customers. The primary objectives are:
- Sectionalizing customers based on subscription type.
- Tracking and analyzing susbscription trends and their performance.
- Identify customers based on cancellation and retention subsription patterns to understand and uncover factors influencing trend.


## Data Overview
---

The dataset has the following content: ([LITA Capstone customer.csv](https://github.com/user-attachments/files/17653908/LITA.Capstone.customer.csv)
- Customer Id: The unique identifier of each customer
- Customer Name: The names of all customers
- Region: The region which every customer is based.
- Subscription Type: This is categorized into three part(Basic, Premium and Standard) based on customers preference
- Subscription Starts: The start date which a customer subscribed to a subscription type
- Subscription End: The End data which a customer cancels his/her subscription type.
- Cancelled: This is categorized as False and True. False validates that the customer did not cancel the subscription type while True validates that the subscription type of that customer has ended.
- Revenue: The income generated per customer based on the subscription type.

## Data Cleaning and Methodology
---

The following actions were performed in this phase:
- Remove duplicate data
- Added subscription duration column by using DAX function(SunscriptionEnd - SubscriptionStart) 
- Identify cancellation patters of subscription type
- Track the popular subscription type such as exploring the factors of patterns based on duration.


## Explorative Data Analysis
---

The following questions provided insights on the data
- What is the total number of customers from each region. 
- Determine the most popular subscription type by the number of customers. 
- Determine customers who canceled their subscription within 6 months. 
- What is the average subscription duration for all customers. 
- Find customers with subscriptions longer than 12 months. 
- calculate total revenue by subscription type. 
- Determine he top 3 regions by subscription cancellations. 
- Find the total number of active and canceled subscriptions.

## Dashboard Overview
![Screenshot 2024-11-06 231905](https://github.com/user-attachments/assets/df8dc991-9914-40c9-be42-8b0819b38794)



![Screenshot 2024-11-06 232001](https://github.com/user-attachments/assets/e4693508-6ce9-4190-8e8a-c2870317682c)



