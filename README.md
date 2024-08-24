# Analyzing-Customer-Churn

-	Churn allow companies to measure competitiveness.
-	It tells you exactly why customers are leaving.
-	It is the rate at which customers stop doing business with an entity.
-	It is a leaky bucket problem.
-	Reducing churn is a priority for many companies

## Problem: Discovering Why Customers are Churning?

**1.	Data Preparation:**
The first step is to ensure that the data is prepared, before doing any analysis. Verifying the data with simple check i.e. putting data in a table formats and then investigating whether are any duplicate rows in our customer level data or doing any other cleaning such as handling missing data, or conditional formatting.

**2.	Calculating Churn**
It is useful to have a measure that calculates churn before deep-diving into the analysis.
There is a column called Churn Label that indicates “Yes” or “No”

So, this column is converted to a binomial column indicating if the customer churned or not. It will be used to calculate the churn rate.

“Yes” then 1
“No” then 0

**What is the total churn rate?**
26.86%

**3.	Investigating Churn Reasons:**

Investigating the different reasons why customers churned. Creating a column chart listing the different reasons why customers churn. 

**Top churn reasons**

![image](https://github.com/user-attachments/assets/3ab408d5-3ca5-490a-900a-aa88796bc13b)

**4.	Digging deeper into churn categories:**

Identifying which churn category is accounting for the highest proportion of churn and understanding which priority we should tackle first based on the churn reasons. 

![image](https://github.com/user-attachments/assets/737c88a3-874c-460d-a1d3-13294597ead6)

Competitors are coming in and taking customers with lucrative new telecom deals as indicated in the Doughnut chart. This is something to investigate internally with the sales team. 

**5.	Analyzing Demographics: Analyzing different demographics with its churn rate.**

![image](https://github.com/user-attachments/assets/b4e06c2e-c62f-4b07-a797-5da674cb7b03)

Customers that are considered senior are the most likely segment to churn at most 40%, an interesting insight and can be used for future projects to tackle reducing churn amongst this age group.

**6.	Age Groups:**
A good idea to analyze the customer age in general. Creating different age bins and making a combo chart to visualize the number of customers per bracket and their respective churn rates.

Customers aged between 79-88 only make up a small percentage of our customer base but have the highest churn rate. This might be expected as customers in this range may pass away, but there might be other factors that are causing customers to churn.

![image](https://github.com/user-attachments/assets/dbde2874-1c45-44fa-8e20-4f7c615b4991)

**7.	Unlimited Plan:**

The hypothesis is that people who are not on an unlimited data plan are more likely to churn. Investigating how the unlimited data plan influences churn rate.

![image](https://github.com/user-attachments/assets/85520789-2a3e-4e8d-92bb-795bf9f06aad)

-	Customers who consume the lowest amount of data are actually the most likely to churn at almost 35%
-	Customers who consume between 5 and 10 GB are second most likely to churn around 34%, followed by consumers who consume between 10 or more GB.

**8.	International Calls:**

Analyzing relationship between customers’ international activity and churn. Company is curious about behaviour of customers who call internationally, and if paying for an international plan influences their loyalty. 

It seems that state CA customers has particularly high percentage of churners. This is an important information that can help company to make a good decision while allocating their budget for the new promotion. 

![image](https://github.com/user-attachments/assets/f13de82e-784e-44c8-8dcd-3aecd1f2652b)

**9.	How to retain senior citizens?**

As discovered that the churn rate for customers who are considered senior citizens is almost 40%. So, an important question arises how to retain senior citizens? 
One could argue to roll out personalized plans according to their needs; however, doing so without doing deeper analysis on the churn categories and understanding the reasons for senior citizens’ churn might fail the implementation of personalized plans.

**10.	Two important topics related to customers: the contract type and how many months a person is a customer.** 

Month-to-Month contracts have the biggest churn, but the account length 37-48 group has the biggest gap between one year and two-year contracts.

![image](https://github.com/user-attachments/assets/d032a8a4-4cd4-4522-9421-2b7f473164b6)

Customers between 3 and 4 year mark are much more likely to churn on a One Year contract compared to a Two Year. Sales and marketing can use this information to provide offers that would get customers to sign up to 2 years deals.

## Overview:

![image](https://github.com/user-attachments/assets/4b78b894-333d-4366-a984-41a28a2e4491)
