# Traffic Congestion Prediction

This repository contains the implementation of traffic congestion prediction, focusing on assessing and comparing the effectiveness of different algorithms for long-term traffic congestion prediction.

## Objective

The primary objective of this project is to evaluate various algorithms in predicting long-term traffic congestion. Two datasets are used: one obtained from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/traffic-prediction-dataset) and another generated from road traffic photos in Tirana. The data undergoes cleaning and preprocessing, incorporating a Convolutional Neural Network (CNN - [YOLO V8](https://github.com/ultralytics/ultralytics)) model for image processing and car counting. The YOLOv8 model was trained on a labeled car images dataset available at [this link](https://public.roboflow.com/object-detection/vehicles-openimages) using CUDA and PyTorch.

## Project Structure

- **yolov8-car-detection:** This file contains the model responsible for detecting cars in pictures, contributing to the creation of a time series dataset with images from Tirana.

- **predictions/ARIMA:** Folder containing predictions using the AutoRegressive Integrated Moving Average (ARIMA) model.

- **predictions/GRU:** Folder containing predictions using the Gated Recurrent Unit (GRU) model.

- **predictions/LR_SVR:** Folder containing predictions using Linear Regression (LR) and Support Vector Regression (SVR) with various kernels.

    - **SVR_Kernels:**
      - **Linear Kernel:** 
      - **Polynomial Kernel:** 
      - **Sigmoid Kernel:** 
      - **RBF Kernel:** 
      - **Precomputed Kernel:** 
      - **Custom Kernel:** 
