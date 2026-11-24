<p align="center">
  <img src="banner.svg" alt="SDrole — numerical physics, relativistic hydrodynamics and authorized security labs" width="100%">
</p>

<p>
  <a href="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml"><img src="https://github.com/SDrole/blackholesim/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://github.com/SDrole/blackholesim/commits/main"><img src="https://img.shields.io/github/last-commit/SDrole/blackholesim?style=flat-square&label=last%20commit&labelColor=161b22&color=2ea043" alt="Last commit"></a>
</p>

Student working on numerical physics and scientific computing. Offensive-security practice is limited to authorized labs and training environments.

## BlackHoleSim · [Explore the code](https://github.com/SDrole/blackholesim)

C++17/CUDA codebase for Kerr ray tracing and relativistic hydrodynamics.

| Area | Implemented |
| --- | --- |
| Geodesics | Hamiltonian null-ray integration in Kerr spacetime |
| Hydrodynamics | SRHD · HLLE · PLM · SSPRK2 · exact Riemann oracle |
| Compute / I/O | OpenMP · CUDA · HDF5 |

### Validation

<img src="assets/blackholesim-validation.svg" alt="Carter drift: 1.95819e-7. 147 assertions and 145,036 S2 states checked, with zero failures." width="100%">

| Check | Result |
| --- | --- |
| Relative Carter drift | `1.95819e-7` |
| Regression assertions | `147 / 0 failures` |
| S2 validation states | `145,036 / 0 failures` |

### In progress

General-relativistic magnetohydrodynamics (GRMHD).

<!-- latest:start -->
**Latest:** [`blackholesim`](https://github.com/SDrole/blackholesim/commits/main) — active development
<!-- latest:end -->

### Toolchain

<p>
  <img src="https://img.shields.io/badge/C%2B%2B17-f2a444?style=flat-square" alt="C++17">
  <img src="https://img.shields.io/badge/CUDA-70d9a6?style=flat-square" alt="CUDA">
  <img src="https://img.shields.io/badge/OpenMP-77b9ff?style=flat-square" alt="OpenMP">
  <img src="https://img.shields.io/badge/CMake-aab2ff?style=flat-square" alt="CMake">
  <img src="https://img.shields.io/badge/HDF5-f0a8c7?style=flat-square" alt="HDF5">
  <img src="https://img.shields.io/badge/Python-ffdb75?style=flat-square" alt="Python">
</p>

### GitHub activity

<p>
  <img src="https://github-readme-stats.shion.dev/api?username=SDrole&amp;theme=tokyonight&amp;hide_border=false&amp;include_all_commits=false&amp;count_private=false" alt="SDrole public GitHub statistics" width="49%">
  <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=SDrole&amp;theme=tokyonight&amp;hide_border=false&amp;include_all_commits=false&amp;count_private=false&amp;layout=compact" alt="Most used languages in SDrole’s public repositories" width="38%">
</p>

<p>
  <img src="https://streak-stats.demolab.com/?user=SDrole&amp;theme=tokyonight&amp;hide_border=false" alt="SDrole GitHub contribution streak" width="55%">
</p>

<!-- GitHub activity cards generated with GPRM (https://gprm.itsvg.in/) -->
