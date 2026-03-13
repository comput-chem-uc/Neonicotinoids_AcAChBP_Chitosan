# "In Silico Design of Amino Acid-Functionalized Materials for the Capture of Neonicotinoids"

J. R. C. Santos, P. E. Abreu, and J. M. C. Marques



## DESCRIPTION OF FILES:


### GROMACS INPUT FILES:

In the directory "GROMACS_input-files" we include the topology, the molecular dynamics parameters and the coordinates files to run MD Simulations for each system.
The directory is divided in subdirectories named "Protein+Neonicotinoids" and "Chitosan+Neonicotinoids" where you can find the corresponding inputs files for the Ac-AChBP_Neonicotinoids MD simulations and the Chitosan_Neonicotinoids simulations.


Files in the "Protein+Neonicotinoids" directory for each system:

"minim.mdp"     - input parameter file to run the energy minimization

"nvt.mdp"       - input parameter file to run the temperature equilibration (NVT)

"npt.mdp"       - input parameter file to run the pressure equilibration (NPT)

"md.mdp"        - input parameter file to run the main MD trajectory

"ions.mdp"      - input parameter file of the ions

"NEONICOTINOID_GMX.itp"   - topology file for each neonicotinoid molecule including the forcefield parameters

"neonicotinoid_atoms.itp" - atomtypes file of each neonicotinoid used in the simulation

"topol.top"     - topology file of the system

"topol_Protein_chain_A.itp" - topology file for the chain A of the protein including the forcefield parameters

"topol_Protein_chain_B.itp" - topology file for the chain A of the protein including the forcefield parameters

"complex_solv_ions.gro"       - system coordinates (complex + solvent + ions) file

<br>


Files in the "Chitosan+Neonicotinoids" directory for each system:

"minim.mdp"     - input parameter file to run the energy minimization

"nvt.mdp"       - input parameter file to run the temperature equilibration (NVT)

"npt.mdp"       - input parameter file to run the pressure equilibration (NPT)

"md.mdp"        - input parameter file to run the main MD trajectory

"NEONICOTINOID_GMX.itp"   - topology file for each neonicotinoid molecule including the forcefield parameters

"neonicotinoid_atoms.itp" - atomtypes file of each neonicotinoid used in the simulation

"CTS*.itp"      - topology file for the chitosan models including the forcefield parameters

"cts*_atoms.itp"- atomtypes file used in the simulation for the chitosan models

"topol.top"     - topology file of the system

"solv.gro"       - system coordinates (chitosan model + neonicotinoid + solvent) file



<br>


### ORCA Optimized Geometries:

In the directory "ORCA_optimized-geometries" we include the xyz files of the optimized geometries obtained with ORCA for each complex of amino acids and neonicotinoids



<br>



For help and support please contact: qtmarque@ci.uc.pt

GROMACS is freeware downloadable from https://www.gromacs.org/

(see GROMACS users manual for more info https://manual.gromacs.org/documentation/2019/index.html)
