# Kannada MNIST Digit Classification (Perceptron vs ANN vs CNN)

## Project Overview

This project focuses on **handwritten digit classification** using the Kannada MNIST dataset.
The goal is to compare the performance of different neural network architectures:

* Perceptron
* Artificial Neural Network (ANN)
* Convolutional Neural Network (CNN)

The comparison helps demonstrate how **deep learning architectures perform differently on image data**.

---

## Dataset

Dataset used: **Kannada MNIST**

The dataset contains images of handwritten digits from **0–9 in the Kannada language**.

Dataset structure:

* `train.csv`
* `test.csv`
* `Dig-MNIST.csv`
* `sample_submission.csv`

Each image is:

* 28 × 28 grayscale pixels
* Flattened into **784 features**

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Data Visualization
4. Model Building
5. Model Training
6. Model Evaluation
7. Model Comparison

---

## Data Preprocessing

Steps applied:

* Converted dataset from **CSV to image format**
* Reshaped data to **28×28 pixels**
* Normalized pixel values (0–255 → 0–1)
* Train/Test split

---

## Models Implemented

### 1. Perceptron

A basic single-layer neural network.

**Architecture**

Input Layer → Output Layer

Limitations:

* Cannot capture complex image patterns
* Lower accuracy compared to deep models

---

### 2. Artificial Neural Network (ANN)

Fully connected neural network.

**Architecture**

Input Layer (784)
↓
Hidden Layer (ReLU)
↓
Hidden Layer (ReLU)
↓
Output Layer (Softmax)

Advantages:

* Learns non-linear relationships
* Better performance than Perceptron

---

### 3. Convolutional Neural Network (CNN)

Designed specifically for **image processing**.

**Architecture**

Conv2D → ReLU
↓
MaxPooling
↓
Conv2D → ReLU
↓
MaxPooling
↓
Flatten
↓
Dense Layer
↓
Softmax Output

Advantages:

* Detects spatial features
* Best model for image classification

---

## Model Performance Comparison

| Model      | Accuracy | Observation                    |
| ---------- | -------- | ------------------------------ |
| Perceptron | Lower    | Cannot capture image patterns  |
| ANN        | Medium   | Learns nonlinear relationships |
| CNN        | Highest  | Best for image data            |

CNN significantly outperforms the other models due to its ability to extract spatial features.

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* TensorFlow / Keras
* Scikit-learn

---

## Key Learning Outcomes

From this project I learned:

* Differences between **Perceptron, ANN, and CNN**
* Why **CNN is better for image data**
* Image preprocessing techniques
* Neural network architecture design
* Model performance comparison

---

## Project Structure

---

## Future Improvements

* Add **Data Augmentation**
* Implement **Batch Normalization**
* Try **Transfer Learning**
* Hyperparameter tuning

---

## Author

MD Nazmul Huda Nabil

Aspiring AI Engineer | Machine Learning & Deep Learning Enthusiast
