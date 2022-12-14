# 🚕Taxi-service🚕

Web application to show simple CRUD operations, authentication, registration using MySQL and servlets, without any frameworks.

## Features
+ register like driver
+ for authentication use login and password
+ have ability o add/remove/display all drivers, cars, manufacturers
+ have ability to connect drivers and cars
+ have ability to display all cars connected to driver

## Project structure
### N-tire architecture:
1. Presentation: simple jsp-pages, taxi.controllers
2. Application: taxi.services, taxi.models
3. DAO: taxi.dao
4. MySQL

![alt text](img/project_structure.png)
### DB schema
![alt text](img/taxi_models_diagram.jpeg)

## Technologies
| Technology | Version |
|:-----------|:--------|
| JDK        | 11      |
| Maven      | 4.0.0   |
| TomCat     | 9.0.50  |
| MySQL      | 8.0.22  |
| JDBC       | -       |
| Servlet    | 4.0.1   |
| JSTL       | 1.2     |
| JSP        | -       |
| HTML, CSS  | -       |
## Installation:
1. Create DB using local MySQL or remote database. You can find schema in  [init_db.sql](https://github.com/AndriiMatveev/my_taxi_service/blob/main/src/main/resources/init_db.sql) file.
2. Put our DB URL, username, password, and JDBC driver to [ConnectionUtil.class.](https://github.com/AndriiMatveev/my_taxi_service/blob/main/src/main/java/taxi/util/ConnectionUtil.java)
   ![alt text](img/ConnectionUtil.png)

3. Install [Apache Tomcat v.9.x.x](https://tomcat.apache.org/download-90.cgi).
4. Clone this project from GitHub.
5. Configure Tomcat server.

## You can try working version
Heroku server: https://taxi.herokuapp.com/login