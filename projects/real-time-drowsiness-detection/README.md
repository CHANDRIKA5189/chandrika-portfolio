# Real-Time Drowsiness Detection System

A computer-vision system for detecting driver drowsiness from eye-state information in real time, with an additional age-estimation component.

## Highlights
- CNN-based eye-state classification
- Real-time face and eye detection using OpenCV Haar cascades
- Drowsiness detection from consecutive eye-state observations
- Age estimation using a trained deep-learning model
- GUI-based inference workflow

## Technology Stack
- Python
- TensorFlow / Keras
- OpenCV
- CNN
- Haar Cascade Classifiers

## Project Workflow
1. Capture frames from the camera/input source.
2. Detect the face and eye regions.
3. Classify eye state with the trained CNN.
4. Track eye-state behavior to identify drowsiness.
5. Estimate age with the trained age model.
6. Display the results through the application interface.

## Repository Contents
- `train_eye_model.py` — eye-state model training
- `gui_drowsiness_age.py` — inference/GUI application
- `utils.py` — utility functions
- `requirements.txt` — Python dependencies

## Note
This project is a computer-vision prototype intended for research and demonstration. It should not be treated as a safety-certified driver monitoring system.

## Author
**Chandrika Bhattacharya** — Data Scientist | AI/ML Engineer
