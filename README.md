### Project Overview
---
This project acquires and analyses sales and profit data across different countries and region for the conpany, The goal is to provide in sights into brands,unit price,quantity,cost and profit over different years and months in the region
  This data analysis using SQL highlight on important details about the sales trend in the organization such as total profit for Nigeria in 2019

### Data Collected
---
The data set includes the following key columns
1. Sales ID: This refers to a unique identifier assigned to a sales transaction,order or customer
2. Sales Rep: This is an individual responsible for promoting ans selling products or service to customers
3. Emails: This includes the emalils of the sales rep
4. Brands: This refers to the unique identities or images that represent products
5. Plant cost: It refers to the expenses associated with acquiring,maintaing and operating a manufacturing plant or facility
6. Unit price: It refers to the cost or price of a single unit of the product
7. Quantity: It refers to the amount or number of unit of the products
8. Cost: The amount of money to acquire the products
9. Profit: It is the financial gain after substracting total cost from total revenue
10. Countries: It refers to the distinct geographical territory
11. Region: It refers tp geographical areas within a country or globally,defined by various criteria

  ### Project Objectives
  ---
    This project was designed to address the following
   - To get the total profit
  - To get total profit for Senegal
  - To get total profit for Nigeria in 2019
  - To get total profit for brands in a Nigeria  in 2017
  - To get total profit for brands in Nigeria
  - To get total profit for brand (HERO)
    
    ### Query Codes Used
    ---
    ~~~SQL
    - SELECT SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES
    SELECT SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES WHERE COUNTRIES = 'SENEGAL'
    SELECT SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES WHERE COUNTRIES = 'NIGERIA' AND YEARS = 2019
    SELECT BRANDS SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES WHERE COUNTRIES = 'NIGERIA' AND YEARS '2017' GROUP BY BRANDS  ORDER BY 2 DESC
    SELECT BRANDS SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES WHERE COUNTRIES = 'NIGERIA' GROUP BY BRANDS ORDER BY 2 DESC
    SELECT SUM (PROFIT) AS TOTAL PROFIT FROM INTERNATIONAL BREWERIES WHERE COUNTRIES = 'NIGERIA' AND YEARS = '2017' AND BRANDS = 'HERO'

    
![Screenshot (22)](https://github.com/user-attachments/assets/95bbb263-86f0-4f7e-8a1a-73c849ab9bad)

![Screenshot (23)](https://github.com/user-attachments/assets/bc79afb3-4df1-4e03-a046-e665882de551)
![Screenshot (24)](https://github.com/user-attachments/assets/88323317-4279-4761-accc-d0c164856633)

