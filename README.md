# ISL Translation & Voice-to-Sign Application

## 📌 Overview

The **ISL Translation & Voice-to-Sign Application** is a communication tool designed to reduce the communication gap between the hearing-impaired community and the general public in India.

The system focuses on **Indian Sign Language (ISL)** and provides two main translation modes:

* **Sign-to-Text Translator** – Uses computer vision to interpret hand gestures in real time.
* **Voice-to-Sign Module** – Converts spoken language into sequential sign language videos.

This allows smoother communication between people who use sign language and those who rely on speech.

---

## ✨ Features

### 🔹 Sign-to-Text Translation

Real-time gesture recognition using camera input and hand landmark tracking.

### 🔹 Distance & Mirror Invariance

Gesture recognition works correctly regardless of:

* Distance from the camera
* Left-hand or right-hand usage

### 🔹 Multi-Word Voice-to-Sign

Converts full spoken sentences into a sequence of ISL videos with smooth transitions.

### 🔹 Admin Dashboard

Authorized users can:

* Record new sign gestures
* Upload gesture videos
* Instantly train the AI model with new gestures

### 🔹 Offline Database

The application uses a **local SQLite database** to store:

* Hand landmark "signatures"
* Video paths

This enables **fast and fully offline operation**.

### 🔹 Replay & Word Selection

Interactive UI allows users to:

* Replay individual words
* Replay entire sentences in sign language

---

## 🛠 Technologies Used

* **Java & XML** – Core Android application development
* **MediaPipe** – Hand landmark detection (21 key points)
* **SQLite** – Local database for gesture signatures and video storage
* **Android CameraX** – Camera lifecycle and video processing
* **Google Speech-to-Text API** – Voice recognition and sentence parsing

---

## 📱 Application Modules

1. Sign Gesture Recognition System
2. Voice-to-Sign Translation System
3. Admin Gesture Management Dashboard
4. Local Gesture Database

---

## 👨‍💻 Developer

**Anandhakrishnan S**
B.Tech Computer Science Engineering
KTU University (Expected Graduation: 2026)

GitHub: https://github.com/anandhakrishh

---

## 📄 License

This project is developed for educational and research purposes.
