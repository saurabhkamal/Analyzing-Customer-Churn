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





