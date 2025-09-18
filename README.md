# 📚 Student Records Management System

## 📝 Project Overview

The Student Records Management System is a relational database designed to store and manage information about students, their courses, lecturers, and departments at a university.

The project demonstrates the application of database design principles and shows how different entities in an academic environment are related.

---

## 🎯 Objectives

- To design a structured relational database for managing student academic data.
  
- To implement appropriate constraints and relationships between tables.
  
- To model real-world entities and their interactions within a university setting.

---

## 🧩 Database Design

### Entities

- **Departments**  
  Represents the different academic departments within the university (e.g. Mathematics, Computer Science).

- **Lecturers**  
  Lecturers are staff who belong to a department and can teach multiple courses.

- **Students**  
  Students are enrolled in a department and can register for many courses.

- **Courses**  
  Each course is offered by a department and is taught by a lecturer.

- **Enrollments**  
  A junction table that records which students are enrolled in which courses (many-to-many relationship).

---

## ⚙️ Key Features

- Use of **Primary Keys** to uniquely identify each record.
  
- Use of **Foreign Keys** to create links between tables and enforce referential integrity.
  
- Implementation of **One-to-Many** (Departments → Students) and **Many-to-Many** (Students ↔ Courses) relationships.
  
- Use of constraints such as **NOT NULL** and **UNIQUE** to ensure data accuracy.

---

## 📌 Summary

This project showcases how a real-world scenario can be represented in a relational database using MySQL.

It highlights the importance of proper schema design, data integrity, and the use of relationships to link different parts of a system together in a logical and organized way.

---

## ✍️ Author
**Tracy Imbosa Musiomi**  
Actuarial Science Student & Aspiring Data analyst
