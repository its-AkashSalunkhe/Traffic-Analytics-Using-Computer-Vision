# 🧍 Real-Time Body Pose Tracking

A real-time Computer Vision project that detects and tracks human body poses from video using **MediaPipe BlazePose** and **OpenCV**. The application processes each video frame, identifies body landmarks, draws the skeletal structure, and saves the processed output video.

---

## 📌 Project Overview

Human Pose Estimation is one of the most popular applications of Computer Vision. It enables computers to detect and understand human body movements by identifying key body joints.

In this project, MediaPipe's **BlazePose** model is used to detect body landmarks from an input video, while OpenCV handles video processing, visualization, and output generation.

---

## 🚀 Features

- 🎥 Reads an input video
- 🧍 Detects full-body landmarks in every frame
- 🔗 Draws pose skeleton connections
- ⚡ Real-time pose tracking
- 💾 Saves the processed video automatically
- 🖥️ Displays live tracking while processing

---

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe (BlazePose)

---

## 📂 Project Structure

```
Real-Time-Body-Pose-Tracking/
│
├── input_video.mp4
├── output_pose_detection.mp4
├── body_pose_tracking.py
├── requirements.txt
├── README.md
└── assets/
    ├── input.gif
    └── output.gif
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Real-Time-Body-Pose-Tracking.git
```

Move into the project directory

```bash
cd Real-Time-Body-Pose-Tracking
```

Install the required packages

```bash
pip install opencv-python mediapipe
```

---

## ▶️ How to Run

Update the input and output video paths inside the Python script.

```python
input_video = "path/to/input_video.mp4"
output_video = "path/to/output_pose_detection.mp4"
```

Run the application

```bash
python body_pose_tracking.py
```

Press **Q** to exit the video window.

---

## 🧠 How It Works

1. Load the input video.
2. Read frames one by one.
3. Convert each frame from BGR to RGB.
4. Pass the frame to MediaPipe BlazePose.
5. Detect body landmarks.
6. Draw pose connections on the frame.
7. Display the processed frame.
8. Save the processed video.

---

## 📸 Results

### Input Video

> *(Add a GIF or screenshot here)*

---

### Pose Tracking Output

> *(Add a GIF or screenshot here)*

---

## 💡 Applications

- Fitness Tracking
- Exercise Form Analysis
- Sports Analytics
- Gesture Recognition
- Human Activity Recognition
- Rehabilitation Monitoring
- Motion Capture

---

## 📈 Future Improvements

- Support webcam input
- Multi-person pose estimation
- Joint angle calculation
- Exercise repetition counter
- Yoga pose detection
- Squat and push-up detection
- Real-time performance analytics
- Streamlit web application

---

## 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project, feel free to fork the repository, create a feature branch, and submit a pull request.

---

## ⭐ If you found this project helpful

Please consider giving this repository a **Star ⭐**.