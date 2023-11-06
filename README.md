# sql-challenge
homework assignment 9

Background
It’s been two weeks since you were hired as a new data engineer at Pewlett Hackard (a fictional company). Your first major task is to do a research project about people whom the company employed during the 1980s and 1990s. All that remains of the employee database from that period are six CSV files.


In this assignment, you are playing the role of a data engineer at Pewlett Hackard, a fictitious company. Your primary task is to perform a research project focusing on employees who were part of the company during the 1980s and 1990s. The available data is stored in six CSV files, which collectively represent the company's employee database.

1. **Database Schema and Tables**:
   - You begin by defining the structure of the company's database schema. This schema includes several tables: "departments," "dept_emp," "dept_manager," "employees," "salaries," and "titles." Each table serves a specific purpose and stores information related to employees and departments within the organization.

2. **Data Import**:
   - As a part of your assignment, you create and set up the database tables using SQL statements. This simulates the process of initializing a database or schema to work with the research project's data.

3. **Queries**:
   - **Query 1**: You are tasked with retrieving details about employees, including their employee number, last name, first name, gender, and salary. This information is extracted by joining the "employees" and "salaries" tables, providing insights into employee salary history.

   - **Query 2**: This query is aimed at identifying employees who were hired during the year 1986. You list their first names, last names, and hire dates to analyze the hiring trends during that specific year.

   - **Query 3**: The assignment requires you to compile a list of department managers. The details provided include the department number, department name, manager's employee number, last name, and first name. This allows for an understanding of the managerial structure within the company.

   - **Query 4**: To assist in organizational mapping, you are asked to list the department to which each employee belongs. The information includes the employee's number, last name, first name, and the name of their respective department.

   - **Query 5**: A more specific inquiry focuses on employees with the first name "Hercules" and last names starting with the letter "B." This query aims to identify any employees meeting these criteria.

   - **Query 6**: The Sales department is a point of interest in the assignment. You are requested to compile a list of all employees within the "Sales" department. This includes their employee numbers, last names, first names, and the name of their department.

   - **Query 7**: Expanding on the previous query, you are instructed to list employees not only from the "Sales" department but also from the "Development" department. The goal is to gain insights into two key departments within the company.

   - **Query 8**: In order to understand the diversity of last names among employees, you are tasked with listing the frequency count of each last name. This list is ordered in descending order of frequency, revealing how many employees share each last name.

Overall, your role as a data engineer in this assignment involves setting up and querying a database to extract valuable insights from the company's historical employee data. You're focusing on aspects such as salary trends, hiring patterns, department management, and the distribution of last names among employees during the specified decades.
