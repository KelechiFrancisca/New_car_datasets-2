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


<img width="1180" height="644" alt="Screenshot (14)" src="https://github.com/user-attachments/assets/1364fd13-99f8-4ec1-a806-afdea9ec076c" />

### Visuals

## SQL Queries
```sql
SELECT *FROM car_data;
```
```sql
SELECT color, SUM(price) AS 'Total sales' FROM car_dataset
GROUP BY color
```

```sql
ORDER BY SUM(price) DESC;
```

```sql
SELECT *FROM car_data;
```
