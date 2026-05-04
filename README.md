#  Real-Time Gaze Detection System

##  Overview
This project is a real-time gaze (eye focus) detection system developed using Python.  
It uses computer vision techniques to track eye movement through a webcam and determines whether the user is focusing or distracted. If the user stays unfocused for a period of time, an alert is triggered.

This project was developed as part of an academic assignment in the Faculty of Artificial Intelligence and Data Management, Course: Pattern Recognition.

---

##  Team Members
- Shaza Abdulnaser Sayed  
- Sama Mohamed Tawfik  
- Sarah Hassan Mostafa  
- Zizi Mostafa Hamed  

---

##  Features
- Real-time face and eye tracking using webcam  
- Iris detection using MediaPipe FaceMesh  
- Gaze direction classification (center / not center)  
- Adjustable sensitivity for detection  
- Continuous distraction monitoring  
- Visual feedback on screen  
- Audio alert when focus is lost  

---

##  Technologies Used
- Python  
- OpenCV  
- MediaPipe  
- NumPy  
- Winsound (Windows only)

---

##  System Workflow
1. Capture live video from webcam  
2. Detect facial landmarks using MediaPipe  
3. Extract iris position for both eyes  
4. Calculate eye center and deviation  
5. Determine gaze direction  
6. Trigger alert if distraction continues for several frames  

---

##  Alert System
If the user is not focusing for a continuous number of frames:
- Screen overlay turns red  
- “FOCUS!” warning appears  
- Beep sound is triggered  

---

##  Applications
- Online exam proctoring systems  
- Attention monitoring tools  
- Human-computer interaction research  
- Focus tracking in learning environments  

---

##  Notes
- The project runs in real-time using a webcam  
- Works best under good lighting conditions  
- Designed for educational purposes  

---

##  License
This project is for educational use only.
