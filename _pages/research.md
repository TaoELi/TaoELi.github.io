---
layout: page
permalink: /projects/
title: Research
description: I am interested in developing novel methods and applying these methods to some exciting problems.
nav: true
---

### I. Vibrational strong coupling


Vibrational strong coupling (VSC), strong light-matter interactions between molecular vibrations and optical cavity modes, has the potential of significantly modifying molecular properties. VSC involves a collective motion of all molecules in the condensed phase, and some most outstanding VSC effects resonantly depend on the cavity mode frequency. These global and resonant behaviors are in sharp contrast to our usual understanding of molecular processes, which are mostly local and static.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cavmd_nonlinear.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to better model VSC, I have developed a numerical scheme called [cavity molecular dynamics (CavMD)](https://github.com/TaoELi/cavity-md-ipi), in which the coupled classical dynamics between cavity modes and realistic molecules are propagated on an electronic ground state.

* **Li, T. E.**, Subotnik, J. E., Nitzan, A. Cavity molecular dynamics simulations of liquid water under vibrational ultrastrong coupling. [Proc. Natl. Acad. Sci., 2020, 117 (31), 18324–18331](https://doi.org/10.1073/pnas.2009272117).

Equipped with this numerical tool, I have been exploring how to control molecular properties with VSC. Two major questions are currently under consideration:

* Can we understand the Ebbesen experiments on resonant VSC catalysis from a theoretical perspective?

  * **Li, T. E.**; Nitzan, A.; Subotnik, J. E. Collective vibrational strong coupling effects on molecular vibrational relaxation and energy transfer: Numerical insights via cavity molecular dynamics simulations. [Angew. Chem. Int. Ed. 2021, 60 (28), 15533-15540]( https://doi.org/10.1002/anie.202103920).

  * **Li, T. E.**; Nitzan, A.; Hammes-Schiffer, S.; Subotnik, J. E. Quantum Simulations of Vibrational Strong Coupling via Path Integrals. [J. Phys. Chem. Lett. 2022, 13 (17), 3890-3895](https://doi.org/10.1021/acs.jpclett.2c00613).

* How to understand IR photo-induced polariton dynamics and what novel physical and chemical processes can we find?
  * **Li, T. E.**; Nitzan, A.; Subotnik, J. E. Cavity molecular dynamics simulations of vibrational polariton-enhanced molecular nonlinear absorption. [J. Chem. Phys. 2021, 154 (9), 094124](https://doi.org/10.1063/5.0037623).

  * **Li, T. E.**; Nitzan, A.; Subotnik, J. E. Energy-efficient pathway for selectively exciting solute molecules to high vibrational states via solvent vibration-polariton pumping. [arXiv. 2021](https://arxiv.org/abs/2104.15121).


<br>
<hr>
<br>

### II. Nuclear quantum effects

Nuclei, especially protons, are intrinsically quantum-mechanical. How to properly model the quantum nature of protons is a long-standing question in physical and theoretical chemistry. To date, one of the most successful approaches towards modeling protonic quantum effects for realistic molecules is path-integral based methods such as **ring-polymer molecular dynamics (RPMD)**. However, RPMD does not offer a perfect answer on  describing nonequilibrium real-time proton dynamics  or nonadiabatic coupled electron-proton dynamics. From the other perspective, protonic quantum effects can also be captured by solving the Schrodinger equation directly. This **nuclear-electronic orbital (NEO)** approach is formally exact, but finding a computationally efficient way for solving  the Schrodinger equation is nontrivial.

I am interested in method development on efficiently simulating nuclear quantum effects for real-time, nonadiabatic proton dynamics both in free space and under strong light-matter interactions.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/semiclassical_rt_neo.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

As a first project along this direction, one illustrative example is that, by combining the real-time dynamics of classical cavity photons and quantum electrons and protons, the strong coupling effect on nonadiabatic dynamics of proton transfer can be efficiently captured.

* **Li, T. E.**; Tao, Z.; Hammes-Schiffer, S. Semiclassical Real-Time Nuclear-Electronic Orbital Dynamics for Molecular Polaritons: Unified Theory of Electronic and Vibrational Strong Couplings. [J. Chem. Theory Comput. 2022, 18 (5), 2774-2784](https://doi.org/10.1021/acs.jctc.2c00096).

<br>
<hr>
<br>

### III. Fundamental light-involved processes

While strong light-matter interactions is a hot topic of research, I am also interested in understanding and modeling most fundamental light-involved processes, including **spontaneous emission**, **energy transfer**, and **superradiance**. While these processes have been extensively studied and can be well modeled by quantum mechanics such as Lindbladian equations, the computational cost can become too high to afford when the number of photon modes or two-level systems becomes large. Of course, there are also cheap methods for modeling these processes such as mean-field dynamics, in which a many-body problem is reduced to an effective one-body problem. However, mean-field dynamics can sometimes be very problematic as this approach neglects quantum fluctations between many-body interactions. I am in particular interest in modeling fundamental light-involved processes with **methods between mean-field dynamics and Lindbladian equations**, i.e., those methods which are computationally affordable when the number of particles becomes large but can still recover some important quantum effects.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/delay_time_statistics.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Of course, it is nontrivial to find such a good balance, and the journey towards searching an optimal algorithm will also help better understand the meaning of "quantum" and "classical".

* **Li, T. E.**; Chen, H.-T.; Nitzan, A.; Subotnik, J. E. Quasiclassical modeling of cavity quantum electrodynamics. [Phys. Rev. A. 2020, 101 (3), 033831](https://doi.org/10.1103/PhysRevA.101.033831).
