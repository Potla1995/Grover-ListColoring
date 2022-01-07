# Grover-ListColoring
Companion code to the paper [A Grover search-based algorithm for the list coloring problem"](https://arxiv.org/abs/2108.09061) submitted to the [IEEE Transactions of Quantum Engineering](https://tqe.ieee.org/) journal. Contains implementation and test code for the algorithm output for 3-coloring $K_3$.

# Code structure
The main notebook for comparison with the previous work of [Saha et. al.](https://arxiv.org/pdf/2009.06073.pdf) is [List Coloring Problem.ipynb](./List Coloring Problem.ipynb).
The CSV files in the main directory contain outputs returned by the Amazon Statevector Simulator and the IonQ Physical Device.

# Dependencies
Our code requires the following Python packages (can be installed using `pip`): `numpy matplotlib blueqat blueqat-cloud`.
