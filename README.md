# Iris-and-Spam-Classifier

This repository demonstrates the implementation of a **Decision Tree Classifier** built from scratch in Python, applied to the classic **Iris dataset** and **Spambase dataset**.  
It walks through dataset preprocessing, entropy and information gain calculation, recursive tree building, model training/testing, and performance evaluation — without relying on scikit-learn’s built-in `DecisionTreeClassifier`.

## 📌 Features
- Load and process the **Iris dataset**
- Load and process the **Spambase dataset**
- Core decision tree components:
  - Entropy and information gain
  - Recursive node splitting
  - Stopping criterion (`nmin`: minimum samples required to split)
- Training and testing with cross-validation
- Evaluation using accuracy scores
- Analysis of **`nmin` effect** on model depth, variance, and accuracy
- Visualizations of decision tree performance trends

## Prerequisites
- Download the respective dataset files in repo.
- Python 3.8+.
- Anaconda set up.

## How to Run
1. Copy github repository.
2. Run Jupyter Notebook.
3. Run all cells.
