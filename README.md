# bachelor-thesis

This documentation is prepared to help understanding my bachelor thesis, titled The Effect of Fluorination on the Structure and Dynamics of the Hexapeptide VG(Abu)APG, carried in the Molecular Dynamics Simulation group of Prof. Bettina Keller (https://www.bcp.fu-berlin.de/en/chemie/chemie/forschung/PhysTheoChem/agkeller/index.html), under the supervision of Leon Wehrhan, M.Sc.

In this project, I tried to isolate the effect of fluorinated Abu (mono-, di- and trifluorination) by studying it on a small hexapeptide, which is derived from VGLAPG to study the structure and its kinetics.

The simulation itself was carried on GROMACS 2019.1 using the topology created in PyMol. Here we only analyze their structure by analyzing their Ramachandran plot, side chain torsion angle profiles ($\Chi_1$), end-to-end distance and the formed intramolecular hydrogen bonds.

In this published project, I only use a shorter trajectory length (100 ns instead of 500 ns) due to the size of the file. In the production run in GROMACS, each hexapeptides were simulated for a total time of 100 ns with 2 fs timestep and the trajectories were saved every picosecond, so in the end we have 100.000 data points.

All of the needed topologies and trajectories are provided.

---

# Installation

To run the Jupyter Notebook, please install the following:
1. Anaconda (https://www.anaconda.com/products/distribution), which already consists of NumPy, Seaborn, Matplotlib and Pandas.
2. Jupyter Notebook (https://jupyter.org/install)

To run the notebook, please install the following libraries:
1. NumPy (https://numpy.org/install/)
2. Seaborn (https://seaborn.pydata.org/installing.html)
3. Matplotlib (https://matplotlib.org/stable/users/installing/index.html)
4. Pandas (https://pandas.pydata.org/docs/getting_started/install.html)
5. MDTraj(https://mdtraj.org/1.9.4/installation.html)
6. PyEMMA (http://emma-project.org/latest/INSTALL.html)
