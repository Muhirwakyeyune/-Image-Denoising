# Image Denoising with Autoencoder

## Overview

This repository contains code for image denoising using an autoencoder neural network. The autoencoder is trained on the MNIST dataset with added noise, aiming to improve the quality of biometric images.

## Table of Contents

- [Introduction](#introduction)
- [Methods](#methods)
- [Results](#results)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Biometric data often suffers from noise, affecting the accuracy of recognition systems. This project explores the application of autoencoder neural networks to clean and enhance biometric images, ultimately improving recognition system performance.

## Methods

### Data Preparation

The MNIST dataset is utilized as a representative biometric dataset. Gaussian noise is added during the training phase to simulate real-world noise in biometric images.

### Autoencoder Architecture

The autoencoder architecture consists of an encoder and a decoder. Convolutional layers are used for feature extraction, and linear layers handle encoding and decoding.

### Training

The autoencoder is trained using the Mean Squared Error (MSE) loss function. The Adam optimizer is employed with dropout to prevent overfitting.

## Results

The trained autoencoder is evaluated on a separate test set, and the test loss is reported as a key metric for denoising capabilities. The results demonstrate the effectiveness of the autoencoder in reducing noise and improving image quality.


    ```

## Dependencies

- Python 3.x
- PyTorch
- Matplotlib

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License
