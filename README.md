This is a CLONE, and I made this project from Youtube.

Tourism Management System is to manage the details of Customer, Hotel Booking, Cancellation and Tourism places. It manages all the information about Users, Hotel, Packages etc. The project is totally built at administrative end and thus only the administrator is guaranteed the access to the backend database. The purpose of this project is to build an application program to reduce the manual work for managing Tourists, Booking, Places etc. 

Integrated Development Environment: Netbeans
MySQL Command Line Client
Programming language: JAVA 

Database Query:

-- create database

create database tms;

-- use this database

use tms;

-- create table for signup class

create table account(username varchar(30), name varchar(40), password varchar(30), question varchar(100), answer varchar(50));


-- create table to add new customer in new customer class

create table customer(username varchar(30), id_type varchar(20), number varchar(20), name varchar(30), gender varchar(15), country varchar(20), address varchar(50), phone varchar(20), email varchar(40));

-- create table to add hotels

create table hotels(name varchar(30), cost_per_day varchar(20), food_charges varchar(20), ac_charges varchar(20));

-- insert value in the hotel table

insert into hotels values("JW Marriott Hotel", "2000", "2500", "3000");

insert into hotels values("Four Seasons Hotel", "1200", "1900", "2200");


-- create table for book hotel

create table bookHotel(username varchar(30), name varchar(30), persons varchar(20), days varchar(20), ac varchar(10), food varchar(10), id varchar(30), number varchar(20), phone varchar(20), cost varchar(20));


-- create table for package booking

create table bookPackage(username varchar(30), package varchar(40), persons varchar(20), id varchar(30), number varchar(20), phone varchar(20), price varchar(20));


Added JAR files in library rs2xml mysql-connector-j-8.3.0
