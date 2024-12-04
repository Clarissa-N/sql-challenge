# SQL Challenge: Employee Database Analysis
This repository demonstrates the use of data modeling, data engineering, and data analysis to explore and manipulate employee data. The project includes a structured SQL database schema, data import instructions, and various queries for analyzing the data.

# Repository Structure
**EmployeeSQL:** Contains all SQL files and resources for creating the database and performing analysis.
  + **QuickDBD-export.sql:** SQL code generated from the QuickDBD tool, representing the database schema.
  + **create_tables_schema.sql:** SQL script to create the database tables and establish relationships, as well as import the data from CSV files.
  + **employee_data_analysis.sql:** A collection of SQL queries designed to answer specific data analysis questions.
  + **Resources Folder:** Contains the necessary CSV files for importing data into the database tables.
  
# Instructions to Run the Files
**1. Set Up the Database and Tables**
Open and Execute the Schema Script:
  + Open the create_tables_schema.sql file in PGAdmin
  + Execute the entire script to create the tables

**2. Import the Data:**
  After executing the schema, import the CSV data into the database tables in the following order:
1. **titles**
2. **Departments**
3. **employees**
4. **salaries**
5. **dept_emp**
6. **dept_manager**
You can import the data using the Import/Export feature in PGAdmin

**3. Run Analysis Queries**
Open the employee_data_analysis.sql file in a new query window.
The file contains multiple SQL queries designed to answer various analysis questions. You can run these queries individually to view the results.

