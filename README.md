# VirtualSandPacking
This repository contains sand packing generated using the Discrete Element Method (DEM). The data is structured based on different particle size distributions (PSD) and porosity levels. 

Please contact Dr. Si Suo email: s.suo@imerial.ac.uk and Mr. Yongxin Wang email: yongxin.wang22@imperial.ac.uk

## How to Use
The `bin/` folder contains executable files file used to generate the sand packings. You can modify the PSD curve, the porosity and the particle number in the .json file to generate new packing.

## Data
The `data/` folder contains generated packings according to the PSDs recorded in references. Each subfolder contains the reference, input files, and generated packings (50k particles), which are written in Lammps input format (.lg) and xyzr format (.dat).

