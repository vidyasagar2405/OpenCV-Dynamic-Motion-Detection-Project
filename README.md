# OpenCV-Dynamic-Motion-Detection-Project


This project demonstrates a **Dynamic Motion Detection System** built using **Python and OpenCV**, where users can **interactively draw multiple Regions of Interest (ROIs)** on a live video feed to detect motion **only inside those selected areas**.

---

## 🎯 Project Overview

Unlike static detection, this project allows **dynamic ROI selection** — users can manually draw one or more rectangles on the video stream to mark regions they want to monitor.
Once ROIs are created, the system automatically starts detecting motion **within each selected area**, displaying a **motion Detected alert** whenever activity occurs.

This project showcases real-time **computer vision, image differencing, and interactive ROI selection** concepts.

---

## 🧩 Features

* 🎥 **Real-Time Motion Detection** using webcam
* 🖱️ **Draw Multiple ROIs Dynamically** using mouse
* 🧠 **Motion Detection inside ROIs only**
* 🚨 **Motion Alert** displayed at the top of each ROI
* 🗑️ **Option to Delete/Recreate ROIs**
* 🪄 **Live ROI Drawing Preview for accuracy**

---

## 🛠️ Built With

* **Python 3.x**
* **OpenCV (cv2)**
* **NumPy**

---

## 🚀 How It Works

1. Capture video frames in real-time using OpenCV.
2. Draw one or multiple **rectangular ROIs** interactively on the video.
3. Each frame's all created ROI's is compared to a it's previous frame ROI's.
4. The system detects changes **only within each ROI**.
5. Displays a **motion detected alert** above the active ROI when motion occurs.
6. ROIs can be cleared or redrawn during runtime.

---

## 💻 Installation & Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/<vidyasagar2405>/OpenCV-Dynamic-Motion-Detection-Project.git
   cd OpenCV-Dynamic-Motion-Detection-Project
   ```

2. **Install Dependencies:**

   ```bash
   pip install opencv-python numpy
   ```

3. **Run the Project:**

   ```bash
   python dynamic_motion_detection.py
   ```

---

## 📸 Demo

[demo_video](https://github.com/)<your-username>/OpenCV-Dynamic-Motion-Detection-Project/assets/demo.mp4

---


## 🧑‍💻 Author

**[Vidya sagar]**
💼 GitHub: [vidyasagar2405](https://github.com/vidyasagar2405)

---

