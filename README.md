# Hive
This repo is about Hive. <br>
Link to the Repo:
https://github.com/badisasairam/Hive

# How to start hive?

Enter the cloudera VM or Udacity VM and then type sudo hive in the terminal to enter the hive cli.

How to check the databases present in the hive?
show databases;

How create a database?
create database databsename;

how to use the database?
use databasename;

how to check the tables present inside database?
show tables;

How to create the new tables in the database?
create table tablename(
variable_name varibale_type,
variable_name2 varibale_type2)
row format delimited fields terminated by ",";

gedit filename.input

HOw to load the data into the table?
LOAD DATA LOCAL INPATH 'path_name' INTO TABLE tablename;


Describe extended tablename -  find the path of the database

In Hadoop system,

Hadoop fs -ls 'path name'

## MR in HIVE:

select count(*) from tablename;
