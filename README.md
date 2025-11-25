# VIC-MixedTraffic-Modeling

This repository contains Python code for simulating, calibrating, and analyzing the car-following behaviors of electric vehicles (EVs) and internal combustion engine (ICE) vehicles under adaptive cruise control (ACC). It supports a study submitted to *Transportation Research Part C: Emerging Technologies* for the Special Issue on "Vehicle-Infrastructure Cooperation for Next-Generation Transportation System." The code leverages high-fidelity trajectory datasets to model mixed traffic dynamics within a vehicle-infrastructure cooperation (VIC) framework, optimizing traffic flow stability and efficiency.

## Project Overview

The code includes:
- **Calibration**: Calibrates Optimal Velocity Relative Velocity (OVRV) and Intelligent Driver Model (IDM) using spacing RMSE (Section~\ref{sec:modeling}).
- **Simulation**: Runs ring road traffic simulations to assess EV market penetration rates (MPR) on flow stability (Section~\ref{sec:mixed_traffic_simulation}).
- **Analysis**: Performs statistical analysis and visualizations (e.g., heatmaps) to compare EV and ICE behaviors (Section~\ref{sec:data_analysis}).

These tools support VIC by integrating V2I communication to enhance traffic optimization.

## Datasets

- **ICE ACC Dataset**: Longitudinal dynamics of seven 2018 model-year ICE vehicles under ACC, recorded at 10 Hz [](https://doi.org/10.1016/j.trc.2020.102626).
- **EV ACC Dataset**: Longitudinal dynamics of a 2022 Hyundai IONIQ 5 under ACC, recorded at 50 Hz [](https://doi.org/10.1016/j.trc.2022.103912).
- **Note**: Datasets are not included due to proprietary restrictions. Contact the authors or refer to the cited papers for access.

## Dependencies

- **Python**: 3.8 or higher
- **Libraries**:
  - NumPy
  - SciPy
  - Pandas
  - Matplotlib
  - Seaborn (for visualizations)

