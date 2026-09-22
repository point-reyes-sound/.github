<div align="center">

# Point Reyes Sound, Inc.

### Continuous phase-space kinetics for strongly correlated electrons.

[![Preprint](https://img.shields.io/badge/arXiv-2608.14979-B31B1B.svg?style=flat-square)](https://arxiv.org/abs/2608.14979)
[![Website](https://img.shields.io/badge/Platform-pointreyessound.com-0284c7.svg?style=flat-square)](https://pointreyessound.com)
[![Interactive](https://img.shields.io/badge/Interactive-3D_Phase--Space-0d9488.svg?style=flat-square)](https://pointreyessound.com/interactive)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg?style=flat-square)](https://creativecommons.org/licenses/by/4.0/)

---

### [📄 Read Preprint](https://arxiv.org/abs/2608.14979) • [🔬 Interactive 3D Simulation](https://pointreyessound.com/interactive) • [📊 Open Benchmarks & Data](https://github.com/point-reyes-sound/p1_qbescf) • [🌐 Website](https://pointreyessound.com)

---

</div>

## Discovery Without Deference

**Point Reyes Sound** is a theoretical and computational research pod advancing non-equilibrium kinetic transport methods for quantum chemistry and electronic structure.

Where traditional mean-field electronic structure encounters factorial active-space bottlenecks in multireference systems, we propagate the one-electron reduced density matrix ($\gamma$) through the **Quantum Boltzmann Equation** with a Bhatnagar-Gross-Krook (BGK) collision operator:

$$\frac{\partial \gamma}{\partial t} + \frac{i}{\hbar}[F(\gamma), \gamma] = -\frac{1}{\tau}\left(\gamma - \gamma^{(0)}[S_{\text{vN}}]\right)$$

By introducing finite-time kinetic relaxation and entropic regularization, the solver circumvents unphysical symmetry breaking, resolves topological singularities (conical intersections and Coulson-Fischer points), and accurately simulates **"long electrons"**—delocalized, entangled charge carriers that govern catalysis, transition states, wide-bandgap semiconductors, and battery interfaces.

---

## Core Research Pillars

| Pillar | Theory & Methodology | Key Breakthrough |
| :--- | :--- | :--- |
| **01 · Kinetic Transport & QBE-SCF** | Continuous $O(N^3)$ phase-space relaxation replacing static iterative diagonalization. | Eliminates variational collapse and symmetry-breaking dilemmas without factorial multireference active spaces. |
| **02 · Topological Regularization** | Von Neumann configuration entropy maximization during bond elongation. | Smoothly regularizes mean-field singularities at diradical dissociation limits and conical intersections. |
| **03 · Phase-Space Wigner Tomography** | Continuous joint position-momentum representations $W(z, p_z; R)$. | Directly visualizes non-equilibrium quantum transport and coherent electron delocalization during dissociation. |

---

## Public Repositories & Data Suites

* **[`p1_qbescf`](https://github.com/point-reyes-sound/p1_qbescf)** — *Open Numerical Datasets & Benchmark Suites*  
  Full reproduction datasets and staging scripts for arXiv:2608.14979:
  - $\text{H}_2$ Coulson-Fischer potential energy dissociation curves.
  - $\text{H}_3$ symmetric stretch along $D_{3h}$ geometry and natural orbital configuration entropy.
  - $\text{H}_4$ rectangular scan and non-adiabatic Berry phase loops.
  - $\text{BeH}_2$ conical intersection entropic regularization.
  - Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

* **[`point-reyes-sound`](https://github.com/point-reyes-sound/point-reyes-sound)** — *Web Application & 3D Interactive Engine*  
  Source code for the research pod portal and interactive WebGL / Three.js phase-space reaction engine deployed at [pointreyessound.com](https://pointreyessound.com).

---

## Citation & Preprints

If you utilize Point Reyes Sound datasets, kinetic solvers, or benchmark curves in your academic or industrial research, please cite:

```bibtex
@article{chakraborty2026qbescf,
  title={Quantum Boltzmann Equation Self-Consistent-Field for the Entropic Regularization of Mean-Field Singularities},
  author={Chakraborty, Romit},
  journal={arXiv preprint arXiv:2608.14979},
  year={2026},
  eprint={2608.14979},
  archivePrefix={arXiv},
  primaryClass={physics.chem-ph},
  doi={10.48550/arXiv.2608.14979},
  url={https://arxiv.org/abs/2608.14979}
}
```

---

<div align="center">

**Point Reyes Sound, Inc.** • Point Reyes Station, CA & Berkeley, CA  
Inquiries & Research Collaboration: [contact@pointreyessound.com](mailto:contact@pointreyessound.com)

</div>
