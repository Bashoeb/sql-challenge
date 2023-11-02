#SQL Challenge - Pewlett Hackard Employee Database

Prerequisites

Install a SQL database management system like pgAdmin4.
Download the six CSV files available in the Resources folder.
Download the two SQL files located in the EmployeeSQL folder.

Data Modeling

In this phase, we examined the CSV files in the Resources folder within the repository. Subsequently, we created an Entity-Relationship Diagram (ERD) that represents the relationships among the relevant tables.

You can find the ERD sketch in the "ERD_EmployeeSQL_Diagram" file within the EmployeeSQL folder.

Data Engineering

Using the raw CSV files, we needed to establish the appropriate table structures for each of the six CSV files. During this process, we defined data types, primary keys, foreign keys, and other constraints. Once the schemas were in place, we imported the data from each CSV file into the respective SQL tables.

The SQL script for this data engineering step can be found in the "DataEngineering.sql" file within the EmployeeSQL folder.

Data Analysis

In this section, we were tasked with writing SQL queries to address specific questions:

Retrieve the employee number, last name, first name, sex, and salary of each employee.
Obtain the first name, last name, and hire date for employees hired in 1986.
Identify the manager of each department along with their department number, department name, employee number, last name, and first name.
List the department number for each employee alongside their employee number, last name, first name, and department name.
Find the first name, last name, and sex of employees with the first name "Hercules" and whose last name starts with the letter "B."
List all employees in the Sales department, including their employee number, last name, and first name.
Include in the list all employees in the Sales and Development departments, providing their employee number, last name, first name, and department name.
Calculate and list the frequency counts, in descending order, of all the employee last names (i.e., the number of employees sharing each last name).
The SQL script for the data analysis phase can be located in the "DataAnalysis.sql" file within the EmployeeSQL folder.
