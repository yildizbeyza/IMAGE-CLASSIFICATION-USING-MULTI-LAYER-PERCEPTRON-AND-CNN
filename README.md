# Image Classification using Multi-Layer Perceptron (MLP) and Convolutional Neural Network (LeNet-5)

## Overview
This project focuses on comparing different neural network architectures and training settings for image classification tasks.  
It includes two main experiments:

- **Task 1:** Classification of handwritten digits on the MNIST dataset using a Multi-Layer Perceptron (MLP).  
- **Task 2:** Implementation of the LeNet-5 Convolutional Neural Network (CNN) for classifying images in the CIFAR-10 dataset.  

The goal is to observe how different design choices—such as activation functions, batch sizes, loss functions, and optimizers—affect model performance and learning behavior.

## Task 1: Multi-Layer Perceptron (MLP) on MNIST

The first task uses an MLP to classify grayscale handwritten digits (0–9) from the **MNIST** dataset.

### Network Architecture
- Input layer: 28 × 28 = 784 nodes  
- Hidden Layer 1: 250 neurons  
- Hidden Layer 2: 100 neurons  
- Output layer: 10 neurons (digit classes 0–9)

### Experiments Conducted
| Variation | Parameters Compared |
|------------|--------------------|
| **Activation Functions** | ReLU vs Sigmoid |
| **Batch Size** | 8 vs 64 |
| **Loss Function** | Cross-Entropy vs MSE |
| **Optimizers** | SGD vs Adam |

### Evaluation
For each configuration:
- Calculated and plotted **accuracy** and **confusion matrix**  
- Used **PCA** to visualize the 2D representation before the second hidden layer

## Task 2: Convolutional Neural Network (LeNet-5) on CIFAR-10

The second task implements **Yann LeCun’s LeNet-5 architecture** to classify color images from the **CIFAR-10** dataset.

### Model Overview
LeNet-5 consists of alternating convolutional, pooling, and fully connected layers designed to extract hierarchical image features effectively.  
This implementation follows the original structure but adapts it to CIFAR-10’s 32 × 32 RGB images.

### Evaluation
The same experimental comparisons as Task 1 were performed:
- Activation functions, batch sizes, loss functions, and optimizers  
- Accuracy and confusion matrices  
- PCA visualizations of the learned feature space

## Selected Outputs
Below are a few sample visualizations from the experiments.  
*(These are not all the results — the full set can be found in the accompanying `.ipynb` file in this repository.)*

<img width="614" height="707" alt="image" src="https://github.com/user-attachments/assets/269794ec-e037-48c3-92e3-de1587c6e296" />

<img width="569" height="710" alt="image" src="https://github.com/user-attachments/assets/ad107ff8-54df-480e-913d-864d6b64b5fc" />

<img width="609" height="689" alt="image" src="https://github.com/user-attachments/assets/b718fb69-f82b-4ea5-8e2a-e916fb33d9a0" />

<img width="610" height="682" alt="image" src="https://github.com/user-attachments/assets/5e9c5bf7-21a5-4b00-a997-fb8fcb14296c" />



