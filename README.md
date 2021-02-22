# QMTOV

QMTOV - Quantised Molecular Trajectory Over View

The manual and core concept of QMTOV


QMTOV is a script library for describing and quantising molecular structure
properties and interactions.

For any input molecular trajectory, eg. from GMX, NAMD, or PDB.
It separates the file into its core components of molecules:
amino-acids, nucleic acids, lipids, ions and solvents.

Predefined scripts allows one to calculate certain properties and plot it via
a GUI.

Tcl VMD are used for doing the calculational analysis.
Matplotlib is the graphing software used to graph the data.
PyQt5 is the GUI.
