# Student-Management-System

A CRUD application includes obtaining all student data, adding a student, deleting a student, and updating a student. 
Implemented using the Spring Boot framework, Java, JDBC, JPA, and PostgreSQL.

![image](https://github.com/JesseLee62/img-storage/blob/master/Student-Management-System/springboot%26java%26postgresql.jpg)  

![image](https://github.com/JesseLee62/img-storage/blob/master/Student-Management-System/overview.jpg)  

****
##This application is already packaged. You can directly execute it from the target folder.

### Run
Navigate to: "student-management-system/target" directory
```bash
java -jar student-management-system-0.0.1-SNAPSHOT.jar
```
Or you can specify different port (default is 8080) 
```bash
java -jar student-management-system-0.0.1-SNAPSHOT.jar --server.port=8081
```

#### Endpoints:
* GET/POST:
```bash
http://localhost:8080/api/v1/student
```
* DELETE ("3" is the studentID):
```bash
http://localhost:8080/api/v1/student/3
```
* PUT ("3" is the studentID, "new_name" is the name you want to update, "new@gmail.com" is the email you want to update):
```bash
http://localhost:8080/api/v1/student/3?name=new_name
http://localhost:8080/api/v1/student/3?name=new&email=new@gmail.com
```
