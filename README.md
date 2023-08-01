# Customer-Analytics
CUSTOMER, PRODUCT AND SALES ANALYTICS USING SQL

# OBJECTIVE OF THE PROJECT:

The project has the primary objective of conducting an in-depth analysis of the sales and
customer data of a scale model car business based on a dataset that contains details of orders
of customers from January of 2003 till May of 2005. This analysis is intended to provide the
company with valuable insights into the overall sales performance, customer behaviour, and
employee structure within the organization.
Through this project, we aim to identify the key drivers of the company's sales performance,
as well as the most successful products and product lines.
Additionally, the project will investigate the employee structure within the company,
including identifying top-performing sales employees.

# ABOUT THE DATASET:
The data for the project will be sourced from several tables within the schema, including:
 - ProductLines: This table provides a list of the different categories or product lines to
which the scale model cars belong.

 - Products: This table contains a list of all the scale model cars available for purchase,
including their names, descriptions, prices and vendor.

 - Offices: This table stores data about the sales offices of the business, including their
locations and contact information.

 - Employees: This table contains information about the employees of the business,
including their names, contact information, and job titles. Here EmployeeNumber is
the primary key. This table contains a foreign key ‘OfficeCode’ which connects the
customer table to the employee table.

 - Customers: This table stores information about the customers of the business,
including their names, addresses, contact information and the employee that handles
that customer. Here CustomerNumber is the primary key. This table contains a foreign
key ‘SalesRepEmployeeNumber’ which connects the customer table to the employee
table.

 - Orders: This table stores sales order data, including the date of the order, the
customer who placed the order, order date and shipping date. Here OrderNumber is
the primary key. This table contains a foreign key ‘CustomerNumber’ which connects
the orders table to the customers table.

 - OrderDetails: This table contains information about the line items included in each
sales order, including the product purchased, the quantity, and the price. This table
contains two foreign keys ‘OrderNumber’ and ‘ProductCode’ which connects the
OrderDetails table to the orders table and products table.

 - Payments: This table stores information about customer payments made against their
account, including the payment date and the amount paid. This table contains a
foreign key ‘CustomerNumber’ which connects the payments table to the customers
table.

# The questions that the project aims to answer include:
 - How many orders were placed by each customer?

 - Categorise customers into three categories: ‘churn’, ‘at risk’ and ‘Loyal or Retained’

 - Which customer has the highest total purchase value?

 - Which customer has never ordered?

 - Which order has the max order value and which customer purchased it and which
employee took the order?

 - Which year was the best for sales?

 - How much in %age, the sales had increased or decreased over the months in 2004?

 - What is the median sales?

 - Who are the top buyer from each state?

 - Number of new customers over the years?

 - Which product line has the highest total sales?

 - What are the top most ordered products by quantity sold and total profit of each?

 - How many products were sold in each quarter?

 - Which products are most popular in each of the country?

 - Who are the top-performing sales employees?

INSIGHTS GAINED FROM THE PROJECT:
The insights that the project aims to gain from the data include:
1) Identifying the most profitable product lines and products
2) Understanding the factors that impact sales performance
3) Identifying the most effective sales employees and strategies
4) Segmenting customers for targeted marketing and sales efforts
5) Identifying opportunities to improve payment and account management processes.

# CONCLUSION:
According to the data analysis done, it can be concluded that:
 - Euro + shopping channel and mini gifts distributors Ltd are the most frequent
customers of this business and they also have the highest order or purchase value.
They are high-value customers and the business can focus their effort on providing
them personalised services and incentives to keep them happy.
 - There are many ‘churn’ and ‘at risk’ customers. The business should take actions to
prevent further churn and retain the at-risk customers. They can conduct exit surveys,
analyse customer feedback and complaints. They can come up with loyal or reward
schemes to retain the at-risk customers.
 - The order with maximum value was made by Dragon Souveniers, Ltd.
 - It is seen from the analysis that sale was highest in 2004 and lowest in 2005. The
reason for low sales in 2005 is that the data we have on sales of the year 2005 is of
first 5 months.
 - In the year 2004, the month of November had the highest sale, and saw the biggest
change from the previous month.
 - The number of new customers decreased over the years, with no new customer until
May 2005.
 - Classic cars are the most popular and profitable product line. As per the popularity of
the product lines the business can evaluate the effectiveness of their marketing
strategies for each of them. 1992 Ferrari 360 spider red is the most ordered product,
this information can help the business allocate resources and invest in products that
are performing well.
 - Quarter 4 of the years 2003 and 2004 had high sales.
 - Gerard is the top performing sales representative. The business should provide
incentives or bonuses to top-performing sales representatives, this motivates other
sales reps to work harder.
