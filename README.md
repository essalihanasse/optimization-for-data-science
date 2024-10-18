# Optimization for Data Science - Lab Solutions

This repository contains my solutions for the lab assignments of the **Optimization for Data Science** course.

## Course Labs Overview

The course includes 4 graded lab assignments. Each lab focuses on implementing and experimenting with different optimization algorithms. The solutions are implemented in Jupyter Notebooks, and the grading constitutes 30% of the final grade.

### Lab List

1. **Lab 1: First Order Methods (ISTA/FISTA)**  
   - Focus: Gradient Descent, Proximal Gradient Descent.
   - Implementation of ISTA and FISTA algorithms for solving Lasso problems.
   
2. **Lab 2: Variance Reduction Techniques**  
   - Focus: Stochastic Gradient Descent (SGD), Variance Reduction methods.
   - Implementation and comparison of SGD, SVRG, and SAGA on a ridge regression problem.

3. **Lab 3: Coordinate Descent for Sparse Models**  
   - Focus: Coordinate Descent algorithms.
   - Application of coordinate descent on logistic regression and ridge regression.

4. **Lab 4: Second Order Methods**  
   - Focus: Newton's Method, Quasi-Newton (BFGS, L-BFGS).
   - Implementation of second-order optimization techniques for nonlinear optimization problems.

## How to Use

Each lab folder contains:
- `LabX.ipynb`: Jupyter Notebook with the problem statements, implementation, and solution.
- `data/`: Any datasets used for the lab (if applicable).

To run the notebooks, ensure you have the following dependencies installed:
- `numpy`
- `scipy`
- `matplotlib`
- `sklearn`
- `jupyter`

You can start a Jupyter Notebook server using:
```bash
jupyter notebook
