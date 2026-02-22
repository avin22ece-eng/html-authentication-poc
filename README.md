# html-authentication-poc

# HTML Authentication System (POC)

## 📌 Project Overview

This project is a simple HTML-based Authentication System Proof of Concept (POC).  
It demonstrates a basic authentication flow using only HTML structure and anchor tag navigation.

No CSS and no JavaScript are used in this project.

The goal is to simulate the navigation flow between authentication pages using plain HTML.

---

## 📁 Project Structure

The repository contains the following files:

- login.html
- register.html
- forgot-password.html
- reset-password.html
- dashboard.html
- README.md

---

## 🔄 Page Flow Explanation

### 1. Login Page (login.html)

- Contains fields for Email and Password.
- Login link redirects to dashboard.html.
- Includes navigation links to:
  - Registration page
  - Forgot Password page

Navigation:
Login → Dashboard  
Register → Register Page  
Forgot Password → Forgot Password Page  

---

### 2. Registration Page (register.html)

- Contains fields for:
  - Full Name
  - Email
  - Password
- Register link redirects back to login.html.
- Includes link for existing users to return to Login page.

Navigation:
Register → Login  

---

### 3. Forgot Password Page (forgot-password.html)

- Allows user to enter registered email.
- Submit link redirects to reset-password.html.
- Includes link to go back to Login page.

Navigation:
Submit → Reset Password  
Back → Login  

---

### 4. Reset Password Page (reset-password.html)

- Contains:
  - New Password field
  - Confirm Password field
- Reset link redirects to login.html.

Navigation:
Reset → Login  

---

### 5. Dashboard Page (dashboard.html)

- Displays successful login message.
- Contains Logout link.
- Logout redirects back to login.html.

Navigation:
Logout → Login  

---

## 🛠 Technologies Used

- HTML5
- Anchor Tags for Navigation
- Basic Form Elements

No:
- CSS
- JavaScript
- Backend
- Database

---

## 🎯 Purpose of This Project

This project was created to:

- Understand HTML page structure
- Practice form creation using HTML
- Demonstrate navigation using anchor tags
- Simulate an authentication workflow without backend logic

---

## ▶ How to Run the Project

1. Download or clone the repository.
2. Open login.html in any web browser.
3. Use the links provided to navigate between pages.
4. Verify all redirections work correctly.

No server setup is required.

---

## 📊 Evaluation Criteria Covered

- All 5 required HTML pages created
- Proper anchor tag redirections implemented
- README.md included
- Code pushed to public GitHub repository
- Repository accessible for grading

---

## 👤 Author

Your Name Here

---

## 🔓 Repository Visibility

This repository is public to allow evaluation and grading access.

---
