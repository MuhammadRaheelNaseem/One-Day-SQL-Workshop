![1](https://github.com/MuhammadRaheelNaseem/One-Day-SQL-Workshop/assets/63813881/c15d64b8-141c-4602-af16-b388863d2820)


# Learning Outcome

* What Is Database?
* Downloading & Installation Mysql Or Mariadb
* Memorize Some Mysql Command
* Installation Mysql Library
* Mysql Connectivity With Respect To Python
* Create Database | Create Table |Insert
* Select | Where | Order By | Delete
* Drop Table | Update | Limit | Join | Aggregate Fundtion

# What is MySQL? 
1. **Open-Source RDBMS:** MySQL is an open-source relational database management system.
2. **Free Usage:** It's freely available, making it accessible to all.
3. **Scalable and Versatile:** Suitable for both small and large applications due to its scalability.
4. **Performance:** Recognized for its speed, reliability, and ease of use.
5. **Cross-Platform:** Works seamlessly across various operating systems.
6. **Standards-Compliant:** Adheres to the ANSI SQL standard.
7. **Origin and Support:** Developed, distributed, and supported by Oracle Corporation.
8. **Name Origin:** Named after the daughter of co-founder Monty Widenius.

# What is RDBMS
- **RDBMS:** Relational Database Management System
- **Organization:** Data stored in tables with rows and columns
- **Relationships:** Establishes connections between data sets
- **Query Language:** Uses SQL for data retrieval and management
- **Efficiency:** Facilitates efficient data storage and manipulation
- **Data Integrity:** Maintains integrity through its relational structure and constraints

![image](https://github.com/MuhammadRaheelNaseem/One-Day-SQL-Workshop/assets/63813881/d878c0e9-f8f1-436f-b8a8-9432f9cb945d)



# <li style="font-size:20pt;">Downloading & Installation Mysql Or Mariadb</li>

https://dev.mysql.com/downloads/installer/

## Step 1:
Go to the official website of MySQL and download the community server edition software. Here, you will see the option to choose the Operating System, such as Windows.

## Step 2:
Next, there are two options available to download the setup. Choose the version number for the MySQL community server, which you want. If you have good internet connectivity, then choose the mysql-installer-web-community. Otherwise, choose the other one.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/550d21a8-bb6a-4907-9ee1-e298ed098e5b)

# Installing MySQL on Windows
## Step 1:
After downloading the setup, unzip it anywhere and double click the MSI installer .exe file. It will give the following screen:
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/dca1be60-67e2-49af-bfa3-6e54e990f843)

## Step 2:
In the next wizard, choose the Setup Type. There are several types available, and you need to choose the appropriate option to install MySQL product and features. Here, we are going to select the Full option and click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/5e3f609b-962a-457f-be05-ea131bc1551e)

This option will install the following things: MySQL Server, MySQL Shell, MySQL Router, MySQL Workbench, MySQL Connectors, documentation, samples and examples, and many more.

## Step 3:
Once we click on the Next button, it may give information about some features that may fail to install on your system due to a lack of requirements. We can resolve them by clicking on the Execute button that will install all requirements automatically or can skip them. Now, click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/2876885b-7074-41c4-b7ee-4a9afd7612b4)

## Step 4:
In the next wizard, we will see a dialog box that asks for our confirmation of a few products not getting installed. Here, we have to click on the Yes button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/0975452f-071f-4174-8ce1-34ae89330ecf)

After clicking on the Yes button, we will see the list of the products which are going to be installed. So, if we need all products, click on the Execute button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/2f8d7211-10fd-4e51-a414-40a10367aba4)

## Step 5:
Once we click on the Execute button, it will download and install all the products. After completing the installation, click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/5619d0ef-2b12-48de-81c1-f9a8dffa3230)

## Step 6:
In the next wizard, we need to configure the MySQL Server and Router. Here, I am not going to configure the Router because there is no need to use it with MySQL. We are going to show you how to configure the server only. Now, click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/3a4927cd-9f29-4f97-aa3c-366254ad3bd6)

## Step 7:
As soon as you will click on the Next button, you can see the screen below. Here, we have to configure the MySQL Server. Now, choose the Standalone MySQL Server/Classic MySQL Replication option and click on Next. Here, you can also choose the InnoDB Cluster based on your needs.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/61cc5c0f-0e56-4234-8b00-58a2b0b554ba)

## Step 8:
In the next screen, the system will ask you to choose the Config Type and other connectivity options. Here, we are going to select the Config Type as 'Development Machine' and Connectivity as TCP/IP, and Port Number is 3306, then click on Next.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/95f9ec4c-5bc7-48b3-b84e-777e31f82a57)

## Step 9:
Now, select the Authentication Method and click on Next. Here, I am going to select the first option.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/aea1ca23-41da-44de-9433-87b34a0eeb6b)

## Step 10:
The next screen will ask you to mention the MySQL Root Password. After filling the password details, click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/0b9c1616-2e53-41c0-a070-159b7119769c)

## Step 11:
The next screen will ask you to configure the Windows Service to start the server. Keep the default setup and click on the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/16f05f9d-5cef-4a99-9a38-e15ea28c08bb)

## Step 12:
In the next wizard, the system will ask you to apply the Server Configuration. If you agree with this configuration, click on the Execute button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/deac10cf-d8cb-4d3e-8131-204eb608a644)

## Step 13:
Once the configuration has completed, you will get the screen below. Now, click on the Finish button to continue.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/e1199431-0622-4793-b093-29cfe5d73868)

## Step 14:
In the next screen, you can see that the Product Configuration is completed. Keep the default setting and click on the Next-> Finish button to complete the MySQL package installation.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/95786ef2-2b45-429d-b252-c4bb9242043a)

## Step 15:
In the next wizard, we can choose to configure the Router. So click on Next->Finish and then click the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/c2ba2800-2d44-4917-9bc4-360faf7c81b9)

## Step 16:
In the next wizard, we will see the Connect to Server option. Here, we have to mention the root password, which we had set in the previous steps.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/adcebf22-8ab4-49ed-a849-ae10cce22e29)

In this screen, it is also required to check about the connection is successful or not by clicking on the Check button. If the connection is successful, click on the Execute button. Now, the configuration is complete, click on Next.

## Step 17:
In the next wizard, select the applied configurations and click on the Execute button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/39401439-09ac-4ba1-9ac1-a44b5dd5e757)

## Step 18:
After completing the above step, we will get the following screen. Here, click on the Finish button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/5a62aa85-4c04-45ed-b30b-2efd491f90ad)

## Step 19:
Now, the MySQL installation is complete. Click on the Finish button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/f0beac76-cdda-4bd4-8165-e385205d9ef5)


# Verify MySQL installation
Once MySQL has been successfully installed, the base tables have been initialized, and the server has been started, you can verify its working via some simple tests.

Open your MySQL Command Line Client; it should have appeared with a mysql> prompt. If you have set any password, write your password here. Now, you are connected to the MySQL server, and you can execute all the SQL command at mysql> prompt as follows:

## For example: 
Check the already created databases with show databases command:
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/de0d994c-631f-45c4-b1d7-ac1a0d6648c6)

# What is the Primary key?
A primary key is a single field or combination of fields that contain a unique record. It must be filled. None of the fields of the primary key can contain a null value. A table can have only one primary key.

# <li style="font-size:20pt;">Download MariaDB</li>

`Goto this link `https://mariadb.org/download/?t=mariadb&o=true&p=mariadb&r=10.5.5&os=windows&cpu=x86_64&pkg=msi `and download mariadb`

![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/1b0b8e59-b5fa-4903-81b8-86e7dbf6e6a5)

To install MariaDB on Windows, you follow these steps:

## Step 1. Start installation
Double-click the installer to start the installation process.

![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/e813e135-3d60-46a5-b945-d74e45179b95)

## Step 2. Accept the end-user license agreement
Read the end-user license agreement and click the Next button:

![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/09306b3a-6a24-41f9-8e43-a8ebf6f5c6fd)

## Step 3. Select features
Choose the directory that stores the MariaDB files and click the Next button. The default location on Windows is C:\Program Files\MariaDB 10.4\.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/0a2d3db5-939e-46e0-afb4-cbe9b3f66344)

## Step 4. Set root’s password
Type a password for the root user account. You will use this password to connect to MariaDB later.  The root user is the default user of the MariaDB, which has all privileges.

If you don’t want the root user to login from a remote machine, you need to uncheck the `Enable access from remote machines for 'root' user` checkbox.

The `Use UTF8 as the default server's character set` option allows you to use the UTF8 as the default character set when you create new databases and tables.

Once you complete selecting all options, click the Next button to go to the next step.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/f0bbdc52-245f-46f7-af45-4b3b96db198c)

## Step 5. Configure Database
In this step:

First, install MariaDB as a service by selecting the Install as service option. It allows you to rename the service name.

Second, configure the port for the MariaDB. By default, MariaDB uses 3306 port. However, you can change it to your port if you want.

Third, specify the parameters for the Innodb engine including buffer pool size and page size.  16KB page size is suitable for most databases.

Finally, click the Next button to go to the next step.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/9a6b17b4-21e2-4805-acae-135c3065c36f)

## Step 6. Submit usage information
If you want to submit anonymous usage information so that MariaDB developers can improve the system, check the checkbox and click the Next button.
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/e65edd77-e526-4de4-8c67-925618967a56)


## Step 7.  Ready to install MariaDB
Click the Install button to start installing MariaDB

![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/38145a24-6977-4c75-88b1-3c75721f0e21)
It will take a few minutes depending on the system.

![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/f44b67be-2fb4-4636-b1c0-d4b5477b400f)

## Step 8. Complete the MariaDB setup
Click the Finish button to complete MariaDB setup
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/0d5b5bc3-77e2-4182-8b5c-ac5a8c6f77be)

You can find the MariaDB tools in the startup menu:
![image](https://github.com/MuhammadRaheelNaseem/Learn-Python-By-Sir-Raheel/assets/63813881/3c0a798e-50ba-4132-bbfa-5c378c5deb84)


# Now Lets Do Some Queries


## 1.) SHOW DATABASES; | show databases;
```sql
    SHOW DATABASES;
    ...........or..............
    show databases;
```

<p>
    "SHOW DATABASES" is a command in MySQL that lists all the available databases on the current server. It gives you an overview of the databases present, allowing you to choose and work within a specific database.</p>
    


## 2.) CREATE DATABASE 
```sql
CREATE DATABASE `testing`;
.......or.........
create database `testing`;
```
<p>
    The command "CREATE DATABASE testing" in MySQL is used to create a new database named "testing." This command creates a fresh database within the MySQL server, ready to store and manage data.
    </p>


## 3.)  
```sql
CREATE DATABASE IF NOT EXISTS `testing`;
.............or.................
create database if not exists `testing`;
```
<p>
   "CREATE DATABASE IF NOT EXISTS testing;" makes a new database called "testing" only if it doesn't exist already, preventing any issues if it's already there.
</p>



# 4.) 
```sql
USE testing;
.......or.......
use testing;
```
<p>
    The command "USE testing;" in MySQL is used to switch to or select the database named "testing." Once executed, any subsequent operations or queries will be applied to the "testing" database until you switch to a different database or session ends.
</p>



## 5.)  
```sql
CREATE TABLE employee (employee_id INT(10), employee_name VARCHAR(255), employee_address VARCHAR(255)); 
................................or..........................................
create table employee (employee_id int(10), employee_name varchar(255), employee_address varchar(255)); 
```
<p>
    The command "CREATE TABLE employee (employee_id INT(10), employee_name VARCHAR(255), employee_address VARCHAR(255));" in MySQL creates a table named "employee" with columns for employee ID, name, and address. The specified data types for columns are INT for the ID (allowing up to 10 digits) and VARCHAR for the name and address (allowing up to 255 characters).
</p>


### 6.)  
```sql
CREATE TABLE IF NOT EXISTS employee (employee_id INT(10), employee_name VARCHAR(255), employee_address VARCHAR(255)); 
................................or..........................................
create table if not exists employee (employee_id int(10), employee_name varchar(255), employee_address varchar(255));
```
<p>
    The command "CREATE TABLE IF NOT EXISTS employee (employee_id INT(10), employee_name VARCHAR(255), employee_address VARCHAR(255));" in MySQL creates a table named "employee" with columns for employee ID, name, and address. If the "employee" table already exists, this command ensures that it won't be recreated, preventing any potential conflicts or errors.
</p>


##  7.) 
```sql
SHOW TABLES;
....or.....
show tables;
```
<p>
    The command "SHOW TABLES;" in MySQL displays a list of all the tables within the currently selected database. This command provides an overview of the tables available in the database you're currently working in.
</p>


### 8.) 
```sql
DESC employee;
.....or.....
desc employee;
.....or.....
DESCRIBE employee;
.....or.....
describe employee;
```
<p>
    The command "DESC employee;" in MySQL provides a description or structure of the "employee" table, showing details about its columns such as name, data type, length, and any additional attributes set for each column.
</p>


### 9.) 
```sql
INSERT INTO employee (employee_id, employee_name, employee_address) VALUES (1, 'Muhammad Raheel', 'street 5 london');
...............................or........................
insert into employee (employee_id, employee_name, employee_address) values (1, 'Muhammad Raheel', 'street 5 london');
```
<p>
    The command you provided, "insert into employee (employee_id, employee_name, employee_address) values (1, 'Muhammad Raheel', 'street 5 london');", inserts a new record into the "employee" table with an ID of 1, the name "Muhammad Raheel", and the address "street 5 london". This command adds a new entry to the table with the specified information in the respective columns.
</p>


### 10.)  
```sql
INSERT INTO employee (employee_id, employee_name, employee_address) VALUES (5, 'Thomas Edison', 'Washington, USA'), (6, 'John Doe', '123 Main Street'), (7, 'Alice Smith', '456 Oak Avenue'), (8, 'Cardinal Tom B.', 'Stavanger 4006, Norway');
.......................or............................
insert into employee (employee_id, employee_name, employee_address) values (5, 'Thomas Edison', 'Washington, USA'), (6, 'John Doe', '123 Main Street'), (7, 'Alice Smith', '456 Oak Avenue'), (8, 'Cardinal Tom B.', 'Stavanger 4006, Norway');
```
<p>
This SQL statement inserts multiple records into the "employee" table in one go. It adds four new entries to the table, each with a distinct ID, name, and address specified within the VALUES section.
</p>


### 10.) 
```sql
SELECT * FROM employee;
........or..........
select * from employee;
```
<p>
    The query "SELECT * FROM employee;" retrieves all records from the "employee" table, displaying the complete information stored across all columns for every entry in the table.
</p>


### 11.) 
```sql
SELECT * FROM  employee WHERE employee_name="Muhammad Raheel";
...................or.......................
select * from employee where employee_name="Muhammad Raheel";
```
<p>
    The query "SELECT * FROM employee WHERE employee_name='Muhammad Raheel';" fetches all records from the "employee" table where the "employee_name" column matches the value 'Muhammad Raheel'.
</p>


### 12.) 
```sql
SELECT * FROM employee ORDER BY employee_name ASC;
...............or..................
select * from employee order by employee_name asc;
```
<p>
   The query "SELECT * FROM employee ORDER BY employee_name ASC;" retrieves all records from the "employee" table and arranges them in ascending order based on the values in the "employee_name" column. 
</p>


### 13.) 
```sql
SELECT * FROM employee ORDER BY employee_name DESC;
.......................or......................
select * from employee order by employee_name desc;
```
<p>
The query "SELECT * FROM employee ORDER BY employee_name DESC;" fetches all records from the "employee" table and sorts them in descending order based on the values in the "employee_name" column. 
</p>


### 14.) 
```sql
DELETE FROM employee WHERE employee_name='Steve J';
...................or......................
delete from employee where employee_name='Steve J';
```
<p>
The query "DELETE FROM employee WHERE employee_name='Steve J';" removes records from the "employee" table where the "employee_name" column matches the value 'Steve J'. This will delete the respective entry or entries associated with the name 'Steve J' from the table.
</p>



### 15.) 
```sql
ALTER TABLE employee DROP COLUMN employee_address;
..............or................
alter table employeee drop column employeee_address;
```
<p>
The query "ALTER TABLE employee DROP COLUMN employee_address;" in MySQL alters the "employee" table by removing or dropping the column named "employee_address" from the table's structure. This action permanently deletes the specified column and its data from the table.
</p>


### 16.) 
```sql
UPDATE employee SET employee_name='Black Panther', employee_address='Wakanda, Africa' WHERE employee_id=8; 
.......................or....................................
update employee set employee_name="Black Panter", employee_address="Waganda, Africa" where employee_id=8;
```
<p>
This SQL statement updates the "employee_name" to 'Black Panther' and the "employee_address" to 'Wakanda, Africa' for the employee with an ID of 8 in the "employee" table.
</p>


### 17.)  
```sql
SELECT * FROM employee LIMIT 4;
...........or..............
select * from employee limit 4;
```
<p>
    The query "SELECT * FROM employee LIMIT 4;" retrieves the first four records from the "employee" table, displaying all columns for those specific four entries.
</p>


### 18.) 
```sql
SELECT * FROM employee LIMIT 3 OFFSET 3;
..........or............
select * from employee limit 3 offset 3;
```
<p>
The query "SELECT * FROM employee LIMIT 3 OFFSET 3;" retrieves three records from the "employee" table starting from the fourth record (offset of 3). This means it skips the first three records and fetches the subsequent three entries.
</p>


# Join 


```sql
CREATE TABLE employees (employee_id INT, employee_name VARCHAR(255), department_id INT);

CREATE TABLE departments (department_id INT, department_name VARCHAR(255));

INSERT INTO employees (employee_id, employee_name, department_id) VALUES (1, 'John', 101), (2, 'Alice', 102), (3, 'Bob', 101), (4, 'Mary', 103);

INSERT INTO departments (department_id, department_name) VALUES (101, 'Sales'), (102, 'Marketing'), (103, 'Finance');
```
### INNER JOIN
```sql
19.) SELECT * FROM employees INNER JOIN departments ON employees.department_id = departments.department_id; 
     .................or...................
     select * from employees inner join departments on employees.department_id = departments.department_id;
```
<p>
    This command retrieves all columns from the 'employees' table and combines them with corresponding records from the 'departments' table based on their shared 'department_id'.
</p>


### LEFT JOIN
```sql
20.) SELECT * FROM employees LEFT JOIN departments ON employees.department_id = departments.department_id;
     ...................or..................
     select * from employees left join departments on employees.department_id = departments.department_id;
```
<p>
    This command retrieves all columns from the 'employees' table and combines them with related records from the 'departments' table based on their shared 'department_id'. Unlike an INNER JOIN, a LEFT JOIN includes all records from the 'employees' table, regardless of whether there's a match in the 'departments' table. If there's no match, the corresponding 'departments' columns will be filled with NULL values.
</p>


### RIGHT JOIN
```sql
21.) SELECT * FROM employees RIGHT JOIN departments ON employees.department_id = departments.department_id;
     ...................or.......................
     select * from employees right join departments on employees.department_id = departments.department_id;
```
<p>This command retrieves all columns from the 'employees' table and includes related records from the 'departments' table based on their shared 'department_id'. Using a RIGHT JOIN ensures that all records from the 'departments' table are included, regardless of whether there's a match in the 'employees' table. If there's no match, the corresponding 'employees' columns will be filled with NULL values.</p>


### FULL OUTER JOIN
```sql
22.) SELECT * FROM employees LEFT JOIN departments ON employees.department_id = departments.department_id UNION SELECT * FROM employees RIGHT JOIN departments ON employees.department_id = departments.department_id;
```
<p>
    This query retrieves all columns from the 'employees' table and combines them with related records from the 'departments' table using both LEFT JOIN and RIGHT JOIN. The UNION operator combines the results of the LEFT JOIN and RIGHT JOIN into a single result set, excluding duplicates. This means it includes all records from both tables, ensuring a comprehensive view of the combined data based on the 'department_id'.
</p>


### CROSS JOIN
```sql
CREATE TABLE employees (employee_id INT, employee_name VARCHAR(255), department_id INT);

CREATE TABLE departments (department_id INT, department_name VARCHAR(255));

INSERT INTO employees (employee_id, employee_name, department_id) VALUES (1, 'John', 101), (2, 'Alice', 102), (3, 'Bob', 101), (4, 'Mary', 103);

INSERT INTO departments (department_id, department_name) VALUES (101, 'Sales'), (102, 'Marketing'), (103, 'Finance');
```

```sql
23.) select * from employees cross join departments;
```
<p>
    The query `SELECT * FROM employees CROSS JOIN departments;` performs a CROSS JOIN between the `employees` and `departments` tables. This generates a result set containing every combination of rows from both tables, displaying each employee paired with every department, resulting in a Cartesian product of their rows.
</p>


<p><b>Explaination:</b> A CROSS JOIN combines each row from one table with every row from another table, resulting in a Cartesian product. If Table A has 3 rows and Table B has 3 rows, their CROSS JOIN will yield 3 x 3 = 9 rows, showing all possible pairings between the rows of both tables.
</p>

```sql
24.) select * from employees cross join departments where employees.department_id=departments.department_id;
```
<p>
    This command performs a `CROSS JOIN` between the 'employees' and 'departments' tables. However, the additional condition `employees.department_id = departments.department_id` is attempting to filter the result based on a match between the 'department_id' columns from both tables. In a `CROSS JOIN`, this condition doesn't have any effect as it pairs all rows from 'employees' with all rows from 'departments', disregarding matching criteria.
    </p>



### SELF JOIN
```sql
CREATE TABLE customer (customer_id int, customer_name varchar(255), manager_id INT);
INSERT INTO customer (customer_id, customer_name, manager_id) VALUES(1, 'John', 3),(2, 'Alice', 3),(3, 'Bob', NULL),(4, 'Mary', 2),(5, 'David', 2);

```


```sql
24.)  SELECT e.customer_name AS customer, m.customer_name AS manager FROM customer e LEFT JOIN customer m ON e.manager_id = m.customer_id;
      ...................or......................
      select e.customer_name as customer, m.customer_name as manager as customer e left join customer m on e.manager_id = m.customer_id;
```
<p>This command retrieves customer names (`customer`) and their corresponding manager names (`manager`). It connects the `customer` table with itself using `manager_id` and `customer_id`, displaying each customer alongside their respective manager. If a customer doesn't have a manager, it shows 'NULL' for the manager's name.</p>


## AGGREGATE FUNCTIONS
Aggregate functions in SQL perform calculations on a set of values and return a single value. These functions allow you to compute summaries such as sum, average, count, minimum, or maximum across a group of rows.

Common aggregate functions include:

- **COUNT:** Counts the number of rows in a specified column.
- **SUM:** Calculates the sum of values in a specified column.
- **AVG:** Computes the average of values in a specified column.
- **MIN:** Retrieves the minimum value in a specified column.
- **MAX:** Retrieves the maximum value in a specified column.

These functions are often used with the `GROUP BY` clause to perform calculations on groups of rows, dividing the data into subsets based on the values in specific columns.

```sql
mysql> CREATE TABLE office (employee_id INT, employee_name VARCHAR(50), department_id INT, salary DECIMAL(10, 2));

mysql> INSERT INTO office (employee_id, employee_name, department_id, salary) VALUES (1, 'John', 101, 50000.00), (2, 'Alice', 102, 60000.00), (3, 'Bob', 101, 55000.00), (4, 'Mary', 103, 62000.00), (5, 'David', 101, 58000.00), (6, 'Eva', 102, 63000.00);
```

```sql
-- Department-wise total employees count
25.) SELECT department_id, COUNT(*) AS total_employees FROM employees GROUP BY department_id;
```
<p>
    This command retrieves the 'department_id' column and counts the number of occurrences for each 'department_id' in the 'employees' table. The GROUP BY clause then organizes the results based on 'department_id', creating groups where each group represents a unique 'department_id'. The COUNT(*) function calculates the number of rows in each group, indicating the total count of employees in each department.
</p>

```sql
-- Department-wise average salary
26.) SELECT department_id, AVG(salary) AS avg_salary FROM employees GROUP BY department_id;
```
<p>
    This command fetches the 'department_id' column and computes the average salary for each department in the 'employees' table. It uses the `GROUP BY` clause to organize the results into groups based on 'department_id', calculating the average salary within each department using the `AVG()` function.
</p>

```sql
-- Department-wise maximum salary
27.) SELECT department_id, MAX(salary) AS max_salary FROM employees GROUP BY department_id;
```

<p>
    This command retrieves the 'department_id' column and finds the maximum (highest) salary within each department from the 'employees' table. It utilizes the `GROUP BY` clause to group the results by 'department_id', and then applies the `MAX()` function to determine the highest salary within each department group.
</p>

