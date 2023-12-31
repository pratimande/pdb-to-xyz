Software like VMD or OVITO don't allow visualization of the whole simulation of a .xyz file if the numbers of particles increase or decreases during the simulation.
Using this code, you can load the .pdb file for each frame to VMD and export it as a .xyz file, which can be used for visualization in VMD or OVITO.

1. Change the path info and other details in the code and save it.
2. In the VMD terminal run
    >> source pdb.tcl
