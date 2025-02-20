# Drowsiness-and-Yawn-Detection-with-Integrated-voice-alert-system

# Project Overview:
This project focuses on enhancing road safety by detecting driver drowsiness and yawning in real-time. Upon detection, an integrated voice alert system notifies the driver instantly, reducing the risk of accidents caused by fatigue. The system ensures accurate monitoring, even under challenging lighting conditions, using advanced computer vision techniques.

# Key Features

# Real-Time Detection: 
Detects drowsiness and yawning using live video feed.
# Integrated Voice Alert:
Immediate voice notifications to alert the driver.
 # High Accuracy:
 Robust detection even in varying lighting conditions.
# Efficient Pipeline: 
Optimized for real-time performance with minimal latency.
# User-Friendly Interface: 
Easy-to-use system with minimal hardware requirements.

# Technologies Used

* Programming Language: Python

# Libraries & Frameworks:

* OpenCV (Computer Vision tasks)
* dlib (Facial landmark detection)
* Pygame (Voice alert system integration)

# Other Tools:

* Haar Cascade Classifiers
* Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR) calculations

# System Architecture

Data Acquisition: Live video stream from the camera.
# Face & Landmark Detection:
Use of dlib’s pre-trained shape predictor for facial landmarks.
Haar cascades for initial face detection.

# Feature Extraction:

Calculation of EAR for drowsiness detection.
Calculation of MAR for yawn detection.

# Threshold Analysis:

EAR < threshold → Drowsiness detected.
MAR > threshold → Yawn detected.

# Alert Mechanism:

Trigger voice alerts using Pygame when thresholds are crossed.

# Applications
1. Automobile Industry: Enhancing driver safety in commercial and personal vehicles.

2 .Public Transport: Reducing accidents in buses, trains, and trucks.

3 .Industrial Operations: Ensuring operator alertness in critical industrial environments.
