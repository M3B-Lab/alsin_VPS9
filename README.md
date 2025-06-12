[![Crystal][Crystal-image]][Crystal-link]

[Crystal-image]: https://crystal.m3b.it/wp-content/uploads/2021/10/logo-1.svg
[Crystal-link]: https://crystal.m3b.it/

# alsin_VPS9
This repository contains all the necessary data to replicate the simulations of the paper "Molecular insights into IAHSP: influence of the R1611W mutation on the VPS9 domain of alsin", which has been submitted but not published.

The input data to replicate the simulations are organized as follows:
- `md.mdp`: The mdp file used to run the simulations in GROMACS.

- `VPS9_WT/`: Folder regarding the molecular dynamics simulation of VPS9 WT system.

  - `tpr/`: Folder containing the tpr files for each replica.

  - `Topologies/`: Folder containing the topology defining the system.

- `VPS9_R1611W/`: Folder regarding the molecular dynamics of VPS9 R1611W system.

  - `tpr/`: Folder containing the pdb and tpr files.

  - `Topologies/`: Folder containing the topology defining the system.
# Acknowledgement
This work was supported by Fondazione Telethon (Grant #GSP 20005_PAsIAHSP007) and Associazione Help Olly Onlus (https://helpolly.it/) – Italy, within the framework of CRYSTAL (www.crystal.m3b.it). 
