# CIFAR100-Classifier
Neural network classifier for the CIFAR-100 dataset. My network includes features from state-of-the-art neural networks such as the GoogleNET Inception layer, ResNET skip connections and DenseNET skip connections.

This project implements an image classification model trained on the [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html) dataset using **PyTorch**.

Features:

- Uses `torchvision.datasets.CIFAR100` to load and preprocess data.
- Implements a Convolutional Neural Network (CNN) architecture using `torch.nn`.
- Trains the model using `torch.optim` with backpropagation.
- Evaluates model accuracy and plots sample predictions.

Libraries Used:

- [PyTorch](https://pytorch.org/) - for building and training the neural network
- [Torchvision](https://pytorch.org/vision/stable/index.html) - for dataset loading and image transformations
- `matplotlib` - for data visualization and plotting sample predictions
