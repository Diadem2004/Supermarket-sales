# Supermarket-sales

This dataset contains transaction details of a supermarket in a city with three different locations sellings different sport items.
Including various attributes such as invoice ID, branch, city, customer type, gender, product line, unit price, quantity, tax, total amount, date, time, payment method, cost of goods sold (COGS), gross margin percentage, gross income, and customer rating. The dataset consists of 1000 rows and 17 columns 


**Data Dictionary**

|       Column Name       | Data Type | Description |
| :---------------------- | :--------------: | :---------- |
| Invoice ID              | object  | Computer generated sales slip invoice identification number |
| Branch                  | object       | Branch of supercenter (3 branches are available identified by A, B and C)           |
| City                    | object       | The City the supermarket is located in         |
| Customer type           | object      | If customer used member card, type is "Members", otherwise "Normal"         |
| Gender                  | object       | Gender of customer           |
| Product line            | object       | General item categories - Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel           |
| Unit price              | float64 | Price of each product in $           |
| Quantity                | int64       | Number of products purchased by customer          |
| Tax                     | float64      | 5% tax fee for customer buying          |
| Total                   | float64       | Total price including tax           |
| Date                   | DateTime       | Date of purchase (Record available from January 2019 to March 2019)           |
| Time                    | object       | Purchase time (10am to 9pm)           |
| Payment                 | object       | Payment used by customer for purchase (3 methods are available – Cash, POS, and eNaira)           |
| cogs              | int       | Cost of goods sold           |
| gross margin percentage | float64       | Gross margin percentage           |
| gross income            | float64       | Gross income          |  
| Rating                  | float64       | Customer stratification rating on their overall shopping experience (On a scale of 1 to 10)           |
