The database consists of 7 main tables:

🔹 Departments:-
Field Name	
department_id
department_name	

🔹 Students:-
Field Name	
student_id	
name	
dob
gender	
email	
phone_number 
address	Address
admission_date	
department_id	

🔹 Faculty :-
Field Name	
faculty_id	
name	
email	
phone_number	
experience_years	
department_id

🔹 Course :-
Field Name	
course_id	
course_name	
faculty_id	

🔹 Enrollments:-
Field Name	
enrollment_id	
student_id	
course_id	
enrollment_date	

🔹 Attendance :
Field Name	
attendance_id	
student_id	
course_id	
attendance_date	
status :- Present / Absent / Late

🔹 Grade :-
Field Name 
grade_id 
student_id 
course_id 
marks_obtained 
grade 	


✅ 1. CRUD Operations

Insert a new student record

Update student phone number

Delete an existing student record

These operations demonstrate basic database manipulation techniques.

✅ 2. Data Retrieval Queries

Retrieve students along with their department details using JOIN

Display top 10 students based on marks obtained

Calculate attendance percentage of students

Identify students having attendance below 75%

✅ 3. Subqueries

Find students scoring below 40 with attendance less than 50%

Identify students scoring above 90 marks

Retrieve faculty members not assigned to any course

✅ 4. Aggregate Functions

Count total students

Calculate average marks per course

Determine highest and lowest marks

Count students department-wise

Functions Used:

COUNT()

AVG()

MAX()

MIN()

SUM()

✅ 5. Attendance Analysis

GROUP BY

Conditional expressions

HAVING clause

Students were identified based on low attendance criteria.

✅ 6. Join Operations

INNER JOIN – Students and Departments

LEFT JOIN – Students without enrollment

RIGHT JOIN – Courses without faculty

FULL OUTER JOIN – Students without grades

✅ 7. Filtering & Sorting

Display student records in alphabetical order

Group students based on department

Calculate average marks course-wise

✅ 8. Nested Queries

Nested queries were used to:

Retrieve students scoring above average marks

Find experienced faculty members

Identify students frequently absent

✅ 9. Date Functions Used

Extract month from attendance date

Calculate years since admission

Format attendance date

Functions Used:

MONTH()

TIMESTAMPDIFF()

DATE_FORMAT()

✅ 10. String Functions Used

LENGTH()

TRIM()

IFNULL()

Used to manipulate and handle student data fields.

✅ 11. Window Functions

RANK() – To rank students based on marks

COUNT() OVER() – To calculate cumulative attendance

Running total of enrollments month-wise

✅ 12. CASE Statements

Student Performance:

Excellent

Good

Needs Improvement

Attendance Type:

Regular

Irregular

Defaulter