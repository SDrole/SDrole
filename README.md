<p align="center">
  <img src="banner.svg" alt="SDrole" width="100%">
</p>

I write numerical code for general-relativistic ray tracing and relativistic hydrodynamics, and I do offensive security work in authorized lab environments.

## [blackholesim](https://github.com/SDrole/blackholesim)

A numerical simulation of black holes and relativistic fluids, with validation tied to explicit numerical checks.

| Component | Implementation |
| --- | --- |
| Spacetime | Kerr ray tracing; Kerr–Schild geometry for the solver track |
| Ray tracing | Null geodesics integrated in Hamiltonian form |
| Fluids | SRHD implemented; GRHD and GRMHD on the roadmap |
| Imaging | Relativistic accretion-flow rendering |
| Parallelism | CUDA (GPU), OpenMP (CPU) |
| I/O | HDF5 |

Rays follow Hamilton's equations with the null constraint

$$H = \\tfrac{1}{2}\, g^{\\mu\\nu}(x)\, p_\\mu p_\\nu = 0, \\qquad \\dot{x}^\\mu = \\frac{\\partial H}{\\partial p_\\mu}, \\qquad \\dot{p}_\\mu = -\\frac{\\partial H}{\\partial x^\\mu}$$

**Verification:** Carter drift ≈ **1.95819 × 10⁻⁷**; S0–S3 baseline: **147 assertions, 0 failures**; S2 recovery sweep: **145,036 sampled states, 0 failures**.

## Security

Offensive-security practice is limited to authorized labs and training environments.

## Stack

C++17 · CUDA · OpenMP · CMake · HDF5 · Python · Linux (Arch) · Git
