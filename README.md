# AI Emotion Recognition System

This is an AI-powered web application that detects human emotions from facial expressions using Deep Learning.  
The system utilizes a Convolutional Neural Network (CNN) trained on 48x48 grayscale facial images to classify emotions from live camera input or uploaded video files.

---

## 🚀 Overview

The application provides a secure and interactive platform where users can register, log in, and perform real-time emotion detection. It integrates computer vision with deep learning to deliver accurate emotion predictions through a web-based interface.

---

## 🎯 Features

- 🔐 User Authentication (Sign Up / Login)  
- 🎥 Live Camera Emotion Detection  
- 📤 Video Upload Emotion Analysis  
- 📊 Real-Time Prediction Display  
- 🧠 CNN-Based Deep Learning Model  

---

## 🧠 Model Details

- **Model Type:** Convolutional Neural Network (CNN)  
- **Input Shape:** 48x48 Grayscale Images  
- **Output Classes:**  
  - Angry  
  - Disgust  
  - Fear  
  - Happy  
  - Sad  
  - Surprise  
  - Neutral  
- **Model Format:** `.keras`  
- **Framework:** TensorFlow / Keras  

---

## 🏗️ Tech Stack

### Backend
- Flask  
- Flask-SQLAlchemy  
- Flask-Login  
- Gunicorn  

### AI / Machine Learning
- TensorFlow  
- Keras  
- OpenCV  
- NumPy  

### Database
- SQLite (default configuration)

---

## 📂 Project Structure

```
emotion_app/
│
├── app.py
├── cnn_first_model.keras
├── requirements.txt
├── runtime.txt
├── README.md
│
├── static/
│   ├── uploads/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── live.html
│   └── upload.html
│
└── instance/
    └── database.db
```
