# Traffic Congestion Prediction

This repository contains the implementation of traffic congestion prediction, focusing on assessing and comparing the effectiveness of different algorithms for long-term traffic congestion prediction.

## Objective

The primary objective of this project is to evaluate various algorithms in predicting long-term traffic congestion. Two datasets are used: one obtained from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) and another generated from road traffic photos in Tirana. The data undergoes cleaning and preprocessing, incorporating a Convolutional Neural Network (CNN - [YOLO V8](https://github.com/ultralytics/ultralytics)) model for image processing and car counting. The YOLOv8 model was trained on a labeled car images dataset available at [this link](https://public.roboflow.com/object-detection/vehicles-openimages) using CUDA and PyTorch.
