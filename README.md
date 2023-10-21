# SE_IT_DATABASE_MANGEMENT_SYSTEM
DBMS Statement & Queries

[1] Design and develop below database and execute following SQL DML statements using 
MySQL .
emp (eno, ename, bdate, title, salary, dno) 
proj (pno, pname, budget, dno) 
dept (dno, dname, mgreno) 
workson (eno, pno, hours) 
1) Write an SQL query that returns the project name, hours worked, and project number for all works 
on records where hours > 10. 
2) Write an SQL query that returns the project name, department name, and budget for all projects 
with a budget < $50,000. 
3) Write an SQL query that returns the employee numbers and salaries of all employees in the 
'Consulting' department ordered by descending salary. 
4) Write an SQL query that returns the employee name, project name, employee title, and hours for 
all works on records.


[2] Design and develop below database and execute following SQL DML statements using 
MySQL .
emp (eno, ename, bdate, title, salary, dno) 
proj (pno, pname, budget, dno) 
dept (dno, dname, mgreno) 
workson (eno, pno, hours) 
1) Write an SQL query that returns the project number and name for projects with a budget greater 
than $100,000. 
2) Write an SQL query that returns the employees (number and name only) who have a title of 'EE' 
or 'SA' and salary more than $35,000. 
3) Write an SQL query that returns the employees (name only) in department 'D1' ordered by 
decreasing salary. 
4) Write an SQL query that returns the departments (all fields) ordered by ascending department 
name. 
5) Write an SQL query that returns the employee name, department name, and employee title. 



[3]Consider the following Relations. It defines Library Database Schema 
BOOK (Book_ISBN [PK], Title[Not Null], Publisher_ Name, Price[Check Price>0], 
Date_Of_Publication(Default SYSDATE), Book_Copy) 
BOOK_AUTHORS (Book_ISBN ,Author_Name [PK],Author_City[Default 
“Pune‟], Phone[UNIQUE]) 
Design and Develop SQL DML statements for above database using MySQL 
1. Create tables for above database with all constraints and Insert at least five records in each 
table. 
2. Select Book Names from table Book whose copies are in between 10 to 15. 
3. Update Book Copies as “10” whose Book Publisher is “Tata MacGraw Hill”. 
4. Select the Name of Publisher who supplied maximum books. 
5. Display name of publishers as per no of books published by them in ascending order. 
6. Select details of Books whose Author lives in “Pune”.



[4]Consider the following Relations. It defines Library Database Schema 
BOOK (Book_ISBN [PK], Title[Not Null], Publisher_ Name, Price[Check Price>0], 
Date_Of_Publication(Default SYSDATE), Book_Copy) 
BOOK_AUTHORS (Book_ISBN ,Author_Name [PK],Author_City[Default 
“Pune‟], Phone[UNIQUE]) 
Design and Develop SQL DML statements for above database using MySQL 
1. Create tables for above database with all constraints and Insert at least five records in each table. 
2. Add field Author_email to BOOK_AUTHORS table. 
3.Create a view on Book table as “DBMS BOOKS” by selecting all books titled DBMS. 
4.Drop the view “DBMS BOOKS” just created 



[6] Consider the following relation: Emp_company (ename, cname, salary, joiningdate, and 
city) 
1. List the maximum salary in all companies. 
2. Find maximum salary of employees of “TATA‟ Company. 
3. Count the number employees working in”ACC” company. 
4. Display the names of companies and the maximum salary in that company. 
5. Find the average salary of each company. 
6. Increase the salary of an employee by 15% who are living in city Mumbai. 
7. Delete rows of the table having salary less than 5000. 
8. List the names of employees who joined in Jan-2000



[5] Consider following Computer training institute database schema with following information. 
Course(coursecode, coursename, syllabus) 
Batch(batchcode, coursecode, startingdate, duration, coursefees, netincome, expectedincome) 
Enquiry(enquirynumber, fname, lname, coursecode, plotno, street, city, phone, enquirydate, 
enquirystatus) 
Enrollment(rollno, enquirynumber, batchcode, enrollmentdate) Write following Mysql queries: 
1. Display the contents of batch for particular course having coursecode=10 
2. Display the batchcode of batch having expectedincome more than netincome by 2000 
3. Display the coursename, startingdate of all batches 
4. Find out coursename with coursefees greater than 50000 
5. Display the details of batch having a specified coursename. 
6. Find out the number of persons whose name starts with „S‟. 
7. Delete all rows from enquiry for a specified coursename.



[7] Consider the following Bank DB schema. 
Deposit(accountno, cname, amount, acctdate,bname) 
Branch(bname,city) 
Customer(cname,city) 
Borrow(loanno, cname, bname,amount) 
Write the following Mysql queries. 
1. List all data from borrow table. 
2. Get customer names who has deposit greater than 1000 and name like “A”. 
3. Display name of customer with amount in descending order. 
4. List total loan. 
5. List branchname and branch wise deposit. 
6. Select the branches having sum of deposit more than 4000. 



[8] Consider the following Bank DB schema. 
Deposit(accountno, cname, amount, acctdate,bname) 
Branch(bname,city) 
Customer(cname,city) 
Borrow(loanno, cname, bname,amount) 
Write the following Mysql queries. 
1. List all data from borrow table. 
2. Get customer names who has deposit greater than 1000 and name like “A”.
3. List the branches having sum of deposit more than 1000 and located in Mumbai. 
4. List 10% interest to all depositors living in pune
5. Transfer Rs 500 from account of Anil to the account of Sunil. 
6. Delete depositors having deposit less than 500.



[9]Design and Develop DB for “Customerorder” with all constraints(Not NULL, PrimaryKey, 
Foreign Key). 
Customer (Cust_no, name, Street, city, state) 
Order (Order_no,Cust_no,Order_date,Ship_date,Tocity,ToState,ToZip) 
Contains(Order_no,Stock_no,quantity,Discount)- 
Stock(Stock_no,price,tax) 
1) Create View on columns Order_no and Customer_no with order table. 
2) Display Name of customer, City, OrderNo and order date of customer_no 101. 
3)Display price and discount of stock_no 102. 




[10] A database consists of following tables. 
PROJECT(PNO, PNAME, CHIEF) 
EMPLOYEE(EMPNO, EMPNAME) 
ASSIGNED(PNO,EMPNO) 
A. Get count of employees working on project. 
B. Get details of employee working on project pr002. 
C. Get details of employee working on project DBMS.



[11]Create a table „emp‟ with the following columns by assuming suitable data type and size with 
correct syntax in SQL. 
Emp–id, Ename, City, State, Salary, Age, Hire_ date. 
Give an expression in SQL to solve each of the following queries :
i) Find the names of all employees whose name starts with „Sa‟. 
ii) List all the employees name and salary whose age is less than 40 years. 
iii) Select the employees whose salary is between Rs. 20000 and Rs. 30000.



[12]Design the DB for ”Pets” and perform following operations: 
Pet(pet_name,owner,sex,birth_date,death_date) 
2) Display all the pets information. 
3)Display all pets in ascending and descending order according to birth date. 
4) Display the pet information of specific owner. 
5) count the pet which have same birth_date



[13] Write PL/SQL block to implement Curser to calculate grade of minimum 10 students.



[14] Write a database trigger on Library table. The System should keep track of the records that 
are being updated or deleted. The old value of updated or deleted records should be added in 
Library_Audit table.



[15] Write a Stored Procedure namely proc_Grade for the categorization of student. If marks 
scored by students in examination is <=1500 and marks>=990 then student will be placed in 
distinction category if marks scored are between 989 and900 category is first class, if marks 899 
and 825 category is Higher Second Class. Write a PL/SQL block for using procedure created 
with above requirement. 
Stud_Marks(name, total_marks) 
Result(Roll,Name, Class)
