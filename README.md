# Flower Image Classification (Computer Vision)
Computer Vision Assignment

## Overview
This project implements an image classification model to recognise five flower species (daisy, dandelion, rose, sunflower, tulip) using deep learning. The goal was to improve a baseline convolutional neural network and evaluate performance against computational cost.

## Approach
- Started with a baseline CNN model
- Applied:
  - Data augmentation (random crops, flips, colour jitter)
  - Hyperparameter tuning (learning rate, batch size)
  - Label smoothing
- Used transfer learning with EfficientNet-B0
- Conducted ablation studies to evaluate each modification

## Results
- Baseline accuracy: 62.27%
- Final accuracy: 92.59%
- Computational cost: 0.4206 GFLOPs
- Demonstrated trade-off between accuracy and efficiency

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
