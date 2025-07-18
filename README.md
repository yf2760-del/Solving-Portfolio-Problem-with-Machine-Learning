# Solving the HJB Equation in Merton's Portfolio Problem using Deep Operator Networks

This project is my undergraduate thesis, in which I applied **machine learning** methods to solve a classical problem in **stochastic optimal control theory**.

## Project Overview

In this thesis, I studied **stochastic optimal control theory**, a branch of optimization built upon **probability theory** and **stochastic differential equations (SDEs)**. 

I focused on the **Merton portfolio optimization problem**, a foundational model in continuous-time finance, and formulated it as a **Hamilton–Jacobi–Bellman (HJB) equation**, which is a nonlinear partial differential equation (PDE) characterizing the optimal value function of the control problem.

In the numerical implementation, I employed **deep learning** techniques to solve the HJB equation. Specifically, I used a neural network architecture called the **Deep Operator Network (DeepONet)** to approximate the operator mapping the input function to the solution of the PDE. The model was trained by minimizing a loss function based on the PDE residuals and boundary conditions.

## Tools & Libraries

- Python  
- NumPy  
- SciPy  
- PyTorch  
- DeepXDE (Deep Learning Library for Solving Differential Equations)

## Folder Structure

- `data/`: input functions and sample configurations  
- `model/`: DeepONet architecture and training setup  
- `results/`: learned operators and evaluation metrics  
- `report.pdf`: full thesis write-up with theory, methods, and results  

## Status

Project completed in June 2025 as part of my Bachelor's thesis at [Your University Name].

---

