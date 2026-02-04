# Proximal Random Reshuffling under Local Lipschitz Continuity 

This repository provides Jupyter notebooks to reproduce the numerical examples used in the manuscript **“Proximal random reshuffling under local Lipschitz continuity”**. 

---

## Contents

| File | What it reproduces |
|---|---|
| `Figure1.ipynb` | A lower-bounded, real-analytic, definable example illustrating bounded iterates can be divergent no matter how small constant step sizes are used. |
| `Global Minima.ipynb` | A two-parameter one-hidden-layer sigmoid example where GD approaches the global infimum while the parameter norm diverges. |
| `Matrix Completion.ipynb` | A robust asymmetric matrix completion instance illustrating that under square-summable diminishing step sizes, some random initializations yield bounded trajectories while others become unbounded. |

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
  

