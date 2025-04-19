# 🧠 DC-GAN from Scratch

Welcome to my Deep Convolutional Generative Adversarial Network (DC-GAN) project!  
This repository fully implements a DC-GAN from scratch using Tensorflow, which is built to generate high-quality synthetic images from random noise.

---

## 🌟 Features

- 🏗️ Implemented from scratch using Tensorflow
- 🧩 Modular code structure for easy understanding and extension
- 📈 Includes training loop, generator and discriminator architecture, and loss tracking
- 🖼️ Generates synthetic images after training on real dataset of MNIST

---

## 🧬 What is a DC-GAN?

A **Deep Convolutional GAN** (DC-GAN) is a class of Generative Adversarial Networks that uses convolutional and transposed convolutional layers for improved image generation.  
It consists of two neural networks:
- **Generator**: Learns to generate realistic images from noise
- **Discriminator**: Learns to distinguish between real and generated images

These two networks are trained adversarially to improve the output quality over time.
