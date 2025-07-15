# Weed Detection System 🌿🔍

An end-to-end deep learning pipeline for detecting and classifying 9 species of weeds using object detection (YOLOv11) and image classification (ResNet50). Built for real-time agricultural monitoring using the DeepWeeds dataset.

## 🚀 Features

- ⚡ Real-time weed detection using YOLOv11
- 🧠 Species classification with ResNet50 (Tensorflow)
- 🔁 Cross-framework integration: TensorFlow for preprocessing, Tensorflow for classification
- 🎯 Achieved 94% test accuracy and high per-class F1 scores
- 📈 Custom training loops and performance monitoring
- 🗂 Efficient image loading via `tf.data` API

## 🗃 Dataset

- **DeepWeeds**: A publicly available dataset containing 17,509 labeled images across 9 weed species and negative samples.
- Source: [Dataset](https://www.kaggle.com/datasets/enoshreddy/deepweeds)

## 🛠️ Tech Stack

- YOLOv11 for object detection
- ResNet50 (Tensorflow) for classification
- TensorFlow (for image preprocessing)
- Python, NumPy, Matplotlib, OpenCV, tf.data API
