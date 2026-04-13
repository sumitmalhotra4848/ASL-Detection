# 🤟 ASL Detection System

## 📌 Overview
The ASL Detection System is a computer vision-based application that recognizes American Sign Language (ASL) hand gestures and converts them into text and speech in real time. The system leverages deep learning and transfer learning techniques to accurately classify hand gestures from live webcam input.

---

## 🚀 Features
- 🤖 Real-time ASL gesture recognition using webcam  
- 🧠 Deep learning model based on MobileNetV2  
- 🔊 Text-to-speech conversion for detected gestures  
- 📊 Data augmentation for improved model performance  
- ⚡ Near real-time prediction with optimized inference  

---

## 🧠 How It Works
- Dataset of ASL hand gesture images is loaded using KaggleHub  
- Images are preprocessed and augmented using ImageDataGenerator  
- Transfer learning with MobileNetV2 extracts visual features  
- A custom classification head predicts gesture classes  
- Predictions are displayed in real time and converted to speech  

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- KaggleHub  

---

## 📂 Dataset
Dataset used:  
**asl-hand-landmark-and-gesture-dataset** (Kaggle)

---

## ⚙️ Installation

```bash
pip install tensorflow opencv-python numpy kagglehub pyttsx3
