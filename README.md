# Hodge Laplacian on 1-forms of homogeneous 3-spheres

This repository contains the *Electronic Supplementary Material* for the paper:

> **Hodge Laplacian on 1-forms of homogeneous 3-spheres**  
> *Jonas Henkel and Emilio Lauret*

It provides the source code for the symbolic derivation of the operator and numerical verifications of the *first eigenvalue conjecture*.

## Content

The Jupyter Notebook `Spectral_Analysis_SU2.ipynb` covers the following topics:

1.  **Implementation:** Symbolic construction of the Hodge-Laplacian $\Delta = \nabla^*\nabla + 2q(R)$ using `SageMath`.
2.  **Explicit Matrices:** Visualization of the operator matrices for low representation weights $k$.
3.  **Symbolic Spectrum:** Exact calculation of eigenvalues for $k=0, 1, 2, 3$.
4.  **Monte Carlo Stress Test:** Numerical verification of the conjecture on 1000 random metrics.
5.  **Berger Spheres:** Visualization of the full spectrum and the splitting behavior for canonical variations.

**Supplementary Data Files:**
Due to the complexity of the symbolic expressions for higher $k$, the notebook exports the full results to the following text files:
*   `explicit_matrices.txt`: Contains the full matrix representations for $k=0$ to $5$.
*   `exact_eigenvalues.txt`: Contains the full symbolic eigenvalues for $k=0$ to $5$.

## Usage

To run the code, you need a working installation of *SageMath* (tested with version 10.5).

1.  Clone the repository:
    ```bash
    git clone https://github.com/jmhenkel/Code.git
    ```
2.  Open the notebook `Spectral_Analysis_SU2.ipynb` in Jupyter or VS Code.
3.  Select the SageMath kernel and execute the cells.
