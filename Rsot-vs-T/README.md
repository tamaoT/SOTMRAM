# Rsot vs Temperature Analysis for SOT-MRAM Devices

This repository provides tools for analyzing the temperature-dependent behavior of Rsot and Rsot_bias in Spin-Orbit Torque Magnetic RAM (SOT-MRAM) devices. By fitting experimental data to a non-linear resistance model, this project aims to estimate the temperature increase (ΔT) inside the device during electrical operation.


##  Motivation

SOT-MRAM devices can heat up during operation due to Joule heating or spin current injection. This internal heating affects the Rsot and Rsot_bias values measured during experiments. By analyzing these changes, we can infer how much the device heats up under specific biasing conditions.

The ultimate goal is to **visualize internal temperature rise (ΔT)** and build a robust method to **estimate ΔT from electrical measurements only**.



## Folder Structure
├── analysis/ # Main analysis code (Rsot fitting, plotting, etc.)  
├── results/ # Output plots and fit parameters  
└── README.md  

##  Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- scipy

##  Future Work
Compute temperature rise ΔT between Rsot_bias and Rsot_pulse
Add support for automatic anomaly detection
Improve fit accuracy with robust error estimation
