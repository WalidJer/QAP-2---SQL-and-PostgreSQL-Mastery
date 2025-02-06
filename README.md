# SQL Database Project

This repository contains SQL scripts for two database systems:

1. **University Course Enrollment System**
2. **E-Commerce Order Management System**

## University Course Enrollment System
This database manages students, professors, courses, and enrollments.  
**Key Features:**
✔️ Students can enroll in multiple courses.  
✔️ Each course has one professor.  
✔️ Data retrieval, updates, and deletions are included.  

### Tables:
- `students (student_id, first_name, last_name, email, school_enrollment_date)`
- `professors (professor_id, first_name, last_name, department)`
- `courses (course_id, course_name, course_description, professor_id)`
- `enrollments (student_id, course_id, enrollment_date)`

###  SQL Operations Included:
✅ Create tables  
✅ Insert data  
✅ Retrieve enrolled students  
✅ Update student email  
✅ Remove a student from a course  
