# Handwritten-Digit-Classification-using-ANN
Handwritten Digit Classification using ANN
📌 Project Overview:\n
This project implements a fully connected Artificial Neural Network (ANN) to classify (and predict) handwritten digits (0–9) using the MNIST dataset.

🎯 Goal
The goal of this project was to understand:
Image preprocessing
Data scaling and flattening
Neural network architecture
Training dynamics and evaluation metrics

📂 Dataset
Dataset: MNIST Handwritten Digits
Training samples: 60,000
Test samples: 10,000
Image size: 28 × 28 pixels (grayscale)
Classes: 10 (digits 0–9)

⚙️ Technologies Used
Python
NumPy
Matplotlib
TensorFlow / Keras

🛠️ Data Preprocessing
Flattening Images: Each 28 × 28 image was reshaped into a 784-dimensional vector to be compatible with dense layers.
Feature Scaling: Pixel values were normalized by dividing by 255 to scale the range from [0–255] to [0–1].

🏗️ Model Architecture
Input Layer: 784 neurons
Hidden Layer(s): 3 Dense layer(s) with ReLU & sigmoid activation
Output Layer: 10 neurons with sigmoid activation
Loss Function: Sparse Categorical Crossentropy
Optimizer: Adam

📊 Model Performance
Training Accuracy: 99.93%
Test Accuracy: 98.07%
Evaluation Metric: Accuracy

📉 Epoch Vs Accuracy:
<img width="772" height="566" alt="image" src="https://github.com/user-attachments/assets/636ec9a3-97e6-491c-a0ee-d9d14dfba3f4" />

📉 Epoch Vs Loss:
<img width="748" height="560" alt="image" src="https://github.com/user-attachments/assets/61dc6e39-7ee7-4ef9-ac80-bdc0cc31f1d3" />

📈 Key Observations
Flattening removes spatial structure but still achieves strong performance on MNIST.
Scaling inputs significantly improves convergence speed.
Increasing hidden layer size improves accuracy up to a limit.



