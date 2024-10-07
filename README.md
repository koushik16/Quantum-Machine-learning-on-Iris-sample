# Machine Learning and Quantum Computing on the Iris Dataset

This project implements both classical **Machine Learning** techniques and **Quantum Machine Learning** using **Scikit-learn** and **Qiskit**, respectively. The goal is to demonstrate how classical machine learning algorithms can be applied to the **Iris dataset** and explore the use of quantum circuits to enhance machine learning tasks such as feature mapping and classification.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Running the Project](#running-the-project)
- [Classical Machine Learning](#classical-machine-learning)
  - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
  - [Train-Test Split](#train-test-split)
- [Quantum Machine Learning](#quantum-machine-learning)
  - [Quantum Feature Maps](#quantum-feature-maps)
  - [Parameterized Quantum Circuits](#parameterized-quantum-circuits)
  - [Statevector Sampler](#statevector-sampler)
- [Future Work](#future-work)
- [License](#license)

## Project Overview

The project is divided into two main sections:

1. **Classical Machine Learning**:
   - We use Scikit-learn to preprocess the Iris dataset, reduce dimensionality using Principal Component Analysis (PCA), and set up a train-test split for machine learning model training.
   - This section is prepared for future machine learning models such as Logistic Regression, Support Vector Machines (SVM), and Decision Trees.

2. **Quantum Machine Learning**:
   - Using Qiskit, we introduce quantum-enhanced feature extraction using **Quantum Feature Maps**.
   - We implement a **Parameterized Quantum Circuit (PQC)** to simulate quantum-enhanced learning and use a **StatevectorSampler** to collect results.
   - The quantum circuits are explored to understand their potential in machine learning tasks such as classification, offering a foundation for future experiments in quantum-classical hybrid models.

## Dataset Description

The **Iris dataset** is one of the most well-known datasets in machine learning. It consists of 150 samples, each representing an iris flower with four features:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

Each sample belongs to one of three species of iris flowers:

1. Setosa
2. Versicolor
3. Virginica

The goal is to classify the iris flowers into these three species based on the four features.

## Project Structure

- **Ml_iris.ipynb**: This is the main Jupyter Notebook file containing all the code, including classical machine learning steps and the quantum machine learning experiments.
- **README.md**: This file, which provides an overview of the project, instructions on running the code, and background on both classical and quantum machine learning approaches.

## Dependencies

To run this project, you will need the following Python libraries:

- `qiskit`: For quantum computing, quantum circuit implementation, and running simulations.
- `scikit-learn`: For machine learning models, data preprocessing, and PCA.
- `matplotlib`: For optional visualizations and plotting quantum circuits.
- `numpy`: For handling numerical operations and arrays.

You can install the dependencies using:

```bash
pip install qiskit scikit-learn matplotlib numpy
