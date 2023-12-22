# Image Denoising with Autoencoder

## Overview

This repository contains code for image denoising using an autoencoder neural network. The autoencoder is trained on the MNIST dataset with added noise, aiming to improve the quality of biometric images.

## Table of Contents

- [Introduction](#introduction)
- [Methods](#methods)
- [Results](#results)

- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Biometric data, comprising unique physiological and behav-
ioral characteristics, is fundamental to modern security and
identification systems. These distinctive traits, ranging from
fingerprints to facial features, serve as a reliable means of ver-
ifying and authenticating individuals. However, the effective-
ness of biometric recognition systems is often compromised by
the inherent challenge of noise within acquired biometric im-
ages. This noise can stem from various sources, including im-
age acquisition devices, environmental conditions, and inherent
biological variations.
The accurate and reliable processing of biometric data is im-
perative for the seamless operation of identification systems in
diverse applications, such as access control, border security, and
financial transactions. In particular, the robustness of biometric
recognition systems hinges on the quality of input data, where
noise can introduce errors, leading to false positives or nega-
tives.
This report delves into the intricate realm of addressing noise
in biometric data through the application of advanced machine
learning techniques, with a specific focus on the utilization of
autoencoder neural networks. The motivation behind this ex-
ploration is rooted in the recognition that noise in biometric
images can compromise the precision and integrity of identi-
fication systems, potentially undermining their overall security
and reliability.
The introduction of autoencoder neural networks into this
context presents a promising avenue for mitigating the impact
of noise. Autoencoders, being unsupervised learning models,
possess the inherent capability to learn compact and meaning-
ful representations of input data. Through a systematic train-
ing process, these neural networks can discern patterns in noisy
biometric images, effectively isolating and reconstructing the
underlying clean features.
## Methods

### Data Preparation

The MNIST dataset is utilized as a representative biometric dataset. Gaussian noise is added during the training phase to simulate real-world noise in biometric images.

### Autoencoder Architecture

The autoencoder architecture consists of an encoder and a decoder. Convolutional layers are used for feature extraction, and linear layers handle encoding and decoding.

### Training

The autoencoder is trained using the Mean Squared Error (MSE) loss function. The Adam optimizer is employed with dropout to prevent overfitting.



## Access the Reports and Codes

- [Report (PDF)](https://github.com/Muhirwakyeyune/image-denoising-autoencoder/blob/main/Image_Cleaning_With_Autoencoder_Report.pdf)
- [Code (Jupyter Notebook)](https://github.com/Muhirwakyeyune/image-denoising-autoencoder/blob/main/Autoencoder_for_Image_Denoising_using_PyTorch_Muhirwa__.ipynb)

## Dependencies

- Python 3.x
- PyTorch
- Matplotlib

## Contributing

Contributions are welcome! Please follow the [Contributing Guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).
