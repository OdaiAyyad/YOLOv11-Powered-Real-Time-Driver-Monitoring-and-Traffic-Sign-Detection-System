# YOLOv11-Powered Real-Time Driver Monitoring and Traffic Sign Detection System 🚦🚗

## Overview
This project presents a real-time AI-powered traffic safety system built using YOLOv11. It performs driver behavior monitoring and traffic sign detection, aiming to reduce accidents and improve road safety. The system also includes Text-to-Speech (TTS) feedback, enabling real-time voice alerts to enhance driver responsiveness.

## 🔍 Key Features
🧠 YOLOv11-Based Detection
Leveraged YOLOv11 for accurate object detection.

Achieved excellent performance across both the Traffic Sign and Driver Monitoring datasets.

## 📦 Datasets
### Traffic Sign Dataset

~4,977 images

Includes Stop signs, Speed Limits, Red Lights, and more.

### Driver Monitoring Dataset

~9,884 images

Includes behaviors like drowsiness, phone usage, and more.

## 🎯 Performance
Trained on over 14,000 images in total.

Achieved high precision, recall, and mAP scores.

Real-time testing on webcam using Jupyter Notebook.

## 💬 Text-to-Speech (TTS)
Integrated pyttsx3 for live voice alerts.

The system vocally warns about detected objects like:

"Red light detected."

"Attention: Stop sign ahead."

"Speed limit 100 ahead."

## ⚙️ Real-Time Implementation
Real-time webcam detection via Jupyter Notebook (see webcam_test.py).

Optimized for smooth detection with OpenCV and Ultralytics YOLO.

## 🔋 Training on Google Colab (Free TPU)
Trained using Google Colab TPU (for free) — no Pro subscription required.

Full training pipeline included in the notebook.

## 🎥 Demo Videos
Here are the results of our real-time testing:

▶️ Traffic Sign Detection Test

▶️ Driver Monitoring Detection Test

Click the links or open them directly from your browser to watch the full demos.


## 🚀 Getting Started
### 🧬 Clone the Repository
git clone https://github.com/your-username/YOLOv11-Driver-Monitoring-TSD.git
cd YOLOv11-Driver-Monitoring-TSD

### 📦 Install Dependencies
Install required libraries (ideally inside a virtual environment):

bash
Copy
Edit
pip install ultralytics opencv-python pyttsx3

### 🧪 Run Real-Time Detection (Webcam + TTS)
bash
Copy
Edit
python webcam_test.py
