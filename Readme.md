# 🚨 AI-Powered Real-Time Violence Detection System

## 📌 Overview
The **AI-Powered Real-Time Violence Detection System** is a multi-modal deep learning solution designed to automatically detect violent activities in video streams by analyzing both **visual** and **audio** cues. The system leverages **transformer-based architectures** to deliver accurate and robust real-time surveillance performance.

---

## 🎯 Key Features
- 🔍 Real-time violence detection from video streams  
- 🎥 Visual feature extraction using transformer models  
- 🔊 Audio-based violence recognition  
- 🔗 Multi-modal fusion for synchronized decision-making  
- ⚡ Scalable for surveillance and security applications  

---

## 🧠 Model Architecture

### 1️⃣ Video Processing Module
- **Model:** VideoMAE (Masked Autoencoder for Video)
- **Function:** Extracts spatiotemporal features from video frames
- **Benefit:** Effectively captures motion and temporal dependencies

### 2️⃣ Audio Processing Module
- **Model:** Audio Spectrogram Transformer (AST)
- **Function:** Classifies aggressive and violent audio signals
- **Benefit:** Uses attention mechanisms over spectrograms for high accuracy

### 3️⃣ Multi-Modal Fusion
- Combines audio and video predictions
- Uses synchronized confidence-based decision making
- Reduces false positives compared to single-modal systems

---

## 🛠️ Technologies Used
- **Programming Language:** Python  
- **Deep Learning Frameworks:** PyTorch, TensorFlow  
- **Models:** VideoMAE, Audio Spectrogram Transformer (AST)  
- **Development Environment:** Google Colab  
- **Libraries:** OpenCV, NumPy, Librosa  

---

## ⚙️ System Workflow
1. Capture real-time video input  
2. Extract video frames and audio stream  
3. Process video using VideoMAE  
4. Process audio using AST  
5. Fuse predictions from both modalities  
6. Output final violence detection result  

---

## 📊 Results
- Achieved robust performance across different environments  
- Multi-modal fusion improved accuracy and reduced false positives  
- Suitable for real-time surveillance applications  

---

## 🚀 Future Scope
- Integration with CCTV surveillance systems  
- Deployment on edge devices (Jetson Nano, Raspberry Pi)  
- Alert system with real-time notifications  
- Web dashboard for monitoring and analytics  

---
👤 Author

Sri Varshitha Namburu
Final-Year Computer Science Student
Focus Areas: Artificial Intelligence, Deep Learning, Full Stack Development
