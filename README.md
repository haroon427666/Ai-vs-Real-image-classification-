AI vs Real Image Classifier (ConvNeXt-Tiny)

Deep learning model to detect AI-generated vs real images using ConvNeXt-Tiny architecture.

Project Overview

This project builds a high-performance computer vision model to distinguish AI-generated images from real photographs.

Key highlights:

Trained on 200K images

Balanced dataset (Real vs AI)

Modern architecture (ConvNeXt)

Strong generalization performance

Real-world deepfake detection use case

Model Details

Architecture: ConvNeXt-Tiny

Task: AI-generated vs Real image classification

Training epochs: 30

Best validation accuracy: 93.4%

Best AUC score: 0.981

Training accuracy: ~96%

GPU used: RTX A1000 (4GB VRAM)

Dataset

ArtiFact: Real and Fake Image Dataset
https://www.kaggle.com/datasets/awsaf49/artifact-dataset

Dataset composition:

Total images: 200,000

Real images: 100,000

AI-generated images: 100,000

Balanced binary classification dataset

The dataset includes synthetic images generated from modern generative models and real-world photographs, making it suitable for training deepfake and AI-content detection systems.

Model Weights

Due to GitHub size limits, model weights are hosted externally:

See:

model_link.txt

Installation
pip install -r requirements.txt

Training

Open notebook:

train_convnext.ipynb


Run all cells to reproduce training.

Use Cases

Deepfake detection

Synthetic image detection

AI content moderation

Media authenticity verification

Tech Stack

Python

PyTorch

ConvNeXt

Torchvision

CUDA

Author

Haroon — AI/ML Engineer
Focused on computer vision, deep learning, and generative AI detection.
