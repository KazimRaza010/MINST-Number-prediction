# Numeric Prediction with Neural Network

This project demonstrates a simple neural network model built using TensorFlow/Keras to predict numeric outputs from input features. The model is trained on data (originally intended from `train.csv`) and tested on data from `test.csv`. It highlights preprocessing, model creation, training, and prediction steps.

## Project Structure

- **numpred.ipynb**: Jupyter notebook containing the complete code for data loading, model creation, training, evaluation, and prediction.
- **test.csv**: CSV file containing the test data used for making predictions.
- **train.csv**: (Note: This file was expected but could not be loaded during the project development.)

## Features

- Neural network built using TensorFlow/Keras.
- Handles numeric data.
- Softmax applied to logits for final predictions (if classification) or direct numeric output (if regression).
- Example code for making predictions on test data without labels.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/KazimRaza010/MINST-Number-prediction.git
   cd MINST-Number-prediction
