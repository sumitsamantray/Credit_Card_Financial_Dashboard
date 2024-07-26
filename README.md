# Credit_Card_Financial_Dashboard 
Power BI Dashboard [Link](https://app.powerbi.com/view?r=eyJrIjoiZTRiNTBlNzktNjVhZC00ODZiLTliM2ItODcxZDg0ZjY5ZDQwIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
This repository contains Power BI reports analyzing credit card transactions and customer data. The project involves importing data from Excel into PostgreSQL and creating Power BI dashboards to visualize key performance indicators (KPIs) and insights.

# Tetch Stacks

1. MS Excel 
2. Postgres SQL
3. Power Bi 
4. DAX Language

# Data Source
The data used in this project consists of two tables in PostgreSQL:

# cc_detail Table

Client_Num: Client number
Card_Category: Category of the credit card
Annual_Fees: Annual fees associated with the credit card
Activation_30_Days: Number of activations within 30 days
Customer_Acq_Cost: Acquisition cost for the customer
Week_Start_Date: Start date of the week
Week_Num: Week number
Qtr: Quarter
current_year: Current year
Credit_Limit: Credit limit
Total_Revolving_Bal: Total revolving balance
Total_Trans_Amt: Total transaction amount
Total_Trans_Ct: Total transaction count
Avg_Utilization_Ratio: Average utilization ratio
Use_Chip: Whether the card uses chip technology
Exp_Type: Expenditure type
Interest_Earned: Interest earned
Delinquent_Acc: Delinquent account status

# cust_detail Table

Client_Num: Client number
Customer_Age: Age of the customer
Gender: The gender of the customer
Dependent_Count: Number of dependents
Education_Level: The education level of the customer
Marital_Status: Marital status of the customer
State_cd: State code
Zipcode: Zip code
Car_Owner: Whether the customer owns a car
House_Owner: Whether the customer owns a house
Personal_Loan: Whether the customer has a personal loan
Contact: Contact information
Customer_Job: The job of the customer
Income: Income of the customer
Cust_Satisfaction_Score: Customer satisfaction score

# Importing data From Postgres SQL to Power Bi 
As the database is Postgres SQL in this project, we need to import the datasets from the Postgres SQL database to PowerBi by providing the Database access credential.

# Data Model
![image](https://github.com/user-attachments/assets/7ba7aa7c-4496-4fb0-be79-dfb06c5c23d5)

# Home View 
![image](https://github.com/user-attachments/assets/f8518040-4a97-4087-98b7-c62e3a7b5e40)
1. Info 
2. Credit Card Transaction Report
3. Credit card Customer Report

# Credit Card Transaction Report
![image](https://github.com/user-attachments/assets/79159d23-bd8d-4923-9082-609f564fc87e)

# Credit card Customer Report

![image](https://github.com/user-attachments/assets/95651553-3714-405f-bc0b-8aec8828554c)

# Power BI Dashboards
The Power BI reports consist of two main dashboards:

# Credit Card Transaction Analysis

This dashboard provides insights into credit card transactions, including:
Total revenue
Total interest
Quarterly revenue and total transaction count graph
Week-on-week growth measure is created

# Credit Card Customer Report

This dashboard focuses on customer demographics, with data filtered by gender. It includes visualizations such as:
Distribution of customers by age and gender
Customer satisfaction score analysis
Income distribution by gender
Usage


# To use the Power BI reports, follow these steps:
Write the SQL queries to load the data into PostgreSQL
Import the data from PostgreSQL into Power BI.
Ensure the necessary measures and filters are set up for the dashboards.
Explore the visualizations to gain insights into credit card transactions and customer demographics.



