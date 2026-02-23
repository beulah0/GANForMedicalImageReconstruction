📖 Overview

This project implements a Pix2Pix Conditional Generative Adversarial Network (cGAN) using TensorFlow and Keras to perform image-to-image translation. The model learns to generate realistic images from input images through adversarial training.

🎯 Objectives

Build a Pix2Pix GAN architecture

Train generator and discriminator networks

Generate high-quality translated images

Evaluate output quality using PSNR and SSIM

🧠 Model Architecture
Generator

U-Net based encoder-decoder network

Skip connections for better feature preservation

Discriminator

PatchGAN architecture

Classifies image patches as real or fake

⚙️ Technologies Used

Python

TensorFlow / Keras

NumPy

Scikit-Image

📊 Evaluation Metrics

The model performance is measured using:

PSNR (Peak Signal-to-Noise Ratio) – measures reconstruction quality

SSIM (Structural Similarity Index) – measures perceptual similarity

🚀 Features

Conditional GAN implementation

Adversarial + L1 loss training

Image quality evaluation

Visualization of generated outputs
