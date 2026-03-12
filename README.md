# Deck_FPGA

This repository documents the design of an FPGA-based expansion board for the Crazyflie drone platform, featuring an AMD Xilinx Artix-7 100T FPGA and developed in KiCad.

The board was developed to support the acceleration of linear Model Predictive Control (MPC) execution onboard the Crazyflie quadrotor platform.

## Project Information
The board was designed and used within the master's thesis:

*Hardware-Algorithm Co-Design for Real-Time Linear Model Predictive Control. FPGA Implementation and Deployment on a Resource-Constrained Quadrotor*

Author: Andrea Grillo  
Period: 2025-2026

## Repository Contents

- `Deck_FPGA.kicad_sch`: KiCad schematic
- `Deck_FPGA.kicad_pcb`: KiCad PCB layout
- `Deck_FPGA.kicad_pro`: KiCad project file
- `Deck_FPGA.pdf`: exported board documentation
- `plot/`: fabrication outputs / Gerbers

## Inspiration

This project was inspired by the board presented in *FPGA-Based Neural Thrust Controller for UAVs* by Sharif Azem, David Scheunert, Mengguang Li, Jonas Gehrunger, Kai Cui, Christian Hochberger, and Heinz Koeppl (2024).
