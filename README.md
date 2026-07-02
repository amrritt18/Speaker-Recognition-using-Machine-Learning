<h1 align="center">🎤 Speaker Recognition using Machine Learning</h1>

<p align="center">
A Machine Learning-based Speaker Recognition System that identifies a speaker from voice recordings using MFCC feature extraction and supervised learning.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-orange?style=for-the-badge&logo=scikit-learn)
![Librosa](https://img.shields.io/badge/Librosa-Audio-red?style=for-the-badge)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-94.44%25-success?style=for-the-badge)

</p>

---

# 📖 Overview

Speaker Recognition is a biometric authentication technique that identifies a person based on unique characteristics of their voice.

This project uses **MFCC (Mel Frequency Cepstral Coefficients)** to extract meaningful audio features and trains a **Machine Learning classifier** capable of recognizing different speakers with high accuracy.

The project demonstrates an end-to-end machine learning workflow, including:

- Audio preprocessing
- Feature extraction
- Data normalization
- Model training
- Model evaluation
- Speaker prediction
- Interactive GUI for testing

---

# ✨ Features

- 🎙 Record voice using microphone
- 🔊 Process WAV audio files
- 📊 Extract MFCC features
- 🤖 Train a Machine Learning model
- 🧠 Predict speaker identity
- 💾 Save trained model using Joblib
- 🖥 Simple Tkinter GUI for inference

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Programming | Python |
| Machine Learning | Scikit-learn |
| Audio Processing | Librosa |
| Data Analysis | NumPy, Pandas |
| Visualization | Matplotlib |
| GUI | Tkinter |
| Model Serialization | Joblib |

---

# 📂 Repository Structure

```
Speaker-Recognition-ML
│
├── VOICE_Dataset/
│
├── demo/
│
├── models/
│   ├── voice_model.pkl
│   ├── voice_encoder.pkl
│   └── voice_scaler.pkl
│
├── notebooks/
│   ├── voice.ipynb
│   ├── predict.ipynb
│   └── Tkinter.ipynb
│
├── .gitignore
└── README.md
```

---

# ⚙ Workflow

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

# 📊 Model Performance

The model was evaluated on **18 unseen voice samples** from **9 different speakers**.

## Overall Performance

| Metric | Score |
|---------|-------|
| Accuracy | **94.44%** |
| Macro Precision | **96%** |
| Macro Recall | **94%** |
| Macro F1-score | **94%** |

---

## Classification Report

| Speaker | Precision | Recall | F1-Score |
|----------|----------:|-------:|---------:|
| Ajay | 1.00 | 1.00 | 1.00 |
| Aman | 1.00 | 1.00 | 1.00 |
| Amrit | 1.00 | 1.00 | 1.00 |
| Aritra | 1.00 | 1.00 | 1.00 |
| Atul | 1.00 | 1.00 | 1.00 |
| Jamna | 1.00 | 1.00 | 1.00 |
| Parth | 1.00 | 0.50 | 0.67 |
| Raj | 0.67 | 1.00 | 0.80 |
| Ram | 1.00 | 1.00 | 1.00 |

The model achieved an overall **94.44% accuracy**, demonstrating reliable performance for speaker identification using MFCC-based feature extraction and supervised machine learning.

---

# 🚀 Getting Started

## Clone the repository

```bash
git clone https://github.com/amrritt18/Speaker-Recognition-ML.git
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Train the Model

Open and execute

```
notebooks/voice.ipynb
```

---

## Predict Speaker

Run

```
notebooks/predict.ipynb
```

---

## Launch the GUI

Run

```
notebooks/Tkinter.ipynb
```

---

# 📦 Required Libraries

```
numpy
pandas
scikit-learn
librosa
matplotlib
joblib
sounddevice
soundfile
jupyter
ipykernel
```

---

# 📸 Demo

> Add screenshots or GIFs of your application inside the `demo/` folder.

Example:

```
demo/
│
├── gui.png
├── prediction.png
└── workflow.png
```

After adding screenshots, include them like this:

```markdown
## GUI

<p align="center">
<img src="demo/gui.png" width="800">
</p>

## Prediction

<p align="center">
<img src="demo/prediction.png" width="800">
</p>
```

---

# 🔮 Future Improvements

- Deep Learning-based Speaker Recognition
- CNN/LSTM Models
- Transformer-based Speech Embeddings
- Real-time Microphone Prediction
- Streamlit Web Application
- Flask REST API
- Docker Deployment
- Multi-language Speaker Identification

---

# 👨‍💻 Author

**Amrit Raj**

🎓 M.Tech in Robotics & Artificial Intelligence  
IIT Bhubaneswar

GitHub: https://github.com/amrritt18

LinkedIn: *(Add your LinkedIn URL here)*

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates me to build more open-source AI and Robotics applications.
