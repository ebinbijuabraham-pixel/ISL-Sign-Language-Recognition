# Indian Sign Language Recognition using Transfer Learning

## Overview

This project implements Indian Sign Language recognition using Transfer Learning with MobileNetV2 and TensorFlow.

## Dataset

Total Images: 42,745

Classes: 35

Digits: 1–9

Letters: A–Z

## Technologies Used

- TensorFlow
- Keras
- MobileNetV2
- Kaggle GPU
- Python
- Matplotlib
- Seaborn

## Model Architecture

Input (224×224)

↓

MobileNetV2

↓

GlobalAveragePooling

↓

Dropout

↓

Dense Softmax Layer

## Results

Test Accuracy: 100%

Test Loss: 1.38e−05

## Features

- Transfer Learning
- GPU Training
- Confusion Matrix
- Classification Report
- Saved Model
