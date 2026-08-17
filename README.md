# Optimized AI-Generated Image Detection Using Genetic Algorithm and Deep Feature Hashing

## Overview

This repository contains my M.Tech dissertation project on **AI-generated image detection** using a combination of **deep feature extraction, handcrafted forensic features, Genetic Algorithm-based feature optimization, and machine learning classification**.

The objective is to distinguish between **real images and AI-generated images** by identifying discriminative visual and statistical patterns.

## Key Approach

The overall workflow consists of:

1. Image dataset preparation and preprocessing
2. Deep feature extraction using CNN-based models
3. Extraction of handcrafted forensic features
4. Feature engineering and representation
5. Genetic Algorithm-based feature optimization
6. Machine learning-based classification
7. Performance evaluation

## Features

The framework incorporates handcrafted forensic features based on:

- FFT
- DCT
- LBP
- GLCM
- Color statistics
- Noise patterns

Deep visual representations are combined with these handcrafted features to improve the detection capability.

## Technologies

- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- XGBoost
- ResNet-50
- Genetic Algorithm
- Computer Vision

## Dataset

The experiments were conducted using AI-generated and real-image datasets, including the **VQDM subset of the GenImage dataset**.

The project involved large-scale image processing and feature extraction.

## Results

The developed detection framework achieved:

- **97.94% detection accuracy**
- **55 handcrafted forensic features**
- Large-scale image processing


