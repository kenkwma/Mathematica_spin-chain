# Dynamics spin chain

This folder contains various Mathematica notebooks that I used to study the dynamics of the one-dimensional spin chains

**(1) Nonintegrable_1D_spin-chain-control.nb**

The notebook sets up the tilted field Ising model with a changeable spin-spin interaction at the boundary between the two subsystems A and B. The notebook then diagonalises the Hamiltonian and study the dynamics of the system with an inputted initial state. The notebook also evaluates the bipartite entanglement entropy of each eigenstate, and the evolution of the entanglement entropy. At each time point, the von Neumann entropy of the reduced density matrix for every individual spin is calculated. Different interaction at the boundary can be selected by changing HAB. This allows us to study the thermalisation and entropy between A and B under different conditions. Finally, the numerical results are plotted.

**(2) Heisenberg-model_with_motif.nb**

Setting up and diagonalizing the Heisenberg model with a triangular motif placed at the middle of the spin chain. By selecting the initial state (in the example, singlet and triplet) of the two spins on the boundary, thermalizaing between the left and right subsystems can be controlled. Bipartite entanglement entropy and expected values of energy in both subsystems are calculated. Finally, the numerical results are plotted.


**Related Publications:**

**K. K. W. Ma** and H. J. Changlani, arXiv:2306.07319
