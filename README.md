# Proximal Random Reshuffling under Local Lipschitz Continuity — Reproducibility Code

This repository provides minimal code (Jupyter notebooks) to reproduce the numerical examples
used in the manuscript **“Proximal random reshuffling under local Lipschitz continuity”** and
in the authors’ response to reviewers.

The notebooks are intended to be **self-contained**: open them and run all cells.

---

## Contents

| File | What it reproduces | Notes |
|---|---|---|
| `Figure1.ipynb` | Gradient descent behavior for illustrative 2D examples (including the *lower-bounded*, real-analytic, definable example used in the response). | Includes plots showing non-uniform boundedness/cycling behavior for small constant step sizes. |
| `Global Minima.ipynb` | Two-parameter one-hidden-layer sigmoid example: GD approaches the global infimum while parameter norms diverge. | Used to illustrate that “unbounded iterates” need not imply a meaningless optimization trajectory. |
| `Matrix Completion.ipynb` | Robust/asymmetric matrix completion toy instance, including multi-initialization sweeps. | Demonstrates **initialization sensitivity**: some initializations yield bounded trajectories, others become unbounded. |

---

## Setup Instructions  

To reproduce results locally:  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/WilliamPixell/Proximal-random-reshuffling-under-local-Lipschitz-continuity.git  
   cd Proximal-random-reshuffling-under-local-Lipschitz-continuity

2. **Environment**:  
   This project is tested with following specific library versions:
   - **jax==0.8.1**
   - **matplotlib==3.10.6**
  

