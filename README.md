# POQComputing
**POQComputing** is a project to solve the mean-variance portfolio optimization problem for n assets using quantum computing
## What is Mean-Variance Optimization?
The mean-variance analysis is a tool that is used by investors to spread the risk in their portfolios.in it, the investor measures an asset's risk, expressed as the variance, then compares that with the asset's likely return.
The main goal of mean-variance optimization is to maximize an investment’s reward based on its risk.

Once you calculate the variance and the expected reward, the goal is to invest rationally based on your appetite for risk. All things being equal, when two securities have the same expected return you should select the one with the lower variance. Likewise, when two assets have the same variance, you should select the one with the higher expected return.

## How we can solve this problem using quantum computing ?
firstly we can map this problem into a Hamiltonian whose ground corresponds to the optimal solution then we use VQE and QAOA to find an optimal solution .

### What is VQE ?
The Variational Quantum Eigensolver (VQE) is a hybrid quantum-classical algorithm. It aims to find an upper bound of the lowest eigenvalue of a given Hamiltonian.
The VQE is an algorithm running partly on a classical computer and partly on a quantum computer. It lets you find the combination of values that solve a given optimization problem — approximately.

### What is QAOA ?
The Quantum Approximate Optimization Algorithm (QAOA) is a widely-studied method for solving combinatorial optimization problems on NISQ devices. The applications of QAOA are broad and far-reaching, and the performance of the algorithm is of great interest to the quantum computing research community.

## Assumptions 
- All assets have the same price (normalized to 1).
- The full budget  has to be spent.

