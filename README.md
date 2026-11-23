# SDrole

**Student — numerical physics and scientific computing**

[`blackholesim`](https://github.com/SDrole/blackholesim) is my main public project: a C++17/CUDA codebase for Kerr black-hole ray tracing and relativistic hydrodynamics.

---

## Current work

| Area | Implementation |
| --- | --- |
| Kerr spacetime | Hamiltonian integration of null geodesics |
| Relativistic geometry | Kerr–Schild and modified Kerr–Schild coordinates |
| SRHD | Finite-volume solver with HLLE, PLM and SSPRK2 |
| Validation | Primitive recovery and exact SRHD Riemann comparisons |
| Compute | CPU/OpenMP and CUDA rendering paths |
| Data | HDF5 output for the developing GRHD/GRMHD pipeline |

## Validation

Numerical results, test scope and current limitations are documented in the [`blackholesim` validation section](https://github.com/SDrole/blackholesim#current-validation-status).

**Stack:** C++17 · CUDA · CMake · OpenMP · HDF5 · Python
