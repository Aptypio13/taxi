# Taxi Web-App
### Project description:

A simple web-application that supports authentication, registration and other CRUD operations. It is written for educational purposes.
The app simulates a cab service where you can control the number of drivers, their licenses and cars.

- ## Used technologies and libraries:
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- JDBC
- Javax Servlet
- JSP
- JSTL
- HTML/CSS 
- Checkstyle plugin


## Project structure (N-Tier Architecture):
* `DAO - Data access layer`
* `Service - Application logic layer`
* `Controllers - Presentation layer`
* `DB - вatabase based on MySQL server`


## Features:
- registration like a driver;
- authentication like a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- create/update/remove a driver;
- display list of all manufacturers;
- display list of all cars;
- display list of all drivers;
- display list of all cars by current driver;
- add driver to car.
- remove driver from car.
## Steps to run the program on your computer:
- 1 Clone the repo: [https://github.com/Aptypio13/taxi-serves.git](https://github.com/Aptypio13/taxi-serves.git);
- 2 Install MySQL;
- 3 Configure Apache Tomcat version (**IMPORTANT**) version: 9.0.xx;
- 4 Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- 5 Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- 6 Done. Now just try to use it:
## Example of parameters for ConnectionUtil.class
``` java
    private static final String URL = "jdbc:mysql://localhost:3306/taxi?useUnicode=true&serverTimezone=UTC";
    private static final String USERNAME = "root";
    private static final String PASSWORD = "123456";
    private static final String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver";
```

## I plan to add a:
* Remote sql-server
* CSS style
* Desktop version

### For all questions - aptypio668@gmail.com
