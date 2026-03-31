# Realtime-Driver-Drowsiness-Detection
Here is your **README.md without emojis**, clean and professional:

---

# Driver Drowsiness Detection System

## Overview

The Driver Drowsiness Detection System is an AI-powered application that detects driver fatigue in real time using computer vision and deep learning techniques. It analyzes facial features such as eye closure, blink rate, and yawning to determine whether the driver is alert or drowsy and triggers alerts to prevent accidents.

---

## Features

* Real-time drowsiness detection using webcam
* Eye and mouth tracking (EAR & MAR)
* CNN-based deep learning model for classification
* Alert system with increasing intensity
* Works in low-light conditions using IR functionality
* Non-intrusive and efficient

---

## Technologies Used

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* Convolutional Neural Network (CNN)

---

## System Architecture

1. Video capture through webcam
2. Face detection and facial landmark extraction
3. Feature calculation (Eye Aspect Ratio and Mouth Aspect Ratio)
4. Classification using trained CNN model
5. Alert generation if drowsiness is detected

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/drowsiness-detection.git
cd drowsiness-detection
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python main.py
```

---

## Dataset

* Kaggle Drowsiness Dataset
* yawn_eye_dataset_new

---

## How It Works

* The system captures real-time video from the webcam
* Detects face, eyes, and mouth
* Calculates Eye Aspect Ratio (EAR) and Mouth Aspect Ratio (MAR)
* Uses a trained CNN model to classify driver state
* If drowsiness persists, an alert is triggered

---

## Results

* High accuracy in real-time detection
* Effective in different lighting conditions (with IR support)
* Helps reduce accidents caused by fatigue

---

## Limitations

* Performance depends on camera quality
* May struggle with extreme lighting or heavy occlusion
* Requires proper face visibility

---

## Future Enhancements

* Integration with vehicle systems
* Use of audio and behavioral data
* Deployment on embedded systems
* Mobile application integration

---

## Applications

* Automotive safety systems
* Fleet management
* Driver monitoring systems
