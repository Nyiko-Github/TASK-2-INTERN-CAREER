Online Exam Management System
=============================

Table of Contents
-----------------
1. Introduction
2. Features
3. Technologies Used
4. Setup and Installation
5. Usage
6. Contributing
7. License
8. Contact

1. Introduction
---------------
The Online Exam Management System is a Java-based application designed to streamline the process of creating, managing, and taking exams online. This system provides a user-friendly interface for students and teachers, ensuring a seamless and efficient examination experience.

2. Features
------------
- User Authentication: Secure login and registration for students and teachers.
- Exam Management: Teachers can create, edit, and delete exams.
- Student Dashboard: Students can view and take available exams.
- Real-time Results: Instant grading and feedback for students after completing exams.
- Admin Panel: Manage users, exams, and view statistics.

3. Technologies Used
---------------------
- Java: Core programming language.
- MySQL: Database management system.
- JUnit: Testing framework.
- Maven: Project and dependency management.

4. Setup and Installation
--------------------------
### Prerequisites
- Java Development Kit (JDK) 22.0.1 or higher
- MySQL Server
- Maven

### Steps
1. Clone the Repository:
    git clone https://github.com/yourusername/Online-Exam-Management-System.git

2. Navigate to the Project Directory:
    cd Online-Exam-Management-System

3. Install Dependencies:
    mvn clean install

4. Set up the Database:
    - Create a new MySQL database.
    - Run the SQL script provided in `src/main/resources/db/schema.sql` to set up the tables.
    - Update the database connection details in `src/main/resources/db.properties`.

5. Run the Application:
    mvn exec:java -Dexec.mainClass="com.oems.Main"

5. Usage
---------
1. Login/Registration:
    - Use the application’s login screen to sign in.
    - New users can register for a student or teacher account.

2. Teacher Dashboard:
    - Create, edit, or delete exams.
    - View submitted exams and student performance.

3. Student Dashboard:
    - View available exams.
    - Take exams and view instant results.

6. Contributing
----------------
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

7. License
-----------
This project is licensed under the MIT License. See the LICENSE file for details.

8. Contact
-----------
For any questions or feedback, please reach out to:
- Your Name: nrmaswanganyi@gmail.com
- GitHub: https://github.com/yourusername
- LinkedIn: https://linkedin.com/in/yourprofile

_For any questions or feedback, please reach out to:

Your Name: nrmaswanganyi@gmail.com
GitHub: Nyiko-Github
LinkedIn: Nyiko Roberto Maswanganyi_
