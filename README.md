# Hand Tracking with MediaPipe and OpenCV

A real-time hand tracking project built with Python, OpenCV, and MediaPipe.

## 🚀 Live Demo

👉 [Live URL](https://godugusivanagalakshmi.github.io/hand-tracking-mediapipe/)


## Features

* Real-time hand detection
* Hand landmark tracking
* Supports up to two hands
* Uses a computer webcam
* Built with MediaPipe Tasks API

## Requirements

* Python
* OpenCV
* MediaPipe

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/hand-tracking-mediapipe.git
cd hand-tracking-mediapipe
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## MediaPipe Model

This project requires the MediaPipe Hand Landmarker model:

```text
hand_landmarker.task
```

Download the Hand Landmarker model from Google's official MediaPipe documentation and place it in the project folder.

The project should look like:

```text
hand-tracking-mediapipe/
│
├── handgesture.py
├── requirements.txt
├── .gitignore
├── README.md
└── hand_landmarker.task
```

## Run

Start the program:

```bash
python handgesture.py
```

The webcam will open and display detected hand landmarks.

Press `Q` to close the application.

## Technologies

* Python
* OpenCV
* MediaPipe
