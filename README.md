# SQL_EXERCISES
From Zero To Hero ;P  This repository contains SQL exercises for the purpouse of self learnig and hobby.
## Repository description
This repository is intended to serve as a knowledge base for T-SQL and SQL.
For the purposes of the exercises, the adventureworks database will be used ([link to the website with the database](https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver16&tabs=ssms)), and initially 3 tables DimCustomer, FactInternetSales, DimProduct, DimEmployee.
You will find here examples of queries from the simplest to advanced ones, have fun, I hope it will be a helpful read.


## Contents of the Repository

#### Step 1 - get to know the tables you're working on.
#### Step 2 -
#### Step 3 -  

## Step 1, get to know the tables you're working on.
The most important thing is to get to know the data and tables you are working on. There are at least two simple ways :P

```
SELECT TOP (1000) [EmployeeKey]
      ,[ParentEmployeeKey]
      ,[EmployeeNationalIDAlternateKey]
      ,[ParentEmployeeNationalIDAlternateKey]
      ,[SalesTerritoryKey]
      ,[FirstName]
      ,[LastName]
      ,[MiddleName]
      ,[NameStyle]
      ,[Title]
      ,[HireDate]
      ,[BirthDate]
      ,[LoginID]
      ,[EmailAddress]
      ,[Phone]
      ,[MaritalStatus]
      ,[EmergencyContactName]
      ,[EmergencyContactPhone]
      ,[SalariedFlag]
      ,[Gender]
      ,[PayFrequency]
      ,[BaseRate]
      ,[VacationHours]
      ,[SickLeaveHours]
      ,[CurrentFlag]
      ,[SalesPersonFlag]
      ,[DepartmentName]
      ,[StartDate]
      ,[EndDate]
      ,[Status]
      ,[EmployeePhoto]
  FROM [AdventureWorksDW2022].[dbo].[DimEmployee]
```

In this case, I used the SELECT query, which is available after right-clicking on the selected table in SSMS (SQL Server Management Studio). The first 1000 rows will be displayed.
