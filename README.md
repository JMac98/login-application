# login-application
Simple Spring Boot login application with connected to AWS RDS.

# Features
=====Trainers=====
* Register new trainers 
* View a list of trainers

=====Trainees=====
* Register new trainees
* View a list of trainees

=====Courses=====
* View a list of avaliable courses on offer
* Register a new course

=====Modules=====
* View a list of modules that are taught 
* Register a new module

=====Classroom=====
* View a list of classrooms and their capacitys 
* Register a new classroom

=====Groups=====
* Register a new group and assign it trainees/trainers
* Allocate a group to a classroom and assign it with a schedule (ie. start date and end dates)

### Prerequisites
```
MySQL Installer (MySQL Workbench, MySQL Server, MySQL Sample database)- https://dev.mysql.com/downloads/installer/ 

To run the application locally, You'll need to have a MySQL database (I used MySQL Workbench) and specify the name of the database, your chosen mysql password and username in the "application.properties" file.

```
## Built With
* [Spring Boot](https://spring.io/projects/spring-boot) - Platform based on Spring which provides a pre-defined web application development enviroment
* [Maven](https://maven.apache.org/) - Dependency Management
* [Spring Security] - https://mvnrepository.com/artifact/org.springframework.security/spring-security-core
* [Spring MVC] - https://mvnrepository.com/artifact/org.springframework/spring-webmvc
* [MySQL] - https://mvnrepository.com/artifact/mysql/mysql-connector-java
