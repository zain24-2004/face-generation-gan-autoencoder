# face-generation-gan-autoencoder
Face generation and reconstruction project using GANs and Autoencoders trained on a subset of the CelebA celebrity dataset. Explores representation learning and realistic face synthesis.
# GAN and Autoencoder for Face Generation (CelebA Dataset)

This project implements **Generative Adversarial Networks (GANs)** and **Autoencoders** for face generation and reconstruction using a subset of the **CelebA celebrity dataset (50 identities)**. The goal is to learn meaningful facial representations and generate realistic human faces.

---

##  Project Overview

Generative models such as GANs and Autoencoders play a crucial role in unsupervised and self-supervised learning. This project focuses on training these models to understand facial features and generate new face images based on learned latent representations.

The CelebA dataset provides a rich collection of celebrity face images with high diversity in appearance, making it suitable for generative modeling tasks.

---

##  Objectives

- Train an Autoencoder to learn compressed facial representations
- Train a GAN to generate realistic face images
- Compare reconstruction vs generation quality
- Explore latent space representations
- Analyze visual quality and convergence behavior

---

##  Dataset

- Dataset: CelebA (Custom subset of 50 celebrities)
- Image type: RGB face images
- Preprocessing:
  - Face alignment & resizing
  - Normalization
  - Data augmentation (optional)

---

##  Models Implemented

###  Autoencoder
- Encoder: Convolutional Neural Network (CNN)
- Latent space representation
- Decoder: Transposed CNN for image reconstruction

###  Generative Adversarial Network (GAN)
- Generator Network
- Discriminator Network
- Adversarial training loop

---

##  Methodology

1. Data Loading & Preprocessing
2. Autoencoder Architecture Design
3. GAN Architecture Design
4. Model Training
5. Loss Monitoring
6. Image Generation & Reconstruction
7. Performance Visualization

---

##  Evaluation Criteria

- Reconstruction loss (Autoencoder)
- Generator & Discriminator loss (GAN)
- Visual quality of generated images
- Latent space interpolation

---

##  Tools & Technologies

- Python
- TensorFlow / PyTorch
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook

---

##  Project Structure
gan-autoencoder-celeba/
│
├── data/
│ └── celeba_subset/
│
├── models/
│ ├── autoencoder.py
│ ├── generator.py

