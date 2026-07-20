# synrm-motor-control-simulink
Dynamic dq‑axis modelling and control of a 30 kW synchronous reluctance motor in MATLAB/Simulink, featuring Scalar V/f, Field‑Oriented Control, SPWM inverter modelling, PI current loops, and full performance analysis.

## Project Overview

This repository presents a first-principles dynamic model of a **30 kW Synchronous Reluctance Motor (SynRM)** developed in **MATLAB/Simulink** as part of my Master's thesis at LUT University.

The project implements and compares two widely used electric drive control strategies:

- Scalar V/f Control
- Field-Oriented Control (FOC)

The motor model is based on dq-axis mathematical equations rather than pre-built Simscape machine blocks, providing a transparent and educational implementation of SynRM dynamics and control.

The repository includes the Simulink model, MATLAB scripts, simulation results, documentation, and performance analysis under different operating conditions.

## Key Features

- First-principles SynRM mathematical model
- dq-axis dynamic modelling
- Scalar V/f control
- Field-Oriented Control (FOC)
- Sinusoidal PWM (SPWM)
- PI current and speed controllers
- Inverter modelling
- Rated-load and no-load simulations
- THD analysis
- Torque ripple analysis
- Sensitivity analysis
- MATLAB and Simulink implementation

  ## Repository Structure

├── docs/          Documentation and thesis
├── images/        Figures and diagrams
├── model/         Simulink models
├── scripts/       MATLAB scripts
├── results/       Simulation results
├── videos/        Demonstration videos
├── LICENSE
└── README.md
