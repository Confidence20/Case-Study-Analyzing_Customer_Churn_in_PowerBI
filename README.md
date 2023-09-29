# Case-Study-Analyzing_Customer_Churn_in_PowerBI
In this Project, I investigated a dataset from a telecom company called "Databel" and my task is to analyze the churn rate. Churn rate simply means the rate at which customers leave a company. That is, they no longer do business with the company.

# Data analysis flow in PowerBI
There are five different steps in the data analysis flow
* Data Check
* Explore Data
* Analyze and visualize data.
* Dashboarding
* Commuicating insights.

These steps were exercised in this project.

## Data Check/Validation
First, i checked the data on customers. In this process i checked for missing values of customers Id. from the page below, it is observed that in comparing both the total number of customers and the total number of unique customers(records without duplicates or empty records) are equal. This means the Data is complete.
Next, i calculated the ratio of churned cutomers and the data shows Databel had 26% of customers who are churned.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/70e8c99e-3dad-4bdf-9105-12b8ccc3a51d)

##
#### Investigating Churn reasons
Next, i investigated the reason why customers churned. I created visuals to properly presented the information needed.
This visual was created using the **"customer reason"** column and **"Number of Customers"** column.
From the chart, of the list of reasons customers churned, "competitors made better offers" was the most reason. This means that on the records, This means that Databel had competitors who could attract its customers with offers that seemed better that Databel's.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/4bee52ea-c46b-4b6c-a02a-ecd63a32392a)

## Explore Data
#### Deeper investigation on churn categories
The **"churn reason"** column was grouped in the **"churn category"** column.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/d1d83ac1-242c-45fd-89b1-d740e7e98f4a)

#### Using Maps
I visualized the the churn rate across different states in the the Unied State. It turns out, Databel had the most churned rate in **"California"** was abnormally high at **68%**. This investigation helps trace where the Databel is losing customers.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/ae0a019d-cfee-4b31-992d-774d6ac6bed5)

##
## Analyzing Demographics
This visual reveals the Age Group that has churned the most having a 36% churn Rate.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/ddc9aa61-b776-49fa-9610-524481f9eb03)

##
#### Inspecting Groups
An analogy here was that Databel offers group contract to customers in the same household. The advanteage for the customer is a discount rate in purchases, which is a good way to grow your customer base.
i went further to check if customers in a group have a lower phone bill, and if this affected the churn rate.
From the visual below, the data shows that group category 6 has the lowest churn rate of **6.71%**.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/25a5cd4f-e6c7-47d1-80af-306d90a756b0)

##
### International Calls
The analysis requirement given by **Databel** included a request to analyze the international activity of customers and its realtionship to churn. they were curious about the behaviour of customers who called internationally and if paying for international plan influenced their loyality.
Databel wants to focus on the budget on a state-by-state basis for the promotion of the international plan. From this page, the state with the highest churn rate for customers who have "month-to-month" contract types.
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/0e9a7f81-3056-437d-86aa-a293c9b83583)

#

## Overview
It is very important to see the reasons why customers churn, and their respective percentage of total customers. 
![image](https://github.com/Confidence20/Case-Study-Analyzing_Customer_Churn_in_PowerBI/assets/55492261/a601d42f-150f-4b46-87b8-fa0035df8726)
#

## Age brackets & Groups
I created a second page in the report that portrays insights about the age buckets and groups. I used the visual below to answer the question of **What is the churn rate of customers who are not in a good plan, that belong to age group 50 and have account <= 12 months**
                    ***The answer is 50.67%***

#
## International plan
The Final report covered the insights about the data and any relevant charges.
