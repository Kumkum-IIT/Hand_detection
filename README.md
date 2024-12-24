# Hand Landmark Detection Using MediaPipe Hands

This script uses MediaPipe's Hands solution to detect and visualize hand landmarks in images. It identifies the handedness (left or right hand) and specific landmark coordinates (e.g., index finger tip) and overlays the landmarks on the input images.

## Setup Instructions

1. **Install Dependencies**:
   ```bash
   pip install opencv-python mediapipe

## Load the images into the script using OpenCV, for example:
import cv2
images = {
    "image1": cv2.imread("images/image1.jpg"),
    "image2": cv2.imread("images/image2.jpg"),
}
