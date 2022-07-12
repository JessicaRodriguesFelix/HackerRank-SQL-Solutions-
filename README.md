# HackerRank-SQL-Solutions-
This is a repository of my solutions for the SQL Hacker Rank (Revising the Select Query II)


Query all columns for all American cities in CITY with populations larger than 100,000. The CountryCode for America is USA.

 ![image](https://user-images.githubusercontent.com/40796998/178380807-0559e899-ebdc-472f-ac44-f609eabc0713.png)


SELECT * FROM CITY
WHERE POPULATION > 100000 AND COUNTRYCODE = "USA";
