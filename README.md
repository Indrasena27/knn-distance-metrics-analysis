# K-Nearest Neighbours (KNN) and Distance Metrics

## 📘 Project Title
Analysis of K-Nearest Neighbours Algorithm and Distance Metrics

---

## 🎯 Overview

This project explores the K-Nearest Neighbours (KNN) algorithm and investigates how its performance is influenced by two key factors:

- The number of neighbours (K)
- The choice of distance metric

The study demonstrates how these parameters affect model accuracy, decision boundaries, and overall classification behaviour.

---

## 🧠 Objective

The objective of this project is to understand how KNN behaves under different configurations and how parameter choices influence model performance through both theoretical explanation and experimental analysis.

---

## 🧪 Dataset

The Iris dataset is used for this study.

- 150 samples  
- 3 classes  
- 4 numerical features  
- Two features are selected for visualisation  

---

## ⚙️ Experiments Conducted

### 1. Effect of K
- K = 1 → overfitting (complex decision boundary)  
- K = 5 → optimal performance  
- K = 20 → underfitting (oversimplified boundary)  

---

### 2. Accuracy vs K
- Accuracy evaluated for K values from 1 to 20  
- Optimal K identified based on performance trend  

---

### 3. Distance Metrics Comparison
- Euclidean Distance → highest accuracy  
- Manhattan Distance → slightly lower performance  
- Minkowski Distance → similar to Euclidean  

---

## 📊 Results Summary

- Moderate K values provide the best balance between bias and variance  
- Euclidean distance performs well for continuous datasets  
- Model performance is highly dependent on parameter selection  

---

## 📈 Visualisations

The notebook includes:

- Decision boundary plots for different K values  
- Accuracy vs K graph  
- Distance metric comparison results  

---

## 🚀 How to Run

1. Install dependencies:
pip install -r requirements.txt

2. Launch Jupyter Notebook:
jupyter notebook

3. Open the notebook:
K-Nearest Neighbours (KNN) and Distance Metrics.ipynb

---

## 📦 Requirements

- numpy  
- pandas  
- matplotlib  
- scikit-learn  
- jupyter  

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Vippa Indra Sena Reddy  
Student ID: 24151897
