# 🏥 Doctor Appointment Booking System

## 📖 Overview
The **Doctor Appointment Booking System** is a full-stack web application designed to simplify healthcare access for patients, doctors, and administrators.  
It provides an integrated platform for **appointment scheduling, doctor management, medical chatbot interaction, and AI-based CT scan predictions** for lung and pneumonia diseases.

This system brings together **AI, automation, and healthcare accessibility** in one secure and efficient application.

---

## 🚀 Features

### 👨‍⚕️ 1. User Authentication and Dashboard
- Secure user registration and login.
- Patients can view upcoming appointments, history, and daily notifications.
- Admins and doctors have separate dashboards to manage users and appointments.

### 🩺 2. Doctor Search and Booking
- Patients can search doctors by specialization.
- View doctor profiles (experience, consultation fee, ratings, and availability).
- Book appointments by selecting date, time, and visit reason.
- System ensures valid time slot booking and prevents double-booking.

### 📅 3. Appointment Management
- Patients can **view, reschedule, or cancel** appointments.
- Doctors manage daily schedules and availability.
- Patients can leave reviews only after completing appointments.

### 🔔 4. Notification System
- A notification bell alerts users about today’s appointments.
- Clicking the bell displays relevant reminders.

### 🤖 5. AI-Powered Medical Chatbot
- Assists users with health-related questions and appointment guidance.
- Provides general advice, doctor information, and symptom summaries.
- Supports both **text and voice interaction**.

### 🧠 6. Lung and Pneumonia AI Prediction
- Upload chest CT scan images.
- AI model analyzes and predicts signs of pneumonia or lung diseases.
- Displays instant results with a disclaimer (not a substitute for diagnosis).

### 🔐 7. Security and Admin Controls
- Passwords and sensitive data are encrypted.
- Admins manage doctors, patients, and appointments securely.

---

## 🏗️ System Architecture

**Three-tier Architecture:**
1. **Frontend:** Web UI for patients, doctors, and admins.
2. **Backend:** API and business logic for booking and AI inference.
3. **AI Layer:** ML model for pneumonia and lung disease prediction.

---

## 🧩 Modules

| Module Name | Description |
|--------------|-------------|
| User Authentication | Register, login, and secure access control |
| Doctor Management | Manage doctor profiles, schedules, and specializations |
| Appointment Booking | Book, view, reschedule, and cancel appointments |
| Notification System | Alerts and reminders for scheduled appointments |
| AI Chatbot | Assists users with queries using NLP and voice input |
| AI CT Scan Predictor | Detects pneumonia or lung issues using CNN-based models |

---

## 🧠 AI Model Description
The AI feature uses **Convolutional Neural Networks (CNNs)** trained on chest CT scan datasets.  
It predicts possible **lung diseases or pneumonia** by classifying uploaded images.  
Built with:
- TensorFlow / PyTorch
- OpenCV for image preprocessing
- Scikit-learn for evaluation metrics (Accuracy, Precision, Recall, F1-score, ROC curve)

---

## 🛠️ Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Frontend** | HTML, CSS, JavaScript, React / Bootstrap |
| **Backend** | Python (Streamlit / Django) |
| **Database** | mongodb  |
| **AI/ML** | TensorFlow, PyTorch, Scikit-learn |
| **Tools** | VS Code, Git, Streamlit |
| **Security** | JWT Authentication, Password Hashing |

---

## ⚙️ Installation & Setup

### 🖥️ Prerequisites
- Python 3.8+
- Node.js & npm
- MySQL or PostgreSQL
- Git

npm install
npm start
