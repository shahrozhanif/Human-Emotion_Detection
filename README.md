# Human Emotions Detection using Deep Learning

## Overview
This project focuses on detecting human emotions from images using Convolutional Neural Networks (CNNs). It leverages deep learning techniques to classify facial expressions into three categories:
Angry
Happy
Sad

The project includes:
A baseline CNN model for emotion classification
Data preprocessing and augmentation pipeline
Hyperparameter tuning using Bayesian Optimization

## Project Structure
Human Emotions Detection/
│
├── Human Emotions Detection Using CNN.ipynb
├── Hyperparameter Tuning Using Bayesian Optimization.ipynb

## Dataset

The dataset is sourced from Kaggle:
Dataset Name: Human Emotions Dataset

It contains labeled images divided into:
Training set
Testing/Validation set

Each image belongs to one of the emotion classes.

## Installation & Setup
Download your kaggle.json API key
Place it in your working directory or set environment variables:
export KAGGLE_USERNAME=your_username
export KAGGLE_KEY=your_key

The notebook automatically downloads the dataset using Kaggle API.

## Model Architecture

The CNN model includes:
Convolutional layers
Max pooling layers
Batch normalization
Fully connected (Dense) layers
Softmax output layer

## Results
Training Set Accuracy: 98.6 %
Validation Set Accuracy: 84.7 %
Test Set Accuracy: 82.7% 