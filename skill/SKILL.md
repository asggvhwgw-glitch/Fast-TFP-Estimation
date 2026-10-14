---
name: fasttfp-validation
version: 0.4.0
purpose: Validate and use fasttfp theory-first production function estimators.
---

# fasttfp skill

This project implements OP, LP, ACF and GNR estimators.

Rules:
- Treat original papers as theory truth.
- Do not use package parity to override theory.
- Do not add hidden ridge regularization in theory mode.
- Do not hide ACF multiple roots.
- Separate compatibility modes from theory estimators.

Validation order:
1. Run internal pytest.
2. Run Monte Carlo.
3. Run Stata/R golden reference when available.
4. Run CUDA benchmark when available.
