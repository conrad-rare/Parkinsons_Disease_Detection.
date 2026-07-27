# Parkinson's Disease Detection Using Deep Learning

A deep learning project that detects Parkinson's disease from voice recordings using multiple neural network architectures. The project explores and compares different deep learning models to classify Parkinson's disease from speech-based features extracted from publicly available datasets.

---

## Project Overview

Parkinson's disease is a progressive neurological disorder that affects movement and speech. Early detection can support timely medical intervention and improve patient care.

This project applies deep learning techniques to voice-based Parkinson's disease detection by training and evaluating several neural network architectures on publicly available datasets.

---

## Objectives

- Build an end-to-end deep learning pipeline for Parkinson's disease detection.
- Compare the performance of different deep learning models.
- Evaluate model accuracy using standard classification metrics.
- Demonstrate how AI can assist in healthcare prediction tasks.

---

## Models Implemented

- Multi-Layer Perceptron (MLP)
- 1D Convolutional Neural Network (CNN)
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
- Bidirectional LSTM (BiLSTM)
- CNN-BiLSTM Hybrid Model

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook
- Kaggle

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Feature Engineering
4. Model Development
5. Model Training
6. Model Evaluation
7. Performance Comparison
8. Prediction

---

## Datasets

This project uses publicly available Parkinson's disease datasets available on Kaggle.

Datasets used include:

- **MDVR-KCL Dataset**
- **Oxford Parkinson's Disease Detection Dataset**
- **Parkinson's Telemonitoring Dataset**

The datasets are not included in this repository because of their size and licensing.

To reproduce this project, download the datasets from Kaggle and place them in the appropriate directories before running the notebook.

---

## Repository Structure

```
parkinsons-disease-detection/
│
├── Parkinson's Disease Detection Using Deep Learning.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

## Results

The implemented deep learning models were evaluated using standard classification metrics to compare their effectiveness in detecting Parkinson's disease from voice recordings. The project highlights the strengths of different neural network architectures for healthcare-related prediction tasks.

---

## Future Improvements

- Hyperparameter tuning
- Explainable AI (XAI)
- Web application deployment using Flask or FastAPI
- Cloud deployment using Microsoft Azure
- Real-time voice prediction from microphone input

---

## Disclaimer

This project is intended for educational and research purposes only. It is **not** a medical diagnostic system and should not be used for clinical decision-making.

---

