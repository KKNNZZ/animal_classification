# Image Classification Project

This project showcases different approaches to image classification using popular machine learning architectures like MobileNetV2, a simple custom Convolutional Neural Network (CNN), and ResNet-50.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Functions](#functions)
6. [Acknowledgements](#acknowledgements)

## Introduction

This repository contains code to perform image classification through three methods:

- **MobileNetV2**: A highly efficient architecture that is designed for mobile and embedded vision applications.
- **Simple CNN**: A custom Convolutional Neural Network designed to give a basic introduction to CNNs.
- **ResNet-50**: A widely-used deep residual network that provides a good trade-off between accuracy and computational efficiency.

## Dependencies

- Python 3.x
- TensorFlow 2.x
- PyTorch
- PIL (Pillow)
- ImageAI
- NumPy
- json
- os

## Installation

To clone the repository, run the following command:

\`\`\`
git clone https://github.com/yourusername/image-classification-project.git
\`\`\`

To install the required dependencies, navigate to the project folder and run:

\`\`\`
pip install -r requirements.txt
\`\`\`

## Usage

1. Place the image you want to classify in the project folder or specify the image path.
2. Run the respective function for classification through MobileNetV2, Simple CNN, or ResNet-50:

\`\`\`python
result = mobilnet_v2("path/to/image.jpg")
\`\`\`

or

\`\`\`python
result = simple_CNN("path/to/image.jpg")
\`\`\`

or

\`\`\`python
result = resnet_50("path/to/image.jpg")
\`\`\`

3. The `result` variable will contain the top-n predictions for the image.

## Functions

- `mobilnet_v2(img_dir, n=3)`: Classify image using MobileNetV2 and return top-n results.
- `simple_CNN(img_dir, n=3)`: Classify image using a simple custom CNN and return top-n results.
- `resnet_50(img_dir, n=3)`: Classify image using ResNet-50 and return top-n results.

For more details, refer to the comments in the code.
