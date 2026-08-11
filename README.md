# 🔢 Handwritten Digit Recognition using CNN

Classifying handwritten digits (0–9) from the MNIST dataset using a Convolutional Neural Network built with TensorFlow/Keras.

## Problem Statement
Automatically recognizing handwritten digits is a foundational computer vision task with real applications in postal sorting, cheque processing, and digitizing handwritten forms. This project builds an image classifier that takes a 28x28 grayscale digit image and predicts which digit (0-9) it represents.

## Dataset
[MNIST in CSV](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv) — 70,000 grayscale 28x28 images of handwritten digits (`mnist_train.csv`).

## Approach
1. Load and sample the MNIST CSV data
2. Reshape flat pixel rows into 28x28x1 image arrays
3. Normalize pixel values to 0-1
4. Train/test split (stratified by label)
5. Build a CNN (2 Conv+Pool blocks, Dense layers, softmax output)
6. Train and evaluate on held-out test data
7. Visualize predictions on sample images

## Tech Stack
`pandas` · `numpy` · `matplotlib` · `scikit-learn` · `TensorFlow/Keras` (Conv2D, MaxPooling2D, Dense)

## How to Run
pip install pandas numpy matplotlib scikit-learn tensorflow jupyter
jupyter notebook MNIST_CNN_Digit_Classification.ipynb

Or open directly in Google Colab or Kaggle Notebooks (attach the MNIST in CSV dataset).

## License
MIT
