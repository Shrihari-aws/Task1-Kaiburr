Kaiburr - Task 1 - Java Backend and REST API Example
It implements a Spring Boot application exposing REST API endpoints to manage and execute task objects.

Tasks:
1. Create a task
2. Get task by ID
3. Delete task by ID
4. Search tasks by name
5. Execute task and store execution details (startTime, endTime, output)

Technologies Used:
1. Java 17
2. Spring Boot
3. Maven wrapper
4. MongoDB
5. Postman
6. VS Code

API Endpoints:

Method         Endpoint                     Description                        

PUT     -  /tasks                     -  To create a new task                  
GET     -  /tasks?id={101}            -  To get task by ID                     
DELETE  -  /tasks?id={101}            -  To delete task by ID                  
GET     -  /tasks/search?name=print   -  To search tasks by name      
PUT     -  /tasks/101/execute         -  Execute task and save output       


Prerequisites:
1. Java 17
2. Spring Boot
3. Maven Wrapper
4. MongoDB


To run the Application:
./mvnw spring-boot

Reference to screenshots:

1. Create Task - Create-Task.png 
2. Get a Task - Get-Task.png
3. Get Task using Name - Get-Task-Name.png
4. Delete - Delete-Task.png
5. Execute - Execute-Task.png
7. 404 If nothing found - Exception.png

Task 4 workflow test
Trigger CI/CD test runs 

