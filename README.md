"Application of Funnel Metadynamics to the Platelet Integrin αIIbβ3 in Complex with an RGD Peptide" https://doi.org/10.3390/ijms25126580

These are the necessary files to reproduce the simulations used in our paper. GROMACS 2022.5 patched with PLUMED 2.8.2 was used to produce the simulations.

The funnel metadynamics files were too large to place in one folder on github. walker0.tar.gz through walker9.tar.gz and StartFM.tar.gz are all the files that can be used to reproduce the funnel metadynamics simulations. The other equilibrium simulations are each in one tar file and have appropriate names. The Scripts.tar.gz file contains the custom analysis scripts referenced in the paper. The HILLS files can be used with sum_hills in PLUMED 2.8.2 to recreate the free energy surface of CV1 and CV2 used in the paper. funnel.dat is the data used to plot the free energy surface of the funnel space.
