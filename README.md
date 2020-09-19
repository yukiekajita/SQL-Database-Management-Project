# SQL_Challenge

I designed the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. 

#### Data Modeling

Inspected the CSVs and sketched out an ERD of the tables. I used a tool: [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com).

* ERD Image


![Employee_ERD](EmployeeSQL/Employees_ERD.png)



#### Data Engineering

* Used the information I created a table schema for each of the six CSV files with specifying data types, primary keys, foreign keys, and other constraints.

* Imported each CSV file into the corresponding SQL table. 

#### Data Analysis

1. Listed the following details of each employee: employee number, last name, first name, sex, and salary.

2. Listed first name, last name, and hire date for employees who were hired in 1986.

3. Listed the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. Listed the department of each employee with the following information: employee number, last name, first name, and department name.

5. Listed first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. Listed all employees in the Sales department, including their employee number, last name, first name, and department name.

7. Listed all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, listed the frequency count of employee last names, i.e., how many employees share each last name.

## Bonus (Optional)

1. Imported the SQL database into Pandas.

2. Created a histogram to visualize the most common salary ranges for employees.

3. Created a bar chart of average salary by title.

## Epilogue

Searched ID number: 499942.
