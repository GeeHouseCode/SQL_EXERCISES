#### Step 2 - SQL comparison operators
The most basic way to filter data with WHERE clause is using comparison operators.

Here is the list of Comparison operators you can use to specify in a condition.

|Operator| Description |
| ------------- | ------------- |
| =  | Equal to	  |
| >  | Greater than  |
| <  | 	Less than		 |
| >=  | Greater than or equal to  |
| <=  | Less than or equal to	  |
| <>  | Not equal to	  |

**Example**
```
SELECT * FROM AdventureWorksDW2022.dbo.DimProduct WHERE ProductAlternateKey = 'CR-7833'
```

```
SELECT [ProductKey]
      ,[SalesOrderNumber]
      ,[UnitPrice]
      ,[ProductStandardCost]
      ,[TotalProductCost]
      ,[SalesAmount]
      ,[TaxAmt]
      ,[Freight]
      ,[OrderDate]
      ,[DueDate]
      ,[ShipDate]
  FROM [AdventureWorksDW2022].[dbo].[FactInternetSales]
  WHERE [SalesAmount] = 1000.4375
```

Let's take a look at a couple of examples.
