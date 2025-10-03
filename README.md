#  Iris Flower Species Classification using K-Nearest Neighbors

![Python Version](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Libraries](https://img.shields.io/badge/Libraries-Scikit--learn%20%7C%20Pandas%20%7C%20Seaborn-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

### 📋 Project Overview

This project provides a comprehensive walkthrough of building a machine learning model to classify the species of Iris flowers based on their sepal and petal measurements. We employ the K-Nearest Neighbors (KNN) algorithm, a simple yet powerful classification method, to achieve high accuracy. The analysis includes finding the optimal value of 'K' and visualizing the model's decision boundaries.

---

### 📊 Dataset

The project utilizes the classic **Iris dataset**, which contains 150 samples from three species of Iris flowers (Iris setosa, Iris versicolor, and Iris virginica). Four features were measured for each sample:

* `SepalLengthCm`
* `SepalWidthCm`
* `PetalLengthCm`
* `PetalWidthCm`

---

### 🚀 Analytical Workflow

1.  **Data Loading & Preprocessing**: The Iris dataset is loaded, and features are normalized using `StandardScaler` to ensure uniform scale.
2.  **Optimal K Selection**: The **Elbow Method** is used to determine the most effective number of neighbors (K) by plotting model accuracy against a range of K values.
3.  **Model Training**: A `KNeighborsClassifier` is trained on the preprocessed data using the optimal K.
4.  **Performance Evaluation**: The model is evaluated on a held-out test set using metrics like accuracy and a confusion matrix.
5.  **Decision Boundary Visualization**: The classifier's decision boundaries are plotted on a 2D feature space to visually understand how it separates the different species.

---

### 📈 Key Results

The model achieved high classification accuracy. The optimal value for K was identified, leading to a robust and reliable classifier.

| Metric            | Score                |
| ----------------- | -------------------- |
| **Optimal K**
