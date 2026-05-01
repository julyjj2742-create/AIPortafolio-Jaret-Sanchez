# L03 - CNN

## Overview 
In this lab, I learned how Convolutional Neural Networks (CNNs) work by training a model to tell the difference between a puppy and a bagel. I worked with a real image dataset, built my own CNN from scratch, and then tried transfer learning with pre‑trained models. This lab helped me understand how CNNs process images and why they’re so effective for visual classification tasks.

## Purpose
The purpose of this lab was to help me understand how CNNs handle image classification tasks. By building my own CNN and then comparing it to pre‑trained models, I learned the difference between training from scratch and using transfer learning. The lab also helped me practice working with custom datasets, data augmentation, and evaluation tools like confusion matrices and classification reports.

## Key Concepts
### CNNs
CNNs use convolutional layers, pooling layers, and feature maps to learn patterns in images. The notebook explains that they learn edges, textures, shapes, and objects in a hierarchical way.

### The Puppy vs. Bagel Dataset
The dataset is based on the meme showing how puppies can look like bagels. Both classes share similar shapes and colors, which makes the classification task more challenging and a good test for CNNs.

### Data Augmentation
I used ImageDataGenerator to rotate, flip, zoom, and shift images. This helps the model generalize better and prevents overfitting by showing the model different versions of the same image.

### Building a CNN From Scratch
I created a custom CNN using multiple Conv2D and MaxPooling layers, followed by Flatten, Dense, and Dropout layers. This helped me understand how each layer contributes to feature extraction and classification.

### Transfer Learning
I also worked with pre‑trained models like ResNet50 and MobileNetV2. These models already learned useful features from large datasets, so fine‑tuning them made training faster and more accurate.

### Model Evaluation
I used accuracy, confusion matrices, and classification reports to evaluate how well the model performed on the puppy vs. bagel task.
