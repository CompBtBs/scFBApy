# scFBApy: a Python framework for super-network Flux Balance Analysis

This repository was built to reproduce the results from the publication "scFBApy: a Python framework for
super-network Flux Balance Analysis" submitted to the WIVACE2023 conference.

Constraint-based modelling (CBM) is a computational method
used in systems biology to analyze metabolic fluxes. However, modelling
metabolic fluxes with CBM remains challenging due to the complexity of
metabolism and the integration of omics data. This study introduces scF-
BApy, a Python-based tool for simulating CBM and possible cooperation
between cells. It allows the simulation of a population of networks for a
target objective, such as biomass production, with or without cooperation. The tool integrates single-cell transcriptomics data using Reaction
Activity Scores and uses a denoising algorithm for pre-processing scRNA-
seq data. Five real-world scRNA-seq datasets were used to demonstrate
the applicability of the pipeline. Results showed that cooperation be-
tween cells increased biomass production compared to independent cell
simulations. The scFBApy package provides an open-source alternative
to MATLAB-based CBM tools.

To run the codes you need to install:
* Scanpy
* Cobrapy
* MAGIC denoiser

