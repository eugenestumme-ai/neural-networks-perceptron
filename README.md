# Neural Network Fundamentals & Perceptrons

Exploratory analysis and hands-on implementation of single-layer perceptrons, manual backpropagation, and multi-layer perceptron (MLP) architectures for non-linearly separable data.

## 🚀 Project Overview
This project, developed as part of coursework in Artificial Intelligence Management, demonstrates the foundational mechanics of neural networks from the ground up—moving from manual mathematical calculations to automated optimization with scikit-learn.

## 🔑 Key Topics & Technical Highlights
* **Manual Perceptrons & Activation Functions:** Implemented and compared forward-pass dynamics across **Sigmoid**, **Step**, **Tanh**, and **ReLU** activation functions, analyzing their outputs and boundaries for customer churn prediction data.
* **Perceptron Learning Algorithm:** Trained a single-layer perceptron on logical gates, tracing weight updates and epoch convergence for an **AND gate**. Demonstrated why single-layer perceptrons fail on non-linearly separable functions like **XOR**.
* **Manual Backpropagation & Gradient Descent:** Walked through the complete chain rule mathematically and implemented a gradient descent loop from scratch in Python to evaluate the impact of learning rate ($\eta$) tuning and overshooting behavior.
* **MLP Architecture & Hyperparameter Optimization:** Evaluated multi-layer perceptron classifiers (`MLPClassifier`) across varying hidden layer sizes ($h$) and activation functions (`relu`, `tanh`), analyzing parameter count formulas and diagnosing the **dead ReLU problem**.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** NumPy, scikit-learn, Matplotlib, Pandas
* **Environment:** Google Colab / Jupyter Notebooks

---
*Created by Eugene Stumme | [GitHub Profile](https://github.com/eugenestumme-ai)*
