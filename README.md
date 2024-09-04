#Setting up CI/CD Pipeline that does Unit Testing and Integration Testing on a java application running on Elastic Beanstalk
#Created by Allan Walters (AWS)

#Description
#Use CodePipeline to set up a pipeline that uses CodeBuild to pull from a Git Repository to compile a simple Java application from Spring Boot that does user management (Post,Get,Put,Delete).
#Details on build.yml and Pom.xml to set up a project. Maven to build a .jar file that is then uploaded to a Elastic Beanstalk container to run the application. Additional steps in the 
#pipeline are broken out to execute the unit level testing using examples, followed by a pipeline step that does Integration testing. The pipeline is automatically called when a push is 
#performed to the Git Repository.


#Using a SpringBoot REST API app as a simple example to compile a java application and put the .jar file onto a EC2 running in Elastic Beanstalk.

#POM.xml to define the environmetn

#Buildspec.yml for build step in CodePipeline
#Unit_Testing_Buildspec.yml for unit testing step in CodePipeline
#Integration_Tests_Buildspec.yml for integration testing step in CodePipeline




#Environment
#GitHub for code
#AWS Cloud9 

#Main technology
#•	DevOps pipeline

#AWS Services
#	
#•	AWS CodeBuild 
#•	AWS CodeDeploy 
#•	AWS Elastic Beanstalk 
#•	AWS Identity and Access Management 





# Spring Boot 3 REST API: CRUD example

For more detail, please visit:
> [Spring Boot 3 REST API example: CRUD App](https://www.bezkoder.com/spring-boot-3-rest-api/)

In this tutorial, we're gonna build a Spring Boot 3 Rest API example with Maven that implement CRUD operations. You'll know:
- Way to define Spring Rest Controller
- Way to handle HTTP GET, POST, PUT, DELETE requests for CRUD Operations
- How to define Data Model and Service Component












Run both Back-end & Front-end in one place:
> [Integrate Angular with Spring Boot Rest API](https://www.bezkoder.com/integrate-angular-spring-boot/)

> [Integrate React.js with Spring Boot Rest API](https://www.bezkoder.com/integrate-reactjs-spring-boot/)

> [Integrate Vue.js with Spring Boot Rest API](https://www.bezkoder.com/integrate-vue-spring-boot/)

## Run Spring Boot application
```
mvn spring-boot:run
```



Other databases:
> [Spring Boot JPA + H2](https://www.bezkoder.com/spring-boot-jpa-h2-example/)

> [Spring Boot JPA + MySQL](https://www.bezkoder.com/spring-boot-jpa-crud-rest-api/)

> [Spring Boot JPA + PostgreSQL](https://www.bezkoder.com/spring-boot-postgresql-example/)

> [Spring Boot JPA + SQL Server](https://www.bezkoder.com/spring-boot-sql-server/)

> [Spring Boot + MongoDB](https://www.bezkoder.com/spring-boot-mongodb-crud/)
