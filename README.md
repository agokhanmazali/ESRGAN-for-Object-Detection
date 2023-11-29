# Super Resolution and Object Detection

This repository contains code for performing two primary functions: super-resolution on images using ESRGAN and object detection in images using SSD MobileNet V2.

## ESRGAN Super Resolution

### Overview
The script `esrgan_super_resolution.py` utilizes ESRGAN (Enhanced Super-Resolution Generative Adversarial Networks) to enhance the resolution of images.

### Usage

#### Requirements
- Python 3.x
- TensorFlow 2.x
- Matplotlib
- NumPy
- Pillow
- OpenCV
- TensorFlow Hub

#### Installation
1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.

#### Steps
1. Place the image you want to enhance in the specified `IMAGE_PATH`.
2. Run `esrgan_super_resolution.py`.
3. View the generated high-resolution image and its comparison.

## Object Detection using SSD MobileNet V2

### Overview
The script `object_detection.py` employs SSD MobileNet V2 for object detection in images.

### Usage

#### Requirements
- Python 3.x
- OpenCV

#### Installation
- Ensure OpenCV is installed (`pip install opencv-python`).

#### Steps
1. Provide the image you want to analyze.
2. Run `object_detection.py`.
3. View the detected objects with bounding boxes and labels.

## Use Cases

### Image Enhancement
This codebase is valuable for scenarios where image quality improvement or enhancement is necessary. For instance, it can be utilized in photography applications to upscale images without losing quality or in medical imaging for improving the clarity of scans.

### Object Recognition and Detection
The object detection module proves beneficial in various domains such as security and surveillance for identifying and tracking objects in real-time, in retail for inventory management through automated object recognition, and in autonomous vehicles for detecting pedestrians, vehicles, and obstacles on roads.

### Research and Development
Additionally, this code serves as a starting point for researchers and developers interested in exploring deep learning-based image processing. Specifically, it delves into super-resolution techniques like ESRGAN and object detection using lightweight models like SSD MobileNet V2. Its modular structure allows easy integration into other projects for experimentation and further enhancements.
