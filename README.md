# Project Title: Bank_Customer_Churn

### Description

This project was undertaken to demonstrate my analytical skills using SQL to explore the churn records of customers in an European bank. The dataset was pulled from the Maven Analytics website. The project involved creating a database (bank_churn) and importing a csv file into a table within the database using MYSQL Workbench, performing exploratory data analysis (EDA), and then answering insightful business questions through SQL queries. 

### Objectives
1.	Explore The Records in the Table
2.	Analyze Customer Behavior

### Environments and Tools Used
- Windows 10
- MySQL Workbench

## Data Analysis Walk-Through

### Database and Tables Creation
##### Database: bank_churn

A table named Bank_Churn is created to store the Bank customers churn data. The table structure includes 13 columns for CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember,  EstimatedSalary and Exited.

![Importing the CSV File into MySQL Workbench](pic_01.JPG)

#### Table Creation Completed
![Bank Churn Table Completed](pic_02.JPG)

In total, 13 questions were raised and a few of the most insightful have been highlighted below. 

#### Objective 1: Exploring the Data
The following SQL queries were developed to explore the data and have a general understanding:
1. Inspect the data, count the records grouped by Gender
2. View and count the countries represented in the data
3. Determine the number of customers that have churned/left and those still customers
4. Determine the number of retained customers with a credit card and those without
5. Determine the average tenure of retained customers that don't have a credit card

#### Objective 2: Analyzing Customer Behavior
The following SQL queries were developed to undertand and give insight into the bank customers' behavior:

1. In category of increasing tenure with the bank, count the number of retained customers that don't have a credit card
2. What is the range of Credit Scores. Also, what is the average credit score of customers who churned, and how does it compare across different geographies?
3. Which gender has a higher churn rate, and does age play a significant role in this?
4. Is there a correlation between the number of products a customer has and the likelihood of churning?
5. How does the balance of churned customers compare to those who did not churn?
6. What is the tenure distribution of customers who churned, and how does it differ from those who stayed?

### Screenshots
##### In category of increasing tenure with the bank, count the number of retained customers that don't have a credit card
![Tenure and Credit Card Possession](pic_03.JPG)

#### Is there a correlation between the number of products a customer has and the likelihood of churning?
![Churning Likelihood vs Number of Products](pic_04.JPG)

#### What is the tenure distribution of customers who churned, and how does it differ from those who stayed?
![Tenure Distribution](pic_05.JPG)

### Findings
- Customer Demographics: The dataset includes customers from a wide age range from 18 – 92 years with the majority being male. The records comprised 5457 males and 4543 females.
- High-Value Customers Loss: A little over 20% of customers churned. The average account balance of customers that had churned was 91,108.54 while that of those retained was 72, 745. The maximum balance of churned customers was 250,898 while that of retained customers was 221,532.8.
- Customer Insights: 
A correlation between the number of products a customer has and the likelihood of churning. The more products a customer had, the lower the likelihood of churning. Of the 2037 customers that churned, with increasing number of products, few customers churned. 
Further analysis and data visualization is to be carried out for better insight into tenure distribution of customers that churned and those that stayed 


### Conclusion
The analysis serves as a first-level dive into the bank customer churn data using SQL. Focus was on demonstrating use of MySQL Workbench, performing exploratory data analysis, and writing business-driven SQL queries. The findings from this project which is that the bank could improve customer retention by promoting the adoption of more products by existing customers in order to stem high-deposit outflows. They could provide more services and offering curated for higher net-worth individuals in order to stem such high-deposit outflows. The findings can help drive business decisions but further research is still required to give better in-depth analysis.
