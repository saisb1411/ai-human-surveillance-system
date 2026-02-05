# AI-Powered Real-Time Human Surveillance System

This project implements a real-time human detection system using the YOLOv8 deep learning model and OpenCV.

It captures live webcam footage, detects humans based on confidence thresholds, and triggers an on-screen alert when a person is identified. The system also monitors FPS to evaluate real-time performance.

## Features
- Real-time human detection  
- Confidence filtering to reduce false positives  
- Automated alert display  
- FPS monitoring  

## Tech Stack
Python, OpenCV, YOLOv8

## How to Run
Install dependencies:

pip install ultralytics opencv-python

Run the script:

python human_detection.py

## Future Improvements
- Email/SMS alerts  
- Multi-camera support  
- Edge deployment for smart surveillance  
