# Autonomous Vehicle Detection and Segmentation

## Overview
This project focuses on implementing object detection and semantic segmentation for autonomous vehicles. The primary algorithms utilized are YOLOv5 for object detection and DeepLabV3+ for semantic segmentation.

## Object Detection with YOLOv5
1. **Model Architecture**: Defined the YOLOv5 model architecture, leveraging its capabilities for real-time object detection.
2. **Training Process**: Conducted the training process with built-in checkpointing to save the best-performing weights, ensuring optimal model performance.

## Semantic Segmentation of Indian Roads Using DeepLabV3+
1. **Dataset**: Used the Indian Driving Dataset (IDD) provided by IIIT Hyderabad.
2. **Training Pipeline**: 
   - Developed a training pipeline using TensorFlow’s Data API.
   - Loaded addresses of images and masks.
   - Created functions for reading, resizing, and normalizing images.
   - Constructed a `tf.data.Dataset` object for loading images and masks in batches.
3. **Model Architecture**: Defined the model architecture using the Xception pre-trained model as the base.
4. **Training Process**: Executed the training process and implemented checkpointing to save the best weights only.
5. **Inference and Deployment**: Made predictions on campus roads at IIT BHU and deployed the model into the autonomous vehicle of Team AVERERA.

## Conclusion
This project integrates advanced computer vision techniques for real-time object detection and road segmentation, contributing to the development of autonomous vehicle technology.
