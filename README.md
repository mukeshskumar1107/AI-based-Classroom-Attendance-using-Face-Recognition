# AI-based Classroom Attendance using Face Recognition

## 📌 Project Overview

Traditional classroom attendance methods consume valuable teaching time and are prone to human errors. This project uses Artificial Intelligence and Face Recognition technology to automate the attendance process.

The system captures faces from a classroom image or live video stream, identifies registered students using face recognition algorithms, and stores attendance records in a database.

---

## 🎯 Objective

To build a smart attendance system that:

- Automatically marks attendance using face recognition
- Reduces manual roll-call time
- Improves attendance accuracy
- Maintains digital attendance records
- Provides an easy-to-use dashboard for teachers

---

## ✨ Features

- 👤 Student face registration
- 📷 Attendance using webcam/live camera
- 🖼️ Attendance from uploaded classroom images
- 🧠 AI-based face detection and recognition
- 📋 Automatic Present/Absent marking
- 💾 Attendance database storage
- 🌐 Web dashboard for teachers
- 📊 Attendance report generation
- 📁 Export attendance records

---

## 🛠️ Technologies Used

### Frontend
- HTML
- CSS
- JavaScript
- Bootstrap

### Backend
- Python
- Flask

### AI / Machine Learning
- OpenCV
- Face Recognition Library
- NumPy

### Database
- SQLite / MySQL

---

## 🏗️ System Architecture

1. Capture image/video from camera
2. Detect faces using OpenCV
3. Extract facial features
4. Compare with stored student dataset
5. Identify matched students
6. Mark attendance automatically
7. Store attendance logs in database
8. Display results on teacher dashboard

---

## 📂 Project Structure

```bash
AI-Classroom-Attendance/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── dashboard.html
│   └── attendance.html
│
├── dataset/
│   └── student_images/
│
├── attendance/
│   └── attendance.csv
│
├── app.py
├── face_recognition_model.py
├── database.db
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/AI-Classroom-Attendance.git
cd AI-Classroom-Attendance
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

#### Windows
```bash
venv\Scripts\activate
```

#### Linux / Mac
```bash
source venv/bin/activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000/
```

---

## 📸 How It Works

### Student Registration
- Add student name and ID
- Capture/store student face images
- Save facial data into dataset

### Attendance Process
- Start camera or upload classroom image
- System detects and recognizes faces
- Attendance marked automatically
- Results stored in database

---

## 📊 Output

The system generates:

- Present student list
- Absent student list
- Date and time of attendance
- Attendance reports in CSV format

---

## 🧠 AI Concepts Used

- Face Detection
- Face Encoding
- Face Recognition
- Image Processing
- Machine Learning

---

## 🔒 Advantages

- Saves classroom time
- Contactless attendance system
- Reduces proxy attendance
- Accurate and fast
- Easy attendance tracking

---

## 🚀 Future Enhancements

- Real-time cloud database integration
- Mobile application support
- Multiple classroom support
- Mask face recognition
- SMS/Email notification system
- AI analytics dashboard

---

## 📷 Screenshots

_Add project screenshots here_

```bash
screenshots/
```

---

## 🤝 Contributors

- Your Name
- Team Members

---

## 📄 License

This project is developed for educational purposes.

---

## ⭐ GitHub Repository

If you like this project, give it a ⭐ on GitHub!
