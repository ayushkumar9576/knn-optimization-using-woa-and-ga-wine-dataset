# 🍷 KNN Optimization using WOA and GA on Wine Dataset

## 📌 Project Overview

This project focuses on improving the performance of the K-Nearest Neighbors (KNN) classification algorithm using two optimization techniques: Whale Optimization Algorithm (WOA) and Genetic Algorithm (GA).

The model is applied to the UCI Wine Dataset to classify wines into different categories based on their chemical properties.

---

## 🎯 Objectives

* Implement KNN for wine classification
* Optimize KNN parameters (K value and feature selection)
* Compare optimization techniques:

  * Whale Optimization Algorithm (WOA)
  * Genetic Algorithm (GA)
* Evaluate and analyze performance improvements

---

## 🧠 Technologies Used

* Python
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## 📊 Dataset

* UCI Wine Dataset
* 178 samples
* 13 features
* 3 classes

---

## ⚙️ Methodology

### 1. Baseline Model

* Implement KNN with default parameters
* Measure baseline accuracy

### 2. Whale Optimization Algorithm (WOA)

* Encodes:

  * K value
  * Feature subset
* Uses accuracy as fitness function
* Iteratively improves solutions

### 3. Genetic Algorithm (GA)

* Uses:

  * Selection
  * Crossover
  * Mutation
* Evolves solutions over generations

---

## 📈 Results

The project compares:

* Baseline KNN Accuracy
* WOA Optimized Accuracy
* GA Optimized Accuracy

The best-performing optimization method is identified based on accuracy.

---

## 📊 Visualizations

* Accuracy vs iterations (WOA)
* Accuracy vs generations (GA)
* Comparison bar chart

---

## 📁 Project Structure

```
knn-optimization-using-woa-and-ga-wine-dataset/
│
├── notebook.ipynb
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```
git clone https://github.com/ayushkumar9576/knn-optimization-using-woa-and-ga-wine-dataset.git
```

2. Navigate to the project folder:

```
cd knn-optimization-using-woa-and-ga-wine-dataset
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run Jupyter Notebook:

```
jupyter notebook
```

---

## 🎯 Key Features

* Comparison of two optimization algorithms
* Feature selection + parameter tuning
* Clear visualization of results
* Modular and readable code

---

## 📌 Conclusion

Optimization techniques like WOA and GA significantly improve the performance of KNN by selecting optimal parameters and relevant features.

---

## 👨‍💻 Author

Ayush Kumar

---

## 📄 License

This project is for academic purposes.
