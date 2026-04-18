# CIFAR-10 Image Classification using CNN (PyTorch)

##  Overview

This project implements a Convolutional Neural Network (CNN) for image classification on the CIFAR-10 dataset using PyTorch.

The model is trained to classify images into 10 categories such as airplanes, cars, birds, cats, and more.

---

##  Dataset

* CIFAR-10 Dataset from torchvision
* 60,000 color images (32x32)
* 10 classes:

  * Airplane, Automobile, Bird, Cat, Deer
  * Dog, Frog, Horse, Ship, Truck

---

##  Tech Stack

* Python
* PyTorch
* Torchvision
* NumPy

---

##  Data Preprocessing

* Converted images to tensors using `ToTensor()`
* Normalized using:

  ```
  (0.5, 0.5, 0.5)
  ```
* Loaded using `DataLoader` for batching and shuffling

---

##  Model Architecture

* Convolutional Neural Network (CNN)
* Multiple layers including:

  * Convolution layers
  * Activation functions (ReLU)
  * Fully connected layers

---

##  Training Process

The model is trained using:

1. Forward Propagation
2. Loss Calculation using CrossEntropyLoss
3. Backpropagation
4. Optimizer step (weights update)

### Training Loop

* Number of epochs: 10
* Loss is tracked and printed per epoch

---

##  Results

* Training loss decreases over epochs
* Model learns meaningful features from images


---



## 🔧 Future Improvements

* Add test accuracy evaluation
* Increase model depth


