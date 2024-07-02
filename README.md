# Digit Recognition with Neural Networks

This project implements a basic digit recognition system using a neural network model built with TensorFlow and Keras. The model is trained on the MNIST dataset, which consists of handwritten digits, and can predict the digit in a new image.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)

## Introduction

This project aims to demonstrate a simple yet effective neural network model for recognizing handwritten digits. The model is trained on the MNIST dataset and can be used to predict digits in new images. It covers the entire workflow from loading data, building and training the model, to making predictions on new data.

## Installation

To run this project, you need to have Python and the following libraries installed:

- TensorFlow
- NumPy
- Matplotlib
- Pillow

You can install these dependencies using `pip`:

```sh
pip install tensorflow numpy matplotlib pillow
```

## Usage
1. Clone this Repository:
```sh
git clone https://github.com/your-username/digit-recognition.git
cd digit-recognition
```
2. Ensure your virtual environment is activated if you're using one.

3. Run the script:

```sh
python digits.py
```

## Model Architecture
The neural network model is built using the Sequential API from Keras. The architecture includes:

- Input Layer: Flattens the 28x28 input images.
- Hidden Layer: Dense layer with 128 units and ReLU activation.
- Output Layer: Dense layer with 10 units (one for each digit) and softmax activation.

## Results
After training the model, it achieves an accuracy of around 98% on the test dataset. The model can also predict the digit in a new image provided by the use

