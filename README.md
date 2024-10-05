# Supermarket Sales
### Summary:
The dataset represents 1,000 transactions across three supermarket branches, and analyzes key metrics such as sales, customer demographics, product categories and payment methods. 

### Approach:
The project approach is to understand the data provided after cleaning it, and to answer some questions using some cards and charts for explaining more information about this data to provide a comprehensive view of supermarket performance across multiple dimensions from which we can make appropriate recommendations for the future.

### The Goal to Complete the project:
##### 1 - Gather Data
##### 2 - Assessing Data
##### 3 - Clean Data
##### 4 - Vizualize Data
##### 5 - Answers the questions

## Data Gathering:
##### Read Capstone Data - Supermarket Sales.csv File

## Assessment Part:

### Quality Issues:
##### •	The "Tax" column has 9 missing values (can be calculated).
##### •	The "Total" column has 3 missing values (can be calculated).
##### •	There are 6 duplicated rows.
##### •	The "Customer Type" field contains "-" instead of NaN.
##### •	The "Customer Type" field has missing values.
##### •	The "Customer Type" field contains the values ['Member', 'Memberr'], which have the same meaning.
##### •	The "Unit Price" column contains the value "USD" causing the data type of the column to be object instead of float.
##### •	The "Quality" column contains negative values.
##### •	The "Time" column contains the value "8 – 30 pm" instead of "20:30"
##### •	The "Rating" column contains a value of "97.0" instead of "9.7"

### Tidiness Issues:
##### •	The cities "Yangon," "Naypyidaw," and "Mandalay" are each represented in separate columns, but they should be combined into a single column called "City," with each row containing one of the three city names.


## Wrangling Part:

#### Quality issues and tidiness issues have been solved in the Data Wrangling.ipynb file


## Visualizaion and Business Questions Part

### Key insights : 
##### •	Total Sales with tax
##### •	Total Sales without tax
##### •	Total Quantity
##### •	Average Rating

## Business Questions

#### Q. NO. 1: What is the top-selling product line?
#### Q. NO. 2: What is the top-selling branch?
#### Q. NO. 3: What is the perc. of customer loyalty based on type?
#### Q. NO. 4: What is the top-selling time of day?
#### Q. NO. 5: What is the top-selling Day of week?
#### Q. NO. 6: What is the relation between Product line and Branch based on Quantity?
#### Q. NO. 7: What is the top-selling month?

#### Insights and Answer for these quesions in the Capstone Project Sales.pbix and Final_Report.pdf
