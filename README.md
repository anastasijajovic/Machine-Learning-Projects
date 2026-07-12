# Artificial Intelligence & Machine Learning Portfolio

This repository contains a collection of machine learning models implemented from scratch or using standard data science libraries (such as `pandas`, `scikit-learn`, and `Keras`/`TensorFlow`). The project covers a wide range of paradigms, including supervised learning, unsupervised learning, and deep learning architectures.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Data Preprocessing:** Pandas, NumPy, Scikit-learn (One-Hot Encoding, StandardScaler)
* **Modeling & Frameworks:** Scikit-learn, Keras / TensorFlow (for Neural Networks)
* **Visualization:** Matplotlib, Seaborn

---

## 🤖 Implemented Models & Techniques

### 1. Supervised Learning: Regression & Classification

#### 📈 Linear Regression
* **Concept:** Modeled continuous target variables by establishing a linear relationship between independent features and the dependent output.
* **Implementation:** Handled feature scaling, evaluated model performance using $R^2$ score and Mean Squared Error (MSE).

#### 🌲 Decision Trees
* **Concept:** Developed classification models utilizing tree-like structures based on feature splitting.
* **Implementation:** Analyzed information gain and Gini impurity to optimize tree depth and prevent overfitting.

#### 🎯 K-Nearest Neighbors (KNN)
* **Concept:** Implemented a distance-based instance classifier that categorizes data points based on the majority vote of their closest neighbors.
* **Implementation:** Experimented with different $k$ values and distance metrics (Euclidean, Manhattan).

---

### 2. Unsupervised Learning: Clustering

#### 📊 K-Means Clustering
* **Concept:** Partitioned unlabelled data into $K$ distinct, non-overlapping clusters by minimizing the variance within each cluster (Inertia).
* **Implementation:** Used the Elbow Method to determine the optimal number of clusters ($K$).

#### 🌿 Hierarchical Clustering
* **Concept:** Built a tree of clusters (dendrogram) using an agglomerative (bottom-up) approach to visualize data relationships.
* **Implementation:** Analyzed different linkage criteria (Ward, Complete, Average) to determine hierarchical structures.

---

### 3. Deep Learning: Neural Networks

#### 🧠 Multi-Layer Perceptron (MLP) / Artificial Neural Networks (ANN)
* **Concept:** Engineered fully connected neural network architectures designed to model complex, non-linear relationships.
* **Implementation:** 
  * Performed thorough data preprocessing including handling categorical features via **One-Hot Encoding**.
  * Configured multi-layered network structures with custom activation functions (ReLU, Sigmoid, Softmax).
  * Evaluated model accuracy, loss curves, and optimization techniques during training.

---

## 📊 Evaluation Metrics Used
To ensure model robustness, the following evaluation techniques were applied:
* **Classification:** Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
* **Regression:** $R^2$ Score, MSE, and MAE.
* **Clustering:** Silhouette Score and Dendrogram analysis.

---

## 📁 Repository Structure
```text
├── data/                  # Datasets used for training and testing
├── notebooks/             # Jupyter Notebooks with step-by-step EDA and modeling
│   ├── linear_regression.ipynb
│   ├── clustering_analysis.ipynb
│   ├── knn_decision_trees.ipynb
│   └── neural_networks.ipynb
└── README.md              # Project documentation
