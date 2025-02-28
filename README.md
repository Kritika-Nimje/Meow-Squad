# 📌 QR Attendance System

🚀 **Automate classroom attendance using QR codes, real-time tracking, and AI-driven analytics.**

## 🌟 Features
✅ **Dynamic QR Code Generation** – Unique QR per session, preventing misuse.  
✅ **Geo-Fencing** – Ensures attendance is marked only within the classroom.  
✅ **Time-Limited QR Codes** – Expires after a set time to prevent late scans.  
✅ **Google Sheets Integration** – Auto-updates attendance records in real time.  
✅ **Face Authentication (AI-Powered)** – Prevents proxy attendance using facial recognition.  
✅ **Admin Dashboard** – View analytics, manage students, and export reports.  
✅ **Duplicate Scan Prevention** – Ensures a QR cannot be scanned multiple times.  
✅ **AI-Based Analytics** – Detects habitual latecomers & absentee trends.  

---

## 🏗️ Tech Stack
**Frontend:** React, Vite ⚡  
**Backend:** Node.js, Express.js 🚀  
**Database:** MongoDB, Supabase 📦  
**ML Integration:** Python (Flask API, DeepFace, OpenCV, Scikit-learn) 🧠  

---

## 🔧 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/qr-attendance.git
cd qr-attendance
```
### 2️⃣ Install Dependencies
```bash
# Backend Setup
cd backend
npm install

# Frontend Setup
cd frontend
npm install
```
### 3️⃣ Set Up Environment Variables
Create a `.env` file for both backend and frontend with the necessary API keys and configurations.

### 4️⃣ Run the Application
```bash
# Start Backend Server
cd backend
npm start

# Start Frontend
cd frontend
npm run dev
```

---

## 📸 System Workflow
1️⃣ **Professor Generates a QR Code** for each lecture.  
2️⃣ **Students Scan QR Code** within the classroom (Geo-Fencing enabled).  
3️⃣ **Face Authentication** verifies the student’s identity.  
4️⃣ **Attendance is Marked** and updated in Google Sheets & the database.  
5️⃣ **Admin Dashboard** displays attendance insights and trends.  

---

## 📊 AI & Machine Learning
🧠 **Face Authentication:** Uses **DeepFace & OpenCV** for student verification.  
📈 **Attendance Analytics:** Machine learning (Scikit-learn) to detect latecomers and absentee patterns.  

---

⭐ **Star this repo if you find it useful!** ⭐
