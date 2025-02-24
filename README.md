Problem Solutions
1757 - Recyclable and Low Fat Products
sql
Copy
Edit
SELECT product_id
FROM Products
WHERE low_fats = 'Y'
AND recyclable = 'Y';
584 - Find Customer Referee
sql
Copy
Edit
SELECT name 
FROM Customer 
WHERE referee_id != 2 OR referee_id IS NULL;
595 - Big Countries
sql
Copy
Edit
SELECT name, population, area
FROM WORLD
WHERE area >= 3000000
OR population >= 25000000;
1148 - Article Views I
sql
Copy
Edit
SELECT DISTINCT author_id as id
FROM Views
WHERE viewer_id >= 1
AND author_id = viewer_id
ORDER BY author_id;
1683 - Invalid Tweets
sql
Copy
Edit
SELECT tweet_id
FROM Tweets
WHERE length(content) > 15;
1378 - Replace Employee ID With The Unique Identifier
sql
Copy
Edit
SELECT unique_id, name
FROM Employees e
LEFT JOIN EmployeeUNI eu
ON e.id = eu.id;
