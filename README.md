<p align="center">
  <img src="banner.svg" alt="SDrole — numerical physics, relativistic hydrodynamics and authorized security labs" width="100%">
</p>

**I build relativistic simulations and write the tests that tell me when to trust them.**

I work on numerical physics in C++, from tracing photons through curved spacetime to testing how a solver recovers the state of a relativistic fluid. I practice offensive security in authorized labs and training environments.

## [BlackHoleSim](https://github.com/SDrole/blackholesim)

[![CI](https://github.com/SDrole/blackholesim/actions/workflows/ci.yml/badge.svg)](https://github.com/SDrole/blackholesim/actions/workflows/ci.yml)
[![Last commit](https://img.shields.io/github/last-commit/SDrole/blackholesim?style=flat-square&label=last%20commit&labelColor=161b22&color=2ea043)](https://github.com/SDrole/blackholesim/commits/main)

<img src="assets/photon-trajectories.svg" alt="Schematic of three colored light paths near a black hole and its accretion disk" width="100%">

*Photon trajectories and accretion disk schematic.*

### 🟠 Ray tracing in Kerr spacetime

I integrate Hamiltonian null geodesics and model a Novikov–Thorne accretion disk. The renderer exports redshift, ray classification and Carter drift alongside the image. [Read the physics notes](https://github.com/SDrole/blackholesim#physics)

### 🟢 Relativistic hydrodynamics

I develop a special-relativistic solver alongside the renderer. The test suite checks primitive-variable recovery across sampled fluid states and compares the numerical solution against an independent exact SRHD Riemann solver. [Explore the solver](https://github.com/SDrole/blackholesim/tree/main/grmhd)

| Check | Documented result |
| --- | --- |
| Maximum relative Carter drift in the ray-tracing regression | `1.96 × 10⁻⁷` against a `10⁻⁶` threshold |
| Regression suite | `147` assertions, zero failures |
| S2 primitive/conserved recovery | `145,036` sampled states, zero failures |

### 🟣 In progress · GRMHD

The next goal is to use snapshots from a general-relativistic magnetohydrodynamics solver as inputs to the renderer. [Read the scientific roadmap](https://github.com/SDrole/blackholesim/blob/main/docs/ROADMAP.md)

<!-- latest:start -->
**Latest:** [`blackholesim`](https://github.com/SDrole/blackholesim/commits/main) — active development
<!-- latest:end -->

### Toolchain

![C++17](https://img.shields.io/badge/C%2B%2B17-ffbc70?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-83f0c7?style=flat-square)
![OpenMP](https://img.shields.io/badge/OpenMP-83f0c7?style=flat-square)
![CMake](https://img.shields.io/badge/CMake-b99aff?style=flat-square)
![HDF5](https://img.shields.io/badge/HDF5-b99aff?style=flat-square)
![Python](https://img.shields.io/badge/Python-ffbc70?style=flat-square)

<img src="https://github-readme-stats.shion.dev/api/top-langs/?username=SDrole&amp;theme=tokyonight&amp;hide_border=false&amp;include_all_commits=false&amp;count_private=false&amp;layout=compact" alt="Most used languages in SDrole’s public repositories">

<!-- Language card generated with GPRM (https://gprm.itsvg.in/) -->
