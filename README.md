# Fashion MNIST Classification

This project implements a convolutional neural network (CNN) to classify images from the Fashion MNIST dataset.

## Overview

The Fashion MNIST dataset consists of 70,000 28x28 grayscale images of 10 fashion categories. This project uses a CNN implemented in TensorFlow/Keras to classify these images.

Key components:

- Data loading and preprocessing
- CNN model architecture 
- Model training
- Evaluation and visualization
- Testing on new images

## Requirements

- TensorFlow 
- Keras
- NumPy
- Matplotlib

## Usage

The main notebook `Fashion_MNIST_classification.ipynb` contains the full pipeline:

1. Load and preprocess Fashion MNIST data
2. Define and compile CNN model 
3. Train model on training data
4. Evaluate on test set
5. Visualize results
6. Test on new sample images

## Model Architecture

The CNN architecture consists of:

- Convolutional layers
- Max pooling layers  
- Dense layers
- Dropout for regularization

## Results

The model achieves ~91% accuracy on the test set after training for 20 epochs. The notebook includes examples of using the trained model to classify new sample images of fashion items.
