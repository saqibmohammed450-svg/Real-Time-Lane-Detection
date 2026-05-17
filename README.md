# 🚗 Real-Time Lane Detection System

<p align="center">
  
![Python](https://img.shields.io/badge/PYTHON-3.7+-blue?style=for-the-badge&logo=python)
![OpenCV](https://img.shields.io/badge/OPENCV-COMPUTER_VISION-green?style=for-the-badge&logo=opencv)
![Tkinter](https://img.shields.io/badge/TKINTER-GUI-orange?style=for-the-badge)
![MoviePy](https://img.shields.io/badge/MOVIEPY-VIDEO_PROCESSING-red?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NUMPY-ARRAY_COMPUTING-purple?style=for-the-badge&logo=numpy)
![Status](https://img.shields.io/badge/STATUS-ACTIVE-success?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-teal?style=for-the-badge)

</p>

---

> **Real-Time Lane Detection System** is a Computer Vision project that detects road lane markings from video input using OpenCV and image processing techniques. The system uses edge detection, Hough Transform, and ROI masking to identify lane boundaries and display them through a simple Tkinter GUI interface.

---

# ✨ Features

- 🚘 Real-time lane line detection
- 🎥 Video frame processing
- 📌 Canny Edge Detection
- 📍 Hough Line Transform
- 🛣️ Region of Interest (ROI) masking
- 🖥️ Tkinter GUI support
- 📹 Output video generation
- ⚡ Smooth lane visualization

---

# 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- Tkinter
- Pillow (PIL)
- MoviePy
- Matplotlib

---

# ⚙️ How It Works

1. Captures video frames
2. Converts frames to grayscale
3. Detects white and yellow lane colors
4. Applies Gaussian Blur to remove noise
5. Performs Canny Edge Detection
6. Applies ROI masking
7. Detects lanes using Hough Transform
8. Draws lane lines on frames
9. Generates processed output video

---

# 📂 Project Structure

```bash
Real-Time-Lane-Detection/
│
├── main.py
├── gui.py
├── test2.mp4
├── output.mp4
├── logo.png
└── README.md
```

---

# 📥 Installation

Clone the repository:

```bash
git clone https://github.com/saqibmohammed450-svg/Real-Time-Lane-Detection.git
cd Real-Time-Lane-Detection
```

Install dependencies:

```bash
pip install opencv-python numpy pillow moviepy matplotlib
```

---

# ▶️ Run the Project

Run the lane detection system:

```bash
python main.py
```

Run the GUI application:

```bash
python gui.py
```

---

# 🚀 Future Improvements

- Live webcam support
- Curved lane detection
- Deep learning integration
- Traffic sign detection
- Steering angle prediction
- Performance optimization

---
