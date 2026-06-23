# image-classification-ann-cnn
Fashion-MNIST Image Classification: ANN vs CNN
Project Overview

This project compares the performance of an Artificial Neural Network (ANN) and a Convolutional Neural Network (CNN) on the Fashion-MNIST dataset using TensorFlow.

The goal was to understand the complete image classification workflow, including:

Data preprocessing
Model training
Model evaluation
Error analysis
External image testing
Dataset

Fashion-MNIST consists of 70,000 grayscale images belonging to 10 fashion categories:

T-shirt/Top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle Boot
Models Implemented
Artificial Neural Network (ANN)

Architecture:

Flatten
↓
Dense(128, ReLU)
↓
Dense(10, Softmax)
Convolutional Neural Network (CNN)

Architecture:

Conv2D(32)
↓
MaxPooling2D
↓
Flatten
↓
Dense(128, ReLU)
↓
Dense(10, Softmax)
Results
Model	Test Accuracy
ANN	87.84%
CNN	91.23%

CNN improved performance by approximately 3.39%.

Evaluation
Accuracy Graph
Loss Graph
Confusion Matrix
Misclassified Image Analysis
External Image Testing
Key Learning

CNNs perform better on image classification tasks because they preserve spatial information and learn meaningful image features such as edges, curves, and shapes before classification.

Technologies Used
Python
TensorFlow
NumPy
Matplotlib
Seaborn
Google Colab
