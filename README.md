CIFAR-10 Deep Learning Training Pipeline

Project Overview

This project implements a full machine learning training pipeline for image classification using the CIFAR-10 dataset. The goal of the project is to design, implement, and evaluate a supervised learning model using deep learning while following machine learning engineering best practices such as configuration management, logging, dependency management, and version control.
The project includes data ingestion, preprocessing, model training, evaluation, logging, and artifact management.

Dataset

The project uses the CIFAR-10 dataset, which contains 60,000 32x32 color images in 10 classes. The dataset is automatically downloaded using the data ingestion pipeline.
The dataset is split into:
Training set
Validation set
Test set

Training Pipeline

The machine learning pipeline consists of the following stages:
Data ingestion and dataset download
Data preprocessing and augmentation
Train/validation/test split
Model training
Model evaluation
Saving best model
Logging metrics and training progress
