# Assignment 12: Neural Network and Deep Learning Basics

## Project Overview

This project implements a simple feedforward neural network for image classification using the Fashion MNIST dataset. The model was developed using TensorFlow/Keras and trained to classify images into 10 different clothing categories.

## Dataset

- **Dataset:** Fashion MNIST
- **Source:** TensorFlow/Keras
- **Training Images:** 60,000
- **Testing Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Number of Classes:** 10

## Neural Network Architecture

The model consists of:
- Flatten input layer
- One hidden Dense layer with 128 neurons and ReLU activation
- Softmax output layer with 10 neurons

An improved model with an additional hidden layer was also implemented for comparison.

## Libraries Used

- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Steps

1. Load the Fashion MNIST dataset.
2. Visualize sample images.
3. Normalize image pixel values.
4. Build and train a feedforward neural network.
5. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
6. Plot training and validation accuracy and loss.
7. Improve the model by adding an additional hidden layer.

## Results

- Test Accuracy: Approximately **87–88%**
- The model performed well on most clothing categories.
- An improved model was also evaluated for comparison.

## How to Run the Project

1. Open the notebook in **Google Colab**.
2. Run all cells from top to bottom.
3. The Fashion MNIST dataset will be downloaded automatically by TensorFlow.
4. The notebook will train the model and display the evaluation results and graphs.

## Repository Contents

```
Assignment12.ipynb
Assignment12_Report.pdf
README.md
```
