# Image Denoising with Autoencoder

## Overview

This repository contains code for image denoising using an autoencoder neural network. The autoencoder is trained on the MRI dataset with added noise, aiming to improve the quality of biometric images.

## Table of Contents

- [Introduction](#introduction)
- [Methods](#methods)
- [Results](#results)
- [Related Works](#related-works)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Biometric data, comprising unique physiological and behavioral characteristics, is fundamental to modern security and identification systems. This report delves into addressing noise in biometric data through advanced machine learning techniques, specifically the utilization of autoencoder neural networks. The goal is to enhance the quality of biometric images by denoising them, contributing to the improvement of biometric recognition systems.

## Methods

### Data Preparation

The MNIST dataset is employed as a representative biometric dataset. Gaussian noise is intentionally added during the training phase to simulate real-world noise in biometric images.

### Autoencoder Architecture

The proposed autoencoder architecture consists of an encoder and a decoder, using convolutional layers for feature extraction and linear layers for encoding and decoding.

### Training

The autoencoder is trained using the Mean Squared Error (MSE) loss function, and the Adam optimizer is employed with dropout to prevent overfitting.

## Results

### Training Phase

During the ten epochs of training, the autoencoder effectively learned to denoise biometric images, as indicated by the decreasing trend in training loss:

- Epoch 1: Training Loss - 0.610211
- Epoch 2: Training Loss - 0.568494
- ...
- Epoch 10: Training Loss - 0.506246

### Evaluation Phase

The trained autoencoder was evaluated on a separate test set, resulting in a test loss of 0.074321. Visual inspection of denoised images showcased the model's ability to preserve essential features while removing noise.

## Related Works

The field of image denoising has witnessed significant advancements. One notable contribution is the work titled "Autoencoders Based Deep Learner for Image Denoising" by Komal Bajaj, Dushyant Kumar Singh, and Mohd. Aquib Ansari. The paper introduces an innovative approach leveraging autoencoders for image denoising, achieving higher Peak Signal-to-Noise Ratio (PSNR) results compared to conventional models.


    ```

## Dependencies

- Python 3.11
- PyTorch
- Matplotlib



## License

This project is licensed under the [African Masters In Machine Intelligence](https://aimsammi.org/).
