# Experimental Evaluation of CNN Performance on Reduced CIFAR-100

# 🧠 CNN Experiments with CIFAR-100 for Image Classification

This repository contains my project work for training a Convolutional Neural Network (CNN) using a subset of the CIFAR-100 dataset. The goal of the project is to explore different model architectures, activation functions, and training strategies to improve image classification accuracy under computational constraints (Google Colab free tier).

## 📁 Dataset

- **Primary**: [CIFAR-100](https://www.cs.toronto.edu/~kriz/cifar.html)
- **Optional Extension**: Subset of ImageNet (if time/resources allow)

## 📝 Project Objectives

1. **Load and preprocess** a subset of CIFAR-100 (8–12 classes, reduced samples per class)
2. **Build a CNN** from scratch using TensorFlow/Keras with:
   - Multiple convolutional and max pooling layers
   - Dense inner layers
3. **Train and evaluate** the CNN using the extracted training and test sets
4. **Experiment and improve accuracy** by testing variations in:
   - CNN architecture (depth, number of filters, kernel size)
   - Activation functions (`relu`, `sigmoid`, `softmax`, etc.)
   - Optimizers (`Adam`, `SGD`, etc.) and learning rate
   - Batch size and number of epochs

## ⚗️ Experimentation Strategy

- 🔍 Test model accuracy under different configurations
- 🔁 Compare results using:
  - Various activation function combinations
  - Different network depths and layer widths
  - Optimizer and learning rate tuning
  - Batch size and epoch changes
- 🧪 Optional: Repeat with a new 8–12 class subset of ImageNet (if feasible)

## 📊 Report

A detailed report accompanies the notebook, summarizing:

- Model design decisions
- Experimental setup and rationale
- Accuracy outcomes across all trials
- Key observations and learnings

## 🔧 Tech Stack

- Python  
- TensorFlow / Keras  
- Google Colab (for training and evaluation)

## 📌 Notes

> All experiments are conducted within the constraints of Colab's free tier (limited memory and compute).  
> Only a subset of classes from CIFAR-100 is used to speed up training and improve reproducibility.

---

Feel free to fork, run, or adapt the notebook for similar projects involving image classification using CNNs.
