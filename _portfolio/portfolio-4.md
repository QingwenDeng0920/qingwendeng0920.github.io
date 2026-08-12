---
title: "Agrobiodiversity Timing Model: A Dynamical-Systems Account of Crop Genetic Erosion"
excerpt: "A dynamical-systems model demo showing that agricultural genetic-diversity collapse is governed by the relative timing of promotion and institutional capacity-building, not their eventual levels — a companion piece to my working paper on agricultural modernization and genetic erosion.<br/>"
collection: portfolio
---

This project builds a 3-state ordinary differential equation model (Python) that formalizes when rapid agricultural modernization — the fast promotion of a narrow set of high-yield varieties — causes a permanent loss of crop genetic diversity, and when it doesn't. It serves as a companion demo to my working paper "Capacity Before Promotion: A Dynamic Ecological-Economic Model of Agricultural Modernization and Crop Genetic Erosion", distilling the paper's core dynamical-systems result — a closed-form bistability condition and a diagnostic explaining why the collapse/coexistence threshold is sharp rather than gradual — into a self-contained, numerically validated demo.


**Repository:** [github.com/QingwenDeng0920/agrobiodiversity-timing-model](https://github.com/QingwenDeng0920/agrobiodiversity-timing-model)


**Key features:**
* 3-state ODE model (Python) coupling cultivation extent, genetic diversity, and institutional conservation capacity
* Closed-form bistability condition validated against exact coupled-system numerics across 330 parameter combinations
* A depth- and time-weighted diagnostic (`exposure`) explaining why the collapse threshold is sharp, validated across 13 independent parameter settings
* Written in Python (NumPy, SciPy, Matplotlib)
