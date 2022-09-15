CREATE TABLE STUDENT (
STUDENT_ID INT PRIMARY KEY,
F_NAME VARCHAR (200),
AGE INT,
SALARY DECIMAL (10,2)


);
DESCRIBE STUDENT;

/*DROP TABLE STUDENT;*/

ALTER TABLE STUDENT ADD GPA DECIMAL(3,2);

/*ALTER TABLE STUDENT DROP COLUMN GPA;*/

INSERT INTO STUDENT (STUDENT_ID, F_NAME, AGE, SALARY) VALUES(2,'JACK', 29,0);
INSERT INTO STUDENT (STUDENT_ID, F_NAME, AGE, SALARY) VALUES(1,'TONY', 29, 23657.05);
-- SPACE
show databases;
CREATE DATABASE contactdbs; 
USE contactdbs; /* changes the database to use*/
source
SHOW tables; /* shows the database in contactdbs */

/*SYNTAX

SELECT
    *
FROM
    table_1
[INNER] JOIN table_2
    ON table_1.id = table_2.table_1_id;


Here is another example, this time representing relationships between employees and managers:

SELECT
    *
FROM
    people AS employee
JOIN people AS manager
    ON employee.manager_id = manager.id;


ANOTHER EXAMPLE
SELECT
    *
FROM
    table1
JOIN
    table2
ON
    table1.id = table2.id AND table1.state = table2.state;


    ANOTHER EXAMPLE

    SELECT
    *
FROM
    table1
JOIN
    table2
USING
    (id, state);

    ANOTHER EXAMPLE
    SELECT
    *
FROM
    table1
NATURAL JOIN
    table2;

    ANOTHER Example..  import sql file into a remote server
 first of all you need to login to mysql using the following 
    mysql -u root -p -h  192.168.1.2   -P 3306 --protocol -tcp

    next
    CREATE DATABASE  contactdb; SOURCE c:\TONY\PROGRAMFILES\1.sql; USE contactdb; SHOW TABLES;

    ANOTHER EXAMPLE... IMPORTING MYSQL FILE INTO A DATABASE
    first chanage directory

    cd  C:\TONY\BIN
    mysql -u root -p  contactdb < C:\tony\programfiles\1.sql

     ANOTHER EXAMPLE

     how to load csv data into  sql

     create a database and a table

     then type...

LOAD DATA LOCAL INFILE "/path/to/boats.csv" INTO TABLE boatdb.boats
FIELDS TERMINATED BY ','
ENCLOSED BY '"'
LINES TERMINATED BY '\n'
IGNORE 1 ROWS; -- this means use the first header as rows

ANOTHER EXAMPLE

LOAD DATA LOCAL INFILE "/path/to/boats.csv" INTO TABLE boatdb.boats
FIELDS TERMINATED BY ','
LINES TERMINATED BY '\n'
IGNORE 1 LINES
(id, name, type, owner_id, @datevar, rental_price)
set date_made = STR_TO_DATE(@datevar,'%m/%d/%Y');


ANOTHER EXAMPLE
SELECT * FROM SomeTable
  WHERE timestampField >= TO_TIMESTAMP( '2013-03-04', 'yyyy-mm-dd' )
    AND timestampField < TO_TIMESTAMP( '2013-03-05', 'yyyy-mm-dd')

OR YOU CAN USE THIS EXAMPLE
SELECT * FROM SomeTable
  WHERE TRUNC(timestampField) = TO_DATE( '2013-03-04', 'yyyy-mm-dd' )
*/




