# SQL NOTES

## TOPIC'S AND SOLUTION 💛
<hr>

## create table 
  **Syntax**
```
    create table <table_name>
  (
    Column_name varchar(10),  // varchar for number of input into the box
    Column_name int,          // int for only numbers into the box 
    Column_name date,         // date 'mm-dd-yyyy'
    Column_name varchar(50),  
  );
```
  **Example**
```
  create table lightningzero
  (
    full_name varchar(10),
    reg_no int,
    dob date,
    address varchar(50)
  );
  desc lightningzero
```
<img src='img/create_table.png'>

## insert values into the table 
  **Syntax**
```
  insert into <table_name> values (<Column_1_value>,<Column_2_value>,<Column_3_value>,<Column_4_value>,...);
```
  **Example**
```
  insert into lightningzero values ('lightning zero',00,'05-23-2002','CBE');
```
<img src='img/inserting_values.png'>
