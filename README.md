# Sensory Adaptation in Changing Environments

A computational study of how a single neuron should adapt its encoding
when the statistics of its environment change over time. Using a one-neuron
model with online Bayesian context inference, this project asks how the
*timing* of adaptation, not just the encoding itself, shapes performance. I
compare instant, hysteresis, and refractory-lockout switching rules against
oracle and static baselines.

## Contents
- `analysis.ipynb` — full simulation and analysis (reproduces all figures)
- `manuscript.pdf` — write-up of the methods, results, and discussion
- `supporting_information.pdf` — supplementary derivations and figures
- `presentation.pptx` — slides summarizing the project

## Running
The notebook requires `numpy`, `scipy`, `pandas`, and `matplotlib`.
Run all cells top to bottom to reproduce the figures.