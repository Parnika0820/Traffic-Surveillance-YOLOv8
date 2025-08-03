# Traffic Surveillance Using YOLOv8 and DeepSORT

## 📄 Project Description

### 🔹 Summary

This project implements a real-time traffic monitoring system using deep learning-based object detection and multi-object tracking techniques. It integrates **YOLOv8** for accurate vehicle detection and **DeepSORT** for robust object tracking, identity preservation, and speed estimation. The system is capable of counting vehicles and flagging those exceeding a specified speed limit, making it suitable for modern traffic surveillance and enforcement scenarios.

---

## 🎓 Course Concepts Used

- Object Detection using YOLOv8 (You Only Look Once, version 8)
- Object Tracking with DeepSORT (Kalman Filter + Appearance Matching)
- Centroid-based Euclidean distance calculation
- Speed Estimation using Frame-rate Calibration
- Threshold-based Violation Detection
- Virtual Line-based Counting Logic

---

## 🗂️ Dataset

- **Dataset**: [UA-DETARC](https://www.kaggle.com/datasets/thhyaa/uadetarc)
- **Preprocessing**: Converted VOC-style XML annotations into YOLOv8 format with 3 classes: `Sedan`, `SUV`, and `Taxi`.

---

## 🧠 Novelty

- Fine-tuned YOLOv8 for vehicle detection across 3 defined classes.
- Used DeepSORT for ID consistency and robust multi-vehicle tracking.
- Implemented accurate **speed estimation** using pixel-based motion and FPS calibration.
- Built a modular, real-time pipeline for detection → tracking → counting → speed violation.

---

## 👩‍💻 Contributors

1. Parnika Chilukuri - PES1UG22EC189  
2. Pragati Ramesh - PES1UG22EC197  

---

## ⚙️ Steps to Run

1. **Clone Repository**  
   ```bash
   git clone https://github.com/your-username/Traffic-Surveillance-YOLOv8.git
   cd Traffic-Surveillance-YOLOv8
