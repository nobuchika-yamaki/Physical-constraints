# Physical-constraints
Physical Constraints Shape Neural Connectomes

This repository contains the analysis code used in the study
“Physical constraints shape neural connectomes”.

The code reproduces all quantitative analyses reported in the manuscript, including preprocessing, computation of the non-reciprocity index χ, null-model validation, topological analysis, and effective Hamiltonian optimization.
Figure generation and visualization are intentionally excluded.

Scope

This codebase implements the full analysis pipeline underlying the following results:

Log-scaled and flux-normalized connectome preprocessing

Computation of the non-reciprocity index χ

Statistical characterization of χ distributions

Distance-preserving null-model rewiring

Kurtosis-based rejection of random wiring hypotheses

Directed cycle density and topological compression analysis

Effective Hamiltonian formulation and equilibrium χ* estimation

Scaling analysis via geometric cost bias (α sweep)

All numerical values reported in the manuscript are derived from this pipeline.

Data Sources

The analysis relies on publicly available connectome datasets:

C. elegans
WormWiring / WormBase connectome
Release: 2020
https://wormwiring.org

Drosophila melanogaster
Hemibrain connectome
Version: v1.2
https://neuprint.janelia.org

Raw data files are not redistributed here. Users are expected to obtain the datasets directly from the original sources and provide them as adjacency matrices and neuron coordinate arrays.
