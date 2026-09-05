# TutorPulse
professional, clear, and highlights real time parent &amp; tutor feedback
# TutorPulse 🎓

> A role-based progress tracking platform designed to bridge the communication gap between private tutors, parents, and platform administrators.

---

## 📌 Problem & Motivation

As a tutor, communicating a student’s ongoing performance through scattered chat messages and emails often leads to lost context and poor tracking over time. **TutorPulse** solves this by providing a structured portal where teachers log recurring evaluations, parents track real-time visual progress metrics for their children, and administrators manage platform assignments cleanly.

---

## 🚀 Key Features

* **Role-Based Access Control (RBAC)**: Distinct permissions for `Admin`, `Teacher`, and `Parent` roles.
* **Parent Dashboard**: Visual progress reports and historical metrics for assigned children.
* **Teacher Evaluations**: Form-driven entry for academic performance, notes, and progress logs.
* **Admin Controls**: Roster management, student-to-teacher assignment, and system metrics.
* **Automated Pipeline**: Integrated CI/CD via GitHub Actions for linting, testing, and deployment.

---

## 🛠 Tech Stack & Architecture

### **System Architecture**
[ React Frontend (Tailwind CSS) ]
│  (REST API / JWT)
▼
[ Node.js + Express Backend ]
│  (Mongoose ORM)
▼
[ MongoDB Database ]


### **Core Technologies**
* **Frontend**: React.js, Tailwind CSS, Axios, Recharts (Data Visualization)
* **Backend**: Node.js, Express.js, JWT Authentication, bcrypt
* **Database**: MongoDB (Mongoose ORM)
* **DevOps / CI/CD**: Docker (Local DB), GitHub Actions, Vercel / Render

---

## ⚙️ Environment & Local Setup

### **Prerequisites**
* Node.js (v18+)
* MongoDB local instance or Docker
* npm / yarn
