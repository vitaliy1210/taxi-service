# Taxi service
___
## Project description
A simple web-application that supports authentication, registration and other CRUD operations.
This project is a simulation of taxi service, where users are drivers. 
A car can have multiple drivers and a driver can drive multiple cars.
## Features
* registration like a driver
* authentication like a driver
* CRUD operations for drivers, manufacturers and cars
* display list of all manufacturers, cars and drivers
* display list of cars which drive current user
## Project structure
* N-tier architecture:
  * Database layer
  * DAO layer
  * Service layer
  * Client layer
* Followed SOLID principles;
## Project technologies
* Java
* JDBC
* Java Web
* HTML
* CSS
## Instructions for successful project start
1. You should run SQL-script from resources/init_db.sql in your SQL Server.
2. Set your own properties in ConnectionUtil: 
```
private static final String URL = "YOUR DB URL";
private static final String USERNAME = "YOUR USERNAME";
private static final String PASSWORD = "YOUR PASSWORD";
private static final String JDBC_DRIVER = "YOUR DRIVER";
```
3. Edit debug configurations and add Local Tomcat Server(recommended 9.0.50 version). 
4. Add artifact (war exploded) to deploy project in Tomcat settings.
5. Now you can run this project. In order to use all features you should register as driver and authorize with your login and password;
6. In order to create a car, you should indicate an existent manufacturer ID.
