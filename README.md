# Object and Sub-Object Detection Using YOLOv8 with JSON Output

## Overview

This project implements an object detection system using YOLOv8, capable of detecting objects and their associated sub-objects in images. The detection results are saved in a hierarchical JSON format, enabling easy access to the detected objects and their sub-objects. The system is designed to process custom datasets and can be easily extended for other detection tasks.

## Key Features

- **Object and Sub-Object Detection**: Detects main objects (e.g., "Person", "Car") and their associated sub-objects (e.g., "Helmet", "Tire").
- **JSON Output**: Saves detection results in a structured JSON format for easy retrieval and processing.
- **Real-Time Processing**: Capable of processing images and video streams in real-time with YOLOv8.
- **Modular**: Easily extendable to include new object-sub-object pairs for different tasks.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- YOLOv8 (Ultralytics package)
- PyTorch
- OpenCV
- `yaml`
- `json`

You can install the required dependencies using pip:

```bash
pip install ultralytics opencv-python torch pyyaml
```
## Directory Structure


- `data/`: Contains images and labels for training, validation, and testing.
    - `train/images/`: Folder containing the training images.
    - `train/labels/`: Folder containing the corresponding labels for the training images.
    - `valid/images/`: Folder containing the validation images.
    - `valid/labels/`: Folder containing the corresponding labels for the validation images.
    - `test/images/`: Folder containing the test images.
    - `test/labels/`: Folder containing the corresponding labels for the test images.
    - `data.yaml`: Configuration file containing paths to images and labels, as well as class names.


