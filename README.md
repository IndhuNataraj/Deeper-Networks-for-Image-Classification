# Deeper Networks for Image Classification

This project investigates the performance of deeper convolutional neural network architectures for image classification. It compares **VGG16-style CNN** and **GoogLeNet/Inception-style CNN** models using the **MNIST** and **CIFAR-10** datasets.

## Project Overview

The aim of this project is to understand how deeper neural networks perform on different types of image datasets:

- **MNIST**: grayscale handwritten digit images
- **CIFAR-10**: colour object images across 10 classes

The project includes:

- Dataset loading and preprocessing
- Image normalization
- CNN model implementation
- VGG-style model training
- GoogLeNet/Inception-style model training
- Accuracy comparison
- Training and validation accuracy visualization

## Models Used

### VGG16-style CNN
A deep convolutional neural network using multiple convolutional layers with small filters, max-pooling layers, and dense layers for classification.

### GoogLeNet/Inception-style CNN
A CNN architecture based on Inception modules, using multiple convolution branches with different filter sizes to capture features at different scales.

## Datasets

The project uses:

- MNIST dataset
- CIFAR-10 dataset

Both datasets are loaded directly using TensorFlow/Keras or TorchVision depending on the notebook.

## Project Files


## Requirements

Install the required libraries before running the notebooks:

```bash
pip install numpy tensorflow matplotlib torch torchvision

#How to Run the Project
1. Clone the repository
    git clone https://github.com/your-username/deeper-networks-image-classification.git
    cd deeper-networks-image-classification
2. Install dependencies
    pip install numpy tensorflow matplotlib torch torchvision
3. Open Jupyter Notebook
    jupyter notebook
4. Run the notebooks
     datasets.ipynb
     Model.ipynb
