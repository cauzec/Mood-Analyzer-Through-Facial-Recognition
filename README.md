# Mood-Analyzer-Through-Facial-Recognition

## Overview

This repository contains a comprehensive solution for Mood Analysis using Facial Recognition (SAFR). The project integrates state-of-the-art facial recognition algorithms with advanced mood analysis models to provide a robust system for understanding emotional states in real-time.

## Key Features

Facial Recognition: Utilizes cutting-edge face recognition algorithms to extract and recognize facial features with high precision. Modern image processing techniques capture minor nuances in expressions, providing a solid foundation for emotional cues interpretation.

Mood Analysis: Enhances facial recognition outcomes by incorporating advanced mood analysis algorithms. These models consider not only main emotions but also secondary expressions and contextual signals, resulting in a more thorough understanding of human emotions.

Dataset Utilization: The project utilizes diverse datasets, including CK+ for Facial Expression Recognition (FER), Japanese Female Facial Expression dataset, and FER2013, ensuring a comprehensive portrayal of emotions for robust model building.

Working Methodology: Follows a structured pipeline involving data collection, preprocessing (face detection, dimension reduction, normalization), feature extraction (facial landmarks detection), and emotion classification using machine learning or deep learning models.

## Software Details

Programming Language: Python

Machine Learning Frameworks: TensorFlow or PyTorch

Image Processing Libraries: OpenCV

Version Control: Git

Development Environment: VSCode, Google Collab, or Jupyter Notebooks

## Models

### Model 1: Simple CNN
Utilizes convolutional layers with batch normalization, ReLU activation, max-pooling, and dropout for Mood analysis.
Designed for accuracy optimization over the number of parameters.

### Model 2: Mini Xception
A customized version of the Xception model designed for real-time emotion identification.
Integrates depth-wise separable convolutions, residual connections, and regularization techniques for computational efficiency and expressive capabilities.

Advantages of Mini Xception Model:
Transfer learning
Computational efficiency
Improved convergence

## Integration with OpenCV

Detects emotions in real-time video frames using OpenCV's CascadeClassifier.
Pre-trained Xception model evaluates individual frames, providing instantaneous insights into captured emotional expressions.

## Working Example of the Project

https://github.com/cauzec/Mood-Analyzer-Through-Facial-Recognition/assets/63592624/9b3d45e2-7ded-46d2-bc65-f5702d6b831a

