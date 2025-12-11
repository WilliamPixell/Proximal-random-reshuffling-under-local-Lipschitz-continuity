# Proximal Random Reshuffling under Local Lipschitz Continuity  

This repository contains code to support the findings of our manuscript titled *"[Manuscript Title]"*. It includes Jupyter Notebooks for experimental validation, figure generation, and case studies related to proximal random reshuffling under local Lipschitz continuity assumptions.  


## Repository Structure  

| File Name               | Purpose                                                                 | Key Outputs/Experiments                                                                 |  
|-------------------------|-------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|  
| `Figure1.ipynb`         | Generates main figures for the manuscript (e.g., convergence plots, algorithm comparisons). | - Convergence curves under varying Lipschitz constants<br>- Visualizations for Section 3.2 (manuscript) |  
| `Global Minima.ipynb`   | Analyzes properties of global minima under the proposed algorithm.       | - Stability metrics of minima<br>- Comparison with baseline methods (Table 1 in manuscript) |  
| `Matrix Completion.ipynb` | Implements matrix completion as a case study application.               | - Reconstruction error results<br>- Runtime performance benchmarks (Figure 4 in manuscript) |  
| `.gitignore`            | Excludes generated files (e.g., `.pdf`, `.png`) to keep the repo focused on source code. | - Ensures only executable code is tracked by Git. |  


## Setup Instructions  

To reproduce results locally:  

1. **Clone the repository**:  
   ```bash  
   git clone https://github.com/WilliamPixell/Proximal-random-reshuffling-under-local-Lipschitz-continuity.git  
   cd Proximal-random-reshuffling-under-local-Lipschitz-continuity  
