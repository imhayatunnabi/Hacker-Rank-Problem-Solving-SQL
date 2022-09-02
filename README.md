<P><strong>Hacker Rank Problem Solving</strong></P>
<P><strong>SQL Problems and Answers</strong></P>
<a href="https://www.hackerrank.com/imhayatunnabi"><img src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" alt="imhayatunnabi" /></a>
<br>

[Weather Observation Station 11](https://www.hackerrank.com/challenges/weather-observation-station-11/problem)

### Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.

```sql
SELECT DISTINCT CITY FROM STATION WHERE LOWER(SUBSTR(CITY,1,1)) NOT IN ('a','e','i','o','u') OR LOWER(SUBSTR(CITY, LENGTH(CITY),1)) NOT IN ('a','e','i','o','u');
```

[Higher than 75 marks](https://www.hackerrank.com/challenges/more-than-75-marks/problem)

#### Query the Name of any student in STUDENTS who scored higher than Marks. Order your output by the last three characters of each name. If two or more students both have names ending in the same last three characters (i.e.: Bobby, Robby, etc.), secondary sort them by ascending ID.

```sql
SELECT NAME FROM STUDENTS WHERE MARKS > 75 ORDER BY SUBSTR(NAME, LENGTH(NAME)-2, 3), ID;
```

[Employee Names](https://www.hackerrank.com/challenges/name-of-employees/problem)

### Write a query that prints a list of employee names (i.e.: the name attribute) from the Employee table in alphabetical order.

```sql
select name from Employee ORDER BY name ASC;
```
