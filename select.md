# Select data from table including duplicate records

Select <"columns"> from <"tablename">;

# Select data from the table without inclucding duplicate records

Select Distinct <"columns"> from <"tablename">;

# Select count of data from the table

Select count(Distinct <"column name">) from <"tablename">;

# Select count of data and displaying by alias name 

Select count(*) as <"alias name"> from (select distinct <"columnname"> from <"tablename">;

# Select using where clause 

Select <"column1">, <"column2">, ...
from <"tablename">
where <"condition">;

e.g 
Note: SQL requires single quotes around text values but not for numeric values
```
SELECT * FROM Customers
WHERE CustomerID=1;

SELECT * FROM Customers
WHERE Country='Mexico';
```




