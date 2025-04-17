# SQL-Execise---3

Joins, UNION, Filtering and Aggregates

SQL Practice Exercise: Joins, UNION, Filtering, and Aggregates
BrightLight Tutorials

Instructions:
1. Write answers on paper with a pen.
   
2. Draw tables of the final outcome.
   
3. In the SELECT statement, choose relevant columns to display, if not specified.
   
4. Scan the completed work into a PDF file and email it to:
rofhiwa@brightlighttutorials.co.za

5. Submission Deadline: 25 March 2025, 00:00

![image](https://github.com/user-attachments/assets/02ca38f9-722e-4ae2-80fd-06061e71f511)

Questions

1. SQL Joins
   
  1. Retrieve all employees and their assigned projects using an INNER JOIN.
    o Return: EmployeeID, FirstName, LastName, Department, Salary, ProjectID, ProjectName, Budget, Status.
  
  2. Retrieve all employees and their assigned projects, including employees who have no projects using a LEFT JOIN.
    o Return: EmployeeID, FirstName, LastName, Department, Salary, ProjectID, ProjectName, Budget, Status.
  
  3. Retrieve all projects and their assigned employees, including projects that have   no employees using a RIGHT JOIN.
    o Return: ProjectID, ProjectName, Budget, Status, EmployeeID, FirstName, LastName, Department, Salary.
  
  4. Retrieve all employees and projects, including those without a match in either   table using a FULL OUTER JOIN.
    o Return: EmployeeID, FirstName, LastName, Department, Salary, ProjectID, ProjectName, Budget, Status.

2. UNION & UNION ALL
  5. Retrieve a list of all unique cities where employees are located and project statuses.
    o Return: Location (Rename the column to Location using an alias).

  6. Retrieve a list of all cities where employees are located and project statuses, allowing duplicates.
    o Return: Location (Rename the column to Location using an alias).

3. Filtering Statements
   
  7. Retrieve employees who earn more than 70,000.
    o Return: EmployeeID, FirstName, LastName, Department, Salary.

  8. Retrieve employees working in either IT or Finance departments.
    o Return: EmployeeID, FirstName, LastName, Department, Salary

  9. Retrieve projects that are not yet completed.
    o Return: ProjectID, ProjectName, Budget, Status.

  10. Retrieve projects that have a budget greater than 70,000 and are not
completed.
    • Return: ProjectID, ProjectName, Budget, Status.

  11. Retrieve employees from New York OR Toronto, ordered by salary in descending order.
    • Return: EmployeeID, FirstName, LastName, Department, Salary, City.

  12. Retrieve the top 3 highest-paid employees.
    • Return: EmployeeID, FirstName, LastName, Department, Salary.

4. Aggregate Functions with GROUP BY & HAVING
   
  13. Find the total salary per department, sorted in descending order.

      • Return: Department, TotalSalary (Rename SUM(Salary) as TotalSalary).
      
  14. Find the average salary per city, but only include cities where the average salary is greater than 65,000.
      
    • Return: City, AverageSalary (Rename AVG(Salary) as AverageSalary).
    
  15.Count the number of employees per department, including only departments with more than 1 employee.
  
    • Return: Department, EmployeeCount (Rename COUNT(EmployeeID) as EmployeeCount).
    
  16. Retrieve the number of projects per status, but only include statuses with at least 2 projects.
      
    • Return: Status, ProjectCount (Rename COUNT(ProjectID) as ProjectCount).
    
  17. Retrieve the total project budget per employee, but only for employees who are managing projects worth more than 150,000.
      
    • Return: EmployeeID, FirstName, LastName, TotalProjectBudget (Rename SUM(Budget) as TotalProjectBudget).

 
