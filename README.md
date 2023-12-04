# Spring-Boot-REST-API-Security-with-JPA-Hibernate
It shows how to secure  a Spring Boot REST API with Spring Security using JPA/Hibernate.

# Database scripts(using MySql)
The first script adds sample employees to the database which is my sample data for
Employee CRUD.
The second script creates the database tables for security.The script also creates the user accounts with encrypted passwords. It also includes
the user roles.

## Classes DemoSecurityConfig.java and UserService
These classes are used by Spring Security for custom authentication and authorization.

## Custom User Details entity classes (User, Role)
Creating the User and Role entity classes (using any name for these entities)

## Service and Dao classes
The service class has a method to find the user by username. This is used by Spring
Security to find a user during the login process.

The UserService extends UserDetailsService.
In the UserServiceImpl we implement the methods to lookup a user by username

The corresponding method calls in the Dao classes:
UserDao
UserDaoImpl

 ### Following Spring Boot 3 and Spring 6 & Hibernate Curse(Udemy) by Chad Darby
