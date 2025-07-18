# Solving the HJB Equation in Merton's Portfolio Problem using Deep Operator Networks

This repository contains the code and report for my undergraduate thesis, in which I study **Stochastic Optimal Control Theory** and apply it to the classical **Merton's Portfolio Optimization Problem**. The core idea is to model the problem using **Hamilton-Jacobi-Bellman (HJB) Equation**, and solve it numerically using deep learning techniques.

## 📌 Abstract

In this thesis, I introduce **Stochastic Optimal Control Theory**, an optimization framework grounded in **Probability Theory** and **Stochastic Differential Equations (SDEs)**. I focus on the Merton's portfolio optimization problem, a foundational problem in continuous-time finance. The problem is first reformulated into a **Partial Differential Equation (PDE)** — the **HJB Equation**.

To solve this PDE numerically, I employ the **Deep Operator Network (DeepONet)**, a type of neural operator that approximates the solution operator rather than the solution itself. The DeepONet is trained via **gradient descent over a loss function**, which measures how well the learned operator satisfies the HJB equation.

## 🧠 Methods

- Reformulation of Merton's control problem into the HJB Equation.
- Construction of DeepONet as an operator approximator.
- Training using stochastic sampling and optimization in PyTorch.
- Evaluation through visual inspection of solution quality.

## Tools & Libraries

- Python  
- NumPy  
- SciPy  
- PyTorch  
- DeepXDE (Deep Learning Library for Solving Differential Equations)

## 🗂️ Folder Structure

- `main_notebook.ipynb`: all implementation steps including problem setup, DeepONet training, and result visualization
- `report.pdf`: full thesis write-up with theory, methods, and results

## Status

Project completed in April 2025 as part of my Bachelor's thesis at New York University.

---

