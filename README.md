# login-application
Spring Boot login application.

# Features
* Login and register a new user
* Login credentials saved onto a MySQL Database
* Password encrypted with Spring security and BCrypt
* Role access control

Deployed into a EC2 instance 

### Prerequisites
```
To run the application locally, you'll need to have a MySQL database on your local machine (I used MySQL Workbench) and specify the name of the database, your chosen mysql password/username on the "application.properties" file.

MySQL Installer (MySQL Workbench, MySQL Server, MySQL Sample database)- https://dev.mysql.com/downloads/installer/ 

```
## Built With
* [Spring Boot](https://spring.io/projects/spring-boot) - Platform based on Spring which provides a pre-defined web application development enviroment
* [Maven](https://maven.apache.org/) - Dependency Management
* [Spring Security](https://mvnrepository.com/artifact/org.springframework.security/spring-security-core) - Authentication and access-control framework
* [Spring MVC](https://mvnrepository.com/artifact/org.springframework/spring-webmvc) - Web framework
* [MySQL](https://mvnrepository.com/artifact/mysql/mysql-connector-java) - JDBC Driver for MySQL


* [AWS RDS](https://aws.amazon.com/rds/) - Amazons cloud based relational database service
* [AWS EC2](https://aws.amazon.com/ec2/) - Cloud computing service
