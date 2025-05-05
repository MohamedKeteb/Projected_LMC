# :game_die: On Constrained Sampling Project

**Authors**: Yassine Boukhateb, Mohamed Keteb, and Imrane Zaakour

---

## 📝 Project Overview

This GitHub repository contains a `presentation_MAPLA` on the **Constrained Sampling Problem**. The project introduces two key algorithms:

1. **Projected Langevin Monte Carlo (PLMC)**  
    A method for solving constrained sampling problems using Langevin dynamics, consisting of performing a Langevin step followed by a projection onto the support of the target, which is a convex set.   
2. **Metropolis-Adjusted Preconditioned Langevin Algorithm (MAPLA)**  
      An advanced approach that enhances the efficiency of Langevin dynamics through preconditioning and Metropolis adjustments. Specifically, we precondition the Langevin algorithm by introducing a metric that accounts for the geometry of the support, and we apply a Metropolis filter to correct the Markov chain produced by the resulting dynamics.

The experiments related to **PLMC** are available in the notebook `PLMC`.

---

## 📚 References

- Vishwak Srinivasan, Andre Wibisono, Ashia Wilson, ["High-accuracy sampling from constrained spaces with the Metropolis-adjusted Preconditioned Langevin Algorithm"](https://arxiv.org/abs/1507.02564), arXiv:1507.02564
- Sébastien Bubeck, Ronen Eldan, Joseph Lehec["Sampling from a log-concave distribution with Projected Langevin Monte Carlo"](https://arxiv.org/abs/2412.18701), arXiv:2412.18701
  
---

## 🚀 Installation

To get started, install the required dependencies by running the following command:

```bash
pip install -r requirements.txt
```


