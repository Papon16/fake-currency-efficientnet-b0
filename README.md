Fake Currency Detection Using EfficientNet-B0

Project Overview

This project uses the EfficientNet-B0 deep learning model to classify currency note images into Real and Fake classes.

The project is implemented using Python, PyTorch, and Jupyter Notebook.

Objective

The main objective is to build an image classification model that can identify whether a currency note is real or fake from an input image.

Model

Model: EfficientNet-B0

Framework: PyTorch

Input Image Size: 224 × 224

Task: Binary Image Classification

Classes

Real

Fake

Tools and Technologies

Python

Jupyter Notebook

PyTorch

Torchvision

NumPy

Pandas

Pillow

Matplotlib

Seaborn

Scikit-learn

Dataset

Expected folder structure:

dataset/
├── Fake/
│   ├── fake_001.jpg
│   ├── fake_002.jpg
│   └── ...
└── Real/
    ├── real_001.jpg
    ├── real_002.jpg
    └── ...

The dataset itself is not included in this repository. Set the correct local dataset path in the Jupyter Notebook before running it.

Methodology

Currency Images
      ↓
Data Preprocessing
      ↓
Data Augmentation
      ↓
Train / Validation Split
      ↓
Pretrained EfficientNet-B0
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Real / Fake Prediction

Evaluation Metrics

Accuracy

Precision

Recall

F1 Score

Confusion Matrix

Classification Report

Project Structure

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

How to Run

1. Clone the repository

git clone https://github.com/Papon16/fake-currency-efficientnet-b0.git

2. Install dependencies

pip install -r requirements.txt

3. Open Jupyter Notebook

jupyter notebook

4. Open the notebook

Fake_Currency_EfficientNetB0.ipynb

5. Set your dataset path

Example:

DATASET_PATH = r"C:\Users\YourName\Desktop\dataset"

6. Run the notebook cells sequentially

The notebook trains EfficientNet-B0, evaluates the model, generates graphs and a confusion matrix, and predicts a new currency image.

Results

Add the generated result images to the results folder after training:

results/accuracy.png

results/loss.png

results/confusion_matrix.png

Model File

The trained model is saved as:

models/EfficientNetB0_Fake_Currency_Detection.pth

Note

This is an academic/deep-learning project. Prediction accuracy depends on the quality, size, balance, and diversity of the dataset.

Author

Papon Sarkar
