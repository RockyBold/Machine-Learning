# ResNet50-Based Image Classification Model

This repository contains a TensorFlow/Keras implementation of a **binary image classification model** using **ResNet50 transfer learning**. The model is designed for image datasets organized in directory format and includes data augmentation, training, validation, and model saving.

## 🚀 Features
- Pre-trained **ResNet50** backbone (ImageNet weights)
- Custom fully connected layers with dropout
- Data augmentation using `ImageDataGenerator`
- Binary classification with sigmoid activation
- Automatic train/validation split
- Model saved in `.keras` format

## 🧠 Model Architecture
- ResNet50 (without top layers)
- Flatten layer
- Dense (512 units, ReLU)
- Dropout (0.5)
- Output layer (Sigmoid for binary classification)

## 📂 Dataset Structure
The dataset should be organized as:
