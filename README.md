# Support-Vector-Machines-

# 🧠 Support Vector Machines (SVM) Intuition

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-Enabled-lightgrey.svg)

## 📌 Overview
This repository contains a Jupyter Notebook dedicated to building a strong intuitive understanding of **Support Vector Machines (SVM)**. Rather than just treating the algorithm as a black box, this project explores the underlying mechanics of SVMs, how decision boundaries are formed, and the impact of hyperparameter tuning on model performance.

## 🎯 Key Learning Objectives
* **The Mathematics of Margins:** Understanding how SVM maximizes the margin between different classes.
* **Support Vectors:** Identifying the critical data points that dictate the position of the hyperplane.
* **The Kernel Trick:** Exploring how to solve non-linear classification problems by projecting data into higher dimensions (focusing on the **RBF kernel**).
* **Hyperparameter Tuning:** Visualizing the trade-offs of the Bias-Variance dilemma by adjusting:
  * `C` (Regularization parameter): Controlling the penalty for misclassified points (Hard margin vs. Soft margin).
  * `Gamma`: Defining the influence of a single training example in the RBF kernel.

## 🛠️ Technologies & Libraries Used
* **Python 3**
* **Pandas & NumPy:** For data manipulation and mathematical operations.
* **Scikit-Learn (`sklearn`):** For model building, grid search (`GridSearchCV`), and evaluation.
* **Matplotlib & Seaborn:** For visualizing decision boundaries, support vectors, and data distributions.

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries. You can install the dependencies using `pip`:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
