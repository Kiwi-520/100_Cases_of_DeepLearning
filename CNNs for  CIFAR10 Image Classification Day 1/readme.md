# CIFAR-10 CNN Image Classifier: Diagnostics and Regularization Case Study

## 🚀 Project Overview
This repository contains the complete code for a Convolutional Neural Network (CNN) trained to classify the 10 classes of the CIFAR-10 dataset.

The primary focus of this project was not just building the model, but demonstrating the **end-to-end process of diagnosing and solving severe overfitting** through iterative model tuning and data flow adjustments.

## 🌟 Key Technical Achievements
This project showcases the mastery of several crucial ML engineering concepts:

* **Model Diagnostics:** Identifying the point of severe **overfitting** by analyzing the divergence between training and validation loss curves.
* **Regularization Strategy:** Successfully stabilized the model by iteratively increasing the **Dropout rate (0.5)** to prevent neuron co-dependency.
* **Data-Centric AI:** Implemented robust **Data Augmentation** using the `ImageDataGenerator` to artificially expand the training dataset and solve the root cause of the overfitting.
* **Pipeline Debugging (MLOps):** Resolved a critical **Double Encoding Error** (shape mismatch) during the data flow setup, demonstrating attention to data pipeline integrity.
* **Final Architecture:** Implementation of a Keras Sequential model with Conv2D, MaxPooling2D, Flatten, and Dense layers.

## 📂 Repository Contents
* `CNN_CIFAR10_CaseStudy.ipynb`: The main Jupyter/Colab notebook containing all code for data loading, preprocessing, model definition, training, visualization, and final evaluation.
* `README.md`: This file.

## 🛠️ Requirements
* Python 3.x
* TensorFlow / Keras
* NumPy
* Matplotlib
