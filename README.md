# Student-CRUD-Assignment
This is a simple CRUD (Create, Read, Update, Delete) application built using Spring Boot for managing student records.













**Features**

**Create**: Add new student records to the database.                                                                                  
**Read**: Retrieve existing student records from the database.                                                                                                   
**Update**: Modify existing student records in the database.                                                                                                      
**Delete**: Remove student records from the database.
















**Technologies Used**                                                                                                   
**Spring Boot**: Framework for building robust Java applications.                                                                                 
**Spring Data JPA:** Simplifies data access layer implementation.                                                                                     
**Hibernate**: ORM (Object-Relational Mapping) framework for database interaction.                                                                                         
**MySQL**: Relational database management system for data storage.








**Setup**
Clone the repository:
git clone https://github.com/shreyas-0203/student-crud-spring-boot.git










**Database Configuration:**
Configure your MySQL database credentials in application.yml.







**Build and Run:**

mvn clean install
java -jar target/student-crud-spring-boot.jar





**Access the Application:**
Open your web browser or Postman and navigate to http://localhost:8080.                                









API Endpoints                                                                                      
GET: http://localhost:8080/students                                        
Retrieve all students.


GET: http://localhost:8080/students/student/id                                                                  
Retrieve student by ID.


POST: http://localhost:8080/students   
Create a new student.


PUT: http://localhost:8080/students/update/id                                                                                           
Update an existing student.


DELETE: http://localhost:8080/students/delete/id                                                                      
Delete a student.
