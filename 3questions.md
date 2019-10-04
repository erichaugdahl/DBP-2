# **3 Questions For Avolve Fitness**
#### 1. What section is the dumbell rack in?
```sql
SELECT section
FROM Equipment
WHERE section = "dumbell rack"
```
#### 2. What is the average member age?
```sql
SELECT AVG (age)
FROM members
```
#### 3. What trainers make over $30,000.00 a year in salary?
```sql
SELCT salary
FROM staff
WHERE position = "trainer" AND salary > 30,000.00
```
