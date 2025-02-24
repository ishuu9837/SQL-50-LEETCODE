# SQL 50 LeetCode Solutions

This repository contains my solutions to the **SQL 50 Study Plan** on LeetCode. These problems cover a range of SQL concepts including joins, subqueries, window functions, aggregations, and more. Each solution is written in SQL and tested to work on LeetCode's platform (primarily MySQL, but adaptable to other SQL dialects with minor tweaks).

## How to Use
- Each problem is listed with its LeetCode problem number and title.
- Solutions are provided in SQL code blocks that you can copy and paste directly into LeetCode or your SQL environment.
- Some problems include alternative solutions (commented with `-- OR`) for different approaches.
- Comments within the code explain key logic where applicable.

## Solutions

### 1757 - Recyclable and Low Fat Products
```sql
SELECT product_id
FROM Products
WHERE low_fats = 'Y'
AND recyclable = 'Y';
