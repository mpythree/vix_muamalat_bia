# vix_muamalat_bia
This project is part of a Project-Based Internship: Bank Muamalat x Rakamin Academy assignments in order to complete the final task about creating a Dashboard as a Business Intelligence Analyst.

The tools we used in this project are:
- [Google BigQuery](https://console.cloud.google.com/)
<img src="https://github.com/mpythree/vix_muamalat_bia/assets/86466306/e88ea4f4-81b8-4eb4-9f62-401791f692eb" alt="Girl in a jacket" width="200" height="100">

- [Google Looker Studio](https://lookerstudio.google.com/)
<img src="https://www.marceldigital.com/media/0yncqj5k/looker-studio-logo-2.png?rmode=max&width=400&height=358" alt="Girl in a jacket" width="175" height="150">


The tasks of this project consist of:
1. Choosing the primary key of each table (Customer, Products, Orders, ProductCategory).
2. Determine the relationship between those tables.
3. Creating a master table using those datasets.
4. Create a dashboard visualization using the master table.
5. Add some suggestions to increase sales or transactions.

## Creating Master Table

The __Master Table__ was created by Google BigQuery using this [query](https://github.com/mpythree/vix_muamalat_bia/blob/main/Master_Table_Query.txt) that consisting of:
- CustomerEmail (cust_email)
- CustomerCity (cust_city)
- OrderDate (order_date)
- OrderQty (order_qty)
- ProductName (product_name)
- ProductPrice (product_price)
- ProductCategoryName (category_name)
- TotalSales (total_sales)

## Creating Dashboard

The dashboard was created by Google Looker Studio using the __Master Table__

Check the dashboard [here](https://lookerstudio.google.com/reporting/5c844b3e-0726-41b3-bbb3-316bf256c4a3)

## Creating Report

For the full report check [here](https://github.com/mpythree/vix_muamalat_bia/blob/main/FinalTask_BankMuamalat_BI_Moh.%20Harwin%20Prayoga.pdf)
