# Overview


This program uses Convolutional Neural Networks (CNNs) with PyTorch to implement an image classification system. The program is designed to classify images from the CIFAR-10 dataset of 60,000 32x32 color images in 10 classes with 6,000 images per class. The classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck. 


# Functionality

- **Data Preparation:** The program automatically downloads the CIFAR-10 dataset and preprocesses it for training. It then performs transformations such as normalization and augmentation to prepare the data for input into the CNN model.

- **CNN Model Architecture:** The program defines a CNN model architecture consisting of convolutional layers, pooling layers, and fully connected layers. The model is designed to learn hierarchical features from raw pixel data and make predictions about the class of each input image.

- **Training:** The program trains the CNN model using the training dataset. It uses the stochastic gradient descent (SGD) optimizer with cross-entropy loss to optimize the model parameters. During training, the program monitors the training loss and accuracy to evaluate the model's performance.

- **Evaluation**: After training, the program evaluates the trained model on a separate test dataset to assess its performance. It calculates metrics such as accuracy, precision, recall, and F1-score to measure the model's effectiveness in classifying images.

- **Visualization:** The program provides visualization components to visualize predictions made by the model on a sample of test images. It displays the predicted classes and ground truth labels for each image, allowing users to assess the model's performance visually.


# Usage

It's preferred to use this file on Google Collab for a smooth run. However, if you prefer to run it locally the libraries required to install are:

```bash
pip install torch torchvision
```

```bash
pip install matplotlib
```

```bash
pip install numpy
```
