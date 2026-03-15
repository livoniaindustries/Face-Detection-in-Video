# Face Detection in Video

A Python project that detects faces in real-time from a webcam or a video file using OpenCV's Haar cascades.

## Features

- Detects faces in live webcam feed or video files
- Highlights detected faces with rectangles
- Easy setup with virtual environment

## Requirements

- Python 3.x
- OpenCV
- NumPy
- imutils (optional for advanced video/image processing)

## Installation

1. Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate  # Windows
# source venv/bin/activate  # macOS/Linux
```
Install dependencies:
```
pip install opencv-python
pip install numpy
pip install imutils
```
Make sure the Haar cascade file is in your project folder:
```
haarcascade_frontalface_default.xml
```
Usage
```

python detect_face_video.py
