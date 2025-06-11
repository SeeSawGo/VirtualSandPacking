# VirtualSandPacking
This repository contains sand packing generated using the Discrete Element Method (DEM). The data is structured based on different particle size distributions (PSD) and porosity levels, such as, /pics/cylinder.png

Please contact Dr. Si Suo email: s.suo@imperial.ac.uk and Mr. Yongxin Wang email: yongxin.wang22@imperial.ac.uk

## How to Use
The `bin/` folder contains an executable file for generating the sand packings. You can modify the PSD curve, the porosity and the particle number in the .json file to create new packings.

## Data
The `data/` folder contains generated packings according to the PSDs recorded in references. Each subfolder contains the reference, input files, and generated packings (50k particles), which are written in Lammps input format (.lj), xyzr format (.dat), paraview readable format (.vtk) and its corresponding domain size (Boxsize_0.dat) and PSD curve (.csv).

## Update
2025/06/11 update: by setting a cylinder radius ("Rcylinder" in json file), it can generate a packing within a cylinder domain with the top and bottom periodic boundaries;   


