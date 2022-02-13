---
layout: page
permalink: /projects/
title: Research
description: Brief outline of my current research interests.
nav: true
---

### I. Vibrational strong coupling


Vibrational strong coupling (VSC), strong light-matter interactions between molecular vibrations and optical cavity modes, has the potential of significantly modifying molecular properties. VSC involves a collective motion of all molecules in the condensed phase, and some most outstanding VSC effects resonantly depend on the cavity mode frequency. These global and resonant behaviors are in sharp contrast to our usual understanding of molecular processes, which are mostly local and static.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cavmd_nonlinear.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to better model VSC, I have developed a numerical scheme called [cavity molecular dynamics (CavMD)](https://github.com/TaoELi/cavity-md-ipi), in which the coupled classical dynamics between cavity modes and realistic molecules are propagated on an electronic ground state. Equipped with this numerical tool, I have been exploring the possibilities of engineering molecular properties with VSC.

- [11] **Li, T. E.**, Subotnik, J. E., Nitzan, A. Cavity molecular dynamics simulations of liquid water under vibrational ultrastrong coupling. [Proc. Natl. Acad. Sci., 2020, 117(31), 18324–18331](https://doi.org/10.1073/pnas.2009272117).

- [12] **Li, T. E.**; Nitzan, A.; Subotnik, J. E. Cavity Molecular Dynamics Simulations of Vibrational Polariton-Enhanced Molecular Nonlinear Absorption. [J. Chem. Phys. 2021, 154 (9), 094124](https://doi.org/10.1063/5.0037623).

- [13] **Li, T. E.**; Nitzan, A.; Subotnik, J. E. Collective vibrational strong coupling effects on molecular vibrational relaxation and energy transfer: Numerical insights via cavity molecular dynamics simulations. [Angew. Chem. Int. Ed. 2021, 60(28), 15533-15540]( https://doi.org/10.1002/anie.202103920).



### II. Nuclear quantum effects

Nuclei, especially protons, are intrinsically quantum-mechanical. How to properly model the quantum nature of protons is a long-standing question in physical and theoretical chemistry. To date, one of the most successful approaches towards modeling protonic quantum effects for realistic molecules is path-integral based methods such as **ring-polymer molecular dynamics (RPMD)**. However, RPMD does not offer a perfect answer on  describing nonequilibrium real-time dynamics  of protons and nonadiabatic coupled electron-proton dynamics. From the other perspective, protonic quantum effects can also be captured by solving the Schrodinger equation directly. This **nuclear-electronic orbital (NEO)** approach is formally exact, but finding a computationally efficient way for solving  the Schrodinger equation is nontrivial.

I am interested in method development on efficiently simulating nuclear quantum effects for real-time, nonadiabatic proton dynamics both in free space and under strong light-matter interactions. Exciting results will be reported soon.
