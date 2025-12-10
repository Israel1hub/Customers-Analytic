# Customer Analytics
An analysis of customer data highlighting purchasing behaviors, lifetime value, and marketing strategies.

## Introduction 

A synthetic dataset for customers was generated from Chatgpt, spanning 2022 to 2025, to explore customers purchasing behaviour using RFM analysis and evaluating customer lifetime value (CLV) which are marketing techniques that help identify and segment customers on the basis of their purchasing behaviour and to create marketing strategies.

## About the Dataset 
The dataset provided was from 2022 to 2025.It includes various information on 1,000 customers offering insight into various aspects of customer recency, frequency and Monetary value, below are details about the dataset.

- Scope: 1,000 customers
- Timeframe : 2022 - 2025
- Content: Detailed information on Customers,Transactions,Marketing and Web Analytics
- File type : CSV
- Structure: 5 Tables
- Dataset:Customers,Transactions,Marketing and Web Analytics

  ## Data Cleaning and Transformation
  In preparation of the customer analytics dataset, no major cleaning was required, as it was a cleaned dataset generated from Chatgpt but transformations were applied to ensure consistency and usability, including:
- Calculated Recency, frequency and monetary value: using DAX to calculate each one of them;Recency shows how recently a customer has made a purchase, frequency shows how often a customer makes purchase while Monetary value tells how much a customer spends.
- calculated Customer Lifetime Value: Used DAX to create CLV metric and further segmenting it per customer to predict their total revenue or profit expected

## Key Findings 


<img  width="926" height="407" alt="Customers Analytic" src="https://github.com/Israel1hub/Customers-Analytic/blob/main/customer%20analytics%201.png"/>



This customer analytics report reveals several critical insights:
- 1,000 customers, which 472 are **active** and 528 are **churned**
- Total revenue generated is $3,831,931 and the customer lifetime value (CLV) is calculated at 4,498 over two years.
- Female customers (50.30%) slightly outnumber male customers (49.70%).
- The top 3 revenue-generating countries are:
   Netherlands
   Finland
   Congo
- RFM segmentation categorized customers into the following groups:
Hibernating(232)
Potential loyalists(130)
Promising customers(121)
General customers(105)
Loyal customers(83)
Needs attention(81)
Champions(79)
customers at risk(64)
Big spender(51)
New customers(48)
- 2023 saw the highest revenue and the highest number of customer sign-ups.
- 25.27% of prospects clicked on the campaign,making paid campaigns the top channel for customer acquisition.
- Customers with IDs; 955, 727 and 552 are VIP customers who have strong customer satisfaction and loyalty.They are also among the most frequent purchasers.
- PayPal and bank transfer are the most used payment methods..
  
  ## Marketing Strategies
Based on the insights above, the following Marketing Strategies are recommended:

 - VIP customers should be offered premium services and dedicated support,as this strategy shifts the competitive focus from price to value, expertise, and a personalized customer experience
 - RFM segmentation;
   HIBERNATING: Offer small, targeted promotions to re-engage them without significant expenditure.
   CHAMPION: Provide exclusive offers and early access to new products.
   LOYAL: Offer loyalty program, cross-sell complementary products and encourage higher spending through bundle deals
   POTENTIAL LOYALISTS: Send follow-up offers, welcome series emails, and value propositions
   PROMISING:focus on building loyalty and encouraging repeat purchase
   At Risk:Offer them a discount on best-sellers or previous purchases and Win back campaigns with strong incentives
   NEED ATTENTION:Win them back with re-engagement campaigns or special deals.

   ## Conclusion
The analysis identified customer segments ranging from champions (recent, frequent, high spenders) to at-risk customers (frequent, high spenders who haven’t purchased recently). Specific marketing strategies are proposed to maximize retention, re-engagement, and lifetime value across segments.

  
