# 🎓 Student Portal System

A clean, responsive, and functional **Student Management Web Application** developed for the Web Engineering Lab (**CYS-463L**). This project demonstrates core concepts of front-end development, session management, and interactive UI design.

---

## 🚀 Project Overview
The **Student Portal** is a multi-page web application allowing students to register, log in, manage course enrollments, and provide feedback. It features a modern design language using **Bootstrap 5**, custom CSS, and **JavaScript** for logic and data persistence.

## 🧠 Technical Breakdown
This project uses a "Serverless" front-end approach, relying on browser storage to mimic a real database:

* **Session Persistence:** Uses `sessionStorage` to keep the user logged in across pages. When you register, your name, email, and password are saved.
* **Authentication Logic:** During login, JavaScript retrieves stored credentials (`storedEmail` and `storedPass`) and compares them against input to grant access.
* **Dynamic Course Handling:** In `courses.html`, a JavaScript array tracks clicks in real-time. The "Enroll Now" button only activates once a subject is chosen.
* **Live UI Updates:** The feedback page features a dynamic star-rating display that changes instantly based on user selection.
* **Real-time Synchronization:** The dashboard includes a "Sync Clock" feature to capture the exact time of the user's last activity.

## 🛠️ Built With
* **HTML5:** Semantic structure for all portal pages.
* **CSS3:** Custom styling featuring a "Glassmorphism" effect and University of Wah branding.
* **Bootstrap 5:** For responsive grids, tables, and navigation.
* **JavaScript (ES6):** Handles form validation, DOM manipulation, and session logic.

## 📂 Project Structure
1.  **`index.html` (Home):** A high-level overview of the portal features.
2.  **`registration.html` (Auth):** Dual-purpose authentication for signing up and logging in.
3.  **`dashboard.html` (Main):** Displays student stats, enrollment status, and profile info.
4.  **`courses.html` (Enrollment):** Interactive list of subjects for the Spring 2026 semester.
5.  **`feedback.html` (Survey):** A validation-protected form for student experience ratings.

## 📖 How to Use
1.  **Register:** Go to the registration page and create an account.
2.  **Login:** Use your credentials to access the Dashboard.
3.  **Enroll:** Navigate to "Manage Courses," pick your subjects, and click "Enroll Now".
4.  **Feedback:** Visit the feedback page to submit a rating and see the UI update.

## 👨‍🏫 Supervision & Author
* **Author/ Student:** Rubaiqa Pervez
* **Supervisor:** **Sir Qadeer Yaseen**
* **Course:** Web Engineering Lab (CYS-463L)
* **Institution:** University of Wah

---
*Developed as part of the Web Engineering curriculum at the University of Wah.*
