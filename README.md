# 🧠 Sign Language Detector 🤟 (Real-time using Mediapipe + CNN)

A real-time Sign Language Detection web application built using **Python**, **Mediapipe**, **OpenCV**, and **CNN (Keras/TensorFlow)**. This project detects hand gestures via webcam and classifies them into corresponding ASL (American Sign Language) alphabets.

---

## 🔧 Tech Stack

- 🐍 Python
- 📹 OpenCV
- ✋ MediaPipe (Hand Landmarks)
- 🤖 TensorFlow + Keras (CNN Model)
- 🧠 NumPy, Pandas
- 📊 Matplotlib (for visualization)

---

## 📦 Features

- ✅ Real-time webcam input for hand gesture detection
- ✅ 21-point hand landmark detection via MediaPipe
- ✅ CNN trained on gesture keypoints to recognize ASL alphabets
- ✅ Instant letter prediction shown on-screen
- ✅ Smooth UI using OpenCV window display

---

## 📁 Project Structure

```bash
sign_language_detector/
│
├── data_collection/           # Collect gesture data from webcam
│   └── collect_data.py
│
├── model_training/            # Train CNN on keypoints
│   ├── train_model.py
│   └── sign_model.h5          # Trained model
│
├── detection_app/             # Run real-time detection
│   └── detect_sign.py
│
├── utils/                     # Helper files (keypoint extraction, plotting)
│
├── requirements.txt
└── README.md

