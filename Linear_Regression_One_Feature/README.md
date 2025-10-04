#  Linear Regression from Scratch (One Feature)

This project demonstrates a **manual implementation of Linear Regression** using **Gradient Descent** — without relying on machine learning libraries like `sklearn`.  
It’s written purely in **Python + NumPy** and visualized with **Matplotlib**.

---

##  Overview

The notebook covers:
1. Importing and visualizing data  
2. Implementing:
   - Cost Function  
   - Gradient Computation  
   - Gradient Descent Algorithm  
3. Plotting convergence of cost  
4. Visualizing the fitted regression line  

---

##  Dataset

A small synthetic dataset of house sizes and corresponding prices:

| Size (x) | Price (y) |
|-----------|------------|
| 1.0 | 300 |
| 3.0 | 500 |
| 4.5 | 900 |
| 8.0 | 1200 |
| 9.2 | 1800 |
| 2.3 | 450 |

---

##  Implementation Details

- **Language:** Python  
- **Libraries:** NumPy, Matplotlib  
- **Algorithm:** Batch Gradient Descent  
- **Objective:** Minimize Mean Squared Error (MSE)  

### Key Functions
- `compute_cost(w, b, x, y)` → Calculates cost  
- `compute_gradient(x, y, w, b)` → Computes partial derivatives  
- `perform_gradient_descent(w, b, alpha, iterations, x, y)` → Runs gradient descent  
- `compute_prediction(w, b, x)` → Predicts output values  

---

##  Results

- Gradient descent successfully converges to the optimal parameters.  
- The fitted line passes accurately through the training data points.  
- Cost decreases smoothly over iterations.

Example output plots:
- 📉 *Iterations vs Cost*  
- 📈 *Regression Line vs Actual Data Points*

---

##  Learnings

- Understood how Linear Regression works mathematically.  
- Implemented gradient descent manually.  
- Visualized model convergence and predictions. 