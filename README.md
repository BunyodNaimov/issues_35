## 1. Write a SQL statement that displays all the information about all salespeople
```sql
select *
from salesman
```

![изображение](https://user-images.githubusercontent.com/122611882/221497269-301533b7-95a3-47fa-85e6-4285ac8516d9.png)


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

![изображение](https://user-images.githubusercontent.com/122611882/221497726-f3b1341a-01b6-491d-8a1e-9338e00023bb.png)


##8. From the following table, write a SQL query to identify the unique salespeople ID. Return salesman_id
```sql
select salesman_id
from orders 
```
![изображение](https://user-images.githubusercontent.com/122611882/221497725-634daea7-1968-4a8e-ae31-48d4b0517ac6.png)

## 9. From the following table, write a SQL query to locate salespeople who live in the city of 'Paris'. Return salesperson's name, city

```sql





