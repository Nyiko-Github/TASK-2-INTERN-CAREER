**Online Exam Management System**

**Table of Contents**
_Introduction
Features
Technologies Used
Setup and Installation
Usage
Contributing
License
Contact_

**Introduction**
_The Online Exam Management System is a Java-based application designed to streamline the process of creating, managing, and taking exams online. This system provides a user-friendly interface for students and teachers, ensuring a seamless and efficient examination experience._

**Features**
_User Authentication: Secure login and registration for students and teachers._
_Exam Management: Teachers can create, edit, and delete exams.
Student Dashboard: Students can view and take available exams.
Real-time Results: Instant grading and feedback for students after completing exams.
Admin Panel: Manage users, exams, and view statistics._

**Technologies Used**
_Java: Core programming language.
MySQL: Database management system.
JUnit: Testing framework.
Maven: Project and dependency management._

**Setup and Installation**

**Prerequisites**
_Java Development Kit (JDK) 22.0.1 or higher
MySQL Server
Maven
Steps
Clone the Repository:_

**Copy code**
_git clone https://github.com/yourusername/Online-Exam-Management-System.git
Navigate to the Project Directory:_

**Copy code**
_cd Online-Exam-Management-System
Install Dependencies_:

**Copy code**
_mvn clean install
Set up the Database:_

**Create a new MySQL database.**
_Run the SQL script provided in src/main/resources/db/schema.sql to set up the tables.
Update the database connection details in src/main/resources/db.properties.
Run the Application:_

**Copy code**
_mvn exec:java -Dexec.mainClass="com.oems.Main"
Usage
Login/Registration:_

**Use the application’s login screen to sign in.**
_New users can register for a student or teacher account.
Teacher Dashboard_:

**Create, edit, or delete exams.**
_View submitted exams and student performance.
Student Dashboard:_

**View available exams.**
_Take exams and view instant results.
Contributing
Contributions are welcome! Please follow these steps:_

**Fork the repository.**
_Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
License
This project is licensed under the MIT License. See the LICENSE file for details_.

**Contact**
_For any questions or feedback, please reach out to:

Your Name: nrmaswanganyi@gmail.com
GitHub: Nyiko-Github
LinkedIn: Nyiko Roberto Maswanganyi_
