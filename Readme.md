# Satellite Image Analysis for Border Monitoring

This project focuses on detecting and classifying objects such as tanks and infrastructure in satellite images to support real-time monitoring and surveillance near border areas. The custom object detection model uses YOLOv5, trained on the **xView** dataset, to identify items of interest, helping enhance border security by tracking movements, constructions, and infrastructure.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Labeling Data](#labeling-data)
- [Acknowledgments](#acknowledgments)
- [Future Work](#future-work)

---

## Project Overview
The main objectives of this project are:
- **Custom YOLOv5 Detection Model**: Build a YOLOv5-based detection model to identify specific classes like **tanks** and **infrastructure** in satellite images.
- **Real-Time Monitoring**: Enable real-time analysis of border areas by tracking significant objects and constructions.
- **Satellite Image Utilization**: Use the xView dataset for high-quality satellite imagery in training and evaluation.

## Dataset
- **Dataset**: [xView Dataset](https://xviewdataset.org)
- **Classes of Interest**: This model focuses on detecting tanks, infrastructure, and other relevant classes.

## Installation
1. Clone the YOLOv5 repository:
   ```bash
   git clone https://github.com/ultralytics/yolov5.git
   cd yolov5

## Labelling Data
- Used [Makesense.ai](https://www.makesense.ai/) and labelmg to label the data

## Acknowledgement
- **YOLOv5**: Ultralytics' YOLOv5 (https://github.com/ultralytics/yolov5)
- **xView Dataset**: High-resolution satellite images (https://xviewdataset.org)

## Future Work
- **Enhanced Model Accuracy**: Explore additional data or model architectures to improve detection accuracy.
- **Real-Time Edge Deployment**: Deploy the model to edge devices for live monitoring.
- **Additional Classes**: Expand the model to detect more classes of objects relevant to border monitoring.
