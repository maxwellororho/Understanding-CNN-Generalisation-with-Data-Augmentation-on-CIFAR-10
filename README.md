# Understanding-CNN-Generalisation-with-Data-Augmentation-on-CIFAR-10
# Improving CNN Generalisation with Data Augmentation on CIFAR-10

A TensorFlow CNN tutorial implemented in Google Colab, exploring how different levels of data augmentation affect model generalisation on the CIFAR-10 image classification dataset.

## Overview

This project investigates whether data augmentation always improves the performance of a Convolutional Neural Network (CNN). Three experiments were carried out using the same CNN architecture:

- Baseline CNN with no augmentation
- CNN with light augmentation
- CNN with strong augmentation

The aim was to examine how augmentation strength affects generalisation and whether more augmentation necessarily leads to better results.

## Main Finding

The results showed that:

- The baseline model achieved **0.752** test accuracy
- The light augmentation model achieved **0.750** test accuracy
- The strong augmentation model achieved **0.692** test accuracy

This suggests that stronger augmentation does not always improve performance, especially on very small images such as CIFAR-10 (32×32 pixels), where aggressive transformations can distort meaningful features.

## Dataset

This project uses the **CIFAR-10** dataset, which contains:

- 60,000 colour images
- 10 image classes
- 32×32 image resolution

The classes are:

- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

## Tools and Libraries

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Google Colab

## Repository Structure

```text
cnn-data-augmentation-cifar10-tutorial/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
├── notebook/
├── report/
├── presentation/
├── figures/
└── assets/
