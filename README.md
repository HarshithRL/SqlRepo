# SqlRepo
SQL Assignment

--Q1 (Creating Database and Tables) :

Question-1 

• Connected with SQL server database engine using SSMS

• Created database as school using query and Student database without using query.

• Created a backup file of database and dropped the database using Drop query.

• Backup file was restored from SQL server.

• AdventureWork2019 Db was restored from web source.

 Question-2

• Created table Locations with country_id,country_name and region_id columns.

• Renames the table name as Locations_new from Locations.

• Added a column region_name in Locations table using ALTER query.

• Added a column ID to the table Locations.

• Added a column state_province to the table Locations.

--Q2 (Creating The Table along with Constraint)

• Created table for given values 

• Created table for given values to achieve UNIQUE constraints

• Created Table to check UNIQUE values on more columns

• Created Table with Check constraint

• Altered table with check constraint

• Created table with check constraint and In operator

• Created table using check constraint and AND, OR operator. 

--Q3 (Select Statement Assessment)

• Created a Salesman table with the following columns and make sure Salesman_id column should be auto increment. 

• Inserted  records in salesman table

• SQL query to display all the information from the Salesman table

• SQL query to display distinct city from the Salesman table. 

• SQL query to display all distinct rows from the Salesman table

• SQL query to display distinct name and city from Salesman table. 

• SQL query to display all records but city should be "Paris" 

• SQL query to display all records but city should be "Paris" and commission should be greater than 0.14

• SQL query to display all records from Salesman table but commission column should be ascending order

• SQL query to display all records except San Jose city

• SQL query to display all records except San Jose city

--Q4 (Create a table Persons with PK & FK,analysis on AdventureworksDW2019)

• Created Two Table with given Columns Names & Constraints

• SQL query to sort the LastName as ascending order and show that LastName column as first column from DimCustomer table

• list top 20 Products from DimProduct Table

• list 50 percentage of customers from DimCustomers table

• Minimum and Maximum yearly income from DimCustomer Table.

--Q5 (Wild cards and Aggregate functions)

• List distinct records of EmailAddress where the EmailAddress having a letters combination "vi" from DimEmployee table

• List english product name starts with 'b' and ends with 'e' in EnglishProductName column from DimProduct table

• List english product names have "r" in the second position from EnglishProductName column in DimProduct Table

• List FirstName, DepartmentName, Title as specific columns and show who are working as 'Accountant' and 'Chief Financial Officer' from Title colum from DimEmployee table

• List FirstName and LastName as Employee Full Name using hot coding from DimEmployee Table

• List find minimum unit price from UnitPrice column in FactInternetSales table.

• List total sales amount from SalesAmount column in FactInternetSales table.

• list average tax amount from Taxamt column in FactInternetSales table.

• List  FirstName and Birthdate, the birth date range between 01-01-1980 to 31-12-1985 from BirthDate column in DimCustomer table, and the birthDate show in Ascending order

--Q6(GroupBy function Questions)

• Created Two Tables According to Given Data (Employee & ProjectDetails)

• Inserted Records Into the tables

• Query to  Get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for those employee which have assigned project already.

• Query to Get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for all employee even they have not assigned project.

• Query to Get all project name even they have not matching any employeeid, in left table, order by firstname from "EmployeeDetail" and "ProjectDetail".

• Query to Get complete record(employeename, project name) from both tables(EmployeeDetail,ProjectDetail), if no match found in any table then show NULL.

--Q7 (Group By)

• Created 2 table with mentioned data.

• SQL query to group the DeptID column and Salary need to average salary department-wise from above table.(Output columns: DeptID, Avg.Salary)

• In continuation to above applied Having condition on Average Salary > 3000 and show the result.

• Applied Join on Employee and Department tables using the common column DeptID.

• SQL query to display Dname, Avg. salary of Each dept. using Joins and Group by Clauses.

• From AdventureworksDB2019,SQL query to display FirstName and BirthDate and birthdate should be between 01-01-1985 to 01-12-1985 from DimCustomer and DimEmployee tables using Union and Union all functions.

--Q8 Part 1

• Created 2 table with mentioned data.

• Query to get FirstName in upper case as "First Name".

• Query for combine FirstName and LastName and display it as "Name" 

• Query all employee details from EmployeeDetail table whose "FirstName" contains 'k'

• Query all employee details from EmployeeDetail table whose "FirstName" end with 'h'

• Query all employee detail from EmployeeDetail table whose "FirstName" not start with any single character between 'a-p'

• Query all employee detail from EmployeeDetail table whose "FirstName" start with 'A' and contain 5 letters.

• Query all unique "Department" from EmployeeDetail table.

• Get the highest "Salary"  & Lowest "Salary" from EmployeeDetail table.

• Get the first name, current date, joiningdate and diff between current date and joining date in months.

• Get all employee details from EmployeeDetail table whose joining year is 2013.

• Get all employee details from EmployeeDetail table whose joining month is Jan(1).

• Get all employee details from EmployeeDetail table whose joining date between "2013-01-01" and "2013-12-01".

• Select all employee detail with First name "Vikas","Ashish", and "Nikhil".

• Display first name and Gender as M/F.(if male then M, if Female then F) 

• Select first name from "EmployeeDetail" table prifixed with "Hello "

• Get employee details from "EmployeeDetail" table whose Salary less than 700000

• Get employee details from "EmployeeDetail" table whose Salary between 500000 than 600000

• Select second highest salary from "EmployeeDetail" table.
 
--Q8 Part 2

• Create projectDetails table with above mentioned data

• Write the query to get the department and department wise total(sum) salary from "EmployeeDetail" table.

• Write the query to get the department and department wise total(sum) salary, display it in descending order according to salary.

• Query to get the department, total no. of departments, total(sum) salary with respect to department from "EmployeeDetail" table.

• Query to get department wise average salary from "EmployeeDetail" table order by salary ascending

• Query to get department wise maximum salary from "EmployeeDetail" table order by salary ascending

• Query to get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for those employee which have assigned project already.

• Query to get employee name, project name order by firstname from "EmployeeDetail" and "ProjectDetail" for all employee even they have not assigned project.

• Query to get all project name even they have not matching any employeeid, in left table, order by firstname from "EmployeeDetail" and "ProjectDetail".

• Query to get complete record(employeename, project name) from both tables (EmployeeDetail,ProjectDetail), if no match found in any table then show NULL.

• query to fetch EmployeeName & Project who has assign more than one project.