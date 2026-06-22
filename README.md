Project Overview
Speech Emotion Recognition (SER) is a machine learning application that identifies human emotions from speech signals. This project evaluates and compares the performance of multiple Machine Learning and Deep Learning models using prosodic speech features such as:
Pitch
Energy
Speech Rate
Duration
The goal is to determine which model provides the most accurate and reliable emotion classification.

Objectives
Extract prosodic features from speech signals.
Train multiple ML and DL models on the same dataset.
Compare model performance using standard evaluation metrics.
Identify the best-performing model for Speech Emotion Recognition.

Dataset
RAVDESS Dataset
Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)

Features:
1,440 speech recordings
24 professional actors
48 kHz WAV audio files
Balanced emotional categories

Emotions:
Neutral
Happy
Sad
Angry
Fearful
Disgusted
Surprised

Methodology
1. Data Collection
Speech samples are collected from the RAVDESS dataset.

2. Audio Preprocessing
Noise removal
Silence trimming
Signal enhancement

4. Feature Extraction
Prosodic features extracted:
Pitch
Energy
Speech Rate
Duration

4. Feature Normalization
Features are normalized and scaled before training.

5. Model Training
The following models are trained and evaluated:
Support Vector Machine (SVM)
Random Forest (RF)
Gaussian Mixture Model (GMM)
Convolutional Neural Network (CNN)
Long Short-Term Memory (LSTM)

6. Evaluation Metrics
Accuracy
Precision
Recall
F1-Score
Support
Confusion Matrix

Results
Overall Model Performance
Model	Accuracy	Precision	Recall	F1-Score
SVM	92.03%	92.17%	92.03%	91.99%
LSTM	85.51%	85.23%	85.51%	85.04%
GMM	78.26%	79.09%	78.26%	78.30%
RF	71.74%	71.28%	71.74%	71.07%
CNN	63.04%	77.62%	63.04%	65.17%

Best Performing Model
Support Vector Machine (SVM) achieved the highest performance across all evaluation metrics with an accuracy of approximately 92%.

Key Findings
SVM provides the best overall emotion classification performance.
LSTM effectively captures temporal speech patterns and achieves the second-best results.
Random Forest performs well but is less effective than SVM and LSTM.
GMM offers moderate performance through probabilistic modeling.
CNN underperforms when only prosodic features are used.

Applications
Human-Computer Interaction
Virtual Assistants
Chatbots
Call Center Analytics
Mental Health Monitoring
Smart IoT Systems
Educational Technology
Entertainment and Media Systems

Technologies Used
Python
Machine Learning
Deep Learning
Speech Signal Processing
RAVDESS Dataset
Prosodic Feature Extraction
Classification Algorithms (SVM, RF, GMM, CNN, LSTM)

Conclusion
This project demonstrates that prosodic speech features can effectively be used for Speech Emotion Recognition. Among all evaluated models, SVM achieved the highest accuracy and overall performance, proving to be the most suitable classifier for the selected feature set and dataset. Future work may include multimodal emotion recognition, hybrid feature extraction techniques, and advanced deep-learning architectures for improved accuracy and generalization.
