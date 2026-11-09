Emotion Recognition from Speech

Project Description

This project is a machine learning-based emotion recognition system developed in Python. It identifies human emotions from speech audio by extracting audio features and classifying them using machine learning algorithms.

The system uses MFCC (Mel-Frequency Cepstral Coefficients) to extract important features from speech signals and trains different classifiers to recognize emotions.

Features

Recognizes eight emotions: Neutral, Calm, Happy, Sad, Angry, Fearful, Disgust, and Surprised.

Extracts audio features using MFCC.

Uses K-Nearest Neighbors (KNN) for classification.

Uses Support Vector Machine (SVM) for classification.

Uses Random Forest for classification.

Compares the accuracy of different machine learning models.

Displays classification reports and confusion matrices.

Allows users to upload a new WAV audio recording for emotion prediction.

Saves the trained model and feature scaler.

Technologies Used

Python

Google Colab

Librosa

NumPy

Pandas

Scikit-learn

Matplotlib

Seaborn

RAVDESS Speech Emotion Dataset

How It Works

The system uses the RAVDESS speech emotion dataset containing audio recordings of different emotions.

First, the audio files are loaded and MFCC features are extracted from each recording. These features are then divided into training and testing datasets.

The extracted features are standardized and provided to three machine learning algorithms: KNN, SVM, and Random Forest.

The models are trained and evaluated based on their classification accuracy. The best-performing model is selected to predict emotions from new speech recordings.

How to Run

Open Task_2_Emotion_Recognition.ipynb in Google Colab.

Upload the RAVDESS Audio-only Speech dataset ZIP file as archive.zip to the Colab runtime.

Run the code cells from beginning to end.

Wait for audio feature extraction and model training.

View the model accuracy, comparison graph, classification report, and confusion matrix.

Upload a new WAV speech recording to test emotion prediction.

The system displays the predicted emotion.

