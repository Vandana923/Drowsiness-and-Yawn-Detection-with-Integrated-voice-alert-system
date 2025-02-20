# Drowsiness-and-Yawn-Detection-with-Integrated-voice-alert-system

# Project Overview:
This project focuses on enhancing road safety by detecting driver drowsiness and yawning in real-time. Upon detection, an integrated voice alert system notifies the driver instantly, reducing the risk of accidents caused by fatigue. The system ensures accurate monitoring, even under challenging lighting conditions, using advanced computer vision techniques.

# Key Features

<b>Real-Time Detection:</b>
Detects drowsiness and yawning using live video feed.
<b>Integrated Voice Alert:</b>
Immediate voice notifications to alert the driver.
<b> High Accuracy:</b>
Robust detection even in varying lighting conditions.
<b> Efficient Pipeline: </b>
Optimized for real-time performance with minimal latency.
<b>User-Friendly Interface:</b> 
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

<b>Data Acquisition:<b/>

Live video stream from the camera.
<b>Face & Landmark Detection:<b/>

Use of dlib’s pre-trained shape predictor for facial landmarks.
Haar cascades for initial face detection.

<b>Feature Extraction:<b/>

Calculation of EAR for drowsiness detection.

Calculation of MAR for yawn detection.

<b>Threshold Analysis:<b/>

EAR < threshold → Drowsiness detected.
MAR > threshold → Yawn detected.

<b>Alert Mechanism:<b/> 

Trigger voice alerts using Pygame when thresholds are crossed.

# Applications

1. Automobile Industry: Enhancing driver safety in commercial and personal vehicles.

2 .Public Transport: Reducing accidents in buses, trains, and trucks.

3 .Industrial Operations: Ensuring operator alertness in critical industrial environments.

# Drowsiness and Yawn Detection :

# No Alert

![image](https://github.com/user-attachments/assets/5e61a960-bdfb-46dd-81df-09aebe03fcef)

# Alert

![image](https://github.com/user-attachments/assets/0ae681d3-bd22-43b6-b405-d23d903133dd)

# Yawn alert 

![image](https://github.com/user-attachments/assets/be7d283a-8910-4e6c-af5b-948cf9841ed2)


