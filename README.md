# LITA_Capstone_SalesData_Project

### Project Title: LITA_Capstone_SalesData_Project
------------------

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleansing and Preparations](#data-cleansing-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Key Insights](#key-insights)

[Acknowledgement](#acknowledgement)

### Project Overview
-------------------
This project is an integration of Excel, SQL and Power BI for analysing sales and visualizing the findings per product, & across the regions. It aims to generate insight into the sales performance of the LITA CAPSTONE Project over a period of time. 

By analysing the various parameters in the data gotten from open source (Excel); to gather enough insightto make reasonable decisions which enables to tell compelling stories around the data from the insight gotten and to know the best performance from the data.

### Data Sources
----------------
The dataset for this project was of LITA Capstone - SALESDATA.csv. This included 7 variables:
 - OrderId
 - Customer Id
 - Product
 - Region
 - Quantity
 - UnitPrice

### Tools Used
--------------

- Microsoft Excel [Download Here](http://www.microsoft.com)
  1. For Data Cleaning
  2. For Analysis
  3. For Data Visualization

 - SQL - Structured Query Language
  - For Querying of Data

- Power BI
  - For Data Entry/Get Data from Open Sources
  - For Data Transformation
  - For Data Visualization
 
- GitHub
  - For Portfolio Building

### Data Cleansing and Preparations
-----------------------------------
- In the initial phase of the Data Cleaning and preparations, we perform the following actions:
  1. Data loading and inspection
  2. Handling missing variables
  3. Data cleaning and formatting

### Exploratory Data Analysis
-----------------------------
- EDA involved the exploring of the Data to answer some questions about the Data such as:
  1. Which product is the top performing across the regions?
  2. Wchich region contributed most to the sales?
  3. What is the percentage of total sales contributed by each region?
  4. What is the total revenue  by each region/product?
  5. What is the average sales per product?

### Key Insights
----------------
Some of the Sales Overview include:
- The Top performing product is Shoes Category
- The South Region contributed the highest percentage of total sales
- The month of February has the highest sales

### Data Analysis
-----------------
- This is where we included some basic lines of code or queries or even some of the DAX expressions used during the analysis.
  
  - Example 1:
    ~~~MS-EXCEL
    =SUMIF(C2:C50001,C2:C7,H2:H50001)
    ~~~

 - Example 2:
   ~~~POWER BI
   TopSalesProd = CONCATENATEX(TOPN(1, 'SalesData', [Sales]), [Product], )
   ~~~

- Example 3:
   ~~~SQL
   SELECT COLUMN1, 
   SUM(COLUMN2 AS [ALAS], (SUM(COLUMN2)/(SELECT SUM(COLUMN2) FROM TABLE1) *100)
   AS Percentage
   from TABLE1
   GROUP BY COLUMN1
   ORDER BY SUM(COLUMN2) DESC
   ~~~

### Links
---------
https://wesabimarket-my.sharepoint.com/:x:/r/personal/yetunde_wesabimarket_com_ng/Documents/Desktop/LITA/LITA%20PROJECTS/LITA%20Capstone%20Dataset%20SalesData.xlsx?d=we6cbf079ac2b4e54bbce280237ce54cc&csf=1&web=1&e=5flsVv


### Data Visualization
-----------------------

![SALES OVERVIEW](https://github.com/user-attachments/assets/bcf22b50-3531-4546-8da1-f393346818c9)

![REGIONAL BREAKDOWNS1](https://github.com/user-attachments/assets/104e401e-0fba-4aed-bd94-d62b96bbd9d7)

![REGIONAL BREAKDOWNS2](https://github.com/user-attachments/assets/6fe85c04-ba46-4b9e-a004-7b5d1b1cfe23)

![REGIONAL BREAKDOWNS3](https://github.com/user-attachments/assets/1bc5f581-47f9-46dc-bc97-988428b2444b)



|Heading 1|Heading 2|Heading 3|
|---------|---------|---------|
|Table 1|Table 2|Table 3|



### Acknowledgement
-------------------
I appreciate the Almighty God for the privilege to be part of this journey. My thanks also goes to The Incubator Hub, our Well-equipped Facilitators: Muhsin H. (Excel Facilitator); Femi Ayodele (SQL Facilitator); & Temidayo TeeDee Ayeni (Portfolio building - GItHub/Power BI Facilitator) for the great job done.

