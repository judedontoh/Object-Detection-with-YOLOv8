# YOLOv8 Object Detection, Image Segmentation, and Classification

## Project Overview

Created a tool that uses the YOLOv8 model for detecting, segmenting, and classifying objects in urban scenes. The model can accurately find and identify various objects such as people, buses, backpacks, and traffic lights. This project shows how YOLOv8 can work in real-time to detect objects.

### Motivation
This project aims to explore how well YOLOv8 can detect objects and its uses in real-world scenarios like autonomous driving and urban surveillance. Accurate and fast object detection can significantly enhance applications that need quick and reliable identification of objects.

### Key Features:
- **Object Detection**: Finds and marks objects within images.
- **Image Segmentation**: Separates objects from the background.
- **Classification**: Labels detected objects into different categories.

### Applications:
- **Autonomous Driving**: Identifies pedestrians, vehicles, and traffic signals.
- **Surveillance**: Monitors and identifies objects in real-time for security.
- **Smart City Solutions**: Helps manage urban areas with real-time object detection.

### Model Training:
The YOLOv8 model was trained on a dataset of urban scenes. This ensures it can quickly and accurately recognize different objects, making it useful for real-time applications.

### Getting Started:
1. **Mount Google Drive**: Ensure your Google Drive is mounted to access necessary datasets and save outputs.
   ```python
   from google.colab import drive
   drive.mount('/content/drive')

2. **Set Runtime to GPU**: Before running the script, ensure that the runtime is set to GPU for optimal performance.
Required Libraries:
Import all necessary libraries to get started with the implementation.


### Code and Resources Used
- **Python Version**: 3.7
  **Packages**: pandas, numpy, sklearn, opencv-python, torch, yolov8
-**Requirements**: Install the necessary packages using pip install -r requirements.txt
  
### Data Collection
Data was collected from an urban scene dataset, focusing on various objects typically found in city environments. Key attributes extracted include object types, bounding box coordinates, and image data.


### Model Explainability
The YOLOv8 model was chosen for its high accuracy and speed. After training, it performed well in detecting and classifying objects in test images. The model's decisions were interpreted using visualizations to understand which features were most important.

### Model Application
Instead of just images, the model can also be applied to videos. This allows real-time object detection in video streams, demonstrating the model's capabilities in dynamic environments as seen below.

![Object Detection Video](detection-video-to-gif-converter.gif)
