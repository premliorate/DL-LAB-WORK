Deep Learning Lab Series
Course: Deep Learning (22AIE304)

Batch: 2024-2028

Author: PREM SANTH C K

Roll Number: CH.SC.U4AIE24056
 Overview
This repository contains a series of foundational Deep Learning laboratory implementations. The code explores artificial neural network concepts ranging from basic single-layer perceptrons to multi-layer perceptrons (MLPs) and Deep Neural Networks (DNNs) applied to image classification tasks.

All scripts are specifically optimized and formatted to run seamlessly in Google Colab.

 Lab Contents
Lab 1: Perceptron Learning Implementation
Objective: Implement a single-layer Perceptron using the Heaviside step function from scratch using NumPy.

Tasks: * Train the model on the logic AND gate and visualize the decision boundary.

Attempt to train the model on the XOR gate to demonstrate the Perceptron Convergence Theorem (linearly inseparable data).

Calculate Accuracy, Precision, and Recall.

Lab 2: MLP and Hyperparameter Tuning
Objective: Build a Multi-Layer Perceptron (MLP) using TensorFlow/Keras to solve the non-linear XOR problem.

Tasks: * Experiment with different activation functions (sigmoid vs. relu).

Test different learning rates (0.01 vs. 0.1) and observe the impact on training loss and final accuracy.

Lab 3: Hyperparameter Optimization (Grid Search)
Objective: Automate the search for optimal neural network configurations.

Tasks: * Build an advanced MLP with dropout layers.

Use sklearn.model_selection.ParameterGrid to iterate through combinations of learning rates, hidden units, and dropout rates.

Evaluate models based on validation accuracy and check for overfitting.

Lab 4: DNN for MNIST Digit Classification
Objective: Construct a Deep Neural Network to classify handwritten digits (0-9) from the MNIST dataset.

Tasks: * Preprocess and normalize image data.

Build a sequential model with multiple dense and ReLU layers, ending in a softmax classification layer.

Evaluate test accuracy and loss.

Generate a classification report and plot a Seaborn heatmap of the Confusion Matrix.

Identify and output specific misclassified examples.

 Requirements & Dependencies
To run these scripts locally or in Colab, ensure you have the following Python libraries installed:

Bash
pip install numpy matplotlib tensorflow scikit-learn seaborn
 How to Run (Google Colab)
Open Google Colab.

Create a new notebook or upload the .ipynb / .py files.

Paste the code for the specific lab into a code cell.

Run the cell (Shift + Enter).

All visualizations, including the Lab 1 decision boundary and Lab 4 confusion matrix, will render directly within the Colab output cell.
