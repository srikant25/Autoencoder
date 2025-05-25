# 🧠 Autoencoder from Scratch on MNIST

This project demonstrates how to build and train an **Autoencoder** from scratch using the **MNIST dataset**. The objective is to compress and reconstruct handwritten digits, learning efficient latent representations.

---

## 🧾 What’s Inside?

- ✅ Fully connected **Autoencoder** implemented from scratch
- ✅ Trained on **MNIST handwritten digit dataset**
- ✅ Visual comparison of original and reconstructed digits
- ✅ Code built using **TensorFlow/Keras** (no pre-built autoencoder APIs)
- ✅ Visualization of the latent space (optional: t-SNE or PCA)

---

## 📊 Dataset

- **MNIST**: 70,000 grayscale images of handwritten digits (28x28)
- Train set: 60,000 samples  
- Test set: 10,000 samples  
- Each pixel is normalized to [0, 1]

---

## 🏗️ Model Architecture

### Encoder:
- Input: 784 (flattened 28x28 image)
- Dense(256) → Sigmoid  
- Dense(128) → Sigmoid 
- Latent Vector: 32 units

### Decoder:
- Dense(128) → Sigmoid 
- Dense(256) → Sigmoid 
- Output: 784 (reshaped to 28x28) → Sigmoid

---
