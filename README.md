# Deep Face Recognition Pipeline

This project implements an end-to-end facial recognition system using Deep Learning techniques. 
The pipeline is composed of two main stages:

1. Face Detection using MTCNN
2. Face Recognition (classification) using Transfer Learning with MobileNetV2 and TensorFlow

The system is capable of detecting multiple faces in a single image and identifying each individual using a trained classification model.

## 🔍 Project Overview

- Face detection is performed using the MTCNN algorithm.
- Detected faces are cropped, normalized, and resized.
- Face recognition is performed using a Convolutional Neural Network trained with Transfer Learning.
- The model is trained only on facial images, improving robustness and generalization.
- Data augmentation techniques are applied to reduce overfitting.
- The project was developed and executed in Google Colab.

## 🧠 Technologies and Tools

- Python
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- MTCNN
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## 📂 Dataset

The dataset consists of facial images organized in the following structure:

dataset/

  ├── train/

  │ ├── class_1/

  │ ├── class_2/

  │ └── ...

  └── val/

  ├── class_1/

  ├── class_2/

  └── ...



Each class represents a different individual.

## 🎯 Features

- Multi-face detection in images
- Facial recognition with confidence score
- Data augmentation to improve generalization
- Early stopping and model checkpointing
- Modular and reusable pipeline for future projects

## 🚀 Use Cases

- Academic projects
- Computer Vision studies
- Face recognition systems
- Deep Learning experimentation
- Portfolio projects in Data Science and AI

## 📌 Author

Developed for educational purposes, focusing on Deep Learning, Computer Vision, and practical applications of Neural Networks.


