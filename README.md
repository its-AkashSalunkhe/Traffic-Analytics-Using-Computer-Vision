<h1 align="center">
🚗 Highway Vehicle Tracking System
</h1>

<p align="center">
Real-time vehicle detection and tracking using OpenCV and Computer Vision
</p>

 ---

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green?style=for-the-badge&logo=opencv)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

---

## 📖 Overview

This project demonstrates a **real-time highway vehicle detection and tracking system** using Computer Vision techniques.

The application processes highway video footage, detects moving vehicles using **background subtraction**, extracts the **Region of Interest (ROI)**, and tracks every detected vehicle with a unique ID using the **Euclidean Distance Tracking Algorithm**.

This project showcases practical applications of Computer Vision in **Intelligent Traffic Monitoring Systems (ITS)**.

---

# 🎯 Project Demo

## 🚘 Input Video

> *(Add GIF or screenshot here)*

---

## 🚗 Vehicle Detection

> *(Add GIF or screenshot here)*

---

## 🆔 Vehicle Tracking

> *(Add GIF or screenshot here)*

---

# ✨ Features

- 🎥 Reads highway video
- 🚗 Detects moving vehicles
- 🎯 Region of Interest (ROI) extraction
- 📦 Draws bounding boxes around vehicles
- 🆔 Assigns unique IDs to each vehicle
- ⚡ Real-time multi-object tracking
- 🖥️ Live visualization
- 📊 Background subtraction using MOG2

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| OpenCV | Image Processing |
| NumPy | Numerical Operations |
| Background Subtractor MOG2 | Vehicle Detection |
| Euclidean Distance Tracker | Vehicle Tracking |

---

# 📂 Project Structure

```text
Highway-Vehicle-Tracking-System/
│
├── assets/
│   ├── input.gif
│   ├── output.gif
│   ├── screenshot1.png
│   └── screenshot2.png
│
├── src/
│   ├── main.py
│   ├── tracker.py
│   └── white_mask.py
│
├── videos/
│   ├── highway.mp4
│   └── output.mp4
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Highway-Vehicle-Tracking-System.git
```

Move into the project

```bash
cd Highway-Vehicle-Tracking-System
```

Install dependencies

```bash
pip install opencv-python numpy
```

---

# ▶️ Running the Project

Update the video path inside the script.

```python
video_path = "videos/highway.mp4"
```

Run

```bash
python src/main.py
```

Press **ESC** to exit.

---

# 🧠 How It Works

### Step 1 — Load Video

The system reads highway footage frame-by-frame.

⬇️

### Step 2 — Region of Interest (ROI)

Only the road region is processed, reducing unnecessary computations.

⬇️

### Step 3 — Background Subtraction

MOG2 removes the static background and extracts moving vehicles.

⬇️

### Step 4 — Thresholding

Noise is removed and binary masks are generated.

⬇️

### Step 5 — Contour Detection

Contours identify individual vehicle candidates.

⬇️

### Step 6 — Vehicle Tracking

The Euclidean Distance Tracker assigns a unique ID to every detected vehicle and tracks its movement across frames.

⬇️

### Step 7 — Visualization

Bounding boxes and IDs are drawn in real time.

---

# 📈 Applications

- 🚦 Intelligent Traffic Monitoring
- 🚓 Smart City Surveillance
- 🚗 Vehicle Analytics
- 🚧 Highway Monitoring
- 🚘 Traffic Flow Analysis
- 🚨 Traffic Violation Detection
- 🅿️ Parking Management
- 🚖 Autonomous Driving Research

---

# 🚀 Future Improvements

- YOLOv8 Vehicle Detection
- DeepSORT Tracking
- Vehicle Counting
- Vehicle Speed Estimation
- Lane Detection
- Traffic Density Analysis
- Vehicle Classification
- Number Plate Recognition (ANPR)
- Streamlit Dashboard
- Real-time Webcam Support

---

# 📊 Skills Demonstrated

- Computer Vision
- Object Detection
- Multi-Object Tracking
- Background Subtraction
- OpenCV
- Python
- ROI Processing
- Image Thresholding
- Contour Detection

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, improve the project, and submit a pull request.

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐**.

It helps others discover the project and supports my learning journey in Computer Vision and Artificial Intelligence.
