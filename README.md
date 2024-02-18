# Hand Tracking with MediaPipe and OpenCV

## Overview
This Python script utilizes the MediaPipe library and OpenCV to perform real-time hand tracking using a computer's camera. The script captures video from the default camera, detects hand landmarks, and visualizes them on the video feed.

## Dependencies
Ensure that you have the required libraries installed before running the script:

OpenCV: pip install opencv-python

MediaPipe: pip install mediapipe
## Running the Script
Save the provided code in a file with a .py extension (e.g., hand_tracking.py).

Open a terminal or command prompt and navigate to the directory containing the script.

Run the script using the following command:

```bash

python hand_tracking.py
```
Allow camera access when prompted. The script will display a window showing live video with hand landmarks.

To exit the script, press the 'q' key in the displayed video window.

## Customization
If you have multiple cameras or a different camera index, modify the line cv2.VideoCapture(0) to the appropriate index (e.g., cv2.VideoCapture(1)).

Feel free to explore and modify the script for additional functionalities or integration into larger projects.

## Issues
If you encounter any issues, check the error messages in the terminal or command prompt for troubleshooting. Make sure the camera is accessible and connected.

## Dependencies and Versions
Python 3.x

OpenCV 4.9.0

MediaPipe (latest version)
