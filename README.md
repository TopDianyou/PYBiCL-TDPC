Hysteretic Temporal Damage Prediction Network for Semi-Rigid PC Joints
This repository provides an implementation of a deep learning-based approach for predicting hysteretic temporal damage in semi-rigid precast concrete (PC) joints under earthquake scenarios using single-source image sequences.

Overview
The model utilizes a combination of:

Bidirectional Convolutional LSTM (BiConvLSTM)

Feature Pyramid Networks

Transformer Encoders

Multi-scale temporal and spatial feature fusion

to predict damage progression over time from image sequences captured under seismic conditions.

Key Features
Processes image sequences with associated timestamps

Supports multi-scale feature extraction and fusion

Includes data augmentation for training robustness

Provides multiple evaluation metrics (MAE, MSE, DTW, etc.)

Model Architecture
The network consists of several key components:

Feature Pyramid Network for multi-scale feature extraction

Time Encoder for incorporating temporal information

Transformer Encoders for sequence modeling

Bidirectional ConvLSTM modules for spatiotemporal processing

Multi-stage feature fusion and prediction

Dataset
The model is trained on the KITTI-based PC joint damage dataset (available via Baidu Netdisk).
https://pan.baidu.com/s/19wgFWqLQyFOdlgtBBe01qA 

Usage
Prepare dataset according to the structure in Trainer.py

Train model using the provided training script

Evaluate using the evaluation metrics provided
