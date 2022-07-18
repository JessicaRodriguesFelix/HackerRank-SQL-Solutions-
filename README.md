# HackerRank-SQL-Solutions-
This is a repository of my solutions for the SQL Hacker Rank (Revising the Select Query II)


Query all columns for all American cities in CITY with populations larger than 100,000. The CountryCode for America is USA.

 ![image](https://user-images.githubusercontent.com/40796998/178380807-0559e899-ebdc-472f-ac44-f609eabc0713.png)


My Solution:

SELECT * FROM CITY
WHERE POPULATION > 100000 AND COUNTRYCODE = "USA";


Query a list of CITY names from STATION for cities that have an even ID number. Print the results in any order, but exclude duplicates from the answer. 
The STATION table is described as follows:
![image](https://user-images.githubusercontent.com/40796998/179433386-1a3da011-fc7c-4df2-abf9-76704118a23f.png)
where LAT_N is the northern latitude and LONG_W is the western longitude.

My Solution:

SELECT DISTINCT CITY from STATION
WHERE (ID % 2 = 0)
