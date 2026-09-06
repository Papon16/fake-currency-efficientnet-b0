# Fake Currency Detection Using EfficientNet-B0

## Project Overview

This project detects whether a currency note is Real or Fake using the EfficientNet-B0 deep learning model.

## Objective

The main objective of this project is to develop an image classification model that can classify currency notes into two categories:

- Real
- Fake

## Model

EfficientNet-B0

## Framework

PyTorch

## Programming Language

Python

## Development Environment

Jupyter Notebook

## Dataset

The dataset contains images of real and fake currency notes.

The dataset is divided into two classes:

- Real
- Fake

## Image Preprocessing

Images are resized to 224 × 224 pixels and normalized using the ImageNet mean and standard deviation.

Data augmentation is applied during training.

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Project Structure

```text
fake-currency-efficientnet-b0/
│
├── Fake_Currency_EfficientNetB0.ipynb
├── requirements.txt
├── README.md
│
├── results/
│   ├── accuracy.png
│   ├── loss.png
│   └── confusion_matrix.png
│
└── models/
    └── EfficientNetB0_Fake_Currency_Detection.pth