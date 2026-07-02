# 🎤 Speaker Recognition using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/scikit--learn-orange?style=for-the-badge&logo=scikit-learn">
  <img src="https://img.shields.io/badge/Librosa-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/OpenCV-green?style=for-the-badge&logo=opencv">
  <img src="https://img.shields.io/badge/License-MIT-success?style=for-the-badge">
</p>

---

## 📌 Project Overview

This project implements a **Speaker Recognition System** capable of identifying speakers from their voice recordings using Machine Learning.

The system extracts **MFCC (Mel Frequency Cepstral Coefficients)** from audio signals, preprocesses the features, trains a classification model, and predicts the identity of an unknown speaker.

The project demonstrates the complete Machine Learning workflow including:

- Audio preprocessing
- Feature extraction
- Data normalization
- Model training
- Prediction
- Model saving
- GUI-based testing using Tkinter

---

# 🚀 Features

✅ Voice Recording

✅ Audio Preprocessing

✅ MFCC Feature Extraction

✅ Machine Learning Classification

✅ Speaker Prediction

✅ Tkinter GUI

✅ Saved ML Model (.pkl)

---

# 🧠 Machine Learning Pipeline

```
Voice Recording
        │
        ▼
Audio Preprocessing
        │
        ▼
MFCC Feature Extraction
        │
        ▼
Feature Scaling
        │
        ▼
Machine Learning Model
        │
        ▼
Speaker Prediction
```

---

# 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Librosa
- Scikit-learn
- Tkinter
- Joblib
- Matplotlib

---

# 📂 Repository Structure

```
Speaker-Recognition-ML
│
├── VOICE_Dataset/
│
├── voice.ipynb
├── predict.ipynb
├── Tkinter.ipynb
│
├── voice_model.pkl
├── voice_encoder.pkl
├── voice_scaler.pkl
│
├── README.md
└── requirements.txt
```

---

# 📊 Dataset

The dataset consists of multiple speakers.

Each speaker has multiple audio samples.

Example:

```
VOICE_Dataset

│

├── Person_1

│      ├── audio1.wav

│      ├── audio2.wav

│

├── Person_2

│      ├── audio1.wav

│      ├── audio2.wav
```

---

# ⚙ Feature Extraction

The project uses **MFCC (Mel Frequency Cepstral Coefficients)** extracted using Librosa.

These features capture the important characteristics of human speech and are widely used in speaker recognition systems.

---

# 🤖 Model Training

The workflow includes:

- Dataset Loading
- Feature Extraction
- Label Encoding
- Feature Scaling
- Train-Test Split
- Model Training
- Model Evaluation
- Model Saving

The trained model is saved as:

```
voice_model.pkl
```

---

# 📈 Results

Example Performance

| Metric | Score |
|---------|-------|
| Accuracy | 98% |
| Precision | 98% |
| Recall | 98% |
| F1 Score | 98% |

> Replace these values with your actual results.

---

# ▶ How to Run

## Clone Repository

```bash
git clone https://github.com/amrritt18/Speaker-Recognition-ML.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Train Model

Run

```
voice.ipynb
```

---

## Predict Speaker

Run

```
predict.ipynb
```

---

## Launch GUI

Run

```
Tkinter.ipynb
```

---

# 📦 Requirements

```
numpy
pandas
librosa
matplotlib
joblib
scikit-learn
tkinter
```

---

# 🔮 Future Improvements

- Deep Learning based Speaker Recognition
- CNN/LSTM Models
- Real-Time Microphone Prediction
- Streamlit Web Application
- Docker Deployment
- Multi-language Speaker Identification

---

# 👨‍💻 Author

**Amrit Raj**

M.Tech in Robotics & AI

IIT Bhubaneswar

GitHub

https://github.com/amrritt18

---

# ⭐ Support

If you found this project useful,

please ⭐ Star this repository.

It motivates me to build more open-source AI projects.
