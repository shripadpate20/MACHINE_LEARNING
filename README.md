# Artificial Neural Network (ANN) From Scratch

This project implements an Artificial Neural Network (ANN) from scratch using NumPy and Pandas for image classification on a dataset of 70,000 grayscale images.

## Overview

The neural network is built with the following architecture:
- Input layer: 784 neurons (28x28 pixel images)
- Hidden layer 1: 128 neurons with sigmoid activation
- Hidden layer 2: 64 neurons with sigmoid activation
- Hidden layer 3: 32 neurons with sigmoid activation
- Output layer: 10 neurons (10 classes) with softmax activation

## Features

- Implements forward and backward propagation
- Uses cross-entropy loss function
- Supports different train-test splits (70:30, 70:20, 70:10)
- Includes visualization of training/testing accuracy and loss
- Generates confusion matrix for model evaluation

## Requirements

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Usage

1. Ensure you have the required libraries installed.
2. Place your dataset file (`data.csv`) in the same directory as the script.
3. Run the `ann_from_scratch.py` script.

## Results

The model achieves:
- ~74% training accuracy
- ~73.7% testing accuracy

Performance varies slightly with different train-test splits.

## Files

- `ann_from_scratch.py`: Main script containing the ANN implementation
- `Report.pdf`: Detailed report on the project, including data analysis and results

## Author

Shripad pate (M23MAC007)
Data and Computational Sciences (DCS)
Department of Mathematics
Indian Institute of Technology, Jodhpur

## License

This project is open source and available under the [MIT License](LICENSE).
