---
layout: page
permalink: /cavmd/
title: CavMD
description: Towards realistic simulation of polaritons in the collective regime
nav: true
---

[CavMD, the cavity molecular dynamics simulation toolkit](https://github.com/TaoELi/cavity-md-ipi), is an open-source project towards efficiently simulating vibrational strong coupling (VSC) in the field of polariton chemistry.

VSC is an emerging research topic at the intersection between quantum electrodynamics (QED) and chemistry. When a large ensemble of molecules is confined in optical or plasmonic cavities at the infrared (IR) regime,  a bright collective mode of molecular vibrations can form the Rabi splitting with a cavity mode. Under this VSC regime, it has been shown that many intriguing molecular properties can be modified inside the cavity, and there are many unsolved puzzles in this area.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/cavmd_nonlinear.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to better simulate VSC, I started the CavMD project at Jan 2020. The basic idea of this project is straightforward: because classical molecular dynamics (MD) can simulate the dynamics of molecular vibrations in free space quite well, if we also treat the cavity modes classically and propagate the coupled equations between molecules and cavity modes self-consistently, can we efficiently describe VSC?

During the past few years, I have carefully examined this idea and find that this routine is fruitful. With this CavMD toolkit, I have studied many fundamental processes of VSC, including thermal equilibrium, nonequilibrium dynamics of polaritons and vibrational dark modes, etc. The CavMD description of these **nonreactive VSC dynamics** has shown agreement with conventional theories and recent ultrafast spectroscopy experiments. Moreover, CavMD also provides a simple means to [design new mechanisms](https://doi.org/10.1038/s41467-022-31703-8) which are impossible outside the cavity. Within the framework of CavMD, quantum effects can further be included by path-integral treatments; moreover, chemical reactions can also be efficiently described with QM/MM.

Since March 2023, some fundamental features of CavMD have been available on [the main version of i-pi](https://ipi-code.org/about/features/). 




