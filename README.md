Module 9 Challenge

This repository sorts and analyzes employee information from 1980 to 1990 at Pewlett Hackard (a fictional company). This company data is contained in six csv files found in the data folder. The files are first moduled in QuickDBD to create a functional and practical database. Then using postgreSQL tables were created to match the database model. The queries for this step can be seen in the tables.sql file in the EmployeeSQL folder. From there a series of queries were used to display information on the employees. The questions and queries can be seen in the analysis_queries.sql file.

Chat Gpt was referenced to filter by year, using this code:

SELECT * 
FROM orders 
WHERE EXTRACT(YEAR FROM order_date) = 2024;
