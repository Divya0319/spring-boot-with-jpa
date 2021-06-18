# Spring Boot with JPA
A Demo Spring boot app built using Java Persistence Library (JPA), for performing CRUD operations from local database.

It performs CRUD operations based on endpoints, and using HTTP methods, GET, POST, PUT and DELETE.

The application has no frontend portion, just the backend, returning data in the form of JSON, or if some error occurs, it throws the exception.

 *Following Endpoints are exposed in the app:*

   **GET  /employees** - for fetching all employee's details.  
   
   **GET  /employee{employeeId}** - for fetching single employee's detail by giving id.  
   
   **POST  /employees** - for creating a new employee.  
   
   **PUT  /employees** - for updating a particular employee.  
    
   **DELETE  /employees{employeeId}** - for removing an employee by giving id.  
   
   
   ## Demo of working of application:
   
   Get all employees  
   ![](https://github.com/Divya0319/spring-boot-with-jpa/blob/master/screencaptures/spring-boot-jpa-get-all-employees.gif)
   
   Get single employee by id  
   ![](https://github.com/Divya0319/spring-boot-with-jpa/blob/master/screencaptures/spring-boot-jpa-get-single-employee.gif)
   
   Create new employee  
   ![](https://github.com/Divya0319/spring-boot-with-jpa/blob/master/screencaptures/spring-boot-jpa-create-employee.gif)
   
   Update an employee  
   ![](https://github.com/Divya0319/spring-boot-with-jpa/blob/master/screencaptures/spring-boot-jpa-update-employee.gif)
   
   Delete an employee  
   ![](https://github.com/Divya0319/spring-boot-with-jpa/blob/master/screencaptures/spring-boot-jpa-delete-employee.gif)
   
   
