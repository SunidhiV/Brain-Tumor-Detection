# Brain Tumor Detection using VGG16

## Overview

This project focuses on leveraging machine learning to detect brain tumors in MRI images. The dataset used is sourced from Kaggle, containing images of brains with and without tumors. The model is built using the VGG16 architecture, and its accuracy is evaluated to assess its effectiveness in tumor detection.

## Dataset

The dataset consists of MRI images from Kaggle's Brain MRI Images for Brain Tumor Detection dataset. The images are categorized into two classes: those with tumors(positive) and those without(negative).

- Dataset Link: [Kaggle - Brain MRI Images for Brain Tumor Detection](<https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data>)

## Model Architecture

The VGG16 (Visual Geometry Group) model is employed for its deep architecture and proven performance in image classification tasks. Transfer learning is utilized by fine-tuning the pre-trained VGG16 model on the brain tumor dataset.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- OpenCV
