# Optimizing DNNs for Edge Device Deployment using Unstructured Pruning

## Project Overview

This project focuses on optimizing Deep Neural Networks (DNNs) for deployment on resource-constrained edge devices such as IoT systems, mobile devices, and embedded platforms.

The model was optimized using MobileNetV3-Small, Transfer Learning, Data Augmentation, and L1 Unstructured Pruning to reduce model size while maintaining high prediction accuracy.

---

## Problem Statement

Deep learning models often require significant memory and computational resources, making them difficult to deploy on edge devices.

The objective of this project was to:

- Reduce model size
- Improve computational efficiency
- Maintain high classification accuracy
- Enable deployment on edge devices

---

## Dataset

Dataset: Architectural Heritage Elements (AHE)

- Total Images: 10,235
- Classes: 10
- Categories include:
  - Altar
  - Apse
  - Bell Tower
  - Column
  - Dome
  - Gargoyle
  - Stained Glass
  - Vault

---

## Technologies Used

- Python
- PyTorch
- MobileNetV3-Small
- TensorBoard
- Transfer Learning
- Data Augmentation
- L1 Unstructured Pruning

---

## Methodology

### Data Preprocessing

- Image Resizing (224 × 224)
- Image Normalization
- Data Augmentation
- Train/Test Split

### Model Training

- MobileNetV3-Small
- Cross Entropy Loss
- Adam Optimizer
- Learning Rate Scheduler

### Model Optimization

- 40% L1 Unstructured Pruning
- Removal of low-importance weights
- Model compression for edge deployment

---

## Results

| Metric | Before Pruning | After Pruning |
|----------|----------|----------|
| Model Size | 5.96 MB | 3.64 MB |
| Accuracy | 90.74% | 93.87% |

### Key Achievements

- Reduced model size by 39%
- Improved accuracy by 3.13%
- Increased deployment efficiency
- Suitable for Edge AI applications

---

## Applications

- Edge AI
- IoT Devices
- Smart Cameras
- Mobile Applications
- Real-Time Image Classification

---

## Research Publication

Published Research Project:

Optimizing DNNs for Edge Device Deployment using Unstructured Pruning

---

## Author

Rohan S Dasogamath

Computer Science Engineer

KLE Technological University

GitHub: https://github.com/rohansdasogamath

LinkedIn:
https://www.linkedin.com/in/rohan-s-dasogamath-8098a0383
