# 😃 Face Emotion Recognition 

## 📌 Overview
This project implements a Face Emotion Detection system using a pre-trained deep learning model. It captures an image using a webcam in Google Colab and predicts human emotions from facial expressions.

## 🚀 Features
- Capture image directly using webcam (Colab)
- Detect faces using OpenCV Haar Cascade
- Predict emotions using a trained CNN model
- Supports multiple emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, Neutral

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Google Colab

## ⚙️ Installation
Run the following commands in Colab:
pip install opencv-python-headless  
pip install tensorflow

## ▶️ How It Works
1. Load the pre-trained model (emotion_detection_model.h5)  
2. Capture an image using webcam  
3. Convert image to grayscale  
4. Detect faces using Haar Cascade  
5. Extract face region (ROI)  
6. Resize and normalize image  
7. Predict emotion using CNN model  
8. Display result with bounding box  

## 📂 Required Files
- emotion_detection_model.h5 → Trained model file  
- Haar Cascade (comes with OpenCV)

## 📊 Output
- Displays captured image  
- Shows bounding box around face  
- Displays predicted emotion label  

## 🎯 Use Cases
- Emotion-aware AI systems  
- Human-computer interaction  
- Basic mental state analysis  
- AI learning projects  

## 🔮 Future Improvements
- Real-time video emotion detection  
- Deploy as web app (Streamlit/Flask)  
- Improve model accuracy  
- Use advanced models (ResNet, VGG)  

