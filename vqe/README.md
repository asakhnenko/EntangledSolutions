## Variation Quantum Eigensolver

The initial goal for VQE was to determine ground states of Hamiltonians (lowest eigenvalues), but it usage can be extended to minimization of objective functions.

One possible application of VQE is shown in `clustering_vqe.ipynb`, which uses Max-Cut Problem formulation to describe objective function for clustering task. The objective function is then mapped to Ising Hamiltonian that is fed to VQE algorithm.
