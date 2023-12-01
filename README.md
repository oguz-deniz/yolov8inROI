# yolov8inROI

# YOLOv8 Object Detection and Tracking in ROI 

## Overview

This YOLOv8 Object Detection and Tracking project leverage the YOLOv8 architecture for real-time object detection and tracking within a specified Region of Interest (ROI). This project is particularly useful for scenarios where you want to focus on monitoring and tracking objects within a specific area of interest in a video stream.

### Key Features

- **YOLOv8 Integration:** Utilizes the YOLOv8 architecture for robust and efficient object detection. The pretrained models used in this task are: yolov8n, yolov8s and yolov8m.
- **Region of Interest (ROI):** Define a specific area within the video frames to concentrate object detection and tracking efforts.
- **Object Tracking:** Implements a tracking mechanism to monitor and track objects across frames by using a simple thresholding logic between bounding boxes's centroids.
- **Customization:** Easily adjust ROI coordinates, YOLOv8 parameters, and output settings to suit your specific use case. The output videos and frames are also provided in this repo.
- **Open Source:** The project is open-source, allowing for contributions and customization.
