# Classroom Attention Detection System

## 📌 Project Overview
The **Classroom Attention Detection System** is a smart AI-based application designed to analyze student attention levels in a classroom environment using computer vision and deep learning.

The system captures real-time images through a webcam and classifies student behavior using an **Azure Custom Vision** trained model. Based on the prediction, the system identifies whether students are **Focused**, **Looking Away**, or **Sleeping**.

---

## 🎯 Objectives
- To automatically monitor student attention in classrooms
- To classify student behavior using image-based deep learning
- To assist teachers in understanding classroom engagement
- To maintain attendance records based on attention analysis

---

## 🛠️ Technologies Used
- **Python**
- **Streamlit** (Frontend UI)
- **OpenCV** (Image capture)
- **Azure Custom Vision** (Image classification)
- **REST API**
- **CSV File Handling**

---

## 🧠 Model Details
- Platform: **Azure Custom Vision**
- Project Type: **Image Classification**
- Training Data: Classroom images
- Classes:
  - Focused
  - Looking Away
  - Sleeping
- Deployment: Cloud-based prediction API

---

## ⚙️ System Workflow
1. Webcam captures a classroom image
2. Image is sent to Azure Custom Vision Prediction API
3. API returns class probabilities
4. Highest probability class is selected
5. Attention level is displayed on the UI
6. Attendance is stored in a CSV file

---

## 📊 Output
- Displays student attention level with confidence score
- Stores attendance data with timestamp
- Maintains student profile information

---

## 📁 Data Storage
- `attendance.csv` – Stores attention-based attendance records
- `students.csv` – Stores student profile information

---

## 🔐 Security & Privacy
- API keys are kept private
- No sensitive student data is shared publicly
- Local CSV-based storage used for demonstration

---

## 🚀 Future Scope
- Real-time video stream analysis
- Face recognition for individual student tracking
- Database integration (MySQL / Firebase)
- Dashboard analytics for teachers
- Mobile and cloud deployment

---

## 📚 Use Cases
- Smart classrooms
- Online learning engagement monitoring
- Educational analytics platforms
- Teacher assistance systems
