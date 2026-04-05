# 🤟 Sign Language Detection using LSTM & MediaPipe

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-00C853?style=for-the-badge&logo=google&logoColor=white)

## 📌 Overview
This project is a real-time **Sign Language Recognition System** that translates hand gestures and body language into text. By leveraging **MediaPipe Holistic** for feature extraction and **LSTM (Long Short-Term Memory)** networks for sequence prediction, the system can understand the context of movements over time, not just static images.

## 🚀 Features
- **Real-time Detection:** High-speed processing for live webcam feed.
- **Holistic Tracking:** Captures hand, face, and pose landmarks for better accuracy.
- **Temporal Analysis:** Uses LSTM to recognize actions that happen over a sequence of frames.
- **Custom Dataset:** Built and trained on a specific set of action-based sign language gestures.

## 🛠️ Tech Stack
- **OpenCV:** For image processing and webcam integration.
- **MediaPipe:** To extract 1662 keypoints from the body.
- **TensorFlow/Keras:** For building and training the LSTM neural network.
- **NumPy & Pandas:** For data manipulation and storage.

## 🏗️ Model Architecture
The model consists of:
1. **Feature Extraction Layer:** MediaPipe Holistic model.
2. **Sequential Layers:** 3 stacked LSTM layers to capture temporal dependencies.
3. **Dense Layers:** Fully connected layers for classification.
4. **Softmax Output:** To predict the probability of each gesture.

## 📸 Demo
*(Add a GIF of your project working here or a screenshot of the interface)*
> `![Demo](link_to_your_gif_or_image.gif)`

## 💻 Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/AhmedZaghl0ul/Sign-Language-Detection-using-LSTM.git](https://github.com/AhmedZaghl0ul/Sign-Language-Detection-using-LSTM.git)
