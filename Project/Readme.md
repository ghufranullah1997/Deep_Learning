# Experimental Evaluation of CNN Performance on Reduced CIFAR-100

This project explores the performance of Convolutional Neural Networks (CNNs) trained on a selected 12-class subset of the CIFAR-100 dataset. The goal was to design, train, and evaluate custom CNN architectures under resource constraints (Google Colab free tier) and systematically experiment with hyperparameters to improve image classification accuracy.

---

## 📁 Dataset

- **CIFAR-100** (12 selected classes out of 100)
- Train/Test split retained from the original dataset
- Images normalized and one-hot encoded

---

## 🎯 Objectives

- Load and preprocess a smaller custom CIFAR-100 subset
- Build CNN models from scratch with convolutional, pooling, dropout, and dense layers
- Train and evaluate models using various experimental setups
- Systematically test the effect of:
  - Network depth and layer sizes
  - Activation functions (ReLU, Sigmoid, Tanh, LeakyReLU, Swish)
  - Optimizers (Adam, SGD, RMSprop, Adagrad, etc.)
  - Batch size and number of epochs
- Generate visual insights using confusion matrices and training curves

---

## 🧪 Experiments Conducted

- **Model Depth**: Tested multiple CNN depths from 2 to 4 convolutional blocks
- **Activations**: Compared ReLU, Sigmoid, Tanh, LeakyReLU, and Swish
- **Optimizers**: Evaluated Adam, SGD, RMSprop, Adagrad, and AdamW with various learning rates
- **Training Tuning**: Varied batch size and epochs; early stopping was used to avoid overfitting

---

## 📊 Key Results

- Best test accuracy achieved: **~68%** using ReLU with a moderately deep CNN
- **ReLU** outperformed other activation functions in both stability and accuracy
- **Sigmoid** severely underperformed due to vanishing gradient issues
- **LeakyReLU and Tanh** performed better than Sigmoid, but below ReLU
- Visual analysis with confusion matrices and F1-scores was used for evaluation

---

## 📝 Deliverables

- 📁 `DL_Project_Report.ipynb` – Full notebook including data preparation, model design, training, evaluations, and plots
- 📄 Classification reports and heatmaps for model comparisons
- 📈 Training/validation curves for loss and accuracy

---

## 🛠 Tech Stack

- Python 3.x
- TensorFlow / Keras
- NumPy, Seaborn, Matplotlib, Scikit-learn
- Google Colab environment

---
