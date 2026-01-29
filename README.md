# Conditional GAN for MNIST Digit Generation

This project implements a Conditional Generative Adversarial Network (cGAN) using TensorFlow and Keras to generate handwritten digit images conditioned on class labels.

## 📌 Project Overview
- Uses MNIST handwritten digit dataset
- Generates digits based on user-specified labels (0–9)
- Demonstrates conditional image generation using deep learning

## 🧠 Model Architecture
- **Generator**: Takes random noise and digit labels to generate images
- **Discriminator**: Classifies images as real or fake using label conditioning
- Label embeddings are used in both networks to enable controlled generation

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Gradio
- Google Colab

## 🚀 Features
- End-to-end training of Conditional GAN
- Visual monitoring of generated samples during training
- Interactive Gradio interface for real-time digit generation

