# SQL-CheatSheet


```SQL
-- list databse
\l

-- create database
CREATE DATABASE database_name;

-- connect to a database
\c database_name

-- display tables
\d

-- create table
CREATE TABLE table_name();

-- add column to table
-- INT is DATATYPE
ALTER TABLE table_name ADD COLUMN column_name INT;

-- delete column
ALTER TABLE table_name DROP COLUMN column_name;

-- rename column
ALTER TABLE second_table RENAME COLUMN name TO username;

-- insert row into dable
INSERT INTO table_name(column_1, column_2) VALUES(value1, value2);

-- delete row
-- condition can be username='admin'
DELETE FROM second_table WHERE condition;

-- drop table with schema (structure)
DROP TABLE table_name;

-- rename database
ALTER DATABASE database_name RENAME TO new_database_name;

```
