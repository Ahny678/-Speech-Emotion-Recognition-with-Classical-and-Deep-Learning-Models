# Speech Emotion Recognition (SER)

This repository contains code for a **Speech Emotion Recognition (SER)** project implemented in a Google Colab notebook.

## What the code does

The code performs automatic emotion classification from speech audio. Specifically, it:

- Loads emotional speech audio files
- Extracts acoustic features (Mel-Frequency Cepstral Coefficients – MFCCs)
- Preprocesses and normalizes the extracted features
- Trains and evaluates multiple models:
  - Support Vector Machine (SVM)
  - Random Forest classifier
  - 1D Convolutional Neural Network (CNN) baseline
- Evaluates model performance using accuracy and confusion matrices

The goal is to compare traditional machine learning models with a baseline deep learning approach for speech emotion recognition.

## Dataset

This project uses the **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)** emotional speech dataset.

- Audio format: WAV
- Number of emotion classes: 8  
  (neutral, calm, happy, sad, angry, fearful, disgust, surprised)
- Dataset size: 1,440 speech audio files

### Dataset source

The dataset can be downloaded from Kaggle:

https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

You must download the dataset manually and make it available to the notebook (e.g., by uploading it or mounting Google Drive in Colab).

## How to run

1. Open the Google Colab notebook included in this repository.
2. Upload or mount the RAVDESS dataset.
3. Run all cells to perform feature extraction, model training, and evaluation.

## Repository contents

```

├── speech_emotion_recognition.ipynb
├── README.md

```
```
