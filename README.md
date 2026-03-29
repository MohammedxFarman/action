# action
# Sign Language / Action Detection System

A real-time computer vision system that detects and classifies human actions / sign language gestures using deep learning.

## 🚀 Overview

This project uses a deep learning model to recognize gestures/actions from video input in real time. It combines computer vision techniques with sequence modeling to interpret movements and convert them into meaningful outputs.

Built as an end-to-end system including data collection, preprocessing, model training, and live prediction.

---

## 🧠 Features

- Real-time action / gesture detection via webcam
- Deep learning model trained on custom dataset
- Sequence-based prediction (captures temporal patterns)
- Scalable pipeline for adding new gestures
- End-to-end implementation (data → model → prediction)

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Mediapipe (for keypoint extraction)

---

## 📂 Project Structure
├── Action Detection Tutorial.ipynb # Model training notebook
├── Action Detection Refined.ipynb # Improved model + experiments
├── action.h5 # Trained model file
├── data/ # Dataset (not included in repo)
├── utils/ # Helper functions
└── README.md

---

## ⚙️ How It Works

1. Capture video input using webcam
2. Extract keypoints using Mediapipe
3. Convert frames into sequences
4. Feed sequences into trained model
5. Predict action/gesture in real-time

---

## ▶️ Installation

```bash
git clone https://github.com/yourusername/sign-language-recognition.git
cd sign-language-recognition
pip install -r requirements.txt

python test.py 
