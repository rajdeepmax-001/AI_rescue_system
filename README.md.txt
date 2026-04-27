#  AI Rescue System

An AI-powered real-time survivor detection system designed to assist rescue teams during disasters like earthquakes, floods, and building collapses.

---

##  Problem
In disaster scenarios, locating survivors quickly is extremely difficult and time-sensitive. Manual search operations are slow and often miss critical areas.

---

##  Solution
This system uses computer vision (YOLOv8) to:
- Detect humans in real-time from video feeds (drones/CCTV)
- Track multiple survivors
- Generate heatmaps of high-risk zones
- Assist rescue teams in prioritizing areas

---

##  Features
-  Real-time human detection (YOLOv8)
-  Multi-person tracking
-  Heatmap visualization of survivor density
-  Risk detection system

---

##  Results
- Accuracy improved from **62% → 81%**
- Faster and more consistent detection
- Improved reliability in crowded scenarios

---

##  Demo
 Heatmap Visualization
[Heatmap Sample](Heatmap Sample.png)



---

##  Tech Stack
- Python
- OpenCV
- YOLOv8 (Ultralytics)
- NumPy

---

##  How to Run
```bash
pip install -r requirements.txt
python main.py
