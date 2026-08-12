# In Silico Validation

This stage evaluates whether selected probe candidates are conformationally robust and dynamically stable.

Two complementary approaches are used:

## pNear Analysis

pNear evaluates the conformational energy landscape of a cyclic peptide by combining structural similarity to the designed state with Boltzmann-like energy weighting.

A high pNear value indicates that low-energy conformations are concentrated near the designed structure, consistent with a well-defined energy funnel.

## Molecular Dynamics

Molecular dynamics simulations evaluate how the probe and the protein–probe interface behave over time in an explicit molecular environment.

Representative analyses can include:

* Backbone RMSD
* Probe RMSD
* Radius of gyration
* Persistence of protein–probe contacts
* Hydrogen-bond occupancy
* Interface stability

## Representative Files

This directory contains example inputs, scripts, and representative outputs for pNear analysis and molecular dynamics validation.
