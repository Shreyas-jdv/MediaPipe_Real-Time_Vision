# MediaPipe Real-Time Vision: Face & Hand Tracker with Finger Counting

A real-time computer vision application built with **OpenCV** and **MediaPipe** that simultaneously tracks facial contours and dual-hand landmarks while dynamically counting extended fingers.

---

## 🚀 Features

* **Real-Time Holistic Tracking:** Captures facial landmarks (`FACEMESH_CONTOURS`) and both left and right hand skeletal joints concurrently using MediaPipe's Holistic model.
* **Dynamic Finger Counting:** Programmatically evaluates landmark coordinates to count extended fingers on each hand in real-time.
* **Performance Monitoring:** Includes a live Frame Per Second (FPS) counter overlaid directly on the video stream.
* **Optimized Processing:** Utilizes NumPy array flag manipulation (`image.flags.writeable = False`) to maximize inference speed.

---

## 📋 Prerequisites

Make sure you have Python installed (preferably Python 3.8 to 3.11 for optimal MediaPipe compatibility). You will need a functioning webcam connected to your system.

---

## 📦 Installation & Setup

1. **Clone or Download** this repository/script to your local machine.

2. **Install the required dependencies** using pip:
   ```bash
   pip install opencv-python mediapipe
