# HackerRank-SQL-Solutions-
This is a repository of my solutions for the SQL Hacker Rank

Revising the Select Query II


/*
Query all columns for all American cities in CITY with populations larger than 100,000. The CountryCode for America is USA.

+-------------+--------------+
| FIELD       | TYPE         |
+-------------+--------------+
| ID          | NUMBER       |
| NAME        | VARCHAR2(17) |
| COUNTRYCODE | VARCHAR2(3)  |
| DISTRICT    | VARCHAR2(20) |
| POPULATION  | NUMBER       |
+-------------+--------------+
 */

SELECT * FROM CITY
WHERE POPULATION > 100000 AND COUNTRYCODE = "USA";
