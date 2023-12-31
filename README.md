SQL Challenge - Pewlett Hackard Employee

Prerequisites

1. Install a SQL database management system like pgAdmin4.
2. Download the six CSV files available in the Resources folder.
3. Download the two SQL files located in the EmployeeSQL folder.

Data Modeling

In this phase, we examined the CSV files in the Resources folder within the repository. Subsequently, we created an Entity-Relationship Diagram (ERD) that represents the relationships among the relevant tables.

You can find the ERD sketch in the "ERD_EmployeeSQL_Diagram" file within the EmployeeSQL folder.

Data Engineering

Using the raw CSV files, we needed to establish the appropriate table structures for each of the six CSV files. During this process, we defined data types, primary keys, foreign keys, and other constraints. Once the schemas were in place, we imported the data from each CSV file into the respective SQL tables.

The SQL script for this data engineering step can be found in the "DataEngineering.sql" file within the EmployeeSQL folder.

Data Analysis

In this section, we were tasked with writing SQL queries to address specific questions:

1. List the employee number, last name, first name, sex, and salary of each employee.
2. List the first name, last name, and hire date for the employees who were hired in 1986.
3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
4. List the department number for each employee along with that employee’s employee number, last name, first name, and department name.
5. List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.
6. List each employee in the Sales department, including their employee number, last name, and first name.
7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
   
The SQL script for the data analysis phase can be located in the "DataAnalysis.sql" file within the EmployeeSQL folder.
