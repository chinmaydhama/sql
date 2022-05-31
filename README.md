ASSIGNMENT 1(MYSQL)



Q1)  Write an SQL query to fetch “FIRST_NAME” from Worker table using the alias
name as &lt;WORKER_NAME&gt;.
Ans:    Select FIRST_NAME AS WORKER_NAME from Worker;


Q2) Write an SQL query to fetch unique values of DEPARTMENT from Worker table.
ANS: select distinct DEPARTMENT from worker;


Q3) Write an SQL query to show the last 5 record from a table.
Ans: SELECT * FROM Worker ORDER BY Salary DESC LIMIT 05;

