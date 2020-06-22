![Language](https://img.shields.io/badge/Language-Java-red)
![Framework](https://img.shields.io/badge/Framework-Spring-brightgreen)
[![Licence](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](https://github.com/XinzeWang/GT-Food-Truck/raw/master/LICENSE) 

# GT Food Truck Database Management System

![title_logo](https://github.com/SKZhao97/GT-Food-truck-database-management-system/readme-resource/logo.png)

## Description
This project aims to design and implement a food truck database management system using relational database concepts. The goal is to improve food truck management and food order process for users, admins, managers and staffs. 

The design and structure of the database system originated from ***CS4400 "Database System", instructed by Mark Moss, from Georgia Institute of Technology.*** 

## Technique Stacks
* Database: MySQL
* Backend: Spring Boot + Hibernate
* Frontend: Thymeleaf, Semantic-UI

## Project Highlights
### Admin Manage Buildings and Stations
<br><br>
 ![image1](https://github.com/XinzeWang/GT-Food-Truck/raw/master/readme-resource/screen1.png)
 <br><br>
### Customer Explore Food Truck 
<br><br>
 ![image2](https://github.com/XinzeWang/GT-Food-Truck/raw/master/readme-resource/screen2.png)
<br><br>
### Order History
 ![image3](https://github.com/XinzeWang/GT-Food-Truck/raw/master/readme-resource/screen3.png)
<br><br>

## Run The Application On Your Local System
1.	Open the project file in IntelliJ or Eclipse
2.	Make sure you have a MySQL server running containing correct table schema and data 
3.	Enter your MySQL schema name and credentials in foodtruck/src/main/resources/application.properties
4.	To start the server, press “run application” or navigate to the root of the project via command line and execute the command “mvn spring-boot:run”
5.  The base path is localhost:8080
