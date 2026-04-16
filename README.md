**Face Recognition System Using Deep Learning**

🎯 Objective

Build a system to detect and recognize human faces from images or live video using Computer Vision and Deep Learning.

📝 Overview

This project implements a face recognition system that:

Detects faces using OpenCV
Extracts features using CNN
Recognizes known individuals in real time

🧠 Problem Statement

Manual identification is slow and unreliable. This project provides an automated, real-time face recognition solution.

📊 Dataset

Image dataset organized by person
dataset/
│── person1/
│── person2/

⚙️ Tech Stack

Python
OpenCV
TensorFlow / Keras
NumPy, Matplotlib

🧩 Models Used

Haar Cascade (Face Detection)
CNN (Face Recognition)

🏗️ Workflow

Input → Face Detection → Preprocessing → CNN → Classification → Output

🧪 Preprocessing

Resize (100×100)
Normalize pixels
Label encoding

🔮 Future Work

Improve accuracy (FaceNet, ResNet)
Real-time deployment
Attendance system integration
