# ProductSaleProject

WE are Analyse the sale data 
Sales do not have visibility into daily/current sales performance reports
Current architecture is not scalable and latest report they receive is a month old. 
Sales management cannot measure/analyze their performance against the goal plan
Sales receives a basic summary report of combines sales(direct and trace sales) in summary. Sales analytics team analyze the summary data and share the reports with sales via email. This process limits the sales to run any analytics in excel files. Sales like to have an ability to see how they are performing against goal plan and analyze deeper with their current sales data

Approch:

Create db tables in MYSQL for data:

Data mungin in python
Create app.py provide flask routes for reporting
Create dashboard with graphs and data for reports


Distributer Table
CUSTOMER NUMBER     Primary key
SHIP TO CUSTOMER NAME    
SHIP TO ADDRESS    SHIP CITY    
SHIP STATE    
SHIP ZIP    PHONE_NUMBER    
FORMAN CODE  

Distributor Product Table
CUSTOMER NUMBER Primary key
Product_id
FORMAN CODE  Foreign key

Product Master table
PRODUCT CODE Primary key
Product description
Product Category - Rajat to add data
Unit Price - Rajat to provide data

Sales  Table
PRODUCT CODE Primary key
PURCHASE_DATE    
INVOICE_NUMBER    
SOLD_UNITS
TOTAL_AMOUNT


————————
Reports
1. Category wise Sales report  - Neha
   1. Sales  Table - Product Table
       1. Daily
       2. Weekly
       3. Monthly
       4. Quarterly
2. Total Sales  - Priti
   1. By zip code
   2. By state
   3. By distributor
   4. By Product
   5. By State by zip code
3. Distributor wise sales - Rajat
   1. By state
   2. By product
   3. By revenue
4. Report : -  Jimmy
   1. Q : what is the best selling product  ? Top selling item products
   2. Q : what is the least selling product ? Bottom 5 selling products
   3. Q : what is the best selling region  ?Top selling items by state/zip code
   4. Q : what is the least selling region  ? Botton 5 selling by state/zip code

—————————————————————————
Visualizations :
1. Map that displays the distribution of distributors
2. Ring chart : Top product in sales
3. Line chart for Category wise Sales report  
4. Bar chart for Category by Sale
5. Meter chart : Total  sales by Quarter
6. Sales opportunity data : display product with sales falling between 60 -80 %




