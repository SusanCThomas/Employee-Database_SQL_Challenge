# SQL Homework - Employee Database: A Mystery in Two Parts

## Employee-Database_SQL_Challenge

### Background:

Within this challenge, Pewlett Hackard presented a challenge to complete a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

Tables were designed to hold data in the CSVs, the CSVs were imported into a SQL database, and the data was queried. The following were performed:

1. Data Engineering

2. Data Analysis

### [Data Modeling](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Data_Modeling)

Inspected the CSVs and sketched out an [ERD](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Data_Modeling/QuickDBD-ERD.png) of the tables using [http://www.quickdatabasediagrams.com](http://www.quickdatabasediagrams.com).

### [Data Engineering](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Data_Engineering)

Created a [table schema](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Data_Engineering/Schema.sql) for each of the six [CSV files](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Data). The CSV files were imported into the corresponsing SQL tables after the data type, primary and foreign keys and other constraints were specified. 

### [Data Analysis](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Analysis)

After the database was complete, the following [analysis](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Analysis/EmployeeData_Analysis.sql) was performed:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

### [Bonus Analysis](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Bonus)

Examining the data created a suspicion that the dataset is fake. The following steps were taken to analyze further and create a [visualization](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/tree/main/Bonus/Images) of the data. 

1. Imported the SQL database and ran the analysis in a [Jupyter Notebook](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Bonus/Bonus_Analysis.ipynb).

2. Created a [histogram](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Bonus/Images/salary_range.png) to visualize the most common salary ranges for employees.

3. Created a [bar chart](https://github.com/SusanCThomas/Employee-Database_SQL_Challenge/blob/main/Bonus/Images/avg_salary.png) of average salary by title.


