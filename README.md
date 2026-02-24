# 🚀 Jotish Intern Assignment – React Application

This project is a 4-screen ReactJS application built as part of an internship assignment.  
It demonstrates authentication logic, API integration, data visualization, map integration, and webcam functionality.

---

## 📌 Features

### 🔐 1. Login Page
- Static authentication
- Username: `testuser`
- Password: `Test123`
- Redirects to List page after successful login

### 📋 2. List Page
- Fetches job data from REST API using Axios
- Displays dynamic list of job titles
- Clickable cards navigate to Details page

### 📊 3. Details Page
- Displays selected job information:
  - Job Title
  - City
  - Salary
  - Date
- Salary visualized using **Recharts Bar Chart**
- City displayed using embedded **Google Maps**
- Back button for navigation
- Capture Photo button

### 📸 4. Photo Capture Page
- Integrated webcam using `react-webcam`
- Capture and preview image
- Retake functionality

---

## 🛠️ Technologies Used

- ReactJS
- React Router DOM
- Axios
- Recharts (for charts)
- React Webcam
- Google Maps (iframe embed)
- CSS (custom styling)

---

## 📂 Project Structure
