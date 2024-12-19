# FingerCountTrackerUsingOpenCV
Finger Count Tracker System using OpenCV and Python Modules

# Description:
This project utilizes the MediaPipe library for real-time hand tracking and gesture recognition, with the goal of detecting and counting the number of fingers shown by a person using their hand. The system operates through a live video feed from the webcam and performs hand gesture analysis to recognize finger positions and identify how many fingers are raised.

# Key Features:
_**Live Finger Counting:**_ The project processes the live video feed and tracks the hand's landmarks in real-time to detect and count the number of raised fingers. Hands Detection and Tracking: Using MediaPipe’s hand tracking solution, the system tracks the position of key points on the hand and determines which fingers are raised based on their positions.<br><br> _**Visual Overlay:**_ The application displays a live video feed with a visual overlay of the detected number of fingers shown. The corresponding finger count is overlaid on the screen.<br><br> _**FPS Display:**_ The system continuously calculates and displays the Frames Per Second (FPS) of the live feed to provide performance feedback.

# Technology Stack:
Python: The core programming language used for implementing the project. OpenCV: Used for real-time video capture and image processing. MediaPipe: A powerful library from Google for real-time hand tracking and landmark detection. NumPy: For efficient array handling and mathematical operations in conjunction with OpenCV.
