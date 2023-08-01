# sql-challenge
 
This repository consists of:
* Folder **EmployeeSQL** consisting of the following:
  *   Folder **Data** with the 6 csv files provided
  *   **QuickDBD-export.png** an image file of ERD
  *   **QuickDBD-schemata.sql** consisting of tables schemata generated from ERD using QuickDBD
  *   **schemata.sql** with table schemta that I coded. **Note:** I have compared my results with both schematas and they are identical
  *   **module9_sql_solution.sql** file with my queries for analysis
  *   **Analysis Result** folder with csv downloads from running the 8 analysis sql queries

# Note:
pgAdmin 4V7 was used for sql

# Assumptions: 
* Composite key has been created for both dept_emp and dept_manager tables as the data has multiple managers per department and multiple employees are there in multiple departments. I have assumed that an employee could also be manager of multiple departments since they can be part of multiple departments as per dept_emp data
* I havent created a foreign key on the composite key between dept_emp and dept_manager in order to reduce complexity however it would be another referential constraint to consider in those tables, depending on usage requirement. At present it is not required for the analysis questions posed
* Salaries file will always have salaries against all employees. If this will not be the case then a left join will have to be used for generating results of the first analysis question however it will have null values against non existant salaries which would be incorrect. Therefore assumption holds true
  


