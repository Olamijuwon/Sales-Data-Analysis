# Sales-Data-Analysis


- [Project Overview](#project-overview)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Result/Findings](#result/findings)
- [Conclusion/recommendation](#conclusion/recommendation)

## Project Overview

The dataset is a consist of sales of electronic gadgets like Mac book, iPhone USB cord...
It consists of 11 columns. The unique Key being the Order ID. The columns consist of Products, Price of each Products (in dollars), Order date, Purchase Address, Month, Quantity ordered, Month and sales.
The detail of the dataset is concentrated on United State, namely 9 Cities Atlanta, Austin, Boston, Dallas, Los Angeles, New York, Portland, San Francisco, Seattle.
 ![Sales_Data_Analysis_1](https://github.com/Olamijuwon/Sales-Data-Analysis/assets/107110652/6d414108-5696-4993-89e8-029ef0ad0e7f)
![Sales_Data_Analysis_2](https://github.com/Olamijuwon/Sales-Data-Analysis/assets/107110652/50bfd763-bb14-47ff-8ae0-06520885106c)

## Tools.
Power BI    - Data cleaning was done in power query
            - Data analysis was done too.
            - Creating reports .

## Data Cleaning/Preparation

- The data was imported into PowerBi for cleaning and visualization.
- Data types was changed for some columns, order ID changed from whole no to Text reason being no calculations can be done on this column.
- Price each and sales column was changed from fixed decimal to decimal as it is a currency column and calculation will need to be done.
- Order date column was duplicated, and one was kept as a date and the other was kept as time column. Month column and hour was removed.
- A calendar table, consisting of date, year, month, Quarter and day columns. This was done using DAX.
- The Sales Calendar table was connected in the data model using Date from Sales calendar table and Order date from the 
   Sales table.

## Exploratory Data Analysis

Key Performance Indicators:
 - Metrics made are the Total sales, Total number of orders.
 - Total sales = $34.49 million
 - Total No of Orders = 141,234

- In the Sales by month visual, the trend shows that;
- December has the highest sales of $4.6million, followed by October with $3.7 million,
- April being the 3rd highest at $3.4 million and
- November being the fourth at $3.2 million.

Insights to be generated:
- What is the Price of each Product, in descending order?
- Show the sales by City?
- Show the sales by month?
- Show the total quantity of each product and the sales generated?
- Show sum of sales of Products in descending order?
- Which time of the day is there rush of sales?
- Which day of the week has more sales?

## Result/Findings

- In the Sales by Day Visual;
 Tuesday is seen to bring in the highest sales at $5.09 million, followed by Wednesday ($4.99M), Sunday($4.93M), Saturday 
 ($4.90).
 There is a spike in sales on Tuesdays with almost a million dollars difference while Wednesday, Sunday, Saturday has only a 
 difference of $30,000 to $60,000.
 More promotional sales can be done in days that has lower sales to drive more sale. More hands can be employed in days with 
 more sales or more shifts can be taken.

- Sales by city visual shows that.
 Highest sale was recorded in San Francisco, Los Angeles and Boston.
 Lowest sale was recorded in Austin.
 
- In the Sales by time Visual;
 This visual shows there's more sale around 11am - 12:30pm with sales between $50K-$54 and around 7pm - 8pm with sales between $52-$55k.
 The increase in sales in the evenings might be attributed to the closing hours and free time of people.
 More promotional sales can be done in time of the day that has lower sales to drive more sale.
 More hands can be employed in time of the day with more sales.

## Conclusion/Recommendation

- MacBook Pro is the most expensive gadget ($1,700), followed by ThinkPad laptop ($999), iPhone ($700) and Google Phone  ($600).
  The least expensive are AAA Batteries ($2.99), followed by AA Batteries ($3.84), USB charging Cable ($11.95) and Wired Headphones ($11.99).

- The lowest sales were recorded in January at $1.8 million
  Highest sales recorded in December, October might be due to the festive period, where celebrations are been done and gadgets are changed and gifted.
  More promotional sales can be done in months that has lower sales to drive more sale. More hands can be employed in months with more sales.
  More concentration should be taken on gadgets least expensive but are being purchased, more advertisement can be done for the gadgets.
  We can also see that the MacBook Pro, iPhone, ThinkPad laptop and Google Phone are bringing in the most sales but not the
  most sold Product in fact the least expensive product being AAA Batteries, AA Batteries, USB charging Cable are the ones with the most sold products but brings in less sales.
  This is due to the price differences of the categories of product.
  Also, the most expensive gadgets with least number of gadgets sold can be seen as an outlier compared to the least expensive that has a greater number of gadgets being sold.
