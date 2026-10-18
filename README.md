# K-Nearest Neighbors (KNN): From Scratch to Advanced Concepts

A comprehensive deep dive into the K-Nearest Neighbors (KNN) machine learning algorithm using Python, NumPy, and scikit-learn. 

This repository contains an end-to-end Jupyter Notebook that breaks down the math, intuition, and code behind KNN. It moves from a foundational scratch implementation to exploring advanced caveats like the Curse of Dimensionality and the critical importance of feature scaling.

## 🧠 Key Features & Explorations

*   **Algorithm from Scratch:** A complete implementation of the KNN algorithm using pure NumPy and Euclidean distance.
*   **Library Validation:** Cross-verification of the custom implementation against `scikit-learn`'s `KNeighborsClassifier`.
*   **Hyperparameter Tuning:** Using 5-fold cross-validation to find the optimal `K` and analyzing the bias-variance trade-off.
*   **Decision Boundaries:** 2D visualizations of how different `K` values impact the model's classification territories using the Iris dataset.
*   **Feature Scaling:** A practical experiment using the Breast Cancer dataset to prove why standardizing data is mandatory for distance-based algorithms.
*   **KNN Regression:** Extending the algorithm to predict continuous values using noisy sine wave data.
*   **The Curse of Dimensionality:** A mathematical demonstration of how distance metrics break down in high-dimensional spaces.

## 🛠️ Technologies Used
*   Python 3
*   NumPy & Pandas (Data manipulation and custom math)
*   Scikit-learn (Model validation, datasets, and preprocessing)
*   Matplotlib & Seaborn (Data visualization)

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/RimeeAwasthi01/Comprehensive-KNN-Implementation.git](https://github.com/RimeeAwasthi01/Comprehensive-KNN-Implementation.git)
   cd KNN-Deep-Dive
