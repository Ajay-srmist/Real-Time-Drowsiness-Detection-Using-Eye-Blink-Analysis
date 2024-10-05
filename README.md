# Real-Time-Drowsiness-Detection-Using-Eye-Blink-Analysis
This project is a real-time drowsiness detection system built using Python, OpenCV, and Dlib. It captures live video from a webcam, detects facial landmarks, and analyzes eye blink patterns to determine whether the user is Active, Drowsy, or Sleeping.
# Overview
The system leverages computer vision techniques to detect a person’s face and track their eye movements. Based on the eye aspect ratio (EAR) calculated from facial landmarks, it classifies the user into three states:

Sleeping: Eyes closed for an extended period.
Drowsy: Slow or partial blinks.
Active: Eyes open with normal blink patterns.
This project can be particularly useful for monitoring drivers, machine operators, or anyone who needs to stay alert in a critical environment.
# Features
- Face Detection: Detects faces in real-time using Dlib's pre-trained face detector
- Eye Blink Detection: Tracks specific eye landmarks to compute the blink ratio
- Drowsiness Classification: Classifies the user's state into Sleeping, Drowsy, or Active based on eye movement
- Real-Time Feedback: Displays the current state on the live video feed
- User Alerts: Changes the color and status message based on the user’s alertness.
