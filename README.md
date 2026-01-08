# YOLOv8 Real-Time Object Detection

A YOLOv8-based object detection system for identifying and localizing 80+ object classes in images and videos with real-time inference.

## Features
- **Image Detection:** Single and batch image processing with confidence filtering
- **Video Processing:** Frame-by-frame detection with annotation and output video generation
- **Analysis:** Bounding box dimensions, size classification (Small/Medium/Large), and object counting
- **Class Filtering:** Detect specific object classes (e.g., person, car, bus)
- **Performance:** ~30 FPS inference speed on standard hardware

## Model Performance
- **Model:** YOLOv8 Nano (lightweight)
- **Classes Detected:** 80 (COCO dataset)
- **Confidence Threshold:** Configurable (default 50%)
- **Output:** Annotated images, videos, and JSON metadata

## Project Structure
- `yolov8_detection.ipynb` - Complete detection pipeline
- `detected_bus.jpg` - Sample detection output
- `detections.json` - Detection metadata
- `output_video.mp4` - Annotated video sample

## Technologies Used
- YOLOv8 / Ultralytics
- PyTorch
- OpenCV
- Python

## Results
See notebook for image detection, video processing, box dimension analysis, and object counting examples.
