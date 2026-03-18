# 🚀 YOLO (Ultralytics) Projects Collection
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A professional collection of computer vision projects built using YOLO (You Only Look Once) by Ultralytics. This repository demonstrates core concepts of object detection, tracking, segmentation, and pose estimation using Python, OpenCV, and YOLOv8.

**📌 Overview**<br>
This repository contains multiple beginner-to-intermediate level projects that showcase how to use YOLO models for real-world applications such as object detection, tracking, counting, and human pose estimation.

**🛠️ Tech Stack**
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy

**📂 Project Structure**<br>
├── yolo_checks.py
├── yolo_basic.py
├── yolov8_n_opencv.py
├── customer_detection.py
├── object_tracking.py
├── object_counting.py
├── object_segment.py
├── pose_estimation.py
└── README.md

****📖 Project Descriptions**
**1. yolo_checks.py**
- Basic script to verify YOLO installation, model loading, and environment setup.

**2. yolo_basic.py**
- Introduction to YOLO object detection with simple image input and bounding box output.

**3. yolov8_n_opencv.py**
- Integration of YOLOv8 with OpenCV for real-time object detection using webcam/video stream.

**4. customer_detection.py**
- Detects and identifies customers in a retail-like environment using object detection.

**5. object_tracking.py**
- Tracks moving objects across frames using YOLO and tracking algorithms.

**6. object_counting.py**
- Counts objects passing through a defined region or line in a video stream.

**7. object_segment.py**
- Performs instance segmentation to detect object boundaries and masks.

**8. pose_estimation.py**
- Detects human body keypoints for pose estimation using YOLO models.

**⚙️ Installation**<br>
**1.Clone the repository:**<br>
git clone https://github.com/your-username/yolo-projects.git
cd yolo-projects

**2.Create a virtual environment (optional but recommended):**<br>
python -m venv venv
venv\Scripts\activate  

**3.Install dependencies:**<br>
pip install -r requirements.txt

**▶️ Usage**<br>
Run any script using:<br>
python filename.py

****📊 Features**
- Real-time object detection
- Multi-object tracking
- Object counting in video streams
- Instance segmentation
- Human pose estimation
- Easy-to-understand implementation

**📌 Requirements**<br>
Make sure you have:
- Python 3.8+
- GPU (optional, for faster performance)<br>
Example requirements.txt:
- ultralytics
- opencv-python
- numpy
