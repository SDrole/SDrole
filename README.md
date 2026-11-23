<p align="center">
  <img src="banner.svg" alt="SDrole" width="100%">
</p>

<p align="left">
  <a href="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml"><img src="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/SDrole/blackholesim/commits/main"><img src="https://img.shields.io/github/last-commit/SDrole/blackholesim?style=flat-square&label=LAST%20COMMIT&labelColor=11161d&color=2ea043" alt="Last commit"></a>
  <a href="https://github.com/SDrole/blackholesim"><img src="https://img.shields.io/badge/REPO-PUBLIC-ff8f32?style=flat-square&labelColor=11161d" alt="Repository status"></a>
</p>

I write numerical code for general-relativistic ray tracing and relativistic hydrodynamics, and I do offensive-security work in authorized lab environments.

## [blackholesim](https://github.com/SDrole/blackholesim)

A C++17/CUDA numerical codebase for Kerr ray tracing and relativistic hydrodynamics.

| SYSTEM | CURRENT IMPLEMENTATION |
| --- | --- |
| Spacetime | Kerr ray tracing; Kerr–Schild geometry for the solver track |
| Geodesics | Hamiltonian null-geodesic integration |
| Fluids | SRHD implemented; GRHD / GRMHD on roadmap |
| Numerics | HLLE · PLM · SSPRK2 · exact SRHD Riemann oracle |
| Compute | OpenMP CPU · CUDA GPU |
| I/O | HDF5 |

**VALIDATION**  `Carter Δ = 1.95819e-7` · `S0–S3 = 147 assertions / 0 failures` · `S2 = 145,036 states / 0 failures`

## Security

Offensive-security practice is limited to authorized labs and training environments.

## Stack

`C++17` `CUDA` `OpenMP` `CMake` `HDF5` `Python` `Arch Linux` `Git`
