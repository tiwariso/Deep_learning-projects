# 🧠 CIFAR-10 Image Classification using CNN

A Deep Learning project that implements a **Convolutional Neural Network (CNN)** using TensorFlow/Keras to classify images from the **CIFAR-10 dataset** into 10 different categories.

The model includes **Batch Normalization, Dropout, Data Augmentation, Convolutional Layers, Max Pooling, and Softmax Classification**.

---

## 📌 Experiment Overview

The objective of this experiment is to:

- Load and preprocess the CIFAR-10 dataset
- Normalize image pixel values
- Convert class labels into one-hot encoded vectors
- Build a CNN architecture for image classification
- Apply data augmentation to improve generalization
- Train the CNN model
- Evaluate classification accuracy
- Generate predictions on test images
- Compare predicted and actual class labels
- Explore techniques that could improve accuracy beyond 95%

The implementation is based on the submitted Deep Learning Lab 7 notebook. :contentReference[oaicite:0]{index=0}

---

## 📊 Dataset

### CIFAR-10

CIFAR-10 contains **60,000 color images** belonging to 10 classes.

Each image has a resolution of:

```text
32 × 32 × 3


## 📊 Results

The CNN was trained for **5 epochs** using data augmentation.

### Training Performance

The training and validation accuracy improved consistently across all 5 epochs.

| Epoch | Training Accuracy | Validation Accuracy |
|------:|------------------:|--------------------:|
| 1     | 39.61%            | 52.26%             |
| 2     | 55.97%            | 63.16%             |
| 3     | 63.18%            | 66.66%             |
| 4     | 67.34%            | 68.33%             |
| 5     | **70.23%**        | **71.69%**         |

### Final Test Accuracy

```text
🎯 Test Accuracy: 71.69%
