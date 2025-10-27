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



## 💻 Installation & Setup

### 🧠 **Option 1: Run in Jupyter Notebook**

If you’re using **Jupyter Notebook**, follow these steps:

1. **Install required libraries (if not already installed):**

   ```bash
   pip install opencv-python numpy
   ```

2. **Open Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

3. **Load your notebook file** (for example:
   `Dynamic_Motion_Detection.ipynb`).

4. **Run the Cell** — the webcam will open and display the interactive motion detection window.

---

### 💻 **Option 2: Run as a Python Script**

1. **Clone this repository:**

   ```bash
   git clone https://github.com/vidyasagar2405/OpenCV-Dynamic-Motion-Detection-Project.git
   cd OpenCV-Dynamic-Motion-Detection-Project
   ```

2. **Install dependencies:**

   ```bash
   pip install opencv-python numpy
   ```

3. **Run the script:**

   ```bash
   python dynamic_motion_detection.py
   ```


---

## 📸 Demo

[demo_video](https://youtu.be/NWKQXQL6vVQ)

---


## 🧑‍💻 Author

**[Vidya sagar]**
💼 GitHub: [vidyasagar2405](https://github.com/vidyasagar2405)


