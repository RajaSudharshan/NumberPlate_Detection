# License Plate Recognition using OpenCV and EasyOCR

This project implements license plate detection and recognition using **OpenCV**, **imutils**, and **EasyOCR**. The code extracts the license plate from a car image and recognizes the text on the plate.

- **License Plate Detection**: Detects the license plate region from the image using edge detection and contour approximation.
- **Text Recognition**: Recognizes the license plate number using EasyOCR.
- **Text Annotation**: Annotates the image with the recognized license plate number.
- **Visual Feedback**: Displays intermediate steps including the grayscale, edge-detected, masked, cropped, and final annotated image.

The project requires the following packages:

- **OpenCV**: Open Source Computer Vision Library, a powerful toolkit for image and video analysis, which provides multiple methods for computer vision tasks, such as edge detection, contour approximation, and shape analysis.
- **EasyOCR**: A Python library for Optical Character Recognition (OCR) that supports multiple languages and simplifies text detection in images.
- **imutils**: A utility package that simplifies contour operations and common OpenCV tasks.
- **matplotlib**: Used for displaying images and results.
- **numpy**: For handling numerical operations in Python.

### Python Installation

Ensure that you have **Python 3.x** installed on your machine. You can check this by running the following command in your terminal or command prompt:

```bash
python --version

If Python is not installed, please download and install it from the official Website - https://www.python.org/downloads/
### Install dependencies:

To install the necessary dependencies, run:

```bash
pip install opencv-python opencv-python-headless matplotlib imutils easyocr numpy

### Clone the Repository: Download or clone this repository to your local machine.

```bash
git clone https://github.com/yourusername/license-plate-recognition.git

