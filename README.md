# AI-Driver-Moniter-System
# 🚗 AI Driver Monitoring System

An intelligent real-time AI-based Driver Monitoring System developed using **Python, OpenCV, Dlib, YOLOv8, and Deep Learning concepts** to improve driver safety by detecting:

- 😴 Drowsiness
- 🥱 Yawning
- 📱 Mobile Phone Usage
- ⚠️ Driver Distraction

The system provides live visual alerts and alarm notifications when unsafe driving behavior is detected.

---

# 📌 Features

✅ Real-time Face Detection  
✅ Eye Aspect Ratio (EAR) based Drowsiness Detection  
✅ Mouth Aspect Ratio (MAR) based Yawning Detection  
✅ YOLOv8 Mobile Phone Detection  
✅ Live Alarm System  
✅ FPS Display  
✅ Webcam & Video File Support  
✅ Facial Landmark Tracking  
✅ Improved Brightness & Stability  

---

# 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core Programming |
| OpenCV | Computer Vision |
| Dlib | Facial Landmark Detection |
| YOLOv8 | Object Detection |
| Pygame | Alarm Sound |
| NumPy | Numerical Operations |
| SciPy | Distance Calculation |
| Imutils | Image Processing |

---

# 🧠 System Workflow

1. Capture video from webcam/video file
2. Detect driver's face
3. Extract facial landmarks
4. Calculate:
   - Eye Aspect Ratio (EAR)
   - Mouth Aspect Ratio (MAR)
5. Detect:
   - Eye closure
   - Yawning
   - Mobile phone usage
6. Trigger alarm if unsafe behavior is detected
7. Display live monitoring window

** use python 13.11 version
