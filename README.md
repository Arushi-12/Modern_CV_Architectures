# Modern_CV_Architectures

## Overview

This repository contains two deep learning implementations demonstrating the fundamentals of computer vision architectures:

1. **3D Convolutional Neural Network (3D CNN) built entirely from NumPy primitives**
2. **Encoder-only Vision Transformer (ViT) implemented in PyTorch**

The project focuses on understanding the internal workings of convolutional and transformer-based models by implementing their core components from scratch instead of relying on high-level libraries.

---

## Features

### 1. 3D CNN from Scratch (NumPy)

- Implemented 3D convolution operations using only NumPy
- Supports configurable 3D kernels and stride values
- Manual forward propagation without deep learning frameworks
- Demonstrates volumetric feature extraction
- Achieved **near-perfect reconstruction performance**

### 2. Vision Transformer (ViT) (PyTorch)

- Encoder-only Vision Transformer architecture
- Custom Patch Embedding layer
- Learnable positional embeddings
- Multi-Head Self-Attention mechanism
- Feed Forward Network (MLP)
- Layer Normalization and residual connections
- Classification head for image recognition
- Achieved **75.31% test accuracy**

---

## Tech Stack

- Python
- NumPy
- PyTorch
- Matplotlib (for visualization)
- Jupyter Notebook

---

## Model Architecture

### 3D CNN

Input Volume

↓

3D Convolution

↓

Activation

↓

Feature Maps

↓

Reconstruction Output

---

### Vision Transformer

Input Image

↓

Patch Embedding

↓

Positional Encoding

↓

Transformer Encoder Blocks

├── Multi-Head Self-Attention

├── Layer Normalization

├── Feed Forward Network

└── Residual Connections

↓

Classification Head

↓

Predicted Class

---

## Results

| Model | Performance |
|---------|------------|
| 3D CNN | Near-perfect reconstruction |
| Vision Transformer | **75.31% Test Accuracy** |

---

## Learning Objectives

- Understand the mathematics behind 3D convolutions
- Explore volumetric data processing
- Implement transformer architectures for vision tasks
- Learn Patch Embedding and Self-Attention mechanisms
- Compare convolution-based and transformer-based approaches

---

## Project Structure

```
├── 3D_CNN/
│   ├── convolution.py
│   ├── kernels.py
│   └── reconstruction.py
│
├── Vision_Transformer/
│   ├── patch_embedding.py
│   ├── attention.py
│   ├── encoder.py
│   ├── model.py
│   └── train.py
│
├── notebooks/
├── results/
└── README.md
```

---

## Future Improvements

- Add decoder-based Vision Transformer variants
- Support deeper transformer architectures
- Optimize 3D convolution implementation
- Extend to medical image segmentation and video understanding tasks
- Compare performance with standard CNN architectures

---

## Acknowledgements

This project was developed as an educational implementation to gain a deeper understanding of modern computer vision architectures by building their core components from first principles.
