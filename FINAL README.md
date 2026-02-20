Database table creation

Inserting sample data

CRUD operations

Filtering & sorting

Aggregation functions

JOIN operations

Subqueries

Window functions

Conditional logic


🗂️ Database Structure

The database consists of 5 main tables:

 1. Students

 2. Courses

 3. Instructors

 4. Enrollments

 5. Departments


🔹 Students Table

Student ID

First Name

Last Name

Email

Birth Date

Enrollment Date

🔹 Courses Table

Course ID

Course Name

Department ID

Credits

🔹 Instructors Table

Instructor ID

First Name

Last Name

Email

Department ID

Salary

🔹 Enrollments Table

Enrollment ID

Student ID

Course ID

Enrollment Date

🔹 Departments Table

Department ID

Department Name


✅ CRUD Operations :-

Insert new student record

Retrieve student data

Update student email

Delete student record

✅ Data Retrieval Queries :-

Students enrolled after 2022

Courses offered by Mathematics department

Students enrolled in specific courses

✅ Aggregate Functions :-

Number of students in each course

Average credits of all courses

Maximum instructor salary

Count of students per department

✅ Joins Used :-

INNER JOIN

LEFT JOIN

To fetch:

Students and their enrolled courses

All students with or without course enrollment

✅ Subquery :-

Used to retrieve students enrolled in courses having more than 10 students.

✅ SQL Functions :-

YEAR() – Extract enrollment year

CONCAT() – Combine instructor names

CASE – Label students as Senior or Junior

TIMESTAMPDIFF() – Calculate student duration

✅ Window Function :-

Running total of students enrolled in courses using:

SUM(COUNT(StudentID)) OVER (ORDER BY CourseID)