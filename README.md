# Transient flow-induced deformation of cancer cells in microchannels: a general computational model and experiments

[![Paper](https://img.shields.io/badge/Paper-10.1007%2Fs10237--024--01920--9-blue?logoColor=ecf0f1&labelColor=34495e)](https://link.springer.com/article/10.1007/s10237-024-01920-9)


Lu, R., Li, J., Guo, Z. et al. Transient flow-induced deformation of cancer cells in microchannels: a general computational model and experiments. Biomech Model Mechanobiol (2025) [[DOI link](https://doi.org/10.1007/s10237-024-01920-9)] 

## Overview
This repository contains the experiment and simulation data in the paper above. The data could be used to analyze cell deformation, or benchmark future cell mechanical model.

## Data Description
Folders are named after the figure labels in the paper. Each folder includes
* ``Data_cell.xlsx``: All experimental and simulation parameters have been provided here, which can be used to infer the cell mechanical properties.

* ``cell_fig*.png``: In the flow experiments, the transient cell deformation have been recorded using a high-speed camera. The figures provided here are the instantaneous profiles of cells flowing through constricted and cross-slot channels. 

* ``ProfileData_*.dat``: The cell deformation are obtained from computational simulations, which are used for comparison with experiments. The simulation data have been stored in a format that are readable to Tecplot.

## Data Usage

To achieve the match between experimental and simulation results and reproduce the figures in the paper
1. Load image files and cell deformation profile files.
2. Select the appropriate coordinate axes type (xy line).
3. Scale the image and cell profiles, and carefully move them until the coordinate axes coincide, as shown in the below figure.

![instruction](/usage/instruction.png "instruction")
