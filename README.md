# Deep Embedded Clustering for Image Dataset Organization

## 📌 Project Overview

This project implements **Deep Embedded Clustering (DEC)** for organizing a large unlabeled image dataset.

A **deep autoencoder** is first used to learn a compact representation of the images. The learned **32-dimensional latent features** are then clustered using **K-Means**.

The project is implemented **from scratch** without using high-level machine learning libraries such as Scikit-learn, TensorFlow, or PyTorch.

---

## 🎯 Objective

To use a deep autoencoder to learn meaningful image representations and then apply K-Means clustering in the learned latent space to organize a large unlabeled image dataset.

---

## 📂 Dataset

**Fashion-MNIST**

- Training images: **60,000**
- Image size: **28 × 28**
- Input features: **784**
- Number of classes: **10**
- Image type: Grayscale

The original class labels are used **only for evaluation**, not during training or clustering.

---

## 🧠 Methodology

The project follows these steps:

```text
Fashion-MNIST Images
        ↓
Data Preprocessing
        ↓
Deep Autoencoder
        ↓
32-Dimensional Latent Features
        ↓
K-Means Clustering
        ↓
Cluster Evaluation
        ↓
Visualization & Analysis
