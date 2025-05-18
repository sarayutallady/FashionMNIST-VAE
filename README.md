# FashionMNIST Variational Autoencoder (VAE)

This project implements a simple **Variational Autoencoder (VAE)** using **PyTorch** to reconstruct images from the **FashionMNIST** dataset.

## 📌 Overview

A Variational Autoencoder is a generative model that learns to encode input images into a compressed latent space and then decode them back to reconstruct the original image. In this project:

- **Dataset:** FashionMNIST (10 clothing categories)
- **Model:** Fully connected VAE
- **Loss:** MSE + KL Divergence
- **Framework:** PyTorch
- **Platform:** Google Colab

---

## 🔧 Features

- Custom encoder and decoder using fully connected layers.
- Latent vector sampling using the **reparameterization trick**.
- GPU support for faster training.
- Side-by-side visualization of original and reconstructed images.

---

## 📊 Results

After training, the model is able to reconstruct fashion images like shirts, shoes, and bags with reasonable accuracy.

| Original | Reconstructed |
|----------|---------------|
| ![orig](docs/original.png) | ![recon](docs/reconstructed.png) |

*(You can generate these using the last cell of the notebook.)*

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/sarayutallady/FashionMNIST-VAE.git
cd FashionMNIST-VAE
