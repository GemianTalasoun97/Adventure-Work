# Adventure-Work
https://youtu.be/EvP5XQgEj_A

## Project Description
In this project, I'll analyze the Adventure-Work data. The Adventure Works databases are sample databases that were originally published by Microsoft. For this project, I will be connecting and shaping data in Power Query, building a relational model, and adding calculate fields with DAX measures. Finally, created an interactive Dashboard for data visualization of the performance of the company.

## Project Process

### Tables Used
* Sales.SalesOrderHeader
* Sales.SalesOrderDetail
* Sales.vSalesPerson (view)
* Sales.SalesTerritory
* Purchasing.ShipMethod
* Production.Product
* Production.ProductSubcategory
* Production.ProductCategory

### Cleaning
* Rename Tables, columns.
* Remove unused columns .
* one table (Merge M Language): -
	1. Production.Product
	2. Production.ProductSubcategory
	3. Production.ProductCategory

### Modeling
* Number of Orders Measure 
* Total SubTotal Measure 
* Total Tax Measure 
* Total Freight Measure 
* Total Due Measure 

### visualizing
* Number of Orders Card
* Total SubTotal Card
* Total Tax Card
* Total Freight Card
* Total Due Card
* Number of Orders by OrderDate vs. ShipDate vs. DueDate
* Number of Orders by Status
* Number of Orders by Shipmethod
* Number of Orders by Category, subCategory, Product
* Number of Orders by FlagOnlineOffline
* Number of Ordera vs. TotalDue by Territory
* Top 10 Sales Perosns

