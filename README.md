# 🖼️ CIFAR-10 Image Classification using CNN (PyTorch)

A Deep Learning project that classifies images from the CIFAR-10 dataset into 10 different object categories using a custom-built Convolutional Neural Network (CNN) implemented in PyTorch.

---

## 📌 Project Overview

This project demonstrates the complete workflow of image classification using deep learning. A custom CNN architecture was designed, trained, and evaluated on the CIFAR-10 dataset using PyTorch.

The model learns hierarchical image features through convolutional layers and predicts one of the ten object classes.

---

## 🚀 Features

- End-to-end Deep Learning pipeline
- Custom CNN architecture
- Image normalization
- Multi-class image classification
- PyTorch implementation
- Adam Optimizer
- CrossEntropy Loss
- Test accuracy evaluation

---

## 🛠️ Tech Stack

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib

---

## 📂 Dataset

This project uses the CIFAR-10 dataset provided by Torchvision.

Dataset Statistics:

- 60,000 RGB Images
- 10 Object Classes
- 50,000 Training Images
- 10,000 Testing Images

Classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset is downloaded automatically during the first execution.

---

## ⚙️ Data Preprocessing

Images are transformed using:

- Conversion to Tensor
- Pixel Normalization
- Batch Loading using DataLoader

---

## 🧠 CNN Architecture

Input Image (32×32×3)

↓

Conv2D (3 → 32)

↓

ReLU

↓

Max Pooling

↓

Conv2D (32 → 64)

↓

ReLU

↓

Max Pooling

↓

Conv2D (64 → 128)

↓

ReLU

↓

Max Pooling

↓

Flatten

↓

Fully Connected (2048 → 256)

↓

ReLU

↓

Fully Connected (256 → 10)

---

## ⚙️ Training Configuration

Optimizer

- Adam

Loss Function

- CrossEntropyLoss

Epochs

- 10

Batch Size

- 64

---

## 📊 Model Evaluation

Performance Metric

- Classification Accuracy

The trained model is evaluated on the CIFAR-10 test dataset to measure its generalization performance.

---

## 📁 Project Structure

```
cifar10-image-classification-pytorch/
│
├── data/
├── notebooks/
│   └── cifar10_cnn.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/preetmohantyagi/cifar10-image-classification-pytorch.git
```

Move into the project directory

```bash
cd cifar10-image-classification-pytorch
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## 📚 Libraries Used

- torch
- torchvision
- numpy
- matplotlib

---

## 🔮 Future Improvements

- Add Batch Normalization
- Add Dropout Regularization
- Implement Data Augmentation
- Train using ResNet-18
- Visualize Confusion Matrix
- Save Model Checkpoints
- Display Sample Predictions

---

## 👨‍💻 Author

**Preet Mohan Tyagi**

GitHub:
https://github.com/preetmohantyagi

LinkedIn:
https://www.linkedin.com/in/preetmohantyagi

---

## ⭐ If you found this project useful, consider giving it a star!
