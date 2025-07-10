Ensemble Learning for Image Classification on Fashion MNIST
The goal was to build and compare individual ensemble classifiers

This project aims to build a robust and generalizable image classification system for the Fashion MNIST dataset. Rather than relying on a single model, this work focuses on developing and evaluating ensemble learning techniques—specifically Voting and Stacking—to enhance predictive performance by combining the strengths of multiple diverse classifiers.

The core models developed and ensembled are:

    Random Forest Classifier

    Multi-Layer Perceptron (MLP) using TensorFlow and Keras

    Support Vector Machine (SVM)


This project successfully demonstrates the power of ensemble learning. All three ensemble methods—Hard Voting, Soft Voting, and Stacking—outperformed the best-performing individual model (MLP). The Soft Voting ensemble provided the best balance of performance and computational cost, achieving the highest overall F1-score and accuracy. This underscores the principle that combining diverse, reasonably accurate models can lead to a more robust and powerful predictive system.
