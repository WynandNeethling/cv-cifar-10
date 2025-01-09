# Computer Vision

This repository contains solutions which focuses on training Convolutional Neural Networks (CNNs) for image classification using the CIFAR-10 dataset. The assignment involves two key tasks: training basic CNNs from scratch and applying transfer learning for classification.

## Task Overview

### 1. Training Basic CNNs from Scratch (50%)

- **Objective**: Train a basic CNN from scratch on the CIFAR-10 dataset (50,000 training samples and 10,000 test samples).
- **Steps**:
  1. Set up a basic CNN using libraries like Keras or PyTorch.
  2. Experiment with different architectures and regularization strategies.
  3. Evaluate the final model on the hold-out test set.
- **Important Notes**:
  - Use a portion of the training set for validation throughout.
  - Evaluate the final model on the test set **only once** to ensure an unbiased indication of generalization.
  - Do not use test set performance to guide model design or hyperparameter tuning.

### 2. Classification with Transfer Learning (50%)

- **Objective**: Train a classification model for CIFAR-10 using transfer learning.
- **Steps**:
  1. Load a pre-trained model (e.g., VGG, Inception, ResNet, DenseNet, EfficientNet) into your environment.
  2. Replace the pre-trained model's classification layers with one or two new layers.
  3. Freeze the weights of the feature extraction (convolutional) layers and train the new layers.
  4. Optionally, fine-tune all the convolutional layers.
  5. Compare training times and test accuracies with the best model from Task 1.
- **Additional Notes**:
  - Provide a short motivation for your choice of pre-trained model.
  - Address differences in image dimensions between ImageNet and CIFAR-10 and explain how these differences are handled.

## Submission Guidelines

- Use any deep learning library (e.g., Keras, PyTorch).
- Submit a **condensed and neatly edited report** or notebook.
  - Include short descriptions of what you did, results, and a brief discussion/interpretation.
- Cite all sources other than the lecture slides.

## Dataset

The assignment uses the **CIFAR-10 dataset**, a popular image classification dataset with:
- **Training samples**: 50,000
- **Test samples**: 10,000
- Available through libraries like Keras and PyTorch.

## Results and Discussion

- Training and validation accuracy/loss plots.
- Final test set accuracy for both tasks.
- Comparison of training times and accuracies between Task 1 and Task 2.

