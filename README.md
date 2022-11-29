# 🚕Taxi-service🚕

Web application to show simple CRUD operations, authentication, registration using MySQL and servlets, without any frameworks.

## Functional
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

![alt text](project_structure.png)
### DB schema
![alt text](taxi_models_diagram.jpeg)

## Technologies
- JAVA
- MAVEN
- Tomcat
- JDBC
- JSP
- Dependency injection
- HTTP (GET, POST, Filter)
## Instalation:
1. Create DB using local MySQL or remote database. You can find schema in  [init_db.sql](resources/init_db.sql) file.
2. Put our DB URL, username, password, and JDBC driver to ConnectionUtil.class.
   ![alt text](ConnectionUtil.png)

3. Install [Apache Tomcat v.9.x.x](https://tomcat.apache.org/download-90.cgi).
4. Clone this project from GitHub.
5. Configure Tomcat server.

## You can try working version
Heroku server: https://taxi.herokuapp.com/login