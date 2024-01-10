# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose
The purpose of this document is to provide a comprehensive overview of the requirements for the Learning Platform, a Java-based application with a MySQL database, aimed at facilitating online learning.

### 1.2 Scope
The Learning Platform allows students to enroll in courses, watch instructional videos, attempt quizzes, and receive automatic grading. Teachers can manage courses, add/update/delete content, and monitor students' progress.

## 2. System Overview

### 2.1 System Description
The Learning Platform is a web-based application developed in Java, leveraging a MySQL database for data storage. The system comprises two user roles: Student and Teacher, each with specific functionalities.

## 3. Functional Requirements

### 3.1 User Roles

#### 3.1.1 Student
- Can sign in as a student.
- Enroll in available courses.
- Access course materials, including YouTube video links.
- Attempt quizzes associated with enrolled courses.
- View automatic quiz grading.

#### 3.1.2 Teacher
- Can sign in as a teacher.
- Add, delete, and update courses.
- Manage course content, including adding/deleting/modifying quiz questions.
- View students' progress in enrolled courses.

### 3.2 Authentication
- Users must choose between the Student and Teacher roles during login.

### 3.3 Course Management
- Teachers can add, delete, and update courses.
- Teachers can add, delete, and modify course content, including YouTube video links.

### 3.4 Quiz Management
- Teachers can add, delete, and modify quiz questions.
- Students can attempt quizzes associated with their enrolled courses.
- Automatic grading of quizzes.

### 3.5 Progress Tracking
- Teachers can view students' progress in enrolled courses.

## 4. Non-Functional Requirements

### 4.1 Performance
- The system should handle concurrent user interactions efficiently.
- Response times for user actions should be within acceptable limits.

### 4.2 Security
- User authentication and authorization mechanisms should be secure.
- Data integrity and confidentiality should be maintained.

## 5. User Interface

### 5.1 Login Page
- Users must select either Student or Teacher during login.

### 5.2 Student Dashboard
- Displays enrolled courses and available actions.

### 5.3 Teacher Dashboard
- Provides options for course and content management.

## 6. Dependencies
- The application relies on Java for backend development and a MySQL database for data storage.

## 7. Conclusion
This Software Requirements Specification outlines the essential features and functionalities of the Learning Platform. Future development and improvements should align with the outlined requirements.
