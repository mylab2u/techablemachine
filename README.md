# techablemachine


# Access
https://raw.githack.com/mylab2u/techablemachine/main/index.html


Probability 0.00–0.10: Red

0.11–0.25: Orange

0.26–0.50: Yellow

0.51–0.75: Lime

0.76–1.00: Green

# 🔍 ระบบตรวจสอบ และวิเคราะห์บาดแผล (Wound Detection System) V1.0.3

A web-based AI application for real-time **skin wound detection** using webcam and a machine learning model from Teachable Machine (TensorFlow.js).  
Designed to assist healthcare professionals in **visual classification** of skin conditions, such as **Necrotizing Fasciitis (โรคเนื้อเน่า)**.

---

## 🌟 Features

- 📷 Select **Front / Back Camera**
- 🧠 Real-time **Machine Learning Prediction**
- 📊 Visual feedback with **color-coded progress bars**
- 🔍 Access to wound-specific details
- 🛑 Start / Stop camera control
- 📱 Mobile-friendly & Responsive layout

---

## 🚀 Live Demo Pages

- [📸 กล้องหน้า (Front Camera)](frontpage3.html)
- [📸 กล้องหลัง (Back Camera)](backpage3.html)
- [🔎 อ่านเกี่ยวกับโรคเนื้อเน่า (Necrotizing Fasciitis)](necrotizing-fasciitis.html)

---

## 🧠 Machine Learning Model

- **Hosted via Teachable Machine**  
  URL: [`https://teachablemachine.withgoogle.com/models/nGMPLQljN/`](https://teachablemachine.withgoogle.com/models/nGMPLQljN/)
- **Runs entirely in the browser** using TensorFlow.js

---

## 🛠️ Tech Stack

- HTML5 / CSS3
- Vanilla JavaScript
- TensorFlow.js
- Teachable Machine
- Google Fonts (Roboto)

---

## 🧪 How It Works

1. User selects a camera and clicks "สแกน" (Scan).
2. Webcam initializes and starts streaming.
3. Trained model classifies the image from webcam in real-time.
4. Each class result is displayed with:
   - Class name
   - Confidence value (as percentage)
   - A progress bar with color coded by confidence level:

| Confidence (%) | Color    |
|----------------|----------|
| 0–10%          | 🔴 Red   |
| 10–25%         | 🟠 Orange|
| 25–50%         | 🟡 Yellow|
| 50–75%         | 🟢 Lime  |
| 75–100%        | ✅ Green |

---

## 📦 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wound-detection-webapp.git
   cd wound-detection-webapp
