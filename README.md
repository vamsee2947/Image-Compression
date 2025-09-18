# Auto Image Compression with Deep Learning

This project implements several **autoencoder-based image compression** pipelines
on the [DIV2K dataset](https://data.vision.ee.ethz.ch/cvl/DIV2K/).
It compares learned compression against traditional JPEG and JPEG2000.

## Features
- TensorFlow/Keras convolutional autoencoder.
- Custom loss combining MSE + SSIM (+ optional VGG perceptual loss).
- Comparison with JPEG and JPEG2000 compression.

## Installation
```bash
git clone https://github.com/vamsee2947/auto-image-compression.git
cd auto-image-compression
pip install -r requirements.txt
