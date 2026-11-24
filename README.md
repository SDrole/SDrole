<p align="center">
  <img src="banner.svg" alt="SDrole" width="100%">
</p>

<p>
  <a href="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml"><img src="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/SDrole/blackholesim/commits/main"><img src="https://img.shields.io/github/last-commit/SDrole/blackholesim?style=flat-square&label=last%20commit&labelColor=161b22&color=2ea043" alt="Last commit"></a>
</p>

Student working on numerical physics and scientific computing. Offensive-security practice is limited to authorized labs and training environments.

## [blackholesim](https://github.com/SDrole/blackholesim)

C++17/CUDA codebase for Kerr ray tracing and relativistic hydrodynamics.

| Area | Implemented |
| --- | --- |
| Geodesics | Hamiltonian null-ray integration in Kerr spacetime |
| Hydrodynamics | SRHD · HLLE · PLM · SSPRK2 · exact Riemann oracle |
| Compute / I/O | OpenMP · CUDA · HDF5 |

**Validation:** `Carter Δ = 1.95819e-7` · `147 assertions / 0 failures` · `145,036 S2 states / 0 failures`

<!-- latest:start -->
**Latest:** [`blackholesim`](https://github.com/SDrole/blackholesim/commits/main) — active development
<!-- latest:end -->

`C++17` · `CUDA` · `OpenMP` · `CMake` · `HDF5` · `Python`
