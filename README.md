<P><strong>Hacker Rank Problem Solving</strong></P>
<P><strong>SQL Problems and Answers</strong></P>
<a href="https://www.hackerrank.com/imhayatunnabi"><img src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" alt="imhayatunnabi" /></a>
<br>

[Weather Observation Station 11](https://www.hackerrank.com/challenges/weather-observation-station-11/problem)

<P><strong>Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.</strong></P>

```sql
SELECT DISTINCT CITY FROM STATION WHERE LOWER(SUBSTR(CITY,1,1)) NOT IN ('a','e','i','o','u') OR LOWER(SUBSTR(CITY, LENGTH(CITY),1)) NOT IN ('a','e','i','o','u');
```
