# Binary Classification using Neural Networks (SLP vs MLP)

## Overview
This project builds and compares two neural network models:
- Single Layer Perceptron (SLP)
- Multi Layer Perceptron (MLP)

The models are trained on a synthetic classification dataset to evaluate performance differences between shallow and deep architectures.

---

## Dataset
- Generated using `make_classification` from Scikit-learn
- 1000 samples, 20 features
- Binary classification problem

---

## Models

### 1. Single Layer Perceptron (SLP)
- 1 Dense layer
- Sigmoid activation
- Simple linear decision boundary

### 2. Multi Layer Perceptron (MLP)
- 2 hidden layers (64, 32 neurons)
- ReLU activation
- Sigmoid output layer

---

## Preprocessing
- Train-test split (70/30)
- Feature scaling using StandardScaler

---

## Training
- Optimizer: Adam
- Loss: Binary Crossentropy
- Epochs: 50
- Batch size: 10

---

## Evaluation
- Accuracy Score on train and test sets
- Comparison between SLP and MLP performance

---

## Results Summary
- SLP: simpler model, lower accuracy
- MLP: deeper model, higher accuracy and better generalization

---

## Libraries Used
- TensorFlow / Keras
- Scikit-learn
- NumPy

---

## Author
Arwaa Mamdoh
