# SMART INFANT HEALTH MONITORING SYSTEM WITH IOT-BASED FAILOVER MECHANISMS FOR RURAL AREAS


This project combines **AI-based infant monitoring** with **remote heart rate estimation** using computer vision. It uses infrared-compatible grayscale inputs and supports **real-time monitoring** through a suite of deep learning models deployed efficiently on both CPU and GPU environments.

---

## 🧠 Features

### 🍼 Infant Activity Monitoring
- **Baby Presence Detection** – Detects presence or absence of baby.
- **Safe Sleep Detection** – Identifies unsafe sleep conditions (e.g., prone position, occluded face).
- **Posture Estimation** – Tracks baby posture using keypoint detection.
- **Emotion & Intrusion Detection** – Classifies baby emotions and detects intrusions into crib/room.

**Models Used:**
- `YOLOv8` – Baby detection, safe sleep classification, intrusion.
- `YOLOv11` – Pose and emotion estimation (custom-trained).

### ❤️ Remote Photoplethysmography (rPPG)
- **Facial ROI Extraction** – Automatically detects and tracks facial regions.
- **Color Space Conversion** – Converts RGB to YUV for improved pulse detection.
- **3D-CNN Architecture** – Lightweight 3D-CNN for temporal signal analysis.
- **Real-Time HR Estimation** – Estimates heart rate from face video in real time.

---

## 📂 Dataset

- Combined and preprocessed multiple open-source datasets.
- Converted to **grayscale for infrared (IR) support** to enable night-time monitoring.
- Pose and emotion labels annotated and verified for infant suitability.

---

## 🚀 Installation & Running Locally

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/infant-monitoring-ai.git
cd infant-monitoring-ai
