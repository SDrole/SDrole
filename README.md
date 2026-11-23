# SDrole

Student working on numerical physics and scientific computing.

My main public project is [`blackholesim`](https://github.com/SDrole/blackholesim), a C++17/CUDA codebase for Kerr black-hole ray tracing and relativistic hydrodynamics.

## Current work

- Hamiltonian integration of null geodesics in Kerr spacetime.
- Kerr–Schild geometry and modified Kerr–Schild coordinates.
- Finite-volume special-relativistic hydrodynamics with HLLE, PLM and SSPRK2.
- Primitive/conserved-variable recovery and exact SRHD Riemann validation.
- CPU/OpenMP and CUDA rendering paths.
- HDF5 output for the developing GRHD/GRMHD pipeline.

Validation results and current limitations are documented in the [`blackholesim` README](https://github.com/SDrole/blackholesim#current-validation-status).

**Public project tools:** C++17, CUDA, CMake, OpenMP, HDF5, Python.
