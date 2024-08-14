# sql-challenge
Module_9_Challenge

# Pewlett Hackard Employees (1980 - 1999)

In this challenge my objective was to research the employees of Pewlett Hackard from the 80s and 90s.
I was provided with 6 CSV files that had employee information.
The CSV files can be seen in the 'data' folder.

# Data Modeling

My first task was to inspect the CSV files and sketch an Entity Relationship Diagram.
I used QuickDBD to make a diagram defining the relationships between all the csv files provided.
The diagram can be seen in 'EmployeeSQL/QuickDBD.png'.

# Data Engineering

My next task was to create a table schema for each of the 6 CSV files provided.
I created all 6 tables, assigned each of the variables with their proper data type,
and established the relationships among the tables using constraints such as primary keys, foreign keys, and references.
The table schema can be seen in 'EmployeeSQL/Data Engineering (Table Schemas).sql'.

# Data Analysis

My final task was to conduct queries to retrieve the specific data requested.
Most of the requested data required queries using the 'JOIN' clause to reference multiple tables.
I also used the 'ORDER BY' clause to organize the data according to the context of the request.
The table schema can be seen in 'EmployeeSQL/Data Analysis (Queries).sql'.