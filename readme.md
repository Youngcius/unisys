# Two-Qubit Gate Decomposition & Reck Decomposition

>Date: 2011-11-27
>
>Author: Zhaohui Yang

## Necessary dependencies
- numpy, scipy: for linear algebra  calculation
- matplotlib, qiskit: for `circuit` visualization

## Main functions

- `decompose_gate`: any two-qubit gate decomposition (a high-level interface)
- `cnot_decomp`: decompose an arbitrary two-qubit gate into several single-qubit gates and at most three CNOT gates (based on KAK decomposition)
- `abc_decomp`: for controlled-U gate decomposition
- `tensor_product_decomp`: when a two-qubit gate is in form of tensor product of two single-qubit gate
- `reck_decomp`: decompose an arbitrary U(N) operator into $\frac{N(N-1)}{2}$ U(2) operators *(currently only supports real unitary matrix)*

## How to use

See the `examples.ipynb` file.

## Reference

[1] Vidal, G. and C. M. Dawson (2004). "Universal quantum circuit for two-qubit transformations with three controlled-NOT gates." Physical Review A 69(1).

[2] Tucci, R. (2005). "An Introduction to Cartan's KAK Decomposition for QC Programmers."

[3] Kraus, B. and J. I. Cirac (2001). "Optimal creation of entanglement using a two-qubit gate." Physical Review A 63(6).

[4] Liu, F.-j. (2012). New Kronecker product decompositions and its applications.

[5] Vatan, F. and C. Williams (2004). "Optimal quantum circuits for general two-qubit gates." Physical Review A 69(3).

[6] Berman, A. and R. J. Plemmons (1994). Nonnegative matrices in the mathematical sciences, SIAM.
