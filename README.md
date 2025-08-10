# PWC Customer Retention Power BI Dashboard
## Dataset Used
- <a href="https://github.com/kalim-git/PWC-Switzerland-Customer-Retention-Power-BI-Virtual-Internship-/blob/main/Churn-Dataset.xlsx">Customer Retention Dataset</a>
## Background Information of the Task
The telecom Retention Manager has scheduled a meeting with the engagement partner at PwC to cover these points:
• Customers in the telecom industry are hard-earned: we don’t want to lose them.
• The retention department is here to get customers back in case of termination.
• Currently, we get in touch after they have terminated the contract, but this is reactionary: it would be better to know in advance who is at risk.
• We have done customer analysis with Excel: it has always ended in a dead-end.
• We would like to know more about our customers: visualised clearly so that it’s self-explanatory for our management.
Your colleague, the engagement partner, asks you to do the following tasks:
1.	Define proper KPIs
2.	Create a dashboard for the retention manager reflecting the KPIs
3.	Write a short email to him (the engagement partner) explaining your findings, and include suggestions as to what needs to be changed

Here are some inputs:
 • Customers who left within the last month
 • Services each customer has signed up for: phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
 • Customer account information: how long as a customer, contract, payment method, paperless billing, monthly charges, total charges and number of tickets opened in the categories administrative and technical
 • Demographic info about customers – gender, age range, and if they have partners and dependents

## Object
The object of this analysis is to create a dashboard in PowerBI for Call Center Manager about Customer Retention that reflects all relevant Key Performance Indicators (KPIs) and metrics in the dataset.
## Possible KPIs include (but not limited to):

## Table Details
The tabulation below shows the Call center table with its column names and their description:

The tabulation below shows the Customer retention table with its column names and their description:
Column Name	Description
customerID	Represents the unique number of the customer in the dataset
gender	Describes the gender of the customer
SeniorCitizen	Describes if the customer is a senior citizen
Partner	Describes if the customer has a partner
Dependents	Describes if the customer has a dependent
tenure	Describes how long as a customer
PhoneService	Describes if the customer has registered a phone service
MultipleLines	Describes if the customer has registered multiple lines
InternetService	Describes if the customer has registered for internet service
OnlineSecurity	Describes if the customer has registered for online security
OnlineBackup	Describes if the customer has registered for online backup
DeviceProtection	Describes if the customer has registered for device protection
TechSupport	Describes if the customer has registered for tech support
StreamingTV	Describes if the customer has registered to stream tv
StreamingMovies	Describes if the customer has registered to stream movies
Contract	Describes if the length of the contract of the customer
PaperlessBilling	Describes if the customer has registered for paperless billing
PaymentMethod	Describes the payment method of the customer
MonthlyCharges	Represents the monthly charge incurred by the customer
TotalCharges	Represents the total charge incurred by the customer
numAdminTickets	Represents the number of admin tickets opened by the customer
numTechTickets	Represents the number of tech tickets opened by the customer
Churn	Describes if the customer is at risk of churn


## Data Transformation
The Customer churn dataset has 23 columns and 7043 rows of observation
Data transformation and cleaning were done in Power Query and the dataset was loaded into Microsoft Power BI Desktop for modelling.

## Data Visualization
Data visualization for the dataset was done in Microsoft Power BI Desktop.



## Dashboard
**Customer Retention Dashboard**


## Data Analysis
**Measures(DAX) used**


## Insights
As shown by Data Visualization, It can be deduced that:



## Conclusion

