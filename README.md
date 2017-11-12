# mcxyz add Ryx, use ../sims/ folder for storing input/output files.
All input files (*_H.mci, *_T.bin) and output files (*_F.bin, *_Ryx.bin, *_Rd.dat)
are stored in folder ../sims/*, where * denotes the name of the run, eg., skinvessel.

mcxyz is a 3D multi-voxel Monte Carlo simulation of light transport.
The program is written in ANSI standard C. 
It reads an input text file called yourname.mci, which controls the Monte Carlo simulation.
It reads an input binary file called yourname_T.bin, which assigns tissue types to the voxels.
It outputs a binary file called yourname_F.bin, which is the output of fluence [J/cm^2/J.delivered].
While any program can create the yourname.mci and yourname_T.bin files, this .git uses MATLAB 
to accomplish these tasks. The program is described at http://omlc.org/software/mc/mcxyz/index.html .
