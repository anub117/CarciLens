# CarciLens: Breast Cancer Detection using Neural Networks

## Overview
CarciLens is a machine learning project built to classify breast cancer tumors as benign or malignant. The project uses a neural network built with TensorFlow and Keras, trained on the Breast Cancer Wisconsin dataset, to make predictions based on various features extracted from breast cancer cell samples.

## Objective
This project aims to automate the process of breast cancer diagnosis by using deep learning techniques. The model achieves high accuracy in distinguishing between malignant and benign tumors.

## Dataset
This project uses the [Breast Cancer Wisconsin dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) from `sklearn.datasets`. It consists of 30 features derived from digitized images of breast mass biopsies.

- **Features**: 30 numeric attributes (e.g., radius, texture, smoothness, area, etc.).
- **Target**: The target variable is binary: `0` for malignant tumors and `1` for benign tumors.

## Requirements

- Python 3.x
- TensorFlow >= 2.0
- Scikit-learn
- Numpy
- Matplotlib
