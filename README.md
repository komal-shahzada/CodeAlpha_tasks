🎙️ Speech Emotion Recognition (SER) using CNN
This project implements a Deep Learning Model (CNN) designed to recognize human emotions from speech audio. It was developed as part of Task 2 for the CodeAlpha Machine Learning Internship.

🌟 Project Overview
The model is trained on the RAVDESS dataset. It processes audio signals by extracting MFCC (Mel-frequency cepstral coefficients) features to predict the underlying emotion. An interactive Gradio Interface is included, allowing users to record their own voice and get real-time predictions.

📊 Key Features
Dataset: RAVDESS (Emotional Speech Audio).

Feature Extraction: MFCC (40 features per audio sample).

Model Architecture: Convolutional Neural Network (CNN) with 1D layers.

Accuracy: Achieved a high performance of 91% accuracy.

Interactive UI: Real-time emotion detection via a web-based Gradio interface.

🛠️ Libraries Used
TensorFlow / Keras (Deep Learning Framework)

Librosa (Audio Processing)

Gradio (Web Interface Deployment)

Scikit-learn (Data Preprocessing & Scaling)

Matplotlib / Seaborn (Data Visualization)

📈 Results & Emotions
The model can accurately classify the following 8 emotions:

Neutral

Calm

Happy

Sad

Angry

Fearful

Disgust

Surprised
