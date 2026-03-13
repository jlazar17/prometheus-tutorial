# Prometheus Tutorial

Interactive tutorial notebook for [Prometheus](https://github.com/Harvard-Neutrino/prometheus), an end-to-end Monte Carlo simulation framework for neutrino telescopes.

## Running on Google Colab

Click the badge to open the notebook directly in Colab — no local installation required:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jlazar17/prometheus-tutorial/blob/main/tutorial.ipynb)

The first cell of the notebook handles all installation and downloads pre-computed simulation output automatically.

## Running locally

Requires a working Prometheus environment. See the [Prometheus installation guide](https://github.com/Harvard-Neutrino/prometheus) for setup instructions.

```bash
git clone https://github.com/jlazar17/prometheus-tutorial.git
cd prometheus-tutorial
jupyter notebook tutorial.ipynb
```

Pre-computed output files (optional — the notebook will run the simulations if they are absent) can be downloaded from the [Releases page](https://github.com/Harvard-Neutrino/prometheus/releases/tag/tutorial-v1).

## What the tutorial covers

1. Running a simulation (nu_mu CC, ranged injection)
2. Inspecting the Parquet output format
3. Visualizing events in the detector
4. MC truth distributions
5. Effective area and oneweighting
6. Flux reweighting
7. Comparing topologies: nu_mu track vs nu_e cascade (volume injection)
8. Building custom PPC optical property tables for a water detector
