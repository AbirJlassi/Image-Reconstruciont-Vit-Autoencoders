# Image Reconstruction Project

A comprehensive implementation of image reconstruction techniques using Vision Transformers (ViT) and Autoencoders. This project explores three different approaches: building a ViT from scratch, using pretrained ViT models, and implementing traditional autoencoders.

## Project Overview

This project implements and compares different neural network architectures for image reconstruction tasks:

- **Vision Transformer from Scratch**: Custom implementation of ViT architecture
- **Pretrained Vision Transformer**: Leveraging pretrained ViT models for reconstruction
- **Autoencoder**: Traditional CNN-based autoencoder for image reconstruction



### Prerequisites

- Python 3.8+
- CUDA-compatible GPU (recommended)
- 8GB+ RAM


## Models

### 1. Vision Transformer from Scratch

Custom implementation of the Vision Transformer architecture for image reconstruction.

**Key Features:**
- Multi-head self-attention mechanism
- Patch embedding with learnable position encodings
- Layer normalization and residual connections
- Configurable encoder depth and attention heads


### 2. Pretrained Vision Transformer

Utilizes pretrained ViT models (google/vit-base-patch16-224) fine-tuned for reconstruction tasks.

**Key Features:**
- Transfer learning from pretrained weights
- Fine-tuning strategies for reconstruction
- Multiple pretrained model options
- Faster convergence


### 3. Autoencoder

Traditional CNN-based autoencoder with encoder-decoder architecture.

**Key Features:**
- Convolutional encoder with progressive downsampling
- Symmetric decoder with upsampling
- Batch normalization and dropout



### Key Findings

1. **Autoencoder** provides a good baseline with efficient training
2. **Pretrained ViT** achieves the best reconstruction quality with faster convergence
3. **ViT from scratch** requires more training time but offers full control over architecture



---

### Result Snapshots of AutoEncoder Reconstructions

![image](https://github.com/user-attachments/assets/5433031b-10b8-43fe-991b-2415a577a689)
