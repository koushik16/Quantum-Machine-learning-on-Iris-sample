# Quantum Boosting Algorithm for Iris Dataset

This project implements a **Quantum Boosting Algorithm** using **Qiskit** and compares its performance against classical boosting methods like **AdaBoost** from **Scikit-learn**. The primary goal is to explore how quantum-enhanced machine learning models can be utilized to improve classification tasks, specifically on the well-known **Iris dataset**.

## Project Overview

### Quantum Boosting Algorithm
In this project, we create weak learners using **parameterized quantum circuits (PQC)**, which are trained iteratively in a boosting framework. These quantum weak learners form the basis of the **Quantum Boosting Algorithm**, which is compared to the classical AdaBoost algorithm.

The dataset used for this experiment is the **Iris dataset**, but we simplify the problem by converting it into a binary classification problem.

### Key Components:
- **Quantum Weak Learner**: A parameterized quantum circuit (PQC) is designed for weak classification. Classical data is encoded into quantum states using quantum gates.
- **Boosting Framework**: Similar to AdaBoost, misclassified samples are given more weight in each iteration, forcing the quantum weak learners to focus more on these samples.
- **Comparison with Classical AdaBoost**: The accuracy and performance of the quantum boosting algorithm are compared with a classical boosting algorithm from Scikit-learn.

## Dependencies

The project requires the following Python libraries:

- `qiskit`: For quantum circuit implementation and simulation.
- `scikit-learn`: For classical machine learning algorithms (AdaBoost) and dataset handling.
- `matplotlib`: For visualizations (optional, for circuit visualizations).
- `numpy`: For handling numerical operations.

You can install the dependencies using pip:

```bash
pip install qiskit scikit-learn matplotlib numpy
