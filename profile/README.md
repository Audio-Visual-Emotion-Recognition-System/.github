# 🎭 Aurora Core: Audio-Visual Emotion Recognition System

[Live Demo](https://aurora-core.vercel.app/about)

## 📘 Overview

Aurora Core is a real-time emotion recognition system that leverages both facial expressions (visual data) and vocal cues (audio data) to accurately detect human emotions. By integrating these two modalities, the system enhances the precision of emotion classification, making it suitable for applications in mental health monitoring, security, and human-computer interaction.

---

## 🧠 Problem Statement

The objective is to develop a system capable of recognizing human emotions in real-time by analyzing facial expressions and voice tone. By fusing visual and audio data, the system aims to improve the accuracy of emotion detection and classification.

---

## 🔑 Key Features

### 🎥 Visual Emotion Recognition

- **Real-Time Face Detection**: Utilizes a connected camera to detect faces in real-time.
- **Facial Expression Classification**: Categorizes facial expressions into emotions such as happy, sad, angry, and neutral using pre-trained or custom deep learning models.

### 🎙️ Audio Emotion Recognition

- **Audio Capture**: Records audio input through a microphone.
- **Feature Extraction**: Analyzes features like pitch, tone, and intensity to classify emotions.

### 🔗 Multimodal Fusion

- **Data Integration**: Combines visual and audio data using fusion algorithms to enhance emotion recognition accuracy.

### 📤 Output

- **Emotion Display**: Shows the detected emotion on a screen or sends it to a mobile application.
- **Real-Time Feedback**: Provides immediate feedback through visual or audio cues.

---

## 🛠️ Technology Stack

### 💻 Programming Languages

- **Python**: Primary language for system development.
- **C/C++**: Used for embedded system optimization.

### 📚 Libraries and Frameworks

- **Computer Vision**: OpenCV, MediaPipe, Dlib
- **Audio Processing**: Librosa, PyAudio, SpeechRecognition
- **Machine Learning**: TensorFlow, Keras, PyTorch
- **Data Fusion**: NumPy, Pandas, Scikit-learn

### 🧰 Hardware

- **Embedded Devices**: Raspberry Pi 4 or NVIDIA Jetson Nano for deployment.
- **Peripherals**:
  - Camera Module (e.g., Pi Camera or USB webcam)
  - Microphone (USB or built-in)
  - Optional Display for visualization

### 📊 Datasets

- **Visual**:
  - FER-2013 (Facial Expression Recognition)
  - CK+ (Extended Cohn-Kanade)
- **Audio**:
  - RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
  - CREMA-D (Crowd-Sourced Emotional Multimodal Actors Dataset)

---

## 🔬 Areas of Exploration

### 🌐 Embedded Machine Learning Device Networking

- Investigate communication between multiple embedded devices (e.g., Raspberry Pi or Jetson Nano) to create a collaborative network for enhanced emotion recognition and processing.

### 🧠 Machine Learning on Edge Devices

- Deploy machine learning models directly on edge devices to reduce reliance on centralized systems.
- Optimize models for efficient performance on low-resource hardware while maintaining real-time capabilities.

### 🧹 Preprocessing on Embedded Devices

- Implement data preprocessing on embedded devices using machine learning techniques.
- Transmit preprocessed data to a central, high-capacity system for further analysis and decision-making.

---

## 🚀 Potential Applications

- **Suspicious Activity Detection**: Monitor emotional states to identify abnormal or suspicious behavior in security-sensitive environments.
- **Mental Health Monitoring**: Provide real-time emotional feedback to assist in tracking and managing mental health conditions.

---

Aurora Core exemplifies the integration of embedded systems, machine learning, and multimodal data fusion to create an effective and efficient emotion recognition system suitable for real-world applications.
