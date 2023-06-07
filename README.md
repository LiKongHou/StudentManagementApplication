# The student management program builds on the MVC model.
### 1.Model:

- Student: Represents a student with properties such as ID, name, age, and other relevant information.
- Classroom: Represents a classroom with properties such as ID, name, capacity, etc.
- Grade: Represents the grade of a student for a specific subject, with properties such as student ID, subject, and grade value.
- User: Represents a user with properties such as username and password.
- StudentDAO: Data Access Object responsible for handling CRUD operations for the Student entity.
- ClassroomDAO: Data Access Object responsible for handling CRUD operations for the Classroom entity.
- GradeDAO: Data Access Object responsible for handling CRUD operations for the Grade entity.
- UserDAO: Data Access Object responsible for handling user-related operations such as authentication and authorization.
- DatabaseConnector: Handles the connection to the MySQL database using JDBC.
### 2.View:

- LoginView: User interface components for the login functionality.
- ClassroomView: User interface components for displaying and managing classrooms.
- ClassListView: User interface components for displaying and managing the class list.
- GradeView: User interface components for displaying and managing student grades.
- Forms, tables, and other UI components: Allow users to add, edit, delete, and update data for each section.
### 3.Controller:

- LoginController: Handles user interactions and actions related to the login functionality.
- ClassroomController: Handles user interactions and actions related to the Classroom section.
- ClassListController: Handles user interactions and actions related to the Class List section.
- GradeController: Handles user interactions and actions related to the Grade section.
### 4.Database:

- MySQL Database: Set up a MySQL database to store information about classrooms, students, grades, and users. Create tables for each entity with appropriate columns.