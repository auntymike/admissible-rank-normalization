# On Admissible Rank-Based Input Normalization

This repository provides the reference implementation and experimental notebook for the paper:

**On Admissible Rank-Based Input Normalization**

The notebook reproduces all experiments in **Section 6 (Empirical Validation)** and evaluates admissible rank-based input normalization operators under the structural conditions (C1)–(C3), with comparisons to continuous sorting–based baselines (SoftSort, Sinkhorn, QNorm).

Only synthetic or publicly available datasets are used, and all results are fully reproducible.

---

## Reproducible Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1sGBwlkaqA-ezl65ZKnx8p_zWSYdM1onM?usp=sharing)

This notebook reproduces all experiments in Section 6 (Empirical Validation), including:

- **6.1 Operator Stability**
  - monotone invariance (C1)
  - batch independence (C2)
  - Lipschitz / gradient stability (C3)

- **6.2 Model-Level Robustness**
  - distribution-shift stability
  - ranking consistency (NDCG / Spearman)

- **6.3 Real-World Consistency**
  - UCI Energy Efficiency
  - California Housing
  - NYC Taxi Trip Duration

---

## Environment

Python, PyTorch, NumPy / Pandas / SciPy, scikit-learn, matplotlib

Deterministic options and fixed seeds are enabled to ensure reproducibility.
