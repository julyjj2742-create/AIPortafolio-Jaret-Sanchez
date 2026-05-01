# L02 - Neural Networks from Scratch to Frameworks

## Overview
In this lab, I learned how neural networks work by building them in different ways. I started by understanding the basic pieces of a network, then built one from scratch with NumPy, and finally created and trained models using PyTorch and TensorFlow/Keras. The lab helped me see how each tool handles the same task and what happens behind the scenes when a model learns.

## Purpose
The purpose of this lab was to help me understand the full process of building and training a neural network. By working with both low‑level code and high‑level frameworks, I learned how data is prepared, how models are trained, and how different tools approach deep learning.

## Key Concepts
### Building a Neural Network From Scratch
I learned how to implement the basic components of a neural network using NumPy. This helped me understand what frameworks automate for us.

### PyTorch vs. TensorFlow
The lab compared both frameworks and explained that PyTorch feels more “Pythonic,” while TensorFlow/Keras offers a bigger ecosystem.

### Data Preparation and Splits
I worked with the Fashion‑MNIST dataset and created training, validation, and test sets. The lab emphasized why the test set must stay untouched to avoid overfitting.

### Training Loops and Backpropagation
In PyTorch, I wrote the full training loop manually, including optimizer.zero_grad(), loss.backward(), and optimizer.step(). This showed me how gradients and weight updates work.

### Keras Compile/Fit Workflow
With TensorFlow/Keras, training was much simpler. The compile() and fit() methods handled the entire training pipeline automatically.

### Hyperparameter Tuning
I experimented with different learning rates and epochs to see how they affect accuracy. This helped me understand how sensitive models are to these settings.

### Overfitting and Dropout
The lab introduced dropout as a way to prevent overfitting by randomly turning off neurons during training.
