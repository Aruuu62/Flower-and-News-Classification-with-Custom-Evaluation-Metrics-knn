# Flower-and-News-Classification-with-Custom-Evaluation-Metrics-knn
# KNN from Scratch: Iris and News Classification

This repository contains a custom implementation of the **K-Nearest Neighbors (KNN)** algorithm using Python. It also includes manual implementation of evaluation metrics and comparison with scikit-learn's KNN classifier.

> 💡 **Lab Report 02 for CSE312 (Machine Learning)**

---

## 📚 Objective

- Implement KNN algorithm from scratch without using `sklearn`'s `KNeighborsClassifier`.
- Write custom functions for evaluation metrics: **accuracy, confusion matrix, precision, recall, and F1-score**.
- Apply the algorithm to:
  - The **Iris Flower** dataset.
  - A small **News text classification** dataset.
- Compare the performance with **scikit-learn's KNN** implementation.

---

## 🧠 Topics Covered

- KNN Theory & Implementation
- Evaluation Metric Functions from Scratch
- Text Vectorization (Bag-of-Words)
- Classification on Numerical and Text Data
- Train-Test Splitting
- Comparison with Scikit-learn KNN

---

## 📂 Files Included

| File Name                              | Description |
|----------------------------------------|-------------|
| `KNN_From_Scratch_LabReport02.ipynb`   | Main Jupyter Notebook with full implementation and results |
| `README.md`                            | This file |
| *(Optional)* `news_dataset.csv`        | News dataset (if you provide your own custom dataset) |

---

## 📝 Requirements

Install the following Python libraries:

```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## 🚀 How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/KNN-From-Scratch-LabReport02.git
cd KNN-From-Scratch-LabReport02
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook KNN_From_Scratch_LabReport02.ipynb
```

3. Run all cells to see results and comparison with scikit-learn.

---

## 📊 Results Summary

| Dataset       | Accuracy (Custom KNN) | Accuracy (Sklearn KNN) |
|---------------|------------------------|--------------------------|
| Iris          | ✅ ~93–100%             | ✅ ~93–100%              |
| News (sample) | ✅ ~66–100%             | ✅ ~66–100%              |

*(Exact scores depend on `k` and split ratio used)*

---

## 📌 Notes

- The News dataset used is a small manually created sample.
- Text data is vectorized using simple Bag-of-Words.
- You can replace it with your own dataset for better evaluation.

---

## 🧑‍💻 Author

**M. Tahsinur Rahman**  
Lab Report for CSE312 Machine Learning

---

## 📜 License

This project is for academic use only. Any unauthorized copying will result in mark deduction or academic penalties.

---

## 📎 Citation

If you're referencing this work, cite it as:

> Rahman, M. Tahsinur. *KNN from Scratch: Flower and News Classification with Custom Evaluation Metrics.* Lab Report 02, CSE312, 2025.
