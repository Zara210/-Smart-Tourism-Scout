# Meta-heuristics & Evolutionary Algorithms in C

![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Algorithms](https://img.shields.io/badge/Algorithms-Meta--Heuristics-orange?style=for-the-badge)
![Excel](https://img.shields.io/badge/Data-Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

This system implements a comprehensive suite of optimization algorithms in C, designed to solve complex combinatorial problems through local search techniques, genetic evolution, and hybrid systems.

---

## Implemented Algorithms

The optimization engine is built upon three fundamental pillars:

* **Local Search:**
    * Algorithms: **Hill Climbing** and **Simulated Annealing**.
    * Neighborhood Operators: **Swap** and **Bitflip**.
* **Evolutionary Algorithms (GA):**
    * **Selection:** Tournament and Roulette Wheel.
    * **Crossover:** 1-point, 2-point, and Uniform.
    * **Mutation:** Stochastic bit/element alteration.
* **Hybrid Systems (Memetic Algorithms):**
    * Integrates global exploration (Genetic Algorithms) with local exploitation (Hill Climbing/Simulated Annealing) for fine-tuned convergence.

---

## Repository Structure

| File / Directory | Description |
| :--- | :--- |
| `main.c` | Interactive CLI entry point for real-time parameter configuration. |
| `algoritmo.c` | Core implementation of meta-heuristics and search logic. |
| `funcao.c` | Objective function logic, penalty handling, and repair mechanisms. |
| `/resultados` | Python automation scripts for batch testing and statistical analysis. |
| `*.xlsx / *.csv` | Detailed datasets containing performance metrics for each algorithm. |

---

## Performance & Data Analysis

The project includes a rigorous experimental study to validate algorithmic efficiency, supported by automated data processing:

* **Mass Testing:** Python-based automation to calculate **MBF (Mean Best Fitness)** across multiple runs.
* **Constraint Handling:** Comparative study between **Penalty Functions** vs. **Repair Heuristics** (Random & Heuristic Repair).
* **Data Visualization:** Comprehensive Excel/CSV reports that track convergence, percentage of invalid solutions, and performance comparisons across different problem sizes.
* **Convergence Research:** Analysis of how hybridization and selection methods (Tournament vs. Roulette) impact the quality of the global optimum.

---
**Developed by:** Miguel Zara and Guilherme Eça
