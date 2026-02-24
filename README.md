# 📚 Study Planner App

A role-based Android mobile application developed using **Kotlin** in **Android Studio**, designed to help teachers and students manage academic tasks, assignments, and schedules efficiently.

The application provides separate login access for **Teachers** and **Students**, ensuring structured academic planning and task management.


## 🚀 Project Overview

The Study Planner App aims to digitalize academic task management by allowing:

* Teachers to create and manage assignments
* Students to view and track their academic tasks
* Both users to manage their personal academic schedule

The system ensures reliable performance using structured architecture and local database storage.

---

## 🔐 User Roles

### 👩‍🏫 Teacher

* Login as Teacher
* Create assignments
* Set deadlines
* View student submissions
* Manage personal profile

### 👨‍🎓 Student

* Login as Student
* View assignments
* Track deadlines
* Submit tasks
* Manage personal profile

---

## 📱 Application Pages (5 Main Screens)

1️⃣ **Login / Register Page**

* Email & Password login
* Role selection (Teacher / Student)

2️⃣ **Teacher Dashboard**

* View created assignments
* Add new assignment
* View submission status

3️⃣ **Student Dashboard**

* View all assignments
* Check deadlines
* Submit assignment

4️⃣ **Assignment Details Page**

* Assignment description
* Deadline
* Submission option (Student)
* View submissions (Teacher)

5️⃣ **Profile Page**

* View user information
* Update profile
* Logout

---

## 🏗️ Architecture

The application follows **MVVM (Model-View-ViewModel)** architecture for clean code structure and scalability.

### Layers:

* UI Layer (Jetpack Compose)
* ViewModel Layer
* Repository Layer
* Room Database Layer

This ensures:

* Separation of concerns
* Better maintainability
* Reliable performance

---

## 🛠️ Tech Stack

* **Programming Language:** Kotlin
* **IDE:** Android Studio
* **UI Framework:** Jetpack Compose
* **Architecture Pattern:** MVVM
* **Database:** Room (SQLite)
* **Asynchronous Programming:** Coroutines

---

## 🗄️ Database Structure

### 1️⃣ Users Table

* userId
* name
* email
* password
* role (Teacher / Student)

### 2️⃣ Assignments Table

* assignmentId
* title
* description
* deadline
* teacherId

### 3️⃣ Submissions Table

* submissionId
* assignmentId
* studentId
* submissionDate

---

## 🎯 Objectives

* To develop a role-based academic planning system
* To implement authentication and authorization in Android
* To apply MVVM architecture in a real-world mobile application
* To build a reliable and maintainable mobile system

---

## 🧪 Testing

The application has been tested for:

* User login validation
* Role-based access control
* Assignment creation and retrieval
* Data storage and retrieval using Room
* Proper navigation between screens

---

## 🔮 Future Enhancements

* Push notifications for deadlines
* Calendar integration
* Attendance tracking
* Grade management system
* Firebase cloud integration
* Dark mode support

---



## 👨‍💻 Developer

* Your Name : Pawan Adhikari
* Course Name : Developing Mobile Application
* Semester : Level 6 Semester 2
* Institution Name : The British College
