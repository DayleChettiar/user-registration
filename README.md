
## Prerequisites
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Stack
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL

## Preperation/ Configuration
On your MySQL workbench, run the sql script, ```db.sql```
configure the project, ```user-registration``` as a maven project on you're IDE.

## Run
    ```mvn clean install```
    ```mvn jetty:run```

    go to ```http://localhost:8080/registration``` for first time registration 
     and ```http://localhost:8080/login``` for user login


OR :
    ```mvn clean install```
    user-registration -> run as -> Run on Server (apache tomcat 7.0.59)

    go to ```http://localhost:8080/account/registration``` for first time registration 
     and ```http://localhost:8080/account/login``` for user login

# user-registration
