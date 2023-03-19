
# Online College Assessement

The Online College Assessment project is a web-based application developed using PHP CodeIgniter Framework. This application allows students to take their exams online and enables lecturers/faculty to assess and evaluate student performance. The system requires valid and registered users to gain access to its features and functionalities. It has three different user roles, namely the Administrator, Lecturer/Faculty, and the Student. Each role has different restrictions and permissions.


## Tech Stack

**Client:** HTML, CSS, JavaScript, Bootstrap, jQuery

**Server:** PHP, CodeIgniter, MySQL


## Features

- User authentication and authorization
- Admin can manage users, courses, exam schedules, and generate reports.
- Lecturer/Faculty can create exams, add questions, and view student exams and scores.
- Students can take exams, view scores, and download results.
- Exam timer and automatic submission after the timer expires.
- Multiple-choice questions and descriptive questions.
- Responsive design for optimal user experience.


## User Roles

This project has 3 user roles based on their functionality:

- **Administrator**: 
    The Administrator has full control over the system. They can manage the entire system, including adding or removing users, creating and managing courses, setting exam schedules, generating reports, and other administrative tasks.
- **Lecturer/Faculty**:
    The Lecturer/Faculty can create exams, set exam rules, and add questions to the system. They can also view and grade student exams and generate reports.
- **Student:**
    The Student can take exams created by lecturers/faculty. They can only access exams for which they are registered, and they have limited access to the system. They can view their exam scores and download their result.


## Installation

To install the Online College Assessment project on your local machine, you need to follow the steps below.

- Download and install `XAMPP v3.3.0` on your computer.
- Clone the project files to the `htdocs` folder in your XAMPP installation directory.
- Create a new database in MySQL and import the database file `exam_db.sql` located in the Database folder.
- Configure the database connection in the `application/config/database.php` file. Set the `database name`, `username`, and `password` to match your local MySQL settings.
- Launch XAMPP and start the Apache and MySQL services.
- Open a web browser and navigate to `http://localhost/online_college_assessment` to launch the application.
## System Features
The Online College Assessment project has several features that make it an ideal solution for educational institutions that want to implement an online examination system. These features include:

## User Authentication and Authorization
The system requires valid and registered users to gain access to its features and functionalities. Users can log in with their username and password, and the system checks their credentials to determine their role and permissions.

## Admin Dashboard
The administrator dashboard is the control panel for managing the entire system. The administrator can perform tasks such as adding or removing users, creating and managing courses, setting exam schedules, generating reports, and other administrative tasks.

## Lecturer/Faculty Dashboard
The lecturer/faculty dashboard allows lecturers to create exams, set exam rules, and add questions to the system. They can also view and grade student exams and generate reports.

## Student Dashboard
The student dashboard allows students to take exams created by lecturers/faculty. They can only access exams for which they are registered, and they have limited access to the system. They can view their exam scores and download their result.

## Exam Timer and Automatic Submission
The system has an exam timer that starts when a student begins an exam. The timer counts down the time remaining, and when it reaches zero, the system automatically submits the exam.

## Multiple-Choice Questions and Descriptive Questions
The system supports both multiple-choice questions and descriptive questions. Lecturers can create exams with different question types, and students can answer them accordingly.

## 