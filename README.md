Real-Time Facial Emotion Detection App

Overview

This Python application utilizes a pre-trained deep learning model to detect and classify facial expressions in real-time video streams. The app leverages OpenCV for video capture and face detection, while the emotion classification relies on a loaded TensorFlow/Keras model.

Features

1. Real-Time Video Processing: Captures video from the user's webcam.
2. Face Detection: Identifies human faces within the video frame.
3. Emotion Recognition: Classifies emotions from facial features using a pre-trained model.
4. Emotion Display: Overlays the detected emotion label onto the video frame.

Usage

1. Run the application.
2. The user's webcam feed will display on the screen.
3. The app will identify faces and predict their emotions in real-time.
4. Emotion labels (e.g., Happy, Sad, Angry) will appear above each detected face.
   
Technical Specifications

Programming Language: Python

Libraries: OpenCV, TensorFlow/Keras

Pre-trained Model: Facial emotion classification model (.h5)

Haar Cascade Classifier: Haarcascade_frontalface_default.xml (for face detection)

Note: This application requires a pre-trained facial emotion classification model for operation.

Author: Ayushi Kansara ayushikansara1110
