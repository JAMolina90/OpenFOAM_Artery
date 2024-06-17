# OpenFOAM_Artery

## Overview

This repository contains the source code of the numerical model presented in the paper: **"A new open-source solver for early detection of atherosclerosis based on hemodynamics and LDL transport simulation"**.

The model is implemented using OpenFOAM and includes ad-hoc boundary and initial conditions for simulating hemodynamics and LDL transport in Arteries.

## Repository Contents

- `passiveScalarpisoFoam`: Source code of the numerical solver.
- `Example1`: Example with an inlet velocity that can take negative values; this example includes boundary conditions that adapt according to the sign of the inlet velocity.
- `Example2`: Example with a positive inlet velocity profile.

The mesh employed in both examples was obtained from https://github.com/Chr1sC0de/ArteryScalingLawsBC

## Installation

To use the solver, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/JAMolina90/OpenFOAM_Artery.git
   cd OpenFOAM_Artery