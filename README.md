# AvorisHelloEmployee

PostgreSQL dbname = mydb
PostgreSQL user password = dbpass
PostgreSQL user name = postgres

#SQL

create database mydb;
create table employee(
 e_id int primary key,
 nombre varchar(30),
 edad int
);

insert into employee values (1, 'Devon', 21);
insert into employee values (2, 'Xavi', 43);
