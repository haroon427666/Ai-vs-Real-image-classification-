# 🧠 AI vs Real Image Classifier — ConvNeXt-Tiny

A high-performance deep learning system for detecting AI-generated images vs real photographs using the ConvNeXt-Tiny architecture.

---

## 🚀 Project Overview

This project builds a robust computer vision model capable of distinguishing synthetic (AI-generated) images from real-world photographs with high accuracy.

It is designed for real-world deployment in areas such as deepfake detection, media verification, and AI-content moderation.

**Key Highlights**

* Trained on **200,000 images**
* Fully **balanced dataset** (100K real / 100K AI)
* Modern architecture: **ConvNeXt-Tiny**
* Strong generalization capability
* Optimized for **low-VRAM GPUs (4GB)**
* Real-world deepfake & synthetic media detection use cases

---

## 🏗️ Model Details

| Feature                  | Value                                     |
| ------------------------ | ----------------------------------------- |
| Architecture             | ConvNeXt-Tiny                             |
| Task                     | AI-generated vs Real image classification |
| Training epochs          | 30                                        |
| Best validation accuracy | **93.4%**                                 |
| Best AUC score           | **0.981**                                 |
| Training accuracy        | ~96%                                      |
| GPU used                 | RTX A1000 (4GB VRAM)                      |
| Framework                | PyTorch                                   |

---

## 📊 Dataset

**ArtiFact: Real and Fake Image Dataset**
[https://www.kaggle.com/datasets/awsaf49/artifact-dataset](https://www.kaggle.com/datasets/awsaf49/artifact-dataset)

**Dataset Composition**

* Total images: **200,000**
* Real images: **100,000**
* AI-generated images: **100,000**
* Balanced binary classification

The dataset contains synthetic images generated from modern generative models along with real-world photographs, making it ideal for:

* Deepfake detection
* AI content recognition
* Authenticity verification systems

---

## 🧩 Model Weights

Due to GitHub file size limits, trained weights are hosted externally.

See:

```
model_link.txt
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## 🏋️ Training

Open the training notebook:

```
train_convnext.ipynb
```

Run all cells to reproduce the training pipeline.

---

## 🎯 Use Cases

* Deepfake detection
* AI-generated image identification
* Content moderation systems
* Media authenticity verification
* Digital forensics pipelines

---

## 🧪 Tech Stack

* Python
* PyTorch
* Torchvision
* ConvNeXt Architecture
* CUDA
* NumPy / PIL / Sklearn

---

## 👨‍💻 Author

**Haroon — AI/ML Engineer**

Focused on:

* Computer Vision
* Deep Learning
* Generative AI Detection
* Applied AI Systems

---

## ⭐ Project Goal

To build a reliable, scalable, and deployment-ready system capable of detecting AI-generated media in real-world environments.
