# NorthEast-College
A modern online course register and learning managment website built with HTML, CSS, and JavaScript, featuring smooth GSAP animations for an elegant and interactive browsing experience.

Functional Requirements

This project is an Online Registration and Learning Management System designed to support basic student and teacher activities. Since we are not using a backend yet, the system depends on browser storage (localStorage) to simulate data persistence. The goal is to demonstrate the workflow of a simple LMS with clean UI, smooth navigation, and core learning features.


1. User Management

1.1 Registration

A new user should be able to create an account by providing their full name, email, and password.

The system must validate the inputs before creating the account.

Passwords should be checked for minimum length and matching confirmation.

After successful registration, user data is stored locally.


1.2 Login

Registered users must be able to log in using their email and password.

Login data should be checked against stored accounts.

If authentication succeeds, users should be redirected to the appropriate dashboard (Student or Teacher).

The login page must display error messages for invalid input.


1.3 User Roles

The system supports two roles: Student and Teacher.

Based on the selected role during registration, users see different dashboard features.

User role should be saved and used throughout navigation.



---

2. Course Management

2.1 Course Catalog

All users can view a list of available courses from the public “Courses” page.

Each course should display its title, instructor, short description, and a “View Course” button.


2.2 Course Enrollment (Student)

Students must be able to enroll in any course.

Once enrolled, the course should be added to their dashboard under “My Courses”.

Enrollment should be saved so it remains even after refreshing the page.


2.3 Course Creation (Teacher)

Teachers should be able to create new courses by entering course title, description, and lessons.

Created courses should appear in the general catalog.

Courses created by a teacher must appear on their dashboard for management.



---

3. Learning Flow

3.1 Lessons

Each course contains multiple lessons arranged as a curriculum.

Students should be able to open each lesson and view its content.

Lessons should show a “Mark as Completed” option.

Progress should update automatically based on completed lessons.


3.2 Lesson Viewer

The lesson page should display:

Lesson title

Lesson content

Navigation between lessons

A sidebar listing all lessons


Completion status should be visible inside the lesson list.



---

4. Student Dashboard

The student dashboard must include:

A welcome header showing the user’s name

A progress indicator for each enrolled course

A list of enrolled courses with a “Continue Learning” button

A notifications area (e.g., new assignments or upcoming lessons)

Quick links to assignments, quizzes, and profile settings


The layout should be simple, clean, and easy to navigate.


---

5. Teacher Dashboard

The teacher dashboard must include:

A list of all courses created by the teacher

A “Create Course” or “Add Lesson” button

A summary of enrolled students per course

A section showing recent submissions (assignments/quizzes)

Basic instructor profile details


The purpose is to simulate real LMS functionality in a lightweight way.


---

6. Assignments

6.1 Assignment List

Students should be able to view assignment instructions for each course.

Assignments should include a title, description, and due date.


6.2 Submission

Students must be able to submit a file or text answer.

After submission, the system should show:

Submitted file name or text

Timestamp

A confirmation message



Submission info should be saved so it doesn’t disappear on refresh.


---

7. Quizzes

7.1 Quiz Interface

A quiz consists of multiple-choice questions.

Students should see one question at a time with navigation buttons.


7.2 Grading

After completing a quiz, the system should calculate the score.

A results summary should be shown:

Correct answers

Incorrect answers

Final percentage



Scores should be saved locally.


---

8. Profile Management

Students and teachers should be able to:

View their profile details

Update basic information (name, email, avatar if needed)

See their activity (enrolled courses, created courses, progress, etc.)



---

9. General Requirements

9.1 Responsiveness

The entire website must be responsive and usable on phones, tablets, and laptops.

Layouts should adapt using flexbox and grid.


9.2 Navigation

A consistent header, sidebar, or menu should help users switch between pages.

Pages should load smoothly with transitions for a modern feel.


9.3 Data Handling

LocalStorage is used to simulate:

User accounts

Enrolled courses

Course creation

Progress tracking

Quiz scores

Assignments submissions



9.4 Visual Design

Use a modern UI approach with:

Clean fonts

Smooth hover animations

Modern cards

Soft shadows

Neat spacing



This should make the system feel professional even without a backend.


---

Non-Functional Requirements (Still important)

Usability: Simple UI, clear buttons, readable fonts.

Performance: Lightweight HTML/CSS/JS for fast loading.

Scalability (conceptual): Should be easy to integrate backend later.

Maintainability: Organized folder structure and commented code.

Security (simulated): Basic checks (input validation), but no real backend security.
