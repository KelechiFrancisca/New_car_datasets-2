# New_car_datasets-2

# New Car Sales Report

## Overview

This is a report analysis of car sales.
+ Gender sales Report
+ Auto sales Report
+ Sales
---

> This is a point of sales report
>
- Total sales
-  Males Customers
- Female Customers
- Auto cars sold
- Manual cars sold
- Total cars sold
- Total Revenue by color
- Total Revenue by Body style
- Total Revenue by Dealer Region
- Total Revenue by Transmission
- Total Revenue by Company


## Power BI Visualization


<img width="1197" height="666" alt="Screenshot (15)" src="https://github.com/user-attachments/assets/65a85906-70d7-418e-8b8e-68fcfb8d2a1d" />


## SQL Queries
```sql
SELECT *FROM car_dataset;
```
```sql
SELECT color, SUM(price) AS 'Total sales' FROM car_dataset
GROUP BY color
```
```sql
ORDER BY SUM(price) DESC;
```
```sql
SELECT Body_Style, SUM(price) AS 'Total body_style' FROM car_dataset
GROUY BY Body_Style
```
```sql
SELECT Transmission, SUM(price)  AS 'Total Transmission' FROM car_data
GROUD BY Transmission
```
```sql
SELECT SUM(price) AS 'Total sales 2022' FROM car_data
WHERE date BETWEEN '2022/01/02' AND '2022/12/31' 
```
```sql
SELECT SUM(price) AS 'Total sales 2022 AND 2023' FROM car_data
WHERE date BETWEEN '2022/01/02' AND '2023/12/31'
```
```sql
SELECT Price, SUM(price) AS 'Total sales 2022 and 2023 FROM car_dataset
GROUP BY Price
```
```sql
SELECT Price, AVG(price) AS 'AVERAGE_selling_price' FROM car_dataset
GROUP BY Price
```
```sql
SELECT Price, AVG(price) AS 'AVERAGE_selling_price 2022 and 2023' FROM car_dataset
GROUP BY Price
```

