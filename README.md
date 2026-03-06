# Student Management System (SQL Project)

This is a beginner SQL project demonstrating database design and relational queries.

## Features

* Create relational tables (Students, Courses, Enrollments)
* Insert and manage student data
* Use JOIN queries to combine tables
* Perform filtering and aggregation

## Technologies

* MySQL
* SQL

## Concepts Used

* DDL (CREATE DATABASE, CREATE TABLE)
* DML (INSERT)
* JOINS
* Aggregate Functions

## Example Query

```sql
SELECT Students.name, Courses.course_name
FROM Students
JOIN Enrollments
ON Students.student_id = Enrollments.student_id
JOIN Courses
ON Enrollments.course_id = Courses.course_id;
```
