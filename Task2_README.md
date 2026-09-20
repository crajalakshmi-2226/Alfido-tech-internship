
# Task 2: Deep Learning Image Classification

## Project Overview
This project implements image classification using a pretrained ResNet18 model with transfer learning and PyTorch.

## Technologies Used
- Python
- PyTorch
- Torchvision
- CIFAR-10 Dataset
- Transfer Learning
- Google Colab

## Model Details
- Model: Pretrained ResNet18
- Dataset: CIFAR-10
- Training Images: 10,000
- Testing Images: 2,000
- Number of Classes: 10
- Device: CUDA GPU

## Data Augmentation
- Random Crop
- Random Horizontal Flip
- Image Resizing
- Image Normalization

## Training
The model was trained for 3 epochs using the Adam optimizer and Cross Entropy Loss.

## Model Saving
The trained model was saved as:

cifar10_resnet18_transfer_learning.pth

## Inference Instructions
1. Open the Google Colab notebook.
2. Install the required libraries.
3. Load the saved model.
4. Apply the test image transformations.
5. Pass the image to the model.
6. Display the predicted class.

## Results
Training accuracy reached approximately 74.68% after 3 epochs.

## Author
C. Rajalakshmi
