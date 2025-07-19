# MTJ Switching Analysis under SOT Current
This repository contains Python code for analyzing the switching behavior of Magnetic Tunnel Junctions (MTJs) under Spin-Orbit Torque (SOT) current injection. The MTJ layer is where actual switching occurs, and this tool allows users to visualize and quantify switching events by observing changes in resistance(Rmtj)


# What It Does

data containing Rmtj vs Isot at different temp and magnetic fields

Automatically classifies the two magnetization states (P and AP) using K-means clustering.

Splits measurement data into loops and detects switching events (P→AP, AP→P) from resistance jumps.

Extracts and plots switching currents (Critical surrent Ic) as a function of temperature and magnetic field.

Provides error bars from loop statistics for more robust analysis.


# Input Format
Each .dat file should be named like:

SOT current (μA) MTJ resistance (Ω)

# Requirements
Python 3.8+

numpy

pandas

matplotlib

scikit-learn

scipy

# Output
Per-loop switching currents extracted from resistance jumps.

Visual plots showing resistance switching with temperature dependence.

Error bar plots summarizing switching trends for both positive and negative magnetic field conditions.

# Notes
Bx>0: Switching AP → P and P → AP labeled separately.
Bs<0: Switched currents are plotted in reverse to maintain sign consistency.

