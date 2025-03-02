This is a fine-tuned VGG16 image classification model (binary classification). The following modifications have been made:

Fine-tuned the Fully Connected (FC) layers (last three layers).

Changed the activation function from softmax to sigmoid.

Performed hyperparameter tuning.

These changes were necessary because my laptop's GPU could not handle the training without them. If you want to train using the original VGG16, you may need to modify the model accordingly.

This project uses Anaconda for version control and Jupyter Notebook as the development environment.

Reference Paper

Original VGG16 paper: Very Deep Convolutional Networks for Large-Scale Image Recognition

Environment Setup

Use the following commands to install the required environment:

conda install python=3.7.16
conda install tensorflow-gpu=2.5

If you encounter issues with downloading or setting up the environment, I highly recommend checking out this guide: Anaconda & TensorFlow Setup Guide

Dataset Download

Download the dataset required for training from the following link:
Download Dataset

Issues & Feedback

If you encounter any issues while using this project, please let me know, and I will try to resolve them when I have time.

