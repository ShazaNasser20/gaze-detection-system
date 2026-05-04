#  Real-Time Gaze Detection System

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" />
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg" />
  <img src="https://img.shields.io/badge/MediaPipe-Face%20Tracking-orange.svg" />
</p>

---

##  Overview

This project is a real-time gaze tracking system built using Python, OpenCV, and MediaPipe.  
It detects eye movement and determines whether the user is focused or distracted in real time.

When distraction is detected for a continuous period, the system triggers a visual warning and sound alert.

---

##  Features

- Real-time face and eye landmark detection  
- Iris tracking using MediaPipe FaceMesh  
- Gaze direction estimation (Center / Not Center)  
- Adjustable sensitivity for better accuracy  
- Visual tracking overlays (points, lines, bounding box)  
- Screen warning overlay on distraction  
- Sound alert system  

---

##  Tech Stack

| Technology | Purpose |
|------------|--------|
| Python | Core language |
| OpenCV | Computer vision & webcam handling |
| MediaPipe | Face and eye landmark detection |
| NumPy | Numerical computations |
| Winsound | Sound alerts (Windows only) |

---

##  How It Works

1. Detect facial landmarks using MediaPipe FaceMesh  
2. Extract iris positions for both eyes  
3. Compute deviation from eye center  
4. Determine gaze direction in real time  
5. If gaze stays off-center for several frames:
   - Red warning overlay appears  
   - Sound alert is triggered  

---

##  Future Improvements

- Improve accuracy using deep learning models  
- Add multi-user tracking  
- Export attention logs for analysis  
- Build web-based version using Flask / Streamlit  

---

##  Notes

- Works best in good lighting conditions  
- Requires a webcam  
- Sound alert works only on Windows OS  
- Sensitivity can be adjusted in code (`THRESH_X`, `THRESH_Y`)  

---

##  Report

Full project report with detailed explanation and screenshots is included in this repository as a PDF file.

---

##  Team

- Shaza Abdulnaser Sayed  
- Sama Mohamed Tawfik  
- Sarah Hassan Mostafa  
- Zizi Mostafa Hamed
  
## ▶️ Installation & Run

### Install dependencies
```bash
pip install opencv-python mediapipe numpy
python main.py
