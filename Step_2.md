## Step 2 - SQL operators

### SQL comparison operators
The most basic way to filter data with WHERE clause is using comparison operators.
Here is the list of Comparison operators you can use to specify in a condition.

|ID |Operator| Description |
| -- |------------- | ------------- |
| 1 |  =  | Equal to	  |
| 2 |  >  | Greater than  |
| 3 |  <  | 	Less than		 
| 4 | >=  | Greater than or equal to  |
| 5 | <=  | Less than or equal to	  |
| 6 | <>  | Not equal to	  |

Let's take a look at a couple of examples.

#### 1. Examples comparison operators
1.1 First, the equality operator **"="**, used very often in many different complex SQL queries. It is worth knowing that it is not only used to compare numerical values, it can also be used for strings.
Below are two simple examples.

**SQL query**

```
SELECT * FROM AdventureWorksDW2022.dbo.DimProduct WHERE ProductAlternateKey = 'CR-7833'
```

**Query result**

![image](https://github.com/GeeHouseCode/SQL_EXERCISES/assets/110656951/548bb215-8678-439b-8f80-b1e16ea672c5)

**SQL query**

```
SELECT TOP(10) * FROM AdventureWorksDW2022.dbo.FactInternetSales WHERE SalesAmount = 1000.4375
```

**Query result**

![image](https://github.com/GeeHouseCode/SQL_EXERCISES/blob/main/Step_2/RQ_2.1.2.png)


### SQL Arithmetic Operators
