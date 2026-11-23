<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:050816,40:111B47,75:5425A8,100:7C3AED&text=SDrole&fontColor=FFFFFF&fontSize=62&fontAlignY=38&desc=Physics%20%7C%20Numerical%20Relativity%20%7C%20Scientific%20Computing&descAlignY=58&descSize=17&animation=fadeIn" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=21&duration=2800&pause=800&color=8B5CF6&center=true&vCenter=true&width=760&lines=Exploring+physics+through+computation;Kerr+black+holes+%E2%80%A2+Ray+tracing+%E2%80%A2+GRMHD;Building+first%2C+understanding+deeper+second;A+plausible+result+is+not+necessarily+a+correct+one" />

<br>

![C++](https://img.shields.io/badge/C%2B%2B-17-111827?style=for-the-badge&logo=c%2B%2B&logoColor=6295CB)
![Python](https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=FACC15)
![CUDA](https://img.shields.io/badge/CUDA-111827?style=for-the-badge&logo=nvidia&logoColor=76B900)
![Linux](https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FFFFFF)
![CMake](https://img.shields.io/badge/CMake-111827?style=for-the-badge&logo=cmake&logoColor=5E81AC)

</div>

---

<table>
<tr>
<td width="56%" valign="top">

## `01.` About me

I’m a **physics student** interested in the point where theoretical physics, numerical methods and software engineering meet.

My main interests revolve around:

- 🌌 **Astrophysics**
- 🕳️ **Black-hole physics**
- ⚛️ **Quantum mechanics**
- 🧭 **General relativity**
- 🧮 **Numerical simulation**
- 💻 **Scientific computing**

I like projects where the code is not just expected to *run*, but to reproduce something physically meaningful and survive attempts to prove it wrong.

</td>
<td width="44%" valign="top">

## `02.` Current focus

```text
╭──────────────────────────────╮
│   CURRENT RESEARCH SPACE     │
├──────────────────────────────┤
│  Kerr spacetime              │
│  Null geodesics              │
│  Relativistic hydrodynamics  │
│  GRMHD                       │
│  Radiative transfer          │
│  Numerical validation        │
╰──────────────────────────────╯
```

> **Current objective:** progressively connect black-hole ray tracing, relativistic plasma physics and a self-consistent GRMHD pipeline.

</td>
</tr>
</table>

---

## `03.` Main project

<div align="center">

<a href="https://github.com/SDrole/blackholesim">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=SDrole&repo=blackholesim&theme=midnight-purple&hide_border=true&bg_color=070B17&title_color=A78BFA&icon_color=60A5FA&text_color=CBD5E1" />
</a>

</div>

### 🕳️ `blackholesim`

A physics-first black-hole simulation project evolving toward a complete numerical astrophysics pipeline.

```text
observer
   │
   ▼
camera / tetrad
   │
   ▼
null geodesics in Kerr spacetime
   │
   ├──────────► horizon
   │
   ├──────────► background
   │
   ▼
accretion flow
   │
   ▼
radiative transfer
   │
   ▼
scientific image + diagnostics
```

Current and planned components include:

| Domain | Work |
|---|---|
| Geometry | Kerr & Kerr–Schild spacetime |
| Ray tracing | Hamiltonian null geodesics |
| Validation | Carter constant & independent numerical checks |
| Accretion | Novikov–Thorne disk |
| Hydrodynamics | SRHD finite-volume solver |
| GRHD | Kerr–Schild curved-spacetime evolution |
| GRMHD | Magnetic evolution & constrained transport |
| Radiation | Synchrotron + polarized transfer |
| GPU | CUDA rendering path |

<div align="center">

[![Repository](https://img.shields.io/badge/Explore-blackholesim-7C3AED?style=for-the-badge&logo=github)](https://github.com/SDrole/blackholesim)

</div>

---

## `04.` Scientific interests

<div align="center">

![General Relativity](https://img.shields.io/badge/General_Relativity-312E81?style=flat-square)
![Astrophysics](https://img.shields.io/badge/Astrophysics-4C1D95?style=flat-square)
![Quantum Mechanics](https://img.shields.io/badge/Quantum_Mechanics-581C87?style=flat-square)
![Black Holes](https://img.shields.io/badge/Black_Holes-111827?style=flat-square)
![Numerical Relativity](https://img.shields.io/badge/Numerical_Relativity-1E3A8A?style=flat-square)
![GRMHD](https://img.shields.io/badge/GRMHD-5B21B6?style=flat-square)
![Scientific Computing](https://img.shields.io/badge/Scientific_Computing-0F172A?style=flat-square)

</div>

I’m especially interested in problems where analytical physics eventually reaches the point where computation becomes unavoidable.

```text
Kerr geometry
     ↓
null geodesics
     ↓
relativistic fluids
     ↓
radiation
     ↓
observable images
```

---

## `05.` Tools & technologies

<div align="center">

<img src="https://skillicons.dev/icons?i=cpp,python,cmake,linux,arch,bash,git,github,vscode&theme=dark" />

<br><br>

![CUDA](https://img.shields.io/badge/NVIDIA-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenMP](https://img.shields.io/badge/Parallel-OpenMP-2563EB?style=flat-square)
![HDF5](https://img.shields.io/badge/Data-HDF5-7C3AED?style=flat-square)
![Numerical Methods](https://img.shields.io/badge/Numerical-Methods-4338CA?style=flat-square)
![Physics](https://img.shields.io/badge/Physics-Simulation-6D28D9?style=flat-square)

</div>

---

## `06.` How I approach scientific code

```cpp
while (!result.isConvincing()) {
    derive();
    implement();
    test();
    searchForCounterexamples();
    compareWithIndependentReference();
}
```

Some principles I try to follow:

```text
[01] Physical plausibility ≠ physical correctness
[02] Test invariants, not appearances
[03] Prefer independent oracles
[04] Measure convergence
[05] Instrument numerical fallbacks
[06] Make unsupported states fail loudly
[07] Try to break your own result
```

---

## `07.` Things I’m exploring

<table>
<tr>
<td align="center" width="25%">

### Kerr
Frame dragging  
Photon regions  
ISCO  
Ergosphere

</td>
<td align="center" width="25%">

### Relativity
3+1 formalism  
Kerr–Schild  
Conservative schemes  
Geodesics

</td>
<td align="center" width="25%">

### Plasma
SRHD  
GRHD  
GRMHD  
MRI

</td>
<td align="center" width="25%">

### Radiation
Synchrotron  
Redshift  
Polarization  
Faraday effects

</td>
</tr>
</table>

---

## `08.` GitHub

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=SDrole&show_icons=true&hide_border=true&theme=midnight-purple&bg_color=070B17&title_color=A78BFA&icon_color=60A5FA&text_color=CBD5E1&rank_icon=github" />

<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SDrole&layout=compact&hide_border=true&theme=midnight-purple&bg_color=070B17&title_color=A78BFA&text_color=CBD5E1" />

<br>

<img src="https://streak-stats.demolab.com?user=SDrole&theme=midnight-purple&hide_border=true&background=070B17&ring=8B5CF6&fire=60A5FA&currStreakLabel=A78BFA" />

</div>

---

## `09.` Philosophy

<div align="center">

### “If the only argument for a simulation is that it looks right,  
### the validation is not finished.”

<br>

```text
curiosity
   +
mathematics
   +
physics
   +
computation
   +
skepticism
   =
better models
```

</div>

---

<div align="center">

### Thanks for visiting.

I mainly use GitHub to document what I’m building, what I’m learning,  
and where the physics still has ways to prove me wrong.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-SDrole-181717?style=for-the-badge&logo=github)](https://github.com/SDrole)

<br><br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:7C3AED,45:312E81,100:050816" />

</div>
