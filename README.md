# HAND DETECTION USING MEDIAPIPE

# PROJECT OVERVIEW
- This project demonstrates real-time hand detection using the Mediapipe library in Python. The goal is to utilize the webcam to detect and visualize hand landmarks and connections in a live video feed. Mediapipe's powerful hand detection model is leveraged to track hand movements and draw landmarks on the detected hands.

# CODE PIPELINE SUMMARY(Steps Taken)
## 1.Setup and Dependencies:
- Installed the Mediapipe library.
- Imported necessary libraries including cv2 for handling webcam input and mediapipe for hand detection.

## 2. Webcam Initialization:
- Identified and initialized the webcam using OpenCV's VideoCapture.

## 3. Hand Detection Setup:
- Configured Mediapipe's hand detection model and drawing utilities.

## 4. Real-Time Hand Detection Loop:
-  Captured frames from the webcam.
-  Converted frames from BGR to RGB format.
-  Applied the Mediapipe hand detection model to identify hand landmarks.
-  Drew the detected landmarks and connections on the frame.
-  Displayed the processed frame with annotations in a window.

## 5. Termination:
-  Implemented a loop to continuously process frames until a keypress ('c') is detected.
-  Released the webcam capture and closed all OpenCV windows after the process.

# KEY ACHIEVEMENTS
1. Successfully implemented real-time hand detection using the Mediapipe library.
2. Visualized hand landmarks and connections directly on the video feed.
3. Created a user-friendly display with text annotations for project identification.

# CONCLUSION
- This project effectively showcases the application of Mediapipe for hand detection, providing a robust solution for real-time hand tracking and visualization. The integration of webcam input and Mediapipe's hand detection capabilities allows for interactive and dynamic hand detection experiences. Future enhancements could include additional gesture recognition or integration with other computer vision tasks.

# TECH STACK
-  Jupyter Notebook
-  Webcam
