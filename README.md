# CAHS-Protein-Simulations
This repository contains molecular dynamics (MD) simulation setups, scripts, and analyses to investigate the assembly behavior of the CAHS12 protein and its interactions with a POPC lipid membrane using the Martini 3 coarse-grained force field. The simulations were designed to elucidate the mechanisms by which the CAHS12 protein protects lipid vesicles under dessication conditions. <br />

The following packages were used for running simulations and analyzing trajectories.

`GROMACS 2022.4/2022.5

MDAnalysis 2.7.0

ChimeraX 1.9
`

## CAHS-dimer
This folder contains the .mdp, .gro and .itp files for the five independent simulations of two CAHS12 proteins. The ie.mdp was used to rerun the trajectoeis and extract the short-range interaction energy between the proteins. The notebook pca.ipynb contains the codes for generating the PCA plots.  <br />

## CAHS-lipid
This folder contains the .mdp, .gro and .itp files for setting up simulations of multiple CAHS12, CAHS12 ΔN, or CAHS12 ΔC proteins in the presence of a POPC membrane. Three independent simulations were carried out for each system. The notebooks, network.ipynb and quantification.ipynb, contain the codes for generating the network plots and statistics.   <br />

## water-deletion 
This folder contains the .mdp, .gro and .itp files for running simulations to mimic the dehydration process for the CAHS12,CAHS12 ΔN, or CAHS12 ΔC system in the presence of a POPC membrane. The notebook water_depletion.ipynb plots the results extracted from the simulations with the .csv files.  <br />

## Citation

If you use this work please cite: <br />

<pre> TBA


