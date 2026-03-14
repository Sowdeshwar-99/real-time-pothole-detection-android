# Real-Time Pothole Detection Android Application

## Overview
This project implements a **real-time pothole detection system** using computer vision techniques integrated into an **Android mobile application**.

The application processes live camera frames from a smartphone and detects potholes on road surfaces. The goal is to assist in **road condition monitoring and infrastructure maintenance** by automatically identifying potholes during vehicle movement.

The detection pipeline combines **image processing, object tracking, and machine learning techniques** to detect road surface anomalies.


## Features

- Real-time pothole detection using smartphone camera
- Computer vision–based object detection
- Android mobile application interface
- Native image processing using **JNI and C++**
- Efficient frame processing for mobile devices
- Demo APK included for testing


## System Architecture

1. Camera Input  
2. Frame Capture (Android Camera API)  
3. YUV → RGB Conversion  
4. Image Processing using OpenCV / Native C++  
5. Object Detection & Tracking  
6. Pothole Identification  
7. Bounding Box Visualization

## Technologies Used

- Android Studio
- Java
- C++
- JNI (Java Native Interface)
- OpenCV
- Python
- Jupyter Notebook

## Running the Application

### Option 1 — Install APK (Recommended)

1. Download **app-release.apk**
2. Transfer it to an Android device
3. Install the APK
4. Launch the application
5. Allow camera access

The app will start detecting potholes in real time.

### Option 2 — Build from Source

Clone the repository

```bash
git clone https://github.com/Sowdeshwar-99/real-time-pothole-detection-android.git

Open the project in Android Studio

Build and run on an Android device.

```

The notebook PotholeDetection.ipynb contains the experimentation and development steps for the pothole detection model including:

Image preprocessing

Feature extraction

Model experimentation

Evaluation

Applications

Road infrastructure monitoring

Smart city development

Automated road inspection systems

Driver assistance systems

Future Improvements

GPS-based pothole mapping

Cloud-based reporting system

Deep learning model integration

Integration with municipal road monitoring systems
