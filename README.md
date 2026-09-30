# 🎙️ Emotion Recognition from Speech

[![Live Demo](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://emotion-recognition-from-speech-xgdvrdhsvxeuapufeajbef.streamlit.app/)

## 🌐 Live Demo

🚀 **Try the project online:**

👉 https://emotion-recognition-from-speech-xgdvrdhsvxeuapufeajbef.streamlit.app/

---

## 📌 Project Overview

Emotion Recognition from Speech is a Machine Learning and Deep Learning project that analyzes human speech and predicts the emotion expressed in the audio.

The system extracts **MFCC (Mel-Frequency Cepstral Coefficient)** features from speech audio and uses a **Convolutional Neural Network (CNN)** to classify the speech into different emotional categories.

The project also includes a **Streamlit web application** where users can upload a WAV audio file and receive the predicted emotion.

---

## 🎯 Objective

The main objective of this project is to develop a speech emotion recognition system using Machine Learning and Deep Learning techniques.

The model can classify speech into the following emotions:

- 😠 Angry
- 😌 Calm
- 🤢 Disgust
- 😨 Fearful
- 😊 Happy
- 😐 Neutral
- 😢 Sad
- 😲 Surprised

---

## ✨ Features

- 🎙️ Speech audio upload
- 🎵 WAV audio support
- 🔊 Audio playback
- 🧠 CNN-based emotion classification
- 🎚️ MFCC feature extraction
- 📊 Emotion prediction
- 📈 Model evaluation
- 🌐 Streamlit web interface
- 🚀 Live deployment using Streamlit Community Cloud

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Librosa
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Streamlit

---

## 🧠 Machine Learning Approach

### 1. Audio Input

The user provides a speech audio file in WAV format.

### 2. Feature Extraction

The system uses **MFCC features** to represent important characteristics of the speech signal.

### 3. CNN Model

The extracted MFCC features are given to a Convolutional Neural Network.

The CNN learns patterns from the speech features and predicts the corresponding emotion.

### 4. Emotion Prediction

The trained model predicts one of eight emotions:

**Angry, Calm, Disgust, Fearful, Happy, Neutral, Sad, Surprised**

---

## 📊 Model Performance

The trained CNN model achieved approximately **41% test accuracy** on the evaluation dataset.

The performance can vary depending on the training configuration and audio input.

---

## 📂 Project Structure

```text
Emotion-Recognition-from-Speech
│
├── app.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── model/
│   └── emotion_model.keras
│
├── src/
│   ├── train.py
│   └── predict.py
│
└── dataset/
    └── archive/
        └── audio_speech_actors_01-24/
