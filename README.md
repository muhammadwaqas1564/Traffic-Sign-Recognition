# Traffic-Sign-Recognition
A deep learning-based traffic sign recognition system using ResNet-50 and MobileNetV2, leveraging transfer learning for high accuracy.


# Traffic Sign Recognition using Deep Learning

## Overview
Traffic Sign Recognition (TSR) is an essential part of modern intelligent transportation systems, improving road safety by accurately detecting and classifying traffic signs in real time. This project utilizes **ResNet-50** and **MobileNetV2** with transfer learning to enhance performance.

## Models Used
- **MobileNetV2**: A lightweight CNN optimized for mobile and embedded vision applications.
- **ResNet-50**: A deep CNN using residual learning for effective feature extraction in large-scale image classification.

## Dataset
- **German Traffic Sign Recognition Benchmark (GTSRB)** from Kaggle.
- Contains **43 traffic sign classes**.

## Methodology
1. **Data Preprocessing**: Image formatting, augmentation, and dataset splitting (train/test/validation).
2. **Transfer Learning**: Using pre-trained ResNet-50 and MobileNetV2 on ImageNet.
3. **Training**: Fine-tuning the models for accurate traffic sign classification.

## Results
The combination of **ResNet-50** and **MobileNetV2** achieves high accuracy while maintaining efficiency, making it suitable for real-time applications.


## How to Run
1. Clone the repository:
   git clone https://github.com/your-username/traffic-sign-recognition-dl.git
