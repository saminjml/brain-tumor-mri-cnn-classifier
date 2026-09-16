# Brain Tumor MRI Classification Using CNN

A deep learning project for binary classification of brain MRI images into two classes:

- `yes`: Brain tumor detected
- `no`: No brain tumor detected

This project uses a custom Convolutional Neural Network (CNN) implemented with TensorFlow and Keras.

> This project is intended for educational and research purposes only. It is not a medical diagnostic system.

## Project Overview

The model receives grayscale brain MRI images and predicts whether a tumor is present.

The main workflow includes:

1. Loading the MRI image dataset
2. Splitting the data into training and validation sets
3. Preprocessing and resizing images
4. Building a CNN model
5. Training with validation monitoring
6. Evaluating the model using classification metrics
7. Visualizing predictions and the confusion matrix

## Dataset

The dataset contains two classes:

| Class | Description | Number of Images |
|---|---|---:|
| `no` | MRI image without a brain tumor | 1,500 |
| `yes` | MRI image with a brain tumor | 1,530 |
| **Total** |  | **3,030** |

The dataset is divided into:

- 80% training data: 2,424 images
- 20% validation data: 606 images

The expected directory structure is:
```text
d1/
├── no/
│   ├── image_001.jpg
│   ├── image_002.jpg
│   └── ...
└── yes/
├── image_001.jpg
├── image_002.jpg
└── ...
