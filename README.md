# Photoswitchable Cyclic Peptide Probes for F-actin

This repository contains the computational workflow for the design of photoswitchable cyclic peptide probes targeting F-actin. The probe combines an azobenzene photoswitch, a cyclic peptide scaffold, and non-canonical amino acids, using Rosetta/MASALA for molecular design and structural optimization.

## Poster

[Download Poster PDF](./Summer%20Internship%20Poster%20PSR.pptx.pdf)
## Computational Workflow

1. **Site Selection**  
   Identify an accessible F-actin surface region while avoiding known interaction sites.

2. **Azobenzene Docking**  
   Dock the photoswitchable ABT residue into the selected actin pocket.

3. **Probe Extension**  
   Extend the docked photoswitch with a peptide scaffold.

4. **Cyclization**  
   Close the peptide scaffold into a cyclic structure using Rosetta conformational sampling.

5. **Candidate Optimization and Selection**  
   Optimize sequence and rank designs using multi-objective metrics such as shape complementarity, binding energy, interface quality, and cavity formation.

6. **In Silico Validation**  
   Evaluate lead candidates using pNear, molecular dynamics simulations, and trans–cis photoisomerization compatibility.
