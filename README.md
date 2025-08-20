# 📘 Math for Machine Learning – Weekly Projects

This repository is my **learning journey into the mathematics behind machine learning**.  
Each week I take a math concept (linear algebra, calculus, probability, optimization, etc.),  
implement a small project in Python, and document how the math shows up in machine learning.

The goal: **see the math in action** by coding it from scratch, before relying on high-level libraries.

---

## ✅ Week 1: From Vectors to Predictions – 2D Linear Regression
- **Concepts learned:** vectors, dot product, matrix multiplication, projections  
- **Formula used:**  
  \[
  w = (X^T X)^{-1} X^T y
  \]  
- **Project:** Predict house prices with 2 features (size, rooms)  
- **Tools:** NumPy only (no sklearn/statsmodels)  
- **Evaluation metric:** Mean Squared Error (MSE)  

👉 [Script here](https://github.com/mishra123/maths-to-ml/blob/main/linear_regression.ipynb)  

---

## 📅 Planned Weeks
- **Week 2:** Gradient Descent (calculus in action)  
- **Week 3:** Probability & Bayes Theorem (Naïve Bayes Classifier)  
- **Week 4:** Eigenvalues & SVD (PCA from scratch)  
- **Week 5:** Regularization (L1/L2)  
- **Week 6:** Optimization techniques (SGD, Adam)  

---

## 🛠️ How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/math-for-ml.git
   cd math-for-ml
   pip install -r requirements.txt
   jupyter notebook
