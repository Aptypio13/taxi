# Taxi-Service Web-App
### Project description:

A simple web-application that supports authentication, registration and other CRUD operations. It is written for educational purposes.

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


## Project structure (3-layer architecture):
* `DAO - Data access layer`
* `Service - Application logic layer`
* `Controllers - Presentation layer`

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
- 3 Configure Apache Tomcat version (**IMPORTANT**): 9.0.xx;
- 4 Copy and run SQL script [/src/main/resources/init_db.sql](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
- 5 Configure [/src/main/java/taxi/util/ConnectionUtil.java](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
- 6 Done. Now just try to use it:

### For all questions - aptypio@gmail.com