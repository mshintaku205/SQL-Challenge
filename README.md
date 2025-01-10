# SQL-Challenge
Module 9 Challenge

## Project overview
This project applies Data Engineering and Data Analysis techniques to construct an SQL database containing employee data from Pewlett Hackard, spanning the 1980s and 1990s. Six CSV files were used to store the employee information, which was then used to design SQL tables and successfully imported into the database.

## Objectives
This research project involves designing tables to store the CSV data, importing the CSV files into an SQL database, and addressing a series of questions based on the data. The tasks include:

1. Data Modeling
2. Data Engineering
3. Data Analysis

## Data Modeling
After inspecting the contents of each of the six CSVs, I created an ERD (Entity Relationship Diagram) using Quick Database Diagrams.

<img src = Employee_Relationship_Diagram.png>

## Data Engineering

- Using my ERD from the above, I manually wrote the SQL queries to create each of the tables within the database. While I was aware of the export tool available in the QuickDBD application to generate PostgreSQL queries directly from my ERD, I chose to manually write the queries to gain additional hands-on experience with SQL.
- I created all six tables, defining the appropriate column names, data types, primary keys, and establishing foreign key references where necessary.
- After setting up the tables, I used the built-in "Import/Export Data" tool in pgAdmin 4 to import the data from the CSV files into their corresponding tables.
- Once I verified that all the data had been imported correctly, I proceeded to write my analysis query.


## Data Analysis

I was given eight requirements to create analysis using SQL queries based on the previously imported data.

The eight requirements were as follows:

1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for employees who were hired in 1986.
3. List the manager of each department, along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee, along with the employee's employee number, last name, first name, and department name.
5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name starts with the letter B.
6. List all employees in the Sales department, including their employee number, last name, and first name.
7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency count, in descending order, of all employee last names (i.e., how many employees share the same last name).

The eight SQL queries for these requirements can be found in the "SQL_Challenge_Data_Analysis.sql" file.


## References
 The ERD was created at <a href=https://www.quickdatabasediagrams.com>QuickDBD</a>