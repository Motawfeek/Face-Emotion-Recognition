# Face Emotion Recognition

This project uses **YOLO** for real-time object detection to detect faces and **DeepFace** for emotion recognition.

## Project Description

The **Face Emotion Recognition** project implements a real-time system that:
- Detects faces using the **YOLO** object detection model.
- Analyzes the facial emotion using the **DeepFace** library.
- Displays the detected emotion on the screen in real-time.

This project uses the **YOLOv4-tiny** model for object detection and **DeepFace** for facial emotion recognition.

## Requirements

Before running the project, make sure you have the following dependencies installed:

- Python 3.9.10
- OpenCV
- DeepFace
- TensorFlow (optional, depending on your setup)
- YOLOv4-tiny model weights and configuration files

## How to Run

1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install opencv-python deepface
