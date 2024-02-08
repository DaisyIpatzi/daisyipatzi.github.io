---
title: "Object Recognition with Convolutional Neural Networks"
subtitle: "A CIFAR-10 Dataset Case Study"
date: 2024-02-08 00:00:00
description: "Object Recognition with Convolutional Neural Networks: A CIFAR-10 Dataset Case Study."
featured_image: "images/demo/neuron.jpg"
---


## 1. Introduction

In this project, we investigate into the field of machine learning and image recognition by developing a neural network model using the CIFAR-10 dataset (Krizhevsky, 2009). Our objective is to create a Convolutional Neural Network (CNN) using Keras, an open-source neural network library in Python, constructed to facilitate quick experimentation with deep neural networks.

As noted by Chollet (2015), Keras stands out for its high-level interface, providing a simpler entry point into deep learning, and its ability to operate on top of TensorFlow, a comprehensive platform for machine learning. To facilitate our development process, we will utilise Google Colab, a cloud-based Python programming environment.

This project covers critical aspects of machine learning, from data preprocessing and division of the dataset into training, validation, and testing sets, to defining the CNN architecture and fine-tuning hyperparameters. Our focus will be on preventing overfitting, ensuring model generalisation, and optimising the network's performance.

## 2. Overview of the CIFAR-10 Dataset

According to Krizhevsky (2009), the CIFAR-10 dataset (Canadian Institute for Advanced Research, 10 classes) is a subset of the Tiny Images dataset and contains 60,000 32x32 colour images, gaging from animals to vehicles (see Exhibit 1).

This dataset is balanced, with each class represented by 6,000 images, ensuring unbiased training for machine learning models. My detailed data analysis focused on this balance, crucial for preventing model bias (Huang et al., 2022).

I conducted an analysis of the distribution of pixel values to gain a better understanding of the data's structure (see Exhibit 2). By plotting histograms for both the training and test sets, I observed a consistent distribution pattern where the majority of pixel values cluster in the lower range, indicating that many images have darker pixels. This insight is particularly valuable for preprocessing steps such as normalization and can significantly influence the robustness and performance of the trained model.

The histograms for the training and test sets expose a similar distribution, which is a promising indication that the model will perform consistently on unseen data.

![](/images/demo/E1_CNN.jpg)

![](/images/demo/E2_CNN.jpg)

