## Step 2 - SQL operators
In this step, I will show 3 groups of operators selected by me, which will be useful in the next steps of more advanced queries.
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

#### Examples comparison operators
First, the equality operator **"="**, used very often in many different complex SQL queries. It is worth knowing that it is not only used to compare numerical values, it can also be used for strings.
Below are two simple examples.

**SQL query**

```
SELECT * FROM AdventureWorksDW2022.dbo.DimProduct WHERE ProductAlternateKey = 'CR-7833'
```

**Query result**

![image](https://github.com/GeeHouseCode/SQL_EXERCISES/blob/main/Step_2/RQ_2.1.1.png)

**SQL query**

```
SELECT TOP(10) * FROM AdventureWorksDW2022.dbo.FactInternetSales WHERE SalesAmount = 1000.4375
```

**Query result**

![image](https://github.com/GeeHouseCode/SQL_EXERCISES/blob/main/Step_2/RQ_2.1.2.png)


### SQL Arithmetic Operators

|ID |Operator| Description |
| -- |------------- | ------------- |
| 1 | +	| Add	|
| 2 | -	| Subtract	|
| 3 | *	| Multiply	|
| 4 | /	| Divide	|
| 5 | %	| Modulo |

### SQL Logical Operators

|ID |Operator| Description |
| -- |------------- | ------------- |
| 1 | ALL	| TRUE if all of the subquery values meet the condition	|
| 2 | AND	| TRUE if all the conditions separated by AND is TRUE	|
| 3 | ANY	| TRUE if any of the subquery values meet the condition	|
| 4 | BETWEEN	| TRUE if the operand is within the range of comparisons	|
| 2 | EXISTS	| TRUE if the subquery returns one or more records	|
| 5 | IN	| TRUE if the operand is equal to one of a list of expressions	|
| 6 | LIKE	| TRUE if the operand matches a pattern	|
| 7 | NOT	| Displays a record if the condition(s) is NOT TRUE	|
| 8 | OR	| TRUE if any of the conditions separated by OR is TRUE	|
| 9 | SOME	| TRUE if any of the subquery values meet the condition |


