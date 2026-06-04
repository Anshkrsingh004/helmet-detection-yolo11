# Helmet Detection System using YOLO11

## Overview

This project implements a custom helmet detection system using YOLO11 and Roboflow. The model detects whether a rider is wearing a helmet or not from images.

## Features

* Custom dataset created and managed using Roboflow
* Data preprocessing and augmentation
* YOLO11 model training on Google Colab GPU
* Evaluation using Precision, Recall, F1 Score, and mAP
* Inference on unseen images

## Dataset

* Classes:

  * With Helmet
  * Without Helmet

Dataset preprocessing:

* Auto Orient
* Resize to 512x512

Augmentations:

* Horizontal Flip
* Rotation
* Brightness
* Exposure

## Technologies Used

* Python
* YOLO11
* Roboflow
* OpenCV
* PyTorch
* Google Colab

## Results

* Precision: XX%
* Recall: XX%
* F1 Score: XX%
* mAP50: XX%

## Project Workflow

Dataset Collection → Annotation → Roboflow Versioning → YOLO11 Training → Evaluation → Inference

## Sample Prediction

(Add prediction screenshots here)
