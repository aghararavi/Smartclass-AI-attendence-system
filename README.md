# 🎓 SmartClass – AI Attendance Management System

An AI-powered attendance management system that automates classroom attendance using **Face Recognition**, **Voice Recognition**, and **QR Code-based Enrollment**. The system provides separate dashboards for teachers and students with secure authentication, cloud database integration, and real-time attendance tracking.

---

## 🚀 Live Demo

### 🌐 Frontend (Vercel)
https://smartclass-ai-attendance-system.vercel.app/

### 🤖 Backend (Streamlit)
https://smartclass-mai.streamlit.app/

---

## 📌 Features

### 👨‍🏫 Teacher Module
- Teacher Registration & Login
- Create and Manage Subjects
- Generate QR Code & Join Link
- Face Enrollment for Students
- Voice Enrollment
- Mark Attendance
- View Attendance Records
- Export Attendance Reports

### 👨‍🎓 Student Module
- Join Subject using QR Code
- Face Registration
- Voice Registration
- Secure Attendance Submission
- Attendance Status Tracking

### 🤖 AI Features
- Face Recognition using dlib & librosa
- Voice Recognition using Librosa
- QR Code-based Class Joining
- AI-powered Attendance Verification

---

# 🛠 Tech Stack

## Frontend
- HTML5
- CSS3
- JavaScript
- Vercel

## Backend
- Python
- Streamlit

## AI & Machine Learning
- dlib
- Resemblyzer
- Librosa
- NumPy

## Database
- Supabase (PostgreSQL)

---

# 📂 Project Structure

```
SmartClass-AI-Attendance-System
│
├── backend
│   ├── app.py
│   ├── requirements.txt
│   ├── src
│   └── .streamlit
│
├── Frontend
│   ├── templates
│   ├── static
│   ├── app.py
│   └── vercel.json
│
└── README.md
```

---

# 🧠 System Workflow

Teacher Login

↓

Create Subject

↓

Generate QR Code / Join Link

↓

Student Joins Class

↓

Face & Voice Enrollment

↓

AI Attendance Verification

↓

Attendance Stored in Supabase

↓

Teacher Views Reports

---

# 🔒 Authentication

- Role-Based Login
- Teacher Authentication
- Student Authentication
- Session Management using Streamlit Session State
- Secure Cloud Database using Supabase

---

# 📊 Database

Supabase (PostgreSQL)

Stores

- Teachers
- Students
- Subjects
- Attendance Records
- Face Embeddings
- Voice Features

---

# 🚀 Deployment

Frontend

- Vercel

Backend

- Streamlit Community Cloud

Database

- Supabase

