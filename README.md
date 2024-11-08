# CAPSTONE-CUSTOMER-DATA-ANALYSIS

[Introduction](introduction)


[Data Overview](#data-overview)


[Data Cleaning and Methodology](#data-cleaning-and-methodology)


[Explorative Data Analysis](#explorative-data-analysis)


[Dashboard Overview](#dashboard-overview)


[Findings and conclusion](#findings-and-conclusion)



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


## Tools Used
  - Microsoft Excel
  - Structured Query Language(SQL)
  - PowerBi
  

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




![Screenshot 2024-11-07 003257](https://github.com/user-attachments/assets/7ce3d581-ce38-481d-91b5-3ded26e66688)


### Findings and conclusion
---

- The report shows a total number of 33,787 subscribers and a total revenue of $67,540,175 was generated from all the subscribers of subscription type across the 4 operating regions. The East region produced a larger revenue of 25.11%, following closely is the South region with 25.02%, the North region contributed 24.90% and the West region contributed the least revenue of 24.97%. 
- The Basic subscription pattern is the most preferred and popular subscription type having the highest subscribers of 16,921 producing a total of 50.01% revenue. A total number of 8,446 customers subscribed for the Premium subscription type with a percentage revenue of 25.02%. The Standard subscription type being the least has 8,420 subscribers generating 24.97% revenue. 
- Out of 33,787 subscribers, 18,612 customers remained active with their subscription type while 15,175 customers cancelled their subscription which 5,067 were basic subscribers who were from the North region, 5,064 were Premium subscribers from the South Region and 5,044 were Standard subscribers from the West Region. The analysis shows that 8,488 who are the basic subscribers from the East Region did not cancel their subscription, hence, they are satisfied with their Basic subscription type. 
- The subscription duration is 12 months, however, Seven (7) customers subscribed longer than 12 months. 3 Basic subscribers, 2 Premium and Standard subscribers respectively. 




