<div align="center">
  <img src="assets/slash_logo.png" width="200"/>
  
  # SLASH — Smart Surveillance System
  
  **Real-time edge AI surveillance deployed on NVIDIA Jetson Orin Nano**
  
  ![Python](https://img.shields.io/badge/Python-3.10-blue)
  ![PyTorch](https://img.shields.io/badge/PyTorch-2.8.0-orange)
  ![OpenCV](https://img.shields.io/badge/OpenCV-4.10-green)
  ![CUDA](https://img.shields.io/badge/CUDA-12.6-brightgreen)
  ![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green)
  ![License](https://img.shields.io/badge/License-MIT-yellow)
</div>

---

##  What is SLASH?

SLASH is an intelligent edge surveillance system that detects 
public violations in real time — without cloud dependency.

Built as a Final Year Project and deployed on NVIDIA Jetson Orin Nano.

---

## 🔍 What It Detects

| Violation | Method | Confidence |
|-----------|--------|------------|
| 🚬 Smoking | YOLOv8 + Pose estimation | HIGH/MEDIUM |
| 🗑️ Littering | Object tracking + velocity | HIGH/MEDIUM |
| ⏰ Loitering | Dwell time analysis | MEDIUM |
| 👤 Watchlist faces | InsightFace ArcFace | HIGH |

---

##  System Architecture
