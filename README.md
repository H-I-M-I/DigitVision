# Handwritten Digit Segmentation

This project focuses on segmenting handwritten digits using a deep learning model. The goal is to train a neural network to generate segmentation masks for digit images.

## Why This Project?
Handwritten digit segmentation is useful in OCR (Optical Character Recognition) applications, where separating digits from backgrounds improves accuracy. It has applications in digitizing bank cheques, handwritten forms, and postal codes.

## Dataset Details & Preprocessing
- The dataset consists of handwritten digit images, where each pixel is labeled for segmentation.
- Images are resized and normalized before training.
- Data augmentation techniques such as rotation and flipping are used to improve generalization.

## Features
- Uses a Convolutional Neural Network (CNN) for pixel-wise segmentation.
- Implements an encoder-decoder architecture for segmentation.
- Trained on a dataset of handwritten digits.
- Uses TensorFlow and TensorFlow Datasets.

## Code Overview
- Defines a basic convolution block for feature extraction.
- Implements a downsampling path using CNN layers.
- Constructs an upsampling path to generate segmentation masks.
- Trains the model on handwritten digit images.
