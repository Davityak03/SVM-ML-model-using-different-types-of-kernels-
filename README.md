# SVM-ML-model-using-different-types-of-kernels-
# Support Vector Machine (SVM) with Various Kernels on the Banana Dataset
This repository contains a project that demonstrates the use of Support Vector Machine (SVM) with different kernel functions on the Banana dataset. The kernels used are:
- Radial Basis Function (RBF)
- Linear
- Polynomial (Poly)
- Sigmoid

## Introduction
Support Vector Machines (SVM) are powerful supervised learning models used for classification and regression tasks. This project illustrates how SVM performs with different kernel functions on the Banana dataset, a synthetic dataset commonly used for benchmarking classification algorithms.

## Theory
### Support Vector Machine (SVM)
SVM is a supervised machine learning algorithm used for both classification and regression tasks. However, it is mostly used for classification problems. The goal of the SVM algorithm is to find a hyperplane in an N-dimensional space (N - the number of features) that distinctly classifies the data points.
### Kernels
A kernel is a function that takes low-dimensional input space and transforms it into a higher-dimensional space. In other words, it converts non-separable problems into separable problems by adding more dimensions to it. This makes SVM powerful, as it can handle classification in a high-dimensional space.
The most commonly used kernels are:
- **Linear Kernel**: The simplest kernel function. It is often used when the data is linearly separable.
- **Polynomial Kernel**: Represents the similarity of vectors in a feature space over polynomials of the original variables, allowing the learning of non-linear models.
- **Radial Basis Function (RBF) Kernel**: Also known as the Gaussian kernel. It is a general-purpose kernel; used when there is no prior knowledge about the data.
- **Sigmoid Kernel**: Used as a proxy for neural networks.

## Dataset
The Banana dataset is a synthetic dataset that is commonly used to benchmark machine learning algorithms. It consists of two features and a target label indicating the class. The features are often non-linearly separable, making it an excellent choice for demonstrating the power of different kernel functions in SVM. The datset has been taken from kaggle
