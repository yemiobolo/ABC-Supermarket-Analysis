## ABC-Supermarket-Analysis
Documentation of Sales Retail Dataset analysis with Excel

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/store%20picture.jpg)

## Introduction
This is an analysis of a project for **ABC Supermarket** that I completed recently. The project involves data extraction, cleaning, analysis and visualization to derive actionable insights and answer crucial questions in order to help the store make data driven decisions, using Microsoft Excel. This project has helped to enhance my data analytics skills.

## Business Problem
1.	Which product category, region and Customer Segment is most profitable?
2.	What is the Minimum, Maximum, Median, Mode and Mean (average) days to ship an order from the order date to ship date?
3.	Plot the chart of revenue based on the day of the week. Which weekday do we perform well the most? 
4.	Which Ship mode cost the most and by how much? What is the average shipping cost across all sales transactions?
5.	Which age group of customers are driving profitable, what is the commercial value (Revenue and Profit worth) of each age group?
6.	The business is looking to understand the drivers of returned orders. Which Product Category, Product Sub-Category, Product, Region, Manager is this predominant to?

## Skills/Concept Demonstrated
Data Extraction 
Data exploration and transformations using various Excel functions and formulas like 
- Date part extraction using the text function, 
- Data parsing using the text to column function, 
- The Vlookup formula,
- If conditional statement and 
- IFERROR for error trapping among others.

## Data Extraction
The dataset folder is made up of 3 files:
- Regional Managers.
- Returned items.
- Sales transaction.

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/extraction.PNG)

## Data Exploration and Transformation
I performed some basic and advanced transformations on the dataset using Excel functions and formulas. Some of these are;

1.	Data parsing to break down data into multiple data points and the substite function.

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/substitute%20function.PNG)

2.	Date part extraction to extract/dissect the date into multiple data components using the *Text function* 

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/Date%20part%20extraction.PNG)

3.  The Concatenate function to combine the text from different cells in one cell.

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/Concatenate.PNG)

4.	The Vlookup to look for a specified value across sheets.

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/vlookup.PNG)

5.	IfError for error trapping.

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/iferror.PNG)

## Analysis
Here, I used the pivot table to calculate, summarize, and analyze  the data that let me see comparisons, patterns, and trends in the data.
![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/Pivot%20table.PNG)

To calculate the minimum, maximum and mean days to ship customers’ orders
Minimum days to ship = MIN(sales[Daystoship])
Maximum days to ship = MAX(sales[Daystoship])
Mean days to ship = AVERAGE(sales[Daystoship]) 

## Visualization using the Pivot Chart
This report comprises 5 pages;

Product category, customer segment and region catalog

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/product%20catalogue.PNG)

Days to ship

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/days%20to%20ship.PNG)

Age group profitability

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/age%20group.PNG)

Drivers of returned orders

![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/drivers%20of%20returned%20product.PNG)

Top 10 Products                                                                                         | Bottom 10 products
:------------------------------------------------------------------------------------------------------:|:-------------------------------------------:
![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/top%2010%20products.PNG)| ![](https://github.com/yemiobolo/ABC-Supermarket-Analysis/blob/main/ABC%20Store/bottom%2010%20products.PNG)






