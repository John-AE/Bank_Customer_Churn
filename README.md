# Project Title: Bank_Customer_Churn

### Description

This project was undertaken to demonstrate my analytical skills using SQL to explore the churn records of customers in an European bank. The dataset was pulled from the Maven Analytics website. The project involved creating a database (bank_churn) and importing a csv file into a table within the database using MYSQL Workbench, performing exploratory data analysis (EDA), and then answering insightful business questions through SQL queries. 

### Objectives
1.	Explore The Records in the Table
2.	Analyze Customer Behavior

### Environments and Tools Used
- Windows 10
- MySQL Workbench

## Data Science Analysis Walk-Through

### Database and Tables Creation
##### Database: bank_churn

A table named Bank_Churn is created to store the Bank customers churn data. The table structure includes 13 columns for CustomerId, Surname, CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember,  EstimatedSalary and Exited.

![Importing the CSV File into MySQL Workbench](pjc_02_01.JPG)

In total, 13 questions were raised and a few of the most insightful have been highlighted below. The following SQL queries were developed to answer specific business questions:h category?
- How many dishes are in each category?


![Exploring the menu items table](pjc_02_02.JPG)

### Exploring the Orders Table
During the exploration, some questions were answered such as:

- What is the date range of the table?
- How many orders were made within this date range?
- How many items were ordered within this date range?
- Which orders had the most number of items?
- How many orders had more than 12 items?


![Exploring the orders table](pjc_02_03.JPG)

### Analyzing Customer Behavior
During the exploration, some questions were answered such as:
- What were the least and most ordered items? What categories were they in?
- What were the top 5 orders that spent the most money?
- Determining the details of the top 5 highest spend and gathering insights can you gather from the results?

![Analyzing the behavior of customers](pjc_02_04.JPG)
