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
---

## ⚙️ Tech Stack

| Component | Technology |
|-----------|------------|
| Hardware | NVIDIA Jetson Orin Nano |
| OS | Ubuntu 22.04 + JetPack 6.2 |
| Detection | YOLOv8 (custom trained) |
| Deep Learning | PyTorch 2.8.0 + CUDA 12.6 |
| Computer Vision | OpenCV 4.10 (CUDA-enabled) |
| Face Recognition | InsightFace ArcFace |
| Database | MongoDB Atlas + Local fallback |
| Dashboard | Node-RED |
| Language | Python 3.10 |

---

## 📊 Dashboard

![Dashboard](assets/screenshots/dashboard.png)

- Live camera feed
- Real-time violation alerts
- Statistics charts
- Cloud + local data sync
- PKT timezone support

---

## 🚀 Quick Start

### Prerequisites
- NVIDIA Jetson Orin Nano with JetPack 6.2
- Python 3.10
- MongoDB (local)
- Node-RED



---

## 📁 Models

Due to file size, trained models are not included in this repo.


---

## 👥 Team

Built as Final Year Project at [Your University Name]

| Name | Role |
|------|------|
| Ahmed Hasaan | Partner |
| Syed Mujtaba Ali Shah | Partner |
| Muhammad Thamer | Partner |

---

## 📄 License

MIT License — see [LICENSE](LICENSE)

---

<div align="center">
  Made with ❤️ by Team SLASH
</div>
