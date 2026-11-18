# Digit Recognition

A simple neural network that classifies handwritten digits (0-9), built with
TensorFlow/Keras.

## What it does

Trains a dense network / CNN on the DATASET MNIST
dataset and predicts which digit an image contains. Matplotlib is used to
display sample digits / plot training accuracy.

## Results

- Test accuracy: **97.10%** 

## Tech

Python 3.14.0, TensorFlow/Keras, NumPy, Matplotlib

## Setup

```bash
git clone https://github.com/qqhsinat/digit-recognition.git
cd digit-recognition
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook Number_Identifier_with_leras.ipynb
```

"Downloads the dataset, trains for 3 epochs, prints test accuracy."

## Notes

This is a learning project using the standard approach to digit classification.
It isn't meant to be state of the art.
