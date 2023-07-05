# VASP output file parse

Some of these scripts are written for a particular project, and are thus not general. In particular,
many of them are written for specific atoms. However, if one wishes to write a similar script for a 
different system of atoms, or even a general system, one should keep this in mind. 
## List of individual scripts

### DOS_from_DOSCAR

Description: A script that can parse total density of states (DOS) and orbital-projected DOS
from the DOSCAR output file. An example is provided which parses a data file and plots the DOS.

Example files: 'DOSCAR_CO2_10242022' and 'POSCAR_CO2_10242022'

### MSD_from_XDATCAR

Descriptions: Parses XDATCAR file, which contains the atomic positions at each step in a DFT-MD
simulation. Calculates the mean-squared displacement of atoms given these atomic positions.
