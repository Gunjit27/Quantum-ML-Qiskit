# Quantum-ML-Qiskit

This repository contains end-to-end experiments applying Quantum Machine Learning (QML) models to real-world datasets using [Qiskit](https://qiskit.org/). The notebook explores both classical machine learning baselines and advanced quantum models like Quantum Neural Networks (QNNs) and Variational Quantum Classifiers (VQCs).

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Main Sections](#main-sections)
- [How to Run](#how-to-run)

---

## 📖 Introduction

Quantum Machine Learning (QML) leverages the principles of quantum computing to enhance classical machine learning algorithms. This project explores the use of Qiskit's Machine Learning module to implement models such as Quantum Support Vector Classifier (QSVC), Variational Quantum Classifier (VQC), and Quantum Neural Networks (QNNs).

The goal is to compare the performance of quantum-enhanced models with traditional machine learning techniques.

---

## 🚀 Technologies Used

- Python 3.8+
- Qiskit (Quantum Circuits, Machine Learning)
- Qiskit Aer (Quantum Simulation)
- Matplotlib & Seaborn (Data Visualization)
- Scikit-learn (Classical ML Models)
- LIME (Model Interpretability)


---

## 🧪 Main Sections

### 1. Libraries
- Installation of Qiskit, Qiskit Machine Learning, and auxiliary libraries.

### 2. Data Exploration
- Dataset loading
- Feature visualization using Seaborn/Matplotlib.

### 3. Classical Machine Learning Models
- Training traditional classifiers (e.g., Random Forest, SVM) for baseline comparisons.

### 4. Quantum Machine Learning Models
- **Quantum Support Vector Classifier (QSVC)** using Quantum Kernel Methods.
- **Feature Mapping** using:
  - ZZ Feature Map
  - Pauli Feature Map
- **Variational Quantum Classifier (VQC)**
  - RealAmplitudes ansatz
  - Classical optimizer integration (COBYLA, L-BFGS-B).
- **Quantum Neural Networks (QNN)**
  - Building multiple models.
  - Experimenting with architecture and parameters.
  - Accuracy evaluation and model comparison.

### 5. Interpretability
- Using LIME to interpret and explain the trained models' predictions.

---

## ⚡ How to Run Locally

1. Clone this repository:

    ```bash
    git clone https://github.com/Gunjit27/Quantum-ML-Qiskit.git
    cd Quantum-Machine-Learning-Qiskit
    ```

2. Install dependencies:

    ```bash
    pip install qiskit[visualization]
    pip install qiskit==1.4.2
    pip install qiskit-machine-learning
    pip install qiskit-aer
    pip install qiskit-algorithms
    pip install lime
    pip install scikit-learn
    ```

3. Open the notebook:

    ```bash
    jupyter notebook QML.ipynb
    ```

4. Execute cells step-by-step.

---
