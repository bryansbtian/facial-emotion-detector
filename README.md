# Facial Emotion Detector

A real-time facial emotion detection application built using OpenCV, Keras, and TensorFlow. The application captures live video feed from a webcam, detects faces, and predicts the emotions displayed by individuals.

## Features

- Real-time face detection using OpenCV's Haar Cascades.
- Emotion prediction using a pre-trained deep learning model.
- Supports seven emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.
- Displays the predicted emotion on the video feed.

## Prerequisites

Make sure you have the following installed:

- Python 3.7 or higher
- Required Python packages (see [Installation](#installation) section)
- A webcam for capturing video feed

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/bryansbtian/facial-emotion-detector.git
   cd facial-emotion-detector

2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt

3. Ensure you have the following files in your project directory:
   - emotiondetector.json (Model architecture)
   - emotiondetector.h5 (Pre-trained weights)

## Usage

1. Run the script:
   ```bash
   python realtimedetection.py

2. The application will open a live video feed from your webcam. Detected faces will have a bounding box, and the predicted emotion will be displayed above the face.
3. Press q to exit the application.
