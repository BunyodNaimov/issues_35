## 1. Write a SQL statement that displays all the information about all salespeople




## 2. Write a SQL statement to display a string "This is SQL Exercise, Practice and Solution". 




## 6. Write a SQL statement to display specific columns such as names and commissions for all salespeople. 
```sql
select name,commission
from salesman
```

## 7. Write a query to display the columns in a specific order, such as order date, salesman ID, order number, and purchase amount for all orders

```sql
select ord_date, salesman_id, ord_no, purch_amt
from orders
```

##8. From the following table, write a SQL query to identify the unique salespeople ID. Return salesman_id
```sql
select salesman_id
from orders 





