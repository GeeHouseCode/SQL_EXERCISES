### Step 1, get to know the tables you're working on.
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

```
SELECT TOP (1000) *  FROM AdventureWorksDW2022.dbo.DimProduct
```
This query gives us the same result as the previous one (result on the screenshot and in the STEP_1 file). I showed this at the very beginning to make you realize that when writing SQL queries, several paths can lead to the same solution.
![RQ1 1_1 2](https://github.com/GeeHouseCode/SQL_EXERCISES/blob/main/Step_1/RQ1.1_1.2.png)




