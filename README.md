Handwriting Recognition using PCA + KNN
📌 Overview

This project implements a machine learning pipeline for handwritten digit recognition using:

Principal Component Analysis (PCA) for dimensionality reduction
K-Nearest Neighbors (KNN) for classification

The goal is to improve efficiency while maintaining high accuracy.

⚙️ Workflow
Load handwritten digit dataset
Preprocess and normalize images
Apply PCA to reduce dimensions
Train KNN classifier
Evaluate accuracy
Visualize:
Variance explained by PCA
Accuracy vs number of components
Reconstructed images
📊 Key Results
PCA significantly reduces feature size
Optimal number of components balances accuracy & performance
KNN performs well even after dimensionality reduction
🛠️ Technologies Used
Python
NumPy
Matplotlib
Scikit-learn
📁 Files
pca_knn_digits.ipynb – Main implementation notebook
Visual outputs:
Sample images
Variance curve
Accuracy graph
Image reconstructions
🚀 How to Run
pip install numpy matplotlib scikit-learn

Open the notebook:

jupyter notebook pca_knn_digits.ipynb
📌 Conclusion

Combining PCA + KNN provides an efficient and accurate approach for handwritten digit recognition, reducing computational cost without major loss in performance.
