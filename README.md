# 📉 Gradient Descent Comparison and Optimizer Visualizations

This repository provides a comprehensive exploration of **gradient descent optimization algorithms**, implemented **from scratch in Python** and demonstrated through Jupyter Notebooks.  
The project not only compares different optimizers but also includes **visual interpretations of weight updates, cost surfaces, and convergence trajectories**.

---

## 📖 Overview

**Gradient Descent** is the backbone of many machine learning algorithms.  
This repo builds intuition by:

- Implementing gradient descent variants step by step.  
- Comparing **Batch, Stochastic, and Mini-Batch Gradient Descent**.  
- Extending SGD with advanced optimizers: **Momentum, Adagrad, Adadelta, Adam**.  
- Visualizing how weights (`w0`, `w1`) update across epochs.  
- Demonstrating noisy data scenarios (5-point dataset).  
- Plotting **3D paraboloid cost surfaces** and **trajectories of weight updates**.  

---

## 📂 Notebooks Overview

- **`Batch_SGD_MiniBatch.ipynb`**  
  Implements and compares **Batch Gradient Descent, Stochastic GD, and Mini-Batch GD** on a regression dataset.  

- **`SGD_with_momentum.ipynb`**  
  Adds **momentum** to SGD using exponentially weighted averages to reduce oscillations and speed up convergence.  

- **`SGD_Adagrad.ipynb`**  
  Demonstrates **Adagrad**, which adapts learning rates per parameter, beneficial for sparse features.  

- **`SGD_Adadelta_&_Adam.ipynb`**  
  Introduces **Adadelta** (improving on Adagrad’s decaying learning rate) and **Adam**, which combines momentum and adaptive learning rates.  

- **`SGD_with_5_points.ipynb`**  
  Uses a **synthetic 5-point dataset with noise** to show how gradient descent and SGD handle irregular data, with 2D and 3D paraboloid plots.  

- **`SVD_trajectory_of_weights.ipynb`**  
  Visualizes the **trajectory of weights (`w0`, `w1`) during optimization** on 3D paraboloid cost surfaces, highlighting **update direction vs. gradient direction**.  

---

## ⚙️ Requirements

Install dependencies before running the notebooks:

```bash
pip install numpy matplotlib
