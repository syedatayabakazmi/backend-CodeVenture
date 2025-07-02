# CodeVenture – Integrated Learning and Job Portal

## Project Overview

**CodeVenture** is a full-stack platform designed to empower students with structured learning and real-world career opportunities. The system combines e-learning with a job portal to bridge the gap between academics and industry.

## Problem Statement

Students often lack:
- Clear guidance on learning paths
- Access to practical coding tasks
- A centralized portal to explore jobs/internships
- Mentor support for career growth

## Solution

CodeVenture solves this by offering:
-  Career-based learning paths (courses, lectures, quizzes, assignments, lab tasks)
-  Mentor-student collaboration based on tech interests
-  A job board with dedicated panels for students, mentors, and companies
-  Admin tools to manage users, companies, courses, and jobs
-  Secure login and role-based access control

## Architecture Overview

CodeVenture follows a **modular monolith architecture** using:
- **Backend**: Java + Spring Boot REST APIs
- **Frontend**: AngularJS with Angular Material & Bootstrap UI
- **Database**: MySQL (structured schema for users, courses, jobs, quizzes)
- **Security**: Role-based access (student, mentor, company, admin)

## Core Features

- **User Roles**: Student, Mentor, Company, Admin
- **Courses**: Lectures, Quizzes, Assignments, Labs
- **Mentor Panel**: Approve students, assign and grade marks for assignment and lab tasks
- **Job Portal**: Job listings, student applications, recruiter reviews
- **Admin Dashboard**: Manage users, roles, courses, company approvals

## UI Highlights

- Responsive and accessible layout with **AngularJS + Bootstrap + Angular Material**
- Clean separation of student, mentor, and company interfaces
- Dashboards for each role
- Toasts, dialogs, and tables for a polished UX

## Technologies Used

| Layer        | Tools & Frameworks                       |
|--------------|------------------------------------------|
| Backend      | Java 17, Spring Boot, REST APIs          |
| Frontend     | AngularJS, TypeScript, HTML, CSS         |
| UI Styling   | Bootstrap, Angular Material              |
| Database     | MySQL                                    |
| Security     | Spring Security (role-based access)      |
| Dev Tools    | Postman, Git, VS Code, Spring tool suite |          |
